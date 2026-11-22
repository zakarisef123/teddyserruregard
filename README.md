# Teddy-ets Serrurerie — Gard (30)

Site statique (HTML/CSS/JS, sans build) de Teddy-ets (SOS RENOV), entreprise de serrurerie à Nîmes et dans tout le Gard (30).
Même structure et même charte graphique que le site plomberie Teddy-ets.

## Structure

- `index.html` : accueil
- `urgence-serrurier/`, `prestations/` et une page par prestation :
  ouverture de porte, changement de serrure, cylindre (barillet), blindage de porte, porte blindée,
  dépannage après effraction, verrous & renforts, rideau métallique, coffre-fort, contrôle d'accès & serrure connectée
- `zones-intervention/` et une page par secteur : Nîmes, Alès & Cévennes, Uzès & Pont du Gard,
  Bagnols-sur-Cèze & Gard rhodanien, Beaucaire & Camargue gardoise, Sommières & Vaunage
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
