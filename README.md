# POV-AI-Storytelling

[中文](README_CN.md) | English

> A practical framework for turning an idea into a first-person AI visual story with clear cause and effect and coherent image sequences.

This project documents the work of developing a story, defining its recurring elements, planning shots, generating images, and checking the results. It currently provides five fillable templates and documentation for **Suburban Online Romance**, a 35-shot case study.

The central question is: **How can a sequence of images tell one coherent story?**

Start with the [case study](examples/suburban_online_romance/README.md), or use the [story idea template](templates/story_idea_template.md) for your own project. These are Markdown documents; no software installation is required to use them. Bring your own image-generation tool when you are ready to make images.

Chinese project name: **第一视角 AI 视觉叙事方法论**.

The templates and detailed case-study documents are currently primarily in Chinese. This page provides an English introduction and navigation.

## What you can create

The framework focuses on image sequences and short visual stories, particularly the actions, discoveries, and order of information in first-person storytelling. The current case uses a realistic phone-photo style and a suspense structure. The templates can also support everyday, relationship, adventure, and fantasy stories.

**POV** means *Point of View*. Here, it mainly means seeing the world from a character's position. The audience follows that character toward a place, notices a detail, or witnesses a choice, gradually understanding what is happening.

First-person images do not need visible hands or feet in every frame. They also do not automatically mean the character is holding a phone and recording everything. Third-person shots, memories, photographs, and screens can all be used when changes in perspective and access to information remain clear.

The current materials mainly cover still-image workflows. Timing, sound, and transitions can be added to the storyboard for video, but a complete video-production tutorial remains future work.

## Quick start

Begin with a short story of manageable scope. Each template offers a quick entry point and optional detail; you do not need to complete every field at once.

| Step                         | Question to resolve                                          | Template                                                  | Output                                                       |
| ---------------------------- | ------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------ |
| 1. Develop the idea          | Who wants what, why do they continue, and what happens in the end? | [Story idea](templates/story_idea_template.md)            | `idea.md`: motivation, cause and effect, and ending direction |
| 2. Define recurring elements | Which characters, locations, and props need to stay recognizable? | [Story bible](templates/story_bible_template.md)          | `story_bible.md`: shared definitions and references          |
| 3. Plan the sequence         | What does the audience see in each image, and how do the images connect? | [Storyboard](templates/storyboard_template.md)            | `storyboard.md`: shot order and visual tasks                 |
| 4. Make the images           | How should this particular shot be generated or edited?      | [Shot prompt](templates/shot_prompt_template.md)          | Actual prompts, reference images, and output records         |
| 5. Check and revise          | Does the image do its job, and does it connect with the surrounding shots? | [Continuity checklist](templates/continuity_checklist.md) | `continuity_notes.md`: discrepancies, decisions, and recheck results |

Copy the templates into your own project directory, keeping the originals available for reuse. These output filenames are suggestions; adapt them as needed and keep image paths and document references consistent with the actual files.

After making a related group of shots, review them in presentation order. If the review reveals a problem with motivation or design, revisit the idea, story bible, or storyboard and update the affected images. Revision can move between stages.

## Principles to work with

### 1. Establish why the character acts

A one-sentence idea can start with a character, a situation, a change, and an action. For example: a student preparing for postgraduate entrance exams returns to everyday life after an online romance ends, then notices a table in the vacant land along his route to class.

Why does he notice it? Why does he pass it again? Why does he eventually approach? Actions and motivations connect the events into a story.

For a mystery, you can work backward from the truth to the traces it would leave. Other stories may develop around a goal, relationship, or choice. A hidden identity or final twist is optional.

### 2. Separate authorial facts, visible evidence, and audience inference

| Layer              | Example                                                      |
| ------------------ | ------------------------------------------------------------ |
| Authorial fact     | The bag at the end is the one lost at the beginning          |
| Visible evidence   | Both images show a blue square patch and a metal clasp with a chipped corner |
| Intended inference | The audience recognizes the same bag through those features  |

If the clasp changes in the generated image, the authorial fact can remain, but the visual discrepancy needs to be recorded. Writing “the same bag” in a prompt does not establish that the output provides enough evidence to recognize it.

Audience understanding also requires care. Without actual reader feedback, record it as an intended response or a reviewer's judgment rather than claiming everyone will understand.

### 3. Give each image a clear purpose

An image can advance an action, establish a relationship, introduce a place, bridge time, or allow an emotion to settle. Every image does not need a new clue, but you should be able to explain what would be lost if it were removed.

Choose a main reading task, then arrange supporting details. A single still image depicts a selected moment. Entering a room, opening a file, discovering a photograph, and turning toward someone will usually require several presentation units.

### 4. Describe information boundaries visually

“The blanket covers the photograph's subject, leaving only the lower-right corner visible” is an actionable instruction. “Reveal 20% of the information” is not directly checkable.

