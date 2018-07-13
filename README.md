# TikzExternalize - example usage of tikzexternalize

## Note

You have to make sure that you include `--shell-escape` parameter when invoking pdflatex. For TeXstudio goto `Options > Configure TeXStudio > Commands` and substitute the following

~~pdflatex -synctex=1 -interaction=nonstopmode %.tex~~
  
pdflatex -synctex=1 -interaction=nonstopmode --shell-escape %.tex

## Example

The [compiled example](tikzExternalize.pdf) looks like this 

<p align="center">
  <img scale="0.5" src="tikzExternalize.png" height=400>
</p>

In the `figures` directory you have the [standalone image](figure/tikzExternalize-figure0.pdf)

<p align="center">
  <img scale="0.5" src="tikzExternalize-fig.png" height=400>
</p>

The image is taken from [here](http://www.texample.net/tikz/examples/dominoes/).
