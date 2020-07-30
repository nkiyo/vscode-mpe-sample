@import "sample.csv"

@import "sample.csv" {line_begin=2 line_end=4}

@import "sample.jpg"

## githubからファイルをimportする例
@import "https://raw.githubusercontent.com/nkiyo/vscode-mpe-sample/master/todo.md" {line_begin=1 line_end=2}

@import "https://raw.githubusercontent.com/nkiyo/vuecli_element_sample/master/package.json"
