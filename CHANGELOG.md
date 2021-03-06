# Changelog

## 0.1.5 - 2020-10-21

### Fix
- Fix issue with array merge/append for alphanumeric

## 0.1.4 - 2020-10-14 HACKTOBERFEST 2020 - 2

### Add
- Add Latitude / Longitude coordinates random generation (as object , as array as number). Thanks to @vrabe
- Add Makefile to launch: unit tests, phpstan (level 6), phpcs (PSR12)
- Adding more tests for DateTime

### Change
- Set min and max default for date time (first day of the current year, last day of the current year), thanks to @armsasmart

### Documentation
- Improve readme file, thanks to @pret3nti0u5


## 0.1.3 - 2020-10-07 HACKTOBERFEST 2020 - 1

### Add
- Add Char Model, now you can generate random chars (numeric, alphabetical, alphanumeric...). Thanks to @parnus01
- Add DataTime Model, now you can generate a random date, thanks to @rebelchris
- Add Float Model, now you can generate a random float, thanks to @jirkavrba
- Add Sequence Char, now you can generate a sequence of chars, thanks to @bitasterisk
- Add toString method in order to have a concatenated sequence of chars, thanks to @paresh27



### Change
- Code is PSR compliance, thanks to @Septikwar
- Alias for the Integer class in Randomize.php, thanks to @Rocksheep
- Update/add some phpdocs, thanks to @webhaikal and @Septikwar
- more strict typed tests,thanks to @wesolowski

### CI/CD
- Add cache for vendors and PHP packages
- Add PHP Linter for 7.1, thanks to @Anita-ihuman

### Documentation examples
- Add example/RandomInteger.php file, thanks to @davidribeiro
- Add example/RandomBoolean.php, thanks to @rebelchris
- Add example/RandomDate.php, thanks to @rebelchris
- Add example/RandomFloat.php, thanks to @jirkavrba
- Add examples/RandomSequenceChar.php, thanks to @xanaDev
In readme file:
- Add range usage, thanks to @sam0hack
- Add generate char, thanks to @Zuruckt


- 

## 0.1.2 - 2020-07-22

### Add
- preserveKeys() during drawing sample from an associative array
- added some test in order to have coverage 100%
  
### Change
- method unique(), allowDuplicates(), noDuplicates() for sequence generation;


## 0.1.1 - 2020-07-20

### Add
- range method for generating integer (shortcut for min and max)
- new examples, useful for new users
- add some notes how to launch test coverage
- add some warning in README specially for cryptographic usage (this is a pseudo random library).

### Change
- improve the usage section in readme

## 0.1.0 - 2020-07-19

- initial release
