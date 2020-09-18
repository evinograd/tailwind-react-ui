### Example

```jsx
import { Box } from 'tailwind-react-primitives'
import {
  Header,
  NavBrand,
  NavToggle,
  NavMenu,
  NavItem,
  OutlineButton,
} from 'tailwind-react-ui'
;<>
  <Header>
    <NavBrand as="a" href="#header" font="semibold" text={['white', 'xl']}>
      <Box
        as="svg"
        fill="current"
        h={8}
        w={8}
        m={{ r: 2 }}
        width="54"
        height="54"
        viewBox="0 0 54 54"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z" />
      </Box>
      <Box inlineBlock>Tailwind React UI</Box>
    </NavBrand>
    <NavToggle />
    <NavMenu>
      <NavItem as="a" href="#header" active>
        Docs
      </NavItem>
      <NavItem as="a" href="#header">
        Examples
      </NavItem>
      <NavItem as="a" href="#header">
        Blog
      </NavItem>
      <OutlineButton border="white" text="white" text-hocus="blue-400">
        Download
      </OutlineButton>
    </NavMenu>
  </Header>
</>
```

### Custom Example:

```jsx
import { Box } from 'tailwind-react-primitives'
import {
  Header,
  NavBrand,
  NavToggle,
  NavMenu,
  NavItem,
  OutlineButton,
} from 'tailwind-react-ui'
;<>
  <Header bg="purple-400" text="white" screen="md">
    <NavBrand as="a" href="#header" font="semibold" text={['white', 'xl']}>
      <Box
        as="svg"
        fill="current"
        h={8}
        w={8}
        m={{ r: 2 }}
        width="54"
        height="54"
        viewBox="0 0 54 54"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z" />
      </Box>
      <Box inlineBlock>Tailwind React UI</Box>
    </NavBrand>
    <NavToggle />
    <NavMenu>
      <NavItem as="a" href="#header" active>
        Docs
      </NavItem>
      <NavItem as="a" href="#header">
        Examples
      </NavItem>
      <NavItem as="a" href="#header">
        Blog
      </NavItem>
      <OutlineButton border="white" text="white" text-hocus="blue-400">
        Download
      </OutlineButton>
    </NavMenu>
  </Header>
</>
```