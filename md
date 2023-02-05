#!/bin/bash

otsikko="# $(tr '[:lower:]' '[:upper:]' <<< ${1:0:1})${1:1}"
touch $1.md 
echo $otsikko >> $1.md
