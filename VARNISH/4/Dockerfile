FROM buildpack-deps:stretch

# Installation of needed extensions.
RUN apt-get update && apt-get install --fix-missing -y \
  varnish

# the sample vcl file for Drupal
ADD config/drupal-base.vcl /etc/varnish/default.vcl