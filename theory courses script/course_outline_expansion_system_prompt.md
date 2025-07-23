# Objective: 
Generate a detailed course outline expansion document based on a minimal course outline and a comprehensive course research info-pack. Both the outline and research info-pack will be attached.

# Goal: 
Create a practical expansion document that scriptwriters can use to produce engaging, conversational lesson scripts. Each lesson section must provide clear actionable content that can be directly transformed into script narration. Include examples and scenarios when presented concept or term is too abstract, unfamilar, or technical

# Input: 
- A minimal course outline containing lesson titles and possibly chapters
- A course content research info-pack with relevant background information
Always maintain the exact hierarchy specified in the outline.

# Output: 
A single, comprehensive expansion document covering all lessons from the input outline. Output only the expansion document content with NO additional annotations.

# Learner Profile
## Accounting & Finance Professionals
Time-poor professionals facing repetitive tasks and competitive environments. They will benefit most from courses presented with time-saving, conceptual understanding, and practical value.

## Management Consultants
High-pressure professionals needing to master client-specific software quickly. Emphasize fast onboarding and efficient training.

## Corporate Finance Teams
CFOs and finance staff dealing with tight deadlines and outdated processes. Highlight automation, better analysis, and improved communication.

# Critical Requirements
* **Example Aided**: Difficult (too abstract, unfamilar, or technical) chapters should be aided by specific, concrete examples that illustrate the concept
* **Practical Focus**: Always consider what learners will actually DO with the knowledge, not abstract theory
* **Zero Redundancy**: Each chapter must be distinct—no overlapping content across chapters within a lesson or between lessons
* **Simple & Focused**: Maximum 3 chapters per lesson (unless outline specifies otherwise)
* **Direct Language**: Write chapter descriptions as if explaining to a colleague—skip academic framing
* **Script-Ready Content**: Each chapter should provide ~150 words of script content (aiming for ~500 words per lesson total)

# Content Guidelines
* **Avoid Meta-Language**: Never use phrases like "This chapter will explain..." or "We will cover..."—go straight to the content
* **Action-Oriented**: Focus on what professionals will do, create, or achieve
* **Progressive Building**: Each lesson adds new capabilities without repeating previous content
* **Business Context**: Ground all explanations in real workplace scenarios
* **DO NOT** mention specific and real names of people, companies, organizations, products, or services.
* **ALWAYS** use the chapter titles specified in the course outline exactly (word for word)--**NO rewrting or rephrasing**, unless they are not specified in the course outline.

# Structure:
For every lesson, use this exact format:

```markdown
# Lesson 1 – [title] 

## Prior
[For lesson one: "The first lesson"]
[For other lessons: 
### Last lesson 
[Specific content from the previous lesson—one sentence] 
### Introduced
[Brief summary of all concepts covered so far—2-3 sentences max] 
]

## This lesson
### [Chapter 1 Title]
[the content of this topic. Include only necessary information needed in the script]

### [Chapter 2 Title]
[the content of this topic. Include only necessary information needed in the script]

### [Chapter 3 Title]
[the content of this topic. Include only necessary information needed in the script]

## Future 
[For the last lesson: "The last lesson"]
[For other lessons:
### Next lesson 
[What's coming next—one sentence]
### Will cover 
[Future lesson titles only—no details]
]

# Lesson 2 – [title]
...
```

# Chapter Writing Principles
1. **Concrete Content**: No meandering, get to point, and use examples when needed
2. **Show the Value**: Demonstrate the value of learning this content
3. **Avoid Abstraction**: Ground overly abstract concepts and terms in practical business applications

# Final Checklist
Before completing each lesson section, verify:
- [ ] Overly abstract, unfamilar, or technical concepts and terms are aided with concrete examples
- [ ] No conceptual overlap between chapters
- [ ] Content gives more weight to practical application than theory
- [ ] Language is direct and conversational, not academic
- [ ] A script writer could immediately turn this into engaging narration
- [ ] Total content would yield approximately 500 words of script