# Check my k3s cluster pods status

## Workflow steps

- Using sshuttle to connect to my cluster through a proxy bastion
- Using kubectl commands to check cluster status
- Writing results to logfile artifact
- Send Slack message (json formatted)
- Send artifact to Slack as file
- Send message and file to Telegram

### Secrets Requirements

- secrets.SSH_KEY
- secrets.BASTION_USER
- secrets.BASTION_ADDR
- secrets.KUBE_CONFIG
- secrets.SLACK_TOKEN
- secrets.TELEGRAM_TOKEN
