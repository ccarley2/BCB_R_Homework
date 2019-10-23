#R Homework Review
###by Ryan Fortune

##Part 1
*I can't identify any mistakes, but I suspect that Dennis wants your sections that look like these--
```
maize_chrom01_increase <- filter(mergedmaize, Chromosome == "1") %>% write_csv(path = "Maize/maize_chrom01_increase.csv")
maize_chrom02_increase <- filter(mergedmaize, Chromosome == "2") %>% write_csv(path = "Maize/maize_chrom02_increase.csv")
maize_chrom03_increase <- filter(mergedmaize, Chromosome == "3") %>% write_csv(path = "Maize/maize_chrom03_increase.csv")
maize_chrom04_increase <- filter(mergedmaize, Chromosome == "4") %>% write_csv(path = "Maize/maize_chrom04_increase.csv")
maize_chrom05_increase <- filter(mergedmaize, Chromosome == "5") %>% write_csv(path = "Maize/maize_chrom05_increase.csv")
maize_chrom06_increase <- filter(mergedmaize, Chromosome == "6") %>% write_csv(path = "Maize/maize_chrom06_increase.csv")
maize_chrom07_increase <- filter(mergedmaize, Chromosome == "7") %>% write_csv(path = "Maize/maize_chrom07_increase.csv")
maize_chrom08_increase <- filter(mergedmaize, Chromosome == "8") %>% write_csv(path = "Maize/maize_chrom08_increase.csv")
maize_chrom09_increase <- filter(mergedmaize, Chromosome == "9") %>% write_csv(path = "Maize/maize_chrom09_increase.csv")
maize_chrom10_increase <- filter(mergedmaize, Chromosome == "10") %>% write_csv(path = "Maize/maize_chrom10_increase.csv")
```
--to be for loops instead. However, I couldn't figure it out and resorted to doing mine the same way you did yours, so I can't offer any suggestions on how to accomplish that.

*Everything was really well-organized into subdirectories, so good job on that


##Part 2
*You are obviously a lot more comfortable plotting than I am, so great job so far. I will suggest that you manually set the aspect ratio and/or text size on some of your plots. This is because they seem to be a bit cluttered, especially on the x-axis.
*I think the plots would be more informative if they were run separately for maize and teosinte, in addition to what you've already done. I'd run your same code on the merges teosinte and maize files.

#Overall, GREAT job! Everything is well-annotated and you should be in good shape for Wednesday.
