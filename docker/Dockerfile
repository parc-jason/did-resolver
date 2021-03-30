FROM universalresolver/driver-did-sov

COPY ./genesis.txn /opt/driver-did-sov/sovrin/genesis.txn

ENV uniresolver_driver_did_sov_libIndyPath=
ENV uniresolver_driver_did_sov_poolConfigs=_;./sovrin/genesis.txn
ENV uniresolver_driver_did_sov_poolVersions=_;2
ENV uniresolver_driver_did_sov_walletName=wallet

RUN "/opt/driver-did-sov/docker/run-driver-did-sov.sh"

ENTRYPOINT "/opt/driver-did-sov/docker/run-driver-did-sov.sh"
