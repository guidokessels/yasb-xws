# YASB permalink to XWS endpoint

Since I host [Yet Another X-Wing Squad Builder](https://geordanr.github.io/xwing)
on GitHub pages, I can't arbitrarily respond to a request with
`application/json` (as far as I know).  So instead, here's an endpoint
that will take the permalink and spit out the XWS for it.

## Building

    grunt

## Running the server

    npm start

## Updating the xwing submodule

This is necessary to keep the card list up to date with the builder.

    git submodule foreach git pull origin master
