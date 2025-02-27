# devcontainer-starter

Simple starter repo for setting up a project using devcontainers.

## Usage

Clone the repo and prepare it:

```bash
$ mkdir myapp
$ cd myapp
$ git clone git@github.com:stream-ai/devcontainer.git --depth 1 .
$ rm -rf .git
$ sed -i 's/starter/myapp/g' .devcontainer/devcontainer.json docker-compose.yml
$ code .
```
