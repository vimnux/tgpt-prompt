# tgpt-prompt
tgpt-prompt.sh is a Bash script that uses (custom) chatgpt-prompts
in combinaton with tgpt.

tgpt (Terminal GPT) can be found at:
https://github.com/aandrew-me/tgpt

chatgpt-prompts can be found at:
https://github.com/f/awesome-chatgpt-prompts

### Installation
Download the script with:

<code>curl https://raw.githubusercontent.com/vimnux/tgpt-prompt/main/tgpt-prompt.sh -o tgpt-prompt.sh</code>

Make it executable and place it somewhere in your $PATH

### Usage

<code>tgpt-prompt.sh number</code>

Where 'number' is the number of the prompt that you want to use.

Example:

<code>tgpt-prompt.sh 3</code>

will give you the "Act as a Emoji Translator" prompt.

### TODO for you
Add/remove prompts and customise them to your liking.

Surround prompts that have double quotes (") in them (like the 'DAN' prompt) with single quotes (')

Surround all other prompts with double quotes.

### Notes
If you want to use the "Act as 'Character' from 'Movie/Book/Anything'" prompt, you'll have to give it a Character, etc.

Chat history is not available yet for tgpt.

See:

<code>tgpt -cl</code>
