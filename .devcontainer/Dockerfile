# The below image is created out of the Dockerfile.base
# It has the dependencies already installed so that codespace will boot up fast
FROM ghcr.io/aireset/chatwoot_codespace:latest

# Do the set up required for chatwoot app
WORKDIR /workspaces/chatwoot-wl
COPY . /workspace
RUN yarn && gem install bundler && bundle install
