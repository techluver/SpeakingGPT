## Welcome to SpeakingGPT!
SpeakingGPT is a versatile application that lets you interact with the powerful GPT-4 by OpenAI. It provides both voice and text-based interactions, bringing the power of the world's most advanced conversational AI to your fingertips.
## Installation
* Clone the repo: Clone the repository and run the program manually. To do this: git clone https://github.com/techluver/SpeakingGPT.git
* cd SpeakingGPT
* pip install -r requirements.txt
* python SpeakingGPT.py 
## Usage
When you run SpeakingGPT, you will be asked for a number of settings:
* Use the GPU: If you have a GPU capable of transcription, you can choose to use it for faster processing. If you don't, the program defaults to CPU transcription.  Be aware that GPU transcription has not been extensively tested, due to the fact I do not have an nVidia GPU.
* Use GPT-4 or not: If you have access to the GPT-4 API (not the ChatGPT Plus), you can choose to use it.
* Hands free or not: Hands free mode allows you to control the program by voice alone. If you prefer typing, you can choose to disable this.
* Use Elevenlabs: Elevenlabs is a paid Text-To-Speech (TTS) solution. If you have an API key for Elevenlabs, you can input it here to access superior TTS quality.
* OpenAI API key: You will need to input your OpenAI API key to interact with GPT.
Conversing
Once you're through with the settings, you can start conversing. If you're in voice mode, simply talk as if you're having a conversation. Be patient, as it may take up to 30 seconds to receive a response.
If you're using Elevenlabs, you will be asked to choose a voice from your account before you start conversing.

### Commands
The following commands can be used at the input screen. Speak the spoken version, or type out the letters and press enter:
* rec: If not in hands free mode, this allows you to record one input before reverting to typing.
* lc, load conversation: This loads a conversation from a file.
* sc, save conversation: This saves a conversation to a file.
* chf, change hands free: This switches hands free mode on and off.
* chv, change voice: This changes the voice (only in Elevenlabs mode).
* lp, load preset: loads a preset.
* cp, create preset: creates a preset.
When you're done speaking, exit the program.

## language support.
Although the interface is only in English, this supports English, Spanish, French, Portuguese, German, Italian, Polish and Hindi with elevenlabs.  These languages, plus Chinese, Japenese, Korean, Russian and Ukrainian are supported via Google TTS.  Anything else you try may or may not work.

## Supporting me
If you find SpeakingGPT useful, consider supporting me through donations:
paypal.me/harrison934394

## Thanks to:
* [Novum Classicum](https://www.novumclassicum.com) for all his help testing various alpha versions before this ever made it to release.  Seriously man, you rock.
* Chat GPT for all its help with various bugs I ran across.
* The developers of all the various libraries and tools that make this possible, in particular [Faster Whisper](https://github.com/guillaumekln/faster-whisper), and the Elevenlabs team.  Special shout out to [this Python wrapper to the Elevenlabs API](https://github.com/lugia19/elevenlabslib) without which this would not be possible.

## license
This software is distributed under the ZLib license.
  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.
