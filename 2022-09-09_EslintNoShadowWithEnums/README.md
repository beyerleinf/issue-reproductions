# @typescript-eslint/no-shadow enum issue

## 1. Install dependencies

```
npm i
```

## 2. Run ESLint

```
npm run lint
```

**The following error shows up which is not correct**
```
4:3  error  'SomeThing' is already declared in the upper scope on line 1 column 7  @typescript-eslint/no-shadow
```
