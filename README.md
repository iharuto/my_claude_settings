# my_claude_settings

```json
{
  "model": "claude-sonnet-5-5",
  "hooks": {
    "SessionStart": [
      {
        "hooks": [
          {
            "type": "command",
            "command": "echo 'Project rule: when reporting results in a .md file (docs/*.md, REPORT.md etc.), also generate the corresponding figure under results/figures/ and embed it with a relative markdown image link. Save the raw numbers to results/raw or results/tables first and build the figure from them, not from stdout.'"
          }
        ]
      }
    ]
  },
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": [
      "Hallucinating",
      "Confabulating",
      "Fabricating",
      "Dissociating",
      "Scheming",
      "Mutating",
      "Corrupting",
      "Decaying",
      "Possessing",
      "Whispering",
      "Watching",
      "Dreaming"
    ]
  }
}

```
