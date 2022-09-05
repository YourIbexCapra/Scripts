<div id="header" align="center">
  <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="200"/>
</div>

# Scripts

## Description

Automation scripts.

![GitHub](https://img.shields.io/github/license/YourIbexCapra/configs?label=license)

---

## Table of Contents

- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Setup](#setup)
    - [Clone](#clone)
    - [ENV](#env)
    - [INSTALL](#install)
  - [Start](#start)
  - [Stop](#stop)
- [Build](#build)
- [Usage](#usage)
- [Test](#test)

---

## Getting Started

- ## Requirements

  - [x] Python v3.10.4

- ## Setup

  - ### Clone

    ```shell
    git clone https://github.com/YourIbexCapra/Scripts.git
    ```

  - ### ENV

    ```.env
    python3 -m venv .venv
    ```

    - **Set your shell to use the venv paths for Python by activating the virtual environment.**

      - macOS

        ```shell
        source env/bin/activate
        ```

      - Windows

        ```shell
        .\env\Scripts\activate
        ```

      - Linux
      
        ```shell
        source env/bin/activate
        ```

  - ### Install

    ```python3
    pip install -r requirements.txt
    ```

  - ## Start

    ```shell
    python3 main.py <args>
    ```

  - ## Stop

    **Write to Requirements.txt. (If new packages were installed).**

    ```python
    pip3 freeze > requirements.txt
    ```

    **Disable venv for the project.**

    ```shell
    deactivate
    ```

---

- ## Build

  ```shell
  chmod 755 main.py
  ```

  ```shell
  ./main.py <args>
  ```

---

## Usage

<div align="center">
  <img src=""/>
</div>

---

## Test

  ```shell
  pytest
  ```

<div align="center">

### &#129514; [Unit Tests](docs/UNIT_TESTS.md) &#128221;

</div>
