# ECS 189G HW 3: The PCFG Model

## Task 1

In this part, the first command to be run is ```perl ./cfgparse.pl grammar2 lexicon < examples.sen```. I read the output and see that each line's third entry is 0.5, which is the probability of the parse T that is given according to the given sentence S. Furthermore, I also inspected both the ```grammar2``` and the ```lexicon``` files, and saw that each entry in grammar2 and lexicon has a weight of 1. This means that each rule is given a uniform weight. Therefore grammar2 is implementing a ''