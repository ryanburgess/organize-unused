# Organize Unused RAW files
A CLI tool to add on to [organize-raw](http://github.com/ryanburgess/organize-raw) package. This tool looks through created JPEGs and identified RAW photo files that were not edited.

The organize-used script searches through the current directory for all JPEG files and finds the RAW file counter part, and moves any of the RAW files that were not edited to an 'unused' directory.

This is script I use to help organize the photos I take and don't end up using.

## Install

```js
npm install organize-unused -g
```

## Use
Run the command `organize-unused` in the directory with the photos you'd like to find unused RAW files.

## Contributing
1. Fork it
2. Run `npm install`
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request

## License
MIT © [Ryan Burgess](http://github.com/ryanburgess)
