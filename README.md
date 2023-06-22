# k8s-dev-survival-kit-talk

You can find here the slides and the sample code of my talk "Kubernetes Developer Survival Kit Talk" that I presented on enterJS in Darmstad at 22nd June 2023.

The demo application based on Java and Spring Boot is in folder 'sample-app'.
A second demo application based on NodeJS and ExpressJs is in the folder 'sample-js-app'

Furthermore, there exists an sample how to mock dependet systems for the local development with Mockserver.


## Tools, that are shown in the presentation
- [Docker CE](https://docs.docker.com/get-started/overview/)
- [Helm Charts](https://helm.sh/)
- [Trivy](https://aquasecurity.github.io/trivy/)
- [Helm Secret Plugin](https://github.com/jkroepke/helm-secrets)
- [Docker Compose](https://docs.docker.com/compose/)
- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [K9s](https://k9scli.io/)
- [K8s Lens](https://k8slens.dev/) / [OpenLens](https://github.com/MuhammedKalkan/OpenLens)
- [Monokle Desktop](https://monokle.io/desktop)
- [Mockserver](https://www.mock-server.com)

## Tools, that are Java ecosystem specific
- [Docker Maven Plugin](https://dmp.fabric8.io/)
- [Helm Maven Plugin](https://github.com/kokuwaio/helm-maven-plugin)
- [Spring Boot Maven Plugin](https://docs.spring.io/spring-boot/docs/current/maven-plugin/reference/htmlsingle/)
- [Spring Boot Docker Compose Support](https://docs.spring.io/spring-boot/docs/3.1.0/reference/html/features.html#features.docker-compose)

## Further Information
- [12 Factor App](https://12factor.net/)
- [A visual guide on troubleshooting Kubernetes deployments](https://learnk8s.io/troubleshooting-deployments)
- [Kubernetes Documentation - Troubleshooting Applications](https://kubernetes.io/docs/tasks/debug/debug-application/)
- [Kubernetes Feature - Debug Container](https://kubernetes.io/docs/tasks/debug/debug-application/debug-running-pod/#ephemeral-container)
- [Article](https://www.informatik-aktuell.de/entwicklung/methoden/container-images-deep-dive-101-wege-zum-bauen-und-bereitstellen.html) about Container Image Build Tools (German)

## More good talks to this topic
- [What's going on in my cluster? by Matthias Haeussler](https://speakerdeck.com/maeddes/whats-going-on-in-my-cluster)
- [Wenn ich das nur vorher gewusst hätte: Kubernetes für Entwickler by Stefan Schlott (German)](https://entwicklertag.de/karlsruhe/2022/Wenn_ich_das_nur_vorher_gewusst_haette-_Kubernetes_fuer_Entwickler/Kubernetes%20f%C3%BCr%20Entwickler.pdf)
- Kubernetes-Lektionen aus der Wolke by Jochen Mader
- [We Moved one Java Product to Kubernetes and This Is What We Learned by Carlos Sanchez](https://vimeo.com/747698681)
- [Secrets of Performance Tuning Java on Kubernetes by Bruno Borges](https://vimeo.com/748031919)