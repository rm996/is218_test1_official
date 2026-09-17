# IS 218 Test 1 - Calculator Project

## Name
Riya Menon

## Purpose
The purpose of this project is to create a simple Python calculator that can perform addition and subtraction. I also used pytest to test the functions and make sure they return the correct results for positive numbers as well as negative numbers. I also made it so that it returns these numbers for zero.

## Environment Setup

I created a Python 3.13 virtual environment using:

python3.13 -m venv .venv

I activated the virtual environment using:

source .venv/bin/activate

## Install Dependencies

I installed the required project dependencies using:

python -m pip install -r requirements.txt

## Run Tests

To run the student tests:

python -m pytest

To run the student tests and the supplied acceptance checks:

python -m pytest tests checks -v

## Issues

Setup: 

Addition: https://github.com/rm996/is218_test1_official/issues/2

Subtraction: https://github.com/rm996/is218_test1_official/issues/4

Delivery: 

## Test Explanation

One test I wrote checks the addition function using the inputs 2 and 3. The expected result is 5. The assertion checks that the value returned by the add function is equal to 5. If the function returns a different value, pytest reports that the test failed.

## Why .venv Is Ignored

The .venv folder is ignored because it contains the local Python virtual environment and installed packages for my computer. These files do not need to be stored in GitHub because another developer can recreate the environment and install the required dependencies using requirements.txt.