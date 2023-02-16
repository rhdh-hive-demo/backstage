## API Report File for "@backstage/plugin-entity-validation"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { BackstagePlugin } from '@backstage/core-plugin-api';
import { RouteRef } from '@backstage/core-plugin-api';

// @public (undocumented)
export const EntityValidationPage: (props: {
  defaultYaml?: string | undefined;
  defaultLocation?: string | undefined;
}) => JSX.Element;

// @public (undocumented)
export const entityValidationPlugin: BackstagePlugin<
  {
    root: RouteRef<undefined>;
  },
  {},
  {}
>;

// (No @packageDocumentation comment for this package)
```