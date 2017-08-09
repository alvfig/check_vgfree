# check_vgfree
Nagios plugin to check free space on LVM volume group



$ ./check_vgfree --help
Usage: check_vgfree [options]

Options:
  -h, --help            show this help message and exit
  -c CRITICAL, --critical=CRITICAL
                        critical limit in GB
  -C CP, --critical-percent=CP
                        % critical limit
  -g VG, --volume-group=VG
                        volume group to check
  -w WARNING, --warning=WARNING
                        warning limit in GB
  -W WP, --warning-percent=WP
                        % warning limit
