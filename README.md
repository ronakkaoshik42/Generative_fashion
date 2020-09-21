# Generative Fashion for Indian Clothing

Deep learning-based innovations, particularly GANs, have recently shown great success in fashion modelling for various use cases such as pose and face generation. A famous work, FashionGAN, can generate images with modified clothing as per natural language description and uses the DeepFashion dataset, which primarily contains clothing styles of the Western countries. Currently, no dataset caters to Indian style and clothing. Hence, we present a dataset of 12k images and descriptions pertaining to the Indian culture as well as a baseline approach with this work. Deep learning-based innovations in the Indian Fashion context are a relatively new area of research, and we hope our work will be a starting point for other researchers. 

## Dataset

The images can be accessed at the google drive [link](https://drive.google.com/file/d/1hOsuMZFiMZGlP4oYnLj1MOYview06zf9/view?usp=sharing).
It contains a total of 12306 images scraped using selenium from various commercial websites such as Flipkart, Amazon and Myntra. 
The image distribution can be understood from the following table.

Category (Men) | Count | Category (Women) | Count
------------ | ------------- | ------------ | -------------
Sherwani | 404 | Kurta-Kurtis | 826
Kurta | 1766 | Sarees | 860
Formal | 870 | Lehenga | 936
Casual Shirts | 868 | Dress | 896
T-Shirts | 902 | Shirt | 621
Ethnic Mix | 1649 | Ethnic Mix | 1706
Total | 6459 | Total | 5845

The textual description of each of the images can be found in the images.csv file.

## Scraping

A selenium based script was used to scroll through multiple e-commerce websites and capture the images as well as the textual description. The file 'scrape.py' was used for the same. A sample script used for scraping flipkart has been provided. Similar scripts have been used on Amazon and Myntra.

## Code 

The code can be accessed at https://drive.google.com/drive/folders/1Ebr5LZjVapjZt87LhEFGpw1rKDEKNBPp?usp=sharing
