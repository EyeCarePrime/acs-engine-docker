# ACS-ENGINE

Minimal acs-engine build from source using minideb image.


### Examples

      docker run eyecare/acs-engine version

      docker run --rm -v ${KUBE_JSON_DIR}:/kube -w /kube eyecare/acs-engine generate kube.json