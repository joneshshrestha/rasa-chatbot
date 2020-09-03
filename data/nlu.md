## intent:greet
- hey
- hello
- hi
- hey there

## intent:goodbye
- bye
- goodbye
- see you around
- see you later
- talk to you soon

## intent:buy_phone_laptop
- I would like to buy a [phone]{"entity":"category","value":"phone"}
- I want to buy a [laptop](category)
- Please suggest me a good [laptop](category)
- I wanted to purchase a [phone]{"entity":"category","value":"phone"}
- Can you recommend me a [laptop](category)
- give me some recommendations for [mobile phones]{"entity":"category","value":"phone"}
- Can you suggest a [laptop](category)
- I wanna buy a [phone](category)
- Im interested in purchasing a [smartphone]{"entity":"category","value":"phone"}
- I want to buy a [refrigirator](category)
- show me a new good [air conditioner](category)
- please recommend me a [washing machine](category)

 

## intent:latest_news_phones_laptops
- Whats the latest news with [phones]{"entity":"category","value":"phone"}
- Can you tell me about the trends regarding [phones]{"entity":"category","value":"phone"}
- Whats going in the tech world for [laptops](category)
- Can you show me the trends in [laptops](category)
- Any new releases for [mobiles]{"entity":"category","value":"phone"}, whats the news
- update me on the [mobile]{"entity":"category","value":"phone"} news
- show me the latest news for [mobiles]{"entity":"category","value":"phone"}

## synonym:phone
- mobile
- mobiles
- smart phone

# lookup:category
data/lookup_tables/category.txt

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?
