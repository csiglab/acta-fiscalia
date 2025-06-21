# Acta Fiscalia

> Acta Fiscalia is a conceptual framework designed to formalize and enhance organizational collective cognition.

Status:

- [ ] 🧨 Unable to configure Outline with Keycloak OIDC

## Paperless-ngx

> Note: In order to - drag and drop.


```bash
bash -c "$(curl --location --silent --show-error https://raw.githubusercontent.com/paperless-ngx/paperless-ngx/main/install-paperless-ngx.sh)"

docker compose -f docker-compose.sqlite.yml run --rm webserver createsuperuser
docker compose -f docker-compose.sqlite.yml up

user: dbremont
pass: eb323faf719afb05 `openssl rand -hex 8`

```



## Bookstack

```bash
...
```

## Security

### KeyClock

```bash
docker run -d \
  --name keycloak \
  -p 8080:8080 \
  -e KEYCLOAK_ADMIN=admin \
  -e KEYCLOAK_ADMIN_PASSWORD=admin \
  quay.io/keycloak/keycloak:24.0.3 \
  start-dev
```

- Username: admin
- Password: admin

Email Mapper:

- UnauthorizedError: An email field was not returned in the profile or id_token parameter, but is required.

## Metaculus

Status: Failed; API Failure With  Docker; Try; No Docker.


## References

- [paperless-ngx](https://docs.paperless-ngx.com/)
- [BookStack](https://www.bookstackapp.com/)
- [Docmost](https://docmost.com/)
- [Outline Knowledgebase Deployment](https://blog.gurucomputing.com.au/Outline%20Knowledgebase%20Deployment/)
- [Local development](https://docs.getoutline.com/s/hosting/doc/local-development-5hEhFRXow7)
- [js.wiki](https://js.wiki/)
- [Rocket Chat](https://www.rocket.chat/)
- [Scoold](https://scoold.com/)
