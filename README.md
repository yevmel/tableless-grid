## Run
    npx http-server

## font-size: 0
`font-size: 0` removes spacing between divs with `display: inline-block`.

## ResizeObserver Foobar
global error handler helps debugging errors thrown by ResizeObserver, which are not displayed in console by some browsers (f.e. edge, chrome) otherwise.

    window.onerror = message => {
        console.log(message)
    };