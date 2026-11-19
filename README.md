# Central de Gestão Comercial

Sistema desenvolvido em Django para gestão de pedidos, clientes, propostas, SAC e devoluções.

## Executar

```powershell
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py seed_demo
python manage.py runserver 127.0.0.1:8000
```

Abra http://127.0.0.1:8000.

## Deploy no Render

1. Envie o projeto para um repositorio no GitHub.
2. No Render, escolha **New + > Blueprint**.
3. Selecione o repositorio e use o arquivo `render.yaml`.
4. Aguarde a criação do banco PostgreSQL e a conclusão do deploy.
5. Altere as senhas padrão dos usuários antes do uso em produção.

## Usuários iniciais

- Fran: `fran` / `Fran2026`
- Leandro: `leandro` / `Leandro2026`
- Paulo: `paulo` / `Paulo2026`

Troque as senhas iniciais pelo painel administrativo antes de publicar o sistema.
