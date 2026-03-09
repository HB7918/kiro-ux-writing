# Alerts and Messages Guidelines

Source: AWS Content Design System

## Alert Categories

1. **Information** — A special circumstance or a service change has occurred or will occur
2. **Error** — The current action can't be completed
3. **Success** — A user has completed an action
4. **Warning** — A pending action has important consequences

## Basic Guidelines

### Do

For headings:
- Include a brief heading that summarizes the subject of the body text
- Write headings that are meaningful for users, especially new users — don't supply an error code only
- For HTTP status codes, include the number and standard definition (e.g., "HTTP status code 404 (Not Found)")
- Use sentence case for headings

For messages (body text):
- Follow voice guidelines for all content
- Keep messages short, straightforward, and actionable
- Use sentence case, complete sentences, and ending punctuation
- Use plain, everyday language instead of obscure codes or techie jargon
- Use positive instead of negative language ("You can link an EC2-Classic instance to only one VPC" not "You can't link to more than one")
- Use active voice if you know the subject
- Use passive voice only to avoid blaming the user
- Use present tense to describe conditions
- Use contractions selectively for casual, friendly tone
- Use second person (you) to address the user directly
- Include links to relevant documentation
- Put replaceable values at the end of a sentence after a colon

### Don't

- Don't use "please" or "sorry"
- Don't use "just" or "simply" — it can make users feel ignorant
- Don't use words that imply blame ("You failed to configure the database correctly")
- Don't repeat text that's already on the page
- Don't use exclamation points
- Don't spell out numbers (use "8 characters" not "eight characters" in console)
- Don't use humor — "Oops! You made a boo boo!" won't be well received

## Alert Types

### Information Alert
Notifies users about a special circumstance or change. Usually doesn't require immediate action.

**Do:**
- "Comprehensive usage data for EC2 instances is now available in Cost Explorer."

**Don't:**
- "You do not have this service yet. Click to automatically sign up."

### Success Alert
Tells users they've completed an action and what the next steps are. Typically doesn't need a heading.

**Do:**
- "You successfully registered the domain {domainname}. To route traffic for your domain, create records in the hosted zone."
- "Your preferences are saved. You can change these settings at any time."

**Don't:**
- "The operation completed successfully."
- Listing every item in a long list of successful operations

### Warning Alert
Draws attention to irreversible or potentially damaging actions. For delete actions, begin with "Delete the...?"

**Do:**
- "Delete the domain {domainname}? You will lose all domain data, and you can't recover the data later. Learn more"
- "Delete this shared dataset? All reports, analyses, and dashboards that use this dataset will stop working. Learn more"

**Don't:**
- "Change your settings or you'll lose your data."
- "Your file is corrupted!"
- Long, rambling messages with multiple possible actions

### Error Alert
Informs users that a problem has occurred. See the Error Messages reference for detailed guidance.
