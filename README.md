# d2-diagrams-icons

A [`D2`](https://github.com/terrastruct/d2) template which supplies the icons included
in [`mingrammer/diagrams`](https://github.com/mingrammer/diagrams).

## Quick start

Include `diagrams.g2` in your project<sup>[1]</sup>:

    wget https://raw.githubusercontent.com/denis-ismailaj/d2-diagrams-icons/v0.23.4/diagrams.d2

Import the component you need (you can find them [here](https://diagrams.mingrammer.com/docs/nodes/onprem))

    app: @diagrams.programming.language.Go
    
    # or
    
    app: {
        ...@diagrams.programming.language.Go
    }

This is the same as the following in [`diagrams`](https://github.com/mingrammer/diagrams):

    from diagrams.programming.language import Go
    Go("app")

<sup>[1]</sup> As far as I know, importing remote templates is not supported by G2.

## Running it yourself

    pip3 install -r requirements.txt

    python3 convert.py > diagrams.d2

Feel free to set the [`diagrams`](https://github.com/mingrammer/diagrams) version 
and the output destination as needed.

## Versioning

Tags are matched to the corresponding [`diagrams`](https://github.com/mingrammer/diagrams) versions.

If you need a version that is not provided, check out the [Running it yourself](#Running-it-yourself) section.
