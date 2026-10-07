# json2dir-ansible

json2dir as an Ansible playbook: YAML + Jinja2 with `ansible.builtin` modules only; `json2dir` is a tiny sh wrapper that saves stdin and runs the playbook.

    ANSIBLE_PLAYBOOK=/path/to/ansible-playbook ./json2dir < document.json