When hiding an identity, specify what remains visible and what is covered. When confirming one, provide recognizable features. Captions, chat messages, accompanying text, and narration can carry information too, provided they actually appear in the work rather than only in the author's notes.

### 5. Allow changes that have a reason

Continuity preserves identity and world rules. Characters can change clothes, weather can change, and objects can be moved when the timeline and actions support those changes.

At the same location, a reverse angle can change what appears on the left or right. An object outside the frame has not necessarily disappeared. Check camera position and direction before treating a difference as an error.

A phone-photo look is a stylistic choice. Noise, blur, and imperfect framing are optional and should not obscure key clues. The framework does not require a single aspect ratio or photorealistic style for every story.

### 6. Check the revision before marking it complete

Prefer a local correction for a local problem, specifying what must be preserved. For problems involving overall space, pose, or dependencies across several shots, consider regenerating the image or revising the storyboard.

For an aspect-ratio mismatch, check the actual dimensions and whether cropping would remove clues. For an added object, distinguish an unintended addition from a planned piece of evidence. A broad instruction such as “remove all text” could erase a document or chat message the story needs.

A proposed fix, a newly generated image, and a verified correction are three different stages. Recording a problem does not mean it has been fixed.

## Case study: Suburban Online Romance

A student's everyday life, online relationship, and suburban route gradually become connected through visual clues. The case is organized into 35 shots to show how a story becomes a sequence of images and where the actual outputs differ from the intended design.

**The idea, story bible, storyboard, and continuity documents below contain the full plot and ending.** To explore the story before its breakdown, start with the case-study entry page.

| Document                                                     | Contents                                                   |
| ------------------------------------------------------------ | ---------------------------------------------------------- |
| [Case-study entry](examples/suburban_online_romance/README.md) | Reading guidance, selected images, and document navigation |
| [Story idea](examples/suburban_online_romance/idea.md)       | Motivation, cause and effect, and story direction          |
| [Story bible](examples/suburban_online_romance/story_bible.md) | Characters, places, props, and author-confirmed facts      |
| [Full storyboard](examples/suburban_online_romance/storyboard.md) | Images and information order across 35 shots               |
| [Continuity notes](examples/suburban_online_romance/continuity_notes.md) | Observed discrepancies, their impact, and revision tasks   |

The case retains production issues involving interfaces and timing, prop recognition, spatial consistency, and image proportions. Listed revision tasks do not mean all the images have been corrected. The case is also not a complete archive of original prompts or a video editing project.

Its escalation levels, shot count, and delayed reveals belong to this particular story. You do not need to reproduce them or use fixed numbers of everyday scenes, clues, or twists when working with the templates.

## File navigation

| Path                                                         | Purpose                                     |
| ------------------------------------------------------------ | ------------------------------------------- |
| [README.md](README.md)                                       | English introduction                        |
| [README_CN.md](README_CN.md)                                 | Chinese introduction and starting points    |
| [templates/](templates/)                                     | Five fillable creation and review templates |
| [examples/suburban_online_romance/](examples/suburban_online_romance/) | Case-study documents and image directory    |
| [LICENSE](LICENSE)                                           | Current license notice                      |

You can add prompt or asset directories to your own project. This navigation lists the main materials currently provided; planned tutorials, scripts, and asset packs are not presented as existing resources.

## Current scope and future work

Available materials include Chinese and English project entry pages, five templates, and the Suburban Online Romance case-study documents. Character, location, and prop records are included in the story bible template and can be copied as needed.

Future work includes:

- A complete walkthrough for first-time users.
- A workflow for discussing options with AI, choosing a direction, and recording revisions.
- Prompt examples with actual reference images and version records.
- Cases in more genres to examine how the templates work across different stories.
- Guidance for editing, release, and organizing audience feedback.

These are future directions, not claims that the corresponding tutorials or tools already exist. The workflow requires creative judgment and review and does not guarantee a particular audience response or reach.

## Contributing

Corrections, template improvements, case studies, and translation suggestions are welcome through repository Issues or Pull Requests.

When reporting a problem, identify the file, shot, or entry and describe the proposed change. For continuity issues, include the relevant image versions and visible evidence, distinguishing a change to the story's definitions from a correction to an image.

When contributing cases or assets, state their source, attribution, and usage permissions. If a character's identity or a world rule is uncertain, establish the basis before recording an interpretation as a confirmed fact.

## License

Unless otherwise stated, the original documentation, templates, and other original textual materials use the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See [LICENSE](LICENSE) for attribution and usage terms.

The existing notice requires appropriate credit, links to the project and license, and an indication of changes. Commercial use requires separate permission. Do not assume that this license for textual materials also grants blanket permission for every image, third-party asset, logo, or referenced work; consult [LICENSE](LICENSE) and any material-specific notices.
