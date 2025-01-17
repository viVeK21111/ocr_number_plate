### Number plate detection 
-> used resnet50+custom layers <br>
-> Trasfer learning <br>
-> Tuned resnet50, some few last layers by unfreezing <br>
-> Predicted bouding boxes <br>

### Number detection
-> I used tesseract ocr to get the numbers from the cropped grayscaled image of number plate <br>
<br>
![image](pic.png)
<br>

-> See \templ.ipynb and \tesseractocr.ipynb files for implementation <br>

-> you can check the models and data in the link given of my gdrive link:<br>
> https://drive.google.com/drive/folders/1DZrXUTulUR7H3sAdxY7nqXOHVAagzz9S?usp=drive_link