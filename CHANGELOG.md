# Changelog

### Changed
**Releases 0.0.29 to 0.1.4** -

- README.md references `user` but example table is `users`. [Issue #154](https://github.com/joegasewicz/flask-jwt-router/issues/154)
- Add OAuth 2.0 & compatibility with react-google-oauth2 npm pkg. [Issue #158](https://github.com/joegasewicz/flask-jwt-router/issues/158)
- Fix docs. [Issue #162](https://github.com/joegasewicz/flask-jwt-router/issues/162)
- Fix url is mutated. [Issue #169](https://github.com/joegasewicz/flask-jwt-router/issues/169)
- Entity key state gets stale between requests. [Issue #171](https://github.com/joegasewicz/flask-jwt-router/issues/171)
- Table name form oauth request is stale. [Issue #173](https://github.com/joegasewicz/flask-jwt-router/issues/173)
- Clean up entity state before auth routing . [Issue #175](https://github.com/joegasewicz/flask-jwt-router/issues/175)
- Return 401 status is oauth returns none. [Issue #177](https://github.com/joegasewicz/flask-jwt-router/issues/177)
- PyJWT 2.0 causes Breaking change. [Issue #179](https://github.com/joegasewicz/flask-jwt-router/issues/179)

**Release 0.0.28** -

- Created custom error for `update_token` method called on non existent token [Issue #151](https://github.com/joegasewicz/flask-jwt-router/issues/151)
- Updated `Authenticate`'s `update_token` method's doc string with entity_id kwarg. [Issue #150](https://github.com/joegasewicz/flask-jwt-router/issues/150) 
- README.md references `user` but example table is `users` [Issue #154](https://github.com/joegasewicz/flask-jwt-router/issues/154)

**Release 0.0.27** - 2020-09-14

-   Secret Key now must be set [Issue #137](https://github.com/joegasewicz/flask-jwt-router/issues/137)
-   Fixes ModuleNotFoundError: No module named 'dateutil' [Issue #138](https://github.com/joegasewicz/flask-jwt-router/issues/138)
-   Removes strategy design pattern from project [Issue #141](https://github.com/joegasewicz/flask-jwt-router/issues/141)
-   Renamed extensions to Config [Issue #143](https://github.com/joegasewicz/flask-jwt-router/issues/143)
-   Added token expire duration option [Issue #44](https://github.com/joegasewicz/flask-jwt-router/issues/44)

**Release 0.0.26** - 2019-12-11

-   Preflight OPTIONS bug fix [Issue #125](https://github.com/joegasewicz/Flask-JWT-Router/issues/125)

**Release 0.0.25** - 2019-12-10

-   Replaced the the `entity_type` kwarg to `table_name` in the public method `register_entity` [Issue #111](https://github.com/joegasewicz/Flask-JWT-Router/issues/111)
-   Renamed the `update_entity` public method to be called `update_token` [Issue #114](https://github.com/joegasewicz/Flask-JWT-Router/issues/114)
-   Renamed the `register_entity` public method to be called `create_token` [Issue #113](https://github.com/joegasewicz/Flask-JWT-Router/issues/113)
-   Add Models to JWTRoutes class & init_app method [Issue #119](https://github.com/joegasewicz/Flask-JWT-Router/issues/119)

## Unreleased
