# ValueEdge — application (build)

Build compilé de l'app ValueEdge, publié sur GitHub Pages : https://jerem57990.github.io/ValueEdge-app/

- Code source : dépôt privé `ValueBet` (`cd web && npm run build:cloud`).
- Données : Supabase. Seul le compte propriétaire peut lire ou écrire (connexion + règles RLS). La clé publiée dans
  le bundle est une clé « publishable », publique par conception ; aucune clé secrète n'est présente ici.
- OCR des captures : tesseract.js exécuté dans le navigateur (fichiers dans `tesseract/`), l'image ne quitte pas l'appareil.
