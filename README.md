# bulwark

<div align="center">
  <p><em>Wrapper and some rewrite of RobStatTM R package. Inspired from GSoC 2026 proposal.</em></p>

  <p>
    <a href="https://github.com/DivyenduDutta/bulwark/blob/master/LICENSE"><img src="https://img.shields.io/github/license/DivyenduDutta/bulwark" alt="License"></a>
  </p>

![CI](https://github.com/DivyenduDutta/bulwark/actions/workflows/ci.yaml/badge.svg)

  <p>
    <a href="#introduction">Introduction</a> •
    <a href="#architecture">Architecture</a> •
    <a href="#setup">Setup</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#demo">Demo</a>
  </p>
</div>

## Introduction

Lorem Ipsum

## Architecture

Lorem Ipsum

## Setup

### UV

- Follow [this](https://docs.astral.sh/uv/getting-started/installation/) to install UV
- Install Python 3.10 using UV : `uv python install`
    - this will automatically pick up the correct python version for this project from `.python-version`
- Create a virtual environment : `uv venv`
- Build the project and install all dependencies : `uv sync --locked --all-extras --dev`

## Quick Start

### Sanity

Before committing changes run `uv run pre-commit run --all-files` or `uv run pre-commit run --file <file1>, <file2> ...`

### Run 

`uv run bulwark`

#### Documentation

Run `zensical serve` to start up a localhost server to view the docs for bulwark

Run `zensical build` to generate the static files to deploy to a webserver
