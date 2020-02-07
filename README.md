Earning Call Transcripts scraping
=================================

The following script will web scrape the earnings call transcripts from
seekingalpha.com.

The transcripts will be saved into a html file.

Will need to install necessary libraries if not already installed.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip install scrapy
pip install slugify
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To test run python script.  
Go to folder Scrapy tool.  
Run **earnings.py** script.

If you wish to run the full script set debug_mode variable to **False.**

Credit goes to **kostasx** for code
https://bountify.co/scrape-earnings-conference-call-transcripts

# Plan
* Add from [FinBert](https://arxiv.org/abs/1908.10063)
* Add BERT tutorial
* Add date
* Model...


Instruction

If you run script as is it will just get one transcript and save to html file.  If you set it to False it will download everything.  I haven't tried it on my computer as I've been doing multiple requests from my computer to that site already.   I tried different things and this worked best.  I uploaded it to my repo but if you would like to upload it somewhere else you are welcome to.

