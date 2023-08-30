# Hinglish conversational dataset

Hinglish is a hybrid language blending Hindi and English, commonly spoken in India, combining vocabulary and grammar from both languages.

Hinglish is often used in text conversations by people in India. Hinglish text mostly contains english characters, transliterated from hindi sentences. Example: "Aaj ka din bohot acha hai"

## Dataset
GPT prompt used was:

```
I want you to generate a Hinglish conversation between two young Indians - a male and a female. Feel free to assume the names of these young Indians. The conversation should contain 100 dialogues. Conversation should be in the format [Name]: [Message]. Conversation should be strictly in Hinglish. If the conversation happens in English, I will punish you. The conversation should be slightly flirty in nature - ending in a romantic moment. The conversation is around the topic: '{setting}'. Do not change subjects frequently. If possible, talk about a subject at length.
```

See `topics.md` for the various conversation contexts provided in the prompt.

