# BeansDesign

基本UI组件库，适用于二次开发。

# Components Usage Guide

This document provides usage instructions for various components including Buttons, Toggle Switch, Checkbox, Inputs, and
Badges.

## Table of Contents

1. [Buttons](#buttons)
2. [Toggle Switch](#toggle-switch)
3. [Checkboxes](#checkboxes)
4. [Inputs](#inputs)
5. [Badges](#badges)

## Buttons

### Basic Button

#### Usage

```vue
<template>
  <BasicButton @click="yourMethod">Click Me</BasicButton>
</template>

<script>
import BasicButton from '@/components/BasicButton.vue';

export default {
  components: {
    BasicButton,
  },
  methods: {
    yourMethod() {
      alert('Button clicked!');
    },
  },
};
</script>
```

## Toggle Switch

### Toggle Switch Component

#### Usage

```vue

<template>
	<ToggleSwitch/>
</template>

<script>
	import ToggleSwitch from '@/components/ToggleSwitch.vue';

	export default {
		components: {
			ToggleSwitch,
		},
	};
</script>
```

## Checkboxes

### Round Checkbox

#### Usage

```vue
<template>
  <CheckboxRoundField />
</template>

<script>
import CheckboxRoundField from '@/components/CheckboxRoundField.vue';

export default {
  components: {
    CheckboxRoundField,
  },
};
</script>
```

### Square Checkbox

#### Usage

```vue
<template>
  <CheckboxSquareField />
</template>

<script>
import CheckboxSquareField from '@/components/CheckboxSquareField.vue';

export default {
  components: {
    CheckboxSquareField,
  },
};
</script>
```

## Inputs

### Basic Input

#### Usage

```vue
<template>
  <BasicInput />
</template>

<script>
import BasicInput from '@/components/BasicInput.vue';

export default {
  components: {
    BasicInput,
  },
};
</script>
```

## Badges

### Solid Badge

#### Usage

```vue
<template>
  <BadgeSolid>Solid Badge</BadgeSolid>
</template>

<script>
import BadgeSolid from '@/components/BadgeSolid.vue';

export default {
  components: {
    BadgeSolid,
  },
};
</script>
```

### Outline Badge

#### Usage

```vue
<template>
  <BadgeOutline>Outline Badge</BadgeOutline>
</template>

<script>
import BadgeOutline from '@/components/BadgeOutline.vue';

export default {
  components: {
    BadgeOutline,
  },
};
</script>
```