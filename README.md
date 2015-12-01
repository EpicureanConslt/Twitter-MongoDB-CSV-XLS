# Twitter-MongoDB-CSV-XLS
Extract tweets; load them into a MongoDB instance and export them into CSV/XLS format

<b>How To Use This Tool</b>

1. Ensure you have the right version of Python installed (2.7 or higher)

2. Set up a local MongoDB instance and make sure it is up and running. 
   By default, MongoDB instance should accept connections via port 27017.
   
3. Create an account on http://dev.twitter.com and get your API keys
   You would need 4 parameters - consumer key, consumer secret, access token & access token secret
   
4. Run the Twitter + MongoDB + CSV.py script and input the desired Twitter Handle or Hashtag

![Python Shell Screenshot](images/img1.png)

5. Voila! Done! The script will extract a maximum of ~3000 tweets of the specified user or hashtag
   and load it into a new collection on the MongoDB instance. It will then export this data into a
   CSV file, using the mongoexport functionality.
   
![CSV Output](images/img2.png)
