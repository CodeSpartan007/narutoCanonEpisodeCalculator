# Canon Episode Progress Calculator

A simple Java application to track your progress through a 500-episode TV series by calculating what percentage of canon (non-filler) episodes you've watched.

## Features

- **Automatic Filler Detection**: Pre-configured with filler episode ranges
- **Canon Progress Tracking**: Shows percentage of canon episodes completed
- **Detailed Statistics**: Displays total progress, canon vs filler breakdown
- **Next Episode Preview**: Tells you if the next episode is canon or filler
- **Interactive Interface**: Easy-to-use command-line application

## Quick Start

1. **Compile the program:**
   ```
   javac CanonEpisodeCalculator.java
   ```

2. **Run the application:**
   ```
   java CanonEpisodeCalculator
   ```

3. **Enter episode numbers** to see your progress, or type `quit` to exit



## How It Works

The application uses predefined filler episode ranges:
- 57-71, 91-112, 144-151, 170-171, 176-196, 223-242, 257-260, 271, 279-281, 284-295, 303-320, 347-361, 376-377, 388-390, 394-413, 416-417, 422-423, 427-450, 464-468, 480-483

When you input an episode number, it calculates:
- How many canon episodes you've watched
- Your percentage progress through canon content
- Overall series progress
- Whether the next episode is worth watching (canon) or can be skipped (filler)

## Requirements

- Java 8 or higher
- Command line access

## Usage Tips

- Use this to track your "meaningful" progress through the series
- Check before watching to see if the next episode is canon or filler
- Perfect for binge-watching sessions to maximize story content

---

*Happy watching! 🎬*
