#!/bin/bash

for f in $(find . -iname "*.gif" -type f)
do
    echo "$(basename $f)"
done

for f in $(find . -iname "*.zip" -type f)
do
    less $f | grep "gif" | awk '{print $NF}'
done
