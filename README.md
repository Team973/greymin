# greymin


### Statistical and parsing for the greymin ranking system

- Will mostly include functions required to run the ranking system as well as
a test case for implicit ranking based on data collected from Madtown Throwdown 2016.

- Designed to be implemented by a web application built on go.

- Packages include parser, ranking, statistics, teamstore

- For more in-depth implementation information, refer to the godocs


To use or update the following packages:


	$ go get -u github.com/Team973/greymin/...


To run the demo based on data from Madtown Throwdown 2016:


	$ git clone https://github.com/Team973/greymin.git
	$ go run demo.go

To test the functionality of the packages:

	$ cd $GOPATH/src/github.com/Team973/greymin
	$ go get -t -u ./...
	$ go test ./...

If you've done the above once, feel free to just run:

	$ go test ./...
 

Developed by Ron Bhattacharyay under the MIT License.
