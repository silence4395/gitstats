# gitstats
git history statistics generator

Usage: gitstats [options] <gitpath..> <outputpath>

Options:
-c key=value     Override configuration value

Default config values:
{'project_name': '', 'processes': 8, 'max_domains': 10, 'commit_begin': '', 'max_ext_length': 10, 'commit_end': 'HEAD', 'linear_linestats': 1, 'style': 'gitstats.css', 'max_authors': 20, 'authors_top': 5, 'start_date': ''}

Please see the manual page for more details.
