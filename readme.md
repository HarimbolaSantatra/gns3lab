# MY HOMELAB

> [!IMPORTANT]
`.tfvars`, `.tfstate` and `.tfstate.` must be ignored in production

## Kubernetes
*wip* (branch `k8s`)

## Simple web server for GNS3

    docker build -f webserver.Dockerfile -t harimbolasantatra/some-server .

To run it on external container (w/o gns3):

    docker run --rm --name some-server -d harimbolasantatra/some-server

## Database replication
*wip* (branch `replication`)
