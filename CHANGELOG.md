## 1.4.27 (2025-04-25)

#### Bug Fixes

* pr validation does not require upper casing anymore (bc135a17)


## 1.4.26 (2025-02-14)

#### Bug Fixes

* new build version (6cbcd6c7)
* docker build and publish (18068c8e)


## 1.4.25 (2024-12-10)

#### Bug Fixes

* donot use load flag on container build (37f53f4f)


## 1.4.24 (2024-12-06)

#### Bug Fixes

* platform parameter (a6fae125)
* string quote (b72bf184)
* Debug publish images (80b1c560)


## 1.4.23 (2024-12-06)

#### Bug Fixes

* manual push (b5e4aaae)


## 1.4.22 (2024-12-06)

#### Bug Fixes

* mondoo tag scan (aaf90332)
* multiline output/input (15a393de)
* multiline output/input (69412428)
* multiline output/input (375efd03)
* tags (90c8d3e0)
* tags (a8808703)
* tags (08e0d589)
* eoi of subcommands (7703493b)
* refactor image creation name processing (4f75e235)


## 1.4.21 (2024-12-06)

#### Bug Fixes

* rename ghcr container image name based on image_name var (8ea25356)


## 1.4.20 (2024-12-06)

#### Bug Fixes

* no mondoo scan if token is not available (263cdc71)


## 1.4.19 (2024-08-14)

#### Bug Fixes

* reorganize terratest flows (63a09170)


## 1.4.18 (2024-08-14)

#### Bug Fixes

* hcp auth (02d78a8b)
* testing (bdbe40fd)
* testing (62457c80)
* test timeout as optional (d5b62a95)
* test timeout as optional (f079579b)
* custom terraform test flow (dc976a85)


## 1.4.17 (2024-05-14)

#### Bug Fixes

* Seperate action (3b39cb53)
* Workflow action def (f3fb366b)

#### Code Refactoring

* Change ref from gh action to .github (3a86978a)


## 1.4.16 (2024-05-13)

#### Bug Fixes

* Reset to inheritance (6442a687)
* update changelog ref (536488fa)
* refs to secrets are passed not inherited (18647121)
* vault secrets (8bc2a016)


## 1.4.15 (2024-05-08)

#### Bug Fixes

* build args on both actions (1327dc94)
* Adding buildargs on container input (76c729a8)


## 1.4.14 (2024-05-08)

#### Bug Fixes

* Define required secrets for workflow dispatches (c58dd695)
* using vault data (5559560f)


## 1.4.13 (2024-05-07)

#### Bug Fixes

* adding dedicated image to scan (337da612)
* no debug (07760225)
* adding debug log level (e3c21bb6)
* update vars (6df37ca9)
* update if (270cd5d9)
* container build action (55aaf489)

#### Code Refactoring

* using inputs (449f2cd2)


## 1.4.12 (2024-04-26)

#### Bug Fixes

* release workflow changelog update should not trigger actions (208ea38c)


## 1.4.11 (2024-04-26)

#### Bug Fixes

* release workflow changelog update should not trigger actions (64404cb7)
* Adding workflows for cleanup (83985a49)

#### Chores

* **ci:** commit changes from go-semantic-release (0d925b77)


## 1.4.10 (2024-04-18)

#### Bug Fixes

* container flow (74d7fa99)

#### Chores

* **ci:** commit changes from go-semantic-release (1cb61ee4)


## 1.4.9 (2024-04-18)

#### Bug Fixes

* container flow (e188dc5d)

#### Chores

* **ci:** commit changes from go-semantic-release (3d91a363)


## 1.4.8 (2024-04-18)

#### Bug Fixes

* container flow (690ebce5)

#### Chores

* **ci:** commit changes from go-semantic-release (389b0b27)


## 1.4.7 (2024-04-18)

#### Bug Fixes

* **workflows:** refactor container workflow (525e6816)
* increment auto commit action version (017bb961)

#### Chores

* **ci:** commit changes from go-semantic-release (164a9861)


## 1.4.6 (2024-04-18)

#### Bug Fixes

* Adding PR Validation Step name (cde30176)

#### Chores

* **ci:** commit changes from go-semantic-release (4c2ceafc)


## 1.4.5 (2024-04-18)

#### Bug Fixes

* changelogging (895d1ad9)


## 1.3.1 (2024-04-18)

#### Bug Fixes

* update pre-commit and fixxes of findings (91517d8a)
* update refs (a24b8fbf)
* changelog automation update (7325d86b)

#### Chores

* **ci:** commit changes from go-semantic-release (e4a1a000)


## 1.3.0 (2024-01-12)

#### Feature

* org readme (f3425a59)

#### Chores

* **ci:** commit changes from go-semantic-release (905cfc69)


## 1.2.0 (2024-01-12)

#### Feature

* hcp vault secrets sync (4ad56f6e)

#### Chores

* **ci:** commit changes from go-semantic-release (8caaf7b7)


## 1.1.0 (2023-03-15)

#### Feature

* adding ghcr template; removing docker hub (43f6d7f9)

#### Chores

* **ci:** commit changes from go-semantic-release (60ee77e8)


## 1.0.1 (2022-10-14)

#### Bug Fixes

* bot token access (27b3952f)
* fix changelog EOL (3737c75e)
* add protected branches capabilities (cfd6f828)
* update to use Maschine user (c1fe811e)

#### Chores

* **ci:** commit changes from go-semantic-release (c255adb6)


## 1.0.0 (2022-09-28)

#### Feature

* changelog automation (1dd970c2)
* adding changlog automation workflow template (758a64ce)

#### Bug Fixes

* update changelog triggers (f8ee396d)
* update of changelog (73ef31ee)
* update container with changelog workflow (e17edabe)
