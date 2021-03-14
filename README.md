# Udacity Deep Learning Nanodegree Program - Project: Generate Faces

This project defines and trains a DCGAN on a dataset of faces. The goal is to
get a generator network to generate new images of faces that look as realistic
as possible.

## Setup Instructions

Clone the repository and navigate to the downloaded folder:

```bash
git clone https://github.com/thom/face-generation.git
cd face-generation
```

Install [anaconda](https://www.anaconda.com/products/individual) or
[miniconda](https://docs.conda.io/en/latest/miniconda.html) and create a new
conda environment:

```bash
conda create --name deep-learning python=3
```

Enter your new environment:

```bash
conda activate deep-learning
```

Make sure you have already installed the necessary Python packages:

```bash
conda install pytorch torchvision -c pytorch
```

Run the following to open up the Jupyter lab server:

```bash
jupyter lab
```

In your browser, open ```dlnd_face_generation.ipynb```. Follow the instructions
in the notebook; they will lead you through the project.

## Requirements

Graded according to the [Project Rubric](https://review.udacity.com/#!/rubrics/2261/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2021 © [Thomas Weibel](https://github.com/thom).
