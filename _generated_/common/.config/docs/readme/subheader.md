<div align="center">
  <a href="{{ link.home }}" title="{{ organization }} homepage" target="_blank">
    <img alt="Homepage" src="https://img.shields.io/website?down_color=%23FF4136&down_message=Down&label=Homepage&logo=home-assistant&logoColor=white&up_color=%232ECC40&up_message=Up&url=https%3A%2F%2Fmegabyte.space&style={{ badge_style }}" />
  </a>
  <a href="{{ repository.github }}{{ repository.location.contributing.github }}" title="Learn about contributing" target="_blank">
    <img alt="Contributing" src="https://img.shields.io/badge/Contributing-Guide-0074D9?logo=github-sponsors&logoColor=white&style={{ badge_style }}" />
  </a>
  <a href="{{ link.chat }}" title="Chat with us on Slack" target="_blank">
    <img alt="Slack" src="https://img.shields.io/badge/Slack-Chat-e01e5a?logo=slack&logoColor=white&style={{ badge_style }}" />
  </a>
  <a href="{{ link.gitter }}" title="Chat with the community on Gitter" target="_blank">
    <img alt="Gitter" src="https://img.shields.io/gitter/room/megabyte-labs/community?logo=gitter&logoColor=white&style={{ badge_style }}" />
  </a>
  <a href="{{ repository.github }}" title="GitHub mirror" target="_blank">
    <img alt="GitHub" src="https://img.shields.io/badge/Mirror-GitHub-333333?logo=github&style={{ badge_style }}" />
  </a>
  <a href="{{ repository.gitlab }}" title="GitLab repository" target="_blank">
    <img alt="GitLab" src="https://img.shields.io/badge/Repo-GitLab-fc6d26?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAAHJJREFUCNdNxKENwzAQQNEfWU1ZPUF1cxR5lYxQqQMkLEsUdIxCM7PMkMgLGB6wopxkYvAeI0xdHkqXgCLL0Beiqy2CmUIdeYs+WioqVF9C6/RlZvblRNZD8etRuKe843KKkBPw2azX13r+rdvPctEaFi4NVzAN2FhJMQAAAABJRU5ErkJggg==&style={{ badge_style }}" />
  </a>
</div>
<br/>
<div align="center">
  <a title="Version: {{ pkg.version }}" href="{{ repository.github }}" target="_blank">
    <img alt="Version: {{ pkg.version }}" src="https://img.shields.io/badge/version-{{ pkg.version }}-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAACNJREFUCNdjIACY//+BEp9hhM3hAzYQwoBIAqEDYQrCZLwAAGlFKxU1nF9cAAAAAElFTkSuQmCC&cacheSeconds=2592000&style={{ alt_badge_style }}" />
  </a>
  <a title="Build status on GitLab" href="{{ repository.gitlab }}{{ repository.location.commits.gitlab }}" target="_blank">
    <img alt="GitLab build status" src="https://img.shields.io/gitlab/pipeline-status/{{ repository.group.python_cli_path }}/{{ slug }}?branch=master&label=build&logo=gitlab&style={{ alt_badge_style }}" />
  </a>
  <a title="Test coverage report" href="{{ repository.gitlab }}{{ repository.location.commits.gitlab }}" target="_blank">
    <img alt="Coverage status" src="https://img.shields.io/gitlab/coverage/{{ repository.group.python_cli_path }}/{{ slug }}/master/?label=coverage&logo=pytest&style={{ alt_badge_style }}" />
  </a>
  <a title="Documentation" href="{{ link.docs }}/{{ group }}" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg?logo=readthedocs&style={{ alt_badge_style }}" />
  </a>
  <a title="Supported Python versions" href="https://pypi.org/project/{{(if customPyPiPackageName customPyPiPackageName (append repository.prefix.github slug))}}/" target="_blank">
    <img alt="Python versions" src="https://img.shields.io/pypi/pyversions/{{(if customPyPiPackageName customPyPiPackageName (append repository.prefix.github slug))}}/?label=python&logo=python&style={{ alt_badge_style }}" />
  </a>
  <a title="PyPi status" href="https://pypi.org/project/{{(if customPyPiPackageName customPyPiPackageName (append repository.prefix.github slug))}}/" target="_blank">
    <img alt="Status" src="https://img.shields.io/pypi/status/{{(if customPyPiPackageName customPyPiPackageName (append repository.prefix.github slug))}}/?label=status&logo=pypi&style={{ alt_badge_style }}" />
  </a>
  <a title="License: {{ license }}" href="{{ repository.github }}{{ repository.location.license.github }}" target="_blank">
    <img alt="License: {{ license }}" src="https://img.shields.io/badge/license-{{ license }}-yellow.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgAQMAAABJtOi3AAAABlBMVEUAAAD///+l2Z/dAAAAAXRSTlMAQObYZgAAAHpJREFUCNdjYOD/wMDAUP+PgYHxhzwDA/MB5gMM7AwMDxj4GBgKGGQYGCyAEEgbMDDwAAWAwmk8958xpIOI5zKH2RmOyhxmZjguAiKmgIgtQOIYmFgCIp4AlaQ9OczGkJYCJEAGgI0CGwo2HmwR2Eqw5SBnNIAdBHYaAJb6KLM15W/CAAAAAElFTkSuQmCC&style={{ alt_badge_style }}" />
  </a>
</div>
