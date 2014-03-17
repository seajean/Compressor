Compressor
==========

tools to compress html, css

##html compiler usage

java -jar jar/htmlcompiler.jar -o output.html -t html  --compress-css  --js-compressor closure --closure-externs jar/closure_compiler.jar --compress-js  input.html 

java -jar ${htmlCompiler} --preserve-server-script --type html -o ${output} "${input}"
