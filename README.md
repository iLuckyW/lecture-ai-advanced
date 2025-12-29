# Lecture: AI I - Advanced

Course content for the elective Artificial Intelligence II, focusing on advanced methods and hands-on AI applications.

## Chapter

### Prerequisites

Check the required knowledge and [set up your programming environment](./chapter/00_prerequisites/README.md) to be ready for this module.

### PyTorch & Deep Learning Basics

Learn the fundamentals of deep learning and how to implement neural networks using PyTorch.

1. [Neuronal Network Basics](./chapter/01_basics/01_mlp.ipynb)

### Training and Optimising Deep Networks



### Advanced Techniques



### Excursus

#### Computer Vision (excursus)
#### Natural Language Processing (excursus)
#### Time Series Analysis (excursus)

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
