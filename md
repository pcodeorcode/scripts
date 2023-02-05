#!/bin/bash

title="# $(tr '[:lower:]' '[:upper:]' <<< ${1:0:1})${1:1}"
touch $1.md 
echo $title >> $1.md
