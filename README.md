# v7-CandidateSuggestion

In the future, this will be the primary candidate suggestion engine for the v7 steno system.

1. **Highlighting:** The engine can highlight **two regions** of the text buffer. One highlight region is red, one highlight region is black.
2. **Candidate suggestions:** A candidate can affect only one highlight region or both regions.
3. **Evaluation:** The engine is improved using Codex. The evaluation criteria are:
   * How cluttered the suggestions are
   * How fast the user can type what they want to type

   The evaluation criteria are automatically evaluated by an external evaluation server. Some of the test cases are visible to the agent, other test cases are not.
