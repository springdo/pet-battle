tkn pipeline start fe-pet-battle \
 -w name=shared-workspace,volumeClaimTemplateFile=https://raw.githubusercontent.com/openshift/pipelines-tutorial/master/01_pipeline/03_persistent_volume_claim.yaml \
 -p git-url=http://github.com/springdo/pet-battle.git
