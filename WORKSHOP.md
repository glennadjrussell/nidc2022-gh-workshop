# Workshop 2

## Basic action
```
name: deployment-pipeline

on:
  push:
    branches:
      - main

  pull_request:

jobs:
    build:
      runs-on: ubuntu-latest

      steps:
        - name: hello world
	  run: echo "hello action!"
```
