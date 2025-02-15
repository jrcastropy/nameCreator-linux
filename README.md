# nameCreator
[![GitHub issues](https://img.shields.io/github/issues/JHudd435/nameCreator)](https://github.com/JHudd435/nameCreator/issues)
[![GitHub forks](https://img.shields.io/github/forks/JHudd435/nameCreator)](https://github.com/JHudd435/nameCreator/network)
[![GitHub stars](https://img.shields.io/github/stars/JHudd435/nameCreator)](https://github.com/JHudd435/nameCreator/stargazers)
[![GitHub license](https://img.shields.io/github/license/JHudd435/nameCreator)](https://github.com/JHudd435/nameCreator/blob/main/LICENSE)

A python name generator for Windows.

This is a python package for name generation. It can generate names from different countries, and can generate both male and female names.
Current namesets: "american", "russian", "spanish", "italian", "german", "french", "swedish", "finnish". Will be adding Chinese and Japanese in next release. Also will split spanish into mexican, latino, and spanish.

Many of the name sets come from https://github.com/ironarachne/namegen

# Installation
<i>pip install nameCreator</i>

# Usage

## In python file
<i>firstNameMale = nameCreator.firstM.FirstNameMale('nationality')</i>

<i>print(firstNameMale)</i>

<i>lastName = nameCreator.last.LastName('nationality')</i>

<i>print(lastName)</i>

<i>firstNameFemale = nameCreator.firstF.FirstNameFemale('nationality')</i>

<i>print(firstNameFemale)</i>

<i>lastName = nameCreator.last.LastName('nationality')</i>

<i>print(lastName)</i>

## In command line
<i>nameCreatorCLI generate --help</i>

