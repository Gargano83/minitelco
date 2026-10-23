# MiniTelco

MiniTelco è un operatore di rete in miniatura: una rete fissa, poi mobile, costruita in laboratorio e gestita da sistemi OSS sviluppati in proprio, con il ciclo di vita del cliente sotto monitoraggio.

È un progetto personale di studio sulla network automation e sulla service assurance in ambito Telco. Riproduce protocolli, comportamenti e guasti, non volumi di traffico reali. Non è affiliato ad alcun operatore.

## Stato

Fase 0 del percorso, tappa M0 in corso: ambiente di lavoro, repository e piano di indirizzamento.

## Struttura

```
minitelco/
├── .github/workflows/    pipeline GitHub Actions
├── docs/                 architettura, decisioni, piano di indirizzamento
├── network/              rete come codice: topologie, inventario, template, automazione, test
├── network-services/     configurazioni di FreeRADIUS, accel-ppp, GenieACS, DHCP e DNS
├── services/             servizi OSS in Java (progetto Maven multi-modulo)
├── observability/        metriche, dashboard, telemetria e log
└── deploy/               Docker Compose; più avanti Helm e Terraform
```

Ogni cartella ha un proprio README che dice cosa contiene e in quale tappa viene realizzata.

