# artemis-broker-init
Init container image that configures artemis broker instances

# Repository

The ActiveMQ Artemis broker container images are pushed to https://quay.io/repository/arkmq-org/activemq-artemis-broker-init

# Tags

The ActiveMQ Artemis broker container images have release tags and special tags.

The image release tags point to images built from the sources of the releated release tags,
i.e. the `1.0.0` image release tag points to the image built from
the sources of the [v1.0.0](https://github.com/arkmq-org/activemq-artemis-broker-init-image/tree/v1.0.0) release tag

The image special tags are `latest` and `dev-latest`.
The `latest` tag points to the image built from the sources of the latest release tag.
The `dev-latest` tag points to the image built from the sources of the main branch, it should be used only for development purposes, it expires 7 days after the push.
