[![CI](https://github.com/ktooi/ansible-role-kodi/workflows/CI/badge.svg)](https://github.com/ktooi/ansible-role-kodi/actions?query=workflow%3ACI+branch%3Amain)

# Ansible Role: kodi

Debian/Ubuntu サーバに kodi をインストールし、基本的な設定を行います。

この role では次のことを行います。

* Kodi のインストール
* Kodi の自動起動設定
* フォント差し替え(日本語文字化け対策)
* mediasources の設定

この role では次のことを行いません。

* Kodi 内の詳細な設定

## Requirements

この role には特別な要件はありません。

## Role Variables

```yaml
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: kodi
  roles:
    - kodi
```

## Authors

* **Kodai Tooi** [GitHub](https://github.com/ktooi), [Qiita](https://qiita.com/ktooi)

## License

次のファイルは他の方の著作物を利用しています。再頒布にあたっては、それぞれのライセンスに従ってください。
* [files/fonts/mplus-1p-regular.ttf](files/fonts/mplus-1p-regular.ttf)
    * [M+ FONTS](https://mplusfonts.github.io/)
    * License: [SIL Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL_web)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
