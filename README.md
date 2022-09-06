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
- [Licensing](#licensing)
- [Disclaimer](#disclaimer)
- [Contact Us](#contact-us)
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

- ## Build

  ```shell
  chmod 755 main.py
  ```

  ```shell
  ./main.py <args>
  ```

## Usage

<div align="center">
  <img src=""/>
</div>


## Licensing

This software is provided under a slightly modified version of
the MIT License. See the accompanying [LICENSE](./LICENSE.md) file for
more information.

## Disclaimer

The spirit of this Open Source initiative is to help security researchers,
and the community, speed up research and educational activities related to
the implementation of networking protocols and stacks.

The information in this repository is for research and educational purposes
and not meant to be used in production environments and/or as part
of commercial products.

If you desire to use this code or some part of it for your own uses, we
recommend applying proper security development life cycle and secure coding
practices, as well as generate and track the respective indicators of
compromise according to your needs.

## Contact Us

Whether you want to report a bug, send a patch, or give some suggestions
on this package, checkout ISSUES tab.

For security-related questions check our [security policy](./SECURITY.md).


## Test

  ```shell
  pytest
  ```

<div align="center">

### &#129514; [Unit Tests](docs/UNIT_TESTS.md) &#128221;

</div>
