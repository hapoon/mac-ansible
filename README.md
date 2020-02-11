# mac-ansible
Macの初期環境設定で自動化できる部分をansibleで設定する

## Requirement
- Xcodeがインストールされている
- Homebrewがインストールされている
- Ansibleがインストールされている

## Usage

共通設定だけを自動構築する場合
```
% ansible-playbook playbooks/default.yml
```

SRE向けに自動構築する場合
```
% ansible-playbook playbooks/sre.yml
```

