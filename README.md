# Spanalyzer
Spanalyzer or "Speech Analyser" is an android based mobile application which helps building a basic profile of a person from the speech.

# How it works?

The user is first asked to read out a paraagraph that is taken from the [speech accent archive](http://accent.gmu.edu/browse_language.php) and record his speech of the paragraph. Once recorded the audio file is sent to the Firebase and stored there. The same file will be set to  a Python server and will be processed on a ML algorithm on the server and results are sent back to the app, displaying a basic profile of the user like gender, age and native language.

