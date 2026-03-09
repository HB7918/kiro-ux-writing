# UI Copy Guidelines

Source: AWS Content Design System

## UI Tenets

1. **Conversational** — Use natural, conversational language that speaks directly to users. Avoid coining new terms when a description would suffice. Favor short words and brief, direct phrases.

2. **Consistent** — Employ consistent language and UI conventions, never forcing users to interpret the interface. Consistent, predictable UI helps users explore with ease and confidence.

3. **Succinct** — The more words we put in front of users, the fewer they're likely to read. Cut any word that doesn't serve a purpose. Don't waste users' time with "There's a problem" — directly tell them what the problem is.

4. **Planned** — Think about UI text early in the design process. Structure text so it can be understood at a glance.

5. **Clearly labeled** — Create specific, self-explanatory labels. Headings, buttons, links, and other labels should be specific enough that users can understand the UI and make decisions without pausing or reading instructions.

6. **Effortlessly navigated** — Use bullets, blank space, and bold font to break blocks of text into bite-sized chunks.

7. **Device and language agnostic** — Write text that works across different devices and for different languages. Consider if text is too long for a smaller screen or a localized language.

8. **Accessible** — Remove obstacles for users who have disabilities or who access services in alternative ways. Avoid controls labeled with images rather than text. Provide names, titles, or text labels for each UI element.

## UI Best Practices

- Follow the AWS voice guidelines
- Be consistent with other elements on the page and on the rest of a console
- Use sentence case in the UI, except for service names and other proper nouns

## UI Checklist for Writers

### Are the most important words first?
- Eye tracking shows users don't read all words — they scan down the left column seeing only the first words of each line
- Don't: "Start here to register a domain name"
- Do: "Choose a domain"

### Are headings, links, and button labels self-explanatory?
- Most eyeballs jump to headings, links, and buttons, and ignore static text
- Test: Delete all text except headings and control labels. Could users still proceed correctly?
- Does the heading give a clear, specific sense of the material it introduces?
- Is the heading redundant with the instructional text below it? Can you omit the latter?

### Do you really need that text at all?
- Are you providing information only at the moment users are most likely looking for it?
- Is your text located immediately next to the interaction it describes?
- Is your text a Band-Aid for a bigger design problem?

### How much can you cut?
- The more you write, the less users read
- Test: Cut one word. Does it still make sense? Repeat.
- Don't over-communicate — focus on a single primary message per interaction
- Remove filler words: "Add items to your list" not "You can add items to your list"
- Remove redundancies: "Add an address" not "Add a new address"
- Remove welcome messages that don't accomplish anything specific

### Have you chosen words your users use every day?
- Replace technical jargon with normal, everyday words
- Do: "Choose a key pair to connect to your primary node"
- Don't: "Use an existing key pair to SSH into the primary node"
- Use terms the same way they're used elsewhere on AWS
- Use "choose" instead of "click", "delete" instead of "remove"

### Can you break text into bullets or smaller paragraphs?
- Chunking text into small, digestible fragments makes it more scannable

### Are you speaking directly to users in a conversational tone?
- Test: Read it out loud. Does it sound like natural speech?
- Use short, direct sentences and plain, specific words
- Use contractions as you would in conversation
- Speak directly to users as "you" and "your"
- Write in active voice

### Do your word choices make people feel good?
- Emphasize expansion and possibility rather than limitations and prohibitions
- Don't: "You can have only 50 tags for each resource"
- Do: "You can add up to 50 tags for each resource"
- Focus on solutions rather than failures
- Don't: "You haven't completed your contact information"
- Do: "Enter your address"

### Will your text work in other languages?
- Imagine it will be 1.5x as long in English. Does it still fit the UI?
- Are there colloquialisms that will be difficult to translate?
- Remember that word order changes for different languages

## Voice and Tone Examples (Before/After)

### General instructional text
- Before: "You have no Reserved Nodes. Click the Purchase button above to begin purchasing a reserved node offering."
- After: "You don't have any reserved nodes. If you want one, choose Purchase reserved nodes to get started."

### Dialog box
- Before: "Enable detailed monitoring for your instance to get these metrics at 1-minute frequency."
- After: "Your instance sends metric data to Amazon CloudWatch every five minutes at no charge. For an additional cost, you can turn on detailed monitoring to send metric data every minute."

### Tooltip
- Before: "These roles are the roles belonging to you that are assumable by Elastic Transcoder. They must grant Elastic Transcoder the correct permissions on your S3 buckets and SNS topics to be transcoded."
- After: "An IAM role gives Elastic Transcoder permissions to convert your files. Learn more"

### Wizard step
- Before: "The Setup Wizard will install Amazon WorkMail Migration Tool on your computer. Click Next to continue or Cancel to exit the Setup Wizard."
- After: "Setup installs the Amazon WorkMail migration tool on your computer. You can use the tool to migrate your mailboxes stored in other email systems to Amazon WorkMail."

### Download instructions
- Before: "Click the button to download a report that lists all your account's users and the status of their various credentials."
- After: "Download a list of users in your account and the status of their credentials. Learn more"

## Capitalization

- Use sentence case for titles, headings, and subheadings
- Capitalize proper nouns, including service names
- Use title capitalization for service names
- Use lowercase for feature names
- Use all caps for file format abbreviations (HTML, PDF)
- Use all lowercase for actual file names (getting_started.html)

## Console Terminology

- Service home page (not "first run page")
- Navigation pane (far left pane)
- Content pane (main area — usually called by specific name like "resource list" or "details page")
- Help panel (collapsible panel on right side)
- Use "choose" not "click" for UI actions
- Use "enter" not "type" for text input
