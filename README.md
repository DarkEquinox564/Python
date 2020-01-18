# Python
Can you tell whether this is correct

import re

text = 'random string. hibye@gmail.com.  randoom text'

pattern = re.compile('[a-zA-Z0-9]+@[a-zA-Z0-9]+\.[a-zA-z]+')

result = pattern.search(text)

print(result)
