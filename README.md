# mandaloianTranslator
Decsription:
A fun use of a translator api. The Mandalorian is a new show on disney+ and I am an avid fan of star wars in general. I decided to use this API to show off my talents and have fun at the same time.

Team : 
Alex Bowers

Problem Domain:
Have you ever wondered what your words would be if you were the premier bounty hunter in the Star Wars galaxy? wonder no longer!

API usage:
POST  /mandalorian
Translate from English to mandalorian.

Parameters
Parameter Name	Parameter Type	Description
text	string	Text to translate.
output
The result is a json object with the converted text.
Here is the full url to use.

	https://api.funtranslations.com/translate/mandalorian.json
	
Here is an example using your browser to convert the given text. Click on the below link to get the json response for the text.

https://api.funtranslations.com/translate/mandalorian.json?text=I%27d%20like%20a%20pint%20of%20ale
Here is an example using CURL to convert the given text.

	curl -v  -i -X POST  -H 'X-Funtranslations-Api-Secret: <api_key>' -d "text=I'd like a pint of ale" https://api.funtranslations.com/translate/mandalorian.json
	
The above call if successful will return a json response something like this.

{
  "success": {
    "total": 1
  },
  "contents": {
    "translation": "mandalorian",
    "text": "I'd like a pint of ale",
    "translated": "<translated text>"
  }
}
	
wireframes:
mainpage -https://wireframe.cc/2MomJp
about me -https://wireframe.cc/piuK9A
previous translations - https://wireframe.cc/eUhcub
