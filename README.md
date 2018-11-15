Provides simple, random emoji and/or text responses to use with chat bots for various "themes".

```
const RandomResponse = require('ellipsis-random-response');

RandomResponse.emoji('happy') => '😀'
RandomResponse.emoji('happy') => '😊'

RandomResponse.response('confused') => 'Uh…'
RandomResponse.response('yes') => 'Absolutely'

RandomResponse.responseWithEmoji('oops') => '🙈 Don't worry about it.'
RandomResponse.responseWithEmoji('oops') => '🦃 These things happen.'

RandomResponse.greetingForTimeZone('America/New_York') => "👋 Good morning!"
RandomResponse.greetingForTimeZone('America/New_York') => "☀️ Good day."
```

Available themes:
```
[
  'happy',
  'celebratory',
  'congratulatory',
  'disappointed',
  'oops',
  'confused',
  'yes',
  'no',
  'understood',
  'hello',
  'appreciated',
  'sarcastic',
  'good_morning',
  'good_afternoon',
  'good_evening',
  'late_night'
]
```
