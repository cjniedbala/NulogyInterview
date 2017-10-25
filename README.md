# NulogyInterview
Project for Nulogy Interview

This file describes the methodology and thought processes surrounding the completion of the Nulogy Ineterview Problem.

## Libraries Used

1. igraph

## Methodology

1. Researched networks to determine whether it would be more effective to use R or Python.
2. After selecting R (based on the availability of tutorials), employed code as seen in tutorials, errors and all.
3. Read through the output of the file (ie. the error messages), and chronologically went through and corrected the errors.
4. Utilized print statements and sample outputs (later commented) to assess whether the correct output was produced at each step.
5. Once there were no errors, worked through the plotting (sizing, colouring, etc.) to achieve the desired and/or best case scenario output.

## Though Processes

1. Read the data into an R-readable format
2. Run the networking algorithm from the built-in formula
3. Correct any errors that arise as a result
4. Optimize to fit the needs of the question and/or asthetics

## Assumptions

1. That this was the entirety of the data set (ie. not an excerpt)
2. That this was an individual data set (ie. study would not be replicated)
3. That certain columns were irrelevant for the purposes of the solution and thus omitted them
4. That companies with different spellings/locations were different companies (ie. to be kept separate)

## Question Responses

1. The maximum number of degrees in the network graph is 16 (Walmart Stores Inc)
2. Assuming that no edges are possible between the shippers and the consignees, the density of the network is:
    ((55 + 34) / (55 * 34)) * 100% = 4.76%
