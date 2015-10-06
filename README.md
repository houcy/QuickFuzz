# QuickFuzz

An experimental grammar fuzzer in Haskell using QuickCheck, Template Haskell and specific libraries from Hackage.
It found interesting bugs in gdk-pixbuf, jasper and unzip.

## Authors

* Pablo Buiras (Chalmers University of Technology)
* Gustavo Grieco (CIFASIS-Conicet and VERIMAG)
* Martín Escarrá (UNR)

## Requirements

 * A modern version of GHC (e.g 7.10)
 * zlib-dev
 * libbz2-dev

In Ubuntu, a PPA to install GHC 7.10 is available [here](https://launchpad.net/~hvr/+archive/ubuntu/ghc).

## Instalation

    ./install.sh

  * Additionally, you may want to suscribe QuickFuzz to your _PATH_ variable by adding this line to
  your **~/.bashrc** file:

    export PATH=$HOME/.cabal/bin:$PATH
