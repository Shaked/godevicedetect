## Device Detect Package for Go

Provides the ability to detect different devices by it's user agent.

### Status: not stable yet!

### Installation

```
$ go get github.com/Shaked/godevicedetect
```

### Usage

[Examples](/example)

### Contribute

If you wish to contribute, please just make sure that if its user agent related, you should add it to the [user agent repository](https://github.com/Shaked/user-agents).

### Open Discussion

Unknown user agents can be saved for later usage. This can be solved by:
1. Resolve by regex inside the Handle.Unknown method
2. Save the result into an extra file\resource
3. Result should point to the right device or be marked as Unknown without re using the regex.

