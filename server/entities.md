servers
---
id
hostname
connexion_method
port
health_status [available, error, down]
ssh_key_pair
    public
    private

projects
---
id
location
repo_url
currently_deployed_version
last_deploy_date
deploy_method [git, scp, capistrano, custom_script]
monitors_id

monitors
---
id
method [http, ping, tcp]
config
    any blob of json or anything
period "cron like period of execution"
status