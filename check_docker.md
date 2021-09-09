github: [github.com/timdaman/check_docker]

add nagios user to docker group: sudo usermod -a -G docker nagios
usage: check_docker.py --containers cont_name_regex cont_name2 --status running

