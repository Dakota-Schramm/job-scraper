# job-scraper
Web scraper for freelancer.com. Written in Python.

# The Problem
When using job boards, its hard to keep track of what listings you've looked at. This is especially true when doing searches across different board and with different parameters.

# The Solution
By using web scraping, I can pull in the information from the website and choose how I view it before its printed.

Taking this a step further, one can even pull in information from multiple job boards at once. Once all of this information is pulled in, I can organize it however I want
before its saved. This is useful for several reasons:
  - Removing duplicates: I can filter duplicate results if a company happens to post an opening on several job boards.
  - Ordering the results: I can order the the results by my preferences. This is useful since different job boards prioritize parameters differently and it gives us control over
     how the results are being displayed.
    

# What I did
I researched some of the libraries that existed in Python for web scraping. By combining these with Panda's dataframes, the information from web scraping can be easily
output to an excel sheet.

# What I want to do next
  - Focus on improving the algorithm that pulls the information into the sheets
  - Add a sorting algorithm to organize results before printing to the excel sheet.
