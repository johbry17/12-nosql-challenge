## Module 12 Challenge, 11 September 2023, noSQL (MongoDB)

Development on this project has stopped.

## Description

This project simulates a contractor assignment for a food magazine, _Eat Safe, Love_. Using data from the UK Food Standards Agency, it answers a a series of questions from the editors of a news magazine to help focus future assignments for journalists and food critics.

## Usage

You can view the data extraction and cleanup process in `NoSQL_setup.ipynb`. Analysis results can be viewed in `NoSQL_analysis.ipynb`. 

If you want to run the code, import the data from the command line with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json`. Then run `NoSQL_setup.ipynb` and `NoSQL_analysis.ipynb` in order.

## References

[UK Food Standards Agency](https://www.food.gov.uk/) (2022). UK food hygiene rating data API.[https://ratings.food.gov.uk/open-data/en-GB](https://ratings.food.gov.uk/open-data/en-GB). Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

## Acknowledgments

Thanks to Geronimo Perez for feedback and assistance

## Author

Bryan Johns, September, 2023
