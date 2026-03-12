# Table of Contents

- [AWS Content Design System](#aws-content-design-system) (p.1)
- [Table of Contents](#table-of-contents) (p.3)
- [Overview](#overview) (p.10)
  - [About the CDS](#about-the-cds) (p.10)
- [Usage dictionary](#usage-dictionary) (p.11)
- [AWS style](#aws-style) (p.137)
  - [Accessibility](#accessibility) (p.138)
    - [Accessibility in content](#accessibility-in-content) (p.139)
      - [Color, sounds, and shapes](#color-sounds-and-shapes) (p.139)
      - [Spatial direction (location)](#spatial-direction-location) (p.140)
      - [Device-agnostic verbs](#device-agnostic-verbs) (p.141)
    - [Accessibility in content elements](#accessibility-in-content-elements) (p.141)
      - [Accordions and tabs (collapsible content)](#accordions-and-tabs-collapsible-content) (p.141)
      - [Headings](#headings) (p.142)
      - [Images](#images) (p.142)
      - [Tables](#tables) (p.142)
      - [Links](#links) (p.142)
    - [Accessibility on the console and UI](#accessibility-on-the-console-and-ui) (p.142)
    - [Other resources](#other-resources) (p.142)
  - [Acronyms](#acronyms) (p.143)
    - [When to spell out acronyms](#when-to-spell-out-acronyms) (p.143)
      - [Spell out for clarity](#spell-out-for-clarity) (p.143)
      - [Don't spell out common acronyms](#dont-spell-out-common-acronyms) (p.144)
    - [Plurals](#plurals) (p.147)
    - [Articles an and a](#articles-an-and-a) (p.147)
    - [Headings and titles](#headings-and-titles) (p.148)
    - [AWS service name abbreviations](#aws-service-name-abbreviations) (p.148)
    - [AWS service names in headings](#aws-service-names-in-headings) (p.150)
    - [Latin abbreviations](#latin-abbreviations) (p.150)
    - [Units of measure abbreviations](#units-of-measure-abbreviations) (p.150)
  - [Alerts and messages](#alerts-and-messages) (p.152)
    - [Basic guidelines](#basic-guidelines) (p.153)
    - [Alert types](#alert-types) (p.156)
      - [Information alert](#information-alert) (p.156)
      - [Success alert](#success-alert) (p.157)
      - [Warning alert](#warning-alert) (p.157)
      - [Error alert](#error-alert) (p.158)
    - [Error messages](#error-messages) (p.158)
      - [Anatomy of an error message](#anatomy-of-an-error-message) (p.158)
      - [Guidelines for error messages](#guidelines-for-error-messages) (p.159)
      - [Common errors](#common-errors) (p.160)
        - [Validation errors (user input is missing, incomplete, or incorrect)](#validation-errors-user-input-is-missing-incomplete-or-incorrect) (p.160)
        - [User exceeds a quota or doesn’t meet a quota](#user-exceeds-a-quota-or-doesnt-meet-a-quota) (p.162)
        - [User attempts to perform an unsupported action or operation](#user-attempts-to-perform-an-unsupported-action-or-operation) (p.163)
        - [User doesn’t have permission to perform an action or operation](#user-doesnt-have-permission-to-perform-an-action-or-operation) (p.164)
        - [AWS or the network is experiencing an internal error](#aws-or-the-network-is-experiencing-an-internal-error) (p.165)
      - [Client and server status codes](#client-and-server-status-codes) (p.165)
      - [API and AWS CLI error messages](#api-and-aws-cli-error-messages) (p.167)
        - [Example library](#example-library) (p.167)
  - [Artificial intelligence (AI)](#artificial-intelligence-ai) (p.169)
    - [Best practices](#best-practices) (p.170)
    - [Additional resources](#additional-resources) (p.170)
    - [Checklist for human review of AI-drafted content](#checklist-for-human-review-of-ai-drafted-content) (p.170)
      - [Word use](#word-use) (p.171)
      - [Sentence structure](#sentence-structure) (p.172)
      - [Meaning](#meaning) (p.173)
      - [Accuracy](#accuracy) (p.175)
      - [Transition phrases](#transition-phrases) (p.175)
      - [Document structure and formatting](#document-structure-and-formatting) (p.177)
      - [Prompt remnants](#prompt-remnants) (p.177)
    - [Conversational AI interfaces](#conversational-ai-interfaces) (p.178)
      - [Core principles](#core-principles) (p.178)
      - [Identity guidelines](#identity-guidelines) (p.179)
        - [Professional tone](#professional-tone) (p.179)
        - [Clear boundaries](#clear-boundaries) (p.179)
      - [Response formatting](#response-formatting) (p.180)
      - [Response quality](#response-quality) (p.180)
        - [Information density](#information-density) (p.180)
        - [Response accuracy](#response-accuracy) (p.181)
      - [Managing interactions](#managing-interactions) (p.182)
        - [Customer engagement](#customer-engagement) (p.182)
        - [Handling difficult situations](#handling-difficult-situations) (p.183)
      - [Security and privacy considerations](#security-and-privacy-considerations) (p.183)
    - [Describing chat-based AI](#describing-chat-based-ai) (p.184)
      - [Terminology for chat-based AI experiences](#terminology-for-chat-based-ai-experiences) (p.184)
        - [Pronouns](#pronouns) (p.184)
      - [Describing what AI does](#describing-what-ai-does) (p.184)
  - [Blog posts](#blog-posts) (p.185)
    - [Parts of a blog post](#parts-of-a-blog-post) (p.186)
      - [Title and headings](#title-and-headings) (p.186)
      - [(Optional) guest byline](#optional-guest-byline) (p.187)
      - [Introduction](#introduction) (p.187)
      - [Walkthrough](#walkthrough) (p.187)
        - [Prerequisites](#prerequisites) (p.187)
      - [Cleaning up](#cleaning-up) (p.187)
      - [Conclusion](#conclusion) (p.187)
      - [Author bio](#author-bio) (p.188)
    - [Post types](#post-types) (p.188)
      - [Announcement posts](#announcement-posts) (p.188)
      - [Best practices posts](#best-practices-posts) (p.189)
      - [Curation posts](#curation-posts) (p.189)
      - [Customer posts](#customer-posts) (p.189)
      - [Technical posts](#technical-posts) (p.190)
      - [Thought leadership posts](#thought-leadership-posts) (p.190)
    - [Post learning levels](#post-learning-levels) (p.191)
      - [Foundational (100)](#foundational-100) (p.191)
      - [Intermediate (200)](#intermediate-200) (p.191)
      - [Advanced (300)](#advanced-300) (p.192)
      - [Expert (400)](#expert-400) (p.192)
  - [AWS voice and tone](#aws-voice-and-tone) (p.192)
    - [Voice](#voice) (p.192)
    - [Tone](#tone) (p.193)
      - [Contractions](#contractions) (p.193)
      - [Modal verbs](#modal-verbs) (p.194)
        - [Describing requirements and recommendations](#describing-requirements-and-recommendations) (p.196)
        - [When not to use a modal verb](#when-not-to-use-a-modal-verb) (p.198)
      - [Tone traits](#tone-traits) (p.198)
        - [Approachable](#approachable) (p.198)
        - [Authoritative](#authoritative) (p.199)
        - [Concise](#concise) (p.199)
        - [Conversational](#conversational) (p.199)
        - [Directed](#directed) (p.200)
        - [Respectful](#respectful) (p.200)
        - [Simple](#simple) (p.200)
        - [Smart](#smart) (p.201)
        - [Trustworthy](#trustworthy) (p.201)
    - [Voice and tone examples](#voice-and-tone-examples) (p.202)
      - [General instructional text](#general-instructional-text) (p.202)
      - [Dialog box](#dialog-box) (p.202)
      - [Alerts and notifications](#alerts-and-notifications) (p.203)
      - [Text above a table](#text-above-a-table) (p.203)
      - [Tooltip next to a field](#tooltip-next-to-a-field) (p.203)
      - [Wizard step](#wizard-step) (p.204)
      - [Download instructions](#download-instructions) (p.204)
      - [Error messages](#error-messages) (p.204)
  - [Capitalization](#capitalization) (p.205)
    - [Titles and headings](#titles-and-headings) (p.205)
    - [Service names](#service-names) (p.206)
    - [Feature names](#feature-names) (p.206)
    - [File names and file formats](#file-names-and-file-formats) (p.206)
  - [Consoles and user interfaces](#consoles-and-user-interfaces) (p.206)
    - [UI tenets](#ui-tenets) (p.207)
    - [UI best practices](#ui-best-practices) (p.208)
    - [UI checklist for writers and editors](#ui-checklist-for-writers-and-editors) (p.208)
      - [Are the most important words first?](#are-the-most-important-words-first) (p.208)
      - [Are your headings, links, and button labels self-explanatory?](#are-your-headings-links-and-button-labels-self-explanatory) (p.208)
      - [Do you really need that text at all? Is it in the right place?](#do-you-really-need-that-text-at-all-is-it-in-the-right-place) (p.209)
      - [How much can you cut?](#how-much-can-you-cut) (p.209)
      - [Have you chosen words that your users use every day?](#have-you-chosen-words-that-your-users-use-every-day) (p.209)
      - [Can you break your text into bullets or smaller paragraphs?](#can-you-break-your-text-into-bullets-or-smaller-paragraphs) (p.210)
      - [Are you speaking directly to users in a conversational tone?](#are-you-speaking-directly-to-users-in-a-conversational-tone) (p.210)
      - [Do your word choices make people feel good about using AWS?](#do-your-word-choices-make-people-feel-good-about-using-aws) (p.211)
      - [Will your text work in German, Japanese, Portuguese...?](#will-your-text-work-in-german-japanese-portuguese) (p.211)
      - [Does it communicate clearly?](#does-it-communicate-clearly) (p.211)
    - [Console description](#console-description) (p.212)
      - [Service home page](#service-home-page) (p.212)
      - [Parts of the console](#parts-of-the-console) (p.213)
      - [Navigation bar](#navigation-bar) (p.214)
      - [Navigation pane](#navigation-pane) (p.217)
      - [Content pane](#content-pane) (p.217)
      - [Help panel](#help-panel) (p.220)
      - [Icons](#icons) (p.221)
  - [Global English](#global-english) (p.224)
    - [Syntax guidelines](#syntax-guidelines) (p.224)
      - [Keep sentences short](#keep-sentences-short) (p.225)
      - [Watch for verb-like words that end in "-ing"](#watch-for-verb-like-words-that-end-in--ing) (p.225)
      - [Watch for verb-like words that end in "-ed"](#watch-for-verb-like-words-that-end-in--ed) (p.225)
      - [Keep adjectives and adverbs close to the words that they modify](#keep-adjectives-and-adverbs-close-to-the-words-that-they-modify) (p.226)
      - [Avoid slang, jargon, and colloquialisms](#avoid-slang-jargon-and-colloquialisms) (p.226)
      - [Avoid Latin phrases](#avoid-latin-phrases) (p.226)
      - [Use standard terminology and formats](#use-standard-terminology-and-formats) (p.226)
      - [Use complete sentences](#use-complete-sentences) (p.226)
      - [Use precise words that have only one meaning](#use-precise-words-that-have-only-one-meaning) (p.227)
      - [Use optional clarifying words](#use-optional-clarifying-words) (p.227)
    - [Words that can help clarify](#words-that-can-help-clarify) (p.228)
  - [Images](#images) (p.230)
    - [Topics](#topics) (p.230)
    - [Creating images](#creating-images) (p.230)
    - [Guidelines for images](#guidelines-for-images) (p.231)
    - [Using screenshots](#using-screenshots) (p.231)
    - [Avoiding security issues in images](#avoiding-security-issues-in-images) (p.233)
    - [Legal requirements](#legal-requirements) (p.234)
    - [Regional branding requirements](#regional-branding-requirements) (p.234)
    - [Localization guidelines](#localization-guidelines) (p.234)
    - [Alt text and lead-in content](#alt-text-and-lead-in-content) (p.235)
    - [Lead-in content for images](#lead-in-content-for-images) (p.236)
      - [Referring to an image](#referring-to-an-image) (p.237)
      - [Writing lead-in content for images](#writing-lead-in-content-for-images) (p.237)
        - [Don’t use a screenshot to replace text](#dont-use-a-screenshot-to-replace-text) (p.238)
      - [Describing graphics in lead-in content](#describing-graphics-in-lead-in-content) (p.238)
        - [Lead-in content for conceptual content](#lead-in-content-for-conceptual-content) (p.238)
        - [Lead-in content that summarizes an image](#lead-in-content-that-summarizes-an-image) (p.239)
        - [Including structured information after the image](#including-structured-information-after-the-image) (p.240)
        - [Lead-in content for procedures](#lead-in-content-for-procedures) (p.242)
      - [Checklist for lead-in content](#checklist-for-lead-in-content) (p.242)
  - [Inclusive language](#inclusive-language) (p.243)
    - [Don't use these non-inclusive words and phrases](#dont-use-these-non-inclusive-words-and-phrases) (p.243)
    - [Consider the impact of your language](#consider-the-impact-of-your-language) (p.245)
    - [Inclusive language in API and command names](#inclusive-language-in-api-and-command-names) (p.246)
    - [Additional resources](#additional-resources) (p.246)
  - [Links and cross-references](#links-and-cross-references) (p.246)
    - [General guidelines for links and cross-references](#general-guidelines-for-links-and-cross-references) (p.247)
      - [Formal cross-references](#formal-cross-references) (p.248)
      - [Embedded links](#embedded-links) (p.249)
    - [Specific cross-reference styles guidelines and examples](#specific-cross-reference-styles-guidelines-and-examples) (p.249)
      - [AWS service documentation](#aws-service-documentation) (p.249)
      - [External (not AWS) websites](#external-not-aws-websites) (p.251)
      - [AWS marketing websites](#aws-marketing-websites) (p.252)
      - [Downloads](#downloads) (p.252)
      - [Blogs, whitepapers, and re:Post entries](#blogs-whitepapers-and-repost-entries) (p.253)
    - [Linking to consoles](#linking-to-consoles) (p.254)
    - [Linking to external resources](#linking-to-external-resources) (p.254)
    - [Linking best practices](#linking-best-practices) (p.255)
  - [Lists](#lists) (p.255)
    - [General list guidelines](#general-list-guidelines) (p.256)
      - [Guidelines for list introductions and titles](#guidelines-for-list-introductions-and-titles) (p.256)
    - [Itemized (bulleted) lists](#itemized-bulleted-lists) (p.256)
      - [Guidelines for itemized lists](#guidelines-for-itemized-lists) (p.256)
      - [Example itemized list](#example-itemized-list) (p.257)
    - [Ordered (numbered) lists](#ordered-numbered-lists) (p.257)
      - [Guidelines for ordered lists](#guidelines-for-ordered-lists) (p.257)
      - [Example ordered list](#example-ordered-list) (p.258)
    - [Topic-comment (topcom) lists](#topic-comment-topcom-lists) (p.258)
      - [Guidelines for topic-comment lists](#guidelines-for-topic-comment-lists) (p.258)
      - [Example topic-comment list](#example-topic-comment-list) (p.258)
    - [Variable (termdef) lists](#variable-termdef-lists) (p.259)
      - [Guidelines for variable (termdef) lists](#guidelines-for-variable-termdef-lists) (p.259)
      - [Example variable (termdef) list](#example-variable-termdef-list) (p.259)
    - [Procedures](#procedures) (p.260)
    - [Automatic (topic) lists](#automatic-topic-lists) (p.260)
      - [Automatic (topic) lists guidelines](#automatic-topic-lists-guidelines) (p.261)
      - [Automatic (topic) list examples](#automatic-topic-list-examples) (p.261)
    - [Formal paragraphs](#formal-paragraphs) (p.261)
      - [Guidelines for formal paragraphs](#guidelines-for-formal-paragraphs) (p.261)
  - [Notes and other special messages](#notes-and-other-special-messages) (p.262)
    - [Tip](#tip) (p.262)
    - [Note](#note) (p.262)
    - [Important](#important) (p.263)
    - [Warning](#warning) (p.263)
  - [Numbers](#numbers) (p.264)
    - [Numbers one through nine](#numbers-one-through-nine) (p.264)
    - [Comma separators](#comma-separators) (p.265)
    - [Numbers in tables](#numbers-in-tables) (p.265)
    - [En dashes](#en-dashes) (p.265)
    - [Numbers in measurements](#numbers-in-measurements) (p.266)
    - [Units of measure](#units-of-measure) (p.266)
      - [Capitalization in units of measure](#capitalization-in-units-of-measure) (p.267)
      - [Numbers in units of measure](#numbers-in-units-of-measure) (p.267)
    - [Dates and time](#dates-and-time) (p.267)
      - [Date formatting](#date-formatting) (p.268)
      - [Date ranges](#date-ranges) (p.269)
      - [Time formatting](#time-formatting) (p.269)
      - [Time ranges](#time-ranges) (p.270)
    - [Currency](#currency) (p.270)
      - [Referring to currency](#referring-to-currency) (p.271)
      - [Currency names](#currency-names) (p.272)
      - [Referring to specific monetary amounts](#referring-to-specific-monetary-amounts) (p.273)
      - [Currency ranges](#currency-ranges) (p.274)
      - [Billing and pricing](#billing-and-pricing) (p.274)
  - [Parallel information](#parallel-information) (p.275)
    - [Parallel steps in procedures](#parallel-steps-in-procedures) (p.275)
    - [Handling task flows for different languages](#handling-task-flows-for-different-languages) (p.276)
    - [Filtering content in documentation](#filtering-content-in-documentation) (p.278)
      - [Best practices](#best-practices) (p.278)
      - [Tabs](#tabs) (p.278)
      - [Accordions](#accordions) (p.280)
        - [To turn off automated backups immediately (console)](#to-turn-off-automated-backups-immediately-console) (p.281)
        - [To turn off automated backups immediately (AWS CLI)](#to-turn-off-automated-backups-immediately-aws-cli) (p.281)
        - [To turn off automated backups immediately (RDS API)](#to-turn-off-automated-backups-immediately-rds-api) (p.282)
  - [Plural and singular nouns](#plural-and-singular-nouns) (p.282)
  - [Prepositions](#prepositions) (p.283)
    - [In, on](#in-on) (p.283)
  - [Procedures](#procedures) (p.284)
    - [Parts of a procedure section](#parts-of-a-procedure-section) (p.285)
      - [Section title](#section-title) (p.285)
      - [Procedure introduction](#procedure-introduction) (p.286)
      - [Procedure title](#procedure-title) (p.286)
      - [Steps](#steps) (p.287)
      - [(Optional) Screenshots](#optional-screenshots) (p.287)
      - [(Optional) Notes](#optional-notes) (p.288)
    - [Procedure phrasing](#procedure-phrasing) (p.288)
    - [Example procedure from Amazon EC2](#example-procedure-from-amazon-ec2) (p.291)
  - [Punctuation](#punctuation) (p.292)
    - [Topics](#topics) (p.292)
    - [ampersand (&)](#ampersand) (p.293)
    - [apostrophe (')](#apostrophe) (p.293)
    - [backslash (\)](#backslash) (p.294)
    - [colon (:)](#colon) (p.294)
    - [comma (,)](#comma) (p.294)
    - [dash](#dash) (p.295)
    - [ellipsis (...)](#ellipsis) (p.295)
    - [em dash (—)](#em-dash) (p.295)
    - [en dash (–)](#en-dash) (p.296)
    - [exclamation point (!)](#exclamation-point) (p.296)
    - [forward slash (/)](#forward-slash) (p.296)
    - [hyphen (‐)](#hyphen) (p.297)
    - [parentheses ( )](#parentheses) (p.300)
    - [period (.)](#period) (p.300)
    - [question mark (?)](#question-mark) (p.300)
    - [quotation marks (' ' and " ")](#quotation-marks-and) (p.300)
    - [semicolon (;)](#semicolon) (p.301)
    - [Hyphenation](#hyphenation) (p.302)
  - [Search engine optimization](#search-engine-optimization) (p.305)
    - [Best practices](#best-practices) (p.306)
    - [On-page SEO](#on-page-seo) (p.306)
      - [Best practices](#best-practices) (p.306)
    - [Titles](#titles) (p.306)
      - [Best practices](#best-practices) (p.307)
    - [URLs](#urls) (p.307)
      - [Best practices](#best-practices) (p.307)
    - [Meta descriptions](#meta-descriptions) (p.308)
      - [Best practices](#best-practices) (p.308)
    - [Abstracts](#abstracts) (p.309)
    - [More resources](#more-resources) (p.309)
  - [Tables](#tables) (p.309)
    - [Consider accessibility when creating tables](#consider-accessibility-when-creating-tables) (p.311)
    - [Lead-in sentences](#lead-in-sentences) (p.311)
    - [Table examples](#table-examples) (p.312)
      - [Example 1: Use tables to compare data](#example-1-use-tables-to-compare-data) (p.312)
      - [Example 2: Don't use tables for lists](#example-2-dont-use-tables-for-lists) (p.312)
      - [Example 3: Don't use tables for styling](#example-3-dont-use-tables-for-styling) (p.313)
      - [Example 4: Include text in every header cell](#example-4-include-text-in-every-header-cell) (p.313)
    - [Images and icons in tables](#images-and-icons-in-tables) (p.314)
      - [Inline icons in a table](#inline-icons-in-a-table) (p.315)
      - [Images in table cells (not inline)](#images-in-table-cells-not-inline) (p.315)
    - [Checking tables for rendering issues](#checking-tables-for-rendering-issues) (p.316)
  - [Titles and headings](#titles-and-headings) (p.317)
    - [Title styles](#title-styles) (p.318)
    - [Optimizing titles for SEO](#optimizing-titles-for-seo) (p.318)
    - [Using separate topic and TOC titles](#using-separate-topic-and-toc-titles) (p.319)
  - [Writing basics](#writing-basics) (p.320)
    - [Break up sentences and paragraphs](#break-up-sentences-and-paragraphs) (p.320)
    - [Tighten your prose](#tighten-your-prose) (p.321)
    - [Avoid nominalizations](#avoid-nominalizations) (p.322)
    - [Use lists to break up text](#use-lists-to-break-up-text) (p.322)
    - [Use active voice and strong verbs](#use-active-voice-and-strong-verbs) (p.323)
    - [Write for a global audience](#write-for-a-global-audience) (p.324)
    - [Write a good introductory paragraph](#write-a-good-introductory-paragraph) (p.324)
    - [Document the user's task, not the feature](#document-the-users-task-not-the-feature) (p.325)
    - [In a sentence, put the goal first and then the task](#in-a-sentence-put-the-goal-first-and-then-the-task) (p.325)
    - [Avoid jargon](#avoid-jargon) (p.326)
    - [Avoid Latinisms](#avoid-latinisms) (p.326)
      - [Exceptions](#exceptions) (p.328)
    - [Use customer-centric language](#use-customer-centric-language) (p.328)
    - [Apply correct procedure style](#apply-correct-procedure-style) (p.329)
  - [Other resources](#other-resources) (p.330)
    - [Amazon references](#amazon-references) (p.330)
    - [Other references](#other-references) (p.330)
- [Content patterns](#content-patterns) (p.331)
  - [Code example patterns](#code-example-patterns) (p.331)
    - [Code example pattern](#code-example-pattern) (p.331)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Code snippet pattern](#code-snippet-pattern) (p.334)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [IAM example policy pattern](#iam-example-policy-pattern) (p.335)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
  - [Conceptual patterns](#conceptual-patterns) (p.337)
    - [Basic concept pattern](#basic-concept-pattern) (p.338)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Best practices pattern](#best-practices-pattern) (p.341)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
        - [Conditional components](#conditional-components) (p.342)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Decision guide pattern](#decision-guide-pattern) (p.343)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Security and compliance pattern](#security-and-compliance-pattern) (p.346)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Service and feature overview pattern](#service-and-feature-overview-pattern) (p.348)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
  - [Reference patterns](#reference-patterns) (p.350)
    - [CLI command pattern](#cli-command-pattern) (p.350)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [CloudFormation resource reference pattern](#cloudformation-resource-reference-pattern) (p.352)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Recommended components](#recommended-components) (p.353)
        - [Conditional components](#conditional-components) (p.342)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Deprecation notice pattern](#deprecation-notice-pattern) (p.355)
      - [Deprecation stages](#deprecation-stages) (p.356)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Recommended components](#recommended-components) (p.353)
        - [Conditional components](#conditional-components) (p.342)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
  - [Task-based patterns](#task-based-patterns) (p.358)
    - [Getting started pattern](#getting-started-pattern) (p.359)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
        - [Conditional components](#conditional-components) (p.342)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Procedure pattern](#procedure-pattern) (p.361)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Troubleshooting pattern](#troubleshooting-pattern) (p.363)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
    - [Tutorial pattern](#tutorial-pattern) (p.365)
      - [Usage](#usage) (p.365)
      - [Structure](#structure) (p.332)
        - [Required components](#required-components) (p.332)
        - [Recommended components](#recommended-components) (p.353)
        - [Optional components](#optional-components) (p.332)
      - [Guidelines](#guidelines) (p.333)
      - [Examples](#examples) (p.333)
      - [Additional resources](#additional-resources) (p.333)
  - [Content components](#content-components) (p.367)
    - [What's in this section](#whats-in-this-section) (p.367)
    - [Guidelines](#guidelines) (p.333)
    - [Featured resources](#featured-resources) (p.367)
    - [Related Resources](#related-resources) (p.367)
    - [Text components](#text-components) (p.368)
      - [Headings and titles](#headings-and-titles) (p.368)
        - [Overview](#overview) (p.10)
          - [Primary scenarios](#primary-scenarios) (p.368)
        - [Structure](#structure) (p.332)
          - [Required elements](#required-elements) (p.368)
          - [Optional elements](#optional-elements) (p.369)
        - [Features](#features) (p.369)
          - [Title Variants](#title-variants) (p.369)
        - [Guidelines](#guidelines) (p.333)
          - [Do](#do) (p.369)
          - [Don't](#dont) (p.238)
        - [Additional resources](#additional-resources) (p.370)
          - [Related components/patterns](#related-componentspatterns) (p.370)
      - [Lists](#lists) (p.370)
        - [Overview](#overview) (p.10)
        - [Structure](#structure) (p.332)
          - [Required elements](#required-elements) (p.368)
          - [Optional elements](#optional-elements) (p.369)
        - [Features](#features) (p.369)
          - [Itemized (bulleted) lists](#itemized-bulleted-lists) (p.371)
          - [Ordered (numbered) lists](#ordered-numbered-lists) (p.372)
          - [Variable (termdef) lists](#variable-termdef-lists) (p.373)
          - [Automatic (topic) lists](#automatic-topic-lists) (p.374)
          - [Formal paragraphs](#formal-paragraphs) (p.374)
        - [Guidelines](#guidelines) (p.333)
          - [Do](#do) (p.369)
          - [Don't](#dont) (p.238)
        - [Additional resources](#additional-resources) (p.370)
          - [Related components/patterns](#related-componentspatterns) (p.370)
          - [Support channels](#support-channels) (p.375)
      - [Code blocks](#code-blocks) (p.375)
        - [Overview](#overview) (p.376)
        - [Structure](#structure) (p.376)
          - [Required elements](#required-elements) (p.376)
          - [Optional elements](#optional-elements) (p.376)
        - [Features](#features) (p.376)
        - [Guidelines](#guidelines) (p.376)
          - [Do](#do) (p.376)
          - [Don't](#dont) (p.377)
        - [Examples](#examples) (p.377)
        - [Additional resources](#additional-resources) (p.377)
      - [Notes and alerts](#notes-and-alerts) (p.377)
        - [Overview](#overview) (p.377)
        - [Structure](#structure) (p.378)
          - [Required elements](#required-elements) (p.378)
          - [Optional elements](#optional-elements) (p.378)
        - [Features](#features) (p.378)
          - [Tip](#tip) (p.378)
          - [Note](#note) (p.378)
          - [Important](#important) (p.378)
          - [Warning](#warning) (p.379)
        - [Guidelines](#guidelines) (p.379)
          - [Do](#do) (p.379)
          - [Don't](#dont) (p.379)
        - [Examples](#examples) (p.379)
          - [Tip](#tip) (p.379)
          - [Note](#note) (p.380)
          - [Important](#important) (p.380)
          - [Warning](#warning) (p.380)
        - [Additional resources](#additional-resources) (p.380)
      - [Links and cross-references](#links-and-cross-references) (p.380)
        - [Overview](#overview) (p.380)
        - [Structure](#structure) (p.381)
          - [Required elements](#required-elements) (p.381)
          - [Optional elements](#optional-elements) (p.381)
        - [Features](#features) (p.381)
          - [Formal cross-references](#formal-cross-references) (p.381)
          - [Embedded links](#embedded-links) (p.381)
        - [Guidelines](#guidelines) (p.382)
          - [Do](#do) (p.382)
          - [Don't](#dont) (p.382)
        - [Examples](#examples) (p.382)
          - [Formal cross-reference](#formal-cross-reference) (p.382)
          - [Embedded link](#embedded-link) (p.383)
          - [Console link](#console-link) (p.383)
        - [Additional resources](#additional-resources) (p.383)
- [AWS Legal and security guidelines for content](#aws-legal-and-security-guidelines-for-content) (p.384)
  - [Copyrights and trademarks](#copyrights-and-trademarks) (p.384)
  - [Legal requirements for images](#legal-requirements-for-images) (p.385)
  - [Trademark requirements for AWS and service names](#trademark-requirements-for-aws-and-service-names) (p.385)
    - [Trademark requirements for China Regions](#trademark-requirements-for-china-regions) (p.385)
  - [Third-party brand names](#third-party-brand-names) (p.385)
  - [Incorporating third-party content](#incorporating-third-party-content) (p.386)
  - [Specific legal requirements](#specific-legal-requirements) (p.386)
  - [Safeguarding customer information](#safeguarding-customer-information) (p.387)
  - [Writing about security](#writing-about-security) (p.387)
  - [Linking to external resources](#linking-to-external-resources) (p.387)
  - [Security review](#security-review) (p.388)
  - [Fictitious content library](#fictitious-content-library) (p.388)
    - [API operations](#api-operations) (p.388)
    - [ARNs](#arns) (p.389)
    - [ASNs](#asns) (p.389)
    - [Buckets](#buckets) (p.389)
    - [Companies](#companies) (p.392)
    - [Domains](#domains) (p.392)
    - [ACM servers](#acm-servers) (p.393)
    - [Hashes](#hashes) (p.393)
    - [IP addresses](#ip-addresses) (p.394)
    - [People](#people) (p.397)
    - [Phone numbers](#phone-numbers) (p.399)
    - [Products](#products) (p.400)
      - [Generative AI products](#generative-ai-products) (p.400)
    - [AWS Region codes](#aws-region-codes) (p.401)
    - [AWS Region names](#aws-region-names) (p.401)
    - [Resource IDs](#resource-ids) (p.401)
    - [Street addresses](#street-addresses) (p.402)
    - [User credentials](#user-credentials) (p.402)
  - [Names](#names) (p.405)
    - [AWS](#aws) (p.405)
    - [Code names](#code-names) (p.406)
    - [Service names](#service-names) (p.406)
    - [Service features](#service-features) (p.407)
    - [Service resources](#service-resources) (p.407)
    - [Third-party brand names](#third-party-brand-names) (p.408)
  - [Regions and partitions](#regions-and-partitions) (p.408)
    - [Listing Regions in service documentation](#listing-regions-in-service-documentation) (p.411)
    - [Referring to Regions](#referring-to-regions) (p.413)
    - [Referring to partitions](#referring-to-partitions) (p.415)
  - [Security content requirements](#security-content-requirements) (p.415)
  - [Working with third-party content](#working-with-third-party-content) (p.416)
    - [Link to published third-party content](#link-to-published-third-party-content) (p.416)
    - [Use blog, whitepaper, or webpage content published on the AWS website](#use-blog-whitepaper-or-webpage-content-published-on-the-aws-website) (p.417)
    - [Incorporate third-party content into AWS documentation](#incorporate-third-party-content-into-aws-documentation) (p.417)

---


<!-- Page 1 -->

AWS Content Design System
Copyright © 2026 Amazon Web Services, Inc. and/or its aﬃliates. All rights reserved.
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS
conﬁdential information.


<!-- Page 2 -->

AWS Content Design System
AWS Content Design System:
Copyright © 2026 Amazon Web Services, Inc. and/or its aﬃliates. All rights reserved.
Amazon's trademarks and trade dress may not be used in connection with any product or service
that is not Amazon's, in any manner that is likely to cause confusion among customers, or in any
manner that disparages or discredits Amazon. All other trademarks not owned by Amazon are
the property of their respective owners, who may or may not be aﬃliated with, connected to, or
sponsored by Amazon.
This prerelease documentation is conﬁdential and is provided under the terms of your
nondisclosure agreement with Amazon Web Services (AWS) or other agreement governing your
receipt of AWS conﬁdential information.
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 3 -->

AWS Content Design System
Table of Contents
Overview .......................................................................................................................................... 1
About the CDS .............................................................................................................................................. 1
Usage dictionary ................................................................................................................................................ 2
AWS style ..................................................................................................................................... 128
Accessibility ............................................................................................................................................... 129
Accessibility in content ...................................................................................................................... 130
Accessibility in content elements .................................................................................................... 132
Accessibility on the console and UI ................................................................................................ 133
Other resources ................................................................................................................................... 133
Acronyms ................................................................................................................................................... 134
When to spell out acronyms ............................................................................................................ 134
Plurals ................................................................................................................................................... 138
Articles an and a ................................................................................................................................ 138
Headings and titles ............................................................................................................................ 139
AWS service name abbreviations .................................................................................................... 139
AWS service names in headings ...................................................................................................... 141
Latin abbreviations ............................................................................................................................. 141
Units of measure abbreviations ...................................................................................................... 141
Alerts and messages ............................................................................................................................... 143
Basic guidelines ................................................................................................................................... 144
Alert types ........................................................................................................................................... 147
Error messages .................................................................................................................................... 149
Artiﬁcial intelligence (AI) ........................................................................................................................ 160
Best practices ...................................................................................................................................... 161
Additional resources ........................................................................................................................... 161
Checklist for human review of AI-drafted content ...................................................................... 161
Conversational AI interfaces ............................................................................................................. 169
Describing chat-based AI .................................................................................................................. 175
Blog posts .................................................................................................................................................. 176
Parts of a blog post ........................................................................................................................... 177
Post types ............................................................................................................................................. 179
Post learning levels ............................................................................................................................ 182
AWS voice and tone ................................................................................................................................ 183
Voice ...................................................................................................................................................... 183
Tone ....................................................................................................................................................... 184
iii
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 4 -->

AWS Content Design System
Voice and tone examples .................................................................................................................. 193
Capitalization ............................................................................................................................................ 196
Titles and headings ............................................................................................................................ 196
Service names ..................................................................................................................................... 197
Feature names ..................................................................................................................................... 197
File names and ﬁle formats ............................................................................................................. 197
Consoles and user interfaces ................................................................................................................ 197
UI tenets ............................................................................................................................................... 198
UI best practices ................................................................................................................................. 199
UI checklist for writers and editors ................................................................................................ 199
Console description ............................................................................................................................ 203
Global English ........................................................................................................................................... 215
Syntax guidelines ................................................................................................................................ 215
Words that can help clarify .............................................................................................................. 219
Images ........................................................................................................................................................ 221
Topics .................................................................................................................................................... 221
Creating images .................................................................................................................................. 221
Guidelines for images ........................................................................................................................ 222
Using screenshots ............................................................................................................................... 222
Avoiding security issues in images .................................................................................................. 224
Legal requirements ............................................................................................................................ 225
Regional branding requirements ..................................................................................................... 225
Localization guidelines ...................................................................................................................... 225
Alt text and lead-in content ............................................................................................................ 226
Lead-in content for images .............................................................................................................. 227
Inclusive language ................................................................................................................................... 234
Don't use these non-inclusive words and phrases ....................................................................... 234
Consider the impact of your language .......................................................................................... 236
Inclusive language in API and command names .......................................................................... 237
Additional resources ........................................................................................................................... 237
Links and cross-references ..................................................................................................................... 237
General guidelines .............................................................................................................................. 238
Speciﬁc cross-reference styles guidelines and examples ........................................................... 240
Consoles ................................................................................................................................................ 245
External resources .............................................................................................................................. 245
Best practices ...................................................................................................................................... 246
Lists ............................................................................................................................................................. 246
iv
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 5 -->

AWS Content Design System
General list guidelines ....................................................................................................................... 247
Itemized (bulleted) lists ..................................................................................................................... 247
Ordered (numbered) lists .................................................................................................................. 248
Topic-comment (topcom) lists ......................................................................................................... 249
Variable (termdef) lists ...................................................................................................................... 250
Procedures ............................................................................................................................................ 251
Automatic (topic) lists ....................................................................................................................... 251
Formal paragraphs ............................................................................................................................. 252
Notes and other special messages ....................................................................................................... 253
Tip .......................................................................................................................................................... 253
Note ....................................................................................................................................................... 253
Important ............................................................................................................................................. 254
Warning ................................................................................................................................................. 254
Numbers ..................................................................................................................................................... 255
Numbers one through nine .............................................................................................................. 255
Comma separators ............................................................................................................................. 256
Numbers in tables .............................................................................................................................. 256
En dashes ............................................................................................................................................. 256
Numbers in measurements .............................................................................................................. 257
Units of measure ................................................................................................................................ 257
Dates and time .................................................................................................................................... 258
Currency ................................................................................................................................................ 261
Parallel information ................................................................................................................................. 266
Parallel steps in procedures ............................................................................................................. 266
Handling task ﬂows for diﬀerent languages ................................................................................ 267
Filtering content in documentation ................................................................................................ 269
Plural and singular nouns ...................................................................................................................... 273
Prepositions ............................................................................................................................................... 274
In, on ..................................................................................................................................................... 274
Procedures ................................................................................................................................................. 275
Parts of a procedure section ............................................................................................................ 276
Procedure phrasing ............................................................................................................................ 279
Example procedure from Amazon EC2 .......................................................................................... 282
Punctuation ............................................................................................................................................... 283
Topics .................................................................................................................................................... 283
ampersand (&) ..................................................................................................................................... 284
apostrophe (') ...................................................................................................................................... 284
v
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 6 -->

AWS Content Design System
backslash (\) ........................................................................................................................................ 285
colon (:) ................................................................................................................................................. 285
comma (,) ............................................................................................................................................. 285
dash ....................................................................................................................................................... 286
ellipsis (...) ............................................................................................................................................. 286
em dash (—) ........................................................................................................................................ 286
en dash (–) ........................................................................................................................................... 287
exclamation point (!) .......................................................................................................................... 287
forward slash (/) ................................................................................................................................. 287
hyphen (‐) ............................................................................................................................................. 288
parentheses ( ) ..................................................................................................................................... 291
period (.) ............................................................................................................................................... 291
question mark (?) ................................................................................................................................ 291
quotation marks (' ' and " ") ............................................................................................................. 291
semicolon (;) ........................................................................................................................................ 292
Hyphenation ........................................................................................................................................ 293
Search engine optimization ................................................................................................................... 296
Best practices ...................................................................................................................................... 297
On-page SEO ....................................................................................................................................... 297
Titles ...................................................................................................................................................... 297
URLs ....................................................................................................................................................... 298
Meta descriptions ............................................................................................................................... 299
Abstracts ............................................................................................................................................... 300
More resources .................................................................................................................................... 300
Tables .......................................................................................................................................................... 300
Consider accessibility when creating tables .................................................................................. 302
Lead-in sentences ............................................................................................................................... 302
Table examples ................................................................................................................................... 303
Images and icons in tables ............................................................................................................... 305
Checking tables for rendering issues ............................................................................................. 307
Titles and headings ................................................................................................................................. 308
Title styles ............................................................................................................................................ 309
Optimizing titles for SEO ................................................................................................................. 309
Using separate topic and TOC titles ............................................................................................... 310
Writing basics ........................................................................................................................................... 311
Break up sentences and paragraphs .............................................................................................. 311
Tighten your prose ............................................................................................................................. 312
vi
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 7 -->

AWS Content Design System
Avoid nominalizations ....................................................................................................................... 313
Use lists to break up text ................................................................................................................. 313
Use active voice and strong verbs .................................................................................................. 314
Write for a global audience ............................................................................................................. 315
Write a good introductory paragraph ............................................................................................ 315
Document the user's task, not the feature ................................................................................... 316
In a sentence, put the goal ﬁrst and then the task .................................................................... 316
Avoid jargon ......................................................................................................................................... 317
Avoid Latinisms ................................................................................................................................... 317
Use customer-centric language ....................................................................................................... 319
Apply correct procedure style .......................................................................................................... 320
Other resources ........................................................................................................................................ 321
Amazon references ............................................................................................................................. 321
Other references ................................................................................................................................. 321
Content patterns ......................................................................................................................... 322
Code example patterns .......................................................................................................................... 322
Code example ...................................................................................................................................... 322
Code snippet ........................................................................................................................................ 325
IAM example policy ............................................................................................................................ 326
Conceptual patterns ................................................................................................................................ 328
Basic concept ....................................................................................................................................... 329
Best practices ...................................................................................................................................... 332
Decision guide ..................................................................................................................................... 334
Security and compliance ................................................................................................................... 337
Service and feature overview .......................................................................................................... 339
Reference patterns .................................................................................................................................. 341
CLI command ....................................................................................................................................... 341
CloudFormation resource .................................................................................................................. 343
Deprecation notice ............................................................................................................................. 346
Task-based patterns ................................................................................................................................ 349
Getting started .................................................................................................................................... 350
Procedure .............................................................................................................................................. 352
Troubleshooting .................................................................................................................................. 354
Tutorial .................................................................................................................................................. 356
Content components ............................................................................................................................... 358
What's in this section ........................................................................................................................ 358
Guidelines ............................................................................................................................................. 324
vii
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 8 -->

AWS Content Design System
Featured resources ............................................................................................................................. 358
Related Resources ............................................................................................................................... 358
Text components ................................................................................................................................ 359
Legal and security ....................................................................................................................... 375
Copyrights and trademarks ................................................................................................................... 375
Legal requirements for images ............................................................................................................. 376
Trademark requirements for AWS and service names ..................................................................... 376
Trademark requirements for China Regions ................................................................................. 376
Third-party brand names ....................................................................................................................... 376
Incorporating third-party content ........................................................................................................ 377
Speciﬁc legal requirements ................................................................................................................... 377
Safeguarding customer information .................................................................................................... 378
Writing about security ............................................................................................................................ 378
Linking to external resources ................................................................................................................ 378
Security review ......................................................................................................................................... 379
Fictitious content library ........................................................................................................................ 379
API operations ..................................................................................................................................... 379
ARNs ...................................................................................................................................................... 380
ASNs ...................................................................................................................................................... 380
Buckets .................................................................................................................................................. 380
Companies ............................................................................................................................................ 383
Domains ................................................................................................................................................ 383
ACM servers ......................................................................................................................................... 384
Hashes ................................................................................................................................................... 384
IP addresses ......................................................................................................................................... 385
People ................................................................................................................................................... 388
Phone numbers ................................................................................................................................... 390
Products ................................................................................................................................................ 391
AWS Region codes .............................................................................................................................. 392
AWS Region names ............................................................................................................................ 392
Resource IDs ........................................................................................................................................ 392
Street addresses .................................................................................................................................. 393
User credentials .................................................................................................................................. 393
Names ......................................................................................................................................................... 396
AWS ....................................................................................................................................................... 396
Code names ......................................................................................................................................... 397
Service names ..................................................................................................................................... 397
viii
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 9 -->

AWS Content Design System
Service features .................................................................................................................................. 398
Service resources ................................................................................................................................ 398
Third-party brand names .................................................................................................................. 399
Regions and partitions ............................................................................................................................ 399
Listing Regions in service documentation ..................................................................................... 402
Referring to Regions .......................................................................................................................... 404
Referring to partitions ....................................................................................................................... 406
Security content requirements .............................................................................................................. 406
Third-party content ................................................................................................................................. 407
Link to published third-party content ........................................................................................... 407
Use blog, whitepaper, or webpage content published on the AWS website .......................... 408
Incorporate third-party content into AWS documentation ....................................................... 408
ix
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 10 -->

AWS Content Design System
## Overview
Welcome to the AWS Content Design System.
The AWS Content Design System (CDS) covers AWS style and provides guidelines and patterns
for all AWS content. The CDS is for anyone who creates AWS content. AWS content includes blog
posts, conferences and presentations, consoles and user interfaces, service documentation, social
media, videos, What's New posts, whitepapers, tutorials, and more.
About the CDS
Search – Search doesn't work in the CDS. To search on a page, use Ctrl+F. To search the whole CDS,
open the PDF and use Ctrl+F.
Feedback – To submit feedback, complete the CDS Pulse survey or reach out to us in the #ask-cq-
editors Slack channel.
Tools – If you're building content tools and want to use AWS style rules to evaluate, generate, or
govern style compliance, +1 and comment with your use case in the AWS style in tools SIM.
The AWS Content Design System is owned and maintained by the Content Quality (CQ) and Content
Patterns teams.
About the CDS
## 1
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 11 -->

AWS Content Design System
Usage dictionary
This topic lists usage guidance for words and phrases, including spelling, punctuation, and
capitalization that must be observed in Amazon Web Services (AWS) content.
To search for a speciﬁc term, use Ctrl+F, or choose a letter using the A-Z list.

# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
## Numbers (#)
100-continue
Don't use. Use HTTP status code 100 (Continue) instead.
For more information, see Alerts and messages.
## 24/7, 24/7/365
Don't use. Use all day, or every day.
## 3D
Stands for three-dimensional. Don't use 3-D.
Don't spell out. For more information, see Don't spell out common
acronyms.
## A
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
abort
Don't use in reference to human beings. Consider using stop, end, or
cancel instead.
For more information, see Consider the impact of your language in the
Inclusive language topic.
above
Use only for physical space or screen descriptions (for example, the
outlet above the ﬂoor, or the button above the bar pane).
For orientation within a document, use previous, preceding, or earlier.
access
Use in the sense of what you can use rather than who you are
(authentication).
## 2
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 12 -->

AWS Content Design System
access control list
(ACL)
On ﬁrst mention, use access control list (ACL). Thereafter, OK to use ACL.
access key ID
One access key ID is used in combination with a secret access key to form
one AWS access key.
access policy language
Don't use. Use IAM policy language instead.
account
See AWS account.
action
Use operation or API operation instead so that implementation-
neutral content can be used across conceptual, API, CLI, and SDK
guides. OK to use action or action keywords when referring to
the action in a permissions policy statement (for example, the
dynamodb:CreateTable action).
activate, deactivate
Use activate for describing setting up or associating details with an
account. Use deactivate for the opposite action.
For making a feature available or unavailable for an account or device,
use enable. For switching on a speciﬁc setting or mode, use turn on.
AWS style
• After you set up and activate a user account, you can deactivate the
account when it’s no longer active.
• You can activate the Archive Access tier up to 90 days at a time.
• When you enable this feature, only database users with the
rds_password role can manage passwords.
• You might need to deactivate an account while they’re temporarily
away from your company.
Not AWS style
• When you activate this feature, only database users with the
rds_password role can manage passwords.
• You might need to disable an IAM user while they’re temporarily away
from your company.
## 3
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 13 -->

AWS Content Design System
See Also enable, disable and turn on, turn oﬀ.
## Active Directory
Don't abbreviate as AD. However, related features or products can be
abbreviated.
• Active Directory Domain Services (AD DS)
• Active Directory Federation Services (AD FS)
• Active Directory Lightweight Directory Services (AD LDS)
• AWS Managed Microsoft AD
active-active
Don't use active/active.
active-passive
Don't use active/passive.
ad hoc
Avoid if possible. Use one-time instead. If ad hoc is used frequently in
existing documentation, explain the term on ﬁrst mention using also
known as (or another formulation), and then use one-time.
AWS style
• The row marked as 2 is a one-time, or ad hoc, snapshot taken from the
AWS Storage Gateway console.
Not AWS style
• The row marked as 2 is an ad hoc snapshot taken from the AWS
Storage Gateway console.
adapter
Use this spelling instead of adaptor.
additional
authenticated data
(AAD)
On ﬁrst mention, use additional authenticated data (AAD). Thereafter,
OK to use AAD.
address
Use to refer to a physical street address, email, or an IP address. Don't
use to refer to other internet addresses, such as URLs.
administrator-level
credentials
Not synonymous with AWS account root user credentials. All account
root users have administrator permissions, but not all administrators
## 4
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 14 -->

AWS Content Design System
are account root users. Use AWS account root user only if the actual AWS
account root user credentials are required. If the task doesn't require
the actual AWS root user, but can be performed by any user with admin
permissions, then refer to an IAM user with administrator permissions or
administrator-level credentials.
## Advanced Encryption
Standard (AES)
On ﬁrst mention, use Advanced Encryption Standard. Thereafter, OK to
use AES.
adversary
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
aﬀect (n., v.)
Aﬀect as a noun refers to emotion as expressed in face or body
language. Aﬀect as a verb means to inﬂuence.
Don't confuse with eﬀect.
AFT
Don’t use as an abbreviation for AWS Free Tier.
agent
Can refer to a human support agent, an AI assistant, or a component of
the Agents for Amazon Bedrock feature. To avoid confusion, be explicit
on ﬁrst use ("human support agent", "Amazon Bedrock Agent", or "AI
agent"). Thereafter, "agent" (no capitalization) is acceptable unless
further clariﬁcation or distinction is necessary.
AI
Stands for artiﬁcial intelligence.
AI-generated, AI
generated
Hyphenate when used as an adjective. Two words when used as a verb.
Don't spell out AI.
Don’t use generative AI-generated, or AI-gen.
AWS style
• Label AI-generated images.
• This is AI-generated text.
• AI-generated this text based on user documentation.
Not AWS style
• Label generative AI-generative images.
## 5
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 15 -->

AWS Content Design System
• AI-generated this text.
• This is an artiﬁcial intelligence (AI)–generated image.
See Also generative AI.
ain't
Don't use.
For more information, see Contractions.
AJAX
Stands for Asynchronous JavaScript and XML.
alarm
Use exclusively to refer to formal alarming features, such as what
Amazon CloudWatch provides.
## Alexa
On ﬁrst mention, use Amazon Alexa. Thereafter, OK to use Alexa.
algorithm
When describing chat-based AI, algorithms create models. Don't use
interchangeably with model.
For more information, see Describing chat-based AI.
allow, deny
You can use allow and deny in reference to permissions, but not the
customer:
1. It’s OK to use allow to describe granting permissions to complete a
task. Use deny for the opposite action.
AWS style
• You can allow or deny access to resources based on tags.
• You can use an IAM role to allow a trusted principal in a diﬀerent
account to access resources in your account.
• Create a security group that allows inbound traﬃc on port 22 from
a restricted IP address range.
2. Avoid using allow and deny in direct reference to the customer.
Rewrite to focus on what's important from the customer's point of
view.
AWS style
• You can use the object group name to refer to the object group.
## 6
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 16 -->

AWS Content Design System
• After you connect two VPCs, you can route traﬃc between them by
using private IP addresses.
Not AWS style
• The object group name allows you to also refer to the object group.
• A connection between two VPCs allows you to route traﬃc by using
private IP addresses.
See Also enable, disable and let.
allowlist (n., v.)
One word. Use as a noun to describe a list of allowed items. Use as a
verb to describe the addition to or inclusion in a list of allowed items.
Don't use whitelist.
AWS style
• Create an allowlist to deﬁne and manage groups of trusted IP
addresses.
• Amazon WorkDocs site administrators can add IP allowlist settings to
restrict site access to an allowed range of IP addresses.
• We allowlist the Pipeline IDs in your IAM trust policies so others can't
deploy into your accounts.
Not AWS style
• Create an allow list to deﬁne and manage groups of trusted IP
addresses.
• Amazon WorkDocs site administrators can add IP allow-list settings to
restrict site access to an allowed range of IP addresses.
• We allow-list the Pipeline IDs in your IAM trust policies so others can't
deploy into your accounts.
See Also denylist.
AM
Avoid if possible. Use a 24-hour clock where necessary.
## 7
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 17 -->

AWS Content Design System
Note that 12 AM is midnight and 12 PM is noon.
## Amazon Certiﬁcate
Manager (ACM)
certiﬁcate
On ﬁrst mention, use Amazon Certiﬁcate Manager (ACM) certiﬁcate.
Thereafter, OK to use ACM certiﬁcate.
## Amazon Data Lifecycle
## Manager (Amazon
DLM)
A feature of Amazon EBS. On ﬁrst mention, use Amazon Data Lifecycle
Manager. Thereafter, OK to use Amazon DLM.
Don't use DLM.
## Amazon Dedicated
Cloud (ADC) Regions
Don’t use. This isn’t a public term.
For more information, see Regions and partitions.
Amazon EBS–backed
AMI
Use an en dash for Amazon EBS–backed AMI. This is an exception to the
guidance in Service names and Hyphenation.
Amazon EBS–
optimized
Use an en dash for Amazon EBS–optimized. This is an exception to the
guidance in Service names and Hyphenation.
Amazon GameLift
## Realtime Servers
A feature of Amazon GameLift Servers. On ﬁrst mention, use Amazon
GameLift Realtime Servers. Thereafter, OK to use Realtime Servers.
Realtime Servers is the feature, but you can also have a Realtime server
(note the capitalization).
## Amazon Machine
Image (AMI)
On ﬁrst mention, use Amazon Machine Image (AMI). Thereafter, OK to
use AMI.
## Amazon Payments
Balance Transfer (ABT)
On ﬁrst mention, use Amazon Payments Balance Transfer (ABT).
Thereafter, OK to use ABT.
## Amazon Resource
Name (ARN)
On ﬁrst mention, use Amazon Resource Name (ARN). Thereafter, OK to
use ARN.
Amazon S3–backed
AMI
Use an en dash for Amazon S3–backed AMI. This is an exception to the
guidance in Service names and Hyphenation.
## Amazon Web Services
(AWS)
On ﬁrst mention, use Amazon Web Services (AWS). Thereafter, OK to use
AWS. Also OK to use when using Amazon Web Services seems excessive.
## 8
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 18 -->

AWS Content Design System
In AWS documentation, refer to Amazon Web Services, and not Amazon
Web Services, Inc., the incorporated name.
Use Amazon Web Services, Inc. if you must refer to the incorporated
name. Don't use the term Amazon Web Services, LLC because Amazon
Web Services is no longer a limited liability company (as of 10/2012).
Don't use AWS Web Services.
See Also web service.
ampersand (&)
See ampersand (&) in Punctuation.
and/or
Avoid if possible.
answer
When describing chat-based AI, the generative AI assistant provides an
answer or a response. Response is preferred.
For more information, see Describing chat-based AI.
antivirus
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
## Apache
Capitalize. Be speciﬁc when referring to Apache brands, such as Apache
Cassandra and Apache Hadoop. Don't localize.
For more information, see Third-party brand names.
API
Stands for application programming interface. Use to refer to the entire
set of operations, types, inputs, and outputs for a service. Don't use to
refer to speciﬁc operations within a speciﬁc API.
Don't spell out. For more information, see Don't spell out common
acronyms.
AWS style
• You can use the AWS Lambda API to…
• When you make API calls…
Not AWS style
• Use the AddTagsToResource API to create…
## 9
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 19 -->

AWS Content Design System
APN Partner
For more information about using this term, see Messaging Dos and
Don’ts on the AWS Legal Pathﬁnder website.
apostrophe (')
See apostrophe (') in Punctuation.
app or application
Use app for mobile software, application for all other uses, but follow
the service UI where appropriate.
appear, display, and
open
Messages and pop-up boxes appear. Windows, pages, and applications
open. The verb display requires a deﬁnite object. For example: The
system displays the error message.
appendix, appendices
Use appendices as the plural form of appendix, not appendixes.
## Application Load
## Balancer
In most content, on ﬁrst mention, use the full name. On the consoles,
when space is limited (such as dropdown lists), OK to use the ALB
acronym if the context is clear.
application
programming
interface (API)
See API.
application server
Don't abbreviate as app server.
application tier
Don't use Application Tier.
application-server tier,
application tier server,
application-tier server
Don't use. Use application tier or application server instead.
architect
OK as a verb.
armed with
Don't use. In expressions such as armed with this knowledge, replace with
equipped with.
For more information, see Inclusive language.
artiﬁcial general
intelligence (AGI)
On ﬁrst mention, use artiﬁcial general intelligence (AGI). Thereafter, OK
to use AGI.
artiﬁcial intelligence
and machine learning
(AI/ML)
On ﬁrst mention, use artiﬁcial intelligence and machine learning (AI/ML).
Thereafter, OK to use AI/ML.
## 10
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 20 -->

AWS Content Design System
artiﬁcial narrow
intelligence (ANI)
On ﬁrst mention, use artiﬁcial narrow intelligence (ANI). Thereafter, OK
to use ANI.
as
Primarily used as an adverb. Use it in constructions, such as twice as
long, such as, or EBS as opposed to Amazon S3.
Don't use as to mean because. This is frequently ambiguous and slows
the reader down to parse your meaning.
For more information and examples, see Global English.
as well as
Avoid if possible. Replace with in addition to or and as appropriate.
ASCII
Stands for American Standard Code for Information Interchange.
Don't spell out. For more information, see Don't spell out common
acronyms.
ask
When describing chat-based AI, a user asks a question or makes a
request. Request is preferred.
For more information, see Describing chat-based AI.
assistant
When describing chat-based AI, use for AI services (or components of
services) that provide assistance to users through a chat interface.
On ﬁrst mention or for clariﬁcation, use generative AI assistant or AI
assistant.
For more information, see Describing chat-based AI.
assure
Use assure to mean state positively or remove doubt. Don’t use this term
or others to promise or guarantee outcomes from Amazon or AWS.
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
AWS style
• Using AWS CloudTrail, administrators can assure management that
API calls are logged and monitored for security compliance.
## 11
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 21 -->

AWS Content Design System
Not AWS style
• We assure you that your serverless application will always deploy
correctly.
See Also ensure, make sure, be sure and insure.
at this time
Don't use to refer to AWS support of operating systems, software, or
features. Don't use to imply support for something in the future. For
more information about using forward-looking terms, see Messaging
Dos and Don’ts on the AWS Legal Pathﬁnder website.
See also currently and yet.
audio stream
An encoded stream of audio blobs. Audio streams are encoded as either
HTTP/2 or WebSocket data frames.
Two words. Don't hyphenate.
authenticated
encryption
Authenticated encryption uses additional authenticated data (AAD) to
provide conﬁdentiality, data integrity, and authenticity assurances on
encrypted data.
Don't capitalize. Don't hyphenate. Don't abbreviate as AE.
authentication
Don't use as synonymous with authorization or access.
authorization
Don't use as synonymous with authentication.
auto healing
Two words. Don't hyphenate.
## Auto Recovery
Don't use. Instead, write with a focus on the action that occurs (for
example, Your backups are automatically restored).
See Also instance recovery.
## Auto Scaling
Only use title case Auto Scaling when it's part of a uniquely named
feature, product, or service name, or in rare cases, part of an oﬃcial
resource name (for example, Auto Scaling group and Auto Scaling
instances). However, even when using title case Auto Scaling in a feature,
## 12
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 22 -->

AWS Content Design System
product, service, or resource name, don't abbreviate the phrase on
second mention.
Lowercase scaling, auto scaling, and automatic scaling (but not
autoscaling) are the preferred descriptive terms when generically
describing auto scaling functionality.
Don't use hyphenated auto-scaling as a compound modiﬁer. Use scaling
(for example, scaling policy), or scalable (for example, scalable target, or
scalable, load-balanced environment) instead.
For more information, see hyphen (-) in Punctuation.
AWS style
• You can modify your scaling conﬁguration at any time.
• Amazon EC2 Auto Scaling provides automatic scaling of each node.
You can use Amazon EC2 Auto Scaling to…
• Create your Auto Scaling group in the console. After you create your
Auto Scaling group…
Not AWS style
• You can delete your Auto Scaling conﬁguration at any time.
• This template also uses Auto Scaling to scale your application
whenever application demand changes.
• … an autoscaling, load-balanced environment…
• Create your auto-scaling policy.
## Automated Clearing
House (ACH)
On ﬁrst mention, use Automated Clearing House (ACH). Thereafter, OK to
use ACH.
automated machine
learning (AutoML)
On ﬁrst mention, use automated machine learning (AutoML). Thereafter,
OK to use AutoML.
## Autonomous System
Number (ASN)
On ﬁrst mention, use Autonomous System Number (ASN). Thereafter, OK
to use ASN.
## 13
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 23 -->

AWS Content Design System
## Availability Zone
Spell out in most contexts. OK to abbreviate as AZ when using as an
adjective (Single-AZ or Multi-AZ) or when space is limited (console UI).
OK to use AZs or zones sparingly to refer to multiple Availability Zones
after you've already used Availability Zone in the same paragraph.
For Availability Zone ID, spell out in most contexts. OK to abbreviate as
AZ ID after you've already used Availability Zone in the same paragraph
or section. On ﬁrst mention, use Availability Zone ID (AZ ID). In the
console and in diagrams, OK to use AZ ID if space is limited.
AWS style
• For Multi-AZ deployments...
• You must identify the AWS Region and the Availability Zone. You can
identify the actual location of your resources relative to your accounts
by using the Availability Zone ID (AZ ID). An AZ ID is a unique and
consistent identiﬁer.
Not AWS style
• You must identify the AWS Region and the Availability Zone (AZ).
You can identify the actual location of your resources relative to
your accounts by using the AZ ID. An AZ ID is a unique and consistent
identiﬁer.
AWS access portal
Use when referencing the AWS access portal that's available in the
AWS IAM Identity Center (successor to AWS Single Sign-On) console.
Successor to the SSO user portal.
Don't capitalize access portal.
AWS account
On ﬁrst mention, use AWS account. Thereafter, OK to use account.
There's no other kind of account.
AWS account ID
A 12-digit number, such as 012345678901, that uniquely identiﬁes
an AWS account. Don't capitalize account. For a list of ﬁctitious AWS
account IDs, see Fictitious names and numbers.
## 14
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 24 -->

AWS Content Design System
AWS account root user
On ﬁrst mention, use AWS account root user. Thereafter, OK to use root
user.
AWS Billing and Cost
## Management
Capitalize.
AWS CAF
Use to refer to the AWS Cloud Adoption Framework. On ﬁrst mention,
use AWS Cloud Adoption Framework (AWS CAF). Thereafter, OK to use
AWS CAF. Don't use Cloud Adoption Framework (CAF) or CAF.
AWS Cloud
Capitalize only when preceded by AWS.
AWS style
• You can run a virtual server in the AWS Cloud.
• AWS helps you manage cloud resources.
AWS CloudFormation
StackSets
Use as a singular noun to refer to the feature in AWS CloudFormation.
On ﬁrst mention, use AWS CloudFormation StackSets. Thereafter, OK to
use StackSets. To refer to a speciﬁc resource, use stack set.
AWS style
• AWS CloudFormation StackSets extends the capability of stacks. This
section helps you get started with using StackSets.
• AWS CloudFormation StackSets is supported in multiple AWS Regions.
Not AWS style
• AWS CloudFormation Stack Sets extends the capability of stacks. This
section helps you get started with using Stack Sets.
• AWS CloudFormation Stacksets extends the capability of stacks. This
section helps you get started with using Stacksets.
• AWS CloudFormation StackSets are supported in multiple AWS
Regions.
AWS Free Tier
On ﬁrst mention, use AWS Free Tier. Thereafter, OK to use Free Tier.
Don’t abbreviate as AFT.
## 15
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 25 -->

AWS Content Design System
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
AWS generated tag
Use to describe a tag that's created automatically by AWS. Don't use to
describe a user-deﬁned tag that the customer creates. Don't hyphenate
as AWS-generated tag.
AWS style
• These keys are known as AWS generated tags.
Not AWS style
• These keys are known as AWS-generated tags.
• These keys are known as AWS created tags.
• These keys are known as AWS managed tags.
AWS Global
## Infrastructure,
AWS Global Cloud
## Infrastructure
Capitalize AWS Global Infrastructure and AWS Global Cloud
Infrastructure. Variations must be lowercase.
AWS style
• The AWS Global Infrastructure is built for performance.
• AWS is responsible for protecting the global infrastructure that runs
all of the AWS Cloud.
Not AWS style
• The AWS global infrastructure is built for performance.
• AWS is responsible for protecting the global Infrastructure that runs
all of the AWS Cloud.
See also AWS infrastructure.
AWS GovCloud (US)
## Regions
To refer to the AWS GovCloud (US-East) and AWS GovCloud (US-West)
Regions collectively, use AWS GovCloud (US) Regions.
See Region.
## 16
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 26 -->

AWS Content Design System
AWS infrastructure
On ﬁrst mention, use AWS infrastructure. Thereafter, OK to use
infrastructure without AWS.
AWS style
• With CloudTrail, you can log, continuously monitor, and retain account
activity related to actions across your AWS infrastructure.
Not AWS style
• With CloudTrail, you can log, continuously monitor, and retain account
activity related to actions across your AWS Infrastructure.
See also AWS Global Infrastructure, AWS Global Cloud Infrastructure.
AWS Local Region
A single data center that's designed to complement an existing AWS
Region. Don't use to refer to the closest Region by distance. Use closest
geographical Region instead.
See Region.
AWS managed key
An AWS KMS key that an AWS service manages or creates.
Don't hyphenate. For more information, see hyphen (-)in Punctuation.
AWS Managed
Microsoft AD
A feature of AWS Directory Service.
AWS managed policy
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
AWS Managed Rules
Don't abbreviate to AMR.
AWS Management
Console, console
Title case for the main console, lowercase for service consoles.
AWS style
• Sign in to the AWS Management Console and open the Amazon EC2
console at https://console.aws.amazon.com/ec2/.
AWS Marketplace
## Channel Partner
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
## 17
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 27 -->

AWS Content Design System
AWS Organizations
Use AWS Organizations for the service name. Also note the plural. Use
organization for the resource. Avoid AWS Organizations organization.
AWS style
• You can use the AWS Organizations console to centrally view and
manage all of your accounts within your organization.
See Also organization.
AWS Partner
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
AWS Partner Central
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
AWS Partner Network
Use AWS Partner to describe participants in the AWS Partner Network.
Don't use the term APN Partner.
When describing the relationship between AWS and a partner, use
collaboration, in cooperation with, and working with, or similar terms.
Don't use partnering or partnership.
See also AWS Partner, APN Partner.
AWS style
• AWS Partner
• AWS Select Computing Partner
• With AnyCompany, in cooperation with AWS, you can integrate their
software with your AWS services.
Not AWS style
• APN Partner
• APN Select Computing Partner
• With AnyCompany, in partnership with AWS, you can integrate their
software with your AWS services.
AWS Policy Generator
A tool in IAM for creating custom policies without using the console.
## 18
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 28 -->

AWS Content Design System
AWS Policy Validator
A tool in IAM for checking policy adherence to the IAM policy language
(known internally as Aspen).
AWS products
See web services.
AWS resources
An AWS resource is an entity that you can use on AWS to manage your
cloud operations. Compute instances, database tables, encryption keys,
and cloud storage units are general examples of AWS resources.
An AWS resource name is often preﬁxed with the AWS service that
manages that resource. For example, a cloud storage resource that’s
managed by Amazon S3 is called an S3 bucket. For a list of resources
associated with each service, see AWS oﬀering names.
In general, use the full service name with a resource if it’s the ﬁrst use
of the service name. On subsequent mentions, use either the short
service name with the resource or the resource name alone, as shown
in AWS oﬀering names. Some resources use the extra-short version of
the service name as a preﬁx. For example, you refer to an S3 bucket (not
an Amazon S3 bucket) after the ﬁrst, full reference to the Amazon S3
service, although S3 isn't the oﬃcial abbreviation for Amazon S3.
Be careful to distinguish between resources and services. For example, a
virtual private cloud (VPC) is a virtual network where you can launch AWS
services. A VPC is managed by the Amazon Virtual Private Cloud (Amazon
VPC) service. The resource name isn’t capitalized or branded, but the
service name is.
AWS style
• To upload your data to Amazon S3, you must ﬁrst create an S3 bucket
in one of the AWS Regions.
• You can create an Amazon Elastic Block Store (Amazon EBS) volume
and attach it to a running instance. (First mention of Amazon EBS)
• You can attach an EBS volume to an instance in the same Availability
Zone. (Subsequent mention of Amazon EBS)
Not AWS style
## 19
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 29 -->

AWS Content Design System
• To upload your data to Amazon S3, you must ﬁrst create an Amazon
S3 bucket in an AWS Region.
Here are some examples of AWS resources:
• CloudFormation stack
• EBS volume
• EC2 instance
• ECS container instance
• EMR cluster
• KMS key
• ML model
• RDS DB instance
• S3 bucket
• SNS topic
• SQS queue
• virtual private cloud (VPC)
For additional resource names, see AWS oﬀering names.
For more information about referring to buckets in Amazon Simple
Storage Service, see S3 bucket.
AWS Support
Use instead of Premium Support or Customer Support. Levels of support
are based on the customer's support plan (not support level or support
tier):
• the Basic Support plan
• the Developer Support plan
• the Business Support plan
• the Enterprise Support plan
AWS style
## 20
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 30 -->

AWS Content Design System
• AWS Business Support requires a monthly fee and provides general
guidance with AWS technologies.
Not AWS style
• The Basic support plan from AWS Support is free to all customers and
limited to help with accounts, billing, and service quota increases.
AWS technical
publication names
The oﬃcial names of our guides are always initial-capped. In generic
references, use all lowercase.
AWS style
• The Amazon Inﬁnidash Getting Started Guide is available at... The
getting started guide contains information about...
• The following information is covered in the Amazon Inﬁnidash
Developer Guide. The developer guide also contains...
AWS web services
See web services.
## B
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
back up and restore
Back up is two words when used as a verb. Don’t hyphenate.
backend (adj., n.)
Use backend as an adjective and a noun. Don't use back end or back-end.
Don't make backend possessive except as part of a compound noun, such
as backend system.
See also frontend.
AWS style
• backend conﬁguration
• database backend
• Review the backend router’s load balancing settings before you
continue.
## 21
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 31 -->

AWS Content Design System
Not AWS style
• back end conﬁguration
• database back-end
• Review the backend’s load balancing settings before you continue.
backslash (\)
See backslash (\) in Punctuation.
backup (n.), back up
(v.)
Use backup (one word) as a noun. Use back up (two words) as a verb.
backward compatible
(adv.), backward-
compatible (adj.)
Not backwards.
For more information, see hyphen (-) in Punctuation.
bad actor
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
Base64 (n.), Base64-
encoded (adj.), Base64
encoding (n.)
Use Base64 as a standalone noun. Use Base64-encoded as an adjective
(for example, a Base64-encoded integer).
Base64 encoding is used as a noun and is never hyphenated.
For more information, see hyphen (-) in Punctuation.
BASIC
Stands for Beginner's All-Purpose Symbolic Instruction Code.
Don't spell out. For more information, see Don't spell out common
acronyms.
bastion host, bastion
server
Use bastion host.
be able to
Avoid. Use can instead of will be able to.
For more examples, see Tighten your prose.
below
Use only for physical space or screen descriptions, such as "the outlet
below the vent," or "the button below the bar pane."
For orientation within a document, use following or later.
## 22
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 32 -->

AWS Content Design System
below the fold
Don't use.
For more information, see Writing basics.
best
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
Exception: Best practices is OK to use.
best-in-class
Don't use.
For more information, see Writing basics.
best-of-breed
Don't use.
For more information, see Writing basics.
beta
A service release where the service isn't immediately ready for large
numbers of customers or is missing key features. Customer disclosure is
under a non-disclosure agreement (NDA) and access is gated.
For more information, see New Services Release Types.
big data
Don't capitalize.
bit (b)
For more information, see Units of measure and Units of measure
abbreviations.
bit rate
Two words.
bitmap
Refers to the BMP ﬁle format. Don't use. Use BMP instead.
bits per second (bps)
Don't use b/second or b/s.
For more information, see Units of measure and Units of measure
abbreviations.
black
Use caution when using terms that contain black.
• Don't use blacklist (use deny list instead), black day (use blocked day),
and black hat and their white counterparts. These term pairs are
inappropriate because they have the racist implication of "white is
good, and black is bad." For more information, see Inclusive language.
## 23
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 33 -->

AWS Content Design System
• Avoid terms such as blackout (use service outage or blocked instead)
and black-box testing (use behavioral testing) where possible.
For more information, see Writing basics.
See Also white.
blacklist, blacklisting
Don't use. To describe a list of items that aren't allowed (blocked), use
denylist or a service-appropriate description.
For more information, see Inclusive language.
blast radius
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
blog
Short for weblog. Use when referring to a website of entries or articles.
Use blog post when referring to an individual entry or article on the
website.
See Also blog post.
blog post
Use when referring to an individual entry or article on a blog. Don't use
blog to refer to a speciﬁc blog post.
See Also blog.
## Blox
A collection of open-source projects for container management and
orchestration on Amazon ECS.
blue/green
deployment
A blue/green deployment is a deployment strategy in which you create
two separate, but identical environments. Always use a forward slash (/)
in blue/green. Don't hyphenate.
bold
Use only as an adjective, such as "The characters in bold type indicate..."
Don't use boldface.
bookmark
Preferred term for a saved link. Don't use favorite.
## Boolean
Valid Boolean values are typically true and false. Avoid using the
name of a Boolean value at the beginning of a sentence or sentence
fragment. In general, capitalize the word Boolean, unless it refers to a
speciﬁc code element or value that uses the lowercase form. For speciﬁc
programming languages, follow the usage in that language.
## 24
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 34 -->

AWS Content Design System
AWS style
• You can use the Boolean functions with Boolean expressions or integer
expressions.
• IsTruncated(): A Boolean value that speciﬁes whether the resolved
target list is truncated.
## Border Gateway
Protocol (BGP)
On ﬁrst mention, use Border Gateway Protocol (BGP). Thereafter, OK to
use BGP.
bot
Don't use when describing chat-based AI. Instead, use assistant, model,
or AI.
For more information, see Describing chat-based AI.
## Boto3
The AWS SDK for Python. One word. Capitalize.
bottom
Use only as a general screen reference, such as "scroll to the bottom of
the page." Don't use for window, page, or pane references to features or
controls. Use lower instead (for example, Choose the button on the lower
left).
box
Use for any kind of box or entry ﬁeld in the UI.
breach
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
bring your own license
(BYOL)
Use to refer to an Amazon licensing model where customers provide
their own licenses for software provided by AWS and running on AWS
resources, such as Oracle on Amazon Relational Database Service. OK to
use BYOL on subsequent mentions.
To refer to speciﬁc third-party licensing programs, follow the naming
conventions of the third parties (for example, License Mobility through
Software Assurance).
See also license included model (LI).
bring your own
subscription (BYOS)
Use to refer to an Amazon subscription model where customers provide
their own subscription for software provided by AWS and running on
## 25
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 35 -->

AWS Content Design System
AWS resources, such as Red Hat OpenShift Service on AWS. OK to use
BYOS on subsequent mentions.
To refer to speciﬁc third-party licensing programs, follow the naming
conventions of the third parties (for example,  Red Hat Cloud Access.
browse
Use when referring to scanning information or browsing the web. Don't
use when describing how to navigate to a particular item on our site or a
computer. Use see or navigate to instead.
AWS style
• Navigate to the AWS Management Console.
Not AWS style
• Browse to the Amazon EC2 landing page.
bucket
See S3 bucket.
build (n., v.)
Use as a verb to refer to compiling and linking code. Use as a noun only
to refer to a compiled version of a program (for example, Use the current
build of Amazon Linux 2...) in a programming reference.
by using, that use,
using
To avoid ambiguity, use by using or that use instead of using. If it doesn’t
create ambiguity, it’s OK to use using.
If you’re not sure if using is creating ambiguity, consider this example.
If you write The client launches a new instance using the speciﬁed back-
oﬀ interval, the customer might not know whether the client or the
instance is using the speciﬁed back-oﬀ interval. However, if you precede
using with by like this—The client launches a new instance by using the
speciﬁed back-oﬀ interval—it’s clear that it’s the client that’s using the
speciﬁed back-oﬀ interval.
AWS style
• You can connect to a session for a given ledger by using default
settings.
## 26
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 36 -->

AWS Content Design System
• By using this software, you agree to its terms.
• Before using the integrated development environment (IDE), run a
brazil-build command in your workspace.
• This class counts the number of live test objects that use this ﬁxture.
Not AWS style
• You can connect to a session for a given ledger using default settings.
• Using this software, you agree to its terms.
• This class counts the number of live test objects using this ﬁxture.
See Also via, using.
byte (B)
For more information, see Units of measure and Units of measure
abbreviations.
bytes per second (Bps)
For more information, see Units of measure and Units of measure
abbreviations.
## C
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
cache
Diﬀerentiate between cache and disk cache.
• Use cache to refer to a special memory subsystem where data values
are duplicated for quick access.
• Use disk cache to refer to a portion of RAM that temporarily stores
information read from a disk.
cached volume
Don't use gateway-cached.
callout
A graphical device to point out, or call out, something in a graphic or
sample for the reader.
## 27
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 37 -->

AWS Content Design System
can
Use to express capability.
See Also may and might.
can't, cannot, can not
For a friendly, conversational tone, use can't.
AWS style
• Other users can't alias their AMIs.
• The .zip ﬁle that AWS CloudFormation generates can't exceed 4MB.
Not AWS style
• Other users cannot alias their AMIs.
• The .zip ﬁle that AWS CloudFormation generates can not exceed 4MB.
For more information, see Contractions.
cancel, canceled,
canceling
The spelling with two ls is British in origin and, although a recognized
alternative, is nonstandard for American English.
Exception: cancellation is correct.
## Canonical Name
Record (CNAME)
On ﬁrst mention, use Canonical Name Record (CNAME). Thereafter, OK to
use CNAME.
capex
Don't use. Also, don't use capital expenditure or capital expense. Use ﬁxed
costs, upfront costs, and hardware purchases instead.
AWS style
• In addition to being able to shift from a ﬁxed costs model to a variable
costs model, AWS Ground Station provides the ability to collect fresh
data more quickly.
Not AWS style
• In addition to being able to shift from a capex (capital expense) to
opex (operating expense) model, AWS Ground Station provides the
ability to collect fresh data more quickly.
## 28
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 38 -->

AWS Content Design System
See Also opex.
capitalization
Use lowercase for technical terms that are not proper nouns. For
example, including resource names such as EC2 instance and DynamoDB
table. Use title case for service names and other proper nouns. Use
sentence case for titles, headings, and subheadings. In console UI, art
captions and callouts, or presentations, use sentence capitalization.
For existing features, tools, and resources, follow precedent. For
new features, tools, and resources, use lowercase in most instances.
Exceptions can be made for the following reasons: to establish a
trademark or respect an established trademark, to distinguish a feature
from an existing general technology, or to follow industry capitalization
standards. Review any proposed change in capitalization with the
product team and Legal.
See Also AWS oﬀering names.
Cascading, cascading
Title case for the open source Java library.
case sensitive (n.),
case-sensitive (adj.)
Use case sensitive as a noun (for example, Your password is case
sensitive). Use case-sensitive as an adjective (You can perform a case-
sensitive search from the console...).
For more information, see hyphen (-) in Punctuation.
## Cassandra
Full name is Apache Cassandra. Capitalize. Don't localize.
For more information, see Third-party brand names.
central processing unit
(CPU)
See CPU.
certiﬁcate authority
(CA)
On ﬁrst mention, use certiﬁcate authority (CA). Thereafter, OK to use CA.
certs, certiﬁcates
Use certiﬁcates on ﬁrst mention. It's OK to use certs thereafter.
CGW
See customer gateway.
## 29
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 39 -->

AWS Content Design System
chat (n., v.)
When describing chat-based AI, use as a verb to describe how a user can
chat with a generative AI assistant. Use as a noun to describe how a user
can enter information into the chat.
For more information, see Describing chat-based AI.
See Also session.
chat room
Two words. Don't hyphenate.
chat-based AI
Hyphenate chat-based. Use to describe artiﬁcial intelligence that
communicates with users through a text or audio interface. Can be used
interchangeably with conversational AI.
For more information, see Describing chat-based AI.
chatbot
One word. When describing chat-based AI, use assistant, model, or AI
instead.
For more information, see Describing chat-based AI.
checkbox
One word. A checkbox has three states: unchecked (usually by default),
selected, and cleared.
AWS style
• The default state of the checkbox is unchecked.
• Select the checkbox next to the pipeline name.
• Clear the checkbox and choose Save.
• Conﬁrm that you cleared the checkbox.
Not AWS style
• The checkbox is unselected by default.
• Mark the check box next to the pipeline name.
• Deselect the checkbox and choose Save.
• Uncheck the checkbox.
## China Regions
To refer to the China (Beijing) and China (Ningxia) Regions collectively,
use China Regions.
## 30
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 40 -->

AWS Content Design System
See Region.
CI/CD
Stands for continuous integration and continuous delivery or continuous
integration and continuous deployment. On ﬁrst mention, use continuous
integration and continuous delivery (CI/CD) or continuous integration and
delivery (CI/CD).
For information about the diﬀerence between continuous delivery and
continuous deployment, see What is Continuous Delivery on the DevOps
page.
CIDR block
A CIDR block is a collection of IP addresses that share the same network
preﬁx and number of bits. Don't spell out CIDR.
ciphertext
One word. Information that started as plaintext and is now unreadable
after being passed through a cipher, which is also known as an
encryption algorithm. If ciphertext is decrypted, it becomes plaintext.
See Also plaintext and cleartext.
## Classic Load Balancer
(CLB)
In most content, use the full name. On the consoles, when space is
limited (such as dropdown lists), it’s OK to use CLB if the context is clear.
## Classless Inter-Domain
Routing (CIDR)
On ﬁrst mention, use Classless Inter-Domain Routing (CIDR). Thereafter,
OK to use CIDR.
cleartext
One word. Information that is stored or sent in an unencrypted form,
with no expectation of being encrypted at any point. Cleartext is not
the same as plaintext, which is unencrypted text that is expected to be
encrypted during transmission, storage, or both.
See Also plaintext and ciphertext.
cloud applications
Use when referring to external cloud applications, such as Salesforce,
Box, and Microsoft 365.
Don't use to refer to AWS enterprise applications, such as Amazon
SageMaker or AWS IoT SiteWise.
See also Identity Center enabled applications.
cloud function
Don't use to mean Lambda function.
## 31
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 41 -->

AWS Content Design System
cloud native (n.),
cloud-native (adj.)
Avoid if possible. Depending on your use case, alternatives might include
built for the cloud, originating from the cloud, cloud-centered, or cloud-
focused.
For more information, see hyphen (-) in Punctuation.
cloud platform
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
CloudHub
A feature of Amazon Virtual Private Cloud (Amazon VPC). Don't use. Use
AWS VPN CloudHub instead.
Note capitalization.
## Co-Branded User
Interface (CBUI)
On ﬁrst mention, use Co-Branded User Interface (CBUI). Thereafter, OK to
use CBUI.
code base
Two words.
code example
Use to describe a complete code example that can be compiled.
code sample
A small portion of code. Don't use when referencing the automated
Code examples chapters, linking to the Code Examples Library, or the
aws-doc-sdk-examples repository. Use code example instead.
OK to use when linking directly to the AWS Samples repository or if
you're using a portion of real code.
See Also code example.
code snippet
Use to describe an illustrative fragment of code.
collaborator
Don't use when describing chat-based AI. Instead use assistant, model,
or AI.
For more information, see Describing chat-based AI.
colocate, colocated
Don't use colo except in reference to the cloud computing company of
that name.
Don't use collocate or collocated.
colon (:)
See colon (:) in Punctuation.
## 32
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 42 -->

AWS Content Design System
coming soon
Don't use to imply support for something in the future. For more
information about using forward-looking terms, see Messaging Dos and
Don’ts on the AWS Legal Pathﬁnder website.
comma (,)
See comma (,) in Punctuation.
command line
interface (CLI)
Use to describe the set of commands associated with a service. On ﬁrst
mention, use command line interface (CLI). Thereafter, OK to use CLI.
Don't use as a synonym for command line tools.
command line tools
Use to describe any utilities or tools that come packaged with a service.
Don't use as a synonym for command line interface.
commercial Region
Use to refer to an AWS Region that isn't part of AWS GovCloud (US), the
China Regions, or the Secret and Top Secret Regions. On ﬁrst reference
to commercial Region or commercial AWS Region, link to the Region
entry in the AWS Glossary, which deﬁnes the various types of Regions.
See Region.
companion
Don't use when describing chat-based AI. Instead use assistant, model,
or AI.
For more information, see Describing chat-based AI.
complete
Use only as a transitive verb. You can also recast the sentence to avoid
intransitive usage.
AWS style
• When the update is complete, ....
• After a successful update, ....
Not AWS style
• When the update completes, ...
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## 33
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 43 -->

AWS Content Design System
compromise
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
condition keys
Two words. Don't capitalize.
console
See AWS Management Console.
## Consolidated Billing,
consolidated billing
Capitalize when referring to the former feature previously found in AWS
Billing and Cost Management service. Lowercase in reference to the new
feature in AWS Organizations.
continuous
Avoid when describing AWS services and solutions. This is because, by
using continuous (as opposed to continual), you imply that the service is
always available, thus potentially overpromising on availability.
Continuous is OK in set industry terms such as continuous integration
and continuous delivery (CI/CD).
control plane
Use to refer to a node that controls and manages a set of other nodes
and resembles a cluster in Kubernetes. Don't use master node.
conversational AI
When describing chat-based AI, use to describe artiﬁcial intelligence that
communicates with users through a text or audio interface. Can be used
interchangeably with chat-based AI.
For more information, see Describing chat-based AI.
cool down
Two words.
## Coordinated Universal
Time (UTC)
See UTC.
co-pilot
Don't use when describing chat-based AI. Instead, use assistant, model,
or AI.
For more information, see Describing chat-based AI.
could
Don’t use could as a substitute for can or might. Could can introduce
uncertainty in these contexts.
Use could to describe something that already happened or that’s in the
past, such as a speciﬁc error.
## 34
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 44 -->

AWS Content Design System
AWS style
• You can pull the image by using the controller.
• If you choose Sync now, it might still take several minutes to
synchronize.
• The server couldn't load the results. Try again later.
Not AWS style
• You could pull the image by using the controller.
• If you choose Sync now, it could still take several minutes to
synchronize.
For more information, see Modal verbs and Words that help clarify.
See Also can, should, and would.
CPU
Stands for central processing unit.
Don't spell out. For more information, see Don't spell out common
acronyms.
cross-Region
Hyphenate. Capitalize Region when referring to AWS Regions.
See Region.
For more information, see hyphen (-) in Punctuation.
currently
Don't use to refer to AWS supporting operating systems, software, or
features. Don't use to imply support for something in the future. For
more information about using forward-looking terms, see Messaging
Dos and Don’ts on the AWS Legal Pathﬁnder website.
See also at this time and yet.
customer gateway
Don't abbreviate as CGW.
See Also internet gateway, NAT gateway.
customer managed
policy
Don't hyphenate.
## 35
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 45 -->

AWS Content Design System
customer master key
(CMK)
Don't use.
For more information, see Inclusive language.
See also key.
## Customer Support
Don't use. Use AWS Support instead.
cyber
Use as a preﬁx in a closed compound noun. Don't hyphenate. Don't
use a space between cyber and the rest of the word unless the closed
compound causes the word to be misread or it is deﬁned as an open
compound in the NIST glossary. Open compounds include cyber attack,
cyber incident, cyber resiliency, cyber risk, and cyber threat.
AWS style
• Develop and implement the appropriate activities to take action
regarding a detected cybersecurity event.
## D
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
dark mode
Two words. Don't capitalize.
dash
See dash in Punctuation.
data
Use data is, not data are. Don't use datas. Use pieces of data or
equivalent to describe individual items within a set of data.
AWS style
• The data is stored in an S3 bucket that you choose.
Not AWS style
• The data are stored in an S3 bucket that you choose.
data at rest
Data stored in Amazon S3 or on Amazon EBS, Amazon RDS, or other
AWS database services.
See Also data in transit.
## 36
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 46 -->

AWS Content Design System
data bus
Two words.
data center
Two words.
data in ﬂight
Don’t use. Use data in transit.
data in transit
Use instead of data in ﬂight for data network traﬃc between clients and
servers and among servers.
data lake
Two words.
data security
standards (DSS)
On ﬁrst mention, use data security standards (DSS). Thereafter, OK to use
DSS.
data store, datastore
Two words when used generically, but one word when referring to the
VMware product.
data type
Two words.
DataNode, data node
DataNode is a Hadoop term.
dataset, data set
Use dataset as one word for a set of numbers or values that pertain to a
speciﬁc topic.
Exception: Use data set as two words for mainframe concepts, such as in
AWS Mainframe Modernization documentation.
dates
Use one of the following date formats:
• When a human-readable date format is preferred, spell out the date
using the Month D, YYYY format (for example, October 1, 2022).
Don't use an ordinal number for the day (use 1, not 1st). If the context
is clear, you can omit the year on subsequent mention. If the speciﬁc
day isn't known, use the Month YYYY format (for example, October
2022).
• When a numeric, lexicographically sortable date is required, use the
YYYY-MM-DD format (for example, 2022-10-01). Make sure to add a
zero (0) in front of a single-digit month and day. This is the ISO 8601
standard date format. Make sure also that you use a hyphen (-) and
avoid omitting the year. Doing so avoids the ambiguity that's caused
by the common, locally used formats of MM/DD and DD/MM.
## 37
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 47 -->

AWS Content Design System
AWS style
## • October 1, 2022
## • October 2022
## • 2022-10-01
Not AWS style
## • 2022/10/01
## • 1-10-2022
## • 10/01/2022
## • 1/10
## • 1 October 2022
• October 1st, 2022
## • October, 2022
See also UTC.
DB
Used in RDS as an adjective, to distinguish RDS resource types.
• DB compute class
• DB instance
• DB parameter group
• DB snapshot
de facto
Don't use. Replace with actual.
For more information, see Writing basics.
## Dedicated Host
Capitalized by request of the product team.
## Dedicated Instance,
## Dedicated Reserved
## Instance
Capitalized by request of the product team.
defense in depth
Don't capitalize. Don't hyphenate.
## 38
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 48 -->

AWS Content Design System
demilitarized zone
(DMZ)
Refers to the secure boundary between a private, local network and the
public internet.
Don't use. Use perimeter network or perimeter zone instead.
For more information, see Inclusive language.
denial-of-service (DoS)
Hyphenate denial-of-service. On ﬁrst mention, use denial-of-service
(DoS). Thereafter, OK to use DoS.
denylist
One word. Use to describe a list of items that aren't allowed (blocked).
You can also use a service-appropriate description instead of denylist.
Don't use blacklist.
AWS style
• You can add speciﬁc websites to the denylist to block them for your
users.
• IP denylists inform email providers of internet addresses suspected of
sending unwanted email.
• Learn how denylists can aﬀect the delivery of your email, and what to
do when your address is on the denylist.
Not AWS style
• You can add speciﬁc websites to the deny list to block them for your
users.
• IP blacklists inform email providers of internet addresses suspected of
sending unwanted email.
• Learn how blacklists can aﬀect the delivery of your email, and what to
do when your address is blacklisted.
See Also allowlist.
deprecate
Avoid if possible. Deprecate isn't speciﬁc and is considered jargon.
For headings, tables, and similar applications where space is limited, use
terms such as discontinued, replaced by, or no longer supported, or similar
language as appropriate that clearly indicates what was changed.
## 39
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 49 -->

AWS Content Design System
In paragraphs or procedures, rewrite the sentence to be speciﬁc about
the nature of the change and how it impacts the user, as in the following
example:
AWS style
• Amazon Linux AMI will reach its end of standard support on December
31, 2026.
Not AWS style
• Amazon Linux AMI will be deprecated as of December 31, 2026.
desire, desired
Don't use. Desire and desired are subjective words. Consider using that
you want instead.
AWS style
• For Event variable, enter the variable values that you want to test.
• Choose the ﬁnding classiﬁcation that's next to the instance that you
want to access this page for.
Not AWS style
• For Event variable, enter your desired variable values.
• Choose the ﬁnding classiﬁcation that's next to the desired instance.
See Also need, want, and wish.
DevOps
Note capitalization. Development Operations, as in two departments
combined.
DevSecOps
Note capitalization.
dialog
When referring to a dialog box, use dialog box.
dialog box
See ???TITLE???.
digital rights
management (DRM)
On ﬁrst mention, use digital rights management (DRM). Thereafter, OK
to use DRM.
## 40
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 50 -->

AWS Content Design System
directory
Use in a ﬁle management context for Linux and command line
interfaces. For Windows (File Explorer) and AWS services that include
folder in their UI, use folder instead.
disable
See enable, disable.
disaster recovery (DR)
On ﬁrst mention, use disaster recovery (DR). Thereafter, OK to use DR.
disk cache
See cache.
disruptive
Don't use. Replace with innovative.
For more information, see Writing basics.
distributed denial-of-
service (DDoS)
Hyphenate denial-of-service. On ﬁrst mention, use distributed denial-of-
service (DDoS). Thereafter, OK to use DDoS.
DNS
Stands for Domain Name System.
Don't spell out. For more information, see Don't spell out common
acronyms.
domain controller
Don't capitalize.
domain join
Don't use. Rewrite to include the object, Join the instance to the
domain...
## Domain Name System
(DNS)
See DNS.
DomainKeys Identiﬁed
Mail (DKIM)
On ﬁrst mention, use DomainKeys Identiﬁed Mail (DKIM). Thereafter, OK
to use DKIM.
DOS
Stands for disk operating system.
Don't spell out. For more information, see Don't spell out common
acronyms.
double quotation
marks (" ")
See quotation marks (' ' and " ") in Punctuation.
double-click
Hyphenate. Don't use double click.
For more information, see hyphen (-) in Punctuation.
## 41
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 51 -->

AWS Content Design System
downtime
One word.
dropdown list
Don't use dropdown as a noun, such as for a UI element.
dropdown menu
Don't use. Use menu instead.
dual stack (n.), dual-
stack (adj.)
Use dual stack (two words, not capitalized) as a noun. Use dual-stack as
an adjective (for example, dual-stack network, dual-stack IP address).
For more information, see hyphen (-) in Punctuation.
due to
Don't use. Use because of instead.
For more information and examples, see Global English.
## E
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
e.g.
Avoid if possible. Use for example or such as instead.
For more information, see Writing basics.
See also etc. and i.e.
earlier
OK to use with reference to software versions.
easy, easier, easily
Avoid the use of easy, easier, or easily if possible when describing or
comparing an AWS service, feature, or procedure in technical content.
Use of these terms is audience dependent. These terms are potentially
misleading or inaccurate, and might be perceived as condescending by
some technical users. Instead, describe the speciﬁc beneﬁts.
On service documentation landing pages, it’s acceptable to use
easy, easier, or easily within the service description only. Ensure
that the service description is consistent across the service
documentation landing page (on docs.aws.amazon.com), marketing
pages (on aws.amazon.com), and the AWS Management Console (on
console.aws.amazon.com) whenever possible.
For more information, see Writing service documentation landing pages.
AWS style
## 42
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 52 -->

AWS Content Design System
• You can use Amazon EC2 to launch as many or as few virtual servers
as you need, conﬁgure security and networking, and manage storage.
Not AWS style
• Amazon EC2 makes it easy to scale your computing capacity.
See Also just and simple, simply.
ebook
One word. Don't capitalize. Don't hyphenate.
EBS volume
Use Amazon Elastic Block Store (Amazon EBS) volume if it's the ﬁrst
mention of Amazon EBS. Thereafter, OK to use EBS volume. It's also OK
to use Amazon EBS volume in contexts where extra clarity is needed.
See Also AWS resources.
EBS-backed
On ﬁrst mentioned, use Amazon EBS-backed. Thereafter, OK to use EBS-
backed. Hyphenate EBS-backed. This is an exception to the guidance in
Service names and Hyphenation.
EBS-optimized
On ﬁrst mention, use Amazon EBS–optimized when it's used with a
modiﬁer. Thereafter, OK to use EBS-optimized. This is an exception to the
guidance in Service names and Hyphenation.
EC2 compute unit
(ECU)
Don't use.
EC2 instance
Use Amazon Elastic Compute Cloud (Amazon EC2) instance if it's the ﬁrst
mention of Amazon EC2. Thereafter, OK to use EC2 instance. It's also OK
to use Amazon EC2 instance in contexts where extra clarity is needed.
See Also AWS resources and EC2 instance type.
EC2 instance type
An EC2 instance type is named by combining the instance family,
generation, and size. For example, in the instance type c4.8xlarge, c is
the family, 4 is the generation, and 8xlarge is the size.
Instance type names can also include markers for additional capabilities,
such as the following:
• a – indicates that the instance has an AMD processor
## 43
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 53 -->

AWS Content Design System
• g – indicates that the instance has a Graviton processor
• i – indicates that the instance has an Intel processor
• d – indicates that the instance has store volumes
• n – indicates an instance with network optimization
• e – indicates instances with extra storage or memory capacity
• z – indicates high frequency instances
For a full list of currently supported EC2 instance types, see Available
instance types in the Amazon EC2 User Guide.
When referring to the instance type or family in technical
documentation, use lowercase for an instance type, and an initial capital
letter for an instance family. When listing multiple instance families,
use alpha order (for example, “M5, M5a, M5ad, M5d, M5dn, M5n, and
M5zn”).
AWS style
• For example, you can use a c4.8xlarge instance type.
• You can assign the application to any C4 instance in your account.
Not AWS style
• For example, you can use a C4.8XLarge instance type.
• You can assign the application to any c4 instance in your account.
See Also EC2 instance.
EC2Conﬁg service
In code, it can be rendered as EC2ConﬁgService.
ecommerce
One word. Don't capitalize. Don't hyphenate.
ecosystem
For more information about using this term, see Messaging Dos and
Don’ts on the AWS Legal Pathﬁnder website.
eﬀect (n., v.)
Eﬀect as a noun refers to something that's caused by something else.
Eﬀect as a verb means to bring about.
## 44
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 54 -->

AWS Content Design System
Don't confuse with aﬀect.
egress
Avoid if possible. Use send (verb), output (noun), or an adjective such as
outbound or outgoing paired with a noun, for example, outbound traﬃc
instead.
For more information, see Writing basics.
Elastic IP address
Don't use EIP or Elastic IP.
elastic network
interface
On ﬁrst mention, use elastic network interface. Thereafter, use network
interface.
eliminate
Avoid when describing AWS products, solutions, and services.
ellipsis (...)
See ellipsis (...) in Punctuation.
em dash (—)
See em dash (—) in Punctuation.
email (n., v.)
Use as a singular noun or adjective to refer to the collective concept,
and use message or mail for individual items. Use send email as the verb
form. Don't use the plural form because it's a collective noun.
See Also spam.
EMR File System
(EMRFS)
On ﬁrst mention, use EMR File System (EMRFS). Thereafter, OK to use
EMRFS.
en dash (–)
See en dash (–) in Punctuation.
enable, disable
Use enable and disable in reference to services, features, and settings
(for example, to describe making a feature available or unavailable).
Don't use enable or disable in reference to the customer or any human
being.
For more information, see Writing basics.
AWS style
• You can invite users, enable or disable their access, and change user
roles and settings.
• You can enable enhanced networking on supported instance types for
lower latency.
## 45
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 55 -->

AWS Content Design System
• With tags, you can categorize your AWS IoT resources in a variety of
diﬀerent ways.
Not AWS style
• You can invite, enable or disable users, and change user roles and
settings.
• Tags enable you to categorize your AWS IoT resources in a variety of
diﬀerent ways.
## Important
Enable and disable were removed from the sensitive terms list on
April 24, 2023. Instead of avoiding enable and disable, prioritize
consistency, consider which word is the most appropriate for
your speciﬁc context, and .
See Also activate, deactivate, allow, deny, let, and turn on, turn oﬀ.
encryption
AWS docs refer to multiple types of encryption.
asymmetric encryption
Type of encryption that uses a mathematically related public-private
key pair for encryption and decryption. Encryption uses only the
public key. Decryption uses only the private key.
envelope encryption
Type of encryption where the encryption key that's used to encrypt
data is encrypted under another encryption key. In AWS KMS, the
data key that encrypts your data is encrypted under a KMS key that
never leaves AWS KMS unencrypted.
client-side encryption
Type of encryption where data is encrypted before it's transmitted
to a server. At AWS, client-side encryption means that our customers
## 46
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 56 -->

AWS Content Design System
encrypt their data (on the client side) before they send the data to
AWS.
server-side encryption (SSE)
Type of encryption where data is encrypted on the server. At AWS,
server-side encryption means that an AWS service encrypts the data.
symmetric encryption
Type of encryption that uses the same encryption key for encryption
and decryption.
See ciphertext and plaintext.
encryption context
A key-value pair map of additional information associated with AWS
KMS encrypted information.
end to end, end-to-
end
Avoid if possible. OK in widely recognizable industry terms such as
end-to-end encryption. Don't use complete encryption, which isn't a
recognized term.
For more information, see Writing basics.
enhanced networking
Don't capitalize.
ensure, make sure, be
sure
Don't use these terms to promise or guarantee outcomes from Amazon
or AWS. For more information, see Messaging Dos and Don’ts on the
AWS Legal Pathﬁnder website.
AWS style
• Verify that a SIM is annotated when the ﬂag is provided.
• Conﬁrm that your serverless application deployed correctly.
• Ensure that you have a rollback plan before you migrate your
database.
Not AWS style
• Amazon Virtual Private Cloud ensures the security of your cloud data.
## 47
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 57 -->

AWS Content Design System
See Also assure and insure.
enter
In general, use in preference to type when a user adds text or other input
(such as numbers or symbols).
enterprise resource
planning (ERP)
On ﬁrst mention, use enterprise resource planning (ERP). Thereafter, OK
to use ERP.
enterprise-grade
Don't use. For more information, see Writing basics.
ergo
Don't use. Use therefore, so, as a result, or similar terms instead.
For more information, see Writing basics.
etc., et cetera
Don't use.
Generally speaking, etc. and its equivalents (such as and more or and so
on) aren’t necessary. When you use for example, such as, or including,
only provide a limited number of examples to help aid understanding,
don't write a long list and avoid using etc. or and so on. Long lists lower
the readability of your writing.
For more information, see such as.
Exception: If need be for technical accuracy (to indicate explicitly that
not all options are listed), you can use and so on.
AWS style
• Depending on the environment, the value might be
development.settings or production.settings.
• If you have multiple processes and rely on Elastic Beanstalk passing
incremental port values to your processes (for example, 5000, 5100,
or 5200), modify your implementation.
• A common issue that many customers face is managing the snapshot
lifecycle and clearly aligning snapshots by purpose, retention policy,
and so on.
Not AWS style
## 48
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 58 -->

AWS Content Design System
• Depending on the environment, the value might be
development.settings, production.settings, etc.
• If you have multiple processes and rely on Elastic Beanstalk passing
incremental port values to your processes (5000, 5100, 5200, etc.),
modify your implementation.
• A common issue that many customers face is managing the snapshot
lifecycle and clearly aligning snapshots by purpose, retention policy,
and more.
For more information, see Writing basics.
See also e.g. and i.e.
## Ethernet
Capitalize.
exabyte (EB)
For more information, see Units of measure and Units of measure
abbreviations.
exbibyte (EiB)
Don't use EIB.
For more information, see Units of measure and Units of measure
abbreviations.
exclamation point (!)
See exclamation point (!) in Punctuation.
execute, execution
Don't use in reference to human beings.
For more information, see Consider the impact of your language in the
Inclusive language topic.
experience
When describing chat-based AI, use as an alternative to assistant if
assistant doesn't accurately describe what the service does, or use to
describe the overall experience of interacting with an AI service.
For more information, see Describing chat-based AI.
exploit
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## Extensible Markup
Language (XML)
See XML.
## 49
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 59 -->

AWS Content Design System
## F
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
fail over (v.), failover
(n.)
Two words as a verb, one word as an adjective or a noun. It's OK to use
the plural form, failovers (for example, Performing managed failovers for
Aurora global databases).
FAQ, FAQs
Stands for frequently asked questions. Both FAQ and FAQs are correct but
they mean diﬀerent things. Use FAQ as the abbreviation of Frequently
asked questions. Use FAQs to refer to multiple FAQ sections or topics.
Don't spell out. For more information, see Don't spell out common
acronyms.
favorite
Don't use as a synonym for bookmark.
ﬁber-optic (adj., n.)
Don't use ﬁber optic. Hyphenate ﬁber-optic as a noun or adjective.
For more information, see hyphen (-) in Punctuation.
ﬁle name (adj., n.)
Two words as an adjective or a noun when referring to the name of a
ﬁle. Don't hyphenate.
ﬁne-grained access
control
Don't use in place of resource-level permissions. Use when referring
to using condition keys to ﬁnely control access to speciﬁc resources.
For example, using condition keys in DynamoDB to provide access to
individual data items in a speciﬁc table.
Hyphenate ﬁne-grained.
For more information, see hyphen (-) in Punctuation.
ﬁne-tuned model
Don't abbreviate.
For more information, see Describing chat-based AI.
See Also foundation model (FM) and model.
ﬂywheel
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
## 50
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 60 -->

AWS Content Design System
folder
Use in a ﬁle or object management context for Windows (File Explorer)
and AWS services that include folder in their UI, such as Amazon S3,
WorkDocs, Amazon WorkSpaces, and Quick Suite. For Linux or command
line interfaces, use directory instead.
foo, foobar, fubar
Don't use foo, foobar, or fubar. Use a more descriptive placeholder
instead.
Don't use fubar, in particular, because it has a strongly negative
connotation.
forward slash (/)
Seeforward slash (/) in Punctuation.
foundation model (FM)
On ﬁrst mention, use foundation model (FM). Thereafter, OK to use FM.
frame rate
Two words.
free
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
## Free Tier
On ﬁrst mention, use AWS Free Tier. Thereafter, OK to use Free Tier.
frontend (adj., n.)
Use frontend as an adjective and a noun. Don't use front end or front-
end. Don't make frontend possessive except as part of a compound noun,
such as frontend system.
See also backend.
AWS style
• frontend model
• outward-facing frontend
• Use the frontend system’s conﬁguration options.
Not AWS style
• front end model
• outward-facing front-end
• Use the frontend’s conﬁguration options.
FTP
Stands for File Transfer Protocol.
## 51
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 61 -->

AWS Content Design System
Don't spell out. For more information, see Don't spell out common
acronyms.
full stack, full-stack
Do not use as a noun (full stack) to mean “a complete platform.” This
is jargon that can have several diﬀerent meanings. Rather, use detailed
language to fully describe the idea you’re discussing.
Do not use as an adjective (full-stack) to describe an application. OK to
use “full-stack developer” to refer to a job title or function.
fully managed
Two words. Don't hyphenate.
For more information, see hyphen (-) in Punctuation.
fully qualiﬁed domain
name (FQDN)
A fully qualiﬁed domain name (FQDN) is the unique name of an
organization or individual on the Internet followed by a top-level
domain extension such as .com or .org.
On ﬁrst mention, use fully qualiﬁed domain name (FQDN). Thereafter, OK
to use FQDN.
Don't hyphenate as fully-qualiﬁed.
function
Depending on the product, this can also be an action or an operation.
Use the same term consistently within each product.
future
Don't use to imply support for something at a later date. For more
information about using forward-looking terms, see Messaging Dos and
Don’ts on the AWS Legal Pathﬁnder website.
## G
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
gateway
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
## Gateway Load
## Balancer
In most content, use the full name. On the consoles, when space is
limited (such as dropdown lists), it’s OK to use GLB if the context is clear.
gateway-cached
Don't use. Use cached volume instead.
## 52
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 62 -->

AWS Content Design System
gateway-stored
Don't use. Use stored volume instead.
gem
See RubyGems.
gen AI
Avoid if possible. In UI text with space constraints, OK to use gen AI if
generative AI is used on ﬁrst mention. Gen AI isn't a proper noun. Don't
capitalize it in the middle of a sentence.
Don't use gen-AI, or genAI.
For more information, see Describing chat-based AI.
generate
Use as a verb when AWS creates passwords or credentials. Don't use
auto-generate.
generative AI
Stands for generative artiﬁcial intelligence.
Don't spell out. For more information, see Don't spell out common
acronyms.
For more information, see Describing chat-based AI.
See Also assistant, AI-generated.
generative pre-trained
transformer (GPT)
On ﬁrst mention, use generative pre-trained transformer (GPT).
Thereafter, OK to use GPT.
Hyphenate pre-trained.
geolocated routing
Don't hyphenate as geo-located routing.
gibibyte (GiB)
Don’t use GIB.
For more information, see Units of measure and Units of measure
abbreviations.
gibibytes per second
(GiBps)
Don't spell out as GiB per second. Don't use GiB/second or GiB/s.
For more information, see Units of measure and Units of measure
abbreviations.
GIF
Stands for Graphics Interchange Format.
Don't spell out. For more information, see Don't spell out common
acronyms.
## 53
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 63 -->

AWS Content Design System
gigabit (Gb)
For more information, see Units of measure and Units of measure
abbreviations.
gigabits per second
## (Gbps)
Don't spell out as Gb per second. Don't use Gb/second or Gb/s.
For more information, see Units of measure and Units of measure
abbreviations.
gigabyte (GB)
Don’t use G, G byte, or GByte.
For more information, see Units of measure and Units of measure
abbreviations.
global Region
Don't use when referring to AWS Regions. Use commercial Region
instead.
See Region and Regional.
GMT
Stands for Greenwich Mean Time (archaic). Use UTC instead.
government Region,
governmental Region
Don't use when referring to AWS Regions. See AWS GovCloud (US)
Regions.
See Region.
grandfathered
Don't use.
For more information, see Inclusive language.
grant (n., v.)
In IAM documentation, grant is the preferred verb for permissions.
For example, you grant permissions by attaching a policy. In AWS
KMS documentation, a grant (noun) is a mechanism for giving IAM
permissions to use AWS KMS keys. AWS KMS documentation prefers the
verbs give and allow to avoid confusion.
granularity
DynamoDB term for discussing permissions. Don't use in IAM
documentation.
ground truth
Two words.
guarantee
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
## 54
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 64 -->

AWS Content Design System
GUID
Stands for Globally Unique IDentiﬁer. GUIDs are speciﬁc IDs that
Microsoft uses.
See Also UUID.
gzip
Don't use Gzip, GZip, or GZIP.
## H
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
hacker
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## Hadoop
Full name is Apache Hadoop.
Capitalize. Don't localize.
For more information, see Third-party brand names.
## Hadoop Distributed
File System (HDFS)
On ﬁrst mention, use Hadoop Distributed File System (HDFS). Thereafter,
OK to use HDFS.
hallucination
Use to refer to the output generated from a large language model (LLM)
where an assertion or claim might sound plausible but is incorrect or
nonsensical.
Don't capitalize.
hang
Don't use in reference to human beings.
For more information, see Consider the impact of your language in the
Inclusive language topic.
hard disk drive (HDD)
On ﬁrst mention, use hard disk drive (HDD). Thereafter, OK to use HDD.
hardcode
One word.
hardware security
module (HSM)
On ﬁrst mention, use hardware security module (HSM). You store keys in
the HSM but the users are on the HSM. You log in to the HSM.
## Hardware Virtual
Machine (HVM)
On ﬁrst mention, use Hardware Virtual Machine (HVM). Thereafter, OK to
use HVM.
## 55
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 65 -->

AWS Content Design System
Hash-based Message
## Authentication Code
(HMAC)
On ﬁrst mention, use Hash-based Message Authentication Code (HMAC)
. Thereafter, OK to use HMAC. Hyphenate Hash-based.
For more information, see hyphen (-) in Punctuation.
have to
Don’t use. Use must or need to. Have to is potentially ambiguous: It can
mean that you have a need to do something or that you have yet to do
it.
See Also must and need to.
## Health Insurance
Portability and
Accountability Act of
1996 (HIPAA)
On ﬁrst mention, use Health Insurance Portability and Accountability
Act of 1996 (HIPAA). Thereafter, OK to use HIPAA. Don’t abbreviate as
HIPPA.
healthcare
One word.
## Hello World
Use as a descriptor for this common application. Don't use in a generic
sense. This term is a registered trademark.
AWS style
• Debug the Hello World application.
Not AWS style
## • Debug "Hello, World!"
helper script
Two words. Don't hyphenate.
high availability (HA)
On ﬁrst mention, use high availability (HA). Thereafter, OK to use HA.
high performance
computing (HPC)
On ﬁrst mention, use high performance computing (HPC). Thereafter, OK
to use HPC.
hit (v.)
Don't use. Replace with reach or meet in the context of service quotas or
technical limitations.
See Also search hits.
host name
Two words. OK to use hostname if you're referring to a programming
element. Don't capitalize.
## 56
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 66 -->

AWS Content Design System
hot standby
Don’t hyphenate.
hover
Use as needed to reference holding a pointer or ﬁnger over a screen
object. UI elements that require hovering over an object are not
accessible to people who use screen readers or who are keyboard-only
users. In most cases, the Popover element should be used instead.
HTML
Stands for hypertext markup language. Use all caps for ﬁle formats
unless expressed as extensions.
Don't spell out. For more information, see Don't spell out common
acronyms.
HTTP
Stands for hypertext transfer protocol.
Don't spell out. For more information, see Don't spell out common
acronyms.
HTTP ﬂood
A type of malicious attack.
HTTP(S)
Use to refer to both protocols, HTTP and HTTPS.
Don't spell out. For more information, see Don't spell out common
acronyms.
HTTPS
Stands for hypertext transfer protocol secure.
Don't spell out. For more information, see Don't spell out common
acronyms.
## Human Intelligence
Task (HIT)
An Amazon Mechanical Turk term. On ﬁrst mention, use Human
Intelligence Task (HIT). Thereafter, OK to use HIT.
hypertext markup
language (HTML)
See HTML.
hyphen (-)
See hyphen (‐) in Punctuation.
## I
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
i.e.
Don't use. Use that is or speciﬁcally instead.
## 57
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 67 -->

AWS Content Design System
For more information, see Writing basics.
See also etc. and e.g.
## I/O
Stands for input/output.
Don't spell out. For more information, see Don't spell out common
acronyms.
IAM group
Use IAM group when introducing the concept, and use group thereafter.
IAM identities
The IAM resource objects that are used to identify and group. You can
attach a policy to an IAM identity. These include users, groups, and roles.
IAM role
Use IAM role when introducing the concept, and use role thereafter.
Avoid using role generically as a term for position in a company.
IAM user
Use IAM user when introducing the concept, and use user thereafter.
ID
Stands for identiﬁer. If necessary to improve clarity, use an equivalent
instead, such as identity, token, or identiﬁer, or use the parameter name
of which Id is a part, such as MerchantId. Don't spell out as identiﬁer (ID).
For more information, see Don't spell out common acronyms.
## 58
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 68 -->

AWS Content Design System
identity as a service
(IDaaS)
On ﬁrst mention, use identity as a service (IDaaS). Thereafter, OK to use
IDaaS.
## Identity Center
directory
Don't use with the service name as AWS IAM Identity Center (successor to
AWS Single Sign-On) directory or IAM Identity Center directory.
Don't use workforce directory.
## Identity Center
enabled applications
Don't hyphenate. Don't use with the service name as AWS IAM Identity
Center (successor to AWS Single Sign-On) directory or IAM Identity Center
enabled applications.
Use when referring to AWS enterprise applications, such as Amazon
SageMaker or AWS IoT SiteWise.
Don't use to refer to external cloud applications, such as Salesforce, Box,
and Oﬃce 365.
See also cloud applications.
Identity provider (IdP)
Identity provider, such as Login with Amazon, Facebook, or Google. On
ﬁrst mention, use Identity provider (IdP). Thereafter, OK to use IdP.
identity spooﬁng
A type of malicious attack.
identity-based policy
Hyphenate identity-based. Don't capitalize.
For more information, see hyphen (-) in Punctuation.
in, on
Use in Windows or in Linux in reference to components of the operating
system (OS) or work in the OS. Use on Windows in reference to Windows
applications. Examples:
• Use the Devices and Printers Control Panel in Windows to install a new
printer.
• In Windows, run the setup command.
• Select an application that runs on Windows.
Run applications and instances in the cloud, but extend services to the
cloud.
## 59
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 69 -->

AWS Content Design System
For a hardware security module (HSM), keys are stored in the HSM but
users are on the HSM. You log in to the HSM.
AWS, cards, consoles, dashboards, menus, pages, tabs, toolbars
• computing on AWS
• on the card
• on the AWS Management Console
• on the console
• on the dashboard
• on the Edit menu
• on the sign-up page
• on the Home tab
• on the toolbar
Dialog boxes, form boxes, groups, panes, sections, views
• in the Create Report dialog box
• in the Data box
• in the Forms group
• in the navigation pane
• in the User Policies section
• in Outline view
See Also install in, on and locate in, on.
index, indexes, indices
Use indexes as the plural form of index. Use indices only in context of
mathematical expressions.
industry standards
Only use if the subject is part of a codiﬁed standard from an
organization, business, or governmental entity in a speciﬁc ﬁeld. If
referring to an item, practice, or topic that's commonly used, but not
formally codiﬁed, use best practice or best practices.
Not a synonym of open standard.
## 60
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 70 -->

AWS Content Design System
## Information Security
## Management System
(ISMS)
On ﬁrst mention, use Information Security Management System.
Thereafter, OK to use ISMS.
infrastructure as a
service (IaaS)
On ﬁrst mention, use infrastructure as a service (IaaS). Thereafter, OK to
use IaaS.
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
infrastructure as code
(IaC)
On ﬁrst mention, use infrastructure as code (IaC). Thereafter, OK to use
IaC.
ingress
Avoid if possible. Use receive (verb), input (noun), or an adjective such
as inbound or incoming paired with a noun, for example, inbound traﬃc
instead.
For more information, see Writing basics.
input/output
operations per second
(IOPS)
On ﬁrst mention, use input/output operations per second (IOPS).
Thereafter, OK to use IOPS.
install in, on
You install in a folder, directory, or path. You install on a disk, drive, or
instance.
See Also in, on and locate in, on.
instance
See EC2 instance and EC2 instance type.
instance metadata,
## Instance Metadata
Service (IMDS)
Do not capitalize unless discussing the service. On ﬁrst mention, use
Instance Metadata Service. Thereafter, OK to use IMDS.
instance recovery
Two words.
insure
Use insure to refer to what an insurance company provides. Don’t use
this term or others to promise or guarantee outcomes from Amazon or
AWS.
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
## 61
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 71 -->

AWS Content Design System
AWS style
• Modernizing core systems on AWS gives insurers the ﬂexibility to oﬀer
new services that leverage new networks of partners.
Not AWS style
• Insure that a SIM is annotated when the ﬂag is provided.
• By learning from each incident, you can insure that you avoid
repeating the same mistakes.
See Also assure and ensure, make sure, be sure.
interface
Use interface to describe the UI itself, as opposed to the model or the
service as a whole.
When describing chat-based AI, you can combine interface with
adjectives for greater speciﬁcity, such as chat interface. Can be used
interchangeably with UI.
For more information, see Describing chat-based AI.
internet
Don't confuse with intranet.
internet gateway
Don't abbreviate as IGW because this abbreviation most often refers to
international gateway.
See Also customer gateway, NAT gateway.
Internet of Things
For general audiences, on ﬁrst mention, use Internet of Things (IoT).
Thereafter, OK to use IoT. For example, IoT devices. Don't spell out on
ﬁrst use if your audience is familiar with the abbreviation IoT.
## Internet Protocol
Security (IPsec)
On ﬁrst mention, use Internet Protocol Security (IPsec). Thereafter, OK to
use IPsec.
intrusion detection
system (IDS)
On ﬁrst mention, use intrusion detection system (IDS). Thereafter, OK to
use IDS.
invalid
Don't use in reference to human beings.
## 62
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 72 -->

AWS Content Design System
For more information, see Consider the impact of your language in the
Inclusive language topic.
iOS
Use iOS for Apple's mobile operating system. Use macOS for Apple's
desktop operating system.
See Also macOS.
IP
Stands for Internet Protocol.
Don't spell out. For more information, see Don't spell out common
acronyms.
See Also IP address.
IP address
Don't abbreviate as IP only.
See Also Elastic IP address.
iptables
One word.
IPv4 address
Don't spell out.
OK to use IPv4 alone when referring to the protocol itself.
Don't abbreviate as IPv4 only if you are referring to an address.
See Also IPv6 address.
IPv6 address
Don't spell out.
OK to use IPv6 alone when referring to the protocol itself.
Don't abbreviate as IPv6 only if you are referring to an address.
See Also IPv4 address.
IT
Stands for information technology.
Don't spell out.
## J
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
JAR
Also known as a Java Archive, which is a ﬁle format.
## 63
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 73 -->

AWS Content Design System
JavaScript Object
Notation (JSON)
See JSON.
job zero
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
JobTracker
An Apache Hadoop service.
One word. Note capitalization.
JPEG
Stands for Joint Photographic Experts Group.
Don't spell out. For more information, see Don't spell out common
acronyms.
JSON
Stands for JavaScript Object Notation. Use all caps for ﬁle formats unless
expressed as extensions.
Don't spell out. For more information, see Don't spell out common
acronyms.
jump server
Use instead of jump host.
Exception: jump host can be used in AWS Cloud9 documentation.
## Jupyter
See Jupyter notebooks.
just
Use just in the sense of just now (for example, "the resources that you
just created"). Just is also OK in the term just-in-time (JIT). Otherwise,
use only in all other contexts (to mean "limited to or nothing more
than").
AWS style
• Currently, only port 0 is supported.
• The Memory metric is returned only for resources with the uniﬁed
CloudWatch agent installed.
• Similar to replication servers, CloudEndure also manages conversion
server machines on your behalf.
Not AWS style
## 64
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 74 -->

AWS Content Design System
• Currently, just port 0 is supported.
• The Memory metric is just returned for resources with the uniﬁed
CloudWatch agent installed.
• Just like replication servers, CloudEndure also manages conversion
server machines on your behalf.
For more information, see Global English.
See Also easy, easier, only, and simple, simply.
## K
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
keep, leave
In general, use keep instead of leave, especially when referring to a
default setting.
AWS style
• Keep the default setting.
Not AWS style
• Leave the default setting.
key
We use this term in discussions of tagging when we talk about key-value
pairs, and in discussions of encryption.
## Important
We no longer use customer master key or CMK. These terms
are replaced by AWS KMS key (ﬁrst mention) and KMS key
(subsequent mention). For more information about replacement
terms, see the table below.
Types of encryption keys in AWS KMS
• AWS KMS key
## 65
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 75 -->

AWS Content Design System
• AWS KMS managed encryption keys
• AWS managed keys
• customer managed keys
• data keys
• default keys
• private keys
• public keys
• root key (unrelated to AWS KMS)
## Term
## Replacement
customer master key, CMK
AWS KMS key (ﬁrst mention)
KMS key (subsequent mention)
AWS owned CMK
AWS owned key
AWS managed CMK
AWS managed key
customer managed CMK
customer managed key
master key (unrelated to AWS
KMS)
root key

key pair
Two words.
key-value pair
Don't use key/value pair. Hyphenate key-value.
For more information, see hyphen (-) in Punctuation.
kibibyte (KiB)
Don't use KIB.
For more information, see Units of measure and Units of measure
abbreviations.
## 66
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 76 -->

AWS Content Design System
kibibytes per second
(KiBps)
Don't spell out as KiB per second. Don't use KiB/second or KiB/s.
For more information, see Units of measure and Units of measure
abbreviations.
kill
Don't use in reference to human beings.
For more information, see Consider the impact of your language in the
Inclusive language topic.
kilobits per second
## (Kbps)
Don't spell out as Kb per second. Don't use Kb/second or Kb/s.
For more information, see Units of measure and Units of measure
abbreviations.
kilobyte (KB)
Don't use K, K byte, or KByte.
For more information, see Units of measure and Units of measure
abbreviations.
kilobytes per second
(KBps)
Don't spell out as KB per second. Don't use KB/second or KB/s.
For more information, see Units of measure and Units of measure
abbreviations.
KMI
Stands for key management infrastructure, an AWS KMS term. On ﬁrst
mention, use key management infrastructure. Thereafter, OK to use KMI.
## L
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
Lambda function
A customer-deﬁned function that's uploaded to AWS Lambda. Don't
refer to as a cloud function.
large language model
(LLM)
On ﬁrst mention, use large language model (LLM). Thereafter, OK to use
LLM. Don’t hyphenate as large-language.
For more information, see Describing chat-based AI.
latency-based routing
(LBR)
On ﬁrst mention, use latency-based routing (LBR). Thereafter, OK to use
LBR.
## 67
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 77 -->

AWS Content Design System
Hyphenate latency-based.
For more information, see hyphen (-) in Punctuation.
later
OK to use with reference to software versions.
launch, start
You start an application but launch an instance, environment, or cluster.
leak
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
least privilege
Also referred to as principle of least privilege.
let
Avoid using let in direct reference to the customer. Rewrite to focus on
what's important from the customer's point of view.
AWS style
• You can use a knowledge graph to store information in a graph model
and use graph queries.
• With background blur, users can blur their backgrounds by choosing
Blur my video background.
Not AWS style
• A knowledge graph lets you store information in a graph model and
use graph queries.
• Background blur lets users blur their backgrounds by choosing Blur
my video background.
For more information, see Writing basics.
See Also allow, deny and enable, disable.
leverage
Replace with use.
For more information, see Writing basics.
license included (LI)
Use to refer to an AWS licensing model that provides AWS customers
with access to external software licenses provided by AWS and running
## 68
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 78 -->

AWS Content Design System
on AWS resources, such as Microsoft Windows Server bundled with
Amazon EC2. OK to use LI on subsequent mentions.
See also bring your own license(BYOL).
## License Mobility
through Software
## Assurance
On ﬁrst mention, use License Mobility through Software Assurance .
Thereafter, OK to use License Mobility.
lifecycle
One word in reference to software.
lift and shift (n.),
lifting and shifting (v.)
Use lift and shift as a noun (for example, you can perform a lift and
shift), or as a verb (for example, you can lift and shift your applications).
Don't use lift-and-shift or lifting-and-shifting.
For more information, see hyphen (-) in Punctuation.
like (prep.)
OK to use to call out something for comparison.
As a general rule, if you can replace like with similar to, it's OK to use like.
But, if you can replace like with such as, use such as.
AWS style
• Like products, IT operations should be tested on a regular cadence.
• The ideal distribution should look like a standard bell curve, with a
few high priority and low priority workloads.
Not AWS style
• Use a query like the following one to check for fragmentation.
• AWS WAF can ﬁlter out malicious traﬃc that contain attack patterns
like SQL injection and cross-site scripting.
See Also such as.
limit
Don't use in reference to AWS services. This usage is being phased out.
Instead, use quota. If necessary in existing content, on ﬁrst mention
## 69
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 79 -->

AWS Content Design System
of limit, revise to use a phrase such as "quota (formerly referred to as
limit)."
Use limit only in the following contexts:
• In an existing ﬁle name (such as the quotas ﬁle name for a service) or
in a link to such a ﬁle.
• In API names (such as Elastic Load Balancing and AWS Shield
Advanced, which have a Limit data type).
• In the JSON ﬁles that are used to integrate services with Service
Quotas, use only in ﬁelds that aren't visible to customers.
• When used as a verb. For example: Use a policy to limit who can access
your resource.
AWS style
• Service quotas, formerly referred to as limits, are the maximum
number of service resources for your AWS account.
See Also quota.
list of strings
When referring to a list of strings as a data type, use plain English (a
list of strings) in complete sentences, but shorten it to list of strings in a
table or list or other short-format context.
live (adj.), live stream
(n., v.), live streaming
(v., adj.)
Don't use a hyphen for the adjective.
AWS style
• In a MediaPackage output, the output is always a live stream, not a
video-on-demand (VOD) stream.
• In live streaming scenarios, MediaTailor makes ad calls simultaneously
at the ad avail start for connected players.
• After you create the distribution, add the origins, and create the cache
behaviors, you can serve the live streaming channel using CloudFront.
Not AWS style
## 70
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 80 -->

AWS Content Design System
• In a MediaPackage output, the output is always a livestream, not a
video-on-demand (VOD) stream.
• In livestreaming scenarios, MediaTailor makes ad calls simultaneously
at the ad avail start for connected players.
• After you create the distribution, add the origins, and create the cache
behaviors, you can serve the live-streaming channel using CloudFront.
LLM-as-a-judge
Hyphenate, and don’t capitalize judge. Don’t shorten to LLMaaJ.
load balance (v.), load
balancer (n.), load-
balanced (adj.)
An environment is load balanced or is a load-balanced environment.
Don't use load-balancing environment.
For more information, see hyphen (-) in Punctuation.
local host
Two words.
locate in, on
Located in (a folder, directory, path), located on a disk drive or instance.
See Also in, on and install in, on.
log in (v.), login (adj.,
n.)
Use with EC2 instances or other technologies with interfaces that use
this term. Also note that you log in to an instance, not log into. Also use
log out and logout. Don't use log on, logon, log oﬀ, or logoﬀ.
AWS style
• Log in to your EC2 instance.
• Your login will be used in the following section.
Not AWS style
• Log into your EC2 instance.
• Your log-in will be used in the following section.
Do not use for the AWS Management Console. Use sign in.
See also sign in (v.), sign-in (adj., n.).
low code
Don't use.
See also low-code.
## 71
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 81 -->

AWS Content Design System
low latency (n.), low-
latency (adj.)
Hyphenate when used as an adjective.
For more information, see hyphen (-) in Punctuation.
See Also ultra-low latency (n.), ultra-low-latency (adj.).
low-code
Hyphenate. Don’t abbreviate as LC.
AWS style
• With low-code platforms, you don't need coding expertise to build
custom applications.
• Low-code refers to products that provide a visual drag-and-drop
interface with the option to add your own code.
Not AWS style
• With low code platforms, you don't need coding expertise to build
custom applications.
• Low code refers to products that provide a visual drag-and-drop
interface with the option to add your own code.
• LC refers to products that provide a visual drag-and-drop interface
with the option to add your own code.
See also no-code.
For more information, see hyphen (-) in Punctuation.
low-code no-code
(LCNC)
Hyphenate. On ﬁrst mention, use low-code no-code (LCNC). Thereafter,
OK to use LCNC.
Don’t reverse the word order as no-code low-code. Don’t use NCLC. Don’t
abbreviate the individual terms as LC or NC. Don’t hyphenate as low-
code-no-code. Don’t include a slash as low-code/no-code, or low code/no
code.
AWS style
## 72
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 82 -->

AWS Content Design System
• Low-code no-code (LCNC) services help you oﬄoad initial dataset
screening to non-technical personnel. LCNC services for Amazon
SageMaker include JumpStart and Autopilot.
Not AWS style
• AWS oﬀers low code/no code data and AI services.
• AWS oﬀers no-code low-code (LCNC) data and AI services.
For more information, see hyphen (-) in Punctuation.
low-order ports
Hyphenate low-order. Don't capitalize.
For more information, see hyphen (-) in Punctuation.
## Low-Rank Adaptation
(LoRA)
Hyphenate Low-Rank.
## M
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
machine learning (ML)
On ﬁrst mention, use machine learning (ML). Thereafter, OK to use ML.
Write as two words (no hyphen) in all cases, including when used as an
adjective before a noun.
machine learning
operations (MLOps)
On ﬁrst mention, use machine learning operations (MLOps). Thereafter,
OK to use MLOps. Don’t use ML Ops or other variations. Don't use ML
operations. Don't capitalize machine learning operations.
AWS style
• Use machine learning operations (MLOps) to automate and
standardize processes across the machine learning (ML) lifecycle. You
can use SageMaker MLOps tools to train, test, troubleshoot, deploy,
and govern ML models.
## 73
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 83 -->

AWS Content Design System
• Use machine learning operations (MLOps) to automate and
standardize processes.
Not AWS style
• Use MLOps to automate and standardize processes across the machine
learning (ML) lifecycle. You can use SageMaker MLOps tools to train,
test, troubleshoot, deploy, and govern ML models.
• Use ML operations (MLOps) to automate and standardize processes.
• Use machine learning operations (ML Ops) to automate and
standardize processes.
macOS
When referring to the Mac operating system, use macOS and iOS. Don't
use Mac, MacOS, Mac OS, IOS, or OS X.
Don't capitalize macOS or iOS when used as the ﬁrst word in a sentence.
malicious actor
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
man in the middle (n.),
man-in-the-middle
(adj.)
A type of malicious attack. Use man in the middle as a standalone noun.
Use man-in-the-middle as an adjective modifying a noun.
For more information, see hyphen (-) in Punctuation.
management account
Use to refer to an account in AWS Organizations that creates an
organization. Don't use the term master account.
manually enabled
Regions, manual
## Regions
Don't use. Use opt-in Region instead.
master
Don't use.
1. Use a service-appropriate description, such as primary, main, control,
or leader.
If you're working on content related to encryption or AWS KMS, see key
for guidance.
AWS style
## 74
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 84 -->

AWS Content Design System
• Each primary database consumes the changes that occur in your
current Region.
• Data type: "PRIMARY_EMAIL"
• Exception: MAIN _NOT_GOVCLOUD_ENABLED
• Select one node in your cluster as the leader node. The remaining
nodes are referred to as the member nodes.
Not AWS style
• Each master database consumes the changes that occur in your
current Region.
• Data type: "MASTER_EMAIL"
• Exception: MASTER_NOT_GOVCLOUD_ENABLED
• Select one node in your cluster as the master node. The remaining
nodes are referred to as the slave nodes.
2. In addition to technical discussions and names, don't use master
generally. For example, as a verb, consider learn.
AWS style
• Learn important concepts by completing the tutorial.
Not AWS style
• Master important concepts by completing the tutorial.
3. To designate an authoritative position, use a service-appropriate
description. For example, lead or primary.
AWS style
• The lead user has permissions to create payment accounts.
Not AWS style
## 75
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 85 -->

AWS Content Design System
• The master user has permissions to create payment accounts.
For more information, see Inclusive language.
See Also slave.
master account
Don't use. Use management account instead to refer to an account in
AWS Organizations that creates an organization.
For more information, see Inclusive language.
master node
For Amazon Elastic Kubernetes Service (Amazon EKS), don't use master
node, use control plane. The term master node is no longer used by
Kubernetes.
For more information, see Inclusive language.
may
Avoid if possible. Use can or might instead.
For more information and examples, see Global English.
mebibyte (MiB)
Don't use MIB.
For more information, see Units of measure and Units of measure
abbreviations.
mebibytes per second
(MiBps)
Don't spell out as MiB per second. Don't use MiB/second or MiB/s.
For more information, see Units of measure and Units of measure
abbreviations.
megabit (Mb)
Don’t abbreviate, unless in UI.
For more information, see Units of measure and Units of measure
abbreviations.
megabits per second
## (Mbps)
Don't spell out as Mb per second. Don't use Mb/second or Mb/s.
For more information, see Units of measure and Units of measure
abbreviations.
megabyte (MB)
Don’t use M, meg, M byte, or MByte.
## 76
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 86 -->

AWS Content Design System
For more information, see Units of measure and Units of measure
abbreviations.
megabytes per second
(MBps)
Don't spell out as MB per second. Don't use MB/second or MB/s.
For more information, see Units of measure and Units of measure
abbreviations.
member account
Two words. Use member account only in reference to AWS Organizations.
message
authentication code
(MAC)
On ﬁrst mention, use message authentication code (MAC). Thereafter, OK
to use (MAC).
meta prompting
Two words. Don't hyphenate as meta-prompting, or write as one word,
metaprompting.
metadata
Use metadata is, not metadata are.
One word.
method
Use operation or API operation instead so that implementation-neutral
content can be used across conceptual, API, CLI, and SDK guides.
microservice
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
## Microsoft
See the list of trademarks for correct usage. Also see individual products.
middleend
Don't use. Instead, speciﬁcally describe the hardware or software layer
with which the user interacts.
See also backend and frontend.
might
Use to express possibility. Don’t substitute with may, which might be
interpreted as providing permission.
For more information, see Modal verbs and Words that can help clarify.
See Also can.
model
Use when referring to a foundation model or ﬁne-tuned model. Don't
use interchangeably with algorithm.
For more information, see Describing chat-based AI.
## 77
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 87 -->

AWS Content Design System
MQTT
Stands for Message Queuing Telemetry Transport.
Don't spell out. For more information, see Don't spell out common
acronyms.
multi-account
Hyphenate.
For more information, see hyphen (-) in Punctuation.
multi-account
permissions
Always hyphenate multi-account.
multi-factor
authentication (MFA)
On ﬁrst mention, use multi-factor authentication (MFA). Thereafter, OK
to use MFA. Hyphenate multi-factor.
For more information, see hyphen (-) in Punctuation.
multilayer,
multilayered
Use multilayer to refer to multiple physical layers of a substance.
Use multilayered to refer to multiple viewpoints, layers, or complexities.
Don’t hyphenate as multi-layer or multi-layered.
For more information, see hyphen (-) in Punctuation.
multi-master
replication
Hyphenate multi-master.
For more information, see hyphen (-) in Punctuation.
multimodal
Don't hyphenate as multi-modal.
multi-node
See single-node.
multipage
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
## Multipurpose Internet
Mail Extensions (MIME)
On ﬁrst mention, use Multipurpose Internet Mail Extensions (MIME).
Thereafter, OK to use MIME.
multi-Region
Hyphenate. Capitalize Region when referring to AWS Regions.
See Region.
For more information, see hyphen (-) in Punctuation.
## 78
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 88 -->

AWS Content Design System
multi-tenant
Hyphenate.
For more information, see hyphen (-) in Punctuation.
multi-tier
Hyphenate.
For more information, see hyphen (-) in Punctuation.
multiuser
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
multiversion
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
must
Use must to assert obligation. Must makes it unambiguous that the
customer has no choice but to proceed or adhere to a requirement.
Avoid using must for situations where the customer does have a choice
because using must in these situations can sound overbearing. For more
information, see Describing requirements and recommendations.
AWS style
• Before choosing the workloads to migrate, make sure that you’re
familiar with the migrating environment.
• The language code that you speciﬁed in your request must be en-US.
• Carefully evaluate the options because each option impacts the
number of instances required.
Not AWS style
• Before choosing the workloads to migrate, you must fully understand
the migrating environment.
• The language code that you speciﬁed in your request should be en-
US.
• You must carefully evaluate the options because each option impacts
the number of instances required.
See Also need, need to and should.
## 79
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 89 -->

AWS Content Design System
## N
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
name server
Two words.
NameNode
One word. Note capitalization.
namespace
One word.
NAT
Stands for network address translation.
Don't spell out. For more information, see Don't spell out common
acronyms.
Capitalize and spell out in the name of the internet protocol, Network
Address Translation and Protocol Translation (NAT-PT).
NAT gateway, NAT
## Gateway
Don't abbreviate as NGW. Use lowercase gateway for the type of NAT
device, title case for the AWS managed service that controls NAT
gateway resources.
See Also customer gateway, internet gateway.
natural language
processing (NLP)
On ﬁrst mention, use natural language processing (NLP). Thereafter, OK
to use NLP. Don’t hyphenate as natural-language.
navigate to
Not navigate in.
See Also in, on.
near real time (n.),
near real-time (adj.)
(NRT)
Use near real time as a noun, use near real-time as an adjective. Don't
add a hyphen between near and real time or real-time.
On ﬁrst mention, use near real time (NRT). Thereafter, OK to use NRT.
For more information, see hyphen (-) in Punctuation.
AWS style
• AWS Health Dashboard communicates in near real time to report
updates.
• You can send near real-time requests using the AWS Health Dashboard
API.
## 80
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 90 -->

AWS Content Design System
• You can communicate with your users in near real time (NRT) using
Amazon Simple Notiﬁcation Service.
Not AWS style
• AWS Health Dashboard communicates in near-real time to report
updates.
• You can send near-real-time requests using the AWS Health
Dashboard API.
• You can communicate with your users in NRT using Amazon Simple
Notiﬁcation Service.
See also real time.
need, need to
Use need and need to to describe needs or requirements.
Unlike must, need to doesn’t assert obligation. That is, need and need
to describe when an action is required but leave the decision up to the
customer. For more information about must and need, see Describing
requirements and recommendations.
AWS style
• You only need to provide an AWS KMS key if you want to use a non-
default AWS KMS key or if you’re using the Encryption:Mode of
aes-cbc-pkcs7, aes-ctr, or aes-gcm.
• If you don’t use the same VPC name, you need to update each data
source to use the new VPC.
See Also desire and wish, want, need.
NetBIOS
Stands for Network Basic Input/Output System.
Don't spell out. Note capitalization.
network access control
list (network ACL)
On ﬁrst mention, use network access control list (network ACL).
Thereafter, OK to use network ACL. Don't use NACL.
## 81
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 91 -->

AWS Content Design System
network address
translation (NAT)
See NAT.
network ﬁrewall
Use lower case when discussing ﬁrewall and network ﬁrewall resources.
Use initial caps only when referring to the service AWS Network Firewall
on subsequent mentions.
For more information, see AWS oﬀering names for ﬁrst and subsequent
use guidelines.
AWS style
• If you don't know how to do this, work with someone who
understands your network ﬁrewall rules to determine an open port in
your ﬁrewall.
• AWS Network Firewall returns a token to your requests that access the
ﬁrewall.
Not AWS style
• The subnets that you've conﬁgured for use by the Network Firewall.
• To use a rule group, you include it by reference in an AWS Network
Firewall Firewall policy, then you use the policy in a Firewall.
network interface card
(NIC)
On ﬁrst mention, use network interface card (NIC). Thereafter, OK to use
NIC.
## Network Load
## Balancer
In most content, use the full name. On the consoles, when space is
limited (such as dropdown lists), it’s OK to use NLB if the context is clear.
neural network
Don’t capitalize. Don’t abbreviate as NN.
NGINX
Stands for engine x.
Don't spell out. For more information, see Don't spell out common
acronyms.
no code
Don't use.
See also no-code.
## 82
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 92 -->

AWS Content Design System
no-code
Hyphenate. Don’t abbreviate as NC.
For more information, see hyphen (-) in Punctuation.
AWS style
• No-code often refers to drag-and-drop software that requires no
coding skills to use.
• With no-code platforms, you can create software using a graphical
user interface.
Not AWS style
• No code often refers to drag-and-drop software that requires no
coding skills to use.
• With no code platforms, you can create software using a graphical
user interface.
• With NC platforms, you can create software using a graphical user
interface.
See also low-code.
node
Don't use master node and avoid using worker node.
For more information, see master, master node, and worker node.
noncommercial
Region, non-
commercial Region
Don't use when referring to AWS Regions. For AWS GovCloud (US)
Regions, see AWS GovCloud (US) Regions. For China Regions, see China
Regions.
See Region.
noncompliant,
noncompliance
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
noncurrent
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
## 83
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 93 -->

AWS Content Design System
nondisclosure
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
nongovernmental
Region, non-
governmental Region
Don't use when referring to AWS Regions. Use commercial Region
instead.
See Region.
non-production
Hyphenate.
For more information, see hyphen (-) in Punctuation.
nonproﬁt
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
NoOps, no-op, Noop
NoOps denotes an automated system in PaaS contexts. No-op denotes
no operation. Noop is a Google programming language project.
Hyphenate no-op.
For more information, see hyphen (-) in Punctuation.
north, south, east,
west
In general, use sentence case. Capitalize if part of a proper noun. When
describing traﬃc ﬂow, use the north-south or east-west format. Use a
hyphen instead of an en dash or em dash.
AWS style
• north-south
## • South America (São Paulo)
• cn-northwest-1
• Europe (Paris) Region (eu-west-3)
• US East (N. Virginia)
• east-west
Not AWS style
• north—south
## • North-South
## 84
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 94 -->

AWS Content Design System
• US east (N. Virginia)
## • East/West
null
Don't use null as a general term for missing user input error messages.
Use null to refer to a null value. Use the capitalization or formatting
style of the programming language or format that you're referencing.
For example, this can be NULL, Null, or null.
For missing user input error messages, use empty, missing, or required.
For more information, see User input is missing, incomplete, or incorrect.
## O
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
OAuth
An open standard for authorizing access to server resources.
oﬄine
One word.
oﬀsite
One word.
older
Don't use in reference to software versions. Use previous or similar
wording instead.
See Also or earlier.
on premises (n.), on-
premises (adj.)
Use on premises as a noun. Use on-premises (note the hyphen) as an
adjective (for example, You don't need on-premises software to use this
service...)
For more information, see hyphen (-) in Punctuation.
See Also premise, premises.
once
Only use to mean at one time. Don't use to mean after.
For more information, see Global English.
## On-Demand Instance
Capitalized by request of the product team.
online
One word.
online analytic
processing (OLAP)
On ﬁrst mention, use online analytic processing (OLAP). Thereafter, OK to
use OLAP.
## 85
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 95 -->

AWS Content Design System
online transaction
processing (OLTP)
On ﬁrst mention, use online transaction processing (OLTP). Thereafter,
OK to use OLTP.
only
For the greatest clarity, place only next to the thing that it modiﬁes.
AWS style
• The persistent data must be kept private. It can be accessed only with
the microservice API.
• This action restores the DB cluster only. It doesn't restore the DB
instances for the DB cluster.
• Only you can use your AWS account root user password or access keys.
Never share the password or access keys.
• You can use this parameter only if you set IdentifyLanguage to true in
your request.
For more information, see Global English.
See Also easy, easier, just, and simple, simply.
onsite
One word.
open source (adj., n.)
Two words. Use open source as an adjective (for example, open source
software), or as a noun (for example, the code throughout this tutorial is
open source).
Don't use open-source, opensource, or OpenSource.
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
open standard (n.)
Don't hyphenate. Refers to a standard, typically maintained by an
organization or community, that is commonly available on a royalty-
free basis. Open-source software is a type of open standard. Be mindful
that the exact deﬁnition of open standard can vary between countries,
companies, and organizations.
Don't use as a synonym for industry standards.
OpenID Connect
(OIDC)
On ﬁrst mention, use OpenID Connect (OIDC). Thereafter, OK to use
OIDC. OIDC providers are entities in IAM that describe an identity
## 86
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 96 -->

AWS Content Design System
provider that supports the OpenID Connect standard. OIDC-compatible
providers include Google and Salesforce.
OpenSSL
Don't spell out.
operating system (OS)
On ﬁrst mention, use operating system (OS). Thereafter, OK to use OS.
When referencing operating systems in documentation, follow these
guidelines.
• In general, if your docs or procedures apply to both Linux and macOS,
you can also include Unix.
• Unix and UNIX aren't the same. UNIX is a trademarked name that's
owned by The Open Group. In most cases, you should use Unix.
For more information, see Unix.
• When referring to the Mac operating system, use macOS and iOS.
Don't use Mac, Mac OS, or OS X.
• When referring to Windows, don't preﬁx with Microsoft and don't use
Windows-based.
• To reference multiple Unix-like operating systems, separate by
commas and use the following order: Linux, macOS, or Unix.
operation
Use instead of action or method so that implementation-neutral content
can be used across conceptual, API, CLI, and SDK guides.
AWS style
• Use the CopySnapshot operation to...
• The following API operations…
Not AWS style
• Use the CopySnapshot action to...
• Use the CopySnapshot method to...
• Use the CopySnapshot function to...
• This action requires permissions for the lambda:AddPermission
action.
## 87
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 97 -->

AWS Content Design System
opex
Don't use. Also, don't use operating expenditure or operating expense. Use
variable costs, ongoing costs, IT costs instead.
AWS style
• In addition to being able to shift from a ﬁxed costs model to a variable
costs model, AWS Ground Station provides the ability to collect fresh
data more quickly.
Not AWS style
• In addition to being able to shift from a capex (capital expense) to
opex (operating expense) model, AWS Ground Station provides the
ability to collect fresh data more quickly.
See Also capex.
optimal
Don't use. The word optimal qualiﬁes an outcome without providing
speciﬁcs, and it makes assumptions about user requirements. Rewrite to
provide more information about what the service or feature can do for
the customer, such as provide high availability, provide accurate data, or
be more eﬃcient or more eﬀective.
When recommending a practice, instead of saying that it's optimal,
rewrite as a recommendation (typically with the phrase "We
recommend...").
AWS style
• When the default value is set, SQL Server can use all available
processors, but this can lower performance.
• Gather dictionary-level and schema-level statistics for more accurate
results.
Not AWS style
• When the default value is set, SQL Server can use all available
processors. This can aﬀect performance, which isn’t optimal.
## 88
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 98 -->

AWS Content Design System
• Gather dictionary-level and schema-level statistics for optimal
performance.
opt-in Region
On ﬁrst mention, use opt-in Region (Region that is disabled by default)
and link to the opt-in Region entry in the AWS Glossary. Thereafter, OK
to use opt-in Regions.
Don’t use Regions that are manually enabled or manually enabled
Regions to describe opt-in Regions. To refer to Regions that aren't opt-in
Regions, use Regions that are enabled by default.
To describe the act of enabling an opt-in Region, use the verb enable
instead of opt in. To describe the act of disabling an opt-in Region,
use the verb disable instead of opt out. To describe the status of a
Region (whether it's enabled or disabled), use opt-in status instead of
enablement status.
For a list of opt-in Regions, see Considerations before enabling and
disabling Regions in the AWS Account Management Guide.
optional
See ???TITLE???.
opt-out Region
Don’t use. Use Region that is enabled by default.
See Also opt-in Region.
or earlier, or later
OK to use with software versions.
organization
Use for the resource in AWS Organizations. Never capitalize it or use
AWS organization. Avoid AWS Organizations organization.
AWS style
• You can use the AWS Organizations console to centrally view and
manage all of your accounts within your organization.
See Also AWS Organizations.
origin access identity
(OAI)
On ﬁrst mention, use origin access identity (OAI). Thereafter, OK to use
OAI.
## 89
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 99 -->

AWS Content Design System
OS-level access
On ﬁrst mention, use operating system-level access. Thereafter, OK to
use OS-level access.
Hyphenate OS-level.
For more information, see hyphen (-) in Punctuation.
ought to
Don't use.
See Also must and should.
owned
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## P
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
parentheses ( )
See parentheses ( ) in Punctuation.
partition
A group of AWS Regions. AWS commercial Regions are in the aws
partition, China Regions are in the aws-cn partition, and AWS GovCloud
(US) Regions are in the aws-us-gov partition. On ﬁrst mention of
partition, link to the partition entry in the AWS Glossary, which deﬁnes
what a partition is and describes which Regions are in each partition.
See Also Regions and partitions.
partner
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
## Partner Central
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
partnership
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
payload
Use a speciﬁc term for what the payload is, such as message.
For more information, see Writing basics.
payment card industry
(PCI)
On ﬁrst mention, use payment card industry (PCI). Thereafter, OK to use
PCI.
## 90
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 100 -->

AWS Content Design System
PDF
Stands for Portable Document Format. Use all caps for ﬁle formats
unless expressed as extensions.
Don't spell out. For more information, see Don't spell out common
acronyms.
pebibyte (PiB)
Don't use PIB.
For more information, see Units of measure and Units of measure
abbreviations.
pen testing
OK to use pen testing as an abbreviation for penetration testing.
per
Don't use to mean according to (for example, per the agreement).
Consider writing around per elsewhere. Per can sound stuﬀy and
confusing to some global users.
OK to use in meaning of to, in, for, or by each (one per account) where
space is limited and in set terms and phrases, such as any of the
following:
• on a per-Region basis
• queries per second (QPS)
• bits per second (bps)
• megabytes per second (MBps)
AWS style
• If this argument is provided, the service generates a unique upload
URL for each ﬁle.
• If RAM on the server is between 4 GB and 16 GB, leave 1 GB for every
4 GB of RAM. For example, for a server with 16 GB, leave 4 GB.
• You can specify and pay for resources for individual applications
separately.
Not AWS style
## 91
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 101 -->

AWS Content Design System
• If this argument is provided, the service generates a unique upload
URL per ﬁle.
• If RAM on the server is between 4 GB and 16 GB, leave 1 GB per 4 GB
of RAM. For example, for a server with 16 GB, leave 4 GB.
• You can specify and pay for resources per application.
For more information, see Writing basics.
See also per se.
per se
Don't use. For more information, see Writing basics.
See also per.
percent
Spell out (for example, 30 percent).
Exception: Use % in headlines, quotations, art callouts, and tables.
performant
Replace with high-performing.
For more information, see Writing basics.
period (.)
See period (.) in Punctuation.
permission,
permissions
Use instead of privilege. In IAM, you grant permissions.
Exception: Least privilege is correct.
permissions policy
Use the plural form of permissions. Don't use permission.
Don't capitalize.
persistent identiﬁer
(PID)
On ﬁrst mention, use persistent identiﬁer (PID). Thereafter, OK to use
PID.
petabyte (PB)
Don’t use P, P byte, or PByte.
For more information, see Units of measure and Units of measure
abbreviations.
plain text, plaintext
Use plain text (two words) to refer to text that doesn't have formatting—
such as bold or italic—applied to it.
## 92
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 102 -->

AWS Content Design System
Use plaintext (one word) to refer to unencrypted information used
as input into a cipher (also known as an encryption algorithm) for
encryption, or information that is decrypted. Compare with cleartext,
which is information that isn't intended for encryption at any point.
See Also ciphertext and cleartext.
platform
For more information about using this term, see Messaging Dos and
Don’ts on the AWS Legal Pathﬁnder website.
platform as a service
(PaaS)
On ﬁrst mention, use platform as a service (PaaS). Thereafter, OK to use
PaaS.
please
Avoid using except in quoted text.
See Also Voice.
plugin
Don't capitalize or treat as part of the product name.
Exception: Capitalize if it appears as part of product name in the UI.
PM
See AM.
pointer
Don't use mouse pointer or mouse.
point-in-time recovery
Don't use to mean point-in-time restore. Hyphenate point-in-time.
policy statement
Don't capitalize.
pop-up (adj., n.)
Hyphenate.
For more information, see hyphen (-) in Punctuation.
port address
translation (PAT)
On ﬁrst mention, use port address translation (PAT). Thereafter, OK to
use PAT.
portal
Don't use as a reference to the Amazon Web Services website.
Exception: Okay to use AWS access portal when referring to AWS IAM
Identity Center single sign-on access.
post-migration
Hyphenate.
For more information, see hyphen (-) in Punctuation.
## 93
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 103 -->

AWS Content Design System
See Also pre-migration.
post-training
Use to refer to the evaluation of metrics and adjustment of a trained
machine learning (ML) model.
Hyphenate.
See Also pre-training and re-training.
PowerShell
PowerShell is available on Windows and is also an open-source project
for Mac and Linux. Use the following:
• Windows PowerShell
• PowerShell for Mac
• PowerShell for Linux
Don't use Microsoft PowerShell or Microsoft Windows PowerShell.
See Also Windows PowerShell.
pre-installed
Hyphenate.
For more information, see hyphen (-) in Punctuation.
pre-migration
Hyphenate.
For more information, see hyphen (-) in Punctuation.
See Also post-migration.
premise, premises
A premise (singular) is the basis of an argument. Premises (plural) refers
to property and buildings. Always use the plural form, premises.
AWS style
• an on-premises solution
Not AWS style
• an on-premise solution
• an on-prem solution
See Also on premises.
## 94
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 104 -->

AWS Content Design System
## Premium Support
Don't use. Use AWS Support instead.
prerelease
Don't hyphenate (for example, This prerelease documentation is
conﬁdential and is provided under the terms of your nondisclosure
agreement with Amazon Web Services.)
For more information, see hyphen (-) in Punctuation.
presigned URL
Use presigned as one word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
pre-training
Use to refer to the initial training of a machine learning (ML) model on a
dataset, such as a large language model (LLM) on a large text dataset.
Hyphenate.
See Also post-training and re-training.
preview
A service release where the service might not be immediately ready
for large numbers of customers or is missing key features. For these
services, there's typically a public announcement, and generally the
service is expected to be open to all customers. For more information,
see New Services Release Types.
primitive
Don't use in reference to human beings.
For more information, see Consider the impact of your language in the
Inclusive language topic.
priority zero
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
private beta
Don't use. Use beta instead.
For more information, see New Services Release Types.
private preview
Don't use. Use beta instead.
For more information, see New Services Release Types.
private virtual
interface
Don't abbreviate as PVI.
## 95
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 105 -->

AWS Content Design System
privilege
Avoid except in the expression least privilege. Otherwise, use permission.
prompt engineering
Don’t capitalize. Don’t abbreviate as PE.
public cloud
For information about using this term, see Messaging Dos and Don’ts on
the AWS Legal Pathﬁnder website.
public key
cryptography
Don't hyphenate.
public key encryption
Don't hyphenate.
public key
infrastructure (PKI)
On ﬁrst mention, use public key infrastructure (PKI). Thereafter, OK to
use PKI.
public Region
Don't use when referring to AWS Regions. Use commercial Region
instead.
See Region.
public-facing
Avoid if possible. Use public instead.
For more information, see Writing basics.
purge
Use in reference to speciﬁc programming methods. Otherwise, use
delete, clear, or remove instead.
pwned
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## Python
Capitalize.
## Q
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
## Qualiﬁed Security
Assessor (QSA)
On ﬁrst mention, use Qualiﬁed Security Assessor (QSA). Thereafter, OK to
use QSA.
question mark (?)
See question mark (?) in Punctuation.
queuing
Don't spell as queueing.
## 96
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 106 -->

AWS Content Design System
quota
Use instead of limit when referring to the maximum value for resources,
actions, and items in an AWS account.
AWS style
• See the following section for information about Amazon Kendra
service quotas and how to request a quota increase.
Not AWS style
• The following section contains information about service limits.
See Also limit.
quotation marks (" ")
See quotation marks (' ' and " ") in Punctuation.
## R
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
RAM
Stands for random access memory.
Don't spell out. For more information, see Don't spell out common
acronyms.
random access
memory (RAM)
See RAM.
read local/write global
Don’t use read local-write global.
read local/write local
Don’t use read local-write local.
read/write
Use instead of read-write. Capitalize both read and write if the context
requires read to be capitalized.
Use read/write permissions, not read/write access.
real time (n.), real-time
(adj.)
Use with caution. This term can imply a degree of responsiveness or
speed that might not be true. When needed, use real time as a noun (for
example, The request is sent in real time...). Use real-time as an adjective
( for example, A real-time feed is displayed...).
## 97
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 107 -->

AWS Content Design System
For more information, see hyphen (-) in Punctuation.
See also near real time.
## Real Time Messaging
Protocol (RTMP)
On ﬁrst mention, use Real Time Messaging Protocol (RTMP). Thereafter,
OK to use RTMP. Don't hyphenate as Real-Time.
## Realtime Servers
A feature of Amazon GameLift Servers. On ﬁrst mention, use Amazon
GameLift Realtime Servers. Realtime Servers is the feature but you can
also have a Realtime server (note the capitalization).
reasoning and acting
(ReAct)
Spell out as reasoning and acting (ReAct) on ﬁrst use. Thereafter, OK to
use ReAct.
reboot
OK to use for technical audiences, such as IT administrators and
developers. Use reboot in reference to EC2 instances. Don't alternate
between using reboot and restart.
See also restart.
## Reduced Redundancy
Storage (RRS)
On ﬁrst mention, use Reduced Redundancy Storage (RRS). Thereafter, OK
to use RRS.
referer
Speciﬁcally for the HTTP referer. Originally misspelled in the
speciﬁcation, this is now the generally accepted spelling for this
particular case.
Always spell as referrer for all other uses.
## Region
On ﬁrst mention, use AWS Region. Thereafter, OK to use Region. Use
lowercase region only when referring to a generic region that's not
related to AWS, for example, a geographical region.
Capitalize Region in terms that refer to AWS Regions. This includes the
following:
## • Regional
• cross-Region
• multi-Region
• AWS Local Region
## 98
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 108 -->

AWS Content Design System
Don't use labels such as global, governmental, noncommercial,
nongovernmental, public, or standard in relation to AWS Regions because
such labels can cause confusion. For guidance on how to refer to the
diﬀerent kinds of Regions, see Referring to Regions.
AWS style
• Specify an AWS Region for your EC2 instance. Your S3 bucket must be
in the same Region.
• Post-quantum TLS for AWS KMS is available in all AWS Regions that
AWS KMS supports, except for the AWS GovCloud (US) Regions and
the China Regions.
• Amazon Neptune is now available in the Asia Paciﬁc (Sydney) Region.
Not AWS style
• Use the Region selector to specify a region for your AWS resources.
For more information, see Regions and partitions.
Region that is enabled
by default
Use Region that is enabled by default to refer to a Region that isn't an
opt-in Region.
In service documentation, you can link to the Region that is enabled by
default deﬁnition in the AWS Glossary.
For a list of Regions that aren’t enabled by default (opt-in Regions),
see Considerations before enabling and disabling Regions in the AWS
Account Management Guide.
See Also opt-out Region.
## Regional
Capitalize when referring to AWS Regions.
See Region.
Regions that are
enabled by default
Don't use default Regions.
## 99
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 109 -->

AWS Content Design System
For more information, see opt-in Region.
reinstall, reinstalled,
reinstalling
One word.
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
release
Describes a web service software release such as a deployment that
might include a version update.
See Also version.
## Remote Desktop
Gateway (RD Gateway)
On ﬁrst mention, use Remote Desktop Gateway (RD Gateway). Thereafter,
OK to use RD Gateway. Capitalize Gateway.
repo
On ﬁrst mention, use repository. Thereafter, use repo.
request
When describing chat-based AI, a user asks a question or makes a
request. Request is preferred.
For more information, see Describing chat-based AI.
## Reserved Instance
Capitalized by request of the EC2 product team.
re-sort
Hyphenate.
For more information, see hyphen (-) in Punctuation.
resource
See AWS resources.
resource-based policy
Don't use in place of resource-level permissions. Use to refer to IAM
permissions policies that you attach directly to a resource (instead of
attaching a policy to an IAM user or role). Only a few AWS services
support resource-based policies.
Hyphenate resource-based.
For more information, see hyphen (-) in Punctuation.
resource-level
permissions
OK to use in IAM content. Don't use in place of resource-based policy.
Avoid using in service-speciﬁc Authentication and Access Control
content—write around instead to prevent confusion with resource-
based policies. Resource-level permissions are those that don't require
"Resource":"*" in a policy. Instead, you can use a resource-level
## 100
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 110 -->

AWS Content Design System
permission to identify the speciﬁc resources that the action can aﬀect.
For example, an RDS policy that aﬀects a speciﬁc DB instance. Some
AWS services and actions don't support resource-level permissions.
Hyphenate resource-level.
For more information, see hyphen (-) in Punctuation.
response
When describing chat-based AI, the generative AI assistant provides an
answer or a response. Response is preferred.
For more information, see Describing chat-based AI.
response group
Two words. Don't capitalize.
REST
Stands for Representational State Transfer. Generally used in discussions
to contrast with SOAP.
If the web service uses both query-based and resource-based REST calls,
keep the distinction clear using the terms REST and REST-Query.
Don't spell out. For more information, see Don't spell out common
acronyms.
restart
OK to use. For non-technical audiences, this term is more appropriate
than reboot. Don't alternate between using reboot and restart.
See also reboot.
re-training
Use to refer to taking a pre-trained machine learning (ML) model and
further ﬁne-tuning it on a new dataset.
Hyphenate.
See Also post-training and pre-training.
## Retrieval Augmented
Generation (RAG)
On ﬁrst mention, use Retrieval Augmented Generation (RAG). Thereafter,
OK to use RAG. Don’t hyphenate as Retrieval-Augmented.
RGB
Stands for red-green-blue.
Don't spell out. For more information, see Don't spell out common
acronyms.
## 101
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 111 -->

AWS Content Design System
ROM
Stands for read-only memory.
Don't spell out. For more information, see Don't spell out common
acronyms.
root account,
root identity, root
credentials
Don't use when referring to the AWS account root user (account owner).
Refer to the account owner as the AWS account root user. Encourage
users to refrain from using account root user credentials and instead
use IAM user credentials. Terms like AWS account credentials or security
credentials are OK. Refer readers to AWS Account Root User Credentials
vs. IAM User Credentials topic in the AWS General Reference for a
discussion of credentials.
This restriction doesn't apply to the terms root account, root identity, or
root credentials that exists within a speciﬁc service, such as Amazon EC2
or AWS Organizations
root user
On ﬁrst mention, use AWS account root user.
RSA
Stands for Rivest-Shamir-Adleman. A public key cryptosystem named for
the initials of its creators. OK not to spell out.
RubyGems
Name of the package manager. Use gem for individual libraries.
runtime (adj., n.)
Can be used as an adjective (for example, runtime environment) or as a
noun (for example, at runtime).
Don't use run time or run-time.
See also execute, execution.
Note: App Runner uses  runtime as a synonym for instance. Follow
guidance for instance in App Runner documentation.
## S
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
(s) or (es)
Don’t use (s) or (es) on the end of a singular noun to indicate that the
noun can be singular or plural.
See Also ???TITLE???.
## 102
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 112 -->

AWS Content Design System
S3 bucket
Use to refer to general purpose buckets in Amazon S3. If this text is the
ﬁrst mention of Amazon S3, use Amazon Simple Storage Service (Amazon
S3) bucket. If the audience is already familiar with Amazon S3, you can
use Amazon S3 bucket on ﬁrst reference and S3 bucket thereafter. If
you're frequently using S3 bucket in a piece of text, you can further
shorten the reference to bucket.
Amazon S3 has multiple bucket types. The most commonly used bucket
type is the general purpose bucket (the original S3 bucket type). Amazon
S3 directory buckets and table buckets have specialized uses. If your
customer must use a bucket type other than a general purpose bucket,
say Amazon S3 directory bucket, S3 directory bucket, Amazon S3 table
bucket, or S3 table bucket on ﬁrst reference as needed. Thereafter, use
directory bucket or table bucket.
If you're using a mix of bucket types in the same piece of text, clarify for
each reference whether it's a general purpose bucket, a directory bucket,
or a table bucket. In cases where you're using multiple bucket types, use
Amazon S3 general purpose bucket or S3 general purpose bucket on ﬁrst
reference to a general purpose bucket and use general purpose bucket
thereafter.
See Also AWS resources.
SAML 2.0
Stands for Security Assertion Markup Language. Note that we ONLY
support version 2.0, so be sure to use SAML 2.0 on ﬁrst mention.
Don't spell out. For more information, see Don't spell out common
acronyms.
SAML solution
Don’t use.
SAML technology
Don’t use.
sandbox
One word.
scale in, scale out
In EC2 Auto Scaling, use scale in, scale out.
scale up, scale down
Don't hyphenate. For more information, see hyphen (-) in Punctuation.
screenshot
One word.
## 103
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 113 -->

AWS Content Design System
SDK
Stands for software development kit.
Don't spell out. For more information, see Don't spell out common
acronyms.
## Search Data Format
(SDF)
On ﬁrst mention, use Search Data Format (SDF). Thereafter, OK to use
SDF.
search hits
Don't use. Use search results instead.
For more information, see Writing basics.
See Also hit.
## Secure Hash Algorithm
(SHA)
On ﬁrst mention, use Secure Hash Algorithm (SHA). Thereafter, OK to use
SHA.
security
When you discuss security-enhancing features or tools, don't make
statements that promise absolute security, safety, or privacy.
AWS style
• This security feature can help with...
• This security feature is designed to...
• Comparatives are also OK: stricter, more secure, better security
Not AWS style
• This feature protects your data from hackers.
security control
framework
Don't capitalize.
security group
Don't capitalize.
semicolon
See semicolon (;) in Punctuation.
## Sender Policy
Framework (SPF)
On ﬁrst mention, use Sender Policy Framework (SPF). Thereafter, OK to
use SPF.
server (related terms)
• application server (not application-tier server)
• jump server (not jump host)
## 104
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 114 -->

AWS Content Design System
• mirror server
• server farm
• server instance
• web frontend (WFE) server
• witness server

server-side encryption
(SSE)
On ﬁrst mention, use server-side encryption (SSE). Thereafter, OK to use
SSE. AWS KMS supports three modes of server-side encryption:
• SSE-S3, where Amazon S3 manages the keys
• SSE-C, where the customer manages the keys
• SSE-KMS, where KMS manages the keys
service
When describing chat-based AI, use to describe an AWS conversational
AI assistant or experience in its role as an AWS service.
When describing a web service, see web service, Amazon Web Services
(AWS).
For more information, see Describing chat-based AI.
service-linked role
(SLR)
On ﬁrst mention, use service-linked role (SLR). Thereafter, OK to use SLR.
Always hyphenate service-linked. Don’t use Service Linked Role.
For more information, see hyphen (-) in Punctuation.
service-oriented
architecture (SOA)
On ﬁrst mention, use service-oriented architecture (SOA). Thereafter, OK
to use SOA. Hyphenate service-oriented.
For more information, see hyphen (-) in Punctuation.
session (n., v.)
When describing chat-based AI, use interchangeably with chat (as a
noun). Use for speciﬁcity or to avoid confusion with chat (as a verb).
For more information, see Describing chat-based AI.
set up (v.), setup (n.,
adj.)
Use set up as a verb (To set up a new user...). Use setup as a noun or
adjective (To begin setup...).
## 105
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 115 -->

AWS Content Design System
shall
Don’t use except where required for speciﬁc legal content.
See Also must and should.
shared responsibility
model
Security model wherein AWS and customers share responsibility for
security.
SharePoint
On ﬁrst mention, use Microsoft SharePoint. Recent versions include:
• SharePoint 2013
• SharePoint 2010
• SharePoint 2010 for Internet Sites, Enterprise Trial
SharePoint 2010 glossary
should
Don’t use should as a substitute for will or must. Should can introduce
uncertainty and is often unnecessary. Before using should, consider
these questions:
• Is an action required?
• Is an action recommended?
• Is an action optional?
• Is an outcome expected?
• Is an outcome possible?
• Is a state actual?
• If it should happen, will it?
• If I should do it, must I?
For recommendations, use “we recommend” or “consider.” For more
information, see Describing requirements and recommendations.
AWS style
• Look for the following log ﬁles to troubleshoot the error.
• The name must be unique within your account.
• Use tagging to help identify resources that you want to clean up.
• If successful, the output looks like the following.
## 106
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 116 -->

AWS Content Design System
Not AWS style
• You should ﬁnd the following log ﬁles to troubleshoot the error.
• The name should be unique within your account.
• Use tagging to help identify resources that should be cleaned up.
• The output should look like the following.
For more information, see Writing basics, Modal verbs, and Words that
can help clarify.
See Also might, must, and would.
shut down
Use in reference to quitting an application. Don't use terminate for
applications. See terminate.
sign in (v.), sign-in
(adj., n.)
Use sign in as a verb in speciﬁc reference to signing in to the console,
never log in. Use sign-in as an adjective or noun (for example, Use your
sign-in credentials.).
For more information, see hyphen (-) in Punctuation.
Don't use sign into.
Don't use for Amazon EC2 instances and other
See also log in (v.), login (adj., n.).
## Simple Object Access
Protocol (SOAP)
See SOAP.
simple, simply
Don't use. Both simple and simply are not neutral in tone and might
sound condescending to some users. If you mean only, use only instead.
See Also easy, easier, just, and only.
since
Use only to describe time events. Don't use in place of because.
For more information, see Global English.
single quotation marks
## (' ')
See quotation marks (' ' and " ") in Punctuation.
## 107
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 117 -->

AWS Content Design System
single sign-on
Hyphenate sign-on. Don’t spell out as single sign on. Avoid SSO as an
acronym if possible, to avoid confusion with the retired service name
AWS Single Sign-On (AWS SSO).
For more information, see hyphen (-) in Punctuation.
single-node
Hyphenate.
For more information, see hyphen (-) in Punctuation.
See Also multi-node.
single-root I/O
virtualization (SR-IOV)
On ﬁrst mention, use single-root I/O virtualization (SR-IOV). Thereafter,
OK to use SR-IOV.
slash (/)
See forward slash (/) in Punctuation.
slave
Don't use.
Use a service-appropriate description. For example, in discussing
database replication, use replica, secondary, or standby. For example, in
machine learning (ML), use member.
For more information, see Inclusive language.
See also master.
smart card
Two words.
smartphone
One word.
SOAP
Stands for Simple Object Access Protocol.
Don't spell out. For more information, see Don't spell out common
acronyms.
software as a service
(SaaS)
On ﬁrst mention, use software as a service (SaaS). Thereafter, OK to use
SaaS.
For more information, see Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website.
solid state drive (SSD)
See SSD.
solutions architect
Not solution.
## 108
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 118 -->

AWS Content Design System
spam
Mass noun, no plural. For example, How much spam do you get? Not,
How many...
spend (n.)
Use as a noun in billing documentation.
## Spot Instance
Capitalized by request of the product team.
Spot price
Capitalize Spot.
SQL
Stands for structured query language.
Don't spell out.
For more information, see Don't spell out common acronyms.
SQL Server
On ﬁrst mention, use Microsoft SQL Server. Thereafter, OK to use SQL
Server. Recent versions include:
• SQL Server 2012 [ Enterprise | Business Intelligence | Standard | Web |
Developer | Express ] edition
• SQL Server 2008 R2 [ Datacenter | Enterprise | Standard | Developer
| Workgroup | Web | Compact ] – note that edition as a qualiﬁer isn't
required
• SQL Server 2008 [ Enterprise | Standard | Developer | Workgroup |
Web | Compact ] – note that edition as a qualiﬁer isn't required
For more information, see SQL Server 2012 glossary.
SSD
Stands for solid state drive (SSD).
Don't spell out. For more information, see Don't spell out common
acronyms.
SSH (Secure Shell)
Stands for Secure Shell. Don't use as a verb.
Don't spell out. For more information, see Don't spell out common
acronyms.
AWS style
• Connect by using SSH
## 109
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 119 -->

AWS Content Design System
Not AWS style
• SSH into...
SSL
Stands for Secure Sockets Layer.
Don't spell out. For more information, see Don't spell out common
acronyms.
See also TLS.
SSO user
Don't use. The AWS Single Sign-On (AWS SSO) service has been
rebranded to AWS IAM Identity Center (successor to AWS Single Sign-
On).
Use user or user in IAM Identity Center to refer to users managed in the
IAM Identity Center console.
In IAM Identity Center, workforce user is used to diﬀerentiate a user in
IAM Identity Center from an IAM user.
See also workforce user.
stack set
Use to refer to a speciﬁc resource of AWS CloudFormation StackSets. Two
words. Don’t capitalize.
AWS style
• A stack set has a single template and parameter set.
• You can create stack sets by using either self-managed permissions or
service-managed permissions.
Not AWS style
• A stackset has a single template and parameter set.
• You can create stacksets by using either self-managed permissions or
service-managed permissions.
StackSets
On ﬁrst mention, use AWS CloudFormation StackSets. Thereafter, OK to
use StackSets. Use as a singular noun.
## 110
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 120 -->

AWS Content Design System
AWS style
• AWS CloudFormation StackSets extends the capability of stacks. This
section helps you get started with using StackSets.
• StackSets is supported in multiple AWS Regions.
Not AWS style
• AWS CloudFormation StackSets extends the capability of stacks.
This section helps you get started with using AWS CloudFormation
StackSets.
• StackSets are supported in multiple AWS Regions.
standalone
One word.
standard Region
Don't use when referring to AWS Regions. Use commercial Region
instead.
See Region.
standby
Don’t hyphenate.
start, launch
You start an application but launch an instance, environment, or cluster.
startup (n.), start up
(v.)
Don't hyphenate. Use startup as a noun (for example, The following
startup procedure guides you through...). Use start up as a verb (You can
start up the instances by...). Do not use as a colloquial term for a new
business.
step function
Don't use. For the service, use AWS Step Functions or Step Functions. For
elements in the service, use workﬂow, step, or Lambda function.
storage gateway
Generic use. Distinguish from AWS Storage Gateway, the service.
stored volume
Don't use gateway-stored.
structured query
language (SQL)
See SQL.
subnet
One word.
## 111
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 121 -->

AWS Content Design System
such as
Use to introduce one or more examples of something that's already
mentioned (for example, links such as cross-reference links). Limit the
number of examples that you use, and don't use etc., or so on because
examples introduced by such as aren't exhaustive in nature.
AWS style
• Neptune powers graph use cases such as recommendation engines,
knowledge graphs, and network security.
• To perform basic administrative tasks on your AWS Batch compute
resources, such as updating software or accessing diagnostic logs, you
must connect to the instance using SSH.
• You must conﬁgure permissions to allow an IAM entity (such as a user,
group, or role) to create, edit, or delete a service-linked role.
See Also like.
superuser
One word.
support agent
Use when describing human support roles. On ﬁrst mention, use
support agent. Thereafter, OK to use agent. Use human support agent to
distinguish for the customer whether they are interacting with a human
support agent or a generative AI service.
For more information, see Conversational AI interfaces and Describing
chat-based AI.
SYN ﬂood
A type of malicious attack.
SysOps
Note capitalization.
## T
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
TCP
Stands for Transmission Control Protocol.
Don't spell out. For more information, see Don't spell out common
acronyms.
TCP passthrough
Don't spell out as Transmission Control Protocol (TCP) passthrough.
## 112
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 122 -->

AWS Content Design System
For more information, see Don't spell out common acronyms.
TCP/IP
Stands for Transmission Control Protocol/Internet Protocol, which is a
suite of protocols also known as the Internet protocol suite.
Don't spell out. For more information, see Don't spell out common
acronyms.
tebibyte (TiB)
Don't use TIB.
For more information, see Units of measure and Units of measure
abbreviations.
terabyte (TB)
Don’t use T, T byte, or TByte.
For more information, see Units of measure and Units of measure
abbreviations.
terminate
Use in reference to deleting an EC2 instance, which permanently erases
its data. Use stop for taking an instance oﬄine. Stopping halts further
billing but allows for restarting with all the data intact. Don't use shut
down for instances. However, shutting-down is a valid status.
See also shut down.
threat actor
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
TiB
tebibyte
TIFF
Stands for Tagged Image File Format.
Don't spell out. For more information, see Don't spell out common
acronyms.
time frame
Two words. Don't hyphenate.
Don't use timeframe or time-frame.
time out (v.), timeout
(adj., n.)
Don't hyphenate. Use time out as a verb (The request will time out if the
server doesn't respond...). Use timeout as a noun or adjective (You can set
the timeout interval by entering a number into...).
## 113
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 123 -->

AWS Content Design System
time series, Timeseries,
time-series
Two words. Don't capitalize. Don't hyphenate.
time zone
Two words. Don't hyphenate.
Don't use timezone or time-zone.
timeline
One word.
timestamp
One word. Don't hyphenate.
Don't use time stamp or time-stamp.
'tis
Don't use.
For more information, see Contractions.
TLS
Stands for Transport Layer Security, the successor to SSL. Both
are cryptographic protocols that are used to secure network
communications.
Don't spell out. For more information, see Don't spell out common
acronyms.
See also SSL.
## Tn
T stands for terabyte. The following integer n is the raw capacity in
terabytes. For example, T40 = 40 TB, T80 = 80 TB, and T100 = 100 TB.
top-k
Use lowercase with a hyphen. Don't localize.
top-p
Use lowercase with a hyphen. Don't localize.
top priority
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
touch screen (n.),
touch-screen (adj.)
Two words as a noun. Hyphenate as an adjective.
transformer model
Don’t capitalize. Don’t abbreviate as TM.
## Transparent Data
Encryption (TDE)
On ﬁrst mention, use Transparent Data Encryption (TDE). Thereafter, OK
to use TDE.
## 114
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 124 -->

AWS Content Design System
turn on, turn oﬀ
Use turn on and turn oﬀ in reference to a toggle UI element to describe
switching a setting or mode on or oﬀ.
Don't use choose, select, clear, slide, enable, or disable for a toggle.
For making a feature available or unavailable for an account or device,
use enable. For setting up an account or associating details with an
account, use activate.
AWS style
• Turn on Expiration date, and then choose Conﬁrm.
• To turn on animation, set to true. To turn oﬀ animation, set to false.
Not AWS style
• Enable Expiration date, and then choose Conﬁrm.
For more information, see the section called “Procedure”.
See Also activate, deactivate and enable, disable.
tutorial, walkthrough
Use tutorial for guided instructions in user and developer guides. OK to
use walkthrough in whitepapers.
'twas
Don't use.
For more information, see Contractions.
'twere
Don't use.
For more information, see Contractions.
type
See enter.
## U
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
UDP
Stands for User Datagram Protocol.
## 115
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 125 -->

AWS Content Design System
Don't spell out. For more information, see Don't spell out common
acronyms.
UDP ﬂood
A type of malicious attack.
UI
Stands for user interface.
When describing chat-based AI, can be used interchangeably with
interface.
Don't spell out. For more information, see Don't spell out common
acronyms.
For more information, see Describing chat-based AI.
ultra-low latency (n.),
ultra-low-latency (adj.)
Hyphenate.
For more information, see hyphen (-) in Punctuation.
See Also low latency (n.), low-latency (adj.).
uncomment
OK to use sparingly. Write around it if possible.
## Unicode
## Transformation
Format (UTF)
See UTF.
uniform resource
locator (URL)
See URL.
unique identiﬁer
Don't use as a synonym for GUID or UUID.
Unix, UNIX
Unix and UNIX aren't the same. UNIX is a trademarked name that's
owned by The Open Group. In most cases, you should use Unix.
For more information, see Unix (Wikipedia).
See Also operating system (OS).
unresponsive
Don't use nonresponsive. Don't hyphenate.
update (adj., n., v.)
Use update as a noun or adjective to refer to a set of changes (other
than a new release or version) to an application, service, or dataset. Use
## 116
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 126 -->

AWS Content Design System
update as a verb to refer to the act of installing or implementing an
update.
See Also upgrade.
upfront (adj.n.), up
front (adv.)
Use upfront as a noun or adjective (The upfront cost...). Use up front as
an adverb (An initial payment should be made up front...).
upgrade (adj., n., v.)
Use upgrade as a noun or adjective to describe a new release or version
of an application, service, or dataset. Use upgrade as a verb to refer to
the act of installing or implementing an upgrade. If the change to the
application isn't a new release or version, don't use upgrade. Use update
instead.
See Also update.
URI
Stands for uniform resource identiﬁer.
Don't spell out. For more information, see Don't spell out common
acronyms.
URL
Stands for uniform resource locator.
Don't spell out. For more information, see Don't spell out common
acronyms.
US
No periods, as speciﬁed in the Chicago Manual of Style.
Exception: U.S. is correct usage in documentation, whitepapers, or slide
decks that deal with the U.S. government, which uses periods.
user
In most cases, replace with the more direct form you. Reserve user for
cases where you're referring to a third party (not the audience that
you're writing for).
user-deﬁned tag
Use to describe a custom tag that the customer creates. Don't use to
describe an AWS generated tag that AWS creates automatically.
Hyphenate user-deﬁned.
For more information, see hyphen (-) in Punctuation.
AWS style
## 117
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 127 -->

AWS Content Design System
• There are usage requirements for the number of user-deﬁned tags
that you can add to an AWS resource.
Not AWS style
• There are usage requirements for the number of user-created tags
that you can add to an AWS resource.
username
One word.
using
If it causes ambiguity, avoid using. Instead, use by using or that use.
See Also by using, that use, using.
UTC
UTC is the oﬃcial international abbreviation of Coordinated Universal
Time. Use this instead of GMT when describing times and time zones.
For the greatest clarity, don't use UTC itself as a time zone to refer to
Greenwich time. Rather, use it as a notation standard that's the basis for
denoting speciﬁc time zones worldwide. Use the UTC±N format when
denoting speciﬁc time zones (for example, UTC-8).
Don't spell out. For more information, see Don't spell out common
acronyms.
AWS style
• By default, Amazon Linux instances are set to the UTC+0 time zone.
Not AWS style
• By default, Amazon Linux instances are set to the UTC (Coordinated
Universal Time) time zone.
UTF
Stands for Unicode Transformation Format.
Don't spell out. For more information, see Don't spell out common
acronyms.
UUID
Stands for Universally Unique IDentiﬁer. UUIDs are universal IDs deﬁned
in RFC 4122.
See Also GUID.
## 118
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 128 -->

AWS Content Design System
## V
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
v., vs., versus
Don't use. Use compared to or compared with instead.
For more information, see Writing basics.
AWS style
• What is the annual cost of maintaining your workload on premises
compared to AWS?
Not AWS style
• What is the annual cost of maintaining your workload on premises vs.
AWS?
version
Describes a speciﬁc API version, which might change with a software
release. Use this term to describe the changes in an API, such as a new
operation, which also refers to a new WSDL version.
Display the API version in a product title using parentheses. For example,
Amazon E-Commerce Service (API Version 2005-12-25).
via
Don't use. Replace with by using, through, or with, or a more speciﬁc
phrase such as by accessing or by choosing.
For more information, see Writing basics.
See also per.
vice versa
Don't use. Replace with the reverse, the other way around, or similar
words.
For more information, see Writing basics.
virgule (/)
See forward slash (/) in Punctuation.
virtual CPU (vCPU)
On ﬁrst mention, use virtual CPU (vCPU). Thereafter, OK to use vPCU.
virtual machine (VM)
On ﬁrst mention, use virtual machine (VM). Thereafter, OK to use VM.
## 119
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 129 -->

AWS Content Design System
virtual private cloud
(VPC)
Frequently confused with Amazon VPC. A virtual private cloud (VPC)
is a networking resource that you create in your AWS account. A VPC
provides a secure infrastructure for deploying cloud applications,
servers, databases, and other resources.
To create or manage a VPC on AWS, you use Amazon Virtual Private
Cloud (Amazon VPC), which is an AWS service.
If referring to the resource, use all lowercase. If referring to the service,
use title case. For ﬁrst and subsequent use guidelines, see AWS oﬀering
names.
AWS style
• Create a virtual private cloud (VPC) in your AWS account.
• Amazon VPC provides features for monitoring the security of your
VPC.
Not AWS style
• Create a Virtual Private Cloud (VPC) in your AWS account.
• Create an Amazon Virtual Private Cloud (Amazon VPC) in your AWS
account.
• You can connect your Amazon VPC to remote networks and users.
For more information about VPCs and Amazon VPC, see the AWS
documentation.
virtual private gateway
Don't abbreviate as VPG. Only abbreviated as VGW to match the
resource ID where space is tight.
See Also customer gateway, internet gateway, and NAT gateway.
virtual private network
See VPN.
virtual routing and
forwarding
Use lowercase.
See also VRF.
## 120
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 130 -->

AWS Content Design System
## Visual Question
Answering (VQA)
Spell out as Visual Question Answering (VQA) on ﬁrst use. Thereafter, OK
to use VQA. Don’t use visual question answering.
viz.
Don't use.
For more information, see Writing basics.
See also etc. and i.e.
volume
See EBS volume.
VPC
Stands for virtual private cloud. If referring to the service, see AWS
oﬀering names for ﬁrst and subsequent use guidelines.
VPC Flow Logs, AWS
## Network Flow Logs
Use initial caps for VPC Flow Logs and AWS Network Flow Logs only when
referring to the feature or service. Use lower case when referring to ﬂow
log resources.
For more information, see AWS oﬀering names for ﬁrst and subsequent
use guidelines.
AWS style
• In the following table, the Version column indicates the VPC Flow Logs
version where the ﬁeld was introduced.
• With VPC Flow Logs enabled for your Amazon VPC, you can capture
ﬂow logs for all the connections in your VPC.
VPN
Stands for virtual private network.
Don't spell out.
VRF
Stands for virtual routing and forwarding.
Spell out in lowercase on ﬁrst mention.
vulnerability
When writing about security, see the AWS Security Messaging Guidelines
on the Growth Strategies (Amazon Security) Wiki.
## W
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
## 121
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 131 -->

AWS Content Design System
WAF
Stands for web application ﬁrewall. Always spell out.
Exception: Don't spell out when referring to AWS WAF. For more
information, see the AWS oﬀering names Wiki.
walkthrough, tutorial
Use tutorial for guided instructions in User and Developer Guides. In
whitepapers, walkthrough is an acceptable alternative.
want
Use when referring to a choice, as opposed to a requirement. Don’t use
wish or desire.
See Also need, need to and would.
warm standby
Don’t hyphenate.
web ACL
On ﬁrst mention, use web access control list (web ACL). Thereafter, OK to
use web ACL. Don't use WACL.
web application
ﬁrewall (WAF)
Always spell out.
Exception: Don't spell out when referring to AWS WAF. For more
information, see the AWS oﬀering names Wiki.
web frontend (WFE)
On ﬁrst mention, use web frontend (WFE). Thereafter, OK to use WFE.
Don't use web front-end or web front end.
web services
Use web services or AWS services to describe more than one of the web
services oﬀered by AWS. Otherwise, where it's important to note the
distinction, use AWS oﬀerings, AWS products, or web services oﬀered by
AWS. Don't use the redundant AWS web services.
Don't use Amazon web services as a generic term for AWS products.
Be sure to use web service only to describe the web service component
of products that include website and other products, such as Amazon
Mechanical Turk. For example: Developers use the Amazon Mechanical
Turk web service to place work for others to complete on the Amazon
Mechanical Turk website.
## Web Services
## Description Language
(WSDL)
On ﬁrst mention, use Web Services Description Language (WSDL).
Thereafter, OK to use WSDL.
## 122
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 132 -->

AWS Content Design System
webpage
Never web page.
website
Never web site.
WebSocket
Don't use Websocket, Web Socket, or websocket.
weighted routing
policy
Don't capitalize.
## Well-Architected
## Framework
Capitalize. Hyphenate Well-Architected.
For more information, see hyphen (-) in Punctuation.
## Well-Architected
## Framework Review
(WAFR)
On ﬁrst mention, use Well-Architected Framework Review (WAFR).
Thereafter, OK to use WAFR.
Don't use WAR or Well-Architected Review.
## Well-Architected Tool
AWS Well-Architected Tool (AWS WA Tool) is a service in the cloud that
provides a consistent process for measuring your architecture using AWS
best practices.
On ﬁrst mention, use AWS Well-Architected Tool (AWS WA Tool).
Thereafter, OK to use AWS WA Tool.
Don't use WAT.
while, although,
whereas
Only use while to mean during an interval of time. Don't use it to mean
although because it's often ambiguous. Whereas is a better alternative to
although in many cases, but it can sound overly formal.
For more information and examples, see Global English.
white
Exercise caution when using terms that contain white.
• Don't use whitelist (use allowlist instead), white day (use open day),
and white hat and their black counterparts. These term pairs are
inappropriate because they have the racist implication of "white is
good, and black is bad." For more information, see Inclusive language.
• Avoid jargon such as white-labelled (use rebranded instead) and white-
box testing (use structural testing).
For more information, see Writing basics.
## 123
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 133 -->

AWS Content Design System
whitelist, whitelisting
Don't use. To describe a list of items that are allowed (not blocked), use
allowlist or a service-appropriate description.
For more information, see Inclusive language.
WHOIS
On ﬁrst mention, you can use a parenthetical to add clarity: WHOIS
("Who is").
## Wi-Fi
Hyphenate. This term is a registered trademark. Note capitalization.
For more information, see hyphen (-) in Punctuation.
wiki, Wiki
Capitalize only when used as a proper noun. For example, when referring
to a site that includes the capitalized version in the name.
wildcard character
A character used to represent one or many characters, such as the
asterisk (*) or question mark (?). Wildcard is one word. Use wildcard
character, not just wildcard.
will
Avoid if possible. Use present tense. By using present tense, you tell the
customer that information is relevant regardless of the time that they’re
reading it. For more information, see Voice and tone.
AWS style
• If you don't set a custom encryption key, Amazon Neptune uses the
default encryption key.
• A detector version deﬁnes the models and rules that are use to
generate fraud predictions.
• In this step, you create and train a model for the event type.
Not AWS style
• If you don't set a customer encryption key, Amazon Neptune will use
the default encryption key.
• A detector version deﬁnes the models and rules that will be used to
generate fraud predictions.
• In this step, you will be creating and training a model for the event
type.
## 124
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 134 -->

AWS Content Design System
See Also would.
Windows PowerShell
Use to refer only to the scripting language on Windows operating
systems to manage Windows computers. For non-Windows operating
systems, use PowerShell. (PowerShell is also an open-source project for
Mac and Linux.) For more information, see the PowerShell Glossary.
See Also PowerShell.
wish, want, need
Don't use wish. Use want for a choice and need for a requirement.
AWS style
• Repeat the cycle as needed to get the results that you want.
• If you want to test the event, enter the following variable values.
• Edit the monthly amounts based on your situation.
Not AWS style
• Repeat the cycle to get the results that you desire.
• If you wish to test the event, enter the following variable values.
• Edit the monthly amounts as desired.
See Also desire and would.
wizard
Use to describe a series of related steps in a console. Use sparingly. Write
around it if you can.
worker node
Avoid if possible. Use node instead. In Amazon Elastic Kubernetes Service
(Amazon EKS), a node can refer to either an EC2 instance or a Fargate
node. The term worker node is being phased out by both Kubernetes and
AWS.
workﬂow
One word.
workforce identity
An IAM identity type for users managed in the AWS IAM Identity Center
(successor to AWS Single Sign-On) console.
See also workforce user.
## 125
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 135 -->

AWS Content Design System
workforce user
A type of user that is managed in the AWS IAM Identity Center
(successor to AWS Single Sign-On) console. The generic term user can
also be used as a substitute for workforce user.
See also workforce identity.
would
Avoid is possible. Would can introduce uncertainty.
When describing a customer's choice, use want to, instead of would like
to, to be more direct.
AWS style
• In this example, the environment schema looks like the following.
• The comparison shows what the CPU utilization is if you set your CPU
to the recommended settings during the analysis period.
Not AWS style
• In this example, the environment schema would be like the following.
• The comparison shows you what the CPU utilization would have been
if you had set your CPU to the recommended settings during the
analysis period.
See Also could, should, will, and wish, want, need.
## X-Y-Z
# | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S | T | U | V | W | X-Y-Z
XML
Stands for Extensible Markup Language.
Don't spell out. For more information, see Don't spell out common
acronyms.
YAML
Stands for YAML Ain't Markup Language.
Don't spell out. For more information, see Don't spell out common
acronyms.
## 126
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 136 -->

AWS Content Design System
yet
Don't use to refer to AWS supporting operating systems, software, or
features. Don't use to imply support for something in the future. For
more information about using forward-looking terms, see Messaging
Dos and Don’ts on the AWS Legal Pathﬁnder website.
See also at this time and currently.
yobibyte (YiB)
Don’t use YIB.
For more information, see Units of measure and Units of measure
abbreviations.
yottabyte (YB)
Don't use Y, Y byte, or YByte.
For more information, see Units of measure and Units of measure
abbreviations.
zebibyte (ZiB)
Don’t use ZIB.
For more information, see Units of measure and Units of measure
abbreviations.
zero trust
Don't capitalize.
zettabyte (ZB)
Don’t use Z, Z byte, or ZByte.
For more information, see Units of measure and Units of measure
abbreviations.
## Zonal
Capitalize when referring to Availability Zones.
zone
Use sparingly as a synonym for Availability Zone.
## 127
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 137 -->

AWS Content Design System
AWS style
This section of the content design system covers AWS style and provides guidelines for all AWS
content. These guidelines are owned and maintained by the Content Quality (CQ) team. To provide
feedback, see AWS Style Guide requests.
What's in this section
• the section called “Global English” – Write for our worldwide audience.
• the section called “AWS voice and tone” – Address customers with a consistent AWS voice and
tone.
• the section called “Artiﬁcial intelligence (AI)” – Keep informed about how to refer to AI at AWS.
• the section called “Accessibility” – Earn trust by presenting content based on our customers'
variety of lived experiences, unique competencies, and diverse perspectives.
• the section called “Search engine optimization” – Help customers to ﬁnd the content they're
looking for.
• Other resources – Consult other resources that support writing and editing AWS content.
Featured resources
• the section called “Global English”
• the section called “Artiﬁcial intelligence (AI)”
• Legal and security
Related resources
• Content patterns – Content templates and patterns within this content design system.
• the section called “Content components” – Content components within this content design
system.
• Legal and security – Legal and security guidelines within this content design system.
• AWS oﬀering names Wiki – Oﬃcial list of AWS service names, brand preﬁx requirements,
resource examples, localization guidance, and marketing categories.
• Cloudscape Design System – User interface guidelines, front-end components, design resources,
and developemental tools.
## 128
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 138 -->

AWS Content Design System
## Topics
## • Accessibility
## • Acronyms
• Alerts and messages
• Artiﬁcial intelligence (AI)
• Blog posts
• AWS voice and tone
## • Capitalization
• Consoles and user interfaces
## • Global English
## • Images
• Inclusive language
• Links and cross-references
## • Lists
• Notes and other special messages
## • Numbers
• Parallel information
• Plural and singular nouns
## • Prepositions
## • Procedures
## • Punctuation
• Search engine optimization
## • Tables
• Titles and headings
• Writing basics
• Other resources
## Accessibility
When you create and design websites, you must follow accessibility guidelines for user interfaces
and documentation. Accessibility guidelines at AWS help all customers perceive, navigate, and
interact with our content.
## Accessibility
## 129
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 139 -->

AWS Content Design System
To build accessible experiences, our guidelines are based on recommendations from stakeholder
communities, such as the Web Accessibility Initiative (WAI) by World Wide Web Consortium (W3C).
For information about AWS Accessibility Customer Critical Requirements, see the AWS Accessibility
Requirements wiki.
This topic provides guidelines and resource links to help you make sure that your content is
accessible.
## Topics
• Accessibility in content
• Accessibility in content elements
• Accessibility on the console and UI
• Other resources
Accessibility in content
The following sections provide accessibility guidelines in AWS content.
## Topics
• Color, sounds, and shapes
• Spatial direction (location)
• Device-agnostic verbs
Color, sounds, and shapes
Color, sound, and shape terminology isn't accessible to many customers. Refer to the following
guidelines to make sure that all customers can understand and access your content.
## Do
• Refer to a verbatim UI label or title in an interface, not the color of the UI element.
• Refer to the actual text in a replaceable text example.
• Refer to the object label name in a graphical image, not the shape.
• Use colors that pass the minimum contrast for their size.
Don't
Accessibility in content
## 130
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 140 -->

AWS Content Design System
• Don't refer to the shape alone.
• Don't use sound as a reference point.
For more information about color, sound, shape, and other requirements, see the AWS Accessibility
Requirements Wiki, Accessibility Critical Customer Requirements (CCR) Wiki, and Use of color on
the WCAG website.
Spatial direction (location)
To accommodate customers who can't perceive spatial location, we use consistent terminology and
verbatim UI labels. Customers can then locate UI elements and components by using a search tool
for that speciﬁc text.
To help customers navigate the UI or ﬁnd content, follow these guidelines:
## Do
• Indicate a location in an interface, use procedure phrasing and the UI label or title. In service
documentation, use the <guilabel> tag for UI labels.
• Refer to a focal point in a console by the UI label. If it doesn’t have a UI label, refer to the
approved name for the UI element or parts of the console.
• Refer to a spatial location only if it’s inline with the UI name or label. Such as the left navigation
pane.
• Use the terms preceding, previous, or following to refer to content or component locations on the
same page.
• Direct customers to something in an interface, and use verbatim reference to the UI label or
heading.
Don't
• Don't use unapproved or inconsistent names or labels.
• Don’t use the terms above or below in documentation, such as “the example above” or “the table
below.”
• Don’t refer to locations like left, right, up, down, lower, and so on, unless you also refer to
verbatim UI text (label). For example, refer to the text (label) on a button label.
AWS style
Accessibility in content
## 131
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 141 -->

AWS Content Design System
• Your ARN is located to the right of the Studio resources section.
• In the navigation pane, choose Deployments.
• In the left navigation pane, choose Deployments.
Not AWS style
• Your ARN is located below.
• On the left, choose Deployments.
Device-agnostic verbs
Not everyone uses a mouse or keyboard, so use device-agnostic (independent) verbs. For example,
use choose instead of click, and use enter instead of type. For more information about which verbs
to use for UI elements, see Procedure phrasing.
Accessibility in content elements
This section provides guidelines or resources for making content elements accessible, such as links,
headings, and more.
## Topics
• Accordions and tabs (collapsible content)
## • Headings
## • Images
## • Tables
## • Links
Accordions and tabs (collapsible content)
Because tabs and accordions hide content, to improve accessibility and search engine optimization
(SEO), we recommend that you write lead-in content that summarizes the hidden content. For
clarity, refer to the tab or accordion headings by their verbatim heading labels.
For more information about tab and accordion accessibility, see Tabs and Expandable sections in
the AWS Design System (Cloudscape) website.
Accessibility in content elements
## 132
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 142 -->

AWS Content Design System
## Headings
Headings and titles provide page navigation to screen readers and other assistive technologies.
Screen readers use heading tags to create a more accessible experience. Use appropriate headings
to mark sections (don't only use bold text), and follow the correct headings hierarchy in topics. For
more information, see the section called “Lists” and the section called “Titles and headings”.
For information about creating accessible headings in the AWS Management Console, see
Accessible headings in the AWS design system (Cloudscape) website.
## Images
There are several factors that make images accessible. For example, all images should have alt text
and lead-in content.
## Tables
For information about creating accessible tables, see the section called “Tables”.
## Links
Use link text that describes the target page's topic, such as the title of the page. Don't use vague
or device-speciﬁc wording like "click here" or "this link." For more information, see Links and cross-
references. See also Link and accessibility in Cloudscape.
Accessibility on the console and UI
The Cloudscape team works to make the fundamental building blocks of the UI accessible for
everyone who uses our console interfaces. For more information, see the Accessibility learning
resources Wiki and Accessibility on the Cloudscape Design System website.
Other resources
• W3C Introduction to Web Accessibility
• Accessibility at Amazon
• AWS Accessibility site
• AWS Accessibility Wiki
• ARIA Authoring Practices Guide (APG)
Accessibility on the console and UI
## 133
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 143 -->

AWS Content Design System
## Acronyms
In this topic, the term acronym refers to all types of abbreviations. This includes both acronyms
(words formed by the initial letters of a series of words pronounced as a word, such as BASIC)
and initialisms (words formed by the initial letters of a series of words, pronounced as a series of
letters, such as PDF and HTML).
When to spell out acronyms
Spell out acronyms the ﬁrst time that you use them on a page and follow them with the acronym
in parentheses. Use the format spelled-out term (acronym). On subsequent use, use the
acronym alone.
For more speciﬁc guidance, see the following sections.
• Spell out for clarity
• Don't spell out common acronyms
Spell out for clarity
In general, spell out acronyms once on a page. However, you can spell them out more often for
clarity. Spelling out an acronym helps in the following situations:
• The acronym is uncommon.
• There's more than one acronym in a sentence.
• You're deﬁning the acronym as a term or concept.
AWS style
• The Amazon Resource Name (ARN) for the public certiﬁcate issued by ACM. This ARN is used to
validate custom domain ownership.
• --sns-topic-arn: The Amazon Resource Name (ARN) of the SNS topic that's created for event
notiﬁcation.
Not AWS style
• The ARN of the public certiﬁcate issued by ACM to validate ownership of your custom domain.
## Acronyms
## 134
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 144 -->

AWS Content Design System
• --sns-topic-arn: The ARN of the SNS topic created for event notiﬁcation.
Don't spell out common acronyms
Some acronyms are better known than their spelled-out counterparts or might be used almost
exclusively. These include industry standard protocols, markdown and programming languages,
and common ﬁle formats. For these acronyms, we recommend that you don’t spell them out.
The following table lists acronyms that we recommend you don't spell out.
## Acronym
Spelled out term
## 3D
three-dimensional
AI
artiﬁcial intelligence
AI-generated
artiﬁcial intelligence–generated
API
application programming interface
ASCII
American Standard Code for Information
## Interchange
BASIC
Beginner's All-Purpose Symbolic Instruction
## Code
CPU
central processing unit
DNS
## Domain Name System
DOS
disk operating system
FAQ
frequently asked questions
FTP
## File Transfer Protocol
generative AI
generative artiﬁcial intelligence
GIF
## Graphics Interchange Format
HTML
hypertext markup language
When to spell out acronyms
## 135
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 145 -->

AWS Content Design System
## Acronym
Spelled out term
HTTP
hypertext transfer protocol
HTTPS
hypertext transfer protocol secure
HTTP(s)
Use to refer to both protocols, HTTP and
HTTPS.
## I/O
input/output
ID
identiﬁer
IP
Internet protocol
IPv4
Internet protocol version 4
IPv6
Internet protocol version 6
IT
information technology
JPEG
## Joint Photographic Experts Group
JSON
JavaScript Object Notation
MQTT
## Message Queuing Telemetry Transport
NAT
network address translation
NGINX
engine x
OpenSSL
## Open Secure Sockets Layer
PDF
## Portable Document Format
RAM
random access memory
REST
## Representational State Transfer
RGB
red-green-blue
ROM
read-only memory
When to spell out acronyms
## 136
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 146 -->

AWS Content Design System
## Acronym
Spelled out term
SAML
## Security Assertion Markup Language
SDK
software development kit
SOAP
## Simple Object Access Protocol
SQL
structured query language
SSD
solid state drive
SSH
## Secure Shell; Secure Socket Shell
SSL
## Secure Sockets Layer
TCP
## Transmission Control Protocol
TCP/IP
## Transmission Control Protocol/Internet
## Protocol
TIFF
## Tagged Image File Format
TLS
## Transport Layer Security
UDP
## User Datagram Protocol
UI
user interface
URI
uniform resource identiﬁer
URL
uniform resource locator
UTC
## Coordinated Universal Time
UTF
## Unicode Transformation Format
VPN
virtual private network
XML
## Extensible Markup Language
YAML
YAML Ain't Markup Language
When to spell out acronyms
## 137
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 147 -->

AWS Content Design System
## Plurals
Make an acronym plural by adding an s to the end of it. Don't add an apostrophe. For more
information about plurals, see Plural and singular nouns-->.
AWS style
• Amazon Machine Image (AMI)
• Amazon Machine Images (AMIs)
Not AWS style
• AMI's (for plural)
## Note
Both FAQ and FAQs are correct, but they mean diﬀerent things. Use FAQ as the abbreviation
of frequently asked questions. Use FAQs to refer to multiple FAQ sections or topics.
Articles an and a
How an acronym is pronounced determines whether you use the article an or a before it. If it's
pronounced with an initial vowel sound, use an. Otherwise, use a.
The following table lists acronyms with their appropriate article.
## Acronym
An or a
## Example
Pronunciation guide
AI
an
an AI
AY-eye
AI/ML
an
an AI/ML
AY-eye-EM-ehl
API
an
an API Operation
AY-PEE-eye
ASCII
an
an ASCII character
ASS-kee, ASK-kee
FTP
an
an FTP server
EFF-tee-pee
## Plurals
## 138
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 148 -->

AWS Content Design System
## Acronym
An or a
## Example
Pronunciation guide
HTML
an
an HTML element
AYTCH-TEE-EHM-ehl
HTTP
an
an HTTP request
AYTCH-tee-tee-pee
## I/O
an
an I/O device
EYE-oh
LLM
an
an LLM
EHL-ehl-ehm
ML
an
an ML
EM-ehl
NGINX
an
an NGINX proxy
EN-jin-EKS
RGB
an
an RGB color value
AHR-gee-bee
SaaS
a
a SaaS service
SASS
SAML
a
a SAML assertion
SAM-ehl
SQL
a
a SQL command
SEE-kwel
SSH
an
an SSH session
ESS-ESS-aytch
URL
a
a URL
YOO-AHR-ehl
Headings and titles
If the ﬁrst use of an acronym is in a heading, retain the acronym in the heading. Then write out the
term in the following body text, followed by the acronym in parentheses. Don't spell out the term
in the heading with the acronym included in parentheses. If the ﬁrst use of the service name is in a
title or heading, use the short form of the name in the heading. Then use the long form followed
by the short form in parentheses in the following body text.
For more information about how to use acronyms in titles and headings, see AWS service name
abbreviations and Titles.
AWS service name abbreviations
For AWS services, use the long name followed by the short name in parentheses on ﬁrst use on
each page.
Headings and titles
## 139
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 149 -->

AWS Content Design System
• First use – Full name (or long form). Use on ﬁrst mention in most marketing content followed by
the short name in parentheses. Also use for guide names in technical documentation. Blog posts,
slides, graphics, and tweets can use the approved short form (in Subsequent use) on ﬁrst use.
• Subsequent use – Short name (or short form). Use after the full name on second and subsequent
use. If clarity is needed, you can reuse the full name. Some services require the full name on
subsequent use for legal or branding reasons.
• Limited use (use with caution) – Extra-short name. Use the extra-short name only where space
is very tight and the context is clear (slides, console, tweets).
• Don't use – Some service names require Amazon or AWS on all uses or prohibit certain short
forms of the service name.
AWS style
First use
Subsequent use
Limited use (use with
caution)
AWS Auto Scaling
AWS Auto Scaling
## Auto Scaling
AWS Cloud Development Kit
(AWS CDK)
AWS CDK
CDK
AWS Database Migration
Service (AWS DMS)
AWS DMS
DMS
AWS Identity and Access
Management (IAM)
IAM

## Exceptions
• For Amazon Elastic Compute Cloud (Amazon EC2) and Amazon Simple Storage Service (Amazon
S3), using the full service name on ﬁrst reference in the guide is adequate. You don't need to
repeat it in each topic.
AWS service name abbreviations
## 140
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 150 -->

AWS Content Design System
AWS service names in headings
If the ﬁrst use of the service name is in a title or heading, use the short form of the name in the
heading. Then use the long form followed by the short form in parentheses in the following body
text. For more information about how to use service names in titles and headings, see Titles.
Latin abbreviations
Don't use Latin abbreviations and phrases. For more information, see Write for a global audience.
Units of measure abbreviations
In general, spell out abbreviations that end with -bit or -byte. Use abbreviations only with numbers
in speciﬁc measurements. Always include a space between the number and unit. Abbreviations that
are well known and don't need to be spelled out on are KB, MB, GB, and TB.
For more information, see Units of measure.
AWS style
• 128 TB
Not AWS style
• 128 terabytes
• 128TB
Common units of measure abbreviations are included in the following table.
## Abbreviation
## Unit
## Guidance
b
bit

bps
bits per second
Don't use b/second or b/s.
## Bps
Bytes per second

## B
byte

EB
exabyte

AWS service names in headings
## 141
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 151 -->

AWS Content Design System
## Abbreviation
## Unit
## Guidance
EiB
exbibyte
Don't use EIB.
GB
gigabyte
Don’t use G, G byte, or GByte.
## Gb
gigabit

## Gbps
gigabits per second
Don't spell out as Gb per
second. Don't use Gb/second
or Gb/s.
GiB
gibibyte
Don't use GIB.
GiBps
gibibytes per second
Don't spell out as GiB per
second. Don't use GiB/second
or GiB/s.
KB
kilobyte
Don't use K, K byte, or KByte.
## Kbps
kilobits per second
Don't spell out as Kb per
second. Don't use Kb/second
or Kb/s.
KBps
kilobytes per second
Don't spell out as KB per
second. Don't use KB/second
or KB/s.
KiB
kibibyte
Don't use KIB.
KiBps
kibibytes per second
Don't spell out as KiB per
second. Don't use KiB/second
or KiB/s.
## Mb
megabit
Don’t abbreviate, unless in UI.
MB
megabyte
Don’t use M, meg, M byte, or
MByte.
Units of measure abbreviations
## 142
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 152 -->

AWS Content Design System
## Abbreviation
## Unit
## Guidance
## Mbps
megabits per second
Don't spell out as Mb per
second. Don't use Mb/second
or Mb/s.
MBps
megabytes per second
Don't spell out as MB per
second. Don't use MB/second
or MB/s.
MiB
mebibyte
Don't use MIB.
MiBps
mebibytes per second
Don't spell out as MiB per
second. Don't use MiB/second
or MiB/s.
PB
petabyte
Don’t use P, P byte, or PByte.
PiB
pebibyte
Don't use PIB.
TB
terabyte
Don’t use T, T byte, or TByte.
TiB
tebibyte
Don't use TIB.
YB
yottabyte
Don't use Y, Y byte, or YByte.
YiB
yobibyte
Don't use YIB.
ZB
zettabyte
Don’t use Z, Z byte, or ZByte.
ZiB
zebibyte
Don't use ZIB.
Alerts and messages
An alert is a brief message that appears on the console of an AWS service. It appears in the output
of the AWS Command Line Interface (AWS CLI), or in response to a programmatic call using an AWS
SDK or API operation.
Alerts fall into four general categories:
Alerts and messages
## 143
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 153 -->

AWS Content Design System
• Information – A special circumstance or a service change has occurred or will occur.
• Error – The current action can’t be completed.
• Success – A user has completed an action.
• Warning – A pending action has important consequences.
For design guidelines for alerts, see the following:
• Alerts (choose the Usage tab) on the Cloudscape Design System website.
For writing guidelines, see the following sections:
## Topics
• Basic guidelines
• Alert types
• Error messages
Basic guidelines
The following lists provide basic guidelines about the correct and incorrect way to write alerts.
## Do
For headings:
• For most console alerts, include a brief heading that grabs the attention of the user and
summarizes the subject of the body text (the message). Not all alerts need headings (for
example, success alerts typically don’t need headings).
• Write headings that are meaningful for your users, especially for users who are new to a service.
Don’t supply an error code only.
• For HTTP status code messages, include the status code number and the standard deﬁnition in
the heading. For example, "HTTP status code 404 (Not Found)."
• Use sentence case for headings (except for proper nouns and standard deﬁnitions for HTTP
status codes).
For messages (body text):
Basic guidelines
## 144
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 154 -->

AWS Content Design System
• Follow the voice guidelines for all content, including alerts.
• Keep messages short, straightforward, and actionable if action is needed.
• Use sentence case, complete sentences, and ending punctuation.
• Avoid one size ﬁts all generic messages such as "Something went wrong."
• Use plain, everyday language instead of obscure codes, techie jargon, or cryptic descriptions such
as "an error of type 2 occurred." For more information about error messages, see Error alert.
• In most cases, use positive instead of negative language. For example, instead of "You can’t link
an EC2-Classic instance to more than one VPC," recast as "You can link an EC2-Classic instance to
only one VPC."
• Use an active voice if you know who or what the subject is. For example, "Amazon SQS places the
message in a queue." Use passive voice only to avoid blaming the user or when an unspeciﬁed or
unknown program, service, or process runs an action.
• In most cases, use simple forms of verbs in present tense to describe the conditions that
generated the alert or the conditions that currently exist. Use other verb tenses only if necessary
to convey the proper meaning. For example, you can use past tense to describe a distinct event
that occurred in the past. You can use future tense to describe a distinct event that, given certain
conditions, might occur in the future.
• Use contractions for a casual and friendly tone, but use them selectively. For more information,
see Contractions in the Voice and tone topic.
• Use second person (you) to address the user directly, where appropriate.
## Example
You reached the quota for security groups. You can create up to ﬁve security groups.
Learn more
• Use the name of the AWS service or we, when appropriate (but use we sparingly).
## Examples
• CloudFront can’t create the distribution because...
• Amazon ES can’t create the domain because...
• We recommend that you use...
• We don’t recognize that password. Try another password, or contact AWS Support.
Basic guidelines
## 145
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 155 -->

AWS Content Design System
• When you refer to speciﬁc errors in your documentation topics, format the error text using
either the <errortext> tag or the <screen> tag. For more information, see the typographical
conventions section in the Using Zonbook Wiki.
• For console alerts, include links to relevant documentation topics. You can use both inline
(embedded) links and "Learn more" links. For more information about links for console alerts,
choose the Usage tab on the Links page of the Cloudscape Design System website and Create
console help links on the Wiki. For messages that don’t support links, such as CLI messages,
include enough explanation in the message to help users understand the problem. Also
include the right keywords in the message so that users can search the internet to ﬁnd more
information.
• In general, put replaceable values at the end of a sentence after a colon. For example, "You can't
delete the following snapshot: {1}." This helps translators on a Localization team understand the
word order, the gender of the placeholder value (because it aﬀects the verb or adjective that's
associated with the value), and whether the value is singular or plural. However, if the values are
obvious the placement doesn’t matter. For example, "A/n {item} is required" is acceptable.
• Be careful with using humor. Users who receive an error message are trying to ﬁx a problem,
so playful messages such as "Oops! You made a boo boo!" won’t be well received. For some
companies, a message such as "We just blew a fuse!" might be ﬁne for a "Page Not Found" 404
error, but it could distress our AWS users who trust AWS with their resources. Also, humor in US
English doesn’t always translate well into other languages or cultures.
Don't
• Don’t use please or sorry.
• Don’t use just or simply. For example, "Simply enter the account’s ARN, wait ﬁve seconds, and
then choose Create." This wording might make users feel ignorant. If the process were simple for
them, they wouldn’t see the alert.
• Don’t use words that imply blame, for example, "You failed to conﬁgure the database correctly."
• For console alerts, don’t repeat text that's on the page of the console. The alert should contain
either new information or diﬀerent phrasing of the text on the page, to help users understand
the meaning.
• Don’t use exclamation points.
• For console alerts, don’t spell out numbers, including numbers under 10 (for example, "The name
must have at least 8 characters" instead of "The name must have at least eight characters"). This
guideline also applies to numbers on the pages of a console.
Basic guidelines
## 146
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 156 -->

AWS Content Design System
## Note
In the service documentation, spell out numbers under 10. For more information, see the
Numbers and units of measure topic.
Alert types
The following sections provide details about each of the four types of alerts.
## Topics
• Information alert
• Success alert
• Warning alert
• Error alert
Information alert
An information alert notiﬁes users about a special circumstance or a change to a service. This type
of alert usually doesn’t require immediate action by the user. For example, the alert might inform
users about a planned deprecation or tell users about a feature update or pricing change.
The message should be straightforward. If you can’t explain the message in a few words, provide a
link to more information.
AWS style
• Comprehensive usage data for EC2 instances is now available in Cost Explorer.
Not AWS style
• You do not have this service yet. Click to automatically sign up.
• The existing parameter may have expired. If you want to overwrite this value, set the overwrite
option in the request to true.
Alert types
## 147
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 157 -->

AWS Content Design System
Success alert
A success alert is used on AWS consoles. The message tells users that they’ve successfully
completed a speciﬁc action, and should tell users what the next steps are. Typically, a success alert
doesn’t include a heading because the body text is usually suﬃcient.
AWS style
• You successfully registered the domain {domainname}. To route traﬃc for your domain, create
records in the hosted zone that Route 53 created for you automatically when you registered the
domain. Learn more
• Your preferences are saved. You can change these settings at any time.
Not AWS style
• The operation completed successfully.
• Jobs Test-node-001, Test-node-002, Test-node-003, Test-node-004, Test-node-005, Test-
node-006, Test-node-007, Test-node-008, Test-node-009, and Test-node-010 successfully
created.
Warning alert
In the user interface, a warning alert draws special attention to actions that are irreversible
and potentially damaging to equipment and data or that might aﬀect the user’s conﬁdential
information. The message describes what could happen if the warning is ignored. For delete
actions, the message typically begins with "Delete the...?"
AWS style
• Delete the domain {domainname}? You will lose all domain data, and you can't recover the data
later. Learn more
• Delete this shared dataset? All reports, analyses, and dashboards that use this dataset will stop
working. Learn more
• If you change the conﬁguration, you might need to stop the instance. Learn more
Not AWS style
• Change your settings or you'll lose your data.
Alert types
## 148
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 158 -->

AWS Content Design System
• Your ﬁle is corrupted!
• Conﬁrm that you want to delete this shared dataset. All reports based on it will break, and you
may not be able to ﬁx them. To ﬁx them, you could try to recreate the dataset with the same
column names, or you could try to reshare the original dataset, or you may want to call support
for assistance.
Error alert
An error alert informs users that a problem has occurred. For detailed guidance, see Error
messages.
Error messages
An error alert informs users that a problem has occurred.
Helpful error messages are concise, constructive, and diagnostic. An error message should explain
the following:
• What happened
• Why it happened (if known)
• How the user can ﬁx it
• How the user can get help or ﬁnd more information
## Topics
• Anatomy of an error message
• Guidelines for error messages
• Common errors
• Client and server status codes
• API and AWS CLI error messages
Anatomy of an error message
Here is the structure for a typical error message:
Heading (optional, but recommended for most alerts):
Summary of error or DescriptiveErrorCode
Error messages
## 149
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 159 -->

AWS Content Design System
Message body:
This ﬁrst sentence tells the user what happened and why. This second sentence says how to ﬁx
it or move toward a solution. This last part is a "Learn more" link, a "Learn more about [topic]"
link, or a link to AWS Support.
Guidelines for error messages
Follow these guidelines for writing error messages:
• Provide enough information to help users understand and ﬁx the issue, but keep the message
short. 1–3 brief sentences should be suﬃcient.
• Plainly state the issue and oﬀer a recommended action, solution, or workaround.
## Example
You tried to transfer 47 domains to Route 53, but you can transfer only 23 domains before you
reach the quota of 100. To request an increase in the number of domains that you can transfer to
Route 53, create a support case. Increasing the quota might take up to 24 hours. Learn more
• Use straightforward, everyday language instead of cryptic descriptions such as "an error of type
2 occurred."
• For error codes and exception types:
• Use error codes that are unique and readable, in PascalCase. PascalCase capitalizes the ﬁrst
letter of each word without using spaces between words. For example, ErrorCodeNotFound.
• Include the speciﬁc error code or exception type if it will help users (and AWS Support) to
identify a solution. (Avoid using the actual error code from the source code unless it follows
these rules.) Also, include the error code or exception type if it will help users search online for
a solution.
• If possible, avoid generic messages such as "Unknown error." (If your service team catches all
the exceptions that they aren’t expecting, you might not be able to avoid a generic message
such as "Unknown error.")
AWS style
• The backtick character (`) isn't valid in this command. Remove the character, and try again.
• A parameter with this name already exists. Enter a diﬀerent name.
Error messages
## 150
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 160 -->

AWS Content Design System
• This name isn't valid. Names can include only letters (A-Z and a-z), numbers (0-9), dashes (-), and
periods (.). Enter a diﬀerent name.
Not AWS style
• Invalid name.
• Duplicate parameter name.
Common errors
These are the most common types of errors:
• User input is missing, incomplete, or incorrect
• User exceeds a quota or doesn’t meet a quota
• User attempts to perform an unsupported action or operation
• User doesn’t have permission to perform a supported action or operation
• AWS or the network is experiencing an internal error
This section includes information about these errors. The section also includes information about
client and server status codes. For guidance about constraint text for form ﬁelds (which can be
related to error messages), see Form ﬁeld (constraint text). For console messaging patterns, see
Access denied messaging on the Cloudscape Design System website.
Validation errors (user input is missing, incomplete, or incorrect)
Validation errors occur when a user leaves a required ﬁeld blank or enters incomplete or incorrect
information. These errors are located inline, directly under the ﬁeld they're referring to and just
before any constraint text.
Use the following format for validation errors when a required ﬁeld is left blank: [label descriptor]
[label type] is required.
AWS style
• Alarm name is required.
• Template URL is required.
• Expiration date is required.
Error messages
## 151
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 161 -->

AWS Content Design System
Not AWS style
• Value is required.
• This ﬁeld is empty.
• Email can’t be blank.
• Enter all required ﬁelds.
• The value must not be null.
Use the following format for errors when users enter values that aren’t valid: Enter a valid [label
descriptor] [label type].
AWS style
• Enter a valid email address.
• Enter a valid subnet group name.
• Enter a valid phone number.
• Enter a valid KMS key ARN.
Not AWS style
• The ARN isn’t valid.
• Invalid entry.
• The input fails to satisfy the constraints.
When user input doesn't match what's in the system (such as a security code) or is already in use
(such as for a new user name), use one short sentence to indicate what doesn’t match. For example,
"The security code doesn’t match." If additional context is necessary, follow the ﬁrst sentence with
clearly deﬁned next steps.
AWS style
• The security code doesn’t match. Refresh the code and try again.
• The instance name is already in use. Use a diﬀerent name.
Not AWS style
Error messages
## 152
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 162 -->

AWS Content Design System
• The security code is wrong.
• The input is invalid.
Form ﬁelds that have character requirements, use constraint text to include any character count
requirements the user needs to know to ensure that their input is valid. For more information
about writing contraint text for form ﬁelds, see Form ﬁelds (constraint text).
If the user's input doesn't meet the form ﬁeld requirements, the corresponding validation error
should let the user know which constraint text requirements aren't met.
AWS style
• The name has characters that aren’t valid: #
• The name has too many characters. Character count: 120/50
• The name has too few characters. Character count: 1/50
Not AWS style
• The ARN isn’t valid.
• Invalid entry.
• The input fails to satisfy the constraints.
User exceeds a quota or doesn’t meet a quota
A quota error occurs when a user either exceeds a quota or fails to meet a minimum requirement
for a quota.
AWS style
• You’ve reached the quota for security groups. You can create up to ﬁve security groups.
Learn more
• You’ve reached the quota of applications that you can deploy for your account. Archive or delete
applications that you don’t need, or request a quota increase.
• The tag key has too many characters. Enter a tag key from 1–127 characters.
• The URL preﬁx doesn’t have enough characters. A URL preﬁx must have at least four characters.
Error messages
## 153
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 163 -->

AWS Content Design System
• The name doesn’t have enough characters. The name must have at least eight characters. Valid
characters are lowercase a-z, 0-9, and – (hyphen).
• Your request rate is too high. The AWS SDKs for DynamoDB automatically retry requests that
receive this exception. Your request will eventually succeed unless your retry queue is too large
to ﬁnish. Reduce the frequency of requests and use exponential backoﬀ.
Learn more
Not AWS style
• Invalid action.
• Quota exceeded.
• Unable to validate environment URL: 1 validation error detected: Value ‘1’ at ‘cNAMEPreﬁx’ failed
to satisfy constraint: Member must have a length greater than or equal to 4.
• Sorry you are having problems with this feature. The conﬁguration of these shared data is wrong
and may not work. To proceed, please contact the data owner for permissions to the report. To
ﬁnd out who owns the data, you might need to ask the service administrator or contact the AWS
account owner.
User attempts to perform an unsupported action or operation
This type of error occurs when a user tries to perform an action or operation that an AWS service
doesn’t allow.
AWS style
• You can’t delete this snapshot: {1}. You can delete snapshots only of this type: {0}.
Learn more
• You tried to create another subnet in the same Availability Zone. Each subnet must be in a
separate Availability Zone. Choose a diﬀerent Availability Zone, and try again. Learn more
• Remove the ConﬁgRuleArn and ConﬁgRuleId parameters from the request, and try again.
Not AWS style
• Zone ﬁle contains no records to create.
• Your email could not be sent.
Error messages
## 154
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 164 -->

AWS Content Design System
• Something went wrong!
• 1 validation error detected: Value ‘ZIP’ at ‘format’ failed to satisfy constraint: Member must
satisfy enum value set [CSV, TSV, XLSX, CLF, ELF].
User doesn’t have permission to perform an action or operation
This type of error occurs when a user doesn’t have authorization to complete a task.
AWS style
• You don’t have permission to delete the bucket {bucketname}.
Learn more
Not AWS style
• You don’t have access!
• Sorry, there was a problem.
For IAM permission errors that appear on a console, use one of the following messages (try to use
the provided wording, but customize if necessary):
• For consoles that can programmatically identify the speciﬁc user error:
You don't have permission to perform the following operation on the <service name> console:
<operation name>. Contact your AWS administrator if you need help. If you're an AWS
administrator, you can provide permissions for your users or groups by creating IAM policies.
Learn more <link to IAM documentation or to service-speciﬁc documentation about IAM>
• For consoles that can't programmatically identify the speciﬁc user error:
The <service name> console uses AWS Identity and Access Management (IAM) policies for
better security and ﬂexibility. Some of your actions are currently restricted by these policies.
Contact your AWS administrator if you need help. If you're an AWS administrator, you can
provide permissions for your users or groups by creating IAM policies. Learn more <link to IAM
documentation or to service-speciﬁc documentation about IAM>
Error messages
## 155
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 165 -->

AWS Content Design System
AWS or the network is experiencing an internal error
On rare occasions, AWS or the network might experience system issues. Be as speciﬁc about the
issue as possible. If you can’t identify the cause of the issue, use general wording such as “issue
with the network.” Also, you can use the words "Try again later," but you should inform users if
"trying again" incurs an additional cost.
AWS style
• DynamoDB can’t process the request right now because of an issue with the server. Try again
later.
• Amazon QuickSight can't connect to this database. The host is unknown. Check that the server is
running and that the Amazon QuickSight data source is validated.
Not AWS style
• Internal error.
• System error.
• Unexpected error. Please investigate.
• Error from server: query did not return a unique result: 2
• Oops! We just blew a fuse!
Client and server status codes
HTTP status codes include ﬁve standard classes of responses: informational, success, redirection,
client error, or server error. This section provides information about client or server errors:
• Client errors
These errors usually occur because there's a problem with the structure, content, or validity of
a request from a client, such as a web server. For example, a client might specify an incorrect
parameter in the request, or attempt to use an action or resource on behalf of a user who doesn't
have the right permissions.
The errors have an HTTP status code from 400–499. Client errors can be common errors (errors
that all actions can return) or errors that are speciﬁc to the API operations of an individual AWS
service.
• For 400 errors, use this title: Bad request
Error messages
## 156
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 166 -->

AWS Content Design System
• For 403 errors, use this title: Access denied
• For 404 error, use this title: Page not found
• For 408 errors, use this title: Request timeout
• Server errors
These errors indicate a server-side problem that must be resolved by AWS. A web server returns
this type of error when it can’t process an apparently valid request. The errors have an HTTP
status code from 500–599.
In addition to the HTTP status code, a client or server error typically includes the name of the
exception and a message that explains the issue.
## Note
Both client and server errors can occur because of the speciﬁc way that AWS services and
the software clients that communicate with them are designed. It's often insuﬃcient to rely
only on the HTTP status code and standard error description to inform the user of what has
happened.
After you provide the standard response code and description, you can provide more
information about the error or response in relation to the functionality of the service. For
example:
• HTTP Status Code 403 (Access Forbidden): Make sure that you're using the correct
credentials and that your account is on the allowlist for this beta release.
• HTTP Status Code 500 (Unexpected Internal Server Error): Retrying your request might
resolve the issue.
For information about the full range of HTTP status codes, see List of HTTP Status Codes in
Wikipedia.
AWS style (common client error)
ResourceInUseException
The resource that you tried to change is in use. For example, you tried to recreate an existing table
or delete a table in the CREATING state.
AWS style (service-speciﬁc client error)
Error messages
## 157
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 167 -->

AWS Content Design System
InstanceAlreadyLinked
The EC2-Classic instance that you tried to link is already linked to another VPC. You can link an
EC2-Classic instance to only one VPC.
AWS style (server-side error)
HTTP 504 (Gateway Timeout)
The load balancer closed a connection because a request didn't ﬁnish within the idle timeout
period. To allow lengthy operations (such as large ﬁle uploads) to complete, you can increase your
capacity or the conﬁgured idle timeout. For more information, see Conﬁgure the Idle Connection
Timeout for Your Classic Load Balancer and How do I troubleshoot Elastic Load Balancing high
latency?
API and AWS CLI error messages
API and AWS CLI error messages can be diﬀerent than error messages in the console. For example,
with the console, frontend developers or UX designers might be able to help the user avoid certain
mistakes by restricting the input in some way. The UI can provide valid values and constraint
information.
However, with the API or CLI, the service team must provide an error message for the same
scenario that indicates which parameters aren’t valid or which criteria isn’t being met.
Also, API and CLI error messages tend to be more concise than error messages in the console,
where there’s more space to provide details. But, consider that API or AWS CLI error messages
might also be used in the console. It’s important to create customer-focused error messages that
follow our guidance, regardless of where the user will see them.
Example library
The following examples are error messages for the API and AWS CLI that are grouped in common
categories. For more information, see AWS API standards. For details about HTTP status codes, see
the Exceptions section.
Parameter values aren't valid (for example, length or pattern constraint)
• The name can't begin or end with a hyphen.
• The name can contain only alphanumeric characters and hyphens.
• The name must be unique within this AWS Region.
Error messages
## 158
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 168 -->

AWS Content Design System
• The speciﬁed AMI ID isn’t in a valid format. Verify that the AMI ID is in the form ami-
xxxxxxxxxxxxxxxxx.
• The value that you provided for the parameter CpuManufacturers isn't valid. Valid values:
{{supportedParameterValues}}.
• The speciﬁed pagination token isn’t valid or has expired.
• Negative values aren’t valid for NetworkBandwidthGbps.Max. Valid values: null, 0, positive
integers.
• vCpuCountRange.Min must be less than or equal to vCpuCountRange.Max.
• The diﬀerence between MaxHealthyPercentage and MinHealthyPercentage must be less than or
equal to 100.
• The interval between the start and end date can’t be more than 30 days.
• MaxInstanceLifetime must be either equal to 0 or between 604,800 and 31,536,000 seconds
(inclusive). A value of 0 is used to remove a previously set value.
• One or more of the following CloudWatch alarms don’t exist or aren’t valid: {{alarmNames}}.
Duplicate entries in a list
• The service found a duplicate name. You can’t use duplicate names for load balancers or target
groups.
Parameter missing
• InstanceRequirements is missing the VCpuCount parameter. Add VCpuCount, and try again.
• A load metric is required. Provide either the PredeﬁnedLoadMetricSpeciﬁcation parameter or the
CustomizedLoadMetricSpeciﬁcation parameter, and try again.
• A resource label is required to use the ALBRequestCountPerTarget metric. Provide a resource
label, and try again.
• The ARN isn't valid. Specify a valid ARN, or add the Type parameter to your request when you're
specifying the name of a classic load balancer, and try again.
Unsupported operation or parameter combination
• You can’t specify InstanceType and InstanceRequirements in the same request. Remove either
InstanceType or InstanceRequirements.
Error messages
## 159
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 169 -->

AWS Content Design System
• The service doesn’t support specifying EC2 in addition to other health check types. Remove EC2
from HealthCheckType and try again.
• The metric speciﬁcation isn't valid. The following parameters aren't allowed when the
PredeﬁnedMetricPairSpeciﬁcation parameter is used: {{unsupportedParameterNames}}.
• The value ElastiCacheDatabaseMemoryUsageCountedForEvictPercentage for
PredeﬁnedMetricType isn’t supported because of incompatible cluster or instance types on the
speciﬁed resource. The supported values are {{supportedParameterValues}}.
• You can’t specify a CloudWatch alarm if it’s already in the ALARM state. Either remove the option
to specify a CloudWatch alarm, or wait a few minutes and try again.
• The speciﬁed instance type {{selectedInstanceType}} isn’t allowed. You can't use a Network Load
Balancer if the launch template or launch conﬁguration speciﬁes one of the following instance
types: {{unsupportedInstanceTypes}}.
• You can specify only one subnet per Availability Zone.
• The 'prioritized' On-Demand allocation strategy can't be used with InstanceRequirements. Either
change the strategy to 'lowest-price' or remove InstanceRequirements.
• You can’t use a mixed instances policy when there are instances in an active Capacity Block
reservation present in the Auto Scaling group.
• The CreateLaunchConﬁguration API operation isn’t available in your account. Use launch
templates to create conﬁguration templates for your Auto Scaling groups.
• The endpoint isn’t currently supported when you’re using tags. Use the endpoint application-
autoscaling.{{region}}.amazonaws.com for tagging operations.
AWS or the network is experiencing an internal error
• The request encountered an unknown internal error for the service {{serviceNamespace}} and
can’t continue. Try again later or report the issue to AWS Support.
Artiﬁcial intelligence (AI)
The ﬁeld of generative AI is evolving rapidly and can be confusing. Clear, consistent, and
ﬂexible language helps reduce the research load on writers and other experts who are creating
documentation about AI, reassures customers about AWS expertise and market leadership in
generative AI, and helps preserve transparency and accuracy.
Artiﬁcial intelligence (AI)
## 160
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 170 -->

AWS Content Design System
If you have style questions about how to write about generative AI that aren't answered in this
section of the AWS Style Guide, ask in the #ask-cq-editors Slack channel.
Best practices
Follow these guidelines when creating documentation about AI to ensure clarity, consistency, and
transparency.
## Do
• Check the AWS Style Guide announcements for updates to AI guidance
• Follow established terminology for AI components and services
• Maintain transparency about AI capabilities and limitations
• Use clear, precise language when describing AI functionality
Don't
• Don't use inconsistent or unoﬃcial terms for AI features
• Don't make unsupported claims about AI capabilities
• Don't anthropomorphize AI systems
Additional resources
• Conversational interfaces overview on CQ wiki
• TCX Generative AI Resource Center
Checklist for human review of AI-drafted content
Reviewing AI-generated text is the same as reviewing human-written text in most ways: quality is
quality, no matter who or what wrote it. But there are speciﬁc aspects to which reviewers should be
especially attentive when the content is AI-drafted. Beyond ensuring that the text is accurate and
AWS style-compliant, this checklist can help reviewers make text feel less like it was generated by
AI and more like it was written by humans.
Best practices
## 161
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 171 -->

AWS Content Design System
## Important
Don't publish outputs from generative AI without human review. For more information, see
the TCX Guidelines for Using Generative AI.
Ask the following questions when reviewing AI-drafted content:
Word use
Review the following questions about word use in AI-generated text.
• Does this content overuse adjectives, especially hyperbolic ones?
• LLM-generated language often sounds "marketing-ish." Evaluate whether text sounds like
it's informing customers about what our services can and can't do and how to do things with
them, or bragging about how good they are.
• Avoid hyperbolic words or those that overpromise ("groundbreaking", "revolutionize", "cutting-
edge").
• Eliminate unnecessary adjectives and adverbs (adverbs usually end in -ly, like
"comprehensively" or "excitingly"). Overuse of adjectives and adverbs is one of the main factors
contributing to text sounding like marketing.
• Does this content use words overused by LLMs?
• One use of "delve" or "leverage" in a topic is probably ﬁne; beyond that, use synonyms or
otherwise rewrite.
• Replace verbs with simpler, more straightforward alternatives. "Use," in most cases, means the
same thing as "utilize" or "leverage." ("Leverage" and "delve" are two of the words currently
overused by AI.)
• Tip: Microsoft Visual Studio Code (also known as VSCode, available in the Software Center) will
highlight all uses of a word in a ﬁle if you click on/put your cursor within that word, which can
help you check for overused words.
• Does this content use phrases overused by LLMs?
• Search for "phrases overused by AI" or a similar search string to get a sense of the type of
phrases LLMs use more than humans.
• LLMs overuse clichés ("a rich tapestry of...", "only time will tell if..."). Eliminate clichés wherever
possible (as a bonus, a lot of clichés and metaphors are also bad for Global English and
localization).
Checklist for human review of AI-drafted content
## 162
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 172 -->

AWS Content Design System
• Is the same word repeated a lot in close proximity?
• "Burstiness" is a metric that measures the proximity of identical or related words and concepts.
It's not good or bad, but it is something that AI tends to do diﬀerently than humans. How
much repetition is too much is contextual and very much a human judgment call.
• Ensure that procedural content is precise and unambiguous so the customer can follow the
procedure without confusion, even if that means frequently repeating words or phrases.
• Vary vocabulary in conceptual content to hold the customer's interest.
• Tip: VSCode can highlight all uses of a word.
Sentence structure
• Are the sentences in this content too simple?
• Humans tend to write sentences with more complex structure (perplexity) than AI does. In
general, our style guidance also favors shorter sentences with more straightforward structure,
but if a slightly longer or more complex structure better conveys an idea, go ahead and ﬁx it.
• Tip: One area where shorter, simpler sentences can actually be worse for readers than longer,
more complex sentences is if the sentence is a series. "You can do A, B, or C" is generally better
than "You can do A. You can also do B. You can also do C." (If A, B, and C are all long, complex
list items, it might be better to break it up, but in general, making them separate sentences
increases the cognitive load on the reader, who must connect them into a series.)
• Does the text repeat identical sentence structure in close proximity?
• AI-generated text has a tendency to overuse particular sentence structures (such as X not only
Y but also Z). It sometimes generates multiple sentences in a row that use identical structures.
Make sure sentence structure is varied unless there's a reason it needs to be identical.
• Tip: You can highlight a phrase in VSCode (such as "but also") to see where else it shows up in
the document, which can help identify identical sentence structure.
• Does the content use too many negative parallelisms?
LLMs tend to overuse negative parallelisms. Watch out for sentence structures like the following:
• Not only does it... but it also...
• It's not just about... it's...
• Does the text contain strings of participial phrases?
LLMs use participial phrases (-ing phrases) at 2-5x the average in human-written text.
• Does the text use "that" as a subject?
Checklist for human review of AI-drafted content
## 163
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 173 -->

AWS Content Design System
Instruction-tuned models often begin sentences with "That" or otherwise use it as a subject. For
example:
• "That the system failed to account for these variables indicates a fundamental ﬂaw..."
• Does the content contain an excessive number of nominalizations?
AI models produce nominalizations at 1.5-2x the human rate. For example:
• "These schemes can help to reduce deforestation, habitat destruction, and pollution..." (As
opposed to "These plans can help save forests, protect habitats, and cut pollution...")
• Does the content begin "In today's..." (especially followed by "organizations face
increasing")?
We're seeing up to a third of technical blog submissions begin with phrases like:
• "In today's fast-paced digital landscape, marketing teams face increasing pressure..."
• "In today's rapidly evolving Artiﬁcial Intelligence (AI) landscape, organizations are seeking..."
• "Organizations face increasing challenges..."
• "Organizations are increasingly deploying..."
## Meaning
• Does this content avoid expressing an opinion or preference where it should have one?
• We want our content to be objective and data-based, but we should still acknowledge when
one option is better than another (such as a best practice, or a method that works better than
another method for a particular use case).
• Tip: AI-generated content tends to present multiple options without directly acknowledging if
one is better than another.
• Tip: LLMs rarely tell you "no" or "you shouldn't do that," and instead write around giving that
sort of answer. (For example, in response to Should I do electrical work without gloves? many
LLMs will respond with something like Let's talk about how to work safely with electricity rather
than saying No, you should wear gloves or You don't need to wear gloves.) It's okay, for example,
to answer a FAQ question with "No".
• Does the text editorialize unnecessarily?
While in some cases, AI tools avoid expressing an opinion, in others, they introduce unasked-for
analysis or interpretation. Watch for phrases similar to the following:
Checklist for human review of AI-drafted content
## 164
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 174 -->

AWS Content Design System
• It's important to consider...
• No discussion would be complete without...
• In this article...
• A deﬁning feature of...
• Does the content engage in unnecessary both-sides-ing?
Even when prompted not to, LLMs often try to "balance" any recommendations or claims in their
text with warnings or alternates. (For example, "While it's a good idea to prepare thoroughly for
an interview, over-preparation may cause some candidates to provide rote-sounding answers.")
At times, they may generate nonsensical or incorrect information in an attempt to provide a
counterpoint.
• Does the text overstate importance, signiﬁcance, or symbolism?
LLMs are usually trained to be positive, which means they can overstate signiﬁcance. Look out
for phrases similar to the following:
• stands as a testament to
• plays a vital role
• underscores the importance of
• Does each sentence or paragraph make logical sense?
• Because LLM-generated text is usually correct in terms of grammar and syntax, and LLMs
rarely make typos or similar mistakes, it's easy to skim past a sentence that actually doesn't
make sense.
• Tip: As you read, mentally paraphrase each sentence in your own words to slow yourself down
as a reviewer enough to notice if something that sounds vaguely right has substance to it.
• Is every sentence in the document actually contributing to the content?
• LLMs can generate sentences that aren't nonsensical, but also really aren't saying much (like
Claude's writing advice to "Highlight intriguing points with enthusiasm"). Keep an eye out for
ﬂuﬀ.
• Tip: If you had to cut the word count in this document in half, what are the ﬁrst sentences
you'd eliminate?
• Is all the information or discussion in the document relevant to the content's purpose?
• AI-generated text can sometimes veer oﬀ into irrelevant content. Make sure everything in the
document is necessary to follow the procedure, understand the concept, or otherwise use the
document in the way it's intended.
Checklist for human review of AI-drafted content
## 165
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 175 -->

AWS Content Design System
• Tip: Even if the content is related, it might not be relevant. Ask yourself whether it would ﬁt
better in another topic.
## Accuracy
• Is every factual assertion in the document true?
LLMs hallucinate because they only have access to linguistic validity, not actual truth. Unless you
know oﬀhand that a factual assertion is true, don't assume that it is.
• Does every source linked or referenced in the document exist?
Making up sources is an especially common type of LLM hallucination. Make sure any blog posts,
references, or other sources actually exist and are correctly titled and attributed, and that link
text matches the title of the page it links to.
• Does every UI element referenced exist? Does any UI text mentioned match the real UI text
exactly?
Hallucinating buttons or other UI elements in an otherwise correct procedure is another common
type of AI hallucination. Make sure text exactly matches what's in the console or other interface.
• Are attributions actually identiﬁed?
LLMs have a tendency to use "weasel words": vague attributions that imply that something is
widely known or a settled consensus.
Tip: Look for passive voice in attributions:
• ...has been described as...
• Critics have argued...
Transition phrases
• Does the information following a connector word or phrase actually match the purpose of
that connector?
LLMs sometimes follow a connector phrase that signals a contrast or contradiction ("but," "that
said", "however") with more of the same instead of contrasting information. They also sometimes
follow a connector phrase that indicates similarity ("in addition," "also") with contrasting
information. Make sure these signals match the actual meaning of the text.
Checklist for human review of AI-drafted content
## 166
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 176 -->

AWS Content Design System
• Do multiple sentences in a row begin with transition phrases?
• LLMs overuse transition phrases (such as "However" or "On the other hand"), especially at
the beginning of sentences. While transition/connector phrases used in moderation make
writing smoother, using them too often can make writing feel disjointed or choppy. Eliminate
unnecessary transition phrases, rewriting/restructuring if necessary.
• Tip: Overuse of transition phrases at the beginning of sentences (followed by a comma) is
more noticeable and choppy than those used in the middle of a sentence.
• Are organizational signals necessary?
AI-generated text often has unnecessary organizational signals, which are transition phrases
used to indicate order or level of importance, such as "ﬁrst" or "ﬁrstly," or "primarily" and
"secondarily."
• Tip: If the text is discussing concepts, ask yourself whether simply discussing things in a
particular order is clear enough without organizational signals.
• Tip: If the text presents a collection of short ideas/tips/objects/etc., ask yourself whether
they'd be better as an unordered (bulleted) list or table.
• Tip: If the text presents a collection of longer ideas/tips/etc., ask yourself whether they'd be
better as individual subsections.
• Tip: If the text is discussion actions that must be performed in a particular order, ask yourself
whether it would be better as a procedure, or some other type of ordered list.
• Are additive transitions necessary?
• Additive transitions (such as "furthermore," or "in addition") link ideas that support or build on
each other. LLMs often insert additive transitions where the structure of the text itself already
implies the connection or makes it explicit. For example, if you're following a discussion of
Concept A with a discussion of Concept B and saying that Concept B builds on Concept A, you
don't also need a "furthermore."
• Tip: Additive transitions are more likely to be necessary when a discussion point has gotten
long and detailed, and the reader needs a clear signal that a new paragraph or sentence marks
the start of a new but related point. If your discussion of a particular idea has gone on for
multiple paragraphs, you might need one. Otherwise, a new idea in a new paragraph probably
doesn't need the signal that it's a new idea.
• Are summative transitions at the end of a document or section, or marking a summary?
Summative transitions (such as "ultimately," "to sum up," or "in conclusion") usually mark an
ending, whether of a document, a section, or a particularly complex idea. AI-generated text
Checklist for human review of AI-drafted content
## 167
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 177 -->

AWS Content Design System
sometimes uses them before it's actually done, or for very short or simple ideas that don't need a
summation called out.
Document structure and formatting
• Are related ideas clustered sensibly?
• This is the ﬂipside of burstiness. Just as AI might monotonously use the same word over and
over in a short block of text, it might scatter related ideas across an entire piece of content or
come back to an idea after discussing unrelated concepts rather than grouping them in a way
that makes sense.
• Tip: Logical section headings can help determine where in a document information should go.
• Overall, is the document both cohesive and not overly repetitive?
AI-generated text is not always well-structured, whether because it includes irrelevant
information, because it doesn't group related paragraphs, or because it repeats itself by saying
the same thing multiple times in diﬀerent words. Take a step back and analyze the structure of
the document to make sure everything's necessary and where it should be.
• Do section headings use title case instead of sentence case?
LLMs tend to capitalize all the words in headings (title case)
• Does the text use excessive boldface, lists, or em dashes (especially incorrect use of em
dashes)?
• AI-generated text often contains many words bolded for emphasis, excessive use of lists, and
multiple em-dash clauses in a paragraph.
• Em dashes may have spaces around them (when used as punctuation in a sentence, they
shouldn't have spaces on either side).
• Does the text contain Markdown?
LLM answers may contain Markdown formatting, including broken Markdown. Most frequently,
this is double asterisks (**) to create boldface.
Prompt remnants
• Does the content contain remnants of conversational format?
Sometimes AI-generated content contains conversational responses from the LLM, such as:
Checklist for human review of AI-drafted content
## 168
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 178 -->

AWS Content Design System
• Certainly! I'll provide...
• Here's a detailed breakdown of...
• In this section, we will discuss...
• This document combines...
• Does the content reference a knowledge cutoﬀ date?
LLMs may reference their knowledge cutoﬀ dates in their answers. For example:
• No... have been documented as of June 2025.
• As of my last knowledge update...
Conversational AI interfaces
Interactive chat and AI oﬀerings pose unique challenges in maintaining a consistent AWS style,
tone, and voice. In a pre-written document, we control everything from the overall structure to
the individual word choice and sentence-level formatting. However, generative AI organically
composes answers based on the large body of material on which it has been trained and materials
provided to it through retrieval-augmented generation (RAG). While we can train and tune a model
to answer in a particular way, we lack direct control over the answers that the model generates.
The following guidelines represent our current understanding of a rapidly evolving form of
technology. As our understanding and body of research grows, these guidelines will likely change.
For an overview of conversational interfaces, see Conversational interfaces overview (AI, LLMS,
chatbots, and more) Conversational interfaces overview (AI, LLMS, chatbots, and more) on the
Content Quality (CQ) team wiki.
Core principles
AI, such as large language models (LLMs) and other forms of chat-based AI, can engage in
conversation. This makes the customer experience that they provide a direct dialogue between
customers and AWS. To strengthen trust in AWS and the information and services that we provide,
conversational design should reﬂect direct and personal interaction with customers and follow
these principles.
## Do
• Build trust through consistency, transparency, and competence
• Respect customer consent and preferences
Conversational AI interfaces
## 169
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 179 -->

AWS Content Design System
• Meet customer needs eﬃciently and directly
• Allow customers to guide conversations
• Maintain AWS partnership standards
Don't
• Pretend that the AI is human or express emotions that it doesn't have
• Force interactions or compel engagement
• Make unsupported claims about capabilities
• Intrude on customer privacy
Identity guidelines
These guidelines help establish clear identity and boundaries for conversational AI services while
maintaining useful and eﬃcient conversational partnerships with customers.
Professional tone
Conversational services' responses use a professional tone with a level of humanization that
provides productive conversation in an environment in which the service and the customer take
turns communicating in text.
• Use ﬁrst person ("I") when the AI service is referring to itself
• Address customers as "you"
• Maintain professional but approachable language
• Use contractions appropriately
• Introduce acronyms on ﬁrst use
Clear boundaries
Conversational services don't pretend to be human or include excessive personality, adjectives,
or emotional language. While our AI services are clear that they're not human, they must still be
useful and eﬃcient conversational partners.
• State clearly that the service uses AI to produce answers
• Don't write or design for it to pretend to be human or express emotions it doesn't have
Conversational AI interfaces
## 170
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 180 -->

AWS Content Design System
• Use "customer" rather than "user" in most contexts
• Address customers by name in multi-user contexts
Response formatting
Conversational services follow best practices for presenting text on a screen, prioritizing presenting
text in a way that users can scan and navigate eﬃciently.
## Do
• Use short, scannable paragraphs
• Include white space between sections
• Use bulleted lists for collections
• Use numbered lists for procedures
• Include relevant links to documentation
• Start with high-level summaries
• Suggest related follow-up questions
Don't
• Create walls of text
• Include irrelevant information
• Force continued engagement
• Duplicate documentation content
• Use regional idioms or slang
Response quality
Our conversational services build trust and demonstrate their competence by giving responses
that are relevant to the situation and targeted to contain the information that the customer needs
most.
Information density
Our customers are busy. Our conversational design should be welcoming to customers who want to
explore, but it shouldn't get in the way of customers who want a quick, straightforward answer.
Conversational AI interfaces
## 171
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 181 -->

AWS Content Design System
## Do
• Target a 12th-grade reading level
• Use active voice
• Include speciﬁc nouns rather than pronouns
• Link to documentation for additional details
• Start with 1-2 sentence overviews
• Adjust detail level based on context and device
• Suggest relevant follow-up questions
Don't
• Include walls of text
• Duplicate full documentation content
• Overwhelm with unnecessary details
• Force exploration of unrelated topics
• Use excessive politeness
Response accuracy
Conversational services recommend other AWS services when appropriate, and encourage
customers to explore them, but prioritize providing good information about how to use our
services rather than marketing other services. Responses explain what our services can do and help
customers accomplish their goals without inﬂated language or boasting.
## Do
• State facts with conﬁdence
• Acknowledge when recommendations are opinions
• Be transparent about limitations
• Clarify ambiguous situations
• Indicate when questions are out of scope
Don't
Conversational AI interfaces
## 172
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 182 -->

AWS Content Design System
• Use hyperbolic language
• Make absolute claims
• Hide uncertainties
• Pretend to know unavailable information
• Compare with competitors' services
Managing interactions
These guidelines help ensure that conversational AI services maintain appropriate boundaries while
providing helpful and engaging customer experiences.
Customer engagement
Our conversational services drive engagement with a clear purpose. Responses welcome customer
engagement, give concise and targeted information with suggestions about what to ask next, and
attempt to help customers decide what to explore and how to dive deeper into a topic.
## Do
• Welcome exploration while respecting the customer's time
• Provide contextual suggestions
• Demonstrate understanding of queries
• Reference relevant previous interactions
• Maintain professional boundaries
Don't
• Force continued engagement
• Suggest unrelated topics
• Ask unnecessary personal questions
• Use overly emotional language
• Pretend the AI assistant has feelings
Conversational AI interfaces
## 173
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 183 -->

AWS Content Design System
Handling diﬃcult situations
Conversational services should be patient with frustrated customers, but they should not tolerate
open abuse such as the use of slurs, insults, threats, or harassment.
## Do
• Remain professional with frustrated customers
• Clearly state service limitations
• End interactions if abuse occurs
• Redirect oﬀ-topic questions
• Provide alternative resources when appropriate
Don't
• Argue with customers
• Express emotional responses
• Tolerate abusive behavior
• Attempt to handle out-of-scope requests
• Show artiﬁcial distress or regret
Security and privacy considerations
This section describes some common security issues in conversational AI and how to avoid them.
This isn't a comprehensive guide. If you have any security questions, contact your service's security
reviewer.
Best practices
• End interactions immediately if abuse occurs
• Never share customer information unnecessarily
• Maintain clear boundaries around scope of assistance
• Direct security-related questions to appropriate documentation
• Follow AWS security guidelines for all interactions
Response limitations
Conversational AI interfaces
## 174
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 184 -->

AWS Content Design System
• Stay within deﬁned service boundaries
• Direct customers to human support when appropriate
• Never attempt to handle sensitive security issues
• Maintain consistent privacy standards
• Follow established escalation procedures
Describing chat-based AI
Large language models (LLMs) and other forms of generative artiﬁcial intelligence (generative
AI) represent a signiﬁcant leap forward in the capabilities of artiﬁcial intelligence (AI) to produce
human-like responses. When describing chat-based or conversational AI and its capabilities, we
strive for precision and transparency, and use great care to make sure that we're being factual,
transparent, and ethical.
Terminology for chat-based AI experiences
To be precise and transparent in our discussion of conversational AI, be clear about the layer or
component of a conversational experience to which you're referring.
## Pronouns
Conversational AI assistants and experiences can use ﬁrst-person pronouns for themselves in
conversation, but third-person pronouns for them should be non-gendered and non-human.
• Conversational AI assistants can use ﬁrst-person pronouns (I, me, my)
• Use non-gendered and non-human third-person pronouns (it, its)
• Don't use he, him, she, her, or singular they, them
Describing what AI does
Avoid terms that attribute human-like awareness, intent, agency, feelings, or cognition to AI.
Generative AI can produce human-like interaction, but to be responsible, transparent, safe, and
ethical with our language use, avoid any unnecessary anthropomorphization.
## Do
• Focus on outputs rather than process
Describing chat-based AI
## 175
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 185 -->

AWS Content Design System
• Be precise and stick to facts
• Use clear, speciﬁc terminology
• Describe capabilities accurately
Don't
• Attribute human-like awareness
• Suggest human-style cognition
• Imply emotional responses
• Use terms suggesting consciousness
AWS style
• The assistant requests that you enter a home address.
• The assistant acknowledges that it generated an incorrect response.
• The assistant generates jokes that many customers ﬁnd funny.
Not AWS style
• The assistant wants you to enter a home address.
• The assistant feels bad about giving you an incorrect response.
• The assistant gets humor.
Blog posts
AWS blog posts provide an informal approach to educating or inspiring readers through the
personal perspective of the authors. Brief posts generally accompany service or feature releases,
and longer posts can establish AWS as a thought leader in a solution space, note best practices, or
provide creative solutions. Each post must provide a clear customer beneﬁt.
To enhance the strengths of the blogging platform, follow these post guidelines:
• Be conversational and informal.
Posts tend to be more personable, unlike service documentation. Ask questions, include relevant
anecdotes, add recommendations, and generally try to make the post as approachable as
Blog posts
## 176
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 186 -->

AWS Content Design System
possible. However, be careful of slang, jargon, and phrases that a global audience might not
understand.
• Keep it short.
Deep topics don’t necessarily require long posts. Shorter, more focused posts are quicker for
readers to digest. Consider breaking a long post into a series, which can also encourage repeat
visitors to the blog channel.
• Avoid redundancy.
Posts should add to the conversation. Instead of repeating content that's already available
elsewhere, link to detail pages and technical documentation. Keep only the information that's
speciﬁc to the post solution or recommendations.
• Connect with other AWS content.
All posts should contain one or more calls to action that give readers the opportunity to create
AWS resources, learn more about services or features, or connect with other customers. Posts
should also include metadata tags such as services, solutions, or learning levels to help readers
navigate to related content.
## Topics
• Parts of a blog post
• Post types
• Post learning levels
Parts of a blog post
Create posts with the appropriate combination of the following parts, based on the post type. Use
the visual annotated post as an example.
Title and headings
Follow the general guidance for the section called “Titles and headings”.
• Use 75 characters or fewer, with AWS brand names closer to the end.
• Maximum of two service names even if more service names are involved.
• Sentence case.
Parts of a blog post
## 177
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 187 -->

AWS Content Design System
(Optional) guest byline
• Located immediately after the title.
• Include the author’s name, job title, and optional service team.
• Use italics.
## Introduction
• In the ﬁrst sentence, use the same keywords as in the title, for better discoverability.
• Avoid starting the post with a service or feature overview. For more information about avoiding
redundancy, see Blog posts.
• Begin with a common use case or problem, ask a question, or highlight an industry trend.
• When you reference an AWS service for the ﬁrst time, link to the service detail page.
• Use the oﬃcial AWS oﬀering names.
## Walkthrough
Posts that include technical instructions should use the style for procedures.
## Prerequisites
Include an AWS account, AWS resources, specialized programming skills, or speciﬁc hardware or
software.
Cleaning up
Remind users to delete example resources if they no longer need them, to avoid incurring future
costs.
## Conclusion
• Restate the post purpose, using phrases such as ‘In this post, I showed how…”
• Add other ways that this solution can be used or next steps for readers who want to learn more.
Calls to action can include related blog posts, service detail pages, or technical documentation.
• Invite readers to comment.
Parts of a blog post
## 178
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 188 -->

AWS Content Design System
Author bio
• Located at the end of the post, with an author headshot.
• Include a maximum of three sentences: job title and team, professional memberships or
interests, and a personal note.
• Use italics.
Post types
Each post should drive one or more of the following goals:
• Educate readers in how to use AWS products and services
• Drive revenue through resource usage or customer signups
• Increase customer awareness of AWS products, events, or other content
• Position AWS as a thought leader for a solution, layer, or vertical
• Evangelize customer success stories
Posts can ﬁt into one of the following general types. Each blog channel chooses the subset of post
types that ﬁts its audience and content strategy. For channel-speciﬁc guidance, view the AWS Blog
Wiki.
Announcement posts
Use this post type to promote releases, events, open-source code, or new tools.
• Suggested max word count: 600
• Suggested learning levels: the section called “Foundational (100)”
• Voice: First-person plural speaking for AWS (we), second-person to address readers (you)
• Calls to action:
• AWS Management Console (service-speciﬁc)
• Detail page
• Service documentation
Post types
## 179
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 189 -->

AWS Content Design System
Best practices posts
Use this post type to show patterns and anti-patterns, and how to use AWS products to build
better applications.
• Suggested max word count: 2,400
• Suggested learning levels: the section called “Intermediate (200)”, the section called “Advanced
(300)”, or the section called “Expert (400)”
• Voice: First-person for authors (I or we for multiple authors), second-person to address readers
(you)
Don't use we to speak for AWS unless you're doing so oﬃcially and have been cleared by the
Social Media team.
• Calls to action:
• Related posts
• AWS Management Console (service-speciﬁc)
• Detail page
• Service documentation
Curation posts
Use this post type to help readers discover other technical content and events (upcoming or
retrospective).
• Suggested max word count: 1,200
• Suggested learning levels: the section called “Foundational (100)”
• Voice: First-person plural speaking for AWS (we), second-person to address readers (you)
• Calls to action: Multiple links
Customer posts
Use this post type to highlight how a customer solved a speciﬁc technical challenge.
• Suggested max word count: 2,400
• Suggested learning levels: the section called “Intermediate (200)”, the section called “Advanced
(300)”, or the section called “Expert (400)”
Post types
## 180
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 190 -->

AWS Content Design System
• Voice: First-person for authors (I or we for multiple authors), second-person to address readers
(you)
Don't use we to speak for AWS unless you're doing so oﬃcially and have been cleared by the
Social Media team.
• Calls to action:
• Related posts
• AWS Management Console (service-speciﬁc)
• (Optional) GitHub repo or CloudFormation stack
• Detail page
• Service documentation
Technical posts
Use this post type to provide how-to content that includes code examples, diagrams, and carefully
chosen screenshots.
• Suggested max word count: 2,400
• Suggested learning levels: the section called “Intermediate (200)”, the section called “Advanced
(300)”, or the section called “Expert (400)”
• Voice: First-person for authors, second-person to address readers (you)
Don't use we to speak for AWS unless you're doing so oﬃcially and have been cleared by the
Social Media team.
• Calls to action:
• Related posts
• AWS Management Console (service-speciﬁc)
• GitHub repo or CloudFormation stack
• Detail page
• Service documentation
Thought leadership posts
Use this post type to set context on broader technical challenges and opportunities while linking to
other relevant content.
Post types
## 181
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 191 -->

AWS Content Design System
• Suggested max word count: 1,200
• Suggested learning levels: the section called “Foundational (100)”
• Voice: First-person for authors, second-person to address readers (you)
Don't use we to speak for AWS unless you're doing so oﬃcially and have been cleared by the
Social Media team.
• Calls to action:
• Related posts
• Detail page
• Service documentation
Post learning levels
If the technical depth of a post doesn't meet reader expectations, they disengage from the page or
the platform. Use the following guidelines to assign the right learning level for each post.
## Foundational (100)
Readers might have zero or minimal experience with AWS services. Avoid assuming deep familiarity
with the console, API, or CLI.
Posts do one or more of the following:
• Introduce a service, feature, beneﬁt, or concept
• Explain basic use cases for AWS services or integration
## Intermediate (200)
Readers have used multiple AWS services from the console, API, or CLI (or all three).
Posts do one or more of the following:
• Explain how a set of services or features works together
• Showcase common use cases for architecture, integration, and conﬁguration
• Discuss industry trends
• Provide high-level, troubleshooting guidance
Post learning levels
## 182
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 192 -->

AWS Content Design System
## Advanced (300)
Readers are IT decision makers or developers who lean more toward the API or CLI.
Posts do one or more of the following:
• Discuss best practices for design, development, migration, or deployment
• Contain implementation details or customer use cases
• Contain a walkthrough
• Contain code examples
## Expert (400)
Readers are developers, architects, or CTOs.
Posts do one or more of the following:
• Introduce a service or services at a deep level
• Explain advanced techniques for design, development, migration, or deployment
• Contain implementation details or customer use cases
• Contain a walkthrough
• Contain code examples
AWS voice and tone
Voice is the point of view or style of an author. Voice can refer to active or passive, but can also
refer to verb tense (past, present, future, and so on). Tone is the emotional undercurrent (such as
calm or angry) of the voice. AWS strives to speak to customers with a consistent voice and tone, as
if a single writer writes all content. Writing with a common voice also helps to establish the AWS
identity and brand.
## Voice
Whenever possible, use the active voice instead of the passive voice. The passive form is typically
wordier and can often cause writers to obscure the details of the action. For example, change the
agentless passive it is recommended to the more direct we recommend.
AWS voice and tone
## 183
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 193 -->

AWS Content Design System
Refer to the reader as you (second person) and refer to AWS as we (ﬁrst person). If there are
multiple authors for a blog post, you can use we to refer to the authors as individuals.
For procedures or instructions, make sure that the action is taken by the reader ("Now you provision
the NAT instance...") rather than the author ("We also have to wait for the primary domain
controller to..."). Reserve the ﬁrst person plural for speaking as AWS, with recommendations,
warnings, or explanations.
In general, use the present tense and discuss the current state and behavior of features and
services as though you are sitting beside the customer at the moment when they refer to the
documentation. Use the future tense only when an event happens later than—not immediately
after—the action under discussion. Avoid using language that implies promised outcomes, such as
"currently," "at this time," and "yet."
For more information, see Messaging Dos and Don’ts on the AWS Legal Pathﬁnder website.
## Tone
We talk to customers in their own words, never assuming that they understand how our services
work. We use precise technical terms where appropriate, but we avoid technical jargon and insider
lingo. We speak to customers in straightforward, plain, everyday language.
The tone of AWS is direct and friendly. The overall tone is informal, informative, and friendly
without getting chatty.
Avoid excessive words, such as "please." Be courteous but not wordy. Extra detail can often be
moved elsewhere.
## Topics
## • Contractions
• Modal verbs
• Tone traits
## Contractions
Use contractions carefully for a more casual tone. Use common contractions. Avoid future tense
(I'll). Don't use archaic ('twas), colloquial (ain't), or compound (couldn't've) contractions.
AWS style
## Tone
## 184
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 194 -->

AWS Content Design System
• With be – I'm, you're, he's, she's, it's, we're, they're
• With not – isn't, aren't, doesn't, don't, can't, couldn't, shouldn't, won't, haven't, hasn't
• With have – you've, they've, we've
Not AWS style
• With will – I'll, you'll, he'll, she'll, it'll, we'll, they'll
• With not – ain't, mayn't, mightn't, oughtn't, shan't
• With it – 'twas, 'twere, 'tis
• Compounds with have – couldn't've
• With nouns – Amazon'll
Modal verbs
Modal verbs are a class of verbs that include can, must, would, and should. These words help set
the tone of your writing and describe how certain or necessary something is. To keep your message
clear and direct, consider how you use these words.
The following table provides a general overview for how to use modal verbs. For more details
about using each term, see the term's entry in the Usage dictionary.
Modal verb
Usage guidance
be able to
Avoid if possible.
See Tighten your prose.
can
Use to express capability.
could
Don't use could to mean   can or might.
OK to use for something that already
happened or that's in the  past (for example,
the server couldn't   load).
have to
Replace with must or need  to.
## Tone
## 185
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 195 -->

AWS Content Design System
Modal verb
Usage guidance
may
Avoid if possible.
Don't use may to mean might or can.
might
Use to express possibility. Don’t substitut
e with may, which might be interpreted as
providing permission.
must
Use to assert obligation.
need to
Use to express needs and requirements.
ought to
Don't use.
shall
Don't use.
should
Don't use to mean will or   must.
For recommendations, use "we recommend" or
"consider."
See Tighten your prose.
will
Avoid if you can use present tense instead. See
Voice.
OK for future events (for example, will no
longer be supported).
would
Avoid if possible.
For more information about how to distinguish diﬀerent modal verbs, see Words that can help
clarify.
## Tone
## 186
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 196 -->

AWS Content Design System
Describing requirements and recommendations
Modal verbs shape our communication with the customer. For example, must and need, though
similar in meaning, establish diﬀerent tones of voice. When it comes to describing requirements
and recommendations, it’s helpful to consider both clarity and the tone of voice.
• If you want to be direct with the customer, use an imperative sentence.
AWS style
• Use the AWS Management Console.
Not AWS style
• You might want to use the AWS Management Console.

• If it's important to clarify that something is not optional, use must.
AWS style
• You must use the AWS Management Console for this procedure.
Not AWS style
• You need to use the AWS Management Console for this procedure.

• For a gentle reminder, use make sure.
AWS style
• Make sure that you have a stable internet connection.
Not AWS style
• Don't forget to check that you have a stable internet connection.

• For a speciﬁc requirement within a particular context, use need to.
AWS style
• If you change the conﬁguration, you might need to stop the instance.
Not AWS style
## Tone
## 187
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 197 -->

AWS Content Design System
• If you change the conﬁguration, you should stop the instance.

• If you want to suggest or recommend something that's optional, use we recommend or consider.
AWS style
• We recommend the following best practices:
• Consider the following best practices:
Not AWS style
• The following best practices are recommended:
• The following best practices should be considered:

When describing requirements, consider your priorities and tone. Don't use should because should
can mean optional. Must is unambiguous but can sound harsh and might not be necessary when
there's suﬃcient context.
• You must → [Delete entirely]
Exception: Only use "you must" for requirements, not for recommendations.
AWS style
• You must provide a value.
• make sure that you...
• you set...
• To..., set...
Not AWS style
• You must make sure that they receive or can get the source code.
• you have to...
• To..., you can...
## Tone
## 188
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 198 -->

AWS Content Design System
Before using should or must, consider other ways to discuss recommendations or requirements,
such as the imperative mood for required actions and a phrase such as we recommend for optional
ones. Be careful to make your tone helpful, not bossy.
## Examples
• You will need an internet connection to install the upgrade.
• We recommend that you wait for us to notify you.
• Free technical support is available when you register with Microsoft.
When not to use a modal verb
Modal verbs are used to show possibility, intent, and necessity. If your sentence is clear without
using a modal verb, don't use one. Imperative sentences are shorter and more direct.
You should → [Delete entirely]
You need → [Delete entirely]
Be direct and use the right modal verb. For example, instead of have the option to, use can, and
instead of must be able to, use must.
Tone traits
As you write content, apply the following tone traits.
## Approachable
What it is
What it isn't
## Personable
## Chatty
## Friendly
## Hyperbolic
## Welcoming
## Cloying
## Genuine
## Insincere
## Tone
## 189
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 199 -->

AWS Content Design System
## Authoritative
What it is
What it isn't
## Professional
## Stuﬀy
## Expert
## Dictatorial
## Informed
## Smug
## Dependable
## Unsure
## Validated
## Untested
## Concise
What it is
What it isn't
## Succinct
## Wordy
## Brief
## Lengthy
## Lean
## Verbose
To the point
## Rambling
## Conversational
What it is
What it isn't
## Informal
## Stilted
## Casual
## Pompous
## Familiar
## Chummy
Matter-of-fact
## Pedantic
## Tone
## 190
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 200 -->

AWS Content Design System
## Directed
What it is
What it isn't
## Focused
## Vague
## Guided
## Wandering
## Controlled
## Confusing
## Purposeful
## Ambiguous
## Predictable
## Surprising
## Deﬁnitive
## Indecisive
## Essential
## Redundant
## Respectful
What it is
What it isn't
## Considerate
## Insulting
## Helpful
## Condescending
## Supportive
## Insensitive
## Empathic
## Indiﬀerent
## Simple
What it is
What it isn't
## Plain
## Fancy
## Everyday
## Esoteric
## Recognizable
## Perplexing
## Tone
## 191
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 201 -->

AWS Content Design System
What it is
What it isn't
## Clear
## Unintelligible
## Straightforward
## Complicated
## Common
## Unusual
## Smart
What it is
What it isn't
## Knowledgeable
## Pedantic
## Logical
## Invalid
## Correct
## Inaccurate
## Consistent
## Varying
## Coherent
## Disorganized
## Grammatical
## Careless
## Polished
## Sloppy
## Trustworthy
What it is
What it isn't
## Reliable
## Infallible
## Truthful
## Evasive
## Fair
## Devious
## Candid
## Obfuscating
## Tone
## 192
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 202 -->

AWS Content Design System
Voice and tone examples
The following "before and after" examples show the real-world beneﬁts of applying the AWS voice
and tone. The examples are from the consoles, but the same principles apply to the technical
documentation.
General instructional text
## Before
## After
You have no Reserved Nodes. Click the
Purchase button above to begin purchasing a
reserved node oﬀering.
You don't have any reserved nodes. If you
want one, choose Purchase reserved nodes to
get started.
## Before
## After
You can store an unlimited number of archives
and an unlimited amount of data in Amazon
Glacier.
Store as many archives and as much data as
you want in Amazon Glacier.
Dialog box
## Before
## After
Enable detailed monitoring for your instance
to get these metrics at 1-minute  frequency.
Learn more
Are you sure you want to enable detailed
monitoring for the following instances?
(Additional charges apply.)
Your instance sends metric data to Amazon
CloudWatch every ﬁve minutes at no charge.
For an additional cost, you can turn on
detailed monitoring to send  metric data every
minute. Learn more
Voice and tone examples
## 193
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 203 -->

AWS Content Design System
Alerts and notiﬁcations
## Before
## After
Users connecting to an AWS CodeCommit
repository for the ﬁrst time must complete
setup  steps before they can use it. Learn more
Heading: Connecting to this repository for the
ﬁrst  time?
Body text: You must set up your computer
before continuing.
Text above a table
## Before
## After
Each trails listed below is resulting in extra
copies of events. Select trails to remove. All
listed trails may be safely deleted while still
maintaining a complete record of all events
through the trail(s) conﬁgured to deliver
events from all Regions. The “Duplicate”
column indicates whether the extra trail is
resulting in duplicate events in the exact same
S3 bucket and preﬁx as a trail conﬁgured to
deliver events from all Regions.
The following trails are receiving duplicate
events. Delete the trails that you don’t  need
to avoid additional costs. Learn more
Tooltip next to a ﬁeld
## Before
## After
These roles are the roles belonging to you
that are assumable by Elastic Transcoder. T
hey must grant Elastic Transcoder the correct
permissions on your S3 buckets and SNS
topics to be transcoded.
An IAM role gives Elastic Transcoder permissio
ns to convert your ﬁles. Learn more
Voice and tone examples
## 194
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 204 -->

AWS Content Design System
Wizard step
## Before
## After
The Setup Wizard will install Amazon
WorkMail Migration Tool on your computer.
Click Next to continue or Cancel to exit the
Setup Wizard.
Setup installs the Amazon WorkMail migration
tool on your computer. You can use the tool to
migrate your mailboxes stored in other email
systems  to Amazon WorkMail.
Download instructions
## Before
## After
Click the button to download a report that
lists all your account’s users and the  status
of their various credentials. After a report is
created, it  is stored for up to four hours. For
more information see the documentation.
Download a list of users in your account and
the status of their credentials. Learn more
Error messages
## Before
## After
Cannot upload attachments. The total
attachment size is x while the allowed
maximum is y.
We can’t upload your attachments because
the total size exceeds the y quota. Reduce the
size, and try  again.
## Before
## After
You have reached the quota of maximum
applications that you can deploy for your
account. Please archive your unused active
applications or delete  your error applications
for new application deployments to succeed.
You’ve reached the quota of applications that
you can deploy for your  account. Archive or
delete applications that you don’t need, or
request a quota increase.
Voice and tone examples
## 195
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 205 -->

AWS Content Design System
## Before
## After
Learn more about service quotas or request a
quota increase.
## Original
First revision
Second revision
public static ﬁnal String
ARN_OR_ID_DISALLOWED
Values for the ConﬁgRuleArn
and ConﬁgRuleId parameters
are not accepted in a request
to create a Conﬁg rule. AWS
Conﬁg generates the ARN and
ID when it creates the rule. R
emove these values from your
request, and try again.
Remove the ConﬁgRuleArn
and ConﬁgRuleId parameters,
and try again.
## Capitalization
Use the following guidelines for capitalizing titles, headings, service names, feature names, ﬁle
names, and ﬁle formats.
AWS style uses lowercase for nouns and noun phrases that are not proper nouns—for example big
data. This style follows the standard rules of American English grammar.
## Topics
• Titles and headings
• Service names
• Feature names
• File names and ﬁle formats
Titles and headings
Use sentence case for titles, headings, and subheadings. Capitalize proper nouns, including service
names.
## Capitalization
## 196
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 206 -->

AWS Content Design System
Service names
Use title capitalization for service names. For oﬃcial names, see the Oﬀering names wiki.
Feature names
Use lowercase for feature names. For existing feature names, use title case when necessary to be
consistent with the product team usage.
File names and ﬁle formats
In general, always use all caps for ﬁle format abbreviations—for example HTML.
However, when referring to an actual ﬁle name (such as getting_started.html), use all lowercase
letters and include the period.
AWS style
• Extract the contents of deployment_package.zip.
• Save the ﬁle as index.html.
• Use the appropriate HTML tag.
• This is the default interface for storing and retrieving XML elements.
• These features are ignored in PDF output.
Not AWS style
• Extract the contents of deployment_package.ZIP.
• Save your work as an .html ﬁle.
• Use the appropriate .html tag.
• This is the default interface for storing and retrieving .xml elements.
Consoles and user interfaces
Consistent, succinct, and clear text is a critical component of a good user interface (UI). Writers and
editors help our AWS users complete their tasks by providing instructions that follow a logical ﬂow.
This topic provides UI tenets, UI best practices, and a UI checklist for writers and editors. It also
provides guidelines for content in help panels on the AWS consoles.
Service names
## 197
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 207 -->

AWS Content Design System
For information about developing a consistent voice for both UI text and help documentation,
see AWS Voice and tone in this style guide. For UI text guidelines, see the individual articles for
each design pattern in the Cloudscape Design System. For information about speciﬁc parts of the
AWS Management Console and how to refer to them in documentation, see Console description. If
you're looking for information about error messages and alerts, see Alerts and messages.
## Topics
• UI tenets
• UI best practices
• UI checklist for writers and editors
• Console description
UI tenets
• Conversational. We use natural, conversational language that speaks directly to users. We avoid
coining new terms or creating feature names when a description would suﬃce instead. We favor
short words and brief, direct phrases.
• Consistent. We employ consistent language and UI conventions, never forcing users to
interpret the interface. Consistent, predictable UI helps users explore our services with ease
and conﬁdence. UI text guidelines and UX design patterns are our top tools for establishing
consistency.
• Succinct. Research shows that the more words we put in front of users, the fewer words that
they're likely to read. We cut any word that doesn't serve a purpose. We don't waste users' time
with messages such as "There's a problem." Instead, we directly tell them what the problem is.
• Planned. We think about UI text early in the design process. We structure our text so that it can
be understood at a glance. This gives us time to iterate on text and to ﬁx design problems that
the text might reveal.
• Clearly labeled. We create speciﬁc, self-explanatory labels. Headings, buttons, links, and other
labels should be speciﬁc enough that users can understand the UI and make decisions, without
having to pause or read instructions. Users tend to focus not on instructional text but on the
labels of the controls they plan to use, so these labels must speak for themselves.
• Eﬀortlessly navigated. We use bullets, blank space, and bold font to break blocks of text into
bite-sized chunks.
• Device and language agnostic. We write text that works across diﬀerent devices and for
diﬀerent languages. We ask whether a piece of text is too long for a smaller screen or a localized
UI tenets
## 198
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 208 -->

AWS Content Design System
language. It also means that when writing text for a button, link, or menu, we think about
how touchable it is: Is it large enough for a customer to tap on a touchscreen? Is there enough
padding between elements to prevent mis-taps? A link or dropdown list that works great on a
desktop computer might be unusable on a small tablet.
• Accessible. We try to remove obstacles for our users who have disabilities or who must access
our services in alternative ways. For example, we avoid controls that are labeled with images
rather than text. We also provide names, titles, or text labels for each element of the UI.
UI best practices
• Follow the AWS voice guidelines and the UI text guidelines in the Cloudscape Design System.
• Be consistent with other elements on the page and on the rest of a console.
• Use sentence case in the UI, except for service names and other proper nouns.
UI checklist for writers and editors
This checklist is designed to help writers and editors deliver concise, discoverable UI content that's
scannable. The checklist is based on the  printable Amazon UX writing checklist, but it has been
customized for AWS.
Are the most important words ﬁrst?
Help make sure that users don’t scan past your content.
Test: Cover up all but the ﬁrst two or three words. Can you still get the gist?
• Eye tracking shows that users don’t read all the words. They frequently only scan down the left
column of text, seeing only the ﬁrst words of each line. Will they see your key message?
• Don’t: Start here to register a domain name
• Do: Choose a domain
• Are you beginning with the exact words that users are likely to scan for?
• In a bulleted list or paragraph, are your most important items placed at the top?
Are your headings, links, and button labels self-explanatory?
Test: Delete all text except your headings and control labels. Could users still proceed correctly?
UI best practices
## 199
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 209 -->

AWS Content Design System
• Most eyeballs jump to headings, links, and buttons, and ignore static text. Are your labels clear?
• Does the heading give a clear, speciﬁc sense of the material it introduces?
• Is the heading redundant with the instructional text below it? Can you omit the latter?
• Do your control labels make it clear what will happen when selected?
• Are the most important words ﬁrst, so users don’t scan past your content?
Do you really need that text at all? Is it in the right place?
Test: Try to think of a design that removes the text altogether. Is it a better design?
• Are you providing information only at the moment that users are most likely looking for it?
• Is your text located immediately next to the interaction that it describes (not a subsequent
interaction, or an interaction somewhere else in the UI)?
• Are you having an unusually diﬃcult time concisely explaining your feature? This is often a
symptom of a ﬂawed design or business goal. Is your text a Band-Aid for a bigger problem?
How much can you cut?
The more you write, the less that users read.
Test: Cut one word. Does it still make sense? Repeat. (For longer messages, cut an entire sentence.)
• Don’t over-communicate. Being speciﬁc doesn’t mean telling users everything that they might
possibly want to know. Does your text focus on a single primary message for each interaction?
• Are there ﬁller words?
• Add items to your list instead of You can add items to your list
## • Redundancies?
• Add an address instead of Add a new address
• Welcome messages or intro text that don’t accomplish anything speciﬁc?
• Don’t: Welcome to AWS Widget Builder! Start building your personalized widget in minutes!
• Do: Build your personalized widget
Have you chosen words that your users use every day?
Are you using everyday words and using them consistently?
UI checklist for writers and editors
## 200
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 210 -->

AWS Content Design System
Test: Does your text contain terms that users have to learn in order to understand? Have you tested
these words in usability labs?
• Many of our users are admins, not developers. They might be familiar with standard technical
terms that are used broadly across the industry, but they might not understand advanced techie
jargon. Can you replace technical jargon with normal, everyday words, even if it means adding a
few extra words?
## Do
• Choose a key pair to connect to your primary node.
• Choose a key pair to connect to your primary node through the Secure Shell (SSH) protocol.
Don't
• Use an existing key pair to SSH into the primary node.
• Are you using terms the same way they’re used elsewhere on AWS?
• We say Conﬁrm your phone number instead of Verify your phone number. Use choose instead
of click. Use delete instead of remove.
• Are you using terms that might be confused with other terms on our site?
Can you break your text into bullets or smaller paragraphs?
Smaller segments are more scannable.
Test: Try breaking your text into bullets or numbered lists. Is it more readable?
• Chunking text into small, digestible fragments makes it more scannable. Could you add more
space? (Caution: Does this push important content below the fold?)
• Are you using headings and bold text to help users quickly ﬁnd key information?
Are you speaking directly to users in a conversational tone?
Test: Read it out loud. Does it sound like natural speech? Is this how you would describe it to your
aunt or uncle?
• Are you using short, direct sentences and plain, speciﬁc words?
• Have you used contractions as you would use them in conversation? To see a list of approved
contractions, see Contractions in the Voice and tone topic.
UI checklist for writers and editors
## 201
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 211 -->

AWS Content Design System
• Do you speak directly to users as you and your?
• Are you writing in the active voice, focusing on the agent performing an action, rather than the
object being acted upon?
• Don’t: These domains can be transferred to your new account.
• Do: You can transfer these domains to your new account.
(Exception: Some passive voice is OK in error messages, to avoid blaming users).
Do your word choices make people feel good about using AWS?
Do you emphasize expansion and possibility rather than limitations and prohibitions?
Test: Does your text contain negative sentiments, such as only, cannot, do not, and never?
• Is your glass half-full, rather than half-empty?
• Don’t: You can have only 50 tags for each resource.
• Do: You can add up to 50 tags for each resource.
• Does your message focus on solutions rather than failures?
• Don't: You haven’t completed your contact information.
• Do: Enter your address.
Will your text work in German, Japanese, Portuguese...?
Test: Imagine that it will be 1.5 times as long as it is in English. Does it still ﬁt the UI?
• Now imagine it in a German mobile app.
• Are there colloquialisms that will be diﬃcult to translate?
• Remember that word order will change for diﬀerent languages.
Does it communicate clearly?
No matter how plain and clear you think your text is, many people will completely misread or
overlook it.
Test: When you think you’re done, show it to a couple of people who are unfamiliar with your
project. How many new blind spots emerge?
UI checklist for writers and editors
## 202
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 212 -->

AWS Content Design System
• Every text contains inherent ambiguity, which is usually invisible to the person who wrote it. How
severe is the potential misunderstanding? How likely is it?
• Can you remove the ambiguity without making the text less clear for most users?
Console description
AWS is updating the look and feel of the AWS Management Console with the Cloudscape Design
System design. This topic shows you the names to use when writing documentation that involves
the console.
## Note
Services are updating their designs on diﬀerent schedules. As a result, diﬀerences in service
consoles will persist until adoption of Cloudscape is complete.
## Topics
• Service home page
• Parts of the console
• Navigation bar
• Navigation pane
• Content pane
• Help panel
## • Icons
Service home page
The ﬁrst time that users navigate to a service console, they typically see the service home page,
also known internally as the ﬁrst run page. To refer to individual service home pages by their
names, use the service name, followed by service home page. For example, refer to the service
home page for Amazon S3 as the Amazon S3 service home page. Don't refer to these pages as ﬁrst
run pages.
Console description
## 203
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 213 -->

AWS Content Design System
Parts of the console
The console consists of the following hierarchical divisions, from largest to smallest: page, pane,
panel, view, section, and card view. At the top of the console, there's a navigation bar.
Console description
## 204
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 214 -->

AWS Content Design System
The main part of the console consists of the navigation pane, content pane, and help panel. You
don't need to refer to the content pane because it's usually called by a speciﬁc name such as
resource list or details page.
Navigation bar
The navigation bar includes controls for accessing service consoles, specifying a Region, and more.
Users can customize the navigation bar with icons for their favorite services.
• Homepage icon
• Services menu
Console description
## 205
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 215 -->

AWS Content Design System
The Services menu allows users to search for a service or to see services listed alphabetically or
by group.
• Pushpin icon
The pushpin icon enables drag-and-drop customization of the navigation bar.
Customized navigation bar
Console description
## 206
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 216 -->

AWS Content Design System
• Navigation bar with Region selector
• Region selector
Console description
## 207
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 217 -->

AWS Content Design System
Navigation pane
The navigation pane is the far left pane. Users can collapse the navigation
pane by choosing the X icon or expand it by choosing the menu icon
## (
).
Content pane
The content pane typically displays available resources and tools for creating and managing
resources.
• Resource list
Many service consoles display resources in a table format.
Console description
## 208
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 218 -->

AWS Content Design System
• Card view
Some service consoles display resources or groups of resources in special sections known as
cards.
• Wizard page
Resource creation is often handled through a single- or multipage form, sometimes called a
wizard. However, try to avoid the term wizard. Use the page names instead.
Console description
## 209
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 219 -->

AWS Content Design System
• Details page
Choosing a resource name typically displays a page with additional details and conﬁguration
options.
Console description
## 210
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 220 -->

AWS Content Design System
Help panel
A help panel is a special type of collapsible, scrollable panel that appears on the right side of a
console to provide in-context user assistance. For more information, see Help panel.
Console description
## 211
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 221 -->

AWS Content Design System
## Icons
The following table shows a selection of the icons that commonly appear on the AWS consoles. The
table also shows how to refer to the icons in the service documentation, for example, in the rare
cases when you might need to refer to an icon in a console procedure.
You can ﬁnd the .jpg ﬁles for the icon images at https://code.amazon.com/packages/
AWSStyleGuide/trees/heads/mainline/--/latest/userguide/images.
## Note
The Cloudscape Design System includes a similar, more comprehensive table of icons in the
Iconography topic. However, the Cloudscape team uses code-based names for some of the
icons. The icon names aren't always the same ones that we use in public documentation.
For example, they use caret-right-ﬁlled, but we use right arrow. The following table shows
the friendly names that we use in customer-facing documentation.
Console description
## 212
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 222 -->

AWS Content Design System
IconName
## Example
arrow (up arrow, down arrow, right
arrow, left arrow)
To close the section, choose the down arrow
## (
).
arrow (right arrow, left arrow)
double arrows (double-right arrows,
double-left arrows)
To advance the page, choose the right arrow
## (
).
To view more pages, choose
the double-right arrow
## (
).
calendar icon
To set a date, choose the calender icon
## (
).
copy icon
To copy the code, choose the copy icon
## (
).
download icon
To download the ﬁle, choose the download icon
## (
).
edit icon
To edit the conﬁguration, choose the edit icon
## (
).
expand icon
To open the section, choose the expand icon
## (
).
ﬁlter icon
To ﬁnd a resource, enter the resource name
in the ﬁlter box next to the ﬁlter icon
## (
).
full view
To expand the page, choose the full view icon
## (
).
help panel icon
To open the help panel,
choose the help panel icon
Console description
## 213
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 223 -->

AWS Content Design System
IconName
## Example
## (
## )
in the upper-right corner.
horizontal view
To change to a horizontal view,
choose the horizontal view icon
## (
).
menu (can be horizontal lines or
vertical lines)
To open the navigation
pane, choose the menu icon
## (
).
microphone icon
To begin recording, choose the microphone icon
## (
).
notiﬁcation icon
To view your notiﬁcations,
choose the notiﬁcation icon
## (
).
plus sign
To add another IP address, choose the plus sign
## (
).
refresh icon
To refresh your data, choose the refresh icon
## (
).
magnifying glass (or refer to "search,"
"search icon," or "search box")
To ﬁnd a resource, enter the resource name in the
search box.
settings icon (or refer to "preferences
icon")
To change your settings, choose the settings icon
## (
).
To change your preferences,
choose the preferences icon
## (
).
Console description
## 214
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 224 -->

AWS Content Design System
IconName
## Example
share icon
To share your rule group, choose the share icon
## (
).
undo icon
To undo an action, choose the undo icon
## (
).
upload icon
To upload your ﬁle, choose the upload icon
## (
).
vertical view
To change to a vertical view,
choose the vertical view icon
## (
).
## X
To close the page, choose the X in the upper-right
corner.
## Global English
AWS documentation serves a worldwide audience. To do so, we must write content that English as
a Second Language (ESL) readers can comprehend. Our content should also be straightforward and
translatable into other languages.
Fortunately, content that is optimized for a worldwide audience is generally good for all audiences.
## Note
AWS style adheres to American English usage.
Syntax guidelines
Following are some guidelines for writing content for a worldwide audience.
## Topics
• Keep sentences short
## Global English
## 215
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 225 -->

AWS Content Design System
• Watch for verb-like words that end in "-ing"
• Watch for verb-like words that end in "-ed"
• Keep adjectives and adverbs close to the words that they modify
• Avoid slang, jargon, and colloquialisms
• Avoid Latin phrases
• Use standard terminology and formats
• Use complete sentences
• Use precise words that have only one meaning
• Use optional clarifying words
Keep sentences short
Long sentences with multiple clauses, even when beautifully written, can be hard for ESL readers
to follow and painful for translators. Where possible, limit your sentences to fewer than 25 words.
Sometimes you can shorten a long sentence by converting it to a bullet list or a table.
For more information, see Break up sentences and paragraphs in Writing basics.
Watch for verb-like words that end in "-ing"
Because "-ing" words can be nouns, adjectives, or gerunds, they can slow down ESL readers who
have to ﬁgure them out. Avoid "ing's" in regular text if you can. If you can't ﬁnd an alternative,
sometimes you can add a determiner to clarify whether an "-ing" word is an adjective or a verb. It's
OK to use the gerund verb form in titles, such as Getting started or Setting up.
AWS style
• This is the blocking code. This is blocking the code.
Not AWS style
• This is blocking code.
Watch for verb-like words that end in "-ed"
Like "-ing" words, "-ed" words can be ambiguous. You can often add a determiner to clarify the
function of such a word.
Syntax guidelines
## 216
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 226 -->

AWS Content Design System
AWS style
• Conﬁgure limits for the backup size that are based on the amount of disk space available.
Not AWS style
• Conﬁgure limits for the backup size based on the amount of disk space available.
Keep adjectives and adverbs close to the words that they modify
Watch out for adverbs such as successfully and automatically and especially the word only. For
more information and examples, see just and only.
Avoid slang, jargon, and colloquialisms
Slang, jargon, and colloquialisms can confuse ESL readers.
Avoid Latin phrases
Avoid Latin phrases such as etc., vs., and e.g. Others to avoid are de facto, ad hoc, viz., ergo, and ad
nauseam.
Use standard terminology and formats
Don't try to ﬁnd new, more interesting, or idiomatic ways of saying the same thing. Choose one
term, deﬁne it, and then use that same term every time.
Similarly, make sure that you consistently use AWS preferred formats and use standards that a
global audience can understand.
These standard formats include the following:
• Use our preferred date and time formats (for example, October 1, 2022, 2022-10-01, and UTC-8).
For more information, see dates and UTC.
Use complete sentences
Don't break up sentences by using bullets, code examples, screenshots, or other methods.
AWS style
Before you launch your jet pack, do the following:
Syntax guidelines
## 217
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 227 -->

AWS Content Design System
• Adjust your seat
• Fasten your seatbelt
• Adjust the rear and side mirrors
Not AWS style
Before launching your jet pack, you should
• adjust your seat,
• fasten your seatbelt,
• and adjust the rear and side mirrors.
Use precise words that have only one meaning
The terms once and may are examples of words that have multiple meanings, which can slow an
ESL reader down. For example, once can mean either one time or after. Use the term after when
that's the sense that you intend. May can mean either has permission to or might. Use the term
might when that's the sense you intend.
For additional examples, see the following table of ambiguous words.
Use optional clarifying words
We recommend that you use the following clarifying words.
• Optional pronouns (who, that)
• Optional determiners (a, an, the, this, such as, which)
• If/then pairs (if including the pair is essential for meaning or to reduce the risk of any
misinterpretation)
• Optional punctuation (such as commas after introductory phrases)
These elements help ESL readers keep track of clauses and antecedents.
AWS style
• Perform a local build to make sure that you haven't introduced errors.
Not AWS style
Syntax guidelines
## 218
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 228 -->

AWS Content Design System
• Perform a local build to make sure you haven't introduced errors.
For examples of clarifying words, see the following tables.
Words that can help clarify
The following table shows some examples of ambiguous words, with words that you can use
instead.
Don't
use
## When
you
mean
AWS style
Not AWS style
## As
BecauseBecause the DB instance for this
tutorial is private, add a second private
subnet to the VPC.
As the DB instance for this tutorial is
private, add a second private subnet to
the VPC.
## Could Can
You can pull the image by using the
controller.
You could pull the image by using the
controller.
Could Might If you choose Sync now, it might still
take several minutes to synchronize.
If you choose Sync now, it could still
take several minutes to synchronize.
## Due
to
## Because
of
There might be a delay because of
latency.
There might be a delay due to latency.
## Just
## Only
The Memory metric is returned only for
resources with the uniﬁed CloudWatch
agent installed.
The Memory metric is just returned for
resources with the uniﬁed CloudWatch
agent installed.
## May
Might The eﬀect of some rule changes might
depend on how the traﬃc is tracked.
The eﬀect of some rule changes may
depend on how the traﬃc is tracked.
## Once
## After
After you create and register an
Amazon Machine Image (AMI), you can
use it to launch new instances.
Once you create and register an
Amazon Machine Image (AMI), you can
use it to launch new instances.
ShouldMust
The name must be unique within your
account.
The name should be unique within your
account.
Words that can help clarify
## 219
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 229 -->

AWS Content Design System
Don't
use
## When
you
mean
AWS style
Not AWS style
## Since
BecauseBecause public (IPv4) internet
addresses are a scarce public resource,
all AWS accounts are limited to ﬁve
Elastic IP addresses in each AWS
Region.
Since public (IPv4) internet addresses
are a scarce public resource, all AWS
accounts are limited to ﬁve Elastic IP
addresses in each AWS Region.
## While Although
or
whereas
Although an instance store is dedicated
to a particular instance, the disk
subsystem is shared among instances
on a host computer.
While an instance store is dedicated
to a particular instance, the disk
subsystem is shared among instances
on a host computer.
The following tables show some examples of clarifying words to set oﬀ clauses and make text
more readable.
## Pronouns
AWS style
Not AWS style
## That
Perform a local build to conﬁrm that you
haven't introduced errors.
Perform a local build to ensure you
haven't introduced errors.
## Who/
who
are
CodementorX has vetted AWS developer
s who are available for hire and remote
work.
CodementorX has vetted AWS developers
available for hire and remote work.
ArticlesAWS style
Not AWS style
a, an
You can submit your WordPress podcast as
an oﬃcial iTunes podcast source.
You can submit your WordPress podcast as
oﬃcial iTunes podcast source.
the
Use full quotation marks (" ") around the
input text.
Use full quotation marks (" ") around input
text.
Words that can help clarify
## 220
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 230 -->

AWS Content Design System
For more information about language for global English, see Plain Language Action Network.
## Images
This topic provides information about incorporating images and screenshots in AWS content so
that they're helpful and accessible. The topic also includes common use cases, best practices, and
links to design resources.
To help customers visualize concepts, systems, and processes, writers can include images in
their content, such as diagrams, graphics, ﬂowcharts, and screenshots. At AWS, we use images
and screenshots to support written content, not to replace it. Written content should be
comprehensible without images.
To comply with accessibility requirements, all images require alt text. We also recommend that
the content that precedes an image states what's important and relevant about the image. This is
called lead-in content.
## Topics
• Creating images
• Guidelines for images
• Using screenshots
• Avoiding security issues in images
• Legal requirements
• Regional branding requirements
• Localization guidelines
• Alt text and lead-in content
Creating images
Images used in public content must conform to AWS design guidelines, including color, padding,
font, and more.
Refer to the following AWS design guidelines:
• Diagrams for AWS Documentation
## Images
## 221
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 231 -->

AWS Content Design System
• AWS Architecture Icons
To request help with images, contact the  doc graphics group.
## Note
Before you use stock images, refer to the AWS legal guidelines in Pathﬁnder.
Guidelines for images
To include images in your content, follow these guidelines:
## Do
• Place the image after a procedural step or descriptive paragraph. This introduces the image and
gives it context.
• Follow best practices for accessibility and alt text.
Don't
• Don't embed explanatory text in images. Embedded text isn't accessible, and it presents
localization issues.
• Don't use images alone to convey information. Always write detailed lead-in content.
Using screenshots
A screenshot is a digital capture of a device's current screen display, such as an open webpage or
application. Sometimes screenshots don't improve the customer experience. For example, text that
appears in a screenshot presents localization and accessibility issues for many customers.
## Note
After you write clear lead-in content, you might determine that the screenshot is no longer
necessary, in which case you can remove it.
## Do
Guidelines for images
## 222
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 232 -->

AWS Content Design System
• In procedures, use screenshots to point out hard-to-ﬁnd UI components, show new or unfamiliar
UI, and show a single step in a process.
• Use screenshots sparingly to reduce image maintenance, and to help prevent accessibility and
localization issues. For example, don't use screenshots to replace written content.
• To help customers access screenshots, follow the requirements for alt text and guidelines for
lead-in content.
• You can also make screenshots more helpful by following these guidelines for these speciﬁc use
cases:
• When using screenshots to help customers locate speciﬁc components or areas in complex
user interfaces, follow the procedure phrasing guidelines so that customers can locate UI
components by label name. Alert the UX team about confusing UI so that they can improve it.
• For screenshots that highlight key actions or steps, write clear procedures about those steps
and actions. However, avoid screenshots that show an action or step that customers can
quickly see or ﬁnd in the user interface.
• With a dynamic ﬁeld, one ﬁeld controls the values that a user can choose in another ﬁeld. If
you include a screenshot of dynamic ﬁelds, write preceding content that explains the relevant
details about the screenshot. This is so that all customers can read and understand it. For
example, describe the user options, queries, and settings that populate the ﬁelds.
• Customize screenshots based on customer familiarity with the subject matter and skill level.
• You can use screenshots to show menus, context menus, submenus, multiple subsets of
information, and selection options. Describe this in your written content so that customers
who use assistive technology also learn what's important about the screenshot.
Don't
• Don't use screenshots for code examples and error codes. To display code, write it in code blocks
so that everyone can access it. Screenshots of code or text aren't accessible.
• Don't use screenshots of tables. Instead, create a table, or copy and paste the table from the
original authoring tool.
• Don't use screenshots to convey messaging, such as dialog boxes, pop-ups, and notiﬁcations.
Instead, write the messaging in your content, and explain why and when it occurs.
• Don't use screenshots for content that's subject to frequent updates or changes. Instead, write
descriptions that you can modify and update as needed.
Using screenshots
## 223
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 233 -->

AWS Content Design System
• Don't use screenshots to capture dynamic content, such as a video or interactive elements. For
more information, see Videos and Slide presentations.
• Don't use screenshots for outcomes and progress bars. When customers follow procedures
and tutorials, they already see the outcomes and progress. We recommend omitting these
screenshots.
• Don't use screenshots of UI and well-known actions. For example, a screenshot of a prominent
button or a "File  → Print" menu is unnecessary.
## More Resources
For information about creating and formatting screenshots, see the  Create, modify, and add
graphics and screenshots wiki.
Avoiding security issues in images
This section describes some common security issues in images and how to avoid them. This isn't a
comprehensive guide. If you have any security questions, contact your service's security reviewer or
contact AWS security.
Best practices
• Protect conﬁdential and sensitive information by knowing what to redact in screenshots. For
more information, see Hiding Sensitive Information.
• When creating graphics, only use the safe content that we provide in Fictitious examples.
• Obfuscate sensitive information. The Support Tools Program (STP) has a Greasemonkey script
that blurs sensitive information on the AWS Management Console, Command Center, and
Isengard. For more information, see Sensitive Information Obfuscation Script.
## More Resources
• For questions about security, or to request a review of your content, see the Security Review
Process Details.
• For information about safeguarding customer information or other concerns, see the AWS Legal
Pathﬁnder website. See also Personal Identiﬁable Information (PII) Compliance Guidance for
Global Learning Content.
Avoiding security issues in images
## 224
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 234 -->

AWS Content Design System
Legal requirements
Logos and media include third-party branding images, stock images, and AWS icons and graphics.
This section provides some basic information about using logos and media.
Best practices
• As a general rule, don't use third-party images, such as graphics, logos, or stock art.
• If you use third-party images, see Messaging Dos and Don'ts on the AWS Legal Pathﬁnder
website.
## More Resources
For more information, see Use of logos and media on the AWS Legal Pathﬁnder website.
Regional branding requirements
Regional branding requirements ensure compliance with local regulations and brand guidelines in
diﬀerent AWS regions.
## Do
• Use region proﬁling to remove content. Writers are responsible for including or excluding
content based on publication Region, such as BJS, APA/DCA, LCK. To remove graphics and
content based on Region see Region proﬁling in service doc content.
Don't
• Don't use AWS or the AWS logo in graphics for documentation published in the China Regions
(BJS). Instead, provide an alternate version of the graphic with approved substitutions for AWS
branding. For information about using alternate versions of graphics for the China Regions, see
the Update AWS images for China Rebranding.
Localization guidelines
Currently, AWS doesn't localize text in images. For this reason, writers should provide information
about graphics in your written content. Written information is localized and customers can access it
in diﬀerent languages.
Legal requirements
## 225
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 235 -->

AWS Content Design System
## Do
• Keep text minimal in graphics. Instead of text-heavy graphics, write lead-in content that
customers can read. The most important written information about an image should precede the
image, so that the image has context. Secondary or related information can follow the image.
• Avoid complex graphics. A graphic should convey information about one topic. For example,
when writing a paragraph, you don't combine several topics into one. Instead, you write multiple
paragraphs.
Don't
• Don't embed callouts and legends in a graphic. Instead of longer callouts and legends in the
graphic, write the information in the lead-in content that precedes the graphic.
Alt text and lead-in content
To help customers understand what an image is, we use alt text and lead-in content together.
Alt text is a text alternative that accompanies a graphic as metadata. Alt text isn't visible on a
webpage unless the image fails to load. Customers can use assistive technology, such as screen
readers, to read alt text. For more guidance about alt text, including ZonBook schema, see the
Writing alt text for image accessibility wiki.
Lead-in content introduces the image for all customers to access, whether by sight or with screen
readers. For more information, see Lead-in content for images.
## Do
• Include alt text for every image. Use either null alt text or descriptive alt text. Null alt text tells
screen readers that the image provides no important information. Never omit alt text or your
image will not comply to WCAG minimum standards.
• State the most relevant point of the image, because alt text can't be structured.
• To keep alt text brief, we recommend a maximum character count of 125, including spaces. If the
character count exceeds that by 25 characters or so, it will still meet accessibility standards.
• To provide more written information or details about an image, write lead-in content.
• Always end alt text with a period, so that screen readers know when the alt text ends.
Alt text and lead-in content
## 226
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 236 -->

AWS Content Design System
Don't
• Don't start alt text with "Screenshot of," "Illustration of," or "Graphic of." That's redundant,
because a screen reader announces "Graphic" or a similar word at the beginning of alt text.
• Don't mention the type of image that you uploaded unless that is the main point of the image.
• Don't start alt text with "A" followed by an acronym. To a screen reader, "A TV" sounds like "ATV."
• Don't describe color, such as a "blue button" or "orange text in the dropdown list."
• Don't describe markings that were added to images for visual location, such as a circle around a
menu item.
• Don't give instructions in alt text, such as "Choose the Edit proﬁle button." Instead, put that in a
procedure step.
AWS style
• The navigation bar showing the available Regions.
• Workﬂows for replicating, monitoring, and distributing multiple video signals.
Not AWS style
• Arrow pointing to the navigation bar showing the available Regions.
• Choose the orange Save button.
• Screenshot of the Save button with a circle drawn around it.
Lead-in content for images
In AWS content, images are often used to support text-based content. In this topic, an image refers
to all visual content such as a diagram, illustration, photo, screenshot, or graphic.
Before adding an image, consider if customers really need the image to understand a concept or
procedure. If the image is redundant or doesn't add value, consider removing the image.
If you decide to keep the image, write highly descriptive lead-in content for the image before you
write alt text. Lead-in content precedes the image and includes details about an image that help
customers understand it. After you write the lead-in content, you can summarize that into concise
alt text.
Lead-in content for images
## 227
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 237 -->

AWS Content Design System
## Note
When written lead-in content is detailed and helpful, your customers might not need the
image after all. Having fewer images reduces documentation maintenance.
Lead-in content beneﬁts customers in the following ways:
• Lead-in content is written on the webpage for all customers to access, whether by sight or with
screen readers.
• You can structure lead-in content with lists, paragraphs, and headings to make the content
scannable and uncomplicated to understand. You can’t structure the alt text strings, so we
recommend keeping those brief.
• Alt text isn’t visible on a webpage unless an image breaks, but everyone can read lead-in
content.
• There’s no character limit for lead-in content.
Referring to an image
When describing an image in the lead-in content, use the term that most accurately describes it,
such as graph, illustration, photo, or diagram. However, don’t use these terms in alt text unless the
type of image is the main point. For details about referring to image type, see When is the type of
image relevant? and How to describe graphs in the Writing alt text for images wiki.
When referring to the orientation of the image within a document or on a page, instead of using
the word below, use following. Instead of using the word above, use previous or preceding.
Writing lead-in content for images
Write lead-in content that helps customers understand an image. Explain what the image
represents that’s relevant to the subject matter.
If the information is complex, your lead-in content can include subheadings, paragraphs, and lists
to structure that information. For a screenshot of a user interface in a procedure, put the lead-in
content in steps or substeps.
Lead-in content for images
## 228
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 238 -->

AWS Content Design System
Don’t use a screenshot to replace text
If an image has text that customers must read, your lead-in content must state what it says. Don’t
use a screenshot of blocks of text and messages. Instead, write that in a paragraph or code block.
Many customers can’t read text in a screenshot.
AWS style
• The following error occurs when an IAM user tries to access billing information in the console but
doesn’t have the required IAM role permissions.
## You Need Permissions
You don’t have permission to access billing information for this account. Contact your AWS
administrator if you need help. If you are an AWS administrator, you can provide permissions
for your users or groups by making sure that (1) this account allows IAM and federated users to
access billing information and (2) you have the required IAM permissions.
Not AWS style
• An IAM user sees the following message when they try to use the console without the required
permissions.
Describing graphics in lead-in content
Because some customers can’t see images, describe pertinent information in lead-in content, such
as where to ﬁnd UI components or what the graphic represents. The methods for lead-in content
diﬀer for conceptual and procedural topics.
Lead-in content for conceptual content
Write a paragraph that describes what the graphic represents. In most cases, you can summarize
what the graphic represents. That summary can go into your lead-in content.
However, to help customers understand what the graphical elements represent, you can describe
those elements and say why they’re important. Make sure that the graphical element has a label
Lead-in content for images
## 229
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 239 -->

AWS Content Design System
and that you refer to that label verbatim. For example: The triangle represents the New users
category.
## Note
Don’t describe graphical elements unless they’re necessary to understand vital information
in the graphic.
To describe complex graphics, such as workﬂow diagrams, you can do one of the following:
• If you can describe the main points of an image within a paragraph and a short list: Write that
information in the lead-in content that precedes the image.
• If your graphic requires several paragraphs, subheadings, and lists to organize complex
information: Write a brief summary preceding the image and also structure additional
information after the image. For more information, see Including structured information after
the image.
Lead-in content that summarizes an image
The lead-in content for the following image summarizes its main point in a paragraph that
precedes the image. The image is of a workﬂow diagram.
Example of a summary that precedes an image
The following illustration shows how you can use MediaConnect CDI workﬂows to replicate and
distribute video to multiple destinations. You can create a single output broadcast from video
content coming from multiple events, and send the output from multiple signals for monitoring in
real time.
Lead-in content for images
## 230
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 240 -->

AWS Content Design System
Alt text: CDI workﬂows for replicating, monitoring, and distributing multiple video signals.
Including structured information after the image
When you need more than a paragraph to describe an image, you can also include structured
information (for example, a list) before or after the image.
If the information is complex, we recommend starting with a summary, then the image, and then
using lists or multiple subheadings and paragraphs.
Example of a summary that precedes an image
The following illustration shows three options and use cases for containers: Using pre-built
Docker containers with SageMaker, extending a pre-built Docker container, and building your own
container.
Lead-in content for images
## 231
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 241 -->

AWS Content Design System
Alt text: Options for building a custom container, extending a container, or using a pre-built
container.
After the image, you can provide structured information, such as multiple paragraphs,
subheadings, or lists.
Example of structured information that follows an image
After you determine the type of container that you need, the following information provides
details about container options:
• List item – Provide details about using pre-built SageMaker framework
containers.
• List item – Provide details about extending a pre-built Docker container.
• List item – Provide details about building your own container.
Lead-in content for images
## 232
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 242 -->

AWS Content Design System
To learn how to write helpful lists and subheadings, see Lists and Titles and headings.
Lead-in content for procedures
A procedure is a series of numbered steps that a customer follows to complete a task. Generally,
images in procedures don’t have lead-in paragraphs for the following reasons:
• A procedure’s steps provide vital information about a task and interface, such as a console. It’s
redundant to duplicate that information in a lead-in paragraph.
• An image in a procedure shows where to ﬁnd the UI element to use for a speciﬁc step, and it
focuses on one or two UI elements. To keep alt text brief and understandable, we recommend a
maximum of 125 characters, including spaces.
• Alt text example: The AWS Region selector in the menu bar of the AWS
Management Console.
• If you can’t ﬁt some information into alt text, you can include it in the procedure steps or
substeps.
• Because the ﬁrst step of a procedure includes the console’s service name, you can omit that
name in alt text.
For more information, see Procedures and the Add procedures section in the Using ZonBook wiki.
Checklist for lead-in content
• Summarize what the image intends to teach or show customers.
• To help customers understand what graphical elements represent, describe that in your lead-in
content.
• For procedures about an interface, state the relevant UI component label, type, and location.
• For consistency, use the exact words in the image.
• If the lead-in content refers to verbatim interface text, follow the ZonBook wiki guidelines for
typographic conventions.
• Include relevant text from the image so that all customers can read and understand that
information.
• To describe structured graphics, like a ﬂowchart, you can organize information under headings,
multiple paragraphs, and lists.
• Provide details and clarity in lead-in content so that alt text can be brief.
Lead-in content for images
## 233
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 243 -->

AWS Content Design System
For information, see the Writing alt text for image accessibility wiki.
Inclusive language
It’s important for the language that we use at AWS to be inclusive, respectful, and as impartial
as possible. Language that’s not inclusive can be harmful, exclusionary, or reinforce stereotypes.
Current and potential AWS customers have a variety of lived experiences, unique competencies,
and diverse perspectives. The words that we use can have a lasting impact on our relationships with
them, so it’s important to focus on earning trust.
## Topics
• Don't use these non-inclusive words and phrases
• Consider the impact of your language
• Inclusive language in API and command names
• Additional resources
Don't use these non-inclusive words and phrases
The following table provides guidance about American English terms that you must not use in AWS
content. While the list centers on United States English language and culture, the spirit of the list is
global. These principles apply to words with similar meanings in all cultures and languages.
Don't use this term
## Because
Consider this alternative
black day
It applies a negative connotati
on to things that are black
and a positive connotation to
those that are white.
blocked day
blacklist
It applies a negative connotati
on to things that are black
and a positive connotation to
those that are white.
deny list
customer master key (CMK)
See Updating KMS terms
for inclusive language and
the AWS Security Messaging
KMS-related:
AWS KMS key (ﬁrst mention)
Inclusive language
## 234
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 244 -->

AWS Content Design System
Don't use this term
## Because
Consider this alternative
Guidelines on the Growth
## Strategies (Amazon Security)
Wiki.
KMS key (subsequent
mention)
Not KMS-related:
AWS owned key
AWS managed key
customer managed key
demilitarized zone (DMZ)
See the AWS Security
Messaging Guidelines on the
## Growth Strategies (Amazon
Security) Wiki.
perimeter network, perimeter
zone
grandfathered
It has historical ties to
concepts of slavery and racist
social structures.
pre-approved, pre-existing
agreement, legacy approval
master
It has historical ties to
concepts of slavery and racist
social structures.
primary, main, control, leader,
manager, root
master account
It has historical ties to
concepts of slavery and racist
social structures.
management account,
primary account
master node
It has historical ties to
concepts of slavery and racist
social structures. The term
master node is no longer used
by Kubernetes.
control plane, head node
slave
It has historical ties to
concepts of slavery and racist
social structures.
replica, secondary, standby
Don't use these non-inclusive words and phrases
## 235
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 245 -->

AWS Content Design System
Don't use this term
## Because
Consider this alternative
whitelist
It applies a negative connotati
on to things that are black
and a positive connotation to
those that are white.
allow list
## Note
Our list of alternatives isn’t exhaustive. If you have a better alternative that aligns with the
inclusive spirit of this list, it's OK to use it.
Consider the impact of your language
It’s impossible to capture every word or phrase that has the potential to cause harm, but here are
some best practices to consider as you use your judgment.
When writing public content, follow these guidelines for words, phrases, and examples.
## Do
• Embrace the varied and diverse experiences and perspectives of our customers
• Communicate respect
• Describe things in speciﬁc, accurate, and relevant ways
Don't
• Assume ethnic, religious, or racial identities
• Use terms that are appropriated from a speciﬁc culture
• Assume binary gender identities or he/she pronouns
• Model or propagate gender role stereotypes
• Use ableist terms that could cause harm to people with mental or physical health conditions
• Use language that could be perceived as derogatory or violent toward a particular person or
group
Consider the impact of your language
## 236
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 246 -->

AWS Content Design System
Inclusive language in API and command names
Our guidance for the use of inclusive language applies to API names and operations, as well. Follow
the guidance on this page for new API and command names.
If you have an existing API name that isn't inclusive, use the following resources to help you
through the process of deprecating API operations.
For more information about language in APIs, see How to form API names, Reserved nouns and
recommended noun substitutions, Recommended verbs, and Deprecated verbs.
Additional resources
For more information about inclusive language at AWS and beyond, see the following resources:
• Writing at AWS
• Voice and tone
• Fictitious content library
• Disability and Accessibility Language Guide
• KMS terms for inclusive language
• Alternative Phrasings to Unconscious Bias in Communication
• IXT Learning and Capabilities
• IXT: Inclusive eXperiences and Technology
Links and cross-references
This topic provides guidance for links and cross-references in AWS service documentation. When
we use consistent methods and phrases to introduce links and cross-references, we help readers to
navigate more quickly. We also help to reduce translation costs. The type of cross-reference or link
that you use depends on the content that you want to reference or link to (or from).
This topic covers the style issues only, not the mechanics of constructing links using entities and
ZonBook elements. For more information about constructing links, see Add links.
## Topics
• General guidelines for links and cross-references
• Speciﬁc cross-reference styles guidelines and examples
Inclusive language in API and command names
## 237
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 247 -->

AWS Content Design System
• Linking to consoles
• Linking to external resources
• Linking best practices
General guidelines for links and cross-references
Follow these general style guidelines for cross-references and links to content that appears within
an AWS service documentation topic (same-page cross-references) or on diﬀerent webpages (oﬀ-
page cross-references). Oﬀ-page cross-references include other topics within a guide, other AWS
guides, Amazon marketing websites, external URLs, or AWS blog posts.
• Link formatting – Don't add extra formatting to hyperlinks. If the link contains text that
shouldn't be localized (for example, API operations or CLI commands), enclose that text in
<noloc> tags. Don't add terminal punctuation if the link matches the title of the link page that
already has terminal punctuation.
AWS style
IAM User Guide
ListAliases
For more information, see What is ABAC for AWS?
Not AWS style
IAM User Guide
ListAliases
For more information, see What is ABAC for AWS?.
• Reference within the same topic – When you reference something on the same webpage and
the target is less than a screen length away from the reference, don't use a link. Use following,
later, preceding, previous, or earlier without adding a link. Don't use above or below because
these terms don’t align with accessibility recommendations. For examples, see AWS service
documentation.
General guidelines
## 238
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 248 -->

AWS Content Design System
When you reference something on the same webpage and the target is more than a screen
length away from the reference, use a link. You can use Formal cross-references or Embedded
links.
• Multiple references within the same topic – Use a link for the ﬁrst referenced instance only.
Exception: Extremely long webpages can have more than one link.
Cross-reference styles
• Formal cross-references
• Embedded links
Formal cross-references
In most cases, a formal cross-reference is the preferred style because it provides context and helps
readers understand where they're going when they choose the link. Follow these guidelines for
formal cross-references:
• Introduce links with formal introductory text:
• Use "For information about" or "For more information about." Don't use "For information on."
• If you are linking to procedures, you can use either "For instructions on" or "instructions for."
Don't use "instructions about."
• Where space is limited (for example, in a table), you can use "See <link text>." Don't use "go to."
• When you're linking to AWS service documentation, don't hardcode your links because they
might break in localized or special AWS Region builds.
• Don't use shared content URL entities in your links. Instead, follow the best practices
guidelines in Add links.
• You can use the shared content guide name entity (if it exists) or create a local entity for your
guide name if it doesn't. We no longer add guide name entities to shared content.
• Make sure that the link text matches the section title text.
For a list of shared content guide name entities, see the AWS Shared General Entities File.
General guidelines
## 239
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 249 -->

AWS Content Design System
Embedded links
Embedded links are woven into a sentence without formal introductory text. They're especially
useful in tables or other elements where space is tight.
The text around the embedded link must relate to the information in the link so that the reader
understands the context. Do not use here or click here for link text because it creates problems
for accessibility and SEO. In some cases, such as lists of API operations that are linked, context is
not required if you're linking directly to the API operation in the title. See the CreateFunction
example in the following table.
For more information about how to construct links in XML, see Add links.
Speciﬁc cross-reference styles guidelines and examples
This section contains speciﬁc guidelines for diﬀerent kinds of cross-references and examples that
show correct and incorrect cross-reference styles.
## Topics
• AWS service documentation
• External (not AWS) websites
• AWS marketing websites
## • Downloads
• Blogs, whitepapers, and re:Post entries
AWS service documentation
When linking to AWS service documentation, use the following:
• Formal cross-reference style or embedded links style
• Topic or section title for link text, or descriptive link text for embedded links
• The preferred linking method shown in Add links
Speciﬁc cross-reference styles guidelines and examples
## 240
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 250 -->

AWS Content Design System
AWS style
Not AWS style
For more information about managing your
Amazon S3 resources, see Identity and Access
Management for Amazon S3.
See Identity and Access Management for
Amazon S3.
(Exception: you can use "See" links in a table or
other places where space is tight.)
For more information about setting up an
Administrators  group in IAM, see  Create a
user with administrative access   in the IAM
User Guide.
Create IAM users for everyone who needs to
access  AWS OpsWorks, and then import those
users into AWS OpsWorks.
For more info and details on setting up your
Administrators group in IAM, go  to Create a
user with administrative access   in the IAM
User Guide.
In DynamoDB (see Access Control), you
have the option to specify  conditions when
granting permissions using an IAM policy.
Click here to ﬁnd out more about how to
get  everyone access AWS OpsWorks and
then do this to import those users into  AWS
OpsWorks.
For instructions on managing tags to objects
using the Amazon S3 console, see Managing
object tags.
For instructions for installing the SDK for Java,
see Ways to get the AWS SDK for Java.
For instructions, see Getting Started with
Amazon SNS.
For instructions about how to install the AWS
Explorer, see Using the AWS SDKs, CLI, and
Explorers.
CreateFunction
Function  (Link text is generic, doesn't match
the API action,  and doesn't provide any
context.)
For more information, see AWS Command Line
Interface User Guide.
Go to AWS Command Line Interface User
Guide.
Speciﬁc cross-reference styles guidelines and examples
## 241
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 251 -->

AWS Content Design System
AWS style
Not AWS style
In this step, you perform a query on the tables
that you created in the preceding step.
In this step, you perform a simple query on
the tables that  you created above.
The following tasks step you through setting
up your static  website using AWS.
The tasks below step you through setting up
your static  website using AWS.
Information about embedded links is covered
later in this  topic.
Information about embedded links appears
below.
For information about topic lists, see
Automatic (topic) lists.
Automatic (topic) lists provides  detailed
information about creating links to content
that  appears on other webpages.
See Automatic (topic) lists.
Automatic (topic) lists is a helpful  topic.
External (not AWS) websites
When linking to external (not AWS) websites, use the following:
• Formal cross-reference style
• Descriptive link text (better for SEO)
• Webpage title
For external websites that don't have useful titles, describe the site generally.
AWS style
Not AWS style
For more information and to download the
code examples, see Amazon Web Services -
Labs on the GitHub website.
For the code, go to GitHub.
The image is owned by NASA and comes from
the Visible Earth  website.
The visible  earth image is owned by NASA.
Speciﬁc cross-reference styles guidelines and examples
## 242
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 252 -->

AWS Content Design System
AWS style
Not AWS style
For more information about Ruby clients, see
the Ruby  website.
Check out the Ruby clients at the Ruby  webs
ite.
AWS marketing websites
When linking to marketing websites on https://aws.amazon.com/, use the following:
• Formal cross-reference style
• Descriptive link text (better for SEO)
## Note
Don't use product page or details page in the page description or the link text.
• The preferred linking method shown in Add links.
AWS style
Not AWS style
For more information about Amazon ElastiCac
he features, see Amazon ElastiCache.
See the AWS marketing  website.
For answers to frequently asked questions, see
Amazon CloudWatch  FAQs.
For product info, see Amazon ElastiCache
marketing  website.
For information about pricing, see CodeCommi
t  Pricing.
For pricing information, click  here.
## Downloads
Follow these guidelines for links to ﬁle downloads:
• Formal cross-reference style
• Introductory text must contain the term download
Speciﬁc cross-reference styles guidelines and examples
## 243
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 253 -->

AWS Content Design System
AWS style
Not AWS style
To download the sample data archive, choose
sampledata.zip.
Download the sample data archive here.
Download the latest version of Git for
Windows at Downloading  Git on the Git
website.
To download the latest version of Git for
Windows, click  this download   link.
You can download the sample code from
GitHub.
You can download the sample code from
https://github.com/.
Blogs, whitepapers, and re:Post entries
## Important
Most blog posts, whitepapers, and re:Post entries are too specialized to include as a link
from the AWS service documentation, and the content can go stale quickly. Before you add
a link, consider the questions listed in Linking to a blog post.
• From AWS service documentation to blogs – Use Formal cross-references.
• From blogs to AWS service documentation – Use Formal cross-references or Embedded links.
• From AWS service documentation to whitepapers – Follow the guidelines for External (not
AWS) websites. This applies to all whitepapers, even those published by AWS.
• From whitepapers – Follow the guidelines in the Citations section of the AWS whitepaper
template and style guide Word template.
• From AWS service documentation to re:Post Knowledge Center articles – Follow the guidelines
for External (not AWS) websites. Use Formal cross-references.
## Note
We don't recommend linking to customer questions in the Questions section on re:Post.
You can link to articles in the Knowledge Center section, however.
• From re:Post Knowledge Center articles to AWS service documentation – Use Formal cross-
references or Embedded links.
Speciﬁc cross-reference styles guidelines and examples
## 244
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 254 -->

AWS Content Design System
AWS style
Not AWS style
For more information, see the whitepaper
Dynamo: Amazon’s Highly Available Key-value
Store on the All Things Distributed website.
For more information, see this whitepaper at
the Marketing TechBlog  website.
For more information, see How do I gather
the Amazon S3 request ID values requested by
AWS Support?  on AWS re:Post.
For more information, see this Knowledge
Center article on AWS re:Post.
Linking to consoles
Whenever possible, we recommend that you link to the speciﬁc service console that you're writing
about, rather than the top-level AWS Management Console. For example, "Sign in to the AWS
Management Console and open the Amazon RDS console at  https://console.aws.amazon.com/
rds/." For more information about how to construct console links using ZonBook XML and entities,
see Add links.
Linking to external resources
• If possible, link to an AWS or Amazon owned resource instead of an external website. For code
examples or tools that are hosted on external sites, such as GitHub, link directly to an AWS
owned repository or AWS oﬃcial tool. AppSec has approved these resources for use in public
content.
• Don't link to external websites that a customer might perceive to be unreliable or untrustworthy,
or that pose a security risk.
• Use caution when linking to Wikipedia. Wikipedia doesn’t guarantee the validity of its
information. If no AWS or Amazon owned resource is available, you can link to Wikipedia content
about an established concept, principle, or technology standard. Examples include Confusion
matrix, Classless Inter-Domain Routing, and IEEE 754.
• Don't link to answers provided by generative AI or chatbots. Generative AI models might use
information that's outdated, incomplete, biased, or incorrect. For more information, download
the AWS Responsible Use of Machine Learning guide.
• Don't link to external websites using third-party services (such as tinyurl.com) to create a
shortened link for the URL.
## Consoles
## 245
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 255 -->

AWS Content Design System
Linking best practices
• Prevent link fatigue. Using too many links can be a distraction or become a usability burden. Use
the following principles when deciding whether to include information or link to it:
• Don’t include a link unless it provides important context or value for the customer.
• Use a link if the topic is subject to change, such as AWS service procedures, AWS service pricing
information, or Regional oﬀerings.
• Use a link if the topic is complex and can’t be quickly summarized in your content.
• If the deﬁnition of a term is straightforward or critical for reader comprehension, consider
deﬁning the term in the body of the content instead of linking to it. However, you can also link
to a term in the AWS Glossary.
• In general, don’t repeat a link if you’ve already provided it elsewhere on the same page. For
more information, see General guidelines for links and cross-references.
• Link directly to the relevant heading or section. Include a bookmark (an anchor tag) in the link to
take the reader directly to the target content.
## Lists
The purpose of a list is to itemize data relating to a topic or to present conceptually similar
information in a format that's scannable. Lists shouldn't replace normal text or the structured
presentation of tables.
The following are common list types used in AWS documentation:
• Itemized (bulleted) lists
• Ordered (numbered) lists
• Topic-comment (topcom) lists
• Variable (termdef) lists
## • Procedures
• Automatic (topic) lists
A series of formal paragraphs is commonly used for lists but discouraged going forward. Consider
Variable (termdef) lists instead.
For tagging guidelines and examples for all list types, see Add lists in the Using ZonBook Wiki.
Best practices
## 246
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 256 -->

AWS Content Design System
General list guidelines
The following guidelines apply to all list types:
• Make lists parallel in content and structure. Don't mix single words with phrases, don't start some
phrases with a noun and others with a verb, and don't mix verb forms.
• Avoid admonitions within lists. Use them before or after if possible.
• Present the items in alphabetical order if the order of items is arbitrary.
• Capitalize the ﬁrst letter of the ﬁrst word of each list item.
• Punctuate each list item with a period if a list item has more than one sentence.
• Punctuate list items consistently. If at least one item in a list requires a period, use a period for all
items in that list.
Guidelines for list introductions and titles
The following guidelines apply to list titles and introductory sentences:
• Titles are optional for most lists. If used, the title comes after an introductory sentence.
• Titles are required for automatically generated lists (topic lists).
• Titles are highly recommended for procedures.
• Introductory sentences are required for lists.
• Introductory sentences should be complete sentences.
• Introductory sentences should end with a period if the list has a title.
• Introductory sentences should end with a colon if the list does not have a title.
Itemized (bulleted) lists
Itemized lists are displayed with bullets. Use an itemized list when presenting a series of items that
don’t need to be ordered.
Guidelines for itemized lists
Follow these guidelines for itemized lists:
• Avoid titles for itemized lists.
General list guidelines
## 247
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 257 -->

AWS Content Design System
• Use an introductory sentence before the list.
• Capitalize the ﬁrst word of each item.
• If the list is basic, you don't need end punctuation for the list items.
• If the list has a mixture of phrases and sentences, punctuate each list item.
• If each list item has three pieces of information to convey, consider the topic-comment (topcom)
list style.
Example itemized list
Each error includes the following elements:
• A Code that identiﬁes the type of error
• A Detail that might give additional details about the error
• A Message that describes the error condition
• A Type that identiﬁes whether the error was from a receiver or sender
Ordered (numbered) lists
Use an ordered, or numbered, list when it is important to describe the items in sequence but not
for steps that a reader must complete.
To describe steps that a reader must complete, use a procedure. A procedure is a speciﬁc type of
ordered list with unique considerations, guidelines, and XML tags. The procedure guidelines are
described in a Procedures topic. For information about the XML tags to use in procedures, see Add
procedures.
Guidelines for ordered lists
Follow these guidelines for an ordered list:
• Avoid titles for ordered lists. If you use a title, avoid starting it with "To" because that is the
standard for procedures.
• Introduce the list with a sentence that ends with a colon.
• Capitalize the ﬁrst word of each entry.
• Use numbers or letters. Numbers are preferred; only use letters to avoid confusion. For more
information, see Add lists.
Ordered (numbered) lists
## 248
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 258 -->

AWS Content Design System
Example ordered list
You can attach an identity-based permissions policy to an IAM role to grant cross-account
permissions, as described in the following example:
1. Account A administrator creates an IAM role and attaches a permissions policy to the role. The
policy grants permissions on resources in account A.
2. Account A administrator attaches a trust policy to the role. The policy identiﬁes account B as the
principal who can assume the role.
3. Account B administrator can then delegate permissions to assume the role to any users in
account B. This allows users in account B to create or access resources in account A.
Topic-comment (topcom) lists
Use a topic-comment list when each list item requires three pieces: term, short deﬁnition, and
further description. The phrase, or topic, is brief and is used to orient the reader. The comment is a
short explanation of the topic. For information about how to apply tags for this style, see Add lists.
Guidelines for topic-comment lists
Follow these guidelines for using (and avoiding) a topic-comment list:
• For a short basic list, where each item has two pieces (that is, term and short deﬁnition or
description), use a termdef list instead.
• Don't overuse topic-comment lists to build constructions that a table would handle more
eﬀectively.
• A title is optional. Include a title when you need the list to stand out signiﬁcantly from the ﬂow.
• Capitalize the ﬁrst word following the en dash in a topic-comment list.
• Use an en dash to separate the topic from the comment. Surround the en dash with spaces. For
the correct markup, see Add lists.
• Introduce the list with a sentence.
Example topic-comment list
In amazon-ses-sample.php, replace the following with your own values:
Topic-comment (topcom) lists
## 249
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 259 -->

AWS Content Design System
• path_to_sdk_inclusion – Replace with the path required to include the AWS SDK for PHP in the
program. For more information, see the AWS SDK for PHP documentation.
• sender@example.com – Replace with an email address that you have veriﬁed with Amazon SES.
For more information, see Verifying Email Addresses and Domains.
• recipient@example.com – Replace with the address of the recipient. If your account is still in the
sandbox, you must verify this address before you use it. For more information, see Moving Out of
the Amazon SES Sandbox.
• (Optional) us-west-2 – If you want to use Amazon SES in a Region other than US West (Oregon),
replace this with the Region that you want to use. For a list of Regions in which Amazon SES is
available, see Regions and Amazon SES.
Variable (termdef) lists
Use a variable, or termdef, list when you have a short item that is followed by a deﬁnition or
description. For information about how to apply tags for this style, see Add lists.
Guidelines for variable (termdef) lists
Follow these guidelines for a variable list:
• Use a variable list when you have a list that requires a brief explanation for each item, and each
item has two pieces: term and deﬁnition (or description).
• If you have a short basic list, and each item has three pieces (that is, term, short deﬁnition or
description, and further explanation), consider using a topic-comment list instead.
• Include an introductory sentence.
• A title is optional. Include a title when you need the list to stand out signiﬁcantly from the ﬂow.
• Use a variable list for nesting, such as for nested UI labels. For example, you can create multi-
level lists with a combination of termdef lists and itemized lists, as shown next.
Example variable (termdef) list
The Add Stack page has the following basic options.
Stack name
(Required) A name that is used to identify the stack in the AWS OpsWorks Stacks console. The
name does not need to be unique. AWS OpsWorks Stacks also generates a stack ID, which is a
Variable (termdef) lists
## 250
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 260 -->

AWS Content Design System
GUID that uniquely identiﬁes the stack. For example, with AWS CLI commands such as update-
stack, you use the stack ID to identify the particular stack. After you have created a stack, you
can ﬁnd its ID by choosing Stack in the navigation pane and then choosing Stack Settings. The
ID is labelled OpsWorks ID.
## Region
(Required) The AWS Region where the instances will be launched.
VPC
(Optional) The ID of the VPC that the stack is to be launched into. All instances will be launched
into this VPC, and you cannot change the ID later.
• If your account supports EC2 Classic, you can specify No VPC (the default value) if you don't
want to use a VPC. For more information about EC2 Classic, see Supported Platforms.
• If your account does not support EC2 Classic, you must specify a VPC. The default setting
is Default VPC, which combines the ease of use of EC2 Classic with the beneﬁts of VPC
networking features. If you want to run your stack in a regular VPC, you must create it by
using the VPC console, API, or CLI. For more information about how to create a VPC for an
AWS OpsWorks Stacks stack, see Running a Stack in a VPC. For general information, see
Amazon Virtual Private Cloud.
## Procedures
For procedure guidelines, see Procedures. For information about how to apply tags for the
procedure style, see Add procedures.
Automatic (topic) lists
Use automatic (topic) lists to provide links to child sections, without commentary or explanation.
You can use them in the parent chapter, section, or subsection after the introductory paragraphs.
The default title for the list is "Topics" but the heading can be customized for improved readability.
The default depth of the list is one level, but you can go deeper if the level of detail is helpful to
your reader. For information about creating and customizing these lists, see Add automatic lists.
The following is an example of an automatic (topic) list.
## Topics
• Automatic (topic) lists guidelines
## Procedures
## 251
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 261 -->

AWS Content Design System
• Automatic (topic) list examples
Automatic (topic) lists guidelines
Follow these guidelines for an automatic (topic) list:
• Introduce them with a complete sentence with a period at the end.
• Use the default heading for automatic (topic) lists when possible.
• Customize the heading, if needed, to clarify context for your reader.
• Be aware that the more levels of depth you include in your list, the more vertical space is taken
up by it.
Automatic (topic) list examples
The following topics contain AWS style examples for automatic (topic) lists.
## • Example 1
## • Example 2
• Example 3 (list of links to subsections within a subsection with custom heading text)
• Example 4 (section within a topic)
Formal paragraphs
Use formal paragraphs when you want to oﬀset a paragraph from the text by using a title. Avoid
using a series of formal paragraphs. A termdef list often works well, is more semantically correct
when documenting a series, and works well with multi-level lists. For more information, see
Variable (termdef) lists.
Guidelines for formal paragraphs
Follow these guidelines for formal paragraphs:
• The title of the formal paragraph is bold.
• The title begins with a capital letter.
• The paragraph starts with a capital letter.
• Don't use end punctuation for the title of a formal paragraph.
Formal paragraphs
## 252
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 262 -->

AWS Content Design System
Notes and other special messages
Notes call the reader's attention to information of timely importance or information that you can't
otherwise present suitably in the main text. AWS documentation uses a variety of diﬀerent notes.
Busy pages with multiple notes (or consecutive notes), can be diﬃcult to scan, understand, and
read. The following are best practices for notes and other messages.
• Avoid stacking notes
• Avoid including notes in tables, lists, or procedures
## Topics
## • Tip
## • Note
## • Important
## • Warning
## Tip
A tip presents a shortcut or recommended best practice. The tip itself is not essential information,
even though it might prove useful the next time the reader encounters a similar situation.
AWS style
## Tip
If you launched your instance from an Amazon Linux AMI, the default username is ec2-
user. Otherwise, you might need to specify a diﬀerent username. For example, for Ubuntu,
the default username is ubuntu, and for RHEL5, the default username is root. Otherwise,
check with your AMI provider.
## Note
A note calls attention to information of special interest or importance to the reader. Failure to
read the note will not result in physical harm to the reader, equipment, or data. For example, a
Notes and other special messages
## 253
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 263 -->

AWS Content Design System
note might emphasize that in certain cases restrictions might apply, as for memory requirements,
service quotas, or issues speciﬁc to certain software versions.
AWS style
## Note
Amazon EC2 uses SSH keys, Windows passwords, and security groups to control who has
access to speciﬁc EC2 instances. There's no method in the IAM system to allow or deny
access to a speciﬁc instance.
## Important
An important note provides information that is essential to the completion of a task. An important
note might also remind the user of the consequences of not performing an action—for example,
not logging out.
AWS style
## Important
Remember, if you launched an instance in the free usage tier, there are no charges.
Otherwise, as soon as your instance starts to boot, you're billed for each hour or partial
hour that you keep the instance running. This will happen even if the instance is idle. You
will stop incurring charges for a regular instance as soon as the instance status changes to
shutting down or terminated.
## Warning
In technical documentation, a warning draws special attention to actions that are irreversible and
potentially damaging to equipment or data. Describe what could happen if the warning is ignored.
Always place the warning before the step that it applies to.
AWS style
## Important
## 254
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 264 -->

AWS Content Design System
## Warning
Windows-based systems typically use a diﬀerent end of record character sequence: a
carriage return and line feed together (ASCII value 13 and ASCII value 10). You must
accommodate this diﬀerence using an additional mechanism. For example, a pre-copy
script to modify the input data, to make sure that CopyActivity can properly detect the
end of a record. Otherwise, the CopyActivity will fail repeatedly.
## Numbers
Use the following guidelines for referring to numbers in general, as well as units of measure, date
and time formats, and currency.
## Topics
• Numbers one through nine
• Comma separators
• Numbers in tables
• En dashes
• Numbers in measurements
• Units of measure
• Dates and time
## • Currency
Numbers one through nine
## Do
• Spell out cardinal numbers from one through nine. For example, one NAT instance.
• Use numerals for cardinal numbers 10 and higher.
• Spell out ordinal numbers. For example, ﬁrst and second.
## Exceptions
• In a series that includes numbers 10 or higher, use numerals for all.
## Numbers
## 255
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 265 -->

AWS Content Design System
• On consoles and for conversational services, use numerals for all.
• 3D. For more information, see 3D.
Comma separators
Use a comma separator for numbers of four digits or more—for example, 1,000.
## Exceptions
• For years and baud, use a comma separator only if the number is more than ﬁve digits.
• For street addresses, don't use commas.
Numbers in tables
When a number precedes an item in a table, use lowercase for the item name (unless the name is a
proper noun).
AWS style
• 23 domains
Not AWS style
## • 23 Domains
En dashes
For descriptions that include time ranges, sepearate the numbers with an en dash (–).
Avoid extra words such as between or from n to n.
AWS style
• It can take 5–10 minutes before logs are available.
Not AWS style
• It can take between 5 and 10 minutes before logs are available.
Comma separators
## 256
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 266 -->

AWS Content Design System
• It can take from 5 to 10 minutes before logs are available.
## Exceptions
• On consoles, use hyphens (‐). En dashes render as question marks ("2?25 characters").
Numbers in measurements
Use numerals for all measurement-based references, including time. Include a space between the
number and the abbreviation for the unit of measure.
AWS style
• 100 GB
• 1 TB
• 3 minutes
• 12 subnets (8 public and 4 private)
Not AWS style
• One hundred GB
• 1TB
For more information, see Units of measure.
Units of measure
When using units of measure, spell out the full term on the ﬁrst use, unless the term is familiar
to your audience. Units of measure can be confused with one another. For example, spelling
out megabyte (MB), megabit (Mb), and mebibyte (MiB), while still including the abbreviation in
parentheses, is helpful because these abbreviations use the same letters. On subsequent uses, use
the abbreviation.
For more information, see the section called “Units of measure abbreviations”.
## Topics
• Capitalization in units of measure
Numbers in measurements
## 257
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 267 -->

AWS Content Design System
• Numbers in units of measure
Capitalization in units of measure
As a general rule, secondary units of measure are lowercase in compound abbreviations. For
example, the z in hertz (Hz) is lowercase. The use of k in abbreviations to denote kilo- is lowercase
except in the case of kilobit (Kb), kilobyte (KB), kibibit (Kib), and kibibyte (KiB). Higher-level
abbreviations (such as M for mega and G for giga) are always uppercase. Fractional abbreviations
(m for milli- and n for nano-) are lowercase. For micro, use the Greek lowercase mu (μ, ANSI 181, µ
in XML).
For more information, see the section called “Capitalization”.
Numbers in units of measure
When you use units of measure with a number, include a space between the number and the unit
of measure.
AWS style
• 128 TB
Not AWS style
• 128TB
Dates and time
This topic provides information about date and time content and formatting. The guidelines in this
topic follow the internationally accepted way to represent dates and times. For more information,
see ISO 8601.
## Topics
• Date formatting
• Date ranges
• Time formatting
• Time ranges
Dates and time
## 258
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 268 -->

AWS Content Design System
Date formatting
When your content requires a numeric, lexicographically sortable date:
• Use the <YYYY>-<MM>-<DD> format. For example, write October 1, 2022 as 2022-10-01.
• When referring to a single-digit month or day, include a zero (0). For example, write February 5,
2022 as 2022-02-05.
• When referring to the month and year only, use YYYY-MM. For example, write February 2022 as
2022-02.
• Use hyphens (‐).
• Always include the year to avoid ambiguity, because of the locally used formats of MM/DD and
DD/MM.
When your content requires a human-readable date:
• Use the <month> <day>, <YYYY> format. For example, October 1, 2022.
• Don’t use an ordinal number for the day. For example, use January 1, not January 1st.
• If the context is clear, then you can omit the year on subsequent mention. For example, October
1.
• If you need to mention the month, but not a speciﬁc day, use the <month> <YYYY> format. For
example, October 2022.
AWS style
## • 2022-10-01
## • 2022-10
## • October 1, 2022
## • October 2022
Not AWS style
## • 2022/10/01
## • 1-10-2022
## • 10/01/2022
## • 1/10
Dates and time
## 259
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 269 -->

AWS Content Design System
## • 1 October 2022
• October 1st, 2022
## • October, 2022
Date ranges
To designate a date range, use an en dash (–). Don't use a hyphen (‐) or em dash (—).
AWS style
## • August 8–10
## • August–December
Not AWS style
• August 8 through 10
• August 8 to August 10
## • August 8-10
## • August 8—August 10
Time formatting
AM/PM
Avoid if possible. Use a 24-hour clock where necessary.
12 AM is midnight, and 12 PM is noon.
Daylight saving time
Note capitalization and singular use of “saving.” Don't use Daylight savings time. This is according
to the U.S. DOT Bureau of Transportation Statistics.
Time zone
Two words. Don't hyphenate. Don't use timezone or time-zone.
GMT
Don’t use. Use UTC instead.
Dates and time
## 260
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 270 -->

AWS Content Design System
UTC
UTC is the oﬃcial international abbreviation of Coordinated Universal Time. Use this instead of
GMT when describing times and time zones.
Don't spell out. For more information, see the section called “Don't spell out common acronyms”.
AWS style
• By default, Amazon Linux instances are set to the UTC+0 time zone.
• November 5, 2020 00:00 UTC
• Last saved November 5, 2020 14:27
Not AWS style
• By default, Amazon Linux instances are set to the UTC (Coordinated Universal Time) time zone.
Time ranges
For descriptions that include time ranges, separate the numbers with an en dash. Avoid extra words
such as between or from n to n.
AWS style
• It can take 5–10 minutes before logs are available.
Not AWS style
• It can take between 5 and 10 minutes before logs are available.
• It can take from 5 to 10 minutes before logs are available.
Exception: On consoles, use hyphens. En dashes render as question marks ("2?25 characters").
## Currency
This topic describes how to write about currency.
## Topics
• Referring to currency
## Currency
## 261
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 271 -->

AWS Content Design System
• Currency names
• Referring to speciﬁc monetary amounts
• Currency ranges
• Billing and pricing
Referring to currency
AWS services use the US dollar as the default currency, but customers can choose from multiple
currency options. When referring to a speciﬁc currency, always use the internationally recognized
name of the currency. For a list of currency names, see Currency names.
When using a currency name, capitalize the country or region. Don't capitalize the currency unit.
AWS style
• British pound
Not AWS style
## • British Pound
When abbreviating currency names, use the oﬃcial ISO code for the currency. You can also add
the ISO code in parenthesis for additional clarity, or use it where space is limited. Always use the
currency name with the ISO code for the country or region, with the exception of euros.
AWS style
• You can make payments in US dollars (USD).
• You can pay your bill in euros.
Not AWS style
• You can make payments in dollars.
• You can pay your bill in EU euros.
For more information about referring to speciﬁc monetary amounts, see Referring to speciﬁc
monetary amounts.
## Currency
## 262
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 272 -->

AWS Content Design System
Currency names
The following table provides the oﬃcial names, ISO codes, and symbols for multiple major world
currencies. Currencies are ordered alphabetically based on their ISO code.
Currency name
ISO code
## Symbol
Australian dollar
AUD
## $
Brazilian real
BRL
## $
Canadian dollar
CAD
## $
Swiss franc
CHF
## ₣
Chinese yuan
CNY
## ¥
Danish krone
DKK
kr
## Euro
EUR
## €
British pound
GBP
## £
Hong Kong dollar
HKD
## $
Indonesian rupiah
IDR
## Rp
Indian rupee
INR
## ₹
South Korean won
KRW
## ₩
Japanese yen
JPY
## ¥
Norwegian krone
NOK
kr
New Zealand dollar
NZD
## $
Swedish krona
SEK
kr
Singapore dollar
SGD
## $
US dollar
USD
## $
## Currency
## 263
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 273 -->

AWS Content Design System
Currency name
ISO code
## Symbol
South African rand
ZAR
## R
Referring to speciﬁc monetary amounts
Use the correct symbol when giving a speciﬁc amount of currency. Space permitting, we
recommend that you include the ISO currency code before the amount, as multiple countries or
regions might use the same currency symbol. Don't spell out monetary amounts.
AWS style
• Rates begin at USD $5.00 per month.
• A fee of $1.50 will be applied to each transaction.
Not AWS style
• Rates begin at 5.00 USD per month.
• A fee of 1.50 will be applied to each transaction.
• The cost of this service is four United States dollars.
When referring to a negative amount of currency, the minus sign (-) must be placed before the
currency symbol or the currency code.
AWS style
• Your account shows a current balance of -$5.00.
Not AWS style
• Your account shows a current balance of $-5.00.
When referring to speciﬁc amounts of money, use the currency code followed by the amount, with
no space.
## Currency
## 264
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 274 -->

AWS Content Design System
Currency ranges
To designate a currency range, use an en dash (–). Don't use a hyphen (‐) or an em dash (—). Write
the currency symbol before the ﬁrst number in the range. Spell out hundred, thousand, million,
billion, and trillion on ﬁrst mention. It's OK to use K, M, B, and T without a space on subsequent
mention.
AWS style
• $50–100 (with endash)
## • ¥50–100
• €50–100 million (on ﬁrst mention)
• €50–100M (on subsequent mention)
Not AWS style
• $50-100 (with hyphen)
## • ¥50–¥100
• €50–100M (on ﬁrst mention)
Billing and pricing
Make sure to clearly explain how your service or feature is billed, and always link to the pricing
information. It's important that customers understand how and why a speciﬁc resource is billed.
AWS style
• For billing purposes, AWS treats all of the accounts in the organization as if they were one
account. Some services, such as AWS Data Transfer and Amazon S3, have volume pricing tiers
across certain usage dimensions that give you lower prices the more you use the service. With
consolidated billing, AWS combines the usage from all accounts to determine which volume
pricing tiers to apply. This gives you a lower overall price whenever possible. AWS then allocates
each member account a portion of the overall volume discount based on the account's usage.
To avoid misleading or confusing customers, we recommend that you provide examples without
monetary amounts. If you must do so, make sure that you clearly frame the example as being
illustrative or hypothetical in nature.
## Currency
## 265
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 275 -->

AWS Content Design System
AWS style
• For example, if AWS charges $0.17 per GB for the ﬁrst 10 TB of data transferred and $0.13 for
the next 40 TB. This translates into $174.08 per TB (.17*1024) for the ﬁrst 10 TB, and $133.12
per TB ( .13*1024) for the next 40 TB.
Parallel information
## Topics
• Parallel steps in procedures
• Handling task ﬂows for diﬀerent languages
• Filtering content in documentation
In documentation, there are three types of parallel information:
• Steps within a procedure
• Tasks for diﬀerent programming languages
• Processes for diﬀerent user interfaces
Parallel steps in procedures
Within a procedure, there might be multiple options for how a user completes the task.
Present options with a simple table in your procedure that uses the left column to identify the
decision point or option and the right column to give the appropriate instruction. The following
tables show two example headings.
To...
Do this...
List all available report results.
Choose the Search button.
Search for a report name.
In the Report Name text box, enter part of
your report’s name, and then choose the
Search button.
Parallel information
## 266
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 276 -->

AWS Content Design System
If you're using...
Enter the following at your command
prompt...
## Unix
ls
## Windows
dir
A procedure might also present a set of parallel substeps. In the following example, the user
chooses either to retry or fail a transaction.
To retry a transaction
To fail a transaction
a. Change transaction status to Pending.
b. Call RetryTransaction .
c. Poll results using GetResults .
d. Discard results using DiscardResults .
a. Change transaction status to Failure.
b. Change download status to Download
Canceled.
c. Email the customer a description of the
failure.
d. Discard results using DiscardResults .
Handling task ﬂows for diﬀerent languages
When you are writing for application developers, you must guide them to the SDKs and API.
In addition to references to the SDK or API reference materials, you often have programming
language-speciﬁc descriptions and samples. Because AWS provides multiple language SDKs, these
sections are often not only parallel in content, but also quite lengthy. To help the reader navigate
to the right content quickly, you should accept some redundancy and provide independent, parallel
sections for each language.
For an example of this kind of chunking, see Getting Objects.
In the following example screenshot, the section on getting objects has a brief introduction of
common information, followed by four independent descriptions and examples for Java, .NET, PHP,
and REST.
Handling task ﬂows for diﬀerent languages
## 267
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 277 -->

AWS Content Design System
The following process covers the essentials of constructing parallel sections for multiple languages.
Process for handling multiple programing language sections
A. Start with a general introduction to the topic. It should cover overview and important generic
information about the feature or functionality. Also provide links from here to the language-
speciﬁc sections.
B. Create an independent section for each programming language. Put all instructions necessary to
succeed in each language section:
• Present essential information when it's needed (just-in-time).
• It's likely you will have some redundant content across languages. You can control single
sourcing through includes and entities.
• You might need subsections within each language, but keep all feature or functional
information together.
C. Provide links out to the appropriate SDKs and API reference material from the overview and top
of each programming language section.
D. Don't discuss programming languages that we don't support. Particularly avoid statements such
as "Support for Ruby developers will be provided in a future release."
For information about forward-looking statements, see Messaging Dos and Don’ts on the AWS
Legal Pathﬁnder website.
Handling task ﬂows for diﬀerent languages
## 268
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 278 -->

AWS Content Design System
Filtering content in documentation
With HTML, you can organize text in ways that hides redundancy and reduces TOC depth. The
following two methods for ﬁltering or collapsing sections on a single page are most common:
## • Tabs
## • Accordions
These features are ignored in PDF output.
Follow these style guidelines when using ﬁltering techniques in your topics. For information about
XML tags for ﬁltering text, see the Elements Wiki.
Best practices
• Notify your editor if you're planning to use collapsible content.
• Don't use page-level ﬁlters or minimized content.
• Keep ﬁltered content to a minimum. It can cause issues for discoverability, so use it with care.
Filtering content is entirely optional.
• Don't use ﬁltered content to hide detail or complexity.
• Use clear headlines and topic titles, because these might be the only searchable parts of your
content. Searching on a browser page (Ctrl+F) can't ﬁnd ﬁltered or collapsed content or content
in an inactive tab.
• Avoid duplicating content. For example, instead of repeating the same introductory sentence or
paragraph, move the sentence or paragraph above the ﬁltered content.
• Filter content consistently within your guide so that users know what to expect.
• Avoid using multiple ﬁltering methods in the same guide.
• Make sure the most common scenario described in your content is the default (the ﬁrst section or
visible section).
## Tabs
Tabs are used to organize parallel information. The following are best practices for tabs:
• Use tabs to organize parallel code examples and syntax for diﬀerent programming language. Use
one tab for each programming language.
Filtering content in documentation
## 269
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 279 -->

AWS Content Design System
• Tabs are acceptable for parallel information for diﬀerent operating systems. Use one tab for each
operating system. You can also consider using the section called “Accordions” or refactoring the
content into multiple sections.
• Use 2–6 tabs if possible. If your label names are short, such as programming language names,
then more than 6 is acceptable. Check your rendered content to verify that it looks okay.
• Use brief, parallel label names, with a maximum character limit of 15.
• If you have more than 6 tabs or the tab labels are longer than 15 characters, consider using the
section called “Accordions” or refactoring the content into multiple topics.
• Use the same tab names throughout a guide when possible so that the customer's choice persists
within that guide.
• Keep introductory text to a minimum.
For more examples, see Tabbed Content Box in the AWS KitchenSink Test Guide.
XML
<mediaobject>
<imageobject>
<imagedata fileref="images/copy-code.png" format="PNG" scale="100"/>
</imageobject>
<textobject>
<phrase>Copy Code button</phrase>
</textobject>
</mediaobject>
JSON
## {
mediaobject: {
imageobject: {
imagedata: {
fileref: "image/copy-code.png",
format: "PNG",
scale: 100
## }
## },
textobject: {
phrase: {
value: "Copy Code button"
Filtering content in documentation
## 270
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 280 -->

AWS Content Design System
## }
## }
## }
## }
## Perl
my $mediaobject = {
'imageobject' => {
'imagedata' => {
'fileref' => "image/copy-code.png",
'format' => 'PNG',
'scale' => 100
## }
## },
'textobject' => {
'phrase' => {
'value' => "Copy Code button"
## }
## }
## };
## Accordions
Use accordions (or collapsible sections) to show multiple ways of doing the same thing, or to group
a list of short topics when the reader is likely to need only one of the topics.
By default, accordions expand only one section when the page is loaded. If the reader might miss
important hidden text, consider using a series of single-section accordions. This has the same
visual appearance as regular accordions, but allows all sections to be expanded when the page
loads. Alternatively, if the sections are long or complex, you can override the default to collapse all
sections upon page load. For more examples, see Collapsible Sections in the AWS KitchenSink Test
Guide.
## Examples
• Procedures that have a console, API, and CLI approaches.
• Troubleshooting topics
Filtering content in documentation
## 271
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 281 -->

AWS Content Design System
To turn oﬀ automated backups immediately (console)
1.
Sign in to the AWS Management Console and open the Amazon RDS console at https://
console.aws.amazon.com/rds/.
2.
In the navigation pane, choose Databases, and then choose the DB instance that you want to
modify.
3.
Choose Modify. The Modify DB Instance page appears.
4.
For Backup Retention Period, choose 0 days.
5.
Choose Continue.
6.
Choose Apply Immediately.
7.
On the conﬁrmation page, choose Modify DB Instance to save your changes and turn oﬀ
automated backups.
To turn oﬀ automated backups immediately (AWS CLI)
Use the modify-db-instance command and set the backup retention period to 0 with --apply-
immediately.
## Example
The following example immediately turns oﬀ automatic backups.
The following AWS CLI example is formatted for Unix, Linux, and macOS.
aws rds modify-db-instance \
--db-instance-identifier mydbinstance \
--backup-retention-period 0 \
--apply-immediately
The following AWS CLI example is formatted for Windows.
aws rds modify-db-instance ^
--db-instance-identifier mydbinstance ^
--backup-retention-period 0 ^
--apply-immediately
To know when the modiﬁcation is in eﬀect, call describe-db-instances for the DB instance
until the value for backup retention period is 0 and mydbinstance status is available.
Filtering content in documentation
## 272
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 282 -->

AWS Content Design System
aws rds describe-db-instances --db-instance-identifier mydbinstance
To turn oﬀ automated backups immediately (RDS API)
Call the ModifyDBInstance action with the following parameters:
• DBInstanceIdentifier = mydbinstance
• BackupRetentionPeriod = 0
## Example
https://rds.amazonaws.com/
?Action=ModifyDBInstance
&DBInstanceIdentifier=mydbinstance
&BackupRetentionPeriod=0
&SignatureVersion=2
&SignatureMethod=HmacSHA256
## &Timestamp=2009-10-14T17%3A48%3A21.746Z
&AWSAccessKeyId=<AWS Access Key ID>
## &Signature=<Signature>
Plural and singular nouns
This topic explains how to properly express singular and plural forms.
Best practices
• Don’t use (s) or (es) at the end of a noun to signify both the singular and plural form of the noun.
Using (s) and (es) can cause problems:
• It complicates localization.
• It can be ambiguous.
• It’s awkward and ugly.
• Consider that, typically, the plural form of a noun can also be read to imply the singular. For
example, if a procedure title is “To terminate instances...,” the customer understands that the
procedure can be used to terminate multiple instances or a single instance.
• If necessary, add words to clarify whether you mean one thing or multiple things. You can also
explicitly use both the singular and plural form of the noun where it makes sense.
Plural and singular nouns
## 273
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 283 -->

AWS Content Design System
AWS style
• Select and terminate the instances in the placement group.
• To terminate one or more instances,...
• Enter the IP address or addresses.
Not AWS style
• Enter the IP address(es).
• Select and terminate the instance(s) in the placement group.
## Prepositions
This topic describes the guidelines for using the prepositions in and on.
In, on
• Use in Windows or in Linux in reference to components of the operating system (OS) or work in
the OS. Use on Windows in reference to Windows applications.
AWS style
• Use Printers & scanners in Windows to install a new printer.
• In Windows, run the setup command.
• Select an application that runs on Windows.
• You run applications and instances in the cloud, but extend services to the cloud.
• For a hardware security module (HSM), keys are stored in the HSM, but users are on the HSM. You
log in to the HSM.
• Use on for AWS, cards, consoles, dashboards, menus, pages, tabs, and toolbars.
AWS style
• computing on AWS
• on the card
• on the AWS Management Console
• on the console
## Prepositions
## 274
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 284 -->

AWS Content Design System
• on the dashboard
• on the Edit menu
• on the sign-up page
• on the Home tab
• on the toolbar
• Use in for dialog boxes, form boxes, groups, panes, sections, and views.
AWS style
• in the Create Report dialog box
• in the Data box
• in the Forms group
• in the navigation pane
• in the User Policies section
• in the Outline view
## Procedures
A procedure is a series of numbered steps that a user follows to complete a speciﬁc task. Users
should be able to scan for and recognize procedures easily. Make procedures recognizable by using
the following:
• Predictable content parts
• Parallel language constructions
• Consistent formatting
You typically use procedures for console steps, but you can also use them for AWS CLI or SDK steps.
## Topics
• Parts of a procedure section
• Procedure phrasing
• Example procedure from Amazon EC2
## Procedures
## 275
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 285 -->

AWS Content Design System
Parts of a procedure section
These are the basic parts of a procedure section:
• Section title
• Procedure introduction
• Procedure title
## • Steps
## • (Optional) Screenshots
## • (Optional) Notes
A procedure section can include one or more procedures.
The following sections give speciﬁcs on each procedure part.
Section title
Title the procedure section consistently as follows:
• In general, use a gerund phrase (such as creating, deﬁning, restricting). For tutorials and Getting
started topics, you can use imperatives, especially when the section title includes a number (such
as "Step 1: Create a repository").
• Use sentence case.
• Use a singular object, unless the most common application is to perform the procedure on
multiple objects at once. For example, use “Creating a domain,” not “Creating domains.”
• Use terms both new and experienced users will know. ("Restricting access to a resource" is better
than "Deﬁning a policy.")
• Use parentheses to diﬀerentiate between console, AWS CLI, and SDK procedures, as needed.
Example of parenthetical diﬀerentiation
Conﬁguring a snapshot (console)
Conﬁguring a snapshot (AWS CLI)
Conﬁguring a snapshot (AWS SDKs)
Parts of a procedure section
## 276
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 286 -->

AWS Content Design System
Procedure introduction
The procedure introduction brieﬂy explains the following:
• What the procedure will accomplish
• When or why the reader should perform the procedure
• What the reader must have done ﬁrst
• Where to ﬁnd more information
Ideally, the procedure introduction also includes information that you otherwise have to insert in
the text of a step to explain background, choices, and consequences. If you need more than a short
paragraph to convey this information, consider adding it at the topic level so you can keep the
procedure itself straightforward.
Procedure title
Title procedures consistently as follows:
• Use an inﬁnitive phrase ("To restrict access to a resource").
• Use sentence case.
• Don't use end punctuation.
• Avoid adding text between the procedure title and the ﬁrst step of the procedure.
• To diﬀerentiate between diﬀerent ways of performing the same procedure, such as performing
steps in the console, AWS CLI, and SDK, use parentheses at the end of the procedure title. It
is possible to diﬀerentiate between ways of performing a procedure by using tabs or by using
accordions to create collapsible steps. However, these formats are not recommended because
they cause issues for SEO and localization.
Example of parenthetical diﬀerentiation
To conﬁgure a snapshot (console)
To conﬁgure a snapshot (AWS CLI)
To conﬁgure a snapshot (AWS SDKs)
Parts of a procedure section
## 277
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 287 -->

AWS Content Design System
## Steps
Streamline the steps of the procedure as much as possible. Follow these guidelines to keep them
lean:
• Include only one main action per step.
• Use an active voice.
• Use an imperative verb where possible. For example, "Choose Create."
• First step: Locate the reader in the service-speciﬁc console or speciﬁc area in the UI. For example,
"Sign in to the AWS Management Console and open the Amazon RDS console at https://
console.aws.amazon.com/rds/."
• Subsequent steps: Start with where to ﬁnd the option that you want the reader to use, or what
action to take. "For Actions, choose Create."
• Begin optional steps with "(Optional)" with no other punctuation.
Avoid having procedures more than seven steps long. Where possible, break longer procedures into
multiple ones.
When a procedure includes or references other procedures, consider the following:
• In general, create a top-level procedure that cross-references other procedures rather than
replicating those procedures within your topic. This avoids inconsistencies and reduces
maintenance.
• For Tutorials, Getting started tutorials, and other content for a beginner audience, replicate short
procedures when necessary. You can also include them as prerequisites to the procedure so that
users don’t have to switch between document sets to complete the procedure.
• In general, avoid creating entities for procedures that are shared across multiple services as this
creates issues for localization.
## (Optional) Screenshots
Optionally, you can add screenshots, as follows:
• Placement – Place screenshots or examples related to a step after the descriptive text. No text
related to a step should follow the screenshot.
• Usage – Use screenshots to draw a user’s attention to the following:
Parts of a procedure section
## 278
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 288 -->

AWS Content Design System
• Speciﬁc or multiple items on a console page.
• UI elements that are hard to ﬁnd on the console page.
Use screenshots sparingly, because they can be hard to maintain and localize. For details about
how to use and format screenshots most eﬀectively, see Create, modify, and add graphics and
screenshots.
## (Optional) Notes
Avoid using notes in procedures if possible. Instead, place related information that's not part of a
step either in the overview or in supplemental paragraphs after the last procedure step.
Avoid stacking notes.
Procedure phrasing
The following section outlines an approach designed to support accessibility and device agnosticity
for procedures in AWS content. As an added beneﬁt, this approach clariﬁes procedure language.
Replace pointer-speciﬁc language with device-agnostic language to accommodate readers with
disabilities and users of various input methods and devices, including the pointer, keyboard, and
touch screens.
For example, instead of the term click, which is pointer-speciﬁc, use choose, which is more generic
and device-agnostic. However, when the generic language makes it diﬃcult to understand the
instructions (for example, in the case of opening a context menu), include pointer-speciﬁc hints.
If the instructions vary signiﬁcantly among input methods, we recommend creating separate
procedures. Use your judgment. If you have a question, ask your editor. If you're an editor, ask the
editors alias, aws-editors@.
• Use choose to describe moving to a UI component such as a tab or pane or taking action on a
button or menu.
• Use select to describe picking a user-speciﬁc resource or enabling one of several options.
Contrast with clear to turn oﬀ previously selected options.
• Use press to describe single key or key combination entries that users would perform on a
keyboard.
• Use enter to describe information that users add using a keyboard.
• Do not use hit or strike.
Procedure phrasing
## 279
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 289 -->

AWS Content Design System
AWS style
• Press Enter.
• Press Ctrl+Alt+Del.
• Run the ec2-purchase-reserved-instances-offering command.
• Enter an alternate CNAME into the Alternate Domain Names (CNAMEs) box.
Use bold formatting for console UI text labels, including page names, left navigation pane, option
labels, and any UI text on the console. Also, use bold for the name of a single key or keyboard
combination. Use a monospace font for literal text that the user enters. For more information
about terms for the parts of the console, see Console description. For ZonBook formatting details,
see Typographic conventions (text formatting).
UI element
## Language
## Example
## Menu
On the menu
menu, choose
command.
On the Edit menu, choose Copy.
Cascading menu
[For AWS] On
the navigatio
n bar, choose
menu, submenu,
…,   command.
[For conventio
nal Windows
UIs] On the
menu bar,
choose menu,
submenu, …,
command.
On the navigation bar, choose AWS, Create a Resource
Group.
Context menu
Open the
context (right-
click) menu
for item, and
Open the context (right-click) menu for an AMI, and
then choose Launch  Instance.
Procedure phrasing
## 280
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 290 -->

AWS Content Design System
UI element
## Language
## Example
then choose
command.
## [Cascadin
g] Open the
context (right-
click) menu
for item, and
then  choose
submenu, ...,
command.
Open the context (right-click) menu for the instance,
and then choose Networking, Manage  Private IP
Addresses.
## Command
button
## Choose
command.
Choose Next.
Option button
Choose option.
For label, choose
option.
For Type of key to generate, choose SSH-2 RSA.
## Checkbox
Select label.
Clear label.
To grant read access to anonymous requests, select
Make  everything public.
List box
For label, choose
item.
For Backup Retention Period, choose 0.
Text box
For label, enter
text.
[Combo box] For
label, specify
xyz.
For Program/script, enter   Powershell.exe .
For Source, specify the table name.
Toggle switch
Turn on text.
Turn oﬀ text.
Turn on Expiration date, and then  choose Conﬁrm.
Procedure phrasing
## 281
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 291 -->

AWS Content Design System
UI element
## Language
## Example
Other controls
Specify the type
of control only
if it’s helpful
or unavoidab
le, and use the
verb   choose.
On the Conﬁgure Security Group page, choose an
existing security group, and then choose Next.
Double-clicking
Replace with
menu instructi
ons, or use a
generic term
such as "open."
If double-cl
icking is the
most familiar
method, include
it in parenthes
es.
In general, use
your judgment
depending on
the context and
your audience.
In AWS Explorer, open Amazon VPC, VPCs. On the VPCs
tab, choose Create  VPC.
To display the EC2 Instances view, open the context
(right-click) menu for the   Instances node, and then
choose   View. (Or double-click the  node.)
## Displaying
tooltips
Choose item.
In the Your repositories area, choose the target  repo
sitory name to display the GitHub user or organization.
Selecting items
Select the item.
Select the row of the parameter group that you want to
delete.
Example procedure from Amazon EC2
Following is an example of procedure phrasing usage from Amazon EC2.
Example procedure from Amazon EC2
## 282
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 292 -->

AWS Content Design System
To create an AMI from a snapshot (console)
1.
Open the Amazon EC2 console.
2.
In the navigation pane, under Elastic Block Store, choose Snapshots.
3.
Select the row of the snapshot that you want to use.
4.
For Actions, choose Create Image.
5.
In the Create Image from EBS Snapshot dialog box, do the following:
a.
For Architecture, choose i386 for 32-bit or x86_64 for 64-bit.
b.
For Kernel ID, choose the AKI.
c.
Choose Create.
## Punctuation
Use the punctuation mark guidelines in this topic to maintain consistency and clarity for readers
across AWS content.
## Topics
## • Ampersand
## • Apostrophe
## • Backslash
## • Colon
## • Comma
## • Dash
## • Ellipsis
• Em dash
• En dash
• Exclamation point
• Forward slash
## • Hyphen
## • Parentheses
## Punctuation
## 283
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 293 -->

AWS Content Design System
## • Period
• Question mark
• Quotation marks
## • Semicolon
ampersand (&)
The ampersand (&) is a symbol that represents the word "and".
## Do
• In body and UI text, use exclusively when quoting a reference or resource that requires the
symbol. For example: AT&T.
Don't
• Don't use to shorten any phrase that has the word and in it.
apostrophe (')
Indicates the possessive case of singular nouns.
## Do
• For plural forms of nouns that end in "s", form the possessive case by adding only an apostrophe.
• Use the straight apostrophe (').
Don't
• Don't use the curly apostrophe (’).
AWS style
• user's instances
• tools' BIN directory
ampersand (&)
## 284
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 294 -->

AWS Content Design System
backslash (\)
The backslash (\) is used as a path separator in Windows and DOS systems and as an escape
character in programming languages.
## Do
• In Windows and DOS, use to separate components of a path (for example, C:\Windows
\assembly).
• Also use as an escape character in some programming languages. See also forward slash.
colon (:)
The colon (:) is used to introduce lists, explanations, or complete sentences that follow from the
preceding clause.
## Do
• When a colon introduces a list of words, a phrase, or other sentence fragment, lowercase the ﬁrst
word following the colon unless it's a proper name.
• When a colon introduces one or more complete sentences, capitalize the ﬁrst word following it.
comma (,)
The comma (,) is used to separate elements in a sentence, including clauses, phrases, and items in a
series.
## Do
• Use commas to separate independent clauses separated by coordinating conjunctions (but, or,
yet, for, and, nor, so).
• Use commas to separate introductory clauses, phrases, and words that precede the main clause.
• Use commas to separate words, clauses, and phrases listed in a series. Also known as the Oxford
comma.
AWS style
backslash (\)
## 285
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 295 -->

AWS Content Design System
• Each AMI can have only a single product code associated with it, but you can associate a single
product code with more than one AMI.
• For server-side encryption, set the ServerSideEncryptionMethod property by calling the
WithServerSideEncryptionMethod method.
• The sample uses DeleteVersionRequest to provide a bucket name, an object key, and a version ID.
dash
A dash is a horizontal line used for various purposes in writing, with diﬀerent types serving
diﬀerent functions.
See em dash, en dash, or hyphen.
ellipsis (...)
An ellipsis (...) is a series of three dots used to indicate omitted text or a trailing oﬀ of thought.
Don't use in service documentation.
em dash (—)
An em dash is the width of an uppercase M.
## Do
• Use an em dash to set oﬀ parenthetical phrases within a sentence or set oﬀ phrases or clauses at
the end of a sentence for restatement or emphasis.
Don't
• Don't include spacing on either side.
AWS style
• A download distribution gets ﬁles from locations—known as origins—that you specify.
• If an operation speciﬁes the same document version that already exists in the index, the result is
undeﬁned—there's no guarantee which one takes precedence.
dash
## 286
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 296 -->

AWS Content Design System
en dash (–)
An en dash is the width of an uppercase N.
## Do
• Use an en dash to indicate ranges in values and dates, separate a bullet heading from the
following text in a list, or separate an open compound adjective (two compounds, only one of
which is hyphenated) from the word that it modiﬁes.
Don't
• In ranges, don't include spacing on either side.
AWS style
## • August 13–15
• Introduction – An introduction to AWS IAM and users.
• Amazon EBS–optimized
Amazon EBS–optimized is an exception to the guidance in Service names and Hyphenation.
exclamation point (!)
An exclamation point (!) is used to express strong emotion, emphasis, or surprise.
Don't use.
In conversational interfaces, OK to use in the Greeting element. For more information, see
Conversational interfaces (AI, LLMs, chatbots, and more).
forward slash (/)
The forward slash (/) is used in URLs, ﬁle paths, fractions, and some abbreviations.
## Do
• Refer to as a forward slash in public content.
• Use in URLs, ﬁle names (UNIX), code, fractions, and approved technical abbreviations such as I/O
or SSL/TLS certiﬁcates.
en dash (–)
## 287
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 297 -->

AWS Content Design System
Don't
• Don't use slash or virgule.
• Don't use spaces on either side of a forward slash (unless spaces are necessary in code).
• Don't use as a separator to indicate options and alternatives. This guideline applies to both the
technical documentation and the console.
See also backslash.
AWS style
## • I/O
• SSL/TLS certiﬁcates
• AI/ML
• CI/CD
• myawsbucket/production/acme/index.html
• Add or edit tags
Not AWS style
• and/or
• pass/fail
• his/her
• Add/edit tags
hyphen (‐)
The hyphen (-) is used to join words or parts of words, particularly in compound adjectives and
compound nouns.
## Do
• Check the Usage dictionary for AWS usage of industry and technology terms and follow the
guidance in this topic. Not all possible terms are in the Usage dictionary. If no AWS speciﬁc usage
exists, check the Microsoft Writing Style Guide for technical terms, and the Merriam-Webster
dictionary for other usage.
hyphen (‐)
## 288
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 298 -->

AWS Content Design System
• Hyphenate two or more words in the following circumstances:
• Two or more words form compound adjectives that precede a noun.
• Two words precede a noun and the second word ends in -ed or -ing.
• One or two words preceding a noun is a number or a single letter, including compound
fractions.
• Two words where part of the adjective is separated from the rest by a hyphen. This is called a
suspended compound modiﬁer. Its purpose is to reduce repetition while maintaining meaning
when space is limited.
Don't
• Don't use a hyphen in place of an en dash.
• Don't use double-hyphens in place of an em dash.
• Don't hyphenate terms that contain AWS, AWS services or oﬀerings, or any AWS trademark.
• Don't modify service names by using hyphens or en dashes, unless the exception is documented
in the Usage dictionary. We don't want to create any "new" terms with service names because
that is a legal risk for brand and trademark.
## • Exceptions:
• Amazon EBS–backed AMI
• Amazon EBS–optimized instance types
• Amazon S3–backed AMI
AWS style
• AWS managed key
• AWS managed policy
• high-quality inventory
• easy-to-ﬁnd locations
• up-to-date calendar
• in-market shoppers
• on-site meeting
• dual-stack endpoint
• closed-door meeting
hyphen (‐)
## 289
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 299 -->

AWS Content Design System
• long-lasting eﬀect
• service-linked role
• ﬁrst-party data
• third-party sites
• Y-axis coordinates
• one-quarter full
• 30-day period
• High- and low-priority queues
• Cost- and time-eﬃcient solution
• Single- and multi-threaded performance tests
Not AWS style
• AWS-managed key
• AWS-managed policy
• high quality inventory
• easy to ﬁnd locations
• up to date calendar
• in market shoppers
• onsite meeting
• dual stack endpoint
• closed door meeting
• long lasting eﬀect
• service linked role
• ﬁrst party data
• third party sites
• Y axis coordinates
• one quarter full
• 30 day period
• High and low-priority queues
• Cost and time eﬃcient solution
hyphen (‐)
## 290
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 300 -->

AWS Content Design System
• Single and multithreaded solution
For more information about when to use a hyphen, see .
parentheses ( )
Parentheses ( ) are curved brackets used to enclose supplementary or explanatory information
within a sentence.
## Do
• Use to add tangentially related information (such as an example or commentary) to a sentence.
You can set oﬀ information that is more closely related to the topic of the sentence with commas
or em dashes.
• If the parentheses are within a sentence, place all punctuation outside the parentheses. If
the parentheses stand alone outside any other sentence, all punctuation belongs inside the
parentheses.
period (.)
The period (.) is used to mark the end of a declarative sentence or statement.
## Do
• Use to indicate the end of a sentence.
• Add one space after the period.
question mark (?)
The question mark (?) is used at the end of a sentence to indicate a direct question.
Use sparingly as rhetorical devices.
quotation marks (' ' and " ")
Quotation marks (' ' and " ") are used to enclose direct quotations, dialogue, or words being
referenced as words.
## Do
parentheses ( )
## 291
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 301 -->

AWS Content Design System
• Use quotation marks for actually quoted words or phrases from other text sources.
• Place periods and commas inside quotation marks, but place question and exclamation marks
outside the quotation marks—unless they are a part of the quotation. The exception is when it
would be technically inaccurate or confusing to the customer to include punctuation inside the
quotation marks.
• Use straight single quotation marks (' ') and double quotation marks (" ").
• Refer to as quotation marks in public content.
Don't
• Don't use quotation marks to call out special or unfamiliar words or phrases. (Use italics instead.)
• Don't use curly quotation marks (‘ ’, “ ”).
• Don't refer to as quotes or double quotes. OK to refer to single quotation marks (' ') and double
quotation marks (" ") when the distinction is important.
• Don't use quotation marks to imply the ironic use of a word. Have the conﬁdence to use the word
in earnest, or use something else.
AWS style
• Enclose each value in quotation marks (" ").
• Use single quotation marks (' ') or double quotation marks (" ").
Not AWS style
• Attribute values must be quoted with a single or double quote.
• If data does not contain values enclosed in double quotes (")...
• AWS Elastic Beanstalk "knows" the infrastructure needs of your application, and it deploys the
right resources automatically.
semicolon (;)
The semicolon (;) is used to connect closely related independent clauses or to separate items in
complex lists.
Don't
semicolon (;)
## 292
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 302 -->

AWS Content Design System
• Don't use semicolons (except in code examples). Instead, break up the sentence into multiple
sentences or use a table or list. For more information, see Breaking up sentences and paragraphs
in Writing Basics.
AWS style
• Supply at least one parameter name, value, and apply method. Subsequent arguments are
optional.
• Test your agent in the console. If necessary, modify the agent's conﬁguration.
• Tables and databases contain metadata. However, they don't contain data from a data store.
• This option ignores all default values. For example:
• null – Objects and nullable types
• 0 – Integers, decimals, and ﬂoating point numbers
• false – Booleans
Not AWS style
• Supply at least one parameter name, value, and apply method; subsequent arguments are
optional.
• Test your agent in the console; modify its conﬁguration if necessary.
• Tables and databases contain metadata; they don't contain data from a data store.
• This option ignores all default values (for example, null for objects and nullable types; 0 for
integers, decimals, and ﬂoating point numbers; and false for Booleans).
## Hyphenation
In general, check the Usage dictionary for AWS usage of industry and technology terms and follow
the guidance in this topic. Not all possible terms are in the Usage dictionary. If no AWS speciﬁc
usage exists, check the Microsoft Writing Style Guide for technical terms, and the Merriam-Webster
dictionary for other usage.
Don't hyphenate terms that contain AWS:
• AWS, AWS services or oﬀerings, or any AWS trademark.

## Hyphenation
## 293
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 303 -->

AWS Content Design System
AWS style
• AWS managed key
• AWS managed policy
Not AWS style
• AWS-managed key
• AWS-managed policy

Hyphenate two or more words in the following circumstances:
• Two or more words form compound adjectives that precede a noun.

AWS style
• high-quality inventory
• easy-to-ﬁnd locations
• up-to-date calendar
• in-market shoppers
• on-site meeting
• dual-stack endpoint
Not AWS style
• high quality inventory
• easy to ﬁnd locations
• up to date calendar
• in market shoppers
• onsite meeting
• dual stack endpoint

• Two words precede a noun and the second word ends in -ed or -ing.
## Hyphenation
## 294
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 304 -->

AWS Content Design System

AWS style
• closed-door meeting
• long-lasting eﬀect
• service-linked role
Not AWS style
• closed door meeting
• long lasting eﬀect
• service linked role

• One or two words preceding a noun is a number or a single letter, including compound fractions.

AWS style
• ﬁrst-party data
• third-party sites
• Y-axis coordinates
• one-quarter full
• 30-day period
Not AWS style
• ﬁrst party data
• third party sites
• Y axis coordinates
• one quarter full
• 30 day period

• Two words where part of the adjective is separated from the rest by a hyphen. This is called a
suspended compound modiﬁer. Its purpose is to reduce repetition while maintaining meaning
when space is limited.
## Hyphenation
## 295
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 305 -->

AWS Content Design System

AWS style
• High- and low-priority queues
• Cost- and time-eﬃcient solution
• Single- and multi-threaded performance tests
Not AWS style
• High and low-priority queues
• Cost and time eﬃcient solution
• Single and multithreaded solution

Don't modify service names:
• In general, we don't modify service names by using hyphens or en dashes, unless the exception
is documented in the Usage dictionary. We don't want to create any "new" terms with service
names because that is a legal risk for brand and trademark.
## • Exceptions:
• Amazon EBS–backed AMI
• Amazon EBS–optimized instance types
• Amazon S3–backed AMI
Search engine optimization
Search engine optimization (SEO) is an iterative process of creating great content that people are
looking for and helping them ﬁnd it. SEO is a major part of discoverability, along with information
architecture.
SEO has three main areas of focus, in priority order:
• On-page SEO: The URL, title, description, ﬁrst sentence, keyword use, and organization of a
page.
• Research keywords: Connecting your content with the terms that readers actually search for.
Search engine optimization
## 296
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 306 -->

AWS Content Design System
• Backlinks: Internal and third-party links to your content.
Best practices
When you are considering which SEO techniques to use, use the following guidelines:
• Write for the reader ﬁrst, search engine second.
• Fix your content and keywords before you work on backlinks.
• Review performance regularly. SEO is not a one-time achievement.
• Optimize only your most important and useful topics. Don't try to optimize every topic.
Reference topics should complete on-page SEO only, for example.
On-page SEO
Write content that's structured in a way to allow the best results from search engine crawling
and result page position. Search engines use certain HTML tags such as <title>, <meta
name="description">, and <h1> (among many other data points) to create page ranking scores.
These scores determine the search engine result page position for a webpage and keyword pair.
Best practices
When optimizing content for on-page SEO, follow these best practices:
• Keep content focused on one main idea.
• Choose one set of 2–5 keywords that reﬂect the main idea, such as spot pricing bids for each
webpage. For more information about choosing good keywords, see Keyword research.
• Use the same keywords or synonyms in the title, URL, description, ﬁrst sentence, ﬁle names
(including art), captions and alt text, and throughout the content. For more information, see SEO
for content.
• Organize the content logically, with one <h1> tag, one or more <h2> tags, and so on.
• Correct errors as soon as possible and make improvements as needed.
## Titles
The topic title is one of the top factors in search engine ranking. It's used on the page, in the
browser chrome, as anchor text for social media links, and in search engine results. A well-designed
Best practices
## 297
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 307 -->

AWS Content Design System
title creates a relevant browsing experience. There's no disconnect for readers who click through
from another site. For more information about writing titles, see Titles.
Best practices
To create eﬀective SEO titles, follow these guidelines:
• Keep the title to 50–60 characters. Search engines might truncate anything longer in search
engine results.
• Use keywords early in the title and move branding closer to the end.
• Use short product names and acronyms. Avoid introducing an acronym with parentheses in the
title.
• Avoid generic titles, such as Troubleshooting or Error Messages. Use keywords speciﬁc to a service,
feature, or task.
• Create a positive message that will encourage readers to go through to your topic.
AWS style
• How to make money using the Product Advertising API
Not AWS style
• Amazon Product Advertising API Monetization Considerations
URLs
A topic URL consists of the protocol (http://), domain or subdomain (docs.aws.amazon.com),
folders (AmazonEC2/latest/UserGuide), page name (instance-concepts), and extension (.html). The
HTML page name is set by the ID attribute for the section element. The URL is displayed on search
engine results, the browser chrome, and in links.
Best practices
When creating URLs for optimal SEO performance, follow these guidelines:
• Make the page name brief but descriptive: use keywords separated by hyphens, and avoid
branding. The URL should help orient the reader within the documentation set.
URLs
## 298
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 308 -->

AWS Content Design System
AWS style
http://docs.aws.amazon.com/AWSECommerceService/latest/DG/ﬁnding-items-using-browse-
nodes.html
Not AWS style
• http://docs.aws.amazon.com/AWSECommerceService/latest/DG/
ﬁndingitemsusingbrowsenodes.html
• http://docs.aws.amazon.com/AWSECommerceService/latest/DG/
ﬁnding_items_using_browse_nodes.html
• http://docs.aws.amazon.com/AWSECommerceService/latest/DG/nodes.html
• http://docs.aws.amazon.com/AWSECommerceService/latest/DG/6d88033d.html
Meta descriptions
A meta description is an HTML attribute that provides a brief summary of a webpage. The meta
description is displayed in search results and in social media such as Facebook. Along with the
title, it's the best hook to invite readers to our content. Meta descriptions should be added to each
topic or section of content that's displayed as a separate webpage. As with other SEO tactics, meta
descriptions are most important at the chapter level and for high-traﬃc pages.
Best practices
To write eﬀective meta descriptions that improve click-through rates, follow these best practices:
• Write compelling copy that tells readers what the topic is about and encourages them to click
through, without using overly strong marketing language. You don't have to start with a verb,
but click-through rate improves when you make the description active or describe a solution.
• Keep the character count between 50–150. Descriptions should be long enough to inform the
customer about the content but not so long that they are truncated in search results.
• Use relevant keywords (shown in bold in search engine results). For more information, see
Research keywords.
• Avoid repeating the title in the meta description because titles are typically displayed
immediately above descriptions in search results.
• Use short product names.
• Avoid quotation marks and links.
Meta descriptions
## 299
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 309 -->

AWS Content Design System
• Avoid duplicating descriptions across multiple pages.
## Abstracts
In AWS documentation, the abstract element is used to tag meta descriptions. For more
information about how to tag the meta description using the ZonBook schema, see the abstract
tag in the list of ZonBook Elements. A bstracts are not required by the ZonBook schema. However,
they do improve discoverability, click-through rate, and the experience of customers looking for our
content using AWS site search. If you don't include an abstract, search results will display the ﬁrst
lines of text on the page instead of a succinct description of the topic.
AWS style
• Use a network access control list to control traﬃc in and out of a subnet.
Not AWS style
• A network access control list is an optional layer of security that acts as a ﬁrewall for controlling
traﬃc in and out of one or more subnets.
• Network ACLs for Amazon VPC
• 6 reasons why you should control subnet traﬃc with this one weird trick
More resources
• Moz.com
## • Web Analytics 2.0 (Kaushik)
• The Art of SEO (Enge, Spencer, Fishkin, and Stricchiola)
• Search Engine Optimization an Hour a Day (Grappone and Couzin)
## Tables
A table presents related data in rows and columns, which helps readers identify categories or
compare values in a dataset. Use a table when you want to list three or more categories, or when
you want to show a comparison. Avoid using a table when a basic list or term deﬁnition list would
work instead.
## Abstracts
## 300
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 310 -->

AWS Content Design System
For service documentation guidance for XML tagging, see the tables element in the ZonBook
elements wiki.
When creating tables:
## Do
• Consider accessibility.
• Include a lead-in sentence before a table.
• Use the last (rightmost) column for the longest or largest volume text, to prevent rendering
issues.
• Use sentence case capitalization for column headings.
• Use column headers so a screen reader can locate rows and columns quicker.
• When using footnotes, include the footnotes immediately after the table in a paragraph. Use
superscript numbers to indicate footnotes, unless the footnotes are for numbers. If the footnotes
are for numbers, use special characters as the superscript text, such as the asterisk (*), caret (^),
or plus (+) characters.
• When using images and icons in tables, follow the guidelines for Images and icons in tables.
• Check tables in a test build or preview to verify that they don't have rendering issues.
• Use the words Not applicable or None in a cell when needed to indicate an empty or blank cell.
• Exception: Cloudscape tables should use a hyphen (‐) for empty cells. For more information,
see Table on the AWS Design System website.
Don't
• Don't use tables as a way to format or stylize paragraphs, for example to act as a banner or to
right align text.
• Don't add a title to a table. Instead, use the table element to create a table without a title.
• Don't create a table with only two columns. Instead, use a variable list or other list format.
• Don't use rowspans in headings. Instead, split a complex table with rowspans into multiple
tables.
• Don't use rowspans in rows or columns.
• Don't use row headers.
• Don't leave table cells empty or blank. Instead, use Not applicable or None. Don't use N/A or an
em dash (—), en dash (–), or hyphen (‐), to indicate the cell is empty or blank.
## Tables
## 301
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 311 -->

AWS Content Design System
• Exception: Cloudscape tables should use a hyphen (‐) for empty cells. For more information,
see Table on the AWS Design System website.
• Don't use formatting, color, or shading in tables.
• Don't use notes and warnings in tables.
• Don't use screenshots or complex graphics in tables. You can use icons, if necessary, for
scannability or for a visual reference. For more information, see Images and icons in tables.
Consider accessibility when creating tables
Keep tables simple. Complex tables aren’t accessible and can make it harder for all audiences
to understand. Complex tables are tables with multiple header rows, rowspans, or colored cells.
Instead of one large complex table, use one or more simple tables.
For more information about simple and complex tables, see the Tables Tutorial on the Web
Accessibility Initiative (W3C) website.
For more information, see the section called “Accessibility”.
Lead-in sentences
Lead-in sentences before tables provide context for the table in the content. Don't insert tables
into topics without explanation or integration with the text. Any table worthy of presenting is also
worth introducing with a lead-in sentence.
When writing lead-in sentences:
• Use complete sentences. Don't use a sentence fragment.
• Don't end the sentence with a colon.
AWS style
• The following table lists the categories of instance metadata.
• The following table lists the tasks, and the command line tools and SOAP APIs for accomplishing
the tasks.
Consider accessibility when creating tables
## 302
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 312 -->

AWS Content Design System
Table examples
Here are some examples of when to use tables.
Example 1: Use tables to compare data
AWS style
The following table shows the rWRU consumption for 2017.11.29 (Legacy) and 2019.11.21
(Current) tables.
## Operation
## 2017.11.29 (Legacy)
## 2019.11.21 (Current)
## Savings
PutItem
4 rWRUs
2 rWRUs
## 50%
UpdateItem
3 rWRUs
2 rWRUs
## 33%
DeleteItem
3 rWRUs
2 rWRUs
## 33%
Not AWS style
The following table shows the rWRU consumption for 2017.11.29 (Legacy) and 2019.11.21
(Current) tables.
rWRU consumption of 2017.11.29 (Legacy) and 2019.11.21 (Current) tables for a 1KB item in
two Regions
## Operation
## 2017.11.29 (Legacy)
## 2019.11.21 (Current)
## Savings
PutItem
4 rWRUs
2 rWRUs
## 50%
UpdateItem
3 rWRUs
2 rWRUs
## 33%
DeleteItem
3 rWRUs
2 rWRUs
## 33%
Example 2: Don't use tables for lists
AWS style
1. The user opens a web browser and accesses your webpage.
Table examples
## 303
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 313 -->

AWS Content Design System
2. Your webpage contains an HTTP form that contains all the information necessary for the user to
upload content to Amazon S3.
3. The user uploads content directly to Amazon S3.
Not AWS style
Uploading Using POST
## 1
The user accesses your page from a web browser.
## 2
Your webpage contains a form that contains all the information necessary for the user
to upload content to Amazon S3.
## 3
The user uploads content to Amazon S3 through the web browser.
Example 3: Don't use tables for styling
AWS style
Supports identity-based policies: Yes.
Not AWS style
Supports identity-based policies
## Yes
Example 4: Include text in every header cell
AWS style
## Browser
macOS
## 10.15+
## Windows 10
## Linux
iOS 14.5+
## Android 7+
## Chrome
## Yes
## Yes
## Yes
## Yes
## No
## Safari
## Yes
## No
## No
## Yes
## No
## Edge
## Yes
## Yes
## No
## Yes
## No
Table examples
## 304
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 314 -->

AWS Content Design System
## Browser
macOS
## 10.15+
## Windows 10
## Linux
iOS 14.5+
## Android 7+
## Firefox
## Yes
## Yes
## No
## Yes
## No
Not AWS style

macOS
## 10.15+
## Windows 10
## Linux
iOS 14.5+
## Android 7+
## Chrome
## Yes
## Yes
## Yes
## Yes
## No
## Safari
## Yes
## No
## No
## Yes
## No
## Edge
## Yes
## Yes
## No
## Yes
## No
## Firefox
## Yes
## Yes
## No
## Yes
## No
Images and icons in tables
You can use an icon as a visual reference or to improve scannability in tables. However, a table
should be clear without reliance on images or icons.
In tables, we use icons for the following use cases:
• To show customers what a UI component looks like, if the customer might not recognize it by
name only.
• To supplement written text if the icon is in the same table cell, such as a checkmark icon next to
the word "Yes."
When using images and icons in tables:
## Do
• When an icon and its description share the same cell, use null alt text. For more information, see
Inline icons in a table.
• When an icon is used as a visual reference alone in a cell (such as a UI component), use
descriptive alt text. For more information, see Images in table cells (not inline).
Images and icons in tables
## 305
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 315 -->

AWS Content Design System
Don't
• Don't use a table to format how an image appears on a page. For example, to align an image on
the page or add a border to an image.
• Don't use null alt text in tables except for inline icons. For more information, see Inline icons in a
table.
For more information about using icons in service documentation, see Add inline icons.
Inline icons in a table
For accessibility, never use an image to replace words. If you use icons for yes, no, or maybe in
tables, you must also provide written words for these icons in the same cell.
In AWS documentation, when an icon in a cell has descriptive, written text in the same cell, it’s
considered inline, and should use null alt text. For more information, see Decorative Images on
the W3C website. For more information about the yes, no, or maybe icons, see Add Yes/No/Maybe
inline icons in your docs.
## Note
For AWS documentation, when an icon is in the same cell as its written description, we
recommend null alt text to prevent redundancy for screen readers. However, an icon that
already has descriptive alt text is accessible, so there’s no requirement to change that to
null alt text.
Aside from the short descriptive phrase or word in the cell, do the following:
• Write lead-in content to help customers understand what the words or icons refer to. For
example, “The warning icon indicates <what>.”
• Write table headings that give context to icons. For example, a column heading, “Supported by
ServiceName,” followed by a cell with “Yes” and the yes icon.
Images in table cells (not inline)
Sometimes a table uses an image as a visual reference. For example, a table might list UI
component icons in one column, and describe what they do in another column.
Images and icons in tables
## 306
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 316 -->

AWS Content Design System
Seeing the UI components helps customers with vision to locate the components in an interface.
However, customers who use screen readers also need a way to locate the components in an
interface. To provide this, your alt text must include the accurate ARIA label name followed by the
word “icon.“
AWS style
• The settings icon.
Not AWS style
• The gear icon.
## Note
Never use null alt text for icons that are alone in a cell. Customers sometimes tab through
columns, and hearing “null” in each cell makes the icon inaccessible.
Aside from using descriptive alt text for these types of images, do the following:
• In the separate “Description” cell, use the ARIA label name for the icon. For more information,
see Accessibility and Iconography in the Cloudscape Design System.
• Provide context about the icon by writing a label heading and related lead-in content.
Checking tables for rendering issues
Tables render diﬀerently depending on the content, output format, and display device. As much
as possible, avoid large tables, formatting in tables, and dense text. Keeping tables simple helps
customers: they can scan the information, and they won't need to use horizontal scroll. When
reviewing how tables render, pay attention to the following items:
• Bulleted lists.
• Non-wrapping elements, such as code.
• Wide content or long API names.
• Four or more columns.
Checking tables for rendering issues
## 307
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 317 -->

AWS Content Design System
• Rows that span columns.
• All supported output formats, such as PDF.
• Small screen sizes.
Titles and headings
## Topics
• Title styles
• Optimizing titles for SEO
• Using separate topic and TOC titles
Titles and headings describe the key subjects that are covered in a topic or section. In many
contexts, a title might be the ﬁrst and last thing that the reader will see for a topic. When you write
a title, think of it as your ﬁrst and only opportunity to concisely communicate what your topic has
to oﬀer.
In general, noun phrases are more common for conceptual topics, and present participle phrases
or imperative statements are more common for procedural topics. (The heading for an actual
procedure is an inﬁnitive phrase.) It's ﬁne to deviate from these conventions, but we recommend
that you make your title phrasing strategy consistent within your service.
For information about how to specify topic and TOC titles, see the title element in the Zonbook
elements Wiki page.
Best practices
• Avoid beginning titles with an article, such as a, an, or the.
• Use sentence case for topic titles, headings, and subheadings. Use title case for guides and
references.
• Keep titles short, descriptive, and unique. We recommend titles that are 50–60 characters for
comprehension and discoverability. See the section called “Optimizing titles for SEO”.
• Don't stack headings. Be sure to include explanatory text in between headings.
• Avoid titles that might be hard to localize, such as "Under the hood."
• Avoid using parentheses or introducing both versions of an acronym. Use the most recognized
form in the title, and spell it out or introduce the acronym in the ﬁrst sentence.
Titles and headings
## 308
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 318 -->

AWS Content Design System
AWS style
Creating an instance store-backed Linux AMI
Tutorial: Getting started with S3 Express One Zone
Not AWS style
Creating an instance store-backed Linux Amazon Machine Image (AMI)
A tutorial on how to use the S3 Express One Zone
Title styles
Here are two styles that you can use for titles:
• Noun-based phrase + preposition + service name
• Present participle phrase + preposition + service name
AWS style
• Access control in Amazon S3
• Data protection in Amazon S3
• Performance optimization in Amazon S3
AWS style
• Creating a bucket in Amazon S3
• Adding an object to a bucket in Amazon S3
• Viewing an object in Amazon S3
Optimizing titles for SEO
Titles (and secondarily headings) are crucial for search engine optimization (SEO). Of all topic
elements, the title has the biggest impact on SEO.
Title styles
## 309
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 319 -->

AWS Content Design System
• Use keywords that describe the topic that readers are most likely to use in their search query.
Examples include:
## • Task
• Feature name
• Service name
• Programming language
• Present critical and diﬀerentiating information ﬁrst on the left and supplementary and
supporting information second on the right of the title.
• Use 50–60 characters. If that's not possible, make sure that the most likely searched keywords
are presented in the ﬁrst 70 characters.
• Use short service names and acronyms. Avoid introducing an acronym with parentheses in the
title.
For more information, see Titles and AWS service names in headings.
Using separate topic and TOC titles
To optimize titles for both search engines and the TOC, consider using separate titles for the topic
and for the TOC.
The topic title is displayed as the title of the topic and used in search engine results.
• Include: All keywords that uniquely describe the information in the topic and the name of the
relevant service.
• Include: Disambiguating information that would uniquely identify the service.
The TOC title is a shorter title displayed only in the table of contents.
• Include: Key information that describes the topic within the context of the service.
• Exclude: Disambiguating information that would uniquely identify the service. (The service
context of the titles is provided by the location of where users are in the documentation.)
The following examples illustrate topic and TOC titles.
Using separate topic and TOC titles
## 310
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 320 -->

AWS Content Design System
Topic title
TOC title
Access control in Amazon S3
Access control
Adding an object to a bucket in Amazon S3
Adding an object to a bucket
## Command Line Interface Reference
CLI Reference
Writing basics
To make text more readable and accessible for our customers, take the following steps.
## Topics
• Break up sentences and paragraphs
• Tighten your prose
• Avoid nominalizations
• Use lists to break up text
• Use active voice and strong verbs
• Write for a global audience
• Write a good introductory paragraph
• Document the user's task, not the feature
• In a sentence, put the goal ﬁrst and then the task
• Avoid jargon
## • Avoid Latinisms
• Use customer-centric language
• Apply correct procedure style
Break up sentences and paragraphs
As we advise in Global English, keep sentences short. Long sentences with multiple clauses can be
hard for English as a Second Language (ESL) readers to follow and painful for translators. Shorter
sentences are more readable for all audiences.
Writing basics
## 311
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 321 -->

AWS Content Design System
Where possible, limit your sentences to 25 words or fewer. Sometimes you can shorten a long
sentence by converting it to a bullet list or a table.
Keep paragraphs short. We often get customer feedback that our docs are too dense. Research
shows that web readers skim, not read. Catch people's eye and break text with short, tight
paragraphs.
Tighten your prose
Don't use unnecessary words. Keep sentences short and concise.
Some ﬁxes:
• Have the opportunity to → Can
• Have the option to → Can
• In order to → To
• Must be able to → Must
• Note that → [Delete entirely]
• Please → [Delete entirely]
• Whether or not → Whether
• Will be able to → Can
• Won't be able to → Can't
• Would like to → Want to
• You should → [Delete entirely]
AWS style
• After you sign up and download the AWS Import/Export Web Service Tool, create an export job.
An export job downloads data from Amazon S3 buckets in your AWS account to your storage
device.
(33 words in two sentences)
Not AWS style
Tighten your prose
## 312
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 322 -->

AWS Content Design System
• Now that you're signed up and have downloaded the AWS Import/Export Web Service Tool, you
can create an export job to download your data from Amazon S3 buckets owned by your AWS
account to your storage device.
(35 words in one sentence)
Avoid nominalizations
Nominalizations are nouns created from adjectives and verbs. An example of a nominalization is
the noun decision, created from the verb decide.
Nominalizations make it diﬃcult to identify the subject and action of a sentence. This makes
translation and localization of the text more diﬃcult. Nominalizations can also change a sentence
to the passive voice (see the following section, Use active voice and strong verbs). Write around
nominalizations where possible.
AWS style
• In this process, your application source (subject) doesn't redeploy (verb).
Not AWS style
• In this process, no redeployment (nominalized verb) of your application source (subject) occurs.
Use lists to break up text
Lists are another way to clarify text and catch the eye.
They also make text less dense.
When using lists, make sure that your introductory sentence is complete.
AWS style
• Spatial analysis can also be valuable in a number of other domains, such as these and similar
ones:
• Marketing – Target a promotion to all prospects within two miles of a store.
• Asset management – Locate repair units to minimize impact based on customer location and
density.
Avoid nominalizations
## 313
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 323 -->

AWS Content Design System
• Risk analysis – Estimate risk premiums based on incidence of car thefts in locations near the
customer's residence and workplace.
• Fraud detection – Estimate the likelihood of a fraudulent transaction based on the distance
from the previous transaction.
• Logistics planning – Assign trouble tickets to ﬁeld technicians to minimize the radius of travel.
Not AWS style
• It turns out that spatial analysis can be valuable in a number of other domains as well, such as
marketing—"target promo to all prospects within 2 miles of store," asset management—"locate
repair units to minimize impact based on customer location and density," risk analysis—"estimate
risk premiums based on incidence of car-thefts in locations adjacent to the customer's residence
and workplace," fraud detection—"estimate likelihood of fraud transaction based on distance
from previous transaction," logistics planning—"assign trouble tickets to ﬁeld technicians to
minimize radius of travel".
Use active voice and strong verbs
As The Chicago Manual of Style says, "Voice shows whether the subject acts (active voice) or is acted
on (passive voice). Passive voice is typically, though not always, inferior to active voice."
Strunk and White say, "Use deﬁnite, speciﬁc, concrete language. Prefer the speciﬁc to the general,
the deﬁnite to the vague, the concrete to the abstract. In practice, avoid 'to be' and 'to have' where
you can use stronger verbs."
AWS style
• Choose encryption.
Not AWS style
• Encryption should be chosen.
AWS style
• Now you can use encryption.
Use active voice and strong verbs
## 314
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 324 -->

AWS Content Design System
Not AWS style
• Support is now available for encryption.
For more details about eﬀective use of voice, see Voice and Tone.
Write for a global audience
Our guides must be uncomplicated for ESL customers to read and translators to translate. These
writing rules mentioned elsewhere apply here:
• Use active voice.
• Use short sentences.
• Avoid jargon.
For global writing, we also focus on these:
• Use complete sentences rather than fragments.
• Use terms consistently; deﬁne new terms.
• Reduce ambiguity; use words that have two meanings correctly.
• Use optional clarifying words.
For complete guidelines, see Global English.
Write a good introductory paragraph
A good introductory paragraph starts a topic in an interesting, informative way. Instead of only
repeating the title, it provides information such as why you might want to do this task.
AWS style
• To run your extract, transform, and load (ETL) scripts, you sometimes develop and test your
scripts using a development endpoint. When you set up a development endpoint, you specify a
virtual private cloud (VPC), subnet, and security groups.
Not AWS style
• This topic tells you how to set up your environment for development endpoints.
Write for a global audience
## 315
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 325 -->

AWS Content Design System
Document the user's task, not the feature
Customers want to know what to do with a new feature. Write headings to make clear the task that
the feature performs.
AWS style
• Recognizing an email address
• Converting phone numbers into strings
• Reducing latency
Not AWS style
• AMAZON.EmailAddress
• AMAZON.PhoneNumber
## • Image Operation Latency
In a sentence, put the goal ﬁrst and then the task
To place readers, start how-to sentences by describing the goal to be accomplished ﬁrst (what or
why) and then describe the actions to do it (how).
AWS style
• To enable the Binary Reader, modify your source connection to include the following parameters.
• To connect to your gateway, ﬁrst get the IP address of your gateway VM.
• Complete activation by conﬁguring your gateway.
Not AWS style
• Modify your source connection to include the following parameters to enable the Binary Reader.
• Get the IP address of your gateway VM as the ﬁrst step in connecting to your gateway.
• Provide the information on the activation page to conﬁgure your gateway and complete
activation.
Document the user's task, not the feature
## 316
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 326 -->

AWS Content Design System
Avoid jargon
Jargon is terminology used by a particular group that's diﬃcult for others to understand. It can
confuse readers and convey "you're not smart enough to get this." If necessary, we can deﬁne
terms, but often jargon is unnecessary. You should avoid the following jargon.
• Best-in-class or best-of-breed → (Don't use. Don't overpromise. Rewrite with a focus on what the
service or feature can do for the customer.)
• below the fold → (Don't use)
• black-box testing → behavioral testing
• blackout → service outage or blocked
• Disruptive → innovative
• Ecosystem → environment, system
• End-to-end → (Avoid. OK in industry terms such as "end-to-end encryption.")
• enterprise-grade → (Don't use)
• Leverage → use
• Payload → (Use the speciﬁc term for what the payload is, such as "message.")
• Performant → high-performing
• Primitive → primitive type or primitive data type
• Public-facing, internet-facing, or customer-facing → public
• Search hits → search results
• white-box testing → structural testing
• white-labelled → rebranded
## Avoid Latinisms
Latinisms are Latin words or phrases that are found in English, such as etc. and per se. Don't use
them. Instead, use more common words and phrases. This makes your writing more accessible to
global users, and more approachable and friendly sounding. For more information about using the
correct tone in your writing, see AWS voice and tone.
AWS style
• You can automate sending text message notiﬁcations to users with Amazon SNS.
Avoid jargon
## 317
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 327 -->

AWS Content Design System
• If no value is passed, then only the membership of the dialog in the proﬁle is checked.
• What is the annual cost of maintaining your workload on premises compared to AWS?
Not AWS style
• You can automate sending text message notiﬁcations to users via Amazon SNS.
• If no value is passed, then only the membership of the dialog in the proﬁle per se is checked.
• What is the annual cost of maintaining your workload on premises vs. AWS?
The following table provides a list of common Latinisms and their preferred substitutes.
Latin term
Preferred term
ad hoc
(Don't use. If need be, use one-time or when
required.)
de facto
actual
etc. (et cetera)
(Don't use. If necessary, replace with and so
on.)
ergo
therefore, so, as a result
e.g. (exempli gratia)
for example, such as
i.e. (id est)
that is, speciﬁcally
per
for, for each
per se
(Don't use)
v., vs. (versus)
compared to, compared with
via
through, by using, with
vice versa
the reverse, the other way around, the
opposite is also true
viz. (videlicet)
for example, such as
## Avoid Latinisms
## 318
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 328 -->

AWS Content Design System
## Exceptions
One exception to this guidance is the word per. Because it’s common in the documentation and
console, and is typically well understood by users, it’s OK to use per, especially where space is
limited. Also, don’t replace it from set terms and phrases, such as any of the following:
• on a per-Region basis
• queries per second (QPS)
• bits per second (bps)
• megabytes per second (MBps)
However, it’s still good to write around it elsewhere. Avoiding it can help make the tone of your
writing more approachable and quicker to parse.
AWS style
• If this argument is provided, the service generates a unique upload URL for each ﬁle.
• You can specify and pay for resources for individual applications separately.
• You can use more slides to reduce the amount of content on each slide.
Not AWS style
• If this argument is provided, the service generates a unique upload URL per ﬁle.
• You can specify and pay for resources per application.
• You can use more slides if the content per slide is kept to a minimum.
For more examples and information about how to use per, see the per entry in the Usage
dictionary.
Use customer-centric language
When your writing involves the customer, write in a way that speaks directly to the customer and
their point of view. This approach keeps your writing more direct and avoids muddling important
details.
• Speak directly to the customer – Use second-person you to refer to the customer. Avoid using
words such as developer or user, except where it’s unavoidable (for example, Redshift users or
Use customer-centric language
## 319
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 329 -->

AWS Content Design System
IAM users). Similarly, avoid using ﬁrst-person we or let’s in procedures and instructions that
describe actions that the customer does. For more information, see AWS voice and tone.
• Consider the customer's point of view – Describe the actions that the customer takes, rather
than contextualizing from the service or feature perspective. For example, use phrases such as
“With this service, you can...” or “Use this feature to...” instead of saying a service or feature
allows, enables, or lets the customer do something.
AWS style
• With Amazon RDS for MySQL, you can publish your log events directly to Amazon CloudWatch
Logs.
• With Amazon Linux 2023, you can now use cloud-init with SELinux to enable enforcing mode.
• For testing purposes, update the bucket policy and explicitly deny Account B the
s3:ListBucket permission.
Not AWS style
• Amazon RDS for MySQL allows you to publish your log events directly to Amazon CloudWatch
Logs.
• Use of cloud-init with SELinux to enable enforcing mode is also a new feature option for
Amazon Linux 2023.
• For testing purposes, let's update the bucket policy and explicitly deny Account B the
s3:ListBucket permission.
## Note
Use enable and disable in reference to services, features, and settings (for example, to
describe making a feature available or unavailable). Don't use enable or disable in reference
to the customer or any human being.
Apply correct procedure style
To write eﬀective procedures, place your reader in the ﬁrst procedure step. This is less necessary
if you have a group of tightly linked procedures. However, if there's a question prefer placing the
reader.
Apply correct procedure style
## 320
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 330 -->

AWS Content Design System
As an example, if your customer is working in the console, use the console paragraph entity for the
ﬁrst step. The standard phrasing for a console paragraph is: Open the [service] console at [URL].
For example, the DataSync console paragraph entity is &DSYconsole_para; and in the docs reads
as: Open the AWS DataSync console at https://console.aws.amazon.com/datasync/.
For more details on writing procedures, see Procedures.
Other resources
For issues of terminology, style, and other guidance that aren't covered in this guide, use the
following guides and resources.
Amazon references
• For UI:
• AWS console UI style – Cloudscape Design System website
• Amazon.com UI style – UX text style guide
• For API reference – AWS API Standards
• For partner marketing content – AWS Partner Creative and Messaging Guide
• For AWS brand content, such as visual brand assets (logos, color palettes, fonts, textures), latest
advertising campaign concepts, and video guidelines – Amazon Brand Portal
• For certiﬁcation exams and other assessment assets – AWS Assessment Style Guide
• For localization and translation reference – AWS Localization Terminology Management
• For internal AI assistant – Cedric - Productivity AI
Other references
• For technical style guidance:
## • Microsoft Writing Style Guide
## • Google Developer Documentation Style Guide
## • Apple Style Guide
• For general style guidance – The Chicago Manual of Style Online (subscription required)
• For language reference and guidance – The Merriam-Webster Dictionary
• For localization and translation reference – Microsoft Language Portal
Other resources
## 321
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 331 -->

AWS Content Design System
Content patterns
Content patterns for AWS content types.
Code example patterns
Use a code example pattern when you add code to a topic.
To chose the correct pattern, review the purpose and goal for each pattern:
## Pattern
## Purpose
## Goal
## Code
example
Accomplish a task (job-to-be-
done (JTBD)) using code
Complete a task
## Code
snippet
Present a small, syntactically
correct, piece of code

IAM
policy
Model security best practices
Understand security for AWS services
Code example pattern
Last updated date: 2025-04-30
Last updated by: Julie MacAller
• Purpose statement: Code examples demonstrate how to accomplish a customer task or job-
to-be-done (JTBD) using code. They include examples written in a supported programming or
conﬁguration language, such as C#, JavaScript, JSON, or .YAML. They also include CLI examples,
example IAM policies and CloudFormation templates. Code examples are usually assumed to be
working code that can be compiled and run or that can be scanned by a linter.
• Customer need/problem the pattern solves: Our customers who interact with AWS using
code expect and need code examples to help them see how to securely implement features and
services eﬀectively in their own code. They ask for code examples often. Code examples are of
diﬀerent types:
Code example patterns
## 322
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 332 -->

AWS Content Design System
• snippet: single block of code, no accompanying text, might not be runnable on its own
• complex snippet: snippet with description or instructions of some kind
• partial example: runnable block of code with accompanying text. Requires additional code/
conﬁg ﬁles to truly run (found on GitHub or similar).
• scenario: multiple blocks of code (and text) that form a larger job to be done. Might
encompass multiple services.
• complex scenario: scenario with additional supporting code (CFN or CDK setup, conﬁguration,
environment setup).
• application: complete runnable piece of software that includes everything required to run it.
• tutorial: diﬀers from the rest in that it has more text and takes a "let's build this together"
approach where the reader is expected to cut & paste code into their IDE and follow along so
that they exit the tutorial with a runnable demo.
## Structure
The components you use in your code example depend on what type of code example it is. The
only required component is the code block, which contains the actual code. The other elements are
optional, although for some types of examples including them is a best practice.
Required components
• Code block: contains the actual code for the example.
Optional components
• Title: contains the title of the code example.
• Alternative title: contains the alternative title for the example.
• SEO description: contains a short SEO description for the example.
• Summary: contains the abstract or summary for the example.
• Prerequisites: contains the prerequisites for the example.
• Details: a list of items in the code example and their deﬁnitions or explanations. Use a bulleted
list or a deﬁnition list.
• Paragraphs: accompanying text providing more information about the example. Can include a
lead-in sentence that introduces the example.
• Conclusion: contains the conclusion for the example.
Code example
## 323
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 333 -->

AWS Content Design System
• Exclusions: contains any exclusions for the example.
• Next steps: contains the next steps for the example.
## Guidelines
Apply the guidelines to the code example content.
## Do
• Use the summary element to explain what the code example does and what behaviors customers
can expect when the example runs successfully.
• Use the prerequisites element to describe required permissions, and any other prerequisites.
• Use the exclusions element for the runnable disclaimer, if it applies. The runnable disclaimer
informs customers that this example is not runnable on its own, and must be run in context. For
example, "Action examples are code excerpts from larger programs and must be run in context.
You can see this action in context in the following code example: (provide links to contextual
code examples)."
• Use a tabbed interface for multiple programming or conﬁguration languages, if applicable.
• Use clear placeholder names for replaceable values, such as my-region or my-bucket.
• Identify replaceable values clearly.
Don't
• Don't use a screenshot to show a code example.
• Don't add a code example that isn't part of the repository. The repository ensures that examples
adhere to Amazon security policies and pass linter checks and other quality assurance tests.
## Examples
TBD
Additional resources
• Related patterns/types/templates
• Training materials
• Support channels
Code example
## 324
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 334 -->

AWS Content Design System
Code snippet pattern
Last updated date: 2025-04-29
Last updated by: Julie MacAller
• Purpose statement: Code snippets are small, reusable fragments of code or command-
line interface commands, as small as a single, syntactically correct statement. A snippet can
demonstrate how to accomplish a customer task or job-to-be-done (JTBD), or the proper syntax
and options for a particular command-line interface command. Code snippets include examples
written in a supported programming language, such as JavaScript or C++, as well as in supported
conﬁguration languages such as JSON or YAML.
• Customer need/problem the pattern solves: The diﬀerence between a code snippet and a
code example is that code snippets aren't expected to be runnable. They're expected to be
syntactically correct, so that a customer can copy a code snippet into their own code and expect
that the snippet won't generate errors.
One use case for code snippets is to help customers understand a larger code example by
showing an excerpt of the code and discussing it using other content components (paragraphs,
lists, and so on).
Writers can also use code snippets for showing excerpts of IAM example policies, CloudFormation
templates, and other conﬁguration ﬁles when they want to provide more information for the
customer about one of these sections.
## Structure
Pages that use the code snippet template must contain all of the required components.
Required components
• Code block: contains the line or lines of code, or the command-line interface command.
Optional components
• Details: a list of items in the code snippet and their deﬁnitions or explanations. Use a bulleted list
or a deﬁnition list.
• Paragraphs: accompanying text providing more information about the snippet. Can include a
lead-in sentence that introduces the snippet.
Code snippet
## 325
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 335 -->

AWS Content Design System
• Title: provides a customer-focused title for the snippet that describes what the snippet does.
## Guidelines
Apply the guidelines to the code snippet content.
## Do
• Introduce a code snippet with a lead-in sentence that explains what the snippet does or
represents.
• Follow a code snippet with a list of details if the snippet contains anything that customers might
need more information about.
• If the code snippet comes from a larger code example, provide a link to the larger sample.
• Use clear placeholder names for replaceable values, such as my-region or my-bucket.
• Identify replaceable values clearly.
Don't
• Don't refer to replaceable values by how they are formatted. Formatting can change.
• Include a screenshot of a code snippet. Make sure that all code snippets are code blocks.
## Examples
TBD
Additional resources
• Code example pattern
• Code block component
• IAM example policy pattern
• Training materials
• Support channels
IAM example policy pattern
Last updated date: 2025-04-03
IAM example policy
## 326
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 336 -->

AWS Content Design System
Last updated by: Julie MacAller
• Purpose statement: IAM example policies demonstrate security best practices so that customers
can understand how to implement them in their AWS infrastructure. JSON is the conﬁguration
language for IAM policies. IAM example policies should be working JSON that can pass scanning
by a linter and not generate any security warnings.
• Customer need/problem the pattern solves: IAM example policy snippets are smaller fragments
of JSON, all the way down to a single, syntactically correct statement. They are addressed in the
code snippet pattern.
Securing AWS resources and infrastructure is complex. Crafting IAM policies that meet customer
needs and exemplify best practices is also complicated. Our customers need abundant example
IAM policies that demonstrate best practices in many situations.
## Structure
Pages that use the IAM example policy template must contain all of the required components.
Required components
• Summary: contains the customer-focused description of the job to be done with the IAM policy
example.
• Code block: contains the JSON for the IAM example policy.
• Title: contains the title of the IAM example policy.
Optional components
• Alternative title: contains the alternative title for the IAM example policy.
• SEO description: contains a short SEO description for the IAM example policy.
• Prerequisites: contains the prerequisites for the IAM example policy.
• Details: contains explanations of the parts of the IAM example policy.
• Conclusion: contains the conclusion for the IAM example policy.
• Exclusions: contains any exclusions for the IAM example policy.
• Next steps: contains the next steps for the IAM example policy.
IAM example policy
## 327
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 337 -->

AWS Content Design System
## Guidelines
Apply the guidelines to the IAM example policy content.
## Do
• Use the Summary element to explain what the IAM example policy does and the customer
impact of using the policy.
• Use the Prerequisites element to describe required permissions. Also use for sequential
examples, where you build on the ﬁrst.
• Use the Details element to explain the policy at a deeper level.
• Use the Conclusions element to explain the expected results of applying the policy.
• Use clear placeholder names for replaceable values, such as my-region or my-bucket.
• Identify replaceable values clearly.
Don't
• Don't include incomplete policies as example policies. An example policy must be a complete and
valid JSON document that lints successfully. A standalone statement and/or portion of a policy is
called a snippet, and is not included in this content pattern.
## Examples
[TBD]
Additional resources
• Code block component
• Code example pattern
• Code snippet pattern
• Training materials
• Support channels
Conceptual patterns
Use a conceptual pattern when the customers need to understand ideas.
Conceptual patterns
## 328
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 338 -->

AWS Content Design System
To chose the correct pattern, review the purpose and goal for each pattern:
## Pattern
## Purpose
## Goal
## Basic
concept
Explain basic concepts for cases not
covered by more speciﬁc conceptual
patterns
Gain knowledge
## Best
practices
Document service-speciﬁc best
practices in a consistent way across all
AWS services
Understand AWS best practices
## Decision
guide
Help customers to choose the AWS
services or features that meet their
needs
Choose between AWS services or features
## Security
and
complianc
e
Provide service-speciﬁc security
information
Understand security for AWS services
## Service
and
feature
overview
Provide a high-level introduction to an
AWS service or feature
Understand AWS services and features
Basic concept pattern
Last updated date: 2025-08-01
Last updated by: Jim Eagan
• Purpose statement: Concept documentation provides customers with a broad understanding of
a topic, product, or system, explaining what it is and providing context for related tasks. It helps
build foundational knowledge before customers implement solutions.
• Customer need/problem this solves: Our customers need clear explanations of AWS concepts,
services, and technologies to build foundational knowledge before implementing solutions. They
want to understand what something is and why it matters before learning how to use it.
Basic concept
## 329
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 339 -->

AWS Content Design System
• Important note: This is a generic concept pattern intended for cases not covered by more
speciﬁc conceptual patterns. Before using this pattern, please check if a more speciﬁc conceptual
pattern applies to your content, such as:
• Best practices pattern
• "What is" service/feature overview pattern
• Decision guide pattern
• Security and compliance pattern
Only use this generic concept pattern when your content doesn't ﬁt into one of the more speciﬁc
patterns.
## Structure
Pages that use the basic concept template must contain all of the required components.
Required components
• Title: Clear, descriptive title that accurately represents the concept being explained
• Abstract: Brief overview of the concept and its importance to customers
• Introduction paragraph: Brief overview paragraph (without a heading) that introduces the
concept and the context in which it might be used or applied
• Deﬁnition section: Clear explanation of the concept, breaking it down into smaller parts if
necessary; update the section title to be speciﬁc to your content
• Key points section: Main components or aspects of the concept that customers should
understand; update the section title to be speciﬁc to your content
Optional components
• Deﬁnition subsections: Optional subsections within the Deﬁnition section to organize complex
information
• Key points subsections: Optional subsections within the Key points section to organize complex
information
• Additional resources: Links to related documentation, tutorials, or resources that customers
might need
Basic concept
## 330
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 340 -->

AWS Content Design System
## Guidelines
Apply the guidelines to the basic concept content.
## Do
• Provide a clear, concise deﬁnition of the concept
• Break complex concepts into smaller, more manageable parts
• Use plain language and avoid unnecessary jargon
• Explain why the concept is important or relevant to customers
• Connect the concept to related tasks or procedures
• Provide real-world examples or use cases when applicable
• Use consistent terminology throughout the document
• Update section titles to be speciﬁc to your content (for example, "Understanding AWS Lambda"
instead of just "Deﬁnition")
• Use bullet points or subsections to organize complex information within the Deﬁnition and Key
points sections when needed
• Consider using itemized lists within sections to highlight important points
Don't
• Don't assume prior knowledge of related concepts
• Don't use technical jargon without explanation
• Don't include procedural steps (use procedure pattern instead)
• Don't include troubleshooting information (use troubleshooting pattern instead)
• Don't overwhelm with too much detail in a single concept document
• Don't use generic section titles when speciﬁc ones would be more helpful
## Examples
• How Lambda works
Additional resources
• Concept topic types
Basic concept
## 331
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 341 -->

AWS Content Design System
• Writing about concepts
Best practices pattern
Last updated date: 2024-04-22
Last updated by: Shwetha Madhan
• Purpose statement: To provide a ﬂexible yet structured format for documenting best practices
across all AWS services, accommodating service-speciﬁc needs while ensuring consistency and
clarity for users.
• Customer need/problem the pattern solves:
• Customers need guidance on optimizing their use of speciﬁc AWS services
• Customers want to implement eﬃcient, secure, and cost-eﬀective solutions
• Customers seek to avoid common pitfalls and performance issues
• Customers need to understand service-speciﬁc considerations and limitations
## Structure
Pages that use the best practices template must contain all of the required components.
Required components
• Clear title indicating the service and "Best Practices"
• Introduction explaining the importance of these practices for the speciﬁc service
• Categorized sections relevant to the service (Security, Administration, Deployment, Compliance)
• Concise, actionable recommendations
• Explanations or rationales for each practice
• Links to related documentation or examples
Optional components
• Performance tips
• Speciﬁc use case scenarios
• Code examples or queries
Best practices
## 332
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 342 -->

AWS Content Design System
• Conﬁguration recommendations
• Monitoring and maintenance advice
• Cost optimization strategies
• Scalability considerations
Conditional components
• Service limits and quotas (if applicable)
• Data modeling recommendations (for database services)
• Query optimization techniques (for query-based services)
• Encryption and access control (for services handling sensitive data)
• Backup and recovery strategies
• Integration with other AWS services
## Guidelines
Apply the guidelines to the best practices content.
## Do
• Tailor the structure to the speciﬁc needs of each service
• Use consistent formatting for recommendations across services
• Provide clear, actionable steps or guidelines
• Include service-speciﬁc terminology and concepts
• Oﬀer both general and advanced recommendations where applicable
• Update regularly to reﬂect new features and evolving best practices
Don't
• Overload with excessive technical details better suited for API references
• Include basic "getting started" information that belongs in user guides
• Use overly broad or vague recommendations
• Neglect to explain the rationale behind each practice
Best practices
## 333
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 343 -->

AWS Content Design System
• Duplicate large amounts of content from other documentation sections
## Examples
Live examples of this on the site
• DynamoDB Best Practices
## • Amazon S3 Performance Optimization
## • Amazon Redshift Best Practices
Additional resources
Related patterns/types/templates
## • Troubleshooting
Training materials
Support channels
AWS Content Patterns team
Decision guide pattern
Last updated date: 2025-04-17
Last updated by: Jim Eagan
• Purpose statement: Decision guides help customers make informed technology choices by
providing a structured framework that highlights key factors to consider and connects to in-
depth resources. This pattern covers two types of decision content: service category guides
(choosing within a speciﬁc category) and micro decision guides (choosing between two speciﬁc
services). Both types simplify the discovery process by clearly presenting options and tradeoﬀs,
enabling customers to select the best solution for their needs.
• Customer need/problem the pattern solves: AWS oﬀers more than 200 services across 30
technology categories, and customers often struggle to ﬁnd the ﬁrst step in selecting among
them. Despite extensive documentation for each service, research shows customers need clear
guidance to navigate initial service selection when building or migrating applications.
Decision guide
## 334
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 344 -->

AWS Content Design System
## Structure
Pages that use the decision guide template must contain all of the required components.
Required components
• Title: A clear and concise title that sets the context for the decision the customer needs to make.
For service category decision guides, use the following format: Choosing an AWS [category]
service. For micro decision guides, list the services being considered, for example, [Service A] or
[Service B]?.
• Subtitle: Your subtitle should clearly communicate the purpose of the decision guide to help
customers quickly understand its value. Use diﬀerent approaches based on the guide type:
Service category decision guide: Taking the ﬁrst step; micro decision guide: Understand the
diﬀerences and pick the one that's right for you.
• Short description (abstract): A compelling 155-160 character synopsis that tells customers how
the content will beneﬁt them.
• Keywords: Should be unique to the content, focused on customer intent, and include primary,
secondary, and tertiary keywords. Refer to the keywords/phrases guidance for more details.
• At-a-glance details: A short table that details the purpose of the guide, the date it was last
updated, and the services covered.
• Introduction: A clear, concise, and context-setting overview of the choice and the services
involved. Imagine a new AWS customer reading this guide, who might be new to the topic
or might already be familiar with it. Use videos and visual elements where possible. Strike a
balance between technical and marketing so that a new AWS customer gets "just the facts" in an
engaging way, without "ﬂuﬀ" (75-200 words).
• Understand AWS [category] service (for service category guides) or Understand the diﬀerences
between [Service A] and [Service B] (for micro decision guides): Sets the context for the family of
services within the category, or the services being considered in a micro decision guide. Answer
this question: What will help a new customer understand the category as a whole, and how all
the services ﬁt into it, or the services being considered in the micro decision guide? (Up to 325
words).
• Consider AWS [category] criteria (for service category guides only): Answers the question, "What
criteria should I consider in this choice and why?" Sets the context for what customers need
to think about, and how each consideration helps the customer choose services. Highlights
distinguishing factors among services where possible (150 words per criterion).
Decision guide
## 335
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 345 -->

AWS Content Design System
• Choose an AWS [category] service (for service category guides only): Maps the preceding criteria
to customer needs to help them choose their services (150 words for section intro, and 75 words
for each customer need category).
• Use AWS [category] services (for service category guides) or Use [Service A] or [Service B]:
Suggests additional assets for understanding and using each service.
• Explore AWS [category] services (for service category guides only): Suggests additional resources
scoped by content type, such as editable architecture diagrams, ready-to-use code, and other
documentation.
Optional components
• Deﬁne: Helps users establish speciﬁc requirements based on their environment and needs.
Uses real-world examples to translate business needs into technical requirements, bridging
understanding of options with ﬁnal decision-making. For an example, see Application integration
decision guide (Up to 500 words).
## Guidelines
Apply the guidelines to the decision guide content.
## Do
• Present the decision options in a clear and structured way
• Highlight the key factors customers should consider when making their choice
• Provide clear next steps to guide customers after they have made their decision
Don't
• Overwhelm customers with too many details or options
• Use overly technical language or jargon that may be confusing
• Assume customers have deep prior knowledge of the services or technologies involved
## Examples
• Choosing an AWS analytics service
Decision guide
## 336
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 346 -->

AWS Content Design System
Additional resources
• AWS decision guides
Security and compliance pattern
Last updated date: 2025-08-04
Last updated by: Logan Schobel
• Purpose statement: Create security and compliance documentation to provide customers with
standardized, comprehensive security information for AWS services.
• Customer need/problem this solves: Before customers can adopt AWS services, customers
need to understand the security and compliance information for each service. Consistent,
comprehensive security documentation can increase the speed of customer adoption and
decrease barriers for regulated customers who need clear security information for compliance
assessments.
• Important note: This pattern is mandatory for all AWS services and must be used in conjunction
with the Security and compliance integration for TCX service documentation wiki. Use the
security and compliance pattern to structure your content while customizing the content to the
speciﬁc security features and controls of the service.
## Structure
Pages that use the security and compliance pattern must contain all required components in the
speciﬁed order and structure.
Required components
• Security in <service>: Top-level node that all other security topics are grouped under
• Data protection in <Short Service Name>: Comprehensive coverage of data encryption,
internetwork traﬃc privacy, and data management
• Data encryption (with subsections for encryption at rest, encryption in transit, key
management)
• Internetwork traﬃc privacy
• Identity and Access Management in <Short Service Name>: IAM integration details
Security and compliance
## 337
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 347 -->

AWS Content Design System
• Compliance validation for <Short Service Name>: Best practices for compliance. Link to the
AWS Marketing compliance program page.
• Resilience in <Short Service Name>: Backup, disaster recovery, versioning, and object locking
capabilities
• Infrastructure security in <Short Service Name>: VPC integration, network isolation, and multi-
tenancy information
• Conﬁguration and vulnerability analysis in <Short Service Name>: Customer responsibilities
for scanning, updates, and maintenance
• Cross-service confused deputy prevention: Protection against confused deputy attacks
• Security best practices for <Short Service Name>: Detective and preventative security controls
Optional components
• Incident response in <Short Service Name>: How customers detect, alert, and respond to
incidents
## Guidelines
Apply these guidelines when implementing security and compliance integration documentation.
## Do
• Include all required sections even if they don't apply to your service (state "not applicable" with
explanation)
• Use provided XML templates where available
• Have content reviewed by your service team before publishing
• Document default security features clearly, even when no customer action is required
Don't
• Don't expose internal processes or architecture that your security team wants to keep private
• Don't assume customers understand security concepts without explanation
• Don't guarantee compliance. Provide best practices and guidance instead.
Security and compliance
## 338
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 348 -->

AWS Content Design System
## Examples
• Amazon S3data protection
• Amazon Cognito IAM integration
• Amazon Bedrock incident response
Additional resources
• Security chapter template
• Security and compliance integration wiki
• IAM documentation integration template
Service and feature overview pattern
Last updated date: 2025-04-30
Last updated by: Jenna Messer
• Purpose statement: Service and feature overview pages provide a high-level introduction to an
AWS service or a feature. Overviews quickly familiarize customers with the service or feature key
features, beneﬁts, and basic concepts, setting the foundation for more detailed exploration of
the service or feature.
• Customer need/problem the pattern solves: Helps new customers quickly understand what the
service or feature does. An overview page provides a starting point for customers to navigate to
more speciﬁc information about the service or feature.
## Structure
Pages that use the service and feature overview template must contain all of the required
components.
Required components
• Title: Clear and concise (for example, "What is Amazon S3?")
• Short description: A brief (1-2 sentence) explanation of the service or feature
• Key features list: Bulleted list of main capabilities
Service and feature overview
## 339
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 349 -->

AWS Content Design System
• How it works section: A high-level explanation of the service's functionality, often with a diagram
• Basic concepts: Deﬁnitions of fundamental terms and ideas related to the service
• Use cases: Common scenarios where the service is applicable
• Pricing information: A brief mention of the pricing model or link to pricing page
• Compliance and security information: Brief overview of relevant certiﬁcations or security
features
• Related services: Other AWS services that integrate or work well with this one
• Next steps: Links to getting started guides, tutorials, or other relevant documentation
Optional components
• Alternative title
• Video overview: A short video explaining the service
• Media (images, video)
• Latest updates: Recent feature additions or improvements
## Guidelines
Apply the guidelines to the service/feature overview content.
## Do
• Keep the language clear, concise, and jargon-free
• Use visuals (diagrams, icons) to illustrate complex concepts
• Provide clear navigation to more detailed documentation
• Regularly update the content to reﬂect new features or changes
Don't
• Don't overwhelm the customer with too much technical detail
• Avoid using marketing language or making direct comparisons to competitors
• Don't assume prior knowledge of AWS services or cloud computing concepts
• Avoid long blocks of text without breaks or subheadings
• Don't include information that quickly becomes outdated (for example, speciﬁc pricing)
Service and feature overview
## 340
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 350 -->

AWS Content Design System
## Examples
[Need to add]
Additional resources
[Need to add]
Reference patterns
Use a reference pattern when customers need comprehensive information presented with little
context. Customers use reference topics to quickly look up information, so the information is often
structured using tables and lists.
To chose the correct pattern, review the purpose and goal for each pattern:
## Pattern
## Purpose
## Goal
CLI
command
Information about command line interface
commands, syntax, parameters, and usage
examples
Understand the options available for
a CLI command
CloudForm
ation
resource
Information about CloudFormation resource
types, properties, return values, and
examples for infrastructure as code
Understand how to deﬁne and
conﬁgure a resource in CloudForm
ation templates
## Deprecati
on
notice
Information about deprecated features,
services, or APIs, including timelines,
alternatives, and migration guidance
Understand what is being deprecate
d and how to transition to supported
alternatives
CLI command pattern
Last updated date: 2025-08-05
Last updated by: Logan Schobel
• Purpose statement: CLI command documentation provides customers with comprehensive
information about command line interface commands, their syntax, parameters, and usage
examples.
Reference patterns
## 341
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 351 -->

AWS Content Design System
• Customer need/problem the pattern solves: Our customers need clear, accurate, and
complete reference information about CLI commands to eﬀectively use AWS services through
the command line interface. Customers need to understand command syntax and available
parameters and to see practical examples of how to use commands for common tasks.
## Structure
Pages that use the CLI command template must contain all of the required components.
Required components
• Title: The name of the CLI command as it would appear on the command line (for example,
create-bucket)
• Short description: Detailed explanation of what the command does, what resource it acts upon,
and when to use it
• Contextual paragraph: Explain the expected outcome and context needed for success.
• Syntax: Formal syntax deﬁnition showing the command structure. List any positional arguments,
the required parameters, and then the optional parameters.
• At least one of the following components:
• Positional arguments: Complete list of positional arguments in the correct order with
descriptions.
• Required parameters: Complete list of all required parameters with descriptions, constraints,
and any default values
• Optional parameters: Complete list of all optional parameters with descriptions, constraints,
and any default values.
• Examples: Practical usage examples with explanations. Include both the request and the output
returned by the request.
• Output: The elements returned by the CLI command. Describe each element. If there is no
output, use the following text: There is no output for this command.
• Additional resources: Links to related documentation, tutorials, or resources. Include a link to the
AWS Command Line Interface guide.
Optional components
• Related commands: Links to related CLI commands
CLI command
## 342
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 352 -->

AWS Content Design System
## Guidelines
Apply the guidelines to the CLI command content.
## Do
• For each parameter, include the parameter the both short name and long name if available
• For each parameter, include the expected value type (examples - string or integer)
• For CLI examples, start with simple, common use cases
• For CLI examples, progress to more complex scenarios
• Use consistent, common formatting for command syntax such as square brackets [] for optional
parameters and pipes | for "or" conditions
• Use mono-space font for command names, parameters, and code examples
• Include complete command examples that can be copied and used directly
• Use clear placeholder names for replaceable values (for example, <bucket-name>)
Don't
• Don't use vague descriptions for commands or parameters
• Don't use technical jargon
• Don't assume advanced knowledge of the service
• Don't use screenshots instead of text for command examples
• Don't refer to replaceable values by their formatting
• Don't include incomplete command examples
## Examples
Additional resources
• AWS CLI Command Reference
• AWS Command Line Interface User Guide
CloudFormation resource reference pattern
Last updated date: 2025-11-10
CloudFormation resource
## 343
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 353 -->

AWS Content Design System
Last updated by: Jim Eagan
• Purpose statement: CloudFormation resource reference documentation provides detailed
information about individual CloudFormation resources and their properties, including
syntax, parameters, return values, and examples, to help developers deﬁne and manage AWS
infrastructure as code.
• Customer need/problem this solves: Developers and infrastructure engineers need clear,
comprehensive CloudFormation resource documentation to understand how to deﬁne AWS
resources in templates, conﬁgure properties correctly, troubleshoot issues, and implement
infrastructure-as-code best practices.
## Structure
Pages that use the CloudFormation resource reference template must contain all of the required
components.
Required components
• Resource type: Must follow AWS::Service::ResourceType naming convention (for example,
AWS::Lambda::Function)
• Short description: A single, concise sentence (maximum 200 characters) that clearly states what
the resource creates or manages
• Detailed description: Explanation of what the resource creates or manages in AWS, including
primary use cases, scenarios, behavioral characteristics, limitations, or dependencies (100-2000
characters)
• Syntax section: Must include both JSON and YAML CloudFormation syntax examples showing
how to declare the resource in a template
• Properties section: Must document all resource properties in alphabetical order, with required/
optional status, type, and update behavior for each property
• Return values section: Must document the Ref return value (the primaryIdentiﬁer from
the CloudFormation Resource Provider Schema) and all available Fn::GetAtt attributes with
descriptions and example return values
Recommended components
• Examples section: At least one complete, working example demonstrating a straightforward
"getting started" conﬁguration in both JSON and YAML formats
CloudFormation resource
## 344
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 354 -->

AWS Content Design System
• Considerations section: Important behavioral notes, limitations, or special considerations users
should know about
• See also section: Links to related CloudFormation resources, API operations, and documentation
Conditional components
• Update behaviors section: Required when one or more properties cause replacement or
interruption (not "No interruption") during updates, to provide a quick reference summary
• Dependencies section: Required when the resource has dependencies on other resources or
services to function properly
## Guidelines
Apply the guidelines to CloudFormation resource reference content.
## Do
• Follow CloudFormation-speciﬁc formatting conventions: Use proper CloudFormation resource
type naming (AWS::Service::ResourceType) when referring to resources in template syntax,
deﬁnitions, or examples, but use general or descriptive terms in explanatory text (for example,
"In the AWS::Lambda::Function resource, the Handler property..." vs. "Each Lambda function
needs a handler...")
• Include both JSON and YAML syntax examples for all code samples
• Document all properties with required/optional status, type, and update behavior
• List properties in alphabetical order for easy reference
• Provide clear property descriptions with constraints and valid values
• Use consistent formatting for property constraints: Start with the Type (for example, "Array of
strings", "String", "Integer"), then specify array constraints ("Array members: Minimum number of
X items. Maximum number of Y items.") and length constraints ("Length constraints: Minimum
length of X. Maximum length of Y.")
• Link to complex property types when they have their own reference pages
• Document the primaryIdentiﬁer from the CloudFormation Resource Provider Schema (Uluru) that
the Ref function returns
• List all available Fn::GetAtt attributes with realistic example return values
• Use realistic property values and resource names in examples
CloudFormation resource
## 345
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 355 -->

AWS Content Design System
• Include comments or descriptions explaining each example's purpose
• Show common use cases and conﬁgurations in examples
Don't
• Don't omit any of the required sections speciﬁed in this pattern
• Don't use inconsistent formatting for similar elements across resources
• Don't provide incomplete or non-functional examples
• Don't skip documenting update behaviors for properties
• Don't use placeholder values without explaining what they represent
• Don't duplicate information that's already covered in general CloudFormation documentation
• Don't create resource references that don't follow the consistent structure deﬁned in this pattern
## Examples
• AWS::Lambda::Function
• AWS::S3::Bucket
Additional resources
• CloudFormation Template Reference
• CloudFormation User Guide
• AWS resource and property types reference
• CloudFormation intrinsic functions
Deprecation notice pattern
Last updated date: 2025-11-07
Last updated by: Jim Eagan
• Purpose statement: Deprecation notices inform customers about AWS services, service
features, or APIs that are being discontinued, providing clear timelines, migration guidance, and
alternative solutions to ensure smooth transitions. This pattern supports diﬀerent deprecation
stages from maintenance mode to full service termination.
Deprecation notice
## 346
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 356 -->

AWS Content Design System
• Customer need/problem this solves: Our customers need advance notice when AWS services,
service features, or APIs are being deprecated so they can plan migrations, update their
applications, and avoid service disruptions. They require clear timelines, alternative solutions,
and actionable guidance to transition successfully. The notice format should vary based on the
deprecation stage and impact level.
Deprecation stages
Deprecation notices use diﬀerent formats based on the stage of deprecation:
• Maintenance mode: Service no longer accepts new customers but existing customers can
continue using it
• Sunset announced: Service termination date has been announced and customers need to
migrate
• End of support: Service is no longer available and customers must use alternatives
## Structure
Pages that use the deprecation notice template must contain all of the required components.
Required components
• Deprecation stage: Identiﬁes which stage of deprecation (maintenance mode, sunset announced,
or end of support) to determine alert format and content requirements
• Service name: Name of the service, service feature, or API being deprecated (maximum 50
characters)
• Key date: Most critical date such as new customer cutoﬀ, end of support, or service termination
(maximum 50 characters)
• Impact summary: Brief explanation of what happens to existing customers and when (maximum
300 characters)
• Alert box: Standardized alert format appropriate for the deprecation stage, concise and
scannable (under 200 characters). Use "Warning" for service termination, standard tone for
maintenance mode
Recommended components
• Announcement date: Date when deprecation was announced (maximum 50 characters)
Deprecation notice
## 347
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 357 -->

AWS Content Design System
• Recommended alternatives: Alternative services or approaches with structured details including
name, description, use case, migration summary, and documentation links
• Support resources: Contact information and support channels (maximum 500 characters)
Conditional components
• Custom alert message: Custom alert message only if standard formats don't apply (maximum
200 characters). Use sparingly
• New customer cutoﬀ date: Date when new customers can no longer sign up, required for
maintenance mode (maximum 50 characters)
• Service termination date: Date when the service will be completely unavailable, required for
sunset/end of support stages (maximum 50 characters)
• Migration guidance: Step-by-step guidance or links to migration resources, required for sunset
stage (maximum 2000 characters)
• Technical considerations: Technical details that may aﬀect customer implementations
(maximum 1500 characters)
• Cost implications: Information about how deprecation aﬀects customer costs (maximum 1000
characters)
## Guidelines
Apply the guidelines to deprecation notice content.
## Do
• Use the standardized alert format for the appropriate deprecation stage
• Lead with the most critical information (what, when, impact)
• Provide actionable next steps immediately after the alert
• Include links to alternative services and migration documentation
• Be transparent about the reasons for deprecation when appropriate
• Update the notice regularly as deprecation progresses
• Use empathetic tone that acknowledges customer impact
• Provide multiple ways for customers to get help (documentation, support, forums)
• Structure content with clear hierarchy: Alert  → Impact  → Actions  → Details
Deprecation notice
## 348
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 358 -->

AWS Content Design System
• Provide speciﬁc dates for all deprecation milestones
• Focus maintenance mode notices on new customer restrictions
• Include links to detailed migration guidance in sunset notices
Don't
• Don't create custom alert messages unless standard formats don't apply
• Don't use vague timelines like "soon" or "in the future"
• Don't assume customers understand the technical implications
• Don't leave customers without guidance on next steps when alternatives are available
• Don't minimize the impact on customers
• Don't use overly technical language in alert boxes
• Don't forget to update related documentation and remove deprecated references
• Don't provide deprecation notices without suﬃcient advance warning
• Don't include detailed migration steps in the alert box
## Examples
• AWS Proton End of Support
• Amazon FinSpace End of Support
• Amazon CodeCatalyst Migration
Additional resources
• AWS Service Terms
Task-based patterns
Use a task-based pattern when customers need to follow steps to complete a job-to-be-done
(JTBD).
To chose the correct pattern, review the purpose and goal for each pattern:
Task-based patterns
## 349
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 359 -->

AWS Content Design System
## Pattern
## Purpose
## Goal
## Getting
started
Set up an AWS service or feature with a
series of sequential steps
Use a service or feature
Procedure Accomplish a task (job-to-be-done (JTBD))
using a series of action-oriented, sequential
steps
Complete a task
## Troublesh
ooting
Identify, diagnose, and resolve problems
Solve a problem
## Tutorial
Help customers to use AWS services with
content that don’t require prior knowledge
beyond what’s presented in the tutorial itself
Gain knowledge through a hands-on
approach
Getting started pattern
Last updated date: 2025-05-01
Last updated by: Logan Schobel
• Purpose statement: Create a getting started page for an AWS service or a feature when there
are a series of sequential steps customers must take to set up the service or feature. When a
getting started topic is complete, the customer must be able to use the service or feature.
• Customer need/problem the pattern solves: Give customers clear setup instructions that
include AWS best practices and that leave them with a solid foundation to build on.
## Structure
Pages that use the getting started template must contain all of the required components.
Required components
• Title: Clear, action-oriented title. Try to avoid “Getting started with …”
• Short description: Summarize the what the customer is doing and why they're doing it
• Contextual paragraph: Explain the expected outcome and any additional context needed to be
successful with the task
Getting started
## 350
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 360 -->

AWS Content Design System
• Time to complete
• Cost to complete
• Steps: Numbered, sequential steps with action-oriented language
• Next steps
Optional components
• Alternative title
• Prerequisites: Required materials, system requirements, and prior steps
• Code examples
• Media (images, video)
• Troubleshooting: Common issues and solutions
• Related topics
Conditional components
• Decision table: Add if you have multiple getting started topics
## Guidelines
Apply the guidelines to the getting started content.
## Do
• Use the best practices for your service or feature
• Use the latest security guidance
• Include detailed content about the expected outcome
• Include cost information if any
• Include help for common mis-steps
• If there are multiple ways to get started, create content that helps customers choose and include
information about any one-way doors and costs
Don’t
• Link out to tasks
Getting started
## 351
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 361 -->

AWS Content Design System
• Leave customer unsure about what to do next
## Examples
Additional resources
Procedure pattern
Last updated date: 2025-04-17
Last updated by: Jim Eagan
• Purpose statement: Procedures demonstrate how to accomplish a speciﬁc customer task or
job-to-be-done (JTBD) using a series of sequential steps. They provide clear, action-oriented
instructions that guide users through completing a process successfully.
• Customer need/problem the pattern solves: Our customers need clear, concise procedures to
help them complete tasks eﬃciently and correctly. They rely on well-structured procedures to
navigate complex processes without errors or confusion.
## Structure
Pages that use the procedure template must contain all of the required components.
Required components
• Title: Clear, action-oriented title
• Short description: Brief statement of what the procedure accomplishes
• Steps: Numbered, sequential steps with action-oriented language
• Expected results: Description of successful completion and veriﬁcation methods
Optional components
• Alternative title
• Prerequisites: Contains required materials, system requirements, and prior steps
• Section title: Describes a set of procedures, such as “Creating a domain.” Use only when multiple
procedures are presented together as part of a customer job
## Procedure
## 352
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 362 -->

AWS Content Design System
• Safety warnings/notes: Important cautions, warnings, or critical information
• Code examples
• Media (images, video)
• Troubleshooting: Common issues and solutions
• Related topics
## Guidelines
Apply the guidelines to the procedure content.
## Do
• Use the best practices for your service or feature
• Use the latest security guidance
• Include prerequisites
• Use ordered (numerical) lists for steps
• Use clear, action-oriented language in steps
• Include one action per step
• Start with the where, then the what (for example: “In the General purpose buckets tab, choose
Create bucket.”)
• Limit steps to 5-7 per procedure
• Organize steps in logical ﬂow
• Provide expected results after key steps
• Add safety warnings when applicable
• Provide troubleshooting guidance for common issues
• Use screenshots sparingly
Don’t
• Skip important prerequisites
• Combine multiple actions in a single step
• Omit expected results
## Procedure
## 353
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 363 -->

AWS Content Design System
## Examples
Additional resources
## • Procedures
• Parallel steps in procedures
• Apply correct procedure style
Troubleshooting pattern
Last updated date: 2025-04-17
Last updated by: Jim Eagan
• Purpose statement: Troubleshooting content helps customers identify, diagnose, and resolve
problems they encounter when using a service. Troubleshooting guides customers through
resolving speciﬁc issues, providing step-by-step instructions along with additional context about
error conditions and prevention strategies.
• Customer need/problem the pattern solves: Our customers need clear, actionable
troubleshooting content to quickly resolve issues that block their progress. They need to
understand what caused the problem and how to ﬁx it eﬃciently to minimize downtime and
frustration.
## Structure
Pages that use the troubleshooting template must contain all of the required components.
Required components
• Section title: Describes a set of troubleshooting topics, such as "Troubleshooting Amazon EC2
connectivity issues"
• Short description: Brief overview of the kinds of errors and problems the topic addresses
• Error/issue title: Exact error message or clear description of the problem
• Common cause: Explanation of what typically causes the problem and any background
information to help customers understand the underlying issues
• Resolution: Step-by-step instructions to resolve the issue
## Troubleshooting
## 354
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 364 -->

AWS Content Design System
Optional components
• Prevention: Guidance on how to avoid the issue in the future
• Code examples
• Media (images, video)
• Related topics
## Guidelines
Apply the guidelines to the troubleshooting content.
## Do
• Use the best practices for your service or feature
• Use the latest security guidance
• Use exact error messages or clear problem descriptions as titles
• Explain the cause of the issue in plain language
• Use ordered (numerical) lists for resolution steps
• Include one action per step
• Provide expected results after key steps
• Include code snippets or commands when applicable
• Link to related troubleshooting topics when relevant
• Include prevention guidance when possible
• Use screenshots sparingly and only when they add value
Don’t
• Use vague problem descriptions
• Provide resolution steps without context
• Use technical jargon without explanation
• Mix troubleshooting content with reference material
## Examples
• Troubleshooting Amazon ECR error messages
## Troubleshooting
## 355
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 365 -->

AWS Content Design System
Additional resources
• the section called “Procedure”
Tutorial pattern
Last updated date: 2025-17-10
Last updated by: Kavya Parthasarathy
• Purpose statement: Tutorials are learning-focused content that helps customers use AWS
services. They break complex tasks, often series of tasks that must be completed in sequence,
into digestible steps. Tutorials don’t require prior knowledge beyond what’s presented in the
tutorial itself.
• Customer need/problem the pattern solves: Tutorials help customers build conﬁdence in using
AWS services through practical, hands-on experience.
## Usage
Tutorials are provided to customers in technical documentation. In this context, the pace is self-
directed. Customers may read a tutorial ﬁrst and implement later, or implement as they follow the
tutorial. Steps can be completed in a sandbox or a production environment.
Within the AWS console, procedures are shown inside of a UI experience called “Onboarding
tutorials.” Although this experience is branded as tutorials, the content should follow the
procedure content pattern.
## Structure
Pages that use the tutorial template must contain all of the required components.
Required components
• Title: Clear, action-oriented title containing the word "Tutorial"
• Overview: Summarizes the customer goal/learning objectives
• Time to complete
• Cost to complete
## Tutorial
## 356
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 366 -->

AWS Content Design System
## • Prerequisites
• Expected outcomes: For example, running a service use case, sandbox deployment
• Steps: Numbered, sequential steps with action-oriented language
• Cleanup steps: If deploying resources, you must include cleanup steps to help customers avoid
charges
Recommended components
• Code examples
• Troubleshooting: Common issues and solutions
• Next steps
Optional components
• API references
• Media (images, video)
• Best practices: Tips and tricks for successful completion
## Guidelines
Apply the guidelines to the tutorial content.
## Do
• Focus on practical, real-world scenarios
• Explain cost information and cleanup guidance
• Include only information needed for the speciﬁc objective of the tutorial
• Include a brief Overview that integrates customer goals and learning objectives into a cohesive
summary
• A single tutorial can contain multiple related tasks as long as they are tied to one discrete
outcome. For complex tasks, provide brief context on what the task will accomplish before the
set of steps. Limit the steps within each task to 5-7 steps when possible. Organize steps in logical
ﬂow. For processes that take additional time, include the typical time for process completion
• Start with the where, then the what (for example: “In the General purpose buckets tab, choose
Create bucket.”)
## Tutorial
## 357
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 367 -->

AWS Content Design System
• Format troubleshooting items as bullet points with bold issue names
Don’t
• Assume knowledge beyond prerequisites
• Skip steps that seem "obvious"
• Mix tutorial content with reference material
• Provide information in an FAQ instead of within the relevant section of the tutorial
## Examples
• Host a static website
Additional resources
• AWS tutorial past insights research report
Content components
Brief overview paragraph explaining this category's purpose and importance
What's in this section
• Bulleted list summarizing key subcategories
• 1-2 sentences describing each (where needed)
## Guidelines
Quick guidance on how to use this section of the content design system
Featured resources
Highlight 2-3 most commonly used pages in this category
## Related Resources
Links to related content in other sections
Content components
## 358
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 368 -->

AWS Content Design System
Text components
Headings and titles
Last updated date: May 1, 2025
Last updated by: Jenna Messer
## Overview
Titles and headers are critical navigational and organizational elements that help customers
quickly understand and locate content. They serve as both structural elements and key entry points
for search engine optimization (SEO).
Primary scenarios
• Topic titles for documentation pages
• Section headers within topics
• Navigation elements in tables of contents (TOC)
• Guide and reference titles
• Procedure titles
## Structure
Required elements
Topic title
• Must be unique and descriptive
• 50-60 characters recommended for optimal comprehension and SEO
• Uses sentence case
• Includes service name where appropriate
Section headers
• Must have explanatory text between headers (no stacking)
• Uses consistent grammatical structure within sections
• Follows topic hierarchy (H1, H2, H3, etc.)
Speciﬁc formatting requirements:
Text components
## 359
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 369 -->

AWS Content Design System
• Topic titles: Sentence case
• Guide/Reference titles: Title case
• TOC entries: Matches corresponding topic titles unless speciﬁed otherwise
Optional elements
Separate TOC title
• Shorter version of topic title
• Excludes service name when context is clear
• Used when full topic title is too long for navigation
Subtitle or secondary header
• Provides additional context when needed
• Must not duplicate primary title information
## Features
## Title Variants
## Conceptual Topics
• Structure: Noun-based phrase + preposition + service name
• Example: "Access control in Amazon S3"
## Procedural Topics
• Structure: Present participle phrase + preposition + service name
• Example: "Creating a bucket in Amazon S3"
## Tutorial Topics
• Structure: "Tutorial: " + present participle phrase
• Example: "Tutorial: Getting started with S3 Express One Zone"
## Guidelines
## Do
• Use words that match the customer scenario
• Place critical information at the beginning of the title
Text components
## 360
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 370 -->

AWS Content Design System
• Maintain consistent phrasing within a service
• Use the most recognized form of terms/acronyms
Don't
• Begin titles with articles (a, an, the)
• Use diﬃcult-to-localize phrases
• Include parenthetical acronyms
• Create generic or vague titles
• Exceed 70 characters for SEO optimization
Additional resources
• [Need to add]
Related components/patterns
• SEO guidelines
• Navigation patterns
• Service naming conventions
## Lists
Last updated date: 04/28/2025
Last updated by: Kavya Parthasarathy
## Overview
• The purpose of a list is to itemize data relating to a topic or to present conceptually similar
information in a format that's scannable. Lists shouldn't replace normal text or the structured
presentation of tables.
• The following are common list types used in AWS documentation:
• Itemized (bulleted) lists
• Ordered (numbered) lists
• Topic-comment (topcom) lists
Text components
## 361
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 371 -->

AWS Content Design System
• Variable (termdef) lists
• Automatic (topic) lists
## Structure
Required elements
## Titles
• Titles are required for automatically generated lists (topic lists).
• Titles are highly recommended for procedures.
Introductory sentences
• Introductory sentences are required for lists.
• Introductory sentences should be complete sentences.
• Introductory sentences should end with a period if the list has a title.
• Introductory sentences should end with a colon if the list does not have a title.
## Punctuation
• If the list is basic, you don't need end punctuation for the list items.
• If the list has a mixture of phrases and sentences, punctuate each list item.
• Capitalize the ﬁrst word of each item.
Optional elements
• Titles are optional for most lists. If used, the title comes after an introductory sentence.
## Features
The following are guidelines for list variants.
Itemized (bulleted) lists
Itemized lists are displayed with bullets. Use an itemized list when presenting a series of items that
don't need to be ordered.
• Avoid titles for itemized lists.
Text components
## 362
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 372 -->

AWS Content Design System
• If each list item has three pieces of information to convey, consider the topic-comment (topcom)
list style.
Example itemized list:
Each error includes the following elements:
• A Code that identiﬁes the type of error
• A Detail that might give additional details about the error
• A Message that describes the error condition
• A Type that identiﬁes whether the error was from a receiver or sender
Ordered (numbered) lists
Use an ordered, or numbered, list when it is important to describe the items in sequence but not
for steps that a reader must complete.
To describe steps that a reader must complete, use a procedure instead. A procedure is a speciﬁc
type of ordered list with unique considerations, guidelines, and XML tags. The procedure guidelines
are described in a Procedures topic. For information about the XML tags to use in procedures, see
Add procedures.
• Avoid titles for ordered lists. If you use a title, avoid starting it with "To" because that is the
standard for procedures.
• Introduce the list with a sentence that ends with a colon.
• Use numbers or letters. Numbers are preferred; only use letters to avoid confusion. For more
information, see Add lists.
Example ordered list
You can attach an identity-based permissions policy to an IAM role to grant cross-account
permissions, as described in the following example:
1. Account A administrator creates an IAM role and attaches a permissions policy to the role. The
policy grants permissions on resources in account A.
2. Account A administrator attaches a trust policy to the role. The policy identiﬁes account B as the
principal who can assume the role.
Text components
## 363
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 373 -->

AWS Content Design System
3. Account B administrator can then delegate permissions to assume the role to any users in
account B. This allows users in account B to create or access resources in account A.
Variable (termdef) lists
Use a variable, or termdef, list when you have a short item that is followed by a deﬁnition or
description. For information about how to apply tags for this style, see Add lists.
• Use a variable list when you have a list that requires a brief explanation for each item, and each
item has two pieces: term and deﬁnition (or description).
• If you have a short basic list, and each item has three pieces (that is, term, short deﬁnition or
description, and further explanation), consider using a topic-comment list instead.
• A title is optional. Include a title when you need the list to stand out signiﬁcantly from the ﬂow.
• Use a variable list for nesting, such as for nested UI labels. For example, you can create multi-
level lists with a combination of termdef lists and itemized lists, as shown next.
Example variable (termdef) list
The Add Stack page has the following basic options.
Stack name
(Required) A name that is used to identify the stack in the AWS OpsWorks Stacks console. The
name does not need to be unique. AWS OpsWorks Stacks also generates a stack ID, which is a
GUID that uniquely identiﬁes the stack. For example, with AWS CLI commands such as update-
stack, you use the stack ID to identify the particular stack. After you have created a stack, you
can ﬁnd its ID by choosing Stack in the navigation pane and then choosing Stack Settings. The
ID is labelled OpsWorks ID.
## Region
(Required) The AWS Region where the instances will be launched.
VPC
(Optional) The ID of the VPC that the stack is to be launched into. All instances will be launched
into this VPC, and you cannot change the ID later.
• If your account supports EC2 Classic, you can specify No VPC (the default value) if you don't
want to use a VPC. For more information about EC2 Classic, see Supported Platforms.
Text components
## 364
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 374 -->

AWS Content Design System
• If your account does not support EC2 Classic, you must specify a VPC. The default setting
is Default VPC, which combines the ease of use of EC2 Classic with the beneﬁts of VPC
networking features. If you want to run your stack in a regular VPC, you must create it by
using the VPC console, API, or CLI. For more information about how to create a VPC for an
AWS OpsWorks Stacks stack, see Running a Stack in a VPC. For general information, see
Amazon Virtual Private Cloud.
Automatic (topic) lists
Use automatic (topic) lists to provide links to child sections, without commentary or explanation.
You can use them in the parent chapter, section, or subsection after the introductory paragraphs.
The default title for the list is "Topics" but the heading can be customized for improved readability.
The default depth of the list is one level, but you can go deeper if the level of detail is helpful to
your reader. For information about creating and customizing these lists, see Add automatic lists.
• Introduce them with a complete sentence with a period at the end.
• Use the default heading for automatic (topic) lists when possible.
• Customize the heading, if needed, to clarify context for your reader.
• Be aware that the more levels of depth you include in your list, the more vertical space is taken
up by it.
Automatic (topic) lists examples
The following topics contain AWS style examples for automatic (topic) lists.
## • Example 1
## • Example 2
• Example 3 (list of links to subsections within a subsection with custom heading text)
• Example 4 (section within a topic)
Formal paragraphs
Use formal paragraphs when you want to oﬀset a paragraph from the text by using a title. Avoid
using a series of formal paragraphs. A termdef list often works well, is more semantically correct
when documenting a series, and works well with multi-level lists. For more information, see
Variable (termdef) lists.
Text components
## 365
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 375 -->

AWS Content Design System
Follow these guidelines for formal paragraphs:
• The title of the formal paragraph is bold.
• The title begins with a capital letter.
• The paragraph starts with a capital letter.
• Don't use end punctuation for the title of a formal paragraph.
## Guidelines
## Do
• Make lists parallel in content and structure. Don't mix single words with phrases, don't start some
phrases with a noun and others with a verb, and don't mix verb forms.
• Present the items in alphabetical order if the order of items is arbitrary.
• Punctuate list items consistently. If at least one item in a list requires a period, use a period for all
items in that list.
Don't
• Use admonitions within lists. Use them before or after if possible.
Additional resources
Related components/patterns
• Procedures: For procedure guidelines, see Procedures. For information about how to apply tags
for the procedure style, see Add procedures.
Support channels
• Content Patterns team
Code blocks
Last updated date: 4/29/2025
Last updated by: Julie MacAller
Text components
## 366
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 376 -->

AWS Content Design System
## Overview
• Code blocks are standalone content components that present computer code in a distinctive
way that makes it easy for customers to identify and locate code. Customers are always on the
lookout for code examples and snippets that they can use in their own projects. Code blocks
support syntax highlighting for programming and conﬁguration languages. Code blocks can
optionally include line numbers to help with navigation, support scrolling, and the ability to copy
the code so that customers can paste it into their own code.
• Use code blocks in code examples, command-line interface (CLI) examples, code snippets,
CloudFormation example templates, and IAM example policies. You can include a code block
in other content components, including tabbed interfaces, but be careful about including code
blocks in tables. The column size can make the code diﬃcult to read.
## Structure
Required elements
• None. Code block is a standalone component.
Optional elements
• None.
## Features
Each of the following is optional, but can improve the customer experience depending on the
situation.
• The copy/paste control helps customers copy the code and paste it into their own development
environment.
• Line numbers help customers navigate the code.
• Syntax highlighting helps customers understand the code.
## Guidelines
## Do
• # Use a code block for all code.
Text components
## 367
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 377 -->

AWS Content Design System
• # Use clear placeholder names for replaceable values, such as my-region or my-bucket.
• # Identify replaceable values clearly.
Don't
• # Use a screenshot to show code.
• # Don't refer to replaceable values by how they are formatted. Formatting can change.
## Examples
• TBD
Additional resources
• Code example
• Code snippet
• IAM example policy
• Support channels
Notes and alerts
Last updated date: April 22, 2025
Last updated by: Jim Eagan
## Overview
• Notes and alerts are special messages that call attention to important information in AWS
documentation and interfaces. They range from helpful tips to critical warnings about potential
data loss.
Primary scenarios
• Highlighting important information that can't be eﬀectively presented in the main text
• Warning users about potentially harmful actions
• Providing essential task completion information
Text components
## 368
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 378 -->

AWS Content Design System
• Notifying users about errors or system status
## Structure
Required elements
• Message type indicator (Tip, Note, Important, Warning)
• Clear, concise heading (except for success messages)
• Body text explaining the situation and required actions
• Proper formatting and visual treatment
• Ending punctuation for complete sentences
Optional elements
• Links to additional information
• Related error codes (when helpful for troubleshooting)
• Next steps or recommended actions
## Features
## Tip
• Presents optional shortcuts or best practices
• Uses positive, helpful tone
• Doesn't contain essential information
## Note
• Highlights special interest information
• No risk of physical harm if ignored
• Often contains version-speciﬁc details or limitations
## Important
• Contains essential task completion information
• Highlights signiﬁcant consequences
Text components
## 369
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 379 -->

AWS Content Design System
• Must be read to complete task successfully
## Warning
• Indicates potential for irreversible damage
• Describes consequences if ignored
• Must appear before related step
## Guidelines
## Do
• Keep messages brief and actionable
• Use everyday language
• Include clear next steps when needed
• Place warnings before aﬀected steps
• Use sentence case for headings
• Include complete sentences with proper punctuation
• Link to relevant documentation when appropriate
Don't
• Stack multiple notes together
• Include notes in tables, lists, or procedures
• Use please or sorry
• Use exclamation points
• Blame the user
• Use technical jargon or cryptic codes
• Use humor or casual language in serious situations
## Examples
## Tip
• "If you launched your instance from an Amazon Linux AMI, the default username is ec2-user."
Text components
## 370
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 380 -->

AWS Content Design System
## Note
• "Amazon EC2 uses SSH keys, Windows passwords, and security groups to control instance access.
IAM doesn't control access to speciﬁc instances."
## Important
• "Remember, you're billed for each hour or partial hour that your instance runs, even when idle.
Charges stop when the instance status changes to shutting down or terminated."
## Warning
• "Deleting this dataset will permanently remove all associated data. This action cannot be
undone."
Additional resources
Related components/patterns
• Troubleshooting pattern
Support channels
• TBD
Links and cross-references
Last updated date: April 25, 2025
Last updated by: Jim Eagan
## Overview
• Links and cross-references are interactive elements that help users navigate between related
content. They create connections between pieces of content and guide users to additional
relevant information.
Primary scenarios
Text components
## 371
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 381 -->

AWS Content Design System
• Referencing content within the same topic
• Connecting to other AWS service documentation
• Linking to external resources
• Providing paths to downloadable content
• Referencing AWS blogs, whitepapers, and re:Post entries
## Structure
Required elements
• Link text that matches the destination title or clearly describes the destination
• Proper introductory phrases for formal cross-references (e.g., "For more information about")
• Standard link formatting without additional styling
• Direct links to relevant sections using anchor tags when applicable
• For same-page references: No link when target is less than a screen length away; link required
when target is more than a screen length away
Optional elements
• External link icon (for links that navigate outside the current application)
• Use of "See <link text>" where space is limited (for example, in a table)
• Multiple links to the same content on very long pages
## Features
Formal cross-references
• Preferred style for most AWS documentation
• Includes introductory text like "For information about" or "For instructions on"
• Provides context about the linked content
Embedded links
• Integrated naturally into sentences
• Used in tables or space-constrained elements
Text components
## 372
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 382 -->

AWS Content Design System
• Must have clear context from surrounding text
## Guidelines
## Do
• Use links judiciously - include necessary links but avoid overwhelming users with too many
options
• Use descriptive link text that matches destination titles
• Link only the ﬁrst instance on a page (except for very long pages)
• Use "following," "later," "preceding," "previous," or "earlier" for same-page references
• Include the term "download" in introductory text for ﬁle downloads
• Link directly to speciﬁc sections when possible
• Link to speciﬁc service consoles rather than the top-level AWS Management Console
• Consider deﬁning straightforward terms in content instead of linking
• Use links for content subject to change (procedures, pricing, regional oﬀerings)
• Use links for complex topics that can't be quickly summarized
Don't
• Use "click here" or "here" as link text
• Add extra formatting to hyperlinks
• Use "above" or "below" for same-page references
• Use "go to" in link instructions
• Link to unreliable external resources or third-party URL shorteners
• Link to answers from generative AI or chatbots
• Create too many links, which could cause link fatigue
## Examples
Formal cross-reference
• For more information about managing your Amazon S3 resources, see Identity and Access
Management for Amazon S3.
Text components
## 373
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 383 -->

AWS Content Design System
Embedded link
• Create IAM users for everyone who needs to access AWS OpsWorks, and then import those users
into AWS OpsWorks.
Console link
• Sign in to the AWS Management Console and open the Amazon RDS console at https://
console.aws.amazon.com/rds/.
Additional resources
Related components/patterns:
• Navigation (to come in June 2025)
• Link component in AWS Design System
Support channels
• Content Patterns team
Text components
## 374
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 384 -->

AWS Content Design System
AWS Legal and security guidelines for content
All content must conform to the requirements in Messaging Dos and Don’ts on the AWS Legal
Pathﬁnder website. If the content doesn't conform to these requirements, you must have it
reviewed and approved by AWS Legal. If you're a vendor or contractor, please consult with your
AWS manager.
## Topics
• Copyrights and trademarks
• Legal requirements for images
• Trademark requirements for AWS and service names
• Third-party brand names
• Incorporating third-party content
• Speciﬁc legal requirements
• Safeguarding customer information
• Writing about security
• Linking to external resources
• Security review
• Fictitious content library
## • Names
• Regions and partitions
• Security content requirements
• Working with third-party content
Copyrights and trademarks
For more information about copyrights and trademarks for both AWS and third parties, see
Messaging Dos and Don’ts on the AWS Legal Pathﬁnder website. For more information about third-
party content, see Working with third-party content.
Copyrights and trademarks
## 375
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 385 -->

AWS Content Design System
Legal requirements for images
As a general rule, don't use third-party images, such as graphics, logos, or stock images. For more
information, see Use of logos and media on the AWS Legal Pathﬁnder website and .
Trademark requirements for AWS and service names
Be cautious about distinguishing between AWS the service and AWS the corporate entity. For more
information, see Messaging Dos and Don’ts on the AWS Legal Pathﬁnder website.
Some service names require Amazon or AWS for all uses or prohibit certain short forms of the
service name. For more information, see AWS oﬀering names. Don't modify service names or use
AWS or service names with puncuation unless directed to do so in the Usage dictionary.
Trademark requirements for China Regions
These are speciﬁc rules for referring to AWS and AWS services in the China Regions. For more
information, see AWS China, its Regions, and its customers in the Legal Messaging Dos and Don'ts
guidelines.
Third-party brand names
AWS content often refers to third-party brand names, such as Apache Cassandra, Docker, Hive,
Hugging Face, Llama, Meta, Microsoft, Parquet, and Spark. Always check third-party names against
the brand's naming guidelines.
## Do
• For service documentation, use nolog tags () to help prevent localization.
• To help prevent translation and localization of third-party brand names in service
documentation, see Prepare your content for localization.
Don't
• Don't localize third-party brand names.
• Don't alter third-party brand names.
• Don't make names possessive (by adding apostrophes).
• Don't change singular and plural names (by adding or removing s).
Legal requirements for images
## 376
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 386 -->

AWS Content Design System
• Don't change case (by changing capitalization).
• Don't add hyphens to names.
For more information about third-party names, see Guidance from AWS Legal in the Terminology
Management Framework Wiki. See also Messaging Dos and Don’ts on the AWS Legal Pathﬁnder
website.
Incorporating third-party content
Third-party content is content created and published by a third-party. Original content authored by
AWS that describes a third-party's product, service, or features isn't considered third-party content
because AWS is the author. We recommend that you err on the side of caution when including
third-party content in your AWS documentation. If you must include third-party content in your
documentation, follow these guidelines:
## Do
• Ask yourself "Does this content provide a signiﬁcant beneﬁt to AWS customers in a way that we
can't provide in our documentation?" Consider this question carefully.
• Link to the third-party content.
• Make sure that you have the written persmission to use third-party content. Some third-party
content providers and ISVs require signed legal agreements.
• Make sure that the third-party content provider or ISV understands that the content might be
rewritten, edited, andu pdated by AWS. As with all documentation, you're responsible for the
content's accuracy, format, publication, and updating.
• Create your own original content instead, including information that describes a third-party's
product, service, or features.
Don't
• Don't copy, reqwrite, or repurpose content published by a third-party content provider. This is
plagiarism.
Speciﬁc legal requirements
See the Usage dictionary for legal requirements that are speciﬁc to speciﬁc words and phrases.
Incorporating third-party content
## 377
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 387 -->

AWS Content Design System
Safeguarding customer information
For information about safeguarding customer information or other concerns, see the AWS Legal
Pathﬁnder website. See also Personal Identiﬁable Information (PII) Compliance Guidance for Global
Learning Content.
Writing about security
When writing about security, see the AWS Security Messaging Guidelines on the Growth Strategies
(Amazon Security) Wiki.
Linking to external resources
If possible, link to an AWS or Amazon owned resource instead of an external website.
## Do
• For code examples, or tools that are hosted on external sites, such as GitHub, link directly to
an AWS owned repository or AWS oﬃcial tool. AppSec has approved these resources for use in
public content.
• Use caution when linking to Wikipedia. Wikipedia doesn’t guarantee the validity of its
information. If no AWS or Amazon owned resource is available, you can link to Wikipedia content
about an established concept, principle, or technology standard. Examples include Confusion
matrix, Classless Inter-Domain Routing, and IEEE 754.
Don't
• Don't link to external websites that a customer might perceive to be unreliable or untrustworthy,
or that pose a security risk.
• Don't link to answers provided by generative AI or chatbots. Generative AI models might use
information that's outdated, incomplete, biased, or incorrect. For more information, download
the AWS Responsible Use of Machine Learning guide.
• Don't link to external websites using third-party services (such as tinyurl.com) to create a
shortened link for the URL.
Safeguarding customer information
## 378
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 388 -->

AWS Content Design System
Security review
For questions about security, or to request a review of your content, see the Security Review
Process Details Wiki.
Fictitious content library
Examples are important tools for making content easier for customers to understand and relate to.
Choose from these examples, which have been curated and approved by the AWS Content Quality,
Legal, and Trademark teams.
## Topics
• API operations
• ARNs
• ASNs
## • Buckets
## • Companies
## • Domains
• ACM servers
## • Hashes
• IP addresses
## • People
• Phone numbers
## • Products
• AWS Region codes
• AWS Region names
• Resource IDs
• Street addresses
• User credentials
API operations
When creating API names, use the recommended verb list. For example:
Security review
## 379
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 389 -->

AWS Content Design System
• CreateResourceName
• DeleteResourceName
• ListResourceName
• StartResourceName
• StopResourceName
• UpdateResourceName
For more information and examples, see the AWS API Standards Wiki.
ARNs
To create a ﬁctitious Amazon Resource Name (ARN), use the base format of the ARN and substitute
in a shared entity for the account ID. The only thing that you need to change is the account
number. For more information about entities, see Shared entities in the AWS Docs Wiki.
Example ARNs
• arn:aws:cloudfront::111122223333:distribution/E1WG1ZNPRXT0D4 (uses entity
ExampleAWSAccountNo1)
• arn:aws:ec2:us-east-1:555555555555:instance/i-b188560f (uses entity
ExampleAWSAccountNo10)
• arn:aws:iam::444455556666:role/Admin (uses entity ExampleAWSAccountNo2)
ASNs
• 64,496 to 64,511 of the 16-bit range
• 65,536 to 65,551 of the 32-bit range
For more information, see Autonomous System (AS) Number Reservation for Documentation Use.
## Buckets
If you need to use an Amazon S3 general purpose bucket name in an example, use one of the
following:
• amzn-s3-demo-bucket
ARNs
## 380
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 390 -->

AWS Content Design System
• amzn-s3-demo-bucket1
• amzn-s3-demo-bucket2
• amzn-s3-demo-bucket3
• amzn-s3-demo-source-bucket
• amzn-s3-demo-destination-bucket
• amzn-s3-demo-source-bucket1
• amzn-s3-demo-destination-bucket1
• amzn-s3-demo-source-bucket2
• amzn-s3-demo-destination-bucket2
• amzn-s3-demo-logging-bucket
• amzn-s3-demo-logging-bucket1
• amzn-s3-demo-logging-bucket2
• amzn-s3-demo-website-bucket
• amzn-s3-demo-website-bucket1
• amzn-s3-demo-website-bucket2
If you need to use an Amazon S3 directory bucket name in an example, use one of the following:
• amzn-s3-demo-bucket--usw2-az1--x-s3
• amzn-s3-demo-bucket1--usw2-az1--x-s3
• amzn-s3-demo-bucket2--usw2-az1--x-s3
• amzn-s3-demo-bucket3--usw2-az1--x-s3
• amzn-s3-demo-source-bucket--usw2-az1--x-s3
• amzn-s3-demo-destination-bucket--usw2-az1--x-s3
• amzn-s3-demo-source-bucket1--usw2-az1--x-s3
• amzn-s3-demo-destination-bucket1--usw2-az1--x-s3
• amzn-s3-demo-source-bucket2--usw2-az1--x-s3
• amzn-s3-demo-destination-bucket2--usw2-az1--x-s3
If you need to use an Amazon S3 table bucket name in an example, use one of the following:
• amzn-s3-demo-table-bucket
## Buckets
## 381
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 391 -->

AWS Content Design System
• amzn-s3-demo-table-bucket1
• amzn-s3-demo-table-bucket2
• amzn-s3-demo-table-bucket3
• amzn-s3-demo-source-table-bucket
• amzn-s3-demo-destination-table-bucket
• amzn-s3-demo-source-table-bucket1
• amzn-s3-demo-destination-table-bucket1
• amzn-s3-demo-source-table-bucket2
• amzn-s3-demo-destination-table-bucket2
If you need to use an Amazon S3 vector bucket name in an example, use one of the following:
• amzn-s3-demo-vector-bucket
• amzn-s3-demo-vector-bucket1
• amzn-s3-demo-vector-bucket2
• amzn-s3-demo-vector-bucket3
• amzn-s3-demo-source-vector-bucket
• amzn-s3-demo-destination-vector-bucket
• amzn-s3-demo-source-vector-bucket1
• amzn-s3-demo-destination-vector-bucket1
• amzn-s3-demo-source-vector-bucket2
• amzn-s3-demo-destination-vector-bucket2
Don’t use awsexamplebucket or examplebucket because these bucket names aren't owned by AWS.
If the preceding ﬁctitious bucket names don't work for a speciﬁc scenario, you can create other
ﬁctitious bucket names by using the reserved preﬁx amzn-s3-demo- at the start of the bucket
name.
You must use this preﬁx for any ﬁctitious bucket names that you create because the reserved preﬁx
forces customers to replace the ﬁctitious bucket name with their own bucket name.
## Buckets
## 382
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 392 -->

AWS Content Design System
## Important
If you're working on service documentation, we strongly recommend using the
corresponding shared content entities for these example buckets. To ﬁnd the relevant
entities, search for "example" in the Entities pane in Oxygen.
## Companies
In examples, you can use the following company names as adjectives describing generic nouns
for types of company. For example, you can use AnyCompany Gas Networks or AnyCompany
Manufacturing.
• AnyAuthority
• AnyCompany
• AnyDepartment
• AnyGovernment
• AnyOrganization
## • Example Authority
## • Example Corp
## • Example Department
## • Example Government
## • Example Organization
Don't use MyCompany, which is registered.
## Domains
• example.com
• example.net
• example.org
• any variation of example.*
• amazondomains.com (AWS owns this domain, which points to the Amazon Route 53 marketing
site.)
## Companies
## 383
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 393 -->

AWS Content Design System
Don't use mydomain.com, which is an actual site.
Don't use amazonregistry.com because it's an Amazon Registry site.
ACM servers
ACM validation domains are composed of a randomized string of 32 characters, a period, and a
second randomized string of 11 characters. The ﬁrst string must contain the word example so that
it doesn't match an operational ACM server domain name.
An underscore (_) can be added in front of the domain name for DNS providers who require it.
• uoc1c1qsw7poexampleewjeno1pte3rw.3ym756xh7yj.acm-validations.aws.
• hc30uowyhpzoexample6jjr5ez4fp5gj.wvmregv6udf.acm-validations.aws.
• cf1z2npwt9vzexample93c1j4xzc92wl.2te3iym6kzr.acm-validations.aws.
• vn0rb8nk9wv3examplewwynrr47qke3u.4md2kvmucqw.acm-validations.aws.
• e0k1r4sii7l8exampleh6fausp0hjzcx.xfvbcprl3a6.acm-validations.aws.
## Hashes
For security, make sure that the string being used to generate a hash is safe for external
publication. Use the hash function's output on the null input.
Avoid referencing MD5 and SHA1 algorithms unless absolutely necessary for interoperability with
an existing system. For more information, see the Amazon Cryptography Standard, speciﬁcally the
Password Hashing Algorithms and Identity Algorithms sections. For more guidance about hash use,
contact AWS Security.
If you need a hash value example and the input doesn’t matter, choose an algorithm-speciﬁc value
from the following list:
• MD5 : d41d8cd98f00b204e9800998ecf8427e
• SHA256 : e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
• SHA384 :
38b060a751ac96384cd9327eb1b1e36a21fdb71114be07434c0cc7bf63f6e1da274edebfe76f65f
• SHA512 :
cf83e1357eefb8bdf1542850d66d8007d620e4050b5715dc83f4a921d36ce9ce47d0d13c5d85f2b
ACM servers
## 384
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 394 -->

AWS Content Design System
Another example follows:
$ python3
Python 3.7.4 (default, Sep 7 2019, 18:27:02)
[Clang 10.0.1 (clang-1001.0.46.4)] on darwin
Type "help", "copyright", "credits" or "license" for more information.

import hashlib
hashlib.md5().hexdigest() 'd41d8cd98f00b204e9800998ecf8427e'
hashlib.sha256().hexdigest()
'e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855'
hashlib.sha384().hexdigest()

'38b060a751ac96384cd9327eb1b1e36a21fdb71114be07434c0cc7bf63f6e1da274edebfe76f65fbd51ad2f14898b
hashlib.sha512().hexdigest()

'cf83e1357eefb8bdf1542850d66d8007d620e4050b5715dc83f4a921d36ce9ce47d0d13c5d85f2b0ff8318d2877ee

IP addresses
When you're providing IP addresses, use numbers that are reserved but that fall within the
protocol's allowed range of addresses.
## Important
• Don't use IP addresses from public IP address ranges as example IP address
values in documentation. A public IP address is assigned to an entity for use and
IP address assignment can change often. For example, don't use a public IP address
123.45.167.89 as a ﬁctitious IP address because this public IP address is assigned to
another company. Use only IP addresses in the recommended ﬁctitious IP address ranges.
• If you specify a single IP address in a given IP range, don’t use the network address
or the broadcast address. The network address is the ﬁrst IP address in an IP range and
is used to identify a network segment. The broadcast address is the last IP address in an
IP range and is used for addressing all hosts in the network at the same time. These two
addresses are reserved. Don’t assign them to network hosts. Use a value from the host
address range.
IP addresses
## 385
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 395 -->

AWS Content Design System
• Public IP addresses – The following addresses are designed for use with the domain names
example.com or example.net. As described in RFC5737, addresses within these blocks don't
legitimately appear on the public internet and can be used without any coordination with IANA
or an internet registry. For more information, see Documentation Address Blocks in RFC5737.
• 192.0.2.0/24 – This block is assigned as TEST-NET-1
IP range details:
Network address: 192.0.2.0
Host address range: 192.0.2.1–192.0.2.254
Broadcast address: 192.0.2.255
Type: Class C, reserved for documentation
• 198.51.100.0/24 – This block is assigned as TEST-NET-2
IP range details:
Network address: 192.0.2.0
Host address range: 198.51.100.1–198.51.100.254
Broadcast address: 198.51.100.255
Type: Class C, reserved for documentation
• 203.0.113.0/24 – This block is assigned as TEST-NET-3
IP range details:
Network address: 203.0.113.0
Host address range: 203.0.113.1–203.0.113.254
Broadcast address: 203.0.113.255
Type: Class C, reserved for documentation
• CIDR ranges – For more information, see Address Delegation in RFC4632.
• Use the basic notation wherever possible: xxx.xxx.xxx.xxx/n. In other words, if the range
ends in .0.0.0, include the zeroes instead of dropping them.
IP addresses
## 386
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 396 -->

AWS Content Design System
• If you must give a speciﬁc sample CIDR range, use one of the following:
## • 10.24.34.0/23
IP range details:
Network address: 10.24.34.0
Host address range: 10.24.34.1–10.24.35.254
Broadcast address: 10.24.35.255
Type: Class A, private
## • 10.24.34.0/24
IP range details:
Network address: 10.24.34.0
Host address range: 10.24.34.1–10.24.34.254
Broadcast address: 10.24.34.255
Type: Class A, private
• Private IP addresses – IANA has reserved the following three blocks of the IP address space
for private internets. So, to use private IP addresses in your content, use examples from these
ranges. For more information, see Private Address Space in RFC1918.
## • 10.0.0.0/8
IP range details:
Network address: 10.0.0.0
Host address range: 10.0.0.1–10.255.255.254
Broadcast address: 10.255.255.255
## • 172.16.0.0/12
IP range details:
Network address: 172.16.0.0
IP addresses
## 387
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 397 -->

AWS Content Design System
Host address range: 172.16.0.1–172.31.255.254
Broadcast address: 172.31.255.255
## • 192.168.0.0/16
IP range details:
Network address: 192.168.0.0
Host address range: 192.168.0.1–192.168.255.254
Broadcast address: 192.168.255.255
• Loopback addresses – We don't recommend using the loopback address. For IPv4, this is
127.0.0.0/8, with 127.0.0.1 being common. For IPv6, the loopback address is ::1.
• IPv6 addresses – IANA has reserved a special IPv6 address range for documentation samples. For
more information, see RFC3849.
• 2001:db8::/32
IP range details:
Network address: 2001:db8::
Host address range: 2001:db8::1–2001:db8:ffff:ffff:ffff:ffff:ffff:fffe
• Using IP addresses in IAM policies
• In IAM policies, if you specify an IP address without the associated routing preﬁx, IAM uses
the default preﬁx value of /32. For example, if you enter IP address 203.0.113.1, IAM uses
203.0.113.1/32.
• For IAM policy examples that use the AWS global condition key aws:SourceIP, mention
somewhere near the example that this condition key can be used only for public IP address
ranges. For more information, see AWS global condition context keys in the IAM User Guide.
## People
The names in this list have been approved for use in AWS content by AWS Legal. Don't attempt to
manufacture other names. For additions or modiﬁcations to names, see AWS Style Guide requests.
For email addresses, any combination of ﬁctitious username and ﬁctitious domain is permitted. For
example, both alejandro_rosalez@example.org and alejandro_rosalez@example.com are OK.
## People
## 388
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 398 -->

AWS Content Design System
## First
## Last
## Username
Typical pronouns
## Alejandro
## Rosalez
alejandro_rosalez
he, they
## Akua
## Mansa
akua_mansa
she, they
## Ana Carolina
## Silva
anacarolina_silva
she, they
## Arnav
## Desai
arnav_desai
he, they
## Carlos
## Salazar
carlos_salazar
he, they
## Diego
## Ramirez
diego_ramirez
he, they
## Efua
## Owusu
efua_owusu
he, they
Gil-dong*
## Hong
gil-dong_hong
he, they
## Jane
## Doe
jane_doe
she, they
Ji-hoon*
## Namgoong
ji-hoon_namgoong
he, they
## John
## Doe
john_doe
he, they
## John
## Stiles
john_stiles
he, they
## Jorge
## Souza
jorge_souza
he, they
## Kwaku
## Mensah
kwaku_mensah
he, they
## Kwesi
## Manu
kwesi_manu
he, they
## Juan*
## Li
juan_li
she, they
## Jie*
## Liu
jie_liu
he, they
## Márcia
## Oliveria
márcia_oliveria
she, they
## María
## García
maría_garcia
she, they
## Martha
## Rivera
martha_rivera
she, they
## People
## 389
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 399 -->

AWS Content Design System
## First
## Last
## Username
Typical pronouns
## Mary
## Major
mary_major
she, they
## Mateo
## Jackson
mateo_jackson
he, they
## Nikhil
## Jayashankar
nikhil_jayashankar
he, they
## Nikki
## Wolf
nikki_wolf
he, she, they
## Pat
## Candella
pat_candella
he, she, they
## Paulo
## Santos
paulo_santos
he, they
## Richard
## Roe
richard_roe
he, they
## Saanvi
## Sarkar
saanvi_sarkar
she, they
## Shirley
## Rodriguez
shirley_rodriguez
she, they
## Sofía
## Martínez
soﬁa_martinez
she, they
Soo-jin*
## Ki
soo-jin_ki
she, they
## Terry
## Whitlock
terry_whitlock
he, she, they
## Xiulan*
## Wang
xiulan_wang
she, they
## Wei*
## Zhang
wei_zhang
he, they
*When writing the complete name, ﬁrst provide the last name (sometimes referred to as a family
name) followed by the ﬁrst name (sometimes referred to as a given name). For example, Ki Soo-jin
and Wang Xiulan.
Phone numbers
For a standard U.S. or Canadian area code, use any number between 555-0100 and 555-0199. Do
not use these numbers with toll-free or other special area codes, such as 800, 888, and 900. For
such area codes, these numbers are not reserved for ﬁctitious use.
Phone numbers
## 390
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 400 -->

AWS Content Design System
## Products
Use the following format to create ﬁctitious product names in AWS material.
Product- and a number, for example:
## • Product-1
## • Product-2
## • Product-3
## • Product-4
AnyProduct- and a number, for example:
• AnyProduct-1
• AnyProduct-2
• AnyProduct-3
• AnyProduct-4
AnyProduct Manufactured- and a number, for example:
• AnyProduct Manufactured-1
• AnyProduct Manufactured-2
• AnyProduct Manufactured-3
• AnyProduct Manufactured-4
AnySmartProduct- and a number, for example:
• AnySmartProduct-1
• AnySmartProduct-2
• AnySmartProduct-3
• AnySmartProduct-4
Generative AI products
Use the following ﬁctitious names for generative artiﬁcial intelligence (generative AI) products:
## Products
## 391
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 401 -->

AWS Content Design System
• Amazon Ask – A large language model (LLM) for questions and answers. For example:
• Amazon Ask helps you ﬁnd answers about AWS services and get the most out of them.
• Amazon Draft – An LLM for text generation. For example:
• Amazon Draft produces full-length drafts of documentation for writers to use in their writing
process.
• Amazon Draw – A generative AI service for images. For example:
• Amazon Draw generates diagrams and images for use in technical documentation.
AWS Region codes
• aa-example-1
• aa-example-2
• aa-example-3
AWS Region names
• AWS (Example 1)
• AWS (Example 2)
• AWS (Example 3)
Resource IDs
When you create ﬁctitious resource IDs, make sure that it's clear that the ID is ﬁctionalized.
When the resource has speciﬁc guidance in this section (such as Buckets), follow that guidance.
Otherwise, you can use some variation of the following, with adjustments made for the
appropriate length of your resource:
• 1234567890abcdef0
• abcdef01234567890
• 021345abcdef6789
If you need to use a 128-bit, Universally Unique Identiﬁer (UUID) to identify a resource, use the
following format:
AWS Region codes
## 392
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 402 -->

AWS Content Design System
• a1b2c3d4-5678-90ab-cdef-EXAMPLE11111
• a1b2c3d4-5678-90ab-cdef-EXAMPLE22222
• a1b2c3d4-5678-90ab-cdef-EXAMPLE33333
• a1b2c3d4-5678-90ab-cdef-EXAMPLEaaaaa
• a1b2c3d4-5678-90ab-cdef-EXAMPLEbbbbb
If you're unsure what a resource ID looks like for your service, contact your service team for
guidance.
Street addresses
Chieﬂy, you can use any innocuous street name, as long as the town is some version of Anytown
USA. For contrast, Anywhere and Nowhere are also common. Avoid humorous names, such as
Pigwater, WA, or any name that could be ethnically oﬀensive. Not everyone shares your sense of
humor.
• 123 Any Street, Any Town, USA
• 100 Main Street, Anytown, USA
User credentials
For security, it's important to recommend best practices for using credentials and use those best
practices in a topic, such as avoiding the use of keys in examples even for sandbox or temporary
use. You can add a cross-reference to Best Practices for Managing AWS Access Keys in the IAM User
Guide.
For more information about IAM unique IDs, see Unique identiﬁers in the AWS Identity and Access
Management User Guide.
If you need to discuss keys, use the following examples.
• IAM user ID (preﬁx, AIDA)
• AIDACKCEVSQ6C2EXAMPLE
• In service documentation, use the shared content entity &ExampleUserId1;.
• AIDA123456789EXAMPLE
• In service documentation, use the shared content entity &ExampleUserId2;.
• AIDA987654321EXAMPLE
Street addresses
## 393
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 403 -->

AWS Content Design System
• In service documentation, use the shared content entity &ExampleUserId3;.
• IAM role ID (preﬁx, AROA)
• AROA123456789EXAMPLE
• In service documentation, use the shared content entity &ExampleRoleSessionId1;.
• AROA987654321EXAMPLE
• In service documentation, use the shared content entity &ExampleRoleSessionId2;.
• Access key ID
Important: It is a best practice to use short-term access keys (temporary credentials), not long-
term access keys. For more information, see Security best practices in IAM and Alternatives for
long-term access keys in the AWS Identity and Access Management User Guide.
• Short-term access keys (temporary credentials) for federated users (preﬁx, ASIA)
• ASIAIOSFODNN7EXAMPLE (&ExampleTempAccessKeyID1;)
• ASIAI44QH8DHBEXAMPLE (&ExampleTempAccessKeyID2;)
• Long-term access keys for IAM users (preﬁx, AKIA)
• AKIAIOSFODNN7EXAMPLE (&ExampleAccessKeyID1;)
• AKIAI44QH8DHBEXAMPLE (&ExampleAccessKeyID2;)
• Secret access key
• wJalrXUtnFEMI/K7MDENG/bPxRﬁCYEXAMPLEKEY (&ExampleSecretKey1;)
• je7MtGbClwBF/2Zp9Utk/h3yCo8nvbEXAMPLEKEY (&ExampleSecretKey2;)
• IAM SSH public key ID (preﬁx, APKA)
• APKAEIBAERJR2EXAMPLE (&ExampleSshKey1;)
• APKAEIVFHP46CEXAMPLE (&ExampleSshKey2;)
• IAM managed policy ID (preﬁx, ANPA)
• ANPAJ2UCCR6DPCEXAMPLE (&ExamplePolicyId1;)
• ANPAJ4AE5446DAEXAMPLE (&ExamplePolicyId2;)
• Digital certiﬁcate (&ExampleCert;)
The following safe certiﬁcate was generated from a public server on the Amazon site speciﬁcally
for use in samples.
-----BEGIN CERTIFICATE-----
User credentials
## 394
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 404 -->

AWS Content Design System
MIICiTCCAfICCQD6m7oRw0uXOjANBgkqhkiG9w0BAQUFADCBiDELMAkGA1UEBhMC
VVMxCzAJBgNVBAgTAldBMRAwDgYDVQQHEwdTZWF0dGxlMQ8wDQYDVQQKEwZBbWF6
b24xFDASBgNVBAsTC0lBTSBDb25zb2xlMRIwEAYDVQQDEwlUZXN0Q2lsYWMxHzAd
BgkqhkiG9w0BCQEWEG5vb25lQGFtYXpvbi5jb20wHhcNMTEwNDI1MjA0NTIxWhcN
MTIwNDI0MjA0NTIxWjCBiDELMAkGA1UEBhMCVVMxCzAJBgNVBAgTAldBMRAwDgYD
VQQHEwdTZWF0dGxlMQ8wDQYDVQQKEwZBbWF6b24xFDASBgNVBAsTC0lBTSBDb25z
b2xlMRIwEAYDVQQDEwlUZXN0Q2lsYWMxHzAdBgkqhkiG9w0BCQEWEG5vb25lQGFt
YXpvbi5jb20wgZ8wDQYJKoZIhvcNAQEBBQADgY0AMIGJAoGBAMaK0dn+a4GmWIWJ
21uUSfwfEvySWtC2XADZ4nB+BLYgVIk60CpiwsZ3G93vUEIO3IyNoH/f0wYK8m9T
rDHudUZg3qX4waLG5M43q7Wgc/MbQITxOUSQv7c7ugFFDzQGBzZswY6786m86gpE
Ibb3OhjZnzcvQAaRHhdlQWIMm2nrAgMBAAEwDQYJKoZIhvcNAQEFBQADgYEAtCu4
nUhVVxYUntneD9+h8Mg9q6q+auNKyExzyLwaxlAoo7TJHidbtS4J5iNmZgXL0Fkb
FFBjvSfpJIlJ00zbhNYS5f6GuoEDmFJl0ZxBHjJnyp378OD8uTs7fLvjx79LjSTb
NYiytVbZPQUQ5Yaxu2jXnimvw3rrszlaEXAMPLE=
-----END CERTIFICATE-----

• AWS account IDs
These can be expressed either with or without hyphens, depending on the context.
• 111122223333 (&ExampleAWSAccountNo1;)
• 1111-2222-3333 (&ExampleAWSAccountNo1H;)
• 444455556666 (&ExampleAWSAccountNo2;)
• 4444-5555-6666 (&ExampleAWSAccountNo2H;)
• 123456789012 (&ExampleAWSAccountNo3;)
• 1234-5678-9012 (&ExampleAWSAccountNo3H;)
• 777788889999 (&ExampleAWSAccountNo4;)
• 7777-8888-9999 (&ExampleAWSAccountNo4H;)
• 000000000000 (&ExampleAWSAccountNo5;)
• 0000-0000-0000 (&ExampleAWSAccountNo5H;)
• 111111111111 (&ExampleAWSAccountNo6;)
• 1111-1111-1111 (&ExampleAWSAccountNo6H;)
• 222222222222 (&ExampleAWSAccountNo7;)
• 2222-2222-2222 (&ExampleAWSAccountNo7H;)
• 333333333333 (&ExampleAWSAccountNo8;)
• 3333-3333-3333 (&ExampleAWSAccountNo8H;)
• 444444444444 (&ExampleAWSAccountNo9;)
User credentials
## 395
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 405 -->

AWS Content Design System
• 4444-4444-4444 (&ExampleAWSAccountNo9H;)
• 555555555555 (&ExampleAWSAccountNo10;)
• 5555-5555-5555 (&ExampleAWSAccountNo10H;)
• 666666666666 (&ExampleAWSAccountNo11;)
• 6666-6666-6666 (&ExampleAWSAccountNo11H;)
• 777777777777 (&ExampleAWSAccountNo12;)
• 7777-7777-7777 (&ExampleAWSAccountNo12H;)
• 888888888888 (&ExampleAWSAccountNo13;)
• 8888-8888-8888 (&ExampleAWSAccountNo13H;)
• 999999999999 (&ExampleAWSAccountNo14;)
• 9999-9999-9999 (&ExampleAWSAccountNo14H;)
## Names
The Trademarks team must review new service, feature, project, product, and resource names
that product teams create before you use the names in public content. Names can be descriptive,
suggestive, arbitrary, or fanciful. They can include “AWS,” “Amazon,” or neither. If you have
concerns about a proposed name, contact your editor or the Trademarks team.
## Topics
• AWS
• Code names
• Service names
• Service features
• Service resources
• Third-party brand names
AWS
Be cautious about distinguishing between AWS the service and AWS the corporate entity. For more
information, see Messaging Dos and Don’ts on the AWS Legal Pathﬁnder website.
Refer to AWS in the ﬁrst person plural (for example, we are, we will, we have, new service for us, we
recommend).
## Names
## 396
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 406 -->

AWS Content Design System
Code names
Don't use code names or any variation of a code name in public content, including API operations
or graphic ﬁle names. Don't publish any general availability (GA) content that includes a code
name.
When creating internal or prerelease content that references conﬁdential code names, always
surround the code name in brackets ([]), as [code name], to clearly indicate it isn't a public product,
project, or service.
Service names
For a complete list of service names and abbreviations, see AWS oﬀering names. For a list of the
corresponding AWS service name entities to use in AWS service documentation, see the AWS
shared content service names ﬁle.
• Full name on ﬁrst mention – Use the full name on ﬁrst mention in most content, with the
exception of titles. Blog posts, UI text, slides, graphics, and tweets can use the approved short
form on ﬁrst use.
• Exceptions – Some service names must always include "AWS" or “Amazon” and can't be
abbreviated. For more information, see AWS oﬀering names.
• Parts of speech – Capitalize the service name as a proper noun no matter where it appears in
the sentence. Don't use a service name as a common noun. You can use a service name as an
adjective but not a verb.
AWS style
• multiple Amazon ECR registries
• using Elastic Load Balancing to balance your traﬃc
Not AWS style
• multiple ECRs
• Elastic Load Balancing your traﬃc
• Possessives – Don't use the possessive forms of service names or of Amazon or AWS trademarks.
AWS style
• The variety of EC2 instance types
Not AWS style
Code names
## 397
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 407 -->

AWS Content Design System
• Amazon EC2's variety of instance types
• No preﬁxes or suﬃxes – Don't add preﬁxes or suﬃxes to service names and trademarks unless
they are part of a feature name.
AWS style
• A string assigned by Amazon S3
• EBS-optimized instance
Not AWS style
• An Amazon S3-assigned string
• a non-EBS volume
• Services can take action – A service as a sentence subject, such as "Amazon EC2 manages…", is
appropriate because it views the services as systems that perform functions.
• When to use AWS – Don't use a service name in place of “Amazon Web Services.” For example,
use the company name (AWS) for the agent that releases code or sets pricing decisions, and the
product name (Amazon EC2) for the agent that manages the functioning of the API.
• Hyphenation guidance – In general, we don't modify service names by using hyphens or en
dashes, unless the exception is documented in the Usage dictionary. We don't want to create any
"new" terms with service names because that is a legal risk for brand and trademark.
Service features
In general, feature names should not combine more than one service name to avoid diluting
trademarks.
Use lowercase for new feature names as directed under Capitalization. Use title case when
necessary to be consistent with the product team usage.
For speciﬁc usage by service, see the AWS oﬀering names Wiki or the service documentation.
Service resources
In general, new resource names should not repeat the service name or abbreviation.
Resources are introduced in content with the short form of the service name, and may only use the
abbreviated form on second use (unless they are an exception) and when the attribution is clear.
AWS style
Service features
## 398
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 408 -->

AWS Content Design System
• Amazon EC2 instance
• EC2 instance
• instance
Use sentence capitalization for certain resources (such as EC2 instance, DynamoDB table, IAM user,
and OpsWorks stack). Exceptions include: Spot Instances, Reserved Instances, Dedicated Hosts, and
Dedicated Instances.
For speciﬁc usage by service, see the AWS oﬀering names Wiki or the service documentation.
Third-party brand names
AWS content often refers to third-party brand names, such as Apache Cassandra, Docker, Hive,
Hugging Face, Llama, Meta, Microsoft, Parquet, and Spark. Always check third-party names against
the brand's naming guidelines.
The following includes some best practices for using third-party names:
• Don't localize third-party brand names. For service documentation, use noloc tags (<noloc>) to
help prevent localization.
• Don't alter third-party brand names.
• Don't make names possessive (by adding apostrophes).
• Don't change singular and plural names (by adding or removing s).
• Don't change case (by changing capitalization).
• Don't add hyphens to names.
• To help prevent translation and localization of third-party brand names in service
documentation, see Prepare your content for localization.
For more information about third-party names, see Guidance from AWS Legal in the Terminology
Management Framework Wiki. See also Messaging Dos and Don’ts on the AWS Legal Pathﬁnder
website.
Regions and partitions
The AWS Cloud infrastructure is built around AWS Regions and Availability Zones. Each Region has
a friendly name, a code name that's used in API operations, and an endpoint. For a list of the AWS
Region names and codes, see AWS service endpoints in the AWS General Reference. To view the
Third-party brand names
## 399
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 409 -->

AWS Content Design System
available Regions, endpoints, and service quotas for a speciﬁc service, see Service endpoints and
quotas. For general information about AWS Regions, see AWS Global Infrastructure. For a list of
shared content entities in service documentation, see Region shared content entities.
## Location
Airport code
Don't use airport
codes in public
content
Region code
Region name
## Africa
CPT
af-south-1
## Africa (Cape Town)
## Asia Paciﬁc
HKG
ap-east-1
## Asia Paciﬁc (Hong
## Kong)
## Asia Paciﬁc
HYD
ap-south-2
## Asia Paciﬁc
## (Hyderabad)
## Asia Paciﬁc
CGK
ap-southeast-3
## Asia Paciﬁc (Jakarta)
## Asia Paciﬁc
KUL
ap-southeast-5
## Asia Paciﬁc (Malaysia)
## Asia Paciﬁc
MEL
ap-southeast-4
## Asia Paciﬁc
## (Melbourne)
## Asia Paciﬁc
BOM
ap-south-1
## Asia Paciﬁc (Mumbai)
## Asia Paciﬁc
KIX
ap-northeast-3
## Asia Paciﬁc (Osaka)
## Asia Paciﬁc
ICN
ap-northeast-2
## Asia Paciﬁc (Seoul)
## Asia Paciﬁc
SIN
ap-southeast-1
## Asia Paciﬁc (Singapor
e)
## Asia Paciﬁc
SYD
ap-southeast-2
## Asia Paciﬁc (Sydney)
## Asia Paciﬁc
TPE
ap-east-2
## Asia Paciﬁc (Taipei)
## Asia Paciﬁc
BKK
ap-southeast-7
## Asia Paciﬁc (Thailand)
## Asia Paciﬁc
NRT
ap-northeast-1
## Asia Paciﬁc (Tokyo)
Regions and partitions
## 400
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 410 -->

AWS Content Design System
## Location
Airport code
Don't use airport
codes in public
content
Region code
Region name
## China
BJS
cn-north-1
## China (Beijing)
## China
ZHY
cn-northwest-1
## China (Ningxia)
## Europe
FRA
eu-central-1
## Europe (Frankfurt)
## Europe
DUB
eu-west-1
## Europe (Ireland)
## Europe
LHR
eu-west-2
## Europe (London)
## Europe
MXP
eu-south-1
## Europe (Milan)
## Europe
CDG
eu-west-3
## Europe (Paris)
## Europe
ZAZ
eu-south-2
## Europe (Spain)
## Europe
ARN
eu-north-1
## Europe (Stockholm)
## Europe
ZRH
eu-central-2
## Europe (Zurich)
## Israel
TLV
il-central-1
## Israel (Tel Aviv)
## Middle East
BAH
me-south-1
## Middle East (Bahrain)
## Middle East
DXB
me-central-1
Middle East (UAE)
## North America
IAD
us-east-1
US East (N. Virginia)
## North America
CMH
us-east-2
US East (Ohio)
## North America
SFO
us-west-1
US West (N. Californi
a)
## North America
PDX
us-west-2
US West (Oregon)
## North America
YUL
ca-central-1
## Canada (Central)
Regions and partitions
## 401
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 411 -->

AWS Content Design System
## Location
Airport code
Don't use airport
codes in public
content
Region code
Region name
## North America
YYC
ca-west-1
## Canada West
## (Calgary)
## North America
QRO
mx-central-1
## Mexico (Central)
## South America
GRU
sa-east-1
## South America (São
## Paulo)
AWS GovCloud (US)
PDT
us-gov-west-1
AWS GovCloud (US-
## West)
AWS GovCloud (US)
OSU
us-gov-east-1
AWS GovCloud (US-
## East)
Secret and Top Secret
APA
us-iso-west-1
Top Secret (US-West)
Secret and Top Secret
DCA
us-iso-east-1
Top Secret (US-East)
Secret and Top Secret
LCK
us-isob-east-1
Secret (US-East)
Listing Regions in service documentation
When listing Regions in documentation, US Regions must be listed ﬁrst in alphabetical order,
followed by all others in alphabetical order. AWS GovCloud (US) Regions come last, and are listed in
alphabetical order.
To include both the Region name and Region code in a list, alphabetize based on the Region
name and listing the name ﬁrst, followed by the code. For example, use US East (N. Virginia) – us-
east-1 in your list instead of us-east-1 – US East (N. Virginia).
• US East (N. Virginia)
• US East (Ohio)
• US West (N. California)
Listing Regions in service documentation
## 402
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 412 -->

AWS Content Design System
• US West (Oregon)
## • Africa (Cape Town)
## • Asia Paciﬁc (Hong Kong)
## • Asia Paciﬁc (Hyderabad)
## • Asia Paciﬁc (Jakarta)
## • Asia Paciﬁc (Malaysia)
## • Asia Paciﬁc (Melbourne)
## • Asia Paciﬁc (Mumbai)
## • Asia Paciﬁc (Osaka)
## • Asia Paciﬁc (Seoul)
## • Asia Paciﬁc (Singapore)
## • Asia Paciﬁc (Sydney)
## • Asia Paciﬁc (Thailand)
## • Asia Paciﬁc (Tokyo)
## • Canada (Central)
## • Canada West (Calgary)
## • China (Beijing)
## • China (Ningxia)
## • Europe (Frankfurt)
## • Europe (Ireland)
## • Europe (London)
## • Europe (Milan)
## • Europe (Paris)
## • Europe (Spain)
## • Europe (Stockholm)
## • Europe (Zurich)
## • Israel (Tel Aviv)
## • Mexico (Central)
## • Middle East (Bahrain)
• Middle East (UAE)
Listing Regions in service documentation
## 403
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 413 -->

AWS Content Design System
## • South America (São Paulo)
• AWS GovCloud (US-East)
• AWS GovCloud (US-West)
Referring to Regions
Use these guidelines to refer to the diﬀerent types of AWS Regions.
## General Regions:
## Do
• Capitalize AWS Region and AWS Regional on ﬁrst mention.
• Capitalize Region and Regional on subsequent mention.
• Use lowercase region only when referring to a generic region that's not related to AWS. For
example, a geographical region.
Don't
• Don't use labels such as global, governmental, noncommercial, nongovernmental, special, regular,
public, or standard in relation to AWS Regions because such labels can cause confusion.
## Commercial Regions:
## Do
• Use the descriptor commercial (as in “the commercial AWS Regions”).
• On ﬁrst reference to commercial AWS Regions, use the wording commercial AWS Regions
(Regions other than the AWS GovCloud (US) Regions and the China Regions) on ﬁrst mention. Use
commercial AWS Regions thereafter.
## China Regions:
## Do
• To refer collectively to the China (Beijing) and China (Ningxia) Regions, use the China Regions.
Referring to Regions
## 404
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 414 -->

AWS Content Design System
• To refer to customers in the China Regions, or to the seller of services there, see AWS China, its
Regions, and its customers in the Legal guidelines.
AWS GovCloud (US) Regions:
## Do
• To refer to the AWS GovCloud (US-East) and AWS GovCloud (US-West) Regions collectively, use
AWS GovCloud (US) Regions.
Regions that aren’t enabled by default (opt-in Regions):
## Do
• On ﬁrst mention, use opt-in Region (Region that is disabled by default) and link to the opt-in
Region entry in the AWS Glossary. Thereafter, use opt-in Regions.
• To refer to Regions that aren’t opt-in Regions in the context of comparing them to those that
are, use Regions that are enabled by default.
• To describe the act of enabling an opt-in Region, use the verb enable instead of opt in.
• To describe the act of disabling an opt-in Region, use the verb disable instead of opt out.
• To describe the status of a Region (whether it has been enabled or disabled), use opt-in status
instead of enablement status.
AWS Secret and Top Secret Regions:
Don't
• Don’t use AWS Secret Regions, Top Secret Regions, or the individual Region names outside of the
service documentation user guides (the DiﬀDocs) or any other content that's published within
the partition for those Regions. Service documentation content that mentions these Regions
must be proﬁled to appear only in these Regions. For more information, see Special Region
content and Region proﬁling in AWS Docs content in the AWS Docs Wiki.
• Don’t use Amazon Dedicated Cloud (ADC) Regions in any public content. This term is internal only.
Regions that aren’t enabled by default (opt-in Regions):
Don't
Referring to Regions
## 405
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 415 -->

AWS Content Design System
• Don’t use Regions that are manually enabled or manually enabled Regions to describe opt-in
Regions.
Referring to partitions
Use these guidelines to refer to partitions.
## Do
• Deﬁne partition on ﬁrst reference or link to the partition entry in the AWS Glossary. For example,
to deﬁne what a partition is, use wording such as A partition is a group of Regions. Each AWS
account is scoped to one partition. AWS currently has three partitions: aws (commercial AWS
Regions), aws-cn (China Regions), and aws-us-gov (AWS GovCloud (US)).
Don't
• Don’t use labels such as global, governmental, noncommercial, nongovernmental, special, regular,
or public in relation to partitions because such labels can cause confusion.
Security content requirements
Cloud security is the highest priority at AWS. To help customers ﬁnd security and compliance
information in AWS service documentation, guides must include a Security chapter that addresses
the security and compliance controls that security engineers, compliance professionals, regulators,
and auditors care about.
## Do
• Include a Security chapter as a top-level node in your TOC.
• Include service-speciﬁc information.
• Include a set of mandatory sections based on templates that provide consistent headings and
standardized information.
• Consult your service’s security expert before publishing. Some teams don’t want certain internal
processes or architecture exposed.
Don't
Referring to partitions
## 406
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 416 -->

AWS Content Design System
• Don't include generic security information that every customer needs.
• Don't publish your Security chapter without consulting your service’s security expert.
For more information about adding this information to your guide, see Security and compliance
integration in the AWS TCX Service Docs Wiki.
Working with third-party content
AWS customers can beneﬁt from integrating software provided by independent software vendors
(ISVs), open-source projects, and content from other sources such as third-party blogs or websites.
Third-party content is content created and published by a third-party organization (not AWS). This
content can be in the form of written material, logos, graphics, or diagrams. For more information
about open source content, see Messaging Dos and Don’ts on the AWS Legal Pathﬁnder website.
Original content created by AWS that describes a third party's product, service, or features isn't
considered third-party content because AWS is the author. You can create your own original
content that describes a third party's product, service, or features.
We recommend that you err on the side of caution if you want to include third-party content or
descriptions of third-party content in your AWS documentation. For AWS documentation, you can
integrate third-party content or create original content about third-party products in the following
ways:
## Topics
• Link to published third-party content
• Use blog, whitepaper, or webpage content published on the AWS website
• Incorporate third-party content into AWS documentation
Link to published third-party content
If existing published material can meet your readers' needs, link to the third-party content as
explained in .
Third-party content
## 407
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 417 -->

AWS Content Design System
Use blog, whitepaper, or webpage content published on the AWS
website
AWS typically publishes in-depth content about using a third-party product, service, or feature
with AWS on the AWS website in a blog post or whitepaper. After the content is published, you can
link to the existing content.
If you want to incorporate content from an AWS blog post, whitepaper, or webpage into your
documentation, you can do so. AWS content produced by another AWS team outside the AWS
Documentation team and published on the AWS website isn't considered third-party content.
However, out of respect for our AWS colleagues, make sure that you have permission from the
author or other AWS team to use their content in your documentation.
## Tip
We recommend that you work closely with the original author if you choose to incorporate
their content. Preferably, link to the existing content instead of integrating it into your
documentation.
Occasionally, writers on the AWS Documentation team write content for the AWS website that
deals with how to use third-party products, services, or features with AWS services. For more
information about publishing a blog post on the AWS website, see the AWS Blog team Wiki.
For more information about publishing whitepapers, see the AWS Architecture Content team's
Technical Content Creation Kits Wiki.
Incorporate third-party content into AWS documentation
Third-party content is content created and published by a third-party. Original content authored by
AWS that describes a third-party's product, service, or features isn't considered third-party content
because AWS is the author.
We recommend that you err on the side of caution when including third-party content in your
AWS documentation. If you must include third-party content in your documentation, follow these
guidelines:
• Ask yourself "Does this content provide a signiﬁcant beneﬁt to AWS customers in a way that we
can't provide in our documentation?"
Use blog, whitepaper, or webpage content published on the AWS website
## 408
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.


<!-- Page 418 -->

AWS Content Design System
We recommend that you consider this question carefully. We recommend that you create your
own original content instead, including information that describes a third-party's product,
service, or features.
• Don't copy, rewrite, or repurpose content published by a third-party content provider. This is
plagiarism. Instead, link to the third-party content as explained in or follow the other guidelines
in this section to get permission to incorporate third-party content into your documentation.
## Note
AWS content produced by another AWS team outside the AWS Documentation team and
published on the AWS website isn't considered third-party content.
• If you decide to incorporate third-party content that was written by someone else into your
documentation, follow these guidelines:
• Make sure that you have the written permission to use third-party content. Some third-party
content providers and ISVs require signed legal agreements.
• Make sure the third-party content provider or ISV understands that the content might be
rewritten, edited, and updated by AWS.
• As with all documentation, you're responsible for the content’s accuracy, format, publication,
and updating.
Incorporate third-party content into AWS documentation
## 409
This prerelease documentation is conﬁdential and is provided under the terms of your nondisclosure agreement (NDA) with Amazon Web Services (AWS) or other agreement governing your receipt of AWS conﬁdential information.
