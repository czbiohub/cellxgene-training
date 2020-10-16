# cellxgene-training
**how to make the most out of cellxgene?**

# install cellxgene

## install Anaconda 3

1. download the installer for your system at the end of this page: https://www.anaconda.com/products/individual
2. follow installation instructions here https://docs.anaconda.com/anaconda/install/ 

## install the python dependencies
(pip)pip3 install scanpy louvain --upgrade

## install cellxgene
(pip)pip3 install cellxgene --upgrade


# run cellxgene
cellxgene launch [path-to-your-object/name-object.h5ad] --experimental-annotations-ontology --experimental-enable-reembedding --open

## tricks for macOS
1. to open terminal go to spotlight (magnifying glass symbol on the very top right corner) and type `terminal`
2. if you don't know your file path, get a finder window right next to the terminal window. Select the h5ad file in finder and drag it to terminal


# for some asynchronous learning...
checkout [this](https://drive.google.com/file/d/1NA1VvHYtIpCUhMio7Ui9eDF2flmMpdhU/view?usp=sharing) recording for an enternaining cellxgene live demo! or reach out to the [cellxgene team](https://github.com/chanzuckerberg/cellxgene)


# data to use
for this session let's use [Tabula Muris Senis](https://s3.console.aws.amazon.com/s3/buckets/czb-tabula-muris-senis/Data-objects/?region=us-west-2). Choose a tissue that interests you and let's have some fun :)
