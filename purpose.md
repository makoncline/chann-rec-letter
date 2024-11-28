# Letter of Recommendation Generator

## Project Overview

This project assists dermatologists in generating personalized letters of recommendation for medical staff applying to healthcare programs. It uses existing letters to maintain writing style while ensuring personalization.

## Primary Use Case

Generate letters for:

- Medical School applications
- Physician Assistant (PA) programs
- Nursing School applications
- Other healthcare professional programs

## Project Structure

- `/output/` - Directory of historical letters organized by program type and year

## Required Information

- Candidate's full name
- Program type (Medical School, PA, Nursing, etc.)
- Duration of working relationship
- At least 2-3 specific examples of candidate's work
- Any unique achievements or characteristics
- Target school/program (if known)

## Document Structure

### Notes Section (`<notes>`)

Contains:

- Key observations about candidate
- Position/program applying to
- Duration of working relationship
- Specific examples of work
- Q&A section for additional information

Example format:
'''
<notes>

- Key observations and examples
- Program details
- Working relationship details

Q&A:
Q: How long did the candidate work with you?
A: 8 months
</notes>
'''

### Letter Structure

1. Opening paragraph:

   - Relationship context and duration
   - Candidate's role
   - Program applying to

2. Body paragraphs:

   - 2-3 key strengths with examples
   - Connect to future program
   - Show growth

3. Closing:
   - Strong endorsement
   - Contact offer

## Style Guidelines

- Use clear, concise language
- Focus on specific examples
- Be positive without exaggeration
- Avoid vague statements or complex words
- Keep professional tone
- No comparisons to other candidates

## AI Q&A Process

1. Initial Questions:

   - Examples relevant to target program
   - Growth in role
   - Program specifics
   - Areas needing expansion
   - Writing style confirmation

2. Documentation:
   - Add to notes as "AI Q&A with Dr. [Name]:"
   - Include all questions, using n/a for unanswered

## Letter Refinement

1. First Draft from notes
2. Enhance with Q&A responses
3. Final Check:
   - Verify key information
   - Match style guidelines
   - Confirm tone
