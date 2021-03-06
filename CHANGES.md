# Flask-Migrate Change Log

**Release 2.5.2** - 2019-05-25

- add python 3.7 builds, remove 3.4 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/1af28ba273de6c88544623b8dc02dd539340294b))
- auto-generate change log during release ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/250a3110ad84ba331ffc7cb871e5a12fddc55f2d))
- Nicer change log ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/829edefe09dff82b6c91203dd0f5b5795bf9c8d1))

**Release 2.5.1** - 2019-05-20

- Fix `__version__` file not found in sdist [#267](https://github.com/miguelgrinberg/flask-migrate/issues/267) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/8ba8d7dca6cb233280d4644fc8d81cbba123a5ad)) (thanks **Christoph Gohlke**!)

**Release 2.5.0** - 2019-05-19

- helper release script ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/fb041b9b9221e7125e5ee27dd9eb7514cf143181))
- support % character in database URLs [#59](https://github.com/miguelgrinberg/flask-migrate/issues/59) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/4663819b416dfb5a450fe948e84111af3712078d))
- log command output in unit tests ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/506f3541c04dd0b2c020dbafc60a93fb541ca324))
- add a section on why use this extension to the docs [#101](https://github.com/miguelgrinberg/flask-migrate/issues/101) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/5467b295f7912d195333482325052eae81d30f7a))

**Release 2.4.0** - 2019-02-16

- updates to env.py ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/2a1ae1b9aa62c246fca2b2f1566284de8d4b940b))
- Link to binds is unreachable [#244](https://github.com/miguelgrinberg/flask-migrate/issues/244) The original link redirects to flask-sqlalchemy.pocoo.org Addressing it directly works and redirects to the latest version of flask-sqlalchemy ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/eb2ab8f797a179d807b6560947f4498bb543def0)) (thanks **FaBrand**!)

**Release 2.3.1** - 2018-11-28

- Don't swallow transaction errors [#236](https://github.com/miguelgrinberg/flask-migrate/issues/236) A change proposed by @kjohnsen from [#216](https://github.com/miguelgrinberg/flask-migrate/issues/216). You can read more starting with [this comment](https://github.com/miguelgrinberg/Flask-Migrate/issues/216#issuecomment-408159125). ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/87b40ec9b2113ab87f1dc41c4eb517e8ff0f5dd8)) (thanks **Nikolay Shebanov**!)

**Release 2.3.0** - 2018-10-05

- use the root logger for alembic error messages ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/fa3b45ea6ecd16f436bbdee210745335128bf514))
- Add indicate-current option into history command [#192](https://github.com/miguelgrinberg/flask-migrate/issues/192) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/1fa1936375bf609e9dab401e26f46f715f5b272b)) (thanks **misebox**!)

**Release 2.2.1** - 2018-06-18

- dependency updates ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/5d61c191d7d8853f81e4fe71609b5ae315604c52))
- add pypy3 to test matrix ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/1cc819e9f2a17435429c16531043d0a874f76288))

**Release 2.2.0** - 2018-06-13

- suppress stack traces on command errors [#204](https://github.com/miguelgrinberg/flask-migrate/issues/204) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/2dd45d0037cb62bc7a8a981f0de70071b891a2ff))
- Fix typo in docs [#207](https://github.com/miguelgrinberg/flask-migrate/issues/207) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/817893fe16eb5361469af671c52d8276b69efeab)) (thanks **Grey Li**!)
- Update documentation link [#206](https://github.com/miguelgrinberg/flask-migrate/issues/206) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/98374a6ac1006fe37ef6f09674ebaa094214ff3e)) (thanks **Grey Li**!)
- [#182](https://github.com/miguelgrinberg/flask-migrate/issues/182): clear executable permission [#183](https://github.com/miguelgrinberg/flask-migrate/issues/183) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/ee0b47ede1e88340c390fca9d0c27a9c8a7e3a9c)) (thanks **Christopher Yeleighton**!)

**Release 2.1.1** - 2017-08-28

- Make directory as optional parameter ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/7e6f511b050a023c9388868b97d7905b7571c16f)) (thanks **Diego Oliveira**!)
- Update CHANGELOG.md ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/dcffe1e91f9f5cfc29c5cf5f285ef9a4169113bb))
- updated README.md to use flask cli in examples ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/349826ef53f607fd5e866919f40b16315a2127cc))

**Release 2.1.0** - 2017-07-28

- Remove the Flask-Script dependency in setup.py ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/7bd5ef80016257ea56a1d10f917a361a13b6aad9))

**Release 2.0.4** - 2017-05-31

