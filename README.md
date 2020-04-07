# farmacias
proyecto de negocio de una farmacia

create database FARMACIA
use FARMACIA

--crear las tablas


create table empleados
(
id_empl varchar(8) primary key not null,
nombre varchar(25)not null,
apell varchar(25)not null,
turno varchar(2)not null,
)
go

create table clientes
(
codi_client varchar(8) primary key not null,
nom_client varchar(25)not null,
apell_cli varchar(25)not null,
tel_client varchar(12)not null,
)
go

create table productos
(
cod_produ varchar(8) primary key not null,
nom_produ varchar(25) not null,
fabr_produ varchar(25) not null,
prec_produ varchar(8) not null,
stok_produ varchar(8) not null,
ubuca_produ varchar(8) not null
)
go

create table suplidores
(
nom_supli varchar(25) primary key not null,
num_pedid varchar(8) not null,
tel_suplid varchar(12) not null,
)
go

insert into empleados
(id_empl,nombre,apell,turno)
values ('1','armando','molina','1');

insert into empleados
(id_empl,nombre,apell,turno)
values (2,'josefina','perz',2)

insert into empleados
(id_empl,nombre,apell,turno)
values (4,'carmen','payano',1)

insert into empleados
(id_empl,nombre,apell,turno)
values (6,'katy','martinez',1)

insert into empleados
(id_empl,nombre,apell,turno)
values (7,'carlos','sanchez',2)

insert into empleados
(id_empl,nombre,apell,turno)
values (8,'emilio','lon',2)

insert into empleados
(id_empl,nombre,apell,turno)
values (10,'juan','jaquz',2)

insert into empleados
(id_empl,nombre,apell,turno)
values (15,'juan','lorenzo',3)

insert into empleados
(id_empl,nombre,apell,turno)
values (20,'cesarina','santiago',3)


insert into clientes
(codi_client,nom_client,apell_cli,tel_client)
values (45,'henrry','pena',8095376652)

insert into clientes
values (48,'alberto','valerio',809637683)

insert into clientes
values (47,'jorge','amancio',8097362819)

insert into clientes
values (49,'juana','pachceco',8095647389)

insert into clientes
values (50,'pedro','sanchez',8298987746)

insert into clientes
values (52,'lucas','marinez',8297886376)

insert into clientes
values (53,'ana','perez',8097768346)

insert into clientes
values (58,'jose','mendez',8094533679)

insert into clientes
values (57,'pablo','garcia',8097362819)

insert into clientes
values (59,'karla','rose',8097364719)

insert into clientes
values (60,'julio','almanzar',803776493)

insert into clientes
values (61,'erik','matos',8097367848)

insert into clientes
values (462,'jorge','romero',8097362678)

insert into clientes
values (63,'raisa','adames',8092673976)

insert into clientes
values (64,'lidia','casado',8097388889)

insert into clientes
values (68,'fajardo','amancio',809657848)

insert into clientes
values (69,'enmanuel','lizardoo',809774662)

insert into clientes
values (70,'pancho','lucas',8097362819)

insert into clientes
values (73,'jorge','manzanillo',8097383919)

insert into clientes
values (74,'matias','perez',8097764562)

insert into clientes
values (48,'maria','garcia',8096445623)


insert into productos
(cod_produ,nom_produ,fabr_produ,prec_produ,stok_produ,ubuca_produ)
values (23,'acetaminifen 500mg','MK',75,400,'P3LAN3')


insert into productos
values (24,'acetaminifen jarab','MK',85,325,'P3LAN2')

insert into productos
values (25,'winasorb','MAGNACHEM',25,545,'P2LBN1')

insert into productos
values (26,'winasorb ultra','MAGNACHEM',35,436,'P2LAN3')

insert into productos
values (27,'tabcin','MK',30,239,'P2LBN1')

insert into productos
values (28,'tabcin te','MK',50,305,'P4LBN3')

insert into productos
values (29,'complejo b jarab','ROWE',75,400,'P1LAN3')


insert into productos
values (30,'antifudes 500mg','UNION',45,350,'P3LAN3')

insert into productos
values (31,'antifudes te','UNION',54,232,'P3LBN1')

insert into productos
values (32,'laritox 500mg','BAYER',78,344,'P1LCN2')

insert into productos
values (33,'laritox jarab','BAYER',300,179,'P1LCN2')

insert into productos
values (34,'alcohol 500mg','COLLADO',250,240,'P3LAN3')

insert into productos
values (35,'coralax 500mg','ETHICAL',800,567,'P4LBN2')

insert into productos
values (36,'sumox 500mg','ALPHA',746,400,'P3LAN3')

insert into productos
values (37,'algodon ','UNION',50,400,'P2LAN1')

insert into productos
values (38,'jeringa 3cc','UNION',50,800,'P3LAN3')

insert into productos
values (39,'jeinga 5cc','UNION',45,400,'P3LCN2')

insert into productos
values (40,'prolyn 500mg','ACROMAX',239,140,'P2LAN3')

insert into productos
values (41,'vitamina c 500mg','ROWE',150,400,'P2LAN1')

insert into productos
values (42,'ovulos 500mg','ACROMAX',300,600,'P4LBN1')

insert into productos
values (43,'suero bols','UNION',80,330,'P3LAN3')

insert into productos
values (44,'vic vaporus 500mg','MAGNACHEM',155,434,'P3LAN3')

insert into productos
values (45,'mentol blanco','MAGNACHEM',200,167,'P2LBN3')

insert into productos
values (46,'pastilla bacal','MK',20,329,'P3LAN3')

insert into productos
values (47,'prodon 500mg','COLLADO',24,768,'P1LAN1')

insert into productos
values (48,'pectobismol 500mg','MK',75,400,'P3LAN3')

insert into productos
values (49,'zentel 100mg','ROWE',89,264,'P2LBN1')

insert into productos
values (50,'gasa 500mg','UNION',75,400,'P1LCN1')

insert into productos
values (51,'wipes ','PEQUE',146,400,'P3LAN3')

insert into productos
values (52,'complejo b pas 500mg','MK',20,400,'P1LBN3')

insert into productos
values (35,'inflavir jarabe','MALLEN',400,345,'P2LBN5')


insert into suplidores
(nom_supli,num_pedid,tel_suplid)
values ('MAGNACHEM',37655,8093221156)

insert into suplidores
values ('MK',37657,8097449823)

insert into suplidores
values ('UNION',37658,8094553678)

insert into suplidores
values ('ALPHA',37659,8096551478)

insert into suplidores
values ('ACROMAX',42661,8098447725)

insert into suplidores
values ('BAYER',47656,8096378904)

insert into suplidores
values ('COLLADO',47654,8096551045)

insert into suplidores
values ('ETHICAL',47857,8096473939)

insert into suplidores
values ('ROWE',47639,8093667745)


insert into suplidores
values ('UNION2',37656,8096551123)
