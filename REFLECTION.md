# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.
content safety was defently the most difficult to get working until i realized i had mistyped the import line then everything fell into place and worked as expected
the next day: looking back over i realized i was just returing safe, and not checking the message now i think i am but it is suprizingly relax i had to put a lot of hate in the message to get anything above 0

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?
the lazy initialization pattern is used to hide the API keys from the main repo it works as a keyvault 

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?
flag for human review because law inforsement needs to be notified but running it myself with that message it didnt flag it