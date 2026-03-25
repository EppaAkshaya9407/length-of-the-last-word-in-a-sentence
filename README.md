# length-of-the-last-word-in-a-sentence
s=input()
words=s.split()
if not words:
   print(0)
else:
  print(len(words[-1]))
