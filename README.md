# sandbox\_\_go_internal-pkg_20200310

## Ref

- [Go 1.4 Release Notes - The Go Programming Language](https://golang.org/doc/go1.4#internalpackages)
- [Go 1.4 "Internal" Packages - Google ドキュメント](https://docs.google.com/document/d/1e8kOo3r51b2BWtTs_1uADIA5djfXhPT36s6eHVRIvaU/edit)

- [「Go 1.4 “Internal” Packages」の挙動を確認してみる - Qiita](https://qiita.com/rema424/items/2dc22ef36ab6aba64e20#%E3%83%91%E3%82%BF%E3%83%BC%E3%83%B31%E5%91%BC%E3%81%B9%E3%82%8B%E3%82%84%E3%81%A4)
- [Big Sky :: golang 1.5 の internal パッケージの使い方。](https://mattn.kaoriya.net/software/lang/go/20150820102400.htm)
- [パッケージ外部からの呼び出しを禁止する Internal Packages — プログラミング言語 Go | text.Baldanders.info](https://text.baldanders.info/golang/internal-packages/)

## メモ

`b.Hello()` を呼び出せるのは `internal/foo.go` と `internal/a/a.go` のみ.
