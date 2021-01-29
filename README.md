## Contact

Discord: itssujee#9904

Team Number: 65

## Inspiration

During the COVID-19 pandemic hospitals have been over-working their staff and as a result quality of care has taken a hit. One of the common ailments associated with contracting COVID-19 is pneumonia, which is  a deadly combination.

## What it does

The 50 Shades of Grey Project uses a Machine Learning Model to determine whether or not an X-ray shows symptoms of pneumonia. Much of the backend processing is done through DCP, which allows for quick distributed cloud processing.

## How I built it

The dataset was hosted on the Google Cloud Platform in the GCS bucket. I made the dataset public to allow for easy access in my notebook. I found a couple articles, research papers, and official Tensorflow documentation to create the Machine Learning Model. I used the DCP API to distribute the work required to process the data for the machine learning model to digest it. 

## Challenges I ran into

The DCP API does not support a lot of features that data scientists would find useful. Furthermore the platform is in a extremely beta form and the lack of documentation made the discovery process more difficult.

## Accomplishments that I'm proud of

I'm proud that my model achieved a 98% recall rate, and a 70% accuracy on the testing dataset. 

## What I learned

I learned how to data engineer using parallelization, as well as I figured out how to build, train, and export a machine learning model in Tensorflow.

## What's next for 50 Shades of Grey

Developing better support for parallelization for data scientists in conjunction with the DCP Platform.

