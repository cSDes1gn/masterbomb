# Master Bomb

![img](/docs/img/MB.png)

Modified: 2021-02

Bill of Materials in one place.

## Nodejs Server
Run as nodemon listener:
```bash
npm run dev
```

## Postgres Container
Initialize and start daemonized postgres docker container:
```bash
npm run start-db
```

Teardown postgres db:
```bash
npm run stop-db
```

## API Testing
Run the ansible playbook from tests:
```bash
ansible-playbook -i inventory/inventory.yaml playbooks/main.yaml
```