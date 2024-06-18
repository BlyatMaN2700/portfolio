<script setup>
import { onMounted } from 'vue'
import MainCompetence from '@/components/MainCompetence.vue'
import SubCompetence from '@/components/SubCompetence.vue'
import TechnoCategory from '@/components/TechnoCategory.vue'

onMounted(() => window.scrollTo(0, 0))
</script>

<template>
  <main>
    <div class="competence" id="realiser">
      <h1>Réaliser</h1>
      <p>Développer une solution informatique pour un client.</p>
      <MainCompetence>
        <template #name> Niveau 1 : Développer des applications informatiques simples </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>AC11.01 | Implémenter des conceptions simples</template>
                <template #resources>
                  <ul>
                    <li>R1.01 : Initiation au développement</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#1' }">
                        SAÉ Implémentation d’un besoin client
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Cette compétence ayant déjà été acquise durant mon lycée et mes notes étant
                      très bonnes je considère cette compétence maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC11.02 | Elaborer des conceptions simples</template>
                <template #resources>
                  <ul>
                    <li>R1.01 : Initiation au développement</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#1' }">
                        SAÉ Implémentation d’un besoin client
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Cette compétence ayant déjà été acquise durant mon lycée et mes notes étant
                      très bonnes je considère cette compétence maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC11.03 | Faire des essais et évaluer leurs résultats en regard des spécifications
                </template>
                <template #resources>
                  <ul>
                    <li>R1.01 : Initiation au développement</li>
                    <li>R1.02 : Développement d’interfaces web</li>
                    <li>R1.10 : Anglais</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#1' }">
                        SAÉ Implémentation d’un besoin client
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Cette compétence ayant déjà été acquise durant mon lycée et mes notes étant
                      très bonnes je considère cette compétence maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC11.04 | Implémenter des conceptions simples</template>
                <template #resources>
                  <ul>
                    <li>R1.02 : Développement d’interfaces web</li>
                    <li>R1.10 : Anglais</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#1' }">
                        SAÉ Implémentation d’un besoin client
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Cette compétence ayant déjà été acquise durant mon lycée et mes notes étant
                      très bonnes je considère cette compétence maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Maîtrisé </template>
      </MainCompetence>
      <MainCompetence>
        <template #name>
          Niveau 2 : Partir des exigences et aller jusqu'à une application complète
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC21.01 | Élaborer et implémenter les spécifications fonctionnelles et non
                  fonctionnelles à partir des exigences
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.03 : Analyse</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC21.02 | Appliquer des principes d’accessibilité et d’ergonomie
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC21.03 | Adopter de bonnes pratiques de conception et de programmation
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.02 : Développement efficace</li>
                    <li>R3.04 : Qualité de développement</li>
                    <li>R3.11 : Droit des contrats et du numérique</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Je maîtrise bien certains points tout en ayant des lacunes sur d'autres que je
                      peine à combler notamment en qualité de développement, je considère donc cette
                      compétence comme partiellement acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Partiellement Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC21.04 | Vérifier et valider la qualité de l’application par les tests
                </template>
                <template #resources>
                  <ul>
                    <li>R3.04 : Qualité de développement</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      J'ai du mal à prendre le réflexe de réaliser des tests pertinent et à
                      appliquer certains bons principes de dévellopement, je considère cette
                      compétence comme en cours d'acquisition.
                    </li>
                  </ul>
                </template>
                <template #level>En Cours d'Acquisition</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Partiellement Acquis </template>
      </MainCompetence>
      <div hidden>
        <MainCompetence>
          <template #name>
            Niveau 3 : Adapter des applications sur un ensemble de supports
          </template>
          <template #subComp>
            <ul>
              <li>
                <SubCompetence>
                  <template #name
                    >AC31.01 | Choisir et implémenter les architectures adaptées</template
                  >
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>AC31.02 | Faire évoluer une application existante</template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC31.03 | Intégrer des solutions dans un environnement de production
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
            </ul>
          </template>
          <template #level> Acquis </template>
        </MainCompetence>
      </div>
    </div>

    <div class="competence" id="optimiser">
      <h1>Optimiser</h1>
      <p>Proposer des applications informatiques optimisées en fonction de critères spécifiques.</p>
      <MainCompetence>
        <template #name> Niveau 1 : Appréhender er construire des algorithmes </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>AC12.01 | Analyser un problème avec méthode</template>
                <template #resources>
                  <ul>
                    <li>R1.01 : Initiation au développement</li>
                    <li>R1.03 : Introduction à l’architecture des ordinateurs</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#2' }">
                        SAÉ 1.02 : Comparaison d’approches algorithmiques
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC12.02 | Comparer des algorithmes pour des problèmes classiques
                </template>
                <template #resources>
                  <ul>
                    <li>R1.01 : Initiation au développement</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#2' }">
                        SAÉ 1.02 : Comparaison d’approches algorithmiques
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC12.03 | Formaliser et mettre en œuvre des outils mathématiques pour
                  l’informatique
                </template>
                <template #resources>
                  <ul>
                    <li>R1.06 : Mathématiques discrètes</li>
                    <li>R1.07 : Outils mathématiques fondamentaux</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#2' }">
                        SAÉ 1.02 : Comparaison d’approches algorithmiques
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <MainCompetence>
        <template #name>
          Niveau 2 : Sélectionner les algorithmes adéquats pour répondre à un problème donné
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC22.01 | Choisir des structures de données complexes adaptées au problème
                </template>
                <template #resources>
                  <ul>
                    <li>R3.02 : Développement efficace</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC22.02 | Utiliser des techniques algorithmiques adaptées pour des problèmes
                  complexes
                </template>
                <template #resources>
                  <ul>
                    <li>R3.02 : Développement efficace</li>
                    <li>R3.06 : Architecture des réseaux</li>
                    <li>R3.08 : Probabilités</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC22.03 | Comprendre les enjeux et moyens de sécurisation des données et du code
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.09 : Cryptographie et sécurité</li>
                    <li>R3.12 : Anglais</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      J'ai compris l'idée générale mais il me reste quand même des points assez
                      flous, notamment en cryptographie, sur lesquels il faudrait que je m'améliore.
                      Je considère donc la compétence comme partiellement acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Partiellement Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC22.04 | Évaluer l’impact environnemental et sociétal des solutions proposées
                </template>
                <template #resources>
                  <ul>
                    <li>R3.02 : Développement efficace</li>
                    <li>R3.03 : Analyse</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      J'ai beaucoup de mal à comprendre la plupart de ce qui a été fait en analyse
                      et malgré mes notes acceptables je ne pense pas pouvoir dire que cette
                      compétence est acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Partiellement Acquis</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Partiellement Acquis </template>
      </MainCompetence>
    </div>

    <div class="competence" id="administrer">
      <h1>Administrer</h1>
      <p>
        Installer, configurer, mettre à disposition, maintenir en conditions opérationnelles des
        infrastructures, des services et des réseaux et optimiser le système informatique d’une
        organisation.
      </p>
      <MainCompetence>
        <template #name> Niveau 1 : Installer et configurer un poste de travail </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC13.01 | Identifier les différents composants d’un système numérique
                </template>
                <template #resources>
                  <ul>
                    <li>R1.03 : Introduction à l’architecture des ordinateurs</li>
                    <li>R1.10 : Anglais</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#3' }">
                        SAÉ 1.03 : Installation d’un poste pour le développement
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC13.02 | Utiliser les fonctionnalités de base d’un système multitâches /
                  multiutilisateurs
                </template>
                <template #resources>
                  <ul>
                    <li>
                      R1.04 : Introduction aux systèmes d’exploitation et à leur fonctionnement
                    </li>
                    <li>R1.10 : Anglais</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#3' }">
                        SAÉ 1.03 : Installation d’un poste pour le développement
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC13.03 | Installer et configurer un système d’exploitation et des outils de
                  développement
                </template>
                <template #resources>
                  <ul>
                    <li>
                      R1.04 : Introduction aux systèmes d’exploitation et à leur fonctionnement
                    </li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#3' }">
                        SAÉ 1.03 : Installation d’un poste pour le développement
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC13.04 | Configurer un poste de travail dans un réseau d’entreprise
                </template>
                <template #resources>
                  <ul>
                    <li>R1.11 : Bases de la communication</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources liées ainsi que mon ressenti général me font
                      considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <MainCompetence>
        <template #name> Niveau 2 : Déployer des services dans une architecture réseau </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC23.01 | Concevoir et développer des applications communicantes
                </template>
                <template #resources>
                  <ul>
                    <li>R3.05 : Programmation système</li>
                    <li>R3.06 : Architecture des réseaux</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC23.02 | Utiliser des serveurs et des services réseaux virtualisés
                </template>
                <template #resources>
                  <ul>
                    <li>R3.06 : Architecture des réseaux</li>
                    <li>R3.12 : Anglais</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC23.03 | Sécuriser les services et données d’un système
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.09 : Cryptographie et sécurité</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Il me reste des lacunes en réseau et en cryptographie qui me font considérer
                      cette compétence comme partiellement acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Partiellement Acquis</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <div hidden>
        <MainCompetence>
          <template #name>
            Niveau 3 : Faire évoluer et maintenir un système informatique communicant en conditions
            opérationnelles
          </template>
          <template #subComp>
            <ul>
              <li>
                <SubCompetence>
                  <template #name>AC33.01 | Créer des processus de traitement automatisé</template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC33.02 | Configurer un serveur et des services réseaux de manière avancée
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC33.03 | Appliquer une politique de sécurité au niveau de l’infrastructure
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC33.04 | Déployer et maintenir un réseau d’organisation en fonction de ses
                    besoins
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
            </ul>
          </template>
          <template #level> Acquis </template>
        </MainCompetence>
      </div>
    </div>

    <div class="competence" id="gerer">
      <h1>Gérer</h1>
      <p>
        Concevoir, gérer, administrer et exploiter les données de l’entreprise et mettre à
        disposition toutes les informations pour un bon pilotage de l’entreprise.
      </p>
      <MainCompetence>
        <template #name>
          Niveau 1 : Concevoir et mettre en place une base de données à partir d'un cahier des
          charges client
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC14.01 | Mettre à jour et interroger une base de données relationnelle
                </template>
                <template #resources>
                  <ul>
                    <li>R1.05 : Introduction aux bases de données et SQL</li>
                    <li>R1.06 : Mathématiques discrètes</li>
                    <li>R1.09 : Introduction à l’économie durable et numérique</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#4' }">
                        SAÉ 1.04 : Création d’une base de données
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC14.02 | Visualiser des données</template>
                <template #resources>
                  <ul>
                    <li>R1.09 : Introduction à l’économie durable et numérique</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources liées ainsi que mon ressenti général me font
                      considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC14.03 | Concevoir une base de données relationnelle à partir d’un cahier des
                  charges
                </template>
                <template #resources>
                  <ul>
                    <li>R1.05 : Introduction aux bases de données et SQL</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#4' }">
                        SAÉ 1.04 : Création d’une base de données
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      me font considérer cette compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Maitrisé </template>
      </MainCompetence>
      <MainCompetence>
        <template #name>
          Niveau 2 : Optimiser une base de données, interagir avec une application et mettre en
          oeuvre la sécurité
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC24.01 | Optimiser les modèles de données de l’entreprise
                </template>
                <template #resources>
                  <ul>
                    <li>R3.07 : SQL dans un langage de programmation</li>
                    <li>R3.08 : Probabilités</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes notes dans les ressources et projets liés ainsi que mon ressenti général
                      et mon expérience en entreprise me font considérer cette compétence comme
                      acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC24.02 | Assurer la sécurité des données </template>
                <template #resources>
                  <ul>
                    <li>R3.07 : SQL dans un langage de programmation</li>
                    <li>R3.09 : Cryptographie et sécurité</li>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.11 : Droit des contrats et du numérique</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Mes lacunes, notamment en cryptographie, me font considérer cette compétence
                      comme partiellement acquise.
                    </li>
                  </ul>
                </template>
                <template #level>Partiellement Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC24.03 | Organiser la restitution de données à travers la programmation et la
                  visualisation
                </template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.07 : SQL dans un langage de programmation</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      Il me reste encore du mal à penser à des graphiques intéressants mais je
                      réussis bien à concevoir ceux que l'on me demande, j'ai pu le voir en
                      entreprise. Je considère cette compétence seulement comme acquise mais pas
                      loin d'être maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Acquis</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC24.04 | Manipuler des données hétérogènes</template>
                <template #resources>
                  <ul>
                    <li>R3.01 : Développement web</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #feeling>
                  <ul>
                    <li>
                      La manipulation de données est très intuitive pour moi, je considère cette
                      compétence comme maîtrisée.
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
    </div>

    <div class="competence" id="conduire">
      <h1>Conduire</h1>
      <p>
        Satisfaire les besoins des utilisateurs au regard de la chaîne de valeur du client,
        organiser et piloter un projet informatique avec des méthodes classiques ou agiles.
      </p>
      <MainCompetence>
        <template #name>
          Niveau 1 : Identifier les besoins métiers des clients et des utilisateurs
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC15.01 | Appréhender les besoins du client et de l'utilisateur
                </template>
                <template #resources>
                  <ul>
                    <li>R1.02 : Développement d’interfaces web</li>
                    <li>R1.08 : Introduction à la gestion des organisations</li>
                    <li>R1.11 : Bases de la communication</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#5' }">
                        SAÉ 1.05 : Recueil de besoins
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC15.02 | Mettre en place les outils de gestion de projet</template>
                <template #resources>
                  <ul>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC15.03 | Identifier les acteurs et les différentes phases d’un cycle de
                  développement
                </template>
                <template #resources>
                  <ul>
                    <li>R1.11 : Bases de la communication</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#5' }">
                        SAÉ 1.05 : Recueil de besoins
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <MainCompetence>
        <template #name>
          Niveau 2 : Appliquer une démarche de suivi de projet en fonction des besoins métiers des
          clients et des utilisateurs
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC25.01 | Identifier les processus présents dans une organisation en vue
                  d’améliorer les systèmes d’information
                </template>
                <template #resources>
                  <ul>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC25.02 | Formaliser les besoins du client et de l'utilisateur
                </template>
                <template #resources>
                  <ul>
                    <li>R3.03 : Analyse</li>
                    <li>R3.11 : Droit des contrats et du numérique</li>
                    <li>R3.12 : Anglais</li>
                    <li>R3.13 : Communication professionnelle</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC25.03 | Identifier les critères de faisabilité d’un projet informatique
                </template>
                <template #resources>
                  <ul>
                    <li>R3.03 : Analyse</li>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC25.04 | Définir et mettre en œuvre une démarche de suivi de projet
                </template>
                <template #resources>
                  <ul>
                    <li>R3.04 : Qualité de développement</li>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
    </div>

    <div class="competence" id="collaborer">
      <h1>Collaborer</h1>
      <p>
        Acquérir, développer et exploiter les aptitudes nécessaires pour travailler efficacement
        dans une équipe informatique.
      </p>
      <MainCompetence>
        <template #name>
          Niveau 1 : Identifier ses aptitudes pour travailler dans une équipe
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>AC16.01 | Appréhender l’écosystème numérique</template>
                <template #resources>
                  <ul>
                    <li>R1.02 : Développement d’interfaces web</li>
                    <li>R1.08 : Introduction à la gestion des organisations</li>
                    <li>R1.09 : Introduction à l’économie durable et numérique</li>
                    <li>R1.11 : Bases de la communication</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#6' }">
                        SAÉ 1.06 : Découverte de l’environnement économique et écologique
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC16.02 | Découvrir les aptitudes requises selon les différents secteurs
                  informatiques
                </template>
                <template #resources>
                  <ul>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC16.03 | Identifier les statuts, les fonctions et les rôles de chaque membre
                  d’une équipe pluridisciplinaire
                </template>
                <template #resources>
                  <ul>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC16.04 | Acquérir les compétences interpersonnelles pour travailler en équipe
                </template>
                <template #resources>
                  <ul>
                    <li>R1.10 : Anglais</li>
                    <li>R1.11 : Bases de la communication</li>
                    <li>R1.12 : Projet professionnel et personnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#6' }">
                        SAÉ 1.06 : Découverte de l’environnement économique et écologique
                      </RouterLink>
                    </li>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#7' }">
                        SAÉ Aide à la décision Santé
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <MainCompetence>
        <template #name>
          Niveau 2 : Situer son rôle et ses missions au sein d'une équipe informatique
        </template>
        <template #subComp>
          <ul>
            <li>
              <SubCompetence>
                <template #name>
                  AC26.01 | Comprendre la diversité, la structure et la dimension de l’informatique
                  dans une organisation
                </template>
                <template #resources>
                  <ul>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>Aucun projets</li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC26.02 | Appliquer une démarche pour intégrer une équipe informatique au sein
                  d’une organisation
                </template>
                <template #resources>
                  <ul>
                    <li>R3.04 : Qualité de développement</li>
                    <li>R3.12 : Anglais</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>
                  AC26.03 | Mobiliser les compétences interpersonnelles pour travailler dans une
                  équipe informatique
                </template>
                <template #resources>
                  <ul>
                    <li>R3.10 : Management des systèmes d’information</li>
                    <li>R3.12 : Anglais</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
            <li>
              <SubCompetence>
                <template #name>AC26.04 | Rendre compte de son activité professionnelle</template>
                <template #resources>
                  <ul>
                    <li>R3.12 : Anglais</li>
                    <li>R3.14 : Projet personnel et professionnel</li>
                  </ul>
                </template>
                <template #projects>
                  <ul>
                    <li>
                      <RouterLink :to="{ name: 'projects', hash: '#10' }">
                        SAÉ Everlong
                      </RouterLink>
                    </li>
                  </ul>
                </template>
                <template #level>Maîtrisé</template>
              </SubCompetence>
            </li>
          </ul>
        </template>
        <template #level> Acquis </template>
      </MainCompetence>
      <div hidden>
        <MainCompetence>
          <template #name> Niveau 3 : Manager un équipe informatique </template>
          <template #subComp>
            <ul>
              <li>
                <SubCompetence>
                  <template #name>
                    AC36.01 | Organiser et partager une veille technologique et informationnelle
                    dans une organisation
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC36.02 | Identifier les enjeux de l’économie de l’innovation numérique
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC36.03 | Guider la conduite du changement informatique au sein d’une
                    organisation
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
              <li>
                <SubCompetence>
                  <template #name>
                    AC36.04 | Accompagner le management de projet informatique
                  </template>
                  <template #level>Maîtrisé</template>
                </SubCompetence>
              </li>
            </ul>
          </template>
          <template #level> Acquis </template>
        </MainCompetence>
      </div>
    </div>

    <div class="competence">
      <h1>Technologies connues</h1>
      <div id="techno">
        <TechnoCategory>
          <template #name>Web</template>
          <template #techno>
            <ul>
              <li>HTML</li>
              <li>JavaScript</li>
              <li>CSS</li>
              <li>PHP</li>
              <li>PHPmyadmin</li>
            </ul>
          </template>
        </TechnoCategory>
        <TechnoCategory>
          <template #name>Frameworks</template>
          <template #techno>
            <ul>
              <li>Symfony</li>
              <li>Vue js</li>
              <li>Maven</li>
            </ul>
          </template>
        </TechnoCategory>
        <TechnoCategory>
          <template #name>Langages Applicatifs</template>
          <template #techno>
            <ul>
              <li>Python</li>
              <li>Java</li>
              <li>C</li>
            </ul>
          </template>
        </TechnoCategory>
        <TechnoCategory>
          <template #name>Base de données</template>
          <template #techno>
            <ul>
              <li>SQL</li>
              <li>PL/SQL</li>
              <li>MongoDB</li>
            </ul>
          </template>
        </TechnoCategory>
        <TechnoCategory>
          <template #name>Reporting</template>
          <template #techno>
            <ul>
              <li>Power BI</li>
              <li>Grafana</li>
              <li>Metabase</li>
              <li>Microsoft Report Builder</li>
            </ul>
          </template>
        </TechnoCategory>
        <TechnoCategory>
          <template #name>IDE</template>
          <template #techno>
            <ul>
              <li>VS Code</li>
              <li>Code::Blocks</li>
              <li>NetBeans</li>
              <li>PHP Storm</li>
            </ul>
          </template>
        </TechnoCategory>
      </div>
    </div>
  </main>
</template>

<style>
h1 {
  color: pink;
}

.level {
  color: cyan;
}

.competence {
  background-color: var(--vt-c-card);
  border-radius: 30px;
  padding: 30px;
  margin: 20px;
  margin-top: 40px;
}

#techno {
  display: grid;
  grid-template-columns: 30% 30% 30%;
  padding: 15px;
}
</style>
