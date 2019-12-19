# Byteframe

[![GoDoc](https://godoc.org/github.com/Andoryuuta/byteframe?status.svg)](https://godoc.org/github.com/Andoryuuta/byteframe)

Byteframe is a small helper library for reading and writing binary data in Go.

byteframe assumes all of you binary data can easily fit into memory at once. This library should _not_ be used for anything that would benefit from data streaming (file format parsing, audio/video encoding, etc).  

This library is _HEAVILY_ based on the code from [sgemu](https://github.com/sinni800/sgemu/blob/master/Core/Packet.go)