# Police interventions

This python app produces a single bar plot showing the level of activity by town of a police service within a region in the province of Quebec (Canada), in comparison to the % of the population of each town of the region.

This plot is produced on a monthly basis.

The program uses the Python library *docx2txt* to convert daily police activity reports produced
in Microsoft word by the police administration service into a txt file that is parsed to find all police interventions for each town of a region.



## Getting Started

The file requirements.txt contains the packages/dependencies to use in your virtual python environment and a dozen of daily police reports are included as input files to the program for convenience. _(The police daily reports never contain any nominative information)_

Using Python 3 in a virtual environment:

```
$ pip install -r requirements.txt
```

## Running the program


```
$ python analyze.py
```



## License

The MIT License (MIT)

Copyright (c) 2017 Serge Grégoire

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
