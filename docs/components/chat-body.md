---
sidebar_position: 2
---

# Chat Body Components

This section is responsible of displaying and sending messages in group and DMs. This section is made up of 5 Components:-

- **`GroupTab:` ** The Section Header of chat body section is created via this component.

```js title="Section2.jsx"
import { GroupTab } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<GroupTab />
		</>
	);
};

export default SampleApp;
```

![Group Tab](./img/GroupTab.png)

- **`SingleChatContainer:` ** This component is the what displays a single block of chat. Changes color absed on whether sent by user or not.

```js title="Section2.jsx"
import { SingleChatContainer } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<SingleChatContainer />
		</>
	);
};

export default SampleApp;
```

![Single Chat Container](./img/Single%20Chat%20Container.png)

- **`ChatSendDate:` ** This component is the what displays the date in `SingleChatContainer`.

```js title="Section2.jsx"
import { ChatSendDate } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<ChatSendDate />
		</>
	);
};

export default SampleApp;
```

![Chat Send Data](./img/Send%20Chat%20Date.png)

- **`ProfileCard:` ** This component is where user info is displayed in form of a small card.

```js title="Section2.jsx"
import { ProfileCard } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<ProfileCard />
		</>
	);
};

export default SampleApp;
```

![Profile Card](./img/Profile%20Card.png)

- **`ChatWindow:` ** This component is where all the chats in `SingleChatContainer` is displayed, basically this is the main attraction of this section.

```js title="Section2.jsx"
import { ChatWindow } from "@Chattgator/components"

const SampleApp = () => {
	return (
		<>
			<ChatWindow />
		</>
	);
};

export default SampleApp;
```

![Chat Window](./img/Chat%20Window.png)