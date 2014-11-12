## go-mediainfo

Basic MediaInfo bindings for Go.

## Installing

go get github.com/dwbuiten/go-mediainfo/mediainfo

### Notes

On FreeBSD or MinGW, you must remove `-ldl` from the `LDFLAGS` in `mediainfo.go`. This is because these platforms do not require an extra library to support dynamic loading of libraries, which MediaInfo requires.
