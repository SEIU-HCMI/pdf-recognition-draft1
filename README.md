# PDF Recognition

Checks cards for signatures

## Description

Analyzes cards or forms downloaded from VAN as PDFs. Assuming two signature boxes, this code will determine the locations of the boxes and output a pixel density, along with a determination of the existance of a signature or not (set at XXX by default). 

Converts to a rasterized image then looks for a box

## Getting Started

### Dependencies

* Python 3.12.3 (latest) via Bash Command Line
* [uv](https://docs.astral.sh/uv/getting-started/installation/)
* 

### Installing

* Clone repo
* uv sync (create the .venv directory)
* activate venv
* cd to the repo

### Executing program

* For single card
```
./check_sigs ../location_of_card/card.pdf
```
* For multiple cards
```
ls ../location_of_files/* | xargs ./check_sigs
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

David Mertz
[@DomPizzie](https://securityreflections.substack.com/about)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release


## Acknowledgments

Inspiration, code snippets, etc.
* [Readme Template](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
