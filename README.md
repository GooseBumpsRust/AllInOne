# GooseBumpsAllInOne

This is the mono repo.

## clone

This repo contains submodules so you have to clone it recursive:

```sh
git clone --recusive https://github.com/GooseBumpsRust/GooseBumpsAllInOne
```

## Backend

Open a new console and move to backend folder.
You need rust and cargo installed then you can build the backend.

```sh
cd GooseBumpsBackend
cargo build
```

When its builded you can start with `cargo run`.

The backends swagger ui should run now on [http://localhost:8000/swagger-ui](http://localhost:8000/swagger-ui)

## Frontend

Open another console and move to the frontend.
You need node installed with version at least 16.

```sh
cd GooseBumpsFrontend
npm install
npm run start
```

The frontend now runs on [http://localhost:4200](http://localhost:4200)
