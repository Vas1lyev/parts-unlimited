<p align="center">
  <img src="assets/parts-unlimited-logo.svg" width="128" alt="Parts Unlimited logo">
</p>

# Parts Unlimited

Parts Unlimited is an educational software engineering project for practicing
project planning, documentation, continuous integration, and delivery workflows.

The project models an online auto-parts store using the original Microsoft
Parts Unlimited training application based on ASP.NET 4.5. GitHub is used for
source control, documentation, work tracking, delivery planning, and CI.

## Project goals

- maintain a clear and searchable project knowledge base;
- organize product work with issues, iterations, and project views;
- build and test the application automatically on every relevant change;
- visualize milestones, dependencies, and team workload;
- keep all implementation and planning artifacts traceable.

## Planned solution structure

```text
PartsUnlimited-aspnet45/src/    application source code
PartsUnlimited-aspnet45/test/   automated tests
docs/                         project records and supporting documentation
assets/                       project branding and shared media
```

## Technology

- .NET Framework 4.5
- ASP.NET MVC
- GitHub Projects and Issues
- GitHub Actions

## Documentation

The project knowledge base is maintained in the
[GitHub Wiki](https://github.com/Vas1lyev/parts-unlimited/wiki).
The setup record for the first practical work is available in
[Practice 1.1](docs/practices/1.1-project-setup.md).

Результат работы с Wiki описан в документе
[Практическая работа 1.2](docs/practices/1.2-wiki.md).

Подготовка тестовых данных и гибкое планирование описаны в документе
[Практическая работа 2.1](docs/practices/2.1-planning.md).

Настройка канбан-доски, мониторинга и командного процесса описана в документе
[Практическая работа 2.2](docs/practices/2.2-kanban-monitoring.md).

Управление календарём, внешней командой и зависимостями поставки описано в
документе [Практическая работа 3](docs/practices/3-delivery-planning.md).

Настройка локального агента сборочного конвейера описана в документе
[Практическая работа 4.0](docs/practices/4.0-self-hosted-runner.md).

Сборка, модульное тестирование и автоматический запуск CI описаны в документе
[Практическая работа 4.1](docs/practices/4.1-continuous-integration.md).

## Текущее состояние

Репозиторий, Wiki и проектное пространство настроены. Приложение собирается и
тестируется автоматически при изменениях в ветке `main`.
