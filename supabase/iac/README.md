# Ansible Collection - supabase.iac

Documentation for the collection.

## Install
```
ansible-galaxy collection install git+https://github.com/simhead/supabase#supabase/iac,main
ansible-playbook supabase.iac.supabase_deploy -i /iac-run-dir/output/inventory
     e.g. ansible-playbook supabase.iac.supabase_deploy -i /home/ubuntu/ally/tmp/output/spbase-app1/inventory

```

## Uninstall
```
ansible-galaxy collection install git+https://github.com/simhead/supabase#supabase/iac,main
ansible-playbook supabase.iac.supabase_undeploy -i /home/ubuntu/ally/tmp/output/spbase-app1/inventory
ansible-playbook supabase.iac.oci_cleanup -i /home/ubuntu/ally/tmp/output/spbase-app1/inventory
```