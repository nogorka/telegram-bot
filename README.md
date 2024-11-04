# Document checking Service: Telegram Bot

This is a telegram client for document checking service


## Bot Information

Bot is available via [@doc_checking_isu_bot](https://t.me/doc_checking_isu_bot).
> **Note:** Don't forget to run the main file unless your desired host is remote.


## Setup Instructions

1. **Obtain API Token**
    - Contact a maintainer to get the `API_TOKEN`.
    - Place the `API_TOKEN` inside the `.env` file.

2. **Setup Virtual Environment**
    - Create a virtual environment.
    - Install required dependencies:
      ```bash
      pip install -r requirements.txt
      ```

3. **Run the Bot**
    - Make sure to run the main Python file to start the bot.


## TODO

- [ ] Find host and provider services
- [ ] Design architecture, data flows, DB, file management for reports, and dynamic HTML results
- [ ] Design bot options and commands
- [ ] Add autotests
- [ ] Configure CI/CD pipelines

More information about development iterations available on the [board](https://unidraw.io/app/board/fd7bf5e99d6a7d3368fa)