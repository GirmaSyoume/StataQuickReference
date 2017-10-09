# A list of useful Stata packages.

## StataTools

Includes the following:

More information from: https://github.com/skhiggins/StataTools which explains:

* `exampleobs` prints (randomly selected) example observations and optionally stores the values in a local macro. This is useful to explore possible values of a variable in your data set without being biased by the ordering of the data.
* `head` prints the head observations (first observations in data set) and mimics the `head()` function in R and `head` command in Linux.
* `randomselect` randomly selects observations and marks them with a dummy variable. It differs from `sample` in that it does not drop the non-selected observations from the data set, and that either individual observations or other units, defined by a variable in the data set, can be randomly selected.
* `tail` prints the tail observations (last observations in data set) and mimics the `tail()` function in R and `tail` command in Linux.

Download and install through Stata using `ssc install <package_name>, replace`

## Classtabi

More information from: https://ideas.repec.org/c/boc/bocode/s458127.html which explains:

Command that reports summary statistics, including a 2 x 2 table for discrete classification data. `classtabi` is helpful in cases where only summarized data are available. For example, data-mining software generally produce a 2 X 2 classification table (referred to as confusion matrix) as part of the output. Those values can then be entered into classtabi to produce the additional classification statistics.

Download and install through Stata using `ssc install <classtabi>, replace`

See also: https://github.com/adamrossnelson/conmtrx