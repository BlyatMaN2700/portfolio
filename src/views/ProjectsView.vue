<script setup>
import { onMounted } from 'vue'
import ProjectComponent from '@/components/ProjectComponent.vue'

onMounted(() => window.scrollTo(0, 0))
</script>

<template>
  <main>
    <div id="academique">
      <h1>Projets Académiques</h1>
      <div id="1">
        <ProjectComponent>
          <template #name>SAÉ 1.01 : Implémentation d’un besoin client</template>
          <template #descriptif>
            Réalisation d'un annuaire en langage C à partir d'un fichier .csv avec lequel
            l'utilisateur peut intéragir via la console.
          </template>
          <template #techno>
            <ul>
              <li>Langage C</li>
              <li>Code::Blocks</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.01 | Implémenter des conceptions simples
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.02 | Élaborer des conceptions simples
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.03 | Faire des essais et évaluer leurs résultats en regard des spécifications
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.01 | Initiation au développement</li>
              <li>R1.02 | Développement d’interfaces web</li>
              <li>R1.10 | Anglais</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="2">
        <ProjectComponent>
          <template #name>SAÉ 1.02 : Comparaison d’approches algorithmiques</template>
          <template #descriptif>
            Analyse et comparaison d'algorithmes de tris ainsi que réalisation d'un algorithme de
            tri différent.
          </template>
          <template #techno>
            <ul>
              <li>Python</li>
              <li>EduPython</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC12.01 | Analyser un problème avec méthode</RouterLink
                >
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }"
                  >AC12.02 | Comparer des algorithmes pour des problèmes classiques</RouterLink
                >
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC12.03 | Formaliser et mettre en oeuvre des outils mathématiques pour
                  l’informatique</RouterLink
                >
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.01 | Initiation au développement</li>
              <li>R1.03 | Introduction à l’architecture des ordinateurs</li>
              <li>R1.06 | Mathématiques discrètes</li>
              <li>R1.07 | Outils mathématiques fondamentaux</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="3">
        <ProjectComponent>
          <template #name>SAÉ 1.03 : Installation d’un poste pour le développement</template>
          <template #descriptif>
            Installation et paramétrage d'une machine virtuelle Linux.
          </template>
          <template #techno>
            <ul>
              <li>VMWare</li>
              <li>Bash</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }"
                  >AC13.01 | Identifier les différents composants d’un système numérique</RouterLink
                >
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC13.02 | Utiliser les fonctionnalités de base d’un système multitâches /
                  multiutilisateurs</RouterLink
                >
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC13.03 | Installer et configurer un système d’exploitation et des outils de
                  développement</RouterLink
                >
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.03 | Introduction à l’architecture des ordinateurs</li>
              <li>R1.04 | Introduction aux systèmes d’exploitation et à leur fonctionnement</li>
              <li>R1.10 | Anglais</li>
              <li>R1.11 | Bases de la communication</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="4">
        <ProjectComponent>
          <template #name>SAÉ 1.04 : Création d’une base de données</template>
          <template #descriptif>
            Conception et réalisation d'une base de données SQL basée sur la demande d'un client.
          </template>
          <template #techno>
            <ul>
              <li>SQL</li>
              <li>PowerAMC</li>
              <li>Oracle SQL Develloper</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC14.01 | Mettre à jour et interroger une base de données
                  relationnelle</RouterLink
                >
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC14.03 | Concevoir une base de données relationnelle à partir d’un cahier des
                  charges</RouterLink
                >
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.05 | Introduction aux bases de données et SQL</li>
              <li>R1.06 | Mathématiques discrètes</li>
              <li>R1.09 | Introduction à l’économie durable et numérique</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="5">
        <ProjectComponent>
          <template #name>SAÉ 1.05 : Recueil de besoins</template>
          <template #descriptif>
            Réalisation d'un site web basique de vente de chaussures personnalisées.
          </template>
          <template #techno>
            <ul>
              <li>HTML</li>
              <li>CSS</li>
              <li>VS Code</li>
              <li>Git</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC15.01 | Appréhender les besoins du client et de l’utilisateur
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC15.03 | Identifier les acteurs et les différentes phases d’un cycle de
                  développement
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.02 | Développement d’interfaces web</li>
              <li>R1.08 | Introduction à la gestion des organisations</li>
              <li>R1.11 | Bases de la communication</li>
            </ul>
          </template>
          <template #link>
            <h3>Lien vers le projet</h3>
            <a
              href="https://forge.univ-lyon1.fr/p2200733/sae-receuil-des-besoins-phounpadith-douangmarath-et-noa-limandas"
              target="_blank"
            >
              Dépôt Git
            </a>
          </template>
        </ProjectComponent>
      </div>
      <div id="6">
        <ProjectComponent>
          <template #name>
            SAÉ 1.06 : Découverte de l’environnement économique et écologique
          </template>
          <template #descriptif>
            Réalisation d'un rapport sur la dimension RSA d'une entreprise du numérique
          </template>
          <template #techno>
            <ul>
              <li>Microsoft Word</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.01 | Appréhender l’écosystème numérique
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.04 | Acquérir les compétences interpersonnelles pour travailler en équipe
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R1.08 | Introduction à la gestion des organisations</li>
              <li>R1.09 | Introduction à l’économie durable et numérique</li>
              <li>R1.10 | Anglais</li>
              <li>R1.11 | Bases de la communication</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="7">
        <ProjectComponent>
          <template #name>SAÉ Aide à la décision Santé</template>
          <template #descriptif>
            <p>
              Analyse des demandes du client pour la rédaction d'un cahier des charges et d'un
              dossier de gestion de projet.
            </p>
            <p>Gestion de l'équipe et répartition des tâches.</p>
            <p>Exploration de solution algorithmiques pour résoudre un problème.</p>
            <p>
              Réalisation d'une application d'aide à la décision pour les hôpitaux d'un pays en
              développement basé sur un algorithme de Djikstra suivant 3 paramètres.
            </p>
          </template>
          <template #techno>
            <ul>
              <li>Java</li>
              <li>Java Swing</li>
              <li>NetBeans</li>
              <li>Git</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.01 | Implémenter des conceptions simples
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.02 | Élaborer des conceptions simples
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.03 | Faire des essais et évaluer leurs résultats en regard des spécifications
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC11.04 | Développer des interfaces utilisateurs
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC12.01 | Analyser un problème avec méthode
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC12.02 | Comparer des algorithmes pour des problèmes classiques
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC12.02 | Comparer des algorithmes pour des problèmes classiques
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC15.01 | Appréhender les besoins du client et de l’utilisateur
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC15.02 | Mettre en place les outils de gestion de projet
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC15.03 | Identifier les acteurs et les différentes phases d’un cycle de
                  développement
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.01 | Appréhender l’écosystème numérique
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.02 | Découvrir les aptitudes requises selon les différents secteurs
                  informatiques
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.03 | Identifier les statuts, les fonctions et les rôles de chaque membre
                  d’une équipe pluridisciplinaire
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC16.04 | Acquérir les compétences interpersonnelles pour travailler en équipe
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R2.01 | Développement orienté objets</li>
              <li>R2.02 | Développement d’applications avec IHM</li>
              <li>R2.03 | Qualité de développement</li>
              <li>R2.07 | Graphes</li>
              <li>R2.08 | Outils numériques pour les statistiques descriptives</li>
              <li>R2.09 | Méthodes numériques</li>
              <li>R2.10 | Introduction à la gestion des systèmes d’information</li>
              <li>R2.11 | Introduction au droit</li>
              <li>R2.12 | Anglais</li>
              <li>R2.13 | Communication technique</li>
            </ul>
          </template>
          <template #link>
            <h3>Liens</h3>
            <a href="https://forge.univ-lyon1.fr/p2209709/sae-java" target="_blank">Dépôt Git</a>
          </template>
        </ProjectComponent>
      </div>
      <div id="8">
        <ProjectComponent>
          <template #name>SAÉ 2.03 : Installation de services réseau</template>
          <template #descriptif>
            Installation d'un réseau local ainsi que réalisation d'une notice sur cette dernière
          </template>
          <template #techno>
            <ul>
              <li>Routeur CISCO</li>
              <li>WireShark</li>
              <li>Microsoft Word</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC13.01 | Identifier les différents composants d’un système numérique
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC13.02 | Utiliser les fonctionnalités de base d’un système multitâches /
                  multiutilisateur
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC13.03 | Installer et configurer un système d’exploitation et des outils de
                  développement
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC13.04 | Configurer un poste de travail dans un réseau d’entreprise
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R2.04 | Communication et fonctionnement bas niveau</li>
              <li>R2.05 | Introduction aux services réseaux</li>
              <li>R2.12 | Anglais</li>
              <li>R2.13 | Communication technique</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="9">
        <ProjectComponent>
          <template #name>SAÉ 2.04 : Exploitation d’une base de données</template>
          <template #descriptif>
            Ecriture de requêtes SQL pour exploiter une base de données déjà existante.
          </template>
          <template #techno>
            <ul>
              <li>SQL</li>
              <li>Oracle SQL Develloper</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC14.01 | Mettre à jour et interroger une base de données relationnelle
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC14.02 | Visualiser des données
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC14.03 | Concevoir une base de données relationnelle à partir d’un cahier des
                  charges
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R2.06 | Exploitation d’une base de données</li>
              <li>R1.08 | Introduction à la gestion des organisations</li>
              <li>R2.10 | Introduction à la gestion des systèmes d’information</li>
              <li>R2.12 | Anglais</li>
            </ul>
          </template>
        </ProjectComponent>
      </div>
      <div id="10">
        <ProjectComponent>
          <template #name>SAÉ Everlong</template>
          <template #descriptif>
            Réalisation de toutes les étapes d'un cycle de vie de projet pour un site de musique
            participatif permettant aux utilisateurs de créer facilement des pages pour leurs
            artistes, albums ou titre préférés, y mettre des commentaires et des annecdotes.
          </template>
          <template #techno>
            <ul>
              <li>HTML</li>
              <li>JavaScript</li>
              <li>PHP</li>
              <li>CSS</li>
              <li>SQL</li>
              <li>PHPmyadmin</li>
              <li>bitrix24</li>
            </ul>
          </template>
          <template #competences>
            <ul>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC21.01 | Élaborer et implémenter les spécifications fonctionnelles et non
                  fonctionnelles à partir des exigences
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC21.02 | Appliquer des principes d’accessibilité et d’ergonomie
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC21.03 | Adopter de bonnes pratiques de conception et de programmation
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#realiser' }">
                  AC21.04 | Vérifier et valider la qualité de l’application par les tests
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC22.01 | Choisir des structures de données complexes adaptées au problème
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC22.02 | Utiliser des techniques algorithmiques adaptées pour des problèmes
                  complexes
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC22.03 | Comprendre les enjeux et moyens de sécurisation des données et du code
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#optimiser' }">
                  AC22.04 | Évaluer l’impact environnemental et sociétal des solutions proposées
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC23.01 | Concevoir et développer des applications communicantes
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC23.02 | Utiliser des serveurs et des services réseaux virtualisés
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC23.03 | Sécuriser les services et données d’un système
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#administrer' }">
                  AC24.01 | Optimiser les modèles de données de l’entreprise
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC24.02 | Assurer la sécurité des données
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC24.03 | Organiser la restitution de données à travers la programmation et la
                  visualisation
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC24.04 | Manipuler des données hétérogènes
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#gerer' }">
                  AC25.02 | Formaliser les besoins du client et de l’utilisateur
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC25.03 | Identifier les critères de faisabilité d’un projet informatique
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#conduire' }">
                  AC25.04 | Définir et mettre en œuvre une démarche de suivi de projet
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC26.02 | Appliquer une démarche pour intégrer une équipe informatique au sein
                  d’une organisation
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC26.03 | Mobiliser les compétences interpersonnelles pour travailler dans une
                  équipe informatique
                </RouterLink>
              </li>
              <li>
                <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                  AC26.04 | Rendre compte de son activité professionnelle
                </RouterLink>
              </li>
            </ul>
          </template>
          <template #resources>
            <ul>
              <li>R3.01 | Développement web</li>
              <li>R3.02 | Développement efficace</li>
              <li>R3.03 | Analyse</li>
              <li>R3.04 | Qualité de développement</li>
              <li>R4.05 | Anglais</li>
              <li>R3.06 | Architecture des réseaux</li>
              <li>R3.07 | SQL dans un langage de programmation</li>
              <li>R3.09 | Cryptographie et sécurité</li>
              <li>R3.10 | Management des systèmes d’information</li>
              <li>R3.12 | Anglais</li>
              <li>R3.13 | Communication professionnelle</li>
              <li>R4.Admin.08 | Cryptographie et sécurité</li>
              <li>R4.Admin.09 | Réseau avancé</li>
              <li>R4.Admin.10 | Analyse et visualisation avancée des données</li>
              <li>R4.Admin.11 | Management avancé des systèmes d’information</li>
            </ul>
          </template>
          <template #link>
            <a href="https://forge.univ-lyon1.fr/groupe-big-sae/big-sae" target="_blank"
              >Dépôt Git</a
            >
          </template>
        </ProjectComponent>
      </div>
    </div>
    <div id="pro">
      <h1>Projets Professionnels</h1>
      <ProjectComponent>
        <template #name>Tableaux de bord</template>
        <template #descriptif>
          Réalisation de tableaux de bord pour Izypay afin d'aider à la communication ainsi qu'à la
          gestion du parc de terminaux de l'entreprise.
        </template>
        <template #techno>
          <ul>
            <li>SQL</li>
            <li>MetaBase</li>
            <li>Grafana</li>
            <li>Microsoft Excel</li>
          </ul>
        </template>
        <template #competences>
          <ul>
            <li>
              <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                Optimiser
              </RouterLink>
            </li>
            <li>
              <RouterLink :to="{ name: 'competences', hash: '#collaborer' }"> Gérer </RouterLink>
            </li>
            <li>
              <RouterLink :to="{ name: 'competences', hash: '#collaborer' }">
                Collaborer
              </RouterLink>
            </li>
          </ul>
        </template>
        <template #resources>
          <ul>
            <li>Base de données</li>
            <li>SQL</li>
            <li>Informatique décisionnel</li>
          </ul>
        </template>
      </ProjectComponent>
    </div>
  </main>
</template>
