Controller:
----------

Change:
 - inventory
 - group_vars/all/configure_connection_controller_credentials.yml

ansible-navigator run casc_ctrl_config.yml -i inventory -m stdout --eei quay.io/automationiberia/aap-gymkana-2023/ee-casc

EDA Controller:
----------

1.- Create token in Controller and attach it to EDA admin User
2.- Create project pointing to this repo
3.- Create rulebook pointing to webhook.yaml

