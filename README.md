# Check the status of website periodically and notify if failed
<div align='center'>
<img alt='last-commit' src='https://img.shields.io/github/last-commit/davoudarsalani/website-status?&labelColor=black&color=grey&style=flat'>
<img alt='commit-activity' src='https://img.shields.io/github/commit-activity/m/davoudarsalani/website-status?&labelColor=black&color=grey&style=flat'>
</div>
<br>

```yml
- name: Checking status
  uses: ./.github/actions
  with:
    url:
    TELEGRAM_TOKEN: ${{ secrets.TELEGRAM_TOKEN }}
    TELEGRAM_TO: ${{ secrets.TELEGRAM_TO }}
```
