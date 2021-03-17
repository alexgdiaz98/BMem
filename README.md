# BMem (Bible Memorizer)

## Overview
BMem is a tool to memorize passages of scripture by typing them repeatedly. The download tool can cache passages of scripture, so you don't have to request a passage from the ESV API each time. BMem can run with passages from the ESV API or any text you properly format.

To run the download tool, run `./download` and enter the passage reference in a reasonable format (Gen 1:1-32, jn11.35, 1 Thessalonians 3, etc.). This will save the passage in the proper format in an aptly-named .txt file in the `src/` directory.

**Note: To use the download tool, you must first create an ESV API key (See API\_KEY section below).**

To run the main application, run `./bmem [filename]`, where `filename` is a path to a formatted .txt file. Follow the prompts to begin the memorization practice. 

## API_KEY
To access the ESV API, you need an API KEY available [here](https://api.esv.org/docs/). Once you have an API KEY, create a `config.json` file with contents like so:

```json
{
    "ESV": "YOUR_API_KEY"
}
```

## Copyright
Scripture quotations are from the ESV® Bible (The Holy Bible, English Standard Version®), copyright © 2001 by Crossway, a publishing ministry of Good News Publishers. Used by permission. All rights reserved. You may not copy or download more than 500 consecutive verses of the ESV Bible or more than one half of any book of the ESV Bible.
