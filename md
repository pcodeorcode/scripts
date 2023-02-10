#!/bin/bash

# Creates markdown file with header named in argument

lower=${1,,}
touch $lower.md
echo "# ${lower^}" >> "$lower.md"

