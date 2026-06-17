# Carteira — painel (casco público)

Apenas a interface do painel de investimentos (HTML/JS), publicada via **GitHub Pages**.

**Não contém dado nenhum.** Os dados ficam no Supabase, protegidos por login Google + RLS;
quem abre a página sem logar vê só a tela de "Entrar com Google". O `config.js` traz apenas
a URL do projeto e a chave anônima (públicas por design).

O código-fonte, o pipeline de dados e o extrato da B3 ficam num **repositório privado** separado.

- `index.html` — a SPA (cópia de `painel/index.html` do repo privado).
- `config.js` — URL + anon key do Supabase.
