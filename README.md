# NCPodspec

A private podspec repository for all iOS libraries for Nomah Coffee

## Built With

This repository is a conglomeration of various Cocoapods. If you need more information on Cocoapods, [read about it here](https://cocoapods.org). This repo is built on Ruby and is just a hosting location for each of the private pods' .podspec files.

## Getting Started

Follow the steps detailed below if you intend to use one (or more) of the pods in this repo in your project

1. Install the Ruby gem
   ```
   gem install cocoapods
   ```
   
2. Before you can use any pod from this repo, you must add it to Cocoapods
   ```
   pod repo add NCPodspec https://github.com/NomahCoffee/NCPodspec.git
   ```
   
3. Now you can add the private specs repo as a source in your `Podfile`
   ```
   source source 'https://github.com/NomahCoffee/NCPodspec.git'
   ```
   
4. Then you can add each invidual pod to your project using the following command
   ```
   pod 'NCUtils', '~> 1.2'
   ```

## Contact

Caleb Rudnicki - calebrudnicki@gmail.com

📍 Made in BOS
