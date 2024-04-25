# getFredData-matlab-legacy
getFredData, as it existed until April 2024 (when it switched from datenum to datetime for matlab dates)

R2022 of Matlab changed the way to handle dates from 'datenum' to 'datetime'. In April 2024 getFredData() got a breaking update to switch from datenum to datetime. This repository hosts a legacy copy of getFredData() as it was at the beginning of April 2024 (so using datenum), it exists just so you can run older codes.

In the legacy version: Dates should be formatted as 'YYYY-MM-DD'. The functions returns dates in the standard matlab format (counting number of days since 0001-01-01, and matlab fns 'datevec', 'datenum', etc. can be used)

And the output includes 'X.Data', the first column of which is the dates in datenum format, while the second column is the data values.

The current version of matlab can be found here: https://github.com/robertdkirkby/getfreddata-matlab
