
# Evaluating LLM based applications

## Workshop description
It is so easy and quick to build a shiny PoC using LLMs and it is so hard to turn it into a production-grade LLM application. To succeed you need a robust evaluation framework, which you are going to use during the development and post-deployment of your LLM based app.

This workshop focuses on understanding evaluation-driven development and architecture of a LLM based app, building an evaluation framework for a LLM based app, establishing a test suite with evals and laying the monitoring foundations for it. All of it by leveraging Python OSS libraries.

## Requirements
PyLadies Amsterdam uses [uv](https://astral.sh/blog/uv) for dependency management. For installation instructions, please check the [official documentation](https://astral.sh/blog/uv) or the [PyPI page](https://pypi.org/project/uv/).

## Usage
To get started, open the `pyproject.toml` file and set the required Python version. The pre-selected version 3.8 is generally a safe choice for most use cases.

After you have specified the Python version, you can create a virtual environment with `uv venv` and add packages with `uv add <package>`. Before the workshop, you can generate a requirements.txt file, which is needed e.g. for running code in GoogleColab, by running `uv export > requirements.txt`.

## Video record
Re-watch [this YouTube stream](link)

## Credits
This workshop was set up by @pyladiesams and @una-ai-mlops-agency


## Appendix

### Google Colab

To run this project on Google Colab, follow the following instructions:
1. Visit [Google Colab](https://colab.research.google.com/)
2. In the top left corner select "File" &#8594; "Open Notebook"
3. Under "GitHub", enter the URL of the repo of this workshop
4. Select one of the notebooks within the repo.
5. At the top of the notebook, run the following code:
```bash
!cd ./name-of-repo
!pip install -r requirements.txt
```

Happy Coding :)


### Pre-Commit Hooks

To ensure our code looks beautiful, PyLadies uses pre-commit hooks. You can enable them by running `pre-commit install`. You may have to install `pre-commit` first, using `uv sync`, `uv pip install pre-commit` or `pip install pre-commit`.
