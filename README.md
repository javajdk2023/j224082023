# 24082023

## Configurar versão do Java

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>br.com.fuctura.seunome</groupId>
	<artifactId>projetoSistemaBancario</artifactId>
	<version>0.0.1-SNAPSHOT</version>

	<project xmlns="http://maven.apache.org/POM/4.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>br.com.fuctura.seunome</groupId>
	<artifactId>projetoSistemaBancario</artifactId>
	<version>0.0.1-SNAPSHOT</version>

	<!-- ADICIONE ESTA CONFIGURACAO -->
	<!-- COPIAR A PARTIR DAQUI -->
	<build>
		<plugins>

			<plugin>
				<groupId>org.apache.maven.plugins</groupId>
				<artifactId>maven-compiler-plugin</artifactId>
				<version>3.11.0</version>
				<configuration>
					<source>17</source>
					<target>17</target>
				</configuration>
			</plugin>

		</plugins>
	</build> <!-- COPIAR ATÉ AQUI -->

</project>
	
````
