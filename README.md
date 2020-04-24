# Sample Wordpress Setup for Docker

## Installation Dependencies
- Docker

## Instructions
1. Run `docker network create wordpress-net`
2. Run `docker-compose up`
3. Develop your "theme" for wordpress within the `app` directory

## Future To-Do

- [x] Add boilerplate theme configurations in the `app` folder
- [x] Integrate gulp.babel workflow with ES6
- [ ] Autoselect the "app" theme when WP is initiated
- [ ] Investigate plugins
- [ ] Decide whether to use the current auto-generated theme or re-prepare with Foundation SCSS.
- [ ] Add SCSS compilation to build and remove `style.css` from source control.