The hook gets a Jira issue ID from the branch name and adds it to the beginning of a commit message

Branch name must contain a valid Jira issue ID

Examples of valid branch names:
- feature/JR-123/name_parser
- bugfix/BG-555/null_ref_in_init
- TD-32
- JR-765/weird_fix

Works both on Linux and Windows (with git bash)