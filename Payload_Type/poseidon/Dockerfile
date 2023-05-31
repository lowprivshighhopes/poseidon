FROM itsafeaturemythic/mythic_go_macos:latest

WORKDIR /Mythic/

COPY [".", "."]
RUN mkdir -p ../../../../MythicMeta/MythicContainer
RUN make build

CMD make run
