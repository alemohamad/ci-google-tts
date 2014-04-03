# CodeIgniter Library: Text to Speech

**ci-google-tts**

## About this library

This CodeIgniter's Library that creates audio files using Google's text to speech web service.  

Its usage is recommended for CodeIgniter 2 or greater.  

**Note:** The API has a 100 character limit.  

## Usage

```php
$this->load->library('TextToSpeech');

$this->texttospeech->setMessage( "Hello world!" );

// *optional: setting the filename is not required
$this->texttospeech->createMessage( "hello" );

// change the output language ("en-US" by default)
$this->texttospeech->setLanguage( "es-AR" );

// get the audio file url
$this->texttospeech->getAudioFile();

// get the HTML5 audio tag with the audio file
// *optional: you can pass TRUE for autoplay
$this->texttospeech->getEmbedAudio();
```

![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)
