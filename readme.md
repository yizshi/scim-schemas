# Project Title

Quick comparison jupyter notebook on different cloud service provider's implementation on scim.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Finding](#finding)

## Installation

    -python3
    -jupyter notebook
    -requirement.txt

## Usage

-use your fav way to start jupyter notebook (vscode|cmd) 

## Finding

Some interesting discover

- Not all cloud provider shares exact same user schemas even they all claim it was created from same RFC.
- All 4 vender seems to have optional enterprise user attribute added as optional to regular user schema. It might be they are optional and this is easier?
- 4me and scim.dev unlike slack and SF, does not have `id` in there schema even it is required by RFC ad they should use it in ther db/persistent layer. They might just not advertise it in their schema.
- Most of the key/value pair within same attribute are similar because they mostly have default value in RFC.
- Attribute can have subattribute and it has similar story as attribute. It an be wildly different.