- Change an Alembic doc link to http from https The SSL certificate is not valid for the alembic subdomain. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/00e8192f56f778939fd819a799a9b26010b46e2e)) (thanks **bovarysme**!)
- Update links pointing to the old Alembic doc [#152](https://github.com/miguelgrinberg/flask-migrate/issues/152) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/81367408c46ecd96b2352f6e309dcb02dfc359e9)) (thanks **bovarysme**!)
- allow -x argument for migrate command [#148](https://github.com/miguelgrinberg/flask-migrate/issues/148) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/3293d835811924822cf0e8d321760ddc482ea5f2)) (thanks **Tim Mundt**!)
- stop building python 2.6 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/5f34c5cd9610f2e3194672a350f57c55cb7edd25))

**Release 2.0.3** - 2017-01-30

- remove py33 builds, add py36 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/c25ef622efc4dc28452124f56fc9bfa550ce858e))
- Support multiple -x arguments in Flask-Script interface [#103](https://github.com/miguelgrinberg/flask-migrate/issues/103) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/d2947338d673041b6198b909a9f9381b73f6bf99))
- Fix autogenerate typos. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/19af3191d8245c110860f01bb48b02b0e2d9351a)) (thanks **Sorin Muntean**!)

**Release 2.0.2** - 2016-12-09

- Merge branch 'briancappello-application_factory_kwargs' ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/4ab45f60bea8227f94adbf5de1e8509ef79afa66))
- support passing alembic context kwargs from constructor into init_app ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/57c82f35366ea9122908e3b0cbdcf536d430c2de)) (thanks **Brian Cappello**!)
- fix link for alembics command reference page ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/bfbfcb24abf3ede22104211157f05d3f370ed467)) (thanks **Brian Cappello**!)
- update autogenerate capabilities ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/118b84d384106ebfde767931119204b80fcbbac5)) (thanks **Brian Cappello**!)

**Release 2.0.1** - 2016-11-13

- Imports at top of file as specified by Flake8 and added branch label. Moving the imports to the top of the file will prevent an error: 'E402 module level import not at top of file'. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/c95c20134655cbe8f771a7e47f6d3fd4ed3e8cb6)) (thanks **Maico Timmerman**!)
- Fix typo [#126](https://github.com/miguelgrinberg/flask-migrate/issues/126) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/109f42fc1752422c0e3899942abe10020641edf6)) (thanks **Wells Lucas Santo**!)
- Fix typo [#123](https://github.com/miguelgrinberg/flask-migrate/issues/123) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/f37bdb70529e5f984b9008eace59244a293ea3db)) (thanks **Jeff Widman**!)
- flask cli documentation updates ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/254b88bc4bdafd8fb9210b37f772a72035a12cff))

**Release 2.0.0** - 2016-07-31

- add travis builds for python 3.5 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/080b7100e2f8077d95deb7c5dcdd5adb792f528c))
- Support the new flask cli based on click [#114](https://github.com/miguelgrinberg/flask-migrate/issues/114) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/8c208b54837ccbf65eee8d95fc623057e2753b4e))

**Release 1.8.1** - 2016-07-10

- Allow to init_app correctly without specifying db. [#118](https://github.com/miguelgrinberg/flask-migrate/issues/118) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/e339f27b8ee3e932d74fff91344b615fe6170333)) (thanks **Victor Akimov**!)

**Release 1.8.0** - 2016-02-24

- Allow db to be provided separately from the app ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/d612c10c05ceab7e1131839ab8a7eadcc4a71beb))
- Added missing Python 2 version classifier to package ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/6f321543fec6c04b445c34c312092c45deaf2d29))
- Fix the link for flask-sqlalchemy binds [#99](https://github.com/miguelgrinberg/flask-migrate/issues/99) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/6bf0452b084f14d06e56784465240e0258b710cb)) (thanks **lord63**!)
- Update the way to import the flask extension [#98](https://github.com/miguelgrinberg/flask-migrate/issues/98) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/c27cfea43d923b991b5f609a94a58efcdca4fe3b)) (thanks **lord63**!)

**Release 1.7.0** - 2015-12-28

- configuration callbacks ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/835d3e4b33bfbd7dae2166b88c49aee8f5fbeac0))
- Update __init__.py Update description of edit command. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/3a657dcb683ff3b91cb9e2393fbdaaa11ea33b8a)) (thanks **Kostyantyn Leschenko**!)
- fixed link in documentation ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/738d33cd76185455063d9499f7752b846193889a))

**Release 1.6.0** - 2015-09-17

