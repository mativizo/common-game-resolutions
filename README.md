# common-game-resolutions
What are common game resolutions? Take a look at this repository, which contains list of resolutions for your game settings or project starting resolution.


### Table of contents:
- [List of the resolutions](#common-resolutions)
- [The most popular resolutions by Steam](#popular-resolutions-by-steam)
- [About Resolution Scaling](#about-resolution-scaling)
 - [What is it?](#what-is-it)
 - [How does it work?](#how-does-it-work)
 - [Benefits](#benefits)


### Common resolutions

Twelve common resolutions that can be found in real world.

| # | Resolution | Aspect Ratio | Name | Use cases |
| - | ---------- | ------------ | ---- | --------- |
| 1 | 1920x1080 | 16:9 | Full HD / 1080p | The most common resolution. Modern screens, TVs, etc. |
| 2 | 2560x1440 | 16:9 | 2K | High-end screens and TVs. |
| 3 | 3840x2160 | 16:9 | 4K / Ultra HD | resolution for high-end displays. |
| 4 | 1680x1050 | 16:10 | - | Common in older laptops and monitors. |
| 5 | 1920x1200 | 16:10 | - | Provides extra vertical space to extend Full HD. |
| 6 | 1024x768 | 4:3 | - | Classic resolution from the CRT monitor era. |
| 7 | 1280x960 | 4:3 | - | A variant of 4:3 with more pixels. |
| 8 | 2560x1080 | 21:9 | Ultra-wide Full HD | Not commonly used. Extra vertical space for Full HD. |
| 9 | 3440x1440 | 21:9 | Ultra-wide 2K | Not commonly used. Extra vertical space for 2K. |
| 10 | 1280x720 | 16:9 | HD | Common for lower-end devices. |
| 11 | 1600x900 | 16:9 | - | Offers a balance between HD and 2K. |
| 12 | 1366x768 | 16:9 | - | Common for older laptops. |

### Popular resolutions by Steam

Below you can find the most popular resolutions based on Steam survey.
List was updated to **January 2024** results of the survey.

| # | Resolution | Aspect Ratio | % of players | Tendency |
| - | ---------- | ------------ | ------------ | -------- |
| 1 | 1920 x 1080 | 16:9 | 59.70% | ⬆ |
| 2 | 2560 x 1440 | 16:9 | 16.02% | ⬇ |
| 3 | 1366 x 768 | 16:9 (almost) | 4.01% | ⬇ |
| 4 | 3840 x 2160 | 16:9 | 3.78% | ⬆ |
| 5 | 2560 x 1600 | 16:10 | 3.33% | ⬆ |
| 6 | Others | - | 2.75% | ⬆ |
| 7 | 3440 x 1440 | 21:9 | 2.31% | ⬆ |
| 8 | 1440 x 900 | 16:10 | 1.19% | ⬇ |
| 9 | 1920 x 1200 | 16:10 | 1.14% | ⬆ |
| 10 | 1600 x 900 | 16:9 | 1.13% | ⬇ |
| 11 | 2560 x 1080 | 21:9 | 0.98% | ⬆ |
| 12 | 1680 x 1050 | 16:10 | 0.75% | ⬇ |
| 13 | 1360 x 768 | 16:9 | 0.71% | ⬇ |
| 14 | 1280 x 800 | 8:5 | 0.48% | ⬇ |
| 15 | 800 x 1280 | 10:16 | 0.47% | ⬆ |
| 16 | 1280 x 1024 | 5:4 | 0.43% | ➡ |
| 17 | 5120 x 1440 | 21:9 | 0.30% | ⬆ |
| 18 | 2880 x 1800 | 3:2 | 0.28% | ⬆ |
| 19 | 1280 x 720 | 16:9 | 0.23% | ⬇ |

#### Conclusions

- It's good to prioritize common resolutions. The majority of players (59.70%) still use the good old 1920 x 1080 (16:9) resolution. Ensure your game looks great at this resolution, as it remains the standard choice.
- Be ready for 4K. With 3.78% of players using 3840 x 2160 (16:9) (4K), consider optimizing your new project for higher resolutions. High-quality textures and UI scaling are crucial for a pleasant 4K experience.
- Support Ultra-Wide resoultions. 3440 x 1440 (21:9) and 5120 x 1440 (21:9) are gaining popularity (2.31% and 0.30% respectively). Implementing proper ultra-wide support can enhance immersion for these players.
- Don’t forget about 16:10 resolutions like 2560 x 1600 and 1920 x 1200 (3.33% and 1.14% respectively). Cater to these users by ensuring UI elements scale correctly.
- Keep an eye on trends. Some resolutions are declining (e.g., 1366 x 768, 1440 x 900), while others are rising (e.g., 2560 x 1600, 800 x 1280).
- Dynamic Scaling can be helpful. Consider implementing dynamic resolution scaling to adapt to different monitors without sacrificing performance.


Remember to test responsiveness of your game. Test your game across various resolutions. Responsive UI design is crucial to accommodate different screen sizes.


### About Resolution Scaling

##### What is it?
Resolution scaling allows you to adjust the output resolution dynamically to improve performance.

##### How does it work?
When your GPU encounters demanding areas, resolution scaling lowers the output resolution.

##### Benefits
- Focusing on gameplay without compromising image quality.
- Enhancing visuals without requiring more powerful hardware.
- Reducing GPU power consumption and memory usage.
