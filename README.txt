This is the directory and repo-structure to contribute to CJungs RHAAP project, the vmware instance creation within that project and maybe other matters in the project as well.

To test:
. ./env.sh
ansible-navigator run do-instance.yml --mode stdout  --eei bcl-ov:9 -e remove=true