# Fireworks event displays

The Fireworks Twiki can be found at https://twiki.cern.ch/twiki/bin/view/CMSPublic/WorkBookFireworks 

## Event numbers and files

2018 data events with high DNN scores:
1. run 315973, lumi 307, evt 376801960
    * `/store/data/Run2018A/SingleMuon/MINIAOD/17Sep2018-v2/00000/55A8BDC4-FC8D-AC41-BFBC-4C196D34F747.root` 
2. run 316590, lumi 496, evt 673296798
    * `/store/data/Run2018A/SingleMuon/MINIAOD/17Sep2018-v2/60000/D3025FBC-7433-6B4A-A2A6-C184F68CB738.root` 
3. run 321831, lumi 512, evt 901426047
    * `/store/data/Run2018D/SingleMuon/MINIAOD/22Jan2019-v2/110000/F47D0DD0-004B-EE48-8E5B-D6F35D73DE69.root`

To query DAS, for instance,
```
file, dataset=/SingleMuon/Run2018A-17Sep2018-v2/MINIAOD run=315973 lumi=307
```
which gives the results https://cmsweb.cern.ch/das/request?view=list&limit=50&instance=prod%2Fglobal&input=file%2C+dataset%3D%2FSingleMuon%2FRun2018A-17Sep2018-v2%2FMINIAOD+run%3D315973+lumi%3D307 

## To use the config files

1. On the cmsShowWeb Gateway @ CERN: https://fireworks.cern.ch/cmsShowWeb/revetor.pl,
    - Paste the CERN EOS LFN (/store/...) into the first box
    - And paste the raw GitHub configuration file into the second box
2. In the GUI, you have to type in the run, lumi, and event number again (these are not stored in the config file).


## To export a config file

1. Exporting on the website sends the files to this URL for my account `https://fireworks.cern.ch/config/skkwan/`, where they can be right-clicked and downloaded.