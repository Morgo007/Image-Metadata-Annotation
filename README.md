## Image-Metadata-Annotation

This Python script processes a folder of JPEG images, extracting and embedding metadata such as the original timestamp and GPS coordinates directly onto the images. 
The script utilizes EXIF data to gather information and overlay it on the images in a clear and readable format.

## Inspiration

As a Domestic Energy Assessor (DEA) and Retrofit Assessor (RA), I often need to include timestamps and GPS coordinates in my photos for auditing purposes. While searching for an app that could easily add this information to my existing photos in the gallery, I realized that no such tool was available. This led me to develop my own solution, which inspired the creation of this code.

This script is valuable for anyone who needs to document when and where photos were taken by embedding this information directly onto the image. I hope it proves useful to others in similar situations, making the task of photo documentation more efficient and reliable.

## Features:

- **GPS Extraction:** Extracts GPS latitude and longitude information from the image's EXIF data and converts it to a readable format.

- **Timestamp Extraction:** Retrieves the original timestamp of when the photo was taken from the EXIF data.

- **Image Annotation:** Overlays the extracted GPS coordinates and timestamp onto the image.

- **Batch Processing:** Processes all .jpg and .jpeg files in a specified input folder and saves the annotated images to a specified output folder.

## Usage:

- Specify the input folder containing the images and the output folder where you want to save the processed images.
- Run the script to automatically annotate each image with its timestamp and GPS data, if available.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.
