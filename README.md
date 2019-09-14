# mu-epub-reader

Epub viewer using Electron.

This application is forked of [futurepress/epubjs-reader: Epub.js Reader](https://github.com/futurepress/epubjs-reader).

## Differences

- Integrate Google Translation
- Scroll Shortcuts: 
    - <kbd>j</kbd> or <kbd>Space</kbd>: Scroll down
    - <kbd>k</kbd> or <kbd>Shift+Space</kbd>: Scroll up
- One column mode: continuous scroll like PDF
- Open file with arguments

## Development

Build electron app

    npm install
    npm run dist
    # output .app to dist/

## Related

- [Epub.js](http://futurepress.github.com/epub.js/) library


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
