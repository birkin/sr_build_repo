2022-Jul-18...
- not working
- the log and db directories (commented out now in docker-compose) do get created in the code-parent folder.
- doesn't seem the `python3 -m venv ../venv_sr_repo` command is working; maybe add `..venv_sr_repo` to a volumes entry? 