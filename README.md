# fallback-test
Test site-local-config.xml fallback methods for event-data

To test, setup a CMSSW release and execute run\_analysis.sh:

You can edit the siteconf/JobConfig/site-local-config.xml \<event-data\> block to change fallback methods before running the analysis script.

E.g:
```
cmsrel CMSSW_10_0_0
cd CMSSW_10_0_0
cmsenv
cd -
./run_analysis.sh
```
