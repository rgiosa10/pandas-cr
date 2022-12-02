# Code Review: Pandas Code Review

#### By Ruben Giosa

#### This repo includes exercises for working with datasets using pandas.

<br>

## Technologies Used

* Python
* Git
* Markdown
* JSON
* pandas
* numpy
* `.gitignore`
* `requirements.txt`

</br>

## Description
This repo includes exercises for accessing, profiling, cleaning and transforming dataframes using pandas. Data used were large data sets in CSV files for spotify data. The `.gitignore` file includes an exclusion for upload to github because of the size of files.

This repo includes profiling techniques such as `head()`, `tail()`, and `shape`. Leverages `iloc` and `loc` for viewing slices of data. For transformation techniques such as `map()` and `merge()`, and aggregation techniques such as `groupby()`, `count()`, and `max()`.

<br>

## Setup/Installation Requirements

* Go to https://github.com/rgiosa10/pandas-cr.git to find the specific repository for this website.
* Then open your terminal. I recommend going to your Desktop directory:
    ```bash
    cd Desktop
    ```
* Then clone the repository by inputting: 
  ```bash
  git clone https://github.com/rgiosa10/pandas-cr.git
  ```
* Go to the new directory or open the directory folder on your desktop:
  ```bash
  cd python-adv-cr
  ```
* Once in the directory you will need to set up a virtual environment in your terminal:
  ```bash
  python3.7 -m venv venv
  ```
* Then activate the environment:
  ```bash
  source venv/bin/activate
  ```
* Install the necessary items with requirements.txt:
  ```bash
    pip install -r requirements.txt
  ```
* With your virtual environment now enabled with proper requirements, open the directory:
  ```bash
  code .
  ```

</br>

## Known Bugs

* No known bugs

<br>

## License

MIT License

Copyright (c) 2022 Ruben Giosa

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

</br>