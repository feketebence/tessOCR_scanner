# TessOCR Scanner
OCR Scanner webapp, using the Tesseract OCR engine. Client-server communication with Socket.IO, connection between server and background process is established using with ZMQ.

1. Install required packages and libraries. <br>
`$ sudo apt install tesseract-ocr` <br>
`$ sudo apt install libtesseract-dev` <br>
`$ pip install pytesseract` <br>
`$ pip install imutils` <br>
`$ apt-get install libzmq3-dev` <br>
`$ pip install pyzmq` <br>
`$ pip install opencv-python` <br>
`$ npm install` <br>
(NodeJS and libzmq is required, check https://github.com/zeromq/libzmq for details about ZMQ)

2. Open a terminal window and start the NodeJS server with `$ node server.js` 

3. Open another terminal window and start the image preprocessing process with `$ python3 preprocess-server.py` 

4. Navigate your browser to 
http://localhost:4630/

5. Upload an image.
