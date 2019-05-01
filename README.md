# Upgrade Solr index

Bash script to upgrade an entire Solr index from 4.x -> 5.x -> 6.x so it can be read by Solr6.x or Solr 7.x

![Bash_script](https://img.shields.io/badge/bash-100%25-blue.svg) ![Apache-Solr-Scripts](https://img.shields.io/github/issues/spy86/Apache-Solr-Scripts.svg) ![Apache-Solr-Scripts](https://img.shields.io/github/forks/spy86/Apache-Solr-Scripts.svg) ![Apache-Solr-Scripts](https://img.shields.io/github/stars/spy86/Apache-Solr-Scripts.svg) ![Apache-Solr-Scripts](https://img.shields.io/github/license/spy86/Apache-Solr-Scripts.svg) ![Apache-Solr-Scripts](https://img.shields.io/twitter/url/https/github.com/spy86/Apache-Solr-Scripts.svg?style=social)
## Usage:

    Script to Upgrade old indices from 4.x -> 5.x -> 6.x format, so it can be used with Solr 6.x or 7.x
    Usage: ./upgradeindex.sh [-s] [-t target-ver] <indexdata-root>
    
    Example: ./upgradeindex.sh -t 5 /var/solr
    Please run the tool only on a cold index (no Solr running)
    The script leaves a backup in <indexdata-root>/<core>/data/index_backup_<version>.tgz. Use -s to skip backup
    Requires wget or curl to download dependencies

**Use on your own risk!**
