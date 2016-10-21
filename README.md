# Landing page

## Development

```bash
gem install bundler ; bundle

```

### OSX Sierra problems

```
brew install libxml2 libxslt libiconv # OR
bundle config build.nokogiri --with-xml2-include=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.12.sdk/usr/include/libxml2 --use-system-libraries
bundle
```
