# Github Workflow

## Our Team's Workflow

![image](https://user-images.githubusercontent.com/27392567/94516144-1bb69a80-0260-11eb-83cd-4cbcb6f45389.png)

## Master Branch

제품으로 출시될 수 있는 브랜치이다. 배포 가능한 상태만을 관리한다.

필요성: 코드의 안전성을 보장하기 쉽다.

## Hotfix Branch
긴급 버그 수정. 이미 배포한 버전에 긴급하게 수정사항이 생기면, ‘Master’ 브랜치에서 나누어지는 브랜치이다.  

필요성 : ‘Develop’ 브랜치에서 수정사항을 수정하여 배포 가능한 버전을 만들기에는 시간도 많이 소요되고 안정성을 보장하기가 어렵다. 
따라서, ‘Master’브랜치에서 직접 나누어진 ‘Hotfix’ 브랜치에서 수정을 진행하는 것이 효율적이다.

## Develop Branch
기능 개발을 위한 브랜치들을 병합하기 위해 사용되는 브랜치이다.

필요성 : 'Master'브랜치에서 개발을 진행하고 배포를 진행하면 배포된 제품에 버그가 발생할 가능성이 있고 안정성이 떨어지게 된다. 따라서 모든 기능이 추가되고 버그가 수정되어 안정성이 보장된 상태일 때 'Master'브랜치에 병합하는 방식으로 운영될 필요가 있다.
## Feature Branch
