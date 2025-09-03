# Three_day_invasion - OSINT CTF Challenge

## Challenge Description
The challenge, worth **200 points**, was titled **Three_day_invasion**. The objective was straightforward yet intriguing:  
> Find the username of the person who posted this image.  

The flag format was clearly stated as:  
**flag{username}**

---

## Approach
This was an OSINT-style challenge involving a satellite image. The task was to trace the image's origin and identify who initially shared it online. Here’s a step-by-step breakdown of the solution process:

1. **Image Analysis**  
   The given image appeared to be a satellite photo, possibly taken from a news or social media post. As no metadata was directly available, reverse image searching was the best starting point.

2. **Reverse Image Search**  
   I uploaded the image to **Google Reverse Image Search**. This technique helps identify visually similar images and their sources.

3. **Source Discovery**  
   Google search results revealed a match on **Twitter (X)**, linking to a post that featured the exact same image.

4. **Extracting the Username**  
   By visiting the linked Twitter post, I found the username of the person who originally shared the image.  

---

## Outcome
Once the username was identified, the flag was constructed using the provided format:

**Flag:** `flag{jembobineuse}`

---

## Key Takeaways
- OSINT techniques like **reverse image search** are powerful tools for tracing the origin of images.
- Social media is often a goldmine for attribution in CTF challenges.
- Always verify the username carefully, as many similar accounts might exist.

