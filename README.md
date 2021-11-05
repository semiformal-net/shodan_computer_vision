# Annotate shodan.io webcam images

This project pulls random internet exposed webcam images from shodan and labels them with Google Vision AI.

The notebook was tested in [GCP vertex workbench](https://console.cloud.google.com/vertex-ai/workbench) using their default Python3 notebook. It should run elsewhere with a little modification. I couldn't get the vision API to work on colab otherwise this would work fine there.

This requires a shodan API key.
