# Lecture: AI I - Advanced

Course content for the elective Artificial Intelligence II, focusing on advanced methods and hands-on AI applications.

## Chapter

### Prerequisites

Check the required knowledge and [set up your programming environment](./chapter/00_prerequisites/README.md) to be ready for this module.

### PyTorch & Deep Learning Basics

Learn the fundamentals of deep learning and how to implement neural networks using PyTorch.

1. [Artificial Neuron](./chapter/01_basics/01_mlp.ipynb)
2. [Multi Layer Perceptron](./chapter/01_basics/02_mlp.ipynb)

### Training and Optimising Deep Networks

Learn techniques to effectively train and optimize deep learning models.

1. [Regularization](./chapter/02_training/01_regularization.ipynb)
2. [Hyperparameter Tuning](./chapter/02_training/02_optimization.ipynb)
3. [Ensemble Learning](./chapter/02_training/03_ensemble.ipynb)

### Advanced Techniques

### Excursus

#### Computer Vision (excursus)

Have a look at some popular architectures and techniques used in computer vision tasks.

1. [Convolutional Neural Networks](./chapter/04_excursus/01_cv/01_cnn.ipynb)
2. [Residual Networks](./chapter/04_excursus/01_cv/02_resnet.ipynb)

#### Natural Language Processing (excursus)

Explore transformer architectures and their applications in natural language processing.

1. [Transformer with GPT2](./chapter/04_excursus/02_nlp/01_gpt2.ipynb)
2. [Sentiment Analysis with Transformers](./chapter/04_excursus/02_nlp/02_sentiment.ipynb)
3. [Named Entity Recognition](./chapter/04_excursus/02_nlp/03_ner.ipynb)
4. [AI Agent](./chapter/04_excursus/02_nlp/04_agent.ipynb)

### Assessment

Apply your knowledge in practical assessments to demonstrate your skills in machine learning, optimization, and evaluation.

1. [Assessment 1](./chapter/05_assessment/01_assessment/README.md):
2. [Assessment 2](./chapter/05_assessment/02_assessment/README.md):

## Getting Started

> [!NOTE]
> Use the included dev container to automatically install all the necessary dev tools and dependencies. To use this you first need to install docker under Linux or WSL2 under windows.

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Paul-B98/python-project-template.git
    cd python-project-template
    ```

2. **Open the project in Visual Studio Code:**
    ```sh
    code .
    ```

3. **Reopen in container:**
    - Press `F1` to open the command palette.
    - Type `Remote-Containers: Reopen in Container` and select it.
    - VS Code will build the Docker container defined in the `.devcontainer` folder and open the project inside the container.

## Contributing

### Conventional Commits

We follow the [Conventional Commits]() specification to maintain a consistent commit history and enable automated tooling for releases and changelogs.

#### Commit message format:
```
Commit Message Format

<type>(optional scope): <short summary>

[optional body]

[optional footer(s)]
```

#### Common Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (formatting, missing semicolons, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding or correcting tests
- `chore`: Changes to the build process or auxiliary tools
- `infra`: infrastructure ch

## Documentation

* [Contributing](./.github/contributing.md): A guide on how to contribute to this project, including commit conventions and best practices.
