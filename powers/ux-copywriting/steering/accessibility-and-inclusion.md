# Accessibility and Inclusive Language Guidelines

Source: AWS Content Design System

## Accessibility in Content

### Color, Sounds, and Shapes
- Refer to a verbatim UI label or title, not the color of the UI element
- Refer to the actual text in a replaceable text example
- Refer to the object label name in a graphical image, not the shape
- Use colors that pass the minimum contrast for their size
- Don't refer to shape alone
- Don't use sound as a reference point

### Spatial Direction (Location)
- Use procedure phrasing and the UI label or title to indicate location
- Refer to a focal point in a console by the UI label
- Use "preceding," "previous," or "following" to refer to content locations on the same page
- Don't use "above" or "below" in documentation
- Don't refer to locations like left, right, up, down unless you also refer to verbatim UI text

**Do:**
- "Your ARN is located to the right of the Studio resources section."
- "In the navigation pane, choose Deployments."

**Don't:**
- "Your ARN is located below."
- "On the left, choose Deployments."

### Device-Agnostic Verbs
- Use "choose" instead of "click"
- Use "enter" instead of "type"
- Not everyone uses a mouse or keyboard — use device-independent verbs

### Content Elements
- **Headings**: Use appropriate heading tags for screen readers. Follow correct heading hierarchy. Don't use bold text alone as headings.
- **Images**: All images should have alt text and lead-in content
- **Tables**: Follow accessible table guidelines
- **Links**: Use link text that describes the target page's topic. Don't use "click here" or "this link"

---

## Inclusive Language

It's important for language to be inclusive, respectful, and as impartial as possible. Language that's not inclusive can be harmful, exclusionary, or reinforce stereotypes.

### Terms to Avoid

| Don't use | Use instead |
|---|---|
| black day | blocked day |
| blacklist | deny list |
| whitelist | allow list |
| master | primary, main, control, leader, manager, root |
| master account | management account, primary account |
| master node | control plane, head node |
| slave | replica, secondary, standby |
| demilitarized zone (DMZ) | perimeter network, perimeter zone |
| grandfathered | pre-approved, pre-existing agreement, legacy approval |

### Best Practices

**Do:**
- Embrace the varied and diverse experiences and perspectives of customers
- Communicate respect
- Describe things in specific, accurate, and relevant ways

**Don't:**
- Assume ethnic, religious, or racial identities
- Use terms appropriated from a specific culture
- Assume binary gender identities or he/she pronouns
- Model or propagate gender role stereotypes
- Use ableist terms that could cause harm to people with mental or physical health conditions
- Use language that could be perceived as derogatory or violent toward a particular person or group

### Inclusive Language in API and Command Names
The guidance for inclusive language applies to API names and operations as well. Follow the guidance for new API and command names. For existing non-inclusive API names, follow the deprecation process.
