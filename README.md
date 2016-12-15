# setup-my-env

## 事前準備

### GitとAnsibleのインストール

```bash
$ sudo apt-get install git ansible
```

### Playbookのダウンロード

```bash
$ git clone https://github.com/YujiAzama/setup-my-env.git
```

### Playbookの実行

```bash
$ ansible-playbook -i playbooks/install-dev-tools.yaml
```
