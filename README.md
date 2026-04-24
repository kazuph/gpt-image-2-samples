# gpt-image-2-samples

GitHub Pages で配信する、360度パノラマのサンプル集です。

## Local Preview

```bash
cd site
python3 -m http.server 8765
```

その後、`http://127.0.0.1:8765` を開きます。

## Deployment

`main` へ push すると GitHub Actions で `site/` が GitHub Pages にデプロイされます。
