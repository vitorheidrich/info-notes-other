# Kickoff for beginners in microbial ecology analysis and bioinformatics

I am going to highlight some materials it could be useful to someone starting to work with bioinformatics from the biology-side. It won't be comprehensive but it should cover the basics for the main tools to do the work.

## 1. The tool to rule them all

The tool to use tools in bioinformatics is the command line, and therefore a shell! Its mandatory to have the overall abilities for creating directories, entering them, listing files and connecting to servers.

[The Carpentry](https://software-carpentry.org/lessons/) has an [introduction to the Unix shell](https://swcarpentry.github.io/shell-novice/) quite complete and with examples to learn by doing.

Mike Lee also has created a [tutorial specific for bioinformatics](https://astrobiomike.github.io/unix/) to understand better the Unix system.

Having knowledge of the shell allows to escalate between working with just one file to hundreds of thousands. That's the main point. And also forces you to make your programs explicit since with a click and point approach you will not remember what you did.

## 2. Programming languages

Right now with just two -python and R- you will cover most of your situations. In fact, for someone that only wants to run multiple bioinformatic programs, connect between them and then perform some statistics and figures, just taking one will do the trick.

Since you fall to my hands somehow, anonymous stranger, I have to state that I fancy R. My passion in science is understanding, complex data need statistics, and the main warehouse of statistics is R. Buuut I have to say that as of today (2023) both programs are quite interchangeable, and python, well, it will give you work outside academia. R too, and the community is more fun and wonderful, but well, cards on the table. Ideally... learn both :D

Anyways:

### The language of stats

R is based on generating stats, and its really good at managing table-like data.

Since...2017 the community has grown exponentially (figure of speech), and a big chunk has created an specific philosophy of work based on the tidy data. They call it the `tidyverse`.

Today people do [books with R](https://www.huber.embl.de/msmb/), whole [webpages](https://compasp23.classes.andrewheiss.com/), generative [art](https://www.data-imaginist.com/art), and god knows what else. Really weird people out there.

-   Knowing how to start with R + tidyverse: [R for Data Science](https://r4ds.had.co.nz/).

-   Improving and delving deeper into visualizations: [ggplot2 book](https://ggplot2-book.org/https://ggplot2-book.org/).

-   Stylizing better these visualizations:

### The language of reptilezz

Phyton is versatile, easy to learn, well documented, beautiful and with a strong bioinfo community.

I would switch to this end if in your bioinformatics or microbial ecology future you will need complex analysis of nucleotide data that will need developing new tools. Or machine learning (albeit right now R has also tons of tools).

I don't have an specific starting point. This [carprentries course](https://swcarpentry.github.io/python-novice-inflammation/) seems to cover most of it. There is also a course in the [biocvnet](https://github.com/biovcnet/biovcnet.github.io/wiki/TOPIC%3A-Python).

## 3. Statistics

Given that we usually work with hundreds of thousands of taxa, that we have to process millions of reads and that we are measuring all that through gradients of environmental parameters, knowing statistics is a must to gain some real knowledge of the system.

Susan P. Holmes and Wolfgang Huber have created a detailed book to discuss the overall topics of the present biology, called [Modern Statistics for Modern biology](https://www.huber.embl.de/msmb). It is a must!

If you feel that the content of the last book is too much, you can start with [OpenIntro Statistics](https://www.openintro.org/book/os/). The pdf is for free and covers a nice intro

## 4. Omics

The Omics field has a lot of weird names. Contigs, kmers, primers, bins, SNPs, brujingraphs, goatis, nah, the last one is made up.

Murat Eren is a researcher in microbial ecology that has done the heavylifting for us and has compiled definitions and animations for most of these concepts. Thanks Murat Eren and co!

In this website named [Microbial 'Omics: An introduction](https://merenlab.org/momics/#week-2) you can find all this info.

In his youtube channel you can [have a video](https://www.youtube.com/watch?v=R9KLkCZ95cU&list=PL7133RHfhW-MwCLz-c2DZxAmtoHipqBcL) for each of the topics explained by himself. Thanks again Meren and co!

Another big effort that happened during the pandemic is the [Bioinformatics Virtual Coordination Network](https://biovcnet.github.io/). It has tons of tutorials for all the topics listed above and specific tutorials for specific tools. See the [Wiki](https://github.com/biovcnet/biovcnet.github.io/wiki) for the different topics. Thanks random people. Thanks COVID I guess?

## Summary of the most important websites

These are the most important from my point of view and that deserve to be read from start to finish at the beginning of a PhD or at any point of the career.

| Website                                                                             | Topic                                          |
|------------------------|-----------------------------------------------|
| [The Unix Shell carpentry](https://swcarpentry.github.io/shell-novice/)             | Shell                                          |
| [R for Data Science](https://r4ds.had.co.nz/)                                       | R wrangling                                    |
| [Modern Statistics for Modern biology](https://www.huber.embl.de/msmb) | Statisics for the modern world we live in      |
| [Microbial 'Omics: An introduction](https://merenlab.org/momics/#week-2)            | Microbial omics concepts really well explained |

I hope it was helpful!
