# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Custom Project

### Dataset
The dataset used is from a clinic's patient records.
There are 24 rows with two columns, those columns being:
- age_years: How old the patient is
- height_inches: How tall the patient is in inches

### Signals
The signals used were the raw, direct measurements from the input data.
No computations were done.

### Experiments
The modification experiment was to detect anomalies in the clinic data.
Upper bounds were set at 100 years old 6'2 for height.
Lower bounds were set at 18 years old and 4'8 for height.

### Results
The results observed from the set bounds were that of the 24 patients, two were flagged as anomalies.
Both anomalies were the result of an age out-of-bounds with one patient being 102 and the other 118.

### Interpretation
This means that the system can detect anomalies successfully when discussing older individuals.
The fact that no anomalies were detected via height either means that there were no height anomalies or that I am incorrect in setting the upper bound so high.
I have met numerous people in my life who have been at least 6'2, but statistically speaking, only about ~16% of the American population is over 6 feet tall.
These bounds may need to be reconsidered if applied to a dataset much larger than 24 patients, as that dataset would be much more statistically significant and representative of the general population.

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)
