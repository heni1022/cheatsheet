@import url(http://fonts.googleapis.com/css?family=Open+Sans);

@import url(/absolute/something.css) screen and (color) and (max-width: 600px);

@var: 100px;
@import url("//ha.com/file.css") (min-width:@var);

#import-test {
  .mixin;
  width: 10px;
  height: (@a + 10%);
}
@import "import/import-test-e" screen and (max-width: 600px);

@import url("import/import-test-a.less");