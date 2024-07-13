# Extremely simple checkout replacement that does not use node.js

## Usage
```
name: build
on: push

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: TheXTech/checkout@v10.1
    # Build
```
