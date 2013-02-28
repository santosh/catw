#!/usr/bin/env python
#-*- coding:utf-8 -*-

import sys

def Cat(filename):
    try:
        f = open(filename)
        text = f.read()
        print('---', filename)
        print(text, end='')
    except FileNotFoundError:
        print(":::::::::::::::::=>", filename, "NOT FOUND <=::::::::::::::::::::")


def main():
    args = sys.argv[1:]
    for arg in args:
        Cat(arg)


if __name__ == '__main__':
    main()
