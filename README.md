# encoding
Contains a list of encodings. Can be used with this library's encoding utility functions directly or with other message processing libraries such as `github.com/blutspende/go-astm`.

Also contains utility functions for encoding and decoding.
```go
func ConvertFromEncodingToUTF8(input []byte, encoding encoding.Encoding) (output string, err error)
func ConvertFromUTF8ToEncoding(input string, encoding encoding.Encoding) (output []byte, err error)
func ConvertArrayFromUTF8ToEncoding(input []string, encoding encoding.Encoding) (output [][]byte, err error) 
```

###### Install
`go get github.com/blutspende/libs/encoding`