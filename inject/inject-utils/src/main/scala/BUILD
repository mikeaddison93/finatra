scala_library(
  provides = scala_artifact(
    org = 'com.twitter',
    name = 'inject-utils',
    repo = artifactory,
  ),
  dependencies=[
    '3rdparty/jvm/commons-lang',
    'finatra/inject/inject-core',
    '3rdparty/jvm/joda-time:joda-time',
    '3rdparty/jvm/org/clapper:grizzled-slf4j',
    'finagle/finagle-core/src/main/scala:scala',
    'finagle/finagle-mux/src/main/scala:scala',
    'util/util-core/src/main/scala:scala',
  ],
  fatal_warnings=True,
  sources=rglobs('*.scala'),
  resources=[
    'finatra/inject/inject-utils/src/main/resources'
  ]
)
