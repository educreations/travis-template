# .travis.yml Template

A template to use for projects that build with Travis.

## Encrypting Hipchat Tokens

Run:

```bash
travis encrypt --org \
  ${HIPCHAT_TOKEN}@${HIPCHAT_ROOM_NAME} \
  --add notifications.hipchat.rooms
```
