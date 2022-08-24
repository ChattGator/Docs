---
sidebar_position: 3
---

# Bio Section Components

This section is responsible of displaying the infomation of the user or the group. This section is made up of 5 Components:-

- **`BioHeader:` ** The Section Header of bio section is created via this component.

```js title="Section3.jsx"
import { BioHeader } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<BioHeader />
		</>
	);
};

export default SampleApp;
```

![Bio Header](./img/Bio%20Header.png)

- **`BioImage:` ** The Image of the group or the user is displayed in this component.

```js title="Section3.jsx"
import { BioImage } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<BioImage />
		</>
	);
};

export default SampleApp;
```

![Bio Image](./img/Bio%20Image.png)

- **`BioInfo:` ** The Name and username, or number of member in the group, is displayed in this component.

```js title="Section3.jsx"
import { BioInfo } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<BioInfo />
		</>
	);
};

export default SampleApp;
```

![Bio Info](./img/Bio%20Info.png)

- **`BioDescription:` ** The description of the user or group is displayed in this component.

```js title="Section3.jsx"
import { BioDescription } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<BioDescription />
		</>
	);
};

export default SampleApp;
```

![Bio Description](./img/Bio%20Desc.png)

- **`BioParticipation:` ** The list of memebers in the group and their status is displayed in this component.

```js title="Section3.jsx"
import { BioParticipation } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<BioParticipation />
		</>
	);
};

export default SampleApp;
```

![Bio Description](./img/Bio%20Participation.png)