---
layout: security.hbs
title: 보안
---

<!--
# Security

## Reporting a Bug

All security bugs in Node.js are taken seriously and should be reported by emailing [security@nodejs.org](mailto:security@nodejs.org).
This will be delivered to a subset of the core team who handle security issues.

Your email will be acknowledged within 24 hours, and you’ll receive a more detailed response to your email within 48
hours indicating the next steps in handling your report.
-->
# 보안

# 버그 보고

Node.js의 모든 보안 버그는 심각한 문제이므로
[security@nodejs.org](mailto:security@nodejs.org) 이메일로 보고해야 합니다.
이 이메일은 보안 이슈를 처리하는 코어 팀 내의 사람들에게 보내질 것입니다.

보고된 내용은 24시간 이내에 승인하고 48시간 이내에 다음 처리 단계를 안내하는
자세한 내용을 응답할 것입니다.

<!--
After the initial reply to your report, the security team will endeavor to keep you informed of the progress being made
towards a fix and full announcement, and may ask for additional information or guidance surrounding the reported issue.
These updates will be sent at least every five days, in practice, this is more likely to be every 24-48 hours.

Security bugs in third party modules should be reported to their respective maintainers and can also be coordinated
through the [Node Security Project](https://nodesecurity.io).

Thank you for improving the security of Node.js. Your efforts and responsible disclosure are greatly appreciated and
will be acknowledged.
-->
보고한 내용에 첫 답변을 한 후 보안 팀은 수정사항과 전체 공지를 만드는 과정을 보고자에게 계속 알려주려고
노력할 것입니다. 보고된 이슈에 대한 추가 정보나 안내를 물어볼 수도 있습니다. 이러한 진행사항은
최소 5일마다 계속 알려줄 것입니다만 실제로는 24~48시간 마다 알려줄 가능성이 큽니다.

서드파티 모듈의 보안 버그는 각 메인테이너에게 보고해야 하고
[Node 보안 프로젝트](https://nodesecurity.io)를 통해 조정할 수도 있습니다.

Node.js의 보안을 개선하게 해 준 것에 감사드립니다. 당신이 들인 노력과 책임 있는 공개에 아주
감사드리고 이는 인정받을 것입니다.

<!--
## Disclosure Policy

Here is the security disclosure policy for Node.js

- The security report is received and is assigned a primary handler. This person will coordinate the fix and release
process. The problem is confirmed and a list of all affected versions is determined. Code is audited to find any
potential similar problems. Fixes are prepared for all releases which are still under maintenance. These fixes are not
committed to the public repository but rather held locally pending the announcement.

- A suggested embargo date for this vulnerability is chosen and a CVE (Common Vulnerabilities and  Exposures (CVE®))
is requested for the vulnerability.

- On the embargo date, the Node.js security mailing list is sent a copy of the announcement. The changes are pushed to
the public repository and new builds are deployed to nodejs.org. Within 6 hours of the mailing list being notified, a
copy of the advisory will be published on the Node.js blog.

- Typically the embargo date will be set 72 hours from the time the CVE is issued. However, this may vary depending on
the severity of the bug or difficulty in applying a fix.

- This process can take some time, especially when coordination is required with maintainers of other projects. Every
effort will be made to handle the bug in as timely a manner as possible, however, it’s important that we follow the
release process above to ensure that the disclosure is handled in a consistent manner.
-->

## 공개 정책

다음은 Node.js의 보안 공개 정책입니다.

- 보안 보고를 받으면 1차 담당자에게 할당됩니다. 이 사람은 수정사항과 릴리스 절차를 조율합니다.
  해당 문제가 확인되면 영향을 받는 버전 목록을 결정합니다. 잠재적으로 비슷한 문제를 일으킬 수 있는
  코드를 점검합니다. 관리 중인 모든 릴리스 버전에 대한 수정사항을 준비합니다. 이 수정사항은
  공개 저장소에 커밋하지 않고 공지할 때까지 로컬에 보관해 둡니다.

- 해당 취약점에 대한 공개 금지 날짜를 결정하고
  CVE(Common Vulnerabilities and Exposures (CVE®))를 요청합니다.

- 공개 금지 날짜가 끝나면 Node.js 보안 메일링 리스트로 공지의 복사본을 보냅니다. 수정사항을 공개
  저장소에 올리고 새로운 빌드를 nodejs.org에 배포합니다. 메일링 리스트에 공지하고 6시간 이내에
  권고안의 복사본을 Node.js 블로그에 발행합니다.

- 보통 공개 금지 날짜는 CVE가 발급된 후 72시간으로 정하지만, 버그의 심각도나 수정의 어려움에 따라
  달라질 수 있습니다.

- 이 절차는 시간이 걸릴 수 있고 다른 프로젝트의 메인테이너들과의 협업이 필요한 경우에는 더 오랜 시간이
  걸릴 수 있습니다. 가능한 최적의 시기에 버그를 처리하려고 노력할 것이지만 정보 공개를 일관되게 하려고
  위에서 설명한 릴리스 절차를 따르는 것이 중요합니다.

<!--
## Receiving Security Updates

Security notifications will be distributed via the following methods.

- [https://groups.google.com/group/nodejs-sec](https://groups.google.com/group/nodejs-sec)
- [https://nodejs.org/en/blog](https://nodejs.org/en/blog)
-->

## 보안 업데이트 받기

다음 방법으로 보안 공지를 합니다.

- <https://groups.google.com/group/nodejs-sec>
- <https://nodejs.org/en/blog>

<!--
## Comments on this Policy

If you have suggestions on how this process could be improved please submit a [pull request](https://github.com/nodejs/nodejs.org)
or email [security@nodejs.org](mailto:security@nodejs.org) to discuss.
-->

## 이 정책에 대한 의견

이 절차를 개선하기 위한 의견이 있다면 논의를 위해 [풀 리퀘스트](https://github.com/nodejs/nodejs.org)를 올리거나
[security@nodejs.org](mailto:security@nodejs.org)로 이메일을 보내주시기 바랍니다.
