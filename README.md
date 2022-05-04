# Zalo-TTS

How to use?

ZaloTTS supports python >= 3.7, <3.9


Step 1: Install library

Open Terminal.app
Execute there command:
$ pip install pyaudio
$ pip install ZaloTTS

Step 2: Speaker

1	South women	    ZaloTTS.SOUTH_WOMEN
2	Northern women	ZaloTTS.NORTHERN_WOMEN
3	South men	      ZaloTTS.SOUTH_MEN
4	Northern men	  ZaloTTS.NORTHERN_MEN

Step 3: Get API key
Get api key [here](https://zalo.ai/docs/api/getting-started).

Step 4: Example (demo file)
from zalo_tts import ZaloTTS

tts = ZaloTTS(speaker=ZaloTTS.NORTHERN_MEN, api_key={your_api_key})
tts.text_to_speech("Câu lạc bộ học thuật ICON xin chào các bạn nhé.")