- Add edit command [#76](https://github.com/miguelgrinberg/flask-migrate/issues/76) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/e9c855ca8a935bc55e830481073e377d09cdf66d)) (thanks **Jelte Fennema**!)
- Updates so that directory doesn't get overridden [#78](https://github.com/miguelgrinberg/flask-migrate/issues/78) where directory gets overridden if it is not explicitly specified in init_app.  This fix allows it to be set when the `Migrate` object is initialized and not automatically get overridden when the `init_app` is called.  This is a non-breaking change. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/0c9a2cbe35953cdabca571f402883c202ddfa09f)) (thanks **Tim Martin**!)

**Release 1.5.1** - 2015-08-24

- Do not generate a migration if no schema changes are found ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/626c83feb49f571c2a4468a8fc9f81a44eecc451))
- Fix the merge command by allowing more than one argument. [#74](https://github.com/miguelgrinberg/flask-migrate/issues/74) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/9c62c963c0e142a40233dd6dde17925cdc34ea9d)) (thanks **Kevin Dwyer**!)

**Relese 1.5.0** - 2015-08-01

- Make the multi-database configuration fully automatic ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/ed1606c02dd3e57580d853db6ebe66804a5f0ceb))
- Add sane default for `db downgrade --sql` [#71](https://github.com/miguelgrinberg/flask-migrate/issues/71) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/01a2e701259e7792c82b2173587750efe5523877)) (thanks **Anthony Miyaguchi**!)
- Add support for multiple databases migration [#70](https://github.com/miguelgrinberg/flask-migrate/issues/70) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/07737da36faf103987a9aa1df1e39ab8259b5181)) (thanks **Nan Jiang**!)
- Added support for -x option ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/a2ff9d668393e4d2da555dc145ee80c065ac932a)) (thanks **jesse**!)

**release 1.4.0** - 2015-04-27

- Pass custom Alembic configuration options, such as compare_type. Also the tests have been restructured for clarity. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/ee32ae4db5f406508dac0b93f1dacb2b8d05a5f9))

**release 1.3.1** - 2015-03-20

- Update __init__.py alembic version now includes parts that are not integers (e.g., 0.7.5.post1). This change will prevent the code from trying to convert non-integer values to integers. ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/49d4d99897a8756c0fa732d879b29900e6adcef4)) (thanks **pjryan126**!)
- Added syntax highlighting to README [#44](https://github.com/miguelgrinberg/flask-migrate/issues/44) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/8cef3eb124c4df443b32cc33ddfeb97a3a810c05)) (thanks **Bulat Bochkariov**!)

**version 1.3.0** - 2014-12-01

- new commands and options introduced with Alembic 0.7 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/d848cb43da247259948270cb0745a99c2e118866))
- pep8 changes ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/71ff1d717be124d5a1c6c930dc911a5635e323e0))
- Updated docs: add installation [#37](https://github.com/miguelgrinberg/flask-migrate/issues/37) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/aca0ce8381fbb083a3eae9b0e1d60a3de43a0be2)) (thanks **Mozillazg**!)
- travis CI builds ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/8e8a4d018f9a0a148adef712b9227dab6c990d1b))
- travis configuration ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/5241108fdb1797a883bd1844f525e35081ceb199))
- Added Python 3 programming language support to setup.py ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/d13b42bdce60db64ad56f43350f3cb15f5f7bbe7)) (thanks **Fotis Gimian**!)
- Added travis configuration ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/917b2577e58c35b03acca0fcf8f2f09e7686975f)) (thanks **Fotis Gimian**!)
- Added test-related temp_folder to gitignore list ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/ccc87167c68759b4eded529ca2335f2743f7bb4f)) (thanks **Fotis Gimian**!)
- Repaired tests to correctly run under Python 3.3 ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/d4451fddddd951cdb144320e98162ba8616f1109)) (thanks **Fotis Gimian**!)

**release 1.2.0** - 2014-01-19

- Added the branches command [#15](https://github.com/miguelgrinberg/flask-migrate/issues/15) ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/b9913c6458adba1e511ee86fd5a7291214f2eb9f)) (thanks **Bogdan Gaza**!)
- added tests directory to tarball ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/9896e370f98bb62d9a363fea564d6758d2566263))

**release 1.1.0** - 2013-12-20

- [#12](https://github.com/miguelgrinberg/flask-migrate/issues/12): pass a default migrations directory in the Migrate constructor ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/189dbb5600c164147751453e72a1c8bb8e4229c3))
- Merge branch 'master' of github.com:miguelgrinberg/Flask-Migrate ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/3d364a81edacda81ccee60a33616ba15d47b5c27))
- pass revision range to history command ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/790442da2f9fa8168c6c0aa837ed4a1505980059)) (thanks **David Lord**!)
- scripting interface ([commit](https://github.com/miguelgrinberg/flask-migrate/commit/ba6a0904616b701cc48f066fe3fca18a432b7f10))

**release 1.0.0** - 2013-12-03

- First official release!
