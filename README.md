# DeepLogic_Assignment

This Flask Application provides a simple API endpoint to extract the 6 lastest stories from the Time Website.

From this URL : https://time.com

# Installation

Your system should have pip and python installed. Install the required depedencies using:

``` pip install Flask requests ```

# Usage 

Run the given python file using this command.

``` python3 DeepLog.py ```

The API will be accessible at 

http://127.0.0.1:5000/getTimeStories.

You can also do this to get the desired number of stories (we are asked only 6).

by appending ``` ?n_stories=<desired_number> ``` to the URL.
# Output

We get our output in JSON format. We would be directed to the web browser when we click on the above link.

# Dependencies

``` Flask ```
``` Python ```
