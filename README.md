## Example usage

    - role: delayed_job
        delayed_job_dir: /srv/www/app.climatesmartbusiness.com/climatesmart
        delayed_job_user: climatesmart
        delayed_job_group: climatesmart
        tags: ['delayed_job']

## Controlling the service

With no instance:

    systemctl status delayed_job@0

With an instance name of `urgent`

    systemctl status delayed_job_urgent@0

