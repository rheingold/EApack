Repository.


Uses following sumbodules containing clones of:

https://github.com/rheingold/Enterprise-Architect-Toolpack.git	from https://github.com/GeertBellekens/Enterprise-Architect-Toolpack
https://github.com/rheingold/Enterprise-Architect-Add-in-Framework.git from https://github.com/GeertBellekens/Enterprise-Architect-Add-in-Framework
https://github.com/rheingold/UML-Tooling-Framework from https://github.com/GeertBellekens/UML-Tooling-Framework
https://github.com/rheingold/DDL-Parser.git from https://github.com/GeertBellekens/DDL-Parser
https://github.com/rheingold/cobol-object-mapper.git from https://github.com/GeertBellekens/cobol-object-mapper



git submodule foreach 'git branch rheingold/FeatureName'

git submodule foreach 'git checkout rheingold/FeatureName'

git submodule foreach 'git add .'

git submodule foreach 'git commit -m "MESSAGE"'