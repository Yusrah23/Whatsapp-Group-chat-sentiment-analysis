# Whatsapp-Group-chat-sentiment-analysis
A group of data professionals/enthusiasts decided to create a WhatsApp group to help each other pivot through the data field. Being inquisitive, I wanted to know how often people chat in the group, the most active members, peak hours, and the sentiment behind the messages being sent.

I imported Textblob which is one of the libraries used for sentiment analysis. Then I wrote a function to get the polarity score of each message, with 1 being positive, 0 being neutral and <0 being negative. 

Note: Textblob will ignore the words that it doesn't know, it will consider words and phrases that it can assign polarity to and averages to get the final score.
