# hello-world

steps:
- uses: actions/first-interaction@v1
  with:
    repo-token: ${{ secrets.GITHUB_TOKEN }}
    issue-message: '# Message with markdown.\nThis is the message that will be displayed on users' first issue.'
    pr-message: 'Message that will be displayed on users' first pr. Look, a `code block` for markdown.'
