# Analysis of SEATTLE AirBnB Dataset from 2016
Analysis of the AirBnB Dataset for Seattle in 2016 with focus on features of a listing and its location. Trying to predict the price of a listing based on these information and answer some questions regarding the impact of different aspects on price.

1. Is there a relation between the availability of listings per month and the level of prices?
2. What are the most common features and locations of a listing and what is their impact on price?
3. Is it possible to predict a price based on the feature and location variables?

For more information refer to my blog on [medium link not yet available](https://...)

## Installation
Clone this repo to the preferred directory on your computer using `git clone https://github.com/jochenruland/Project_ABB`
The file `AirBnb_Data_Analysis.ipynb` contains the code. It is recommended to use Juypter Notebook.

The repository contains three datasets
1. `calendar_S.csv` Calender dataset showing prices of available listings per day and non-available listings for AirBnB Seattle
2. `listings_S.csv` Listing dataset of the host listings in 2016 for AirBnB Seattle
3. `reviews_S.csv`: Reviews dataset of the customer reviews for AirBnB Seattle

You must have installed the following libraries to run the code (assuming pip is installed on your computer you can use the pip commands for installation):
- numpy       (`pip install numpy`)
- pandas      (`pip install pandas`)
- matplotlib  (`pip install matplotlib`)
- sklearn     (`pip install sklearn`)
- seaborn     (`pip install seaborn`)

## Additional Explanations
You might be confused with regard to the calendar dataset as I was in the beginning. This dataset does not contain booking information. It contains the information if a listing is available on a specific day in 2016 and the price for the listing on that day. And it contains listings which are not available and do not have any price information.

## License
The MIT License (MIT)

Copyright (c) 2020 Jochen Ruland

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
