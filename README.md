
## M10_assignment

Part I. Create web-scraper to load csv file into S3 Bucket 

A web scraper was created as part of the project's first phase to gather information from the website https://www.charitiesnys.com/RegistrySearch/search charities.jsp. The pandas module was then used to convert the information into a CSV file. The CSV file only contained data that was retrieved from the first page of search results. The credentials entered by the user were used to access the Amazon account using the boto3 python package, and an AWS S3 bucket was created to hold this CSV file. The S3 bucket was then used to store the CSV file.

Part II: Update web-scraper to iterate all results and load csv file into S3 Bucket

The project's second phase concentrated on updating the web scraper to repeatedly go through all the pages of the search results and extract all the charity-related data. By doing this, it was made sure that all the data was recorded and saved in the CSV file for analysis. The CSV file was uploaded to the S3 bucket using the same procedure as in Part I.

The web scraper was able to get a more complete picture of the data on the website by going through every page of the search results. This is crucial because it gives a comprehensive image of the charity environment, which can be used to guide decision-making and the creation of policies.

Overall, this study shows the effectiveness of web scraping and how it can be utilized to collect useful data for analysis from websites. Additionally, it emphasizes the value of effective data storage and the part AWS S3 buckets may play in it.
