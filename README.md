# linuxtips

Exercicio proposto pela Linuxtips.

Realizados:

* Criar um grupo de usuários no IAM, chamado Operations
* Configurar o AWS Cloud Trail
* Criar um VPC chamado Giropops. 
* Duas subnets, uma privada e outra publica
* Criar duas instâncias ec2 para funcionar como webserver (porta tcp 80) e 02 para que seja o nosso database (seria um database Postgresql)
* Em nossa subnet publica, teremos o nossos web servers
* Em nossa subnet privada, teremos os nossos databases
* Não esqueça do nosso security group!
* Nesse VPC, precisamos ter todos os componentes (NAT, GWs, Sec Group) necessários para que nossas subnets funcionem adequadamente.


Não realizados pois apresentava erro do modo como eu tentava resolver:

* Criar iam role e 'attachar' a um grupo de usuários de Operação, com permissão PowerUsers
* Habilitar as seguintes regras de AWS Config: required-tags, root-account-mfa-enabled, iam-password-policy e approved-amis-by-id

Obs: Só está sendo possível subir este CloudFormation na região São Paulo. Na região Virgina apresenta erro. Não testei em outras regiões.
