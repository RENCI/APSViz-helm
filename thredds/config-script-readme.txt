to create the configMap scripts for a deployment use the following command line for each config file.
then place the body of the output into the configMap file.

  kubectl create configmap --dry-run=client anyname --from-file=./thredds/config-files/tds2/<file name> --output yaml