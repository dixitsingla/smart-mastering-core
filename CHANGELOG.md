# Change Log

## [v1.2.4](https://github.com/marklogic-community/smart-mastering-core/tree/v1.2.4) (2019-02-01)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.2.2...v1.2.4)

**Implemented enhancements:**

- Use variable for DHF version in build.gradle that is set in gradle.properties [\#277](https://github.com/marklogic-community/smart-mastering-core/issues/277)
- Update example DHF project to 4.1.1 [\#276](https://github.com/marklogic-community/smart-mastering-core/issues/276)

**Fixed bugs:**

- Thesauri and synonym expansion does not check document format [\#283](https://github.com/marklogic-community/smart-mastering-core/issues/283)
- sm-match endpoint tries to match XML docs when POSTing a JSON doc [\#279](https://github.com/marklogic-community/smart-mastering-core/issues/279)
- Merge is pulling in TDE triples for documents on merge [\#278](https://github.com/marklogic-community/smart-mastering-core/issues/278)
- Don't require sources in order to merge [\#274](https://github.com/marklogic-community/smart-mastering-core/issues/274)
- Empty responses for sm-notifications PUT and DELETE [\#272](https://github.com/marklogic-community/smart-mastering-core/issues/272)
- match-and-merge throws error with mixed match results [\#271](https://github.com/marklogic-community/smart-mastering-core/issues/271)
- Merge options name is returned truncated \('-xml' removed\) [\#270](https://github.com/marklogic-community/smart-mastering-core/issues/270)

**Merged pull requests:**

- Fixes \#279 [\#280](https://github.com/marklogic-community/smart-mastering-core/pull/280) ([patrickmcelwee](https://github.com/patrickmcelwee))
- Ryanjdew minimal readme [\#275](https://github.com/marklogic-community/smart-mastering-core/pull/275) ([ryanjdew](https://github.com/ryanjdew))
- Release v1.2.2 [\#269](https://github.com/marklogic-community/smart-mastering-core/pull/269) ([ryanjdew](https://github.com/ryanjdew))

## [v1.2.2](https://github.com/marklogic-community/smart-mastering-core/tree/v1.2.2) (2018-12-27)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.2.1...v1.2.2)

**Implemented enhancements:**

- Enhancement : collection pattern consistency when saving match and merge options [\#213](https://github.com/marklogic-community/smart-mastering-core/issues/213)
- Add optional tracing to matching and merging operations [\#172](https://github.com/marklogic-community/smart-mastering-core/issues/172)

**Fixed bugs:**

- Documentation typo under sm-notifications [\#264](https://github.com/marklogic-community/smart-mastering-core/issues/264)
- Error when trying to remove a match block via REST [\#263](https://github.com/marklogic-community/smart-mastering-core/issues/263)
-  latest document has only duplicate objects in an array, merged document is returning an object but it has to return an array [\#259](https://github.com/marklogic-community/smart-mastering-core/issues/259)
- Reopening max-sources=1 issue [\#258](https://github.com/marklogic-community/smart-mastering-core/issues/258)
- Merge issue with empty object in an array [\#254](https://github.com/marklogic-community/smart-mastering-core/issues/254)
- Not running already merged document through mastering again [\#252](https://github.com/marklogic-community/smart-mastering-core/issues/252)
- Merged document sources property in headers is changing to object [\#251](https://github.com/marklogic-community/smart-mastering-core/issues/251)
- Removing empty string properties on merging [\#250](https://github.com/marklogic-community/smart-mastering-core/issues/250)
- Merging not working as expected with deeply nested JSON Arrays and Objects [\#246](https://github.com/marklogic-community/smart-mastering-core/issues/246)
- Ensure required security deployed as part of minimal project [\#245](https://github.com/marklogic-community/smart-mastering-core/issues/245)
- find-document-matches-by-options-name function does not report same result after unmerge [\#233](https://github.com/marklogic-community/smart-mastering-core/issues/233)
- Merging two documents with max-values=1 changes an array property to object [\#218](https://github.com/marklogic-community/smart-mastering-core/issues/218)

**Closed issues:**

- On default max-values="1" Merged record has to get all objects from the latest document but taking only one object from the latest document [\#253](https://github.com/marklogic-community/smart-mastering-core/issues/253)
- smart-mastering-core/examples/dhf-flow missing gradle-local.properties [\#247](https://github.com/marklogic-community/smart-mastering-core/issues/247)

**Merged pull requests:**

- Fix documentation typo GH\#264 [\#268](https://github.com/marklogic-community/smart-mastering-core/pull/268) ([ryanjdew](https://github.com/ryanjdew))
- \#263 return document-nodes from sm-block-match [\#265](https://github.com/marklogic-community/smart-mastering-core/pull/265) ([dmcassel](https://github.com/dmcassel))
- Minor 1.2.1 related updates [\#257](https://github.com/marklogic-community/smart-mastering-core/pull/257) ([ryanjdew](https://github.com/ryanjdew))

## [v1.2.1](https://github.com/marklogic-community/smart-mastering-core/tree/v1.2.1) (2018-11-26)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.2.0...v1.2.1)

**Implemented enhancements:**

- Missing documentation details regarding thesaurus use for matching [\#207](https://github.com/marklogic-community/smart-mastering-core/issues/207)
- Allow processMatchAndMerge to put unmatched documents into the mastered collections [\#191](https://github.com/marklogic-community/smart-mastering-core/issues/191)
- Enable users to control collections during merging [\#190](https://github.com/marklogic-community/smart-mastering-core/issues/190)

**Fixed bugs:**

- An array of objects wraps any duplicate objects in an additional parent property in the merged record [\#235](https://github.com/marklogic-community/smart-mastering-core/issues/235)
- Match result reported with matcher:find-document-matches-by-options-name does not list match based on dbl-metaphone algorithm [\#208](https://github.com/marklogic-community/smart-mastering-core/issues/208)

**Closed issues:**

- Can't open smart-mastering-core/examples/dhf-flow with DHF QuickStart v4.0.3 [\#255](https://github.com/marklogic-community/smart-mastering-core/issues/255)

**Merged pull requests:**

- 1.2.1 release [\#256](https://github.com/marklogic-community/smart-mastering-core/pull/256) ([ryanjdew](https://github.com/ryanjdew))
- Correct on-no-match description [\#249](https://github.com/marklogic-community/smart-mastering-core/pull/249) ([ryanjdew](https://github.com/ryanjdew))
- GH \#246 handle deeply nested JSON with merge [\#248](https://github.com/marklogic-community/smart-mastering-core/pull/248) ([ryanjdew](https://github.com/ryanjdew))

## [v1.2.0](https://github.com/marklogic-community/smart-mastering-core/tree/v1.2.0) (2018-11-12)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.1.1...v1.2.0)

**Implemented enhancements:**

- Use consistent naming for similar functions [\#201](https://github.com/marklogic-community/smart-mastering-core/issues/201)
- Document how to integrate smart mastering into DHF 4 and update example project [\#186](https://github.com/marklogic-community/smart-mastering-core/issues/186)
- Clarify the data model requirements needed [\#174](https://github.com/marklogic-community/smart-mastering-core/issues/174)
- Declare default algorithms in merging options [\#170](https://github.com/marklogic-community/smart-mastering-core/issues/170)
- Allow the collection names to be configurable [\#153](https://github.com/marklogic-community/smart-mastering-core/issues/153)
- Provide config example in comments for each algorithm [\#87](https://github.com/marklogic-community/smart-mastering-core/issues/87)

**Fixed bugs:**

- Default merge strategy doesn't apply to headers section [\#230](https://github.com/marklogic-community/smart-mastering-core/issues/230)
- merge.getOptionNames\(constant.FORMATJSON\) does not return all saved merge options [\#200](https://github.com/marklogic-community/smart-mastering-core/issues/200)
- URI of a merged json document shows .xml extension [\#188](https://github.com/marklogic-community/smart-mastering-core/issues/188)
- Documentation's page "Smart Mastering with Libraries" contains a dead link [\#183](https://github.com/marklogic-community/smart-mastering-core/issues/183)

**Closed issues:**

- Documentation - Merging Options : missing explanation for source-weights/sourceWeights use [\#216](https://github.com/marklogic-community/smart-mastering-core/issues/216)
- Documentation - Merging Options : source-weights / sourceWeights not explained [\#215](https://github.com/marklogic-community/smart-mastering-core/issues/215)
- Clarify that to merge based on data freshness \(e.g., timestamp\) there must be data sources provided in a specific format [\#175](https://github.com/marklogic-community/smart-mastering-core/issues/175)
- Document specific available algorithms and their usage for both matching and merging [\#168](https://github.com/marklogic-community/smart-mastering-core/issues/168)

**Merged pull requests:**

- Update docs for 1.2.0 release [\#242](https://github.com/marklogic-community/smart-mastering-core/pull/242) ([ryanjdew](https://github.com/ryanjdew))
- Smart Mastering 1.2.0 release [\#241](https://github.com/marklogic-community/smart-mastering-core/pull/241) ([ryanjdew](https://github.com/ryanjdew))
- Avoid constructing additional level when merging array properties [\#240](https://github.com/marklogic-community/smart-mastering-core/pull/240) ([ryanjdew](https://github.com/ryanjdew))
- Allow headers to be handled with default merge strategy [\#238](https://github.com/marklogic-community/smart-mastering-core/pull/238) ([ryanjdew](https://github.com/ryanjdew))
- Ensure custom actions are included in match results [\#237](https://github.com/marklogic-community/smart-mastering-core/pull/237) ([ryanjdew](https://github.com/ryanjdew))
- Add documentation for new collection options [\#236](https://github.com/marklogic-community/smart-mastering-core/pull/236) ([ryanjdew](https://github.com/ryanjdew))
- Allow custom ways of handling collections [\#234](https://github.com/marklogic-community/smart-mastering-core/pull/234) ([ryanjdew](https://github.com/ryanjdew))
- Allow custom collection names [\#231](https://github.com/marklogic-community/smart-mastering-core/pull/231) ([ryanjdew](https://github.com/ryanjdew))
- Mdm 576: \#200 fix get option names as JSON [\#229](https://github.com/marklogic-community/smart-mastering-core/pull/229) ([dmcassel](https://github.com/dmcassel))
- added sm-match-and-merge and a toc [\#228](https://github.com/marklogic-community/smart-mastering-core/pull/228) ([dmcassel](https://github.com/dmcassel))
- Docs next catchup [\#227](https://github.com/marklogic-community/smart-mastering-core/pull/227) ([dmcassel](https://github.com/dmcassel))
- Mdm 516: Add match-and-merge service; update dhf-flow example to use it [\#226](https://github.com/marklogic-community/smart-mastering-core/pull/226) ([dmcassel](https://github.com/dmcassel))
- Ensure double metaphone matches appear in results [\#224](https://github.com/marklogic-community/smart-mastering-core/pull/224) ([ryanjdew](https://github.com/ryanjdew))
- Preserve array when only one value exists [\#223](https://github.com/marklogic-community/smart-mastering-core/pull/223) ([ryanjdew](https://github.com/ryanjdew))
- Add mlcp options file for push to globalsearch.marklogic.com [\#222](https://github.com/marklogic-community/smart-mastering-core/pull/222) ([kghmanuel](https://github.com/kghmanuel))
- Mdm 575: make matching function names consistent with merging names [\#221](https://github.com/marklogic-community/smart-mastering-core/pull/221) ([dmcassel](https://github.com/dmcassel))
- Mdm 566: update examples to DHF4 [\#220](https://github.com/marklogic-community/smart-mastering-core/pull/220) ([dmcassel](https://github.com/dmcassel))
- removing duplicate entry, which caused validation to fail [\#212](https://github.com/marklogic-community/smart-mastering-core/pull/212) ([dmcassel](https://github.com/dmcassel))
- further updates about loading thesauri [\#211](https://github.com/marklogic-community/smart-mastering-core/pull/211) ([dmcassel](https://github.com/dmcassel))
- clarified thesaurus insert instructions [\#210](https://github.com/marklogic-community/smart-mastering-core/pull/210) ([dmcassel](https://github.com/dmcassel))
- Docs next [\#209](https://github.com/marklogic-community/smart-mastering-core/pull/209) ([dmcassel](https://github.com/dmcassel))
- MDM-541: removing comments that were moved to the documentation [\#206](https://github.com/marklogic-community/smart-mastering-core/pull/206) ([dmcassel](https://github.com/dmcassel))
- Mdm 541: Adding documentation about included algorithms [\#205](https://github.com/marklogic-community/smart-mastering-core/pull/205) ([dmcassel](https://github.com/dmcassel))
- Mdm 516: pass multiple URIs into process-match-and-merge [\#152](https://github.com/marklogic-community/smart-mastering-core/pull/152) ([dmcassel](https://github.com/dmcassel))

## [v1.1.1](https://github.com/marklogic-community/smart-mastering-core/tree/v1.1.1) (2018-10-12)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.1.0...v1.1.1)

**Implemented enhancements:**

- Have meaningful error responses on incomplete REST endpoint calls [\#144](https://github.com/marklogic-community/smart-mastering-core/issues/144)

**Fixed bugs:**

- Smart Mastering documentation has link to smart-mastering-demo [\#177](https://github.com/marklogic-community/smart-mastering-core/issues/177)
- Getting sources timestamps from JSON documents always returns null instead of the timestamp [\#176](https://github.com/marklogic-community/smart-mastering-core/issues/176)
- Matching fails due to a missing namespace in the match query [\#166](https://github.com/marklogic-community/smart-mastering-core/issues/166)
- Error with rs:includeMatches param in sm-match endpoint [\#146](https://github.com/marklogic-community/smart-mastering-core/issues/146)
- Get 500 error when sending match options in POST body [\#145](https://github.com/marklogic-community/smart-mastering-core/issues/145)

**Merged pull requests:**

- Updates for v1.1.1 [\#199](https://github.com/marklogic-community/smart-mastering-core/pull/199) ([dmcassel](https://github.com/dmcassel))
- changes for v1.1.1 [\#198](https://github.com/marklogic-community/smart-mastering-core/pull/198) ([dmcassel](https://github.com/dmcassel))
- Updating docs for v1.1.1 release [\#197](https://github.com/marklogic-community/smart-mastering-core/pull/197) ([dmcassel](https://github.com/dmcassel))
- \#188 merged URI extension should depend on the format of source files [\#196](https://github.com/marklogic-community/smart-mastering-core/pull/196) ([dmcassel](https://github.com/dmcassel))
- Mdm 438: documenting algorithm configurations [\#195](https://github.com/marklogic-community/smart-mastering-core/pull/195) ([dmcassel](https://github.com/dmcassel))
- adding a new test suite for double-metaphone [\#189](https://github.com/marklogic-community/smart-mastering-core/pull/189) ([dmcassel](https://github.com/dmcassel))
- Mdm 541: documentation about custom algorithms [\#185](https://github.com/marklogic-community/smart-mastering-core/pull/185) ([dmcassel](https://github.com/dmcassel))
- Adding information about custom functions [\#182](https://github.com/marklogic-community/smart-mastering-core/pull/182) ([dmcassel](https://github.com/dmcassel))
- Changing smart-mastering-demo links to point to examples [\#181](https://github.com/marklogic-community/smart-mastering-core/pull/181) ([dmcassel](https://github.com/dmcassel))
- Mdm 551: fix error in get-sources affecting JSON data [\#180](https://github.com/marklogic-community/smart-mastering-core/pull/180) ([dmcassel](https://github.com/dmcassel))
- MDM-552 GH \#177 Fix outdated link in documentation [\#179](https://github.com/marklogic-community/smart-mastering-core/pull/179) ([ryanjdew](https://github.com/ryanjdew))
- MDM-544 Update docs to show an example of merge strategies [\#178](https://github.com/marklogic-community/smart-mastering-core/pull/178) ([ryanjdew](https://github.com/ryanjdew))
- MDM-544 Added ability to set a default merge and define merge strategies [\#173](https://github.com/marklogic-community/smart-mastering-core/pull/173) ([ryanjdew](https://github.com/ryanjdew))
- MDM-542 Preserve element namespaces in match queries [\#169](https://github.com/marklogic-community/smart-mastering-core/pull/169) ([ryanjdew](https://github.com/ryanjdew))
- Adding error code documentation [\#167](https://github.com/marklogic-community/smart-mastering-core/pull/167) ([dmcassel](https://github.com/dmcassel))
- MDM-490 Restrict matches to within instance [\#165](https://github.com/marklogic-community/smart-mastering-core/pull/165) ([ryanjdew](https://github.com/ryanjdew))
- MDM-486 Add Smart Mastering Error codes to docs [\#164](https://github.com/marklogic-community/smart-mastering-core/pull/164) ([ryanjdew](https://github.com/ryanjdew))

## [v1.1.0](https://github.com/marklogic-community/smart-mastering-core/tree/v1.1.0) (2018-09-25)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.0.0...v1.1.0)

**Closed issues:**

- MDMImport input flow output collections are in upper case [\#140](https://github.com/marklogic-community/smart-mastering-core/issues/140)
- deployMatchOptions FAILED [\#96](https://github.com/marklogic-community/smart-mastering-core/issues/96)

**Merged pull requests:**

- releasing v1.1.0 [\#163](https://github.com/marklogic-community/smart-mastering-core/pull/163) ([dmcassel](https://github.com/dmcassel))
- Release [\#162](https://github.com/marklogic-community/smart-mastering-core/pull/162) ([dmcassel](https://github.com/dmcassel))
- Merging for v1.1.0 [\#161](https://github.com/marklogic-community/smart-mastering-core/pull/161) ([dmcassel](https://github.com/dmcassel))
- Updating docs for v1.1.0 [\#160](https://github.com/marklogic-community/smart-mastering-core/pull/160) ([dmcassel](https://github.com/dmcassel))
- MDM-528 Enhance unit test to verfiy includeMatches option works [\#159](https://github.com/marklogic-community/smart-mastering-core/pull/159) ([ryanjdew](https://github.com/ryanjdew))
- MDM-527: record path in nested property history [\#158](https://github.com/marklogic-community/smart-mastering-core/pull/158) ([dmcassel](https://github.com/dmcassel))
- MDM-535 Check parameters and report errors [\#157](https://github.com/marklogic-community/smart-mastering-core/pull/157) ([ryanjdew](https://github.com/ryanjdew))
- update based on Sprint Review comment [\#156](https://github.com/marklogic-community/smart-mastering-core/pull/156) ([dmcassel](https://github.com/dmcassel))
- Update testing [\#155](https://github.com/marklogic-community/smart-mastering-core/pull/155) ([dmcassel](https://github.com/dmcassel))
- Mdm 526: Fix 500 error when sending match options in POST body [\#154](https://github.com/marklogic-community/smart-mastering-core/pull/154) ([ryanjdew](https://github.com/ryanjdew))
- Update examples in README.md [\#151](https://github.com/marklogic-community/smart-mastering-core/pull/151) ([ryanjdew](https://github.com/ryanjdew))
- Mdm 504 [\#150](https://github.com/marklogic-community/smart-mastering-core/pull/150) ([dmcassel](https://github.com/dmcassel))
- updated for instance path properties [\#149](https://github.com/marklogic-community/smart-mastering-core/pull/149) ([dmcassel](https://github.com/dmcassel))
- Mdm 349: control merging of nested properties [\#148](https://github.com/marklogic-community/smart-mastering-core/pull/148) ([dmcassel](https://github.com/dmcassel))
- \#146 Fix sm-match endpoint to cast rs:includeMatches param properly [\#147](https://github.com/marklogic-community/smart-mastering-core/pull/147) ([aajacobs](https://github.com/aajacobs))
- MDM-492: documenting custom function signatures [\#142](https://github.com/marklogic-community/smart-mastering-core/pull/142) ([dmcassel](https://github.com/dmcassel))
- Mdm 492: send JSON to custom actions instead of XML [\#141](https://github.com/marklogic-community/smart-mastering-core/pull/141) ([dmcassel](https://github.com/dmcassel))
- adding xqdocs to test functions [\#139](https://github.com/marklogic-community/smart-mastering-core/pull/139) ([paxtonhare](https://github.com/paxtonhare))
- updating docs.next with triple merge config info [\#138](https://github.com/marklogic-community/smart-mastering-core/pull/138) ([paxtonhare](https://github.com/paxtonhare))
- adding custom triple merge support [\#137](https://github.com/marklogic-community/smart-mastering-core/pull/137) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 267: adding organizations to dhf-flow example [\#136](https://github.com/marklogic-community/smart-mastering-core/pull/136) ([dmcassel](https://github.com/dmcassel))
- updating readme to mention PROV-O schemas requirement. [\#135](https://github.com/marklogic-community/smart-mastering-core/pull/135) ([paxtonhare](https://github.com/paxtonhare))

## [v1.0.0](https://github.com/marklogic-community/smart-mastering-core/tree/v1.0.0) (2018-08-14)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/1.0.0-beta.2...v1.0.0)

**Implemented enhancements:**

- Change sm-merge REST extension to accept more than two URIs [\#120](https://github.com/marklogic-community/smart-mastering-core/issues/120)

**Fixed bugs:**

- property-history returns empty strings for simple JSON fields [\#108](https://github.com/marklogic-community/smart-mastering-core/issues/108)
- sm-match only returns one result, and no matches [\#100](https://github.com/marklogic-community/smart-mastering-core/issues/100)
- sm-history-document returns blank activities [\#99](https://github.com/marklogic-community/smart-mastering-core/issues/99)
- POSTing pseudo-document to sm-match [\#98](https://github.com/marklogic-community/smart-mastering-core/issues/98)
- Not able to add merge configuration using Rest api in minimal-project. [\#82](https://github.com/marklogic-community/smart-mastering-core/issues/82)

**Closed issues:**

- Documentation - Wrong Namespace in Merge Options [\#116](https://github.com/marklogic-community/smart-mastering-core/issues/116)
- node\(\) instead of object-node\(\) [\#102](https://github.com/marklogic-community/smart-mastering-core/issues/102)
- Documentation - required roles [\#40](https://github.com/marklogic-community/smart-mastering-core/issues/40)

**Merged pull requests:**

- use camel case for JSON matching options [\#132](https://github.com/marklogic-community/smart-mastering-core/pull/132) ([dmcassel](https://github.com/dmcassel))
- removing unused algorithms [\#131](https://github.com/marklogic-community/smart-mastering-core/pull/131) ([paxtonhare](https://github.com/paxtonhare))
- MDM-455 [\#130](https://github.com/marklogic-community/smart-mastering-core/pull/130) ([paxtonhare](https://github.com/paxtonhare))
- Ensure consistent object vs array [\#129](https://github.com/marklogic-community/smart-mastering-core/pull/129) ([dmcassel](https://github.com/dmcassel))
- Mdm 338: document JSON options format [\#128](https://github.com/marklogic-community/smart-mastering-core/pull/128) ([dmcassel](https://github.com/dmcassel))
- Fix options as json [\#127](https://github.com/marklogic-community/smart-mastering-core/pull/127) ([dmcassel](https://github.com/dmcassel))
- fixing deadlock with notifications. [\#126](https://github.com/marklogic-community/smart-mastering-core/pull/126) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 395: adding more developer documentation [\#125](https://github.com/marklogic-community/smart-mastering-core/pull/125) ([dmcassel](https://github.com/dmcassel))
- updating parameter [\#124](https://github.com/marklogic-community/smart-mastering-core/pull/124) ([dmcassel](https://github.com/dmcassel))
- Mdm 94 [\#123](https://github.com/marklogic-community/smart-mastering-core/pull/123) ([paxtonhare](https://github.com/paxtonhare))
- fixing mdm-332 [\#122](https://github.com/marklogic-community/smart-mastering-core/pull/122) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 466 [\#121](https://github.com/marklogic-community/smart-mastering-core/pull/121) ([dmcassel](https://github.com/dmcassel))
- Support more complex json [\#119](https://github.com/marklogic-community/smart-mastering-core/pull/119) ([ryanjdew](https://github.com/ryanjdew))
- MDM-451 add telemetry [\#118](https://github.com/marklogic-community/smart-mastering-core/pull/118) ([paxtonhare](https://github.com/paxtonhare))
- fixing json matching. newer version of marklogic no longer match json… [\#117](https://github.com/marklogic-community/smart-mastering-core/pull/117) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 395: documenting the code [\#115](https://github.com/marklogic-community/smart-mastering-core/pull/115) ([dmcassel](https://github.com/dmcassel))
- adding documentation about match results [\#114](https://github.com/marklogic-community/smart-mastering-core/pull/114) ([dmcassel](https://github.com/dmcassel))
- documenting the role requirements [\#113](https://github.com/marklogic-community/smart-mastering-core/pull/113) ([dmcassel](https://github.com/dmcassel))
- Mdm 339: minimal privileges for examples [\#112](https://github.com/marklogic-community/smart-mastering-core/pull/112) ([dmcassel](https://github.com/dmcassel))
- correcting version number [\#111](https://github.com/marklogic-community/smart-mastering-core/pull/111) ([dmcassel](https://github.com/dmcassel))
- fixing build: problem in normalize-value-for-tracing [\#110](https://github.com/marklogic-community/smart-mastering-core/pull/110) ([dmcassel](https://github.com/dmcassel))
- Handle text nodes in history:normalize-value-for-tracing [\#109](https://github.com/marklogic-community/smart-mastering-core/pull/109) ([patrickmcelwee](https://github.com/patrickmcelwee))
- stating that content is expected not to be mixed [\#107](https://github.com/marklogic-community/smart-mastering-core/pull/107) ([dmcassel](https://github.com/dmcassel))
- tests for Ryan's PR [\#106](https://github.com/marklogic-community/smart-mastering-core/pull/106) ([dmcassel](https://github.com/dmcassel))
- adding information about path properties [\#105](https://github.com/marklogic-community/smart-mastering-core/pull/105) ([dmcassel](https://github.com/dmcassel))
- Fix XPath grouping to account for es:info under es:instance [\#104](https://github.com/marklogic-community/smart-mastering-core/pull/104) ([ryanjdew](https://github.com/ryanjdew))
- \#100 \#102 fixed JSON serialization of match results [\#103](https://github.com/marklogic-community/smart-mastering-core/pull/103) ([dmcassel](https://github.com/dmcassel))
- Issue 98 [\#101](https://github.com/marklogic-community/smart-mastering-core/pull/101) ([dmcassel](https://github.com/dmcassel))
- Mdm 348 [\#97](https://github.com/marklogic-community/smart-mastering-core/pull/97) ([dmcassel](https://github.com/dmcassel))
- Mdm 348 [\#95](https://github.com/marklogic-community/smart-mastering-core/pull/95) ([dmcassel](https://github.com/dmcassel))
- mdm 391 - adding docs for custom actions [\#94](https://github.com/marklogic-community/smart-mastering-core/pull/94) ([paxtonhare](https://github.com/paxtonhare))
- mdm 391 [\#93](https://github.com/marklogic-community/smart-mastering-core/pull/93) ([paxtonhare](https://github.com/paxtonhare))
- updating to talk about the optional filtering query [\#92](https://github.com/marklogic-community/smart-mastering-core/pull/92) ([paxtonhare](https://github.com/paxtonhare))
- MDM-403 [\#91](https://github.com/marklogic-community/smart-mastering-core/pull/91) ([paxtonhare](https://github.com/paxtonhare))
- Ignoring dhf-flow gradle-local.properties [\#90](https://github.com/marklogic-community/smart-mastering-core/pull/90) ([rjrudin](https://github.com/rjrudin))
- Feature/minimal project [\#89](https://github.com/marklogic-community/smart-mastering-core/pull/89) ([rjrudin](https://github.com/rjrudin))
- changes happen on develop branch now [\#88](https://github.com/marklogic-community/smart-mastering-core/pull/88) ([dmcassel](https://github.com/dmcassel))
- adding a non-person test [\#86](https://github.com/marklogic-community/smart-mastering-core/pull/86) ([paxtonhare](https://github.com/paxtonhare))
- adding profiling to the dhf-flow example [\#85](https://github.com/marklogic-community/smart-mastering-core/pull/85) ([paxtonhare](https://github.com/paxtonhare))
- MDM-397 [\#84](https://github.com/marklogic-community/smart-mastering-core/pull/84) ([paxtonhare](https://github.com/paxtonhare))
- fixing demos [\#83](https://github.com/marklogic-community/smart-mastering-core/pull/83) ([paxtonhare](https://github.com/paxtonhare))
- Updates [\#81](https://github.com/marklogic-community/smart-mastering-core/pull/81) ([dmcassel](https://github.com/dmcassel))
- adding more comments in the code [\#80](https://github.com/marklogic-community/smart-mastering-core/pull/80) ([dmcassel](https://github.com/dmcassel))

## [1.0.0-beta.2](https://github.com/marklogic-community/smart-mastering-core/tree/1.0.0-beta.2) (2018-06-25)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v1.0.0-beta.1...1.0.0-beta.2)

**Merged pull requests:**

- removing ext from docs [\#79](https://github.com/marklogic-community/smart-mastering-core/pull/79) ([paxtonhare](https://github.com/paxtonhare))
- moving /ext/\* to /\* [\#78](https://github.com/marklogic-community/smart-mastering-core/pull/78) ([paxtonhare](https://github.com/paxtonhare))

## [v1.0.0-beta.1](https://github.com/marklogic-community/smart-mastering-core/tree/v1.0.0-beta.1) (2018-06-22)
[Full Changelog](https://github.com/marklogic-community/smart-mastering-core/compare/v0.0.7...v1.0.0-beta.1)

**Implemented enhancements:**

- Publish and depend on smart-mastering-code like ml-unit-test [\#47](https://github.com/marklogic-community/smart-mastering-core/issues/47)

**Closed issues:**

- Attribution wrong where only one value present [\#32](https://github.com/marklogic-community/smart-mastering-core/issues/32)

**Merged pull requests:**

- a couple of tweaks to the README and build.gradle for example projects [\#77](https://github.com/marklogic-community/smart-mastering-core/pull/77) ([paxtonhare](https://github.com/paxtonhare))
- adding triggers example [\#76](https://github.com/marklogic-community/smart-mastering-core/pull/76) ([paxtonhare](https://github.com/paxtonhare))
- Add dhf flow example [\#75](https://github.com/marklogic-community/smart-mastering-core/pull/75) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 350 [\#74](https://github.com/marklogic-community/smart-mastering-core/pull/74) ([dmcassel](https://github.com/dmcassel))
- ensure that the results are ordered by their index attribute [\#73](https://github.com/marklogic-community/smart-mastering-core/pull/73) ([dmcassel](https://github.com/dmcassel))
- fixing incorrect merge [\#72](https://github.com/marklogic-community/smart-mastering-core/pull/72) ([dmcassel](https://github.com/dmcassel))
- Fix extractions [\#71](https://github.com/marklogic-community/smart-mastering-core/pull/71) ([paxtonhare](https://github.com/paxtonhare))
- Mdm 245 [\#70](https://github.com/marklogic-community/smart-mastering-core/pull/70) ([dmcassel](https://github.com/dmcassel))
- refactoring match response [\#69](https://github.com/marklogic-community/smart-mastering-core/pull/69) ([paxtonhare](https://github.com/paxtonhare))
- Fix build [\#68](https://github.com/marklogic-community/smart-mastering-core/pull/68) ([dmcassel](https://github.com/dmcassel))
- fixing scenario where scores get too high [\#67](https://github.com/marklogic-community/smart-mastering-core/pull/67) ([paxtonhare](https://github.com/paxtonhare))
- Merge locking [\#66](https://github.com/marklogic-community/smart-mastering-core/pull/66) ([dmcassel](https://github.com/dmcassel))
- use image to illustrate matching process [\#65](https://github.com/marklogic-community/smart-mastering-core/pull/65) ([dmcassel](https://github.com/dmcassel))
- updating based on review [\#64](https://github.com/marklogic-community/smart-mastering-core/pull/64) ([dmcassel](https://github.com/dmcassel))
- added note [\#63](https://github.com/marklogic-community/smart-mastering-core/pull/63) ([dmcassel](https://github.com/dmcassel))
- except does not preserve order, but we need that here [\#62](https://github.com/marklogic-community/smart-mastering-core/pull/62) ([dmcassel](https://github.com/dmcassel))
- added how-does-it-work [\#61](https://github.com/marklogic-community/smart-mastering-core/pull/61) ([dmcassel](https://github.com/dmcassel))
- Testing filter queries [\#60](https://github.com/marklogic-community/smart-mastering-core/pull/60) ([dmcassel](https://github.com/dmcassel))
- added reference to zip.xqy [\#59](https://github.com/marklogic-community/smart-mastering-core/pull/59) ([dmcassel](https://github.com/dmcassel))
- adding zip custom matcher with notes [\#58](https://github.com/marklogic-community/smart-mastering-core/pull/58) ([dmcassel](https://github.com/dmcassel))
- added includeMatches parameter for sm-match [\#57](https://github.com/marklogic-community/smart-mastering-core/pull/57) ([dmcassel](https://github.com/dmcassel))
- wrapped cts:walk in a control flag [\#56](https://github.com/marklogic-community/smart-mastering-core/pull/56) ([dmcassel](https://github.com/dmcassel))
- fixing json \<=\> json [\#55](https://github.com/marklogic-community/smart-mastering-core/pull/55) ([paxtonhare](https://github.com/paxtonhare))
- Overview [\#54](https://github.com/marklogic-community/smart-mastering-core/pull/54) ([dmcassel](https://github.com/dmcassel))
- verifying if json works or not [\#53](https://github.com/marklogic-community/smart-mastering-core/pull/53) ([paxtonhare](https://github.com/paxtonhare))
- adding match options page [\#52](https://github.com/marklogic-community/smart-mastering-core/pull/52) ([dmcassel](https://github.com/dmcassel))
- refactored merging functionality [\#51](https://github.com/marklogic-community/smart-mastering-core/pull/51) ([dmcassel](https://github.com/dmcassel))
- moved threshold config to matching options [\#50](https://github.com/marklogic-community/smart-mastering-core/pull/50) ([dmcassel](https://github.com/dmcassel))
- adding function-level comments [\#49](https://github.com/marklogic-community/smart-mastering-core/pull/49) ([dmcassel](https://github.com/dmcassel))
- \#47 Improved publishing and included example of depending on Smart Mastering [\#48](https://github.com/marklogic-community/smart-mastering-core/pull/48) ([rjrudin](https://github.com/rjrudin))
- History bug [\#46](https://github.com/marklogic-community/smart-mastering-core/pull/46) ([dmcassel](https://github.com/dmcassel))
- Fixing MDM-127 [\#45](https://github.com/marklogic-community/smart-mastering-core/pull/45) ([paxtonhare](https://github.com/paxtonhare))
- Refactoring [\#44](https://github.com/marklogic-community/smart-mastering-core/pull/44) ([dmcassel](https://github.com/dmcassel))
- refactored matcher.xqy to separate public API from interface [\#43](https://github.com/marklogic-community/smart-mastering-core/pull/43) ([dmcassel](https://github.com/dmcassel))
- updating files per Legal [\#42](https://github.com/marklogic-community/smart-mastering-core/pull/42) ([dmcassel](https://github.com/dmcassel))
- refactored a function for readability; expanded tests [\#41](https://github.com/marklogic-community/smart-mastering-core/pull/41) ([dmcassel](https://github.com/dmcassel))
- refactoring and added tests [\#39](https://github.com/marklogic-community/smart-mastering-core/pull/39) ([dmcassel](https://github.com/dmcassel))
- Options test [\#38](https://github.com/marklogic-community/smart-mastering-core/pull/38) ([dmcassel](https://github.com/dmcassel))
- refactoring service code to a library [\#37](https://github.com/marklogic-community/smart-mastering-core/pull/37) ([dmcassel](https://github.com/dmcassel))
- Required files [\#36](https://github.com/marklogic-community/smart-mastering-core/pull/36) ([dmcassel](https://github.com/dmcassel))
- Formatting [\#35](https://github.com/marklogic-community/smart-mastering-core/pull/35) ([dmcassel](https://github.com/dmcassel))
- updating README, added CONTRIBUTING [\#34](https://github.com/marklogic-community/smart-mastering-core/pull/34) ([dmcassel](https://github.com/dmcassel))
- \#32 Attribution bug [\#33](https://github.com/marklogic-community/smart-mastering-core/pull/33) ([dmcassel](https://github.com/dmcassel))
- fixing archived merge counts [\#31](https://github.com/marklogic-community/smart-mastering-core/pull/31) ([paxtonhare](https://github.com/paxtonhare))
- Update test [\#30](https://github.com/marklogic-community/smart-mastering-core/pull/30) ([dmcassel](https://github.com/dmcassel))
- Auto block [\#29](https://github.com/marklogic-community/smart-mastering-core/pull/29) ([dmcassel](https://github.com/dmcassel))
- MDM-234 [\#28](https://github.com/marklogic-community/smart-mastering-core/pull/28) ([paxtonhare](https://github.com/paxtonhare))
- Delete multiple [\#27](https://github.com/marklogic-community/smart-mastering-core/pull/27) ([dmcassel](https://github.com/dmcassel))
- Notification status [\#26](https://github.com/marklogic-community/smart-mastering-core/pull/26) ([dmcassel](https://github.com/dmcassel))
- change sm-notifications to include total [\#25](https://github.com/marklogic-community/smart-mastering-core/pull/25) ([dmcassel](https://github.com/dmcassel))
- paging fix [\#24](https://github.com/marklogic-community/smart-mastering-core/pull/24) ([paxtonhare](https://github.com/paxtonhare))
- Revise notfications [\#23](https://github.com/marklogic-community/smart-mastering-core/pull/23) ([dmcassel](https://github.com/dmcassel))

## [v0.0.7](https://github.com/marklogic-community/smart-mastering-core/tree/v0.0.7) (2018-04-20)
**Merged pull requests:**

- incrementing release number [\#22](https://github.com/marklogic-community/smart-mastering-core/pull/22) ([dmcassel](https://github.com/dmcassel))
- Adding notification delete service. [\#21](https://github.com/marklogic-community/smart-mastering-core/pull/21) ([dmcassel](https://github.com/dmcassel))
- Notification service [\#20](https://github.com/marklogic-community/smart-mastering-core/pull/20) ([dmcassel](https://github.com/dmcassel))
- bringing in Ryan Dew's change from the AMT repo [\#19](https://github.com/marklogic-community/smart-mastering-core/pull/19) ([dmcassel](https://github.com/dmcassel))
- adding a test [\#18](https://github.com/marklogic-community/smart-mastering-core/pull/18) ([dmcassel](https://github.com/dmcassel))
- making uri same as id [\#17](https://github.com/marklogic-community/smart-mastering-core/pull/17) ([paxtonhare](https://github.com/paxtonhare))
- incrementing version [\#16](https://github.com/marklogic-community/smart-mastering-core/pull/16) ([dmcassel](https://github.com/dmcassel))
- Block match [\#15](https://github.com/marklogic-community/smart-mastering-core/pull/15) ([dmcassel](https://github.com/dmcassel))
- allowing json requests to work from the java client api [\#14](https://github.com/marklogic-community/smart-mastering-core/pull/14) ([paxtonhare](https://github.com/paxtonhare))
- Fix spacing [\#13](https://github.com/marklogic-community/smart-mastering-core/pull/13) ([dmcassel](https://github.com/dmcassel))
- adding tests and a comment [\#12](https://github.com/marklogic-community/smart-mastering-core/pull/12) ([dmcassel](https://github.com/dmcassel))
- enhancing dashboard status MDM-171 [\#11](https://github.com/marklogic-community/smart-mastering-core/pull/11) ([paxtonhare](https://github.com/paxtonhare))
- use the target weight instead of zero [\#10](https://github.com/marklogic-community/smart-mastering-core/pull/10) ([dmcassel](https://github.com/dmcassel))
- updating search options and adding search results transform [\#9](https://github.com/marklogic-community/smart-mastering-core/pull/9) ([paxtonhare](https://github.com/paxtonhare))
- Renaming [\#8](https://github.com/marklogic-community/smart-mastering-core/pull/8) ([dmcassel](https://github.com/dmcassel))
- bumping for 0.0.3 release [\#7](https://github.com/marklogic-community/smart-mastering-core/pull/7) ([dmcassel](https://github.com/dmcassel))
- adding transform to return the es instance as json [\#6](https://github.com/marklogic-community/smart-mastering-core/pull/6) ([paxtonhare](https://github.com/paxtonhare))
- bumping to 0.0.2 [\#5](https://github.com/marklogic-community/smart-mastering-core/pull/5) ([dmcassel](https://github.com/dmcassel))
- adding mastering-stats service [\#4](https://github.com/marklogic-community/smart-mastering-core/pull/4) ([dmcassel](https://github.com/dmcassel))
- improving directions [\#3](https://github.com/marklogic-community/smart-mastering-core/pull/3) ([dmcassel](https://github.com/dmcassel))
- Adding usage instructions [\#2](https://github.com/marklogic-community/smart-mastering-core/pull/2) ([dmcassel](https://github.com/dmcassel))
- adding services code [\#1](https://github.com/marklogic-community/smart-mastering-core/pull/1) ([dmcassel](https://github.com/dmcassel))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*