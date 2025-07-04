# escape=`

ARG BASE_IMAGE
ARG SPE_IMAGE
ARG SHS_IMAGE

FROM ${SHS_IMAGE} as shs
FROM ${SPE_IMAGE} as spe
FROM ${BASE_IMAGE}

COPY --from=spe C:\module\db C:\resources\spe
COPY --from=shs C:\module\db C:\resources\jss