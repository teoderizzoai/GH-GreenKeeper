# 🌱 GH-GreenKeeper

*Because apparently, a green GitHub profile is the new LinkedIn premium*

## What is this madness?

Welcome to **GH-GreenKeeper**, the most sophisticated solution to the most trivial problem: keeping your GitHub contribution graph looking like a lush, verdant forest. 

This project automatically commits motivational messages to your repository 4 times a day, ensuring your GitHub profile stays as green as your neighbor's envy. Because nothing says "productive developer" like a perfectly green contribution graph, right? 

## 🎯 Features

- **AI-Powered Motivation**: Uses OpenRouter API to generate unique, inspiring quotes
- **Natural Contribution Pattern**: Randomizes commits to create realistic green squares
- **Variable Intensity**: 1-4 commits per run for different shades of green
- **Realistic Skipping**: 15% chance to skip runs (just like real life!)
- **Fallback System**: 10 handcrafted motivational messages when AI fails
- **Duplicate Detection**: Ensures variety in your daily dose of inspiration
- **Automatic Timestamps**: Each message comes with a precise timestamp
- **Retry Logic**: Because even bots have commitment issues

## 🚀 How it works

1. **GitHub Actions** runs every 6 hours (00:00, 06:00, 12:00, 18:00 UTC)
2. **Randomization Engine** decides whether to skip (15% chance) or commit 1-4 times
3. **OpenRouter API** generates unique motivational quotes for each commit
4. **Fallback System** kicks in if the AI is having a bad day
5. **Auto-commit** adds messages to `progress.md` with natural timing
6. **Your profile** becomes the envy of every developer on GitHub (with realistic green squares!)

## 📋 Requirements

- A GitHub repository (duh)
- An OpenRouter API key (for the fancy AI messages)
- A sense of humor about your GitHub profile

## ⚙️ Setup

1. **Fork this repository** (or create your own with these files)
2. **Add your OpenRouter API key** as a GitHub secret:
   - Go to Settings → Secrets and variables → Actions
   - Add `OPENROUTER_API_KEY` with your API key
3. **Enable GitHub Actions** in your repository
4. **Sit back and watch the magic happen**

## 📝 Sample Output

Your `progress.md` will look something like this:

```markdown
# Daily Motivational Message

- **2024-01-15 00:00:00**: Every line of code is a step toward your dreams. Keep building.
- **2024-01-15 00:00:05**: Your persistence today shapes tomorrow's success. Stay focused.
- **2024-01-15 00:00:10**: In the quiet of creation, magic happens. Trust the process.
- **2024-01-15 06:00:00**: Small progress compounds into extraordinary results. Keep going.
- **2024-01-15 12:00:00**: Your dedication is the foundation of achievement. Build wisely.
- **2024-01-15 12:00:05**: Every challenge overcome makes you stronger. Embrace the journey.
- **2024-01-15 18:00:00**: The best code is written one function at a time. Stay patient.
```

*Note: Some runs might be skipped (15% chance), and some might have multiple commits, creating a natural-looking contribution pattern.*

## 🤖 The AI Prompt

The system uses this prompt to generate messages:
> "Generate a unique, inspiring motivational quote for someone working on a long-term project. Make it creative, varied, and under 30 words. Avoid generic phrases. Make each quote feel fresh and original."

## 🎭 Fallback Messages

When the AI is having an existential crisis, these gems come to the rescue:

- "Every line of code is a step toward your dreams. Keep building."
- "Your persistence today shapes tomorrow's success. Stay focused."
- "In the quiet of creation, magic happens. Trust the process."
- "Small progress compounds into extraordinary results. Keep going."
- "Your dedication is the foundation of achievement. Build wisely."
- "Every challenge overcome makes you stronger. Embrace the journey."
- "The best code is written one function at a time. Stay patient."
- "Your vision becomes reality through consistent action. Keep coding."
- "Innovation happens in the space between comfort and chaos."
- "Every bug fixed is a lesson learned. Grow through debugging."

## 🎪 Why does this exist?

Look, we all know that:
- GitHub's contribution graph is basically a productivity beauty contest
- Recruiters judge you by the color of your squares
- Your self-worth shouldn't depend on green pixels
- But here we are, optimizing for the algorithm

This project is a playful commentary on that reality. It's like wearing a fake mustache to a party - everyone knows it's fake, but it's still fun.

## 🛠️ Technical Details

- **Language**: YAML (GitHub Actions)
- **API**: OpenRouter (using openchat/openchat-7b:free model)
- **Schedule**: Cron job every 6 hours
- **Error Handling**: Comprehensive fallback system
- **Commit Strategy**: Atomic commits with descriptive messages

## 🤝 Contributing

Want to make this even more ridiculous? Contributions are welcome! Some ideas:
- Add more fallback messages
- Implement different AI models
- Create themed message categories
- Add seasonal variations

## 📄 License

MIT License - because sharing is caring, and we're all in this green square game together.

## 🙏 Acknowledgments

- GitHub for making us care about green squares
- OpenRouter for providing the AI magic
- The entire developer community for this shared delusion
- My future self for having a green profile

---

*Remember: A green GitHub profile doesn't make you a better developer, but it does make you feel better about yourself. And sometimes that's enough.* 🌱✨