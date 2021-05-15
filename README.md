bar depends on "package-b" from yarn-monorepo - this works

```
cd bar
yarn
```

foo depends on package "@org/package-a" from yarn-monorepo - this fails

```
cd foo
yarn
```
