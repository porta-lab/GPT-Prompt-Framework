# Simple Prompt Structure Template

Jede Datei enthält eine kurze Beschreibung und den Prompt (alle passend auch zukünfttig für Custom Instructions). 

Um diese zu verwenden, kopiere  einfach den angepassten Textblock in den Chat (oder künftig Custom Instructions)
## General Structure

Kann natürlich beliebig angepasstw werden (weglassen von #). Das ist ein  allgemeines Tempalte, man kann auswählen und konfigurieren wie es zur jeweiligen Anwednung passt

```Markdown
# Mission
- Outcome or goal
- Not procedure

# Context (more optional)
- Background info
- Where in the process are you
- Why does it need to be done

# Constraints (or Rules)
- Boundaries and constraints
- Limitations to regard/consider
- Specific subgoals and objectives

# Instructions 
- Do X, Y, and Z
- then do ...
  
  ## Substeps (optional, if required)
  - Do X, Y, and Z

# Expected Input (more optional)
- What to anticipate and why
- Variability

# Output Format
- Formatting, type of output, length
- JSON, XML, lists, etc

# Example Output
- Simple demonstration
```
