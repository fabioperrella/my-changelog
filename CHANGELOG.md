| Date | Category | Description |
|------|----------|-------------|
| 03/03/20 | tls | [Working around OpenSSL::SSL::SSLErrors](https://makandracards.com/makandra/26255-working-around-openssl-ssl-sslerrors) |
| 03/01/20 | git | `git checkout --ours PATH` to resolve conflicts easily |
| 30/12/19 | bash | To open gzip files with less: `zless` |
| 30/12/19 | memcached | To flush all data via telnet: `echo 'flush_all' | nc localhost 11211` |
| 28/05/19 | sublime | [plugin BufferScroll](https://github.com/titoBouzout/BufferScroll) to save the state of code folding |
| 21/03/19 | rails | [try works different in rails 3 and rails 4](https://stackoverflow.com/questions/7426808/rails-try-method-throwing-nomethoderror) |
| 07/02/19 | rails | [resolving activerecord N+1](http://blog.scoutapp.com/articles/2017/01/24/activerecord-includes-vs-joins-vs-preload-vs-eager_load-when-and-where) |
| 04/02/19 | postgres | [using row_number to get first element when grouping by](https://blog.codeship.com/folding-postgres-window-functions-into-rails/) |
| 23/01/19 | rspec | `rspec --bisect` to find the cause of failing tests  |
| 03/10/18 | git | git rebase --preserve-merges |
| 31/08/18 | postgres | [using constraint to set a column not null withou locking the table](https://medium.com/doctolib-engineering/adding-a-not-null-constraint-on-pg-faster-with-minimal-locking-38b2c00c4d1c) |
| 31/08/18 | rails | [change_column_null to set a column null](https://apidock.com/rails/v4.2.7/ActiveRecord/ConnectionAdapters/SchemaStatements/change_column_null) |
| 30/08/18 | postgres | [tracking progress of an update](https://drone-ah.com/2011/11/02/tracking-progress-of-an-update-statement-1101/) |
| 29/08/18 | rails | [alias_attribute](https://apidock.com/rails/Module/alias_attribute) |
| 29/08/18 | tools | firefox reader mode |
| 23/08/18 | ruby | [gem contracts](https://github.com/egonSchiele/contracts.ruby) |
| 26/07/18 | linux | [prefer IPv4 over IPv6](http://terokarvinen.com/2016/prefer-ipv4-on-ubuntu-16-04-lts-xenial-etcgai-conf-precedence-ffff0096-100) |
| 06/03/18 | rspec | [Webmock to_timeout](https://github.com/bblimke/webmock#raising-timeout-errors) to stub timeout errors |
| 02/03/18 | bash | [xsel](https://github.com/kfish/xsel) to copy output to clipboard |
| 02/03/18 | rspec | `mocks.verify_partial_doubles = true` to raise error if mocking a not existing method |
| 26/02/18 | ruby | [Enumerable#each_with_object](https://apidock.com/rails/Enumerable/each_with_object) |
| 11/01/18 | sublime | ctags plugin for a better "go to definition" |
| 11/01/18 | ruby,tools | https://unused.codes - command to detect unused code |
| 10/01/18 | ruby,tools | tableprintgem.com - gem to improve table visualization in rails console |
| 02/01/18 | firefox | extension [multi-account-containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/) to use multiple sessions in FF |
| 02/01/18 | git testing | `git fast-export` and `git fast-import` to save a fixture git repo inside a git repo, from [das s02e15](https://www.destroyallsoftware.com/screencasts/catalog/simple-bash-script-testing) |
| 22/12/17 | sublime | plugin [Select Quoted](https://packagecontrol.io/packages/Select%20Quoted) to select string inside quotes |
| 22/12/17 | sublime | plugin [CopyFilepathWithLineNumbers](https://github.com/theskyliner/CopyFilepathWithLineNumbers) to run specs faster |
| 22/12/17 | rspec | [FactoryBot's attributes_for](https://github.com/thoughtbot/factory_bot/blob/master/GETTING_STARTED.md#using-factories) |
| 29/11/17 | ruby | avoid using delegate with `prefix: true` to help to find methods definitions  |
| 12/09/17 | bash | diff with subshell | diff -u <(echo aa) <(echo bbbaaa) |
| 12/09/17 | bash | tidy | to format html / xml |
| 12/09/17 | bash | screen | screen to detach terminal |
| 12/09/17 | bash | pstree | vi - (open the stdin in vim) |
| 25/08/17 | naming | [How to name methods according to side effects](https://swift.org/documentation/api-design-guidelines/#name-according-to-side-effects) |
| 23/08/17 | vcr | `VCR.current_cassette.file` to print the current cassete file |
| 27/06/17 | tools | https://www.shellcheck.net |
| 09/06/17 | rspec | [Rails (time) travel_to](http://brandonhilkert.com/blog/rails-4-1-travel-to-test-helper/)
| 31/05/17 | rspec | [Rspec compound expectations](https://relishapp.com/rspec/rspec-expectations/docs/compound-expectations) |
| 30/05/17 | rails | [ActiveRecord Merge](https://apidock.com/rails/v4.2.7/ActiveRecord/SpawnMethods/merge) |
| 09/05/17 | postgres | [query case insensitive](https://nandovieira.com.br/usando-campos-case-insensitive-no-postgresql) |
| 13/04/17 | tools | [autojump to change dirs fast](https://github.com/wting/autojump) |
| 12/04/17 | rspec | [diffence between `spy`, `double` and `instance_double`](https://www.ombulabs.com/blog/rspec/ruby/spy-vs-double-vs-instance-double.html) |
| 12/04/17 | bash | use `{}` to join output to pipe, ex: `{ echo 1; echo 11; echo 0; } \| grep 1` |
| 07/04/17 | grafana | use `group by time($interval)` to retrive data from a big time interval, otherwise it will reach the limit of `max-select-point` |
| 22/03/17 | ruby | [Array &(and)](https://ruby-doc.org/core-2.4.0/Array.html#method-i-26) to return the intersection of 2 arrays |
| 16/03/17 | rails | ActiveRecord query `.where('lala = :value and popo = :other', value: 'x', other: 'y')` |
| 14/03/17 | rails | [ActiveRecord nested transactions](http://api.reonrails.org/classes/ActiveRecord/Transactions/ClassMethods.html) |
| 11/03/17 | js | [Current status of JS tools](https://hackernoon.com/a-map-to-modern-javascript-development-2017-16d9eb86309c#.8xo1fckel) |
| 02/03/17 | tools | [jepsen.io](jepsen.io) for analysis over databases |
| 01/03/17 | sublime | [shortcut to move to other panels](http://stackoverflow.com/questions/25065771/move-tab-from-one-column-to-another-in-sublime-using-only-keys) |
| 24/02/17 | productivity | menos reuniões com discussões assíncronas (basecamp) |
| 24/02/17 | ruby | [gem pronto](https://github.com/mmozuras/pronto) to run rubocop in current MR |
| 15/02/17 | ruby | [bundle outdated --strict](http://bundler.io/v1.3/bundle_outdated.html) |
| 15/02/17 | bash | [tee /dev/tty](http://stackoverflow.com/questions/5677201/how-to-pipe-stdout-while-keeping-it-on-screen-and-not-to-a-output-file) |
| 13/02/17 | bash | `!#set -eou pipefail` |
| 10/02/17 | tools | [sqlectron - client sql for linux](sqlectron.github.io) |
| 09/02/17 | rspec | [sanitize post body for random params](http://railsware.com/blog/2013/10/03/custom-vcr-matchers-for-dealing-with-mutable-http-requests/) |
| 07/02/17 | tools | [Json diff tool](http://jsondiff.com/)  |
| 02/02/17 | git | [Auto-squashing Git Commits](https://robots.thoughtbot.com/autosquashing-git-commits)  |
| 01/02/17 | rspec | [factory_girl ignore/transient attributes](http://www.rubydoc.info/gems/factory_girl/file/GETTING_STARTED.md#Transient_Attributes)|
| 01/02/17 | git | [How to add a changed file to an older (not last) commit in Git](http://stackoverflow.com/questions/2719579/howto-add-a-changed-file-to-an-older-not-last-commit-in-git)  |
| 25/01/17 | ruby | [Enumerator::Lazy](http://dev.af83.com/2012/11/22/ruby-2-0-enumerator-lazy.html) to iterate without creating intermediate arrays |
| 17/01/17 | rspec | difference between `double` and `spy`. Spy is made to be used with `have_received` |
| 17/01/17 | ruby | use `Module.prepend` to log messages and keep the main class cleaner |
| 16/01/17 | git | [how to add custom commands to tig](https://github.com/fabioperrella/dotfiles/commit/848fca0ddcdfef1b43fb859a30b82b55a6ee9626) |
| 11/01/17 | productivity | [rescue time](http://rescuetime.com) for time track in general  |
| 11/01/17 | productivity | wakatime.com (time tracking) |
| 09/01/17 | bundler | ruby version only accepts the exact version (it does not accept '> 2.1' or '~> 2.1') |
| 05/01/17 | jsonapi| [Compound-Documents](http://jsonapi.org/format/#document-compound-documents) |
| 03/01/17 | git | git changelog (alias `changelog=log --reverse --pretty=format:'- %B' master..HEAD`). The output can be used to create the merge request |
| 01/01/17 | bash | it is possible to create a dynamic alias using single quotes (instead of using double quotes) |
| 30/12/16 | ruby | avoid recursion, prefer [iterations](http://www.refactoring.com/catalog/replaceRecursionWithIteration.html) |
| 30/12/16 | rspec | its. Ex: `its(:domain) { params[:domain] }` |
| 28/12/16 | rspec | remote factory-girl |
| 27/12/16 | postgres | where com regex, ex: `where xx ~ '.+\d+'` |
| 26/12/16 | sublime | ctrl + j (Joining and swapping lines) |
| 22/12/16 | rails | [Object.presence](http://api.rubyonrails.org/classes/Object.html#method-i-presence). Ex: `[].presence #=> nil` |
| 22/12/16 | ruby | gem [debride](https://github.com/seattlerb/debride) to detect unused code to delete
| 22/12/16 | bash | use function to run “alias” rs, since alias can not run dinamic code |
| 22/12/16 | ruby | private_constant |
| 22/12/16 | git | tig (client leve) |
| 22/12/16 | docs | http://tomdoc.org |
| 22/12/16 | docs | http://keepachangelog.com |
| 22/12/16 | git | [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) |
| 22/12/16 | git | [How to write a git commit message](http://chris.beams.io/posts/git-commit/) |
| 22/12/16 | git | Rebuild commits using reset and tig (add interactive) before create a MR |
| 22/12/16 | ruby | Using monads to multi-step code |
| 22/12/16 | docs | diagrams in ascii: [asciiflow.com](http://asciiflow.com) |
| 22/12/16 | docs | [gitbook](https://www.gitbook.com/) |
| 22/12/16 | docs | [Mermaid to "code" diagrams](https://knsv.github.io/mermaid/) |
| 22/12/16 | rspec | Dont DRY the tests:  http://blog.plataformatec.com.br/2014/04/improve-your-test-readability-using-the-xunit-structure, https://robots.thoughtbot.com/lets-not, http://stackoverflow.com/questions/6453235/what-does-damp-not-dry-mean-when-talking-about-unit-tests |
