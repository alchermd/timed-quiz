# timed-quiz

A timed quiz that can be played through the command line

## Installation

This project does not depend on external dependencies. Just run the following to start playing:

```bash
$ go build .
$ ./timed-quiz
```

## Usage

Help is available with the `-h` flag:

```bash
$ ./timed-quiz -h
Usage of ./timed-quiz
  -csv string
    	a csv file in the format of 'question, answer' (default "problems.csv")
  -limit int
    	the time limit of the quiz in seconds (default 30)
  -shuffle
    	if the questions should be shuffled
```

## License

See [LICENSE](LICENSE)