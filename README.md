# jitpack


JitPack là gì?

https://github.com/jitpack

Dễ dàng sử dụng các package repository. JitPack builds các project trên github và chuyển nó thành các .jar có thể sử dụng như các thư viện.
Nếu bạn muốn thư viện của mình to be available với thế giới. Chỉ cần xây dựng project của mình và upload lên github. JitPack sẽ lo phần còn lại.

Để sử dụng nó ta làm như sau: https://jitpack.io/

Step1: add Jitpack repository vào file pom.
	
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>

Step2: add dependency
	
	<dependency>
	    <groupId>com.github.User</groupId>
	    <artifactId>Repo</artifactId>
	    <version>Tag</version>
	</dependency>
	
Lần đầu tiên khi request 1 project JitPack sẽ checkout code, build nó và trả nó về dạng .jar, .aar	# javamail
