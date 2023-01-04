# CanvasLMS_Quiz_Uploader
This Excel sheet generates cURL commands to upload quiz questions through Canvas' API.

Follow Canvas' API documentation for clarification on quiz question formatting.
  https://canvas.instructure.com/doc/api/quiz_questions.html

Steps to use the quiz generator:

  1. Generate your API key in Canvas, then paste this into cell A4
  2. Create a quiz in Canvas and grab the quiz ID from the URL, then paste this into cell A6
  3. Type your institutions url into cell A2
  4. Once all your questions have been created, the cURL commands are generated in column G.
  5. Copy and paste this code into your text editor of choice using the bash (.sh) "language."
  6. Save this file, then make it an executable file using terminal/command prompt
  7. Execute the file by double clicking it
