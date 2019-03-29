# [reveal-md][reveal-md] with multiple files support

Example to show simple preprocessor to use multiple files for your markdown presentation

## How it works

Preprocessor is used to parse markdown file and include content of other files.

Before reveal-md 3.0 there was an options value with slides directory.
Since 3.0 there isn't, so I have added my own into reveal-md.json `includeDir`.
It is used as a base path for includes.

## Run

```
yarn
yarn start
```


[reveal-md]: https://github.com/webpro/reveal-md
