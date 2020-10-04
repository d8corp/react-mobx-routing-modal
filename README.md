# react-mobx-routing-modal
[![NPM](https://img.shields.io/npm/v/react-mobx-routing-modal.svg)](https://github.com/d8corp/react-mobx-routing-modal/blob/master/CHANGELOG.md)
[![downloads](https://img.shields.io/npm/dm/react-mobx-routing-modal.svg)](https://www.npmjs.com/package/react-mobx-routing-modal)
[![license](https://img.shields.io/npm/l/react-mobx-routing-modal)](https://github.com/d8corp/react-mobx-routing-modal/blob/master/LICENSE)  
Cool pop-ups related to URL with [React 16.3+](https://reactjs.org) and [Mobx 3+](https://mobx.js.org).
### Installation
npm
```bash
npm i react-mobx-routing-modal
```
yarn
```bash
yarn add react-mobx-routing-modal
```
### Using
All modals should be placed into `Modals`.
```typescript jsx
import RouterModal, {Modals, OpenModal} from 'react-mobx-routing-modal'
import theme from 'react-mobx-modal/theme/default.module.scss'

export default () => (
  <>
    <OpenModal id='test'>Open</OpenModal>
    <Modals className={theme.modals}>
      <RouterModal id='test' delay={300} classNames={theme}>
        Test modal
      </RouterModal>
    </Modals>
  </>
)
```
## Issues
If you find a bug, please file an issue on [GitHub](https://github.com/d8corp/react-mobx-routing-modal/issues)  
[![issues](https://img.shields.io/github/issues-raw/d8corp/react-mobx-routing-modal)](https://github.com/d8corp/react-mobx-routing-modal/issues)  
> ---
[![stars](https://img.shields.io/github/stars/d8corp/react-mobx-routing-modal?style=social)](https://github.com/d8corp/react-mobx-routing-modal/stargazers)
[![watchers](https://img.shields.io/github/watchers/d8corp/react-mobx-routing-modal?style=social)](https://github.com/d8corp/react-mobx-routing-modal/watchers)

