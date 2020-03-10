# Speech to Text
1.Can recognize speech of any language and convert it to text and save it in a downloadable Word format with the original language text and then converted text.
2.Able to convert the spoken text into .mp3 file.Useful for making audio books.

## Prerequisites
```
Translator from googletrans
speech_recognition
docx
gTTS from gtts
```

## How to run the program
1. Install all the prerequisites using pip3 install package-name.
2. Run the code and wait for 5 seconds to let the program calibrate the microphone to the ambient noise.
3. Say something and wait for the code to run.
4. A file named temp.mp3 is created containing the speech in same language.
5. A Microsoft Word document is created named demo_original.docx which contains the text in the same language.
6. Another Microsoft Word document named demo_arabic.docx contains the data of speech in the translated language specified by the user.
