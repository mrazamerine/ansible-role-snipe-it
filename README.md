# Ansible role – Snipe-IT
Ansible role for setting up and configuring [Snipe-IT](https//snipeitapp.com/).


## Variables

* **snipeit\_app\_timezone** – Time zone (string) [America/Los_Angeles]

* **snipeit\_debug\_mode** – Set debug mode (boolean) [false]

* **snipeit\_domain\_name** – Domain name for Snipe-IT (string)

* **snipeit\_mail\_encryption** – Email encryption (string) [tls]

* **snipeit\_mail\_from\_address** – Email address for sending email alerts/reports (string)

* **snipeit\_mail\_host** – Hostname for outgoing mail server (string)

* **snipeit\_mail\_username** – Username of the authenticated user to send email as (string)

* **snipeit\_mail\_password** – Password for the authenticated user to send email as (string)

* **snipeit\_mail\_port** – Outgoing mail port (int) [25]

* **snipeit\_mail\_replyto\_address** – Reply:to name on emails (string)

* **mysql\_snipeit\_password** – Database password (string)