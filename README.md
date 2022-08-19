# Henry Scholfield's website webflow backup

This is an automated backup of the Webflow website hosted at https://henry-scholfield.webflow.io.

## How it works

This projects uses webflow-git, an utility that works by visiting your site at regular intervals and downloading, formatting and comparing the code to the previous revision. If any difference is detected, a new revision is committed to the repository.

> You can find more about Webflow-git here: https://github.com/jason-ro/webflow-git

### Check frequency

The update frequency of the backups is defined in the cron schedule in the [workflow configuration file](./.github/workflows/main.yml).

> Helper: [Crontab generator](https://crontab-generator.com)

### Manual trigger

The backup can also be manually triggered by clicking the Actions link on the menu below the project name, then selecting `webflow-git` workflow and finally clicking on the "Run workflow" button:

![Trigger manually](https://user-images.githubusercontent.com/2506014/134331249-c2e64b87-3d8d-4dbd-b1d9-46352fd5d3bd.png)
