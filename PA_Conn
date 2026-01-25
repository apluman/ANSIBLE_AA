- name: Palo Alto connectivity test
  hosts: pa-fw-ANOT_LAB
  connection: local
  gather_facts: no

  collections:
    - paloaltonetworks.panos

  vars:
    provider:
      ip_address: "{{ 172.19.152.186 }}"
      api_key: "{{ LUFRPT1pZG9Pby9ITFpRSGpWM0pRYmlHczJoVjRNQ2s9M0NCZkhWTFhSK3lmaTk4SEc3bXE0V2NIZ1NQUFcwM25VeUJFSGZkeWVqVT0 }}"

  tasks:
    - name: Get firewall system info
      panos_facts:
        provider: "{{ provider }}"
