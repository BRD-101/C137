
**Student:** Brian Dillion
**Course:** Intro Artificial Intelligence (11122)
**Institution:** Columbus State Community College
**Date:** March 2026

---

## Large Language Model Interaction: The Art of War
---

## Overview

This assignment required selecting a classic text from Project Gutenberg,
downloading it, and interacting with a Large Language Model to gather
information, insights, and summaries from the text. I selected Sun Tzu's
*The Art of War*, translated by Lionel Giles (1910), sourced from Project
Gutenberg (eBook #132). I used Google Gemini as the LLM tool for this
interaction. I chose this text because it is one of the most studied
strategic works in history and its principles have direct application to
operations management, a domain I have worked in for 35 years in
commercial aviation.

> Source: Sun Tzu. *The Art of War.* Translated by Lionel Giles.
> Project Gutenberg, 1910. https://www.gutenberg.org/ebooks/132[^1]

---

## The Book

*The Art of War* is a 2,400-year-old Chinese military treatise attributed
to Sun Tzu, a general serving the King of Wu in the 6th century BC. It
consists of thirteen chapters covering strategy, tactics, terrain,
intelligence, and the philosophy of conflict. The Giles translation
includes extensive commentary from historical Chinese scholars including
Tu Mu, Chang Yu, and Ts'ao Ts'ao, providing additional analytical depth
beyond the original text.

---

## Interactions with Gemini

### Prompt 1: Summarize the main strategic principles of The Art of War

Gemini accurately surfaced six core principles: deception as a
foundation, the goal of efficiency over prolonged conflict, victory
without direct battle, information supremacy through intelligence,
adaptability using the water metaphor, and the principle of combined
energy. The response went beyond the most commonly cited aphorisms and
engaged with less familiar concepts including the energy principle and
the water metaphor, reflecting genuine engagement with the full text
rather than surface-level pattern matching.

What Gemini did not surface unprompted was Sun Tzu's treatment of the
five dangerous faults of commanders: recklessness, cowardice, excessive
concern for reputation, an uncontrolled temper, and oversensitivity to
criticism. These passages represent Sun Tzu's most sophisticated
contribution to leadership thinking, yet they are absent from popular
treatments of the text and were correspondingly absent from Gemini's
unprompted response. A human scholar of the text would have flagged them
as central; the LLM pattern of defaulting to culturally familiar content
left them invisible until specifically requested.

### Prompt 2: Who are the key figures referenced in The Art of War?

Gemini produced a well-structured table identifying seven figures:

| Figure | Role |
|--------|------|
| Sun Tzu (Sun Wu) | Author, native of Ch'i State, served King of Wu |
| Ho Lu | King of Wu who employed Sun Tzu |
| Sun Pin | Described as a descendant of Sun Tzu, military strategist |
| Wu Yuan (Tzu-hsu) | Official and general of Wu, worked alongside Sun Tzu |
| Ts'ao Ts'ao (Wei Wu Ti) | First to write comprehensive commentary on the text |
| Lionel Giles | 1910 translator, British Museum |
| Han Hsin | General who applied Sun Tzu's desperate ground tactics |

This response was more complete than expected, correctly identifying
commentators and translator context rather than limiting itself to the
primary figures. One observation worth noting: Gemini described Sun Pin
as a descendant of Sun Tzu. This is a contested claim among scholars.
Sun Pin was a later military strategist associated with the Warring
States period and the family connection to Sun Tzu is disputed. This
is an example of the LLM producing historically plausible but
unverified content without flagging the uncertainty.

### Prompt 3: How do the principles apply to modern business and
operations management?

Gemini connected five principles to operational and organizational
contexts: strategic planning as pre-action calculation, leadership
virtues and their absence as organizational risk, supply chain
efficiency through external resource utilization, competitive
intelligence through human networks, and organizational discipline
through clear command structures.

The responses were specific and referenced actual passages rather than
generic leadership platitudes. However Gemini did not independently
connect Sun Tzu's resource management argument to aviation operations.
When that lens was applied, the connections became concrete:

| Sun Tzu Principle | Aviation Operations Application |
|-------------------|--------------------------------|
| Prolonged campaigns exhaust resources | Extended ground time and deferred decisions compound operational losses |
| First in the field awaits the enemy fresh | Airlines with schedule buffers absorb disruption better than those at maximum utilization |
| Make calculations before battle | Pre-flight risk assessment and dispatch release decisions |
| Adapt to terrain | Adjusting operations to weather, ATC constraints, and airport conditions |

### Prompt 4: Explain Chapter I of The Art of War in plain language

Gemini produced an accurate and well-structured breakdown of Chapter I,
correctly identifying the five constant factors: Moral Law, Heaven,
Earth, the Commander, and Method and Discipline. The response applied
modern business framing effectively, describing Heaven as market weather
and Earth as competitive landscape.

The treatment of deception was competent but softened. Gemini framed
deception as managing the opponent's expectations rather than the
deliberate calculated manipulation Sun Tzu describes. The instruction
to appear incapable when capable is not a communications strategy; it
is an operational posture. A human military historian would have been
more direct about the intent.

---

## Challenges and Limitations

The primary limitation encountered was the LLM's tendency to produce
plausible but unverified historical claims without flagging uncertainty.
Gemini described Sun Pin as a descendant of Sun Tzu, a claim that is
contested among scholars but was presented without qualification. In a
safety-critical or regulatory context this pattern would represent a
material risk. A second limitation was the absence of domain-specific
connections without user prompting. The LLM required explicit aviation
framing to surface the operational applications that a subject matter
expert would have identified independently. This confirms that LLM
output quality is bounded by the quality of the prompts and the domain
knowledge the user brings to the interaction.

---

## Observations on LLM Patterns

Three consistent patterns emerged across all four interactions:

1. **Accuracy on well-known content**: Passages and principles that
appear frequently in popular culture were reproduced reliably and with
appropriate structure.

2. **Better than expected on secondary figures**: Gemini identified
commentators and historical figures beyond the primary cast, suggesting
the model had meaningful exposure to the Giles edition specifically.

3. **Domain gap on operational application**: Without domain-specific
prompting, Gemini connected principles to generic business strategy.
The aviation operations connections required an informed user to surface
them. This is the most important observation: the value of LLM
interaction scales directly with the domain knowledge the user brings
to the prompts.

The most significant limitation was the production of an unverified
historical claim about Sun Pin without flagging uncertainty. In a
safety-critical or regulatory context, that pattern would be a
material risk.

---

## References

[^1]: Sun Tzu. (1910). *The Art of War.* Translated by Lionel Giles.
Project Gutenberg. https://www.gutenberg.org/ebooks/132
[^2]: WIIT-7810 Course Slides. (2025). *Natural Language Processing.*
Columbus State Community College.
