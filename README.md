Be sure to review the [OpenMRS 3 Frontend Developer Documentation](https://o3-docs.openmrs.org) :teacher:	

![OpenMRS CI](https://github.com/openmrs/openmrs-esm-patient-chart/actions/workflows/ci.yml/badge.svg)

# OpenMRS ESM Patient Chart

The `openmrs-esm-patient-chart` is a frontend module for the OpenMRS SPA. It contains various microfrontends that constitute widgets in a patient dashboard. These widgets include:

- [Allergies](packages/esm-patient-allergies-app/README.md)
- [Attachments](packages/esm-patient-attachments-app/README.md)
- [Biometrics](packages/esm-patient-biometrics-app/README.md)
- [Conditions](packages/esm-patient-conditions-app/README.md)
- [Forms](packages/esm-patient-forms-app/README.md)
- [Immunizations](packages/esm-patient-immunizations-app/README.md)
- [Medications](packages/esm-patient-medications-app/README.md)
- [Notes](packages/esm-patient-notes-app/README.md)
- [Patient banner](packages/esm-patient-banner-app/README.md)
- [Patient chart](packages/esm-patient-chart-app/README.md)
- [Programs](packages/esm-patient-programs-app/README.md)
- [Tests](packages/esm-patient-tests-app/README.md)
- [Vitals](packages/esm-patient-vitals-app/README.md)

In addition to these widgets, two other microfrontends exist that encapsulate cross-cutting concerns. These are:

- [Common lib](packages/esm-patient-common-lib/README.md)
- [Patient chart](packages/esm-patient-chart-app/README.md)

## Setup

Check out the developer documentation [here](http://o3-dev.docs.openmrs.org).

This monorepo uses [yarn](https://yarnpkg.com).

To install the dependencies, run:

```bash
yarn
```

To start a dev server for a specific microfrontend, run:

```bash
yarn start 
```

## Design Patterns

For documentation about our design patterns, please visit our [design system](https://zeroheight.com/23a080e38/p/880723--introduction) documentation website.

## Configuration

Please see the [Implementer Documentation](https://wiki.openmrs.org/pages/viewpage.action?pageId=224527013) for information about configuring modules.

## Deployment

See [Creating a Distribution](http://o3-dev.docs.openmrs.org/#/main/distribution?id=creating-a-distribution) for information about adding microfrontends to a distribution.
