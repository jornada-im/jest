# JEST @ 2022 Jornada Ecology Short Course

**Date and time:** Wednesday June 29, 2022 at 1:00pm Mountain time

**Location:** Garcia Hall conference room at Jornada Experimental Range HQ

**Instructors:** Darren James and Greg Maurer

Welcome to our ecological statistics and models workshop for the 2022 Jornada Desert Ecology Short Course. This workshop is the first of what we hope will be a series of "JEST" (tentative title) workshops, with the aim of teaching introductory and intermediate data analysis and statistics skills to Jornada researchers using hands-on programming in R. This is the first-ever JEST workshop, so please be patient with us.

This workshop will teach basic hypothesis testing with ecological data, building from relatively simple t-tests, up to the (potentially) more complex use of mixed models. Mixed models are an active area of research and development in the statistics community, and there are numerous pitfalls and briar patches in the mixed-model landscape. We'll discuss them and demonstrate the basics, but our goal is primarily to give you the confidence needed to start exploring this topic on your own (perhaps we'll also have another future mixed-model workshop).

## Getting set up

The lessons we are teaching have been developed using `R`, and we are expecting learners to code along with us as we subset the data, fit models, and interpret results. Please follow the general [setup instructions](../../html/setup.html) to be prepared with a working version of R and R Studio. We will download data directly from the EDI repository at the start of the workshop (see more info on the [teaching datasets page](../../html/teaching-datasets.html)). 

In addition to the basic preparations above, you should:

1. Install these R packages: `tidyverse`, `car`, `emmeans`, and `lme4`.
2. Download the [code handout](./jesc-code-handout.R)

If you have trouble preparing or need help please contact Greg (<gmaurer@nmsu.edu>).

## Lesson plan

We only have one big lesson for this workshop:

1. [Hypothesis testing with general linear models and mixed models](../../html/hypothesis-testing-basics.html)