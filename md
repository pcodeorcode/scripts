#!/opt/homebrew/bin/bash

lower=${1,,}
touch $lower.md
echo "# ${lower^}" >> "$lower.md"

