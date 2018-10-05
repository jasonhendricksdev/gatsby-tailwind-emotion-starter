# Gatsby Tailwind Emotion Starter

## Usage

### Develop

```
npm run develop
```

### Build

```
npm run build
```
Your built file will be in `/public`

This project was based on [gatsby-plugin-tailwindcss](https://github.com/muhajirframe/gatsby-plugin-tailwindcss/)

### How the heck do I use it?

```javascript
import React from 'react'
import styled from 'react-emotion'


const Container = styled.div`
  ${tw`py-8`};
`
const Text = styled.p`
  ${tw`bg-black text-white`};
`

const Home = () => (
  <Container>
    <Text>I am Text component made with Tailwind CSS + EmotionJS</Text>
  </Container>
)

export default Home
```


## For more information

- [Github](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter)
- [gatsby-tailwind-emotion-starter](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter)
- Got a question? [Submit an issue](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter/issues/new)

## Contributing

- [Submit an idea](https://github.com/muhajirframe/gatsby-tailwind-emotion-starter/issues/new)
- Make a pull request

## Related
- [react-tailwind-emotion-starter](https://github.com/muhajirframe/react-tailwind-emotion-starter) A React + Tailwind + EmotionJs starter based on [create-react-app](https://github.com/facebook/create-react-app)
- [vscode-tailwind-styled-snippets](https://github.com/muhajirframe/vscode-tailwind-styled-snippets)
- [gatsby-plugin-tailwindcss](https://github.com/muhajirframe/gatsby-plugin-tailwincss)
**Enjoy!**
