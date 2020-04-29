pipeline {
  agent any
  stages {
    stage('Holo') {
      steps {
        doktor server: 'sandbox', markdownIncludePatterns: ['glob:**.md'], markdownExcludePatterns: ['glob:README.md'], asciidocIncludePatterns: ['glob:**.adoc', 'glob:**.asc'], asciidocExcludePatterns: ['glob:LICENSE.adoc', 'glob:CONTRIBUTING.asc']
      }
    }

  }
}
