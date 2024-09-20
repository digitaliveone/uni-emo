this project defines and provide guidelines for a new universal lanuage based on emoji called uni-emo. 
this project also contains prompt json for LLMs to translate natural languages into uni-emo.

# uni-emo: Universal Emoji-Based Communication System

## Overview

uni-emo is an universal communication system that utilizes emojis to bridge language barriers and facilitate global understanding. 
By combining the visual appeal of emojis with structured language principles, uni-emo aims to create a more inclusive and expressive form of digital communication.

## prompt for LLM
Copy and paste the following json into your LLM prompt.
[Prompt for LLM](/uni_emo_for_prompt.json)
developed by claude sonnet 3.5 at this stage so it may work best on claude

## Features

- 🌍 Universal: Designed to be understood across cultures and languages
- 🧠 Intuitive: Based on visual representations for easier comprehension
- 🔧 Flexible: Adaptable to various communication needs and contexts
- 🚀 Expandable: Open for community contributions and enhancements

## Basic Structure

uni-emo uses the following markers:
- 👤 : Subject marker
- 🏃‍♂️ : Verb marker
- 🎯 : Object marker
- 🏷️ : Adjective marker

Words are separated by spaces.

## Word Order

By default, uni-emo sentences are structured by order of importance, with the most crucial information first. Language-specific orders can be indicated using flags (e.g., 🔄🇯🇵 for Japanese order, 🔄🇺🇸 for English order).

## Sentence Types

- Statements: Use markers only
- Questions: Start with ❓ or place ❓ after the relevant part
- Conditional: Use 🔀 after the condition

## Emoji Combinations

Combine emojis to create new concepts:
- Order by importance
- Use 2-3 emojis typically, max 5 for complex ideas
- Prioritize culturally neutral emojis
- Use country flags for cultural specificity when needed

Examples:
- Hospital: 🏥🏠
- Forest bathing: 🌳🧘‍♂️
- Video conference: 💼📱👥
- Japanese cuisine: 🍽️🇯🇵

## No dictionary

We at least in this project. We will not provide a comprehensive dictionary.
We only define crucial markers and core words.

We will let the people and LLM to naturually come up with most intuitive choices and see those good outcomes be repeatedly shared.
The dictionary maybe is needed in the future but it is way too early at this stage.

## Contributing

We welcome contributions to uni-emo! If you'd like to contribute, please:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

For more details, please refer to our [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

Project Link: [https://github.com/Dary1/uni-emo](https://github.com/Dary1/uni-emo)

## Acknowledgments

- Thanks to all contributors and supporters of uni-emo
- Inspired by the universal appeal of emojis and the need for global communication

---

🌟 Join us in revolutionizing digital communication with uni-emo! 🌍🤝 
