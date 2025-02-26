# Example Package
This is a simple example package. You can use
[GitHub-flavored Markdown] (https://guides.github.com/features/mastering-markdown/) to write your content

# pyproject.toml instructions
* pyproject.toml tells build frontend tools such as pip and build which backend to use for the project.
* `requires` is a key indicating a list of necessary packages for building your package. It should always include your backend's package
* `build-backed` is the name of the Python objects frontends use to perform the build
* `tool` contains additional configuration for the build tool.
## pyproject.toml metadata
* `name` is the distribution name of your package, it can be anything as long as it is not taken and solely contains, letters, numbers, underscores, dashes, and periods (no special characters)
* `version` is the package version
* `authors` identifies the author of the package (name and email)
* `description` is a brief (one-sentence) summary of the package
* `readme` is a path to a file with a detailed description of the package
* `requires-python` shows the versions of Python your project supports
* `classifiers` gives the index and pip additional metadata (like programming language and operating system needed)
* `license` is the SPDX license expression of the package
* `license-files` lists paths to license files
* `urls` lets you list extra links to show on PyPi (source, documentation, issue trackers)

# dist files
* `tar.gz` files are source distribution
* `whl` is a built distribution 

# Using Twine
* To use a TestPyPi API token....
    * Set your username to `__token__`
    * Set password to the token value 