include_defs('//bucklets/gerrit_plugin.bucklet')

MODULE = 'com.googlesource.gerrit.plugins.github.profile'

gerrit_plugin(
  name = 'github-profile',
  srcs = glob(['src/main/java/**/*.java']),
  resources = glob(['src/main/**/*']),
  manifest_entries = [
    'Gerrit-PluginName: github-profile',
    'Gerrit-Module: com.googlesource.gerrit.plugins.github.profile.Module',
    'Implementation-Title: GitHub Profile',
    'Implementation-URL: https://gerrit-review.googlesource.com/#/admin/projects/plugins/github-profile',
  ],
)
