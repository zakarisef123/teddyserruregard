# Maison Ferrand Serrurier — Gard (30)

Site statique (HTML/CSS/JS, sans build) de Maison Ferrand Serrurier (SOS RENOV), entreprise de serrurerie à Nîmes et dans tout le Gard (30).
Même structure et même charte graphique que le site plomberie Teddy-ets (même société, SOS RENOV).
Logo : `images/logo-clair.svg` (fond clair), `images/logo-sombre.svg` (fond sombre), icône `images/icone.svg` / `icone.png`,
favicon `favicon.svg` / `favicon.png`, image de partage `logo-partage.png`.
Palette : Noir Fonte #121212, Laiton #C9A04A, Ivoire #F4EFE4, Graphite #2A2A2A. Typographies : Archivo Black, DM Sans.

## Structure

- `index.html` : accueil
- `urgence-serrurier/`, `prestations/` et une page par prestation :
  ouverture de porte, changement de serrure, cylindre (barillet), blindage de porte, porte blindée,
  dépannage après effraction, verrous & renforts, rideau métallique, coffre-fort, contrôle d'accès & serrure connectée
- `zones-intervention/` et une page par secteur : Nîmes, Alès & Cévennes, Uzès & Pont du Gard,
  Bagnols-sur-Cèze & Gard rhodanien, Beaucaire & Camargue gardoise, Sommières & Vaunage
- `serrurier/<ville>/` : une page d'accueil par commune (72 communes), avec le nom de la ville en haut de page,
  sans mention de « tout le Gard » (pratique pour les annonces Google Ads ciblées par ville)
- `notre-entreprise/`, `faq/`, `contact/`, `merci/`, `404.html`, mentions légales et confidentialité
- `assets/app.css` et `assets/app.js` : styles et scripts communs

Prestations volontairement exclues : reproduction de clés et clés de voiture.

## À compléter avant la mise en ligne

- **Nom de domaine** : les URL canoniques, le `sitemap.xml`, `robots.txt` et la redirection des formulaires (`_next`)
  utilisent l'adresse provisoire `https://teddyserruregard.netlify.app`. À remplacer par le vrai domaine.
- **Mentions légales** (`mentions-legales/index.html`) : restent `[À COMPLÉTER]` : TVA intracommunautaire, assureur, médiateur.
- **Suivi Google** : Google Tag Manager `GTM-53CVPFZZ` (le même que le site plomberie), chargé après accord cookies dans `assets/app.js`.
  Événements envoyés : `clic_appel` (clic sur un numéro) et `envoi_formulaire` (page `/merci/`).
- **Formulaires** : envoyés via FormSubmit vers sos.renov10@gmail.com (objet « serrurerie »).
- **Téléphone** : 07 54 86 49 39.
- **Nom commercial** : « Maison Ferrand Serrurier » doit être déclaré comme nom commercial de SOS RENOV (guichet unique INPI).
