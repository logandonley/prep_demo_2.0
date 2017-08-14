# prep_demo_2.0

Run by performing the following:
* `ansible-galaxy install -r requirements.yml --roles-path .`
* `ansible-playbook -i data/inventory playbook.yml --connection=local`

Note:
You must be logged into the cluster locally using the `oc` command.