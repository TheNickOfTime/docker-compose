# docker-compose

This is a collection of docker compose configuration files that are referenced in the various guides I've written on [my blog](https://nickcunningh.am/blog). Some things to note:

- You will likely need to change various parameters for these to work with your setup, such as:
  - Volume mappings
  - UUID/GUID mappings
  - Environment variables & secrets
- Image version tags will likely be out of date when you look at these files - be sure to check for updates if you don't have an automatic process in place!
- These files represent the _finished_ version from the guides, these files might not work right out of the gate always if additional configuration was required.

All of these files are derived from the actual configurations I am running on my _hobbyist_ home-lab/server, but some are modified for security reasons/public release. I do my best to keep configurations clean, consistent, and secure as possible while following best practices - but there might be things I could be doing better. I'm always learning new things that influence or change the way I approach things, so I will do my best to keep these files up to date if I find meaningful issues in my work.

## Current Compose Files

| Stack name            | Links                                                                                                              | Description                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------- |
| [forgejo](./forgejo/) | [Guide](https://nickcunningh.am/blog/how-to-setup-and-configure-forgejo-with-support-for-forgejo-actions-and-more) | Deploys Forgejo & a single Forgejo Actions runner |
