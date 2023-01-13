<a href="https://github.com/SadikCihanAyaz"><img src="https://github.com/SadikCihanAyaz/SadikCihanAyaz/blob/main/images/header3.png?raw=true"></a>
```js

<Header message="WELCOME MY REPO!!"/>

```
```js
import React from 'react';
import {Text} from 'react-native';

interface Props {
  message: string;
}

const Header: React.FC<Props> = props => {
  const {message} = props;
  return <Text>{message}</Text>;
};

export default Header;

```
<table>
  <tr>
    <th>GO MY WEBSITE </th>
    <th>SEND A MESSAGE</th>
    <th>CONTACT ME</th>
  </tr>
  <tr>
    <td>    <a href="https://sadikcihanayaz.github.io/"><img src="https://github.com/SadikCihanAyaz/SadikCihanAyaz/blob/main/images/website.png?raw=true"></a></td>
        <td>    <a href="mailto:scayaz.19.19@gmail.com"><img src="https://github.com/SadikCihanAyaz/SadikCihanAyaz/blob/main/images/gmail.png?raw=true"></a></td>
            <td>    <a href="https://www.linkedin.com/in/sadikcihanayaz/"><img src="https://github.com/SadikCihanAyaz/SadikCihanAyaz/blob/main/images/linkedin.png?raw=true"></a></td>
  </tr>

</table>
