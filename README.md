# FootballProject


## Setting up GCE Development

1.  Install [Google Cloud SDK](https://cloud.google.com/sdk/docs/quickstart-macos)
2.  `gcloud config set project PROJECT_ID`
3.  `gcloud auth login`
4.   Setup port forwarding: `gcloud compute ssh INSTANCE_NAME  --zone ZONE -- -L MAC_PORT:localhost:SERVER_PORT`
