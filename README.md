markdown_content = """# Prosper Wapali

---

## About Me

Developer based in Cameroon. 
Navigating complex codebases, mostly trying to prevent things from breaking.

I build software that:
- Is destined to become legacy code
- Solves a problem until the next breaking API update
- Often keeps me awake much longer than it should

---

## Dependencies

The tools I rely on (and occasionally fight with):

- **Languages:** Python, JavaScript, PHP, HTML5, CSS3
- **Frameworks:** React, Expo, Django, Flask
- **Databases:** MySQL, SQLite
- **Workflow:** Git, GitHub, VS Code, Figma

---

## Projects

### GCE Mathematics PDF Scraper
- Automatically extracts A-Level past papers because manual downloads are tedious.
- Attempts to organize PDFs by academic year, assuming the source hosts haven't changed their structure.
- Handles Google Drive embeds and basic verification to filter out corrupt files.

### Discord Utility Bot
- A bot designed to format and clean up unreadable code blocks.
- Forces a terminal-style layout inside Discord channels to bring some order to chaotic chats.

---

## Contact

Where to find me when things are compile-ready:

- [GitHub](https://www.github.com/prosperwaps)
- [GitLab](https://www.gitlab.com/prosperwaps)
- [X](https://www.x.com/prosperwaps)
- [Threads](https://www.threads.net/@prosperwaps)
- [Hashnode](https://prosperwaps.hashnode.dev)
- [YouTube](https://www.youtube.com/@EmptoneOfficial)
- [Discord](https://discord.com/users/eniugma.)

---

## Activity Monitor

![](https://github-readme-stats.vercel.app/api?username=prosperwaps&theme=dark&hide_border=false&include_all_commits=true&count_private=false)
![](https://nirzak-streak-stats.vercel.app/?user=prosperwaps&theme=dark&hide_border=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=prosperwaps&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

---

## End of File

Until the next unhandled exception.

*Writing code. Fixing bugs. Shipping anyway.*
"""

filename = "README.md"
with open(filename, "w", encoding="utf-8") as f:
    f.write(markdown_content)

print(f"File saved successfully as {filename}")
