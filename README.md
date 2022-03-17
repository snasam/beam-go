# beam-go
## Go version
go version
## get the SDK
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
## install wordcount
go install github.com/apache/beam/sdks/v2/go/examplesgo run wordcount.go --input sample.txt --output vyshnavi.txt/wordcount
## executing word count
go run wordcount.go --input input.txt --output snasam.txt
## create packages
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
## execute word count
go run wordcount.go --input input.txt --output input.txt
