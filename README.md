# Yarn cheatsheet
A list of some common things I need to do with Yarn

## Adding packages
To add a package from a public Github repo at a specific commit:
```
yarn add git://github.com/normative/react-native-navigation.git#ddbfac788e31c0c5e2efa914c553cfb77d2e6f1f
```

To force a reinstall of all packages:
```
yarn install --force
```
