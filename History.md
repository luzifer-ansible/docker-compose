# 1.6.0 / 2018-04-25

  * Introduce delay option for clusters not to reload at the same time

# 1.5.0 / 2018-04-24

  * Add option to disable validation of docker-compose file

# 1.4.0 / 2018-04-18

  * Introduce stop action (thanks @EugenMayer)  
    This enables users of this role to execute `docker-compose stop` instead
    of `docker-compose down` on shutdown and speed up the startup. For full
    discussion leading to this see: https://git.io/vpIOy

# 1.3.0 / 2018-04-12

  * Remove deprecated option --parallel

# 1.2.0 / 2018-03-19

  * Use `cache_valid_time` for apt module

# 1.1.1 / 2018-01-23

  * Fix: Don't do reloads on packer builds

# 1.1.0 / 2018-01-23

  * Do not start services in packer builds

# 1.0.2 / 2018-01-12

  * Ensure plain "pip" is used

# 1.0.1 / 2018-01-07

  * Fix: Ensure docker-compose is restarted on docker restart

# 1.0.0 / 2017-12-27

  * Rename variable to prevent name collisions

# 0.2.0 / 2017-09-18

  * Use "remove-orphans" to remove deleted services

# 0.1.0 / 2017-09-14

  * Initial import as galaxy role