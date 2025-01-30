### Odoo Production Server Setup

This project sets up a production-ready Odoo server using Ansible and Vagrant.

## Prerequisites

- Vagrant
- VirtualBox
- Ansible

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/MuhammadAhmad522/Odoo-Production.git
    cd Odoo-Production
    ```

2. Start the Vagrant environment:
    ```bash
    vagrant up
    ```

3. Provision the server using Ansible:
    ```bash
    ansible-playbook -i inventory playbook.yml
    ```

## Roles

The following roles are included in the Ansible playbook:

- `users`: Manages user accounts.
- `common`: Common setup tasks.
- `postgresql`: Sets up PostgreSQL.
- `odoo`: Installs and configures Odoo.
- `ssl`: Configures SSL.
- `nginx`: Sets up Nginx.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Contact

For any questions or issues, please open an issue in the repository.
