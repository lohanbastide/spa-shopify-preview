# Landing institut beauté / spa — sections Shopify

Style « Soft UI Evolution » : rose poudré `#E8B4B8`, sauge `#A8D5BA`, or `#D4AF37`, fond `#FFF5F5`, texte `#2D3436`.
Typographies : Cormorant Garamond (titres) et Montserrat (texte).

## Contenu

| Fichier | Rôle |
|---|---|
| `sections/spa-hero.liquid` | Hero : titre, 2 boutons, arguments de confiance, image en forme organique |
| `sections/spa-services.liquid` | Cartes de soins (icône, description, durée, prix) |
| `sections/spa-testimonials.liquid` | Avis clients + appel à réserver répété |
| `sections/spa-booking.liquid` | Formulaire de demande de rendez-vous (formulaire de contact Shopify) |
| `sections/spa-contact.liquid` | Adresse, téléphone, e-mail, horaires, plan Google Maps |
| `snippets/spa-icon.liquid` | Icônes Lucide en SVG |
| `assets/spa-landing.css` | Styles, tous préfixés `.spa` |
| `templates/page.spa.json` | Modèle de page qui assemble les 5 sections |
| `index.html` | Aperçu statique (GitHub Pages). **Ne pas téléverser dans le thème Shopify.** |

## Installation (thème Online Store 2.0, par exemple Dawn)

1. Admin Shopify → **Boutique en ligne → Thèmes** → `…` → **Dupliquer** le thème actif (travailler sur la copie).
2. Sur la copie : `…` → **Modifier le code**.
3. Créer chaque fichier dans le dossier correspondant (`sections/`, `snippets/`, `assets/`, `templates/`) et coller son contenu.
4. **Pages → Ajouter une page**, puis choisir le modèle **spa** dans « Modèle de thème ».
5. Ouvrir l'éditeur de thème sur cette page pour remplacer textes, prix et images.

Les 5 sections sont aussi disponibles séparément dans l'éditeur (« Ajouter une section → Spa · … »).

## À faire avant publication

- Remplacer les **avis d'exemple** par de vrais avis clients, publiés avec leur accord.
- Ajouter l'image du hero (portrait 4:5, au moins 1000 px de large) et vérifier son texte alternatif.
- Saisir adresse, téléphone, e-mail et horaires réels.
- Réservation : les demandes arrivent par e-mail à l'adresse de contact du magasin, et le créneau se confirme manuellement. Pour une réservation avec agenda en temps réel, il faut une application Shopify dédiée.
- Plan Google Maps : contenu tiers, à mentionner dans la politique de cookies (ou décocher l'option).
