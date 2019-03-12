# Snail Problem - APIs

REST services for the snail problem project:

### The Problem (example)

A snail is at the bottom of a 6-foot well and wants to climb to the top. The snail can climb 3 feet
while the sun is up, but slides down 1 foot at night while sleeping. The snail has a fatigue factor
of 10%, which means that on each successive day the snail climbs 10% * 3 = 0.3 feet less than
it did the previous day. (The distance lost to fatigue is always 10% of the first day's climbing
distance.) On what day does the snail leave the well, i.e., what is the first day during which the
snail's height exceeds 6 feet? (A day consists of a period of sunlight followed by a period of
darkness.) Based on these parameters, the snail leaves the well during the third day.

The purpose of this project is to solve this problem in general. Depending on the parameters of the problem, the
snail will eventually either leave the well or slide back to the bottom of the well. (In other words,
the snail's height will exceed the height of the well or become negative.) You must find out
which happens first and on what day.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
