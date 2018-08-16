[Website](https://www.floydhub.com) • [Docs](https://docs.floydhub.com) • [Forum](https://forum.floydhub.com) • [Twitter](https://twitter.com/floydhub_) • [We're Hiring](https://angel.co/floydhub)

![FloydHub Logo](https://s3-us-west-2.amazonaws.com/floydhub-assets/logo/floydhub_logo_large_transparent.png)

# FloydHub Examples

A collection of ready-to-run machine learning and deep learning models using FloydHub.

## Getting Started

If you are new to FloydHub, we recommend [creating a free account](https://www.floydhub.com) so that you'll be able run jobs and workspaces on our service. Check out [FloydHub Templates](https://www.floydhub.com/explore/templates) for more information on these examples.

## Examples

Each example provides a one-click "Run on FloydHub" button. When you click this button, you'll automatically open up the project in a [Workspace](https://docs.floydhub.com/guides/workspace/) on FloydHub. Behind the scenes, FloydHub will:

* Prepare your Workspace's [environment](https://docs.floydhub.com/guides/environments/) and [CPU or GPU machine](https://docs.floydhub.com/guides/basics/using_gpu/), including installing any [specified libraries or dependencies](https://docs.floydhub.com/guides/jobs/installing_dependencies/)
* Download the project's code from GitHub to the cloud Workspace
* Attach any datasets specified in the project's [floyd.yml config file](https://docs.floydhub.com/floyd_config/) to the Workspace

| Example | [FloydHub Environment](https://docs.floydhub.com/guides/environments/) | Try it now |
|:------ | :------ | :------: |
| [**ColorNet**](https://github.com/floydhub/colornet-template) <br/> Colorize black & white photos  | TensorFlow-1.8 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/colornet-template) |
| [**Pix2Code**](https://github.com/floydhub/pix2code-template) <br/> Train a neural network to code a basic HTML and CSS website based on a picture of a design mockup | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/pix2code-template) |
| [**Image Classification**](https://github.com/floydhub/image-classification-template) <br/> Classify dog breeds in an image | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/image-classification-template) |
| [**Sentiment Analysis**](https://github.com/floydhub/sentiment-analysis-template) <br/> Convolutional neural network (CNN) classifier to predict the sentiment (positive or negative) of IMDB movie reviews | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/sentiment-analysis-template) |
| [**Reinforcement Learning with Gym Retro**](https://github.com/floydhub/gym-retro-template) <br/> Setup for Gym Retro reinforcement learning platform | TensorFlow-1.8 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/gym-retro-template) |
| [**Named Entity Recognition**](https://github.com/floydhub/named-entity-recognition-template) <br/> Use Sequence Tagging with a LSTM-CRF model to extract the named entities from an annotated corpus | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/named-entity-recognition-template) |
| [**Object Detection**](https://github.com/floydhub/object-detection-template) <br/> Use TensorFlow Object Detection API to detect an object in an image | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/object-detection-template) |
| [**Regression Using Wide & Deep Model**](https://github.com/floydhub/regression-template) <br/> Build a classifier to predict the price of a bottle of wine based on its description | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/regression-template) |
| [**Language Identification**](https://github.com/floydhub/language-identification-template) <br/> Detect the language used in a short piece of text (140 characters) | TensorFlow-1.7 | [![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run?template=https://github.com/floydhub/language-identification-template) |

## Contributing

We'd love to add more examples from the community! Please add examples via Pull requests!
