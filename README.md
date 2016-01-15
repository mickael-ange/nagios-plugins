Nagios Plugins
==============

check_systemctl
---------------

    Check service status with systemctl.
    USAGE: ./check_systemctl -s <service_name> [OPTIONS]
    OPTIONS:
        -e | --expected-status
            The expected service status: active | inactive.
            Defaults: active

        -h | --help
            Display this help.

        -s | --service
            The name of the service to check, e.g. nginx or nginx.service.

        -v | --version
            Display script version.


