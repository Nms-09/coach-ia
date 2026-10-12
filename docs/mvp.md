# Cadrage du Projet : Coach Virtuel

## Le Problème

Une personne décrit son niveau, son matériel, son objectif et ses jours disponibles.  
Le coach lui propose un programme de musculation ou de calisthénie adapté, s’appuie sur des sources vérifiées pour répondre à ses questions, et calcule des indicateurs clés (ex. volume hebdomadaire par groupe musculaire).

---

## Périmètre du MVP (Etape 4 MLOps)

1. **RAG documentaire** : Répond aux questions d'entraînement en citant explicitement ses sources.
2. **Génération de programme** : Produit un planning hebdomadaire au format JSON structuré et validé.
3. **Agent outillé (Tools)** :
   * Recherche d'exercices adaptés au matériel disponible.
   * Calcul automatique du volume d'entraînement.
   * Conseils nutritionnels simples basés sur les objectifs.