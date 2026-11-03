
[![Badge GPL2]][License]
[![Badge LGPL]][License]

<div align = center>

<br>
  
# LinuxCNC
  
*Controlling CNC Machines*

<br>
  
[![Badge Translation]][Translation]
  
<br>
  
---

[<kbd> <br> Ｗｅｂｓｉｔｅ <br> </kbd>][Website] 
[<kbd> <br> Ｉｎｓｔａｌｌ <br> </kbd>][Ｉｎｓｔａｌｌ] 
[<kbd> <br> Ｂｕｉｌｄ <br> </kbd>][Ｂｕｉｌｄ] 
[<kbd> <br> Ｄｏｃｕｍｅｎｔａｔｉｏｎ <br> </kbd>][Ｄｏｃｕｍｅｎｔａｔｉｏｎ]  
  
---

<br>
  
It can drive milling machines, lathes, 3D printers, laser <br>
cutters, plasma cutters, robot arms, hexapods, and more.

LinuxCNC was initiated 25 years ago and evolved into a very <br>
international project with contributions from all over the globe.
  
With release 2.9 of LinuxCNC we also transitioned the <br>
documentation to the use of the public crowd translation <br>
services [Weblate] and invite all our users to contribute.
  
The translations we expect to help attract practitioners <br>
to the project and also helps educating enthusiasts of <br>
all age groups on automated machining.

<br>

## DISCLAIMER
  
<br>

```
  
Ｔｈｅ ａｕｔｈｏｒｓ ｏｆ ｔｈｉｓ ｓｏｆｔｗａｒｅ ａｃｃｅｐｔ
ａｂｓｏｌｕｔｅｌｙ ｎｏ ｌｉａｂｉｌｉｔｙ ｆｏｒ ａｎｙ
ｈａｒｍ　ｏｒ ｌｏｓｓ ｒｅｓｕｌｔｉｎｇ ｆｒｏｍ ｉｔｓ ｕｓｅ．

Ｉｔ ｉｓ ＥＸＴＲＥＭＥＬＹ ｕｎｗｉｓｅ ｔｏ　ｒｅｌｙ
ｏｎ ｓｏｆｔｗａｒｅ ａｌｏｎｅ ｆｏｒ ｓａｆｅｔｙ．

Any machinery capable of harming persons must have
provisions for completely removing power from all
motors, etc, before persons enter any danger area.

All machinery must be designed to comply with local 
and national safety codes, and the authors of this 
software cannot and do not, take any responsibility 
for such compliance.
  
```

<br>
  
</div>

<!----------------------------------------------------------------------------->

[Badge Translation]: https://hosted.weblate.org/widgets/linuxcnc/-/svg-badge.svg
[Badge GPL2]: https://img.shields.io/badge/Most-LGPL_3-blue.svg?style=for-the-badge 'The license this software is under'
[Badge LGPL]: https://img.shields.io/badge/Some-GPL_2-blue.svg?style=for-the-badge 'Some parts are under this license'

[Translation]: https://hosted.weblate.org/engage/linuxcnc/
[Weblate]: https://hosted.weblate.org/projects/linuxcnc/
[Website]: https://linuxcnc.org/

[Ｄｏｃｕｍｅｎｔａｔｉｏｎ]: http://linuxcnc.org/docs/stable/html/
[Ｉｎｓｔａｌｌ]: http://linuxcnc.org/docs/stable/html/getting-started/getting-linuxcnc.html
[Ｂｕｉｌｄ]: http://linuxcnc.org/docs/stable/html/code/building-linuxcnc.html
[License]: COPYING

## Repository status and workstream maintenance

Documentation review: 3 November 2026. This is repository-local status, not an upstream release or deployment acceptance.

### Purpose and function

LinuxCNC controls CNC machines. It can drive milling machines, lathes, 3d printers, laser cutters, plasma cutters, robot arms, hexapods, and more.

### Current objective

Maintain a clearly documented local copy for authorised evaluation/development, preserving upstream attribution and distinguishing local changes from upstream capabilities.

### Progress and evidence

This is a fork of LinuxCNC/linuxcnc. Existing upstream documentation and attribution are retained. Local customisation, upstream parity, build success and runtime/hardware acceptance have not been verified in this documentation review.

### Next steps and roadmap

1. Confirm the next owner-approved outcome and reconcile this default branch with the workstream's actual source, test evidence and deployed version.
2. Compare with the upstream project before updating and use an appropriate disposable/non-live test setup.
3. Keep completed/in-progress/blocked work and next actions current here. Broader feature priorities remain for the owning workstream to agree; this update does not invent a feature commitment.

### Documentation chain

Read this README first, then the existing records and source/example entry points below. Listed paths were observed on the inspected default branch; source folders are not test results.

- [docs](docs)
- [tests](tests)
- [src](src)

- [Upstream repository](https://github.com/LinuxCNC/linuxcnc)

### Standing instruction for every workstream

Every agent, developer or project workstream maintaining this repository must automatically keep this README current with its purpose/function, agreed objective, dated progress, blockers, roadmap/next actions and links to authoritative records. Update it when these facts materially change, at meaningful milestones and before handback, interruption or completion; do not wait for a separate owner reminder.

Read applicable project instructions, preserve concurrent work and existing attribution/licences, and distinguish source commits from deployed versions and verified results. Link requirements, design, handover, validation and recovery records when they exist rather than creating conflicting copies. If a fact is unknown, say so and identify the next verification action. Check affected links, publish authorised changes and verify the remote commit before claiming completion.

Keep credentials, private infrastructure/access routes, private datasets and confidential material out of public documentation. This instruction does not grant new access, replace project-specific authority or approve untested hardware/live operations. Retain detailed historical evidence in project records/version history rather than an ever-growing README log.
