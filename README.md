# Installation
## Pre-requisites
1. Docker

## Step 1:
Build container image

`docker build -t products_crud .`

`docker run -d -p 5000:5000 --name products_crud products_crud`