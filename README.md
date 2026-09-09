# Tawes Store

Marketplace responsive pour achat au détail et achat en gros, basée sur React et Supabase.

## Connexion Supabase

Le catalogue lit les tables products et categories. Configurez REACT_APP_SUPABASE_URL et REACT_APP_SUPABASE_ANON_KEY dans les secrets de l'environnement. La clé ne doit jamais être commitée dans GitHub.

Colonnes produit compatibles : name ou title, description, price, wholesale_price ou bulk_price, category, image ou image_url, stock et min_order. Si products est vide, un catalogue de démonstration s'affiche.
