# Discord Matrix Bridge dev repo for testing purposes for the Tripsit community

This is a Discord bot that creates a bridge between a Matrix room and a Discord channel

## Things to consider

`matterbridge.toml` doesn't pass `.env` variables very well, so I had to add it to `.gitignore`. The `matterbridge.toml.example` file has everything that is needed, with all secrets redacted. Just do a `cp matterbridge.toml.example matterbridge.toml` and you should be good to go.

### Things to update

- Create a function to recursively go through all the Discord channels and create Matrix rooms with the same name
- Work on perms and how they will work between the two services
- Ensure commands work, and are able to be used from a Matrix room and paste the output

**Written by doctorofplagues. This is open-source, so feel free to use for non-commercial purposes.**
*For any questions, e-mail doctorofplagues35@gmail.com, or contact me on Discord at doctor.of.plagues.*
