## <small>5.3.4 (2024-07-18)</small>

* fix:  resolve browser mapping using bare imports (fix #11208) (#11219) ([22de84f](https://github.com/vitejs/vite/commit/22de84f)), closes [#11208](https://github.com/vitejs/vite/issues/11208) [#11219](https://github.com/vitejs/vite/issues/11219)
* fix: __VITE_PUBLIC_ASSET__hash__ in HTML (#9247) ([a2b24ee](https://github.com/vitejs/vite/commit/a2b24ee)), closes [#9247](https://github.com/vitejs/vite/issues/9247)
* fix: ?html-proxy with trailing = added by some servers (#7093) ([5818ac9](https://github.com/vitejs/vite/commit/5818ac9)), closes [#7093](https://github.com/vitejs/vite/issues/7093)
* fix: ?inline warning for .css.js file (#11347) ([729fb1a](https://github.com/vitejs/vite/commit/729fb1a)), closes [#11347](https://github.com/vitejs/vite/issues/11347)
* fix: "EISDIR: illegal operation on a directory, realpath" error on RA… (#13655) ([6bd5434](https://github.com/vitejs/vite/commit/6bd5434)), closes [#13655](https://github.com/vitejs/vite/issues/13655)
* fix: /@fs/ dir traversal with escaped chars (fixes #8498) (#8804) ([6851009](https://github.com/vitejs/vite/commit/6851009)), closes [#8498](https://github.com/vitejs/vite/issues/8498) [#8804](https://github.com/vitejs/vite/issues/8804)
* fix: `__vite__mapDeps` code injection (#15732) ([aff54e1](https://github.com/vitejs/vite/commit/aff54e1)), closes [#15732](https://github.com/vitejs/vite/issues/15732)
* fix: `$ vite preview` 404 handling (#7665) ([66b6dc5](https://github.com/vitejs/vite/commit/66b6dc5)), closes [#7665](https://github.com/vitejs/vite/issues/7665)
* fix: `apply` condition skipped for nested plugins (#7741) ([1f2ca53](https://github.com/vitejs/vite/commit/1f2ca53)), closes [#7741](https://github.com/vitejs/vite/issues/7741)
* fix: `completeSystemWrapPlugin` captures `function ()` (fixes #9807) (#9821) ([1ee0364](https://github.com/vitejs/vite/commit/1ee0364)), closes [#9807](https://github.com/vitejs/vite/issues/9807) [#9821](https://github.com/vitejs/vite/issues/9821)
* fix: `fs.deny` with globs with directories (#16250) ([ba5269c](https://github.com/vitejs/vite/commit/ba5269c)), closes [#16250](https://github.com/vitejs/vite/issues/16250)
* fix: `fsp.rm` removing files does not take effect (#16032) ([b05c405](https://github.com/vitejs/vite/commit/b05c405)), closes [#16032](https://github.com/vitejs/vite/issues/16032)
* fix: `generateCodeFrame` infinite loop (#15093) ([6619de7](https://github.com/vitejs/vite/commit/6619de7)), closes [#15093](https://github.com/vitejs/vite/issues/15093)
* fix: `import.meta.accept()` -> `import.meta.hot.accept()` (#8361) ([c5185cf](https://github.com/vitejs/vite/commit/c5185cf)), closes [#8361](https://github.com/vitejs/vite/issues/8361)
* fix: `import.meta.url` should not throw (#7219) ([5de3a98](https://github.com/vitejs/vite/commit/5de3a98)), closes [#7219](https://github.com/vitejs/vite/issues/7219)
* fix: `injectQuery` break relative path (#9760) ([61273b2](https://github.com/vitejs/vite/commit/61273b2)), closes [#9760](https://github.com/vitejs/vite/issues/9760)
* fix: `isBuiltin` using patched native `builtinModules` (#5827) ([4a05a6e](https://github.com/vitejs/vite/commit/4a05a6e)), closes [#5827](https://github.com/vitejs/vite/issues/5827)
* fix: `optimizeDeps.include` not working with paths inside packages (#13922) ([06e4f57](https://github.com/vitejs/vite/commit/06e4f57)), closes [#13922](https://github.com/vitejs/vite/issues/13922)
* fix: `server.headers` after restart in middleware mode (#14905) ([f9ce9db](https://github.com/vitejs/vite/commit/f9ce9db)), closes [#14905](https://github.com/vitejs/vite/issues/14905)
* fix: `sideEffects: []` should work as `sideEffects: false` (#16152) ([f377a84](https://github.com/vitejs/vite/commit/f377a84)), closes [#16152](https://github.com/vitejs/vite/issues/16152)
* fix: `ssrExternal` should not skip nested dependencies (#7154) ([f8f934a](https://github.com/vitejs/vite/commit/f8f934a)), closes [#7154](https://github.com/vitejs/vite/issues/7154)
* fix: add `@types/node` as an optional peer dependency (#10757) ([57916a4](https://github.com/vitejs/vite/commit/57916a4)), closes [#10757](https://github.com/vitejs/vite/issues/10757)
* fix: add `import` support to `ssrModuleLoader` (#5197) ([baba1f9](https://github.com/vitejs/vite/commit/baba1f9)), closes [#5197](https://github.com/vitejs/vite/issues/5197)
* fix: add `virtual:` to virtual module source map ignore (#12444) ([c4aa28f](https://github.com/vitejs/vite/commit/c4aa28f)), closes [#12444](https://github.com/vitejs/vite/issues/12444)
* fix: add a warning if css urls not exist during build time (fix #9800) (#10331) ([9f268da](https://github.com/vitejs/vite/commit/9f268da)), closes [#9800](https://github.com/vitejs/vite/issues/9800) [#10331](https://github.com/vitejs/vite/issues/10331)
* fix: add base to virtual html (#16442) ([721f94d](https://github.com/vitejs/vite/commit/721f94d)), closes [#16442](https://github.com/vitejs/vite/issues/16442)
* fix: add direct query to html-proxy css (fixes #8091) (#8094) ([54a941a](https://github.com/vitejs/vite/commit/54a941a)), closes [#8091](https://github.com/vitejs/vite/issues/8091) [#8094](https://github.com/vitejs/vite/issues/8094)
* fix: add hash to lib chunk names (#7190) ([c81cedf](https://github.com/vitejs/vite/commit/c81cedf)), closes [#7190](https://github.com/vitejs/vite/issues/7190)
* fix: add missed JPEG file extensions to `KNOWN_ASSET_TYPES` (#8565) ([2dfc015](https://github.com/vitejs/vite/commit/2dfc015)), closes [#8565](https://github.com/vitejs/vite/issues/8565)
* fix: add module types (#10299) ([0b89dd2](https://github.com/vitejs/vite/commit/0b89dd2)), closes [#10299](https://github.com/vitejs/vite/issues/10299)
* fix: add ref() and unref() to chokidar.d.ts for typescript build to work (#15706) ([6b45037](https://github.com/vitejs/vite/commit/6b45037)), closes [#15706](https://github.com/vitejs/vite/issues/15706)
* fix: add source map to Web Workers (fix #14216) (#14217) ([6f86de3](https://github.com/vitejs/vite/commit/6f86de3)), closes [#14216](https://github.com/vitejs/vite/issues/14216) [#14217](https://github.com/vitejs/vite/issues/14217)
* fix: add type for function localsConvention value (#11152) ([c9274b4](https://github.com/vitejs/vite/commit/c9274b4)), closes [#11152](https://github.com/vitejs/vite/issues/11152)
* fix: add version to optimized chunks, fix #7323 (#7350) ([1be1db6](https://github.com/vitejs/vite/commit/1be1db6)), closes [#7323](https://github.com/vitejs/vite/issues/7323) [#7350](https://github.com/vitejs/vite/issues/7350)
* fix: add watch in fallback file load (#14938) ([b24b951](https://github.com/vitejs/vite/commit/b24b951)), closes [#14938](https://github.com/vitejs/vite/issues/14938)
* fix: address file path mismatch when loading Vite config file on Windows (fix #12923) (#13005) ([84c4118](https://github.com/vitejs/vite/commit/84c4118)), closes [#12923](https://github.com/vitejs/vite/issues/12923) [#13005](https://github.com/vitejs/vite/issues/13005)
* fix: adjust esm syntax judgment logic (#16436) ([af72eab](https://github.com/vitejs/vite/commit/af72eab)), closes [#16436](https://github.com/vitejs/vite/issues/16436)
* fix: adjust import analysis behavior to match Node (#16738) ([f599ab4](https://github.com/vitejs/vite/commit/f599ab4)), closes [#16738](https://github.com/vitejs/vite/issues/16738)
* fix: allow `localhost` as a valid hostname (#7092) ([4194cce](https://github.com/vitejs/vite/commit/4194cce)), closes [#7092](https://github.com/vitejs/vite/issues/7092)
* fix: allow cache overlap in parallel builds (#8592) ([2dd0b49](https://github.com/vitejs/vite/commit/2dd0b49)), closes [#8592](https://github.com/vitejs/vite/issues/8592)
* fix: allow css to be written for systemjs output (#5902) ([780b4f5](https://github.com/vitejs/vite/commit/780b4f5)), closes [#5902](https://github.com/vitejs/vite/issues/5902)
* fix: Allow custom asset URL origin in development (#5104) ([e4ef6dd](https://github.com/vitejs/vite/commit/e4ef6dd)), closes [#5104](https://github.com/vitejs/vite/issues/5104)
* fix: allow onwarn to override vite default warning handling (#12757) ([f736930](https://github.com/vitejs/vite/commit/f736930)), closes [#12757](https://github.com/vitejs/vite/issues/12757)
* fix: allow optional trailing comma in asset `import.meta.url` (#6983) ([2debb9f](https://github.com/vitejs/vite/commit/2debb9f)), closes [#6983](https://github.com/vitejs/vite/issues/6983)
* fix: allow path ending with .html to fallback to index.html ([dae6d0a](https://github.com/vitejs/vite/commit/dae6d0a))
* fix: allow ping to http from https website (#9561) ([f4b4405](https://github.com/vitejs/vite/commit/f4b4405)), closes [#9561](https://github.com/vitejs/vite/issues/9561)
* fix: allow port 0 to be provided to server (#7530) ([173e4c9](https://github.com/vitejs/vite/commit/173e4c9)), closes [#7530](https://github.com/vitejs/vite/issues/7530)
* fix: allow tree-shake glob eager css in js (#9547) ([2e309d6](https://github.com/vitejs/vite/commit/2e309d6)), closes [#9547](https://github.com/vitejs/vite/issues/9547)
* fix: allow using vite as a proxy for another vite server (#13218) ([711dd80](https://github.com/vitejs/vite/commit/711dd80)), closes [#13218](https://github.com/vitejs/vite/issues/13218)
* fix: allowed files logic (fix #5416) (#5420) ([414bc45](https://github.com/vitejs/vite/commit/414bc45)), closes [#5416](https://github.com/vitejs/vite/issues/5416) [#5420](https://github.com/vitejs/vite/issues/5420)
* fix: always bundle config file, fix config hmr (#5779) ([19d2b6a](https://github.com/vitejs/vite/commit/19d2b6a)), closes [#5779](https://github.com/vitejs/vite/issues/5779)
* fix: always remove temp config (#8782) ([2c2a86b](https://github.com/vitejs/vite/commit/2c2a86b)), closes [#8782](https://github.com/vitejs/vite/issues/8782)
* fix: analysing build chunk without dependencies (#15469) ([bd52283](https://github.com/vitejs/vite/commit/bd52283)), closes [#15469](https://github.com/vitejs/vite/issues/15469)
* fix: apply correct fs restrictions for Yarn PnP when serving files from node_modules (#15957) ([a149d9e](https://github.com/vitejs/vite/commit/a149d9e)), closes [#15957](https://github.com/vitejs/vite/issues/15957)
* fix: avoid --open optimization if preTransformRequests is disabled (#14666) ([d4f62e4](https://github.com/vitejs/vite/commit/d4f62e4)), closes [#14666](https://github.com/vitejs/vite/issues/14666)
* fix: avoid binding ClassExpression (#13572) ([1a0c806](https://github.com/vitejs/vite/commit/1a0c806)), closes [#13572](https://github.com/vitejs/vite/issues/13572)
* fix: avoid caching transform result of invalidated module (#7254) ([2d7ba72](https://github.com/vitejs/vite/commit/2d7ba72)), closes [#7254](https://github.com/vitejs/vite/issues/7254)
* fix: avoid clean up while committing deps folder (#12722) ([3f4d109](https://github.com/vitejs/vite/commit/3f4d109)), closes [#12722](https://github.com/vitejs/vite/issues/12722)
* fix: avoid crash because of no access permission (#12552) ([eea1682](https://github.com/vitejs/vite/commit/eea1682)), closes [#12552](https://github.com/vitejs/vite/issues/12552)
* fix: avoid dev-server crash when ws proxy error (#12829) ([87e1f58](https://github.com/vitejs/vite/commit/87e1f58)), closes [#12829](https://github.com/vitejs/vite/issues/12829)
* fix: avoid early error when server is closed in ssr (#13787) ([89d01eb](https://github.com/vitejs/vite/commit/89d01eb)), closes [#13787](https://github.com/vitejs/vite/issues/13787)
* fix: avoid errors when loading the overlay code in workers (#9064) ([a52b45e](https://github.com/vitejs/vite/commit/a52b45e)), closes [#9064](https://github.com/vitejs/vite/issues/9064)
* fix: avoid mangling code from incorrect magic-string usage (#7397) ([68d76c9](https://github.com/vitejs/vite/commit/68d76c9)), closes [#7397](https://github.com/vitejs/vite/issues/7397)
* fix: avoid module preload polyfill for zero js html (#4999) ([ac55755](https://github.com/vitejs/vite/commit/ac55755)), closes [#4999](https://github.com/vitejs/vite/issues/4999)
* fix: avoid null sourcePath in `server.sourcemapIgnoreList` (#12251) ([209c3bd](https://github.com/vitejs/vite/commit/209c3bd)), closes [#12251](https://github.com/vitejs/vite/issues/12251)
* fix: avoid optimizing non-optimizable external deps (#8860) ([cd8d63b](https://github.com/vitejs/vite/commit/cd8d63b)), closes [#8860](https://github.com/vitejs/vite/issues/8860)
* fix: avoid outdated module to crash in importAnalysis after restart (#13231) ([3609e79](https://github.com/vitejs/vite/commit/3609e79)), closes [#13231](https://github.com/vitejs/vite/issues/13231)
* fix: avoid referencing importGlob from importMeta.d.ts (#6531) ([962d285](https://github.com/vitejs/vite/commit/962d285)), closes [#6531](https://github.com/vitejs/vite/issues/6531)
* fix: avoid replacing defines and NODE_ENV in optimized deps (fix #8593) (#8606) ([739175b](https://github.com/vitejs/vite/commit/739175b)), closes [#8593](https://github.com/vitejs/vite/issues/8593) [#8606](https://github.com/vitejs/vite/issues/8606)
* fix: avoid scan failures in .svelte and .astro files (#5193) ([386ca79](https://github.com/vitejs/vite/commit/386ca79)), closes [#5193](https://github.com/vitejs/vite/issues/5193)
* fix: avoid SSR requests in waitForRequestIdle (#16246) ([7093f77](https://github.com/vitejs/vite/commit/7093f77)), closes [#16246](https://github.com/vitejs/vite/issues/16246)
* fix: avoid temporal optimize deps dirs (#12582) ([ff92f2f](https://github.com/vitejs/vite/commit/ff92f2f)), closes [#12582](https://github.com/vitejs/vite/issues/12582)
* fix: avoid type mismatch with Rollup (fix #7843) (#8701) ([87e51f7](https://github.com/vitejs/vite/commit/87e51f7)), closes [#7843](https://github.com/vitejs/vite/issues/7843) [#8701](https://github.com/vitejs/vite/issues/8701)
* fix: avoid unnecessary  pre-bundling warning ([b586098](https://github.com/vitejs/vite/commit/b586098))
* fix: avoid using `import.meta.url` for relative assets if output is not ESM (fixes #9297) (#9381) ([6d95225](https://github.com/vitejs/vite/commit/6d95225)), closes [#9297](https://github.com/vitejs/vite/issues/9297) [#9381](https://github.com/vitejs/vite/issues/9381)
* fix: avoid wrong warning of explicit public paths (#4927) ([9e06b81](https://github.com/vitejs/vite/commit/9e06b81)), closes [#4927](https://github.com/vitejs/vite/issues/4927)
* fix: await `buildStart` before server start (#12647) ([871d353](https://github.com/vitejs/vite/commit/871d353)), closes [#12647](https://github.com/vitejs/vite/issues/12647)
* fix: await `configResolved` hooks of worker plugins (#15597) ([03c8004](https://github.com/vitejs/vite/commit/03c8004)), closes [#15597](https://github.com/vitejs/vite/issues/15597)
* fix: await bundle closing (#11873) ([1e6768d](https://github.com/vitejs/vite/commit/1e6768d)), closes [#11873](https://github.com/vitejs/vite/issues/11873)
* fix: await requests to before server restart (#13262) ([0464398](https://github.com/vitejs/vite/commit/0464398)), closes [#13262](https://github.com/vitejs/vite/issues/13262)
* fix: await scanner (#11242) ([52a6732](https://github.com/vitejs/vite/commit/52a6732)), closes [#11242](https://github.com/vitejs/vite/issues/11242)
* fix: better error message for parse failures (#5192) ([8fe8df3](https://github.com/vitejs/vite/commit/8fe8df3)), closes [#5192](https://github.com/vitejs/vite/issues/5192)
* fix: bindCLIShortcuts to proper server (#15162) ([67ac572](https://github.com/vitejs/vite/commit/67ac572)), closes [#15162](https://github.com/vitejs/vite/issues/15162)
* fix: breakpoints in JS not working (#13514) ([0156bd2](https://github.com/vitejs/vite/commit/0156bd2)), closes [#13514](https://github.com/vitejs/vite/issues/13514)
* fix: broken middleware name (#12871) ([32bef57](https://github.com/vitejs/vite/commit/32bef57)), closes [#12871](https://github.com/vitejs/vite/issues/12871)
* fix: brotli let for reassignment (#7544) ([d0253d7](https://github.com/vitejs/vite/commit/d0253d7)), closes [#7544](https://github.com/vitejs/vite/issues/7544)
* fix: browser cache of newly discovered deps (#7378) ([392a0de](https://github.com/vitejs/vite/commit/392a0de)), closes [#7378](https://github.com/vitejs/vite/issues/7378)
* fix: build optimize deps metada location (#7214) ([dc46adf](https://github.com/vitejs/vite/commit/dc46adf)), closes [#7214](https://github.com/vitejs/vite/issues/7214)
* fix: build path error on Windows (#7383) ([e3c7c7a](https://github.com/vitejs/vite/commit/e3c7c7a)), closes [#7383](https://github.com/vitejs/vite/issues/7383)
* fix: build pluginContext types error (#5846) ([c278439](https://github.com/vitejs/vite/commit/c278439)), closes [#5846](https://github.com/vitejs/vite/issues/5846)
* fix: build should also respect esbuild=false config (#7602) ([2dc0e80](https://github.com/vitejs/vite/commit/2dc0e80)), closes [#7602](https://github.com/vitejs/vite/issues/7602)
* fix: build time deps optimization, and ensure single crawl end call (#12851) ([fa30879](https://github.com/vitejs/vite/commit/fa30879)), closes [#12851](https://github.com/vitejs/vite/issues/12851)
* fix: bump js parser ecmaVersion option to 'latest', fix #5013 (#5021) ([3541ebc](https://github.com/vitejs/vite/commit/3541ebc)), closes [#5013](https://github.com/vitejs/vite/issues/5013) [#5021](https://github.com/vitejs/vite/issues/5021)
* fix: bundle ws types (#5340) ([bc4a96c](https://github.com/vitejs/vite/commit/bc4a96c)), closes [#5340](https://github.com/vitejs/vite/issues/5340)
* fix: cacheDir should be ignored from watch (#10242) ([75dbca2](https://github.com/vitejs/vite/commit/75dbca2)), closes [#10242](https://github.com/vitejs/vite/issues/10242)
* fix: cachedTransformMiddleware for direct css requests (#15919) ([5099028](https://github.com/vitejs/vite/commit/5099028)), closes [#15919](https://github.com/vitejs/vite/issues/15919)
* fix: call `buildStart` only once when using next port (#12624) ([e10c6bd](https://github.com/vitejs/vite/commit/e10c6bd)), closes [#12624](https://github.com/vitejs/vite/issues/12624)
* fix: call `tryFsResolve` for relative `new URL(foo, import.meta.url)` (#13142) ([eeb0617](https://github.com/vitejs/vite/commit/eeb0617)), closes [#13142](https://github.com/vitejs/vite/issues/13142)
* fix: cannot reassign process.env.NODE_ENV in ssr (#6989) ([983feb2](https://github.com/vitejs/vite/commit/983feb2)), closes [#6989](https://github.com/vitejs/vite/issues/6989)
* fix: caret position was incorrect (#14984) ([2b4e793](https://github.com/vitejs/vite/commit/2b4e793)), closes [#14984](https://github.com/vitejs/vite/issues/14984)
* fix: catch and handle websocket error (#11991) (#12007) ([4b5cc9f](https://github.com/vitejs/vite/commit/4b5cc9f)), closes [#11991](https://github.com/vitejs/vite/issues/11991) [#12007](https://github.com/vitejs/vite/issues/12007)
* fix: catch statSync error (#11907) ([f80b9a2](https://github.com/vitejs/vite/commit/f80b9a2)), closes [#11907](https://github.com/vitejs/vite/issues/11907)
* fix: check document before detect script rel (#13559) ([be4b0c0](https://github.com/vitejs/vite/commit/be4b0c0)), closes [#13559](https://github.com/vitejs/vite/issues/13559)
* fix: check exactly in proxyESM (#5512) ([a17da55](https://github.com/vitejs/vite/commit/a17da55)), closes [#5512](https://github.com/vitejs/vite/issues/5512)
* fix: check for publicDir before checking if it is a parent directory (#16046) ([b6fb323](https://github.com/vitejs/vite/commit/b6fb323)), closes [#16046](https://github.com/vitejs/vite/issues/16046)
* fix: check if build exists so preview doesn't show 404s due to nonexistent build (#10564) ([0a1db8c](https://github.com/vitejs/vite/commit/0a1db8c)), closes [#10564](https://github.com/vitejs/vite/issues/10564)
* fix: check if e.stack exists in the first place (#6362) ([f144aa9](https://github.com/vitejs/vite/commit/f144aa9)), closes [#6362](https://github.com/vitejs/vite/issues/6362)
* fix: check server after tsconfig reload (#9106) ([d12d469](https://github.com/vitejs/vite/commit/d12d469)), closes [#9106](https://github.com/vitejs/vite/issues/9106)
* fix: circular dependency hmr causes refresh crash (#4589) ([00d8c9b](https://github.com/vitejs/vite/commit/00d8c9b)), closes [#4589](https://github.com/vitejs/vite/issues/4589)
* fix: cjs interop export names local clash, fix #8950 (#8953) ([2185f72](https://github.com/vitejs/vite/commit/2185f72)), closes [#8950](https://github.com/vitejs/vite/issues/8950) [#8953](https://github.com/vitejs/vite/issues/8953)
* fix: clean string regexp (#7871) ([ecc78bc](https://github.com/vitejs/vite/commit/ecc78bc)), closes [#7871](https://github.com/vitejs/vite/issues/7871)
* fix: cleanUpStaleCacheDirs once per process (#12847) ([2c58b6e](https://github.com/vitejs/vite/commit/2c58b6e)), closes [#12847](https://github.com/vitejs/vite/issues/12847)
* fix: client full reload (#8018) ([2f478ed](https://github.com/vitejs/vite/commit/2f478ed)), closes [#8018](https://github.com/vitejs/vite/issues/8018)
* fix: client type error (#9289) ([b82ddfb](https://github.com/vitejs/vite/commit/b82ddfb)), closes [#9289](https://github.com/vitejs/vite/issues/9289)
* fix: close socket when client error handled (#9816) ([ba62be4](https://github.com/vitejs/vite/commit/ba62be4)), closes [#9816](https://github.com/vitejs/vite/issues/9816)
* fix: code frame was not generated for postcss errors (#14986) ([bedfcfa](https://github.com/vitejs/vite/commit/bedfcfa)), closes [#14986](https://github.com/vitejs/vite/issues/14986)
* fix: configure proxy before subscribing to error events (#12263) ([c35e100](https://github.com/vitejs/vite/commit/c35e100)), closes [#12263](https://github.com/vitejs/vite/issues/12263)
* fix: consider # as a valid dir symbol (fix #4701) (#4703) ([52689c8](https://github.com/vitejs/vite/commit/52689c8)), closes [#4701](https://github.com/vitejs/vite/issues/4701) [#4703](https://github.com/vitejs/vite/issues/4703)
* fix: consider deep imports in isBuiltIn (#5248) ([269a1b6](https://github.com/vitejs/vite/commit/269a1b6)), closes [#5248](https://github.com/vitejs/vite/issues/5248)
* fix: consider undefined port when checking port (#7318) ([c7fc7c3](https://github.com/vitejs/vite/commit/c7fc7c3)), closes [#7318](https://github.com/vitejs/vite/issues/7318)
* fix: constrain inject helpers for iife (#13909) ([c89f677](https://github.com/vitejs/vite/commit/c89f677)), closes [#13909](https://github.com/vitejs/vite/issues/13909)
* fix: correct access to `crossOrigin` attribute (#12023) ([6a0d356](https://github.com/vitejs/vite/commit/6a0d356)), closes [#12023](https://github.com/vitejs/vite/issues/12023)
* fix: correct ssr flag in resolve calls (fix #6213) (#6216) ([6dd7d1a](https://github.com/vitejs/vite/commit/6dd7d1a)), closes [#6213](https://github.com/vitejs/vite/issues/6213) [#6216](https://github.com/vitejs/vite/issues/6216)
* fix: correct vite config temporary name (#12833) ([cdd9c23](https://github.com/vitejs/vite/commit/cdd9c23)), closes [#12833](https://github.com/vitejs/vite/issues/12833)
* fix: Correctly process urls when they are rewritten to contain space (#7452) ([9ee2cf6](https://github.com/vitejs/vite/commit/9ee2cf6)), closes [#7452](https://github.com/vitejs/vite/issues/7452)
* fix: correctly replace process.env.NODE_ENV (#8283) ([ec52baa](https://github.com/vitejs/vite/commit/ec52baa)), closes [#8283](https://github.com/vitejs/vite/issues/8283)
* fix: correctly resolve virtual modules during import scan (#5659) ([40d503c](https://github.com/vitejs/vite/commit/40d503c)), closes [#5659](https://github.com/vitejs/vite/issues/5659)
* fix: csp nonce injection when no closing tag (#16281) (#16282) ([3c85c6b](https://github.com/vitejs/vite/commit/3c85c6b)), closes [#16281](https://github.com/vitejs/vite/issues/16281) [#16282](https://github.com/vitejs/vite/issues/16282)
* fix: css order problem in async chunk (#9949) ([6c7b834](https://github.com/vitejs/vite/commit/6c7b834)), closes [#9949](https://github.com/vitejs/vite/issues/9949)
* fix: custom event payload type (#7498) ([28b0660](https://github.com/vitejs/vite/commit/28b0660)), closes [#7498](https://github.com/vitejs/vite/issues/7498)
* fix: debug `dotenv` when specifically scoped (#6682) ([c2f0021](https://github.com/vitejs/vite/commit/c2f0021)), closes [#6682](https://github.com/vitejs/vite/issues/6682)
* fix: dedupe import analysis public name (#5032) ([545b1f1](https://github.com/vitejs/vite/commit/545b1f1)), closes [#5032](https://github.com/vitejs/vite/issues/5032)
* fix: deep resolve side effects when glob does not contain / (#11807) ([f3a0c3b](https://github.com/vitejs/vite/commit/f3a0c3b)), closes [#11807](https://github.com/vitejs/vite/issues/11807)
* fix: default export module transformation for vitest spy (#8567) ([d357e33](https://github.com/vitejs/vite/commit/d357e33)), closes [#8567](https://github.com/vitejs/vite/issues/8567)
* fix: default host to `localhost` instead of `127.0.0.1` (#8543) ([49c0896](https://github.com/vitejs/vite/commit/49c0896)), closes [#8543](https://github.com/vitejs/vite/issues/8543)
* fix: default sideEffect option is delivered to rollup (#15665) ([f6cf3d1](https://github.com/vitejs/vite/commit/f6cf3d1)), closes [#15665](https://github.com/vitejs/vite/issues/15665)
* fix: default value of assetsDir option (#7703) ([83d32d9](https://github.com/vitejs/vite/commit/83d32d9)), closes [#7703](https://github.com/vitejs/vite/issues/7703)
* fix: define plugin not ignore file names (#6340) ([7215a03](https://github.com/vitejs/vite/commit/7215a03)), closes [#6340](https://github.com/vitejs/vite/issues/6340)
* fix: delayed full page reload (#7347) ([fa0820a](https://github.com/vitejs/vite/commit/fa0820a)), closes [#7347](https://github.com/vitejs/vite/issues/7347)
* fix: dep with dynamic import wrong error log (#7313) ([769f535](https://github.com/vitejs/vite/commit/769f535)), closes [#7313](https://github.com/vitejs/vite/issues/7313)
* fix: deprecate `{ assert: { type: raw }}` in favor of `{ as: raw }` (fix #7017) (#7215) ([87ecce5](https://github.com/vitejs/vite/commit/87ecce5)), closes [#7017](https://github.com/vitejs/vite/issues/7017) [#7215](https://github.com/vitejs/vite/issues/7215)
* fix: deps optimizer idle logic for workers (fix #8479) (#8511) ([1e05548](https://github.com/vitejs/vite/commit/1e05548)), closes [#8479](https://github.com/vitejs/vite/issues/8479) [#8511](https://github.com/vitejs/vite/issues/8511)
* fix: deps optimizer should wait on entries (#8822) ([2db1b5b](https://github.com/vitejs/vite/commit/2db1b5b)), closes [#8822](https://github.com/vitejs/vite/issues/8822)
* fix: derive `useDefineForClassFields` value from `tsconfig.compilerOptions.target` (fixes #10296) (# ([42976d8](https://github.com/vitejs/vite/commit/42976d8)), closes [#10296](https://github.com/vitejs/vite/issues/10296) [#11301](https://github.com/vitejs/vite/issues/11301)
* fix: detect env hmr (#7595) ([212d454](https://github.com/vitejs/vite/commit/212d454)), closes [#7595](https://github.com/vitejs/vite/issues/7595)
* fix: dev sourcemap (#8269) ([505f75e](https://github.com/vitejs/vite/commit/505f75e)), closes [#8269](https://github.com/vitejs/vite/issues/8269)
* fix: Dev SSR dep optimization + respect optimizeDeps.include (#11123) ([515caa5](https://github.com/vitejs/vite/commit/515caa5)), closes [#11123](https://github.com/vitejs/vite/issues/11123)
* fix: disable fs.cachedChecks for custom watch ignore patterns (#15828) ([9070be3](https://github.com/vitejs/vite/commit/9070be3)), closes [#15828](https://github.com/vitejs/vite/issues/15828)
* fix: disable inlineDynamicImports for ssr.target = node (#8641) ([3b41a8e](https://github.com/vitejs/vite/commit/3b41a8e)), closes [#8641](https://github.com/vitejs/vite/issues/8641)
* fix: disable keepNames in `vite:esbuild` (fixes #9164) (#9166) ([e6f3b02](https://github.com/vitejs/vite/commit/e6f3b02)), closes [#9164](https://github.com/vitejs/vite/issues/9164) [#9166](https://github.com/vitejs/vite/issues/9166)
* fix: display manualChunks warning only when a function is not used (#13797) (#13798) ([51c271f](https://github.com/vitejs/vite/commit/51c271f)), closes [#13797](https://github.com/vitejs/vite/issues/13797) [#13798](https://github.com/vitejs/vite/issues/13798)
* fix: do not access document in `/@vite/client` when not defined (#16318) ([646319c](https://github.com/vitejs/vite/commit/646319c)), closes [#16318](https://github.com/vitejs/vite/issues/16318)
* fix: do not append `browserHash` on optimized deps during build (#13906) ([0fb2340](https://github.com/vitejs/vite/commit/0fb2340)), closes [#13906](https://github.com/vitejs/vite/issues/13906)
* fix: do not append version query param when scanning for dependencies (#11961) ([575bcf6](https://github.com/vitejs/vite/commit/575bcf6)), closes [#11961](https://github.com/vitejs/vite/issues/11961)
* fix: do not include css string in bundle if not needed ([3e3c203](https://github.com/vitejs/vite/commit/3e3c203))
* fix: do not init optimizer during build (#15727) ([a08f646](https://github.com/vitejs/vite/commit/a08f646)), closes [#15727](https://github.com/vitejs/vite/issues/15727)
* fix: do not overwrite pendingReload promise (fix #5448) (#5452) ([cc9c2da](https://github.com/vitejs/vite/commit/cc9c2da)), closes [#5448](https://github.com/vitejs/vite/issues/5448) [#5452](https://github.com/vitejs/vite/issues/5452)
* fix: do not overwrite rollupOptions.input in dev (#6025) ([6cdf13a](https://github.com/vitejs/vite/commit/6cdf13a)), closes [#6025](https://github.com/vitejs/vite/issues/6025)
* fix: do not warn (about not being able to bundle non module scripts) when src is an external url (#7 ([0646fe8](https://github.com/vitejs/vite/commit/0646fe8)), closes [#7380](https://github.com/vitejs/vite/issues/7380)
* fix: docs for ssr manifest plugin and dedupe name (#4974) ([1bd6d56](https://github.com/vitejs/vite/commit/1bd6d56)), closes [#4974](https://github.com/vitejs/vite/issues/4974)
* fix: don't add `?import` for `@vite-ignore`ed import (#14851) ([42fee9e](https://github.com/vitejs/vite/commit/42fee9e)), closes [#14851](https://github.com/vitejs/vite/issues/14851)
* fix: don't add outDirs to watch.ignored if emptyOutDir is false (#16453) ([6a127d6](https://github.com/vitejs/vite/commit/6a127d6)), closes [#16453](https://github.com/vitejs/vite/issues/16453)
* fix: don't append `/@fs/` for bare imports (#14995) ([2a519a1](https://github.com/vitejs/vite/commit/2a519a1)), closes [#14995](https://github.com/vitejs/vite/issues/14995)
* fix: don't check .yarn/patches for computing dependencies hash (#11168) ([65bcccf](https://github.com/vitejs/vite/commit/65bcccf)), closes [#11168](https://github.com/vitejs/vite/issues/11168)
* fix: don't duplicate styles with dynamic import (fix #9967) (#9970) ([65f97bd](https://github.com/vitejs/vite/commit/65f97bd)), closes [#9967](https://github.com/vitejs/vite/issues/9967) [#9970](https://github.com/vitejs/vite/issues/9970)
* fix: don't force terser on non-legacy (fix #6266) (#6272) ([1da104e](https://github.com/vitejs/vite/commit/1da104e)), closes [#6266](https://github.com/vitejs/vite/issues/6266) [#6272](https://github.com/vitejs/vite/issues/6272)
* fix: don't inject CSS sourcemap for direct requests (#13115) ([7d80a47](https://github.com/vitejs/vite/commit/7d80a47)), closes [#13115](https://github.com/vitejs/vite/issues/13115)
* fix: don't modify config (#9262) ([bbc8318](https://github.com/vitejs/vite/commit/bbc8318)), closes [#9262](https://github.com/vitejs/vite/issues/9262)
* fix: don't override user config (#7034) ([8fd8f6e](https://github.com/vitejs/vite/commit/8fd8f6e)), closes [#7034](https://github.com/vitejs/vite/issues/7034)
* fix: don't overwrite default options unless given new value (#5111) ([4d72b40](https://github.com/vitejs/vite/commit/4d72b40)), closes [#5111](https://github.com/vitejs/vite/issues/5111)
* fix: don't pretransform classic script links (#15361) ([19e3c9a](https://github.com/vitejs/vite/commit/19e3c9a)), closes [#15361](https://github.com/vitejs/vite/issues/15361)
* fix: don't print urls on restart with default port (#11230) ([5aaecb6](https://github.com/vitejs/vite/commit/5aaecb6)), closes [#11230](https://github.com/vitejs/vite/issues/11230)
* fix: don't replace NODE_ENV in vite:client-inject (#6935) ([2b70003](https://github.com/vitejs/vite/commit/2b70003)), closes [#6935](https://github.com/vitejs/vite/issues/6935)
* fix: don't throw on malformed URLs (#10901) ([feb9b10](https://github.com/vitejs/vite/commit/feb9b10)), closes [#10901](https://github.com/vitejs/vite/issues/10901)
* fix: don't watch SPA fallback paths (#14953) ([24c2c57](https://github.com/vitejs/vite/commit/24c2c57)), closes [#14953](https://github.com/vitejs/vite/issues/14953)
* fix: dont handle sigterm in middleware mode (#8550) ([c6f43dd](https://github.com/vitejs/vite/commit/c6f43dd)), closes [#8550](https://github.com/vitejs/vite/issues/8550)
* fix: dont replace define in json (#7294) ([fc5c937](https://github.com/vitejs/vite/commit/fc5c937)), closes [#7294](https://github.com/vitejs/vite/issues/7294)
* fix: dont resolve imports with malformed URI (#16244) ([fbf69d5](https://github.com/vitejs/vite/commit/fbf69d5)), closes [#16244](https://github.com/vitejs/vite/issues/16244)
* fix: duplicate variable declaration caused by css modules (#5873) ([8e16a78](https://github.com/vitejs/vite/commit/8e16a78)), closes [#5873](https://github.com/vitejs/vite/issues/5873)
* fix: duplicated sourceMappingURL for worker bundles (fix #11601) (#11602) ([5444781](https://github.com/vitejs/vite/commit/5444781)), closes [#11601](https://github.com/vitejs/vite/issues/11601) [#11602](https://github.com/vitejs/vite/issues/11602)
* fix: dynamic import path contain ../ and its own directory (#9350) ([c6870f3](https://github.com/vitejs/vite/commit/c6870f3)), closes [#9350](https://github.com/vitejs/vite/issues/9350)
* fix: dynamic import vars ignored warning (#14006) ([4479431](https://github.com/vitejs/vite/commit/4479431)), closes [#14006](https://github.com/vitejs/vite/issues/14006)
* fix: dynamic import warning with @vite-ignore (#7533) ([29c1ec0](https://github.com/vitejs/vite/commit/29c1ec0)), closes [#7533](https://github.com/vitejs/vite/issues/7533)
* fix: dynamic-import-vars plugin normalize path issue (#16518) ([f71ba5b](https://github.com/vitejs/vite/commit/f71ba5b)), closes [#16518](https://github.com/vitejs/vite/issues/16518)
* fix: EACCES permission denied due to resolve new paths default (#7612) ([1dd019f](https://github.com/vitejs/vite/commit/1dd019f)), closes [#7612](https://github.com/vitejs/vite/issues/7612)
* fix: early discovery of missing deps, fix #7333 (#7346) ([7d2f37c](https://github.com/vitejs/vite/commit/7d2f37c)), closes [#7333](https://github.com/vitejs/vite/issues/7333) [#7346](https://github.com/vitejs/vite/issues/7346)
* fix: emit `vite:preloadError` for chunks without deps (#15203) ([d8001c5](https://github.com/vitejs/vite/commit/d8001c5)), closes [#15203](https://github.com/vitejs/vite/issues/15203)
* fix: emit assets from SSR build (#11430) ([ffbdcdb](https://github.com/vitejs/vite/commit/ffbdcdb)), closes [#11430](https://github.com/vitejs/vite/issues/11430)
* fix: empty CSS file was output when only .css?url is used (#15846) ([b2873ac](https://github.com/vitejs/vite/commit/b2873ac)), closes [#15846](https://github.com/vitejs/vite/issues/15846)
* fix: encode path uri only (#16212) ([0b2e40b](https://github.com/vitejs/vite/commit/0b2e40b)), closes [#16212](https://github.com/vitejs/vite/issues/16212)
* fix: encode URLs correctly (fix #15298) (#15311) ([b10d162](https://github.com/vitejs/vite/commit/b10d162)), closes [#15298](https://github.com/vitejs/vite/issues/15298) [#15311](https://github.com/vitejs/vite/issues/15311)
* fix: enforce absolute path for server.sourcemapIgnoreList (#12309) ([ab6ae07](https://github.com/vitejs/vite/commit/ab6ae07)), closes [#12309](https://github.com/vitejs/vite/issues/12309)
* fix: ensure define overrides import.meta in build (#8892) ([7d810a9](https://github.com/vitejs/vite/commit/7d810a9)), closes [#8892](https://github.com/vitejs/vite/issues/8892)
* fix: ensure deps optimizer first run, fixes #8750 (#8775) ([3f689a4](https://github.com/vitejs/vite/commit/3f689a4)), closes [#8750](https://github.com/vitejs/vite/issues/8750) [#8775](https://github.com/vitejs/vite/issues/8775)
* fix: ensure module in graph before transforming (#12774) ([44ad321](https://github.com/vitejs/vite/commit/44ad321)), closes [#12774](https://github.com/vitejs/vite/issues/12774)
* fix: ensure server.host is passed in preview-mode (fix #5387) (#5389) ([61b4b39](https://github.com/vitejs/vite/commit/61b4b39)), closes [#5387](https://github.com/vitejs/vite/issues/5387) [#5389](https://github.com/vitejs/vite/issues/5389)
* fix: ensure version query for direct node_modules imports (#9848) ([e7712ff](https://github.com/vitejs/vite/commit/e7712ff)), closes [#9848](https://github.com/vitejs/vite/issues/9848)
* fix: ensure version query for relative node_modules imports (#10016) ([1b822d0](https://github.com/vitejs/vite/commit/1b822d0)), closes [#10016](https://github.com/vitejs/vite/issues/10016)
* fix: entries in ssr.external (#9286) ([d420f01](https://github.com/vitejs/vite/commit/d420f01)), closes [#9286](https://github.com/vitejs/vite/issues/9286)
* fix: env variables override (#10113) ([d619460](https://github.com/vitejs/vite/commit/d619460)), closes [#10113](https://github.com/vitejs/vite/issues/10113)
* fix: EPERM error on Windows when processing dependencies (#8235) ([67743a3](https://github.com/vitejs/vite/commit/67743a3)), closes [#8235](https://github.com/vitejs/vite/issues/8235)
* fix: errors in worker handling (#7236) ([77dc1a1](https://github.com/vitejs/vite/commit/77dc1a1)), closes [#7236](https://github.com/vitejs/vite/issues/7236)
* fix: esbuild complains with extra fields (#12516) ([7be0ba5](https://github.com/vitejs/vite/commit/7be0ba5)), closes [#12516](https://github.com/vitejs/vite/issues/12516)
* fix: esbuild glob import resolve error (#15140) ([676804d](https://github.com/vitejs/vite/commit/676804d)), closes [#15140](https://github.com/vitejs/vite/issues/15140)
* fix: esbuild glob resolve error (#14533) ([3615c68](https://github.com/vitejs/vite/commit/3615c68)), closes [#14533](https://github.com/vitejs/vite/issues/14533)
* fix: esbuildOutputFromId for symlinked root (#10154) ([fc5310f](https://github.com/vitejs/vite/commit/fc5310f)), closes [#10154](https://github.com/vitejs/vite/issues/10154)
* fix: escape character in string regexp match (#7834) ([1d468c8](https://github.com/vitejs/vite/commit/1d468c8)), closes [#7834](https://github.com/vitejs/vite/issues/7834)
* fix: escape glob path (#9842) ([6be971e](https://github.com/vitejs/vite/commit/6be971e)), closes [#9842](https://github.com/vitejs/vite/issues/9842)
* fix: escape msg in render restricted error html (#12889) ([3aa2127](https://github.com/vitejs/vite/commit/3aa2127)), closes [#12889](https://github.com/vitejs/vite/issues/12889)
* fix: escape replacements in clientInjections (#12486) ([3765067](https://github.com/vitejs/vite/commit/3765067)), closes [#12486](https://github.com/vitejs/vite/issues/12486)
* fix: escape single quote when relative base is used (#16060) ([8f74ce4](https://github.com/vitejs/vite/commit/8f74ce4)), closes [#16060](https://github.com/vitejs/vite/issues/16060)
* fix: esm detection with `export const { A, B }` pattern (#13483) ([ea1bcc9](https://github.com/vitejs/vite/commit/ea1bcc9)), closes [#13483](https://github.com/vitejs/vite/issues/13483)
* fix: exclude ?commonjs-external when building in JSON plugin (#4867) ([fe25567](https://github.com/vitejs/vite/commit/fe25567)), closes [#4867](https://github.com/vitejs/vite/issues/4867)
* fix: exclude dependency of optimized dependency (fix: 5410) (#5411) ([ebd4027](https://github.com/vitejs/vite/commit/ebd4027)), closes [#5411](https://github.com/vitejs/vite/issues/5411)
* fix: exclude missing dependencies from optimization during SSR (#5017) ([2204afa](https://github.com/vitejs/vite/commit/2204afa)), closes [#5017](https://github.com/vitejs/vite/issues/5017)
* fix: execute classic worker in dev mode (#7099) ([3c0a609](https://github.com/vitejs/vite/commit/3c0a609)), closes [#7099](https://github.com/vitejs/vite/issues/7099)
* fix: export preprocessCSS in CJS (#11067) ([793255d](https://github.com/vitejs/vite/commit/793255d)), closes [#11067](https://github.com/vitejs/vite/issues/11067)
* fix: expose client dist in `exports` (#8324) ([689adc0](https://github.com/vitejs/vite/commit/689adc0)), closes [#8324](https://github.com/vitejs/vite/issues/8324)
* fix: expose server as Http2SecureServer type (#10196) ([f328f61](https://github.com/vitejs/vite/commit/f328f61)), closes [#10196](https://github.com/vitejs/vite/issues/10196)
* fix: externalize explicitly configured linked packages (#9346) ([c33e365](https://github.com/vitejs/vite/commit/c33e365)), closes [#9346](https://github.com/vitejs/vite/issues/9346)
* fix: externalize workspace relative import when bundle config (#9140) ([5a8a3ab](https://github.com/vitejs/vite/commit/5a8a3ab)), closes [#9140](https://github.com/vitejs/vite/issues/9140)
* fix: file link in overlay with custom backend (#14879) ([1bfb584](https://github.com/vitejs/vite/commit/1bfb584)), closes [#14879](https://github.com/vitejs/vite/issues/14879)
* fix: fileToBuiltUrl got undefined when file type is `.ico` (#7106) ([7a1a552](https://github.com/vitejs/vite/commit/7a1a552)), closes [#7106](https://github.com/vitejs/vite/issues/7106)
* fix: filter of BOM tags in json plugin (#8628) ([e10530b](https://github.com/vitejs/vite/commit/e10530b)), closes [#8628](https://github.com/vitejs/vite/issues/8628)
* fix: fix accumulated stacks in error overlay (#16393) ([102c2fd](https://github.com/vitejs/vite/commit/102c2fd)), closes [#16393](https://github.com/vitejs/vite/issues/16393)
* fix: fix HMR propagation when imports not analyzed (#7561) ([57e7914](https://github.com/vitejs/vite/commit/57e7914)), closes [#7561](https://github.com/vitejs/vite/issues/7561)
* fix: fix sourcemap when using object as `define` value  (#15805) ([445c4f2](https://github.com/vitejs/vite/commit/445c4f2)), closes [#15805](https://github.com/vitejs/vite/issues/15805)
* fix: fix the error message in the `toOutputFilePathWithoutRuntime` function (#11367) ([8820f75](https://github.com/vitejs/vite/commit/8820f75)), closes [#11367](https://github.com/vitejs/vite/issues/11367)
* fix: force overlay LTR (#4943) ([f8d8b73](https://github.com/vitejs/vite/commit/f8d8b73)), closes [#4943](https://github.com/vitejs/vite/issues/4943)
* fix: formatError() outside rollup context (#11156) ([2aee2eb](https://github.com/vitejs/vite/commit/2aee2eb)), closes [#11156](https://github.com/vitejs/vite/issues/11156)
* fix: fs cached checks disabled by default for yarn pnp (#15920) ([8b11fea](https://github.com/vitejs/vite/commit/8b11fea)), closes [#15920](https://github.com/vitejs/vite/issues/15920)
* fix: fs deny for case insensitive systems (#15653) ([89be67d](https://github.com/vitejs/vite/commit/89be67d)), closes [#15653](https://github.com/vitejs/vite/issues/15653)
* fix: fs serve only edit pathname (fixes #9148) (#9173) ([28cffc9](https://github.com/vitejs/vite/commit/28cffc9)), closes [#9148](https://github.com/vitejs/vite/issues/9148) [#9173](https://github.com/vitejs/vite/issues/9173)
* fix: fs.deny with leading double slash (#13348) ([813ddd6](https://github.com/vitejs/vite/commit/813ddd6)), closes [#13348](https://github.com/vitejs/vite/issues/13348)
* fix: glob import parsing (#10949) (#11056) ([ac2cfd6](https://github.com/vitejs/vite/commit/ac2cfd6)), closes [#10949](https://github.com/vitejs/vite/issues/10949) [#11056](https://github.com/vitejs/vite/issues/11056)
* fix: glob types (#8257) ([03b227e](https://github.com/vitejs/vite/commit/03b227e)), closes [#8257](https://github.com/vitejs/vite/issues/8257)
* fix: graceful rename in windows (#8036) ([fe704f1](https://github.com/vitejs/vite/commit/fe704f1)), closes [#8036](https://github.com/vitejs/vite/issues/8036)
* fix: gracefully handle forbidden filesystem access (#10793) ([92637a2](https://github.com/vitejs/vite/commit/92637a2)), closes [#10793](https://github.com/vitejs/vite/issues/10793)
* fix: gracefully shutdown preview server on `SIGTERM` (fix #12990) (#17333) ([2207a68](https://github.com/vitejs/vite/commit/2207a68)), closes [#12990](https://github.com/vitejs/vite/issues/12990) [#17333](https://github.com/vitejs/vite/issues/17333)
* fix: handle addWatchFile in load hooks (#14967) ([a0ab85b](https://github.com/vitejs/vite/commit/a0ab85b)), closes [#14967](https://github.com/vitejs/vite/issues/14967)
* fix: handle context resolve options (#8966) ([57c6c15](https://github.com/vitejs/vite/commit/57c6c15)), closes [#8966](https://github.com/vitejs/vite/issues/8966)
* fix: handle error without line and column in loc (#12312) ([ce18eba](https://github.com/vitejs/vite/commit/ce18eba)), closes [#12312](https://github.com/vitejs/vite/issues/12312)
* fix: handle errors during `hasWorkspacePackageJSON` function (#14394) ([c3e4791](https://github.com/vitejs/vite/commit/c3e4791)), closes [#14394](https://github.com/vitejs/vite/issues/14394)
* fix: handle files with multiple comments (#7202) ([3f5b645](https://github.com/vitejs/vite/commit/3f5b645)), closes [#7202](https://github.com/vitejs/vite/issues/7202)
* fix: handle fs.realpath.native MAX_PATH issue for Node.js <18.10 (#14487) ([17c5928](https://github.com/vitejs/vite/commit/17c5928)), closes [#14487](https://github.com/vitejs/vite/issues/14487)
* fix: handle function property extension in namespace import (#16113) ([f699194](https://github.com/vitejs/vite/commit/f699194)), closes [#16113](https://github.com/vitejs/vite/issues/16113)
* fix: handle local and module scripts separately (#5464) ([0713446](https://github.com/vitejs/vite/commit/0713446)), closes [#5464](https://github.com/vitejs/vite/issues/5464)
* fix: handle more yarn pnp load errors (#13160) ([adf61d9](https://github.com/vitejs/vite/commit/adf61d9)), closes [#13160](https://github.com/vitejs/vite/issues/13160)
* fix: handle namespace import and dynamic import interop consistently (#15619) ([ec8b420](https://github.com/vitejs/vite/commit/ec8b420)), closes [#15619](https://github.com/vitejs/vite/issues/15619)
* fix: handle optimize failure (#8006) ([ba95a2a](https://github.com/vitejs/vite/commit/ba95a2a)), closes [#8006](https://github.com/vitejs/vite/issues/8006)
* fix: handle relative path glob raw import, fix #7307 (#7371) ([7f8dc58](https://github.com/vitejs/vite/commit/7f8dc58)), closes [#7307](https://github.com/vitejs/vite/issues/7307) [#7371](https://github.com/vitejs/vite/issues/7371)
* fix: handle resolve optional peer deps (#9321) ([eec3886](https://github.com/vitejs/vite/commit/eec3886)), closes [#9321](https://github.com/vitejs/vite/issues/9321)
* fix: handle sourcemap correctly when multiple line import exists (#14232) ([627159d](https://github.com/vitejs/vite/commit/627159d)), closes [#14232](https://github.com/vitejs/vite/issues/14232)
* fix: handle sourcemap: false in transformWithEsbuild ([864d41d](https://github.com/vitejs/vite/commit/864d41d))
* fix: handle try-catch for fs promise when resolve https config (#12808) ([0bba402](https://github.com/vitejs/vite/commit/0bba402)), closes [#12808](https://github.com/vitejs/vite/issues/12808)
* fix: handle url imports with semicolon (fix #7717) (#7718) ([a5c2a78](https://github.com/vitejs/vite/commit/a5c2a78)), closes [#7717](https://github.com/vitejs/vite/issues/7717) [#7718](https://github.com/vitejs/vite/issues/7718)
* fix: handle warmup request error correctly (#16223) ([d7c5256](https://github.com/vitejs/vite/commit/d7c5256)), closes [#16223](https://github.com/vitejs/vite/issues/16223)
* fix: hmr for env files, regression from #15365 (#15559) ([d1b143f](https://github.com/vitejs/vite/commit/d1b143f)), closes [#15365](https://github.com/vitejs/vite/issues/15365) [#15559](https://github.com/vitejs/vite/issues/15559)
* fix: hmr full-reload encodeURI path (#6212) ([46b862a](https://github.com/vitejs/vite/commit/46b862a)), closes [#6212](https://github.com/vitejs/vite/issues/6212)
* fix: HMR propagation of HTML changes (fix #7870) (#7895) ([1f7855c](https://github.com/vitejs/vite/commit/1f7855c)), closes [#7870](https://github.com/vitejs/vite/issues/7870) [#7895](https://github.com/vitejs/vite/issues/7895)
* fix: honor the host param when creating a websocket server (#5617) ([882c8a8](https://github.com/vitejs/vite/commit/882c8a8)), closes [#5617](https://github.com/vitejs/vite/issues/5617)
* fix: html env replacement plugin position (#12404) ([96f36a9](https://github.com/vitejs/vite/commit/96f36a9)), closes [#12404](https://github.com/vitejs/vite/issues/12404)
* fix: htmlFallbackMiddleware for favicon (#15301) ([c902545](https://github.com/vitejs/vite/commit/c902545)), closes [#15301](https://github.com/vitejs/vite/issues/15301)
* fix: if host is specified check whether it is valid (#14013) ([c39e6c1](https://github.com/vitejs/vite/commit/c39e6c1)), closes [#14013](https://github.com/vitejs/vite/issues/14013)
* fix: ignore Playwright test results directory (#8778) ([314c09c](https://github.com/vitejs/vite/commit/314c09c)), closes [#8778](https://github.com/vitejs/vite/issues/8778)
* fix: ignore pnp resolve error (#12719) ([2d30ae5](https://github.com/vitejs/vite/commit/2d30ae5)), closes [#12719](https://github.com/vitejs/vite/issues/12719)
* fix: ignore sideEffects for scripts imported from html (#12786) ([f09551f](https://github.com/vitejs/vite/commit/f09551f)), closes [#12786](https://github.com/vitejs/vite/issues/12786)
* fix: ignore tsconfig target when bundling config (#9457) ([c5e7895](https://github.com/vitejs/vite/commit/c5e7895)), closes [#9457](https://github.com/vitejs/vite/issues/9457)
* fix: image -> image/x-icon (#7120) ([065ceca](https://github.com/vitejs/vite/commit/065ceca)), closes [#7120](https://github.com/vitejs/vite/issues/7120)
* fix: image-set with base64 images (fix #8028) (#8035) ([e10c0c1](https://github.com/vitejs/vite/commit/e10c0c1)), closes [#8028](https://github.com/vitejs/vite/issues/8028) [#8035](https://github.com/vitejs/vite/issues/8035)
* fix: import css in less/scss (fix 3293) (#7147) ([9b51a3a](https://github.com/vitejs/vite/commit/9b51a3a)), closes [#7147](https://github.com/vitejs/vite/issues/7147)
* fix: import url worker two times (#7468) ([f05a813](https://github.com/vitejs/vite/commit/f05a813)), closes [#7468](https://github.com/vitejs/vite/issues/7468)
* fix: import with query with exports field (#7073) ([88ded7f](https://github.com/vitejs/vite/commit/88ded7f)), closes [#7073](https://github.com/vitejs/vite/issues/7073)
* fix: import with query with exports/browser field (#7098) ([9ce6732](https://github.com/vitejs/vite/commit/9ce6732)), closes [#7098](https://github.com/vitejs/vite/issues/7098)
* fix: import with query with imports field (#16085) ([ab823ab](https://github.com/vitejs/vite/commit/ab823ab)), closes [#16085](https://github.com/vitejs/vite/issues/16085)
* fix: import.meta.env and process.env undefined variable replacement (fix #8663) (#10958) ([3e0cd3d](https://github.com/vitejs/vite/commit/3e0cd3d)), closes [#8663](https://github.com/vitejs/vite/issues/8663) [#10958](https://github.com/vitejs/vite/issues/10958)
* fix: import.meta.url in worker (#7464) ([8ac4b12](https://github.com/vitejs/vite/commit/8ac4b12)), closes [#7464](https://github.com/vitejs/vite/issues/7464)
* fix: importmap should insert before module preload link (#11492) ([25c64d7](https://github.com/vitejs/vite/commit/25c64d7)), closes [#11492](https://github.com/vitejs/vite/issues/11492)
* fix: improve alias merging (#6497) ([e57d8c6](https://github.com/vitejs/vite/commit/e57d8c6)), closes [#6497](https://github.com/vitejs/vite/issues/6497)
* fix: improve array config merging (#6344) ([028cbeb](https://github.com/vitejs/vite/commit/028cbeb)), closes [#6344](https://github.com/vitejs/vite/issues/6344)
* fix: improve CLI shortcuts help display (#11247) ([bb235b2](https://github.com/vitejs/vite/commit/bb235b2)), closes [#11247](https://github.com/vitejs/vite/issues/11247)
* fix: improve error message for HTML compilation error (fix #5769) (#5777) ([79d1397](https://github.com/vitejs/vite/commit/79d1397)), closes [#5769](https://github.com/vitejs/vite/issues/5769) [#5777](https://github.com/vitejs/vite/issues/5777)
* fix: improve HTML script proxying (#5279) ([1d6e7bb](https://github.com/vitejs/vite/commit/1d6e7bb)), closes [#5279](https://github.com/vitejs/vite/issues/5279)
* fix: Improve post-build asset update check (#6113) ([611fa03](https://github.com/vitejs/vite/commit/611fa03)), closes [#6113](https://github.com/vitejs/vite/issues/6113)
* fix: improve warning message for malformed packages (#6086) ([717cb08](https://github.com/vitejs/vite/commit/717cb08)), closes [#6086](https://github.com/vitejs/vite/issues/6086)
* fix: include `vite/types/*` in exports field (#14296) ([66a97be](https://github.com/vitejs/vite/commit/66a97be)), closes [#14296](https://github.com/vitejs/vite/issues/14296)
* fix: inconsistent handling of non-ASCII `base` in `resolveConfig` and dev server (#10247) ([16e4123](https://github.com/vitejs/vite/commit/16e4123)), closes [#10247](https://github.com/vitejs/vite/issues/10247)
* fix: incorrectly resolving `knownJsSrcRE` files from root (fixes #4161) (#8808) ([e1e426e](https://github.com/vitejs/vite/commit/e1e426e)), closes [#4161](https://github.com/vitejs/vite/issues/4161) [#8808](https://github.com/vitejs/vite/issues/8808)
* fix: increase default HTTPS dev server session memory limit (#6207) ([f895f94](https://github.com/vitejs/vite/commit/f895f94)), closes [#6207](https://github.com/vitejs/vite/issues/6207)
* fix: increase error overlay z-index (#10603) ([1157941](https://github.com/vitejs/vite/commit/1157941)), closes [#10603](https://github.com/vitejs/vite/issues/10603)
* fix: infer client port from page location (#7463) ([93ae8e5](https://github.com/vitejs/vite/commit/93ae8e5)), closes [#7463](https://github.com/vitejs/vite/issues/7463)
* fix: infer hmr ws target by client location (#8650) ([4061ee0](https://github.com/vitejs/vite/commit/4061ee0)), closes [#8650](https://github.com/vitejs/vite/issues/8650)
* fix: init dev ssr optimizer on server init (#15561) ([db28b92](https://github.com/vitejs/vite/commit/db28b92)), closes [#15561](https://github.com/vitejs/vite/issues/15561)
* fix: initWasm options should be optional (#14152) ([387a6e8](https://github.com/vitejs/vite/commit/387a6e8)), closes [#14152](https://github.com/vitejs/vite/issues/14152)
* fix: inject `__vite__mapDeps` code before sourcemap file comment (#15483) ([d2aa096](https://github.com/vitejs/vite/commit/d2aa096)), closes [#15483](https://github.com/vitejs/vite/issues/15483)
* fix: inject esbuild helpers in IIFE and UMD wrappers (#7948) ([f7d2d71](https://github.com/vitejs/vite/commit/f7d2d71)), closes [#7948](https://github.com/vitejs/vite/issues/7948)
* fix: injected tags indentation (#5000) ([4b84c0d](https://github.com/vitejs/vite/commit/4b84c0d)), closes [#5000](https://github.com/vitejs/vite/issues/5000)
* fix: injectQuery check with double slash in the url (#14910) ([84c5ff6](https://github.com/vitejs/vite/commit/84c5ff6)), closes [#14910](https://github.com/vitejs/vite/issues/14910)
* fix: inline css hash (#7974) ([f6ae60d](https://github.com/vitejs/vite/commit/f6ae60d)), closes [#7974](https://github.com/vitejs/vite/issues/7974)
* fix: inline dynamic imports for ssr-webworker (fixes #9385) (#9401) ([cd69358](https://github.com/vitejs/vite/commit/cd69358)), closes [#9385](https://github.com/vitejs/vite/issues/9385) [#9401](https://github.com/vitejs/vite/issues/9401)
* fix: inline js and css paths for virtual html (#7993) ([d49e3fb](https://github.com/vitejs/vite/commit/d49e3fb)), closes [#7993](https://github.com/vitejs/vite/issues/7993)
* fix: inline style css sourcemap (#7434) ([47668b5](https://github.com/vitejs/vite/commit/47668b5)), closes [#7434](https://github.com/vitejs/vite/issues/7434)
* fix: inline style hmr, transform style code inplace (#7869) ([a30a548](https://github.com/vitejs/vite/commit/a30a548)), closes [#7869](https://github.com/vitejs/vite/issues/7869)
* fix: invalidate inlined proxy scripts on change (#5891) ([5b8c58b](https://github.com/vitejs/vite/commit/5b8c58b)), closes [#5891](https://github.com/vitejs/vite/issues/5891)
* fix: invalidate ssrError when HMR update occurs (#8052) ([c7356e0](https://github.com/vitejs/vite/commit/c7356e0)), closes [#8052](https://github.com/vitejs/vite/issues/8052)
* fix: isFromTsImporter flag in worker virtual model (#10273) ([78f74c9](https://github.com/vitejs/vite/commit/78f74c9)), closes [#10273](https://github.com/vitejs/vite/issues/10273)
* fix: js fallback sourcemap content should be using original content (#15135) ([227d56d](https://github.com/vitejs/vite/commit/227d56d)), closes [#15135](https://github.com/vitejs/vite/issues/15135)
* fix: json error with position (#15225) ([14be75f](https://github.com/vitejs/vite/commit/14be75f)), closes [#15225](https://github.com/vitejs/vite/issues/15225)
* fix: json HMR (fixes #9521) (#9610) ([e45d95f](https://github.com/vitejs/vite/commit/e45d95f)), closes [#9521](https://github.com/vitejs/vite/issues/9521) [#9610](https://github.com/vitejs/vite/issues/9610)
* fix: judge next dirent cache type (#15787) ([5fbeba3](https://github.com/vitejs/vite/commit/5fbeba3)), closes [#15787](https://github.com/vitejs/vite/issues/15787)
* fix: keep track of ssr version of imported modules separately (#11973) ([8fe6952](https://github.com/vitejs/vite/commit/8fe6952)), closes [#11973](https://github.com/vitejs/vite/issues/11973)
* fix: lazily evaluate __vite__mapDeps files (#17602) ([dafff4a](https://github.com/vitejs/vite/commit/dafff4a)), closes [#17602](https://github.com/vitejs/vite/issues/17602)
* fix: leave fully dynamic import.meta.url asset (fixes #10306) (#10549) ([56802b1](https://github.com/vitejs/vite/commit/56802b1)), closes [#10306](https://github.com/vitejs/vite/issues/10306) [#10549](https://github.com/vitejs/vite/issues/10549)
* fix: legacy no emit worker (#9500) ([9d0b18b](https://github.com/vitejs/vite/commit/9d0b18b)), closes [#9500](https://github.com/vitejs/vite/issues/9500)
* fix: legacy no resolve asset urls (#9507) ([1d6a1eb](https://github.com/vitejs/vite/commit/1d6a1eb)), closes [#9507](https://github.com/vitejs/vite/issues/9507)
* fix: less promises for scanning and await with allSettled (#11245) ([45b170e](https://github.com/vitejs/vite/commit/45b170e)), closes [#11245](https://github.com/vitejs/vite/issues/11245)
* fix: lightningcss fails with html-proxy (#13776) ([6b56094](https://github.com/vitejs/vite/commit/6b56094)), closes [#13776](https://github.com/vitejs/vite/issues/13776)
* fix: lightningCSS should load external URL in CSS file (#13692) ([8517645](https://github.com/vitejs/vite/commit/8517645)), closes [#13692](https://github.com/vitejs/vite/issues/13692)
* fix: load-fallback catch (#5412) ([e73281c](https://github.com/vitejs/vite/commit/e73281c)), closes [#5412](https://github.com/vitejs/vite/issues/5412)
* fix: location is not defined error in cleanScssBugUrl (#13100) ([91d7b67](https://github.com/vitejs/vite/commit/91d7b67)), closes [#13100](https://github.com/vitejs/vite/issues/13100)
* fix: log worker plugins in debug mode (#9553) ([c1fa219](https://github.com/vitejs/vite/commit/c1fa219)), closes [#9553](https://github.com/vitejs/vite/issues/9553)
* fix: main browserHash after stable optimization rerun (#7284) ([98eefa8](https://github.com/vitejs/vite/commit/98eefa8)), closes [#7284](https://github.com/vitejs/vite/issues/7284)
* fix: make @fs URLs work with special characters (#7510) ([2b7dad1](https://github.com/vitejs/vite/commit/2b7dad1)), closes [#7510](https://github.com/vitejs/vite/issues/7510)
* fix: make `addWatchFile()` work (fix #7024) (#9723) ([34db08b](https://github.com/vitejs/vite/commit/34db08b)), closes [#7024](https://github.com/vitejs/vite/issues/7024) [#9723](https://github.com/vitejs/vite/issues/9723)
* fix: make `resolveConfig()` concurrent safe (#9224) ([dfaeb2b](https://github.com/vitejs/vite/commit/dfaeb2b)), closes [#9224](https://github.com/vitejs/vite/issues/9224)
* fix: make `server` type less restrictive (fix #17627) (#17628) ([b55c32f](https://github.com/vitejs/vite/commit/b55c32f)), closes [#17627](https://github.com/vitejs/vite/issues/17627) [#17628](https://github.com/vitejs/vite/issues/17628)
* fix: make `vite optimize` prebundle for dev (#11387) ([b4ced0f](https://github.com/vitejs/vite/commit/b4ced0f)), closes [#11387](https://github.com/vitejs/vite/issues/11387)
* fix: make array `acornInjectPlugins` work (fixes #8410) (#8415) ([08d594b](https://github.com/vitejs/vite/commit/08d594b)), closes [#8410](https://github.com/vitejs/vite/issues/8410) [#8415](https://github.com/vitejs/vite/issues/8415)
* fix: make client type work with `moduleResolution=node16` (#10375) ([8c4df1f](https://github.com/vitejs/vite/commit/8c4df1f)), closes [#10375](https://github.com/vitejs/vite/issues/10375)
* fix: make htmlFallback more permissive (#15059) ([6fcceeb](https://github.com/vitejs/vite/commit/6fcceeb)), closes [#15059](https://github.com/vitejs/vite/issues/15059)
* fix: make optimize error available to meta-framework (#13495) ([b70e783](https://github.com/vitejs/vite/commit/b70e783)), closes [#13495](https://github.com/vitejs/vite/issues/13495)
* fix: make viteMetadata property of RenderedChunk optional (#11768) ([128f09e](https://github.com/vitejs/vite/commit/128f09e)), closes [#11768](https://github.com/vitejs/vite/issues/11768)
* fix: mention `build.rollupOptions.output.manualChunks` instead of  `build.rollupOutput.manualChunks` ([89378c0](https://github.com/vitejs/vite/commit/89378c0)), closes [#16721](https://github.com/vitejs/vite/issues/16721)
* fix: mention that Node.js 13/15 support is dropped (fixes #9113) (#9116) ([2826303](https://github.com/vitejs/vite/commit/2826303)), closes [#9113](https://github.com/vitejs/vite/issues/9113) [#9116](https://github.com/vitejs/vite/issues/9116)
* fix: merge debug params instead of overwrite (#6504) (#6505) ([1ac7fb1](https://github.com/vitejs/vite/commit/1ac7fb1)), closes [#6504](https://github.com/vitejs/vite/issues/6504) [#6505](https://github.com/vitejs/vite/issues/6505)
* fix: mime missing extensions (#8568) ([acf3024](https://github.com/vitejs/vite/commit/acf3024)), closes [#8568](https://github.com/vitejs/vite/issues/8568)
* fix: missing js sourcemaps with rewritten imports broke debugging (#7767) (#9476) ([3fa96f6](https://github.com/vitejs/vite/commit/3fa96f6)), closes [#7767](https://github.com/vitejs/vite/issues/7767) [#9476](https://github.com/vitejs/vite/issues/9476)
* fix: missing tags inject fallback (#5339) ([3c44ac8](https://github.com/vitejs/vite/commit/3c44ac8)), closes [#5339](https://github.com/vitejs/vite/issues/5339)
* fix: missing types for `es-module-lexer` (fixes #8349) (#8352) ([df2cc3d](https://github.com/vitejs/vite/commit/df2cc3d)), closes [#8349](https://github.com/vitejs/vite/issues/8349) [#8352](https://github.com/vitejs/vite/issues/8352)
* fix: missing warmupRequest in transformIndexHtml (#15303) ([103820f](https://github.com/vitejs/vite/commit/103820f)), closes [#15303](https://github.com/vitejs/vite/issues/15303)
* fix: module graph ensureEntryFromUrl based on id (#9759) ([01857af](https://github.com/vitejs/vite/commit/01857af)), closes [#9759](https://github.com/vitejs/vite/issues/9759)
* fix: modulePreload false (#13973) ([488085d](https://github.com/vitejs/vite/commit/488085d)), closes [#13973](https://github.com/vitejs/vite/issues/13973)
* fix: modulepreload polyfill only during build (fix #4786) (#7816) ([709776f](https://github.com/vitejs/vite/commit/709776f)), closes [#4786](https://github.com/vitejs/vite/issues/4786) [#7816](https://github.com/vitejs/vite/issues/7816)
* fix: more stable hash calculation for depsOptimize (#15337) ([2b39fe6](https://github.com/vitejs/vite/commit/2b39fe6)), closes [#15337](https://github.com/vitejs/vite/issues/15337)
* fix: move package.json cache into ResolvedConfig (#5388) ([650b56e](https://github.com/vitejs/vite/commit/650b56e)), closes [#5388](https://github.com/vitejs/vite/issues/5388)
* fix: move peerDeps from #2042 to the right package.json ([3161d75](https://github.com/vitejs/vite/commit/3161d75)), closes [#2042](https://github.com/vitejs/vite/issues/2042)
* fix: multiple entries with shared css and no JS (#13962) ([89a3db0](https://github.com/vitejs/vite/commit/89a3db0)), closes [#13962](https://github.com/vitejs/vite/issues/13962)
* fix: narrow defineConfig return type (#12021) ([18fa8f0](https://github.com/vitejs/vite/commit/18fa8f0)), closes [#12021](https://github.com/vitejs/vite/issues/12021)
* fix: needs es interop check for newly discovered deps (#7243) ([ba3047d](https://github.com/vitejs/vite/commit/ba3047d)), closes [#7243](https://github.com/vitejs/vite/issues/7243)
* fix: nested comments and strings, new regexp utils (#7650) ([93900f0](https://github.com/vitejs/vite/commit/93900f0)), closes [#7650](https://github.com/vitejs/vite/issues/7650)
* fix: new SharedWorker syntax (#7800) ([474d5c2](https://github.com/vitejs/vite/commit/474d5c2)), closes [#7800](https://github.com/vitejs/vite/issues/7800)
* fix: no quote on attrs (#10117) ([f541239](https://github.com/vitejs/vite/commit/f541239)), closes [#10117](https://github.com/vitejs/vite/issues/10117)
* fix: node platform for ssr dev regression (#8840) ([7257fd8](https://github.com/vitejs/vite/commit/7257fd8)), closes [#8840](https://github.com/vitejs/vite/issues/8840)
* fix: node v18 support (#7812) ([fc89057](https://github.com/vitejs/vite/commit/fc89057)), closes [#7812](https://github.com/vitejs/vite/issues/7812)
* fix: non-relative base public paths in CSS files (#8682) ([d11d6ea](https://github.com/vitejs/vite/commit/d11d6ea)), closes [#8682](https://github.com/vitejs/vite/issues/8682)
* fix: normalise css paths in manifest on windows (fixes #9295) (#9353) ([13e6450](https://github.com/vitejs/vite/commit/13e6450)), closes [#9295](https://github.com/vitejs/vite/issues/9295) [#9353](https://github.com/vitejs/vite/issues/9353)
* fix: normalize away `base` in imported URLs (#5065) ([9164da0](https://github.com/vitejs/vite/commit/9164da0)), closes [#5065](https://github.com/vitejs/vite/issues/5065)
* fix: normalize import file path info (#15772) ([306df44](https://github.com/vitejs/vite/commit/306df44)), closes [#15772](https://github.com/vitejs/vite/issues/15772)
* fix: normalize internal plugin names (#4976) ([37f0b2f](https://github.com/vitejs/vite/commit/37f0b2f)), closes [#4976](https://github.com/vitejs/vite/issues/4976)
* fix: normalize literal-only entry pattern (#16010) ([1dccc37](https://github.com/vitejs/vite/commit/1dccc37)), closes [#16010](https://github.com/vitejs/vite/issues/16010)
* fix: normalize postcss dependency messages (#6959) ([3f3f473](https://github.com/vitejs/vite/commit/3f3f473)), closes [#6959](https://github.com/vitejs/vite/issues/6959)
* fix: normalize prettify url (#15705) ([98bc3dc](https://github.com/vitejs/vite/commit/98bc3dc)), closes [#15705](https://github.com/vitejs/vite/issues/15705)
* fix: not match \n when injecting esbuild helpers (#8414) ([5a57626](https://github.com/vitejs/vite/commit/5a57626)), closes [#8414](https://github.com/vitejs/vite/issues/8414)
* fix: objurl for type module, and concurrent tests (#8541) ([26ecd5a](https://github.com/vitejs/vite/commit/26ecd5a)), closes [#8541](https://github.com/vitejs/vite/issues/8541)
* fix: off-by-one bug in HTML whitespace removal (#14589) ([f54e6d8](https://github.com/vitejs/vite/commit/f54e6d8)), closes [#14589](https://github.com/vitejs/vite/issues/14589)
* fix: omit 'plugins' since it has no effect (#13879) ([64888b0](https://github.com/vitejs/vite/commit/64888b0)), closes [#13879](https://github.com/vitejs/vite/issues/13879)
* fix: omit protocol does not require pre-transform (#15355) ([d9ae1b2](https://github.com/vitejs/vite/commit/d9ae1b2)), closes [#15355](https://github.com/vitejs/vite/issues/15355)
* fix: only handle merge ssr.noExternal (#8003) ([642d65b](https://github.com/vitejs/vite/commit/642d65b)), closes [#8003](https://github.com/vitejs/vite/issues/8003)
* fix: only run build-html plugin on bundler inputs (fix #4067) (#5342) ([7541a8d](https://github.com/vitejs/vite/commit/7541a8d)), closes [#4067](https://github.com/vitejs/vite/issues/4067) [#5342](https://github.com/vitejs/vite/issues/5342)
* fix: only show the listened IP when host is specified (#13412) ([20b0cae](https://github.com/vitejs/vite/commit/20b0cae)), closes [#13412](https://github.com/vitejs/vite/issues/13412)
* fix: only watch needed env files (#15365) ([476e572](https://github.com/vitejs/vite/commit/476e572)), closes [#15365](https://github.com/vitejs/vite/issues/15365)
* fix: open browser reuse logic (#12535) ([04d14af](https://github.com/vitejs/vite/commit/04d14af)), closes [#12535](https://github.com/vitejs/vite/issues/12535)
* fix: optimize deps on dev SSR, builtin imports in node (#8854) ([d49856c](https://github.com/vitejs/vite/commit/d49856c)), closes [#8854](https://github.com/vitejs/vite/issues/8854)
* fix: optimized processing folder renaming in win (fix #7939) (#8019) ([e5fe1c6](https://github.com/vitejs/vite/commit/e5fe1c6)), closes [#7939](https://github.com/vitejs/vite/issues/7939) [#8019](https://github.com/vitejs/vite/issues/8019)
* fix: optimizeDeps during build and external ids (#13274) ([e3db771](https://github.com/vitejs/vite/commit/e3db771)), closes [#13274](https://github.com/vitejs/vite/issues/13274)
* fix: optimizeDeps.entries default ignore paths (#7469) ([4c95e99](https://github.com/vitejs/vite/commit/4c95e99)), closes [#7469](https://github.com/vitejs/vite/issues/7469)
* fix: optimizeDeps.entries transformRequest url (fix #8719) (#8748) ([9208c3b](https://github.com/vitejs/vite/commit/9208c3b)), closes [#8719](https://github.com/vitejs/vite/issues/8719) [#8748](https://github.com/vitejs/vite/issues/8748)
* fix: optimizeDeps.entries with literal-only pattern(s) (#15853) ([49300b3](https://github.com/vitejs/vite/commit/49300b3)), closes [#15853](https://github.com/vitejs/vite/issues/15853)
* fix: optimizeDeps.include missing in known imports fallback (#7218) ([6c08c86](https://github.com/vitejs/vite/commit/6c08c86)), closes [#7218](https://github.com/vitejs/vite/issues/7218)
* fix: outdated optimized dep removed from module graph (#8533) ([3f4d22d](https://github.com/vitejs/vite/commit/3f4d22d)), closes [#8533](https://github.com/vitejs/vite/issues/8533)
* fix: output combined sourcemap in importAnalysisBuild plugin (#12642) ([d051639](https://github.com/vitejs/vite/commit/d051639)), closes [#12642](https://github.com/vitejs/vite/issues/12642)
* fix: output correct error for empty import specifier (#16055) ([a9112eb](https://github.com/vitejs/vite/commit/a9112eb)), closes [#16055](https://github.com/vitejs/vite/issues/16055)
* fix: overwrite deps info browserHash only on commit (#7359) ([1e9615d](https://github.com/vitejs/vite/commit/1e9615d)), closes [#7359](https://github.com/vitejs/vite/issues/7359)
* fix: pass `customLogger` to `loadConfigFromFile` (fix #15824) (#15831) ([55a3427](https://github.com/vitejs/vite/commit/55a3427)), closes [#15824](https://github.com/vitejs/vite/issues/15824) [#15831](https://github.com/vitejs/vite/issues/15831)
* fix: pending reload never timeout (#6120) ([e002f4f](https://github.com/vitejs/vite/commit/e002f4f)), closes [#6120](https://github.com/vitejs/vite/issues/6120)
* fix: pending requests after module invalidation (#7283) ([a1044d7](https://github.com/vitejs/vite/commit/a1044d7)), closes [#7283](https://github.com/vitejs/vite/issues/7283)
* fix: performance is not defined (#5048) ([20b20e4](https://github.com/vitejs/vite/commit/20b20e4)), closes [#5048](https://github.com/vitejs/vite/issues/5048)
* fix: prebundle dep with colon (#7006) ([2136f2b](https://github.com/vitejs/vite/commit/2136f2b)), closes [#7006](https://github.com/vitejs/vite/issues/7006)
* fix: prefer exports when resolving (#10371) ([3259006](https://github.com/vitejs/vite/commit/3259006)), closes [#10371](https://github.com/vitejs/vite/issues/10371)
* fix: preload marker duplicate deps (#14955) ([55335cc](https://github.com/vitejs/vite/commit/55335cc)), closes [#14955](https://github.com/vitejs/vite/issues/14955)
* fix: prepend `config.base` to vite/env path (#13941) ([8e6cee8](https://github.com/vitejs/vite/commit/8e6cee8)), closes [#13941](https://github.com/vitejs/vite/issues/13941)
* fix: preserve annotations during build deps optimization (#8358) ([334cd9f](https://github.com/vitejs/vite/commit/334cd9f)), closes [#8358](https://github.com/vitejs/vite/issues/8358)
* fix: preserve default export from externalized packages (fixes #10258) (#10406) ([88b001b](https://github.com/vitejs/vite/commit/88b001b)), closes [#10258](https://github.com/vitejs/vite/issues/10258) [#10406](https://github.com/vitejs/vite/issues/10406)
* fix: preserve extension of css assets in the manifest (#8768) ([9508549](https://github.com/vitejs/vite/commit/9508549)), closes [#8768](https://github.com/vitejs/vite/issues/8768)
* fix: prevent cache on optional package resolve (#10812) ([c599a2e](https://github.com/vitejs/vite/commit/c599a2e)), closes [#10812](https://github.com/vitejs/vite/issues/10812)
* fix: prevent crash when the pad amount is negative (#8747) ([3af6a1b](https://github.com/vitejs/vite/commit/3af6a1b)), closes [#8747](https://github.com/vitejs/vite/issues/8747)
* fix: prevent dev server crashing on malformed URI (fix #6300) (#6308) ([a49d723](https://github.com/vitejs/vite/commit/a49d723)), closes [#6300](https://github.com/vitejs/vite/issues/6300) [#6308](https://github.com/vitejs/vite/issues/6308)
* fix: prevent error on not set location href (#12494) ([2fb8527](https://github.com/vitejs/vite/commit/2fb8527)), closes [#12494](https://github.com/vitejs/vite/issues/12494)
* fix: prevent error overlay style being overridden (fixes #9969) (#9971) ([a7706d0](https://github.com/vitejs/vite/commit/a7706d0)), closes [#9969](https://github.com/vitejs/vite/issues/9969) [#9971](https://github.com/vitejs/vite/issues/9971)
* fix: prevent loading env outside of root (#6995) ([e0a4d81](https://github.com/vitejs/vite/commit/e0a4d81)), closes [#6995](https://github.com/vitejs/vite/issues/6995)
* fix: prevent null pathname error (#9188) ([d66ffd0](https://github.com/vitejs/vite/commit/d66ffd0)), closes [#9188](https://github.com/vitejs/vite/issues/9188)
* fix: prevent production node_env in serve (#9066) ([7662998](https://github.com/vitejs/vite/commit/7662998)), closes [#9066](https://github.com/vitejs/vite/issues/9066)
* fix: prevent unhandledRejection if `--open` fails (#16726) ([1f60647](https://github.com/vitejs/vite/commit/1f60647)), closes [#16726](https://github.com/vitejs/vite/issues/16726)
* fix: preview fallback (#11312) ([cfedf9c](https://github.com/vitejs/vite/commit/cfedf9c)), closes [#11312](https://github.com/vitejs/vite/issues/11312)
* fix: preview jsdoc params (#7903) ([e474381](https://github.com/vitejs/vite/commit/e474381)), closes [#7903](https://github.com/vitejs/vite/issues/7903)
* fix: print error file path when using `rollupOptions.output.dir` (fix #9100) (#9111) ([3bffd14](https://github.com/vitejs/vite/commit/3bffd14)), closes [#9100](https://github.com/vitejs/vite/issues/9100) [#9111](https://github.com/vitejs/vite/issues/9111)
* fix: print urls when dns order change (#12261) ([e57cacf](https://github.com/vitejs/vite/commit/e57cacf)), closes [#12261](https://github.com/vitejs/vite/issues/12261)
* fix: prioritize existing env over .env (fixes #10676) (#10684) ([e2ea6af](https://github.com/vitejs/vite/commit/e2ea6af)), closes [#10676](https://github.com/vitejs/vite/issues/10676) [#10684](https://github.com/vitejs/vite/issues/10684)
* fix: processNodeUrl for srcset (#14870) ([0873bae](https://github.com/vitejs/vite/commit/0873bae)), closes [#14870](https://github.com/vitejs/vite/issues/14870)
* fix: properly clean up optimization temp folder (#12237) ([fbbf8fe](https://github.com/vitejs/vite/commit/fbbf8fe)), closes [#12237](https://github.com/vitejs/vite/issues/12237)
* fix: properly close optimizer on server restart (#10028) ([a32777f](https://github.com/vitejs/vite/commit/a32777f)), closes [#10028](https://github.com/vitejs/vite/issues/10028)
* fix: properly handle postfix for getRealPath (#5149) ([7d257c3](https://github.com/vitejs/vite/commit/7d257c3)), closes [#5149](https://github.com/vitejs/vite/issues/5149)
* fix: proxy html path should be encoded (#15223) ([5b85040](https://github.com/vitejs/vite/commit/5b85040)), closes [#15223](https://github.com/vitejs/vite/issues/15223)
* fix: proxy to secured websocket server (#10045) ([9de9bc4](https://github.com/vitejs/vite/commit/9de9bc4)), closes [#10045](https://github.com/vitejs/vite/issues/10045)
* fix: public files map will be updated on add/unlink in windows (#15317) ([921ca41](https://github.com/vitejs/vite/commit/921ca41)), closes [#15317](https://github.com/vitejs/vite/issues/15317)
* fix: race condition creation module in graph in transformRequest (#13085) ([43cbbcf](https://github.com/vitejs/vite/commit/43cbbcf)), closes [#13085](https://github.com/vitejs/vite/issues/13085)
* fix: re-encode url to prevent fs.allow bypass (fixes #8498) (#8979) ([b835699](https://github.com/vitejs/vite/commit/b835699)), closes [#8498](https://github.com/vitejs/vite/issues/8498) [#8979](https://github.com/vitejs/vite/issues/8979)
* fix: read the correct package.json in ssrExternal (#5927) ([7edabb4](https://github.com/vitejs/vite/commit/7edabb4)), closes [#5927](https://github.com/vitejs/vite/issues/5927) [#5890](https://github.com/vitejs/vite/issues/5890)
* fix: recycle serve to avoid preventing Node self-exit (#6895) ([d6b2c53](https://github.com/vitejs/vite/commit/d6b2c53)), closes [#6895](https://github.com/vitejs/vite/issues/6895)
* fix: regEx for <head> tag, fix #5285 (#5311) ([3ac08cc](https://github.com/vitejs/vite/commit/3ac08cc)), closes [#5285](https://github.com/vitejs/vite/issues/5285) [#5311](https://github.com/vitejs/vite/issues/5311)
* fix: relative path html (#8122) ([d0deac0](https://github.com/vitejs/vite/commit/d0deac0)), closes [#8122](https://github.com/vitejs/vite/issues/8122)
* fix: relax overlay frame regex (#14979) ([0b325bb](https://github.com/vitejs/vite/commit/0b325bb)), closes [#14979](https://github.com/vitejs/vite/issues/14979)
* fix: reload on restart with middleware mode (fixes #9038) (#9040) ([e372693](https://github.com/vitejs/vite/commit/e372693)), closes [#9038](https://github.com/vitejs/vite/issues/9038) [#9040](https://github.com/vitejs/vite/issues/9040)
* fix: relocated logger to respect config. (#10787) ([52e64eb](https://github.com/vitejs/vite/commit/52e64eb)), closes [#10787](https://github.com/vitejs/vite/issues/10787)
* fix: remove buildTimeImportMetaUrl (#8785) ([cd32095](https://github.com/vitejs/vite/commit/cd32095)), closes [#8785](https://github.com/vitejs/vite/issues/8785)
* fix: remove deprecated config.server.base (#13482) ([dc597bd](https://github.com/vitejs/vite/commit/dc597bd)), closes [#13482](https://github.com/vitejs/vite/issues/13482)
* fix: remove empty chunk css imports when using esnext (#8345) ([b3d9652](https://github.com/vitejs/vite/commit/b3d9652)), closes [#8345](https://github.com/vitejs/vite/issues/8345)
* fix: remove extra path shorten when resolving from a dir (#13381) ([5503198](https://github.com/vitejs/vite/commit/5503198)), closes [#13381](https://github.com/vitejs/vite/issues/13381)
* fix: remove loaded input sourcemap (fixes #8411) (#10705) ([eb50e3a](https://github.com/vitejs/vite/commit/eb50e3a)), closes [#8411](https://github.com/vitejs/vite/issues/8411) [#10705](https://github.com/vitejs/vite/issues/10705)
* fix: remove moment from force interop packages (#11502) ([b89ddd6](https://github.com/vitejs/vite/commit/b89ddd6)), closes [#11502](https://github.com/vitejs/vite/issues/11502)
* fix: remove picomatch type import (fixes #10656) (#10678) ([1128b4d](https://github.com/vitejs/vite/commit/1128b4d)), closes [#10656](https://github.com/vitejs/vite/issues/10656) [#10678](https://github.com/vitejs/vite/issues/10678)
* fix: Remove ssrError when invalidating a module (#8124) ([a543220](https://github.com/vitejs/vite/commit/a543220)), closes [#8124](https://github.com/vitejs/vite/issues/8124)
* fix: remove top-level imports in importMeta.d.ts, fixes augmentation (#6214) ([6b8d94d](https://github.com/vitejs/vite/commit/6b8d94d)), closes [#6214](https://github.com/vitejs/vite/issues/6214) [#6194](https://github.com/vitejs/vite/issues/6194) [#6211](https://github.com/vitejs/vite/issues/6211) [#6206](https://github.com/vitejs/vite/issues/6206) [#6205](https://github.com/vitejs/vite/issues/6205)
* fix: remove unneeded skipping optimization log (#7531) ([41fa2f5](https://github.com/vitejs/vite/commit/41fa2f5)), closes [#7531](https://github.com/vitejs/vite/issues/7531)
* fix: remove useless `/__vite_ping` handler (#8133) ([d607b2b](https://github.com/vitejs/vite/commit/d607b2b)), closes [#8133](https://github.com/vitejs/vite/issues/8133)
* fix: remove virtual module prefix while generating manifest (#6225) ([d51259b](https://github.com/vitejs/vite/commit/d51259b)), closes [#6225](https://github.com/vitejs/vite/issues/6225)
* fix: remove ws is already closed error (#9041) ([45b8b53](https://github.com/vitejs/vite/commit/45b8b53)), closes [#9041](https://github.com/vitejs/vite/issues/9041)
* fix: reoptimize deps on esbuild options change (#6855) ([4517c2b](https://github.com/vitejs/vite/commit/4517c2b)), closes [#6855](https://github.com/vitejs/vite/issues/6855)
* fix: replace asset references in CSS returned to JS (#5729) ([880026e](https://github.com/vitejs/vite/commit/880026e)), closes [#5729](https://github.com/vitejs/vite/issues/5729)
* fix: replace chalk with picocolors (#6277) ([5a111ce](https://github.com/vitejs/vite/commit/5a111ce)), closes [#6277](https://github.com/vitejs/vite/issues/6277)
* fix: replace execa with cross-spawn (#6299) ([f68ed8b](https://github.com/vitejs/vite/commit/f68ed8b)), closes [#6299](https://github.com/vitejs/vite/issues/6299)
* fix: replace import.meta.hot with undefined in the production (#11317) ([73afe6d](https://github.com/vitejs/vite/commit/73afe6d)), closes [#11317](https://github.com/vitejs/vite/issues/11317)
* fix: replace import.meta.url correctly (#7792) ([12d1194](https://github.com/vitejs/vite/commit/12d1194)), closes [#7792](https://github.com/vitejs/vite/issues/7792)
* fix: replace server.origin in css plugin (fix #5408) (#5571) ([bd8b66d](https://github.com/vitejs/vite/commit/bd8b66d)), closes [#5408](https://github.com/vitejs/vite/issues/5408) [#5571](https://github.com/vitejs/vite/issues/5571)
* fix: replace white with reset (#10104) ([5d56e42](https://github.com/vitejs/vite/commit/5d56e42)), closes [#10104](https://github.com/vitejs/vite/issues/10104)
* fix: replacing compression with modern version (#6557) ([5648d09](https://github.com/vitejs/vite/commit/5648d09)), closes [#6557](https://github.com/vitejs/vite/issues/6557)
* fix: reset global regex before match (#11132) ([db8df14](https://github.com/vitejs/vite/commit/db8df14)), closes [#11132](https://github.com/vitejs/vite/issues/11132)
* fix: resolve @import of the proxied <style> (#7031) ([c7aad02](https://github.com/vitejs/vite/commit/c7aad02)), closes [#7031](https://github.com/vitejs/vite/issues/7031)
* fix: resolve addons using nodeResolve() (#5809) ([d288772](https://github.com/vitejs/vite/commit/d288772))
* fix: resolve directory correctly when `fs.cachedChecks: true` (#15983) ([4fe971f](https://github.com/vitejs/vite/commit/4fe971f)), closes [#15983](https://github.com/vitejs/vite/issues/15983)
* fix: resolve drive relative path (#9097) ([b393451](https://github.com/vitejs/vite/commit/b393451)), closes [#9097](https://github.com/vitejs/vite/issues/9097)
* fix: resolvedUrls is null in plugin's configureServer after server restart (#15450) ([653a48c](https://github.com/vitejs/vite/commit/653a48c)), closes [#15450](https://github.com/vitejs/vite/issues/15450)
* fix: resovedUrls is null after server restart (#14890) ([bd4d29f](https://github.com/vitejs/vite/commit/bd4d29f)), closes [#14890](https://github.com/vitejs/vite/issues/14890)
* fix: respect .mjs .cjs extension in all modes (#9141) ([5ea70b3](https://github.com/vitejs/vite/commit/5ea70b3)), closes [#9141](https://github.com/vitejs/vite/issues/9141)
* fix: respect `mainFields` when resolving browser/module field (fixes #8659) (#10071) ([533d13c](https://github.com/vitejs/vite/commit/533d13c)), closes [#8659](https://github.com/vitejs/vite/issues/8659) [#10071](https://github.com/vitejs/vite/issues/10071)
* fix: respect `rollupOptions.external` for transitive dependencies (#8679) ([4f9097b](https://github.com/vitejs/vite/commit/4f9097b)), closes [#8679](https://github.com/vitejs/vite/issues/8679)
* fix: respect base when using `/__open-in-editor` (#11337) ([8856c2e](https://github.com/vitejs/vite/commit/8856c2e)), closes [#11337](https://github.com/vitejs/vite/issues/11337)
* fix: respect explicitily external/noExternal config (#8983) ([e369880](https://github.com/vitejs/vite/commit/e369880)), closes [#8983](https://github.com/vitejs/vite/issues/8983)
* fix: respect new port when change the config file (#6075) ([3ceffcc](https://github.com/vitejs/vite/commit/3ceffcc)), closes [#6075](https://github.com/vitejs/vite/issues/6075)
* fix: respect optimize deps entries (#8489) ([fba82d0](https://github.com/vitejs/vite/commit/fba82d0)), closes [#8489](https://github.com/vitejs/vite/issues/8489)
* fix: respect resolve.conditions, when resolving browser/require field (#9860) ([9a83eaf](https://github.com/vitejs/vite/commit/9a83eaf)), closes [#9860](https://github.com/vitejs/vite/issues/9860)
* fix: respect server.headers in static middlewares (#8481) ([408e5a7](https://github.com/vitejs/vite/commit/408e5a7)), closes [#8481](https://github.com/vitejs/vite/issues/8481)
* fix: restart optimize (#7004) ([47fbe29](https://github.com/vitejs/vite/commit/47fbe29)), closes [#7004](https://github.com/vitejs/vite/issues/7004)
* fix: restrict static middleware fs access (#5361) ([1f4723b](https://github.com/vitejs/vite/commit/1f4723b)), closes [#5361](https://github.com/vitejs/vite/issues/5361)
* fix: return 500 on proxy error only if possible (fixes #9172) (#9175) ([d2f02a8](https://github.com/vitejs/vite/commit/d2f02a8)), closes [#9172](https://github.com/vitejs/vite/issues/9172) [#9175](https://github.com/vitejs/vite/issues/9175)
* fix: return 500 on proxy error only if possible (fixes #9172) (#9193) ([b2f6bdc](https://github.com/vitejs/vite/commit/b2f6bdc)), closes [#9172](https://github.com/vitejs/vite/issues/9172) [#9193](https://github.com/vitejs/vite/issues/9193)
* fix: return type of `handleHMRUpdate` (#8367) ([79d5ce1](https://github.com/vitejs/vite/commit/79d5ce1)), closes [#8367](https://github.com/vitejs/vite/issues/8367)
* fix: reusing variable names in html module scripts (fix #6851) (#6818) ([c46b56d](https://github.com/vitejs/vite/commit/c46b56d)), closes [#6851](https://github.com/vitejs/vite/issues/6851) [#6818](https://github.com/vitejs/vite/issues/6818)
* fix: revert "fix: js fallback sourcemap content should be using original content (#15135)" (#15178) ([d2a2493](https://github.com/vitejs/vite/commit/d2a2493)), closes [#15135](https://github.com/vitejs/vite/issues/15135) [#15178](https://github.com/vitejs/vite/issues/15178)
* fix: Revert "fix: missing js sourcemaps with rewritten imports broke debugging (#7767) (#9476)" (#11 ([fdc6f3a](https://github.com/vitejs/vite/commit/fdc6f3a)), closes [#7767](https://github.com/vitejs/vite/issues/7767) [#9476](https://github.com/vitejs/vite/issues/9476) [#11144](https://github.com/vitejs/vite/issues/11144)
* fix: revert "load sourcemaps alongside modules (#11576)" (#11775) ([697dd00](https://github.com/vitejs/vite/commit/697dd00)), closes [#11576](https://github.com/vitejs/vite/issues/11576) [#11775](https://github.com/vitejs/vite/issues/11775)
* fix: revert #11290 (#11412) ([6587d2f](https://github.com/vitejs/vite/commit/6587d2f)), closes [#11290](https://github.com/vitejs/vite/issues/11290) [#11412](https://github.com/vitejs/vite/issues/11412)
* fix: revert #13073, use consistent virtual module ID in module graph (#13734) ([f589ac0](https://github.com/vitejs/vite/commit/f589ac0)), closes [#13073](https://github.com/vitejs/vite/issues/13073) [#13734](https://github.com/vitejs/vite/issues/13734)
* fix: revert #5342, only run build-html plugin on bundler inputs (#6715) ([59f8a63](https://github.com/vitejs/vite/commit/59f8a63)), closes [#5342](https://github.com/vitejs/vite/issues/5342) [#6715](https://github.com/vitejs/vite/issues/6715)
* fix: revert #5601 #6025, don't resolve rollupOptions.input (#6680) ([2a9da2e](https://github.com/vitejs/vite/commit/2a9da2e)), closes [#6680](https://github.com/vitejs/vite/issues/6680)
* fix: revert #5902, fix #8243 (#8654) ([1b820da](https://github.com/vitejs/vite/commit/1b820da)), closes [#8243](https://github.com/vitejs/vite/issues/8243) [#8654](https://github.com/vitejs/vite/issues/8654)
* fix: revert #6233, strip query when resolving entry (fix #6797) ([a012644](https://github.com/vitejs/vite/commit/a012644)), closes [#6797](https://github.com/vitejs/vite/issues/6797)
* fix: revert #6340, definePlugin tests, warning box (#7174) ([6cb0647](https://github.com/vitejs/vite/commit/6cb0647)), closes [#6340](https://github.com/vitejs/vite/issues/6340) [#7174](https://github.com/vitejs/vite/issues/7174)
* fix: revert #6935, bypass replacing process.env.NODE_ENV in ssr (#6970) ([b8218b0](https://github.com/vitejs/vite/commit/b8218b0)), closes [#6935](https://github.com/vitejs/vite/issues/6935) [#6970](https://github.com/vitejs/vite/issues/6970)
* fix: revert #7052, hmr style tag no support in html (#7136) ([5c116ec](https://github.com/vitejs/vite/commit/5c116ec)), closes [#7052](https://github.com/vitejs/vite/issues/7052) [#7136](https://github.com/vitejs/vite/issues/7136)
* fix: revert #7463 and #6624 (#7522) ([8efc6a6](https://github.com/vitejs/vite/commit/8efc6a6)), closes [#7463](https://github.com/vitejs/vite/issues/7463) [#6624](https://github.com/vitejs/vite/issues/6624) [#7522](https://github.com/vitejs/vite/issues/7522)
* fix: revert #7582, fix #7721 and #7736 (#7737) ([fa86d69](https://github.com/vitejs/vite/commit/fa86d69)), closes [#7721](https://github.com/vitejs/vite/issues/7721) [#7736](https://github.com/vitejs/vite/issues/7736) [#7737](https://github.com/vitejs/vite/issues/7737)
* fix: revert #7665 (#7716) ([26862c4](https://github.com/vitejs/vite/commit/26862c4)), closes [#7665](https://github.com/vitejs/vite/issues/7665) [#7716](https://github.com/vitejs/vite/issues/7716)
* fix: revert `package.json` change should trigger server restart (#15519) (#15558) ([9fc5d9c](https://github.com/vitejs/vite/commit/9fc5d9c)), closes [#15519](https://github.com/vitejs/vite/issues/15519) [#15558](https://github.com/vitejs/vite/issues/15558)
* fix: revert ensure module in graph before transforming (#12774) (#12929) ([9cc93a5](https://github.com/vitejs/vite/commit/9cc93a5)), closes [#12774](https://github.com/vitejs/vite/issues/12774) [#12929](https://github.com/vitejs/vite/issues/12929)
* fix: revert es-module-lexer version (#10614) ([cffe5c9](https://github.com/vitejs/vite/commit/cffe5c9)), closes [#10614](https://github.com/vitejs/vite/issues/10614)
* fix: revert import config module as data (#13731) ([b0bfa01](https://github.com/vitejs/vite/commit/b0bfa01)), closes [#13731](https://github.com/vitejs/vite/issues/13731)
* fix: revert only watch .env files in envDir (#12587) (#13217) ([0fd4616](https://github.com/vitejs/vite/commit/0fd4616)), closes [#12587](https://github.com/vitejs/vite/issues/12587) [#13217](https://github.com/vitejs/vite/issues/13217)
* fix: revert optimizeDeps false, keep optimizedDeps.disabled (#7715) ([ba9a1ff](https://github.com/vitejs/vite/commit/ba9a1ff)), closes [#7715](https://github.com/vitejs/vite/issues/7715)
* fix: revert update dotenv-expand #6703, fix #6858 (#6934) ([a9a1ae2](https://github.com/vitejs/vite/commit/a9a1ae2)), closes [#6858](https://github.com/vitejs/vite/issues/6858) [#6934](https://github.com/vitejs/vite/issues/6934)
* fix: reverts #8278 ([a0da2f0](https://github.com/vitejs/vite/commit/a0da2f0)), closes [#8278](https://github.com/vitejs/vite/issues/8278)
* fix: rollup watch crash on Windows (#13339) ([4f582c9](https://github.com/vitejs/vite/commit/4f582c9)), closes [#13339](https://github.com/vitejs/vite/issues/13339)
* fix: run htmlFallbackMiddleware for no accept header requests (#15025) ([b93dfe3](https://github.com/vitejs/vite/commit/b93dfe3)), closes [#15025](https://github.com/vitejs/vite/issues/15025)
* fix: sanitize asset filenames (#9737) ([2f468bb](https://github.com/vitejs/vite/commit/2f468bb)), closes [#9737](https://github.com/vitejs/vite/issues/9737)
* fix: scan entries when the root is in node_modules (#15746) ([c3e83bb](https://github.com/vitejs/vite/commit/c3e83bb)), closes [#15746](https://github.com/vitejs/vite/issues/15746)
* fix: scanner and optimizer should skip wasm (#9257) ([c616077](https://github.com/vitejs/vite/commit/c616077)), closes [#9257](https://github.com/vitejs/vite/issues/9257)
* fix: scope tracking for shadowing variables in blocks (#11806) (#11811) ([568bdab](https://github.com/vitejs/vite/commit/568bdab)), closes [#11806](https://github.com/vitejs/vite/issues/11806) [#11811](https://github.com/vitejs/vite/issues/11811)
* fix: scoped variable with array destructuring & nested arguments (#5730) ([b86a2f3](https://github.com/vitejs/vite/commit/b86a2f3)), closes [#5730](https://github.com/vitejs/vite/issues/5730)
* fix: scripts and styles were missing from built HTML on Windows (#16421) ([0e93f58](https://github.com/vitejs/vite/commit/0e93f58)), closes [#16421](https://github.com/vitejs/vite/issues/16421)
* fix: seperate source and dep for dymamic import after build (#6251) ([49da986](https://github.com/vitejs/vite/commit/49da986)), closes [#6251](https://github.com/vitejs/vite/issues/6251)
* fix: sequential injection of tags in transformIndexHtml (#5851) (#6901) ([649c7f6](https://github.com/vitejs/vite/commit/649c7f6)), closes [#5851](https://github.com/vitejs/vite/issues/5851) [#6901](https://github.com/vitejs/vite/issues/6901)
* fix: serialize bundleWorkerEntry (#11218) ([306bed0](https://github.com/vitejs/vite/commit/306bed0)), closes [#11218](https://github.com/vitejs/vite/issues/11218)
* fix: server and preview open fails to add slash before relative path (#11394) ([57276b7](https://github.com/vitejs/vite/commit/57276b7)), closes [#11394](https://github.com/vitejs/vite/issues/11394)
* fix: server middleware mode resolve (#16122) ([8403546](https://github.com/vitejs/vite/commit/8403546)), closes [#16122](https://github.com/vitejs/vite/issues/16122)
* fix: server.address before listen, chdir in test, basic cli test (#5059) ([fb37a63](https://github.com/vitejs/vite/commit/fb37a63)), closes [#5059](https://github.com/vitejs/vite/issues/5059)
* fix: server.force deprecation and force on restart API (#8842) ([c94f564](https://github.com/vitejs/vite/commit/c94f564)), closes [#8842](https://github.com/vitejs/vite/issues/8842)
* fix: server.host with ipv6 missed [] (fix #11466) (#11509) ([2c38bae](https://github.com/vitejs/vite/commit/2c38bae)), closes [#11466](https://github.com/vitejs/vite/issues/11466) [#11509](https://github.com/vitejs/vite/issues/11509)
* fix: server.preTransformRequests https error (#14991) (#14993) ([58ff849](https://github.com/vitejs/vite/commit/58ff849)), closes [#14991](https://github.com/vitejs/vite/issues/14991) [#14993](https://github.com/vitejs/vite/issues/14993)
* fix: server.proxy ws error causes crash (#9123) ([c2426d1](https://github.com/vitejs/vite/commit/c2426d1)), closes [#9123](https://github.com/vitejs/vite/issues/9123)
* fix: set `isSelfAccepting` to `false` for any asset not processed by importAnalysis (#7898) ([0d2089c](https://github.com/vitejs/vite/commit/0d2089c)), closes [#7898](https://github.com/vitejs/vite/issues/7898)
* fix: set correct `isSsrBuild` value in dev (#15536) ([fdbe04d](https://github.com/vitejs/vite/commit/fdbe04d)), closes [#15536](https://github.com/vitejs/vite/issues/15536)
* fix: shortcut open browser when set host (#13677) ([6f1c55e](https://github.com/vitejs/vite/commit/6f1c55e)), closes [#13677](https://github.com/vitejs/vite/issues/13677)
* fix: should load `--config foo.mjs` as an ES module (#5091) ([5d2c50a](https://github.com/vitejs/vite/commit/5d2c50a)), closes [#5091](https://github.com/vitejs/vite/issues/5091)
* fix: show network URLs when `--host 0.0.0.0` (#13438) ([00ee8c1](https://github.com/vitejs/vite/commit/00ee8c1)), closes [#13438](https://github.com/vitejs/vite/issues/13438)
* fix: simplify prettyUrl (#12488) ([ebe5aa5](https://github.com/vitejs/vite/commit/ebe5aa5)), closes [#12488](https://github.com/vitejs/vite/issues/12488)
* fix: skip applescript when no Chromium browser found (fixes #11205) (#11406) ([274d1f3](https://github.com/vitejs/vite/commit/274d1f3)), closes [#11205](https://github.com/vitejs/vite/issues/11205) [#11406](https://github.com/vitejs/vite/issues/11406)
* fix: skip encode if is data uri (#16233) ([8617e76](https://github.com/vitejs/vite/commit/8617e76)), closes [#16233](https://github.com/vitejs/vite/issues/16233)
* fix: skip injecting `__vite__mapDeps` when it's not used (#16271) ([890538a](https://github.com/vitejs/vite/commit/890538a)), closes [#16271](https://github.com/vitejs/vite/issues/16271)
* fix: skip inline html (#8789) ([4a6408b](https://github.com/vitejs/vite/commit/4a6408b)), closes [#8789](https://github.com/vitejs/vite/issues/8789)
* fix: Skip inlining Git LFS placeholders (fix #9714) (#9795) ([9c7e43d](https://github.com/vitejs/vite/commit/9c7e43d)), closes [#9714](https://github.com/vitejs/vite/issues/9714) [#9795](https://github.com/vitejs/vite/issues/9795)
* fix: skip not only .js but also .mjs manifest entries (#15841) ([3d860e7](https://github.com/vitejs/vite/commit/3d860e7)), closes [#15841](https://github.com/vitejs/vite/issues/15841)
* fix: skip shortcuts on non-tty stdin (#11263) ([9602686](https://github.com/vitejs/vite/commit/9602686)), closes [#11263](https://github.com/vitejs/vite/issues/11263)
* fix: skip undefined proxy entry (#9622) ([e396d67](https://github.com/vitejs/vite/commit/e396d67)), closes [#9622](https://github.com/vitejs/vite/issues/9622)
* fix: skip watchPackageDataPlugin for worker builds (#14762) ([9babef5](https://github.com/vitejs/vite/commit/9babef5)), closes [#14762](https://github.com/vitejs/vite/issues/14762)
* fix: sourcemap missing source files warning with cached vue (#7442) ([a2ce20d](https://github.com/vitejs/vite/commit/a2ce20d)), closes [#7442](https://github.com/vitejs/vite/issues/7442)
* fix: sourcemap source point to null (#8299) ([356b896](https://github.com/vitejs/vite/commit/356b896)), closes [#8299](https://github.com/vitejs/vite/issues/8299)
* fix: sourcemapIgnoreList for optimizedDeps (#12633) ([c1d3fc9](https://github.com/vitejs/vite/commit/c1d3fc9)), closes [#12633](https://github.com/vitejs/vite/issues/12633)
* fix: sourcemaps windows drive letter inconsistency, fix 4964 (#4985) ([723cd63](https://github.com/vitejs/vite/commit/723cd63)), closes [#4985](https://github.com/vitejs/vite/issues/4985)
* fix: spelling mistakes (#7883) ([54728e3](https://github.com/vitejs/vite/commit/54728e3)), closes [#7883](https://github.com/vitejs/vite/issues/7883)
* fix: splitFileAndPostfix works as cleanUrl (#12572) ([276725f](https://github.com/vitejs/vite/commit/276725f)), closes [#12572](https://github.com/vitejs/vite/issues/12572)
* fix: srcset handling in html (#6419) ([a0ee4ff](https://github.com/vitejs/vite/commit/a0ee4ff)), closes [#6419](https://github.com/vitejs/vite/issues/6419)
* fix: srcSet with optional descriptor (#15905) ([81b3bd0](https://github.com/vitejs/vite/commit/81b3bd0)), closes [#15905](https://github.com/vitejs/vite/issues/15905)
* fix: SSR deep imports externalization (fixes #8420) (#8421) ([89d6711](https://github.com/vitejs/vite/commit/89d6711)), closes [#8420](https://github.com/vitejs/vite/issues/8420) [#8421](https://github.com/vitejs/vite/issues/8421)
* fix: SSR import in dev can't resolve default import (fix #5706) (#5923) ([21d79d7](https://github.com/vitejs/vite/commit/21d79d7)), closes [#5706](https://github.com/vitejs/vite/issues/5706) [#5923](https://github.com/vitejs/vite/issues/5923)
* fix: SSR with relative base (#8683) ([c1667bb](https://github.com/vitejs/vite/commit/c1667bb)), closes [#8683](https://github.com/vitejs/vite/issues/8683)
* fix: ssr-manifest no base (#8371) ([37eb5b3](https://github.com/vitejs/vite/commit/37eb5b3)), closes [#8371](https://github.com/vitejs/vite/issues/8371)
* fix: ssr.external/noExternal should apply to packageName (#9146) ([5844d8e](https://github.com/vitejs/vite/commit/5844d8e)), closes [#9146](https://github.com/vitejs/vite/issues/9146)
* fix: ssr.noExternal with boolean values (#7813) ([0b2d307](https://github.com/vitejs/vite/commit/0b2d307)), closes [#7813](https://github.com/vitejs/vite/issues/7813)
* fix: ssrBuild is optional, avoid breaking VitePress (#8912) ([722f514](https://github.com/vitejs/vite/commit/722f514)), closes [#8912](https://github.com/vitejs/vite/issues/8912)
* fix: ssrLoadModule executes code in non-strict mode, fixes #9197 (#9199) ([5866cfb](https://github.com/vitejs/vite/commit/5866cfb)), closes [#9197](https://github.com/vitejs/vite/issues/9197) [#9199](https://github.com/vitejs/vite/issues/9199)
* fix: status optional in windows network drive regex (fix: #12948) (#12949) ([f781fc6](https://github.com/vitejs/vite/commit/f781fc6)), closes [#12948](https://github.com/vitejs/vite/issues/12948) [#12949](https://github.com/vitejs/vite/issues/12949)
* fix: stop considering parent URLs as public file (#11145) ([568a014](https://github.com/vitejs/vite/commit/568a014)), closes [#11145](https://github.com/vitejs/vite/issues/11145)
* fix: strip NULL_BYTE_PLACEHOLDER before transform (#6390) ([5964949](https://github.com/vitejs/vite/commit/5964949)), closes [#6390](https://github.com/vitejs/vite/issues/6390)
* fix: strip query when resolving entry (#6233) ([000ba2e](https://github.com/vitejs/vite/commit/000ba2e)), closes [#6233](https://github.com/vitejs/vite/issues/6233)
* fix: style use string instead of js import (#7786) ([ba43c29](https://github.com/vitejs/vite/commit/ba43c29)), closes [#7786](https://github.com/vitejs/vite/issues/7786)
* fix: support multiline dynamic imports (#9314) ([e66cf69](https://github.com/vitejs/vite/commit/e66cf69)), closes [#9314](https://github.com/vitejs/vite/issues/9314)
* fix: support process each out dir when there are two or more (#9748) ([ee3231c](https://github.com/vitejs/vite/commit/ee3231c)), closes [#9748](https://github.com/vitejs/vite/issues/9748)
* fix: support set NODE_ENV in scripts when custom mode option (#8218) ([adcf041](https://github.com/vitejs/vite/commit/adcf041)), closes [#8218](https://github.com/vitejs/vite/issues/8218)
* fix: support stylesheets with link tag and media/disable prop (#6751) ([e6c8965](https://github.com/vitejs/vite/commit/e6c8965)), closes [#6751](https://github.com/vitejs/vite/issues/6751)
* fix: support vite client in safari 13 (#9315) ([2415193](https://github.com/vitejs/vite/commit/2415193)), closes [#9315](https://github.com/vitejs/vite/issues/9315)
* fix: suppress addWatchFile invalid phase error (#14751) ([c3622d7](https://github.com/vitejs/vite/commit/c3622d7)), closes [#14751](https://github.com/vitejs/vite/issues/14751)
* fix: suppress terser warning if minify disabled (#15275) ([3e42611](https://github.com/vitejs/vite/commit/3e42611)), closes [#15275](https://github.com/vitejs/vite/issues/15275)
* fix: symbolic links in public dir (#15264) ([ef2a024](https://github.com/vitejs/vite/commit/ef2a024)), closes [#15264](https://github.com/vitejs/vite/issues/15264)
* fix: tailwind css sourcemap warning (#7480) ([90df0bb](https://github.com/vitejs/vite/commit/90df0bb)), closes [#7480](https://github.com/vitejs/vite/issues/7480)
* fix: take in relative assets path fixes from rollup (#12695) ([81e44dd](https://github.com/vitejs/vite/commit/81e44dd)), closes [#12695](https://github.com/vitejs/vite/issues/12695)
* fix: terminate WebSocket connections before closing WebSocket server (#6115) ([b9871bb](https://github.com/vitejs/vite/commit/b9871bb)), closes [#6115](https://github.com/vitejs/vite/issues/6115)
* fix: the shortcut fails to open browser when set the host (#13579) ([e0a48c5](https://github.com/vitejs/vite/commit/e0a48c5)), closes [#13579](https://github.com/vitejs/vite/issues/13579)
* fix: this._implicitHeader is not a function (#6313) ([c5ba2f2](https://github.com/vitejs/vite/commit/c5ba2f2)), closes [#6313](https://github.com/vitejs/vite/issues/6313)
* fix: throw error on build optimizeDeps issue (#12560) ([02a46d7](https://github.com/vitejs/vite/commit/02a46d7)), closes [#12560](https://github.com/vitejs/vite/issues/12560)
* fix: throw Error when can't preload CSS (#7108) ([d9f8edb](https://github.com/vitejs/vite/commit/d9f8edb)), closes [#7108](https://github.com/vitejs/vite/issues/7108)
* fix: throw full error causing preprocessor to not load (#5816) ([f6fcd21](https://github.com/vitejs/vite/commit/f6fcd21)), closes [#5816](https://github.com/vitejs/vite/issues/5816)
* fix: throw missing name error only when 'umd' or 'iife' are used (#9886) ([b8aa825](https://github.com/vitejs/vite/commit/b8aa825)), closes [#9886](https://github.com/vitejs/vite/issues/9886)
* fix: throw ssr import error directly (fix #12322) (#12324) ([21ffc6a](https://github.com/vitejs/vite/commit/21ffc6a)), closes [#12322](https://github.com/vitejs/vite/issues/12322) [#12324](https://github.com/vitejs/vite/issues/12324)
* fix: throws error when plugin tries to resolve ID to external URL (#11731) ([49674b5](https://github.com/vitejs/vite/commit/49674b5)), closes [#11731](https://github.com/vitejs/vite/issues/11731)
* fix: timestamp config dynamicImport (#13502) ([6a87c65](https://github.com/vitejs/vite/commit/6a87c65)), closes [#13502](https://github.com/vitejs/vite/issues/13502)
* fix: tolerate undefined parent in `hookNodeResolve` callback (#5664) ([d788682](https://github.com/vitejs/vite/commit/d788682)), closes [#5664](https://github.com/vitejs/vite/issues/5664)
* fix: transform error message add file info (#13687) ([6dca41c](https://github.com/vitejs/vite/commit/6dca41c)), closes [#13687](https://github.com/vitejs/vite/issues/13687)
* fix: transform import.meta.glob when scan JS/TS #10634 (#10635) ([c53ffec](https://github.com/vitejs/vite/commit/c53ffec)), closes [#10634](https://github.com/vitejs/vite/issues/10634) [#10635](https://github.com/vitejs/vite/issues/10635)
* fix: tree-shake modulepreload polyfill (#9531) ([1f11a70](https://github.com/vitejs/vite/commit/1f11a70)), closes [#9531](https://github.com/vitejs/vite/issues/9531)
* fix: tsconfig `jsx` overrides esbuild options, reverts #10374 (#10714) ([aacf6a4](https://github.com/vitejs/vite/commit/aacf6a4)), closes [#10374](https://github.com/vitejs/vite/issues/10374) [#10714](https://github.com/vitejs/vite/issues/10714)
* fix: typo (#14334) ([30df500](https://github.com/vitejs/vite/commit/30df500)), closes [#14334](https://github.com/vitejs/vite/issues/14334)
* fix: typo (#14337) ([6ffe070](https://github.com/vitejs/vite/commit/6ffe070)), closes [#14337](https://github.com/vitejs/vite/issues/14337)
* fix: typo (#7064) ([f38654f](https://github.com/vitejs/vite/commit/f38654f)), closes [#7064](https://github.com/vitejs/vite/issues/7064)
* fix: typo in #8121 (#8143) ([c32e3ac](https://github.com/vitejs/vite/commit/c32e3ac)), closes [#8121](https://github.com/vitejs/vite/issues/8121) [#8143](https://github.com/vitejs/vite/issues/8143)
* fix: typo in client log (#17363) ([68aa9f8](https://github.com/vitejs/vite/commit/68aa9f8)), closes [#17363](https://github.com/vitejs/vite/issues/17363)
* fix: undefined document in worker (#12988) ([08c1452](https://github.com/vitejs/vite/commit/08c1452)), closes [#12988](https://github.com/vitejs/vite/issues/12988)
* fix: unexpected config temporary file (#13269) ([ff3ce31](https://github.com/vitejs/vite/commit/ff3ce31)), closes [#13269](https://github.com/vitejs/vite/issues/13269)
* fix: unhandled exception on eager transformRequest (#7345) ([c3260a4](https://github.com/vitejs/vite/commit/c3260a4)), closes [#7345](https://github.com/vitejs/vite/issues/7345)
* fix: unicode path html entry point (#5821) (#5823) ([2048195](https://github.com/vitejs/vite/commit/2048195)), closes [#5821](https://github.com/vitejs/vite/issues/5821) [#5823](https://github.com/vitejs/vite/issues/5823)
* fix: unify css collecting order (#11671) ([20a8a15](https://github.com/vitejs/vite/commit/20a8a15)), closes [#11671](https://github.com/vitejs/vite/issues/11671)
* fix: unique dep optimizer temp folders (#12252) ([38ce81c](https://github.com/vitejs/vite/commit/38ce81c)), closes [#12252](https://github.com/vitejs/vite/issues/12252)
* fix: unminified build breaks __vitePreload (#5785) ([757a74a](https://github.com/vitejs/vite/commit/757a74a)), closes [#5785](https://github.com/vitejs/vite/issues/5785)
* fix: unwrapId and pass ssr flag when adding to moduleGraph in this.load (#13083) ([9041e19](https://github.com/vitejs/vite/commit/9041e19)), closes [#13083](https://github.com/vitejs/vite/issues/13083)
* fix: update .html fallback in MPA ([b5637a7](https://github.com/vitejs/vite/commit/b5637a7))
* fix: update *.wasm type (fix #4835) (#4881) ([5e1b8d4](https://github.com/vitejs/vite/commit/5e1b8d4)), closes [#4835](https://github.com/vitejs/vite/issues/4835) [#4881](https://github.com/vitejs/vite/issues/4881)
* fix: update CJS interop error message (#11842) ([356ddfe](https://github.com/vitejs/vite/commit/356ddfe)), closes [#11842](https://github.com/vitejs/vite/issues/11842)
* fix: update client.ts@cleanUrl to accomodate blob protocol (#16182) ([1a3b1d7](https://github.com/vitejs/vite/commit/1a3b1d7)), closes [#16182](https://github.com/vitejs/vite/issues/16182)
* fix: update dep types (fixes #9475) (#9489) ([937cecc](https://github.com/vitejs/vite/commit/937cecc)), closes [#9475](https://github.com/vitejs/vite/issues/9475) [#9489](https://github.com/vitejs/vite/issues/9489)
* fix: update javascript mime type to text/javascript (#15427) ([a621de8](https://github.com/vitejs/vite/commit/a621de8)), closes [#15427](https://github.com/vitejs/vite/issues/15427)
* fix: update package cache watcher (#12772) ([a78588f](https://github.com/vitejs/vite/commit/a78588f)), closes [#12772](https://github.com/vitejs/vite/issues/12772)
* fix: update postcss-load-config to load PostCSS plugins based on their config file path (#6856) ([f02f961](https://github.com/vitejs/vite/commit/f02f961)), closes [#6856](https://github.com/vitejs/vite/issues/6856)
* fix: update preview port to 4173 (#6330) ([870e1c0](https://github.com/vitejs/vite/commit/870e1c0)), closes [#6330](https://github.com/vitejs/vite/issues/6330)
* fix: update sourcemap in importAnalysisBuild (#7825) ([d7540c8](https://github.com/vitejs/vite/commit/d7540c8)), closes [#7825](https://github.com/vitejs/vite/issues/7825)
* fix: update SSR externals only when SSR is enabled (fix #6478) (#6492) ([28d1e7e](https://github.com/vitejs/vite/commit/28d1e7e)), closes [#6478](https://github.com/vitejs/vite/issues/6478) [#6492](https://github.com/vitejs/vite/issues/6492)
* fix: update Terser type definitions (fix #17668) (#17669) ([b723a75](https://github.com/vitejs/vite/commit/b723a75)), closes [#17668](https://github.com/vitejs/vite/issues/17668) [#17669](https://github.com/vitejs/vite/issues/17669)
* fix: update to esbuild 0.14.27, fix #6994 (#7320) ([65aaeee](https://github.com/vitejs/vite/commit/65aaeee)), closes [#6994](https://github.com/vitejs/vite/issues/6994) [#7320](https://github.com/vitejs/vite/issues/7320)
* fix: update transform error message (#14139) ([e0eb304](https://github.com/vitejs/vite/commit/e0eb304)), closes [#14139](https://github.com/vitejs/vite/issues/14139)
* fix: update tsconfck to 1.2.1 (#7424) ([a90b03b](https://github.com/vitejs/vite/commit/a90b03b)), closes [#7424](https://github.com/vitejs/vite/issues/7424)
* fix: update type CSSModulesOptions interface (#14987) ([d0b2153](https://github.com/vitejs/vite/commit/d0b2153)), closes [#14987](https://github.com/vitejs/vite/issues/14987)
* fix: update watch mode (#7132) ([9ed1672](https://github.com/vitejs/vite/commit/9ed1672)), closes [#7132](https://github.com/vitejs/vite/issues/7132)
* fix: update ws types (#7605) ([b620587](https://github.com/vitejs/vite/commit/b620587)), closes [#7605](https://github.com/vitejs/vite/issues/7605)
* fix: upgrade esbuild to 0.20.x (#16062) ([899d9b1](https://github.com/vitejs/vite/commit/899d9b1)), closes [#16062](https://github.com/vitejs/vite/issues/16062)
* fix: upgrade esbuild to 0.20.x (#16079) ([30e5ae3](https://github.com/vitejs/vite/commit/30e5ae3)), closes [#16079](https://github.com/vitejs/vite/issues/16079)
* fix: upgrade postcss-modules (#6248) ([ac3f434](https://github.com/vitejs/vite/commit/ac3f434)), closes [#6248](https://github.com/vitejs/vite/issues/6248)
* fix: upgrade to @rollup/plugin-commonjs 21.x (#5173) ([c5bfc5e](https://github.com/vitejs/vite/commit/c5bfc5e)), closes [#5173](https://github.com/vitejs/vite/issues/5173)
* fix: upgrade to launch-editor with picocolors (#6209) ([394539c](https://github.com/vitejs/vite/commit/394539c)), closes [#6209](https://github.com/vitejs/vite/issues/6209)
* fix: url constructor import asset no as url (#9399) ([122c6e7](https://github.com/vitejs/vite/commit/122c6e7)), closes [#9399](https://github.com/vitejs/vite/issues/9399)
* fix: use `hires: true` for SSR require hook source map (#6310) ([0ebeb98](https://github.com/vitejs/vite/commit/0ebeb98)), closes [#6310](https://github.com/vitejs/vite/issues/6310)
* fix: use `strip-literal` to strip string lterals (#8054) ([1ffc010](https://github.com/vitejs/vite/commit/1ffc010)), closes [#8054](https://github.com/vitejs/vite/issues/8054)
* fix: use browser field if it is not likely UMD or CJS (fixes #9445) (#9459) ([c868e64](https://github.com/vitejs/vite/commit/c868e64)), closes [#9445](https://github.com/vitejs/vite/issues/9445) [#9459](https://github.com/vitejs/vite/issues/9459)
* fix: use browser field if likely esm (fixes #9652) (#9653) ([85e387a](https://github.com/vitejs/vite/commit/85e387a)), closes [#9652](https://github.com/vitejs/vite/issues/9652) [#9653](https://github.com/vitejs/vite/issues/9653)
* fix: use browserHash for imports from node_modules (#7278) ([161f8ea](https://github.com/vitejs/vite/commit/161f8ea)), closes [#7278](https://github.com/vitejs/vite/issues/7278)
* fix: use Bun's implementation of `ws` instead of the bundled one (#13901) ([049404c](https://github.com/vitejs/vite/commit/049404c)), closes [#13901](https://github.com/vitejs/vite/issues/13901)
* fix: use cacheDir for resolveHttpsConfig (#6416) ([647168b](https://github.com/vitejs/vite/commit/647168b)), closes [#6416](https://github.com/vitejs/vite/issues/6416)
* fix: use consistent virtual module ID in module graph (#13073) ([aa1776f](https://github.com/vitejs/vite/commit/aa1776f)), closes [#13073](https://github.com/vitejs/vite/issues/13073)
* fix: use correct proxy config in preview (#7604) ([cf59005](https://github.com/vitejs/vite/commit/cf59005)), closes [#7604](https://github.com/vitejs/vite/issues/7604)
* fix: use correct publicDir in ERR_LOAD_PUBLIC_URL (#14847) ([66caef3](https://github.com/vitejs/vite/commit/66caef3)), closes [#14847](https://github.com/vitejs/vite/issues/14847)
* fix: use correct require extension to load config (#9118) ([ebf682e](https://github.com/vitejs/vite/commit/ebf682e)), closes [#9118](https://github.com/vitejs/vite/issues/9118)
* fix: use esbuild platform browser/node instead of neutral (#8714) ([a201cd4](https://github.com/vitejs/vite/commit/a201cd4)), closes [#8714](https://github.com/vitejs/vite/issues/8714)
* fix: use file extensions on type imports so they work with `moduleResolution: 'node16'` (#13947) ([aeef670](https://github.com/vitejs/vite/commit/aeef670)), closes [#13947](https://github.com/vitejs/vite/issues/13947)
* fix: use Function instead of eval to dynamically import config files (#5213) ([10694dd](https://github.com/vitejs/vite/commit/10694dd)), closes [#5213](https://github.com/vitejs/vite/issues/5213)
* fix: use global location for import.meta.url rewrite (fix #5087) (#5113) ([0b54853](https://github.com/vitejs/vite/commit/0b54853)), closes [#5087](https://github.com/vitejs/vite/issues/5087) [#5113](https://github.com/vitejs/vite/issues/5113)
* fix: use hmr port if specified (#7282) ([3ee04c0](https://github.com/vitejs/vite/commit/3ee04c0)), closes [#7282](https://github.com/vitejs/vite/issues/7282)
* fix: use isOptimizable to ensure version query (#10141) ([23a51c6](https://github.com/vitejs/vite/commit/23a51c6)), closes [#10141](https://github.com/vitejs/vite/issues/10141)
* fix: use latest module graph in transform middleware (#14892) ([b6b382c](https://github.com/vitejs/vite/commit/b6b382c)), closes [#14892](https://github.com/vitejs/vite/issues/14892)
* fix: use lax range for peer deps ([35bd963](https://github.com/vitejs/vite/commit/35bd963))
* fix: use micromatch for consistent glob matching (#5610) ([9d50df8](https://github.com/vitejs/vite/commit/9d50df8)), closes [#5610](https://github.com/vitejs/vite/issues/5610)
* fix: use nearest pkg to resolved for moduleSideEffects (#12628) ([1dfecc8](https://github.com/vitejs/vite/commit/1dfecc8)), closes [#12628](https://github.com/vitejs/vite/issues/12628)
* fix: use NODE_ENV in optimizer (#7673) ([50672e4](https://github.com/vitejs/vite/commit/50672e4)), closes [#7673](https://github.com/vitejs/vite/issues/7673)
* fix: use pkgId to get relative path (#4957) (#4961) ([b9e837a](https://github.com/vitejs/vite/commit/b9e837a)), closes [#4957](https://github.com/vitejs/vite/issues/4957) [#4961](https://github.com/vitejs/vite/issues/4961)
* fix: use realpathSync for node <16.18 on windows (#12971) ([965839c](https://github.com/vitejs/vite/commit/965839c)), closes [#12971](https://github.com/vitejs/vite/issues/12971)
* fix: use relative path for sources field (#14247) ([a995907](https://github.com/vitejs/vite/commit/a995907)), closes [#14247](https://github.com/vitejs/vite/issues/14247)
* fix: use relative paths in _metadata.json (#7299) ([8b945f5](https://github.com/vitejs/vite/commit/8b945f5)), closes [#7299](https://github.com/vitejs/vite/issues/7299)
* fix: use relative paths in `sources` for transformed source maps (#12079) ([bcbc582](https://github.com/vitejs/vite/commit/bcbc582)), closes [#12079](https://github.com/vitejs/vite/issues/12079)
* fix: use string manipulation instead of regex to inject esbuild helpers (#14094) ([91a18c2](https://github.com/vitejs/vite/commit/91a18c2)), closes [#14094](https://github.com/vitejs/vite/issues/14094)
* fix: use the same `target` for optimized dependencies and source files (#5095) ([8456a6f](https://github.com/vitejs/vite/commit/8456a6f)), closes [#5095](https://github.com/vitejs/vite/issues/5095) [#4897](https://github.com/vitejs/vite/issues/4897)
* fix: use Vitest for unit testing, clean regex bug (#8040) ([63cd53d](https://github.com/vitejs/vite/commit/63cd53d)), closes [#8040](https://github.com/vitejs/vite/issues/8040)
* fix: virtual html sourcemap warning (#7440) ([476786b](https://github.com/vitejs/vite/commit/476786b)), closes [#7440](https://github.com/vitejs/vite/issues/7440)
* fix: Vite cannot load configuration files in the link directory (#4180) (#4181) ([a3fa1a3](https://github.com/vitejs/vite/commit/a3fa1a3)), closes [#4180](https://github.com/vitejs/vite/issues/4180) [#4181](https://github.com/vitejs/vite/issues/4181)
* fix: vite client types (#7877) ([0e67fe8](https://github.com/vitejs/vite/commit/0e67fe8)), closes [#7877](https://github.com/vitejs/vite/issues/7877)
* fix: Vite module graph race condition (#5470) ([70fd32c](https://github.com/vitejs/vite/commit/70fd32c)), closes [#5470](https://github.com/vitejs/vite/issues/5470)
* fix: vitepress/theme in ssrExternals (#5651) ([1f91cdb](https://github.com/vitejs/vite/commit/1f91cdb)), closes [#5651](https://github.com/vitejs/vite/issues/5651)
* fix: warn for unresolved css in html (#7911) ([2b58cb3](https://github.com/vitejs/vite/commit/2b58cb3)), closes [#7911](https://github.com/vitejs/vite/issues/7911)
* fix: warn on build when bundling code that uses nodejs built in module (#12616) ([72050f9](https://github.com/vitejs/vite/commit/72050f9)), closes [#12616](https://github.com/vitejs/vite/issues/12616)
* fix: warn when publicDir and outDir are nested (#13742) ([4eb3154](https://github.com/vitejs/vite/commit/4eb3154)), closes [#13742](https://github.com/vitejs/vite/issues/13742)
* fix: websocket proxies not the same as http (#4893) ([9260848](https://github.com/vitejs/vite/commit/9260848)), closes [#4893](https://github.com/vitejs/vite/issues/4893)
* fix: when the file path is an absolute path, parsing causes parameter loss (#10449) ([df86990](https://github.com/vitejs/vite/commit/df86990)), closes [#10449](https://github.com/vitejs/vite/issues/10449)
* fix: windows add/delete file ([3a7b650](https://github.com/vitejs/vite/commit/3a7b650))
* fix: Windows path error on script proxying (#5556) ([f8dc1ee](https://github.com/vitejs/vite/commit/f8dc1ee)), closes [#5556](https://github.com/vitejs/vite/issues/5556)
* fix: worker match only run in js (#7500) ([9481c7d](https://github.com/vitejs/vite/commit/9481c7d)), closes [#7500](https://github.com/vitejs/vite/issues/7500)
* fix: worker relative base should use import.meta.url (#9204) ([0358b04](https://github.com/vitejs/vite/commit/0358b04)), closes [#9204](https://github.com/vitejs/vite/issues/9204)
* fix: wrongly resolve to optimized doppelganger (#11290) ([34fec41](https://github.com/vitejs/vite/commit/34fec41)), closes [#11290](https://github.com/vitejs/vite/issues/11290)
* fix: ws never connects after restarting server if server.hmr.server is set (#14127) ([bd9b749](https://github.com/vitejs/vite/commit/bd9b749)), closes [#14127](https://github.com/vitejs/vite/issues/14127)
* fix: ws types (#6083) ([1ded1a8](https://github.com/vitejs/vite/commit/1ded1a8)), closes [#6083](https://github.com/vitejs/vite/issues/6083)
* fix: yarn pnp considerBuiltins (#12903) ([a0e10d5](https://github.com/vitejs/vite/commit/a0e10d5)), closes [#12903](https://github.com/vitejs/vite/issues/12903)
* fix(analysis): warnings for dynamic imports that use static template literals (#14458) ([ec7ee22](https://github.com/vitejs/vite/commit/ec7ee22)), closes [#14458](https://github.com/vitejs/vite/issues/14458)
* fix(asset): allow non-existent url (#7306) ([6bc45a2](https://github.com/vitejs/vite/commit/6bc45a2)), closes [#7306](https://github.com/vitejs/vite/issues/7306)
* fix(asset): import assets from encodeURI(#6195) (#6199) ([4114f84](https://github.com/vitejs/vite/commit/4114f84)), closes [#6195](https://github.com/vitejs/vite/issues/6195) [#6199](https://github.com/vitejs/vite/issues/6199)
* fix(asset): respect assetFileNames if rollupOptions.output is an array (#8561) ([4e6c26f](https://github.com/vitejs/vite/commit/4e6c26f)), closes [#8561](https://github.com/vitejs/vite/issues/8561)
* fix(assetImportMetaUrl): allow ternary operator in template literal urls (#13121) ([d5d9a31](https://github.com/vitejs/vite/commit/d5d9a31)), closes [#13121](https://github.com/vitejs/vite/issues/13121)
* fix(assetImportMetaUrl): reserve dynamic template literal query params (#13034) ([7089528](https://github.com/vitejs/vite/commit/7089528)), closes [#13034](https://github.com/vitejs/vite/issues/13034)
* fix(assets): avoid splitting `,` inside base64 value of `srcset` attribute (#15422) ([8de7bd2](https://github.com/vitejs/vite/commit/8de7bd2)), closes [#15422](https://github.com/vitejs/vite/issues/15422)
* fix(assets): avoid splitting `,` inside query parameter of image URI in srcset property (#16081) ([50caf67](https://github.com/vitejs/vite/commit/50caf67)), closes [#16081](https://github.com/vitejs/vite/issues/16081)
* fix(assets): fix svg inline in css url (#14714) ([eef4aaa](https://github.com/vitejs/vite/commit/eef4aaa)), closes [#14714](https://github.com/vitejs/vite/issues/14714)
* fix(assets): make timestamp invalidation lazy (#14675) ([dd610b5](https://github.com/vitejs/vite/commit/dd610b5)), closes [#14675](https://github.com/vitejs/vite/issues/14675)
* fix(assets): use base64 when inlining SVG with foreignObject tag (#14875) ([9e20ed6](https://github.com/vitejs/vite/commit/9e20ed6)), closes [#14875](https://github.com/vitejs/vite/issues/14875)
* fix(build-import-analysis): should not append ?used when css request has ?url or ?raw (#11910) ([e3f725f](https://github.com/vitejs/vite/commit/e3f725f)), closes [#11910](https://github.com/vitejs/vite/issues/11910)
* fix(build): add crossorigin attribute to `link[rel="stylesheet"]` (#12991) ([6e7b25c](https://github.com/vitejs/vite/commit/6e7b25c)), closes [#12991](https://github.com/vitejs/vite/issues/12991)
* fix(build): allow dynamic import treeshaking when injecting preload (#14221) ([f43f71f](https://github.com/vitejs/vite/commit/f43f71f)), closes [#14221](https://github.com/vitejs/vite/issues/14221)
* fix(build): build error message output twice (#15664) ([74382b9](https://github.com/vitejs/vite/commit/74382b9)), closes [#15664](https://github.com/vitejs/vite/issues/15664)
* fix(build): build project path error (#9793) ([cc8800a](https://github.com/vitejs/vite/commit/cc8800a)), closes [#9793](https://github.com/vitejs/vite/issues/9793)
* fix(build): correctly handle warning ignore list (#12831) ([8830532](https://github.com/vitejs/vite/commit/8830532)), closes [#12831](https://github.com/vitejs/vite/issues/12831)
* fix(build): declare moduleSideEffects for vite:modulepreload-polyfill (#13099) ([d63129b](https://github.com/vitejs/vite/commit/d63129b)), closes [#13099](https://github.com/vitejs/vite/issues/13099)
* fix(build): decode urls in CSS files (fix #15109) (#15246) ([ea6a7a6](https://github.com/vitejs/vite/commit/ea6a7a6)), closes [#15109](https://github.com/vitejs/vite/issues/15109) [#15246](https://github.com/vitejs/vite/issues/15246)
* fix(build): do not output build time when build fails (#15711) ([added3e](https://github.com/vitejs/vite/commit/added3e)), closes [#15711](https://github.com/vitejs/vite/issues/15711)
* fix(build): do not repeatedly output warning message (#12910) ([251d0ab](https://github.com/vitejs/vite/commit/251d0ab)), closes [#12910](https://github.com/vitejs/vite/issues/12910)
* fix(build): do not warn when URL in CSS is externalized (#12873) ([1510996](https://github.com/vitejs/vite/commit/1510996)), closes [#12873](https://github.com/vitejs/vite/issues/12873)
* fix(build): fix chokidar.ignore override (#6317) ([aa47549](https://github.com/vitejs/vite/commit/aa47549)), closes [#6317](https://github.com/vitejs/vite/issues/6317)
* fix(build): fix resolution algorithm when `build.ssr` is true (#9989) ([7229251](https://github.com/vitejs/vite/commit/7229251)), closes [#9989](https://github.com/vitejs/vite/issues/9989)
* fix(build): fix watch crash with inline module (#6373) ([49d2f6d](https://github.com/vitejs/vite/commit/49d2f6d)), closes [#6373](https://github.com/vitejs/vite/issues/6373)
* fix(build): handle preload treeshaking for braces (#17479) ([d355568](https://github.com/vitejs/vite/commit/d355568)), closes [#17479](https://github.com/vitejs/vite/issues/17479)
* fix(build): handle preload treeshaking for commas (#17472) ([3e27071](https://github.com/vitejs/vite/commit/3e27071)), closes [#17472](https://github.com/vitejs/vite/issues/17472)
* fix(build): invalidate chunk hash when css changed (#11475) ([7a97a04](https://github.com/vitejs/vite/commit/7a97a04)), closes [#11475](https://github.com/vitejs/vite/issues/11475)
* fix(build): keep IIFE name after minifying (fix #5490) (#5715) ([1544211](https://github.com/vitejs/vite/commit/1544211)), closes [#5490](https://github.com/vitejs/vite/issues/5490) [#5715](https://github.com/vitejs/vite/issues/5715)
* fix(build): let top-level `this` refer to `globalThis` (#5312) ([7e25429](https://github.com/vitejs/vite/commit/7e25429)), closes [#5312](https://github.com/vitejs/vite/issues/5312)
* fix(build): make build error message clearer (#14761) ([350b4b2](https://github.com/vitejs/vite/commit/350b4b2)), closes [#14761](https://github.com/vitejs/vite/issues/14761)
* fix(build): make output warning message clearer (#12924) ([54ab3c8](https://github.com/vitejs/vite/commit/54ab3c8)), closes [#12924](https://github.com/vitejs/vite/issues/12924)
* fix(build): make SystemJSWrapRE match lazy (#16633) ([6583ad2](https://github.com/vitejs/vite/commit/6583ad2)), closes [#16633](https://github.com/vitejs/vite/issues/16633)
* fix(build): mixed external and transpiled srcset  (#14888) ([b5653d3](https://github.com/vitejs/vite/commit/b5653d3)), closes [#14888](https://github.com/vitejs/vite/issues/14888)
* fix(build): NODE_ENV override by .env (#6303) ([7329b24](https://github.com/vitejs/vite/commit/7329b24)), closes [#6303](https://github.com/vitejs/vite/issues/6303)
* fix(build): normalize html path (#15554) ([d0d5938](https://github.com/vitejs/vite/commit/d0d5938)), closes [#15554](https://github.com/vitejs/vite/issues/15554)
* fix(build): normalized output log (#9594) ([8bae103](https://github.com/vitejs/vite/commit/8bae103)), closes [#9594](https://github.com/vitejs/vite/issues/9594)
* fix(build): preload treeshaking ignore equal (#17480) ([6ced135](https://github.com/vitejs/vite/commit/6ced135)), closes [#17480](https://github.com/vitejs/vite/issues/17480)
* fix(build): remove warning about ineffective dynamic import from node_modules (#13884) ([33002dd](https://github.com/vitejs/vite/commit/33002dd)), closes [#13884](https://github.com/vitejs/vite/issues/13884)
* fix(build): resolve `rollupOptions.input` paths (#5601) ([5b6b016](https://github.com/vitejs/vite/commit/5b6b016)), closes [#5601](https://github.com/vitejs/vite/issues/5601)
* fix(build): silence warn dynamic import module when inlineDynamicImports true (#13970) ([7a77aaf](https://github.com/vitejs/vite/commit/7a77aaf)), closes [#13970](https://github.com/vitejs/vite/issues/13970)
* fix(build): skip preload treeshaking for nested braces (#17687) ([4be96b4](https://github.com/vitejs/vite/commit/4be96b4)), closes [#17687](https://github.com/vitejs/vite/issues/17687)
* fix(build): style insert order for UMD builds (fix #13668) (#13669) ([49a1b99](https://github.com/vitejs/vite/commit/49a1b99)), closes [#13668](https://github.com/vitejs/vite/issues/13668) [#13669](https://github.com/vitejs/vite/issues/13669)
* fix(build): use base64 for inline SVG if it contains both single and double quotes (#15271) ([1bbff16](https://github.com/vitejs/vite/commit/1bbff16)), closes [#15271](https://github.com/vitejs/vite/issues/15271)
* fix(build): use crossorigin for module preloaded ([85cab70](https://github.com/vitejs/vite/commit/85cab70))
* fix(cjs): build cjs for `loadEnv` (#8305) ([80dd2df](https://github.com/vitejs/vite/commit/80dd2df)), closes [#8305](https://github.com/vitejs/vite/issues/8305)
* fix(cli): after setting server.open, the default open is inconsistent… (#11974) ([33a38db](https://github.com/vitejs/vite/commit/33a38db)), closes [#11974](https://github.com/vitejs/vite/issues/11974)
* fix(cli): convert special base (#14283) ([34826aa](https://github.com/vitejs/vite/commit/34826aa)), closes [#14283](https://github.com/vitejs/vite/issues/14283)
* fix(cli): convert the sourcemap option to boolean (fix #13638) (#13663) ([d444bfe](https://github.com/vitejs/vite/commit/d444bfe)), closes [#13638](https://github.com/vitejs/vite/issues/13638) [#13663](https://github.com/vitejs/vite/issues/13663)
* fix(cli): ctrl+C no longer kills processes (#11434) (#11518) ([718fc1d](https://github.com/vitejs/vite/commit/718fc1d)), closes [#11434](https://github.com/vitejs/vite/issues/11434) [#11518](https://github.com/vitejs/vite/issues/11518)
* fix(cli): exit 1 on ctrl+c (#11563) ([fb77411](https://github.com/vitejs/vite/commit/fb77411)), closes [#11563](https://github.com/vitejs/vite/issues/11563)
* fix(cli): log correct hostname (#5156) ([6f977a5](https://github.com/vitejs/vite/commit/6f977a5)), closes [#5156](https://github.com/vitejs/vite/issues/5156)
* fix(cli): pass mode to optimize command (#12776) ([da38ad8](https://github.com/vitejs/vite/commit/da38ad8)), closes [#12776](https://github.com/vitejs/vite/issues/12776)
* fix(cli): reorder dev server message (#5141) ([5fb3e0f](https://github.com/vitejs/vite/commit/5fb3e0f)), closes [#5141](https://github.com/vitejs/vite/issues/5141)
* fix(cli): revert ctrl+C no longer kills processes (#11434) (#11518) (#11562) ([3748acb](https://github.com/vitejs/vite/commit/3748acb)), closes [#11434](https://github.com/vitejs/vite/issues/11434) [#11518](https://github.com/vitejs/vite/issues/11518) [#11562](https://github.com/vitejs/vite/issues/11562)
* fix(cli): when the user enters the same command (#10474) ([2326f4a](https://github.com/vitejs/vite/commit/2326f4a)), closes [#10474](https://github.com/vitejs/vite/issues/10474)
* fix(client-inject): replace globalThis.process.env.NODE_ENV (fix #12185) (#12194) ([2063648](https://github.com/vitejs/vite/commit/2063648)), closes [#12185](https://github.com/vitejs/vite/issues/12185) [#12194](https://github.com/vitejs/vite/issues/12194)
* fix(client): correctly display the config file name (#14160) ([61e801d](https://github.com/vitejs/vite/commit/61e801d)), closes [#14160](https://github.com/vitejs/vite/issues/14160)
* fix(client): fix typo in overlay config hint (#5343) ([96591bf](https://github.com/vitejs/vite/commit/96591bf)), closes [#5343](https://github.com/vitejs/vite/issues/5343)
* fix(client): serve client sources next to deployed scripts (#11865) ([63bd261](https://github.com/vitejs/vite/commit/63bd261)), closes [#11865](https://github.com/vitejs/vite/issues/11865)
* fix(client): uniform variable `location` (#17528) ([a8e2f6f](https://github.com/vitejs/vite/commit/a8e2f6f)), closes [#17528](https://github.com/vitejs/vite/issues/17528)
* fix(client): wait on the socket host, not the ping host (#6819) ([ae56e47](https://github.com/vitejs/vite/commit/ae56e47)), closes [#6819](https://github.com/vitejs/vite/issues/6819)
* fix(commonjs): expose ignoreTryCatch config option (#5555) ([d383c2a](https://github.com/vitejs/vite/commit/d383c2a)), closes [#5555](https://github.com/vitejs/vite/issues/5555)
* fix(config): add random number to temp transpiled file (#12150) ([2b2ba61](https://github.com/vitejs/vite/commit/2b2ba61)), closes [#12150](https://github.com/vitejs/vite/issues/12150)
* fix(config): don't resolve by module field (#10347) ([cc1c829](https://github.com/vitejs/vite/commit/cc1c829)), closes [#10347](https://github.com/vitejs/vite/issues/10347)
* fix(config): don't use file url for external files with cjs output (#9642) ([73ad707](https://github.com/vitejs/vite/commit/73ad707)), closes [#9642](https://github.com/vitejs/vite/issues/9642)
* fix(config): don't use module condition (`import.meta.resolve`) (fixes #10430) (#10528) ([64f19b9](https://github.com/vitejs/vite/commit/64f19b9)), closes [#10430](https://github.com/vitejs/vite/issues/10430) [#10528](https://github.com/vitejs/vite/issues/10528)
* fix(config): exclude config.assetsInclude empty array (#10941) ([18c71dc](https://github.com/vitejs/vite/commit/18c71dc)), closes [#10941](https://github.com/vitejs/vite/issues/10941)
* fix(config): improved warning when root path includes bad characters (#15761) ([1c0dc3d](https://github.com/vitejs/vite/commit/1c0dc3d)), closes [#15761](https://github.com/vitejs/vite/issues/15761)
* fix(config): merge array correctly (#6499) ([b2d972e](https://github.com/vitejs/vite/commit/b2d972e)), closes [#6499](https://github.com/vitejs/vite/issues/6499)
* fix(config): only rewrite .js loader in `loadConfigFromBundledFile` (#8556) ([2548dd3](https://github.com/vitejs/vite/commit/2548dd3)), closes [#8556](https://github.com/vitejs/vite/issues/8556)
* fix(config): partial deno support (#10446) ([c4489ea](https://github.com/vitejs/vite/commit/c4489ea)), closes [#10446](https://github.com/vitejs/vite/issues/10446)
* fix(config): resolve build options with fallback (#10645) ([f7021e3](https://github.com/vitejs/vite/commit/f7021e3)), closes [#10645](https://github.com/vitejs/vite/issues/10645)
* fix(config): resolve dynamic import as esm (#11220) ([f8c1ed0](https://github.com/vitejs/vite/commit/f8c1ed0)), closes [#11220](https://github.com/vitejs/vite/issues/11220)
* fix(config): resolve externalized specifier with internal resolver (#10683) ([b15d21c](https://github.com/vitejs/vite/commit/b15d21c))
* fix(config): resolve implicit deps as absolute path (#10254) ([ec1f3ae](https://github.com/vitejs/vite/commit/ec1f3ae)), closes [#10254](https://github.com/vitejs/vite/issues/10254)
* fix(config): server restart on config dependencies changed on windows (#7366) ([c43467a](https://github.com/vitejs/vite/commit/c43467a)), closes [#7366](https://github.com/vitejs/vite/issues/7366)
* fix(config): skip resolve builtin modules (#10420) ([ecba3f8](https://github.com/vitejs/vite/commit/ecba3f8)), closes [#10420](https://github.com/vitejs/vite/issues/10420)
* fix(config): try catch unlink after load (#9577) ([d35a1e2](https://github.com/vitejs/vite/commit/d35a1e2)), closes [#9577](https://github.com/vitejs/vite/issues/9577)
* fix(config): use file url for import path (fixes #9471) (#9473) ([22084a6](https://github.com/vitejs/vite/commit/22084a6)), closes [#9471](https://github.com/vitejs/vite/issues/9471) [#9473](https://github.com/vitejs/vite/issues/9473)
* fix(config): Warn about terserOptions in more cases (#7101) ([79428ad](https://github.com/vitejs/vite/commit/79428ad)), closes [#7101](https://github.com/vitejs/vite/issues/7101)
* fix(config): watch config even outside of root (#12321) ([7e2fff7](https://github.com/vitejs/vite/commit/7e2fff7)), closes [#12321](https://github.com/vitejs/vite/issues/12321)
* fix(config): watch envDir even outside of root (#12349) ([131f3ee](https://github.com/vitejs/vite/commit/131f3ee)), closes [#12349](https://github.com/vitejs/vite/issues/12349)
* fix(cspNonce): don't overwrite existing nonce values (#16415) ([b872635](https://github.com/vitejs/vite/commit/b872635)), closes [#16415](https://github.com/vitejs/vite/issues/16415)
* fix(css):  missing css in lib mode (#10185) ([e4c1c6d](https://github.com/vitejs/vite/commit/e4c1c6d)), closes [#10185](https://github.com/vitejs/vite/issues/10185)
* fix(css): ?inline cannot self-accept (#5433) ([d283d9b](https://github.com/vitejs/vite/commit/d283d9b)), closes [#5433](https://github.com/vitejs/vite/issues/5433)
* fix(css): @import with .css in node_modules importing a different package failed to resolve (#15000) ([8ccf722](https://github.com/vitejs/vite/commit/8ccf722)), closes [#15000](https://github.com/vitejs/vite/issues/15000)
* fix(css): `.css?url` support (#15259) ([ed56d96](https://github.com/vitejs/vite/commit/ed56d96)), closes [#15259](https://github.com/vitejs/vite/issues/15259)
* fix(css): always use css module content (#8936) ([6e0dd3a](https://github.com/vitejs/vite/commit/6e0dd3a)), closes [#8936](https://github.com/vitejs/vite/issues/8936)
* fix(css): avoid generating empty JS files when JS files becomes empty but has CSS files imported (#1 ([95fe5a7](https://github.com/vitejs/vite/commit/95fe5a7)), closes [#16078](https://github.com/vitejs/vite/issues/16078)
* fix(css): clean comments before hoist at rules (#7924) ([e48827f](https://github.com/vitejs/vite/commit/e48827f)), closes [#7924](https://github.com/vitejs/vite/issues/7924)
* fix(css): correctly set manifest source name and emit CSS file (#14945) ([28ccede](https://github.com/vitejs/vite/commit/28ccede)), closes [#14945](https://github.com/vitejs/vite/issues/14945)
* fix(css): css file emit synchronously (#12558) ([8e30025](https://github.com/vitejs/vite/commit/8e30025)), closes [#12558](https://github.com/vitejs/vite/issues/12558)
* fix(css): do not clean id when passing to postcss (fix #7822) (#7827) ([72f17f8](https://github.com/vitejs/vite/commit/72f17f8)), closes [#7822](https://github.com/vitejs/vite/issues/7822) [#7827](https://github.com/vitejs/vite/issues/7827)
* fix(css): dynamic import css in package fetches removed js (fixes #7955, #6823) (#7969) ([025eebf](https://github.com/vitejs/vite/commit/025eebf)), closes [#7955](https://github.com/vitejs/vite/issues/7955) [#6823](https://github.com/vitejs/vite/issues/6823) [#7969](https://github.com/vitejs/vite/issues/7969)
* fix(css): enhance error message for missing preprocessor dependency (#11485) ([65e5c22](https://github.com/vitejs/vite/commit/65e5c22)), closes [#11485](https://github.com/vitejs/vite/issues/11485)
* fix(css): ensure code is valid after empty css chunk imports are removed (fix #14515) (#14517) ([72f6a52](https://github.com/vitejs/vite/commit/72f6a52)), closes [#14515](https://github.com/vitejs/vite/issues/14515) [#14517](https://github.com/vitejs/vite/issues/14517)
* fix(css): ensure order of extracted CSS (#16588) ([a52ed1d](https://github.com/vitejs/vite/commit/a52ed1d)), closes [#16588](https://github.com/vitejs/vite/issues/16588)
* fix(css): escape pattern chars from base path in postcss dir-dependency messages (#7081) ([5151e74](https://github.com/vitejs/vite/commit/5151e74)), closes [#7081](https://github.com/vitejs/vite/issues/7081)
* fix(css): fix css lang regex (#11237) ([a55d0b3](https://github.com/vitejs/vite/commit/a55d0b3)), closes [#11237](https://github.com/vitejs/vite/issues/11237)
* fix(css): fix sourcemap warning in build with lightningCSS (#14871) ([11b1796](https://github.com/vitejs/vite/commit/11b1796)), closes [#14871](https://github.com/vitejs/vite/issues/14871)
* fix(css): fix stale css when reloading with hmr disabled (#10270) (#11506) ([e5807c4](https://github.com/vitejs/vite/commit/e5807c4)), closes [#10270](https://github.com/vitejs/vite/issues/10270) [#11506](https://github.com/vitejs/vite/issues/11506)
* fix(css): handle environment with browser globals (#11079) ([e92d025](https://github.com/vitejs/vite/commit/e92d025)), closes [#11079](https://github.com/vitejs/vite/issues/11079)
* fix(css): handle lightningcss compiled css in Deno (#17301) ([8e4e932](https://github.com/vitejs/vite/commit/8e4e932)), closes [#17301](https://github.com/vitejs/vite/issues/17301)
* fix(css): handle lightningcss minification in Deno (#17372) ([b3f5bd1](https://github.com/vitejs/vite/commit/b3f5bd1)), closes [#17372](https://github.com/vitejs/vite/issues/17372)
* fix(css): handle pure css chunk heuristic with special queries (#12091) ([a873af5](https://github.com/vitejs/vite/commit/a873af5)), closes [#12091](https://github.com/vitejs/vite/issues/12091)
* fix(css): handle url replacing when preprocessing with lightningcss (#17364) ([6fbb5e0](https://github.com/vitejs/vite/commit/6fbb5e0)), closes [#17364](https://github.com/vitejs/vite/issues/17364)
* fix(css): hoist charset (#7678) ([29e622c](https://github.com/vitejs/vite/commit/29e622c)), closes [#7678](https://github.com/vitejs/vite/issues/7678)
* fix(css): hoist external @import for non-split css (#8022) ([5280908](https://github.com/vitejs/vite/commit/5280908)), closes [#8022](https://github.com/vitejs/vite/issues/8022)
* fix(css): include `.css?url` in assets field of manifest (#17623) ([1465b20](https://github.com/vitejs/vite/commit/1465b20)), closes [#17623](https://github.com/vitejs/vite/issues/17623)
* fix(css): include inline css module in bundle (#7591) ([45b9273](https://github.com/vitejs/vite/commit/45b9273)), closes [#7591](https://github.com/vitejs/vite/issues/7591)
* fix(css): initialize lightningCSS targets when not using options (#14872) ([12f9230](https://github.com/vitejs/vite/commit/12f9230)), closes [#14872](https://github.com/vitejs/vite/issues/14872)
* fix(css): inject source content conditionally (#12449) ([3e665f6](https://github.com/vitejs/vite/commit/3e665f6)), closes [#12449](https://github.com/vitejs/vite/issues/12449)
* fix(css): inline css module when ssr, minify issue (fix #5471) (#7807) ([cf8a48a](https://github.com/vitejs/vite/commit/cf8a48a)), closes [#5471](https://github.com/vitejs/vite/issues/5471) [#7807](https://github.com/vitejs/vite/issues/7807)
* fix(css): insert styles in the same position (#11763) ([d2f1381](https://github.com/vitejs/vite/commit/d2f1381)), closes [#11763](https://github.com/vitejs/vite/issues/11763)
* fix(css): no emit assets in html style tag (fix #5968) (#6321) ([dc9fce1](https://github.com/vitejs/vite/commit/dc9fce1)), closes [#5968](https://github.com/vitejs/vite/issues/5968) [#6321](https://github.com/vitejs/vite/issues/6321)
* fix(css): only use files the current bundle contains (#16684) ([15a6ebb](https://github.com/vitejs/vite/commit/15a6ebb)), closes [#16684](https://github.com/vitejs/vite/issues/16684)
* fix(css): page reload was not happening with .css?raw (#16455) ([8041846](https://github.com/vitejs/vite/commit/8041846)), closes [#16455](https://github.com/vitejs/vite/issues/16455)
* fix(css): preserve dynamic import css code (fix #5348) (#7746) ([12d0cc0](https://github.com/vitejs/vite/commit/12d0cc0)), closes [#5348](https://github.com/vitejs/vite/issues/5348) [#7746](https://github.com/vitejs/vite/issues/7746)
* fix(css): remove `?direct` in id for postcss process (#10514) ([67e7bf2](https://github.com/vitejs/vite/commit/67e7bf2)), closes [#10514](https://github.com/vitejs/vite/issues/10514)
* fix(css): remove `?used` hack (fixes #6421, #8245) (#8278) ([0b25cc1](https://github.com/vitejs/vite/commit/0b25cc1)), closes [#6421](https://github.com/vitejs/vite/issues/6421) [#8245](https://github.com/vitejs/vite/issues/8245) [#8278](https://github.com/vitejs/vite/issues/8278)
* fix(css): remove css-post plugin sourcemap (#9914) ([c9521e7](https://github.com/vitejs/vite/commit/c9521e7)), closes [#9914](https://github.com/vitejs/vite/issues/9914)
* fix(css): remove pure css chunk sourcemap (#14290) ([2b80089](https://github.com/vitejs/vite/commit/2b80089)), closes [#14290](https://github.com/vitejs/vite/issues/14290)
* fix(css): render correct asset url when CSS chunk name is nested (#15154) ([ef403c0](https://github.com/vitejs/vite/commit/ef403c0)), closes [#15154](https://github.com/vitejs/vite/issues/15154)
* fix(css): reset render cache on renderStart (#14326) ([19bf0f1](https://github.com/vitejs/vite/commit/19bf0f1)), closes [#14326](https://github.com/vitejs/vite/issues/14326)
* fix(css): resolve at import from dependency basedir (#12796) ([46bdf7d](https://github.com/vitejs/vite/commit/46bdf7d)), closes [#12796](https://github.com/vitejs/vite/issues/12796)
* fix(css): respect `esbuild.charset` when minify (#13190) ([4fd35ed](https://github.com/vitejs/vite/commit/4fd35ed)), closes [#13190](https://github.com/vitejs/vite/issues/13190)
* fix(css): return deps if have no postcss plugins (#13344) ([28923fb](https://github.com/vitejs/vite/commit/28923fb)), closes [#13344](https://github.com/vitejs/vite/issues/13344)
* fix(css): revert return sourcemap in vite:css transform (#4880) (#4951) ([72cb33e](https://github.com/vitejs/vite/commit/72cb33e)), closes [#4880](https://github.com/vitejs/vite/issues/4880) [#4951](https://github.com/vitejs/vite/issues/4951)
* fix(css): should not rebase http url for less (fix: #12155) (#12195) ([9cca30d](https://github.com/vitejs/vite/commit/9cca30d)), closes [#12155](https://github.com/vitejs/vite/issues/12155) [#12195](https://github.com/vitejs/vite/issues/12195)
* fix(css): skip url replace for function calls (#15544) ([21a52e6](https://github.com/vitejs/vite/commit/21a52e6)), closes [#15544](https://github.com/vitejs/vite/issues/15544)
* fix(css): sourcemap crash with postcss (#7982) ([7f9f8f1](https://github.com/vitejs/vite/commit/7f9f8f1)), closes [#7982](https://github.com/vitejs/vite/issues/7982)
* fix(css): spread lightningcss options (#14024) ([63a4451](https://github.com/vitejs/vite/commit/63a4451)), closes [#14024](https://github.com/vitejs/vite/issues/14024)
* fix(css): spread lightningcss options (#14313) ([80c6608](https://github.com/vitejs/vite/commit/80c6608)), closes [#14313](https://github.com/vitejs/vite/issues/14313)
* fix(css): strip BOM (fixes #10043) (#10577) ([e0463bd](https://github.com/vitejs/vite/commit/e0463bd)), closes [#10043](https://github.com/vitejs/vite/issues/10043) [#10577](https://github.com/vitejs/vite/issues/10577)
* fix(css): support postcss.config.ts (#7935) ([274c10e](https://github.com/vitejs/vite/commit/274c10e)), closes [#7935](https://github.com/vitejs/vite/issues/7935)
* fix(css): track dependencies from addWatchFile for HMR (#15608) ([dfcb83d](https://github.com/vitejs/vite/commit/dfcb83d)), closes [#15608](https://github.com/vitejs/vite/issues/15608)
* fix(css): treeshake css modules (#16051) ([17d71ec](https://github.com/vitejs/vite/commit/17d71ec)), closes [#16051](https://github.com/vitejs/vite/issues/16051)
* fix(css): trim esbuild's minified css (#13893) ([7682a62](https://github.com/vitejs/vite/commit/7682a62)), closes [#13893](https://github.com/vitejs/vite/issues/13893)
* fix(css): unknown file error happened with lightningcss (#16306) ([01af308](https://github.com/vitejs/vite/commit/01af308)), closes [#16306](https://github.com/vitejs/vite/issues/16306)
* fix(css): url() with variable in sass/less (fixes #3644, #7651) (#10741) ([fa2e47f](https://github.com/vitejs/vite/commit/fa2e47f)), closes [#3644](https://github.com/vitejs/vite/issues/3644) [#7651](https://github.com/vitejs/vite/issues/7651) [#10741](https://github.com/vitejs/vite/issues/10741)
* fix(css): use `charset: 'utf8'` by default for css (#12565) ([c20a064](https://github.com/vitejs/vite/commit/c20a064)), closes [#12565](https://github.com/vitejs/vite/issues/12565)
* fix(css): use esbuild legalComments config when minifying CSS (#13661) ([2d9008e](https://github.com/vitejs/vite/commit/2d9008e)), closes [#13661](https://github.com/vitejs/vite/issues/13661)
* fix(css): use non-nested chunk name if facadeModule is not CSS file (#15155) ([811e392](https://github.com/vitejs/vite/commit/811e392)), closes [#15155](https://github.com/vitejs/vite/issues/15155)
* fix(css): use single postcss instance (#13738) ([c02fac4](https://github.com/vitejs/vite/commit/c02fac4)), closes [#13738](https://github.com/vitejs/vite/issues/13738)
* fix(css): var in image-set (#7921) ([e96b908](https://github.com/vitejs/vite/commit/e96b908)), closes [#7921](https://github.com/vitejs/vite/issues/7921)
* fix(debug): import performance from perf_hooks (#13464) ([d458ccd](https://github.com/vitejs/vite/commit/d458ccd)), closes [#13464](https://github.com/vitejs/vite/issues/13464)
* fix(debug): skip filter object args (#13098) ([d95a9af](https://github.com/vitejs/vite/commit/d95a9af)), closes [#13098](https://github.com/vitejs/vite/issues/13098)
* fix(define): allow define process.env (#15173) ([ec401da](https://github.com/vitejs/vite/commit/ec401da)), closes [#15173](https://github.com/vitejs/vite/issues/15173)
* fix(define): correctly replace same define values (#14786) ([f36fcd2](https://github.com/vitejs/vite/commit/f36fcd2)), closes [#14786](https://github.com/vitejs/vite/issues/14786)
* fix(define): correctly replace SSR in dev (#12204) ([0f6de4d](https://github.com/vitejs/vite/commit/0f6de4d)), closes [#12204](https://github.com/vitejs/vite/issues/12204)
* fix(define): inconsistent env values in build mode (#12058) ([0a50c59](https://github.com/vitejs/vite/commit/0a50c59)), closes [#12058](https://github.com/vitejs/vite/issues/12058)
* fix(define): incorrect raw expression value type in build (#13003) ([8f4cf07](https://github.com/vitejs/vite/commit/8f4cf07)), closes [#13003](https://github.com/vitejs/vite/issues/13003)
* fix(define): should not stringify vite internal env (#12120) ([73c3999](https://github.com/vitejs/vite/commit/73c3999)), closes [#12120](https://github.com/vitejs/vite/issues/12120)
* fix(define): stringify object parse error in build mode (#13600) ([71516db](https://github.com/vitejs/vite/commit/71516db)), closes [#13600](https://github.com/vitejs/vite/issues/13600)
* fix(deps): bump postcss-load-config to 3.1.0 (#5277) ([b7e8a5c](https://github.com/vitejs/vite/commit/b7e8a5c)), closes [#5277](https://github.com/vitejs/vite/issues/5277)
* fix(deps): update all non-major dependencies (#10077) ([caf00c8](https://github.com/vitejs/vite/commit/caf00c8)), closes [#10077](https://github.com/vitejs/vite/issues/10077)
* fix(deps): update all non-major dependencies (#10160) ([6233c83](https://github.com/vitejs/vite/commit/6233c83)), closes [#10160](https://github.com/vitejs/vite/issues/10160)
* fix(deps): update all non-major dependencies (#10316) ([a38b450](https://github.com/vitejs/vite/commit/a38b450)), closes [#10316](https://github.com/vitejs/vite/issues/10316)
* fix(deps): update all non-major dependencies (#10610) ([bb95467](https://github.com/vitejs/vite/commit/bb95467)), closes [#10610](https://github.com/vitejs/vite/issues/10610)
* fix(deps): update all non-major dependencies (#10804) ([f686afa](https://github.com/vitejs/vite/commit/f686afa)), closes [#10804](https://github.com/vitejs/vite/issues/10804)
* fix(deps): update all non-major dependencies (#11091) ([073a4bf](https://github.com/vitejs/vite/commit/073a4bf)), closes [#11091](https://github.com/vitejs/vite/issues/11091)
* fix(deps): update all non-major dependencies (#11846) ([5d55083](https://github.com/vitejs/vite/commit/5d55083)), closes [#11846](https://github.com/vitejs/vite/issues/11846)
* fix(deps): update all non-major dependencies (#12036) ([48150f2](https://github.com/vitejs/vite/commit/48150f2)), closes [#12036](https://github.com/vitejs/vite/issues/12036)
* fix(deps): update all non-major dependencies (#12389) ([3e60b77](https://github.com/vitejs/vite/commit/3e60b77)), closes [#12389](https://github.com/vitejs/vite/issues/12389)
* fix(deps): update all non-major dependencies (#13059) ([123ef4c](https://github.com/vitejs/vite/commit/123ef4c)), closes [#13059](https://github.com/vitejs/vite/issues/13059)
* fix(deps): update all non-major dependencies (#13488) ([bd09248](https://github.com/vitejs/vite/commit/bd09248)), closes [#13488](https://github.com/vitejs/vite/issues/13488)
* fix(deps): update all non-major dependencies (#13701) ([02c6bc3](https://github.com/vitejs/vite/commit/02c6bc3)), closes [#13701](https://github.com/vitejs/vite/issues/13701)
* fix(deps): update all non-major dependencies (#13758) ([8ead116](https://github.com/vitejs/vite/commit/8ead116)), closes [#13758](https://github.com/vitejs/vite/issues/13758)
* fix(deps): update all non-major dependencies (#13872) ([975a631](https://github.com/vitejs/vite/commit/975a631)), closes [#13872](https://github.com/vitejs/vite/issues/13872)
* fix(deps): update all non-major dependencies (#14092) ([68638f7](https://github.com/vitejs/vite/commit/68638f7)), closes [#14092](https://github.com/vitejs/vite/issues/14092)
* fix(deps): update all non-major dependencies (#14460) ([b77bff0](https://github.com/vitejs/vite/commit/b77bff0)), closes [#14460](https://github.com/vitejs/vite/issues/14460)
* fix(deps): update all non-major dependencies (#14510) ([eb204fd](https://github.com/vitejs/vite/commit/eb204fd)), closes [#14510](https://github.com/vitejs/vite/issues/14510)
* fix(deps): update all non-major dependencies (#14559) ([6868480](https://github.com/vitejs/vite/commit/6868480)), closes [#14559](https://github.com/vitejs/vite/issues/14559)
* fix(deps): update all non-major dependencies (#14635) ([21017a9](https://github.com/vitejs/vite/commit/21017a9)), closes [#14635](https://github.com/vitejs/vite/issues/14635)
* fix(deps): update all non-major dependencies (#14729) ([d5d96e7](https://github.com/vitejs/vite/commit/d5d96e7)), closes [#14729](https://github.com/vitejs/vite/issues/14729)
* fix(deps): update all non-major dependencies (#14961) ([0bb3995](https://github.com/vitejs/vite/commit/0bb3995)), closes [#14961](https://github.com/vitejs/vite/issues/14961)
* fix(deps): update all non-major dependencies (#15233) ([ad3adda](https://github.com/vitejs/vite/commit/ad3adda)), closes [#15233](https://github.com/vitejs/vite/issues/15233)
* fix(deps): update all non-major dependencies (#15304) ([bb07f60](https://github.com/vitejs/vite/commit/bb07f60)), closes [#15304](https://github.com/vitejs/vite/issues/15304)
* fix(deps): update all non-major dependencies (#15375) ([ab56227](https://github.com/vitejs/vite/commit/ab56227)), closes [#15375](https://github.com/vitejs/vite/issues/15375)
* fix(deps): update all non-major dependencies (#15603) ([109fb80](https://github.com/vitejs/vite/commit/109fb80)), closes [#15603](https://github.com/vitejs/vite/issues/15603)
* fix(deps): update all non-major dependencies (#15675) ([4d9363a](https://github.com/vitejs/vite/commit/4d9363a)), closes [#15675](https://github.com/vitejs/vite/issues/15675)
* fix(deps): update all non-major dependencies (#15803) ([e0a6ef2](https://github.com/vitejs/vite/commit/e0a6ef2)), closes [#15803](https://github.com/vitejs/vite/issues/15803)
* fix(deps): update all non-major dependencies (#15959) ([571a3fd](https://github.com/vitejs/vite/commit/571a3fd)), closes [#15959](https://github.com/vitejs/vite/issues/15959)
* fix(deps): update all non-major dependencies (#16258) ([7caef42](https://github.com/vitejs/vite/commit/7caef42)), closes [#16258](https://github.com/vitejs/vite/issues/16258)
* fix(deps): update all non-major dependencies (#16376) ([58a2938](https://github.com/vitejs/vite/commit/58a2938)), closes [#16376](https://github.com/vitejs/vite/issues/16376)
* fix(deps): update all non-major dependencies (#16488) ([2d50be2](https://github.com/vitejs/vite/commit/2d50be2)), closes [#16488](https://github.com/vitejs/vite/issues/16488)
* fix(deps): update all non-major dependencies (#16549) ([2d6a13b](https://github.com/vitejs/vite/commit/2d6a13b)), closes [#16549](https://github.com/vitejs/vite/issues/16549)
* fix(deps): update all non-major dependencies (#16603) ([6711553](https://github.com/vitejs/vite/commit/6711553)), closes [#16603](https://github.com/vitejs/vite/issues/16603)
* fix(deps): update all non-major dependencies (#16660) ([bf2f014](https://github.com/vitejs/vite/commit/bf2f014)), closes [#16660](https://github.com/vitejs/vite/issues/16660)
* fix(deps): update all non-major dependencies (#17321) ([4a89766](https://github.com/vitejs/vite/commit/4a89766)), closes [#17321](https://github.com/vitejs/vite/issues/17321)
* fix(deps): update all non-major dependencies (#17430) ([4453d35](https://github.com/vitejs/vite/commit/4453d35)), closes [#17430](https://github.com/vitejs/vite/issues/17430)
* fix(deps): update all non-major dependencies (#17494) ([bf123f2](https://github.com/vitejs/vite/commit/bf123f2)), closes [#17494](https://github.com/vitejs/vite/issues/17494)
* fix(deps): update all non-major dependencies (#17590) ([012490c](https://github.com/vitejs/vite/commit/012490c)), closes [#17590](https://github.com/vitejs/vite/issues/17590)
* fix(deps): update all non-major dependencies (#17629) ([93281b0](https://github.com/vitejs/vite/commit/93281b0)), closes [#17629](https://github.com/vitejs/vite/issues/17629)
* fix(deps): update all non-major dependencies (#4545) ([a44fd5d](https://github.com/vitejs/vite/commit/a44fd5d)), closes [#4545](https://github.com/vitejs/vite/issues/4545)
* fix(deps): update all non-major dependencies (#6782) ([e38be3e](https://github.com/vitejs/vite/commit/e38be3e)), closes [#6782](https://github.com/vitejs/vite/issues/6782)
* fix(deps): update all non-major dependencies (#7392) ([b63fc3b](https://github.com/vitejs/vite/commit/b63fc3b)), closes [#7392](https://github.com/vitejs/vite/issues/7392)
* fix(deps): update all non-major dependencies (#7668) ([485263c](https://github.com/vitejs/vite/commit/485263c)), closes [#7668](https://github.com/vitejs/vite/issues/7668)
* fix(deps): update all non-major dependencies (#8281) ([c68db4d](https://github.com/vitejs/vite/commit/c68db4d)), closes [#8281](https://github.com/vitejs/vite/issues/8281)
* fix(deps): update all non-major dependencies (#8391) ([842f995](https://github.com/vitejs/vite/commit/842f995)), closes [#8391](https://github.com/vitejs/vite/issues/8391)
* fix(deps): update all non-major dependencies (#8558) ([9a1fd4c](https://github.com/vitejs/vite/commit/9a1fd4c)), closes [#8558](https://github.com/vitejs/vite/issues/8558)
* fix(deps): update all non-major dependencies (#8802) ([a4a634d](https://github.com/vitejs/vite/commit/a4a634d)), closes [#8802](https://github.com/vitejs/vite/issues/8802)
* fix(deps): update all non-major dependencies (#9176) ([31d3b70](https://github.com/vitejs/vite/commit/31d3b70)), closes [#9176](https://github.com/vitejs/vite/issues/9176)
* fix(deps): update all non-major dependencies (#9575) ([8071325](https://github.com/vitejs/vite/commit/8071325)), closes [#9575](https://github.com/vitejs/vite/issues/9575)
* fix(deps): update all non-major dependencies (#9888) ([e35a58b](https://github.com/vitejs/vite/commit/e35a58b)), closes [#9888](https://github.com/vitejs/vite/issues/9888)
* fix(deps): update all non-major dependencies (#9985) ([855f2f0](https://github.com/vitejs/vite/commit/855f2f0)), closes [#9985](https://github.com/vitejs/vite/issues/9985)
* fix(deps): update dependency dotenv-expand to v10 (#14391) ([d6bde8b](https://github.com/vitejs/vite/commit/d6bde8b)), closes [#14391](https://github.com/vitejs/vite/issues/14391)
* fix(deps): update dependency ufo to v1 (#11372) ([4288300](https://github.com/vitejs/vite/commit/4288300)), closes [#11372](https://github.com/vitejs/vite/issues/11372)
* fix(deps): update rollup to `^2.79.1` (#10298) ([2266d83](https://github.com/vitejs/vite/commit/2266d83)), closes [#10298](https://github.com/vitejs/vite/issues/10298)
* fix(deps): update sirv to 2.0.3 (#13057) ([d814d6c](https://github.com/vitejs/vite/commit/d814d6c)), closes [#13057](https://github.com/vitejs/vite/issues/13057)
* fix(dev): avoid FOUC when swapping out link tag (fix #7973) (#8495) ([0e5c009](https://github.com/vitejs/vite/commit/0e5c009)), closes [#7973](https://github.com/vitejs/vite/issues/7973) [#8495](https://github.com/vitejs/vite/issues/8495)
* fix(dev): bind plugin context functions (#14569) ([cb3243c](https://github.com/vitejs/vite/commit/cb3243c)), closes [#14569](https://github.com/vitejs/vite/issues/14569)
* fix(dev): build.ssr is set during dev, fix #9134 (#9187) ([99b0e67](https://github.com/vitejs/vite/commit/99b0e67)), closes [#9134](https://github.com/vitejs/vite/issues/9134) [#9187](https://github.com/vitejs/vite/issues/9187)
* fix(dev): Fix infinite recursion on query imports (#5671) (#5674) ([bce4e56](https://github.com/vitejs/vite/commit/bce4e56)), closes [#5671](https://github.com/vitejs/vite/issues/5671) [#5674](https://github.com/vitejs/vite/issues/5674)
* fix(dev): prevent stripping query params from CSS in HMR (#6589) ([3ab96c6](https://github.com/vitejs/vite/commit/3ab96c6)), closes [#6589](https://github.com/vitejs/vite/issues/6589)
* fix(dev): read property of undefined (#5177) ([70e882f](https://github.com/vitejs/vite/commit/70e882f)), closes [#5177](https://github.com/vitejs/vite/issues/5177)
* fix(dev): watch publicDir explicitly to include it outside the root (#16502) ([4d83eb5](https://github.com/vitejs/vite/commit/4d83eb5)), closes [#16502](https://github.com/vitejs/vite/issues/16502)
* fix(dynamic-import-vars): preserve custom query string (#14459) ([1f2a982](https://github.com/vitejs/vite/commit/1f2a982)), closes [#14459](https://github.com/vitejs/vite/issues/14459)
* fix(env): compatible with env variables ended with unescaped $ (#12031) ([05b3df0](https://github.com/vitejs/vite/commit/05b3df0)), closes [#12031](https://github.com/vitejs/vite/issues/12031)
* fix(env): prevent env expand on process.env (#11213) ([d4a1e2b](https://github.com/vitejs/vite/commit/d4a1e2b)), closes [#11213](https://github.com/vitejs/vite/issues/11213)
* fix(env): test NODE_ENV override before expand (#11309) ([d0a9281](https://github.com/vitejs/vite/commit/d0a9281)), closes [#11309](https://github.com/vitejs/vite/issues/11309)
* fix(error-logging): rollup errors weren't displaying id and codeframe (#16540) ([22dc196](https://github.com/vitejs/vite/commit/22dc196)), closes [#16540](https://github.com/vitejs/vite/issues/16540)
* fix(esbuild): always support dynamic import and import meta (#9105) ([57a7936](https://github.com/vitejs/vite/commit/57a7936)), closes [#9105](https://github.com/vitejs/vite/issues/9105)
* fix(esbuild): avoid polluting global namespace while minify is false (#11882) ([c895379](https://github.com/vitejs/vite/commit/c895379)), closes [#11882](https://github.com/vitejs/vite/issues/11882)
* fix(esbuild): check server before reload tsconfig (#11747) ([c56b954](https://github.com/vitejs/vite/commit/c56b954)), closes [#11747](https://github.com/vitejs/vite/issues/11747)
* fix(esbuild): enable experimentalDecorators by default (#13805) ([e8880f0](https://github.com/vitejs/vite/commit/e8880f0)), closes [#13805](https://github.com/vitejs/vite/issues/13805)
* fix(esbuild): fix static properties transpile when useDefineForClassFields false (#13992) ([4ca7c13](https://github.com/vitejs/vite/commit/4ca7c13)), closes [#13992](https://github.com/vitejs/vite/issues/13992)
* fix(esbuild): handle inline sourcemap option (#11120) ([4c85c0a](https://github.com/vitejs/vite/commit/4c85c0a)), closes [#11120](https://github.com/vitejs/vite/issues/11120)
* fix(esbuild): handle tsconfck cache undefined (#14650) ([4e763c5](https://github.com/vitejs/vite/commit/4e763c5)), closes [#14650](https://github.com/vitejs/vite/issues/14650)
* fix(esbuild): preserve import.meta even if esbuild.target is set to lower versions (#16151) ([6f77b2b](https://github.com/vitejs/vite/commit/6f77b2b)), closes [#16151](https://github.com/vitejs/vite/issues/16151)
* fix(esbuild): respect esbuild config on build (#5538) ([ff05fe9](https://github.com/vitejs/vite/commit/ff05fe9)), closes [#5538](https://github.com/vitejs/vite/issues/5538)
* fix(esbuild): set js loader for build transpile (#14980) ([80beede](https://github.com/vitejs/vite/commit/80beede)), closes [#14980](https://github.com/vitejs/vite/issues/14980)
* fix(esbuild): transpile with esnext in dev (#10207) ([43b7b78](https://github.com/vitejs/vite/commit/43b7b78)), closes [#10207](https://github.com/vitejs/vite/issues/10207)
* fix(esbuild): umd helper insert into wrong position in lib mode (#11988) ([86bc243](https://github.com/vitejs/vite/commit/86bc243)), closes [#11988](https://github.com/vitejs/vite/issues/11988)
* fix(esbuild): update to tsconfck 3.0.1 to fix edge cases when resolving tsconfig.extends (#15502) ([1fcebeb](https://github.com/vitejs/vite/commit/1fcebeb)), closes [#15502](https://github.com/vitejs/vite/issues/15502)
* fix(esbuild): update tsconfck to fix bug that could cause a deadlock  (#16124) ([fd9de04](https://github.com/vitejs/vite/commit/fd9de04)), closes [#16124](https://github.com/vitejs/vite/issues/16124)
* fix(esbuild): use `useDefineForClassFields: false` when no `compilerOptions.target` is declared (#13 ([7ef2472](https://github.com/vitejs/vite/commit/7ef2472)), closes [#13708](https://github.com/vitejs/vite/issues/13708)
* fix(glob): css imports injecting a ?used query to export the css string (#6949) ([0b3f4ef](https://github.com/vitejs/vite/commit/0b3f4ef)), closes [#6949](https://github.com/vitejs/vite/issues/6949)
* fix(glob): handle glob prop access (#9281) ([0580215](https://github.com/vitejs/vite/commit/0580215)), closes [#9281](https://github.com/vitejs/vite/issues/9281)
* fix(glob): properly handles tailing comma (#8181) ([462be8e](https://github.com/vitejs/vite/commit/462be8e)), closes [#8181](https://github.com/vitejs/vite/issues/8181)
* fix(glob): server perf when globbing huge dirs (#9425) ([156a3a4](https://github.com/vitejs/vite/commit/156a3a4)), closes [#9425](https://github.com/vitejs/vite/issues/9425)
* fix(glob): support static template literals (#9352) ([183c6fb](https://github.com/vitejs/vite/commit/183c6fb)), closes [#9352](https://github.com/vitejs/vite/issues/9352)
* fix(glob): trigger HMR for glob in a  package (#14117) ([86cbf69](https://github.com/vitejs/vite/commit/86cbf69)), closes [#14117](https://github.com/vitejs/vite/issues/14117)
* fix(glob): wrap glob compile output in function invocation (#3682) ([bb603d3](https://github.com/vitejs/vite/commit/bb603d3)), closes [#3682](https://github.com/vitejs/vite/issues/3682)
* fix(hmr): __HMR_PORT__ should not be `'undefined'` (#8761) ([3271266](https://github.com/vitejs/vite/commit/3271266)), closes [#8761](https://github.com/vitejs/vite/issues/8761)
* fix(hmr): `package.json` change should trigger server restart (#15519) ([260ebbf](https://github.com/vitejs/vite/commit/260ebbf)), closes [#15519](https://github.com/vitejs/vite/issues/15519)
* fix(hmr): add timestamp for assets in dev (#13371) ([40ee245](https://github.com/vitejs/vite/commit/40ee245)), closes [#13371](https://github.com/vitejs/vite/issues/13371)
* fix(hmr): base default protocol on client source location (#11497) ([167753d](https://github.com/vitejs/vite/commit/167753d)), closes [#11497](https://github.com/vitejs/vite/issues/11497)
* fix(hmr): call dispose before prune (#15782) ([57628dc](https://github.com/vitejs/vite/commit/57628dc)), closes [#15782](https://github.com/vitejs/vite/issues/15782)
* fix(hmr): cannot reload after missing import on server startup (#9534) (#10602) ([ee7c28a](https://github.com/vitejs/vite/commit/ee7c28a)), closes [#9534](https://github.com/vitejs/vite/issues/9534) [#10602](https://github.com/vitejs/vite/issues/10602)
* fix(hmr): catch thrown errors when connecting to hmr websocket (#7111) ([4bc9284](https://github.com/vitejs/vite/commit/4bc9284)), closes [#7111](https://github.com/vitejs/vite/issues/7111)
* fix(hmr): clean importers in module graph when file is deleted (#14315) ([7acb016](https://github.com/vitejs/vite/commit/7acb016)), closes [#14315](https://github.com/vitejs/vite/issues/14315)
* fix(hmr): client pinging behind a proxy on websocket disconnect (fix #4501) (#5466) ([96573db](https://github.com/vitejs/vite/commit/96573db)), closes [#4501](https://github.com/vitejs/vite/issues/4501) [#5466](https://github.com/vitejs/vite/issues/5466)
* fix(hmr): dedupe virtual modules in module graph (#10144) ([71f08e7](https://github.com/vitejs/vite/commit/71f08e7)), closes [#10144](https://github.com/vitejs/vite/issues/10144)
* fix(hmr): dev mode reduce unnecessary restart (#14426) ([6f9d39d](https://github.com/vitejs/vite/commit/6f9d39d)), closes [#14426](https://github.com/vitejs/vite/issues/14426)
* fix(hmr): don't consider CSS dep as a circular dep (#15229) ([5f2cdec](https://github.com/vitejs/vite/commit/5f2cdec)), closes [#15229](https://github.com/vitejs/vite/issues/15229)
* fix(hmr): don't mutate module graph when collecting modules (#16302) ([dfffea1](https://github.com/vitejs/vite/commit/dfffea1)), closes [#16302](https://github.com/vitejs/vite/issues/16302)
* fix(hmr): duplicate link tags (#9697) ([9aa9515](https://github.com/vitejs/vite/commit/9aa9515)), closes [#9697](https://github.com/vitejs/vite/issues/9697)
* fix(hmr): duplicated modules because of query params mismatch (fixes #2255) (#9773) ([86bf776](https://github.com/vitejs/vite/commit/86bf776)), closes [#2255](https://github.com/vitejs/vite/issues/2255) [#9773](https://github.com/vitejs/vite/issues/9773)
* fix(hmr): handle virtual module update (#10324) ([7c4accb](https://github.com/vitejs/vite/commit/7c4accb)), closes [#10324](https://github.com/vitejs/vite/issues/10324)
* fix(hmr): hmr style tag no support in html (#7052) ([a9dfce3](https://github.com/vitejs/vite/commit/a9dfce3)), closes [#7052](https://github.com/vitejs/vite/issues/7052)
* fix(hmr): hmr style tag no support in html (#7262) ([fae120a](https://github.com/vitejs/vite/commit/fae120a)), closes [#7262](https://github.com/vitejs/vite/issues/7262)
* fix(hmr): hmr websocket failure for custom middleware mode with server.hmr.server (#11487) ([00919bb](https://github.com/vitejs/vite/commit/00919bb)), closes [#11487](https://github.com/vitejs/vite/issues/11487)
* fix(hmr): make watcher ignore build.outDir (#15326) ([2836276](https://github.com/vitejs/vite/commit/2836276)), closes [#15326](https://github.com/vitejs/vite/issues/15326)
* fix(hmr): multiple updates happened when invalidate is called while multiple tabs open (#16307) ([21cc10b](https://github.com/vitejs/vite/commit/21cc10b)), closes [#16307](https://github.com/vitejs/vite/issues/16307)
* fix(hmr): normalize env files path (#15584) ([d0f1d2e](https://github.com/vitejs/vite/commit/d0f1d2e)), closes [#15584](https://github.com/vitejs/vite/issues/15584)
* fix(hmr): normalize the path info (#14255) ([6a085d0](https://github.com/vitejs/vite/commit/6a085d0)), closes [#14255](https://github.com/vitejs/vite/issues/14255)
* fix(hmr): only invalidate `lastHMRTimestamp` of importers if the invalidated module is not a HMR bou ([1143e0b](https://github.com/vitejs/vite/commit/1143e0b)), closes [#13024](https://github.com/vitejs/vite/issues/13024)
* fix(hmr): pass id in `parseImports` for better debugging DX (#15707) ([fb4bddc](https://github.com/vitejs/vite/commit/fb4bddc)), closes [#15707](https://github.com/vitejs/vite/issues/15707)
* fix(hmr): prevent SSR from setting `isSelfAccepting` to false (#5377) ([37e5617](https://github.com/vitejs/vite/commit/37e5617)), closes [#5377](https://github.com/vitejs/vite/issues/5377)
* fix(hmr): propagate `fs.stat` failure for `hmrContext.read` (#15568) ([c6d240b](https://github.com/vitejs/vite/commit/c6d240b)), closes [#15568](https://github.com/vitejs/vite/issues/15568)
* fix(hmr): revert early break from handleHotUpdate loop (#5536) ([4abade6](https://github.com/vitejs/vite/commit/4abade6)), closes [#5536](https://github.com/vitejs/vite/issues/5536)
* fix(hmr): set isSelfAccepting unless it is delayed (#8898) ([ae34565](https://github.com/vitejs/vite/commit/ae34565)), closes [#8898](https://github.com/vitejs/vite/issues/8898)
* fix(hmr): trigger hmr for missing file import errored module after file creation (#16303) ([ffedc06](https://github.com/vitejs/vite/commit/ffedc06)), closes [#16303](https://github.com/vitejs/vite/issues/16303)
* fix(hmr): trigger page reload when calling invalidate on root module (#16636) ([2b61cc3](https://github.com/vitejs/vite/commit/2b61cc3)), closes [#16636](https://github.com/vitejs/vite/issues/16636)
* fix(html): allow self closing on non-void elements (#10478) ([29292af](https://github.com/vitejs/vite/commit/29292af)), closes [#10478](https://github.com/vitejs/vite/issues/10478)
* fix(html): build mode ignore html define transform (#6663) ([79dd003](https://github.com/vitejs/vite/commit/79dd003)), closes [#6663](https://github.com/vitejs/vite/issues/6663)
* fix(html): dont pretransform public scripts (#12650) ([4f0af3f](https://github.com/vitejs/vite/commit/4f0af3f)), closes [#12650](https://github.com/vitejs/vite/issues/12650)
* fix(html): empty script (#6057) ([1487223](https://github.com/vitejs/vite/commit/1487223)), closes [#6057](https://github.com/vitejs/vite/issues/6057)
* fix(html): handle attrs with prefix (fixes #10337) (#10381) ([7b4d6e8](https://github.com/vitejs/vite/commit/7b4d6e8)), closes [#10337](https://github.com/vitejs/vite/issues/10337) [#10381](https://github.com/vitejs/vite/issues/10381)
* fix(html): handle offset magic-string slice error (#15435) ([5ea9edb](https://github.com/vitejs/vite/commit/5ea9edb)), closes [#15435](https://github.com/vitejs/vite/issues/15435)
* fix(html): ignore rewrite external urls (#14774) ([d6d1ef1](https://github.com/vitejs/vite/commit/d6d1ef1)), closes [#14774](https://github.com/vitejs/vite/issues/14774)
* fix(html): import expression in classic script for dev (#14595) ([ea47b8f](https://github.com/vitejs/vite/commit/ea47b8f)), closes [#14595](https://github.com/vitejs/vite/issues/14595)
* fix(html): inline style attribute not working in dev (#14592) ([a4a17b8](https://github.com/vitejs/vite/commit/a4a17b8)), closes [#14592](https://github.com/vitejs/vite/issues/14592)
* fix(html): move importmap before module scripts (#9392) ([b386fba](https://github.com/vitejs/vite/commit/b386fba)), closes [#9392](https://github.com/vitejs/vite/issues/9392)
* fix(html): public asset urls always being treated as paths (fix #11857) (#11870) ([46d1352](https://github.com/vitejs/vite/commit/46d1352)), closes [#11857](https://github.com/vitejs/vite/issues/11857) [#11870](https://github.com/vitejs/vite/issues/11870)
* fix(html): relative paths without leading dot wasn't rewritten (#14591) ([0a38e3b](https://github.com/vitejs/vite/commit/0a38e3b)), closes [#14591](https://github.com/vitejs/vite/issues/14591)
* fix(html): respect disable modulepreload (#12111) ([6c50119](https://github.com/vitejs/vite/commit/6c50119)), closes [#12111](https://github.com/vitejs/vite/issues/12111)
* fix(html): rewrite assets url in `<noscript>` (#11764) ([1dba285](https://github.com/vitejs/vite/commit/1dba285)), closes [#11764](https://github.com/vitejs/vite/issues/11764)
* fix(html): show error overlay when parsing invalid file (#6184) ([1f945f6](https://github.com/vitejs/vite/commit/1f945f6)), closes [#6184](https://github.com/vitejs/vite/issues/6184)
* fix(html): skip inlining icon and manifest links (#14958) ([8ad81b4](https://github.com/vitejs/vite/commit/8ad81b4)), closes [#14958](https://github.com/vitejs/vite/issues/14958)
* fix(html): srcset pointing image in public dir wasn't working during dev (#14663) ([4496ae7](https://github.com/vitejs/vite/commit/4496ae7)), closes [#14663](https://github.com/vitejs/vite/issues/14663)
* fix(html): support `import.meta.env` define replacement without quotes (#13425) ([883089c](https://github.com/vitejs/vite/commit/883089c)), closes [#13425](https://github.com/vitejs/vite/issues/13425)
* fix(html): tags prepend doctype regex (#5315) ([256b2bb](https://github.com/vitejs/vite/commit/256b2bb)), closes [#5315](https://github.com/vitejs/vite/issues/5315)
* fix(html): transform relative path with long base in /index.html (#10990) ([752740c](https://github.com/vitejs/vite/commit/752740c)), closes [#10990](https://github.com/vitejs/vite/issues/10990)
* fix(import-analysis): escape quotes (#9729) ([21515f1](https://github.com/vitejs/vite/commit/21515f1)), closes [#9729](https://github.com/vitejs/vite/issues/9729)
* fix(import-analysis): escape quotes correctly (#12688) ([1638ebd](https://github.com/vitejs/vite/commit/1638ebd)), closes [#12688](https://github.com/vitejs/vite/issues/12688)
* fix(import-analysis): improve error for jsx to not be preserve in tsconfig (#12018) ([91fac1c](https://github.com/vitejs/vite/commit/91fac1c)), closes [#12018](https://github.com/vitejs/vite/issues/12018)
* fix(import-analysis): preserve importedUrls import order (#14465) ([99b0645](https://github.com/vitejs/vite/commit/99b0645)), closes [#14465](https://github.com/vitejs/vite/issues/14465)
* fix(importAnalysis): skip encode in ssr (#16213) ([e4d2d60](https://github.com/vitejs/vite/commit/e4d2d60)), closes [#16213](https://github.com/vitejs/vite/issues/16213)
* fix(importAnalysis): strip url base before passing as safeModulePaths (#13712) ([1ab06a8](https://github.com/vitejs/vite/commit/1ab06a8)), closes [#13712](https://github.com/vitejs/vite/issues/13712)
* fix(importAnalysis): warning on ExportAllDeclaration (#12799) ([5136b9b](https://github.com/vitejs/vite/commit/5136b9b)), closes [#12799](https://github.com/vitejs/vite/issues/12799)
* fix(importAnalysisBuild): support parsing '__VITE_PRELOAD__' (#13023) ([447df7c](https://github.com/vitejs/vite/commit/447df7c)), closes [#13023](https://github.com/vitejs/vite/issues/13023)
* fix(importGlob): don't warn when CSS default import is not used (#11121) ([97f8b4d](https://github.com/vitejs/vite/commit/97f8b4d)), closes [#11121](https://github.com/vitejs/vite/issues/11121)
* fix(importGlob): preserve line count for sourcemap (#11122) ([14980a1](https://github.com/vitejs/vite/commit/14980a1)), closes [#11122](https://github.com/vitejs/vite/issues/11122)
* fix(importGlob): warn on default import css (#11103) ([fc0d9e3](https://github.com/vitejs/vite/commit/fc0d9e3)), closes [#11103](https://github.com/vitejs/vite/issues/11103)
* fix(importMetaGlob): avoid unnecessary hmr of negative glob (#13646) ([844451c](https://github.com/vitejs/vite/commit/844451c)), closes [#13646](https://github.com/vitejs/vite/issues/13646)
* fix(indexHtml): decode html URI (#13581) ([f8868af](https://github.com/vitejs/vite/commit/f8868af)), closes [#13581](https://github.com/vitejs/vite/issues/13581)
* fix(json): load json module error (#6352) ([c8a7ea8](https://github.com/vitejs/vite/commit/c8a7ea8)), closes [#6352](https://github.com/vitejs/vite/issues/6352)
* fix(legacy): error in build with --watch and manifest enabled (#14450) ([b9ee620](https://github.com/vitejs/vite/commit/b9ee620)), closes [#14450](https://github.com/vitejs/vite/issues/14450)
* fix(legacy): fix conflict with the modern build on css emitting (#6584) ([f48255e](https://github.com/vitejs/vite/commit/f48255e)), closes [#6584](https://github.com/vitejs/vite/issues/6584) [#3296](https://github.com/vitejs/vite/issues/3296) [#3317](https://github.com/vitejs/vite/issues/3317) [/github.com/vitejs/vite/commit/6bce1081991501f3779bff1a81e5dd1e63e5d38e#diff-2cfbd4f4d8c32727cd8e1a561cffbde0b384a3ce0789340440e144f9d64c10f6R262-R263](https://github.com//github.com/vitejs/vite/commit/6bce1081991501f3779bff1a81e5dd1e63e5d38e/issues/diff-2cfbd4f4d8c32727cd8e1a561cffbde0b384a3ce0789340440e144f9d64c10f6R262-R263)
* fix(legacy): restore entry chunk CSS inlining, reverts #9761 (#10496) ([9cc808e](https://github.com/vitejs/vite/commit/9cc808e)), closes [#9761](https://github.com/vitejs/vite/issues/9761) [#10496](https://github.com/vitejs/vite/issues/10496)
* fix(legacy): style insert order (#13266) ([e444375](https://github.com/vitejs/vite/commit/e444375)), closes [#13266](https://github.com/vitejs/vite/issues/13266)
* fix(less): empty less file error (#7412) ([0535c70](https://github.com/vitejs/vite/commit/0535c70)), closes [#7412](https://github.com/vitejs/vite/issues/7412)
* fix(less): handles rewriting relative paths passed Less's `data-uri` function. (#7400) ([08e39b7](https://github.com/vitejs/vite/commit/08e39b7)), closes [#7400](https://github.com/vitejs/vite/issues/7400)
* fix(lexGlobPattern): edge case of glob import (#6022) ([d4c5cff](https://github.com/vitejs/vite/commit/d4c5cff)), closes [#6022](https://github.com/vitejs/vite/issues/6022)
* fix(lib-mode): do not minify lib mode es output ([06d86e4](https://github.com/vitejs/vite/commit/06d86e4)), closes [/github.com/vuejs/vue-next/issues/2860#issuecomment-926882793](https://github.com//github.com/vuejs/vue-next/issues/2860/issues/issuecomment-926882793)
* fix(lib): enable inlineDynamicImports for umd and iife (#8126) ([272a252](https://github.com/vitejs/vite/commit/272a252)), closes [#8126](https://github.com/vitejs/vite/issues/8126)
* fix(lib): esbuild helper functions injection not working with named exports (#14539) ([5004d00](https://github.com/vitejs/vite/commit/5004d00)), closes [#14539](https://github.com/vitejs/vite/issues/14539)
* fix(lib): remove pure CSS dynamic import (#17601) ([055f1c1](https://github.com/vitejs/vite/commit/055f1c1)), closes [#17601](https://github.com/vitejs/vite/issues/17601)
* fix(lib): respect `rollupOptions.input` in lib mode (#10116) ([c948e7d](https://github.com/vitejs/vite/commit/c948e7d)), closes [#10116](https://github.com/vitejs/vite/issues/10116)
* fix(lib): use proper extension (#6827) ([34df307](https://github.com/vitejs/vite/commit/34df307)), closes [#6827](https://github.com/vitejs/vite/issues/6827)
* fix(logger): no sameCount if clearScreen is false (#5648) ([afd6b6d](https://github.com/vitejs/vite/commit/afd6b6d)), closes [#5648](https://github.com/vitejs/vite/issues/5648)
* fix(logger): truncate log over 5000 characters long (#16581) ([b0b839a](https://github.com/vitejs/vite/commit/b0b839a)), closes [#16581](https://github.com/vitejs/vite/issues/16581)
* fix(manifest): include assets referenced in html (#14657) ([f627b91](https://github.com/vitejs/vite/commit/f627b91)), closes [#14657](https://github.com/vitejs/vite/issues/14657)
* fix(manifest): preserve pure css chunk assets (#14297) ([4bf31e5](https://github.com/vitejs/vite/commit/4bf31e5)), closes [#14297](https://github.com/vitejs/vite/issues/14297)
* fix(mergeConfig): don't accept callback config (#13135) ([998512b](https://github.com/vitejs/vite/commit/998512b)), closes [#13135](https://github.com/vitejs/vite/issues/13135)
* fix(metadata): expose viteMetadata type (#11511) ([32dee3c](https://github.com/vitejs/vite/commit/32dee3c)), closes [#11511](https://github.com/vitejs/vite/issues/11511)
* fix(mpa): support mpa fallback (#10985) ([61165f0](https://github.com/vitejs/vite/commit/61165f0)), closes [#10985](https://github.com/vitejs/vite/issues/10985)
* fix(node): remove timestamp query of `staticImportedUrls` (#15663) ([6c4bf26](https://github.com/vitejs/vite/commit/6c4bf26)), closes [#15663](https://github.com/vitejs/vite/issues/15663)
* fix(optimize-deps): don't externalize JS files imported with asset extensions (#16242) ([4161843](https://github.com/vitejs/vite/commit/4161843)), closes [#16242](https://github.com/vitejs/vite/issues/16242)
* fix(optimizer): # symbol in deps id stripped by browser (#12415) ([e23f690](https://github.com/vitejs/vite/commit/e23f690)), closes [#12415](https://github.com/vitejs/vite/issues/12415)
* fix(optimizer): add missing keys to hash (#7189) ([b0c0efe](https://github.com/vitejs/vite/commit/b0c0efe)), closes [#7189](https://github.com/vitejs/vite/issues/7189)
* fix(optimizer): avoid double-commit of optimized deps when discovery is disabled (#13865) ([df77991](https://github.com/vitejs/vite/commit/df77991)), closes [#13865](https://github.com/vitejs/vite/issues/13865)
* fix(optimizer): browser field bare import (fix #7599) (#10314) ([cba13e8](https://github.com/vitejs/vite/commit/cba13e8)), closes [#7599](https://github.com/vitejs/vite/issues/7599) [#10314](https://github.com/vitejs/vite/issues/10314)
* fix(optimizer): browser mapping for yarn pnp (#6493) ([c1c7af3](https://github.com/vitejs/vite/commit/c1c7af3)), closes [#6493](https://github.com/vitejs/vite/issues/6493)
* fix(optimizer): check .vite/deps directory existence before removing (#11499) ([1b043f9](https://github.com/vitejs/vite/commit/1b043f9)), closes [#11499](https://github.com/vitejs/vite/issues/11499)
* fix(optimizer): define crawlDeps after scanProcessing and optimizationResult are complete (fix #1428 ([c5f6558](https://github.com/vitejs/vite/commit/c5f6558)), closes [#14284](https://github.com/vitejs/vite/issues/14284) [#14285](https://github.com/vitejs/vite/issues/14285)
* fix(optimizer): don not call context.rebuild after cancel (#12264) ([520d84e](https://github.com/vitejs/vite/commit/520d84e)), closes [#12264](https://github.com/vitejs/vite/issues/12264)
* fix(optimizer): enable experimentalDecorators by default (#13981) ([f8a5ffc](https://github.com/vitejs/vite/commit/f8a5ffc)), closes [#13981](https://github.com/vitejs/vite/issues/13981)
* fix(optimizer): encode `_` and `.` in different way (#8508) ([9065b37](https://github.com/vitejs/vite/commit/9065b37)), closes [#8508](https://github.com/vitejs/vite/issues/8508)
* fix(optimizer): escape entrypoints when running scanner (#11250) ([b61894e](https://github.com/vitejs/vite/commit/b61894e)), closes [#11250](https://github.com/vitejs/vite/issues/11250)
* fix(optimizer): external require-import conversion (fixes #2492, #3409) (#8459) ([1061bbd](https://github.com/vitejs/vite/commit/1061bbd)), closes [#2492](https://github.com/vitejs/vite/issues/2492) [#3409](https://github.com/vitejs/vite/issues/3409) [#8459](https://github.com/vitejs/vite/issues/8459)
* fix(optimizer): fix `optimizeDeps.include` glob syntax for `./*` exports (#16230) ([f184c80](https://github.com/vitejs/vite/commit/f184c80)), closes [#16230](https://github.com/vitejs/vite/issues/16230)
* fix(optimizer): ignore EACCES errors while scanner (fixes #8916) (#9509) ([4e6a77f](https://github.com/vitejs/vite/commit/4e6a77f)), closes [#8916](https://github.com/vitejs/vite/issues/8916) [#9509](https://github.com/vitejs/vite/issues/9509)
* fix(optimizer): include exports for css modules (#13519) ([1fd9919](https://github.com/vitejs/vite/commit/1fd9919)), closes [#13519](https://github.com/vitejs/vite/issues/13519)
* fix(optimizer): limit bundled file name length to 170 characters (#14561) ([a3b6d8d](https://github.com/vitejs/vite/commit/a3b6d8d)), closes [#14561](https://github.com/vitejs/vite/issues/14561)
* fix(optimizer): load the correct lock file (#12700) ([889eebe](https://github.com/vitejs/vite/commit/889eebe)), closes [#12700](https://github.com/vitejs/vite/issues/12700)
* fix(optimizer): log dependencies added by plugins (#16729) ([f0fb987](https://github.com/vitejs/vite/commit/f0fb987)), closes [#16729](https://github.com/vitejs/vite/issues/16729)
* fix(optimizer): log esbuild error when scanning deps (#11977) ([20e6060](https://github.com/vitejs/vite/commit/20e6060)), closes [#11977](https://github.com/vitejs/vite/issues/11977)
* fix(optimizer): log unoptimizable entries (#12138) ([2c93e0b](https://github.com/vitejs/vite/commit/2c93e0b)), closes [#12138](https://github.com/vitejs/vite/issues/12138)
* fix(optimizer): only run require-import conversion if require'd (#8795) ([7ae0d3e](https://github.com/vitejs/vite/commit/7ae0d3e)), closes [#8795](https://github.com/vitejs/vite/issues/8795)
* fix(optimizer): start optimizer after buildStart (#12832) ([cfe75ee](https://github.com/vitejs/vite/commit/cfe75ee)), closes [#12832](https://github.com/vitejs/vite/issues/12832)
* fix(optimizer): suppress esbuild cancel error (#12358) ([86a24e4](https://github.com/vitejs/vite/commit/86a24e4)), closes [#12358](https://github.com/vitejs/vite/issues/12358)
* fix(optimizer): transform css require to import directly (#12343) ([716286e](https://github.com/vitejs/vite/commit/716286e)), closes [#12343](https://github.com/vitejs/vite/issues/12343)
* fix(optimizer): transpile before calling `transformGlobImport` (#8343) ([1dbc7cc](https://github.com/vitejs/vite/commit/1dbc7cc)), closes [#8343](https://github.com/vitejs/vite/issues/8343)
* fix(optimizer): use simple browser external shim in prod (#8630) ([a32c4ba](https://github.com/vitejs/vite/commit/a32c4ba)), closes [#8630](https://github.com/vitejs/vite/issues/8630)
* fix(plugin-legacy): respect `entryFileNames` for polyfill chunks (#8247) ([baa9632](https://github.com/vitejs/vite/commit/baa9632)), closes [#8247](https://github.com/vitejs/vite/issues/8247)
* fix(plugin-react): broken optimized deps dir check (#8255) ([9e2a1ea](https://github.com/vitejs/vite/commit/9e2a1ea)), closes [#8255](https://github.com/vitejs/vite/issues/8255)
* fix(plugin-vue): support scss/sass/less... hmr on custom template languages (fix #10677) (#10844) ([d413848](https://github.com/vitejs/vite/commit/d413848)), closes [#10677](https://github.com/vitejs/vite/issues/10677) [#10844](https://github.com/vitejs/vite/issues/10844)
* fix(pluginContainer): drop previous sourcesContent (#13722) ([9310b3a](https://github.com/vitejs/vite/commit/9310b3a)), closes [#13722](https://github.com/vitejs/vite/issues/13722)
* fix(pluginContainer): run transform in this.load (#14965) ([3f57b05](https://github.com/vitejs/vite/commit/3f57b05)), closes [#14965](https://github.com/vitejs/vite/issues/14965)
* fix(preload): skip preload for non-static urls (#16556) ([bb79c9b](https://github.com/vitejs/vite/commit/bb79c9b)), closes [#16556](https://github.com/vitejs/vite/issues/16556)
* fix(preview): allow path containing . to fallback to index.html ([fddc151](https://github.com/vitejs/vite/commit/fddc151))
* fix(preview): Revert #10564 - throw Error on missing outDir (#11335) ([3aaa0ea](https://github.com/vitejs/vite/commit/3aaa0ea)), closes [#10564](https://github.com/vitejs/vite/issues/10564) [#11335](https://github.com/vitejs/vite/issues/11335) [#10564](https://github.com/vitejs/vite/issues/10564)
* fix(preview): send configured headers (#9976) ([0d20eae](https://github.com/vitejs/vite/commit/0d20eae)), closes [#9976](https://github.com/vitejs/vite/issues/9976)
* fix(preview): set isPreview true (#15695) ([93fce55](https://github.com/vitejs/vite/commit/93fce55)), closes [#15695](https://github.com/vitejs/vite/issues/15695)
* fix(proxy): correct the logic of bypass returning false (#14579) ([261633a](https://github.com/vitejs/vite/commit/261633a)), closes [#14579](https://github.com/vitejs/vite/issues/14579)
* fix(proxy): forward SSE close event (#13578) ([4afbccb](https://github.com/vitejs/vite/commit/4afbccb)), closes [#13578](https://github.com/vitejs/vite/issues/13578)
* fix(proxy): handle error when proxy itself errors (#13929) ([4848e41](https://github.com/vitejs/vite/commit/4848e41)), closes [#13929](https://github.com/vitejs/vite/issues/13929)
* fix(proxy): replace changeOrigin changes in 5.3.0 with new rewriteWsOrigin option (#17563) ([14c3d49](https://github.com/vitejs/vite/commit/14c3d49)), closes [#17563](https://github.com/vitejs/vite/issues/17563)
* fix(proxy): rewrite the origin header to match the target for ws proxy (#16558) ([7b0a65e](https://github.com/vitejs/vite/commit/7b0a65e)), closes [#16558](https://github.com/vitejs/vite/issues/16558)
* fix(reporter): build.assetsDir should not impact output when in lib mode (#12108) ([b12f457](https://github.com/vitejs/vite/commit/b12f457)), closes [#12108](https://github.com/vitejs/vite/issues/12108)
* fix(resolve): always use `module` condition (#13370) ([367920b](https://github.com/vitejs/vite/commit/367920b)), closes [#13370](https://github.com/vitejs/vite/issues/13370)
* fix(resolve): check nested directories for package.json (#5665) ([022db52](https://github.com/vitejs/vite/commit/022db52)), closes [#5665](https://github.com/vitejs/vite/issues/5665)
* fix(resolve): deep import resolvedId error (#13010) ([30a41ff](https://github.com/vitejs/vite/commit/30a41ff)), closes [#13010](https://github.com/vitejs/vite/issues/13010)
* fix(resolve): dont overwrite `isRequire` from `baseOptions` (#5872) ([2b91e5a](https://github.com/vitejs/vite/commit/2b91e5a)), closes [#5872](https://github.com/vitejs/vite/issues/5872)
* fix(resolve): ensure exports has precedence over mainFields (#11234) ([d6eb4f2](https://github.com/vitejs/vite/commit/d6eb4f2)), closes [#11234](https://github.com/vitejs/vite/issues/11234)
* fix(resolve): ensure exports has precedence over mainFields (cherry pick #11234) (#11595) ([691e432](https://github.com/vitejs/vite/commit/691e432)), closes [#11234](https://github.com/vitejs/vite/issues/11234) [#11595](https://github.com/vitejs/vite/issues/11595)
* fix(resolve): make directory package.json check best effort (#14626) ([d520388](https://github.com/vitejs/vite/commit/d520388)), closes [#14626](https://github.com/vitejs/vite/issues/14626)
* fix(resolve): rebase sub imports relative path (#12373) ([fe1d61a](https://github.com/vitejs/vite/commit/fe1d61a)), closes [#12373](https://github.com/vitejs/vite/issues/12373)
* fix(resolve): respect order of browser in mainFields when resolving (#15137) ([4a111aa](https://github.com/vitejs/vite/commit/4a111aa)), closes [#15137](https://github.com/vitejs/vite/issues/15137)
* fix(resolve): revert ensure exports has precedence over mainFields (#11234) (#11270) ([8d05daf](https://github.com/vitejs/vite/commit/8d05daf)), closes [#11234](https://github.com/vitejs/vite/issues/11234) [#11270](https://github.com/vitejs/vite/issues/11270)
* fix(resolve): skip `module` field when the importer is a `require` call (#7438) ([fe4c1ed](https://github.com/vitejs/vite/commit/fe4c1ed)), closes [#7438](https://github.com/vitejs/vite/issues/7438)
* fix(resolve): support `pkg?query` ([21bbceb](https://github.com/vitejs/vite/commit/21bbceb))
* fix(resolve): support submodules of optional peer deps (#14489) ([f80ff77](https://github.com/vitejs/vite/commit/f80ff77)), closes [#14489](https://github.com/vitejs/vite/issues/14489)
* fix(resolve): try .tsx extension for .js import from typescript module (#7005) ([72b8cb6](https://github.com/vitejs/vite/commit/72b8cb6)), closes [#7005](https://github.com/vitejs/vite/issues/7005)
* fix(resolve): update `resolve.exports` to `2.0.1` to fix `*` resolution issue (#12314) ([523d6f7](https://github.com/vitejs/vite/commit/523d6f7)), closes [#12314](https://github.com/vitejs/vite/issues/12314)
* fix(resolve): use different importer check for css imports (#12815) ([d037327](https://github.com/vitejs/vite/commit/d037327)), closes [#12815](https://github.com/vitejs/vite/issues/12815)
* fix(resolve): use only root package.json as exports source (#11259) ([b9afa6e](https://github.com/vitejs/vite/commit/b9afa6e)), closes [#11259](https://github.com/vitejs/vite/issues/11259)
* fix(resolver): skip known ESM entries when resolving a `require` call  (#7582) ([5d6ea8e](https://github.com/vitejs/vite/commit/5d6ea8e)), closes [#7582](https://github.com/vitejs/vite/issues/7582)
* fix(runtime): fix sourcemap with `prepareStackTrace` (#16220) ([dad7f4f](https://github.com/vitejs/vite/commit/dad7f4f)), closes [#16220](https://github.com/vitejs/vite/issues/16220)
* fix(runtime): pass path instead of fileURL to `isFilePathESM` (#15908) ([7b15607](https://github.com/vitejs/vite/commit/7b15607)), closes [#15908](https://github.com/vitejs/vite/issues/15908)
* fix(runtime): runtime HMR affects only imported files (#15898) ([57463fc](https://github.com/vitejs/vite/commit/57463fc)), closes [#15898](https://github.com/vitejs/vite/issues/15898)
* fix(sass): reorder sass importers (#10101) ([a543731](https://github.com/vitejs/vite/commit/a543731)), closes [#10101](https://github.com/vitejs/vite/issues/10101)
* fix(scan): correctly resolve virtual modules (#5711) ([01f9b16](https://github.com/vitejs/vite/commit/01f9b16)), closes [#5711](https://github.com/vitejs/vite/issues/5711)
* fix(scan): detect import .ts as .js (#8969) ([752af6c](https://github.com/vitejs/vite/commit/752af6c)), closes [#8969](https://github.com/vitejs/vite/issues/8969)
* fix(scan): escape for virtual modules (#6863) ([de20c73](https://github.com/vitejs/vite/commit/de20c73)), closes [#6863](https://github.com/vitejs/vite/issues/6863)
* fix(scan): handle .ts import as .js alias (#9282) ([0b083ca](https://github.com/vitejs/vite/commit/0b083ca)), closes [#9282](https://github.com/vitejs/vite/issues/9282)
* fix(scan): handle html script tag attributes that contain ">" (#13101) ([8a37de6](https://github.com/vitejs/vite/commit/8a37de6)), closes [#13101](https://github.com/vitejs/vite/issues/13101)
* fix(scan): handle local scripts with lang=ts (#5850) ([7ed8702](https://github.com/vitejs/vite/commit/7ed8702)), closes [#5850](https://github.com/vitejs/vite/issues/5850)
* fix(scan): skip tsconfigRaw fallback if tsconfig is set (#13823) ([b6155a1](https://github.com/vitejs/vite/commit/b6155a1)), closes [#13823](https://github.com/vitejs/vite/issues/13823)
* fix(scanner): catch all external files for glob imports (#15286) ([129d0d0](https://github.com/vitejs/vite/commit/129d0d0)), closes [#15286](https://github.com/vitejs/vite/issues/15286)
* fix(scanner): duplicate modules for same id if glob is used in html-like types (#16305) ([eca68fa](https://github.com/vitejs/vite/commit/eca68fa)), closes [#16305](https://github.com/vitejs/vite/issues/16305)
* fix(scanner): respect  `experimentalDecorators: true` (#15206) ([4144781](https://github.com/vitejs/vite/commit/4144781)), closes [#15206](https://github.com/vitejs/vite/issues/15206)
* fix(server): avoid chokidar throttling on startup (#15347) ([56a5740](https://github.com/vitejs/vite/commit/56a5740)), closes [#15347](https://github.com/vitejs/vite/issues/15347)
* fix(server): base middleware redirect with search and hash (#6574) ([a516e85](https://github.com/vitejs/vite/commit/a516e85)), closes [#6574](https://github.com/vitejs/vite/issues/6574)
* fix(server): delay ws server listen when restart (#12734) ([abe9274](https://github.com/vitejs/vite/commit/abe9274)), closes [#12734](https://github.com/vitejs/vite/issues/12734)
* fix(server): ensure consistency for url to file mapping in importAnalysis and static middleware (#65 ([b214115](https://github.com/vitejs/vite/commit/b214115)), closes [#6518](https://github.com/vitejs/vite/issues/6518)
* fix(server): handle appType mpa html fallback (#10336) ([65dd88b](https://github.com/vitejs/vite/commit/65dd88b)), closes [#10336](https://github.com/vitejs/vite/issues/10336)
* fix(server): intercept ping requests (#13117) ([d06cc42](https://github.com/vitejs/vite/commit/d06cc42)), closes [#13117](https://github.com/vitejs/vite/issues/13117)
* fix(server): remove restart guard on restart (#13789) ([2a38ef7](https://github.com/vitejs/vite/commit/2a38ef7)), closes [#13789](https://github.com/vitejs/vite/issues/13789)
* fix(server): should close server after create new server (#12379) ([d23605d](https://github.com/vitejs/vite/commit/d23605d)), closes [#12379](https://github.com/vitejs/vite/issues/12379)
* fix(server): should respect hmr port when middlewareMode=false (#13040) ([1ee0014](https://github.com/vitejs/vite/commit/1ee0014)), closes [#13040](https://github.com/vitejs/vite/issues/13040)
* fix(server): skip localhost verbatim dns lookup (#8642) ([7632247](https://github.com/vitejs/vite/commit/7632247)), closes [#8642](https://github.com/vitejs/vite/issues/8642)
* fix(server): skipped for ended response (#5230) ([7255fd5](https://github.com/vitejs/vite/commit/7255fd5)), closes [#5230](https://github.com/vitejs/vite/issues/5230)
* fix(server): the server restart port should remain unchanged (#14418) ([8b96e97](https://github.com/vitejs/vite/commit/8b96e97)), closes [#14418](https://github.com/vitejs/vite/issues/14418)
* fix(server): use `options` argument in caching of `transformRequest` calls (#5391) ([27b7f90](https://github.com/vitejs/vite/commit/27b7f90)), closes [#5391](https://github.com/vitejs/vite/issues/5391)
* fix(server): watch correct env files (#5520) ([03b77bd](https://github.com/vitejs/vite/commit/03b77bd)), closes [#5520](https://github.com/vitejs/vite/issues/5520)
* fix(server): watch env files creating and deleting (fix #12127) (#12129) ([cc3724f](https://github.com/vitejs/vite/commit/cc3724f)), closes [#12127](https://github.com/vitejs/vite/issues/12127) [#12129](https://github.com/vitejs/vite/issues/12129)
* fix(sourcemap): don't warn even if the sourcesContent is an empty string (#16273) ([24e376a](https://github.com/vitejs/vite/commit/24e376a)), closes [#16273](https://github.com/vitejs/vite/issues/16273)
* fix(sourcemap): dont inject fallback sourcemap if have existing (#14370) ([55a3b4f](https://github.com/vitejs/vite/commit/55a3b4f)), closes [#14370](https://github.com/vitejs/vite/issues/14370)
* fix(sourcemap): improve sourcemap compatibility for vue2 (#16594) ([913c040](https://github.com/vitejs/vite/commit/913c040)), closes [#16594](https://github.com/vitejs/vite/issues/16594)
* fix(sourcemap): preserve original sourcesContent (#13662) ([f6362b6](https://github.com/vitejs/vite/commit/f6362b6)), closes [#13662](https://github.com/vitejs/vite/issues/13662)
* fix(sourcemap): sourcemap is incorrect when sourcemap has `sources: [null]` (#14588) ([f8c6a34](https://github.com/vitejs/vite/commit/f8c6a34)), closes [#14588](https://github.com/vitejs/vite/issues/14588)
* fix(sourcemap): tolerate virtual modules in `sources` array (#5587) ([cfd2c5e](https://github.com/vitejs/vite/commit/cfd2c5e)), closes [#5587](https://github.com/vitejs/vite/issues/5587)
* fix(ssr-manifest): filter path undefined when dynamic import (#9655) ([1478a2f](https://github.com/vitejs/vite/commit/1478a2f)), closes [#9655](https://github.com/vitejs/vite/issues/9655)
* fix(ssr): `ssrTransform` handling for empty ArrayPattern (#5988) ([79aa687](https://github.com/vitejs/vite/commit/79aa687)), closes [#5988](https://github.com/vitejs/vite/issues/5988)
* fix(ssr): add normalizePath to require.resolve, fix #2393 (#4980) ([417208c](https://github.com/vitejs/vite/commit/417208c)), closes [#2393](https://github.com/vitejs/vite/issues/2393) [#4980](https://github.com/vitejs/vite/issues/4980)
* fix(ssr): allow primitive default exports and forwarded exports (#5973) ([a47b663](https://github.com/vitejs/vite/commit/a47b663)), closes [#5973](https://github.com/vitejs/vite/issues/5973)
* fix(ssr): allow ssrTransform to parse hashbang (#8005) ([6420ba0](https://github.com/vitejs/vite/commit/6420ba0)), closes [#8005](https://github.com/vitejs/vite/issues/8005)
* fix(ssr): allow virtual paths on node modules (#9405) ([e60368f](https://github.com/vitejs/vite/commit/e60368f)), closes [#9405](https://github.com/vitejs/vite/issues/9405)
* fix(ssr): apply alias to resolvable dependencies during dev (#15602) ([8e54af6](https://github.com/vitejs/vite/commit/8e54af6)), closes [#15602](https://github.com/vitejs/vite/issues/15602)
* fix(ssr): avoid resolving ESM for CJS dependencies (#5693) ([b937ea4](https://github.com/vitejs/vite/commit/b937ea4)), closes [#5693](https://github.com/vitejs/vite/issues/5693)
* fix(ssr): avoid transforming json file in ssrTransform (#6597) ([a709440](https://github.com/vitejs/vite/commit/a709440)), closes [#6597](https://github.com/vitejs/vite/issues/6597)
* fix(ssr): avoid using `tryNodeResolve` on absolute paths (#6488) ([f346d89](https://github.com/vitejs/vite/commit/f346d89)), closes [#6488](https://github.com/vitejs/vite/issues/6488)
* fix(ssr): bypass missing resolve error in SSR (#7164) ([a4927c5](https://github.com/vitejs/vite/commit/a4927c5)), closes [#7164](https://github.com/vitejs/vite/issues/7164)
* fix(ssr): capture scope declaration correctly (#6281) ([60ce7f9](https://github.com/vitejs/vite/commit/60ce7f9)), closes [#6281](https://github.com/vitejs/vite/issues/6281)
* fix(ssr): check esm file with normal file path (#15307) ([1597170](https://github.com/vitejs/vite/commit/1597170)), closes [#15307](https://github.com/vitejs/vite/issues/15307)
* fix(ssr): check root import extension for external (#9494) ([ff89df5](https://github.com/vitejs/vite/commit/ff89df5)), closes [#9494](https://github.com/vitejs/vite/issues/9494)
* fix(ssr): correctly track scope (#10300) ([a60529f](https://github.com/vitejs/vite/commit/a60529f)), closes [#10300](https://github.com/vitejs/vite/issues/10300)
* fix(ssr): crash on circular import (#14441) ([8cd846c](https://github.com/vitejs/vite/commit/8cd846c)), closes [#14441](https://github.com/vitejs/vite/issues/14441)
* fix(ssr): dont replace rollup input (#7275) ([9a88afa](https://github.com/vitejs/vite/commit/9a88afa)), closes [#7275](https://github.com/vitejs/vite/issues/7275)
* fix(ssr): dont transform process.env. in ssr (#5404) ([1140981](https://github.com/vitejs/vite/commit/1140981)), closes [#5404](https://github.com/vitejs/vite/issues/5404)
* fix(ssr): emit js sourcemaps for ssr builds (#11343) ([f12a1ab](https://github.com/vitejs/vite/commit/f12a1ab)), closes [#11343](https://github.com/vitejs/vite/issues/11343)
* fix(ssr): enable `inlineDynamicImports` when input has length 1 (#9904) ([9ac5075](https://github.com/vitejs/vite/commit/9ac5075)), closes [#9904](https://github.com/vitejs/vite/issues/9904)
* fix(ssr): externalize network imports during `ssrLoadModule` (#15599) ([af2aa09](https://github.com/vitejs/vite/commit/af2aa09)), closes [#15599](https://github.com/vitejs/vite/issues/15599)
* fix(ssr): failed ssrLoadModule call throws same error (#7177) ([891e7fc](https://github.com/vitejs/vite/commit/891e7fc)), closes [#7177](https://github.com/vitejs/vite/issues/7177)
* fix(ssr): fix crash when a pnpm/Yarn workspace depends on a CJS package (#9763) ([9e1086b](https://github.com/vitejs/vite/commit/9e1086b)), closes [#9763](https://github.com/vitejs/vite/issues/9763)
* fix(ssr): fix resolution for nested ssr externals (#6080) (#6470) ([4a764f5](https://github.com/vitejs/vite/commit/4a764f5)), closes [#6080](https://github.com/vitejs/vite/issues/6080) [#6470](https://github.com/vitejs/vite/issues/6470)
* fix(ssr): handle class declaration and expression name scoping (#16569) ([c071eb3](https://github.com/vitejs/vite/commit/c071eb3)), closes [#16569](https://github.com/vitejs/vite/issues/16569)
* fix(ssr): handle default arguments properly in `ssrTransform` (#5040) ([6a60080](https://github.com/vitejs/vite/commit/6a60080)), closes [#5040](https://github.com/vitejs/vite/issues/5040)
* fix(ssr): handle function expression name scoping (#16563) ([02db947](https://github.com/vitejs/vite/commit/02db947)), closes [#16563](https://github.com/vitejs/vite/issues/16563)
* fix(ssr): handle nameless descture in function args (#6489) ([debc08d](https://github.com/vitejs/vite/commit/debc08d)), closes [#6489](https://github.com/vitejs/vite/issues/6489)
* fix(ssr): handle object destructure alias, close #6222 (#6224) ([1d97ec3](https://github.com/vitejs/vite/commit/1d97ec3)), closes [#6222](https://github.com/vitejs/vite/issues/6222) [#6224](https://github.com/vitejs/vite/issues/6224)
* fix(ssr): handle parallel hookNodeResolve (#10401) ([1a961d9](https://github.com/vitejs/vite/commit/1a961d9)), closes [#10401](https://github.com/vitejs/vite/issues/10401)
* fix(ssr): hoist import statements to the top (#12274) ([33baff5](https://github.com/vitejs/vite/commit/33baff5)), closes [#12274](https://github.com/vitejs/vite/issues/12274)
* fix(ssr): hoist re-exports with imports (#12530) ([45549e4](https://github.com/vitejs/vite/commit/45549e4)), closes [#12530](https://github.com/vitejs/vite/issues/12530)
* fix(ssr): hoist statements after hashbang (#12985) ([07bd6d1](https://github.com/vitejs/vite/commit/07bd6d1)), closes [#12985](https://github.com/vitejs/vite/issues/12985)
* fix(ssr): ignore __esModule for ssrExportAll (#13084) ([8a8ea1d](https://github.com/vitejs/vite/commit/8a8ea1d)), closes [#13084](https://github.com/vitejs/vite/issues/13084)
* fix(ssr): ignore module exports condition (#11409) ([d3c9c0b](https://github.com/vitejs/vite/commit/d3c9c0b)), closes [#11409](https://github.com/vitejs/vite/issues/11409)
* fix(ssr): improve missing file error (#10880) ([5451a34](https://github.com/vitejs/vite/commit/5451a34)), closes [#10880](https://github.com/vitejs/vite/issues/10880)
* fix(ssr): load sourcemaps alongside modules (#11780) ([be95050](https://github.com/vitejs/vite/commit/be95050)), closes [#11780](https://github.com/vitejs/vite/issues/11780)
* fix(ssr): load sourcemaps alongside modules (fix: #3288) (#11576) ([dc05e97](https://github.com/vitejs/vite/commit/dc05e97)), closes [#3288](https://github.com/vitejs/vite/issues/3288) [#11576](https://github.com/vitejs/vite/issues/11576)
* fix(ssr): make import.meta.url be the filesystem URL (#5268) ([7674cf2](https://github.com/vitejs/vite/commit/7674cf2)), closes [#5268](https://github.com/vitejs/vite/issues/5268)
* fix(ssr): mark builtin modules as side effect free (#15658) ([526cf23](https://github.com/vitejs/vite/commit/526cf23)), closes [#15658](https://github.com/vitejs/vite/issues/15658)
* fix(ssr): move `vite:ssr-require-hook` after user plugins (#6306) ([d856c4b](https://github.com/vitejs/vite/commit/d856c4b)), closes [#6306](https://github.com/vitejs/vite/issues/6306)
* fix(ssr): nested destucture (#6249) ([485e298](https://github.com/vitejs/vite/commit/485e298)), closes [#6249](https://github.com/vitejs/vite/issues/6249)
* fix(ssr): no external symlink package (#9296) ([ea27701](https://github.com/vitejs/vite/commit/ea27701)), closes [#9296](https://github.com/vitejs/vite/issues/9296)
* fix(ssr): prefer CJS but still allow ESM entries (#5662) ([72d8925](https://github.com/vitejs/vite/commit/72d8925)), closes [#5662](https://github.com/vitejs/vite/issues/5662)
* fix(ssr): preserve require for external node (#11057) ([1ec0176](https://github.com/vitejs/vite/commit/1ec0176)), closes [#11057](https://github.com/vitejs/vite/issues/11057)
* fix(ssr): print file url in `ssrTransform` parse error (#12060) ([19f39f7](https://github.com/vitejs/vite/commit/19f39f7)), closes [#12060](https://github.com/vitejs/vite/issues/12060)
* fix(ssr): properly transform export default with expressions (#7705) ([d6830e3](https://github.com/vitejs/vite/commit/d6830e3)), closes [#7705](https://github.com/vitejs/vite/issues/7705)
* fix(ssr): remove pure CSS dynamic import (#17371) ([67ff94b](https://github.com/vitejs/vite/commit/67ff94b)), closes [#17371](https://github.com/vitejs/vite/issues/17371)
* fix(ssr): rename objectPattern dynamic key (fixes #9585) (#9609) ([ee7f78f](https://github.com/vitejs/vite/commit/ee7f78f)), closes [#9585](https://github.com/vitejs/vite/issues/9585) [#9609](https://github.com/vitejs/vite/issues/9609)
* fix(ssr): resolve interlocking circular dependency issues (#15395) ([687c38b](https://github.com/vitejs/vite/commit/687c38b)), closes [#15395](https://github.com/vitejs/vite/issues/15395)
* fix(ssr): resolve with isRequire true (#10569) ([7b81210](https://github.com/vitejs/vite/commit/7b81210)), closes [#10569](https://github.com/vitejs/vite/issues/10569)
* fix(ssr): rewrite dynamic class method name (fix #7751) (#7757) ([b89974a](https://github.com/vitejs/vite/commit/b89974a)), closes [#7751](https://github.com/vitejs/vite/issues/7751) [#7757](https://github.com/vitejs/vite/issues/7757)
* fix(ssr): robust regexp to check cjs content (#6053) ([0373441](https://github.com/vitejs/vite/commit/0373441)), closes [#6053](https://github.com/vitejs/vite/issues/6053)
* fix(ssr): should correctly transfrom identifier in ssr (#6548) ([15cd975](https://github.com/vitejs/vite/commit/15cd975)), closes [#6548](https://github.com/vitejs/vite/issues/6548)
* fix(ssr): show ssr module loader error stack (#12651) ([050c0f9](https://github.com/vitejs/vite/commit/050c0f9)), closes [#12651](https://github.com/vitejs/vite/issues/12651)
* fix(ssr): skip dedupe require if noExternal true (#5928) ([f6aa7fe](https://github.com/vitejs/vite/commit/f6aa7fe)), closes [#5928](https://github.com/vitejs/vite/issues/5928)
* fix(ssr): skip dedupe require in esm (#5714) ([9666446](https://github.com/vitejs/vite/commit/9666446)), closes [#5714](https://github.com/vitejs/vite/issues/5714)
* fix(ssr): skip esm proxy guard for namespace imports (#14988) ([82a5b11](https://github.com/vitejs/vite/commit/82a5b11)), closes [#14988](https://github.com/vitejs/vite/issues/14988)
* fix(ssr): skip optional peer dep resolve (#10593) ([0a69985](https://github.com/vitejs/vite/commit/0a69985)), closes [#10593](https://github.com/vitejs/vite/issues/10593)
* fix(ssr): skip rewriting stack trace if it's already rewritten (fixes #11037) (#11070) ([feb8ce0](https://github.com/vitejs/vite/commit/feb8ce0)), closes [#11037](https://github.com/vitejs/vite/issues/11037) [#11070](https://github.com/vitejs/vite/issues/11070)
* fix(ssr): skip updateCjsSsrExternals if legacy flag disabled (#13230) ([13fc345](https://github.com/vitejs/vite/commit/13fc345)), closes [#13230](https://github.com/vitejs/vite/issues/13230)
* fix(ssr): skip vite resolve for windows absolute path (#6764) ([489a7f1](https://github.com/vitejs/vite/commit/489a7f1)), closes [#6764](https://github.com/vitejs/vite/issues/6764)
* fix(ssr): sourcemap content (fixes #8657) (#8997) ([aff4544](https://github.com/vitejs/vite/commit/aff4544)), closes [#8657](https://github.com/vitejs/vite/issues/8657) [#8997](https://github.com/vitejs/vite/issues/8997)
* fix(ssr): ssrTransfrom function argument destructure (#6171) ([2762a0e](https://github.com/vitejs/vite/commit/2762a0e)), closes [#6171](https://github.com/vitejs/vite/issues/6171)
* fix(ssr): ssrTransfrom with function declaration in scope, fix #4306 (#5376) ([5306632](https://github.com/vitejs/vite/commit/5306632)), closes [#4306](https://github.com/vitejs/vite/issues/4306) [#5376](https://github.com/vitejs/vite/issues/5376)
* fix(ssr): stacktrace uses abs path with or without sourcemap (#12902) ([88c855e](https://github.com/vitejs/vite/commit/88c855e)), closes [#12902](https://github.com/vitejs/vite/issues/12902)
* fix(ssr): strip NULL_BYTE_PLACEHOLDER before import (#9124) ([c5f2dc7](https://github.com/vitejs/vite/commit/c5f2dc7)), closes [#9124](https://github.com/vitejs/vite/issues/9124)
* fix(ssr): support externalized builtins for webworker (#15656) ([639bbd6](https://github.com/vitejs/vite/commit/639bbd6)), closes [#15656](https://github.com/vitejs/vite/issues/15656)
* fix(ssr): track for statements as block scope (#13021) ([2f8502f](https://github.com/vitejs/vite/commit/2f8502f)), closes [#13021](https://github.com/vitejs/vite/issues/13021)
* fix(ssr): track var as function scope (#10388) ([87b48f9](https://github.com/vitejs/vite/commit/87b48f9)), closes [#10388](https://github.com/vitejs/vite/issues/10388)
* fix(ssr): transform class props (#6261) ([2e3fe59](https://github.com/vitejs/vite/commit/2e3fe59)), closes [#6261](https://github.com/vitejs/vite/issues/6261)
* fix(ssr): transform superclass identifier (#13635) ([c5b2c8f](https://github.com/vitejs/vite/commit/c5b2c8f)), closes [#13635](https://github.com/vitejs/vite/issues/13635)
* fix(ssr): use `tryNodeResolve` instead of `resolveFrom` (#3951) ([87c0050](https://github.com/vitejs/vite/commit/87c0050)), closes [#3951](https://github.com/vitejs/vite/issues/3951)
* fix(ssr): use appendRight for import (#9554) ([dfec6ca](https://github.com/vitejs/vite/commit/dfec6ca)), closes [#9554](https://github.com/vitejs/vite/issues/9554)
* fix(ssrTransform): handle arbitrary module namespace identifiers (#17446) ([0a76652](https://github.com/vitejs/vite/commit/0a76652)), closes [#17446](https://github.com/vitejs/vite/issues/17446)
* fix(ssrTransform): use appendLeft instead of appendRight (#6407) ([3012541](https://github.com/vitejs/vite/commit/3012541)), closes [#6407](https://github.com/vitejs/vite/issues/6407)
* fix(transformCjsImport): make dev and build get the same result (#5745) ([9d3e4e6](https://github.com/vitejs/vite/commit/9d3e4e6)), closes [#5745](https://github.com/vitejs/vite/issues/5745)
* fix(type): update ExportsData type ([b582581](https://github.com/vitejs/vite/commit/b582581))
* fix(types): add missing options parameter to importMeta (#6433) ([ccf7d79](https://github.com/vitejs/vite/commit/ccf7d79)), closes [#6433](https://github.com/vitejs/vite/issues/6433)
* fix(types): avoid resolve.exports types for bundling (#12346) ([6b40f03](https://github.com/vitejs/vite/commit/6b40f03)), closes [#12346](https://github.com/vitejs/vite/issues/12346)
* fix(types): dynamic import in import.meta (#6456) ([5d7b4c3](https://github.com/vitejs/vite/commit/5d7b4c3)), closes [#6456](https://github.com/vitejs/vite/issues/6456) [#6433](https://github.com/vitejs/vite/issues/6433)
* fix(types): explicitly set Vite hooks' `this` to `void` (#9885) ([2d2f2e5](https://github.com/vitejs/vite/commit/2d2f2e5)), closes [#9885](https://github.com/vitejs/vite/issues/9885)
* fix(types): mark explicitImportRequired optional and experimental (#9962) ([7b618f0](https://github.com/vitejs/vite/commit/7b618f0)), closes [#9962](https://github.com/vitejs/vite/issues/9962)
* fix(types): mark hmr update internal types optional (#15606) ([df8f5a5](https://github.com/vitejs/vite/commit/df8f5a5)), closes [#15606](https://github.com/vitejs/vite/issues/15606)
* fix(types): missing return type on `logError` (#5067) ([3c9f1a1](https://github.com/vitejs/vite/commit/3c9f1a1)), closes [#5067](https://github.com/vitejs/vite/issues/5067)
* fix(types): narrow down the return type of `defineConfig` (#13792) ([c971f26](https://github.com/vitejs/vite/commit/c971f26)), closes [#13792](https://github.com/vitejs/vite/issues/13792)
* fix(types): remove `null` from `CSSModulesOptions.localsConvention` (#10904) ([a9978dd](https://github.com/vitejs/vite/commit/a9978dd)), closes [#10904](https://github.com/vitejs/vite/issues/10904)
* fix(typescript): correctly expand ${configDir} in tsconfig.json (#17576) ([24c799b](https://github.com/vitejs/vite/commit/24c799b)), closes [#17576](https://github.com/vitejs/vite/issues/17576)
* fix(vite): precisely check if files are in dirs (#14241) ([245d186](https://github.com/vitejs/vite/commit/245d186)), closes [#14241](https://github.com/vitejs/vite/issues/14241)
* fix(wasm): support inlined WASM in Node < v16 (fix #8620) (#8622) ([f586b14](https://github.com/vitejs/vite/commit/f586b14)), closes [#8620](https://github.com/vitejs/vite/issues/8620) [#8622](https://github.com/vitejs/vite/issues/8622)
* fix(watch): build watch fails when outDir is empty string (#15979) ([1d263d3](https://github.com/vitejs/vite/commit/1d263d3)), closes [#15979](https://github.com/vitejs/vite/issues/15979)
* fix(worker): asset in iife worker and relative base (#12697) ([ddefc06](https://github.com/vitejs/vite/commit/ddefc06)), closes [#12697](https://github.com/vitejs/vite/issues/12697)
* fix(worker): disable build reporter plugin when bundling worker (#11058) ([7b72069](https://github.com/vitejs/vite/commit/7b72069)), closes [#11058](https://github.com/vitejs/vite/issues/11058)
* fix(worker): disable manifest plugins in worker build (#12661) ([20b8ef4](https://github.com/vitejs/vite/commit/20b8ef4)), closes [#12661](https://github.com/vitejs/vite/issues/12661)
* fix(worker): dont throw on `import.meta.url` in ssr (#8846) ([ef749ed](https://github.com/vitejs/vite/commit/ef749ed)), closes [#8846](https://github.com/vitejs/vite/issues/8846)
* fix(worker): force rollup to build worker module under watch mode (#11919) ([d464679](https://github.com/vitejs/vite/commit/d464679)), closes [#11919](https://github.com/vitejs/vite/issues/11919)
* fix(worker): force rollup to build workerImportMetaUrl under watch mode (#14712) ([8db40ee](https://github.com/vitejs/vite/commit/8db40ee)), closes [#14712](https://github.com/vitejs/vite/issues/14712)
* fix(worker): hide "The emitted file overwrites" warning if the content is same (#16094) ([60dfa9e](https://github.com/vitejs/vite/commit/60dfa9e)), closes [#16094](https://github.com/vitejs/vite/issues/16094)
* fix(worker): import.meta.* (#7706) ([b092697](https://github.com/vitejs/vite/commit/b092697)), closes [#7706](https://github.com/vitejs/vite/issues/7706)
* fix(worker): inline es worker does not work in build mode (#14307) ([7371c5c](https://github.com/vitejs/vite/commit/7371c5c)), closes [#14307](https://github.com/vitejs/vite/issues/14307)
* fix(worker): nested inlined worker always fallbacked to data URI worker instead of using blob worker ([07bc489](https://github.com/vitejs/vite/commit/07bc489)), closes [#17509](https://github.com/vitejs/vite/issues/17509)
* fix(worker): prevent inject esm in classic workers (#14918) ([2687dbb](https://github.com/vitejs/vite/commit/2687dbb)), closes [#14918](https://github.com/vitejs/vite/issues/14918)
* fix(worker): replace `import.meta` correctly for IIFE worker (#15321) ([08d093c](https://github.com/vitejs/vite/commit/08d093c)), closes [#15321](https://github.com/vitejs/vite/issues/15321)
* fix(worker): return null for shouldTransformCachedModule (#12797) ([ea5f6fc](https://github.com/vitejs/vite/commit/ea5f6fc)), closes [#12797](https://github.com/vitejs/vite/issues/12797)
* fix(worker): support comment in worker constructor option (#10226) ([66c9058](https://github.com/vitejs/vite/commit/66c9058)), closes [#10226](https://github.com/vitejs/vite/issues/10226)
* fix(worker): support trailing comma (#10211) ([0542e7c](https://github.com/vitejs/vite/commit/0542e7c)), closes [#10211](https://github.com/vitejs/vite/issues/10211)
* fix(worker): support UTF-8 encoding in inline workers (fixes #12117) (#15866) ([570e0f1](https://github.com/vitejs/vite/commit/570e0f1)), closes [#12117](https://github.com/vitejs/vite/issues/12117) [#15866](https://github.com/vitejs/vite/issues/15866)
* fix(worker): throw error when circular worker import is detected and support self referencing worker ([eef9da1](https://github.com/vitejs/vite/commit/eef9da1)), closes [#16103](https://github.com/vitejs/vite/issues/16103)
* fix(worker): using data URLs for inline shared worker (#12014) ([79a5007](https://github.com/vitejs/vite/commit/79a5007)), closes [#12014](https://github.com/vitejs/vite/issues/12014)
* fix(worker): worker import.meta.url should not depends on document in iife mode (#12629) ([65f5ed2](https://github.com/vitejs/vite/commit/65f5ed2)), closes [#12629](https://github.com/vitejs/vite/issues/12629)
* release: v2.6.0 ([978575a](https://github.com/vitejs/vite/commit/978575a))
* release: v2.6.0-beta.0 ([5240033](https://github.com/vitejs/vite/commit/5240033))
* release: v2.6.0-beta.1 ([83881aa](https://github.com/vitejs/vite/commit/83881aa))
* release: v2.6.0-beta.2 ([a35e56a](https://github.com/vitejs/vite/commit/a35e56a))
* release: v2.6.0-beta.3 ([eff92a5](https://github.com/vitejs/vite/commit/eff92a5))
* release: v2.6.0-beta.4 ([ffb30b2](https://github.com/vitejs/vite/commit/ffb30b2))
* release: v2.6.1 ([f609a4d](https://github.com/vitejs/vite/commit/f609a4d))
* release: v2.6.10 ([d1c85d1](https://github.com/vitejs/vite/commit/d1c85d1))
* release: v2.6.11 ([841044f](https://github.com/vitejs/vite/commit/841044f))
* release: v2.6.12 ([77bd4c9](https://github.com/vitejs/vite/commit/77bd4c9))
* release: v2.6.13 ([504d700](https://github.com/vitejs/vite/commit/504d700))
* release: v2.6.2 ([2b7e836](https://github.com/vitejs/vite/commit/2b7e836))
* release: v2.6.3 ([a639f77](https://github.com/vitejs/vite/commit/a639f77))
* release: v2.6.4 ([26300f9](https://github.com/vitejs/vite/commit/26300f9))
* release: v2.6.5 ([8a32cb6](https://github.com/vitejs/vite/commit/8a32cb6))
* release: v2.6.6 ([1837141](https://github.com/vitejs/vite/commit/1837141))
* release: v2.6.7 ([04b163c](https://github.com/vitejs/vite/commit/04b163c))
* release: v2.6.8 ([3a6bcd3](https://github.com/vitejs/vite/commit/3a6bcd3))
* release: v2.6.9 ([c50eec9](https://github.com/vitejs/vite/commit/c50eec9))
* release: v2.7.0 ([075128a](https://github.com/vitejs/vite/commit/075128a))
* release: v2.7.0-beta.0 ([7b6af0f](https://github.com/vitejs/vite/commit/7b6af0f))
* release: v2.7.0-beta.1 ([532f683](https://github.com/vitejs/vite/commit/532f683))
* release: v2.7.0-beta.10 ([aaa26a3](https://github.com/vitejs/vite/commit/aaa26a3))
* release: v2.7.0-beta.11 ([49f28e2](https://github.com/vitejs/vite/commit/49f28e2))
* release: v2.7.0-beta.2 ([935f6d7](https://github.com/vitejs/vite/commit/935f6d7))
* release: v2.7.0-beta.3 ([906cc51](https://github.com/vitejs/vite/commit/906cc51))
* release: v2.7.0-beta.4 ([6c0701d](https://github.com/vitejs/vite/commit/6c0701d))
* release: v2.7.0-beta.5 ([96b9fbb](https://github.com/vitejs/vite/commit/96b9fbb))
* release: v2.7.0-beta.6 ([9faefad](https://github.com/vitejs/vite/commit/9faefad))
* release: v2.7.0-beta.7 ([0ed7bc3](https://github.com/vitejs/vite/commit/0ed7bc3))
* release: v2.7.0-beta.8 ([37b85a0](https://github.com/vitejs/vite/commit/37b85a0))
* release: v2.7.0-beta.9 ([7bf9f65](https://github.com/vitejs/vite/commit/7bf9f65))
* release: v2.7.1 ([b625a2c](https://github.com/vitejs/vite/commit/b625a2c))
* release: v2.7.2 ([3e71100](https://github.com/vitejs/vite/commit/3e71100))
* release: v2.7.3 ([a08b4c5](https://github.com/vitejs/vite/commit/a08b4c5))
* release: v2.7.4 ([b04f5a9](https://github.com/vitejs/vite/commit/b04f5a9))
* release: v2.7.5 ([20586f0](https://github.com/vitejs/vite/commit/20586f0))
* release: v2.7.6 ([a96bdd9](https://github.com/vitejs/vite/commit/a96bdd9))
* release: v2.7.7 ([1d722c5](https://github.com/vitejs/vite/commit/1d722c5))
* release: v2.7.8 ([d13ced5](https://github.com/vitejs/vite/commit/d13ced5))
* release: v2.7.9 ([7e3e84e](https://github.com/vitejs/vite/commit/7e3e84e))
* release: v2.8.0 ([d4886ea](https://github.com/vitejs/vite/commit/d4886ea))
* release: v2.8.0-beta.0 ([1f03211](https://github.com/vitejs/vite/commit/1f03211))
* release: v2.8.0-beta.1 ([bd4c3a5](https://github.com/vitejs/vite/commit/bd4c3a5))
* release: v2.8.0-beta.2 ([6ecf9b0](https://github.com/vitejs/vite/commit/6ecf9b0))
* release: v2.8.0-beta.3 ([75ccdf1](https://github.com/vitejs/vite/commit/75ccdf1))
* release: v2.8.0-beta.4 ([29405c3](https://github.com/vitejs/vite/commit/29405c3))
* release: v2.8.0-beta.5 ([6409747](https://github.com/vitejs/vite/commit/6409747))
* release: v2.8.0-beta.6 ([651e0ba](https://github.com/vitejs/vite/commit/651e0ba))
* release: v2.8.0-beta.7 ([b79fec9](https://github.com/vitejs/vite/commit/b79fec9))
* release: v2.8.1 ([b984397](https://github.com/vitejs/vite/commit/b984397))
* release: v2.8.2 ([e8c840a](https://github.com/vitejs/vite/commit/e8c840a))
* release: v2.8.3 ([ac9652b](https://github.com/vitejs/vite/commit/ac9652b))
* release: v2.8.4 ([b146007](https://github.com/vitejs/vite/commit/b146007))
* release: v2.8.5 ([22a0381](https://github.com/vitejs/vite/commit/22a0381))
* release: v2.8.6 ([110212e](https://github.com/vitejs/vite/commit/110212e))
* release: v2.9.0 ([997e735](https://github.com/vitejs/vite/commit/997e735))
* release: v2.9.0-beta.0 ([2351d79](https://github.com/vitejs/vite/commit/2351d79))
* release: v2.9.0-beta.1 ([a8dda1b](https://github.com/vitejs/vite/commit/a8dda1b))
* release: v2.9.0-beta.10 ([4ffd82d](https://github.com/vitejs/vite/commit/4ffd82d))
* release: v2.9.0-beta.11 ([a0f82bd](https://github.com/vitejs/vite/commit/a0f82bd))
* release: v2.9.0-beta.2 ([0b66901](https://github.com/vitejs/vite/commit/0b66901))
* release: v2.9.0-beta.3 ([560fc4d](https://github.com/vitejs/vite/commit/560fc4d))
* release: v2.9.0-beta.4 ([9a7b133](https://github.com/vitejs/vite/commit/9a7b133))
* release: v2.9.0-beta.5 ([d9e39f2](https://github.com/vitejs/vite/commit/d9e39f2))
* release: v2.9.0-beta.6 ([c650f0f](https://github.com/vitejs/vite/commit/c650f0f))
* release: v2.9.0-beta.7 ([4538e59](https://github.com/vitejs/vite/commit/4538e59))
* release: v2.9.0-beta.8 ([d649dab](https://github.com/vitejs/vite/commit/d649dab))
* release: v2.9.0-beta.9 ([dd33d9c](https://github.com/vitejs/vite/commit/dd33d9c))
* release: v2.9.1 ([a3b9f4c](https://github.com/vitejs/vite/commit/a3b9f4c))
* release: v2.9.2 ([f699afb](https://github.com/vitejs/vite/commit/f699afb))
* release: v2.9.3 ([cb5c3f9](https://github.com/vitejs/vite/commit/cb5c3f9))
* release: v2.9.4 ([6c27f14](https://github.com/vitejs/vite/commit/6c27f14))
* release: v2.9.5 ([5d96dca](https://github.com/vitejs/vite/commit/5d96dca))
* release: v2.9.6 ([ef903d6](https://github.com/vitejs/vite/commit/ef903d6))
* release: v2.9.7 ([dde774f](https://github.com/vitejs/vite/commit/dde774f))
* release: v2.9.8 ([77865b4](https://github.com/vitejs/vite/commit/77865b4))
* release: v3.0.0 ([b8c625c](https://github.com/vitejs/vite/commit/b8c625c))
* release: v3.0.0-alpha.0 ([1780a8a](https://github.com/vitejs/vite/commit/1780a8a))
* release: v3.0.0-alpha.1 ([9df59ed](https://github.com/vitejs/vite/commit/9df59ed))
* release: v3.0.0-alpha.10 ([121a482](https://github.com/vitejs/vite/commit/121a482))
* release: v3.0.0-alpha.11 ([98ccc0b](https://github.com/vitejs/vite/commit/98ccc0b))
* release: v3.0.0-alpha.12 ([d402ad3](https://github.com/vitejs/vite/commit/d402ad3))
* release: v3.0.0-alpha.13 ([a96e129](https://github.com/vitejs/vite/commit/a96e129))
* release: v3.0.0-alpha.14 ([4d2fc6c](https://github.com/vitejs/vite/commit/4d2fc6c))
* release: v3.0.0-alpha.2 ([c1e0132](https://github.com/vitejs/vite/commit/c1e0132))
* release: v3.0.0-alpha.3 ([90fe2fa](https://github.com/vitejs/vite/commit/90fe2fa))
* release: v3.0.0-alpha.4 ([7c950ca](https://github.com/vitejs/vite/commit/7c950ca))
* release: v3.0.0-alpha.5 ([2d73f98](https://github.com/vitejs/vite/commit/2d73f98))
* release: v3.0.0-alpha.6 ([a9ccedd](https://github.com/vitejs/vite/commit/a9ccedd))
* release: v3.0.0-alpha.7 ([eddb6fb](https://github.com/vitejs/vite/commit/eddb6fb))
* release: v3.0.0-alpha.8 ([9af61b5](https://github.com/vitejs/vite/commit/9af61b5))
* release: v3.0.0-alpha.9 ([8a68fbd](https://github.com/vitejs/vite/commit/8a68fbd))
* release: v3.0.0-beta.0 ([1550ff8](https://github.com/vitejs/vite/commit/1550ff8))
* release: v3.0.0-beta.1 ([c8aab50](https://github.com/vitejs/vite/commit/c8aab50))
* release: v3.0.0-beta.10 ([e685de3](https://github.com/vitejs/vite/commit/e685de3))
* release: v3.0.0-beta.2 ([eac0494](https://github.com/vitejs/vite/commit/eac0494))
* release: v3.0.0-beta.3 ([de8fdd8](https://github.com/vitejs/vite/commit/de8fdd8))
* release: v3.0.0-beta.4 ([d5c5099](https://github.com/vitejs/vite/commit/d5c5099))
* release: v3.0.0-beta.5 ([e5a39cc](https://github.com/vitejs/vite/commit/e5a39cc))
* release: v3.0.0-beta.6 ([d412860](https://github.com/vitejs/vite/commit/d412860))
* release: v3.0.0-beta.7 ([0d2c257](https://github.com/vitejs/vite/commit/0d2c257))
* release: v3.0.0-beta.8 ([33d6177](https://github.com/vitejs/vite/commit/33d6177))
* release: v3.0.0-beta.9 ([5a7d04d](https://github.com/vitejs/vite/commit/5a7d04d))
* release: v3.0.1 ([8db00d8](https://github.com/vitejs/vite/commit/8db00d8))
* release: v3.0.2 ([af6088f](https://github.com/vitejs/vite/commit/af6088f))
* release: v3.0.3 ([4215d46](https://github.com/vitejs/vite/commit/4215d46))
* release: v3.0.4 ([1c1cf43](https://github.com/vitejs/vite/commit/1c1cf43))
* release: v3.0.5 ([10757b8](https://github.com/vitejs/vite/commit/10757b8))
* release: v3.0.6 ([3455c17](https://github.com/vitejs/vite/commit/3455c17))
* release: v3.0.7 ([e384e31](https://github.com/vitejs/vite/commit/e384e31))
* release: v3.0.8 ([dfdbc59](https://github.com/vitejs/vite/commit/dfdbc59))
* release: v3.0.9 ([518bc6c](https://github.com/vitejs/vite/commit/518bc6c))
* release: v3.1.0 ([b1ad82d](https://github.com/vitejs/vite/commit/b1ad82d))
* release: v3.1.0-beta.0 ([5df788d](https://github.com/vitejs/vite/commit/5df788d))
* release: v3.1.0-beta.1 ([3b10a25](https://github.com/vitejs/vite/commit/3b10a25))
* release: v3.1.0-beta.2 ([4158b98](https://github.com/vitejs/vite/commit/4158b98))
* release: v3.1.1 ([d324181](https://github.com/vitejs/vite/commit/d324181))
* release: v3.1.2 ([cda361c](https://github.com/vitejs/vite/commit/cda361c))
* release: v3.1.3 ([dfa22ca](https://github.com/vitejs/vite/commit/dfa22ca))
* release: v3.2.0 ([4198e34](https://github.com/vitejs/vite/commit/4198e34))
* release: v3.2.0-beta.0 ([599eb81](https://github.com/vitejs/vite/commit/599eb81))
* release: v3.2.0-beta.1 ([8eb0b0a](https://github.com/vitejs/vite/commit/8eb0b0a))
* release: v3.2.0-beta.2 ([0cfd26c](https://github.com/vitejs/vite/commit/0cfd26c))
* release: v3.2.0-beta.3 ([f148c18](https://github.com/vitejs/vite/commit/f148c18))
* release: v3.2.0-beta.4 ([0163abc](https://github.com/vitejs/vite/commit/0163abc))
* release: v3.2.1 ([47a78db](https://github.com/vitejs/vite/commit/47a78db))
* release: v3.2.2 ([65d69b4](https://github.com/vitejs/vite/commit/65d69b4))
* release: v3.2.3 ([ce4c8d4](https://github.com/vitejs/vite/commit/ce4c8d4))
* release: v4.0.0 ([566d4c7](https://github.com/vitejs/vite/commit/566d4c7))
* release: v4.0.0-alpha.0 ([cd78f50](https://github.com/vitejs/vite/commit/cd78f50))
* release: v4.0.0-alpha.1 ([3b770a5](https://github.com/vitejs/vite/commit/3b770a5))
* release: v4.0.0-alpha.2 ([6777d85](https://github.com/vitejs/vite/commit/6777d85))
* release: v4.0.0-alpha.3 ([06f0756](https://github.com/vitejs/vite/commit/06f0756))
* release: v4.0.0-alpha.4 ([d9779c7](https://github.com/vitejs/vite/commit/d9779c7))
* release: v4.0.0-alpha.5 ([95bc282](https://github.com/vitejs/vite/commit/95bc282))
* release: v4.0.0-alpha.6 ([5b66c2c](https://github.com/vitejs/vite/commit/5b66c2c))
* release: v4.0.0-beta.0 ([848680c](https://github.com/vitejs/vite/commit/848680c))
* release: v4.0.0-beta.1 ([c4b192c](https://github.com/vitejs/vite/commit/c4b192c))
* release: v4.0.0-beta.2 ([20c7dd3](https://github.com/vitejs/vite/commit/20c7dd3))
* release: v4.0.0-beta.3 ([556ea49](https://github.com/vitejs/vite/commit/556ea49))
* release: v4.0.0-beta.4 ([60df543](https://github.com/vitejs/vite/commit/60df543))
* release: v4.0.0-beta.5 ([5cb63d0](https://github.com/vitejs/vite/commit/5cb63d0))
* release: v4.0.0-beta.6 ([a9850be](https://github.com/vitejs/vite/commit/a9850be))
* release: v4.0.0-beta.7 ([84d6ca2](https://github.com/vitejs/vite/commit/84d6ca2))
* release: v4.0.1 ([060cd66](https://github.com/vitejs/vite/commit/060cd66))
* release: v4.0.2 ([8ec44a5](https://github.com/vitejs/vite/commit/8ec44a5))
* release: v4.0.3 ([b9511f1](https://github.com/vitejs/vite/commit/b9511f1))
* release: v4.0.4 ([4f7a48f](https://github.com/vitejs/vite/commit/4f7a48f))
* release: v4.1.0 ([c57c21c](https://github.com/vitejs/vite/commit/c57c21c))
* release: v4.1.0-beta.0 ([d9323aa](https://github.com/vitejs/vite/commit/d9323aa))
* release: v4.1.0-beta.1 ([e674f85](https://github.com/vitejs/vite/commit/e674f85))
* release: v4.1.0-beta.2 ([88dad65](https://github.com/vitejs/vite/commit/88dad65))
* release: v4.1.1 ([4db491b](https://github.com/vitejs/vite/commit/4db491b))
* release: v4.1.2 ([6eee75c](https://github.com/vitejs/vite/commit/6eee75c))
* release: v4.1.3 ([04e4df3](https://github.com/vitejs/vite/commit/04e4df3))
* release: v4.1.4 ([b5a2485](https://github.com/vitejs/vite/commit/b5a2485))
* release: v4.2.0 ([9dbb7f7](https://github.com/vitejs/vite/commit/9dbb7f7))
* release: v4.2.0-beta.0 ([bf9c49f](https://github.com/vitejs/vite/commit/bf9c49f))
* release: v4.2.0-beta.1 ([4cf6d46](https://github.com/vitejs/vite/commit/4cf6d46))
* release: v4.2.0-beta.2 ([d89de6c](https://github.com/vitejs/vite/commit/d89de6c))
* release: v4.2.1 ([a53feb5](https://github.com/vitejs/vite/commit/a53feb5))
* release: v4.3.0 ([d6468a3](https://github.com/vitejs/vite/commit/d6468a3))
* release: v4.3.0-beta.0 ([ba45f92](https://github.com/vitejs/vite/commit/ba45f92))
* release: v4.3.0-beta.1 ([9697e64](https://github.com/vitejs/vite/commit/9697e64))
* release: v4.3.0-beta.2 ([a4341bc](https://github.com/vitejs/vite/commit/a4341bc))
* release: v4.3.0-beta.3 ([063d93b](https://github.com/vitejs/vite/commit/063d93b))
* release: v4.3.0-beta.4 ([72a379f](https://github.com/vitejs/vite/commit/72a379f))
* release: v4.3.0-beta.5 ([e0061d1](https://github.com/vitejs/vite/commit/e0061d1))
* release: v4.3.0-beta.6 ([ca93d67](https://github.com/vitejs/vite/commit/ca93d67))
* release: v4.3.0-beta.7 ([f2bcad8](https://github.com/vitejs/vite/commit/f2bcad8))
* release: v4.3.0-beta.8 ([3334660](https://github.com/vitejs/vite/commit/3334660))
* release: v4.3.1 ([2a8779c](https://github.com/vitejs/vite/commit/2a8779c))
* release: v4.3.2 ([1bc42cf](https://github.com/vitejs/vite/commit/1bc42cf))
* release: v4.3.3 ([f749c3e](https://github.com/vitejs/vite/commit/f749c3e))
* release: v4.3.4 ([5890aa9](https://github.com/vitejs/vite/commit/5890aa9))
* release: v4.3.5 ([775505d](https://github.com/vitejs/vite/commit/775505d))
* release: v4.3.6 ([9a42e31](https://github.com/vitejs/vite/commit/9a42e31))
* release: v4.3.7 ([d09bbd0](https://github.com/vitejs/vite/commit/d09bbd0))
* release: v4.3.8 ([3f3fff2](https://github.com/vitejs/vite/commit/3f3fff2))
* release: v4.3.9 ([a460a2b](https://github.com/vitejs/vite/commit/a460a2b))
* release: v4.3.9 ([5c9abf7](https://github.com/vitejs/vite/commit/5c9abf7))
* release: v4.4.0 ([3b47e34](https://github.com/vitejs/vite/commit/3b47e34))
* release: v4.4.0-beta.0 ([92b7fbb](https://github.com/vitejs/vite/commit/92b7fbb))
* release: v4.4.0-beta.1 ([309b011](https://github.com/vitejs/vite/commit/309b011))
* release: v4.4.0-beta.2 ([168e1fc](https://github.com/vitejs/vite/commit/168e1fc))
* release: v4.4.0-beta.3 ([f899f9a](https://github.com/vitejs/vite/commit/f899f9a))
* release: v4.4.0-beta.4 ([2b1ffe8](https://github.com/vitejs/vite/commit/2b1ffe8))
* release: v4.4.1 ([487bdcd](https://github.com/vitejs/vite/commit/487bdcd))
* release: v4.4.2 ([df492fa](https://github.com/vitejs/vite/commit/df492fa))
* release: v4.4.3 ([ec9d2e7](https://github.com/vitejs/vite/commit/ec9d2e7))
* release: v4.4.4 ([435d4e7](https://github.com/vitejs/vite/commit/435d4e7))
* release: v4.4.5 ([af77f3e](https://github.com/vitejs/vite/commit/af77f3e))
* release: v4.4.6 ([85c38ab](https://github.com/vitejs/vite/commit/85c38ab))
* release: v4.4.7 ([d4f13bd](https://github.com/vitejs/vite/commit/d4f13bd))
* release: v4.4.8 ([e41d78e](https://github.com/vitejs/vite/commit/e41d78e))
* release: v4.4.9 ([898fee7](https://github.com/vitejs/vite/commit/898fee7))
* release: v5.0.0 ([0c31258](https://github.com/vitejs/vite/commit/0c31258))
* release: v5.0.0-beta.0 ([c2b1414](https://github.com/vitejs/vite/commit/c2b1414))
* release: v5.0.0-beta.1 ([44ca967](https://github.com/vitejs/vite/commit/44ca967))
* release: v5.0.0-beta.10 ([55c7564](https://github.com/vitejs/vite/commit/55c7564))
* release: v5.0.0-beta.11 ([50b7cc0](https://github.com/vitejs/vite/commit/50b7cc0))
* release: v5.0.0-beta.12 ([5631b94](https://github.com/vitejs/vite/commit/5631b94))
* release: v5.0.0-beta.13 ([5b58eca](https://github.com/vitejs/vite/commit/5b58eca))
* release: v5.0.0-beta.14 ([2124264](https://github.com/vitejs/vite/commit/2124264))
* release: v5.0.0-beta.15 ([1816232](https://github.com/vitejs/vite/commit/1816232))
* release: v5.0.0-beta.16 ([ac2503d](https://github.com/vitejs/vite/commit/ac2503d))
* release: v5.0.0-beta.17 ([987b8fa](https://github.com/vitejs/vite/commit/987b8fa))
* release: v5.0.0-beta.18 ([b42a228](https://github.com/vitejs/vite/commit/b42a228))
* release: v5.0.0-beta.19 ([2546ddc](https://github.com/vitejs/vite/commit/2546ddc))
* release: v5.0.0-beta.2 ([1c03172](https://github.com/vitejs/vite/commit/1c03172))
* release: v5.0.0-beta.20 ([9258ce0](https://github.com/vitejs/vite/commit/9258ce0))
* release: v5.0.0-beta.3 ([5e28eef](https://github.com/vitejs/vite/commit/5e28eef))
* release: v5.0.0-beta.4 ([a30fdd9](https://github.com/vitejs/vite/commit/a30fdd9))
* release: v5.0.0-beta.5 ([90fbe30](https://github.com/vitejs/vite/commit/90fbe30))
* release: v5.0.0-beta.6 ([1414207](https://github.com/vitejs/vite/commit/1414207))
* release: v5.0.0-beta.7 ([a43167c](https://github.com/vitejs/vite/commit/a43167c))
* release: v5.0.0-beta.8 ([00bf697](https://github.com/vitejs/vite/commit/00bf697))
* release: v5.0.0-beta.9 ([a76be5d](https://github.com/vitejs/vite/commit/a76be5d))
* release: v5.0.1 ([c3b55c4](https://github.com/vitejs/vite/commit/c3b55c4))
* release: v5.0.10 ([5684fcd](https://github.com/vitejs/vite/commit/5684fcd))
* release: v5.0.11 ([b44c493](https://github.com/vitejs/vite/commit/b44c493))
* release: v5.0.2 ([5d05fc2](https://github.com/vitejs/vite/commit/5d05fc2))
* release: v5.0.3 ([2649f40](https://github.com/vitejs/vite/commit/2649f40))
* release: v5.0.4 ([73ef074](https://github.com/vitejs/vite/commit/73ef074))
* release: v5.0.5 ([fa79767](https://github.com/vitejs/vite/commit/fa79767))
* release: v5.0.6 ([bd26284](https://github.com/vitejs/vite/commit/bd26284))
* release: v5.0.7 ([25d7924](https://github.com/vitejs/vite/commit/25d7924))
* release: v5.0.8 ([9d547f2](https://github.com/vitejs/vite/commit/9d547f2))
* release: v5.0.9 ([77d5165](https://github.com/vitejs/vite/commit/77d5165))
* release: v5.1.0 ([3036bef](https://github.com/vitejs/vite/commit/3036bef))
* release: v5.1.0-beta.0 ([fdc142c](https://github.com/vitejs/vite/commit/fdc142c))
* release: v5.1.0-beta.1 ([0649444](https://github.com/vitejs/vite/commit/0649444))
* release: v5.1.0-beta.2 ([5b4be42](https://github.com/vitejs/vite/commit/5b4be42))
* release: v5.1.0-beta.3 ([3c9cab6](https://github.com/vitejs/vite/commit/3c9cab6))
* release: v5.1.0-beta.4 ([8ca9743](https://github.com/vitejs/vite/commit/8ca9743))
* release: v5.1.0-beta.5 ([997a695](https://github.com/vitejs/vite/commit/997a695))
* release: v5.1.0-beta.6 ([9f4b996](https://github.com/vitejs/vite/commit/9f4b996))
* release: v5.1.0-beta.7 ([0f9c72a](https://github.com/vitejs/vite/commit/0f9c72a))
* release: v5.1.1 ([8e946a1](https://github.com/vitejs/vite/commit/8e946a1))
* release: v5.1.2 ([75ddc0e](https://github.com/vitejs/vite/commit/75ddc0e))
* release: v5.1.3 ([bf39527](https://github.com/vitejs/vite/commit/bf39527))
* release: v5.1.4 ([0137ea0](https://github.com/vitejs/vite/commit/0137ea0))
* release: v5.1.5 ([2af1ae8](https://github.com/vitejs/vite/commit/2af1ae8))
* release: v5.1.6 ([6f7466e](https://github.com/vitejs/vite/commit/6f7466e))
* release: v5.2.0 ([e4572b8](https://github.com/vitejs/vite/commit/e4572b8))
* release: v5.2.0-beta.0 ([d82e8b1](https://github.com/vitejs/vite/commit/d82e8b1))
* release: v5.2.0-beta.1 ([20bf97d](https://github.com/vitejs/vite/commit/20bf97d))
* release: v5.2.1 ([ee4d2bc](https://github.com/vitejs/vite/commit/ee4d2bc))
* release: v5.2.10 ([088d24b](https://github.com/vitejs/vite/commit/088d24b))
* release: v5.2.11 ([2bc5d3d](https://github.com/vitejs/vite/commit/2bc5d3d))
* release: v5.2.12 ([bed3faa](https://github.com/vitejs/vite/commit/bed3faa))
* release: v5.2.2 ([d443428](https://github.com/vitejs/vite/commit/d443428))
* release: v5.2.3 ([a67f9f6](https://github.com/vitejs/vite/commit/a67f9f6))
* release: v5.2.4 ([6a07243](https://github.com/vitejs/vite/commit/6a07243))
* release: v5.2.5 ([7a2791c](https://github.com/vitejs/vite/commit/7a2791c))
* release: v5.2.6 ([7369016](https://github.com/vitejs/vite/commit/7369016))
* release: v5.2.7 ([ad246da](https://github.com/vitejs/vite/commit/ad246da))
* release: v5.2.8 ([8b8d402](https://github.com/vitejs/vite/commit/8b8d402))
* release: v5.2.9 ([a77707d](https://github.com/vitejs/vite/commit/a77707d))
* release: v5.3.0 ([29a260c](https://github.com/vitejs/vite/commit/29a260c))
* release: v5.3.0-beta.0 ([18a68cf](https://github.com/vitejs/vite/commit/18a68cf))
* release: v5.3.0-beta.1 ([feae09f](https://github.com/vitejs/vite/commit/feae09f))
* release: v5.3.0-beta.2 ([7176c90](https://github.com/vitejs/vite/commit/7176c90))
* release: v5.3.1 ([c608e6a](https://github.com/vitejs/vite/commit/c608e6a))
* release: v5.3.2 ([3af02bd](https://github.com/vitejs/vite/commit/3af02bd))
* release: v5.3.3 ([22b2994](https://github.com/vitejs/vite/commit/22b2994))
* release: v5.3.4 ([4e57a97](https://github.com/vitejs/vite/commit/4e57a97))
* refactor: `ExportData.imports` to `ExportData.hasImports` (#8355) ([168de2d](https://github.com/vitejs/vite/commit/168de2d)), closes [#8355](https://github.com/vitejs/vite/issues/8355)
* refactor: `import.meta.url` condition from renderChunk hook of worker plugin (#12696) ([fdef8fd](https://github.com/vitejs/vite/commit/fdef8fd)), closes [#12696](https://github.com/vitejs/vite/issues/12696)
* refactor: add new overload to the type of defineConfig (#13958) ([24c12fe](https://github.com/vitejs/vite/commit/24c12fe)), closes [#13958](https://github.com/vitejs/vite/issues/13958)
* refactor: align with Promise.withResolvers() (#15171) ([642f9bc](https://github.com/vitejs/vite/commit/642f9bc)), closes [#15171](https://github.com/vitejs/vite/issues/15171)
* refactor: always load config with esbuild bundled code (#9121) ([a2b3131](https://github.com/vitejs/vite/commit/a2b3131)), closes [#9121](https://github.com/vitejs/vite/issues/9121)
* refactor: append tags logic in applyHtmlTransforms (#15647) ([09b1517](https://github.com/vitejs/vite/commit/09b1517)), closes [#15647](https://github.com/vitejs/vite/issues/15647)
* refactor: avoid splitting vendor chunk by default (#6534) ([849e845](https://github.com/vitejs/vite/commit/849e845)), closes [#6534](https://github.com/vitejs/vite/issues/6534)
* refactor: bundle json5 (#6527) ([4e83e44](https://github.com/vitejs/vite/commit/4e83e44)), closes [#6527](https://github.com/vitejs/vite/issues/6527)
* refactor: change location of server start log messages (#5016) ([4872003](https://github.com/vitejs/vite/commit/4872003)), closes [#5016](https://github.com/vitejs/vite/issues/5016)
* refactor: change style.innerHTML to style.textContent (#10801) ([8ea71b4](https://github.com/vitejs/vite/commit/8ea71b4)), closes [#10801](https://github.com/vitejs/vite/issues/10801)
* refactor: clean up preTransformRequest (#12672) ([561227c](https://github.com/vitejs/vite/commit/561227c)), closes [#12672](https://github.com/vitejs/vite/issues/12672)
* refactor: config hook helper function (#9982) ([9c1be10](https://github.com/vitejs/vite/commit/9c1be10)), closes [#9982](https://github.com/vitejs/vite/issues/9982)
* refactor: customize ErrorOverlay (part 2) (#11830) ([4159e6f](https://github.com/vitejs/vite/commit/4159e6f)), closes [#11830](https://github.com/vitejs/vite/issues/11830)
* refactor: delete dependent pre built proxy modules (#10427) ([b3b388d](https://github.com/vitejs/vite/commit/b3b388d)), closes [#10427](https://github.com/vitejs/vite/issues/10427)
* refactor: enforce a cache directory (#6415) ([fb7ba53](https://github.com/vitejs/vite/commit/fb7ba53)), closes [#6415](https://github.com/vitejs/vite/issues/6415)
* refactor: ensure HTML is stripped of generated blank lines (#14274) ([bc97091](https://github.com/vitejs/vite/commit/bc97091)), closes [#14274](https://github.com/vitejs/vite/issues/14274)
* refactor: esbuild handles `target` and `useDefineForClassFields` (#7698) ([0c928aa](https://github.com/vitejs/vite/commit/0c928aa)), closes [#7698](https://github.com/vitejs/vite/issues/7698)
* refactor: esbuild plugin config logic (#12493) ([45b5b0f](https://github.com/vitejs/vite/commit/45b5b0f)), closes [#12493](https://github.com/vitejs/vite/issues/12493)
* refactor: extract '_metadata.json' string to a constant (#15541) ([adda370](https://github.com/vitejs/vite/commit/adda370)), closes [#15541](https://github.com/vitejs/vite/issues/15541)
* refactor: import version from rollup (#10964) ([9f54c6a](https://github.com/vitejs/vite/commit/9f54c6a)), closes [#10964](https://github.com/vitejs/vite/issues/10964)
* refactor: improve scanner logs (#12578) ([9925a72](https://github.com/vitejs/vite/commit/9925a72)), closes [#12578](https://github.com/vitejs/vite/issues/12578)
* refactor: isInNodeModules util (#12588) ([fb3245a](https://github.com/vitejs/vite/commit/fb3245a)), closes [#12588](https://github.com/vitejs/vite/issues/12588)
* refactor: make debugger nullable (#12687) ([89e4977](https://github.com/vitejs/vite/commit/89e4977)), closes [#12687](https://github.com/vitejs/vite/issues/12687)
* refactor: make HMR agnostic to environment (#15179) ([0571b7c](https://github.com/vitejs/vite/commit/0571b7c)), closes [#15179](https://github.com/vitejs/vite/issues/15179)
* refactor: migrate from vue/compiler-dom to parse5 (#9678) ([05b3ce6](https://github.com/vitejs/vite/commit/05b3ce6)), closes [#9678](https://github.com/vitejs/vite/issues/9678)
* refactor: move CSS emitFile logic closer to rollup (#10909) ([92a206b](https://github.com/vitejs/vite/commit/92a206b)), closes [#10909](https://github.com/vitejs/vite/issues/10909)
* refactor: normalize cache package dir (#15546) ([e030f4b](https://github.com/vitejs/vite/commit/e030f4b)), closes [#15546](https://github.com/vitejs/vite/issues/15546)
* refactor: normalize fs/promises usage (#13441) ([f201805](https://github.com/vitejs/vite/commit/f201805)), closes [#13441](https://github.com/vitejs/vite/issues/13441)
* refactor: normalize publicDir when resolving config (#15360) ([ea5fdeb](https://github.com/vitejs/vite/commit/ea5fdeb)), closes [#15360](https://github.com/vitejs/vite/issues/15360)
* refactor: normalize scripts and commands naming (#5207) ([22873a7](https://github.com/vitejs/vite/commit/22873a7)), closes [#5207](https://github.com/vitejs/vite/issues/5207)
* refactor: opt-in optimizeDeps during build and SSR (#8965) ([f8c8cf2](https://github.com/vitejs/vite/commit/f8c8cf2)), closes [#8965](https://github.com/vitejs/vite/issues/8965)
* refactor: optimize `async` and `await` in code (#9854) ([31f5ff3](https://github.com/vitejs/vite/commit/31f5ff3)), closes [#9854](https://github.com/vitejs/vite/issues/9854)
* refactor: plugin container (#17288) ([4aa4a80](https://github.com/vitejs/vite/commit/4aa4a80)), closes [#17288](https://github.com/vitejs/vite/issues/17288)
* refactor: remove ?used inject in glob plugin (#8900) ([f9b5c14](https://github.com/vitejs/vite/commit/f9b5c14)), closes [#8900](https://github.com/vitejs/vite/issues/8900)
* refactor: remove `ensureVolumeInPath` (#12690) ([a3150ee](https://github.com/vitejs/vite/commit/a3150ee)), closes [#12690](https://github.com/vitejs/vite/issues/12690)
* refactor: remove `idToPkgMap` (#12564) ([a326ec8](https://github.com/vitejs/vite/commit/a326ec8)), closes [#12564](https://github.com/vitejs/vite/issues/12564)
* refactor: remove `vite build --force` (#15837) ([f1a4242](https://github.com/vitejs/vite/commit/f1a4242)), closes [#15837](https://github.com/vitejs/vite/issues/15837)
* refactor: remove acorn (#16238) ([454e2d1](https://github.com/vitejs/vite/commit/454e2d1)), closes [#16238](https://github.com/vitejs/vite/issues/16238)
* refactor: remove build time pre-bundling (#15184) ([757844f](https://github.com/vitejs/vite/commit/757844f)), closes [#15184](https://github.com/vitejs/vite/issues/15184)
* refactor: remove CJS ssr output format (#13944) ([2f60b9e](https://github.com/vitejs/vite/commit/2f60b9e)), closes [#13944](https://github.com/vitejs/vite/issues/13944)
* refactor: remove constructed sheet type style injection (#11818) ([1a6a0c2](https://github.com/vitejs/vite/commit/1a6a0c2)), closes [#11818](https://github.com/vitejs/vite/issues/11818)
* refactor: remove deprecated api for 3.0 (#5868) ([b5c3709](https://github.com/vitejs/vite/commit/b5c3709)), closes [#5868](https://github.com/vitejs/vite/issues/5868)
* refactor: remove json-stable-stringify (#15571) ([b9b0816](https://github.com/vitejs/vite/commit/b9b0816)), closes [#15571](https://github.com/vitejs/vite/issues/15571)
* refactor: remove unnecessary async (#13546) ([7f241e9](https://github.com/vitejs/vite/commit/7f241e9)), closes [#13546](https://github.com/vitejs/vite/issues/13546)
* refactor: remove unnecessary condition (#8742) ([2ae269e](https://github.com/vitejs/vite/commit/2ae269e)), closes [#8742](https://github.com/vitejs/vite/issues/8742)
* refactor: remove unnecessary if conditions (#11668) ([9c114c5](https://github.com/vitejs/vite/commit/9c114c5)), closes [#11668](https://github.com/vitejs/vite/issues/11668)
* refactor: remove unused const (#5748) ([67a465f](https://github.com/vitejs/vite/commit/67a465f)), closes [#5748](https://github.com/vitejs/vite/issues/5748)
* refactor: remove unused exports data props (#12740) ([4538bfe](https://github.com/vitejs/vite/commit/4538bfe)), closes [#12740](https://github.com/vitejs/vite/issues/12740)
* refactor: remove unused record flatIdToExports (#14557) ([7e62710](https://github.com/vitejs/vite/commit/7e62710)), closes [#14557](https://github.com/vitejs/vite/issues/14557)
* refactor: rename `force` to `optimizeDeps.force` (#8418) ([f520a54](https://github.com/vitejs/vite/commit/f520a54)), closes [#8418](https://github.com/vitejs/vite/issues/8418)
* refactor: rename `mergeConfig` parameters (#6144) ([5f39c28](https://github.com/vitejs/vite/commit/5f39c28)), closes [#6144](https://github.com/vitejs/vite/issues/6144)
* refactor: replace duplicate code with tryStatSync (#14461) ([be6b0c8](https://github.com/vitejs/vite/commit/be6b0c8)), closes [#14461](https://github.com/vitejs/vite/issues/14461)
* refactor: replace includes with logical operations (#17620) ([c4a2227](https://github.com/vitejs/vite/commit/c4a2227)), closes [#17620](https://github.com/vitejs/vite/issues/17620)
* refactor: resolveExports (#10917) ([ad21ec3](https://github.com/vitejs/vite/commit/ad21ec3)), closes [#10917](https://github.com/vitejs/vite/issues/10917)
* refactor: reuse existing node utils (#15480) ([17ab48a](https://github.com/vitejs/vite/commit/17ab48a)), closes [#15480](https://github.com/vitejs/vite/issues/15480)
* refactor: share code with vite runtime (#15907) ([b20d542](https://github.com/vitejs/vite/commit/b20d542)), closes [#15907](https://github.com/vitejs/vite/issues/15907)
* refactor: simplify `resolveSSRExternal` (#5544) ([f663348](https://github.com/vitejs/vite/commit/f663348)), closes [#5544](https://github.com/vitejs/vite/issues/5544)
* refactor: simplify array handling (#5734) ([2cacc6b](https://github.com/vitejs/vite/commit/2cacc6b)), closes [#5734](https://github.com/vitejs/vite/issues/5734)
* refactor: simplify build optimizer node_env handling (#14829) ([275907b](https://github.com/vitejs/vite/commit/275907b)), closes [#14829](https://github.com/vitejs/vite/issues/14829)
* refactor: simplify crawlEndFinder (#12868) ([31f8b51](https://github.com/vitejs/vite/commit/31f8b51)), closes [#12868](https://github.com/vitejs/vite/issues/12868)
* refactor: simplify filter callback (#6119) ([dd79858](https://github.com/vitejs/vite/commit/dd79858)), closes [#6119](https://github.com/vitejs/vite/issues/6119)
* refactor: simplify lookupFile (#12585) ([4215e22](https://github.com/vitejs/vite/commit/4215e22)), closes [#12585](https://github.com/vitejs/vite/issues/12585)
* refactor: simplify SSR options' if statement (#13254) ([8013a66](https://github.com/vitejs/vite/commit/8013a66)), closes [#13254](https://github.com/vitejs/vite/issues/13254)
* refactor: tryStatSync as util (#12575) ([92601db](https://github.com/vitejs/vite/commit/92601db)), closes [#12575](https://github.com/vitejs/vite/issues/12575)
* refactor: tsconfck for esbuild compilerOptions tsconfig files (#4889) ([9560af8](https://github.com/vitejs/vite/commit/9560af8)), closes [#4889](https://github.com/vitejs/vite/issues/4889)
* refactor: type client maps (#8626) ([cf87882](https://github.com/vitejs/vite/commit/cf87882)), closes [#8626](https://github.com/vitejs/vite/issues/8626)
* refactor: update es-module-lexer to 1.4.0 (#14937) ([374e6fd](https://github.com/vitejs/vite/commit/374e6fd)), closes [#14937](https://github.com/vitejs/vite/issues/14937)
* refactor: update import analysis plugin debugger ([2fb2561](https://github.com/vitejs/vite/commit/2fb2561))
* refactor: update to tsconfck3 with lazy cache (#14234) ([6e0b0ee](https://github.com/vitejs/vite/commit/6e0b0ee)), closes [#14234](https://github.com/vitejs/vite/issues/14234)
* refactor: upgrade resolve.exports (#11712) ([00a79ec](https://github.com/vitejs/vite/commit/00a79ec)), closes [#11712](https://github.com/vitejs/vite/issues/11712)
* refactor: use `import.meta.glob` over `globEager` in tests (#8066) ([1878f46](https://github.com/vitejs/vite/commit/1878f46)), closes [#8066](https://github.com/vitejs/vite/issues/8066)
* refactor: use `resolvePackageData` in `requireResolveFromRootWithFallback` (#12712) ([1ea38e2](https://github.com/vitejs/vite/commit/1ea38e2)), closes [#12712](https://github.com/vitejs/vite/issues/12712)
* refactor: use `server.ssrTransform` (#9769) ([246a087](https://github.com/vitejs/vite/commit/246a087)), closes [#9769](https://github.com/vitejs/vite/issues/9769)
* refactor: use dedicated regex methods (#15228) ([0348137](https://github.com/vitejs/vite/commit/0348137)), closes [#15228](https://github.com/vitejs/vite/issues/15228)
* refactor: use dynamic import directly (#14661) ([af60592](https://github.com/vitejs/vite/commit/af60592)), closes [#14661](https://github.com/vitejs/vite/issues/14661)
* refactor: use findNearestPackageData in more places (#12577) ([35faae9](https://github.com/vitejs/vite/commit/35faae9)), closes [#12577](https://github.com/vitejs/vite/issues/12577)
* refactor: use function to eval worker and glob options (#10999) ([f4c1264](https://github.com/vitejs/vite/commit/f4c1264)), closes [#10999](https://github.com/vitejs/vite/issues/10999)
* refactor: use node hash (#7975) ([5ce7c74](https://github.com/vitejs/vite/commit/5ce7c74)), closes [#7975](https://github.com/vitejs/vite/issues/7975)
* refactor: use performance timing for debug logs ([3ba2d7e](https://github.com/vitejs/vite/commit/3ba2d7e))
* refactor: use rollup hashing when emitting assets (#10878) ([78c77be](https://github.com/vitejs/vite/commit/78c77be)), closes [#10878](https://github.com/vitejs/vite/issues/10878)
* refactor: use simpler resolve for nested optimized deps (#12770) ([d202588](https://github.com/vitejs/vite/commit/d202588)), closes [#12770](https://github.com/vitejs/vite/issues/12770)
* refactor: use types from sass instead of @types/sass (#16340) ([4581e83](https://github.com/vitejs/vite/commit/4581e83)), closes [#16340](https://github.com/vitejs/vite/issues/16340)
* refactor(build): close rollup bundle directly (#11460) ([a802828](https://github.com/vitejs/vite/commit/a802828)), closes [#11460](https://github.com/vitejs/vite/issues/11460)
* refactor(build): remove quotes from preload marker (#16562) ([9853190](https://github.com/vitejs/vite/commit/9853190)), closes [#16562](https://github.com/vitejs/vite/issues/16562)
* refactor(build): type rollup output (#13447) ([5ee6fd2](https://github.com/vitejs/vite/commit/5ee6fd2)), closes [#13447](https://github.com/vitejs/vite/issues/13447)
* refactor(cli): improve output aesthetics (#6997) ([809ab47](https://github.com/vitejs/vite/commit/809ab47)), closes [#6997](https://github.com/vitejs/vite/issues/6997)
* refactor(client): simplify fetchUpdate code (#11004) ([f777b55](https://github.com/vitejs/vite/commit/f777b55)), closes [#11004](https://github.com/vitejs/vite/issues/11004)
* refactor(config): remove unnecessary esbuild option (#13580) ([67f4e52](https://github.com/vitejs/vite/commit/67f4e52)), closes [#13580](https://github.com/vitejs/vite/issues/13580)
* refactor(config): replace `fs.promises`  with `fsp` (#13427) ([1e299cc](https://github.com/vitejs/vite/commit/1e299cc)), closes [#13427](https://github.com/vitejs/vite/issues/13427)
* refactor(css): make `getEmptyChunkReplacer` for unit test (#14528) ([18900fd](https://github.com/vitejs/vite/commit/18900fd)), closes [#14528](https://github.com/vitejs/vite/issues/14528)
* refactor(css): remove `export {}` ([98fbdc3](https://github.com/vitejs/vite/commit/98fbdc3))
* refactor(css): simplify cached import code (#12730) ([0646754](https://github.com/vitejs/vite/commit/0646754)), closes [#12730](https://github.com/vitejs/vite/issues/12730)
* refactor(css): use `preliminaryFileName` to detect pure CSS chunks (#13974) ([835249d](https://github.com/vitejs/vite/commit/835249d)), closes [#13974](https://github.com/vitejs/vite/issues/13974)
* refactor(eslint): migrate to `eslint-plugin-n` (#12895) ([62ebe28](https://github.com/vitejs/vite/commit/62ebe28)), closes [#12895](https://github.com/vitejs/vite/issues/12895)
* refactor(hmr): keep buffer implementation internal, expose queueUpdate (#15486) ([c029efb](https://github.com/vitejs/vite/commit/c029efb)), closes [#15486](https://github.com/vitejs/vite/issues/15486)
* refactor(hmr): provide a separate logger interface (#15631) ([110e2e1](https://github.com/vitejs/vite/commit/110e2e1)), closes [#15631](https://github.com/vitejs/vite/issues/15631)
* refactor(hmr): simplify fetchUpdate (#9881) ([8872aba](https://github.com/vitejs/vite/commit/8872aba)), closes [#9881](https://github.com/vitejs/vite/issues/9881)
* refactor(importAnalysis): cache injected env string (#12154) ([2aad552](https://github.com/vitejs/vite/commit/2aad552)), closes [#12154](https://github.com/vitejs/vite/issues/12154)
* refactor(optimizer): await depsOptimizer.scanProcessing (#11251) ([fa64c8e](https://github.com/vitejs/vite/commit/fa64c8e)), closes [#11251](https://github.com/vitejs/vite/issues/11251)
* refactor(optimizer): use early continues (#17551) ([7c06ef0](https://github.com/vitejs/vite/commit/7c06ef0)), closes [#17551](https://github.com/vitejs/vite/issues/17551)
* refactor(resolve): remove commonjs plugin handling (#9460) ([2042b91](https://github.com/vitejs/vite/commit/2042b91)), closes [#9460](https://github.com/vitejs/vite/issues/9460)
* refactor(resolve): remove deep import syntax handling (#12381) ([42e0d6a](https://github.com/vitejs/vite/commit/42e0d6a)), closes [#12381](https://github.com/vitejs/vite/issues/12381)
* refactor(runtime): minor tweaks (#15904) ([63a39c2](https://github.com/vitejs/vite/commit/63a39c2)), closes [#15904](https://github.com/vitejs/vite/issues/15904)
* refactor(runtime): seal ES module namespace object instead of feezing (#15914) ([4172f02](https://github.com/vitejs/vite/commit/4172f02)), closes [#15914](https://github.com/vitejs/vite/issues/15914)
* refactor(runtime): share more code between runtime and main bundle (#16063) ([93be84e](https://github.com/vitejs/vite/commit/93be84e)), closes [#16063](https://github.com/vitejs/vite/issues/16063)
* refactor(runtime): use functions from `pathe` (#16061) ([aac2ef7](https://github.com/vitejs/vite/commit/aac2ef7)), closes [#16061](https://github.com/vitejs/vite/issues/16061)
* refactor(ssr): remove unused metadata code (#14711) ([c5f2d60](https://github.com/vitejs/vite/commit/c5f2d60)), closes [#14711](https://github.com/vitejs/vite/issues/14711)
* refactor(types): bundle client types (#9966) ([da632bf](https://github.com/vitejs/vite/commit/da632bf)), closes [#9966](https://github.com/vitejs/vite/issues/9966)
* refactor(types): share hot context type (#7475) ([64ddff0](https://github.com/vitejs/vite/commit/64ddff0)), closes [#7475](https://github.com/vitejs/vite/issues/7475)
* refactor(types): simplify type exports (#10243) ([291174d](https://github.com/vitejs/vite/commit/291174d)), closes [#10243](https://github.com/vitejs/vite/issues/10243)
* chore: `utf8` replaced with `utf-8` (#16232) ([9800c73](https://github.com/vitejs/vite/commit/9800c73)), closes [#16232](https://github.com/vitejs/vite/issues/16232)
* chore: 2.9 release notes (#7525) ([4324f48](https://github.com/vitejs/vite/commit/4324f48)), closes [#7525](https://github.com/vitejs/vite/issues/7525)
* chore: 3.0 release notes and bump peer deps (#9072) ([427ba26](https://github.com/vitejs/vite/commit/427ba26)), closes [#9072](https://github.com/vitejs/vite/issues/9072)
* chore: 4.1.0 changelog cleanup (#11900) ([7747d32](https://github.com/vitejs/vite/commit/7747d32)), closes [#11900](https://github.com/vitejs/vite/issues/11900)
* chore: add `\0` to virtual files id (#11261) ([02cdfa9](https://github.com/vitejs/vite/commit/02cdfa9)), closes [#11261](https://github.com/vitejs/vite/issues/11261)
* chore: add `PluginWithRequiredHook` type & extract `getHookHandler` function  (#14845) ([997f2d5](https://github.com/vitejs/vite/commit/997f2d5)), closes [#14845](https://github.com/vitejs/vite/issues/14845)
* chore: add callback to http-proxy.d.ts jsdoc (#17646) ([d8a5d70](https://github.com/vitejs/vite/commit/d8a5d70)), closes [#17646](https://github.com/vitejs/vite/issues/17646)
* chore: add changelog for vite 4.2.2 and 3.2.6 (#13055) ([0c9f1f4](https://github.com/vitejs/vite/commit/0c9f1f4)), closes [#13055](https://github.com/vitejs/vite/issues/13055)
* chore: add comment about crossorigin attribute for script module (#15040) ([03c371e](https://github.com/vitejs/vite/commit/03c371e)), closes [#15040](https://github.com/vitejs/vite/issues/15040)
* chore: add error recovery option to LightningCSSOptions (#17420) ([e04193f](https://github.com/vitejs/vite/commit/e04193f)), closes [#17420](https://github.com/vitejs/vite/issues/17420)
* chore: add funding field (#13585) ([2501627](https://github.com/vitejs/vite/commit/2501627)), closes [#13585](https://github.com/vitejs/vite/issues/13585)
* chore: add jsdoc default value (#11746) ([8c87af7](https://github.com/vitejs/vite/commit/8c87af7)), closes [#11746](https://github.com/vitejs/vite/issues/11746)
* chore: add note about assets to importAnalysis.ts (#6278) ([05e71d5](https://github.com/vitejs/vite/commit/05e71d5)), closes [#6278](https://github.com/vitejs/vite/issues/6278)
* chore: add notes to 4.4.0-beta.1 changelog (#13586) ([097c583](https://github.com/vitejs/vite/commit/097c583)), closes [#13586](https://github.com/vitejs/vite/issues/13586)
* chore: add package.json to export map (#8838) ([cbefc63](https://github.com/vitejs/vite/commit/cbefc63)), closes [#8838](https://github.com/vitejs/vite/issues/8838)
* chore: add region comment (#17370) ([a8c7083](https://github.com/vitejs/vite/commit/a8c7083)), closes [#17370](https://github.com/vitejs/vite/issues/17370)
* chore: adjust comments/typos (#9325) ([ffb2ba3](https://github.com/vitejs/vite/commit/ffb2ba3)), closes [#9325](https://github.com/vitejs/vite/issues/9325)
* chore: avoid bundling resolve dep (#15570) ([ae49ac4](https://github.com/vitejs/vite/commit/ae49ac4)), closes [#15570](https://github.com/vitejs/vite/issues/15570)
* chore: better error hint for data URI mime type (#12496) ([0cb9171](https://github.com/vitejs/vite/commit/0cb9171)), closes [#12496](https://github.com/vitejs/vite/issues/12496)
* chore: build signatures (#6841) ([0941620](https://github.com/vitejs/vite/commit/0941620)), closes [#6841](https://github.com/vitejs/vite/issues/6841)
* chore: build time message setting color (#12940) ([ada7cd5](https://github.com/vitejs/vite/commit/ada7cd5)), closes [#12940](https://github.com/vitejs/vite/issues/12940)
* chore: bump minors and rebuild lock (#8074) ([aeb5b74](https://github.com/vitejs/vite/commit/aeb5b74)), closes [#8074](https://github.com/vitejs/vite/issues/8074)
* chore: changelog edits for 4.2 (#12438) ([ce047e3](https://github.com/vitejs/vite/commit/ce047e3)), closes [#12438](https://github.com/vitejs/vite/issues/12438)
* chore: changelog for 2.7-beta-0 (#5500) ([9f1f221](https://github.com/vitejs/vite/commit/9f1f221)), closes [#5500](https://github.com/vitejs/vite/issues/5500)
* chore: changelog notes and clean for 4.4 (#13728) ([3f4e36e](https://github.com/vitejs/vite/commit/3f4e36e)), closes [#13728](https://github.com/vitejs/vite/issues/13728)
* chore: clarify writableEnded guard comment (#7256) ([dddda1e](https://github.com/vitejs/vite/commit/dddda1e)), closes [#7256](https://github.com/vitejs/vite/issues/7256)
* chore: clean debug log ([efe003c](https://github.com/vitejs/vite/commit/efe003c))
* chore: clean up 4.3 changelog ([55ec023](https://github.com/vitejs/vite/commit/55ec023))
* chore: clean up changelog, downgrade conventional-changelog-cli to v2 (#13566) ([435bacc](https://github.com/vitejs/vite/commit/435bacc)), closes [#13566](https://github.com/vitejs/vite/issues/13566)
* chore: cleanup #5601 (#5672) ([3ba3e2c](https://github.com/vitejs/vite/commit/3ba3e2c)), closes [#5601](https://github.com/vitejs/vite/issues/5601) [#5672](https://github.com/vitejs/vite/issues/5672)
* chore: cleanup now that we've dropped Node 12 (#8239) ([29659a0](https://github.com/vitejs/vite/commit/29659a0)), closes [#8239](https://github.com/vitejs/vite/issues/8239)
* chore: cleanup old changelogs (#10056) ([9e65a41](https://github.com/vitejs/vite/commit/9e65a41)), closes [#10056](https://github.com/vitejs/vite/issues/10056)
* chore: cleanup PluginContext Omit (#10902) ([361c3cd](https://github.com/vitejs/vite/commit/361c3cd)), closes [#10902](https://github.com/vitejs/vite/issues/10902)
* chore: cleanup v5 beta changelog (#14694) ([531d3cb](https://github.com/vitejs/vite/commit/531d3cb)), closes [#14694](https://github.com/vitejs/vite/issues/14694)
* chore: clear dist before build (#5331) ([939e384](https://github.com/vitejs/vite/commit/939e384)), closes [#5331](https://github.com/vitejs/vite/issues/5331)
* chore: code structure (#7790) ([5f7fe00](https://github.com/vitejs/vite/commit/5f7fe00)), closes [#7790](https://github.com/vitejs/vite/issues/7790)
* chore: collapse alpha version in v3 beta changelog (#8697) ([83286dd](https://github.com/vitejs/vite/commit/83286dd)), closes [#8697](https://github.com/vitejs/vite/issues/8697)
* chore: comment typo (#7344) ([61df324](https://github.com/vitejs/vite/commit/61df324)), closes [#7344](https://github.com/vitejs/vite/issues/7344)
* chore: consolidate changelog for 5.3 (#17476) ([1f09344](https://github.com/vitejs/vite/commit/1f09344)), closes [#17476](https://github.com/vitejs/vite/issues/17476)
* chore: convert scripts to TS (#6160) ([15b6f1b](https://github.com/vitejs/vite/commit/15b6f1b)), closes [#6160](https://github.com/vitejs/vite/issues/6160)
* chore: correct 2.8 beta changelog link ([3949d21](https://github.com/vitejs/vite/commit/3949d21))
* chore: correct changelog size note ([12ff293](https://github.com/vitejs/vite/commit/12ff293))
* chore: correct config transpile comment (#5735) ([4ffc9a5](https://github.com/vitejs/vite/commit/4ffc9a5)), closes [#5735](https://github.com/vitejs/vite/issues/5735)
* chore: correct typo in console message (#8618) ([13d05bd](https://github.com/vitejs/vite/commit/13d05bd)), closes [#8618](https://github.com/vitejs/vite/issues/8618)
* chore: delete extra blank line (#6152) ([39c252e](https://github.com/vitejs/vite/commit/39c252e)), closes [#6152](https://github.com/vitejs/vite/issues/6152)
* chore: delete useless condition (#5772) ([5588eb9](https://github.com/vitejs/vite/commit/5588eb9)), closes [#5772](https://github.com/vitejs/vite/issues/5772)
* chore: deprecate `rollupOptions.output.output` to avoid subtle errors (#5930) ([e3a1aa5](https://github.com/vitejs/vite/commit/e3a1aa5)), closes [#5930](https://github.com/vitejs/vite/issues/5930) [/github.com/vitejs/vite/issues/5812#issuecomment-984345618](https://github.com//github.com/vitejs/vite/issues/5812/issues/issuecomment-984345618)
* chore: deprecate splitVendorChunkPlugin (#16274) ([45a06da](https://github.com/vitejs/vite/commit/45a06da)), closes [#16274](https://github.com/vitejs/vite/issues/16274)
* chore: deprecated substr (#5917) ([08a1ec7](https://github.com/vitejs/vite/commit/08a1ec7)), closes [#5917](https://github.com/vitejs/vite/issues/5917)
* chore: enable `@typescript-eslint/ban-ts-comment` (#11326) ([e58a4f0](https://github.com/vitejs/vite/commit/e58a4f0)), closes [#11326](https://github.com/vitejs/vite/issues/11326)
* chore: enable `@typescript-eslint/explicit-module-boundary-types` (#8372) ([104caf9](https://github.com/vitejs/vite/commit/104caf9)), closes [#8372](https://github.com/vitejs/vite/issues/8372)
* chore: enable `import/no-duplicates` eslint rule (#8199) ([11243de](https://github.com/vitejs/vite/commit/11243de)), closes [#8199](https://github.com/vitejs/vite/issues/8199)
* chore: enable eslint and prettier cache (#8585) ([d7beaeb](https://github.com/vitejs/vite/commit/d7beaeb)), closes [#8585](https://github.com/vitejs/vite/issues/8585)
* chore: enable prettier trailing commas (#11167) ([134ce68](https://github.com/vitejs/vite/commit/134ce68)), closes [#11167](https://github.com/vitejs/vite/issues/11167)
* chore: enable reportUnusedDisableDirectives (#8384) ([9a99bc4](https://github.com/vitejs/vite/commit/9a99bc4)), closes [#8384](https://github.com/vitejs/vite/issues/8384)
* chore: explain why `new CSSStyleSheet` feature detection is disabled (#6774) ([5306234](https://github.com/vitejs/vite/commit/5306234)), closes [#6774](https://github.com/vitejs/vite/issues/6774)
* chore: extract DEFAULT_DEV_PORT and DEFAULT_PREVIEW_PORT (#11669) ([c9f009d](https://github.com/vitejs/vite/commit/c9f009d)), closes [#11669](https://github.com/vitejs/vite/issues/11669)
* chore: fix changelog compare links (#14695) ([cc6ac1e](https://github.com/vitejs/vite/commit/cc6ac1e)), closes [#14695](https://github.com/vitejs/vite/issues/14695)
* chore: fix code typos (#9033) ([ed02861](https://github.com/vitejs/vite/commit/ed02861)), closes [#9033](https://github.com/vitejs/vite/issues/9033)
* chore: fix dev build replacing undefined (#10740) ([1358a3c](https://github.com/vitejs/vite/commit/1358a3c)), closes [#10740](https://github.com/vitejs/vite/issues/10740)
* chore: fix eslint warnings (#14031) ([4021a0e](https://github.com/vitejs/vite/commit/4021a0e)), closes [#14031](https://github.com/vitejs/vite/issues/14031)
* chore: fix format (#11311) ([9c2b1c0](https://github.com/vitejs/vite/commit/9c2b1c0)), closes [#11311](https://github.com/vitejs/vite/issues/11311)
* chore: fix pnpm bug with version-less workspace (#13700) ([e48d35d](https://github.com/vitejs/vite/commit/e48d35d)), closes [#13700](https://github.com/vitejs/vite/issues/13700)
* chore: fix repeated error message (#8153) ([63ec05a](https://github.com/vitejs/vite/commit/63ec05a)), closes [#8153](https://github.com/vitejs/vite/issues/8153)
* chore: fix resolve debug log timing (#12746) ([22f6ae6](https://github.com/vitejs/vite/commit/22f6ae6)), closes [#12746](https://github.com/vitejs/vite/issues/12746)
* chore: fix some comments (#17495) ([ec16a5e](https://github.com/vitejs/vite/commit/ec16a5e)), closes [#17495](https://github.com/vitejs/vite/issues/17495)
* chore: fix term cases (#7553) ([c296130](https://github.com/vitejs/vite/commit/c296130)), closes [#7553](https://github.com/vitejs/vite/issues/7553)
* chore: fix test misc (#12392) ([a595b11](https://github.com/vitejs/vite/commit/a595b11)), closes [#12392](https://github.com/vitejs/vite/issues/12392)
* chore: fix test optimizeDeps at build time flag (#9004) ([9363872](https://github.com/vitejs/vite/commit/9363872)), closes [#9004](https://github.com/vitejs/vite/issues/9004)
* chore: fix test run in dev (#11214) ([c747a3f](https://github.com/vitejs/vite/commit/c747a3f)), closes [#11214](https://github.com/vitejs/vite/issues/11214)
* chore: fix ts error (#14053) ([6cb397f](https://github.com/vitejs/vite/commit/6cb397f)), closes [#14053](https://github.com/vitejs/vite/issues/14053)
* chore: fix type warning during building vite (#11673) ([305b76e](https://github.com/vitejs/vite/commit/305b76e)), closes [#11673](https://github.com/vitejs/vite/issues/11673)
* chore: fix typo (#14820) ([eda1247](https://github.com/vitejs/vite/commit/eda1247)), closes [#14820](https://github.com/vitejs/vite/issues/14820)
* chore: fix typo (#5033) ([2c58616](https://github.com/vitejs/vite/commit/2c58616)), closes [#5033](https://github.com/vitejs/vite/issues/5033)
* chore: fix typo (#5697) ([1e079f4](https://github.com/vitejs/vite/commit/1e079f4)), closes [#5697](https://github.com/vitejs/vite/issues/5697)
* chore: fix typo (#5768) ([d383112](https://github.com/vitejs/vite/commit/d383112)), closes [#5768](https://github.com/vitejs/vite/issues/5768)
* chore: fix typo in comment (#7370) ([e682863](https://github.com/vitejs/vite/commit/e682863)), closes [#7370](https://github.com/vitejs/vite/issues/7370)
* chore: fix typo in console warning message (#14519) ([ad9718d](https://github.com/vitejs/vite/commit/ad9718d)), closes [#14519](https://github.com/vitejs/vite/issues/14519)
* chore: fix typo in error message (#9645) ([7121ee0](https://github.com/vitejs/vite/commit/7121ee0)), closes [#9645](https://github.com/vitejs/vite/issues/9645)
* chore: fix typos (#12032) ([ee1a686](https://github.com/vitejs/vite/commit/ee1a686)), closes [#12032](https://github.com/vitejs/vite/issues/12032)
* chore: fix typos (#13862) ([f54e8da](https://github.com/vitejs/vite/commit/f54e8da)), closes [#13862](https://github.com/vitejs/vite/issues/13862)
* chore: fix worker sourcemap output style (#7805) ([17f3be7](https://github.com/vitejs/vite/commit/17f3be7)), closes [#7805](https://github.com/vitejs/vite/issues/7805)
* chore: format (#4931) ([e59997f](https://github.com/vitejs/vite/commit/e59997f)), closes [#4931](https://github.com/vitejs/vite/issues/4931)
* chore: format (#5459) ([484aad5](https://github.com/vitejs/vite/commit/484aad5)), closes [#5459](https://github.com/vitejs/vite/issues/5459)
* chore: format & check with prettier (#5869) ([c344865](https://github.com/vitejs/vite/commit/c344865)), closes [#5869](https://github.com/vitejs/vite/issues/5869)
* chore: format and fix typo (#5718) ([5987a77](https://github.com/vitejs/vite/commit/5987a77)), closes [#5718](https://github.com/vitejs/vite/issues/5718)
* chore: format css minify esbuild error (#7731) ([c445075](https://github.com/vitejs/vite/commit/c445075)), closes [#7731](https://github.com/vitejs/vite/issues/7731)
* chore: generate vite sourcemap when not production (#8453) ([129b499](https://github.com/vitejs/vite/commit/129b499)), closes [#8453](https://github.com/vitejs/vite/issues/8453)
* chore: ignore ts warning (#9015) ([e2a6bf4](https://github.com/vitejs/vite/commit/e2a6bf4)), closes [#9015](https://github.com/vitejs/vite/issues/9015)
* chore: improve debug log filtering (#12763) ([da1cb02](https://github.com/vitejs/vite/commit/da1cb02)), closes [#12763](https://github.com/vitejs/vite/issues/12763)
* chore: improve html plugin name (#5158) ([e8a1d19](https://github.com/vitejs/vite/commit/e8a1d19)), closes [#5158](https://github.com/vitejs/vite/issues/5158)
* chore: improve jsdoc of library options (#8381) ([44dc27d](https://github.com/vitejs/vite/commit/44dc27d)), closes [#8381](https://github.com/vitejs/vite/issues/8381)
* chore: improve local variable url is redundant (#5769) ([4a6cf35](https://github.com/vitejs/vite/commit/4a6cf35)), closes [#5769](https://github.com/vitejs/vite/issues/5769)
* chore: improve public assets warning message (#6738) ([f6bd317](https://github.com/vitejs/vite/commit/f6bd317)), closes [#6738](https://github.com/vitejs/vite/issues/6738)
* chore: improve v4 beta release notes (#11215) ([f24679c](https://github.com/vitejs/vite/commit/f24679c)), closes [#11215](https://github.com/vitejs/vite/issues/11215)
* chore: include 2.9.10-2.9.12 changelog in main (#8535) ([87f58ad](https://github.com/vitejs/vite/commit/87f58ad)), closes [#8535](https://github.com/vitejs/vite/issues/8535)
* chore: include 2.9.13-2.9.14 changelog in main (#9053) ([f020066](https://github.com/vitejs/vite/commit/f020066)), closes [#9053](https://github.com/vitejs/vite/issues/9053)
* chore: include 2.9.9 changelog in main (#8250) ([48f03e0](https://github.com/vitejs/vite/commit/48f03e0)), closes [#8250](https://github.com/vitejs/vite/issues/8250)
* chore: init imports var before use (#9569) ([905b8eb](https://github.com/vitejs/vite/commit/905b8eb)), closes [#9569](https://github.com/vitejs/vite/issues/9569)
* chore: inline selfsigned license (#6530) ([d303264](https://github.com/vitejs/vite/commit/d303264)), closes [#6530](https://github.com/vitejs/vite/issues/6530)
* chore: join URL segments more safely (#10590) ([675bf07](https://github.com/vitejs/vite/commit/675bf07)), closes [#10590](https://github.com/vitejs/vite/issues/10590)
* chore: link migration guide to changelog (#14699) ([4cedcdc](https://github.com/vitejs/vite/commit/4cedcdc)), closes [#14699](https://github.com/vitejs/vite/issues/14699)
* chore: move playground to root (#8072) ([875fc11](https://github.com/vitejs/vite/commit/875fc11)), closes [#8072](https://github.com/vitejs/vite/issues/8072)
* chore: move to eslint flat config (#16743) ([8f16765](https://github.com/vitejs/vite/commit/8f16765)), closes [#16743](https://github.com/vitejs/vite/issues/16743)
* chore: narrow down rollup version (#9637) ([fcf4d98](https://github.com/vitejs/vite/commit/fcf4d98)), closes [#9637](https://github.com/vitejs/vite/issues/9637)
* chore: new line for non-existent url (#7308) ([522faf8](https://github.com/vitejs/vite/commit/522faf8)), closes [#7308](https://github.com/vitejs/vite/issues/7308)
* chore: next replace core (#6664) ([8338e26](https://github.com/vitejs/vite/commit/8338e26)), closes [#6664](https://github.com/vitejs/vite/issues/6664)
* chore: node prefix lint (#9514) ([9e9cd23](https://github.com/vitejs/vite/commit/9e9cd23)), closes [#9514](https://github.com/vitejs/vite/issues/9514)
* chore: optimize esm flag (#5778) ([a32b105](https://github.com/vitejs/vite/commit/a32b105)), closes [#5778](https://github.com/vitejs/vite/issues/5778)
* chore: output tsconfck debug log (#9768) ([9206ad7](https://github.com/vitejs/vite/commit/9206ad7)), closes [#9768](https://github.com/vitejs/vite/issues/9768)
* chore: post 5.1 release edits (#15840) ([9da6502](https://github.com/vitejs/vite/commit/9da6502)), closes [#15840](https://github.com/vitejs/vite/issues/15840)
* chore: prefer type imports (#5835) ([7186857](https://github.com/vitejs/vite/commit/7186857)), closes [#5835](https://github.com/vitejs/vite/issues/5835)
* chore: prefer using nullish-coalescing over or logic operator (#6790) ([0e58e72](https://github.com/vitejs/vite/commit/0e58e72)), closes [#6790](https://github.com/vitejs/vite/issues/6790)
* chore: prefer using weakmap over writing field on nodes (#6788) ([4a883a4](https://github.com/vitejs/vite/commit/4a883a4)), closes [#6788](https://github.com/vitejs/vite/issues/6788)
* chore: prettier format (#5121) ([16fc894](https://github.com/vitejs/vite/commit/16fc894)), closes [#5121](https://github.com/vitejs/vite/issues/5121)
* chore: proxy bypass do nothing with object result (#10209) ([934a304](https://github.com/vitejs/vite/commit/934a304)), closes [#10209](https://github.com/vitejs/vite/issues/10209)
* chore: reapply #5930 (#8423) ([ab23e6e](https://github.com/vitejs/vite/commit/ab23e6e)), closes [#5930](https://github.com/vitejs/vite/issues/5930) [#8423](https://github.com/vitejs/vite/issues/8423)
* chore: reduce one if judgment (#14331) ([d0eb803](https://github.com/vitejs/vite/commit/d0eb803)), closes [#14331](https://github.com/vitejs/vite/issues/14331)
* chore: reduce the usage of require (#8121) ([67ff257](https://github.com/vitejs/vite/commit/67ff257)), closes [#8121](https://github.com/vitejs/vite/issues/8121)
* chore: refactor as functions ([5684382](https://github.com/vitejs/vite/commit/5684382))
* chore: refactor interop named imports (#8544) ([63b523a](https://github.com/vitejs/vite/commit/63b523a)), closes [#8544](https://github.com/vitejs/vite/issues/8544)
* chore: release notes (#15777) ([775bb50](https://github.com/vitejs/vite/commit/775bb50)), closes [#15777](https://github.com/vitejs/vite/issues/15777)
* chore: remove acorn plugins (#6275) ([eb08ec5](https://github.com/vitejs/vite/commit/eb08ec5)), closes [#6275](https://github.com/vitejs/vite/issues/6275)
* chore: remove build warn filter (#12391) ([0755cf2](https://github.com/vitejs/vite/commit/0755cf2)), closes [#12391](https://github.com/vitejs/vite/issues/12391)
* chore: remove cacheDir param (#10188) ([6eb374a](https://github.com/vitejs/vite/commit/6eb374a)), closes [#10188](https://github.com/vitejs/vite/issues/10188)
* chore: remove custom vitepress config (#9785) ([b2c0ee0](https://github.com/vitejs/vite/commit/b2c0ee0)), closes [#9785](https://github.com/vitejs/vite/issues/9785)
* chore: remove extra ) in changelog (#12932) ([e7924d2](https://github.com/vitejs/vite/commit/e7924d2)), closes [#12932](https://github.com/vitejs/vite/issues/12932)
* chore: remove maybeVirtualHtmlSet (#8010) ([e85164e](https://github.com/vitejs/vite/commit/e85164e)), closes [#8010](https://github.com/vitejs/vite/issues/8010)
* chore: remove no longer needed type shim ([5acc277](https://github.com/vitejs/vite/commit/5acc277))
* chore: remove non used type definitions (#10738) ([ee8c7a6](https://github.com/vitejs/vite/commit/ee8c7a6)), closes [#10738](https://github.com/vitejs/vite/issues/10738)
* chore: remove noop watch close (#6294) ([5484c8c](https://github.com/vitejs/vite/commit/5484c8c)), closes [#6294](https://github.com/vitejs/vite/issues/6294)
* chore: remove outdated documentation (#5700) ([162c9a0](https://github.com/vitejs/vite/commit/162c9a0)), closes [#5700](https://github.com/vitejs/vite/issues/5700)
* chore: remove parameters that are not used (#10747) ([df8e476](https://github.com/vitejs/vite/commit/df8e476)), closes [#10747](https://github.com/vitejs/vite/issues/10747)
* chore: remove rollup `namespaceToStringTag` (#8569) ([b85802a](https://github.com/vitejs/vite/commit/b85802a)), closes [#8569](https://github.com/vitejs/vite/issues/8569)
* chore: remove src/client from package (#10703) ([816842e](https://github.com/vitejs/vite/commit/816842e)), closes [#10703](https://github.com/vitejs/vite/issues/10703)
* chore: remove unneccessary eslint-disable-next-line regexp/no-unused-capturing-group (#15247) ([35a5bcf](https://github.com/vitejs/vite/commit/35a5bcf)), closes [#15247](https://github.com/vitejs/vite/issues/15247)
* chore: remove unneded async in resolveId hook (#12499) ([e6337aa](https://github.com/vitejs/vite/commit/e6337aa)), closes [#12499](https://github.com/vitejs/vite/issues/12499)
* chore: remove unneeded condition in getRealPath (#15267) ([8e4655c](https://github.com/vitejs/vite/commit/8e4655c)), closes [#15267](https://github.com/vitejs/vite/issues/15267)
* chore: remove unneeded normalizePath (#15713) ([92f2747](https://github.com/vitejs/vite/commit/92f2747)), closes [#15713](https://github.com/vitejs/vite/issues/15713)
* chore: remove unneeded worker context param (#8268) ([30a7acc](https://github.com/vitejs/vite/commit/30a7acc)), closes [#8268](https://github.com/vitejs/vite/issues/8268)
* chore: remove unused `module` field in `package.json` (#11698) ([595b55f](https://github.com/vitejs/vite/commit/595b55f)), closes [#11698](https://github.com/vitejs/vite/issues/11698)
* chore: remove unused code (#7303) ([467512b](https://github.com/vitejs/vite/commit/467512b)), closes [#7303](https://github.com/vitejs/vite/issues/7303)
* chore: remove unused dts from dist (#8346) ([de9f556](https://github.com/vitejs/vite/commit/de9f556)), closes [#8346](https://github.com/vitejs/vite/issues/8346)
* chore: remove unused timestamp option (#8545) ([d641860](https://github.com/vitejs/vite/commit/d641860)), closes [#8545](https://github.com/vitejs/vite/issues/8545)
* chore: remove useless cli option (#5653) ([68e8e35](https://github.com/vitejs/vite/commit/68e8e35)), closes [#5653](https://github.com/vitejs/vite/issues/5653)
* chore: remove useless dep (#13165) ([9a7ec98](https://github.com/vitejs/vite/commit/9a7ec98)), closes [#13165](https://github.com/vitejs/vite/issues/13165)
* chore: replace 'some' with 'includes' in resolveEnvPrefix (#15220) ([ee12f30](https://github.com/vitejs/vite/commit/ee12f30)), closes [#15220](https://github.com/vitejs/vite/issues/15220)
* chore: replace `any` with `string` (#13850) ([4606fd8](https://github.com/vitejs/vite/commit/4606fd8)), closes [#13850](https://github.com/vitejs/vite/issues/13850)
* chore: replace mime with mrmime (#6312) ([8bdb184](https://github.com/vitejs/vite/commit/8bdb184)), closes [#6312](https://github.com/vitejs/vite/issues/6312)
* chore: replace source-map with source-map-js (#6556) ([7b95f4d](https://github.com/vitejs/vite/commit/7b95f4d)), closes [#6556](https://github.com/vitejs/vite/issues/6556)
* chore: replace SourceMapConsumer with trace-mapping (#6746) ([ed4d191](https://github.com/vitejs/vite/commit/ed4d191)), closes [#6746](https://github.com/vitejs/vite/issues/6746)
* chore: resolve ssr options (#8455) ([d97e402](https://github.com/vitejs/vite/commit/d97e402)), closes [#8455](https://github.com/vitejs/vite/issues/8455)
* chore: revert "feat: show warning to discourage putting process/global to `define` option (#14447)"  ([0426910](https://github.com/vitejs/vite/commit/0426910)), closes [#14447](https://github.com/vitejs/vite/issues/14447) [#14827](https://github.com/vitejs/vite/issues/14827)
* chore: revert "fix: don't add `?import` for `@vite-ignore`ed import (#14851)" (#14866) ([6516607](https://github.com/vitejs/vite/commit/6516607)), closes [#14851](https://github.com/vitejs/vite/issues/14851) [#14866](https://github.com/vitejs/vite/issues/14866)
* chore: revert #10196 until Vite 4 (#10574) ([07c0336](https://github.com/vitejs/vite/commit/07c0336)), closes [#10196](https://github.com/vitejs/vite/issues/10196) [#10574](https://github.com/vitejs/vite/issues/10574)
* chore: revert #15746 (#15839) ([ed875f8](https://github.com/vitejs/vite/commit/ed875f8)), closes [#15746](https://github.com/vitejs/vite/issues/15746) [#15839](https://github.com/vitejs/vite/issues/15839)
* chore: revert custom license resolve (#12709) ([621bb2f](https://github.com/vitejs/vite/commit/621bb2f)), closes [#12709](https://github.com/vitejs/vite/issues/12709)
* chore: revert prev release commit ([2a30a07](https://github.com/vitejs/vite/commit/2a30a07))
* chore: revert removed line in #7698 ([7e6a2c8](https://github.com/vitejs/vite/commit/7e6a2c8)), closes [#7698](https://github.com/vitejs/vite/issues/7698)
* chore: revert vitejs/vite#8152 (#8161) ([85b8b55](https://github.com/vitejs/vite/commit/85b8b55)), closes [vitejs/vite#8152](https://github.com/vitejs/vite/issues/8152) [#8161](https://github.com/vitejs/vite/issues/8161)
* chore: revise typo (#5233) ([a3f2238](https://github.com/vitejs/vite/commit/a3f2238)), closes [#5233](https://github.com/vitejs/vite/issues/5233)
* chore: rework v2.8.0 changelog and add release notes (#6825) ([8e92aa7](https://github.com/vitejs/vite/commit/8e92aa7)), closes [#6825](https://github.com/vitejs/vite/issues/6825)
* chore: scanner after server listen (#9020) ([53799e1](https://github.com/vitejs/vite/commit/53799e1)), closes [#9020](https://github.com/vitejs/vite/issues/9020)
* chore: set target in tsconfig.check.json (#12675) ([15177a1](https://github.com/vitejs/vite/commit/15177a1)), closes [#12675](https://github.com/vitejs/vite/issues/12675)
* chore: show error position (#13623) ([90271a6](https://github.com/vitejs/vite/commit/90271a6)), closes [#13623](https://github.com/vitejs/vite/issues/13623)
* chore: show ws port conflict error (#8209) ([c86329b](https://github.com/vitejs/vite/commit/c86329b)), closes [#8209](https://github.com/vitejs/vite/issues/8209)
* chore: shrink genSourceMapUrl type (#11667) ([9fb406b](https://github.com/vitejs/vite/commit/9fb406b)), closes [#11667](https://github.com/vitejs/vite/issues/11667)
* chore: simplify filter plugin code (#10459) ([5d9b810](https://github.com/vitejs/vite/commit/5d9b810)), closes [#10459](https://github.com/vitejs/vite/issues/10459)
* chore: stabilize experimental api (#7707) ([b902932](https://github.com/vitejs/vite/commit/b902932)), closes [#7707](https://github.com/vitejs/vite/issues/7707)
* chore: temporary typo (#15329) ([7b71854](https://github.com/vitejs/vite/commit/7b71854)), closes [#15329](https://github.com/vitejs/vite/issues/15329)
* chore: tidy up eslint config (#9468) ([f4addcf](https://github.com/vitejs/vite/commit/f4addcf)), closes [#9468](https://github.com/vitejs/vite/issues/9468)
* chore: tweak server start output (#8582) ([3439132](https://github.com/vitejs/vite/commit/3439132)), closes [#8582](https://github.com/vitejs/vite/issues/8582)
* chore: type unknown env as any (#7702) ([23fdef1](https://github.com/vitejs/vite/commit/23fdef1)), closes [#7702](https://github.com/vitejs/vite/issues/7702)
* chore: typecheck create-vite (#11295) ([af86e5b](https://github.com/vitejs/vite/commit/af86e5b)), closes [#11295](https://github.com/vitejs/vite/issues/11295)
* chore: typo (#7520) ([4fda42f](https://github.com/vitejs/vite/commit/4fda42f)), closes [#7520](https://github.com/vitejs/vite/issues/7520)
* chore: unpin rollup (#11204) ([014e4aa](https://github.com/vitejs/vite/commit/014e4aa)), closes [#11204](https://github.com/vitejs/vite/issues/11204)
* chore: unresolved deps for client build ([9e3bb65](https://github.com/vitejs/vite/commit/9e3bb65))
* chore: update @types/node to v18 (#11195) ([4ec9f53](https://github.com/vitejs/vite/commit/4ec9f53)), closes [#11195](https://github.com/vitejs/vite/issues/11195)
* chore: update 3.1 changelog (#9994) ([44dbcbe](https://github.com/vitejs/vite/commit/44dbcbe)), closes [#9994](https://github.com/vitejs/vite/issues/9994)
* chore: update changelog for 2.7 (#5985) ([1102789](https://github.com/vitejs/vite/commit/1102789)), closes [#5985](https://github.com/vitejs/vite/issues/5985)
* chore: update changelog for 3.2 (#10646) ([f787a60](https://github.com/vitejs/vite/commit/f787a60)), closes [#10646](https://github.com/vitejs/vite/issues/10646)
* chore: update changelog release notes for 4.0 (#11285) ([83abd37](https://github.com/vitejs/vite/commit/83abd37)), closes [#11285](https://github.com/vitejs/vite/issues/11285)
* chore: update comments (#8394) ([3d14372](https://github.com/vitejs/vite/commit/3d14372)), closes [#8394](https://github.com/vitejs/vite/issues/8394)
* chore: update deprecation warnings for improved migration DX (#8866) ([4eb2348](https://github.com/vitejs/vite/commit/4eb2348)), closes [#8866](https://github.com/vitejs/vite/issues/8866)
* chore: update es-module-lexer (#7357) ([fde0f3c](https://github.com/vitejs/vite/commit/fde0f3c)), closes [#7357](https://github.com/vitejs/vite/issues/7357)
* chore: update esbuild to 0.16.2 (#11265) ([e1d8d46](https://github.com/vitejs/vite/commit/e1d8d46)), closes [#11265](https://github.com/vitejs/vite/issues/11265)
* chore: update license ([d58c030](https://github.com/vitejs/vite/commit/d58c030))
* chore: update license (#11476) ([3d346c0](https://github.com/vitejs/vite/commit/3d346c0)), closes [#11476](https://github.com/vitejs/vite/issues/11476)
* chore: update license (#14790) ([ac5d8a7](https://github.com/vitejs/vite/commit/ac5d8a7)), closes [#14790](https://github.com/vitejs/vite/issues/14790)
* chore: update license file (#15885) ([d9adf18](https://github.com/vitejs/vite/commit/d9adf18)), closes [#15885](https://github.com/vitejs/vite/issues/15885)
* chore: update magic-string (#10364) ([23c9259](https://github.com/vitejs/vite/commit/23c9259)), closes [#10364](https://github.com/vitejs/vite/issues/10364)
* chore: update major deps (#8572) ([0e20949](https://github.com/vitejs/vite/commit/0e20949)), closes [#8572](https://github.com/vitejs/vite/issues/8572)
* chore: update manually bumped deps (#14430) ([995c4b6](https://github.com/vitejs/vite/commit/995c4b6)), closes [#14430](https://github.com/vitejs/vite/issues/14430)
* chore: update packages' (vite, vite-legacy) keywords (#11402) ([a56bc34](https://github.com/vitejs/vite/commit/a56bc34)), closes [#11402](https://github.com/vitejs/vite/issues/11402)
* chore: update region comment (#16380) ([77562c3](https://github.com/vitejs/vite/commit/77562c3)), closes [#16380](https://github.com/vitejs/vite/issues/16380)
* chore: update rollup (#11710) ([193d55c](https://github.com/vitejs/vite/commit/193d55c)), closes [#11710](https://github.com/vitejs/vite/issues/11710)
* chore: update the website url for homepage in package.json (#15181) ([282bd8f](https://github.com/vitejs/vite/commit/282bd8f)), closes [#15181](https://github.com/vitejs/vite/issues/15181)
* chore: update tips and docs (#5116) ([789130b](https://github.com/vitejs/vite/commit/789130b)), closes [#5116](https://github.com/vitejs/vite/issues/5116)
* chore: update tsconfck to 2.1.0 to add support for typescript 5 config syntax (#12401) ([3f1c379](https://github.com/vitejs/vite/commit/3f1c379)), closes [#12401](https://github.com/vitejs/vite/issues/12401)
* chore: update type init (#10251) ([ed40a65](https://github.com/vitejs/vite/commit/ed40a65)), closes [#10251](https://github.com/vitejs/vite/issues/10251)
* chore: update vitest to 1.0.0-beta.6 (#15194) ([2fce647](https://github.com/vitejs/vite/commit/2fce647)), closes [#15194](https://github.com/vitejs/vite/issues/15194)
* chore: upgrade babel and release-scripts (#14330) ([b361ffa](https://github.com/vitejs/vite/commit/b361ffa)), closes [#14330](https://github.com/vitejs/vite/issues/14330)
* chore: upgrade rollup (#12965) ([bdb2f25](https://github.com/vitejs/vite/commit/bdb2f25)), closes [#12965](https://github.com/vitejs/vite/issues/12965)
* chore: upgrade rollup 3.20.0 (#12497) ([7288a24](https://github.com/vitejs/vite/commit/7288a24)), closes [#12497](https://github.com/vitejs/vite/issues/12497)
* chore: upgrade rollup to 3.25.2 (#13608) ([5497abe](https://github.com/vitejs/vite/commit/5497abe)), closes [#13608](https://github.com/vitejs/vite/issues/13608)
* chore: upgrade to pnpm v7 (#8041) ([50f8f3b](https://github.com/vitejs/vite/commit/50f8f3b)), closes [#8041](https://github.com/vitejs/vite/issues/8041)
* chore: upgrade to Rollup 3.18 (#12283) ([cde9191](https://github.com/vitejs/vite/commit/cde9191)), closes [#12283](https://github.com/vitejs/vite/issues/12283)
* chore: use 'new URL' instead of 'url.parse' (#8254) ([d98c8a7](https://github.com/vitejs/vite/commit/d98c8a7)), closes [#8254](https://github.com/vitejs/vite/issues/8254)
* chore: use "kB" everywhere with the correct definition (#14061) ([f97ef58](https://github.com/vitejs/vite/commit/f97ef58)), closes [#14061](https://github.com/vitejs/vite/issues/14061)
* chore: use `@polka/compression` (#16146) ([592c95a](https://github.com/vitejs/vite/commit/592c95a)), closes [#16146](https://github.com/vitejs/vite/issues/16146)
* chore: use `esno` to replace `ts-node` (#8162) ([c18a5f3](https://github.com/vitejs/vite/commit/c18a5f3)), closes [#8162](https://github.com/vitejs/vite/issues/8162)
* chore: use `tsx` directly instead of indirect `esno` (#8773) ([f018f13](https://github.com/vitejs/vite/commit/f018f13)), closes [#8773](https://github.com/vitejs/vite/issues/8773)
* chore: use `unbuild` to bundle plugins (#8139) ([638b168](https://github.com/vitejs/vite/commit/638b168)), closes [#8139](https://github.com/vitejs/vite/issues/8139)
* chore: use cjs extension with scripts (#5877) ([775baba](https://github.com/vitejs/vite/commit/775baba)), closes [#5877](https://github.com/vitejs/vite/issues/5877)
* chore: use forge partially to generate certificates (#6325) ([dd8869b](https://github.com/vitejs/vite/commit/dd8869b)), closes [#6325](https://github.com/vitejs/vite/issues/6325)
* chore: use isArray to check array (#10953) ([02c334a](https://github.com/vitejs/vite/commit/02c334a)), closes [#10953](https://github.com/vitejs/vite/issues/10953)
* chore: use isScannable in optimizer scan (#7641) ([f18eedf](https://github.com/vitejs/vite/commit/f18eedf)), closes [#7641](https://github.com/vitejs/vite/issues/7641)
* chore: use jsdoc's default tag (#11725) ([a6df6b4](https://github.com/vitejs/vite/commit/a6df6b4)), closes [#11725](https://github.com/vitejs/vite/issues/11725)
* chore: use node prefix (#8309) ([60721ac](https://github.com/vitejs/vite/commit/60721ac)), closes [#8309](https://github.com/vitejs/vite/issues/8309)
* chore: use node tsconfig in all src/node builds (#6019) ([8161d4a](https://github.com/vitejs/vite/commit/8161d4a)), closes [#6019](https://github.com/vitejs/vite/issues/6019)
* chore: use tsconfig for client build (#8815) ([10936cd](https://github.com/vitejs/vite/commit/10936cd)), closes [#8815](https://github.com/vitejs/vite/issues/8815)
* chore: use typescript for rollup configPlugin (#8290) ([fa538cf](https://github.com/vitejs/vite/commit/fa538cf)), closes [#8290](https://github.com/vitejs/vite/issues/8290)
* chore: using Unicode instead of unicode in doc and tests (#6852) ([c2bf62b](https://github.com/vitejs/vite/commit/c2bf62b)), closes [#6852](https://github.com/vitejs/vite/issues/6852)
* chore: v3 beta release notes (#8718) ([7e899d0](https://github.com/vitejs/vite/commit/7e899d0)), closes [#8718](https://github.com/vitejs/vite/issues/8718)
* chore: v3.0.0-beta.9 release notes (#8996) ([2a9bc6d](https://github.com/vitejs/vite/commit/2a9bc6d)), closes [#8996](https://github.com/vitejs/vite/issues/8996)
* chore: vite 4 beta changelog cleanup and release notes (#11200) ([cf6c175](https://github.com/vitejs/vite/commit/cf6c175)), closes [#11200](https://github.com/vitejs/vite/issues/11200)
* chore: warning about ssr cjs format removal (#13827) ([4646e9f](https://github.com/vitejs/vite/commit/4646e9f)), closes [#13827](https://github.com/vitejs/vite/issues/13827)
* chore(client): expose hot.prune API (#11016) ([f40c18d](https://github.com/vitejs/vite/commit/f40c18d)), closes [#11016](https://github.com/vitejs/vite/issues/11016)
* chore(client): remove redundant if statement (#14137) ([fe1c0b9](https://github.com/vitejs/vite/commit/fe1c0b9)), closes [#14137](https://github.com/vitejs/vite/issues/14137)
* chore(config): improve the readability of warning messages (#14594) ([b43b4df](https://github.com/vitejs/vite/commit/b43b4df)), closes [#14594](https://github.com/vitejs/vite/issues/14594)
* chore(css): catch postcss config error (fix #2793) (#7934) ([7f535ac](https://github.com/vitejs/vite/commit/7f535ac)), closes [#2793](https://github.com/vitejs/vite/issues/2793) [#7934](https://github.com/vitejs/vite/issues/7934)
* chore(css): remove useless parameter (#13411) ([1197b24](https://github.com/vitejs/vite/commit/1197b24)), closes [#13411](https://github.com/vitejs/vite/issues/13411)
* chore(define): remove inconsistent comment with import.meta.env replacement in lib mode (#12152) ([2556f88](https://github.com/vitejs/vite/commit/2556f88)), closes [#12152](https://github.com/vitejs/vite/issues/12152)
* chore(deps): bump rollup to 4.13.0 (#15295) ([2f95c2b](https://github.com/vitejs/vite/commit/2f95c2b)), closes [#15295](https://github.com/vitejs/vite/issues/15295)
* chore(deps): bump rollup version (#5045) ([b19fb33](https://github.com/vitejs/vite/commit/b19fb33)), closes [#5045](https://github.com/vitejs/vite/issues/5045)
* chore(deps): esbuild 0.16.3 (#11271) ([495c0be](https://github.com/vitejs/vite/commit/495c0be)), closes [#11271](https://github.com/vitejs/vite/issues/11271)
* chore(deps): massive major deps update (#5574) ([211f183](https://github.com/vitejs/vite/commit/211f183)), closes [#5574](https://github.com/vitejs/vite/issues/5574)
* chore(deps): remove unneeded type dep (#5541) ([9986ccb](https://github.com/vitejs/vite/commit/9986ccb)), closes [#5541](https://github.com/vitejs/vite/issues/5541)
* chore(deps): remove unused deps (#17329) ([5a45745](https://github.com/vitejs/vite/commit/5a45745)), closes [#17329](https://github.com/vitejs/vite/issues/17329)
* chore(deps): rollup 3.7 (#11269) ([fe388df](https://github.com/vitejs/vite/commit/fe388df)), closes [#11269](https://github.com/vitejs/vite/issues/11269)
* chore(deps): typescript 4.9 (#11229) ([6b4c4e2](https://github.com/vitejs/vite/commit/6b4c4e2)), closes [#11229](https://github.com/vitejs/vite/issues/11229)
* chore(deps): update @rollup/plugin-node-resolve to v14 (#10078) ([3390c87](https://github.com/vitejs/vite/commit/3390c87)), closes [#10078](https://github.com/vitejs/vite/issues/10078)
* chore(deps): update all non-major dependencies ([61dd3ed](https://github.com/vitejs/vite/commit/61dd3ed))
* chore(deps): update all non-major dependencies (#10393) ([f519423](https://github.com/vitejs/vite/commit/f519423)), closes [#10393](https://github.com/vitejs/vite/issues/10393)
* chore(deps): update all non-major dependencies (#10488) ([15aa827](https://github.com/vitejs/vite/commit/15aa827)), closes [#10488](https://github.com/vitejs/vite/issues/10488)
* chore(deps): update all non-major dependencies (#10725) ([22cfad8](https://github.com/vitejs/vite/commit/22cfad8)), closes [#10725](https://github.com/vitejs/vite/issues/10725)
* chore(deps): update all non-major dependencies (#10910) ([f6ad607](https://github.com/vitejs/vite/commit/f6ad607)), closes [#10910](https://github.com/vitejs/vite/issues/10910)
* chore(deps): update all non-major dependencies (#11006) ([96f2e98](https://github.com/vitejs/vite/commit/96f2e98)), closes [#11006](https://github.com/vitejs/vite/issues/11006)
* chore(deps): update all non-major dependencies (#11182) ([8b83089](https://github.com/vitejs/vite/commit/8b83089)), closes [#11182](https://github.com/vitejs/vite/issues/11182)
* chore(deps): update all non-major dependencies (#11321) ([dcc0004](https://github.com/vitejs/vite/commit/dcc0004)), closes [#11321](https://github.com/vitejs/vite/issues/11321)
* chore(deps): update all non-major dependencies (#11419) ([896475d](https://github.com/vitejs/vite/commit/896475d)), closes [#11419](https://github.com/vitejs/vite/issues/11419)
* chore(deps): update all non-major dependencies (#11701) ([1d2ee63](https://github.com/vitejs/vite/commit/1d2ee63)), closes [#11701](https://github.com/vitejs/vite/issues/11701)
* chore(deps): update all non-major dependencies (#11787) ([271394f](https://github.com/vitejs/vite/commit/271394f)), closes [#11787](https://github.com/vitejs/vite/issues/11787)
* chore(deps): update all non-major dependencies (#12299) ([b41336e](https://github.com/vitejs/vite/commit/b41336e)), closes [#12299](https://github.com/vitejs/vite/issues/12299)
* chore(deps): update all non-major dependencies (#12805) ([5731ac9](https://github.com/vitejs/vite/commit/5731ac9)), closes [#12805](https://github.com/vitejs/vite/issues/12805)
* chore(deps): update all non-major dependencies (#13553) ([3ea0534](https://github.com/vitejs/vite/commit/3ea0534)), closes [#13553](https://github.com/vitejs/vite/issues/13553)
* chore(deps): update all non-major dependencies (#13633) ([c72fb9b](https://github.com/vitejs/vite/commit/c72fb9b)), closes [#13633](https://github.com/vitejs/vite/issues/13633)
* chore(deps): update all non-major dependencies (#13938) ([a1b519e](https://github.com/vitejs/vite/commit/a1b519e)), closes [#13938](https://github.com/vitejs/vite/issues/13938)
* chore(deps): update all non-major dependencies (#15145) ([7ff2c0a](https://github.com/vitejs/vite/commit/7ff2c0a)), closes [#15145](https://github.com/vitejs/vite/issues/15145)
* chore(deps): update all non-major dependencies (#15874) ([d16ce5d](https://github.com/vitejs/vite/commit/d16ce5d)), closes [#15874](https://github.com/vitejs/vite/issues/15874)
* chore(deps): update all non-major dependencies (#16028) ([7cfe80d](https://github.com/vitejs/vite/commit/7cfe80d)), closes [#16028](https://github.com/vitejs/vite/issues/16028)
* chore(deps): update all non-major dependencies (#16131) ([a862ecb](https://github.com/vitejs/vite/commit/a862ecb)), closes [#16131](https://github.com/vitejs/vite/issues/16131)
* chore(deps): update all non-major dependencies (#16186) ([842643d](https://github.com/vitejs/vite/commit/842643d)), closes [#16186](https://github.com/vitejs/vite/issues/16186)
* chore(deps): update all non-major dependencies (#16325) ([a78e265](https://github.com/vitejs/vite/commit/a78e265)), closes [#16325](https://github.com/vitejs/vite/issues/16325)
* chore(deps): update all non-major dependencies (#16722) ([b45922a](https://github.com/vitejs/vite/commit/b45922a)), closes [#16722](https://github.com/vitejs/vite/issues/16722)
* chore(deps): update all non-major dependencies (#17373) ([f2d52f1](https://github.com/vitejs/vite/commit/f2d52f1)), closes [#17373](https://github.com/vitejs/vite/issues/17373)
* chore(deps): update all non-major dependencies (#17553) ([a33a97f](https://github.com/vitejs/vite/commit/a33a97f)), closes [#17553](https://github.com/vitejs/vite/issues/17553)
* chore(deps): update all non-major dependencies (#4992) ([5274c2e](https://github.com/vitejs/vite/commit/5274c2e)), closes [#4992](https://github.com/vitejs/vite/issues/4992)
* chore(deps): update all non-major dependencies (#5100) ([b2ae627](https://github.com/vitejs/vite/commit/b2ae627)), closes [#5100](https://github.com/vitejs/vite/issues/5100)
* chore(deps): update all non-major dependencies (#5245) ([0a3e514](https://github.com/vitejs/vite/commit/0a3e514)), closes [#5245](https://github.com/vitejs/vite/issues/5245)
* chore(deps): update all non-major dependencies (#5679) ([09f4d57](https://github.com/vitejs/vite/commit/09f4d57)), closes [#5679](https://github.com/vitejs/vite/issues/5679)
* chore(deps): update all non-major dependencies (#5783) ([eee9406](https://github.com/vitejs/vite/commit/eee9406)), closes [#5783](https://github.com/vitejs/vite/issues/5783)
* chore(deps): update all non-major dependencies (#5879) ([aab303f](https://github.com/vitejs/vite/commit/aab303f)), closes [#5879](https://github.com/vitejs/vite/issues/5879)
* chore(deps): update all non-major dependencies (#6185) ([b45f4ad](https://github.com/vitejs/vite/commit/b45f4ad)), closes [#6185](https://github.com/vitejs/vite/issues/6185)
* chore(deps): update all non-major dependencies (#6357) ([a272c07](https://github.com/vitejs/vite/commit/a272c07)), closes [#6357](https://github.com/vitejs/vite/issues/6357)
* chore(deps): update all non-major dependencies (#6905) ([839665c](https://github.com/vitejs/vite/commit/839665c)), closes [#6905](https://github.com/vitejs/vite/issues/6905)
* chore(deps): update all non-major dependencies (#7490) ([42c15f6](https://github.com/vitejs/vite/commit/42c15f6)), closes [#7490](https://github.com/vitejs/vite/issues/7490)
* chore(deps): update all non-major dependencies (#7603) ([fc51a15](https://github.com/vitejs/vite/commit/fc51a15)), closes [#7603](https://github.com/vitejs/vite/issues/7603)
* chore(deps): update all non-major dependencies (#7780) ([eba9d05](https://github.com/vitejs/vite/commit/eba9d05)), closes [#7780](https://github.com/vitejs/vite/issues/7780)
* chore(deps): update all non-major dependencies (#7847) ([e29d1d9](https://github.com/vitejs/vite/commit/e29d1d9)), closes [#7847](https://github.com/vitejs/vite/issues/7847)
* chore(deps): update all non-major dependencies (#7949) ([b877d30](https://github.com/vitejs/vite/commit/b877d30)), closes [#7949](https://github.com/vitejs/vite/issues/7949)
* chore(deps): update all non-major dependencies (#8474) ([6d0ede7](https://github.com/vitejs/vite/commit/6d0ede7)), closes [#8474](https://github.com/vitejs/vite/issues/8474)
* chore(deps): update all non-major dependencies (#8669) ([628863d](https://github.com/vitejs/vite/commit/628863d)), closes [#8669](https://github.com/vitejs/vite/issues/8669)
* chore(deps): update all non-major dependencies (#8905) ([4a24c17](https://github.com/vitejs/vite/commit/4a24c17)), closes [#8905](https://github.com/vitejs/vite/issues/8905)
* chore(deps): update all non-major dependencies (#9022) ([6342140](https://github.com/vitejs/vite/commit/6342140)), closes [#9022](https://github.com/vitejs/vite/issues/9022)
* chore(deps): update all non-major dependencies (#9347) ([2fcb027](https://github.com/vitejs/vite/commit/2fcb027)), closes [#9347](https://github.com/vitejs/vite/issues/9347)
* chore(deps): update all non-major dependencies (#9478) ([c530d16](https://github.com/vitejs/vite/commit/c530d16)), closes [#9478](https://github.com/vitejs/vite/issues/9478)
* chore(deps): update all non-major dependencies (#9675) ([4e56e87](https://github.com/vitejs/vite/commit/4e56e87)), closes [#9675](https://github.com/vitejs/vite/issues/9675)
* chore(deps): update all non-major dependencies (#9778) ([aceaefc](https://github.com/vitejs/vite/commit/aceaefc)), closes [#9778](https://github.com/vitejs/vite/issues/9778)
* chore(deps): update chokidar (#6701) ([dc2d1f8](https://github.com/vitejs/vite/commit/dc2d1f8)), closes [#6701](https://github.com/vitejs/vite/issues/6701)
* chore(deps): update dependency @ampproject/remapping to v2 (#6690) ([7a2ddb4](https://github.com/vitejs/vite/commit/7a2ddb4)), closes [#6690](https://github.com/vitejs/vite/issues/6690)
* chore(deps): update dependency @rollup/plugin-alias to v4 (#10394) ([e2b4c8f](https://github.com/vitejs/vite/commit/e2b4c8f)), closes [#10394](https://github.com/vitejs/vite/issues/10394)
* chore(deps): update dependency @rollup/plugin-alias to v5 (#14392) ([2947af7](https://github.com/vitejs/vite/commit/2947af7)), closes [#14392](https://github.com/vitejs/vite/issues/14392)
* chore(deps): update dependency @rollup/plugin-commonjs to v23 (#10611) ([cc4be70](https://github.com/vitejs/vite/commit/cc4be70)), closes [#10611](https://github.com/vitejs/vite/issues/10611)
* chore(deps): update dependency @rollup/plugin-commonjs to v24 (#11420) ([241db16](https://github.com/vitejs/vite/commit/241db16)), closes [#11420](https://github.com/vitejs/vite/issues/11420)
* chore(deps): update dependency @rollup/plugin-commonjs to v25 (#13204) ([a3ff501](https://github.com/vitejs/vite/commit/a3ff501)), closes [#13204](https://github.com/vitejs/vite/issues/13204)
* chore(deps): update dependency @rollup/plugin-commonjs to v26 (#17431) ([507b3de](https://github.com/vitejs/vite/commit/507b3de)), closes [#17431](https://github.com/vitejs/vite/issues/17431)
* chore(deps): update dependency @rollup/plugin-dynamic-import-vars to v2 (#10726) ([326f782](https://github.com/vitejs/vite/commit/326f782)), closes [#10726](https://github.com/vitejs/vite/issues/10726)
* chore(deps): update dependency @rollup/plugin-json to v5 (#10805) ([c22f50c](https://github.com/vitejs/vite/commit/c22f50c)), closes [#10805](https://github.com/vitejs/vite/issues/10805)
* chore(deps): update dependency @rollup/plugin-json to v6 (#11553) ([3647d07](https://github.com/vitejs/vite/commit/3647d07)), closes [#11553](https://github.com/vitejs/vite/issues/11553)
* chore(deps): update dependency @rollup/plugin-node-resolve to v15 (#10911) ([65f1e4d](https://github.com/vitejs/vite/commit/65f1e4d)), closes [#10911](https://github.com/vitejs/vite/issues/10911)
* chore(deps): update dependency @rollup/plugin-typescript to v10 (#11092) ([3fb27b8](https://github.com/vitejs/vite/commit/3fb27b8)), closes [#11092](https://github.com/vitejs/vite/issues/11092)
* chore(deps): update dependency @rollup/plugin-typescript to v11 (#11702) ([f40d511](https://github.com/vitejs/vite/commit/f40d511)), closes [#11702](https://github.com/vitejs/vite/issues/11702)
* chore(deps): update dependency @rollup/plugin-typescript to v9 (#11007) ([0e271ff](https://github.com/vitejs/vite/commit/0e271ff)), closes [#11007](https://github.com/vitejs/vite/issues/11007)
* chore(deps): update dependency @rollup/pluginutils to v5 (#11071) ([6c5ecee](https://github.com/vitejs/vite/commit/6c5ecee)), closes [#11071](https://github.com/vitejs/vite/issues/11071)
* chore(deps): update dependency connect-history-api-fallback to v2 (#8906) ([129c7c6](https://github.com/vitejs/vite/commit/129c7c6)), closes [#8906](https://github.com/vitejs/vite/issues/8906)
* chore(deps): update dependency convert-source-map to v2 (#10548) ([8dc6528](https://github.com/vitejs/vite/commit/8dc6528)), closes [#10548](https://github.com/vitejs/vite/issues/10548)
* chore(deps): update dependency dotenv to v14 (#6605) ([1733955](https://github.com/vitejs/vite/commit/1733955)), closes [#6605](https://github.com/vitejs/vite/issues/6605)
* chore(deps): update dependency dotenv-expand to v11 (#15875) ([642d528](https://github.com/vitejs/vite/commit/642d528)), closes [#15875](https://github.com/vitejs/vite/issues/15875)
* chore(deps): update dependency es-module-lexer to v1 (#9576) ([1d8613f](https://github.com/vitejs/vite/commit/1d8613f)), closes [#9576](https://github.com/vitejs/vite/issues/9576)
* chore(deps): update dependency eslint to v9 (#16661) ([6c10662](https://github.com/vitejs/vite/commit/6c10662)), closes [#16661](https://github.com/vitejs/vite/issues/16661)
* chore(deps): update dependency eslint-plugin-n to v17 (#16381) ([6cccef7](https://github.com/vitejs/vite/commit/6cccef7)), closes [#16381](https://github.com/vitejs/vite/issues/16381)
* chore(deps): update dependency mlly to v1 (#11370) ([9662d4d](https://github.com/vitejs/vite/commit/9662d4d)), closes [#11370](https://github.com/vitejs/vite/issues/11370)
* chore(deps): update dependency node-forge to v1 (#6425) ([4f820e5](https://github.com/vitejs/vite/commit/4f820e5)), closes [#6425](https://github.com/vitejs/vite/issues/6425)
* chore(deps): update dependency periscopic to v4 (#14348) ([badaadb](https://github.com/vitejs/vite/commit/badaadb)), closes [#14348](https://github.com/vitejs/vite/issues/14348)
* chore(deps): update dependency postcss-import to v15 (#9929) ([8f315a2](https://github.com/vitejs/vite/commit/8f315a2)), closes [#9929](https://github.com/vitejs/vite/issues/9929)
* chore(deps): update dependency postcss-import to v16 (#15533) ([36775c4](https://github.com/vitejs/vite/commit/36775c4)), closes [#15533](https://github.com/vitejs/vite/issues/15533)
* chore(deps): update dependency postcss-modules to v5 (#9779) ([aca6ac2](https://github.com/vitejs/vite/commit/aca6ac2)), closes [#9779](https://github.com/vitejs/vite/issues/9779)
* chore(deps): update dependency prettier to v3 (#13759) ([5a56941](https://github.com/vitejs/vite/commit/5a56941)), closes [#13759](https://github.com/vitejs/vite/issues/13759)
* chore(deps): update dependency sirv to v2 (#6358) ([9a58aae](https://github.com/vitejs/vite/commit/9a58aae)), closes [#6358](https://github.com/vitejs/vite/issues/6358)
* chore(deps): update dependency strip-literal to v1 (#12044) ([5bd6c0a](https://github.com/vitejs/vite/commit/5bd6c0a)), closes [#12044](https://github.com/vitejs/vite/issues/12044)
* chore(deps): update dependency strip-literal to v2 (#15475) ([49d21fe](https://github.com/vitejs/vite/commit/49d21fe)), closes [#15475](https://github.com/vitejs/vite/issues/15475)
* chore(deps): update dependency ws to v8 (#5540) ([2efc1e5](https://github.com/vitejs/vite/commit/2efc1e5)), closes [#5540](https://github.com/vitejs/vite/issues/5540)
* chore(deps): update dotenv-expand (#6703) ([0b819e2](https://github.com/vitejs/vite/commit/0b819e2)), closes [#6703](https://github.com/vitejs/vite/issues/6703)
* chore(deps): update es-module-lexer (#12230) ([d617093](https://github.com/vitejs/vite/commit/d617093)), closes [#12230](https://github.com/vitejs/vite/issues/12230)
* chore(deps): update es-module-lexer to 1.5.4 (#17555) ([2d6672f](https://github.com/vitejs/vite/commit/2d6672f)), closes [#17555](https://github.com/vitejs/vite/issues/17555)
* chore(deps): update esbuild (#17290) ([5f13bf8](https://github.com/vitejs/vite/commit/5f13bf8)), closes [#17290](https://github.com/vitejs/vite/issues/17290)
* chore(deps): update esbuild to 0.14.14 in vite package (#6702) ([eb4d4cd](https://github.com/vitejs/vite/commit/eb4d4cd)), closes [#6702](https://github.com/vitejs/vite/issues/6702)
* chore(deps): update esbuild to 0.15.18 (#11227) ([a08ca07](https://github.com/vitejs/vite/commit/a08ca07)), closes [#11227](https://github.com/vitejs/vite/issues/11227)
* chore(deps): update jest (#5480) ([c2de09b](https://github.com/vitejs/vite/commit/c2de09b)), closes [#5480](https://github.com/vitejs/vite/issues/5480)
* chore(deps): update non critical deps (#5569) ([09e2a5f](https://github.com/vitejs/vite/commit/09e2a5f)), closes [#5569](https://github.com/vitejs/vite/issues/5569)
* chore(deps): update postcss config loader (#6532) ([5d97de1](https://github.com/vitejs/vite/commit/5d97de1)), closes [#6532](https://github.com/vitejs/vite/issues/6532)
* chore(deps): update rollup to 3.17.2 (#12110) ([e54ffbd](https://github.com/vitejs/vite/commit/e54ffbd)), closes [#12110](https://github.com/vitejs/vite/issues/12110)
* chore(deps): update tj-actions/changed-files action to v41 (#15476) ([2a540ee](https://github.com/vitejs/vite/commit/2a540ee)), closes [#15476](https://github.com/vitejs/vite/issues/15476)
* chore(deps): update to esbuild fixed at 0.14.3 (#5861) ([44bb4da](https://github.com/vitejs/vite/commit/44bb4da)), closes [#5861](https://github.com/vitejs/vite/issues/5861)
* chore(deps): update to rollup 3.3 (#10890) ([2d17aa2](https://github.com/vitejs/vite/commit/2d17aa2)), closes [#10890](https://github.com/vitejs/vite/issues/10890)
* chore(deps): update to rollup 3.5 (#11165) ([859fe05](https://github.com/vitejs/vite/commit/859fe05)), closes [#11165](https://github.com/vitejs/vite/issues/11165)
* chore(deps): update tsconfck to 2.0.0 built for node14+ (#8144) ([0513d13](https://github.com/vitejs/vite/commit/0513d13)), closes [#8144](https://github.com/vitejs/vite/issues/8144)
* chore(deps): update tsconfck to 3.0.0 (#14629) ([4dcf9c4](https://github.com/vitejs/vite/commit/4dcf9c4)), closes [#14629](https://github.com/vitejs/vite/issues/14629)
* chore(deps): update vite dependencies (#5468) ([6bef595](https://github.com/vitejs/vite/commit/6bef595)), closes [#5468](https://github.com/vitejs/vite/issues/5468)
* chore(deps): upgrade typescript to 4.4 (#4932) ([936b398](https://github.com/vitejs/vite/commit/936b398)), closes [#4932](https://github.com/vitejs/vite/issues/4932)
* chore(deps): use `esno` to replace `ts-node` (#8152) ([2363bd3](https://github.com/vitejs/vite/commit/2363bd3)), closes [#8152](https://github.com/vitejs/vite/issues/8152)
* chore(esbuild): add test for configuration overrides (#11267) ([f897b64](https://github.com/vitejs/vite/commit/f897b64)), closes [#11267](https://github.com/vitejs/vite/issues/11267)
* chore(esbuild): fix typo (#14772) ([6cfc1e2](https://github.com/vitejs/vite/commit/6cfc1e2)), closes [#14772](https://github.com/vitejs/vite/issues/14772)
* chore(eslint): allow type annotations (#13920) ([d1264fd](https://github.com/vitejs/vite/commit/d1264fd)), closes [#13920](https://github.com/vitejs/vite/issues/13920)
* chore(lint): sort for imports (#8113) ([43a58dd](https://github.com/vitejs/vite/commit/43a58dd)), closes [#8113](https://github.com/vitejs/vite/issues/8113)
* chore(optimizedDeps): remove unused return (#14773) ([9d744dd](https://github.com/vitejs/vite/commit/9d744dd)), closes [#14773](https://github.com/vitejs/vite/issues/14773)
* chore(optimizer): debug info on cache dir handle process (#12858) ([21a62da](https://github.com/vitejs/vite/commit/21a62da)), closes [#12858](https://github.com/vitejs/vite/issues/12858)
* chore(optimizer): remove redundant setTimeout call in scan process (#12718) ([0ce0e93](https://github.com/vitejs/vite/commit/0ce0e93)), closes [#12718](https://github.com/vitejs/vite/issues/12718)
* chore(optimizer): show full optimized deps list (#12686) ([8bef662](https://github.com/vitejs/vite/commit/8bef662)), closes [#12686](https://github.com/vitejs/vite/issues/12686)
* chore(pluginContainer): simplify error position judge condition (#12003) ([e3ef9f4](https://github.com/vitejs/vite/commit/e3ef9f4)), closes [#12003](https://github.com/vitejs/vite/issues/12003)
* chore(proxy): update proxy error info (#15678) ([09bd58d](https://github.com/vitejs/vite/commit/09bd58d)), closes [#15678](https://github.com/vitejs/vite/issues/15678)
* chore(reporter): remove unnecessary map (#13972) ([dd9d4c1](https://github.com/vitejs/vite/commit/dd9d4c1)), closes [#13972](https://github.com/vitejs/vite/issues/13972)
* chore(reporter): reuse clearLine (#13156) ([535795a](https://github.com/vitejs/vite/commit/535795a)), closes [#13156](https://github.com/vitejs/vite/issues/13156)
* chore(shortcuts): resolve generic type error (#14802) ([a090742](https://github.com/vitejs/vite/commit/a090742)), closes [#14802](https://github.com/vitejs/vite/issues/14802)
* chore(types): remove unnecessary type assertion (#6784) ([a3a9941](https://github.com/vitejs/vite/commit/a3a9941)), closes [#6784](https://github.com/vitejs/vite/issues/6784)
* chore(types): use more reasonable ts checking annotation comment (#7063) ([745ae2f](https://github.com/vitejs/vite/commit/745ae2f)), closes [#7063](https://github.com/vitejs/vite/issues/7063)
* chore(typo): fix typo (#11445) ([ed80ea5](https://github.com/vitejs/vite/commit/ed80ea5)), closes [#11445](https://github.com/vitejs/vite/issues/11445)
* chore(utils): remove redundant type judgment (#12345) ([01a0056](https://github.com/vitejs/vite/commit/01a0056)), closes [#12345](https://github.com/vitejs/vite/issues/12345)
* test: avoid read check when running as root (#14884) ([1d9516c](https://github.com/vitejs/vite/commit/1d9516c)), closes [#14884](https://github.com/vitejs/vite/issues/14884)
* test: disable isolate for unit test (#17448) ([f16fae5](https://github.com/vitejs/vite/commit/f16fae5)), closes [#17448](https://github.com/vitejs/vite/issues/17448)
* test: fix test typo (#6285) ([1cbf0e1](https://github.com/vitejs/vite/commit/1cbf0e1)), closes [#6285](https://github.com/vitejs/vite/issues/6285)
* test: improve node/build.ts ut coverage (#10786) ([411cc3d](https://github.com/vitejs/vite/commit/411cc3d)), closes [#10786](https://github.com/vitejs/vite/issues/10786)
* test: migrate to vitest (#8076) ([8148f67](https://github.com/vitejs/vite/commit/8148f67)), closes [#8076](https://github.com/vitejs/vite/issues/8076)
* test: respect commonjs options in playgrounds (#13273) ([19e8c68](https://github.com/vitejs/vite/commit/19e8c68)), closes [#13273](https://github.com/vitejs/vite/issues/13273)
* test(hmr): improve #3033 fix description (#14645) ([3e264ef](https://github.com/vitejs/vite/commit/3e264ef)), closes [#14645](https://github.com/vitejs/vite/issues/14645)
* test(ssr): add import and export ordering snapshot (#14468) ([ca34c64](https://github.com/vitejs/vite/commit/ca34c64)), closes [#14468](https://github.com/vitejs/vite/issues/14468)
* test(ssr): proper test coverage of SSR shebang import hoisting (#14448) ([fdd4669](https://github.com/vitejs/vite/commit/fdd4669)), closes [#14448](https://github.com/vitejs/vite/issues/14448)
* feat: `build.assetsInlineLimit` callback (#15366) ([4d1342e](https://github.com/vitejs/vite/commit/4d1342e)), closes [#15366](https://github.com/vitejs/vite/issues/15366)
* feat: `server.fs.deny` support (#5378) ([1a15460](https://github.com/vitejs/vite/commit/1a15460)), closes [#5378](https://github.com/vitejs/vite/issues/5378)
* feat: 500 response if the node proxy request fails (#7398) ([73e1775](https://github.com/vitejs/vite/commit/73e1775)), closes [#7398](https://github.com/vitejs/vite/issues/7398)
* feat: accept AcceptedPlugin type for postcss plugin (#8830) ([6886078](https://github.com/vitejs/vite/commit/6886078)), closes [#8830](https://github.com/vitejs/vite/issues/8830)
* feat: accept assets to be specified as input (#16087) ([75a9fc6](https://github.com/vitejs/vite/commit/75a9fc6)), closes [#16087](https://github.com/vitejs/vite/issues/16087)
* feat: add .txt file format to assets (#6265) ([e87ae41](https://github.com/vitejs/vite/commit/e87ae41)), closes [#6265](https://github.com/vitejs/vite/issues/6265)
* feat: add '*.m4a' to client.d.ts and constants (#15471) ([ebc37f6](https://github.com/vitejs/vite/commit/ebc37f6)), closes [#15471](https://github.com/vitejs/vite/issues/15471)
* feat: add '*.mov' to client.d.ts (#15189) ([d93a211](https://github.com/vitejs/vite/commit/d93a211)), closes [#15189](https://github.com/vitejs/vite/issues/15189)
* feat: add 'system' library format (#11256) ([4102ca9](https://github.com/vitejs/vite/commit/4102ca9)), closes [#11256](https://github.com/vitejs/vite/issues/11256)
* feat: add `build.cssTarget` option (#5132) ([b17444f](https://github.com/vitejs/vite/commit/b17444f)), closes [#5132](https://github.com/vitejs/vite/issues/5132) [#4746](https://github.com/vitejs/vite/issues/4746) [#5070](https://github.com/vitejs/vite/issues/5070) [#4930](https://github.com/vitejs/vite/issues/4930)
* feat: add `importedCss` and `importedAssets` to RenderedChunk type (#6629) ([8d0fc90](https://github.com/vitejs/vite/commit/8d0fc90)), closes [#6629](https://github.com/vitejs/vite/issues/6629)
* feat: add `sourcemapIgnoreList` configuration option (#12174) ([f875580](https://github.com/vitejs/vite/commit/f875580)), closes [#12174](https://github.com/vitejs/vite/issues/12174)
* feat: add `vite:afterUpdate` event (#9810) ([1f57f84](https://github.com/vitejs/vite/commit/1f57f84)), closes [#9810](https://github.com/vitejs/vite/issues/9810)
* feat: add a runtime warning for the old object type transformIndexHtml hook (#14791) ([17fb5ee](https://github.com/vitejs/vite/commit/17fb5ee)), closes [#14791](https://github.com/vitejs/vite/issues/14791)
* feat: add an option to not start a websocket server (#16219) ([14b5ced](https://github.com/vitejs/vite/commit/14b5ced)), closes [#16219](https://github.com/vitejs/vite/issues/16219)
* feat: add CLI keyboard shortcuts (#11228) ([87973f1](https://github.com/vitejs/vite/commit/87973f1)), closes [#11228](https://github.com/vitejs/vite/issues/11228)
* feat: add customResolver option to resolve.alias (#5876) ([6408a3a](https://github.com/vitejs/vite/commit/6408a3a)), closes [#5876](https://github.com/vitejs/vite/issues/5876)
* feat: add entry name to manifest (#15849) ([6d6ae10](https://github.com/vitejs/vite/commit/6d6ae10)), closes [#15849](https://github.com/vitejs/vite/issues/15849)
* feat: add experimental option to skip SSR transform (#11411) ([e781ef3](https://github.com/vitejs/vite/commit/e781ef3)), closes [#11411](https://github.com/vitejs/vite/issues/11411)
* feat: add fixStacktrace option to ssrLoadModule (#7048) ([c703a33](https://github.com/vitejs/vite/commit/c703a33)), closes [#7048](https://github.com/vitejs/vite/issues/7048)
* feat: add generic type for plugin api (#14238) ([830b26e](https://github.com/vitejs/vite/commit/830b26e)), closes [#14238](https://github.com/vitejs/vite/issues/14238)
* feat: add headTagInsertCheck warning (#16555) ([9f02a9f](https://github.com/vitejs/vite/commit/9f02a9f)), closes [#16555](https://github.com/vitejs/vite/issues/16555)
* feat: add import-meta.d.ts (#14615) ([598d423](https://github.com/vitejs/vite/commit/598d423)), closes [#14615](https://github.com/vitejs/vite/issues/14615)
* feat: add invalid `rollupOptions` warnings (#14909) ([7c240a0](https://github.com/vitejs/vite/commit/7c240a0)), closes [#14909](https://github.com/vitejs/vite/issues/14909)
* feat: add lerna workspace support to `searchForWorkspaceRoot` (#6270) ([0e164f8](https://github.com/vitejs/vite/commit/0e164f8)), closes [#6270](https://github.com/vitejs/vite/issues/6270)
* feat: add mdx as known js source (#14560) ([dd213b5](https://github.com/vitejs/vite/commit/dd213b5)), closes [#14560](https://github.com/vitejs/vite/issues/14560)
* feat: add off method to ViteHotContext (issue #14185) (#14518) ([31333bb](https://github.com/vitejs/vite/commit/31333bb)), closes [#14185](https://github.com/vitejs/vite/issues/14185) [#14518](https://github.com/vitejs/vite/issues/14518)
* feat: add opus filetype to assets & mime types (#12526) ([63524ba](https://github.com/vitejs/vite/commit/63524ba)), closes [#12526](https://github.com/vitejs/vite/issues/12526)
* feat: add resolve.preserveSymlinks option (#4708) ([b61b044](https://github.com/vitejs/vite/commit/b61b044)), closes [#4708](https://github.com/vitejs/vite/issues/4708)
* feat: add server.warmup option (#14291) ([da80372](https://github.com/vitejs/vite/commit/da80372)), closes [#14291](https://github.com/vitejs/vite/issues/14291)
* feat: add ssr.format to force esm output for ssr (#6812) ([337b197](https://github.com/vitejs/vite/commit/337b197)), closes [#6812](https://github.com/vitejs/vite/issues/6812)
* feat: add status message for 504 caused by optimizer (#12435) ([5cdd3fa](https://github.com/vitejs/vite/commit/5cdd3fa)), closes [#12435](https://github.com/vitejs/vite/issues/12435)
* feat: add support for .vtt type (#15538) ([a5c6d3d](https://github.com/vitejs/vite/commit/a5c6d3d)), closes [#15538](https://github.com/vitejs/vite/issues/15538)
* feat: Add support for imba in html scripts (#10679) ([b823fd6](https://github.com/vitejs/vite/commit/b823fd6)), closes [#10679](https://github.com/vitejs/vite/issues/10679)
* feat: align default chunk and asset file names with rollup (#10927) ([cc2adb3](https://github.com/vitejs/vite/commit/cc2adb3)), closes [#10927](https://github.com/vitejs/vite/issues/10927)
* feat: align object interface for `transformIndexHtml` hook (#9669) ([1db52bf](https://github.com/vitejs/vite/commit/1db52bf)), closes [#9669](https://github.com/vitejs/vite/issues/9669)
* feat: allow any JS identifier in define, not ASCII-only (#5972) ([95eb45b](https://github.com/vitejs/vite/commit/95eb45b)), closes [#5972](https://github.com/vitejs/vite/issues/5972)
* feat: allow declaring dirname (#9154) ([1e078ad](https://github.com/vitejs/vite/commit/1e078ad)), closes [#9154](https://github.com/vitejs/vite/issues/9154)
* feat: allow globs in node_modules when pattern is explicit (#6056) ([669d7e0](https://github.com/vitejs/vite/commit/669d7e0)), closes [#6056](https://github.com/vitejs/vite/issues/6056)
* feat: allow import.meta.hot define override (#8944) ([857d578](https://github.com/vitejs/vite/commit/857d578)), closes [#8944](https://github.com/vitejs/vite/issues/8944)
* feat: allow passing down "null" to disable server watcher (#14208) ([af5a95e](https://github.com/vitejs/vite/commit/af5a95e)), closes [#14208](https://github.com/vitejs/vite/issues/14208)
* feat: allow providing parent httpServer on middleware mode (#14632) ([e0c86d4](https://github.com/vitejs/vite/commit/e0c86d4)), closes [#14632](https://github.com/vitejs/vite/issues/14632)
* feat: asset type add apng (#13294) ([a11b6f6](https://github.com/vitejs/vite/commit/a11b6f6)), closes [#13294](https://github.com/vitejs/vite/issues/13294)
* feat: asset type add bmp (#17439) ([ec287f8](https://github.com/vitejs/vite/commit/ec287f8)), closes [#17439](https://github.com/vitejs/vite/issues/17439)
* feat: async script module support, close #3163 (#4864) ([3984569](https://github.com/vitejs/vite/commit/3984569)), closes [#3163](https://github.com/vitejs/vite/issues/3163) [#4864](https://github.com/vitejs/vite/issues/4864)
* feat: avoid scanner during build and only optimize CJS in SSR (#8932) ([339d9e3](https://github.com/vitejs/vite/commit/339d9e3)), closes [#8932](https://github.com/vitejs/vite/issues/8932)
* feat: base without trailing slash (#10723) ([8f87282](https://github.com/vitejs/vite/commit/8f87282)), closes [#10723](https://github.com/vitejs/vite/issues/10723)
* feat: better config `__dirname` support (#8442) ([51e9195](https://github.com/vitejs/vite/commit/51e9195)), closes [#8442](https://github.com/vitejs/vite/issues/8442)
* feat: build.modulePreload options (#9938) ([e223f84](https://github.com/vitejs/vite/commit/e223f84)), closes [#9938](https://github.com/vitejs/vite/issues/9938)
* feat: build.ssrEmitAssets out of experimental (#14055) ([f88ab68](https://github.com/vitejs/vite/commit/f88ab68)), closes [#14055](https://github.com/vitejs/vite/issues/14055)
* feat: bump minimum node version to 14.18.0 (#8662) ([8a05432](https://github.com/vitejs/vite/commit/8a05432)), closes [#8662](https://github.com/vitejs/vite/issues/8662)
* feat: cancellable scan during optimization (#12225) ([1e1cd3b](https://github.com/vitejs/vite/commit/1e1cd3b)), closes [#12225](https://github.com/vitejs/vite/issues/12225)
* feat: catch postcss error messages (#6293) ([4d75b2e](https://github.com/vitejs/vite/commit/4d75b2e)), closes [#6293](https://github.com/vitejs/vite/issues/6293)
* feat: clean string module lex string template (#7667) ([dfce283](https://github.com/vitejs/vite/commit/dfce283)), closes [#7667](https://github.com/vitejs/vite/issues/7667)
* feat: cleaner default dev output (#8638) ([dbd9688](https://github.com/vitejs/vite/commit/dbd9688)), closes [#8638](https://github.com/vitejs/vite/issues/8638)
* feat: convert overlay template to DOM (#15852) ([dd49505](https://github.com/vitejs/vite/commit/dd49505)), closes [#15852](https://github.com/vitejs/vite/issues/15852)
* feat: copyPublicDir out of experimental (#14051) ([443c235](https://github.com/vitejs/vite/commit/443c235)), closes [#14051](https://github.com/vitejs/vite/issues/14051)
* feat: csp nonce support (#16052) ([1d5eec4](https://github.com/vitejs/vite/commit/1d5eec4)), closes [#16052](https://github.com/vitejs/vite/issues/16052)
* feat: css sourcemap support during dev (#7173) ([38a655f](https://github.com/vitejs/vite/commit/38a655f)), closes [#7173](https://github.com/vitejs/vite/issues/7173)
* feat: custom manifest file name (#6667) ([e385346](https://github.com/vitejs/vite/commit/e385346)), closes [#6667](https://github.com/vitejs/vite/issues/6667)
* feat: customize ErrorOverlay (#10234) ([fe4dc8d](https://github.com/vitejs/vite/commit/fe4dc8d)), closes [#10234](https://github.com/vitejs/vite/issues/10234)
* feat: default build.minify to esbuild (#5041) ([e4892be](https://github.com/vitejs/vite/commit/e4892be)), closes [#5041](https://github.com/vitejs/vite/issues/5041)
* feat: default esbuild jsxDev based on config.isProduction (#12386) ([f24c2b0](https://github.com/vitejs/vite/commit/f24c2b0)), closes [#12386](https://github.com/vitejs/vite/issues/12386)
* feat: default esm SSR build, simplified externalization (#8348) ([f8c92d1](https://github.com/vitejs/vite/commit/f8c92d1)), closes [#8348](https://github.com/vitejs/vite/issues/8348)
* feat: derive proper js extension from package type (#8382) ([95cdd81](https://github.com/vitejs/vite/commit/95cdd81)), closes [#8382](https://github.com/vitejs/vite/issues/8382)
* feat: don't override `build.target` if terser is 5.16.0+ (#12197) ([9885f6f](https://github.com/vitejs/vite/commit/9885f6f)), closes [#12197](https://github.com/vitejs/vite/issues/12197)
* feat: dynamic import support ?url and ?worker (#8261) ([0cb01ca](https://github.com/vitejs/vite/commit/0cb01ca)), closes [#8261](https://github.com/vitejs/vite/issues/8261)
* feat: emit event to handle chunk load errors (#12084) ([2eca54e](https://github.com/vitejs/vite/commit/2eca54e)), closes [#12084](https://github.com/vitejs/vite/issues/12084)
* feat: enable `generatedCode: 'es2015'` for rollup build (#5018) ([46d5e67](https://github.com/vitejs/vite/commit/46d5e67)), closes [#5018](https://github.com/vitejs/vite/issues/5018)
* feat: enable fs.cachedChecks by default (#15704) ([a05c709](https://github.com/vitejs/vite/commit/a05c709)), closes [#15704](https://github.com/vitejs/vite/issues/15704)
* feat: enable optimizeDeps.esbuildOptions.loader (#6840) ([af8ca60](https://github.com/vitejs/vite/commit/af8ca60)), closes [#6840](https://github.com/vitejs/vite/issues/6840)
* feat: enable tree-shaking for lib es (#8737) ([5dc0f72](https://github.com/vitejs/vite/commit/5dc0f72)), closes [#8737](https://github.com/vitejs/vite/issues/8737)
* feat: error when failed to resolve aliased import (#14973) ([6a564fa](https://github.com/vitejs/vite/commit/6a564fa)), closes [#14973](https://github.com/vitejs/vite/issues/14973)
* feat: esbuild 0.17 (#11908) ([9d42f06](https://github.com/vitejs/vite/commit/9d42f06)), closes [#11908](https://github.com/vitejs/vite/issues/11908)
* feat: experimental Vite Runtime API (#12165) ([8b3ab07](https://github.com/vitejs/vite/commit/8b3ab07)), closes [#12165](https://github.com/vitejs/vite/issues/12165)
* feat: experimental.buildAdvancedBaseOptions (#8450) ([8ef7333](https://github.com/vitejs/vite/commit/8ef7333)), closes [#8450](https://github.com/vitejs/vite/issues/8450)
* feat: experimental.renderBuiltUrl (revised build base options) (#8762) ([895a7d6](https://github.com/vitejs/vite/commit/895a7d6)), closes [#8762](https://github.com/vitejs/vite/issues/8762)
* feat: explicit the word boundary (#6876) ([7ddbf96](https://github.com/vitejs/vite/commit/7ddbf96)), closes [#6876](https://github.com/vitejs/vite/issues/6876)
* feat: export `server.bindCLIShortcuts` (#13675) ([1a2e5e6](https://github.com/vitejs/vite/commit/1a2e5e6)), closes [#13675](https://github.com/vitejs/vite/issues/13675)
* feat: export error message generator (#11155) ([493ba1e](https://github.com/vitejs/vite/commit/493ba1e)), closes [#11155](https://github.com/vitejs/vite/issues/11155)
* feat: export esbuildVersion and rollupVersion (#8675) ([15ebe1e](https://github.com/vitejs/vite/commit/15ebe1e)), closes [#8675](https://github.com/vitejs/vite/issues/8675)
* feat: export transformWithEsbuild (#4882) ([c8c0f74](https://github.com/vitejs/vite/commit/c8c0f74)), closes [#4882](https://github.com/vitejs/vite/issues/4882)
* feat: expose `isFileServingAllowed` as public utility (#12894) ([93e095c](https://github.com/vitejs/vite/commit/93e095c)), closes [#12894](https://github.com/vitejs/vite/issues/12894)
* feat: expose `preview` method (#5014) ([9885656](https://github.com/vitejs/vite/commit/9885656)), closes [#5014](https://github.com/vitejs/vite/issues/5014)
* feat: expose `searchForWorkspaceRoot` util (#4958) ([d0f7bf1](https://github.com/vitejs/vite/commit/d0f7bf1)), closes [#4958](https://github.com/vitejs/vite/issues/4958)
* feat: expose `ssrTransform` to server (#5983) ([8184feb](https://github.com/vitejs/vite/commit/8184feb)), closes [#5983](https://github.com/vitejs/vite/issues/5983)
* feat: expose `version` (#8456) ([e992594](https://github.com/vitejs/vite/commit/e992594)), closes [#8456](https://github.com/vitejs/vite/issues/8456)
* feat: expose createFilter util (#8562) ([c5c424a](https://github.com/vitejs/vite/commit/c5c424a)), closes [#8562](https://github.com/vitejs/vite/issues/8562)
* feat: expose parseAst and parseAstAsync from rollup (#14833) ([6229485](https://github.com/vitejs/vite/commit/6229485)), closes [#14833](https://github.com/vitejs/vite/issues/14833)
* feat: expose server resolved urls (#8986) ([26bcdc3](https://github.com/vitejs/vite/commit/26bcdc3)), closes [#8986](https://github.com/vitejs/vite/issues/8986)
* feat: expose ssrRewriteStacktrace (#7091) ([d4ae45d](https://github.com/vitejs/vite/commit/d4ae45d)), closes [#7091](https://github.com/vitejs/vite/issues/7091)
* feat: formalize waitForRequestsIdle (experimental) (#16135) ([9888843](https://github.com/vitejs/vite/commit/9888843)), closes [#16135](https://github.com/vitejs/vite/issues/16135)
* feat: handle named imports of builtin modules (#8338) ([e2e44ff](https://github.com/vitejs/vite/commit/e2e44ff)), closes [#8338](https://github.com/vitejs/vite/issues/8338)
* feat: handle static assets in case-sensitive manner (#10475) ([c1368c3](https://github.com/vitejs/vite/commit/c1368c3)), closes [#10475](https://github.com/vitejs/vite/issues/10475)
* feat: hide optimized deps found during scan phase logs (#7419) ([f4934e8](https://github.com/vitejs/vite/commit/f4934e8)), closes [#7419](https://github.com/vitejs/vite/issues/7419)
* feat: ignore list client injected sources (#12170) ([8a98aef](https://github.com/vitejs/vite/commit/8a98aef)), closes [#12170](https://github.com/vitejs/vite/issues/12170)
* feat: implement AsyncDisposable (#14648) ([385d580](https://github.com/vitejs/vite/commit/385d580)), closes [#14648](https://github.com/vitejs/vite/issues/14648)
* feat: import public non-asset URL (#13422) ([3a98558](https://github.com/vitejs/vite/commit/3a98558)), closes [#13422](https://github.com/vitejs/vite/issues/13422)
* feat: import ts with .js in vue (#7998) ([9974094](https://github.com/vitejs/vite/commit/9974094)), closes [#7998](https://github.com/vitejs/vite/issues/7998)
* feat: import.meta.glob support ?raw (#5545) ([5279de6](https://github.com/vitejs/vite/commit/5279de6)), closes [#5545](https://github.com/vitejs/vite/issues/5545)
* feat: importing ts files using their corresponding js extesions (#5510) ([7977e92](https://github.com/vitejs/vite/commit/7977e92)), closes [#5510](https://github.com/vitejs/vite/issues/5510)
* feat: improve deno and bun support (#14379) ([9884308](https://github.com/vitejs/vite/commit/9884308)), closes [#14379](https://github.com/vitejs/vite/issues/14379)
* feat: improve dynamic import variable failure error message (#16519) ([f8feeea](https://github.com/vitejs/vite/commit/f8feeea)), closes [#16519](https://github.com/vitejs/vite/issues/16519)
* feat: improve the error message of `expand` (#11141) ([825c793](https://github.com/vitejs/vite/commit/825c793)), closes [#11141](https://github.com/vitejs/vite/issues/11141)
* feat: improved cold start using deps scanner (#8869) ([188f188](https://github.com/vitejs/vite/commit/188f188)), closes [#8869](https://github.com/vitejs/vite/issues/8869)
* feat: include duplicate assets in the manifest (#9928) ([42ecf37](https://github.com/vitejs/vite/commit/42ecf37)), closes [#9928](https://github.com/vitejs/vite/issues/9928)
* feat: include line and column in error format (#10529) ([d806c4a](https://github.com/vitejs/vite/commit/d806c4a)), closes [#10529](https://github.com/vitejs/vite/issues/10529)
* feat: legacy options to revert to v2 strategies (#8623) ([993b842](https://github.com/vitejs/vite/commit/993b842)), closes [#8623](https://github.com/vitejs/vite/issues/8623)
* feat: lint for missing type="module" attribute (#5837) (#5838) ([494e358](https://github.com/vitejs/vite/commit/494e358)), closes [#5837](https://github.com/vitejs/vite/issues/5837) [#5838](https://github.com/vitejs/vite/issues/5838)
* feat: log re-optimization reasons (#15339) ([b1a6c84](https://github.com/vitejs/vite/commit/b1a6c84)), closes [#15339](https://github.com/vitejs/vite/issues/15339)
* feat: make `import.meta.glob` and `import.meta.globEager` generic (#5073) ([78e84c8](https://github.com/vitejs/vite/commit/78e84c8)), closes [#5073](https://github.com/vitejs/vite/issues/5073)
* feat: new hook `configurePreviewServer` (#7658) ([20ea999](https://github.com/vitejs/vite/commit/20ea999)), closes [#7658](https://github.com/vitejs/vite/issues/7658)
* feat: new Worker can bundle URL('path', import.meta.url) script (fix #5979) (#6356) ([a345614](https://github.com/vitejs/vite/commit/a345614)), closes [#5979](https://github.com/vitejs/vite/issues/5979) [#6356](https://github.com/vitejs/vite/issues/6356)
* feat: non-blocking esbuild optimization at build time (#8280) ([909cf9c](https://github.com/vitejs/vite/commit/909cf9c)), closes [#8280](https://github.com/vitejs/vite/issues/8280)
* feat: non-blocking needs interop (#7568) ([531cd7b](https://github.com/vitejs/vite/commit/531cd7b)), closes [#7568](https://github.com/vitejs/vite/issues/7568)
* feat: non-blocking pre bundling of dependencies (#6758) ([24bb3e4](https://github.com/vitejs/vite/commit/24bb3e4)), closes [#6758](https://github.com/vitejs/vite/issues/6758)
* feat: non-blocking scanning of dependencies (#7379) ([676f545](https://github.com/vitejs/vite/commit/676f545)), closes [#7379](https://github.com/vitejs/vite/issues/7379)
* feat: optimize custom extensions (#6801) ([c11af23](https://github.com/vitejs/vite/commit/c11af23)), closes [#6801](https://github.com/vitejs/vite/issues/6801)
* feat: optimize deps option to turn off auto discovery (#13000) ([bd86375](https://github.com/vitejs/vite/commit/bd86375)), closes [#13000](https://github.com/vitejs/vite/issues/13000)
* feat: optimizeDeps.disabled (#7646) ([48e038c](https://github.com/vitejs/vite/commit/48e038c)), closes [#7646](https://github.com/vitejs/vite/issues/7646)
* feat: option to disable pre-transform (#6309) ([2c14525](https://github.com/vitejs/vite/commit/2c14525)), closes [#6309](https://github.com/vitejs/vite/issues/6309)
* feat: pre transform direct imports before requests hit the server (#5037) ([57b9a37](https://github.com/vitejs/vite/commit/57b9a37)), closes [#5037](https://github.com/vitejs/vite/issues/5037)
* feat: preserve process env vars in lib build (#8090) ([908c9e4](https://github.com/vitejs/vite/commit/908c9e4)), closes [#8090](https://github.com/vitejs/vite/issues/8090)
* feat: preserve vite.middlewares connect instance after restarts (#15166) ([9474c4b](https://github.com/vitejs/vite/commit/9474c4b)), closes [#15166](https://github.com/vitejs/vite/issues/15166)
* feat: preview config (#5514) ([ff755eb](https://github.com/vitejs/vite/commit/ff755eb)), closes [#5514](https://github.com/vitejs/vite/issues/5514)
* feat: preview mode add keyboard shortcuts (#12968) ([126e93e](https://github.com/vitejs/vite/commit/126e93e)), closes [#12968](https://github.com/vitejs/vite/issues/12968)
* feat: preview server add close method (#15630) ([947aa53](https://github.com/vitejs/vite/commit/947aa53)), closes [#15630](https://github.com/vitejs/vite/issues/15630)
* feat: print resolved address for localhost (#8647) ([eb52d36](https://github.com/vitejs/vite/commit/eb52d36)), closes [#8647](https://github.com/vitejs/vite/issues/8647)
* feat: relax dep browser externals as warning (#9837) ([71cb374](https://github.com/vitejs/vite/commit/71cb374)), closes [#9837](https://github.com/vitejs/vite/issues/9837)
* feat: reproducible manifest (#11542) ([efc8979](https://github.com/vitejs/vite/commit/efc8979)), closes [#11542](https://github.com/vitejs/vite/issues/11542)
* feat: respect esbuild minify config (#8754) ([8b77695](https://github.com/vitejs/vite/commit/8b77695)), closes [#8754](https://github.com/vitejs/vite/issues/8754)
* feat: respect esbuild minify config for css (#8811) ([d90409e](https://github.com/vitejs/vite/commit/d90409e)), closes [#8811](https://github.com/vitejs/vite/issues/8811)
* feat: reuse existing style elements in dev (#12678) ([3a41bd8](https://github.com/vitejs/vite/commit/3a41bd8)), closes [#12678](https://github.com/vitejs/vite/issues/12678)
* feat: reuse opening tab in chromium browsers when start dev server (#10485) ([1a2e7a8](https://github.com/vitejs/vite/commit/1a2e7a8)), closes [#10485](https://github.com/vitejs/vite/issues/10485)
* feat: rework `dynamic-import-vars` (#7756) ([80d113b](https://github.com/vitejs/vite/commit/80d113b)), closes [#7756](https://github.com/vitejs/vite/issues/7756)
* feat: rollup 3 (#9870) ([beb7166](https://github.com/vitejs/vite/commit/beb7166)), closes [#9870](https://github.com/vitejs/vite/issues/9870)
* feat: scan free dev server (#8319) ([3f742b6](https://github.com/vitejs/vite/commit/3f742b6)), closes [#8319](https://github.com/vitejs/vite/issues/8319)
* feat: server.open supports absolute path (#5068) ([2d6f682](https://github.com/vitejs/vite/commit/2d6f682)), closes [#5068](https://github.com/vitejs/vite/issues/5068)
* feat: show all prebundle deps when debug (#6726) ([e626055](https://github.com/vitejs/vite/commit/e626055)), closes [#6726](https://github.com/vitejs/vite/issues/6726)
* feat: show better parse error in build (#14600) ([84df7db](https://github.com/vitejs/vite/commit/84df7db)), closes [#14600](https://github.com/vitejs/vite/issues/14600)
* feat: show server url by pressing `u` (#11319) ([8c0bb7b](https://github.com/vitejs/vite/commit/8c0bb7b)), closes [#11319](https://github.com/vitejs/vite/issues/11319)
* feat: show warning if root is in build.outDir (#16454) ([11444dc](https://github.com/vitejs/vite/commit/11444dc)), closes [#16454](https://github.com/vitejs/vite/issues/16454)
* feat: show warning on 431 response (#9324) ([e8b61bb](https://github.com/vitejs/vite/commit/e8b61bb)), closes [#9324](https://github.com/vitejs/vite/issues/9324)
* feat: show warning to discourage putting process/global to `define` option (#14447) ([83a56f7](https://github.com/vitejs/vite/commit/83a56f7)), closes [#14447](https://github.com/vitejs/vite/issues/14447)
* feat: show ws connection error (#9007) ([da7c3ae](https://github.com/vitejs/vite/commit/da7c3ae)), closes [#9007](https://github.com/vitejs/vite/issues/9007)
* feat: skip initial clear screen if has logs (#14936) ([a92bc61](https://github.com/vitejs/vite/commit/a92bc61)), closes [#14936](https://github.com/vitejs/vite/issues/14936)
* feat: skip pinging the server when the tab is not shown (#12698) ([bedcd8f](https://github.com/vitejs/vite/commit/bedcd8f)), closes [#12698](https://github.com/vitejs/vite/issues/12698)
* feat: sourcemap for importAnalysis (#8258) ([a4e4d39](https://github.com/vitejs/vite/commit/a4e4d39)), closes [#8258](https://github.com/vitejs/vite/issues/8258)
* feat: spa option, `preview` and `dev` for MPA and SSR apps (#8217) ([d7cba46](https://github.com/vitejs/vite/commit/d7cba46)), closes [#8217](https://github.com/vitejs/vite/issues/8217)
* feat: ssr build using optimized deps (#8403) ([6a5a5b5](https://github.com/vitejs/vite/commit/6a5a5b5)), closes [#8403](https://github.com/vitejs/vite/issues/8403)
* feat: ssr.optimizeDeps (#8917) ([f280dd9](https://github.com/vitejs/vite/commit/f280dd9)), closes [#8917](https://github.com/vitejs/vite/issues/8917)
* feat: ssrBuild flag in config env (#8863) ([b6d655a](https://github.com/vitejs/vite/commit/b6d655a)), closes [#8863](https://github.com/vitejs/vite/issues/8863)
* feat: ssrTransform support import assertion by default (#14202) ([70a379f](https://github.com/vitejs/vite/commit/70a379f)), closes [#14202](https://github.com/vitejs/vite/issues/14202)
* feat: stabilize server.resolvedUrls (#9866) ([c3f6731](https://github.com/vitejs/vite/commit/c3f6731)), closes [#9866](https://github.com/vitejs/vite/issues/9866)
* feat: support .astro files (#5038) ([79ff0ec](https://github.com/vitejs/vite/commit/79ff0ec)), closes [#5038](https://github.com/vitejs/vite/issues/5038)
* feat: support .cjs config file (#5602) ([cddd986](https://github.com/vitejs/vite/commit/cddd986)), closes [#5602](https://github.com/vitejs/vite/issues/5602)
* feat: support `import.meta.hot?.accept` (#12053) ([081c27f](https://github.com/vitejs/vite/commit/081c27f)), closes [#12053](https://github.com/vitejs/vite/issues/12053)
* feat: support `moduleInfo.meta` in dev server (#5465) ([f6d08c7](https://github.com/vitejs/vite/commit/f6d08c7)), closes [#5465](https://github.com/vitejs/vite/issues/5465)
* feat: support async plugins (#8574) ([caa8a58](https://github.com/vitejs/vite/commit/caa8a58)), closes [#8574](https://github.com/vitejs/vite/issues/8574)
* feat: support BROWSER and BROWSER_ARGS in env file (#11513) ([8972868](https://github.com/vitejs/vite/commit/8972868)), closes [#11513](https://github.com/vitejs/vite/issues/11513)
* feat: support cjs noExternal in SSR dev, fix #2579 (#8430) ([11d2191](https://github.com/vitejs/vite/commit/11d2191)), closes [#2579](https://github.com/vitejs/vite/issues/2579) [#8430](https://github.com/vitejs/vite/issues/8430)
* feat: support ESM subpath imports (#7770) ([cc92da9](https://github.com/vitejs/vite/commit/cc92da9)), closes [#7770](https://github.com/vitejs/vite/issues/7770)
* feat: support files for `fs.allow` (#12863) ([4a06e66](https://github.com/vitejs/vite/commit/4a06e66)), closes [#12863](https://github.com/vitejs/vite/issues/12863)
* feat: support for self-referencing (#16068) ([03b9674](https://github.com/vitejs/vite/commit/03b9674)), closes [#16068](https://github.com/vitejs/vite/issues/16068)
* feat: support import assertions (#8937) ([2390422](https://github.com/vitejs/vite/commit/2390422)), closes [#8937](https://github.com/vitejs/vite/issues/8937)
* feat: support import.meta.hot.invalidate (#10244) ([fb8ab16](https://github.com/vitejs/vite/commit/fb8ab16)), closes [#10244](https://github.com/vitejs/vite/issues/10244)
* feat: support importing css with ?raw (#5796) ([fedb106](https://github.com/vitejs/vite/commit/fedb106)), closes [#5796](https://github.com/vitejs/vite/issues/5796)
* feat: support multiple HMR clients on the server (#15340) ([bf1e9c2](https://github.com/vitejs/vite/commit/bf1e9c2)), closes [#15340](https://github.com/vitejs/vite/issues/15340)
* feat: support object style hooks (#9634) ([757a92f](https://github.com/vitejs/vite/commit/757a92f)), closes [#9634](https://github.com/vitejs/vite/issues/9634)
* feat: support postcss sugarss (#6705) ([8ede2f1](https://github.com/vitejs/vite/commit/8ede2f1)), closes [#6705](https://github.com/vitejs/vite/issues/6705)
* feat: support rollup plugin this.load in plugin container context (#11469) ([abfa804](https://github.com/vitejs/vite/commit/abfa804)), closes [#11469](https://github.com/vitejs/vite/issues/11469)
* feat: supports cts and mts config (#8729) ([c2b09db](https://github.com/vitejs/vite/commit/c2b09db)), closes [#8729](https://github.com/vitejs/vite/issues/8729)
* feat: supports cts and mts files (#9268) ([0602017](https://github.com/vitejs/vite/commit/0602017)), closes [#9268](https://github.com/vitejs/vite/issues/9268)
* feat: treat Astro file scripts as TS (#8151) ([559c952](https://github.com/vitejs/vite/commit/559c952)), closes [#8151](https://github.com/vitejs/vite/issues/8151)
* feat: update esbuild compilation affecting fields (#10374) ([f542727](https://github.com/vitejs/vite/commit/f542727)), closes [#10374](https://github.com/vitejs/vite/issues/10374)
* feat: update esbuild to 0.18.10 (#13644) ([f900acd](https://github.com/vitejs/vite/commit/f900acd)), closes [#13644](https://github.com/vitejs/vite/issues/13644)
* feat: update esbuild to 0.18.6 (#13577) ([4cc671f](https://github.com/vitejs/vite/commit/4cc671f)), closes [#13577](https://github.com/vitejs/vite/issues/13577)
* feat: upgrade rollup to 4.2.0 and use parseAstAsync (#14821) ([86a5356](https://github.com/vitejs/vite/commit/86a5356)), closes [#14821](https://github.com/vitejs/vite/issues/14821)
* feat: use `import.meta.url` instead of `self.location` (#14377) ([e9b1e85](https://github.com/vitejs/vite/commit/e9b1e85)), closes [#14377](https://github.com/vitejs/vite/issues/14377)
* feat: use esbuild supported feature (#8665) ([2061d41](https://github.com/vitejs/vite/commit/2061d41)), closes [#8665](https://github.com/vitejs/vite/issues/8665)
* feat: use preview server parameter in preview server hook (#11647) ([4c142ea](https://github.com/vitejs/vite/commit/4c142ea)), closes [#11647](https://github.com/vitejs/vite/issues/11647)
* feat: vite connected logs changed to console.debug (#7733) ([9f00c41](https://github.com/vitejs/vite/commit/9f00c41)), closes [#7733](https://github.com/vitejs/vite/issues/7733)
* feat: warn if # in project root (#14188) ([f5ba696](https://github.com/vitejs/vite/commit/f5ba696)), closes [#14188](https://github.com/vitejs/vite/issues/14188)
* feat: worker config call config hook (#9212) ([3e510ab](https://github.com/vitejs/vite/commit/3e510ab)), closes [#9212](https://github.com/vitejs/vite/issues/9212)
* feat: worker emit fileName with config (#7804) ([04c2edd](https://github.com/vitejs/vite/commit/04c2edd)), closes [#7804](https://github.com/vitejs/vite/issues/7804)
* feat: worker support query url (#7914) ([95297dd](https://github.com/vitejs/vite/commit/95297dd)), closes [#7914](https://github.com/vitejs/vite/issues/7914)
* feat: write cspNonce to style tags (#16419) ([8e54bbd](https://github.com/vitejs/vite/commit/8e54bbd)), closes [#16419](https://github.com/vitejs/vite/issues/16419)
* feat(asset): support `/*@vite-ignore*/` for `new URL(, import.meta.url)` (#16590) ([8880bc5](https://github.com/vitejs/vite/commit/8880bc5)), closes [#16590](https://github.com/vitejs/vite/issues/16590)
* feat(assets): allow `new URL` to resolve package assets (#7837) ([bafccf5](https://github.com/vitejs/vite/commit/bafccf5)), closes [#7837](https://github.com/vitejs/vite/issues/7837)
* feat(build): cleaner logs output (#10895) ([7d24b5f](https://github.com/vitejs/vite/commit/7d24b5f)), closes [#10895](https://github.com/vitejs/vite/issues/10895)
* feat(build): experimental copyPublicDir option (#10550) ([4f4a39f](https://github.com/vitejs/vite/commit/4f4a39f)), closes [#10550](https://github.com/vitejs/vite/issues/10550)
* feat(build): set `hoistTransitiveImports` to false in library builds (#15595) ([e6ebc7b](https://github.com/vitejs/vite/commit/e6ebc7b)), closes [#15595](https://github.com/vitejs/vite/issues/15595)
* feat(build): Use kB in build reporter (#10982) ([b57acfa](https://github.com/vitejs/vite/commit/b57acfa)), closes [#10982](https://github.com/vitejs/vite/issues/10982)
* feat(build): warn dynamic import module with a static import alongside (#12850) ([127c334](https://github.com/vitejs/vite/commit/127c334)), closes [#12850](https://github.com/vitejs/vite/issues/12850)
* feat(cli): add command descriptions (#6991) ([ffda8f0](https://github.com/vitejs/vite/commit/ffda8f0)), closes [#6991](https://github.com/vitejs/vite/issues/6991)
* feat(cli): allow to specify sourcemap mode via --sourcemap build's option (#11505) ([ee3b90a](https://github.com/vitejs/vite/commit/ee3b90a)), closes [#11505](https://github.com/vitejs/vite/issues/11505)
* feat(cli): build --profile (#10719) ([9c808cd](https://github.com/vitejs/vite/commit/9c808cd)), closes [#10719](https://github.com/vitejs/vite/issues/10719)
* feat(cli): clear console by pressing c (#11493) (#11494) ([1ae018f](https://github.com/vitejs/vite/commit/1ae018f)), closes [#11493](https://github.com/vitejs/vite/issues/11493) [#11494](https://github.com/vitejs/vite/issues/11494)
* feat(client): add data-vite-dev-id attribute to style elements (#10080) ([ea09fde](https://github.com/vitejs/vite/commit/ea09fde)), closes [#10080](https://github.com/vitejs/vite/issues/10080)
* feat(client): add debounce on page reload (#13545) ([d080b51](https://github.com/vitejs/vite/commit/d080b51)), closes [#13545](https://github.com/vitejs/vite/issues/13545)
* feat(client): add guide to press Esc for closing the overlay (#13896) ([da389cc](https://github.com/vitejs/vite/commit/da389cc)), closes [#13896](https://github.com/vitejs/vite/issues/13896)
* feat(client): add WebSocket connections events (#13334) ([eb75103](https://github.com/vitejs/vite/commit/eb75103)), closes [#13334](https://github.com/vitejs/vite/issues/13334)
* feat(client): close `vite-error-overlay` with Escape key (#13795) ([85bdcda](https://github.com/vitejs/vite/commit/85bdcda)), closes [#13795](https://github.com/vitejs/vite/issues/13795)
* feat(client): use debug channel on hot updates (#8855) ([0452224](https://github.com/vitejs/vite/commit/0452224)), closes [#8855](https://github.com/vitejs/vite/issues/8855)
* feat(config): `import.meta.filename`/`dirname` support (#15888) ([3efb1a1](https://github.com/vitejs/vite/commit/3efb1a1)), closes [#15888](https://github.com/vitejs/vite/issues/15888)
* feat(config): friendly ESM file require error (#13283) ([b9a6ba0](https://github.com/vitejs/vite/commit/b9a6ba0)), closes [#13283](https://github.com/vitejs/vite/issues/13283)
* feat(config): hmr add disable port config (#6624) ([ce07a0a](https://github.com/vitejs/vite/commit/ce07a0a)), closes [#6624](https://github.com/vitejs/vite/issues/6624)
* feat(create-vite): use typescript 5.0 in templates (#12481) ([8582e2d](https://github.com/vitejs/vite/commit/8582e2d)), closes [#12481](https://github.com/vitejs/vite/issues/12481)
* feat(css): add build.cssMinify (#12207) ([90431f2](https://github.com/vitejs/vite/commit/90431f2)), closes [#12207](https://github.com/vitejs/vite/issues/12207)
* feat(css): add preprocessor option to define stylus vars & funcs (#7227) ([5968bec](https://github.com/vitejs/vite/commit/5968bec)), closes [#7227](https://github.com/vitejs/vite/issues/7227)
* feat(css): add support for Lightning CSS (#12807) ([c6c5d49](https://github.com/vitejs/vite/commit/c6c5d49)), closes [#12807](https://github.com/vitejs/vite/issues/12807)
* feat(css): build assets with the entry name when it is an entry point (#11578) ([fd9a2cc](https://github.com/vitejs/vite/commit/fd9a2cc)), closes [#11578](https://github.com/vitejs/vite/issues/11578)
* feat(css): css.devSourcemap option (#7471) ([57f14cb](https://github.com/vitejs/vite/commit/57f14cb)), closes [#7471](https://github.com/vitejs/vite/issues/7471)
* feat(css): deprecate css default export (#11094) ([01dee1b](https://github.com/vitejs/vite/commit/01dee1b)), closes [#11094](https://github.com/vitejs/vite/issues/11094)
* feat(css): export preprocessCSS API (#10429) ([177b427](https://github.com/vitejs/vite/commit/177b427)), closes [#10429](https://github.com/vitejs/vite/issues/10429)
* feat(css): format error (#9909) ([632fedf](https://github.com/vitejs/vite/commit/632fedf)), closes [#9909](https://github.com/vitejs/vite/issues/9909)
* feat(css): stop injecting `?used` ([fc05454](https://github.com/vitejs/vite/commit/fc05454))
* feat(css): support at import preprocessed styles (#8400) ([2bd6077](https://github.com/vitejs/vite/commit/2bd6077)), closes [#8400](https://github.com/vitejs/vite/issues/8400)
* feat(css): support resolving stylesheets from exports map (#7817) ([108aadf](https://github.com/vitejs/vite/commit/108aadf)), closes [#7817](https://github.com/vitejs/vite/issues/7817)
* feat(css): upgrade postcss-modules (#10987) ([892916d](https://github.com/vitejs/vite/commit/892916d)), closes [#10987](https://github.com/vitejs/vite/issues/10987)
* feat(css): use esbuild.log* options when minifying (#9210) ([88baa53](https://github.com/vitejs/vite/commit/88baa53)), closes [#9210](https://github.com/vitejs/vite/issues/9210)
* feat(css): warn if url rewrite has no importer (#8183) ([0858450](https://github.com/vitejs/vite/commit/0858450)), closes [#8183](https://github.com/vitejs/vite/issues/8183)
* feat(define): handle replacement with esbuild (#11151) ([e4c801c](https://github.com/vitejs/vite/commit/e4c801c)), closes [#11151](https://github.com/vitejs/vite/issues/11151)
* feat(define): prevent assignment (#5515) ([6d4ee18](https://github.com/vitejs/vite/commit/6d4ee18)), closes [#5515](https://github.com/vitejs/vite/issues/5515)
* feat(deps): upgrade rollup to 3.28.0 (#14049) ([490dad8](https://github.com/vitejs/vite/commit/490dad8)), closes [#14049](https://github.com/vitejs/vite/issues/14049)
* feat(dev): added assets to manifest (#6649) ([cdf744d](https://github.com/vitejs/vite/commit/cdf744d)), closes [#6649](https://github.com/vitejs/vite/issues/6649)
* feat(dev): expose APIs for client-server communication (#7437) ([e29ea8e](https://github.com/vitejs/vite/commit/e29ea8e)), closes [#7437](https://github.com/vitejs/vite/issues/7437)
* feat(dev): expose restart function on ViteDevServer (#5723) ([1425a16](https://github.com/vitejs/vite/commit/1425a16)), closes [#5723](https://github.com/vitejs/vite/issues/5723)
* feat(env): support dotenv-expand to contains process env (#10370) ([d5fe92c](https://github.com/vitejs/vite/commit/d5fe92c)), closes [#10370](https://github.com/vitejs/vite/issues/10370)
* feat(glob-import): deprecate as option (#14420) ([953e697](https://github.com/vitejs/vite/commit/953e697)), closes [#14420](https://github.com/vitejs/vite/issues/14420)
* feat(glob-import): support `{ import: '*' }` (#8071) ([0b78b2a](https://github.com/vitejs/vite/commit/0b78b2a)), closes [#8071](https://github.com/vitejs/vite/issues/8071)
* feat(glob): import.meta.glob support alias path (#6526) ([86882ad](https://github.com/vitejs/vite/commit/86882ad)), closes [#6526](https://github.com/vitejs/vite/issues/6526)
* feat(hmr): add full reload reason (#14914) ([60a020e](https://github.com/vitejs/vite/commit/60a020e)), closes [#14914](https://github.com/vitejs/vite/issues/14914)
* feat(hmr): deduplicate paths and join them with commas (#10891) ([967299a](https://github.com/vitejs/vite/commit/967299a)), closes [#10891](https://github.com/vitejs/vite/issues/10891)
* feat(hmr): experimental.hmrPartialAccept (#7324) ([83dab7e](https://github.com/vitejs/vite/commit/83dab7e)), closes [#7324](https://github.com/vitejs/vite/issues/7324)
* feat(hmr): improve circular import updates (#14867) ([b479055](https://github.com/vitejs/vite/commit/b479055)), closes [#14867](https://github.com/vitejs/vite/issues/14867)
* feat(hmr): invalidate message (#10946) ([0d73473](https://github.com/vitejs/vite/commit/0d73473)), closes [#10946](https://github.com/vitejs/vite/issues/10946)
* feat(hmr): reload for circular imports only if error (#15118) ([6ace32b](https://github.com/vitejs/vite/commit/6ace32b)), closes [#15118](https://github.com/vitejs/vite/issues/15118)
* feat(hmr): reload when HTML file is created/deleted (#16288) ([1f53796](https://github.com/vitejs/vite/commit/1f53796)), closes [#16288](https://github.com/vitejs/vite/issues/16288)
* feat(html): clickable error position for html parse error (#11334) ([2e15f3d](https://github.com/vitejs/vite/commit/2e15f3d)), closes [#11334](https://github.com/vitejs/vite/issues/11334)
* feat(html): html simple script tag support import-expression (#6525) ([3546d4f](https://github.com/vitejs/vite/commit/3546d4f)), closes [#6525](https://github.com/vitejs/vite/issues/6525)
* feat(html): Inline entry chunk when possible (#4555) ([e687d98](https://github.com/vitejs/vite/commit/e687d98)), closes [#4555](https://github.com/vitejs/vite/issues/4555)
* feat(html): support env replacement (#12202) ([4f2c49f](https://github.com/vitejs/vite/commit/4f2c49f)), closes [#12202](https://github.com/vitejs/vite/issues/12202)
* feat(html): support image set in inline style (#13473) ([2c0faba](https://github.com/vitejs/vite/commit/2c0faba)), closes [#13473](https://github.com/vitejs/vite/issues/13473)
* feat(importMetaGlob): support sub imports pattern (#12467) ([e355c9c](https://github.com/vitejs/vite/commit/e355c9c)), closes [#12467](https://github.com/vitejs/vite/issues/12467)
* feat(internal): expose printHttpServerUrls ([f94a720](https://github.com/vitejs/vite/commit/f94a720))
* feat(lib): allow multiple entries (#7047) ([65a0fad](https://github.com/vitejs/vite/commit/65a0fad)), closes [#7047](https://github.com/vitejs/vite/issues/7047)
* feat(lib): cjs instead of umd as default format for multiple entries (#10315) ([07d3fbd](https://github.com/vitejs/vite/commit/07d3fbd)), closes [#10315](https://github.com/vitejs/vite/issues/10315)
* feat(node/plugins): esbuild options (#11049) ([735b98b](https://github.com/vitejs/vite/commit/735b98b)), closes [#11049](https://github.com/vitejs/vite/issues/11049)
* feat(optimizer): check optimizeDeps.extensions for scannable files (#14543) ([23ef8a1](https://github.com/vitejs/vite/commit/23ef8a1)), closes [#14543](https://github.com/vitejs/vite/issues/14543)
* feat(optimizer): holdUntilCrawlEnd option (#15244) ([b7c6629](https://github.com/vitejs/vite/commit/b7c6629)), closes [#15244](https://github.com/vitejs/vite/issues/15244)
* feat(optimizer): show a friendly warning with 404 instead of 504 outdated optimize dep (#16080) ([7ee4261](https://github.com/vitejs/vite/commit/7ee4261)), closes [#16080](https://github.com/vitejs/vite/issues/16080)
* feat(optimizer): Support bun lockfile format (#10288) ([931d69b](https://github.com/vitejs/vite/commit/931d69b)), closes [#10288](https://github.com/vitejs/vite/issues/10288)
* feat(optimizer): support glob includes (#12414) ([7792515](https://github.com/vitejs/vite/commit/7792515)), closes [#12414](https://github.com/vitejs/vite/issues/12414)
* feat(optimizer): support patch-package (#10286) ([4fb7ad0](https://github.com/vitejs/vite/commit/4fb7ad0)), closes [#10286](https://github.com/vitejs/vite/issues/10286)
* feat(perf): tsconfck perf improvement (#7055) ([993ea39](https://github.com/vitejs/vite/commit/993ea39)), closes [#7055](https://github.com/vitejs/vite/issues/7055)
* feat(pluginContainer): implement watchChange hook (#14822) ([9369d8d](https://github.com/vitejs/vite/commit/9369d8d)), closes [#14822](https://github.com/vitejs/vite/issues/14822)
* feat(preview): improve error when build output missing (#12096) ([a0702a1](https://github.com/vitejs/vite/commit/a0702a1)), closes [#12096](https://github.com/vitejs/vite/issues/12096)
* feat(preview): support outDir option (#10418) ([15b90b3](https://github.com/vitejs/vite/commit/15b90b3)), closes [#10418](https://github.com/vitejs/vite/issues/10418)
* feat(proxy): Include URL of request in proxy errors (#10508) ([27e2832](https://github.com/vitejs/vite/commit/27e2832)), closes [#10508](https://github.com/vitejs/vite/issues/10508)
* feat(reporter): report built time (#12100) ([f2ad222](https://github.com/vitejs/vite/commit/f2ad222)), closes [#12100](https://github.com/vitejs/vite/issues/12100)
* feat(reporter): show gzip info for all compressible files (fix #11288) (#12485) ([03502c8](https://github.com/vitejs/vite/commit/03502c8)), closes [#11288](https://github.com/vitejs/vite/issues/11288) [#12485](https://github.com/vitejs/vite/issues/12485)
* feat(resolve): auto externalize node builtins for `noExternal: true` in node (#16019) ([1cc88c1](https://github.com/vitejs/vite/commit/1cc88c1)), closes [#16019](https://github.com/vitejs/vite/issues/16019)
* feat(server): add warmupRequest api (#14787) ([8690581](https://github.com/vitejs/vite/commit/8690581)), closes [#14787](https://github.com/vitejs/vite/issues/14787)
* feat(server): allow disabling built-in shortcuts (#15218) ([7fd7c6c](https://github.com/vitejs/vite/commit/7fd7c6c)), closes [#15218](https://github.com/vitejs/vite/issues/15218)
* feat(server): allow to import `data:` uris (#12645) ([4886d9f](https://github.com/vitejs/vite/commit/4886d9f)), closes [#12645](https://github.com/vitejs/vite/issues/12645)
* feat(server): expose server.printUrls() ([96a9ee4](https://github.com/vitejs/vite/commit/96a9ee4))
* feat(server): invalidate module with hmr (#10333) ([8328011](https://github.com/vitejs/vite/commit/8328011)), closes [#10333](https://github.com/vitejs/vite/issues/10333)
* feat(server): support headers configurable (#5580) ([db36e81](https://github.com/vitejs/vite/commit/db36e81)), closes [#5580](https://github.com/vitejs/vite/issues/5580)
* feat(server): trace `error.loc` back to original source (#5467) ([65cd44d](https://github.com/vitejs/vite/commit/65cd44d)), closes [#5467](https://github.com/vitejs/vite/issues/5467)
* feat(ssr): `import.meta.filename`/`dirname` support (#15887) ([74dc73a](https://github.com/vitejs/vite/commit/74dc73a)), closes [#15887](https://github.com/vitejs/vite/issues/15887)
* feat(ssr): add importer path to error msg when invalid url import occur (#11606) ([70729c0](https://github.com/vitejs/vite/commit/70729c0)), closes [#11606](https://github.com/vitejs/vite/issues/11606)
* feat(ssr): debug failed node resolve (#9432) ([364aae1](https://github.com/vitejs/vite/commit/364aae1)), closes [#9432](https://github.com/vitejs/vite/issues/9432)
* feat(ssr): support external true (#10939) ([e451be2](https://github.com/vitejs/vite/commit/e451be2)), closes [#10939](https://github.com/vitejs/vite/issues/10939)
* feat(ssr): support for ssr.resolve.conditions and ssr.resolve.externalConditions options (#14498) ([d0afc39](https://github.com/vitejs/vite/commit/d0afc39)), closes [#14498](https://github.com/vitejs/vite/issues/14498)
* feat(ssr): support preload dynamic css file in html head (#5705) ([07fca95](https://github.com/vitejs/vite/commit/07fca95)), closes [#5705](https://github.com/vitejs/vite/issues/5705)
* feat(ssr): warn if cant analyze dynamic import (#9738) ([e0ecb80](https://github.com/vitejs/vite/commit/e0ecb80)), closes [#9738](https://github.com/vitejs/vite/issues/9738)
* feat(terser): add `maxWorkers` option for terserOptions (#13858) ([884fc3d](https://github.com/vitejs/vite/commit/884fc3d)), closes [#13858](https://github.com/vitejs/vite/issues/13858)
* feat(type): support typing for custom events (#7476) ([50a8765](https://github.com/vitejs/vite/commit/50a8765)), closes [#7476](https://github.com/vitejs/vite/issues/7476)
* feat(types): export Rollup namespace (#12316) ([6e49e52](https://github.com/vitejs/vite/commit/6e49e52)), closes [#12316](https://github.com/vitejs/vite/issues/12316)
* feat(typescript): update tsconfck to add support for `${configDir}` replacement in ts 5.5 (#17350) ([4835e2b](https://github.com/vitejs/vite/commit/4835e2b)), closes [#17350](https://github.com/vitejs/vite/issues/17350)
* feat(vite): pass mode to preview command (#6392) ([1ff1103](https://github.com/vitejs/vite/commit/1ff1103)), closes [#6392](https://github.com/vitejs/vite/issues/6392)
* feat(wasm): new wasm plugin (`.wasm?init`) (#8219) ([75c3bf6](https://github.com/vitejs/vite/commit/75c3bf6)), closes [#8219](https://github.com/vitejs/vite/issues/8219)
* feat(worker): Add sourcemap support for worker bundles (#5417) ([465b6b9](https://github.com/vitejs/vite/commit/465b6b9)), closes [#5417](https://github.com/vitejs/vite/issues/5417)
* feat(worker): bundle worker emit asset file (#6599) ([0ade335](https://github.com/vitejs/vite/commit/0ade335)), closes [#6599](https://github.com/vitejs/vite/issues/6599)
* feat(worker): support a way to name the worker (#14032) ([1f214a4](https://github.com/vitejs/vite/commit/1f214a4)), closes [#14032](https://github.com/vitejs/vite/issues/14032)
* feat(worker): support worker format, plugins and rollupOptions (fix #6191) (#6351) ([133fcea](https://github.com/vitejs/vite/commit/133fcea)), closes [#6191](https://github.com/vitejs/vite/issues/6191) [#6351](https://github.com/vitejs/vite/issues/6351)
* feat(ws): expose `on` / `off` for `server.ws` (#5273) ([6f696be](https://github.com/vitejs/vite/commit/6f696be)), closes [#5273](https://github.com/vitejs/vite/issues/5273)
* build: avoid emitting unused dts files in production build ([cbc633a](https://github.com/vitejs/vite/commit/cbc633a))
* build: avoid generating sourcemap for terser ([c932207](https://github.com/vitejs/vite/commit/c932207))
* build: clean generated type file (#14582) ([fffe16e](https://github.com/vitejs/vite/commit/fffe16e)), closes [#14582](https://github.com/vitejs/vite/issues/14582)
* build: correct d.ts output dir in development (#12212) ([b90bc1f](https://github.com/vitejs/vite/commit/b90bc1f)), closes [#12212](https://github.com/vitejs/vite/issues/12212)
* build: dont strip single line comments (#14969) ([ea9ccb7](https://github.com/vitejs/vite/commit/ea9ccb7)), closes [#14969](https://github.com/vitejs/vite/issues/14969)
* build: fix `declarationDir` for development builds (#6385) ([26512de](https://github.com/vitejs/vite/commit/26512de)), closes [#6385](https://github.com/vitejs/vite/issues/6385)
* build: fix npm package files inclusion ([12e0550](https://github.com/vitejs/vite/commit/12e0550)), closes [#3652](https://github.com/vitejs/vite/issues/3652)
* build: handle latest json-stable-stringify replacement (#15049) ([bcc4a61](https://github.com/vitejs/vite/commit/bcc4a61)), closes [#15049](https://github.com/vitejs/vite/issues/15049)
* build: remove production source map for dist/node ([1c1f82f](https://github.com/vitejs/vite/commit/1c1f82f))
* build: should generate Hi-res sourcemap for dev (#12501) ([1502617](https://github.com/vitejs/vite/commit/1502617)), closes [#12501](https://github.com/vitejs/vite/issues/12501)
* build: strip internal parameters ([1168e57](https://github.com/vitejs/vite/commit/1168e57))
* build: use esbuild to speedup building vite package (#17299) ([6db2515](https://github.com/vitejs/vite/commit/6db2515)), closes [#17299](https://github.com/vitejs/vite/issues/17299)
* build: use rollup-plugin-dts (#14571) ([d89725b](https://github.com/vitejs/vite/commit/d89725b)), closes [#14571](https://github.com/vitejs/vite/issues/14571)
* docs: `server.origin` config trailing slash (fix #6622) (#7865) ([5c1ee5a](https://github.com/vitejs/vite/commit/5c1ee5a)), closes [#6622](https://github.com/vitejs/vite/issues/6622) [#7865](https://github.com/vitejs/vite/issues/7865)
* docs: 4.3 announcement and release notes (#12925) ([f29c582](https://github.com/vitejs/vite/commit/f29c582)), closes [#12925](https://github.com/vitejs/vite/issues/12925)
* docs: add `@shikiji/vitepress-twoslash` (#16168) ([6f8a320](https://github.com/vitejs/vite/commit/6f8a320)), closes [#16168](https://github.com/vitejs/vite/issues/16168)
* docs: add backticks (#6945) ([e234956](https://github.com/vitejs/vite/commit/e234956)), closes [#6945](https://github.com/vitejs/vite/issues/6945)
* docs: add troubleshooting for browser compat (#11877) ([cc00b52](https://github.com/vitejs/vite/commit/cc00b52)), closes [#11877](https://github.com/vitejs/vite/issues/11877)
* docs: change worker config to object instead of array (#6844) ([2c02ce7](https://github.com/vitejs/vite/commit/2c02ce7)), closes [#6844](https://github.com/vitejs/vite/issues/6844)
* docs: clarify assetsInclude (#4955) ([05fae60](https://github.com/vitejs/vite/commit/05fae60)), closes [#4955](https://github.com/vitejs/vite/issues/4955)
* docs: clarify enforce vs hook.order (#16226) ([3a73e48](https://github.com/vitejs/vite/commit/3a73e48)), closes [#16226](https://github.com/vitejs/vite/issues/16226)
* docs: correct description for UserConfig.envDir when used with relative path (#12429) ([2b37cde](https://github.com/vitejs/vite/commit/2b37cde)), closes [#12429](https://github.com/vitejs/vite/issues/12429)
* docs: correct proxy shorthand example (#15938) ([abf766e](https://github.com/vitejs/vite/commit/abf766e)), closes [#15938](https://github.com/vitejs/vite/issues/15938)
* docs: deprecate server.hot (#16741) ([e7d38ab](https://github.com/vitejs/vite/commit/e7d38ab)), closes [#16741](https://github.com/vitejs/vite/issues/16741)
* docs: fix `@rollup/plugin-commonjs` name (#9313) ([c417364](https://github.com/vitejs/vite/commit/c417364)), closes [#9313](https://github.com/vitejs/vite/issues/9313)
* docs: fix alpha changelog links (#8736) ([31348b5](https://github.com/vitejs/vite/commit/31348b5)), closes [#8736](https://github.com/vitejs/vite/issues/8736)
* docs: fix banner image in CHANGELOG.md (#11336) ([45b66f4](https://github.com/vitejs/vite/commit/45b66f4)), closes [#11336](https://github.com/vitejs/vite/issues/11336)
* docs: fix build.cssMinify link (#13840) ([8a2a3e1](https://github.com/vitejs/vite/commit/8a2a3e1)), closes [#13840](https://github.com/vitejs/vite/issues/13840)
* docs: fix grammar in changelog (#11224) ([f1b891f](https://github.com/vitejs/vite/commit/f1b891f)), closes [#11224](https://github.com/vitejs/vite/issues/11224)
* docs: fix incomplete comment (#9466) ([5169c51](https://github.com/vitejs/vite/commit/5169c51)), closes [#9466](https://github.com/vitejs/vite/issues/9466)
* docs: fix invalid jsdoc comments (#10241) ([9acb839](https://github.com/vitejs/vite/commit/9acb839)), closes [#10241](https://github.com/vitejs/vite/issues/10241)
* docs: fix pnpm link (#12803) ([ad358da](https://github.com/vitejs/vite/commit/ad358da)), closes [#12803](https://github.com/vitejs/vite/issues/12803)
* docs: fix preTransformRequests typo (#6319) ([a8a0d84](https://github.com/vitejs/vite/commit/a8a0d84)), closes [#6319](https://github.com/vitejs/vite/issues/6319)
* docs: fix server options link (#9242) ([29db3ea](https://github.com/vitejs/vite/commit/29db3ea)), closes [#9242](https://github.com/vitejs/vite/issues/9242)
* docs: fix typo (#9855) ([583f185](https://github.com/vitejs/vite/commit/583f185)), closes [#9855](https://github.com/vitejs/vite/issues/9855)
* docs: fix typo in changelog (#6201) ([0946796](https://github.com/vitejs/vite/commit/0946796)), closes [#6201](https://github.com/vitejs/vite/issues/6201)
* docs: fix typo in comment (#5123) ([96a2d15](https://github.com/vitejs/vite/commit/96a2d15)), closes [#5123](https://github.com/vitejs/vite/issues/5123)
* docs: fix typos in CHANGELOG (#15825) ([3ee4e7b](https://github.com/vitejs/vite/commit/3ee4e7b)), closes [#15825](https://github.com/vitejs/vite/issues/15825)
* docs: fix typos in comments and documentation (#9711) ([0571232](https://github.com/vitejs/vite/commit/0571232)), closes [#9711](https://github.com/vitejs/vite/issues/9711)
* docs: improve wildcard host note (#8634) ([9a1c1ae](https://github.com/vitejs/vite/commit/9a1c1ae)), closes [#8634](https://github.com/vitejs/vite/issues/8634)
* docs: optimizeDeps.needsInterop (#13323) ([b34e79c](https://github.com/vitejs/vite/commit/b34e79c)), closes [#13323](https://github.com/vitejs/vite/issues/13323)
* docs: point links in messages at https: (#14992) ([d3af879](https://github.com/vitejs/vite/commit/d3af879)), closes [#14992](https://github.com/vitejs/vite/issues/14992)
* docs: port 4.4.10 to 4.5 changelog to main (#14732) ([2728a31](https://github.com/vitejs/vite/commit/2728a31)), closes [#14732](https://github.com/vitejs/vite/issues/14732)
* docs: update api-javascript (#8999) ([05b17df](https://github.com/vitejs/vite/commit/05b17df)), closes [#8999](https://github.com/vitejs/vite/issues/8999)
* docs: update browser baseline features (#9316) ([b82ee5d](https://github.com/vitejs/vite/commit/b82ee5d)), closes [#9316](https://github.com/vitejs/vite/issues/9316)
* docs: update default for optimizeDeps.disabled (#9078) ([4fbf9a8](https://github.com/vitejs/vite/commit/4fbf9a8)), closes [#9078](https://github.com/vitejs/vite/issues/9078)
* docs: update import.meta.glob jsdocs (#9709) ([15ff3a2](https://github.com/vitejs/vite/commit/15ff3a2)), closes [#9709](https://github.com/vitejs/vite/issues/9709)
* docs: update release notes (#7563) ([a74bd7b](https://github.com/vitejs/vite/commit/a74bd7b)), closes [#7563](https://github.com/vitejs/vite/issues/7563)
* docs: update rollup docs links (#11809) ([4bbebf3](https://github.com/vitejs/vite/commit/4bbebf3)), closes [#11809](https://github.com/vitejs/vite/issues/11809)
* docs: update rollup docs links (#12130) ([439a73f](https://github.com/vitejs/vite/commit/439a73f)), closes [#12130](https://github.com/vitejs/vite/issues/12130)
* docs: update WSL2 watch limitation explanation (#8939) ([afbb87d](https://github.com/vitejs/vite/commit/afbb87d)), closes [#8939](https://github.com/vitejs/vite/issues/8939)
* docs: virtual modules internal convention (#5553) ([04016df](https://github.com/vitejs/vite/commit/04016df)), closes [#5553](https://github.com/vitejs/vite/issues/5553)
* docs: worker related notes (#8554) ([c0c5e1a](https://github.com/vitejs/vite/commit/c0c5e1a)), closes [#8554](https://github.com/vitejs/vite/issues/8554)
* docs(changelog): fix broken url (#10692) ([f937ccc](https://github.com/vitejs/vite/commit/f937ccc)), closes [#10692](https://github.com/vitejs/vite/issues/10692)
* docs(changelog): fix raw glob imports syntax (#7540) ([87fbe13](https://github.com/vitejs/vite/commit/87fbe13)), closes [#7540](https://github.com/vitejs/vite/issues/7540)
* docs(chunkSplitting): add `manualChunks` object form syntax warning when it is used with the `splitV ([17511e0](https://github.com/vitejs/vite/commit/17511e0)), closes [#13431](https://github.com/vitejs/vite/issues/13431)
* revert: "fix: upgrade esbuild to 0.20.x" (#16072) ([11cceea](https://github.com/vitejs/vite/commit/11cceea)), closes [#16072](https://github.com/vitejs/vite/issues/16072)
* revert: "fix(css): spread lightningcss options (#14024)" (#14209) ([5778365](https://github.com/vitejs/vite/commit/5778365)), closes [#14024](https://github.com/vitejs/vite/issues/14024) [#14209](https://github.com/vitejs/vite/issues/14209)
* revert: narrow defineConfig return type (#12077) ([54d511e](https://github.com/vitejs/vite/commit/54d511e)), closes [#12077](https://github.com/vitejs/vite/issues/12077)
* revert: perf: use workspace root for fs cache (#15712) (#16476) ([77e7359](https://github.com/vitejs/vite/commit/77e7359)), closes [#15712](https://github.com/vitejs/vite/issues/15712) [#16476](https://github.com/vitejs/vite/issues/16476)
* revert: remove AsyncDisposable (#14908) ([b953b0d](https://github.com/vitejs/vite/commit/b953b0d)), closes [#14908](https://github.com/vitejs/vite/issues/14908)
* perf: avoid `ssrTransform` object allocation (#9706) ([6e58d9d](https://github.com/vitejs/vite/commit/6e58d9d)), closes [#9706](https://github.com/vitejs/vite/issues/9706)
* perf: avoid computing paths on each request (#15318) ([0506812](https://github.com/vitejs/vite/commit/0506812)), closes [#15318](https://github.com/vitejs/vite/issues/15318)
* perf: avoid execSync on openBrowser (#12510) ([a2af2f0](https://github.com/vitejs/vite/commit/a2af2f0)), closes [#12510](https://github.com/vitejs/vite/issues/12510)
* perf: avoid fsp.unlink if we don't use the promise (#12589) ([19d1980](https://github.com/vitejs/vite/commit/19d1980)), closes [#12589](https://github.com/vitejs/vite/issues/12589)
* perf: avoid new URL() in hot path (#12654) ([f4e2fdf](https://github.com/vitejs/vite/commit/f4e2fdf)), closes [#12654](https://github.com/vitejs/vite/issues/12654)
* perf: avoid parseRequest (#15617) ([0cacfad](https://github.com/vitejs/vite/commit/0cacfad)), closes [#15617](https://github.com/vitejs/vite/issues/15617)
* perf: avoid performance.now() call (#15634) ([e43f7ee](https://github.com/vitejs/vite/commit/e43f7ee)), closes [#15634](https://github.com/vitejs/vite/issues/15634)
* perf: avoid side effects resolving in dev and in the optimizer/scanner (#12789) ([fb904f9](https://github.com/vitejs/vite/commit/fb904f9)), closes [#12789](https://github.com/vitejs/vite/issues/12789)
* perf: avoid sourcemap chains during dev (#8796) ([1566f61](https://github.com/vitejs/vite/commit/1566f61)), closes [#8796](https://github.com/vitejs/vite/issues/8796)
* perf: back to temporal optimizer dirs (#12622) ([8da0422](https://github.com/vitejs/vite/commit/8da0422)), closes [#12622](https://github.com/vitejs/vite/issues/12622)
* perf: bundle create-vite (#9034) ([37ac91e](https://github.com/vitejs/vite/commit/37ac91e)), closes [#9034](https://github.com/vitejs/vite/issues/9034)
* perf: cache `depsCacheDirPrefix` value for `isOptimizedDepFile` (#12601) ([edbd262](https://github.com/vitejs/vite/commit/edbd262)), closes [#12601](https://github.com/vitejs/vite/issues/12601)
* perf: cache compiled glob for `server.fs.deny` (#10044) ([df560b0](https://github.com/vitejs/vite/commit/df560b0)), closes [#10044](https://github.com/vitejs/vite/issues/10044)
* perf: cache empty optimizer result (#15245) ([8409b66](https://github.com/vitejs/vite/commit/8409b66)), closes [#15245](https://github.com/vitejs/vite/issues/15245)
* perf: cached fs utils (#15279) ([c9b61c4](https://github.com/vitejs/vite/commit/c9b61c4)), closes [#15279](https://github.com/vitejs/vite/issues/15279)
* perf: disable postcss sourcemap when unused (#8451) ([64fc61c](https://github.com/vitejs/vite/commit/64fc61c)), closes [#8451](https://github.com/vitejs/vite/issues/8451)
* perf: do not bind plugin hook context functions (#15610) ([3b7e0c3](https://github.com/vitejs/vite/commit/3b7e0c3)), closes [#15610](https://github.com/vitejs/vite/issues/15610)
* perf: don't recalculate path.dirname(mod.file) (#15623) ([e459be4](https://github.com/vitejs/vite/commit/e459be4)), closes [#15623](https://github.com/vitejs/vite/issues/15623)
* perf: don't recreate html hooks on each transform call (#15579) ([bdb826c](https://github.com/vitejs/vite/commit/bdb826c)), closes [#15579](https://github.com/vitejs/vite/issues/15579)
* perf: extract regex and use Map in data-uri plugin (#12500) ([137e63d](https://github.com/vitejs/vite/commit/137e63d)), closes [#12500](https://github.com/vitejs/vite/issues/12500)
* perf: extract vite:resolve internal functions (#12522) ([6ea4be2](https://github.com/vitejs/vite/commit/6ea4be2)), closes [#12522](https://github.com/vitejs/vite/issues/12522)
* perf: improve `multilineCommentsRE` regex (fix #10689) (#10751) ([51ed059](https://github.com/vitejs/vite/commit/51ed059)), closes [#10689](https://github.com/vitejs/vite/issues/10689) [#10751](https://github.com/vitejs/vite/issues/10751)
* perf: improve build times and memory utilization (#14016) ([9d7d45e](https://github.com/vitejs/vite/commit/9d7d45e)), closes [#14016](https://github.com/vitejs/vite/issues/14016)
* perf: improve cleanUrl util (#12573) ([68d500e](https://github.com/vitejs/vite/commit/68d500e)), closes [#12573](https://github.com/vitejs/vite/issues/12573)
* perf: improve isFileReadable performance (#12397) ([acf3a14](https://github.com/vitejs/vite/commit/acf3a14)), closes [#12397](https://github.com/vitejs/vite/issues/12397)
* perf: improve isFileReadable performance (#6868) ([62cbe68](https://github.com/vitejs/vite/commit/62cbe68)), closes [#6868](https://github.com/vitejs/vite/issues/6868)
* perf: improve package cache usage (#12512) ([abc2b9c](https://github.com/vitejs/vite/commit/abc2b9c)), closes [#12512](https://github.com/vitejs/vite/issues/12512)
* perf: in-memory public files check (#15195) ([0f9e1bf](https://github.com/vitejs/vite/commit/0f9e1bf)), closes [#15195](https://github.com/vitejs/vite/issues/15195)
* perf: lazy import preview function (#6898) ([2eabcb9](https://github.com/vitejs/vite/commit/2eabcb9)), closes [#6898](https://github.com/vitejs/vite/issues/6898)
* perf: lazy load rollup during dev (#15621) ([6f88a90](https://github.com/vitejs/vite/commit/6f88a90)), closes [#15621](https://github.com/vitejs/vite/issues/15621)
* perf: legacy avoid insert the entry module css (#9761) ([0765ab8](https://github.com/vitejs/vite/commit/0765ab8)), closes [#9761](https://github.com/vitejs/vite/issues/9761)
* perf: middleware to short-circuit on 304 (#15586) ([35ae4f8](https://github.com/vitejs/vite/commit/35ae4f8)), closes [#15586](https://github.com/vitejs/vite/issues/15586)
* perf: minify css only when needed (#5178) ([7970239](https://github.com/vitejs/vite/commit/7970239)), closes [#5178](https://github.com/vitejs/vite/issues/5178)
* perf: module graph url shortcuts (#12635) ([c268cfa](https://github.com/vitejs/vite/commit/c268cfa)), closes [#12635](https://github.com/vitejs/vite/issues/12635)
* perf: more regex improvements (#12520) ([abf536f](https://github.com/vitejs/vite/commit/abf536f)), closes [#12520](https://github.com/vitejs/vite/issues/12520)
* perf: move up external url check before fs path checks (#13639) ([c2ebea1](https://github.com/vitejs/vite/commit/c2ebea1)), closes [#13639](https://github.com/vitejs/vite/issues/13639)
* perf: non-blocking write of optimized dep files (#12603) ([2f5f968](https://github.com/vitejs/vite/commit/2f5f968)), closes [#12603](https://github.com/vitejs/vite/issues/12603)
* perf: optimize getSortedPluginsByHook (#15624) ([f08a037](https://github.com/vitejs/vite/commit/f08a037)), closes [#15624](https://github.com/vitejs/vite/issues/15624)
* perf: optimize logger (#15574) ([0fb9071](https://github.com/vitejs/vite/commit/0fb9071)), closes [#15574](https://github.com/vitejs/vite/issues/15574)
* perf: parallelize await exportsData from depsInfo (#12869) ([ab3a530](https://github.com/vitejs/vite/commit/ab3a530)), closes [#12869](https://github.com/vitejs/vite/issues/12869)
* perf: parallelize imports processing in import analysis plugin (#12754) ([037a6c7](https://github.com/vitejs/vite/commit/037a6c7)), closes [#12754](https://github.com/vitejs/vite/issues/12754)
* perf: pre transform requests while opening the browser (#12809) ([96a4ce3](https://github.com/vitejs/vite/commit/96a4ce3)), closes [#12809](https://github.com/vitejs/vite/issues/12809)
* perf: reduce one if judgment (#14329) ([09ba7c6](https://github.com/vitejs/vite/commit/09ba7c6)), closes [#14329](https://github.com/vitejs/vite/issues/14329)
* perf: reduce preload marker markup size (#14550) ([6f12fd8](https://github.com/vitejs/vite/commit/6f12fd8)), closes [#14550](https://github.com/vitejs/vite/issues/14550)
* perf: reduce runOptimizerIfIdleAfterMs time (#12614) ([d026a65](https://github.com/vitejs/vite/commit/d026a65)), closes [#12614](https://github.com/vitejs/vite/issues/12614)
* perf: reduce size of injected __vite__mapDeps code (#16184) ([c0ec6be](https://github.com/vitejs/vite/commit/c0ec6be)), closes [#16184](https://github.com/vitejs/vite/issues/16184)
* perf: regex to startsWith/slice in utils (#12532) ([debc6e2](https://github.com/vitejs/vite/commit/debc6e2)), closes [#12532](https://github.com/vitejs/vite/issues/12532)
* perf: regexp perf issues, refactor regexp stylistic issues (#10905) ([fc007df](https://github.com/vitejs/vite/commit/fc007df)), closes [#10905](https://github.com/vitejs/vite/issues/10905)
* perf: remove debug only prettifyUrl call (#15204) ([73e971f](https://github.com/vitejs/vite/commit/73e971f)), closes [#15204](https://github.com/vitejs/vite/issues/15204)
* perf: remove regex in ImportMetaURL plugins (#12502) ([1030049](https://github.com/vitejs/vite/commit/1030049)), closes [#12502](https://github.com/vitejs/vite/issues/12502)
* perf: remove unnecessary regex s modifier (#15766) ([8dc1b73](https://github.com/vitejs/vite/commit/8dc1b73)), closes [#15766](https://github.com/vitejs/vite/issues/15766)
* perf: replace endsWith with === (#12539) ([7eb52ec](https://github.com/vitejs/vite/commit/7eb52ec)), closes [#12539](https://github.com/vitejs/vite/issues/12539)
* perf: replace fromEntries with a for loop (#14041) ([8b174fd](https://github.com/vitejs/vite/commit/8b174fd)), closes [#14041](https://github.com/vitejs/vite/issues/14041)
* perf: replace startsWith with === (#12531) ([9cce026](https://github.com/vitejs/vite/commit/9cce026)), closes [#12531](https://github.com/vitejs/vite/issues/12531)
* perf: replace startsWith with === (#13989) ([3aab14e](https://github.com/vitejs/vite/commit/3aab14e)), closes [#13989](https://github.com/vitejs/vite/issues/13989)
* perf: replace startsWith with === (#14005) ([f5c1224](https://github.com/vitejs/vite/commit/f5c1224)), closes [#14005](https://github.com/vitejs/vite/issues/14005)
* perf: replace startsWith with === (#14300) ([75cd29c](https://github.com/vitejs/vite/commit/75cd29c)), closes [#14300](https://github.com/vitejs/vite/issues/14300)
* perf: report compressed size using gzip instead of brotli due to drastic ([deb84c0](https://github.com/vitejs/vite/commit/deb84c0))
* perf: reuse regex in plugins (#12518) ([da43936](https://github.com/vitejs/vite/commit/da43936)), closes [#12518](https://github.com/vitejs/vite/issues/12518)
* perf: shorcircuit resolve in ensure entry from url (#12655) ([82137d6](https://github.com/vitejs/vite/commit/82137d6)), closes [#12655](https://github.com/vitejs/vite/issues/12655)
* perf: simplify explicit import mark in import analysis (#15724) ([2805b2d](https://github.com/vitejs/vite/commit/2805b2d)), closes [#15724](https://github.com/vitejs/vite/issues/15724)
* perf: simplify isHtmlProxy regex (#15590) ([644d120](https://github.com/vitejs/vite/commit/644d120)), closes [#15590](https://github.com/vitejs/vite/issues/15590)
* perf: single slash does not need to be replaced (#13980) ([66f522c](https://github.com/vitejs/vite/commit/66f522c)), closes [#13980](https://github.com/vitejs/vite/issues/13980)
* perf: skip computing sourceRoot in injectSourcesContent (#15207) ([1df1fd1](https://github.com/vitejs/vite/commit/1df1fd1)), closes [#15207](https://github.com/vitejs/vite/issues/15207)
* perf: skip es-module-lexer if have no dynamic imports (#12732) ([5d07d7c](https://github.com/vitejs/vite/commit/5d07d7c)), closes [#12732](https://github.com/vitejs/vite/issues/12732)
* perf: skip windows absolute paths for node resolve (#13162) ([e640939](https://github.com/vitejs/vite/commit/e640939)), closes [#13162](https://github.com/vitejs/vite/issues/13162)
* perf: start preprocessing static imports before updating module graph (#12723) ([c90b46e](https://github.com/vitejs/vite/commit/c90b46e)), closes [#12723](https://github.com/vitejs/vite/issues/12723)
* perf: temporary hack to avoid fs checks for /@react-refresh (#15299) ([b1d6211](https://github.com/vitejs/vite/commit/b1d6211)), closes [#15299](https://github.com/vitejs/vite/issues/15299)
* perf: try using realpathSync.native in Windows (#12580) ([1cc99f8](https://github.com/vitejs/vite/commit/1cc99f8)), closes [#12580](https://github.com/vitejs/vite/issues/12580)
* perf: unresolvedUrlToModule promise cache (#12725) ([80c526e](https://github.com/vitejs/vite/commit/80c526e)), closes [#12725](https://github.com/vitejs/vite/issues/12725)
* perf: use `safeRealpath` in `getRealpath` (#12551) ([cec2320](https://github.com/vitejs/vite/commit/cec2320)), closes [#12551](https://github.com/vitejs/vite/issues/12551)
* perf: use `URL.canParse` (#14068) ([dcee6ef](https://github.com/vitejs/vite/commit/dcee6ef)), closes [#14068](https://github.com/vitejs/vite/issues/14068)
* perf: use fsp in more cases (#12553) ([e9b92f5](https://github.com/vitejs/vite/commit/e9b92f5)), closes [#12553](https://github.com/vitejs/vite/issues/12553)
* perf: use Intl.DateTimeFormatter instead of toLocaleTimeString (#13951) ([af53a1d](https://github.com/vitejs/vite/commit/af53a1d)), closes [#13951](https://github.com/vitejs/vite/issues/13951)
* perf: use Intl.NumberFormat instead of toLocaleString (#13949) ([a48bf88](https://github.com/vitejs/vite/commit/a48bf88)), closes [#13949](https://github.com/vitejs/vite/issues/13949)
* perf: use magic-string hires boundary for sourcemaps (#13971) ([b9a8d65](https://github.com/vitejs/vite/commit/b9a8d65)), closes [#13971](https://github.com/vitejs/vite/issues/13971)
* perf: Use only one ps exec to find a Chromium browser opened on Mac OS (#10588) ([f199e90](https://github.com/vitejs/vite/commit/f199e90)), closes [#10588](https://github.com/vitejs/vite/issues/10588)
* perf: use package cache for one off resolve (#12744) ([77bf4ef](https://github.com/vitejs/vite/commit/77bf4ef)), closes [#12744](https://github.com/vitejs/vite/issues/12744)
* perf: use thread for preprocessors (#13584) ([acd795f](https://github.com/vitejs/vite/commit/acd795f)), closes [#13584](https://github.com/vitejs/vite/issues/13584)
* perf: use transform cache by resolved id (#15785) ([78d838a](https://github.com/vitejs/vite/commit/78d838a)), closes [#15785](https://github.com/vitejs/vite/issues/15785)
* perf: use workspace root for fs cache (#15712) ([8815763](https://github.com/vitejs/vite/commit/8815763)), closes [#15712](https://github.com/vitejs/vite/issues/15712)
* perf(build): disable rollup cache for builds (#11454) ([580ba7a](https://github.com/vitejs/vite/commit/580ba7a)), closes [#11454](https://github.com/vitejs/vite/issues/11454)
* perf(css): cache lazy import (#12721) ([fedb080](https://github.com/vitejs/vite/commit/fedb080)), closes [#12721](https://github.com/vitejs/vite/issues/12721)
* perf(css): hoist at rules with regex (#7691) ([8858180](https://github.com/vitejs/vite/commit/8858180)), closes [#7691](https://github.com/vitejs/vite/issues/7691)
* perf(css): improve postcss config resolve (#12484) ([58e99b6](https://github.com/vitejs/vite/commit/58e99b6)), closes [#12484](https://github.com/vitejs/vite/issues/12484)
* perf(css): only replace empty chunk if imported (#16349) ([e2658ad](https://github.com/vitejs/vite/commit/e2658ad)), closes [#16349](https://github.com/vitejs/vite/issues/16349)
* perf(define): create simple regex for checks (#14788) ([bd15537](https://github.com/vitejs/vite/commit/bd15537)), closes [#14788](https://github.com/vitejs/vite/issues/14788)
* perf(esbuild): make tsconfck non-blocking (#12548) ([e5cdff7](https://github.com/vitejs/vite/commit/e5cdff7)), closes [#12548](https://github.com/vitejs/vite/issues/12548)
* perf(esbuild): update tsconfck to consume faster find-all implementation (#12541) ([b6ea25a](https://github.com/vitejs/vite/commit/b6ea25a)), closes [#12541](https://github.com/vitejs/vite/issues/12541)
* perf(hmr): implement soft invalidation (#14654) ([4150bcb](https://github.com/vitejs/vite/commit/4150bcb)), closes [#14654](https://github.com/vitejs/vite/issues/14654)
* perf(hmr): keep track of already traversed modules when propagating update (#12658) ([3b912fb](https://github.com/vitejs/vite/commit/3b912fb)), closes [#12658](https://github.com/vitejs/vite/issues/12658)
* perf(hmr): skip traversed modules when checking circular imports (#15034) ([41e437f](https://github.com/vitejs/vite/commit/41e437f)), closes [#15034](https://github.com/vitejs/vite/issues/15034)
* perf(html): apply preTransformRequest for html scripts (#12599) ([420782c](https://github.com/vitejs/vite/commit/420782c)), closes [#12599](https://github.com/vitejs/vite/issues/12599)
* perf(lib): improve helper inject regex (#8741) ([19fc7e5](https://github.com/vitejs/vite/commit/19fc7e5)), closes [#8741](https://github.com/vitejs/vite/issues/8741)
* perf(lib): reduce backtrack when injecting esbuild helpers (#8110) ([b993c5f](https://github.com/vitejs/vite/commit/b993c5f)), closes [#8110](https://github.com/vitejs/vite/issues/8110)
* perf(moduleGraph): resolve dep urls in parallel (#12619) ([4823fec](https://github.com/vitejs/vite/commit/4823fec)), closes [#12619](https://github.com/vitejs/vite/issues/12619)
* perf(optimizer): bulk optimizer delay (#12609) ([c881971](https://github.com/vitejs/vite/commit/c881971)), closes [#12609](https://github.com/vitejs/vite/issues/12609)
* perf(optimizer): start optimizer early (#12593) ([4f9b8b4](https://github.com/vitejs/vite/commit/4f9b8b4)), closes [#12593](https://github.com/vitejs/vite/issues/12593)
* perf(resolve): avoid isWorkerRequest and clean up .ts imported a .js (#12571) ([8ab1438](https://github.com/vitejs/vite/commit/8ab1438)), closes [#12571](https://github.com/vitejs/vite/issues/12571)
* perf(resolve): avoid tryFsResolve for /@fs/ paths (#12450) ([3ef8aaa](https://github.com/vitejs/vite/commit/3ef8aaa)), closes [#12450](https://github.com/vitejs/vite/issues/12450)
* perf(resolve): findNearestMainPackageData instead of lookupFile (#12576) ([54b376f](https://github.com/vitejs/vite/commit/54b376f)), closes [#12576](https://github.com/vitejs/vite/issues/12576)
* perf(resolve): fix browser mapping nearest package.json check (#12550) ([eac376e](https://github.com/vitejs/vite/commit/eac376e)), closes [#12550](https://github.com/vitejs/vite/issues/12550)
* perf(resolve): improve file existence check (#11436) ([4a12b89](https://github.com/vitejs/vite/commit/4a12b89)), closes [#11436](https://github.com/vitejs/vite/issues/11436)
* perf(resolve): improve package.json resolve speed (#12441) ([1fc8c65](https://github.com/vitejs/vite/commit/1fc8c65)), closes [#12441](https://github.com/vitejs/vite/issues/12441)
* perf(resolve): reduce vite client path checks (#12471) ([c49af23](https://github.com/vitejs/vite/commit/c49af23)), closes [#12471](https://github.com/vitejs/vite/issues/12471)
* perf(resolve): refactor package.json handling for deep imports (#12461) ([596b661](https://github.com/vitejs/vite/commit/596b661)), closes [#12461](https://github.com/vitejs/vite/issues/12461)
* perf(resolve): refactor tryFsResolve and tryResolveFile (#12542) ([3f70f47](https://github.com/vitejs/vite/commit/3f70f47))
* perf(resolve): skip absolute paths in root as url checks (#12476) ([8d2931b](https://github.com/vitejs/vite/commit/8d2931b)), closes [#12476](https://github.com/vitejs/vite/issues/12476)
* perf(resolve): skip for virtual files (#12638) ([9e13f5f](https://github.com/vitejs/vite/commit/9e13f5f)), closes [#12638](https://github.com/vitejs/vite/issues/12638)
* perf(resolve): support # in path only for dependencies (#12469) ([6559fc7](https://github.com/vitejs/vite/commit/6559fc7)), closes [#12469](https://github.com/vitejs/vite/issues/12469)
* perf(server): only watch .env files in envDir (#12587) ([26d8e72](https://github.com/vitejs/vite/commit/26d8e72)), closes [#12587](https://github.com/vitejs/vite/issues/12587)
* perf(ssr): calculate stacktrace offset lazily (#13256) ([906c4c1](https://github.com/vitejs/vite/commit/906c4c1)), closes [#13256](https://github.com/vitejs/vite/issues/13256)
* perf(transformRequest): fast-path watch and sourcemap handling (#16170) ([de60f1e](https://github.com/vitejs/vite/commit/de60f1e)), closes [#16170](https://github.com/vitejs/vite/issues/16170)
* style: update overlay style on mobile (#15760) ([4559ac0](https://github.com/vitejs/vite/commit/4559ac0)), closes [#15760](https://github.com/vitejs/vite/issues/15760)
* style(client): overlay frame show scrollbar (#14701) ([8aa4134](https://github.com/vitejs/vite/commit/8aa4134)), closes [#14701](https://github.com/vitejs/vite/issues/14701)
* style(utils): remove null check (#16112) ([0d2df52](https://github.com/vitejs/vite/commit/0d2df52)), closes [#16112](https://github.com/vitejs/vite/issues/16112)
*  fix: revert #6251 (#6290) ([83ad7bf](https://github.com/vitejs/vite/commit/83ad7bf)), closes [#6251](https://github.com/vitejs/vite/issues/6251) [#6290](https://github.com/vitejs/vite/issues/6290)
* build!: bump targets (#8045) ([66efd69](https://github.com/vitejs/vite/commit/66efd69)), closes [#8045](https://github.com/vitejs/vite/issues/8045)
* build!: remove node v12 support (#7833) ([eeac2d2](https://github.com/vitejs/vite/commit/eeac2d2)), closes [#7833](https://github.com/vitejs/vite/issues/7833)
* chore!: bump esbuild to 0.15.6 (#9934) ([091537c](https://github.com/vitejs/vite/commit/091537c)), closes [#9934](https://github.com/vitejs/vite/issues/9934)
* chore!: update rollup commonjs plugin to v22  (#8743) ([d4dcdd1](https://github.com/vitejs/vite/commit/d4dcdd1)), closes [#8743](https://github.com/vitejs/vite/issues/8743)
* chore(client)!: remove never implemented hot.decline (#11036) ([e257e3b](https://github.com/vitejs/vite/commit/e257e3b)), closes [#11036](https://github.com/vitejs/vite/issues/11036)
* chore(deps)!: update esbuild to 0.16.1 (#11235) ([d90a262](https://github.com/vitejs/vite/commit/d90a262)), closes [#11235](https://github.com/vitejs/vite/issues/11235)
* feat!: add extension to internal virtual modules (#14231) ([9594c70](https://github.com/vitejs/vite/commit/9594c70)), closes [#14231](https://github.com/vitejs/vite/issues/14231)
* feat!: add isPreview to ConfigEnv and resolveConfig (#14855) ([d195860](https://github.com/vitejs/vite/commit/d195860)), closes [#14855](https://github.com/vitejs/vite/issues/14855)
* feat!: allow path containing . to fallback to index.html (#14142) ([1ae4cbd](https://github.com/vitejs/vite/commit/1ae4cbd)), closes [#14142](https://github.com/vitejs/vite/issues/14142)
* feat!: appType (spa, mpa, custom), boolean middlewareMode (#8452) ([14db473](https://github.com/vitejs/vite/commit/14db473)), closes [#8452](https://github.com/vitejs/vite/issues/8452)
* feat!: bump minimum node version to 18 (#14030) ([2c1a45c](https://github.com/vitejs/vite/commit/2c1a45c)), closes [#14030](https://github.com/vitejs/vite/issues/14030)
* feat!: deprecate cjs node api (#14278) ([404f30f](https://github.com/vitejs/vite/commit/404f30f)), closes [#14278](https://github.com/vitejs/vite/issues/14278)
* feat!: migrate to ESM (#8178) ([76fdc27](https://github.com/vitejs/vite/commit/76fdc27)), closes [#8178](https://github.com/vitejs/vite/issues/8178)
* feat!: relative base (#7644) ([09648c2](https://github.com/vitejs/vite/commit/09648c2)), closes [#7644](https://github.com/vitejs/vite/issues/7644)
* feat!: remove ssr proxy for externalized modules (#14521) ([5786837](https://github.com/vitejs/vite/commit/5786837)), closes [#14521](https://github.com/vitejs/vite/issues/14521)
* feat!: rework `import.meta.glob` (#7537) ([330e0a9](https://github.com/vitejs/vite/commit/330e0a9)), closes [#7537](https://github.com/vitejs/vite/issues/7537)
* feat!: rollup v4 (#14508) ([dee6067](https://github.com/vitejs/vite/commit/dee6067)), closes [#14508](https://github.com/vitejs/vite/issues/14508)
* feat!: server fs strict by default (#5341) ([2136771](https://github.com/vitejs/vite/commit/2136771)), closes [#5341](https://github.com/vitejs/vite/issues/5341)
* feat!: set esbuild default charset to utf8 (#10753) ([4caf4b6](https://github.com/vitejs/vite/commit/4caf4b6)), closes [#10753](https://github.com/vitejs/vite/issues/10753)
* feat!: support `safari14` by default for wider ES2020 compatibility (#9063) ([3cc65d7](https://github.com/vitejs/vite/commit/3cc65d7)), closes [#9063](https://github.com/vitejs/vite/issues/9063)
* feat!: support multiline values in env files (#10826) ([606e60d](https://github.com/vitejs/vite/commit/606e60d)), closes [#10826](https://github.com/vitejs/vite/issues/10826)
* feat!: update esbuild to 0.18.2 (#13525) ([ab967c0](https://github.com/vitejs/vite/commit/ab967c0)), closes [#13525](https://github.com/vitejs/vite/issues/13525)
* feat!: vite dev default port is now 5173 (#8148) ([1cc2e2d](https://github.com/vitejs/vite/commit/1cc2e2d)), closes [#8148](https://github.com/vitejs/vite/issues/8148)
* feat(build)!: inline SVGs (#14643) ([5acda5e](https://github.com/vitejs/vite/commit/5acda5e)), closes [#14643](https://github.com/vitejs/vite/issues/14643)
* feat(css)!: remove css default export ([b6c44cd](https://github.com/vitejs/vite/commit/b6c44cd))
* feat(resolve)!: remove `resolve.browserField` (#14733) ([43cc3b9](https://github.com/vitejs/vite/commit/43cc3b9)), closes [#14733](https://github.com/vitejs/vite/issues/14733)
* feat(shortcuts)!: remove setRawMode (#14342) ([536631a](https://github.com/vitejs/vite/commit/536631a)), closes [#14342](https://github.com/vitejs/vite/issues/14342)
* feat(ssr)!: remove dedupe and mode support for CJS (#11101) ([3090564](https://github.com/vitejs/vite/commit/3090564)), closes [#11101](https://github.com/vitejs/vite/issues/11101)
* fix!: avoid rewriting this (reverts #5312) (#14098) ([9b7b4ed](https://github.com/vitejs/vite/commit/9b7b4ed)), closes [#5312](https://github.com/vitejs/vite/issues/5312) [#14098](https://github.com/vitejs/vite/issues/14098)
* fix!: do not fixStacktrace by default (#7995) ([23f8e08](https://github.com/vitejs/vite/commit/23f8e08)), closes [#7995](https://github.com/vitejs/vite/issues/7995)
* fix!: make `NODE_ENV` more predictable (#10996) ([8148af7](https://github.com/vitejs/vite/commit/8148af7)), closes [#10996](https://github.com/vitejs/vite/issues/10996)
* fix!: put manifest files in .vite directory by default (#14230) ([74fa024](https://github.com/vitejs/vite/commit/74fa024)), closes [#14230](https://github.com/vitejs/vite/issues/14230)
* fix!: return 404 for resources requests outside the base path (#5657) ([40fd2d9](https://github.com/vitejs/vite/commit/40fd2d9)), closes [#5657](https://github.com/vitejs/vite/issues/5657)
* fix!: update node types peer dep range (#14280) ([8f87e86](https://github.com/vitejs/vite/commit/8f87e86)), closes [#14280](https://github.com/vitejs/vite/issues/14280)
* fix!: worker.plugins is a function (#14685) ([9d09dfe](https://github.com/vitejs/vite/commit/9d09dfe)), closes [#14685](https://github.com/vitejs/vite/issues/14685)
* fix(config)!: support development build (#11045) ([8b3d656](https://github.com/vitejs/vite/commit/8b3d656)), closes [#11045](https://github.com/vitejs/vite/issues/11045)
* fix(html)!: align html serving between dev and preview (#14756) ([4f71ae8](https://github.com/vitejs/vite/commit/4f71ae8)), closes [#14756](https://github.com/vitejs/vite/issues/14756)
* fix(lib)!: remove format prefixes for cjs and esm (#8107) ([ad8c3b1](https://github.com/vitejs/vite/commit/ad8c3b1)), closes [#8107](https://github.com/vitejs/vite/issues/8107)
* fix(resolve)!: remove special .mjs handling (#14723) ([2141d31](https://github.com/vitejs/vite/commit/2141d31)), closes [#14723](https://github.com/vitejs/vite/issues/14723)
* fix(types)!: expose httpServer with Http2SecureServer union (#14834) ([ab5bb40](https://github.com/vitejs/vite/commit/ab5bb40)), closes [#14834](https://github.com/vitejs/vite/issues/14834)
* refactor!: align preview api (#5407) ([4edb336](https://github.com/vitejs/vite/commit/4edb336)), closes [#5407](https://github.com/vitejs/vite/issues/5407)
* refactor!: make terser an optional dependency (#8049) ([164f528](https://github.com/vitejs/vite/commit/164f528)), closes [#8049](https://github.com/vitejs/vite/issues/8049)
* refactor!: merge `PreviewServerForHook` into `PreviewServer` type (#14119) ([e0eb07c](https://github.com/vitejs/vite/commit/e0eb07c)), closes [#14119](https://github.com/vitejs/vite/issues/14119)
* refactor!: move basic ssl setup to external plugin, fix #8532 (#8961) ([5c6cf5a](https://github.com/vitejs/vite/commit/5c6cf5a)), closes [#8532](https://github.com/vitejs/vite/issues/8532) [#8961](https://github.com/vitejs/vite/issues/8961)
* refactor!: move side effect of restart server to the caller (#8746) ([521ca58](https://github.com/vitejs/vite/commit/521ca58)), closes [#8746](https://github.com/vitejs/vite/issues/8746)
* refactor!: plugin container API options (#5294) ([5143f1a](https://github.com/vitejs/vite/commit/5143f1a)), closes [#5294](https://github.com/vitejs/vite/issues/5294)
* refactor!: plugin hooks ssr param to object (#5253) ([d5e51f4](https://github.com/vitejs/vite/commit/d5e51f4)), closes [#5253](https://github.com/vitejs/vite/issues/5253)
* refactor!: remove `resolvePackageEntry` and `resolvePackageData` APIs (#14584) ([339f300](https://github.com/vitejs/vite/commit/339f300)), closes [#14584](https://github.com/vitejs/vite/issues/14584)
* refactor!: remove `server.force` (#14530) ([33ecfd9](https://github.com/vitejs/vite/commit/33ecfd9)), closes [#14530](https://github.com/vitejs/vite/issues/14530)
* refactor!: remove exporting internal APIs (#14583) ([7861a33](https://github.com/vitejs/vite/commit/7861a33)), closes [#14583](https://github.com/vitejs/vite/issues/14583)
* refactor!: remove https flag (#14681) ([5b65bfd](https://github.com/vitejs/vite/commit/5b65bfd)), closes [#14681](https://github.com/vitejs/vite/issues/14681)
* refactor!: remove jest condition (#14544) ([8d18a91](https://github.com/vitejs/vite/commit/8d18a91)), closes [#14544](https://github.com/vitejs/vite/issues/14544)
* refactor!: remove non boolean middleware mode (#14792) ([deb5515](https://github.com/vitejs/vite/commit/deb5515)), closes [#14792](https://github.com/vitejs/vite/issues/14792)
* refactor(esbuild)!: remove esbuild 0.17 -> 0.18 compat (#14804) ([7234021](https://github.com/vitejs/vite/commit/7234021)), closes [#14804](https://github.com/vitejs/vite/issues/14804)
* refactor(glob)!: remove `import.meta.globEager` (#14118) ([fdfb61f](https://github.com/vitejs/vite/commit/fdfb61f)), closes [#14118](https://github.com/vitejs/vite/issues/14118)
* refactor(preview)!: use base middleware (#14818) ([69737f4](https://github.com/vitejs/vite/commit/69737f4)), closes [#14818](https://github.com/vitejs/vite/issues/14818)
* refactor(shortcuts)!: tweak shortcuts api (#14749) ([0ae2e1d](https://github.com/vitejs/vite/commit/0ae2e1d)), closes [#14749](https://github.com/vitejs/vite/issues/14749)
* refactor(types)!: remove facade type files (#10903) ([a309058](https://github.com/vitejs/vite/commit/a309058)), closes [#10903](https://github.com/vitejs/vite/issues/10903)
* ci: should exit when build-types-check failed (#12378) ([821d6b8](https://github.com/vitejs/vite/commit/821d6b8)), closes [#12378](https://github.com/vitejs/vite/issues/12378)
* dx: sourcemap combine debug utils (#8307) ([45dba50](https://github.com/vitejs/vite/commit/45dba50)), closes [#8307](https://github.com/vitejs/vite/issues/8307)
* workflow: separate version bumping and publishing on release (#6879) ([fe8ef39](https://github.com/vitejs/vite/commit/fe8ef39)), closes [#6879](https://github.com/vitejs/vite/issues/6879)
* workflow: switch to pnpm (#5060) ([3e1cce0](https://github.com/vitejs/vite/commit/3e1cce0)), closes [#5060](https://github.com/vitejs/vite/issues/5060)



## <small>5.3.4 (2024-07-16)</small>

* fix: update Terser type definitions (fix #17668) (#17669) ([b723a75](https://github.com/vitejs/vite/commit/b723a75)), closes [#17668](https://github.com/vitejs/vite/issues/17668) [#17669](https://github.com/vitejs/vite/issues/17669)
* fix(build): skip preload treeshaking for nested braces (#17687) ([4be96b4](https://github.com/vitejs/vite/commit/4be96b4)), closes [#17687](https://github.com/vitejs/vite/issues/17687)
* fix(css): include `.css?url` in assets field of manifest (#17623) ([1465b20](https://github.com/vitejs/vite/commit/1465b20)), closes [#17623](https://github.com/vitejs/vite/issues/17623)
* fix(worker): nested inlined worker always fallbacked to data URI worker instead of using blob worker ([07bc489](https://github.com/vitejs/vite/commit/07bc489)), closes [#17509](https://github.com/vitejs/vite/issues/17509)
* refactor: replace includes with logical operations (#17620) ([c4a2227](https://github.com/vitejs/vite/commit/c4a2227)), closes [#17620](https://github.com/vitejs/vite/issues/17620)
* chore: add callback to http-proxy.d.ts jsdoc (#17646) ([d8a5d70](https://github.com/vitejs/vite/commit/d8a5d70)), closes [#17646](https://github.com/vitejs/vite/issues/17646)



## <small>5.3.3 (2024-07-03)</small>

* fix: lazily evaluate __vite__mapDeps files (#17602) ([dafff4a](https://github.com/vitejs/vite/commit/dafff4a)), closes [#17602](https://github.com/vitejs/vite/issues/17602)
* fix(deps): update all non-major dependencies (#17590) ([012490c](https://github.com/vitejs/vite/commit/012490c)), closes [#17590](https://github.com/vitejs/vite/issues/17590)
* fix(lib): remove pure CSS dynamic import (#17601) ([055f1c1](https://github.com/vitejs/vite/commit/055f1c1)), closes [#17601](https://github.com/vitejs/vite/issues/17601)
* fix(proxy): replace changeOrigin changes in 5.3.0 with new rewriteWsOrigin option (#17563) ([14c3d49](https://github.com/vitejs/vite/commit/14c3d49)), closes [#17563](https://github.com/vitejs/vite/issues/17563)



## <small>5.3.2 (2024-06-27)</small>

* fix(client): uniform variable `location` (#17528) ([a8e2f6f](https://github.com/vitejs/vite/commit/a8e2f6f)), closes [#17528](https://github.com/vitejs/vite/issues/17528)
* fix(deps): update all non-major dependencies (#17494) ([bf123f2](https://github.com/vitejs/vite/commit/bf123f2)), closes [#17494](https://github.com/vitejs/vite/issues/17494)
* fix(typescript): correctly expand ${configDir} in tsconfig.json (#17576) ([24c799b](https://github.com/vitejs/vite/commit/24c799b)), closes [#17576](https://github.com/vitejs/vite/issues/17576)
* chore: fix some comments (#17495) ([ec16a5e](https://github.com/vitejs/vite/commit/ec16a5e)), closes [#17495](https://github.com/vitejs/vite/issues/17495)
* chore(deps): update all non-major dependencies (#17553) ([a33a97f](https://github.com/vitejs/vite/commit/a33a97f)), closes [#17553](https://github.com/vitejs/vite/issues/17553)
* chore(deps): update dependency eslint to v9 (#16661) ([6c10662](https://github.com/vitejs/vite/commit/6c10662)), closes [#16661](https://github.com/vitejs/vite/issues/16661)
* chore(deps): update es-module-lexer to 1.5.4 (#17555) ([2d6672f](https://github.com/vitejs/vite/commit/2d6672f)), closes [#17555](https://github.com/vitejs/vite/issues/17555)
* refactor(optimizer): use early continues (#17551) ([7c06ef0](https://github.com/vitejs/vite/commit/7c06ef0)), closes [#17551](https://github.com/vitejs/vite/issues/17551)



## <small>5.3.1 (2024-06-14)</small>

* fix(build): handle preload treeshaking for braces (#17479) ([d355568](https://github.com/vitejs/vite/commit/d355568)), closes [#17479](https://github.com/vitejs/vite/issues/17479)
* fix(build): handle preload treeshaking for commas (#17472) ([3e27071](https://github.com/vitejs/vite/commit/3e27071)), closes [#17472](https://github.com/vitejs/vite/issues/17472)
* fix(build): preload treeshaking ignore equal (#17480) ([6ced135](https://github.com/vitejs/vite/commit/6ced135)), closes [#17480](https://github.com/vitejs/vite/issues/17480)
* chore: consolidate changelog for 5.3 (#17476) ([1f09344](https://github.com/vitejs/vite/commit/1f09344)), closes [#17476](https://github.com/vitejs/vite/issues/17476)



## 5.3.0 (2024-06-13)

### Features

* feat: asset type add bmp (#17439) ([ec287f8](https://github.com/vitejs/vite/commit/ec287f8)), closes [#17439](https://github.com/vitejs/vite/issues/17439)
* feat(typescript): update tsconfck to add support for `${configDir}` replacement in ts 5.5 (#17350) ([4835e2b](https://github.com/vitejs/vite/commit/4835e2b)), closes [#17350](https://github.com/vitejs/vite/issues/17350)
* refactor(build): remove quotes from preload marker (#16562) ([9853190](https://github.com/vitejs/vite/commit/9853190)), closes [#16562](https://github.com/vitejs/vite/issues/16562)
* feat: add 'system' library format (#11256) ([4102ca9](https://github.com/vitejs/vite/commit/4102ca9)), closes [#11256](https://github.com/vitejs/vite/issues/11256)
* feat: add an option to not start a websocket server (#16219) ([14b5ced](https://github.com/vitejs/vite/commit/14b5ced)), closes [#16219](https://github.com/vitejs/vite/issues/16219)
* feat: add headTagInsertCheck warning (#16555) ([9f02a9f](https://github.com/vitejs/vite/commit/9f02a9f)), closes [#16555](https://github.com/vitejs/vite/issues/16555)
* feat(asset): support `/*@vite-ignore*/` for `new URL(, import.meta.url)` (#16590) ([8880bc5](https://github.com/vitejs/vite/commit/8880bc5)), closes [#16590](https://github.com/vitejs/vite/issues/16590)
* chore(deps): update esbuild (#17290) ([5f13bf8](https://github.com/vitejs/vite/commit/5f13bf8)), closes [#17290](https://github.com/vitejs/vite/issues/17290)

### Performance

* refactor: plugin container (#17288) ([4aa4a80](https://github.com/vitejs/vite/commit/4aa4a80)), closes [#17288](https://github.com/vitejs/vite/issues/17288)
* refactor: remove acorn (#16238) ([454e2d1](https://github.com/vitejs/vite/commit/454e2d1)), closes [#16238](https://github.com/vitejs/vite/issues/16238)

### Fixes

* fix: typo in client log (#17363) ([68aa9f8](https://github.com/vitejs/vite/commit/68aa9f8)), closes [#17363](https://github.com/vitejs/vite/issues/17363)
* fix(ssrTransform): handle arbitrary module namespace identifiers (#17446) ([0a76652](https://github.com/vitejs/vite/commit/0a76652)), closes [#17446](https://github.com/vitejs/vite/issues/17446)
* fix: gracefully shutdown preview server on `SIGTERM` (fix #12990) (#17333) ([2207a68](https://github.com/vitejs/vite/commit/2207a68)), closes [#12990](https://github.com/vitejs/vite/issues/12990) [#17333](https://github.com/vitejs/vite/issues/17333)
* fix(css): ensure order of extracted CSS (#16588) ([a52ed1d](https://github.com/vitejs/vite/commit/a52ed1d)), closes [#16588](https://github.com/vitejs/vite/issues/16588)
* fix(deps): update all non-major dependencies (#17430) ([4453d35](https://github.com/vitejs/vite/commit/4453d35)), closes [#17430](https://github.com/vitejs/vite/issues/17430)
* fix(build): allow dynamic import treeshaking when injecting preload (#14221) ([f43f71f](https://github.com/vitejs/vite/commit/f43f71f)), closes [#14221](https://github.com/vitejs/vite/issues/14221)
* fix(css): handle lightningcss minification in Deno (#17372) ([b3f5bd1](https://github.com/vitejs/vite/commit/b3f5bd1)), closes [#17372](https://github.com/vitejs/vite/issues/17372)
* fix(css): handle url replacing when preprocessing with lightningcss (#17364) ([6fbb5e0](https://github.com/vitejs/vite/commit/6fbb5e0)), closes [#17364](https://github.com/vitejs/vite/issues/17364)
* fix(ssr): remove pure CSS dynamic import (#17371) ([67ff94b](https://github.com/vitejs/vite/commit/67ff94b)), closes [#17371](https://github.com/vitejs/vite/issues/17371)
* fix(ssr): resolve interlocking circular dependency issues (#15395) ([687c38b](https://github.com/vitejs/vite/commit/687c38b)), closes [#15395](https://github.com/vitejs/vite/issues/15395)
* fix: adjust import analysis behavior to match Node (#16738) ([f599ab4](https://github.com/vitejs/vite/commit/f599ab4)), closes [#16738](https://github.com/vitejs/vite/issues/16738)
* fix: prevent unhandledRejection if `--open` fails (#16726) ([1f60647](https://github.com/vitejs/vite/commit/1f60647)), closes [#16726](https://github.com/vitejs/vite/issues/16726)
* fix(optimize-deps): don't externalize JS files imported with asset extensions (#16242) ([4161843](https://github.com/vitejs/vite/commit/4161843)), closes [#16242](https://github.com/vitejs/vite/issues/16242)
* fix(proxy): rewrite the origin header to match the target for ws proxy (#16558) ([7b0a65e](https://github.com/vitejs/vite/commit/7b0a65e)), closes [#16558](https://github.com/vitejs/vite/issues/16558)

### Chore

* test: disable isolate for unit test (#17448) ([f16fae5](https://github.com/vitejs/vite/commit/f16fae5)), closes [#17448](https://github.com/vitejs/vite/issues/17448)
* build: use esbuild to speedup building vite package (#17299) ([6db2515](https://github.com/vitejs/vite/commit/6db2515)), closes [#17299](https://github.com/vitejs/vite/issues/17299)
* chore: add error recovery option to LightningCSSOptions (#17420) ([e04193f](https://github.com/vitejs/vite/commit/e04193f)), closes [#17420](https://github.com/vitejs/vite/issues/17420)
* chore(deps): update dependency @rollup/plugin-commonjs to v26 (#17431) ([507b3de](https://github.com/vitejs/vite/commit/507b3de)), closes [#17431](https://github.com/vitejs/vite/issues/17431)
* chore: add region comment (#17370) ([a8c7083](https://github.com/vitejs/vite/commit/a8c7083)), closes [#17370](https://github.com/vitejs/vite/issues/17370)
* chore(deps): update all non-major dependencies (#17373) ([f2d52f1](https://github.com/vitejs/vite/commit/f2d52f1)), closes [#17373](https://github.com/vitejs/vite/issues/17373)



### Previous Changelogs

#### [5.3.0-beta.2](https://github.com/vitejs/vite/compare/v5.3.0-beta.1...v5.3.0-beta.2) (2024-06-10)
See [5.3.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v5.3.0-beta.2/packages/vite/CHANGELOG.md)

#### [5.3.0-beta.1](https://github.com/vitejs/vite/compare/v5.3.0-beta.0...v5.3.0-beta.1) (2024-06-07)
See [5.3.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v5.3.0-beta.1/packages/vite/CHANGELOG.md)

#### [5.3.0-beta.0](https://github.com/vitejs/vite/compare/v5.2.12....v5.3.0-beta.0) (2024-05-30)
See [5.3.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v5.3.0-beta.0/packages/vite/CHANGELOG.md)




## <small>5.2.12 (2024-05-28)</small>

* chore: move to eslint flat config (#16743) ([8f16765](https://github.com/vitejs/vite/commit/8f16765)), closes [#16743](https://github.com/vitejs/vite/issues/16743)
* chore(deps): remove unused deps (#17329) ([5a45745](https://github.com/vitejs/vite/commit/5a45745)), closes [#17329](https://github.com/vitejs/vite/issues/17329)
* chore(deps): update all non-major dependencies (#16722) ([b45922a](https://github.com/vitejs/vite/commit/b45922a)), closes [#16722](https://github.com/vitejs/vite/issues/16722)
* fix: mention `build.rollupOptions.output.manualChunks` instead of  `build.rollupOutput.manualChunks` ([89378c0](https://github.com/vitejs/vite/commit/89378c0)), closes [#16721](https://github.com/vitejs/vite/issues/16721)
* fix(build): make SystemJSWrapRE match lazy (#16633) ([6583ad2](https://github.com/vitejs/vite/commit/6583ad2)), closes [#16633](https://github.com/vitejs/vite/issues/16633)
* fix(css): avoid generating empty JS files when JS files becomes empty but has CSS files imported (#1 ([95fe5a7](https://github.com/vitejs/vite/commit/95fe5a7)), closes [#16078](https://github.com/vitejs/vite/issues/16078)
* fix(css): handle lightningcss compiled css in Deno (#17301) ([8e4e932](https://github.com/vitejs/vite/commit/8e4e932)), closes [#17301](https://github.com/vitejs/vite/issues/17301)
* fix(css): only use files the current bundle contains (#16684) ([15a6ebb](https://github.com/vitejs/vite/commit/15a6ebb)), closes [#16684](https://github.com/vitejs/vite/issues/16684)
* fix(css): page reload was not happening with .css?raw (#16455) ([8041846](https://github.com/vitejs/vite/commit/8041846)), closes [#16455](https://github.com/vitejs/vite/issues/16455)
* fix(deps): update all non-major dependencies (#16603) ([6711553](https://github.com/vitejs/vite/commit/6711553)), closes [#16603](https://github.com/vitejs/vite/issues/16603)
* fix(deps): update all non-major dependencies (#16660) ([bf2f014](https://github.com/vitejs/vite/commit/bf2f014)), closes [#16660](https://github.com/vitejs/vite/issues/16660)
* fix(deps): update all non-major dependencies (#17321) ([4a89766](https://github.com/vitejs/vite/commit/4a89766)), closes [#17321](https://github.com/vitejs/vite/issues/17321)
* fix(error-logging): rollup errors weren't displaying id and codeframe (#16540) ([22dc196](https://github.com/vitejs/vite/commit/22dc196)), closes [#16540](https://github.com/vitejs/vite/issues/16540)
* fix(hmr): normalize the path info (#14255) ([6a085d0](https://github.com/vitejs/vite/commit/6a085d0)), closes [#14255](https://github.com/vitejs/vite/issues/14255)
* fix(hmr): trigger page reload when calling invalidate on root module (#16636) ([2b61cc3](https://github.com/vitejs/vite/commit/2b61cc3)), closes [#16636](https://github.com/vitejs/vite/issues/16636)
* fix(logger): truncate log over 5000 characters long (#16581) ([b0b839a](https://github.com/vitejs/vite/commit/b0b839a)), closes [#16581](https://github.com/vitejs/vite/issues/16581)
* fix(optimizer): log dependencies added by plugins (#16729) ([f0fb987](https://github.com/vitejs/vite/commit/f0fb987)), closes [#16729](https://github.com/vitejs/vite/issues/16729)
* fix(sourcemap): improve sourcemap compatibility for vue2 (#16594) ([913c040](https://github.com/vitejs/vite/commit/913c040)), closes [#16594](https://github.com/vitejs/vite/issues/16594)
* docs: correct proxy shorthand example (#15938) ([abf766e](https://github.com/vitejs/vite/commit/abf766e)), closes [#15938](https://github.com/vitejs/vite/issues/15938)
* docs: deprecate server.hot (#16741) ([e7d38ab](https://github.com/vitejs/vite/commit/e7d38ab)), closes [#16741](https://github.com/vitejs/vite/issues/16741)



## <small>5.2.11 (2024-05-02)</small>

* feat: improve dynamic import variable failure error message (#16519) ([f8feeea](https://github.com/vitejs/vite/commit/f8feeea)), closes [#16519](https://github.com/vitejs/vite/issues/16519)
* fix: dynamic-import-vars plugin normalize path issue (#16518) ([f71ba5b](https://github.com/vitejs/vite/commit/f71ba5b)), closes [#16518](https://github.com/vitejs/vite/issues/16518)
* fix: scripts and styles were missing from built HTML on Windows (#16421) ([0e93f58](https://github.com/vitejs/vite/commit/0e93f58)), closes [#16421](https://github.com/vitejs/vite/issues/16421)
* fix(deps): update all non-major dependencies (#16488) ([2d50be2](https://github.com/vitejs/vite/commit/2d50be2)), closes [#16488](https://github.com/vitejs/vite/issues/16488)
* fix(deps): update all non-major dependencies (#16549) ([2d6a13b](https://github.com/vitejs/vite/commit/2d6a13b)), closes [#16549](https://github.com/vitejs/vite/issues/16549)
* fix(dev): watch publicDir explicitly to include it outside the root (#16502) ([4d83eb5](https://github.com/vitejs/vite/commit/4d83eb5)), closes [#16502](https://github.com/vitejs/vite/issues/16502)
* fix(preload): skip preload for non-static urls (#16556) ([bb79c9b](https://github.com/vitejs/vite/commit/bb79c9b)), closes [#16556](https://github.com/vitejs/vite/issues/16556)
* fix(ssr): handle class declaration and expression name scoping (#16569) ([c071eb3](https://github.com/vitejs/vite/commit/c071eb3)), closes [#16569](https://github.com/vitejs/vite/issues/16569)
* fix(ssr): handle function expression name scoping (#16563) ([02db947](https://github.com/vitejs/vite/commit/02db947)), closes [#16563](https://github.com/vitejs/vite/issues/16563)



## <small>5.2.10 (2024-04-20)</small>

* revert: perf: use workspace root for fs cache (#15712) (#16476) ([77e7359](https://github.com/vitejs/vite/commit/77e7359)), closes [#15712](https://github.com/vitejs/vite/issues/15712) [#16476](https://github.com/vitejs/vite/issues/16476)
* fix: add base to virtual html (#16442) ([721f94d](https://github.com/vitejs/vite/commit/721f94d)), closes [#16442](https://github.com/vitejs/vite/issues/16442)
* fix: adjust esm syntax judgment logic (#16436) ([af72eab](https://github.com/vitejs/vite/commit/af72eab)), closes [#16436](https://github.com/vitejs/vite/issues/16436)
* fix: don't add outDirs to watch.ignored if emptyOutDir is false (#16453) ([6a127d6](https://github.com/vitejs/vite/commit/6a127d6)), closes [#16453](https://github.com/vitejs/vite/issues/16453)
* fix(cspNonce): don't overwrite existing nonce values (#16415) ([b872635](https://github.com/vitejs/vite/commit/b872635)), closes [#16415](https://github.com/vitejs/vite/issues/16415)
* feat: show warning if root is in build.outDir (#16454) ([11444dc](https://github.com/vitejs/vite/commit/11444dc)), closes [#16454](https://github.com/vitejs/vite/issues/16454)
* feat: write cspNonce to style tags (#16419) ([8e54bbd](https://github.com/vitejs/vite/commit/8e54bbd)), closes [#16419](https://github.com/vitejs/vite/issues/16419)
* chore(deps): update dependency eslint-plugin-n to v17 (#16381) ([6cccef7](https://github.com/vitejs/vite/commit/6cccef7)), closes [#16381](https://github.com/vitejs/vite/issues/16381)



## <small>5.2.9 (2024-04-15)</small>

* fix: `fsp.rm` removing files does not take effect (#16032) ([b05c405](https://github.com/vitejs/vite/commit/b05c405)), closes [#16032](https://github.com/vitejs/vite/issues/16032)
* fix: fix accumulated stacks in error overlay (#16393) ([102c2fd](https://github.com/vitejs/vite/commit/102c2fd)), closes [#16393](https://github.com/vitejs/vite/issues/16393)
* fix(deps): update all non-major dependencies (#16376) ([58a2938](https://github.com/vitejs/vite/commit/58a2938)), closes [#16376](https://github.com/vitejs/vite/issues/16376)
* chore: update region comment (#16380) ([77562c3](https://github.com/vitejs/vite/commit/77562c3)), closes [#16380](https://github.com/vitejs/vite/issues/16380)
* perf: reduce size of injected __vite__mapDeps code (#16184) ([c0ec6be](https://github.com/vitejs/vite/commit/c0ec6be)), closes [#16184](https://github.com/vitejs/vite/issues/16184)
* perf(css): only replace empty chunk if imported (#16349) ([e2658ad](https://github.com/vitejs/vite/commit/e2658ad)), closes [#16349](https://github.com/vitejs/vite/issues/16349)



## <small>5.2.8 (2024-04-03)</small>

* fix: csp nonce injection when no closing tag (#16281) (#16282) ([3c85c6b](https://github.com/vitejs/vite/commit/3c85c6b)), closes [#16281](https://github.com/vitejs/vite/issues/16281) [#16282](https://github.com/vitejs/vite/issues/16282)
* fix: do not access document in `/@vite/client` when not defined (#16318) ([646319c](https://github.com/vitejs/vite/commit/646319c)), closes [#16318](https://github.com/vitejs/vite/issues/16318)
* fix: fix sourcemap when using object as `define` value  (#15805) ([445c4f2](https://github.com/vitejs/vite/commit/445c4f2)), closes [#15805](https://github.com/vitejs/vite/issues/15805)
* fix(css): unknown file error happened with lightningcss (#16306) ([01af308](https://github.com/vitejs/vite/commit/01af308)), closes [#16306](https://github.com/vitejs/vite/issues/16306)
* fix(hmr): multiple updates happened when invalidate is called while multiple tabs open (#16307) ([21cc10b](https://github.com/vitejs/vite/commit/21cc10b)), closes [#16307](https://github.com/vitejs/vite/issues/16307)
* fix(scanner): duplicate modules for same id if glob is used in html-like types (#16305) ([eca68fa](https://github.com/vitejs/vite/commit/eca68fa)), closes [#16305](https://github.com/vitejs/vite/issues/16305)
* chore(deps): update all non-major dependencies (#16325) ([a78e265](https://github.com/vitejs/vite/commit/a78e265)), closes [#16325](https://github.com/vitejs/vite/issues/16325)
* refactor: use types from sass instead of @types/sass (#16340) ([4581e83](https://github.com/vitejs/vite/commit/4581e83)), closes [#16340](https://github.com/vitejs/vite/issues/16340)



## <small>5.2.7 (2024-03-29)</small>

* chore: deprecate splitVendorChunkPlugin (#16274) ([45a06da](https://github.com/vitejs/vite/commit/45a06da)), closes [#16274](https://github.com/vitejs/vite/issues/16274)
* fix: skip injecting `__vite__mapDeps` when it's not used (#16271) ([890538a](https://github.com/vitejs/vite/commit/890538a)), closes [#16271](https://github.com/vitejs/vite/issues/16271)
* fix(deps): update all non-major dependencies (#16258) ([7caef42](https://github.com/vitejs/vite/commit/7caef42)), closes [#16258](https://github.com/vitejs/vite/issues/16258)
* fix(hmr): don't mutate module graph when collecting modules (#16302) ([dfffea1](https://github.com/vitejs/vite/commit/dfffea1)), closes [#16302](https://github.com/vitejs/vite/issues/16302)
* fix(hmr): trigger hmr for missing file import errored module after file creation (#16303) ([ffedc06](https://github.com/vitejs/vite/commit/ffedc06)), closes [#16303](https://github.com/vitejs/vite/issues/16303)
* fix(sourcemap): don't warn even if the sourcesContent is an empty string (#16273) ([24e376a](https://github.com/vitejs/vite/commit/24e376a)), closes [#16273](https://github.com/vitejs/vite/issues/16273)
* feat(hmr): reload when HTML file is created/deleted (#16288) ([1f53796](https://github.com/vitejs/vite/commit/1f53796)), closes [#16288](https://github.com/vitejs/vite/issues/16288)



## <small>5.2.6 (2024-03-24)</small>

* fix: `fs.deny` with globs with directories (#16250) ([ba5269c](https://github.com/vitejs/vite/commit/ba5269c)), closes [#16250](https://github.com/vitejs/vite/issues/16250)



## <small>5.2.5 (2024-03-24)</small>

* fix: avoid SSR requests in waitForRequestIdle (#16246) ([7093f77](https://github.com/vitejs/vite/commit/7093f77)), closes [#16246](https://github.com/vitejs/vite/issues/16246)
* docs: clarify enforce vs hook.order (#16226) ([3a73e48](https://github.com/vitejs/vite/commit/3a73e48)), closes [#16226](https://github.com/vitejs/vite/issues/16226)



## <small>5.2.4 (2024-03-23)</small>

* fix: dont resolve imports with malformed URI (#16244) ([fbf69d5](https://github.com/vitejs/vite/commit/fbf69d5)), closes [#16244](https://github.com/vitejs/vite/issues/16244)



## <small>5.2.3 (2024-03-22)</small>

* fix: handle warmup request error correctly (#16223) ([d7c5256](https://github.com/vitejs/vite/commit/d7c5256)), closes [#16223](https://github.com/vitejs/vite/issues/16223)
* fix: skip encode if is data uri (#16233) ([8617e76](https://github.com/vitejs/vite/commit/8617e76)), closes [#16233](https://github.com/vitejs/vite/issues/16233)
* fix(optimizer): fix `optimizeDeps.include` glob syntax for `./*` exports (#16230) ([f184c80](https://github.com/vitejs/vite/commit/f184c80)), closes [#16230](https://github.com/vitejs/vite/issues/16230)
* fix(runtime): fix sourcemap with `prepareStackTrace` (#16220) ([dad7f4f](https://github.com/vitejs/vite/commit/dad7f4f)), closes [#16220](https://github.com/vitejs/vite/issues/16220)
* chore: `utf8` replaced with `utf-8` (#16232) ([9800c73](https://github.com/vitejs/vite/commit/9800c73)), closes [#16232](https://github.com/vitejs/vite/issues/16232)



## <small>5.2.2 (2024-03-20)</small>

* fix(importAnalysis): skip encode in ssr (#16213) ([e4d2d60](https://github.com/vitejs/vite/commit/e4d2d60)), closes [#16213](https://github.com/vitejs/vite/issues/16213)



## <small>5.2.1 (2024-03-20)</small>

* fix: encode path uri only (#16212) ([0b2e40b](https://github.com/vitejs/vite/commit/0b2e40b)), closes [#16212](https://github.com/vitejs/vite/issues/16212)



## 5.2.0 (2024-03-20)

* fix: update client.ts@cleanUrl to accomodate blob protocol (#16182) ([1a3b1d7](https://github.com/vitejs/vite/commit/1a3b1d7)), closes [#16182](https://github.com/vitejs/vite/issues/16182)
* fix(assets): avoid splitting `,` inside query parameter of image URI in srcset property (#16081) ([50caf67](https://github.com/vitejs/vite/commit/50caf67)), closes [#16081](https://github.com/vitejs/vite/issues/16081)
* chore(deps): update all non-major dependencies (#16186) ([842643d](https://github.com/vitejs/vite/commit/842643d)), closes [#16186](https://github.com/vitejs/vite/issues/16186)
* perf(transformRequest): fast-path watch and sourcemap handling (#16170) ([de60f1e](https://github.com/vitejs/vite/commit/de60f1e)), closes [#16170](https://github.com/vitejs/vite/issues/16170)
* docs: add `@shikiji/vitepress-twoslash` (#16168) ([6f8a320](https://github.com/vitejs/vite/commit/6f8a320)), closes [#16168](https://github.com/vitejs/vite/issues/16168)



## 5.2.0-beta.1 (2024-03-14)

* feat: csp nonce support (#16052) ([1d5eec4](https://github.com/vitejs/vite/commit/1d5eec4)), closes [#16052](https://github.com/vitejs/vite/issues/16052)
* feat: formalize waitForRequestsIdle (experimental) (#16135) ([9888843](https://github.com/vitejs/vite/commit/9888843)), closes [#16135](https://github.com/vitejs/vite/issues/16135)
* feat(optimizer): show a friendly warning with 404 instead of 504 outdated optimize dep (#16080) ([7ee4261](https://github.com/vitejs/vite/commit/7ee4261)), closes [#16080](https://github.com/vitejs/vite/issues/16080)
* fix: `sideEffects: []` should work as `sideEffects: false` (#16152) ([f377a84](https://github.com/vitejs/vite/commit/f377a84)), closes [#16152](https://github.com/vitejs/vite/issues/16152)
* fix(esbuild): preserve import.meta even if esbuild.target is set to lower versions (#16151) ([6f77b2b](https://github.com/vitejs/vite/commit/6f77b2b)), closes [#16151](https://github.com/vitejs/vite/issues/16151)
* fix(ssr): crash on circular import (#14441) ([8cd846c](https://github.com/vitejs/vite/commit/8cd846c)), closes [#14441](https://github.com/vitejs/vite/issues/14441)



## 5.2.0-beta.0 (2024-03-12)

* chore: use `@polka/compression` (#16146) ([592c95a](https://github.com/vitejs/vite/commit/592c95a)), closes [#16146](https://github.com/vitejs/vite/issues/16146)
* chore(deps): bump rollup to 4.13.0 (#15295) ([2f95c2b](https://github.com/vitejs/vite/commit/2f95c2b)), closes [#15295](https://github.com/vitejs/vite/issues/15295)
* feat: accept assets to be specified as input (#16087) ([75a9fc6](https://github.com/vitejs/vite/commit/75a9fc6)), closes [#16087](https://github.com/vitejs/vite/issues/16087)
* feat: add entry name to manifest (#15849) ([6d6ae10](https://github.com/vitejs/vite/commit/6d6ae10)), closes [#15849](https://github.com/vitejs/vite/issues/15849)
* feat: convert overlay template to DOM (#15852) ([dd49505](https://github.com/vitejs/vite/commit/dd49505)), closes [#15852](https://github.com/vitejs/vite/issues/15852)
* feat: support for self-referencing (#16068) ([03b9674](https://github.com/vitejs/vite/commit/03b9674)), closes [#16068](https://github.com/vitejs/vite/issues/16068)
* feat(config): `import.meta.filename`/`dirname` support (#15888) ([3efb1a1](https://github.com/vitejs/vite/commit/3efb1a1)), closes [#15888](https://github.com/vitejs/vite/issues/15888)
* feat(resolve): auto externalize node builtins for `noExternal: true` in node (#16019) ([1cc88c1](https://github.com/vitejs/vite/commit/1cc88c1)), closes [#16019](https://github.com/vitejs/vite/issues/16019)
* feat(ssr): `import.meta.filename`/`dirname` support (#15887) ([74dc73a](https://github.com/vitejs/vite/commit/74dc73a)), closes [#15887](https://github.com/vitejs/vite/issues/15887)
* fix: apply correct fs restrictions for Yarn PnP when serving files from node_modules (#15957) ([a149d9e](https://github.com/vitejs/vite/commit/a149d9e)), closes [#15957](https://github.com/vitejs/vite/issues/15957)
* fix: encode URLs correctly (fix #15298) (#15311) ([b10d162](https://github.com/vitejs/vite/commit/b10d162)), closes [#15298](https://github.com/vitejs/vite/issues/15298) [#15311](https://github.com/vitejs/vite/issues/15311)
* fix: upgrade esbuild to 0.20.x (#16079) ([30e5ae3](https://github.com/vitejs/vite/commit/30e5ae3)), closes [#16079](https://github.com/vitejs/vite/issues/16079)
* fix(css): treeshake css modules (#16051) ([17d71ec](https://github.com/vitejs/vite/commit/17d71ec)), closes [#16051](https://github.com/vitejs/vite/issues/16051)
* fix(hmr): call dispose before prune (#15782) ([57628dc](https://github.com/vitejs/vite/commit/57628dc)), closes [#15782](https://github.com/vitejs/vite/issues/15782)
* fix(ssr): apply alias to resolvable dependencies during dev (#15602) ([8e54af6](https://github.com/vitejs/vite/commit/8e54af6)), closes [#15602](https://github.com/vitejs/vite/issues/15602)
* refactor: normalize cache package dir (#15546) ([e030f4b](https://github.com/vitejs/vite/commit/e030f4b)), closes [#15546](https://github.com/vitejs/vite/issues/15546)
* style: update overlay style on mobile (#15760) ([4559ac0](https://github.com/vitejs/vite/commit/4559ac0)), closes [#15760](https://github.com/vitejs/vite/issues/15760)



## <small>5.1.6 (2024-03-11)</small>

* chore(deps): update all non-major dependencies (#16131) ([a862ecb](https://github.com/vitejs/vite/commit/a862ecb)), closes [#16131](https://github.com/vitejs/vite/issues/16131)
* fix: check for publicDir before checking if it is a parent directory (#16046) ([b6fb323](https://github.com/vitejs/vite/commit/b6fb323)), closes [#16046](https://github.com/vitejs/vite/issues/16046)
* fix: escape single quote when relative base is used (#16060) ([8f74ce4](https://github.com/vitejs/vite/commit/8f74ce4)), closes [#16060](https://github.com/vitejs/vite/issues/16060)
* fix: handle function property extension in namespace import (#16113) ([f699194](https://github.com/vitejs/vite/commit/f699194)), closes [#16113](https://github.com/vitejs/vite/issues/16113)
* fix: server middleware mode resolve (#16122) ([8403546](https://github.com/vitejs/vite/commit/8403546)), closes [#16122](https://github.com/vitejs/vite/issues/16122)
* fix(esbuild): update tsconfck to fix bug that could cause a deadlock  (#16124) ([fd9de04](https://github.com/vitejs/vite/commit/fd9de04)), closes [#16124](https://github.com/vitejs/vite/issues/16124)
* fix(worker): hide "The emitted file overwrites" warning if the content is same (#16094) ([60dfa9e](https://github.com/vitejs/vite/commit/60dfa9e)), closes [#16094](https://github.com/vitejs/vite/issues/16094)
* fix(worker): throw error when circular worker import is detected and support self referencing worker ([eef9da1](https://github.com/vitejs/vite/commit/eef9da1)), closes [#16103](https://github.com/vitejs/vite/issues/16103)
* style(utils): remove null check (#16112) ([0d2df52](https://github.com/vitejs/vite/commit/0d2df52)), closes [#16112](https://github.com/vitejs/vite/issues/16112)
* refactor(runtime): share more code between runtime and main bundle (#16063) ([93be84e](https://github.com/vitejs/vite/commit/93be84e)), closes [#16063](https://github.com/vitejs/vite/issues/16063)



## <small>5.1.5 (2024-03-04)</small>

* fix: `__vite__mapDeps` code injection (#15732) ([aff54e1](https://github.com/vitejs/vite/commit/aff54e1)), closes [#15732](https://github.com/vitejs/vite/issues/15732)
* fix: analysing build chunk without dependencies (#15469) ([bd52283](https://github.com/vitejs/vite/commit/bd52283)), closes [#15469](https://github.com/vitejs/vite/issues/15469)
* fix: import with query with imports field (#16085) ([ab823ab](https://github.com/vitejs/vite/commit/ab823ab)), closes [#16085](https://github.com/vitejs/vite/issues/16085)
* fix: normalize literal-only entry pattern (#16010) ([1dccc37](https://github.com/vitejs/vite/commit/1dccc37)), closes [#16010](https://github.com/vitejs/vite/issues/16010)
* fix: optimizeDeps.entries with literal-only pattern(s) (#15853) ([49300b3](https://github.com/vitejs/vite/commit/49300b3)), closes [#15853](https://github.com/vitejs/vite/issues/15853)
* fix: output correct error for empty import specifier (#16055) ([a9112eb](https://github.com/vitejs/vite/commit/a9112eb)), closes [#16055](https://github.com/vitejs/vite/issues/16055)
* fix: upgrade esbuild to 0.20.x (#16062) ([899d9b1](https://github.com/vitejs/vite/commit/899d9b1)), closes [#16062](https://github.com/vitejs/vite/issues/16062)
* fix(runtime): runtime HMR affects only imported files (#15898) ([57463fc](https://github.com/vitejs/vite/commit/57463fc)), closes [#15898](https://github.com/vitejs/vite/issues/15898)
* fix(scanner): respect  `experimentalDecorators: true` (#15206) ([4144781](https://github.com/vitejs/vite/commit/4144781)), closes [#15206](https://github.com/vitejs/vite/issues/15206)
* revert: "fix: upgrade esbuild to 0.20.x" (#16072) ([11cceea](https://github.com/vitejs/vite/commit/11cceea)), closes [#16072](https://github.com/vitejs/vite/issues/16072)
* refactor: share code with vite runtime (#15907) ([b20d542](https://github.com/vitejs/vite/commit/b20d542)), closes [#15907](https://github.com/vitejs/vite/issues/15907)
* refactor(runtime): use functions from `pathe` (#16061) ([aac2ef7](https://github.com/vitejs/vite/commit/aac2ef7)), closes [#16061](https://github.com/vitejs/vite/issues/16061)
* chore(deps): update all non-major dependencies (#16028) ([7cfe80d](https://github.com/vitejs/vite/commit/7cfe80d)), closes [#16028](https://github.com/vitejs/vite/issues/16028)



## <small>5.1.4 (2024-02-21)</small>

* perf: remove unnecessary regex s modifier (#15766) ([8dc1b73](https://github.com/vitejs/vite/commit/8dc1b73)), closes [#15766](https://github.com/vitejs/vite/issues/15766)
* fix: fs cached checks disabled by default for yarn pnp (#15920) ([8b11fea](https://github.com/vitejs/vite/commit/8b11fea)), closes [#15920](https://github.com/vitejs/vite/issues/15920)
* fix: resolve directory correctly when `fs.cachedChecks: true` (#15983) ([4fe971f](https://github.com/vitejs/vite/commit/4fe971f)), closes [#15983](https://github.com/vitejs/vite/issues/15983)
* fix: srcSet with optional descriptor (#15905) ([81b3bd0](https://github.com/vitejs/vite/commit/81b3bd0)), closes [#15905](https://github.com/vitejs/vite/issues/15905)
* fix(deps): update all non-major dependencies (#15959) ([571a3fd](https://github.com/vitejs/vite/commit/571a3fd)), closes [#15959](https://github.com/vitejs/vite/issues/15959)
* fix(watch): build watch fails when outDir is empty string (#15979) ([1d263d3](https://github.com/vitejs/vite/commit/1d263d3)), closes [#15979](https://github.com/vitejs/vite/issues/15979)



## <small>5.1.3 (2024-02-15)</small>

* fix: cachedTransformMiddleware for direct css requests (#15919) ([5099028](https://github.com/vitejs/vite/commit/5099028)), closes [#15919](https://github.com/vitejs/vite/issues/15919)
* refactor(runtime): minor tweaks (#15904) ([63a39c2](https://github.com/vitejs/vite/commit/63a39c2)), closes [#15904](https://github.com/vitejs/vite/issues/15904)
* refactor(runtime): seal ES module namespace object instead of feezing (#15914) ([4172f02](https://github.com/vitejs/vite/commit/4172f02)), closes [#15914](https://github.com/vitejs/vite/issues/15914)



## <small>5.1.2 (2024-02-14)</small>

* fix: normalize import file path info (#15772) ([306df44](https://github.com/vitejs/vite/commit/306df44)), closes [#15772](https://github.com/vitejs/vite/issues/15772)
* fix(build): do not output build time when build fails (#15711) ([added3e](https://github.com/vitejs/vite/commit/added3e)), closes [#15711](https://github.com/vitejs/vite/issues/15711)
* fix(runtime): pass path instead of fileURL to `isFilePathESM` (#15908) ([7b15607](https://github.com/vitejs/vite/commit/7b15607)), closes [#15908](https://github.com/vitejs/vite/issues/15908)
* fix(worker): support UTF-8 encoding in inline workers (fixes #12117) (#15866) ([570e0f1](https://github.com/vitejs/vite/commit/570e0f1)), closes [#12117](https://github.com/vitejs/vite/issues/12117) [#15866](https://github.com/vitejs/vite/issues/15866)
* chore: update license file (#15885) ([d9adf18](https://github.com/vitejs/vite/commit/d9adf18)), closes [#15885](https://github.com/vitejs/vite/issues/15885)
* chore(deps): update all non-major dependencies (#15874) ([d16ce5d](https://github.com/vitejs/vite/commit/d16ce5d)), closes [#15874](https://github.com/vitejs/vite/issues/15874)
* chore(deps): update dependency dotenv-expand to v11 (#15875) ([642d528](https://github.com/vitejs/vite/commit/642d528)), closes [#15875](https://github.com/vitejs/vite/issues/15875)



## <small>5.1.1 (2024-02-09)</small>

* fix: empty CSS file was output when only .css?url is used (#15846) ([b2873ac](https://github.com/vitejs/vite/commit/b2873ac)), closes [#15846](https://github.com/vitejs/vite/issues/15846)
* fix: skip not only .js but also .mjs manifest entries (#15841) ([3d860e7](https://github.com/vitejs/vite/commit/3d860e7)), closes [#15841](https://github.com/vitejs/vite/issues/15841)
* chore: post 5.1 release edits (#15840) ([9da6502](https://github.com/vitejs/vite/commit/9da6502)), closes [#15840](https://github.com/vitejs/vite/issues/15840)



## 5.1.0 (2024-02-08)

Vite 5.1 is out! Read the announcement blog post at https://vitejs.dev/blog/announcing-vite5-1!


* chore: revert #15746 (#15839) ([ed875f8](https://github.com/vitejs/vite/commit/ed875f8)), closes [#15746](https://github.com/vitejs/vite/issues/15746) [#15839](https://github.com/vitejs/vite/issues/15839)
* fix: pass `customLogger` to `loadConfigFromFile` (fix #15824) (#15831) ([55a3427](https://github.com/vitejs/vite/commit/55a3427)), closes [#15824](https://github.com/vitejs/vite/issues/15824) [#15831](https://github.com/vitejs/vite/issues/15831)
* fix(deps): update all non-major dependencies (#15803) ([e0a6ef2](https://github.com/vitejs/vite/commit/e0a6ef2)), closes [#15803](https://github.com/vitejs/vite/issues/15803)
* refactor: remove `vite build --force` (#15837) ([f1a4242](https://github.com/vitejs/vite/commit/f1a4242)), closes [#15837](https://github.com/vitejs/vite/issues/15837)



## 5.1.0-beta.7 (2024-02-07)

* fix: disable fs.cachedChecks for custom watch ignore patterns (#15828) ([9070be3](https://github.com/vitejs/vite/commit/9070be3)), closes [#15828](https://github.com/vitejs/vite/issues/15828)
* fix: judge next dirent cache type (#15787) ([5fbeba3](https://github.com/vitejs/vite/commit/5fbeba3)), closes [#15787](https://github.com/vitejs/vite/issues/15787)
* fix: scan entries when the root is in node_modules (#15746) ([c3e83bb](https://github.com/vitejs/vite/commit/c3e83bb)), closes [#15746](https://github.com/vitejs/vite/issues/15746)
* fix(config): improved warning when root path includes bad characters (#15761) ([1c0dc3d](https://github.com/vitejs/vite/commit/1c0dc3d)), closes [#15761](https://github.com/vitejs/vite/issues/15761)
* docs: fix typos in CHANGELOG (#15825) ([3ee4e7b](https://github.com/vitejs/vite/commit/3ee4e7b)), closes [#15825](https://github.com/vitejs/vite/issues/15825)
* perf: use transform cache by resolved id (#15785) ([78d838a](https://github.com/vitejs/vite/commit/78d838a)), closes [#15785](https://github.com/vitejs/vite/issues/15785)
* chore: release notes (#15777) ([775bb50](https://github.com/vitejs/vite/commit/775bb50)), closes [#15777](https://github.com/vitejs/vite/issues/15777)



## 5.1.0-beta.6 (2024-02-01)

* feat: experimental Vite Runtime API (#12165) ([8b3ab07](https://github.com/vitejs/vite/commit/8b3ab07)), closes [#12165](https://github.com/vitejs/vite/issues/12165)
* fix: add ref() and unref() to chokidar.d.ts for typescript build to work (#15706) ([6b45037](https://github.com/vitejs/vite/commit/6b45037)), closes [#15706](https://github.com/vitejs/vite/issues/15706)
* perf: simplify explicit import mark in import analysis (#15724) ([2805b2d](https://github.com/vitejs/vite/commit/2805b2d)), closes [#15724](https://github.com/vitejs/vite/issues/15724)



## 5.1.0-beta.5 (2024-01-27)

* fix: do not init optimizer during build (#15727) ([a08f646](https://github.com/vitejs/vite/commit/a08f646)), closes [#15727](https://github.com/vitejs/vite/issues/15727)
* fix(deps): update all non-major dependencies (#15675) ([4d9363a](https://github.com/vitejs/vite/commit/4d9363a)), closes [#15675](https://github.com/vitejs/vite/issues/15675)



## 5.1.0-beta.4 (2024-01-26)

* perf: lazy load rollup during dev (#15621) ([6f88a90](https://github.com/vitejs/vite/commit/6f88a90)), closes [#15621](https://github.com/vitejs/vite/issues/15621)
* perf: use workspace root for fs cache (#15712) ([8815763](https://github.com/vitejs/vite/commit/8815763)), closes [#15712](https://github.com/vitejs/vite/issues/15712)
* chore: remove unneeded normalizePath (#15713) ([92f2747](https://github.com/vitejs/vite/commit/92f2747)), closes [#15713](https://github.com/vitejs/vite/issues/15713)
* chore(proxy): update proxy error info (#15678) ([09bd58d](https://github.com/vitejs/vite/commit/09bd58d)), closes [#15678](https://github.com/vitejs/vite/issues/15678)
* feat: enable fs.cachedChecks by default (#15704) ([a05c709](https://github.com/vitejs/vite/commit/a05c709)), closes [#15704](https://github.com/vitejs/vite/issues/15704)
* feat(optimizer): holdUntilCrawlEnd option (#15244) ([b7c6629](https://github.com/vitejs/vite/commit/b7c6629)), closes [#15244](https://github.com/vitejs/vite/issues/15244)
* fix: normalize prettify url (#15705) ([98bc3dc](https://github.com/vitejs/vite/commit/98bc3dc)), closes [#15705](https://github.com/vitejs/vite/issues/15705)
* fix: windows add/delete file ([3a7b650](https://github.com/vitejs/vite/commit/3a7b650))
* fix(build): build error message output twice (#15664) ([74382b9](https://github.com/vitejs/vite/commit/74382b9)), closes [#15664](https://github.com/vitejs/vite/issues/15664)
* fix(hmr): pass id in `parseImports` for better debugging DX (#15707) ([fb4bddc](https://github.com/vitejs/vite/commit/fb4bddc)), closes [#15707](https://github.com/vitejs/vite/issues/15707)
* fix(node): remove timestamp query of `staticImportedUrls` (#15663) ([6c4bf26](https://github.com/vitejs/vite/commit/6c4bf26)), closes [#15663](https://github.com/vitejs/vite/issues/15663)
* fix(preview): set isPreview true (#15695) ([93fce55](https://github.com/vitejs/vite/commit/93fce55)), closes [#15695](https://github.com/vitejs/vite/issues/15695)



## 5.1.0-beta.3 (2024-01-22)

* perf: middleware to short-circuit on 304 (#15586) ([35ae4f8](https://github.com/vitejs/vite/commit/35ae4f8)), closes [#15586](https://github.com/vitejs/vite/issues/15586)
* perf: use thread for preprocessors (#13584) ([acd795f](https://github.com/vitejs/vite/commit/acd795f)), closes [#13584](https://github.com/vitejs/vite/issues/13584)
* fix: default sideEffect option is delivered to rollup (#15665) ([f6cf3d1](https://github.com/vitejs/vite/commit/f6cf3d1)), closes [#15665](https://github.com/vitejs/vite/issues/15665)
* fix(ssr): mark builtin modules as side effect free (#15658) ([526cf23](https://github.com/vitejs/vite/commit/526cf23)), closes [#15658](https://github.com/vitejs/vite/issues/15658)
* fix(ssr): support externalized builtins for webworker (#15656) ([639bbd6](https://github.com/vitejs/vite/commit/639bbd6)), closes [#15656](https://github.com/vitejs/vite/issues/15656)
* refactor: append tags logic in applyHtmlTransforms (#15647) ([09b1517](https://github.com/vitejs/vite/commit/09b1517)), closes [#15647](https://github.com/vitejs/vite/issues/15647)
* refactor(hmr): provide a separate logger interface (#15631) ([110e2e1](https://github.com/vitejs/vite/commit/110e2e1)), closes [#15631](https://github.com/vitejs/vite/issues/15631)



## 5.1.0-beta.2 (2024-01-19)

* fix: fs deny for case insensitive systems (#15653) ([89be67d](https://github.com/vitejs/vite/commit/89be67d)), closes [#15653](https://github.com/vitejs/vite/issues/15653)
* perf: don't recalculate path.dirname(mod.file) (#15623) ([e459be4](https://github.com/vitejs/vite/commit/e459be4)), closes [#15623](https://github.com/vitejs/vite/issues/15623)
* perf: optimize getSortedPluginsByHook (#15624) ([f08a037](https://github.com/vitejs/vite/commit/f08a037)), closes [#15624](https://github.com/vitejs/vite/issues/15624)



## 5.1.0-beta.1 (2024-01-18)

* fix: handle namespace import and dynamic import interop consistently (#15619) ([ec8b420](https://github.com/vitejs/vite/commit/ec8b420)), closes [#15619](https://github.com/vitejs/vite/issues/15619)
* fix(css): track dependencies from addWatchFile for HMR (#15608) ([dfcb83d](https://github.com/vitejs/vite/commit/dfcb83d)), closes [#15608](https://github.com/vitejs/vite/issues/15608)
* fix(deps): update all non-major dependencies (#15603) ([109fb80](https://github.com/vitejs/vite/commit/109fb80)), closes [#15603](https://github.com/vitejs/vite/issues/15603)
* fix(hmr): normalize env files path (#15584) ([d0f1d2e](https://github.com/vitejs/vite/commit/d0f1d2e)), closes [#15584](https://github.com/vitejs/vite/issues/15584)
* fix(ssr): externalize network imports during `ssrLoadModule` (#15599) ([af2aa09](https://github.com/vitejs/vite/commit/af2aa09)), closes [#15599](https://github.com/vitejs/vite/issues/15599)
* fix(types): mark hmr update internal types optional (#15606) ([df8f5a5](https://github.com/vitejs/vite/commit/df8f5a5)), closes [#15606](https://github.com/vitejs/vite/issues/15606)
* perf: avoid parseRequest (#15617) ([0cacfad](https://github.com/vitejs/vite/commit/0cacfad)), closes [#15617](https://github.com/vitejs/vite/issues/15617)
* perf: avoid performance.now() call (#15634) ([e43f7ee](https://github.com/vitejs/vite/commit/e43f7ee)), closes [#15634](https://github.com/vitejs/vite/issues/15634)
* perf: do not bind plugin hook context functions (#15610) ([3b7e0c3](https://github.com/vitejs/vite/commit/3b7e0c3)), closes [#15610](https://github.com/vitejs/vite/issues/15610)
* perf: don't recreate html hooks on each transform call (#15579) ([bdb826c](https://github.com/vitejs/vite/commit/bdb826c)), closes [#15579](https://github.com/vitejs/vite/issues/15579)
* perf: simplify isHtmlProxy regex (#15590) ([644d120](https://github.com/vitejs/vite/commit/644d120)), closes [#15590](https://github.com/vitejs/vite/issues/15590)
* feat: preview server add close method (#15630) ([947aa53](https://github.com/vitejs/vite/commit/947aa53)), closes [#15630](https://github.com/vitejs/vite/issues/15630)
* feat: support multiple HMR clients on the server (#15340) ([bf1e9c2](https://github.com/vitejs/vite/commit/bf1e9c2)), closes [#15340](https://github.com/vitejs/vite/issues/15340)
* feat(build): set `hoistTransitiveImports` to false in library builds (#15595) ([e6ebc7b](https://github.com/vitejs/vite/commit/e6ebc7b)), closes [#15595](https://github.com/vitejs/vite/issues/15595)
* refactor: remove build time pre-bundling (#15184) ([757844f](https://github.com/vitejs/vite/commit/757844f)), closes [#15184](https://github.com/vitejs/vite/issues/15184)



## 5.1.0-beta.0 (2024-01-15)

* fix: await `configResolved` hooks of worker plugins (#15597) ([03c8004](https://github.com/vitejs/vite/commit/03c8004)), closes [#15597](https://github.com/vitejs/vite/issues/15597)
* fix: hmr for env files, regression from #15365 (#15559) ([d1b143f](https://github.com/vitejs/vite/commit/d1b143f)), closes [#15365](https://github.com/vitejs/vite/issues/15365) [#15559](https://github.com/vitejs/vite/issues/15559)
* fix: init dev ssr optimizer on server init (#15561) ([db28b92](https://github.com/vitejs/vite/commit/db28b92)), closes [#15561](https://github.com/vitejs/vite/issues/15561)
* fix: only watch needed env files (#15365) ([476e572](https://github.com/vitejs/vite/commit/476e572)), closes [#15365](https://github.com/vitejs/vite/issues/15365)
* fix: resolvedUrls is null in plugin's configureServer after server restart (#15450) ([653a48c](https://github.com/vitejs/vite/commit/653a48c)), closes [#15450](https://github.com/vitejs/vite/issues/15450)
* fix: revert `package.json` change should trigger server restart (#15519) (#15558) ([9fc5d9c](https://github.com/vitejs/vite/commit/9fc5d9c)), closes [#15519](https://github.com/vitejs/vite/issues/15519) [#15558](https://github.com/vitejs/vite/issues/15558)
* fix: set correct `isSsrBuild` value in dev (#15536) ([fdbe04d](https://github.com/vitejs/vite/commit/fdbe04d)), closes [#15536](https://github.com/vitejs/vite/issues/15536)
* fix: update javascript mime type to text/javascript (#15427) ([a621de8](https://github.com/vitejs/vite/commit/a621de8)), closes [#15427](https://github.com/vitejs/vite/issues/15427)
* fix(build): normalize html path (#15554) ([d0d5938](https://github.com/vitejs/vite/commit/d0d5938)), closes [#15554](https://github.com/vitejs/vite/issues/15554)
* fix(css): @import with .css in node_modules importing a different package failed to resolve (#15000) ([8ccf722](https://github.com/vitejs/vite/commit/8ccf722)), closes [#15000](https://github.com/vitejs/vite/issues/15000)
* fix(css): `.css?url` support (#15259) ([ed56d96](https://github.com/vitejs/vite/commit/ed56d96)), closes [#15259](https://github.com/vitejs/vite/issues/15259)
* fix(css): skip url replace for function calls (#15544) ([21a52e6](https://github.com/vitejs/vite/commit/21a52e6)), closes [#15544](https://github.com/vitejs/vite/issues/15544)
* fix(deps): update all non-major dependencies (#15375) ([ab56227](https://github.com/vitejs/vite/commit/ab56227)), closes [#15375](https://github.com/vitejs/vite/issues/15375)
* fix(esbuild): update to tsconfck 3.0.1 to fix edge cases when resolving tsconfig.extends (#15502) ([1fcebeb](https://github.com/vitejs/vite/commit/1fcebeb)), closes [#15502](https://github.com/vitejs/vite/issues/15502)
* fix(hmr): `package.json` change should trigger server restart (#15519) ([260ebbf](https://github.com/vitejs/vite/commit/260ebbf)), closes [#15519](https://github.com/vitejs/vite/issues/15519)
* fix(hmr): make watcher ignore build.outDir (#15326) ([2836276](https://github.com/vitejs/vite/commit/2836276)), closes [#15326](https://github.com/vitejs/vite/issues/15326)
* fix(hmr): propagate `fs.stat` failure for `hmrContext.read` (#15568) ([c6d240b](https://github.com/vitejs/vite/commit/c6d240b)), closes [#15568](https://github.com/vitejs/vite/issues/15568)
* fix(sourcemap): sourcemap is incorrect when sourcemap has `sources: [null]` (#14588) ([f8c6a34](https://github.com/vitejs/vite/commit/f8c6a34)), closes [#14588](https://github.com/vitejs/vite/issues/14588)
* feat: `build.assetsInlineLimit` callback (#15366) ([4d1342e](https://github.com/vitejs/vite/commit/4d1342e)), closes [#15366](https://github.com/vitejs/vite/issues/15366)
* feat: add '*.m4a' to client.d.ts and constants (#15471) ([ebc37f6](https://github.com/vitejs/vite/commit/ebc37f6)), closes [#15471](https://github.com/vitejs/vite/issues/15471)
* feat: add support for .vtt type (#15538) ([a5c6d3d](https://github.com/vitejs/vite/commit/a5c6d3d)), closes [#15538](https://github.com/vitejs/vite/issues/15538)
* feat(glob-import): deprecate as option (#14420) ([953e697](https://github.com/vitejs/vite/commit/953e697)), closes [#14420](https://github.com/vitejs/vite/issues/14420)
* feat(hmr): reload for circular imports only if error (#15118) ([6ace32b](https://github.com/vitejs/vite/commit/6ace32b)), closes [#15118](https://github.com/vitejs/vite/issues/15118)
* feat(ssr): support external true (#10939) ([e451be2](https://github.com/vitejs/vite/commit/e451be2)), closes [#10939](https://github.com/vitejs/vite/issues/10939)
* refactor: extract '_metadata.json' string to a constant (#15541) ([adda370](https://github.com/vitejs/vite/commit/adda370)), closes [#15541](https://github.com/vitejs/vite/issues/15541)
* refactor: normalize publicDir when resolving config (#15360) ([ea5fdeb](https://github.com/vitejs/vite/commit/ea5fdeb)), closes [#15360](https://github.com/vitejs/vite/issues/15360)
* refactor: remove json-stable-stringify (#15571) ([b9b0816](https://github.com/vitejs/vite/commit/b9b0816)), closes [#15571](https://github.com/vitejs/vite/issues/15571)
* refactor: reuse existing node utils (#15480) ([17ab48a](https://github.com/vitejs/vite/commit/17ab48a)), closes [#15480](https://github.com/vitejs/vite/issues/15480)
* refactor(hmr): keep buffer implementation internal, expose queueUpdate (#15486) ([c029efb](https://github.com/vitejs/vite/commit/c029efb)), closes [#15486](https://github.com/vitejs/vite/issues/15486)
* perf: optimize logger (#15574) ([0fb9071](https://github.com/vitejs/vite/commit/0fb9071)), closes [#15574](https://github.com/vitejs/vite/issues/15574)
* chore: avoid bundling resolve dep (#15570) ([ae49ac4](https://github.com/vitejs/vite/commit/ae49ac4)), closes [#15570](https://github.com/vitejs/vite/issues/15570)
* chore(deps): update dependency postcss-import to v16 (#15533) ([36775c4](https://github.com/vitejs/vite/commit/36775c4)), closes [#15533](https://github.com/vitejs/vite/issues/15533)



## <small>5.0.11 (2024-01-05)</small>

* fix: don't pretransform classic script links (#15361) ([19e3c9a](https://github.com/vitejs/vite/commit/19e3c9a)), closes [#15361](https://github.com/vitejs/vite/issues/15361)
* fix: inject `__vite__mapDeps` code before sourcemap file comment (#15483) ([d2aa096](https://github.com/vitejs/vite/commit/d2aa096)), closes [#15483](https://github.com/vitejs/vite/issues/15483)
* fix(assets): avoid splitting `,` inside base64 value of `srcset` attribute (#15422) ([8de7bd2](https://github.com/vitejs/vite/commit/8de7bd2)), closes [#15422](https://github.com/vitejs/vite/issues/15422)
* fix(html): handle offset magic-string slice error (#15435) ([5ea9edb](https://github.com/vitejs/vite/commit/5ea9edb)), closes [#15435](https://github.com/vitejs/vite/issues/15435)
* chore(deps): update dependency strip-literal to v2 (#15475) ([49d21fe](https://github.com/vitejs/vite/commit/49d21fe)), closes [#15475](https://github.com/vitejs/vite/issues/15475)
* chore(deps): update tj-actions/changed-files action to v41 (#15476) ([2a540ee](https://github.com/vitejs/vite/commit/2a540ee)), closes [#15476](https://github.com/vitejs/vite/issues/15476)



## <small>5.0.10 (2023-12-15)</small>

* fix: omit protocol does not require pre-transform (#15355) ([d9ae1b2](https://github.com/vitejs/vite/commit/d9ae1b2)), closes [#15355](https://github.com/vitejs/vite/issues/15355)
* fix(build): use base64 for inline SVG if it contains both single and double quotes (#15271) ([1bbff16](https://github.com/vitejs/vite/commit/1bbff16)), closes [#15271](https://github.com/vitejs/vite/issues/15271)



## <small>5.0.9 (2023-12-14)</small>

* fix: htmlFallbackMiddleware for favicon (#15301) ([c902545](https://github.com/vitejs/vite/commit/c902545)), closes [#15301](https://github.com/vitejs/vite/issues/15301)
* fix: more stable hash calculation for depsOptimize (#15337) ([2b39fe6](https://github.com/vitejs/vite/commit/2b39fe6)), closes [#15337](https://github.com/vitejs/vite/issues/15337)
* fix(scanner): catch all external files for glob imports (#15286) ([129d0d0](https://github.com/vitejs/vite/commit/129d0d0)), closes [#15286](https://github.com/vitejs/vite/issues/15286)
* fix(server): avoid chokidar throttling on startup (#15347) ([56a5740](https://github.com/vitejs/vite/commit/56a5740)), closes [#15347](https://github.com/vitejs/vite/issues/15347)
* fix(worker): replace `import.meta` correctly for IIFE worker (#15321) ([08d093c](https://github.com/vitejs/vite/commit/08d093c)), closes [#15321](https://github.com/vitejs/vite/issues/15321)
* feat: log re-optimization reasons (#15339) ([b1a6c84](https://github.com/vitejs/vite/commit/b1a6c84)), closes [#15339](https://github.com/vitejs/vite/issues/15339)
* chore: temporary typo (#15329) ([7b71854](https://github.com/vitejs/vite/commit/7b71854)), closes [#15329](https://github.com/vitejs/vite/issues/15329)
* perf: avoid computing paths on each request (#15318) ([0506812](https://github.com/vitejs/vite/commit/0506812)), closes [#15318](https://github.com/vitejs/vite/issues/15318)
* perf: temporary hack to avoid fs checks for /@react-refresh (#15299) ([b1d6211](https://github.com/vitejs/vite/commit/b1d6211)), closes [#15299](https://github.com/vitejs/vite/issues/15299)



## <small>5.0.8 (2023-12-12)</small>

* perf: cached fs utils (#15279) ([c9b61c4](https://github.com/vitejs/vite/commit/c9b61c4)), closes [#15279](https://github.com/vitejs/vite/issues/15279)
* fix: missing warmupRequest in transformIndexHtml (#15303) ([103820f](https://github.com/vitejs/vite/commit/103820f)), closes [#15303](https://github.com/vitejs/vite/issues/15303)
* fix: public files map will be updated on add/unlink in windows (#15317) ([921ca41](https://github.com/vitejs/vite/commit/921ca41)), closes [#15317](https://github.com/vitejs/vite/issues/15317)
* fix(build): decode urls in CSS files (fix #15109) (#15246) ([ea6a7a6](https://github.com/vitejs/vite/commit/ea6a7a6)), closes [#15109](https://github.com/vitejs/vite/issues/15109) [#15246](https://github.com/vitejs/vite/issues/15246)
* fix(deps): update all non-major dependencies (#15304) ([bb07f60](https://github.com/vitejs/vite/commit/bb07f60)), closes [#15304](https://github.com/vitejs/vite/issues/15304)
* fix(ssr): check esm file with normal file path (#15307) ([1597170](https://github.com/vitejs/vite/commit/1597170)), closes [#15307](https://github.com/vitejs/vite/issues/15307)



## <small>5.0.7 (2023-12-08)</small>

* fix: suppress terser warning if minify disabled (#15275) ([3e42611](https://github.com/vitejs/vite/commit/3e42611)), closes [#15275](https://github.com/vitejs/vite/issues/15275)
* fix: symbolic links in public dir (#15264) ([ef2a024](https://github.com/vitejs/vite/commit/ef2a024)), closes [#15264](https://github.com/vitejs/vite/issues/15264)
* fix(html): skip inlining icon and manifest links (#14958) ([8ad81b4](https://github.com/vitejs/vite/commit/8ad81b4)), closes [#14958](https://github.com/vitejs/vite/issues/14958)
* chore: remove unneeded condition in getRealPath (#15267) ([8e4655c](https://github.com/vitejs/vite/commit/8e4655c)), closes [#15267](https://github.com/vitejs/vite/issues/15267)
* perf: cache empty optimizer result (#15245) ([8409b66](https://github.com/vitejs/vite/commit/8409b66)), closes [#15245](https://github.com/vitejs/vite/issues/15245)



## <small>5.0.6 (2023-12-06)</small>

* perf: in-memory public files check (#15195) ([0f9e1bf](https://github.com/vitejs/vite/commit/0f9e1bf)), closes [#15195](https://github.com/vitejs/vite/issues/15195)
* chore: remove unneccessary eslint-disable-next-line regexp/no-unused-capturing-group (#15247) ([35a5bcf](https://github.com/vitejs/vite/commit/35a5bcf)), closes [#15247](https://github.com/vitejs/vite/issues/15247)



## <small>5.0.5 (2023-12-04)</small>

* fix: emit `vite:preloadError` for chunks without deps (#15203) ([d8001c5](https://github.com/vitejs/vite/commit/d8001c5)), closes [#15203](https://github.com/vitejs/vite/issues/15203)
* fix: esbuild glob import resolve error (#15140) ([676804d](https://github.com/vitejs/vite/commit/676804d)), closes [#15140](https://github.com/vitejs/vite/issues/15140)
* fix: json error with position (#15225) ([14be75f](https://github.com/vitejs/vite/commit/14be75f)), closes [#15225](https://github.com/vitejs/vite/issues/15225)
* fix: proxy html path should be encoded (#15223) ([5b85040](https://github.com/vitejs/vite/commit/5b85040)), closes [#15223](https://github.com/vitejs/vite/issues/15223)
* fix(deps): update all non-major dependencies (#15233) ([ad3adda](https://github.com/vitejs/vite/commit/ad3adda)), closes [#15233](https://github.com/vitejs/vite/issues/15233)
* fix(hmr): don't consider CSS dep as a circular dep (#15229) ([5f2cdec](https://github.com/vitejs/vite/commit/5f2cdec)), closes [#15229](https://github.com/vitejs/vite/issues/15229)
* feat: add '*.mov' to client.d.ts (#15189) ([d93a211](https://github.com/vitejs/vite/commit/d93a211)), closes [#15189](https://github.com/vitejs/vite/issues/15189)
* feat(server): allow disabling built-in shortcuts (#15218) ([7fd7c6c](https://github.com/vitejs/vite/commit/7fd7c6c)), closes [#15218](https://github.com/vitejs/vite/issues/15218)
* chore: replace 'some' with 'includes' in resolveEnvPrefix (#15220) ([ee12f30](https://github.com/vitejs/vite/commit/ee12f30)), closes [#15220](https://github.com/vitejs/vite/issues/15220)
* chore: update the website url for homepage in package.json (#15181) ([282bd8f](https://github.com/vitejs/vite/commit/282bd8f)), closes [#15181](https://github.com/vitejs/vite/issues/15181)
* chore: update vitest to 1.0.0-beta.6 (#15194) ([2fce647](https://github.com/vitejs/vite/commit/2fce647)), closes [#15194](https://github.com/vitejs/vite/issues/15194)
* refactor: make HMR agnostic to environment (#15179) ([0571b7c](https://github.com/vitejs/vite/commit/0571b7c)), closes [#15179](https://github.com/vitejs/vite/issues/15179)
* refactor: use dedicated regex methods (#15228) ([0348137](https://github.com/vitejs/vite/commit/0348137)), closes [#15228](https://github.com/vitejs/vite/issues/15228)
* perf: remove debug only prettifyUrl call (#15204) ([73e971f](https://github.com/vitejs/vite/commit/73e971f)), closes [#15204](https://github.com/vitejs/vite/issues/15204)
* perf: skip computing sourceRoot in injectSourcesContent (#15207) ([1df1fd1](https://github.com/vitejs/vite/commit/1df1fd1)), closes [#15207](https://github.com/vitejs/vite/issues/15207)



## <small>5.0.4 (2023-11-29)</small>

* fix: bindCLIShortcuts to proper server (#15162) ([67ac572](https://github.com/vitejs/vite/commit/67ac572)), closes [#15162](https://github.com/vitejs/vite/issues/15162)
* fix: revert "fix: js fallback sourcemap content should be using original content (#15135)" (#15178) ([d2a2493](https://github.com/vitejs/vite/commit/d2a2493)), closes [#15135](https://github.com/vitejs/vite/issues/15135) [#15178](https://github.com/vitejs/vite/issues/15178)
* fix(define): allow define process.env (#15173) ([ec401da](https://github.com/vitejs/vite/commit/ec401da)), closes [#15173](https://github.com/vitejs/vite/issues/15173)
* fix(resolve): respect order of browser in mainFields when resolving (#15137) ([4a111aa](https://github.com/vitejs/vite/commit/4a111aa)), closes [#15137](https://github.com/vitejs/vite/issues/15137)
* feat: preserve vite.middlewares connect instance after restarts (#15166) ([9474c4b](https://github.com/vitejs/vite/commit/9474c4b)), closes [#15166](https://github.com/vitejs/vite/issues/15166)
* refactor: align with Promise.withResolvers() (#15171) ([642f9bc](https://github.com/vitejs/vite/commit/642f9bc)), closes [#15171](https://github.com/vitejs/vite/issues/15171)



## <small>5.0.3 (2023-11-28)</small>

* fix: `generateCodeFrame` infinite loop (#15093) ([6619de7](https://github.com/vitejs/vite/commit/6619de7)), closes [#15093](https://github.com/vitejs/vite/issues/15093)
* fix: js fallback sourcemap content should be using original content (#15135) ([227d56d](https://github.com/vitejs/vite/commit/227d56d)), closes [#15135](https://github.com/vitejs/vite/issues/15135)
* fix(css): render correct asset url when CSS chunk name is nested (#15154) ([ef403c0](https://github.com/vitejs/vite/commit/ef403c0)), closes [#15154](https://github.com/vitejs/vite/issues/15154)
* fix(css): use non-nested chunk name if facadeModule is not CSS file (#15155) ([811e392](https://github.com/vitejs/vite/commit/811e392)), closes [#15155](https://github.com/vitejs/vite/issues/15155)
* fix(dev): bind plugin context functions (#14569) ([cb3243c](https://github.com/vitejs/vite/commit/cb3243c)), closes [#14569](https://github.com/vitejs/vite/issues/14569)
* chore(deps): update all non-major dependencies (#15145) ([7ff2c0a](https://github.com/vitejs/vite/commit/7ff2c0a)), closes [#15145](https://github.com/vitejs/vite/issues/15145)
* build: handle latest json-stable-stringify replacement (#15049) ([bcc4a61](https://github.com/vitejs/vite/commit/bcc4a61)), closes [#15049](https://github.com/vitejs/vite/issues/15049)



## <small>5.0.2 (2023-11-21)</small>

* fix: make htmlFallback more permissive (#15059) ([6fcceeb](https://github.com/vitejs/vite/commit/6fcceeb)), closes [#15059](https://github.com/vitejs/vite/issues/15059)



## <small>5.0.1 (2023-11-21)</small>

* test: avoid read check when running as root (#14884) ([1d9516c](https://github.com/vitejs/vite/commit/1d9516c)), closes [#14884](https://github.com/vitejs/vite/issues/14884)
* perf(hmr): skip traversed modules when checking circular imports (#15034) ([41e437f](https://github.com/vitejs/vite/commit/41e437f)), closes [#15034](https://github.com/vitejs/vite/issues/15034)
* fix: run htmlFallbackMiddleware for no accept header requests (#15025) ([b93dfe3](https://github.com/vitejs/vite/commit/b93dfe3)), closes [#15025](https://github.com/vitejs/vite/issues/15025)
* fix: update type CSSModulesOptions interface (#14987) ([d0b2153](https://github.com/vitejs/vite/commit/d0b2153)), closes [#14987](https://github.com/vitejs/vite/issues/14987)
* fix(legacy): error in build with --watch and manifest enabled (#14450) ([b9ee620](https://github.com/vitejs/vite/commit/b9ee620)), closes [#14450](https://github.com/vitejs/vite/issues/14450)
* chore: add comment about crossorigin attribute for script module (#15040) ([03c371e](https://github.com/vitejs/vite/commit/03c371e)), closes [#15040](https://github.com/vitejs/vite/issues/15040)
* chore: cleanup v5 beta changelog (#14694) ([531d3cb](https://github.com/vitejs/vite/commit/531d3cb)), closes [#14694](https://github.com/vitejs/vite/issues/14694)



## 5.0.0 (2023-11-16)

Vite 5 is out! Read the [announcement blog post here](https://vitejs.dev/blog/announcing-vite5)

[![Announcing Vite 5](https://vitejs.dev/og-image-announcing-vite5.png)](https://vitejs.dev/blog/announcing-vite5)

Today, we mark another big milestone in Vite's path. The Vite [team](https://vitejs.dev/team), [contributors](https://github.com/vitejs/vite/graphs/contributors), and ecosystem partners, are excited to announce the release of Vite 5. Vite is now using [Rollup 4](https://github.com/vitejs/vite/pull/14508), which already represents a big boost in build performance. And there are also new options to improve your dev server performance profile.

Vite 5 focuses on cleaning up the API (removing deprecated features) and streamlines several features closing long-standing issues, for example switching `define` to use proper AST replacements instead of regexes. We also continue to take steps to future-proof Vite (Node.js 18+ is now required, and [the CJS Node API has been deprecated](https://vitejs.dev/guide/migration#deprecate-cjs-node-api)).

Quick links:

- [Docs](https://vitejs.dev)
- [Migration Guide](https://vitejs.dev/guide/migration)

Docs in other languages:

- [简体中文](https://cn.vitejs.dev/)
- [日本語](https://ja.vitejs.dev/)
- [Español](https://es.vitejs.dev/)
- [Português](https://pt.vitejs.dev/)
- [한국어](https://ko.vitejs.dev/)
- [Deutsch](https://de.vitejs.dev/) (new translation!)

Learn more at [the Vite 5 announcement blog post](https://vitejs.dev/blog/announcing-vite5).


### Breaking changes

* feat!: add isPreview to ConfigEnv and resolveConfig (#14855) ([d195860](https://github.com/vitejs/vite/commit/d195860)), closes [#14855](https://github.com/vitejs/vite/issues/14855)
* fix(types)!: expose httpServer with Http2SecureServer union (#14834) ([ab5bb40](https://github.com/vitejs/vite/commit/ab5bb40)), closes [#14834](https://github.com/vitejs/vite/issues/14834)
* refactor(preview)!: use base middleware (#14818) ([69737f4](https://github.com/vitejs/vite/commit/69737f4)), closes [#14818](https://github.com/vitejs/vite/issues/14818)
* fix(html)!: align html serving between dev and preview (#14756) ([4f71ae8](https://github.com/vitejs/vite/commit/4f71ae8)), closes [#14756](https://github.com/vitejs/vite/issues/14756)
* refactor!: remove non boolean middleware mode (#14792) ([deb5515](https://github.com/vitejs/vite/commit/deb5515)), closes [#14792](https://github.com/vitejs/vite/issues/14792)
* refactor(esbuild)!: remove esbuild 0.17 -> 0.18 compat (#14804) ([7234021](https://github.com/vitejs/vite/commit/7234021)), closes [#14804](https://github.com/vitejs/vite/issues/14804)
* feat(resolve)!: remove `resolve.browserField` (#14733) ([43cc3b9](https://github.com/vitejs/vite/commit/43cc3b9)), closes [#14733](https://github.com/vitejs/vite/issues/14733)
* refactor!: move side effect of restart server to the caller (#8746) ([521ca58](https://github.com/vitejs/vite/commit/521ca58)), closes [#8746](https://github.com/vitejs/vite/issues/8746)
* refactor(shortcuts)!: tweak shortcuts api (#14749) ([0ae2e1d](https://github.com/vitejs/vite/commit/0ae2e1d)), closes [#14749](https://github.com/vitejs/vite/issues/14749)
* fix(resolve)!: remove special .mjs handling (#14723) ([2141d31](https://github.com/vitejs/vite/commit/2141d31)), closes [#14723](https://github.com/vitejs/vite/issues/14723)
* feat!: remove ssr proxy for externalized modules (#14521) ([5786837](https://github.com/vitejs/vite/commit/5786837)), closes [#14521](https://github.com/vitejs/vite/issues/14521)
* feat(build)!: inline SVGs (#14643) ([5acda5e](https://github.com/vitejs/vite/commit/5acda5e)), closes [#14643](https://github.com/vitejs/vite/issues/14643)
* fix!: worker.plugins is a function (#14685) ([9d09dfe](https://github.com/vitejs/vite/commit/9d09dfe)), closes [#14685](https://github.com/vitejs/vite/issues/14685)
* refactor!: remove https flag (#14681) ([5b65bfd](https://github.com/vitejs/vite/commit/5b65bfd)), closes [#14681](https://github.com/vitejs/vite/issues/14681)
* feat!: rollup v4 (#14508) ([dee6067](https://github.com/vitejs/vite/commit/dee6067)), closes [#14508](https://github.com/vitejs/vite/issues/14508)
* refactor!: remove `resolvePackageEntry` and `resolvePackageData` APIs (#14584) ([339f300](https://github.com/vitejs/vite/commit/339f300)), closes [#14584](https://github.com/vitejs/vite/issues/14584)
* refactor!: remove exporting internal APIs (#14583) ([7861a33](https://github.com/vitejs/vite/commit/7861a33)), closes [#14583](https://github.com/vitejs/vite/issues/14583)
* fix!: return 404 for resources requests outside the base path (#5657) ([40fd2d9](https://github.com/vitejs/vite/commit/40fd2d9)), closes [#5657](https://github.com/vitejs/vite/issues/5657)
* refactor!: remove `server.force` (#14530) ([33ecfd9](https://github.com/vitejs/vite/commit/33ecfd9)), closes [#14530](https://github.com/vitejs/vite/issues/14530)
* refactor!: remove jest condition (#14544) ([8d18a91](https://github.com/vitejs/vite/commit/8d18a91)), closes [#14544](https://github.com/vitejs/vite/issues/14544)
* feat!: deprecate cjs node api (#14278) ([404f30f](https://github.com/vitejs/vite/commit/404f30f)), closes [#14278](https://github.com/vitejs/vite/issues/14278)
* feat(shortcuts)!: remove setRawMode (#14342) ([536631a](https://github.com/vitejs/vite/commit/536631a)), closes [#14342](https://github.com/vitejs/vite/issues/14342)
* fix!: put manifest files in .vite directory by default (#14230) ([74fa024](https://github.com/vitejs/vite/commit/74fa024)), closes [#14230](https://github.com/vitejs/vite/issues/14230)
* feat!: allow path containing . to fallback to index.html (#14142) ([1ae4cbd](https://github.com/vitejs/vite/commit/1ae4cbd)), closes [#14142](https://github.com/vitejs/vite/issues/14142)
* feat!: bump minimum node version to 18 (#14030) ([2c1a45c](https://github.com/vitejs/vite/commit/2c1a45c)), closes [#14030](https://github.com/vitejs/vite/issues/14030)
* fix!: avoid rewriting this (reverts #5312) (#14098) ([9b7b4ed](https://github.com/vitejs/vite/commit/9b7b4ed)), closes [#5312](https://github.com/vitejs/vite/issues/5312) [#14098](https://github.com/vitejs/vite/issues/14098)
* refactor!: merge `PreviewServerForHook` into `PreviewServer` type (#14119) ([e0eb07c](https://github.com/vitejs/vite/commit/e0eb07c)), closes [#14119](https://github.com/vitejs/vite/issues/14119)
* refactor(glob)!: remove `import.meta.globEager` (#14118) ([fdfb61f](https://github.com/vitejs/vite/commit/fdfb61f)), closes [#14118](https://github.com/vitejs/vite/issues/14118)
* feat!: add extension to internal virtual modules (#14231) ([9594c70](https://github.com/vitejs/vite/commit/9594c70)), closes [#14231](https://github.com/vitejs/vite/issues/14231)
* feat(css)!: remove css default export ([b6c44cd](https://github.com/vitejs/vite/commit/b6c44cd))
* fix!: update node types peer dep range (#14280) ([8f87e86](https://github.com/vitejs/vite/commit/8f87e86)), closes [#14280](https://github.com/vitejs/vite/issues/14280)

### Features

* feat: allow providing parent httpServer on middleware mode (#14632) ([e0c86d4](https://github.com/vitejs/vite/commit/e0c86d4)), closes [#14632](https://github.com/vitejs/vite/issues/14632)
* style(client): overlay frame show scrollbar (#14701) ([8aa4134](https://github.com/vitejs/vite/commit/8aa4134)), closes [#14701](https://github.com/vitejs/vite/issues/14701)
* feat: error when failed to resolve aliased import (#14973) ([6a564fa](https://github.com/vitejs/vite/commit/6a564fa)), closes [#14973](https://github.com/vitejs/vite/issues/14973)
* feat: add invalid `rollupOptions` warnings (#14909) ([7c240a0](https://github.com/vitejs/vite/commit/7c240a0)), closes [#14909](https://github.com/vitejs/vite/issues/14909)
* feat: skip initial clear screen if has logs (#14936) ([a92bc61](https://github.com/vitejs/vite/commit/a92bc61)), closes [#14936](https://github.com/vitejs/vite/issues/14936)
* feat(hmr): add full reload reason (#14914) ([60a020e](https://github.com/vitejs/vite/commit/60a020e)), closes [#14914](https://github.com/vitejs/vite/issues/14914)
* feat(hmr): improve circular import updates (#14867) ([b479055](https://github.com/vitejs/vite/commit/b479055)), closes [#14867](https://github.com/vitejs/vite/issues/14867)
* feat: implement AsyncDisposable (#14648) ([385d580](https://github.com/vitejs/vite/commit/385d580)), closes [#14648](https://github.com/vitejs/vite/issues/14648)
* feat: expose parseAst and parseAstAsync from rollup (#14833) ([6229485](https://github.com/vitejs/vite/commit/6229485)), closes [#14833](https://github.com/vitejs/vite/issues/14833)
* feat: upgrade rollup to 4.2.0 and use parseAstAsync (#14821) ([86a5356](https://github.com/vitejs/vite/commit/86a5356)), closes [#14821](https://github.com/vitejs/vite/issues/14821)
* feat(pluginContainer): implement watchChange hook (#14822) ([9369d8d](https://github.com/vitejs/vite/commit/9369d8d)), closes [#14822](https://github.com/vitejs/vite/issues/14822)
* feat(server): add warmupRequest api (#14787) ([8690581](https://github.com/vitejs/vite/commit/8690581)), closes [#14787](https://github.com/vitejs/vite/issues/14787)
* feat(define): handle replacement with esbuild (#11151) ([e4c801c](https://github.com/vitejs/vite/commit/e4c801c)), closes [#11151](https://github.com/vitejs/vite/issues/11151)
* feat: add a runtime warning for the old object type transformIndexHtml hook (#14791) ([17fb5ee](https://github.com/vitejs/vite/commit/17fb5ee)), closes [#14791](https://github.com/vitejs/vite/issues/14791)
* feat: add server.warmup option (#14291) ([da80372](https://github.com/vitejs/vite/commit/da80372)), closes [#14291](https://github.com/vitejs/vite/issues/14291)
* feat: add import-meta.d.ts (#14615) ([598d423](https://github.com/vitejs/vite/commit/598d423)), closes [#14615](https://github.com/vitejs/vite/issues/14615)
* feat: add mdx as known js source (#14560) ([dd213b5](https://github.com/vitejs/vite/commit/dd213b5)), closes [#14560](https://github.com/vitejs/vite/issues/14560)
* feat: add off method to ViteHotContext (issue #14185) (#14518) ([31333bb](https://github.com/vitejs/vite/commit/31333bb)), closes [#14185](https://github.com/vitejs/vite/issues/14185) [#14518](https://github.com/vitejs/vite/issues/14518)
* feat: show better parse error in build (#14600) ([84df7db](https://github.com/vitejs/vite/commit/84df7db)), closes [#14600](https://github.com/vitejs/vite/issues/14600)
* feat(optimizer): check optimizeDeps.extensions for scannable files (#14543) ([23ef8a1](https://github.com/vitejs/vite/commit/23ef8a1)), closes [#14543](https://github.com/vitejs/vite/issues/14543)
* feat(ssr): support for ssr.resolve.conditions and ssr.resolve.externalConditions options (#14498) ([d0afc39](https://github.com/vitejs/vite/commit/d0afc39)), closes [#14498](https://github.com/vitejs/vite/issues/14498)
* feat: show warning to discourage putting process/global to `define` option (#14447) ([83a56f7](https://github.com/vitejs/vite/commit/83a56f7)), closes [#14447](https://github.com/vitejs/vite/issues/14447)
* feat(terser): add `maxWorkers` option for terserOptions (#13858) ([884fc3d](https://github.com/vitejs/vite/commit/884fc3d)), closes [#13858](https://github.com/vitejs/vite/issues/13858)
* feat: add generic type for plugin api (#14238) ([830b26e](https://github.com/vitejs/vite/commit/830b26e)), closes [#14238](https://github.com/vitejs/vite/issues/14238)
* feat: allow passing down "null" to disable server watcher (#14208) ([af5a95e](https://github.com/vitejs/vite/commit/af5a95e)), closes [#14208](https://github.com/vitejs/vite/issues/14208)
* feat: improve deno and bun support (#14379) ([9884308](https://github.com/vitejs/vite/commit/9884308)), closes [#14379](https://github.com/vitejs/vite/issues/14379)
* feat: build.ssrEmitAssets out of experimental (#14055) ([f88ab68](https://github.com/vitejs/vite/commit/f88ab68)), closes [#14055](https://github.com/vitejs/vite/issues/14055)
* feat: ssrTransform support import assertion by default (#14202) ([70a379f](https://github.com/vitejs/vite/commit/70a379f)), closes [#14202](https://github.com/vitejs/vite/issues/14202)
* feat: use `import.meta.url` instead of `self.location` (#14377) ([e9b1e85](https://github.com/vitejs/vite/commit/e9b1e85)), closes [#14377](https://github.com/vitejs/vite/issues/14377)
* feat: warn if # in project root (#14188) ([f5ba696](https://github.com/vitejs/vite/commit/f5ba696)), closes [#14188](https://github.com/vitejs/vite/issues/14188)
* feat(css): stop injecting `?used` ([fc05454](https://github.com/vitejs/vite/commit/fc05454))
* feat: export `server.bindCLIShortcuts` (#13675) ([1a2e5e6](https://github.com/vitejs/vite/commit/1a2e5e6)), closes [#13675](https://github.com/vitejs/vite/issues/13675)
* feat: copyPublicDir out of experimental (#14051) ([443c235](https://github.com/vitejs/vite/commit/443c235)), closes [#14051](https://github.com/vitejs/vite/issues/14051)
* feat(css): build assets with the entry name when it is an entry point (#11578) ([fd9a2cc](https://github.com/vitejs/vite/commit/fd9a2cc)), closes [#11578](https://github.com/vitejs/vite/issues/11578)
* feat(deps): upgrade rollup to 3.28.0 (#14049) ([490dad8](https://github.com/vitejs/vite/commit/490dad8)), closes [#14049](https://github.com/vitejs/vite/issues/14049)
* feat(worker): support a way to name the worker (#14032) ([1f214a4](https://github.com/vitejs/vite/commit/1f214a4)), closes [#14032](https://github.com/vitejs/vite/issues/14032)

### Performance

* perf(define): create simple regex for checks (#14788) ([bd15537](https://github.com/vitejs/vite/commit/bd15537)), closes [#14788](https://github.com/vitejs/vite/issues/14788)
* perf(hmr): implement soft invalidation (#14654) ([4150bcb](https://github.com/vitejs/vite/commit/4150bcb)), closes [#14654](https://github.com/vitejs/vite/issues/14654)
* perf: pre transform requests while opening the browser (#12809) ([96a4ce3](https://github.com/vitejs/vite/commit/96a4ce3)), closes [#12809](https://github.com/vitejs/vite/issues/12809)
* chore(deps): update tsconfck to 3.0.0 (#14629) ([4dcf9c4](https://github.com/vitejs/vite/commit/4dcf9c4)), closes [#14629](https://github.com/vitejs/vite/issues/14629)
* perf: reduce preload marker markup size (#14550) ([6f12fd8](https://github.com/vitejs/vite/commit/6f12fd8)), closes [#14550](https://github.com/vitejs/vite/issues/14550)
* perf: move up external url check before fs path checks (#13639) ([c2ebea1](https://github.com/vitejs/vite/commit/c2ebea1)), closes [#13639](https://github.com/vitejs/vite/issues/13639)
* refactor: update to tsconfck3 with lazy cache (#14234) ([6e0b0ee](https://github.com/vitejs/vite/commit/6e0b0ee)), closes [#14234](https://github.com/vitejs/vite/issues/14234)
* perf: reduce one if judgment (#14329) ([09ba7c6](https://github.com/vitejs/vite/commit/09ba7c6)), closes [#14329](https://github.com/vitejs/vite/issues/14329)
* perf: replace startsWith with === (#14300) ([75cd29c](https://github.com/vitejs/vite/commit/75cd29c)), closes [#14300](https://github.com/vitejs/vite/issues/14300)
* perf: replace fromEntries with a for loop (#14041) ([8b174fd](https://github.com/vitejs/vite/commit/8b174fd)), closes [#14041](https://github.com/vitejs/vite/issues/14041)
* perf: use `URL.canParse` (#14068) ([dcee6ef](https://github.com/vitejs/vite/commit/dcee6ef)), closes [#14068](https://github.com/vitejs/vite/issues/14068)

### Fixes

* fix: caret position was incorrect (#14984) ([2b4e793](https://github.com/vitejs/vite/commit/2b4e793)), closes [#14984](https://github.com/vitejs/vite/issues/14984)
* fix: code frame was not generated for postcss errors (#14986) ([bedfcfa](https://github.com/vitejs/vite/commit/bedfcfa)), closes [#14986](https://github.com/vitejs/vite/issues/14986)
* fix: don't append `/@fs/` for bare imports (#14995) ([2a519a1](https://github.com/vitejs/vite/commit/2a519a1)), closes [#14995](https://github.com/vitejs/vite/issues/14995)
* fix: server.preTransformRequests https error (#14991) (#14993) ([58ff849](https://github.com/vitejs/vite/commit/58ff849)), closes [#14991](https://github.com/vitejs/vite/issues/14991) [#14993](https://github.com/vitejs/vite/issues/14993)
* fix(ssr): skip esm proxy guard for namespace imports (#14988) ([82a5b11](https://github.com/vitejs/vite/commit/82a5b11)), closes [#14988](https://github.com/vitejs/vite/issues/14988)
* fix: don't watch SPA fallback paths (#14953) ([24c2c57](https://github.com/vitejs/vite/commit/24c2c57)), closes [#14953](https://github.com/vitejs/vite/issues/14953)
* fix: handle addWatchFile in load hooks (#14967) ([a0ab85b](https://github.com/vitejs/vite/commit/a0ab85b)), closes [#14967](https://github.com/vitejs/vite/issues/14967)
* fix: preload marker duplicate deps (#14955) ([55335cc](https://github.com/vitejs/vite/commit/55335cc)), closes [#14955](https://github.com/vitejs/vite/issues/14955)
* fix: relax overlay frame regex (#14979) ([0b325bb](https://github.com/vitejs/vite/commit/0b325bb)), closes [#14979](https://github.com/vitejs/vite/issues/14979)
* fix(deps): update all non-major dependencies (#14961) ([0bb3995](https://github.com/vitejs/vite/commit/0bb3995)), closes [#14961](https://github.com/vitejs/vite/issues/14961)
* fix(esbuild): set js loader for build transpile (#14980) ([80beede](https://github.com/vitejs/vite/commit/80beede)), closes [#14980](https://github.com/vitejs/vite/issues/14980)
* fix(pluginContainer): run transform in this.load (#14965) ([3f57b05](https://github.com/vitejs/vite/commit/3f57b05)), closes [#14965](https://github.com/vitejs/vite/issues/14965)
* fix: `server.headers` after restart in middleware mode (#14905) ([f9ce9db](https://github.com/vitejs/vite/commit/f9ce9db)), closes [#14905](https://github.com/vitejs/vite/issues/14905)
* fix: add watch in fallback file load (#14938) ([b24b951](https://github.com/vitejs/vite/commit/b24b951)), closes [#14938](https://github.com/vitejs/vite/issues/14938)
* fix: injectQuery check with double slash in the url (#14910) ([84c5ff6](https://github.com/vitejs/vite/commit/84c5ff6)), closes [#14910](https://github.com/vitejs/vite/issues/14910)
* fix(build): make build error message clearer (#14761) ([350b4b2](https://github.com/vitejs/vite/commit/350b4b2)), closes [#14761](https://github.com/vitejs/vite/issues/14761)
* fix(css): correctly set manifest source name and emit CSS file (#14945) ([28ccede](https://github.com/vitejs/vite/commit/28ccede)), closes [#14945](https://github.com/vitejs/vite/issues/14945)
* fix(server): the server restart port should remain unchanged (#14418) ([8b96e97](https://github.com/vitejs/vite/commit/8b96e97)), closes [#14418](https://github.com/vitejs/vite/issues/14418)
* fix(worker): prevent inject esm in classic workers (#14918) ([2687dbb](https://github.com/vitejs/vite/commit/2687dbb)), closes [#14918](https://github.com/vitejs/vite/issues/14918)
* fix: file link in overlay with custom backend (#14879) ([1bfb584](https://github.com/vitejs/vite/commit/1bfb584)), closes [#14879](https://github.com/vitejs/vite/issues/14879)
* fix: processNodeUrl for srcset (#14870) ([0873bae](https://github.com/vitejs/vite/commit/0873bae)), closes [#14870](https://github.com/vitejs/vite/issues/14870)
* fix: resovedUrls is null after server restart (#14890) ([bd4d29f](https://github.com/vitejs/vite/commit/bd4d29f)), closes [#14890](https://github.com/vitejs/vite/issues/14890)
* fix: use latest module graph in transform middleware (#14892) ([b6b382c](https://github.com/vitejs/vite/commit/b6b382c)), closes [#14892](https://github.com/vitejs/vite/issues/14892)
* fix(assets): use base64 when inlining SVG with foreignObject tag (#14875) ([9e20ed6](https://github.com/vitejs/vite/commit/9e20ed6)), closes [#14875](https://github.com/vitejs/vite/issues/14875)
* fix(build): mixed external and transpiled srcset  (#14888) ([b5653d3](https://github.com/vitejs/vite/commit/b5653d3)), closes [#14888](https://github.com/vitejs/vite/issues/14888)
* fix(css): fix sourcemap warning in build with lightningCSS (#14871) ([11b1796](https://github.com/vitejs/vite/commit/11b1796)), closes [#14871](https://github.com/vitejs/vite/issues/14871)
* fix(css): initialize lightningCSS targets when not using options (#14872) ([12f9230](https://github.com/vitejs/vite/commit/12f9230)), closes [#14872](https://github.com/vitejs/vite/issues/14872)
* fix: use correct publicDir in ERR_LOAD_PUBLIC_URL (#14847) ([66caef3](https://github.com/vitejs/vite/commit/66caef3)), closes [#14847](https://github.com/vitejs/vite/issues/14847)
* fix(define): correctly replace same define values (#14786) ([f36fcd2](https://github.com/vitejs/vite/commit/f36fcd2)), closes [#14786](https://github.com/vitejs/vite/issues/14786)
* fix(deps): update all non-major dependencies (#14729) ([d5d96e7](https://github.com/vitejs/vite/commit/d5d96e7)), closes [#14729](https://github.com/vitejs/vite/issues/14729)
* fix(worker): force rollup to build workerImportMetaUrl under watch mode (#14712) ([8db40ee](https://github.com/vitejs/vite/commit/8db40ee)), closes [#14712](https://github.com/vitejs/vite/issues/14712)
* fix: skip watchPackageDataPlugin for worker builds (#14762) ([9babef5](https://github.com/vitejs/vite/commit/9babef5)), closes [#14762](https://github.com/vitejs/vite/issues/14762)
* fix: suppress addWatchFile invalid phase error (#14751) ([c3622d7](https://github.com/vitejs/vite/commit/c3622d7)), closes [#14751](https://github.com/vitejs/vite/issues/14751)
* fix(css): ensure code is valid after empty css chunk imports are removed (fix #14515) (#14517) ([72f6a52](https://github.com/vitejs/vite/commit/72f6a52)), closes [#14515](https://github.com/vitejs/vite/issues/14515) [#14517](https://github.com/vitejs/vite/issues/14517)
* fix(html): ignore rewrite external urls (#14774) ([d6d1ef1](https://github.com/vitejs/vite/commit/d6d1ef1)), closes [#14774](https://github.com/vitejs/vite/issues/14774)
* fix(assets): fix svg inline in css url (#14714) ([eef4aaa](https://github.com/vitejs/vite/commit/eef4aaa)), closes [#14714](https://github.com/vitejs/vite/issues/14714)
* fix(resolve): make directory package.json check best effort (#14626) ([d520388](https://github.com/vitejs/vite/commit/d520388)), closes [#14626](https://github.com/vitejs/vite/issues/14626)
* fix(assets): make timestamp invalidation lazy (#14675) ([dd610b5](https://github.com/vitejs/vite/commit/dd610b5)), closes [#14675](https://github.com/vitejs/vite/issues/14675)
* fix(build): add crossorigin attribute to `link[rel="stylesheet"]` (#12991) ([6e7b25c](https://github.com/vitejs/vite/commit/6e7b25c)), closes [#12991](https://github.com/vitejs/vite/issues/12991)
* fix(hmr): clean importers in module graph when file is deleted (#14315) ([7acb016](https://github.com/vitejs/vite/commit/7acb016)), closes [#14315](https://github.com/vitejs/vite/issues/14315)
* fix(manifest): include assets referenced in html (#14657) ([f627b91](https://github.com/vitejs/vite/commit/f627b91)), closes [#14657](https://github.com/vitejs/vite/issues/14657)
* fix: avoid --open optimization if preTransformRequests is disabled (#14666) ([d4f62e4](https://github.com/vitejs/vite/commit/d4f62e4)), closes [#14666](https://github.com/vitejs/vite/issues/14666)
* fix(dynamic-import-vars): preserve custom query string (#14459) ([1f2a982](https://github.com/vitejs/vite/commit/1f2a982)), closes [#14459](https://github.com/vitejs/vite/issues/14459)
* fix(hmr): add timestamp for assets in dev (#13371) ([40ee245](https://github.com/vitejs/vite/commit/40ee245)), closes [#13371](https://github.com/vitejs/vite/issues/13371)
* fix(html): srcset pointing image in public dir wasn't working during dev (#14663) ([4496ae7](https://github.com/vitejs/vite/commit/4496ae7)), closes [#14663](https://github.com/vitejs/vite/issues/14663)
* fix(deps): update all non-major dependencies (#14635) ([21017a9](https://github.com/vitejs/vite/commit/21017a9)), closes [#14635](https://github.com/vitejs/vite/issues/14635)
* fix(esbuild): handle tsconfck cache undefined (#14650) ([4e763c5](https://github.com/vitejs/vite/commit/4e763c5)), closes [#14650](https://github.com/vitejs/vite/issues/14650)
* fix: off-by-one bug in HTML whitespace removal (#14589) ([f54e6d8](https://github.com/vitejs/vite/commit/f54e6d8)), closes [#14589](https://github.com/vitejs/vite/issues/14589)
* fix(html): import expression in classic script for dev (#14595) ([ea47b8f](https://github.com/vitejs/vite/commit/ea47b8f)), closes [#14595](https://github.com/vitejs/vite/issues/14595)
* fix(html): inline style attribute not working in dev (#14592) ([a4a17b8](https://github.com/vitejs/vite/commit/a4a17b8)), closes [#14592](https://github.com/vitejs/vite/issues/14592)
* fix(html): relative paths without leading dot wasn't rewritten (#14591) ([0a38e3b](https://github.com/vitejs/vite/commit/0a38e3b)), closes [#14591](https://github.com/vitejs/vite/issues/14591)
* fix(proxy): correct the logic of bypass returning false (#14579) ([261633a](https://github.com/vitejs/vite/commit/261633a)), closes [#14579](https://github.com/vitejs/vite/issues/14579)
* fix(optimizer): limit bundled file name length to 170 characters (#14561) ([a3b6d8d](https://github.com/vitejs/vite/commit/a3b6d8d)), closes [#14561](https://github.com/vitejs/vite/issues/14561)
* fix: esbuild glob resolve error (#14533) ([3615c68](https://github.com/vitejs/vite/commit/3615c68)), closes [#14533](https://github.com/vitejs/vite/issues/14533)
* fix: update transform error message (#14139) ([e0eb304](https://github.com/vitejs/vite/commit/e0eb304)), closes [#14139](https://github.com/vitejs/vite/issues/14139)
* fix(deps): update all non-major dependencies (#14510) ([eb204fd](https://github.com/vitejs/vite/commit/eb204fd)), closes [#14510](https://github.com/vitejs/vite/issues/14510)
* fix(deps): update all non-major dependencies (#14559) ([6868480](https://github.com/vitejs/vite/commit/6868480)), closes [#14559](https://github.com/vitejs/vite/issues/14559)
* fix(lib): esbuild helper functions injection not working with named exports (#14539) ([5004d00](https://github.com/vitejs/vite/commit/5004d00)), closes [#14539](https://github.com/vitejs/vite/issues/14539)
* fix: allow path ending with .html to fallback to index.html ([dae6d0a](https://github.com/vitejs/vite/commit/dae6d0a))
* fix: handle fs.realpath.native MAX_PATH issue for Node.js <18.10 (#14487) ([17c5928](https://github.com/vitejs/vite/commit/17c5928)), closes [#14487](https://github.com/vitejs/vite/issues/14487)
* fix: update .html fallback in MPA ([b5637a7](https://github.com/vitejs/vite/commit/b5637a7))
* fix(analysis): warnings for dynamic imports that use static template literals (#14458) ([ec7ee22](https://github.com/vitejs/vite/commit/ec7ee22)), closes [#14458](https://github.com/vitejs/vite/issues/14458)
* fix(hmr): dev mode reduce unnecessary restart (#14426) ([6f9d39d](https://github.com/vitejs/vite/commit/6f9d39d)), closes [#14426](https://github.com/vitejs/vite/issues/14426)
* fix(import-analysis): preserve importedUrls import order (#14465) ([99b0645](https://github.com/vitejs/vite/commit/99b0645)), closes [#14465](https://github.com/vitejs/vite/issues/14465)
* fix(preview): allow path containing . to fallback to index.html ([fddc151](https://github.com/vitejs/vite/commit/fddc151))
* fix(resolve): support submodules of optional peer deps (#14489) ([f80ff77](https://github.com/vitejs/vite/commit/f80ff77)), closes [#14489](https://github.com/vitejs/vite/issues/14489)
* fix: handle errors during `hasWorkspacePackageJSON` function (#14394) ([c3e4791](https://github.com/vitejs/vite/commit/c3e4791)), closes [#14394](https://github.com/vitejs/vite/issues/14394)
* fix: unify css collecting order (#11671) ([20a8a15](https://github.com/vitejs/vite/commit/20a8a15)), closes [#11671](https://github.com/vitejs/vite/issues/11671)
* fix(deps): update all non-major dependencies (#14092) ([68638f7](https://github.com/vitejs/vite/commit/68638f7)), closes [#14092](https://github.com/vitejs/vite/issues/14092)
* fix(deps): update all non-major dependencies (#14460) ([b77bff0](https://github.com/vitejs/vite/commit/b77bff0)), closes [#14460](https://github.com/vitejs/vite/issues/14460)
* fix(deps): update dependency dotenv-expand to v10 (#14391) ([d6bde8b](https://github.com/vitejs/vite/commit/d6bde8b)), closes [#14391](https://github.com/vitejs/vite/issues/14391)
* fix: omit 'plugins' since it has no effect (#13879) ([64888b0](https://github.com/vitejs/vite/commit/64888b0)), closes [#13879](https://github.com/vitejs/vite/issues/13879)
* fix: typo (#14334) ([30df500](https://github.com/vitejs/vite/commit/30df500)), closes [#14334](https://github.com/vitejs/vite/issues/14334)
* fix: typo (#14337) ([6ffe070](https://github.com/vitejs/vite/commit/6ffe070)), closes [#14337](https://github.com/vitejs/vite/issues/14337)
* fix: use relative path for sources field (#14247) ([a995907](https://github.com/vitejs/vite/commit/a995907)), closes [#14247](https://github.com/vitejs/vite/issues/14247)
* fix(manifest): preserve pure css chunk assets (#14297) ([4bf31e5](https://github.com/vitejs/vite/commit/4bf31e5)), closes [#14297](https://github.com/vitejs/vite/issues/14297)
* fix(resolve): support `pkg?query` ([21bbceb](https://github.com/vitejs/vite/commit/21bbceb))
* fix(sourcemap): dont inject fallback sourcemap if have existing (#14370) ([55a3b4f](https://github.com/vitejs/vite/commit/55a3b4f)), closes [#14370](https://github.com/vitejs/vite/issues/14370)
* fix(worker): inline es worker does not work in build mode (#14307) ([7371c5c](https://github.com/vitejs/vite/commit/7371c5c)), closes [#14307](https://github.com/vitejs/vite/issues/14307)
* fix: add source map to Web Workers (fix #14216) (#14217) ([6f86de3](https://github.com/vitejs/vite/commit/6f86de3)), closes [#14216](https://github.com/vitejs/vite/issues/14216) [#14217](https://github.com/vitejs/vite/issues/14217)
* fix: handle sourcemap correctly when multiple line import exists (#14232) ([627159d](https://github.com/vitejs/vite/commit/627159d)), closes [#14232](https://github.com/vitejs/vite/issues/14232)
* fix: include `vite/types/*` in exports field (#14296) ([66a97be](https://github.com/vitejs/vite/commit/66a97be)), closes [#14296](https://github.com/vitejs/vite/issues/14296)
* fix: use string manipulation instead of regex to inject esbuild helpers (#14094) ([91a18c2](https://github.com/vitejs/vite/commit/91a18c2)), closes [#14094](https://github.com/vitejs/vite/issues/14094)
* fix(cli): convert special base (#14283) ([34826aa](https://github.com/vitejs/vite/commit/34826aa)), closes [#14283](https://github.com/vitejs/vite/issues/14283)
* fix(css): remove pure css chunk sourcemap (#14290) ([2b80089](https://github.com/vitejs/vite/commit/2b80089)), closes [#14290](https://github.com/vitejs/vite/issues/14290)
* fix(css): reset render cache on renderStart (#14326) ([19bf0f1](https://github.com/vitejs/vite/commit/19bf0f1)), closes [#14326](https://github.com/vitejs/vite/issues/14326)
* fix(css): spread lightningcss options (#14313) ([80c6608](https://github.com/vitejs/vite/commit/80c6608)), closes [#14313](https://github.com/vitejs/vite/issues/14313)
* fix(optimizer): define crawlDeps after scanProcessing and optimizationResult are complete (fix #1428 ([c5f6558](https://github.com/vitejs/vite/commit/c5f6558)), closes [#14284](https://github.com/vitejs/vite/issues/14284) [#14285](https://github.com/vitejs/vite/issues/14285)
* fix(vite): precisely check if files are in dirs (#14241) ([245d186](https://github.com/vitejs/vite/commit/245d186)), closes [#14241](https://github.com/vitejs/vite/issues/14241)
* revert: "fix(css): spread lightningcss options (#14024)" (#14209) ([5778365](https://github.com/vitejs/vite/commit/5778365)), closes [#14024](https://github.com/vitejs/vite/issues/14024) [#14209](https://github.com/vitejs/vite/issues/14209)
* fix: breakpoints in JS not working (#13514) ([0156bd2](https://github.com/vitejs/vite/commit/0156bd2)), closes [#13514](https://github.com/vitejs/vite/issues/13514)
* fix: if host is specified check whether it is valid (#14013) ([c39e6c1](https://github.com/vitejs/vite/commit/c39e6c1)), closes [#14013](https://github.com/vitejs/vite/issues/14013)
* fix: initWasm options should be optional (#14152) ([387a6e8](https://github.com/vitejs/vite/commit/387a6e8)), closes [#14152](https://github.com/vitejs/vite/issues/14152)
* fix: rollup watch crash on Windows (#13339) ([4f582c9](https://github.com/vitejs/vite/commit/4f582c9)), closes [#13339](https://github.com/vitejs/vite/issues/13339)
* fix: ws never connects after restarting server if server.hmr.server is set (#14127) ([bd9b749](https://github.com/vitejs/vite/commit/bd9b749)), closes [#14127](https://github.com/vitejs/vite/issues/14127)
* fix(client): correctly display the config file name (#14160) ([61e801d](https://github.com/vitejs/vite/commit/61e801d)), closes [#14160](https://github.com/vitejs/vite/issues/14160)
* fix(css): spread lightningcss options (#14024) ([63a4451](https://github.com/vitejs/vite/commit/63a4451)), closes [#14024](https://github.com/vitejs/vite/issues/14024)
* fix(css): trim esbuild's minified css (#13893) ([7682a62](https://github.com/vitejs/vite/commit/7682a62)), closes [#13893](https://github.com/vitejs/vite/issues/13893)
* fix(glob): trigger HMR for glob in a  package (#14117) ([86cbf69](https://github.com/vitejs/vite/commit/86cbf69)), closes [#14117](https://github.com/vitejs/vite/issues/14117)

### Cleanup

* docs: point links in messages at https: (#14992) ([d3af879](https://github.com/vitejs/vite/commit/d3af879)), closes [#14992](https://github.com/vitejs/vite/issues/14992)
* build: dont strip single line comments (#14969) ([ea9ccb7](https://github.com/vitejs/vite/commit/ea9ccb7)), closes [#14969](https://github.com/vitejs/vite/issues/14969)
* build: strip internal parameters ([1168e57](https://github.com/vitejs/vite/commit/1168e57))
* chore: refactor as functions ([5684382](https://github.com/vitejs/vite/commit/5684382))
* chore: add `PluginWithRequiredHook` type & extract `getHookHandler` function  (#14845) ([997f2d5](https://github.com/vitejs/vite/commit/997f2d5)), closes [#14845](https://github.com/vitejs/vite/issues/14845)
* chore(optimizedDeps): remove unused return (#14773) ([9d744dd](https://github.com/vitejs/vite/commit/9d744dd)), closes [#14773](https://github.com/vitejs/vite/issues/14773)
* refactor: simplify build optimizer node_env handling (#14829) ([275907b](https://github.com/vitejs/vite/commit/275907b)), closes [#14829](https://github.com/vitejs/vite/issues/14829)
* chore: fix typo (#14820) ([eda1247](https://github.com/vitejs/vite/commit/eda1247)), closes [#14820](https://github.com/vitejs/vite/issues/14820)
* chore: revert "feat: show warning to discourage putting process/global to `define` option (#14447)"  ([0426910](https://github.com/vitejs/vite/commit/0426910)), closes [#14447](https://github.com/vitejs/vite/issues/14447) [#14827](https://github.com/vitejs/vite/issues/14827)
* chore: update license (#14790) ([ac5d8a7](https://github.com/vitejs/vite/commit/ac5d8a7)), closes [#14790](https://github.com/vitejs/vite/issues/14790)
* chore(shortcuts): resolve generic type error (#14802) ([a090742](https://github.com/vitejs/vite/commit/a090742)), closes [#14802](https://github.com/vitejs/vite/issues/14802)
* refactor: update es-module-lexer to 1.4.0 (#14937) ([374e6fd](https://github.com/vitejs/vite/commit/374e6fd)), closes [#14937](https://github.com/vitejs/vite/issues/14937)
* chore(esbuild): fix typo (#14772) ([6cfc1e2](https://github.com/vitejs/vite/commit/6cfc1e2)), closes [#14772](https://github.com/vitejs/vite/issues/14772)
* revert: remove AsyncDisposable (#14908) ([b953b0d](https://github.com/vitejs/vite/commit/b953b0d)), closes [#14908](https://github.com/vitejs/vite/issues/14908)
* refactor(ssr): remove unused metadata code (#14711) ([c5f2d60](https://github.com/vitejs/vite/commit/c5f2d60)), closes [#14711](https://github.com/vitejs/vite/issues/14711)
* refactor: use dynamic import directly (#14661) ([af60592](https://github.com/vitejs/vite/commit/af60592)), closes [#14661](https://github.com/vitejs/vite/issues/14661)
* chore(config): improve the readability of warning messages (#14594) ([b43b4df](https://github.com/vitejs/vite/commit/b43b4df)), closes [#14594](https://github.com/vitejs/vite/issues/14594)
* build: clean generated type file (#14582) ([fffe16e](https://github.com/vitejs/vite/commit/fffe16e)), closes [#14582](https://github.com/vitejs/vite/issues/14582)
* build: use rollup-plugin-dts (#14571) ([d89725b](https://github.com/vitejs/vite/commit/d89725b)), closes [#14571](https://github.com/vitejs/vite/issues/14571)
* refactor(css): make `getEmptyChunkReplacer` for unit test (#14528) ([18900fd](https://github.com/vitejs/vite/commit/18900fd)), closes [#14528](https://github.com/vitejs/vite/issues/14528)
* refactor: ensure HTML is stripped of generated blank lines (#14274) ([bc97091](https://github.com/vitejs/vite/commit/bc97091)), closes [#14274](https://github.com/vitejs/vite/issues/14274)
* refactor: remove unused record flatIdToExports (#14557) ([7e62710](https://github.com/vitejs/vite/commit/7e62710)), closes [#14557](https://github.com/vitejs/vite/issues/14557)
* test(ssr): add import and export ordering snapshot (#14468) ([ca34c64](https://github.com/vitejs/vite/commit/ca34c64)), closes [#14468](https://github.com/vitejs/vite/issues/14468)
* refactor: remove CJS ssr output format (#13944) ([2f60b9e](https://github.com/vitejs/vite/commit/2f60b9e)), closes [#13944](https://github.com/vitejs/vite/issues/13944)
* refactor: replace duplicate code with tryStatSync (#14461) ([be6b0c8](https://github.com/vitejs/vite/commit/be6b0c8)), closes [#14461](https://github.com/vitejs/vite/issues/14461)
* refactor(config): remove unnecessary esbuild option (#13580) ([67f4e52](https://github.com/vitejs/vite/commit/67f4e52)), closes [#13580](https://github.com/vitejs/vite/issues/13580)
* test(ssr): proper test coverage of SSR shebang import hoisting (#14448) ([fdd4669](https://github.com/vitejs/vite/commit/fdd4669)), closes [#14448](https://github.com/vitejs/vite/issues/14448)
* chore(optimizer): debug info on cache dir handle process (#12858) ([21a62da](https://github.com/vitejs/vite/commit/21a62da)), closes [#12858](https://github.com/vitejs/vite/issues/12858)
* refactor(css): remove `export {}` ([98fbdc3](https://github.com/vitejs/vite/commit/98fbdc3))
* chore: fix ts error (#14053) ([6cb397f](https://github.com/vitejs/vite/commit/6cb397f)), closes [#14053](https://github.com/vitejs/vite/issues/14053)
* chore: use "kB" everywhere with the correct definition (#14061) ([f97ef58](https://github.com/vitejs/vite/commit/f97ef58)), closes [#14061](https://github.com/vitejs/vite/issues/14061)
* chore(client): remove redundant if statement (#14137) ([fe1c0b9](https://github.com/vitejs/vite/commit/fe1c0b9)), closes [#14137](https://github.com/vitejs/vite/issues/14137)
* refactor(css): use `preliminaryFileName` to detect pure CSS chunks (#13974) ([835249d](https://github.com/vitejs/vite/commit/835249d)), closes [#13974](https://github.com/vitejs/vite/issues/13974)



### Previous Changelogs


#### [5.0.0-beta.20](https://github.com/vitejs/vite/compare/v5.0.0-beta.19...v5.0.0-beta.20) (2023-11-15)
See [5.0.0-beta.20 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.20/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.19](https://github.com/vitejs/vite/compare/v5.0.0-beta.18...v5.0.0-beta.19) (2023-11-14)
See [5.0.0-beta.19 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.19/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.18](https://github.com/vitejs/vite/compare/v5.0.0-beta.17...v5.0.0-beta.18) (2023-11-11)
See [5.0.0-beta.18 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.18/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.17](https://github.com/vitejs/vite/compare/v5.0.0-beta.16...v5.0.0-beta.17) (2023-11-07)
See [5.0.0-beta.17 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.17/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.16](https://github.com/vitejs/vite/compare/v5.0.0-beta.15...v5.0.0-beta.16) (2023-11-03)
See [5.0.0-beta.16 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.16/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.15](https://github.com/vitejs/vite/compare/v5.0.0-beta.14...v5.0.0-beta.15) (2023-11-01)
See [5.0.0-beta.15 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.15/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.14](https://github.com/vitejs/vite/compare/v5.0.0-beta.13...v5.0.0-beta.14) (2023-10-30)
See [5.0.0-beta.14 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.14/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.13](https://github.com/vitejs/vite/compare/v5.0.0-beta.12...v5.0.0-beta.13) (2023-10-27)
See [5.0.0-beta.13 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.13/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.12](https://github.com/vitejs/vite/compare/v5.0.0-beta.11...v5.0.0-beta.12) (2023-10-23)
See [5.0.0-beta.12 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.12/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.11](https://github.com/vitejs/vite/compare/v5.0.0-beta.10...v5.0.0-beta.11) (2023-10-19)
See [5.0.0-beta.11 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.11/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.10](https://github.com/vitejs/vite/compare/v5.0.0-beta.9...v5.0.0-beta.10) (2023-10-17)
See [5.0.0-beta.10 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.10/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.9](https://github.com/vitejs/vite/compare/v5.0.0-beta.8...v5.0.0-beta.9) (2023-10-17)

See [5.0.0-beta.9 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.9/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.8](https://github.com/vitejs/vite/compare/v5.0.0-beta.7...v5.0.0-beta.8) (2023-10-16)

See [5.0.0-beta.8 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.8/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.7](https://github.com/vitejs/vite/compare/v5.0.0-beta.6...v5.0.0-beta.7) (2023-10-12)

See [5.0.0-beta.7 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.7/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.6](https://github.com/vitejs/vite/compare/v5.0.0-beta.5...v5.0.0-beta.6) (2023-10-10)

See [5.0.0-beta.6 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.6/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.5](https://github.com/vitejs/vite/compare/v5.0.0-beta.4...v5.0.0-beta.5) (2023-10-09)

See [5.0.0-beta.5 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.5/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.4](https://github.com/vitejs/vite/compare/v5.0.0-beta.3...v5.0.0-beta.4) (2023-10-02)

See [5.0.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.4/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.3](https://github.com/vitejs/vite/compare/v5.0.0-beta.2...v5.0.0-beta.3) (2023-09-25)

See [5.0.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.3/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.2](https://github.com/vitejs/vite/compare/v5.0.0-beta.1...v5.0.0-beta.2) (2023-09-15)

See [5.0.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.2/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.1](https://github.com/vitejs/vite/compare/v5.0.0-beta.0...v5.0.0-beta.1) (2023-09-08)

See [5.0.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.1/packages/vite/CHANGELOG.md)


#### [5.0.0-beta.0](https://github.com/vitejs/vite/compare/v4.4.9...v5.0.0-beta.0) (2023-08-24)

See [5.0.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v5.0.0-beta.0/packages/vite/CHANGELOG.md)


## 4.5.0 (2023-10-18)

* feat: backport mdx as known js source (#14560) (#14670) ([45595ef](https://github.com/vitejs/vite/commit/45595ef)), closes [#14560](https://github.com/vitejs/vite/issues/14560) [#14670](https://github.com/vitejs/vite/issues/14670)
* feat: scan .marko files (#14669) ([ed7bdc5](https://github.com/vitejs/vite/commit/ed7bdc5)), closes [#14669](https://github.com/vitejs/vite/issues/14669)
* feat(ssr): backport ssr.resolve.conditions and ssr.resolve.externalConditions (#14498) (#14668) ([520139c](https://github.com/vitejs/vite/commit/520139c)), closes [#14498](https://github.com/vitejs/vite/issues/14498) [#14668](https://github.com/vitejs/vite/issues/14668)



## <small>4.4.11 (2023-10-05)</small>

* revert: "fix: use string manipulation instead of regex to inject esbuild helpers ([54e1275](https://github.com/vitejs/vite/commit/54e1275)), closes [#14094](https://github.com/vitejs/vite/issues/14094)



## <small>4.4.10 (2023-10-03)</small>

* fix: add source map to Web Workers (fix #14216) (#14217) ([df6f32f](https://github.com/vitejs/vite/commit/df6f32f)), closes [#14216](https://github.com/vitejs/vite/issues/14216) [#14217](https://github.com/vitejs/vite/issues/14217)
* fix: handle errors during `hasWorkspacePackageJSON` function (#14394) ([6f6e5de](https://github.com/vitejs/vite/commit/6f6e5de)), closes [#14394](https://github.com/vitejs/vite/issues/14394)
* fix: handle sourcemap correctly when multiple line import exists (#14232) ([218861f](https://github.com/vitejs/vite/commit/218861f)), closes [#14232](https://github.com/vitejs/vite/issues/14232)
* fix: if host is specified check whether it is valid (#14013) ([b1b816a](https://github.com/vitejs/vite/commit/b1b816a)), closes [#14013](https://github.com/vitejs/vite/issues/14013)
* fix: include `vite/types/*` in exports field (#14296) ([40e99a1](https://github.com/vitejs/vite/commit/40e99a1)), closes [#14296](https://github.com/vitejs/vite/issues/14296)
* fix: initWasm options should be optional (#14152) ([119c074](https://github.com/vitejs/vite/commit/119c074)), closes [#14152](https://github.com/vitejs/vite/issues/14152)
* fix: restore builtins list ([f8b9adb](https://github.com/vitejs/vite/commit/f8b9adb))
* fix: use string manipulation instead of regex to inject esbuild helpers (#14094) ([128ad8f](https://github.com/vitejs/vite/commit/128ad8f)), closes [#14094](https://github.com/vitejs/vite/issues/14094)
* fix: ws never connects after restarting server if server.hmr.server is set (#14127) ([441642e](https://github.com/vitejs/vite/commit/441642e)), closes [#14127](https://github.com/vitejs/vite/issues/14127)
* fix(analysis): warnings for dynamic imports that use static template literals (#14458) ([0c6d289](https://github.com/vitejs/vite/commit/0c6d289)), closes [#14458](https://github.com/vitejs/vite/issues/14458)
* fix(cli): convert special base (#14283) ([d4bc0fb](https://github.com/vitejs/vite/commit/d4bc0fb)), closes [#14283](https://github.com/vitejs/vite/issues/14283)
* fix(css): remove pure css chunk sourcemap (#14290) ([cd7e033](https://github.com/vitejs/vite/commit/cd7e033)), closes [#14290](https://github.com/vitejs/vite/issues/14290)
* fix(css): reset render cache on renderStart (#14326) ([d334b3d](https://github.com/vitejs/vite/commit/d334b3d)), closes [#14326](https://github.com/vitejs/vite/issues/14326)
* fix(glob): trigger HMR for glob in a  package (#14117) ([0f582bf](https://github.com/vitejs/vite/commit/0f582bf)), closes [#14117](https://github.com/vitejs/vite/issues/14117)
* fix(import-analysis): preserve importedUrls import order (#14465) ([269aa43](https://github.com/vitejs/vite/commit/269aa43)), closes [#14465](https://github.com/vitejs/vite/issues/14465)
* fix(manifest): preserve pure css chunk assets (#14297) ([3d63ae6](https://github.com/vitejs/vite/commit/3d63ae6)), closes [#14297](https://github.com/vitejs/vite/issues/14297)
* fix(optimizer): define crawlDeps after scanProcessing and optimizationResult are complete (fix #1428 ([fcaf749](https://github.com/vitejs/vite/commit/fcaf749)), closes [#14284](https://github.com/vitejs/vite/issues/14284) [#14285](https://github.com/vitejs/vite/issues/14285)
* fix(resolve): support submodules of optional peer deps (#14489) ([104971d](https://github.com/vitejs/vite/commit/104971d)), closes [#14489](https://github.com/vitejs/vite/issues/14489)
* fix(vite): precisely check if files are in dirs (#14241) ([c4758d1](https://github.com/vitejs/vite/commit/c4758d1)), closes [#14241](https://github.com/vitejs/vite/issues/14241)
* feat: improve deno and bun support (#14379) ([8bc1f9d](https://github.com/vitejs/vite/commit/8bc1f9d)), closes [#14379](https://github.com/vitejs/vite/issues/14379)



## <small>4.4.9 (2023-08-07)</small>

* chore: fix eslint warnings (#14031) ([4021a0e](https://github.com/vitejs/vite/commit/4021a0e)), closes [#14031](https://github.com/vitejs/vite/issues/14031)
* chore(deps): update all non-major dependencies (#13938) ([a1b519e](https://github.com/vitejs/vite/commit/a1b519e)), closes [#13938](https://github.com/vitejs/vite/issues/13938)
* fix: dynamic import vars ignored warning (#14006) ([4479431](https://github.com/vitejs/vite/commit/4479431)), closes [#14006](https://github.com/vitejs/vite/issues/14006)
* fix(build): silence warn dynamic import module when inlineDynamicImports true (#13970) ([7a77aaf](https://github.com/vitejs/vite/commit/7a77aaf)), closes [#13970](https://github.com/vitejs/vite/issues/13970)
* perf: improve build times and memory utilization (#14016) ([9d7d45e](https://github.com/vitejs/vite/commit/9d7d45e)), closes [#14016](https://github.com/vitejs/vite/issues/14016)
* perf: replace startsWith with === (#14005) ([f5c1224](https://github.com/vitejs/vite/commit/f5c1224)), closes [#14005](https://github.com/vitejs/vite/issues/14005)



## <small>4.4.8 (2023-07-31)</small>

* fix: modulePreload false (#13973) ([488085d](https://github.com/vitejs/vite/commit/488085d)), closes [#13973](https://github.com/vitejs/vite/issues/13973)
* fix: multiple entries with shared css and no JS (#13962) ([89a3db0](https://github.com/vitejs/vite/commit/89a3db0)), closes [#13962](https://github.com/vitejs/vite/issues/13962)
* fix: use file extensions on type imports so they work with `moduleResolution: 'node16'` (#13947) ([aeef670](https://github.com/vitejs/vite/commit/aeef670)), closes [#13947](https://github.com/vitejs/vite/issues/13947)
* fix(css): enhance error message for missing preprocessor dependency (#11485) ([65e5c22](https://github.com/vitejs/vite/commit/65e5c22)), closes [#11485](https://github.com/vitejs/vite/issues/11485)
* fix(esbuild): fix static properties transpile when useDefineForClassFields false (#13992) ([4ca7c13](https://github.com/vitejs/vite/commit/4ca7c13)), closes [#13992](https://github.com/vitejs/vite/issues/13992)
* fix(importAnalysis): strip url base before passing as safeModulePaths (#13712) ([1ab06a8](https://github.com/vitejs/vite/commit/1ab06a8)), closes [#13712](https://github.com/vitejs/vite/issues/13712)
* fix(importMetaGlob): avoid unnecessary hmr of negative glob (#13646) ([844451c](https://github.com/vitejs/vite/commit/844451c)), closes [#13646](https://github.com/vitejs/vite/issues/13646)
* fix(optimizer): avoid double-commit of optimized deps when discovery is disabled (#13865) ([df77991](https://github.com/vitejs/vite/commit/df77991)), closes [#13865](https://github.com/vitejs/vite/issues/13865)
* fix(optimizer): enable experimentalDecorators by default (#13981) ([f8a5ffc](https://github.com/vitejs/vite/commit/f8a5ffc)), closes [#13981](https://github.com/vitejs/vite/issues/13981)
* perf: replace startsWith with === (#13989) ([3aab14e](https://github.com/vitejs/vite/commit/3aab14e)), closes [#13989](https://github.com/vitejs/vite/issues/13989)
* perf: single slash does not need to be replaced (#13980) ([66f522c](https://github.com/vitejs/vite/commit/66f522c)), closes [#13980](https://github.com/vitejs/vite/issues/13980)
* perf: use Intl.DateTimeFormatter instead of toLocaleTimeString (#13951) ([af53a1d](https://github.com/vitejs/vite/commit/af53a1d)), closes [#13951](https://github.com/vitejs/vite/issues/13951)
* perf: use Intl.NumberFormat instead of toLocaleString (#13949) ([a48bf88](https://github.com/vitejs/vite/commit/a48bf88)), closes [#13949](https://github.com/vitejs/vite/issues/13949)
* perf: use magic-string hires boundary for sourcemaps (#13971) ([b9a8d65](https://github.com/vitejs/vite/commit/b9a8d65)), closes [#13971](https://github.com/vitejs/vite/issues/13971)
* chore(reporter): remove unnecessary map (#13972) ([dd9d4c1](https://github.com/vitejs/vite/commit/dd9d4c1)), closes [#13972](https://github.com/vitejs/vite/issues/13972)
* refactor: add new overload to the type of defineConfig (#13958) ([24c12fe](https://github.com/vitejs/vite/commit/24c12fe)), closes [#13958](https://github.com/vitejs/vite/issues/13958)



## <small>4.4.7 (2023-07-24)</small>

* fix: `optimizeDeps.include` not working with paths inside packages (#13922) ([06e4f57](https://github.com/vitejs/vite/commit/06e4f57)), closes [#13922](https://github.com/vitejs/vite/issues/13922)
* fix: lightningcss fails with html-proxy (#13776) ([6b56094](https://github.com/vitejs/vite/commit/6b56094)), closes [#13776](https://github.com/vitejs/vite/issues/13776)
* fix: prepend `config.base` to vite/env path (#13941) ([8e6cee8](https://github.com/vitejs/vite/commit/8e6cee8)), closes [#13941](https://github.com/vitejs/vite/issues/13941)
* fix(html): support `import.meta.env` define replacement without quotes (#13425) ([883089c](https://github.com/vitejs/vite/commit/883089c)), closes [#13425](https://github.com/vitejs/vite/issues/13425)
* fix(proxy): handle error when proxy itself errors (#13929) ([4848e41](https://github.com/vitejs/vite/commit/4848e41)), closes [#13929](https://github.com/vitejs/vite/issues/13929)
* chore(eslint): allow type annotations (#13920) ([d1264fd](https://github.com/vitejs/vite/commit/d1264fd)), closes [#13920](https://github.com/vitejs/vite/issues/13920)



## <small>4.4.6 (2023-07-21)</small>

* fix: constrain inject helpers for iife (#13909) ([c89f677](https://github.com/vitejs/vite/commit/c89f677)), closes [#13909](https://github.com/vitejs/vite/issues/13909)
* fix: display manualChunks warning only when a function is not used (#13797) (#13798) ([51c271f](https://github.com/vitejs/vite/commit/51c271f)), closes [#13797](https://github.com/vitejs/vite/issues/13797) [#13798](https://github.com/vitejs/vite/issues/13798)
* fix: do not append `browserHash` on optimized deps during build (#13906) ([0fb2340](https://github.com/vitejs/vite/commit/0fb2340)), closes [#13906](https://github.com/vitejs/vite/issues/13906)
* fix: use Bun's implementation of `ws` instead of the bundled one (#13901) ([049404c](https://github.com/vitejs/vite/commit/049404c)), closes [#13901](https://github.com/vitejs/vite/issues/13901)
* feat(client): add guide to press Esc for closing the overlay (#13896) ([da389cc](https://github.com/vitejs/vite/commit/da389cc)), closes [#13896](https://github.com/vitejs/vite/issues/13896)



## <small>4.4.5 (2023-07-20)</small>

* fix: "EISDIR: illegal operation on a directory, realpath" error on RA… (#13655) ([6bd5434](https://github.com/vitejs/vite/commit/6bd5434)), closes [#13655](https://github.com/vitejs/vite/issues/13655)
* fix: transform error message add file info (#13687) ([6dca41c](https://github.com/vitejs/vite/commit/6dca41c)), closes [#13687](https://github.com/vitejs/vite/issues/13687)
* fix: warn when publicDir and outDir are nested (#13742) ([4eb3154](https://github.com/vitejs/vite/commit/4eb3154)), closes [#13742](https://github.com/vitejs/vite/issues/13742)
* fix(build): remove warning about ineffective dynamic import from node_modules (#13884) ([33002dd](https://github.com/vitejs/vite/commit/33002dd)), closes [#13884](https://github.com/vitejs/vite/issues/13884)
* fix(build): style insert order for UMD builds (fix #13668) (#13669) ([49a1b99](https://github.com/vitejs/vite/commit/49a1b99)), closes [#13668](https://github.com/vitejs/vite/issues/13668) [#13669](https://github.com/vitejs/vite/issues/13669)
* fix(deps): update all non-major dependencies (#13872) ([975a631](https://github.com/vitejs/vite/commit/975a631)), closes [#13872](https://github.com/vitejs/vite/issues/13872)
* fix(types): narrow down the return type of `defineConfig` (#13792) ([c971f26](https://github.com/vitejs/vite/commit/c971f26)), closes [#13792](https://github.com/vitejs/vite/issues/13792)
* chore: fix typos (#13862) ([f54e8da](https://github.com/vitejs/vite/commit/f54e8da)), closes [#13862](https://github.com/vitejs/vite/issues/13862)
* chore: replace `any` with `string` (#13850) ([4606fd8](https://github.com/vitejs/vite/commit/4606fd8)), closes [#13850](https://github.com/vitejs/vite/issues/13850)
* chore(deps): update dependency prettier to v3 (#13759) ([5a56941](https://github.com/vitejs/vite/commit/5a56941)), closes [#13759](https://github.com/vitejs/vite/issues/13759)
* docs: fix build.cssMinify link (#13840) ([8a2a3e1](https://github.com/vitejs/vite/commit/8a2a3e1)), closes [#13840](https://github.com/vitejs/vite/issues/13840)



## <small>4.4.4 (2023-07-14)</small>

* chore: warning about ssr cjs format removal (#13827) ([4646e9f](https://github.com/vitejs/vite/commit/4646e9f)), closes [#13827](https://github.com/vitejs/vite/issues/13827)
* fix(esbuild): enable experimentalDecorators by default (#13805) ([e8880f0](https://github.com/vitejs/vite/commit/e8880f0)), closes [#13805](https://github.com/vitejs/vite/issues/13805)
* fix(scan): skip tsconfigRaw fallback if tsconfig is set (#13823) ([b6155a1](https://github.com/vitejs/vite/commit/b6155a1)), closes [#13823](https://github.com/vitejs/vite/issues/13823)
* feat(client): close `vite-error-overlay` with Escape key (#13795) ([85bdcda](https://github.com/vitejs/vite/commit/85bdcda)), closes [#13795](https://github.com/vitejs/vite/issues/13795)



## <small>4.4.3 (2023-07-11)</small>

* fix: avoid early error when server is closed in ssr (#13787) ([89d01eb](https://github.com/vitejs/vite/commit/89d01eb)), closes [#13787](https://github.com/vitejs/vite/issues/13787)
* fix(deps): update all non-major dependencies (#13758) ([8ead116](https://github.com/vitejs/vite/commit/8ead116)), closes [#13758](https://github.com/vitejs/vite/issues/13758)
* fix(server): remove restart guard on restart (#13789) ([2a38ef7](https://github.com/vitejs/vite/commit/2a38ef7)), closes [#13789](https://github.com/vitejs/vite/issues/13789)



## <small>4.4.2 (2023-07-07)</small>

* fix(css): use single postcss instance (#13738) ([c02fac4](https://github.com/vitejs/vite/commit/c02fac4)), closes [#13738](https://github.com/vitejs/vite/issues/13738)



## <small>4.4.1 (2023-07-06)</small>

* fix: revert #13073, use consistent virtual module ID in module graph (#13734) ([f589ac0](https://github.com/vitejs/vite/commit/f589ac0)), closes [#13073](https://github.com/vitejs/vite/issues/13073) [#13734](https://github.com/vitejs/vite/issues/13734)
* fix: revert import config module as data (#13731) ([b0bfa01](https://github.com/vitejs/vite/commit/b0bfa01)), closes [#13731](https://github.com/vitejs/vite/issues/13731)
* chore: changelog notes and clean for 4.4 (#13728) ([3f4e36e](https://github.com/vitejs/vite/commit/3f4e36e)), closes [#13728](https://github.com/vitejs/vite/issues/13728)



## 4.4.0 (2023-07-06)

### Experimental support for Lightning CSS

Starting from Vite 4.4, there is experimental support for [Lightning CSS](https://lightningcss.dev/). You can opt into it by adding [`css.transformer: 'lightningcss'`](https://main.vitejs.dev/config/shared-options.html#css-transformer) to your config file and install the optional [`lightningcss`](https://www.npmjs.com/package/lightningcss) dev dependency. If enabled, CSS files will be processed by Lightning CSS instead of PostCSS.

Lightning CSS can also be used as the CSS minifier with [`build.cssMinify: 'lightningcss'`](https://main.vitejs.dev/config/build-options.html#build-cssminify).

See beta docs at the [Lighting CSS guide](https://main.vitejs.dev/guide/features.html#lightning-css).

### esbuild 0.18 update

[esbuild 0.18](https://github.com/evanw/esbuild/blob/main/CHANGELOG.md#0180) contains backwards-incompatible changes to esbuild's handling of `tsconfig.json` files. We think they shouldn't affect Vite users, you can review [#13525](https://github.com/vitejs/vite/issues/13525) for more information.

### Templates for Solid and Qwik in create-vite

New starter templates have been added to [create-vite](https://vitejs.dev/guide/#scaffolding-your-first-vite-project) for [Solid](https://www.solidjs.com/) and [Qwik](https://qwik.builder.io/). Try them online at [vite.new/solid-ts](https://vite.new/solid-ts) and [vite.new/qwik-ts](https://vite.new/qwik-ts).

### Korean Translation

Vite's docs are now translated to Korean, available at [ko.vitejs.dev](https://ko.vitejs.dev).

### Features

* feat: preview mode add keyboard shortcuts (#12968) ([126e93e](https://github.com/vitejs/vite/commit/126e93e)), closes [#12968](https://github.com/vitejs/vite/issues/12968)
* feat: asset type add apng (#13294) ([a11b6f6](https://github.com/vitejs/vite/commit/a11b6f6)), closes [#13294](https://github.com/vitejs/vite/issues/13294)
* feat: emit event to handle chunk load errors (#12084) ([2eca54e](https://github.com/vitejs/vite/commit/2eca54e)), closes [#12084](https://github.com/vitejs/vite/issues/12084)
* feat: import public non-asset URL (#13422) ([3a98558](https://github.com/vitejs/vite/commit/3a98558)), closes [#13422](https://github.com/vitejs/vite/issues/13422)
* feat: support files for `fs.allow` (#12863) ([4a06e66](https://github.com/vitejs/vite/commit/4a06e66)), closes [#12863](https://github.com/vitejs/vite/issues/12863)
* feat(build): warn dynamic import module with a static import alongside (#12850) ([127c334](https://github.com/vitejs/vite/commit/127c334)), closes [#12850](https://github.com/vitejs/vite/issues/12850)
* feat(client): add debounce on page reload (#13545) ([d080b51](https://github.com/vitejs/vite/commit/d080b51)), closes [#13545](https://github.com/vitejs/vite/issues/13545)
* feat(client): add WebSocket connections events (#13334) ([eb75103](https://github.com/vitejs/vite/commit/eb75103)), closes [#13334](https://github.com/vitejs/vite/issues/13334)
* feat(config): friendly ESM file require error (#13283) ([b9a6ba0](https://github.com/vitejs/vite/commit/b9a6ba0)), closes [#13283](https://github.com/vitejs/vite/issues/13283)
* feat(css): add support for Lightning CSS (#12807) ([c6c5d49](https://github.com/vitejs/vite/commit/c6c5d49)), closes [#12807](https://github.com/vitejs/vite/issues/12807)
* feat(css): support at import preprocessed styles (#8400) ([2bd6077](https://github.com/vitejs/vite/commit/2bd6077)), closes [#8400](https://github.com/vitejs/vite/issues/8400)
* feat(html): support image set in inline style (#13473) ([2c0faba](https://github.com/vitejs/vite/commit/2c0faba)), closes [#13473](https://github.com/vitejs/vite/issues/13473)
* feat(importMetaGlob): support sub imports pattern (#12467) ([e355c9c](https://github.com/vitejs/vite/commit/e355c9c)), closes [#12467](https://github.com/vitejs/vite/issues/12467)
* feat(optimizer): support glob includes (#12414) ([7792515](https://github.com/vitejs/vite/commit/7792515)), closes [#12414](https://github.com/vitejs/vite/issues/12414)
* feat!: update esbuild to 0.18.2 (#13525) ([ab967c0](https://github.com/vitejs/vite/commit/ab967c0)), closes [#13525](https://github.com/vitejs/vite/issues/13525)

### Bug Fixes

* fix: check document before detect script rel (#13559) ([be4b0c0](https://github.com/vitejs/vite/commit/be4b0c0)), closes [#13559](https://github.com/vitejs/vite/issues/13559)
* fix(define): stringify object parse error in build mode (#13600) ([71516db](https://github.com/vitejs/vite/commit/71516db)), closes [#13600](https://github.com/vitejs/vite/issues/13600)
* fix(deps): update all non-major dependencies (#13701) ([02c6bc3](https://github.com/vitejs/vite/commit/02c6bc3)), closes [#13701](https://github.com/vitejs/vite/issues/13701)
* fix(esbuild): use `useDefineForClassFields: false` when no `compilerOptions.target` is declared (#13 ([7ef2472](https://github.com/vitejs/vite/commit/7ef2472)), closes [#13708](https://github.com/vitejs/vite/issues/13708)
* fix(pluginContainer): drop previous sourcesContent (#13722) ([9310b3a](https://github.com/vitejs/vite/commit/9310b3a)), closes [#13722](https://github.com/vitejs/vite/issues/13722)
* fix: lightningCSS should load external URL in CSS file (#13692) ([8517645](https://github.com/vitejs/vite/commit/8517645)), closes [#13692](https://github.com/vitejs/vite/issues/13692)
* fix: shortcut open browser when set host (#13677) ([6f1c55e](https://github.com/vitejs/vite/commit/6f1c55e)), closes [#13677](https://github.com/vitejs/vite/issues/13677)
* fix(cli): convert the sourcemap option to boolean (fix #13638) (#13663) ([d444bfe](https://github.com/vitejs/vite/commit/d444bfe)), closes [#13638](https://github.com/vitejs/vite/issues/13638) [#13663](https://github.com/vitejs/vite/issues/13663)
* fix(css): use esbuild legalComments config when minifying CSS (#13661) ([2d9008e](https://github.com/vitejs/vite/commit/2d9008e)), closes [#13661](https://github.com/vitejs/vite/issues/13661)
* fix(sourcemap): preserve original sourcesContent (#13662) ([f6362b6](https://github.com/vitejs/vite/commit/f6362b6)), closes [#13662](https://github.com/vitejs/vite/issues/13662)
* fix(ssr): transform superclass identifier (#13635) ([c5b2c8f](https://github.com/vitejs/vite/commit/c5b2c8f)), closes [#13635](https://github.com/vitejs/vite/issues/13635)
* fix: show error position (#13623) ([90271a6](https://github.com/vitejs/vite/commit/90271a6)), closes [#13623](https://github.com/vitejs/vite/issues/13623)
* fix(hmr): only invalidate `lastHMRTimestamp` of importers if the invalidated module is not a HMR bou ([1143e0b](https://github.com/vitejs/vite/commit/1143e0b)), closes [#13024](https://github.com/vitejs/vite/issues/13024)
* fix(indexHtml): decode html URI (#13581) ([f8868af](https://github.com/vitejs/vite/commit/f8868af)), closes [#13581](https://github.com/vitejs/vite/issues/13581)
* fix: avoid binding ClassExpression (#13572) ([1a0c806](https://github.com/vitejs/vite/commit/1a0c806)), closes [#13572](https://github.com/vitejs/vite/issues/13572)
* fix: the shortcut fails to open browser when set the host (#13579) ([e0a48c5](https://github.com/vitejs/vite/commit/e0a48c5)), closes [#13579](https://github.com/vitejs/vite/issues/13579)
* fix(proxy): forward SSE close event (#13578) ([4afbccb](https://github.com/vitejs/vite/commit/4afbccb)), closes [#13578](https://github.com/vitejs/vite/issues/13578)
* fix: allow using vite as a proxy for another vite server (#13218) ([711dd80](https://github.com/vitejs/vite/commit/711dd80)), closes [#13218](https://github.com/vitejs/vite/issues/13218)
* fix: await requests to before server restart (#13262) ([0464398](https://github.com/vitejs/vite/commit/0464398)), closes [#13262](https://github.com/vitejs/vite/issues/13262)
* fix: esm detection with `export const { A, B }` pattern (#13483) ([ea1bcc9](https://github.com/vitejs/vite/commit/ea1bcc9)), closes [#13483](https://github.com/vitejs/vite/issues/13483)
* fix: keep track of ssr version of imported modules separately (#11973) ([8fe6952](https://github.com/vitejs/vite/commit/8fe6952)), closes [#11973](https://github.com/vitejs/vite/issues/11973)
* fix: make optimize error available to meta-framework (#13495) ([b70e783](https://github.com/vitejs/vite/commit/b70e783)), closes [#13495](https://github.com/vitejs/vite/issues/13495)
* fix: only show the listened IP when host is specified (#13412) ([20b0cae](https://github.com/vitejs/vite/commit/20b0cae)), closes [#13412](https://github.com/vitejs/vite/issues/13412)
* fix: race condition creation module in graph in transformRequest (#13085) ([43cbbcf](https://github.com/vitejs/vite/commit/43cbbcf)), closes [#13085](https://github.com/vitejs/vite/issues/13085)
* fix: remove deprecated config.server.base (#13482) ([dc597bd](https://github.com/vitejs/vite/commit/dc597bd)), closes [#13482](https://github.com/vitejs/vite/issues/13482)
* fix: remove extra path shorten when resolving from a dir (#13381) ([5503198](https://github.com/vitejs/vite/commit/5503198)), closes [#13381](https://github.com/vitejs/vite/issues/13381)
* fix: show network URLs when `--host 0.0.0.0` (#13438) ([00ee8c1](https://github.com/vitejs/vite/commit/00ee8c1)), closes [#13438](https://github.com/vitejs/vite/issues/13438)
* fix: timestamp config dynamicImport (#13502) ([6a87c65](https://github.com/vitejs/vite/commit/6a87c65)), closes [#13502](https://github.com/vitejs/vite/issues/13502)
* fix: unexpected config temporary file (#13269) ([ff3ce31](https://github.com/vitejs/vite/commit/ff3ce31)), closes [#13269](https://github.com/vitejs/vite/issues/13269)
* fix: use consistent virtual module ID in module graph (#13073) ([aa1776f](https://github.com/vitejs/vite/commit/aa1776f)), closes [#13073](https://github.com/vitejs/vite/issues/13073)
* fix(build): make output warning message clearer (#12924) ([54ab3c8](https://github.com/vitejs/vite/commit/54ab3c8)), closes [#12924](https://github.com/vitejs/vite/issues/12924)
* fix(debug): import performance from perf_hooks (#13464) ([d458ccd](https://github.com/vitejs/vite/commit/d458ccd)), closes [#13464](https://github.com/vitejs/vite/issues/13464)
* fix(deps): update all non-major dependencies (#13059) ([123ef4c](https://github.com/vitejs/vite/commit/123ef4c)), closes [#13059](https://github.com/vitejs/vite/issues/13059)
* fix(deps): update all non-major dependencies (#13488) ([bd09248](https://github.com/vitejs/vite/commit/bd09248)), closes [#13488](https://github.com/vitejs/vite/issues/13488)
* fix(deps): update sirv to 2.0.3 (#13057) ([d814d6c](https://github.com/vitejs/vite/commit/d814d6c)), closes [#13057](https://github.com/vitejs/vite/issues/13057)
* fix(mergeConfig): don't accept callback config (#13135) ([998512b](https://github.com/vitejs/vite/commit/998512b)), closes [#13135](https://github.com/vitejs/vite/issues/13135)
* fix(optimizer): include exports for css modules (#13519) ([1fd9919](https://github.com/vitejs/vite/commit/1fd9919)), closes [#13519](https://github.com/vitejs/vite/issues/13519)
* fix(resolve): always use `module` condition (#13370) ([367920b](https://github.com/vitejs/vite/commit/367920b)), closes [#13370](https://github.com/vitejs/vite/issues/13370)
* fix(ssr): fix crash when a pnpm/Yarn workspace depends on a CJS package (#9763) ([9e1086b](https://github.com/vitejs/vite/commit/9e1086b)), closes [#9763](https://github.com/vitejs/vite/issues/9763)


### Previous Changelogs


#### [4.4.0-beta.4](https://github.com/vitejs/vite/compare/v4.4.0-beta.3...v4.4.0-beta.4) (2023-07-03)

See [4.4.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v4.4.0-beta.4/packages/vite/CHANGELOG.md)


#### [4.4.0-beta.3](https://github.com/vitejs/vite/compare/v4.4.0-beta.2...v4.4.0-beta.3) (2023-06-25)

See [4.4.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v4.4.0-beta.3/packages/vite/CHANGELOG.md)


#### [4.4.0-beta.2](https://github.com/vitejs/vite/compare/v4.4.0-beta.1...v4.4.0-beta.2) (2023-06-22)

See [4.4.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v4.4.0-beta.2/packages/vite/CHANGELOG.md)


#### [4.4.0-beta.1](https://github.com/vitejs/vite/compare/v4.4.0-beta.0...v4.4.0-beta.1) (2023-06-21)

See [4.4.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v4.4.0-beta.1/packages/vite/CHANGELOG.md)


#### [4.4.0-beta.0](https://github.com/vitejs/vite/compare/v4.3.9...v4.4.0-beta.0) (2023-06-20)

See [4.4.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v4.4.0-beta.0/packages/vite/CHANGELOG.md)



## <small>4.3.9 (2023-05-26)</small>

* fix: fs.deny with leading double slash (#13348) ([813ddd6](https://github.com/vitejs/vite/commit/813ddd6)), closes [#13348](https://github.com/vitejs/vite/issues/13348)
* fix: optimizeDeps during build and external ids (#13274) ([e3db771](https://github.com/vitejs/vite/commit/e3db771)), closes [#13274](https://github.com/vitejs/vite/issues/13274)
* fix(css): return deps if have no postcss plugins (#13344) ([28923fb](https://github.com/vitejs/vite/commit/28923fb)), closes [#13344](https://github.com/vitejs/vite/issues/13344)
* fix(legacy): style insert order (#13266) ([e444375](https://github.com/vitejs/vite/commit/e444375)), closes [#13266](https://github.com/vitejs/vite/issues/13266)
* chore: revert prev release commit ([2a30a07](https://github.com/vitejs/vite/commit/2a30a07))
* release: v4.3.9 ([5c9abf7](https://github.com/vitejs/vite/commit/5c9abf7))
* docs: optimizeDeps.needsInterop (#13323) ([b34e79c](https://github.com/vitejs/vite/commit/b34e79c)), closes [#13323](https://github.com/vitejs/vite/issues/13323)
* test: respect commonjs options in playgrounds (#13273) ([19e8c68](https://github.com/vitejs/vite/commit/19e8c68)), closes [#13273](https://github.com/vitejs/vite/issues/13273)
* refactor: simplify SSR options' if statement (#13254) ([8013a66](https://github.com/vitejs/vite/commit/8013a66)), closes [#13254](https://github.com/vitejs/vite/issues/13254)
* perf(ssr): calculate stacktrace offset lazily (#13256) ([906c4c1](https://github.com/vitejs/vite/commit/906c4c1)), closes [#13256](https://github.com/vitejs/vite/issues/13256)



## <small>4.3.8 (2023-05-18)</small>

* fix: avoid outdated module to crash in importAnalysis after restart (#13231) ([3609e79](https://github.com/vitejs/vite/commit/3609e79)), closes [#13231](https://github.com/vitejs/vite/issues/13231)
* fix(ssr): skip updateCjsSsrExternals if legacy flag disabled (#13230) ([13fc345](https://github.com/vitejs/vite/commit/13fc345)), closes [#13230](https://github.com/vitejs/vite/issues/13230)



## <small>4.3.7 (2023-05-16)</small>

* fix: revert only watch .env files in envDir (#12587) (#13217) ([0fd4616](https://github.com/vitejs/vite/commit/0fd4616)), closes [#12587](https://github.com/vitejs/vite/issues/12587) [#13217](https://github.com/vitejs/vite/issues/13217)
* fix(assetImportMetaUrl): allow ternary operator in template literal urls (#13121) ([d5d9a31](https://github.com/vitejs/vite/commit/d5d9a31)), closes [#13121](https://github.com/vitejs/vite/issues/13121)



## <small>4.3.6 (2023-05-15)</small>

* fix: avoid dev-server crash when ws proxy error (#12829) ([87e1f58](https://github.com/vitejs/vite/commit/87e1f58)), closes [#12829](https://github.com/vitejs/vite/issues/12829)
* fix: call `tryFsResolve` for relative `new URL(foo, import.meta.url)` (#13142) ([eeb0617](https://github.com/vitejs/vite/commit/eeb0617)), closes [#13142](https://github.com/vitejs/vite/issues/13142)
* fix: don't inject CSS sourcemap for direct requests (#13115) ([7d80a47](https://github.com/vitejs/vite/commit/7d80a47)), closes [#13115](https://github.com/vitejs/vite/issues/13115)
* fix: handle more yarn pnp load errors (#13160) ([adf61d9](https://github.com/vitejs/vite/commit/adf61d9)), closes [#13160](https://github.com/vitejs/vite/issues/13160)
* fix(build): declare moduleSideEffects for vite:modulepreload-polyfill (#13099) ([d63129b](https://github.com/vitejs/vite/commit/d63129b)), closes [#13099](https://github.com/vitejs/vite/issues/13099)
* fix(css): respect `esbuild.charset` when minify (#13190) ([4fd35ed](https://github.com/vitejs/vite/commit/4fd35ed)), closes [#13190](https://github.com/vitejs/vite/issues/13190)
* fix(server): intercept ping requests (#13117) ([d06cc42](https://github.com/vitejs/vite/commit/d06cc42)), closes [#13117](https://github.com/vitejs/vite/issues/13117)
* fix(ssr): stacktrace uses abs path with or without sourcemap (#12902) ([88c855e](https://github.com/vitejs/vite/commit/88c855e)), closes [#12902](https://github.com/vitejs/vite/issues/12902)
* perf: skip windows absolute paths for node resolve (#13162) ([e640939](https://github.com/vitejs/vite/commit/e640939)), closes [#13162](https://github.com/vitejs/vite/issues/13162)
* chore: remove useless dep (#13165) ([9a7ec98](https://github.com/vitejs/vite/commit/9a7ec98)), closes [#13165](https://github.com/vitejs/vite/issues/13165)
* chore(reporter): reuse clearLine (#13156) ([535795a](https://github.com/vitejs/vite/commit/535795a)), closes [#13156](https://github.com/vitejs/vite/issues/13156)



## <small>4.3.5 (2023-05-05)</small>

* fix: location is not defined error in cleanScssBugUrl (#13100) ([91d7b67](https://github.com/vitejs/vite/commit/91d7b67)), closes [#13100](https://github.com/vitejs/vite/issues/13100)
* fix: unwrapId and pass ssr flag when adding to moduleGraph in this.load (#13083) ([9041e19](https://github.com/vitejs/vite/commit/9041e19)), closes [#13083](https://github.com/vitejs/vite/issues/13083)
* fix(assetImportMetaUrl): reserve dynamic template literal query params (#13034) ([7089528](https://github.com/vitejs/vite/commit/7089528)), closes [#13034](https://github.com/vitejs/vite/issues/13034)
* fix(debug): skip filter object args (#13098) ([d95a9af](https://github.com/vitejs/vite/commit/d95a9af)), closes [#13098](https://github.com/vitejs/vite/issues/13098)
* fix(scan): handle html script tag attributes that contain ">" (#13101) ([8a37de6](https://github.com/vitejs/vite/commit/8a37de6)), closes [#13101](https://github.com/vitejs/vite/issues/13101)
* fix(ssr): ignore __esModule for ssrExportAll (#13084) ([8a8ea1d](https://github.com/vitejs/vite/commit/8a8ea1d)), closes [#13084](https://github.com/vitejs/vite/issues/13084)



## <small>4.3.4 (2023-05-02)</small>

* fix(define): incorrect raw expression value type in build (#13003) ([8f4cf07](https://github.com/vitejs/vite/commit/8f4cf07)), closes [#13003](https://github.com/vitejs/vite/issues/13003)
* fix(importAnalysisBuild): support parsing '__VITE_PRELOAD__' (#13023) ([447df7c](https://github.com/vitejs/vite/commit/447df7c)), closes [#13023](https://github.com/vitejs/vite/issues/13023)
* fix(server): should respect hmr port when middlewareMode=false (#13040) ([1ee0014](https://github.com/vitejs/vite/commit/1ee0014)), closes [#13040](https://github.com/vitejs/vite/issues/13040)
* fix(ssr): track for statements as block scope (#13021) ([2f8502f](https://github.com/vitejs/vite/commit/2f8502f)), closes [#13021](https://github.com/vitejs/vite/issues/13021)
* chore: add changelog for vite 4.2.2 and 3.2.6 (#13055) ([0c9f1f4](https://github.com/vitejs/vite/commit/0c9f1f4)), closes [#13055](https://github.com/vitejs/vite/issues/13055)



## <small>4.3.3 (2023-04-26)</small>

* fix: address file path mismatch when loading Vite config file on Windows (fix #12923) (#13005) ([84c4118](https://github.com/vitejs/vite/commit/84c4118)), closes [#12923](https://github.com/vitejs/vite/issues/12923) [#13005](https://github.com/vitejs/vite/issues/13005)
* fix: undefined document in worker (#12988) ([08c1452](https://github.com/vitejs/vite/commit/08c1452)), closes [#12988](https://github.com/vitejs/vite/issues/12988)
* fix(resolve): deep import resolvedId error (#13010) ([30a41ff](https://github.com/vitejs/vite/commit/30a41ff)), closes [#13010](https://github.com/vitejs/vite/issues/13010)
* feat: optimize deps option to turn off auto discovery (#13000) ([bd86375](https://github.com/vitejs/vite/commit/bd86375)), closes [#13000](https://github.com/vitejs/vite/issues/13000)
* chore(deps): update all non-major dependencies (#12805) ([5731ac9](https://github.com/vitejs/vite/commit/5731ac9)), closes [#12805](https://github.com/vitejs/vite/issues/12805)



## <small>4.3.2 (2023-04-25)</small>

* fix: status optional in windows network drive regex (fix: #12948) (#12949) ([f781fc6](https://github.com/vitejs/vite/commit/f781fc6)), closes [#12948](https://github.com/vitejs/vite/issues/12948) [#12949](https://github.com/vitejs/vite/issues/12949)
* fix: use realpathSync for node <16.18 on windows (#12971) ([965839c](https://github.com/vitejs/vite/commit/965839c)), closes [#12971](https://github.com/vitejs/vite/issues/12971)
* fix(ssr): hoist statements after hashbang (#12985) ([07bd6d1](https://github.com/vitejs/vite/commit/07bd6d1)), closes [#12985](https://github.com/vitejs/vite/issues/12985)
* chore: build time message setting color (#12940) ([ada7cd5](https://github.com/vitejs/vite/commit/ada7cd5)), closes [#12940](https://github.com/vitejs/vite/issues/12940)
* chore: remove extra ) in changelog (#12932) ([e7924d2](https://github.com/vitejs/vite/commit/e7924d2)), closes [#12932](https://github.com/vitejs/vite/issues/12932)
* chore: upgrade rollup (#12965) ([bdb2f25](https://github.com/vitejs/vite/commit/bdb2f25)), closes [#12965](https://github.com/vitejs/vite/issues/12965)
* refactor: resolveExports (#10917) ([ad21ec3](https://github.com/vitejs/vite/commit/ad21ec3)), closes [#10917](https://github.com/vitejs/vite/issues/10917)



## <small>4.3.1 (2023-04-20)</small>

* fix: revert ensure module in graph before transforming (#12774) (#12929) ([9cc93a5](https://github.com/vitejs/vite/commit/9cc93a5)), closes [#12774](https://github.com/vitejs/vite/issues/12774) [#12929](https://github.com/vitejs/vite/issues/12929)
* docs: 4.3 announcement and release notes (#12925) ([f29c582](https://github.com/vitejs/vite/commit/f29c582)), closes [#12925](https://github.com/vitejs/vite/issues/12925)
* chore: clean up 4.3 changelog ([55ec023](https://github.com/vitejs/vite/commit/55ec023))



## 4.3.0 (2023-04-20)

Vite 4.3 is out! Read the [announcement blog post here](https://vitejs.dev/blog/announcing-vite4-3)

[![Vite 4.3, It's Fast](https://vitejs.dev/og-image-announcing-vite4-3.png)](https://vitejs.dev/blog/announcing-vite4-3)

In this minor, we focused on improving the dev server performance. The resolve logic got streamlined, improving hot paths and implementing smarter caching for finding `package.json`, TS config files, and resolved URL in general.

You can read a detailed walkthrough of the performance work done in this blog post by one of Vite Contributors: [How we made Vite 4.3 faaaaster 🚀](https://sun0day.github.io/blog/vite/why-vite4_3-is-faster.html).

This sprint resulted in speed improvements across the board compared to Vite 4.2.

These are the performance improvements as measured by [sapphi-red/performance-compare](https://github.com/sapphi-red/performance-compare), which tests an app with 1000 React Components cold and warm dev server startup time as well as HMR times for a root and a leaf component:

| **Vite (babel)**   |  Vite 4.2 | Vite 4.3 | Improvement  |
| :----------------- | --------: | -------: | -----------: |
| **dev cold start** | 17249.0ms | 5132.4ms |      -70.2%  |
| **dev warm start** |  6027.8ms | 4536.1ms |      -24.7%  |
| **Root HMR**       |    46.8ms |   26.7ms |      -42.9%  |
| **Leaf HMR**       |    27.0ms |   12.9ms |      -52.2%  |

| **Vite (swc)**     |  Vite 4.2 | Vite 4.3 | Improvement  |
| :----------------- | --------: | -------: | -----------: |
| **dev cold start** | 13552.5ms | 3201.0ms |      -76.4%  |
| **dev warm start** |  4625.5ms | 2834.4ms |      -38.7%  |
| **Root HMR**       |    30.5ms |   24.0ms |      -21.3%  |
| **Leaf HMR**       |    16.9ms |   10.0ms |      -40.8%  |

You can read more information about the benchmark [here](https://gist.github.com/sapphi-red/25be97327ee64a3c1dce793444afdf6e)

### Features

* feat: expose `isFileServingAllowed` as public utility (#12894) ([93e095c](https://github.com/vitejs/vite/commit/93e095c)), closes [#12894](https://github.com/vitejs/vite/issues/12894)
* feat: reuse existing style elements in dev (#12678) ([3a41bd8](https://github.com/vitejs/vite/commit/3a41bd8)), closes [#12678](https://github.com/vitejs/vite/issues/12678)
* feat: skip pinging the server when the tab is not shown (#12698) ([bedcd8f](https://github.com/vitejs/vite/commit/bedcd8f)), closes [#12698](https://github.com/vitejs/vite/issues/12698)
* feat(create-vite): use typescript 5.0 in templates (#12481) ([8582e2d](https://github.com/vitejs/vite/commit/8582e2d)), closes [#12481](https://github.com/vitejs/vite/issues/12481)
* feat: use preview server parameter in preview server hook (#11647) ([4c142ea](https://github.com/vitejs/vite/commit/4c142ea)), closes [#11647](https://github.com/vitejs/vite/issues/11647)
* feat(reporter): show gzip info for all compressible files (fix #11288) (#12485) ([03502c8](https://github.com/vitejs/vite/commit/03502c8)), closes [#11288](https://github.com/vitejs/vite/issues/11288) [#12485](https://github.com/vitejs/vite/issues/12485)
* feat(server): allow to import `data:` uris (#12645) ([4886d9f](https://github.com/vitejs/vite/commit/4886d9f)), closes [#12645](https://github.com/vitejs/vite/issues/12645)
* feat: add opus filetype to assets & mime types (#12526) ([63524ba](https://github.com/vitejs/vite/commit/63524ba)), closes [#12526](https://github.com/vitejs/vite/issues/12526)

### Performance

* perf: parallelize await exportsData from depsInfo (#12869) ([ab3a530](https://github.com/vitejs/vite/commit/ab3a530)), closes [#12869](https://github.com/vitejs/vite/issues/12869)
* perf: avoid side effects resolving in dev and in the optimizer/scanner (#12789) ([fb904f9](https://github.com/vitejs/vite/commit/fb904f9)), closes [#12789](https://github.com/vitejs/vite/issues/12789)
* perf: parallelize imports processing in import analysis plugin (#12754) ([037a6c7](https://github.com/vitejs/vite/commit/037a6c7)), closes [#12754](https://github.com/vitejs/vite/issues/12754)
* perf: unresolvedUrlToModule promise cache (#12725) ([80c526e](https://github.com/vitejs/vite/commit/80c526e)), closes [#12725](https://github.com/vitejs/vite/issues/12725)
* perf(resolve): avoid tryFsResolve for /@fs/ paths (#12450) ([3ef8aaa](https://github.com/vitejs/vite/commit/3ef8aaa)), closes [#12450](https://github.com/vitejs/vite/issues/12450)
* perf(resolve): reduce vite client path checks (#12471) ([c49af23](https://github.com/vitejs/vite/commit/c49af23)), closes [#12471](https://github.com/vitejs/vite/issues/12471)
* perf: avoid new URL() in hot path (#12654) ([f4e2fdf](https://github.com/vitejs/vite/commit/f4e2fdf)), closes [#12654](https://github.com/vitejs/vite/issues/12654)
* perf: improve isFileReadable performance (#12397) ([acf3a14](https://github.com/vitejs/vite/commit/acf3a14)), closes [#12397](https://github.com/vitejs/vite/issues/12397)
* perf: module graph url shortcuts (#12635) ([c268cfa](https://github.com/vitejs/vite/commit/c268cfa)), closes [#12635](https://github.com/vitejs/vite/issues/12635)
* perf: reduce runOptimizerIfIdleAfterMs time (#12614) ([d026a65](https://github.com/vitejs/vite/commit/d026a65)), closes [#12614](https://github.com/vitejs/vite/issues/12614)
* perf: shorcircuit resolve in ensure entry from url (#12655) ([82137d6](https://github.com/vitejs/vite/commit/82137d6)), closes [#12655](https://github.com/vitejs/vite/issues/12655)
* perf: skip es-module-lexer if have no dynamic imports (#12732) ([5d07d7c](https://github.com/vitejs/vite/commit/5d07d7c)), closes [#12732](https://github.com/vitejs/vite/issues/12732)
* perf: start preprocessing static imports before updating module graph (#12723) ([c90b46e](https://github.com/vitejs/vite/commit/c90b46e)), closes [#12723](https://github.com/vitejs/vite/issues/12723)
* perf: use package cache for one off resolve (#12744) ([77bf4ef](https://github.com/vitejs/vite/commit/77bf4ef)), closes [#12744](https://github.com/vitejs/vite/issues/12744)
* perf(css): cache lazy import (#12721) ([fedb080](https://github.com/vitejs/vite/commit/fedb080)), closes [#12721](https://github.com/vitejs/vite/issues/12721)
* perf(hmr): keep track of already traversed modules when propagating update (#12658) ([3b912fb](https://github.com/vitejs/vite/commit/3b912fb)), closes [#12658](https://github.com/vitejs/vite/issues/12658)
* perf(moduleGraph): resolve dep urls in parallel (#12619) ([4823fec](https://github.com/vitejs/vite/commit/4823fec)), closes [#12619](https://github.com/vitejs/vite/issues/12619)
* perf(resolve): skip for virtual files (#12638) ([9e13f5f](https://github.com/vitejs/vite/commit/9e13f5f)), closes [#12638](https://github.com/vitejs/vite/issues/12638)
* perf: avoid fsp.unlink if we don't use the promise (#12589) ([19d1980](https://github.com/vitejs/vite/commit/19d1980)), closes [#12589](https://github.com/vitejs/vite/issues/12589)
* perf: back to temporal optimizer dirs (#12622) ([8da0422](https://github.com/vitejs/vite/commit/8da0422)), closes [#12622](https://github.com/vitejs/vite/issues/12622)
* perf: cache `depsCacheDirPrefix` value for `isOptimizedDepFile` (#12601) ([edbd262](https://github.com/vitejs/vite/commit/edbd262)), closes [#12601](https://github.com/vitejs/vite/issues/12601)
* perf: improve cleanUrl util (#12573) ([68d500e](https://github.com/vitejs/vite/commit/68d500e)), closes [#12573](https://github.com/vitejs/vite/issues/12573)
* perf: non-blocking write of optimized dep files (#12603) ([2f5f968](https://github.com/vitejs/vite/commit/2f5f968)), closes [#12603](https://github.com/vitejs/vite/issues/12603)
* perf: try using realpathSync.native in Windows (#12580) ([1cc99f8](https://github.com/vitejs/vite/commit/1cc99f8)), closes [#12580](https://github.com/vitejs/vite/issues/12580)
* perf: use fsp in more cases (#12553) ([e9b92f5](https://github.com/vitejs/vite/commit/e9b92f5)), closes [#12553](https://github.com/vitejs/vite/issues/12553)
* perf(html): apply preTransformRequest for html scripts (#12599) ([420782c](https://github.com/vitejs/vite/commit/420782c)), closes [#12599](https://github.com/vitejs/vite/issues/12599)
* perf(optimizer): bulk optimizer delay (#12609) ([c881971](https://github.com/vitejs/vite/commit/c881971)), closes [#12609](https://github.com/vitejs/vite/issues/12609)
* perf(optimizer): start optimizer early (#12593) ([4f9b8b4](https://github.com/vitejs/vite/commit/4f9b8b4)), closes [#12593](https://github.com/vitejs/vite/issues/12593)
* perf(resolve): avoid isWorkerRequest and clean up .ts imported a .js (#12571) ([8ab1438](https://github.com/vitejs/vite/commit/8ab1438)), closes [#12571](https://github.com/vitejs/vite/issues/12571)
* perf(resolve): findNearestMainPackageData instead of lookupFile (#12576) ([54b376f](https://github.com/vitejs/vite/commit/54b376f)), closes [#12576](https://github.com/vitejs/vite/issues/12576)
* perf(server): only watch .env files in envDir (#12587) ([26d8e72](https://github.com/vitejs/vite/commit/26d8e72)), closes [#12587](https://github.com/vitejs/vite/issues/12587)
* perf: avoid execSync on openBrowser (#12510) ([a2af2f0](https://github.com/vitejs/vite/commit/a2af2f0)), closes [#12510](https://github.com/vitejs/vite/issues/12510)
* perf: extract regex and use Map in data-uri plugin (#12500) ([137e63d](https://github.com/vitejs/vite/commit/137e63d)), closes [#12500](https://github.com/vitejs/vite/issues/12500)
* perf: extract vite:resolve internal functions (#12522) ([6ea4be2](https://github.com/vitejs/vite/commit/6ea4be2)), closes [#12522](https://github.com/vitejs/vite/issues/12522)
* perf: improve package cache usage (#12512) ([abc2b9c](https://github.com/vitejs/vite/commit/abc2b9c)), closes [#12512](https://github.com/vitejs/vite/issues/12512)
* perf: more regex improvements (#12520) ([abf536f](https://github.com/vitejs/vite/commit/abf536f)), closes [#12520](https://github.com/vitejs/vite/issues/12520)
* perf: regex to startsWith/slice in utils (#12532) ([debc6e2](https://github.com/vitejs/vite/commit/debc6e2)), closes [#12532](https://github.com/vitejs/vite/issues/12532)
* perf: remove regex in ImportMetaURL plugins (#12502) ([1030049](https://github.com/vitejs/vite/commit/1030049)), closes [#12502](https://github.com/vitejs/vite/issues/12502)
* perf: replace endsWith with === (#12539) ([7eb52ec](https://github.com/vitejs/vite/commit/7eb52ec)), closes [#12539](https://github.com/vitejs/vite/issues/12539)
* perf: replace startsWith with === (#12531) ([9cce026](https://github.com/vitejs/vite/commit/9cce026)), closes [#12531](https://github.com/vitejs/vite/issues/12531)
* perf: reuse regex in plugins (#12518) ([da43936](https://github.com/vitejs/vite/commit/da43936)), closes [#12518](https://github.com/vitejs/vite/issues/12518)
* perf: use `safeRealpath` in `getRealpath` (#12551) ([cec2320](https://github.com/vitejs/vite/commit/cec2320)), closes [#12551](https://github.com/vitejs/vite/issues/12551)
* perf(css): improve postcss config resolve (#12484) ([58e99b6](https://github.com/vitejs/vite/commit/58e99b6)), closes [#12484](https://github.com/vitejs/vite/issues/12484)
* perf(esbuild): make tsconfck non-blocking (#12548) ([e5cdff7](https://github.com/vitejs/vite/commit/e5cdff7)), closes [#12548](https://github.com/vitejs/vite/issues/12548)
* perf(esbuild): update tsconfck to consume faster find-all implementation (#12541) ([b6ea25a](https://github.com/vitejs/vite/commit/b6ea25a)), closes [#12541](https://github.com/vitejs/vite/issues/12541)
* perf(resolve): fix browser mapping nearest package.json check (#12550) ([eac376e](https://github.com/vitejs/vite/commit/eac376e)), closes [#12550](https://github.com/vitejs/vite/issues/12550)
* perf(resolve): improve package.json resolve speed (#12441) ([1fc8c65](https://github.com/vitejs/vite/commit/1fc8c65)), closes [#12441](https://github.com/vitejs/vite/issues/12441)
* perf(resolve): refactor package.json handling for deep imports (#12461) ([596b661](https://github.com/vitejs/vite/commit/596b661)), closes [#12461](https://github.com/vitejs/vite/issues/12461)
* perf(resolve): refactor tryFsResolve and tryResolveFile (#12542) ([3f70f47](https://github.com/vitejs/vite/commit/3f70f47))
* perf(resolve): skip absolute paths in root as url checks (#12476) ([8d2931b](https://github.com/vitejs/vite/commit/8d2931b)), closes [#12476](https://github.com/vitejs/vite/issues/12476)
* perf(resolve): support # in path only for dependencies (#12469) ([6559fc7](https://github.com/vitejs/vite/commit/6559fc7)), closes [#12469](https://github.com/vitejs/vite/issues/12469)

### Bug Fixes

* fix(build): do not repeatedly output warning message (#12910) ([251d0ab](https://github.com/vitejs/vite/commit/251d0ab)), closes [#12910](https://github.com/vitejs/vite/issues/12910)
* fix: escape msg in render restricted error html (#12889) ([3aa2127](https://github.com/vitejs/vite/commit/3aa2127)), closes [#12889](https://github.com/vitejs/vite/issues/12889)
* fix: yarn pnp considerBuiltins (#12903) ([a0e10d5](https://github.com/vitejs/vite/commit/a0e10d5)), closes [#12903](https://github.com/vitejs/vite/issues/12903)
* fix: broken middleware name (#12871) ([32bef57](https://github.com/vitejs/vite/commit/32bef57)), closes [#12871](https://github.com/vitejs/vite/issues/12871)
* fix: cleanUpStaleCacheDirs once per process (#12847) ([2c58b6e](https://github.com/vitejs/vite/commit/2c58b6e)), closes [#12847](https://github.com/vitejs/vite/issues/12847)
* fix(build): do not warn when URL in CSS is externalized (#12873) ([1510996](https://github.com/vitejs/vite/commit/1510996)), closes [#12873](https://github.com/vitejs/vite/issues/12873)
* fix: build time deps optimization, and ensure single crawl end call (#12851) ([fa30879](https://github.com/vitejs/vite/commit/fa30879)), closes [#12851](https://github.com/vitejs/vite/issues/12851)
* fix: correct vite config temporary name (#12833) ([cdd9c23](https://github.com/vitejs/vite/commit/cdd9c23)), closes [#12833](https://github.com/vitejs/vite/issues/12833)
* fix(importAnalysis): warning on ExportAllDeclaration (#12799) ([5136b9b](https://github.com/vitejs/vite/commit/5136b9b)), closes [#12799](https://github.com/vitejs/vite/issues/12799)
* fix(optimizer): start optimizer after buildStart (#12832) ([cfe75ee](https://github.com/vitejs/vite/commit/cfe75ee)), closes [#12832](https://github.com/vitejs/vite/issues/12832)
* fix: handle try-catch for fs promise when resolve https config (#12808) ([0bba402](https://github.com/vitejs/vite/commit/0bba402)), closes [#12808](https://github.com/vitejs/vite/issues/12808)
* fix(build): correctly handle warning ignore list (#12831) ([8830532](https://github.com/vitejs/vite/commit/8830532)), closes [#12831](https://github.com/vitejs/vite/issues/12831)
* fix(resolve): use different importer check for css imports (#12815) ([d037327](https://github.com/vitejs/vite/commit/d037327)), closes [#12815](https://github.com/vitejs/vite/issues/12815)
* fix: ignore sideEffects for scripts imported from html (#12786) ([f09551f](https://github.com/vitejs/vite/commit/f09551f)), closes [#12786](https://github.com/vitejs/vite/issues/12786)
* fix: warn on build when bundling code that uses nodejs built in module (#12616) ([72050f9](https://github.com/vitejs/vite/commit/72050f9)), closes [#12616](https://github.com/vitejs/vite/issues/12616)
* fix(cli): pass mode to optimize command (#12776) ([da38ad8](https://github.com/vitejs/vite/commit/da38ad8)), closes [#12776](https://github.com/vitejs/vite/issues/12776)
* fix(css): resolve at import from dependency basedir (#12796) ([46bdf7d](https://github.com/vitejs/vite/commit/46bdf7d)), closes [#12796](https://github.com/vitejs/vite/issues/12796)
* fix(worker): asset in iife worker and relative base (#12697) ([ddefc06](https://github.com/vitejs/vite/commit/ddefc06)), closes [#12697](https://github.com/vitejs/vite/issues/12697)
* fix(worker): return null for shouldTransformCachedModule (#12797) ([ea5f6fc](https://github.com/vitejs/vite/commit/ea5f6fc)), closes [#12797](https://github.com/vitejs/vite/issues/12797)
* fix: allow onwarn to override vite default warning handling (#12757) ([f736930](https://github.com/vitejs/vite/commit/f736930)), closes [#12757](https://github.com/vitejs/vite/issues/12757)
* fix: ensure module in graph before transforming (#12774) ([44ad321](https://github.com/vitejs/vite/commit/44ad321)), closes [#12774](https://github.com/vitejs/vite/issues/12774)
* fix: update package cache watcher (#12772) ([a78588f](https://github.com/vitejs/vite/commit/a78588f)), closes [#12772](https://github.com/vitejs/vite/issues/12772)
* fix: avoid clean up while committing deps folder (#12722) ([3f4d109](https://github.com/vitejs/vite/commit/3f4d109)), closes [#12722](https://github.com/vitejs/vite/issues/12722)
* fix: ignore pnp resolve error (#12719) ([2d30ae5](https://github.com/vitejs/vite/commit/2d30ae5)), closes [#12719](https://github.com/vitejs/vite/issues/12719)
* fix: leave fully dynamic import.meta.url asset (fixes #10306) (#10549) ([56802b1](https://github.com/vitejs/vite/commit/56802b1)), closes [#10306](https://github.com/vitejs/vite/issues/10306) [#10549](https://github.com/vitejs/vite/issues/10549)
* fix: output combined sourcemap in importAnalysisBuild plugin (#12642) ([d051639](https://github.com/vitejs/vite/commit/d051639)), closes [#12642](https://github.com/vitejs/vite/issues/12642)
* fix: take in relative assets path fixes from rollup (#12695) ([81e44dd](https://github.com/vitejs/vite/commit/81e44dd)), closes [#12695](https://github.com/vitejs/vite/issues/12695)
* fix: throws error when plugin tries to resolve ID to external URL (#11731) ([49674b5](https://github.com/vitejs/vite/commit/49674b5)), closes [#11731](https://github.com/vitejs/vite/issues/11731)
* fix(css): css file emit synchronously (#12558) ([8e30025](https://github.com/vitejs/vite/commit/8e30025)), closes [#12558](https://github.com/vitejs/vite/issues/12558)
* fix(import-analysis): escape quotes correctly (#12688) ([1638ebd](https://github.com/vitejs/vite/commit/1638ebd)), closes [#12688](https://github.com/vitejs/vite/issues/12688)
* fix(optimizer): load the correct lock file (#12700) ([889eebe](https://github.com/vitejs/vite/commit/889eebe)), closes [#12700](https://github.com/vitejs/vite/issues/12700)
* fix(server): delay ws server listen when restart (#12734) ([abe9274](https://github.com/vitejs/vite/commit/abe9274)), closes [#12734](https://github.com/vitejs/vite/issues/12734)
* fix(ssr): load sourcemaps alongside modules (#11780) ([be95050](https://github.com/vitejs/vite/commit/be95050)), closes [#11780](https://github.com/vitejs/vite/issues/11780)
* fix(ssr): show ssr module loader error stack (#12651) ([050c0f9](https://github.com/vitejs/vite/commit/050c0f9)), closes [#12651](https://github.com/vitejs/vite/issues/12651)
* fix(worker): disable manifest plugins in worker build (#12661) ([20b8ef4](https://github.com/vitejs/vite/commit/20b8ef4)), closes [#12661](https://github.com/vitejs/vite/issues/12661)
* fix(worker): worker import.meta.url should not depends on document in iife mode (#12629) ([65f5ed2](https://github.com/vitejs/vite/commit/65f5ed2)), closes [#12629](https://github.com/vitejs/vite/issues/12629)
* fix: avoid temporal optimize deps dirs (#12582) ([ff92f2f](https://github.com/vitejs/vite/commit/ff92f2f)), closes [#12582](https://github.com/vitejs/vite/issues/12582)
* fix: await `buildStart` before server start (#12647) ([871d353](https://github.com/vitejs/vite/commit/871d353)), closes [#12647](https://github.com/vitejs/vite/issues/12647)
* fix: call `buildStart` only once when using next port (#12624) ([e10c6bd](https://github.com/vitejs/vite/commit/e10c6bd)), closes [#12624](https://github.com/vitejs/vite/issues/12624)
* fix: sourcemapIgnoreList for optimizedDeps (#12633) ([c1d3fc9](https://github.com/vitejs/vite/commit/c1d3fc9)), closes [#12633](https://github.com/vitejs/vite/issues/12633)
* fix: splitFileAndPostfix works as cleanUrl (#12572) ([276725f](https://github.com/vitejs/vite/commit/276725f)), closes [#12572](https://github.com/vitejs/vite/issues/12572)
* fix: throw error on build optimizeDeps issue (#12560) ([02a46d7](https://github.com/vitejs/vite/commit/02a46d7)), closes [#12560](https://github.com/vitejs/vite/issues/12560)
* fix: use nearest pkg to resolved for moduleSideEffects (#12628) ([1dfecc8](https://github.com/vitejs/vite/commit/1dfecc8)), closes [#12628](https://github.com/vitejs/vite/issues/12628)
* fix(css): use `charset: 'utf8'` by default for css (#12565) ([c20a064](https://github.com/vitejs/vite/commit/c20a064)), closes [#12565](https://github.com/vitejs/vite/issues/12565)
* fix(html): dont pretransform public scripts (#12650) ([4f0af3f](https://github.com/vitejs/vite/commit/4f0af3f)), closes [#12650](https://github.com/vitejs/vite/issues/12650)
* fix: avoid crash because of no access permission (#12552) ([eea1682](https://github.com/vitejs/vite/commit/eea1682)), closes [#12552](https://github.com/vitejs/vite/issues/12552)
* fix: esbuild complains with extra fields (#12516) ([7be0ba5](https://github.com/vitejs/vite/commit/7be0ba5)), closes [#12516](https://github.com/vitejs/vite/issues/12516)
* fix: escape replacements in clientInjections (#12486) ([3765067](https://github.com/vitejs/vite/commit/3765067)), closes [#12486](https://github.com/vitejs/vite/issues/12486)
* fix: open browser reuse logic (#12535) ([04d14af](https://github.com/vitejs/vite/commit/04d14af)), closes [#12535](https://github.com/vitejs/vite/issues/12535)
* fix: prevent error on not set location href (#12494) ([2fb8527](https://github.com/vitejs/vite/commit/2fb8527)), closes [#12494](https://github.com/vitejs/vite/issues/12494)
* fix: simplify prettyUrl (#12488) ([ebe5aa5](https://github.com/vitejs/vite/commit/ebe5aa5)), closes [#12488](https://github.com/vitejs/vite/issues/12488)
* fix(config): add random number to temp transpiled file (#12150) ([2b2ba61](https://github.com/vitejs/vite/commit/2b2ba61)), closes [#12150](https://github.com/vitejs/vite/issues/12150)
* fix(deps): update all non-major dependencies (#12389) ([3e60b77](https://github.com/vitejs/vite/commit/3e60b77)), closes [#12389](https://github.com/vitejs/vite/issues/12389)
* fix(html): public asset urls always being treated as paths (fix #11857) (#11870) ([46d1352](https://github.com/vitejs/vite/commit/46d1352)), closes [#11857](https://github.com/vitejs/vite/issues/11857) [#11870](https://github.com/vitejs/vite/issues/11870)
* fix(ssr): hoist import statements to the top (#12274) ([33baff5](https://github.com/vitejs/vite/commit/33baff5)), closes [#12274](https://github.com/vitejs/vite/issues/12274)
* fix(ssr): hoist re-exports with imports (#12530) ([45549e4](https://github.com/vitejs/vite/commit/45549e4)), closes [#12530](https://github.com/vitejs/vite/issues/12530)
* fix: should generate Hi-res sourcemap for dev (#12501) ([1502617](https://github.com/vitejs/vite/commit/1502617)), closes [#12501](https://github.com/vitejs/vite/issues/12501)


### Clean up

* refactor: simplify crawlEndFinder (#12868) ([31f8b51](https://github.com/vitejs/vite/commit/31f8b51)), closes [#12868](https://github.com/vitejs/vite/issues/12868)
* refactor: use simpler resolve for nested optimized deps (#12770) ([d202588](https://github.com/vitejs/vite/commit/d202588)), closes [#12770](https://github.com/vitejs/vite/issues/12770)
* refactor: `import.meta.url` condition from renderChunk hook of worker plugin (#12696) ([fdef8fd](https://github.com/vitejs/vite/commit/fdef8fd)), closes [#12696](https://github.com/vitejs/vite/issues/12696)
* refactor: clean up preTransformRequest (#12672) ([561227c](https://github.com/vitejs/vite/commit/561227c)), closes [#12672](https://github.com/vitejs/vite/issues/12672)
* refactor: make debugger nullable (#12687) ([89e4977](https://github.com/vitejs/vite/commit/89e4977)), closes [#12687](https://github.com/vitejs/vite/issues/12687)
* refactor: remove `ensureVolumeInPath` (#12690) ([a3150ee](https://github.com/vitejs/vite/commit/a3150ee)), closes [#12690](https://github.com/vitejs/vite/issues/12690)
* refactor: remove unused exports data props (#12740) ([4538bfe](https://github.com/vitejs/vite/commit/4538bfe)), closes [#12740](https://github.com/vitejs/vite/issues/12740)
* refactor: use `resolvePackageData` in `requireResolveFromRootWithFallback` (#12712) ([1ea38e2](https://github.com/vitejs/vite/commit/1ea38e2)), closes [#12712](https://github.com/vitejs/vite/issues/12712)
* refactor(css): simplify cached import code (#12730) ([0646754](https://github.com/vitejs/vite/commit/0646754)), closes [#12730](https://github.com/vitejs/vite/issues/12730)
* refactor: improve scanner logs (#12578) ([9925a72](https://github.com/vitejs/vite/commit/9925a72)), closes [#12578](https://github.com/vitejs/vite/issues/12578)
* refactor: isInNodeModules util (#12588) ([fb3245a](https://github.com/vitejs/vite/commit/fb3245a)), closes [#12588](https://github.com/vitejs/vite/issues/12588)
* refactor: remove `idToPkgMap` (#12564) ([a326ec8](https://github.com/vitejs/vite/commit/a326ec8)), closes [#12564](https://github.com/vitejs/vite/issues/12564)
* refactor: simplify lookupFile (#12585) ([4215e22](https://github.com/vitejs/vite/commit/4215e22)), closes [#12585](https://github.com/vitejs/vite/issues/12585)
* refactor: tryStatSync as util (#12575) ([92601db](https://github.com/vitejs/vite/commit/92601db)), closes [#12575](https://github.com/vitejs/vite/issues/12575)
* refactor: use findNearestPackageData in more places (#12577) ([35faae9](https://github.com/vitejs/vite/commit/35faae9)), closes [#12577](https://github.com/vitejs/vite/issues/12577)
* refactor: esbuild plugin config logic (#12493) ([45b5b0f](https://github.com/vitejs/vite/commit/45b5b0f)), closes [#12493](https://github.com/vitejs/vite/issues/12493)


### Previous Changelogs


#### [4.3.0-beta.8](https://github.com/vitejs/vite/compare/v4.3.0-beta.7...v4.3.0-beta.8) (2023-04-19)

See [4.3.0-beta.8 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.8/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.7](https://github.com/vitejs/vite/compare/v4.3.0-beta.6...v4.3.0-beta.7) (2023-04-17)

See [4.3.0-beta.7 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.7/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.6](https://github.com/vitejs/vite/compare/v4.3.0-beta.5...v4.3.0-beta.6) (2023-04-14)

See [4.3.0-beta.6 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.6/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.5](https://github.com/vitejs/vite/compare/v4.3.0-beta.4...v4.3.0-beta.5) (2023-04-11)

See [4.3.0-beta.5 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.5/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.4](https://github.com/vitejs/vite/compare/v4.3.0-beta.3...v4.3.0-beta.4) (2023-04-09)

See [4.3.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.4/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.3](https://github.com/vitejs/vite/compare/v4.3.0-beta.2...v4.3.0-beta.3) (2023-04-07)

See [4.3.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.3/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.2](https://github.com/vitejs/vite/compare/v4.3.0-beta.1...v4.3.0-beta.2) (2023-04-05)

See [4.3.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.2/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.1](https://github.com/vitejs/vite/compare/v4.3.0-beta.0...v4.3.0-beta.1) (2023-03-29)

See [4.3.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.1/packages/vite/CHANGELOG.md)


#### [4.3.0-beta.0](https://github.com/vitejs/vite/compare/v4.2.1...v4.3.0-beta.0) (2023-03-23)

See [4.3.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v4.3.0-beta.0/packages/vite/CHANGELOG.md)


## <small>4.2.2 (2023-04-18)</small>

* fix: escape msg in render restricted error html, backport #12889 ([8758c5c](https://github.com/vitejs/vite/commit/8758c5c)), closes [#12889](https://github.com/vitejs/vite/issues/12889)



## <small>4.2.1 (2023-03-20)</small>

* fix: add `virtual:` to virtual module source map ignore (#12444) ([c4aa28f](https://github.com/vitejs/vite/commit/c4aa28f)), closes [#12444](https://github.com/vitejs/vite/issues/12444)
* fix(css): inject source content conditionally (#12449) ([3e665f6](https://github.com/vitejs/vite/commit/3e665f6)), closes [#12449](https://github.com/vitejs/vite/issues/12449)
* fix(worker): using data URLs for inline shared worker (#12014) ([79a5007](https://github.com/vitejs/vite/commit/79a5007)), closes [#12014](https://github.com/vitejs/vite/issues/12014)
* chore: changelog edits for 4.2 (#12438) ([ce047e3](https://github.com/vitejs/vite/commit/ce047e3)), closes [#12438](https://github.com/vitejs/vite/issues/12438)



## 4.2.0 (2023-03-16)

Vite 4.2 is out!

### Support env variables replacement in HTML files

Vite now supports [replacing env variables in HTML files](https://vitejs.dev/guide/env-and-mode.html#html-env-replacement). Any properties in `import.meta.env` can be used in HTML files with a special `%ENV_NAME%` syntax:

```html
<h1>Vite is running in %MODE%</h1>
<p>Using data from %VITE_API_URL%</p>
```

### Sourcemaps improvements

The Chrome Dev Tools team has been working to improve the DX of Vite and Vite-powered frameworks in the dev tools. Vite 4.2 brings an [improved experience](https://twitter.com/bmeurer/status/1631286267823439881) and tools for framework authors to [hide 3rd party code and build artifacts from the user](https://twitter.com/bmeurer/status/1631531492462526467) from console log traces using [`server.sourcemapIgnoreList`](https://vitejs.dev/config/server-options.html#server-sourcemapignorelist) and [`build.rollupOptions.output.sourcemapIgnoreList`](https://rollupjs.org/configuration-options/#output-sourcemapignorelist).

### ESM subpath imports

Vite 4.2 now supports [subpath imports](https://nodejs.org/api/packages.html#subpath-imports), thanks to [@lukeed05](https://twitter.com/lukeed05)'s [resolve.exports](https://github.com/lukeed/resolve.exports) library.

### TypeScript 5 support

Vite 4.2 also supports TypeScript 5's `tsconfig` `extends` [array format](https://devblogs.microsoft.com/typescript/announcing-typescript-5-0-beta/#supporting-multiple-configuration-files-in-extends), thanks to [tsconfck](https://github.com/dominikg/tsconfck).


### esbuild 0.17

esbuild [v0.17.0](https://github.com/evanw/esbuild/releases/tag/v0.17.0) improved the design of its incremental, watch, and serve APIs. Check out [#11908](https://github.com/vitejs/vite/pull/11908) for the rationale of why we didn't consider the backward-incompatible changes breaking for our use cases. The updated esbuild design now allows Vite to properly cancel in-fly builds and improve server restarts.


### Use Rollup types from the vite package

Expose Rollup types as a namespace. This is helpful to avoid type conflicts because of different versions of Rollup types in environments like [vite-ecosystem-ci](https://github.com/vitejs/vite-ecosystem-ci) ([#12316](https://github.com/vitejs/vite/issues/12316)).

```ts
import type { Rollup } from 'vite'
```


### Português Docs Translation

The Vite documentation is now translated to Português at [pt.vitejs.dev](https://pt.vitejs.dev) thanks to [Nazaré Da Piedade](https://twitter.com/nazarepiedady) .


### Features

* feat: add status message for 504 caused by optimizer (#12435) ([5cdd3fa](https://github.com/vitejs/vite/commit/5cdd3fa)), closes [#12435](https://github.com/vitejs/vite/issues/12435)
* feat: update tsconfck to 2.1.0 to add support for typescript 5 config syntax (#12401) ([3f1c379](https://github.com/vitejs/vite/commit/3f1c379)), closes [#12401](https://github.com/vitejs/vite/issues/12401)
* feat: default esbuild jsxDev based on config.isProduction (#12386) ([f24c2b0](https://github.com/vitejs/vite/commit/f24c2b0)), closes [#12386](https://github.com/vitejs/vite/issues/12386)
* feat(css): add `build.cssMinify` (#12207) ([90431f2](https://github.com/vitejs/vite/commit/90431f2)), closes [#12207](https://github.com/vitejs/vite/issues/12207)
* feat(types): export Rollup namespace (#12316) ([6e49e52](https://github.com/vitejs/vite/commit/6e49e52)), closes [#12316](https://github.com/vitejs/vite/issues/12316)
* feat: add `sourcemapIgnoreList` configuration option (#12174) ([f875580](https://github.com/vitejs/vite/commit/f875580)), closes [#12174](https://github.com/vitejs/vite/issues/12174)
* feat: cancellable scan during optimization (#12225) ([1e1cd3b](https://github.com/vitejs/vite/commit/1e1cd3b)), closes [#12225](https://github.com/vitejs/vite/issues/12225)
* feat: don't override `build.target` if terser is 5.16.0+ (#12197) ([9885f6f](https://github.com/vitejs/vite/commit/9885f6f)), closes [#12197](https://github.com/vitejs/vite/issues/12197)
* feat: support ESM subpath imports (#7770) ([cc92da9](https://github.com/vitejs/vite/commit/cc92da9)), closes [#7770](https://github.com/vitejs/vite/issues/7770)
* feat(css): add preprocessor option to define stylus vars & funcs (#7227) ([5968bec](https://github.com/vitejs/vite/commit/5968bec)), closes [#7227](https://github.com/vitejs/vite/issues/7227)
* feat(css): support resolving stylesheets from exports map (#7817) ([108aadf](https://github.com/vitejs/vite/commit/108aadf)), closes [#7817](https://github.com/vitejs/vite/issues/7817)
* feat(html): support env replacement (#12202) ([4f2c49f](https://github.com/vitejs/vite/commit/4f2c49f)), closes [#12202](https://github.com/vitejs/vite/issues/12202)
* refactor: customize ErrorOverlay (part 2) (#11830) ([4159e6f](https://github.com/vitejs/vite/commit/4159e6f)), closes [#11830](https://github.com/vitejs/vite/issues/11830)
* refactor: remove constructed sheet type style injection (#11818) ([1a6a0c2](https://github.com/vitejs/vite/commit/1a6a0c2)), closes [#11818](https://github.com/vitejs/vite/issues/11818)
* refactor(importAnalysis): cache injected env string (#12154) ([2aad552](https://github.com/vitejs/vite/commit/2aad552)), closes [#12154](https://github.com/vitejs/vite/issues/12154)
* feat: esbuild 0.17 (#11908) ([9d42f06](https://github.com/vitejs/vite/commit/9d42f06)), closes [#11908](https://github.com/vitejs/vite/issues/11908)
* feat: ignore list client injected sources (#12170) ([8a98aef](https://github.com/vitejs/vite/commit/8a98aef)), closes [#12170](https://github.com/vitejs/vite/issues/12170)
* feat: support rollup plugin `this.load` in plugin container context (#11469) ([abfa804](https://github.com/vitejs/vite/commit/abfa804)), closes [#11469](https://github.com/vitejs/vite/issues/11469)
* feat(cli): allow to specify sourcemap mode via --sourcemap build's option (#11505) ([ee3b90a](https://github.com/vitejs/vite/commit/ee3b90a)), closes [#11505](https://github.com/vitejs/vite/issues/11505)
* feat(reporter): report built time (#12100) ([f2ad222](https://github.com/vitejs/vite/commit/f2ad222)), closes [#12100](https://github.com/vitejs/vite/issues/12100)


### Bug Fixes

* fix: html env replacement plugin position (#12404) ([96f36a9](https://github.com/vitejs/vite/commit/96f36a9)), closes [#12404](https://github.com/vitejs/vite/issues/12404)
* fix(optimizer): # symbol in deps id stripped by browser (#12415) ([e23f690](https://github.com/vitejs/vite/commit/e23f690)), closes [#12415](https://github.com/vitejs/vite/issues/12415)
* fix(resolve): rebase sub imports relative path (#12373) ([fe1d61a](https://github.com/vitejs/vite/commit/fe1d61a)), closes [#12373](https://github.com/vitejs/vite/issues/12373)
* fix(server): should close server after create new server (#12379) ([d23605d](https://github.com/vitejs/vite/commit/d23605d)), closes [#12379](https://github.com/vitejs/vite/issues/12379)
* fix(resolve): remove deep import syntax handling (#12381) ([42e0d6a](https://github.com/vitejs/vite/commit/42e0d6a)), closes [#12381](https://github.com/vitejs/vite/issues/12381)
* fix: print urls when dns order change (#12261) ([e57cacf](https://github.com/vitejs/vite/commit/e57cacf)), closes [#12261](https://github.com/vitejs/vite/issues/12261)
* fix: throw ssr import error directly (fix #12322) (#12324) ([21ffc6a](https://github.com/vitejs/vite/commit/21ffc6a)), closes [#12322](https://github.com/vitejs/vite/issues/12322) [#12324](https://github.com/vitejs/vite/issues/12324)
* fix(config): watch config even outside of root (#12321) ([7e2fff7](https://github.com/vitejs/vite/commit/7e2fff7)), closes [#12321](https://github.com/vitejs/vite/issues/12321)
* fix(config): watch envDir even outside of root (#12349) ([131f3ee](https://github.com/vitejs/vite/commit/131f3ee)), closes [#12349](https://github.com/vitejs/vite/issues/12349)
* fix(define): correctly replace SSR in dev (#12204) ([0f6de4d](https://github.com/vitejs/vite/commit/0f6de4d)), closes [#12204](https://github.com/vitejs/vite/issues/12204)
* fix(optimizer): suppress esbuild cancel error (#12358) ([86a24e4](https://github.com/vitejs/vite/commit/86a24e4)), closes [#12358](https://github.com/vitejs/vite/issues/12358)
* fix(optimizer): transform css require to import directly (#12343) ([716286e](https://github.com/vitejs/vite/commit/716286e)), closes [#12343](https://github.com/vitejs/vite/issues/12343)
* fix(reporter): build.assetsDir should not impact output when in lib mode (#12108) ([b12f457](https://github.com/vitejs/vite/commit/b12f457)), closes [#12108](https://github.com/vitejs/vite/issues/12108)
* fix(types): avoid resolve.exports types for bundling (#12346) ([6b40f03](https://github.com/vitejs/vite/commit/6b40f03)), closes [#12346](https://github.com/vitejs/vite/issues/12346)
* fix(worker): force rollup to build worker module under watch mode (#11919) ([d464679](https://github.com/vitejs/vite/commit/d464679)), closes [#11919](https://github.com/vitejs/vite/issues/11919)
* fix:  resolve browser mapping using bare imports (fix #11208) (#11219) ([22de84f](https://github.com/vitejs/vite/commit/22de84f)), closes [#11208](https://github.com/vitejs/vite/issues/11208) [#11219](https://github.com/vitejs/vite/issues/11219)
* fix: avoid null sourcePath in `server.sourcemapIgnoreList` (#12251) ([209c3bd](https://github.com/vitejs/vite/commit/209c3bd)), closes [#12251](https://github.com/vitejs/vite/issues/12251)
* fix: configure proxy before subscribing to error events (#12263) ([c35e100](https://github.com/vitejs/vite/commit/c35e100)), closes [#12263](https://github.com/vitejs/vite/issues/12263)
* fix: enforce absolute path for server.sourcemapIgnoreList (#12309) ([ab6ae07](https://github.com/vitejs/vite/commit/ab6ae07)), closes [#12309](https://github.com/vitejs/vite/issues/12309)
* fix: handle error without line and column in loc (#12312) ([ce18eba](https://github.com/vitejs/vite/commit/ce18eba)), closes [#12312](https://github.com/vitejs/vite/issues/12312)
* fix: properly clean up optimization temp folder (#12237) ([fbbf8fe](https://github.com/vitejs/vite/commit/fbbf8fe)), closes [#12237](https://github.com/vitejs/vite/issues/12237)
* fix: unique dep optimizer temp folders (#12252) ([38ce81c](https://github.com/vitejs/vite/commit/38ce81c)), closes [#12252](https://github.com/vitejs/vite/issues/12252)
* fix(build-import-analysis): should not append ?used when css request has ?url or ?raw (#11910) ([e3f725f](https://github.com/vitejs/vite/commit/e3f725f)), closes [#11910](https://github.com/vitejs/vite/issues/11910)
* fix(optimizer): don not call context.rebuild after cancel (#12264) ([520d84e](https://github.com/vitejs/vite/commit/520d84e)), closes [#12264](https://github.com/vitejs/vite/issues/12264)
* fix(resolve): update `resolve.exports` to `2.0.1` to fix `*` resolution issue (#12314) ([523d6f7](https://github.com/vitejs/vite/commit/523d6f7)), closes [#12314](https://github.com/vitejs/vite/issues/12314)
* fix: use relative paths in `sources` for transformed source maps (#12079) ([bcbc582](https://github.com/vitejs/vite/commit/bcbc582)), closes [#12079](https://github.com/vitejs/vite/issues/12079)
* fix(cli): after setting server.open, the default open is inconsistent… (#11974) ([33a38db](https://github.com/vitejs/vite/commit/33a38db)), closes [#11974](https://github.com/vitejs/vite/issues/11974)
* fix(client-inject): replace globalThis.process.env.NODE_ENV (fix #12185) (#12194) ([2063648](https://github.com/vitejs/vite/commit/2063648)), closes [#12185](https://github.com/vitejs/vite/issues/12185) [#12194](https://github.com/vitejs/vite/issues/12194)
* fix(css): should not rebase http url for less (fix: #12155) (#12195) ([9cca30d](https://github.com/vitejs/vite/commit/9cca30d)), closes [#12155](https://github.com/vitejs/vite/issues/12155) [#12195](https://github.com/vitejs/vite/issues/12195)
* fix(deps): update all non-major dependencies (#12036) ([48150f2](https://github.com/vitejs/vite/commit/48150f2)), closes [#12036](https://github.com/vitejs/vite/issues/12036)
* fix(import-analysis): improve error for jsx to not be preserve in tsconfig (#12018) ([91fac1c](https://github.com/vitejs/vite/commit/91fac1c)), closes [#12018](https://github.com/vitejs/vite/issues/12018)
* fix(optimizer): log esbuild error when scanning deps (#11977) ([20e6060](https://github.com/vitejs/vite/commit/20e6060)), closes [#11977](https://github.com/vitejs/vite/issues/11977)
* fix(optimizer): log unoptimizable entries (#12138) ([2c93e0b](https://github.com/vitejs/vite/commit/2c93e0b)), closes [#12138](https://github.com/vitejs/vite/issues/12138)
* fix(server): watch env files creating and deleting (fix #12127) (#12129) ([cc3724f](https://github.com/vitejs/vite/commit/cc3724f)), closes [#12127](https://github.com/vitejs/vite/issues/12127) [#12129](https://github.com/vitejs/vite/issues/12129)
* build: correct d.ts output dir in development (#12212) ([b90bc1f](https://github.com/vitejs/vite/commit/b90bc1f)), closes [#12212](https://github.com/vitejs/vite/issues/12212)


### Previous Changelogs


#### [4.2.0-beta.2](https://github.com/vitejs/vite/compare/v4.2.0-beta.1...v4.2.0-beta.2) (2023-03-13)

See [4.2.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v4.2.0-beta.2/packages/vite/CHANGELOG.md)


#### [4.2.0-beta.1](https://github.com/vitejs/vite/compare/v4.2.0-beta.0...v4.2.0-beta.1) (2023-03-07)

See [4.2.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v4.2.0-beta.1/packages/vite/CHANGELOG.md)


#### [4.2.0-beta.0](https://github.com/vitejs/vite/compare/v4.1.4...v4.2.0-beta.0) (2023-02-27)

See [4.2.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v4.2.0-beta.0/packages/vite/CHANGELOG.md)



## <small>4.1.4 (2023-02-21)</small>

* fix(define): should not stringify vite internal env (#12120) ([73c3999](https://github.com/vitejs/vite/commit/73c3999)), closes [#12120](https://github.com/vitejs/vite/issues/12120)
* docs: update rollup docs links (#12130) ([439a73f](https://github.com/vitejs/vite/commit/439a73f)), closes [#12130](https://github.com/vitejs/vite/issues/12130)



## <small>4.1.3 (2023-02-20)</small>

* fix: catch and handle websocket error (#11991) (#12007) ([4b5cc9f](https://github.com/vitejs/vite/commit/4b5cc9f)), closes [#11991](https://github.com/vitejs/vite/issues/11991) [#12007](https://github.com/vitejs/vite/issues/12007)
* fix: do not append version query param when scanning for dependencies (#11961) ([575bcf6](https://github.com/vitejs/vite/commit/575bcf6)), closes [#11961](https://github.com/vitejs/vite/issues/11961)
* fix(css): handle pure css chunk heuristic with special queries (#12091) ([a873af5](https://github.com/vitejs/vite/commit/a873af5)), closes [#12091](https://github.com/vitejs/vite/issues/12091)
* fix(esbuild): umd helper insert into wrong position in lib mode (#11988) ([86bc243](https://github.com/vitejs/vite/commit/86bc243)), closes [#11988](https://github.com/vitejs/vite/issues/11988)
* fix(html): respect disable modulepreload (#12111) ([6c50119](https://github.com/vitejs/vite/commit/6c50119)), closes [#12111](https://github.com/vitejs/vite/issues/12111)
* fix(html): rewrite assets url in `<noscript>` (#11764) ([1dba285](https://github.com/vitejs/vite/commit/1dba285)), closes [#11764](https://github.com/vitejs/vite/issues/11764)
* feat(preview): improve error when build output missing (#12096) ([a0702a1](https://github.com/vitejs/vite/commit/a0702a1)), closes [#12096](https://github.com/vitejs/vite/issues/12096)
* feat(ssr): add importer path to error msg when invalid url import occur (#11606) ([70729c0](https://github.com/vitejs/vite/commit/70729c0)), closes [#11606](https://github.com/vitejs/vite/issues/11606)



## <small>4.1.2 (2023-02-17)</small>

* fix: correct access to `crossOrigin` attribute (#12023) ([6a0d356](https://github.com/vitejs/vite/commit/6a0d356)), closes [#12023](https://github.com/vitejs/vite/issues/12023)
* fix: narrow defineConfig return type (#12021) ([18fa8f0](https://github.com/vitejs/vite/commit/18fa8f0)), closes [#12021](https://github.com/vitejs/vite/issues/12021)
* fix(define): inconsistent env values in build mode (#12058) ([0a50c59](https://github.com/vitejs/vite/commit/0a50c59)), closes [#12058](https://github.com/vitejs/vite/issues/12058)
* fix(env): compatible with env variables ended with unescaped $ (#12031) ([05b3df0](https://github.com/vitejs/vite/commit/05b3df0)), closes [#12031](https://github.com/vitejs/vite/issues/12031)
* fix(ssr): print file url in `ssrTransform` parse error (#12060) ([19f39f7](https://github.com/vitejs/vite/commit/19f39f7)), closes [#12060](https://github.com/vitejs/vite/issues/12060)
* revert: narrow defineConfig return type (#12077) ([54d511e](https://github.com/vitejs/vite/commit/54d511e)), closes [#12077](https://github.com/vitejs/vite/issues/12077)
* feat: support `import.meta.hot?.accept` (#12053) ([081c27f](https://github.com/vitejs/vite/commit/081c27f)), closes [#12053](https://github.com/vitejs/vite/issues/12053)
* chore: add jsdoc default value (#11746) ([8c87af7](https://github.com/vitejs/vite/commit/8c87af7)), closes [#11746](https://github.com/vitejs/vite/issues/11746)
* chore: fix typos (#12032) ([ee1a686](https://github.com/vitejs/vite/commit/ee1a686)), closes [#12032](https://github.com/vitejs/vite/issues/12032)
* chore(deps): update dependency strip-literal to v1 (#12044) ([5bd6c0a](https://github.com/vitejs/vite/commit/5bd6c0a)), closes [#12044](https://github.com/vitejs/vite/issues/12044)
* chore(pluginContainer): simplify error position judge condition (#12003) ([e3ef9f4](https://github.com/vitejs/vite/commit/e3ef9f4)), closes [#12003](https://github.com/vitejs/vite/issues/12003)



## <small>4.1.1 (2023-02-02)</small>

* chore: 4.1.0 changelog cleanup (#11900) ([7747d32](https://github.com/vitejs/vite/commit/7747d32)), closes [#11900](https://github.com/vitejs/vite/issues/11900)
* fix: catch statSync error (#11907) ([f80b9a2](https://github.com/vitejs/vite/commit/f80b9a2)), closes [#11907](https://github.com/vitejs/vite/issues/11907)



## 4.1.0 (2023-02-02)

Vite 4.1 updates to the latest versions of Rollup and esbuild. Check out the new [Rollup docs](https://rollupjs.org/), that are now powered by VitePress making the navigation between Vite and Rollup docs easier for users.

[Vite docs](https://vitejs.dev) got a theme update migrating to the latest version of VitePress.

As part of [Vite 4](https://vitejs.dev/blog/announcing-vite4.html), the Vue and React plugins have been extracted out of the monorepo. Although their release cycle will no longer follow Vite releases moving forward, Vite 4.1 is released in parallel with new versions of [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/releases/tag/plugin-react%403.1.0) and [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc/releases/tag/v3.1.0). @vitejs/plugin-react 3.1.0 reworks the way HMR is handled fixing many edge cases and @vitejs/plugin-react-swc 3.1.0 adds support for SWC plugins.

There is also a new major for [@vitejs/plugin-legacy](https://github.com/vitejs/vite/blob/main/packages/plugin-legacy), see [changelog for v4.0.0](https://github.com/vitejs/vite/blob/main/packages/plugin-legacy/CHANGELOG.md#400-2023-02-02). This version contains breaking changes:
- Support browserslist and update default target ([#11318](https://github.com/vitejs/vite/pull/11318)). See [updated `targets` default](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy#targets).
- Bump modern target to support async generator ([#11896](https://github.com/vitejs/vite/pull/11896)). Learn more at [the browsers support docs](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy#browsers-that-supports-esm-but-does-not-support-widely-available-features).

### Features

* feat: add experimental option to skip SSR transform (#11411) ([e781ef3](https://github.com/vitejs/vite/commit/e781ef3)), closes [#11411](https://github.com/vitejs/vite/issues/11411)
* feat: reproducible manifest (#11542) ([efc8979](https://github.com/vitejs/vite/commit/efc8979)), closes [#11542](https://github.com/vitejs/vite/issues/11542)
* feat: support BROWSER and BROWSER_ARGS in env file (#11513) ([8972868](https://github.com/vitejs/vite/commit/8972868)), closes [#11513](https://github.com/vitejs/vite/issues/11513)
* feat(cli): clear console by pressing c (#11493) (#11494) ([1ae018f](https://github.com/vitejs/vite/commit/1ae018f)), closes [#11493](https://github.com/vitejs/vite/issues/11493) [#11494](https://github.com/vitejs/vite/issues/11494)
* perf(build): disable rollup cache for builds (#11454) ([580ba7a](https://github.com/vitejs/vite/commit/580ba7a)), closes [#11454](https://github.com/vitejs/vite/issues/11454)
* perf(resolve): improve file existence check (#11436) ([4a12b89](https://github.com/vitejs/vite/commit/4a12b89)), closes [#11436](https://github.com/vitejs/vite/issues/11436)


### Bug Fixes

* fix: await bundle closing (#11873) ([1e6768d](https://github.com/vitejs/vite/commit/1e6768d)), closes [#11873](https://github.com/vitejs/vite/issues/11873)
* fix: make viteMetadata property of RenderedChunk optional (#11768) ([128f09e](https://github.com/vitejs/vite/commit/128f09e)), closes [#11768](https://github.com/vitejs/vite/issues/11768)
* fix: replace import.meta.hot with undefined in the production (#11317) ([73afe6d](https://github.com/vitejs/vite/commit/73afe6d)), closes [#11317](https://github.com/vitejs/vite/issues/11317)
* fix: update CJS interop error message (#11842) ([356ddfe](https://github.com/vitejs/vite/commit/356ddfe)), closes [#11842](https://github.com/vitejs/vite/issues/11842)
* fix(client): serve client sources next to deployed scripts (#11865) ([63bd261](https://github.com/vitejs/vite/commit/63bd261)), closes [#11865](https://github.com/vitejs/vite/issues/11865)
* fix(deps): update all non-major dependencies (#11846) ([5d55083](https://github.com/vitejs/vite/commit/5d55083)), closes [#11846](https://github.com/vitejs/vite/issues/11846)
* fix(esbuild): avoid polluting global namespace while minify is false (#11882) ([c895379](https://github.com/vitejs/vite/commit/c895379)), closes [#11882](https://github.com/vitejs/vite/issues/11882)
* fix: deep resolve side effects when glob does not contain / (#11807) ([f3a0c3b](https://github.com/vitejs/vite/commit/f3a0c3b)), closes [#11807](https://github.com/vitejs/vite/issues/11807)
* fix: duplicated sourceMappingURL for worker bundles (fix #11601) (#11602) ([5444781](https://github.com/vitejs/vite/commit/5444781)), closes [#11601](https://github.com/vitejs/vite/issues/11601) [#11602](https://github.com/vitejs/vite/issues/11602)
* fix: emit assets from SSR build (#11430) ([ffbdcdb](https://github.com/vitejs/vite/commit/ffbdcdb)), closes [#11430](https://github.com/vitejs/vite/issues/11430)
* fix: revert "load sourcemaps alongside modules (#11576)" (#11775) ([697dd00](https://github.com/vitejs/vite/commit/697dd00)), closes [#11576](https://github.com/vitejs/vite/issues/11576) [#11775](https://github.com/vitejs/vite/issues/11775)
* fix: scope tracking for shadowing variables in blocks (#11806) (#11811) ([568bdab](https://github.com/vitejs/vite/commit/568bdab)), closes [#11806](https://github.com/vitejs/vite/issues/11806) [#11811](https://github.com/vitejs/vite/issues/11811)
* fix(cli): exit 1 on ctrl+c (#11563) ([fb77411](https://github.com/vitejs/vite/commit/fb77411)), closes [#11563](https://github.com/vitejs/vite/issues/11563)
* fix(css): insert styles in the same position (#11763) ([d2f1381](https://github.com/vitejs/vite/commit/d2f1381)), closes [#11763](https://github.com/vitejs/vite/issues/11763)
* fix(esbuild): check server before reload tsconfig (#11747) ([c56b954](https://github.com/vitejs/vite/commit/c56b954)), closes [#11747](https://github.com/vitejs/vite/issues/11747)
* fix(hmr): hmr websocket failure for custom middleware mode with server.hmr.server (#11487) ([00919bb](https://github.com/vitejs/vite/commit/00919bb)), closes [#11487](https://github.com/vitejs/vite/issues/11487)
* fix(ssr): load sourcemaps alongside modules (fix: #3288) (#11576) ([dc05e97](https://github.com/vitejs/vite/commit/dc05e97)), closes [#3288](https://github.com/vitejs/vite/issues/3288) [#11576](https://github.com/vitejs/vite/issues/11576)
* refactor: upgrade resolve.exports (#11712) ([00a79ec](https://github.com/vitejs/vite/commit/00a79ec)), closes [#11712](https://github.com/vitejs/vite/issues/11712)
* fix: remove moment from force interop packages (#11502) ([b89ddd6](https://github.com/vitejs/vite/commit/b89ddd6)), closes [#11502](https://github.com/vitejs/vite/issues/11502)
* fix(css): fix stale css when reloading with hmr disabled (#10270) (#11506) ([e5807c4](https://github.com/vitejs/vite/commit/e5807c4)), closes [#10270](https://github.com/vitejs/vite/issues/10270) [#11506](https://github.com/vitejs/vite/issues/11506)
* fix(hmr): base default protocol on client source location (#11497) ([167753d](https://github.com/vitejs/vite/commit/167753d)), closes [#11497](https://github.com/vitejs/vite/issues/11497)
* fix(metadata): expose viteMetadata type (#11511) ([32dee3c](https://github.com/vitejs/vite/commit/32dee3c)), closes [#11511](https://github.com/vitejs/vite/issues/11511)
* fix(resolve): ensure exports has precedence over mainFields (cherry pick #11234) (#11595) ([691e432](https://github.com/vitejs/vite/commit/691e432)), closes [#11234](https://github.com/vitejs/vite/issues/11234) [#11595](https://github.com/vitejs/vite/issues/11595)
* fix(resolve): use only root package.json as exports source (#11259) ([b9afa6e](https://github.com/vitejs/vite/commit/b9afa6e)), closes [#11259](https://github.com/vitejs/vite/issues/11259)
* refactor(build): close rollup bundle directly (#11460) ([a802828](https://github.com/vitejs/vite/commit/a802828)), closes [#11460](https://github.com/vitejs/vite/issues/11460)


### Previous Changelogs


#### [4.1.0-beta.2](https://github.com/vitejs/vite/compare/v4.1.0-beta.1...v4.1.0-beta.2) (2023-02-01)

See [4.1.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v4.1.0-beta.2/packages/vite/CHANGELOG.md)


#### [4.1.0-beta.1](https://github.com/vitejs/vite/compare/v4.1.0-beta.0...v4.1.0-beta.1) (2023-01-26)

See [4.1.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v4.1.0-beta.1/packages/vite/CHANGELOG.md)


#### [4.1.0-beta.0](https://github.com/vitejs/vite/compare/v4.0.3...v4.1.0-beta.0) (2023-01-09)

See [4.1.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v4.1.0-beta.0/packages/vite/CHANGELOG.md)



## <small>4.0.4 (2023-01-03)</small>

* fix: importmap should insert before module preload link (#11492) ([25c64d7](https://github.com/vitejs/vite/commit/25c64d7)), closes [#11492](https://github.com/vitejs/vite/issues/11492)
* fix: server.host with ipv6 missed [] (fix #11466) (#11509) ([2c38bae](https://github.com/vitejs/vite/commit/2c38bae)), closes [#11466](https://github.com/vitejs/vite/issues/11466) [#11509](https://github.com/vitejs/vite/issues/11509)
* fix: stop considering parent URLs as public file (#11145) ([568a014](https://github.com/vitejs/vite/commit/568a014)), closes [#11145](https://github.com/vitejs/vite/issues/11145)
* fix(build): invalidate chunk hash when css changed (#11475) ([7a97a04](https://github.com/vitejs/vite/commit/7a97a04)), closes [#11475](https://github.com/vitejs/vite/issues/11475)
* fix(cli): ctrl+C no longer kills processes (#11434) (#11518) ([718fc1d](https://github.com/vitejs/vite/commit/718fc1d)), closes [#11434](https://github.com/vitejs/vite/issues/11434) [#11518](https://github.com/vitejs/vite/issues/11518)
* fix(cli): revert ctrl+C no longer kills processes (#11434) (#11518) (#11562) ([3748acb](https://github.com/vitejs/vite/commit/3748acb)), closes [#11434](https://github.com/vitejs/vite/issues/11434) [#11518](https://github.com/vitejs/vite/issues/11518) [#11562](https://github.com/vitejs/vite/issues/11562)
* fix(optimizer): check .vite/deps directory existence before removing (#11499) ([1b043f9](https://github.com/vitejs/vite/commit/1b043f9)), closes [#11499](https://github.com/vitejs/vite/issues/11499)
* fix(ssr): emit js sourcemaps for ssr builds (#11343) ([f12a1ab](https://github.com/vitejs/vite/commit/f12a1ab)), closes [#11343](https://github.com/vitejs/vite/issues/11343)
* chore: update license (#11476) ([3d346c0](https://github.com/vitejs/vite/commit/3d346c0)), closes [#11476](https://github.com/vitejs/vite/issues/11476)
* chore(deps): update dependency @rollup/plugin-json to v6 (#11553) ([3647d07](https://github.com/vitejs/vite/commit/3647d07)), closes [#11553](https://github.com/vitejs/vite/issues/11553)



## <small>4.0.3 (2022-12-21)</small>

* chore(deps): update dependency @rollup/plugin-commonjs to v24 (#11420) ([241db16](https://github.com/vitejs/vite/commit/241db16)), closes [#11420](https://github.com/vitejs/vite/issues/11420)
* chore(typo): fix typo (#11445) ([ed80ea5](https://github.com/vitejs/vite/commit/ed80ea5)), closes [#11445](https://github.com/vitejs/vite/issues/11445)
* fix(ssr): ignore module exports condition (#11409) ([d3c9c0b](https://github.com/vitejs/vite/commit/d3c9c0b)), closes [#11409](https://github.com/vitejs/vite/issues/11409)
* feat: allow import.meta.hot define override (#8944) ([857d578](https://github.com/vitejs/vite/commit/857d578)), closes [#8944](https://github.com/vitejs/vite/issues/8944)



## <small>4.0.2 (2022-12-18)</small>

* fix: fix the error message in the `toOutputFilePathWithoutRuntime` function (#11367) ([8820f75](https://github.com/vitejs/vite/commit/8820f75)), closes [#11367](https://github.com/vitejs/vite/issues/11367)
* fix: make `vite optimize` prebundle for dev (#11387) ([b4ced0f](https://github.com/vitejs/vite/commit/b4ced0f)), closes [#11387](https://github.com/vitejs/vite/issues/11387)
* fix: revert #11290 (#11412) ([6587d2f](https://github.com/vitejs/vite/commit/6587d2f)), closes [#11290](https://github.com/vitejs/vite/issues/11290) [#11412](https://github.com/vitejs/vite/issues/11412)
* fix: server and preview open fails to add slash before relative path (#11394) ([57276b7](https://github.com/vitejs/vite/commit/57276b7)), closes [#11394](https://github.com/vitejs/vite/issues/11394)
* fix: skip applescript when no Chromium browser found (fixes #11205) (#11406) ([274d1f3](https://github.com/vitejs/vite/commit/274d1f3)), closes [#11205](https://github.com/vitejs/vite/issues/11205) [#11406](https://github.com/vitejs/vite/issues/11406)
* fix(deps): update dependency ufo to v1 (#11372) ([4288300](https://github.com/vitejs/vite/commit/4288300)), closes [#11372](https://github.com/vitejs/vite/issues/11372)
* chore: typecheck create-vite (#11295) ([af86e5b](https://github.com/vitejs/vite/commit/af86e5b)), closes [#11295](https://github.com/vitejs/vite/issues/11295)
* chore(deps): update dependency convert-source-map to v2 (#10548) ([8dc6528](https://github.com/vitejs/vite/commit/8dc6528)), closes [#10548](https://github.com/vitejs/vite/issues/10548)
* chore(deps): update dependency mlly to v1 (#11370) ([9662d4d](https://github.com/vitejs/vite/commit/9662d4d)), closes [#11370](https://github.com/vitejs/vite/issues/11370)



## <small>4.0.1 (2022-12-12)</small>

* feat: show server url by pressing `u` (#11319) ([8c0bb7b](https://github.com/vitejs/vite/commit/8c0bb7b)), closes [#11319](https://github.com/vitejs/vite/issues/11319)
* feat(html): clickable error position for html parse error (#11334) ([2e15f3d](https://github.com/vitejs/vite/commit/2e15f3d)), closes [#11334](https://github.com/vitejs/vite/issues/11334)
* fix: ?inline warning for .css.js file (#11347) ([729fb1a](https://github.com/vitejs/vite/commit/729fb1a)), closes [#11347](https://github.com/vitejs/vite/issues/11347)
* fix: check if build exists so preview doesn't show 404s due to nonexistent build (#10564) ([0a1db8c](https://github.com/vitejs/vite/commit/0a1db8c)), closes [#10564](https://github.com/vitejs/vite/issues/10564)
* fix: derive `useDefineForClassFields` value from `tsconfig.compilerOptions.target` (fixes #10296) (# ([42976d8](https://github.com/vitejs/vite/commit/42976d8)), closes [#10296](https://github.com/vitejs/vite/issues/10296) [#11301](https://github.com/vitejs/vite/issues/11301)
* fix: preview fallback (#11312) ([cfedf9c](https://github.com/vitejs/vite/commit/cfedf9c)), closes [#11312](https://github.com/vitejs/vite/issues/11312)
* fix: respect base when using `/__open-in-editor` (#11337) ([8856c2e](https://github.com/vitejs/vite/commit/8856c2e)), closes [#11337](https://github.com/vitejs/vite/issues/11337)
* fix: wrongly resolve to optimized doppelganger (#11290) ([34fec41](https://github.com/vitejs/vite/commit/34fec41)), closes [#11290](https://github.com/vitejs/vite/issues/11290)
* fix(env): test NODE_ENV override before expand (#11309) ([d0a9281](https://github.com/vitejs/vite/commit/d0a9281)), closes [#11309](https://github.com/vitejs/vite/issues/11309)
* fix(preview): Revert #10564 - throw Error on missing outDir (#11335) ([3aaa0ea](https://github.com/vitejs/vite/commit/3aaa0ea)), closes [#10564](https://github.com/vitejs/vite/issues/10564) [#11335](https://github.com/vitejs/vite/issues/11335) [#10564](https://github.com/vitejs/vite/issues/10564)
* docs: fix banner image in CHANGELOG.md (#11336) ([45b66f4](https://github.com/vitejs/vite/commit/45b66f4)), closes [#11336](https://github.com/vitejs/vite/issues/11336)
* chore: enable `@typescript-eslint/ban-ts-comment` (#11326) ([e58a4f0](https://github.com/vitejs/vite/commit/e58a4f0)), closes [#11326](https://github.com/vitejs/vite/issues/11326)
* chore: fix format (#11311) ([9c2b1c0](https://github.com/vitejs/vite/commit/9c2b1c0)), closes [#11311](https://github.com/vitejs/vite/issues/11311)
* chore: update changelog release notes for 4.0 (#11285) ([83abd37](https://github.com/vitejs/vite/commit/83abd37)), closes [#11285](https://github.com/vitejs/vite/issues/11285)
* chore(deps): update all non-major dependencies (#11321) ([dcc0004](https://github.com/vitejs/vite/commit/dcc0004)), closes [#11321](https://github.com/vitejs/vite/issues/11321)
* chore(esbuild): add test for configuration overrides (#11267) ([f897b64](https://github.com/vitejs/vite/commit/f897b64)), closes [#11267](https://github.com/vitejs/vite/issues/11267)



## 4.0.0 (2022-12-09)

![Vite 4 Announcement Cover Image](https://vitejs.dev/og-image-announcing-vite4.png)

Read the announcement blog post: [Announcing Vite 4](https://vitejs.dev/blog/announcing-vite4)

Quick links:

- [Docs](https://vitejs.dev)
- [Migration Guide](https://vitejs.dev/guide/migration)

Docs in other languages:

- [简体中文](https://cn.vitejs.dev/)
- [日本語](https://ja.vitejs.dev/)
- [Español](https://es.vitejs.dev/)

### Main Changes

This major is smaller in scope compared to Vite 3, with the main objective of upgrading to Rollup 3. We've worked with the ecosystem to ensure a smooth upgrade path for this new major.

#### Rollup 3

Vite is now using [Rollup 3](https://github.com/vitejs/vite/issues/9870), which allowed us to simplify Vite's internal asset handling and has many improvements. See the [Rollup 3 release notes here](https://github.com/rollup/rollup/releases).

#### Framework Plugins out of the Vite core monorepo

[`@vitejs/plugin-vue`](https://github.com/vitejs/vite-plugin-vue) and [`@vitejs/plugin-react`](https://github.com/vitejs/vite-plugin-react) have been part of Vite core monorepo since the first versions of Vite. This helped us to get a close feedback loop when making changes as we were getting both Core and the plugins tested and released together. With [vite-ecosystem-ci](https://github.com/vitejs/vite-ecosystem-ci) we can get this feedback with these plugins developed on independent repositories, so from Vite 4, [they have been moved out of the Vite core monorepo](https://github.com/vitejs/vite/pull/11158). This is meaningful for Vite's framework-agnostic story, and will allow us to build independent teams to maintain each of the plugins. If you have bugs to report or features to request, please create issues on the new repositories moving forward: [`vitejs/vite-plugin-vue`](https://github.com/vitejs/vite-plugin-vue) and [`vitejs/vite-plugin-react`](https://github.com/vitejs/vite-plugin-react).

#### New React plugin using SWC during development

[SWC](https://swc.rs/) is now a mature replacement for [Babel](https://babeljs.io/), especially in the context of React projects. SWC's React Fast Refresh implementation is a lot faster than Babel, and for some projects, it is now a better alternative. From Vite 4, two plugins are available for React projects with different tradeoffs. We believe that both approaches are worth supporting at this point, and we'll continue to explore improvements to both plugins in the future.

##### @vitejs/plugin-react

[@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react) is a plugin that uses esbuild and Babel, achieving fast HMR with a small package footprint and the flexibility of being able to use the babel transform pipeline.

##### @vitejs/plugin-react-swc (new)

[@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) is a new plugin that uses esbuild during build, but replaces Babel with SWC during development. For big projects that don't require non-standard React extensions, cold start and Hot Module Replacement (HMR) can be significantly faster.

#### Compatibility

The modern browser build now targets `safari14` by default for wider ES2020 compatibility (https://github.com/vitejs/vite/issues/9063). This means that modern builds can now use [`BigInt`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt) and that the [nullish coallessing operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing) isn't transpiled anymore. If you need to support older browsers, you can add [`@vitejs/plugin-legacy`](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy) as usual.

#### Importing CSS as a string

In Vite 3, importing the default export of a `.css` file could introduce a double loading of CSS.

```ts
import cssString from './global.css';
```

This double loading could occur since a `.css` file will be emitted and it's likely that the CSS string will also be used by the application code — for example, injected by the framework runtime. From Vite 4, the `.css` default export [has been deprecated](https://github.com/vitejs/vite/issues/11094). The `?inline` query suffix modifier needs to be used in this case, as that doesn't emit the imported `.css` styles.

```ts
import stuff from './global.css?inline'
```

#### Other features

* Support for patch-package when pre bundling dependencies ([#10286](https://github.com/vitejs/vite/issues/10286))
* Cleaner build logs output ([#10895](https://github.com/vitejs/vite/issues/10895)) and switch to `kB` to align with browser dev tools ([#10982](https://github.com/vitejs/vite/issues/10982))
* Improved error messages during SSR ([#11156](https://github.com/vitejs/vite/issues/11156))


### Features

* feat: add CLI keyboard shortcuts (#11228) ([87973f1](https://github.com/vitejs/vite/commit/87973f1)), closes [#11228](https://github.com/vitejs/vite/issues/11228)
* feat: export error message generator (#11155) ([493ba1e](https://github.com/vitejs/vite/commit/493ba1e)), closes [#11155](https://github.com/vitejs/vite/issues/11155)
* feat(node/plugins): esbuild options (#11049) ([735b98b](https://github.com/vitejs/vite/commit/735b98b)), closes [#11049](https://github.com/vitejs/vite/issues/11049)
* feat: improve the error message of `expand` (#11141) ([825c793](https://github.com/vitejs/vite/commit/825c793)), closes [#11141](https://github.com/vitejs/vite/issues/11141)
* feat: update @types/node to v18 (#11195) ([4ec9f53](https://github.com/vitejs/vite/commit/4ec9f53)), closes [#11195](https://github.com/vitejs/vite/issues/11195)
* feat(client)!: remove never implemented hot.decline (#11036) ([e257e3b](https://github.com/vitejs/vite/commit/e257e3b)), closes [#11036](https://github.com/vitejs/vite/issues/11036)
* feat!: support `safari14` by default for wider ES2020 compatibility (#9063) ([3cc65d7](https://github.com/vitejs/vite/commit/3cc65d7)), closes [#9063](https://github.com/vitejs/vite/issues/9063)
* feat!: support multiline values in env files (#10826) ([606e60d](https://github.com/vitejs/vite/commit/606e60d)), closes [#10826](https://github.com/vitejs/vite/issues/10826)
* feat(ssr)!: remove dedupe and mode support for CJS (#11101) ([3090564](https://github.com/vitejs/vite/commit/3090564)), closes [#11101](https://github.com/vitejs/vite/issues/11101)
* feat: align object interface for `transformIndexHtml` hook (#9669) ([1db52bf](https://github.com/vitejs/vite/commit/1db52bf)), closes [#9669](https://github.com/vitejs/vite/issues/9669)
* feat(build): cleaner logs output (#10895) ([7d24b5f](https://github.com/vitejs/vite/commit/7d24b5f)), closes [#10895](https://github.com/vitejs/vite/issues/10895)
* feat(css): deprecate css default export (#11094) ([01dee1b](https://github.com/vitejs/vite/commit/01dee1b)), closes [#11094](https://github.com/vitejs/vite/issues/11094)
* feat(optimizer): support patch-package (#10286) ([4fb7ad0](https://github.com/vitejs/vite/commit/4fb7ad0)), closes [#10286](https://github.com/vitejs/vite/issues/10286)
* feat(build): Use kB in build reporter (#10982) ([b57acfa](https://github.com/vitejs/vite/commit/b57acfa)), closes [#10982](https://github.com/vitejs/vite/issues/10982)
* feat(css): upgrade postcss-modules (#10987) ([892916d](https://github.com/vitejs/vite/commit/892916d)), closes [#10987](https://github.com/vitejs/vite/issues/10987)
* feat(hmr): invalidate message (#10946) ([0d73473](https://github.com/vitejs/vite/commit/0d73473)), closes [#10946](https://github.com/vitejs/vite/issues/10946)
* feat(client): expose hot.prune API (#11016) ([f40c18d](https://github.com/vitejs/vite/commit/f40c18d)), closes [#11016](https://github.com/vitejs/vite/issues/11016)
* feat(hmr): deduplicate paths and join them with commas (#10891) ([967299a](https://github.com/vitejs/vite/commit/967299a)), closes [#10891](https://github.com/vitejs/vite/issues/10891)
* feat: base without trailing slash (#10723) ([8f87282](https://github.com/vitejs/vite/commit/8f87282)), closes [#10723](https://github.com/vitejs/vite/issues/10723)
* feat: handle static assets in case-sensitive manner (#10475) ([c1368c3](https://github.com/vitejs/vite/commit/c1368c3)), closes [#10475](https://github.com/vitejs/vite/issues/10475)
* feat(cli): build --profile (#10719) ([9c808cd](https://github.com/vitejs/vite/commit/9c808cd)), closes [#10719](https://github.com/vitejs/vite/issues/10719)
* feat(env): support dotenv-expand to contains process env (#10370) ([d5fe92c](https://github.com/vitejs/vite/commit/d5fe92c)), closes [#10370](https://github.com/vitejs/vite/issues/10370)
* feat!: set esbuild default charset to utf8 (#10753) ([4caf4b6](https://github.com/vitejs/vite/commit/4caf4b6)), closes [#10753](https://github.com/vitejs/vite/issues/10753)
* feat: rollup 3 (#9870) ([beb7166](https://github.com/vitejs/vite/commit/beb7166)), closes [#9870](https://github.com/vitejs/vite/issues/9870)


### Bug Fixes

* fix: add `\0` to virtual files id (#11261) ([02cdfa9](https://github.com/vitejs/vite/commit/02cdfa9)), closes [#11261](https://github.com/vitejs/vite/issues/11261)
* fix: skip shortcuts on non-tty stdin (#11263) ([9602686](https://github.com/vitejs/vite/commit/9602686)), closes [#11263](https://github.com/vitejs/vite/issues/11263)
* fix(ssr): skip rewriting stack trace if it's already rewritten (fixes #11037) (#11070) ([feb8ce0](https://github.com/vitejs/vite/commit/feb8ce0)), closes [#11037](https://github.com/vitejs/vite/issues/11037) [#11070](https://github.com/vitejs/vite/issues/11070)
* refactor(optimizer): await depsOptimizer.scanProcessing (#11251) ([fa64c8e](https://github.com/vitejs/vite/commit/fa64c8e)), closes [#11251](https://github.com/vitejs/vite/issues/11251)
* fix: improve CLI shortcuts help display (#11247) ([bb235b2](https://github.com/vitejs/vite/commit/bb235b2)), closes [#11247](https://github.com/vitejs/vite/issues/11247)
* fix: less promises for scanning and await with allSettled (#11245) ([45b170e](https://github.com/vitejs/vite/commit/45b170e)), closes [#11245](https://github.com/vitejs/vite/issues/11245)
* fix(optimizer): escape entrypoints when running scanner (#11250) ([b61894e](https://github.com/vitejs/vite/commit/b61894e)), closes [#11250](https://github.com/vitejs/vite/issues/11250)
* fix: await scanner (#11242) ([52a6732](https://github.com/vitejs/vite/commit/52a6732)), closes [#11242](https://github.com/vitejs/vite/issues/11242)
* fix(css): fix css lang regex (#11237) ([a55d0b3](https://github.com/vitejs/vite/commit/a55d0b3)), closes [#11237](https://github.com/vitejs/vite/issues/11237)
* fix: don't print urls on restart with default port (#11230) ([5aaecb6](https://github.com/vitejs/vite/commit/5aaecb6)), closes [#11230](https://github.com/vitejs/vite/issues/11230)
* fix: serialize bundleWorkerEntry (#11218) ([306bed0](https://github.com/vitejs/vite/commit/306bed0)), closes [#11218](https://github.com/vitejs/vite/issues/11218)
* fix(config): resolve dynamic import as esm (#11220) ([f8c1ed0](https://github.com/vitejs/vite/commit/f8c1ed0)), closes [#11220](https://github.com/vitejs/vite/issues/11220)
* fix(env): prevent env expand on process.env (#11213) ([d4a1e2b](https://github.com/vitejs/vite/commit/d4a1e2b)), closes [#11213](https://github.com/vitejs/vite/issues/11213)
* fix: add type for function localsConvention value (#11152) ([c9274b4](https://github.com/vitejs/vite/commit/c9274b4)), closes [#11152](https://github.com/vitejs/vite/issues/11152)
* fix: cacheDir should be ignored from watch (#10242) ([75dbca2](https://github.com/vitejs/vite/commit/75dbca2)), closes [#10242](https://github.com/vitejs/vite/issues/10242)
* fix: don't check .yarn/patches for computing dependencies hash (#11168) ([65bcccf](https://github.com/vitejs/vite/commit/65bcccf)), closes [#11168](https://github.com/vitejs/vite/issues/11168)
* fix: formatError() outside rollup context (#11156) ([2aee2eb](https://github.com/vitejs/vite/commit/2aee2eb)), closes [#11156](https://github.com/vitejs/vite/issues/11156)
* fix: Revert "fix: missing js sourcemaps with rewritten imports broke debugging (#7767) (#9476)" (#11 ([fdc6f3a](https://github.com/vitejs/vite/commit/fdc6f3a)), closes [#7767](https://github.com/vitejs/vite/issues/7767) [#9476](https://github.com/vitejs/vite/issues/9476) [#11144](https://github.com/vitejs/vite/issues/11144)
* fix: Dev SSR dep optimization + respect optimizeDeps.include (#11123) ([515caa5](https://github.com/vitejs/vite/commit/515caa5)), closes [#11123](https://github.com/vitejs/vite/issues/11123)
* fix: export preprocessCSS in CJS (#11067) ([793255d](https://github.com/vitejs/vite/commit/793255d)), closes [#11067](https://github.com/vitejs/vite/issues/11067)
* fix: glob import parsing (#10949) (#11056) ([ac2cfd6](https://github.com/vitejs/vite/commit/ac2cfd6)), closes [#10949](https://github.com/vitejs/vite/issues/10949) [#11056](https://github.com/vitejs/vite/issues/11056)
* fix: import.meta.env and process.env undefined variable replacement (fix #8663) (#10958) ([3e0cd3d](https://github.com/vitejs/vite/commit/3e0cd3d)), closes [#8663](https://github.com/vitejs/vite/issues/8663) [#10958](https://github.com/vitejs/vite/issues/10958)
* fix: missing js sourcemaps with rewritten imports broke debugging (#7767) (#9476) ([3fa96f6](https://github.com/vitejs/vite/commit/3fa96f6)), closes [#7767](https://github.com/vitejs/vite/issues/7767) [#9476](https://github.com/vitejs/vite/issues/9476)
* fix: preserve default export from externalized packages (fixes #10258) (#10406) ([88b001b](https://github.com/vitejs/vite/commit/88b001b)), closes [#10258](https://github.com/vitejs/vite/issues/10258) [#10406](https://github.com/vitejs/vite/issues/10406)
* fix: reset global regex before match (#11132) ([db8df14](https://github.com/vitejs/vite/commit/db8df14)), closes [#11132](https://github.com/vitejs/vite/issues/11132)
* fix(css): handle environment with browser globals (#11079) ([e92d025](https://github.com/vitejs/vite/commit/e92d025)), closes [#11079](https://github.com/vitejs/vite/issues/11079)
* fix(deps): update all non-major dependencies (#11091) ([073a4bf](https://github.com/vitejs/vite/commit/073a4bf)), closes [#11091](https://github.com/vitejs/vite/issues/11091)
* fix(esbuild): handle inline sourcemap option (#11120) ([4c85c0a](https://github.com/vitejs/vite/commit/4c85c0a)), closes [#11120](https://github.com/vitejs/vite/issues/11120)
* fix(importGlob): don't warn when CSS default import is not used (#11121) ([97f8b4d](https://github.com/vitejs/vite/commit/97f8b4d)), closes [#11121](https://github.com/vitejs/vite/issues/11121)
* fix(importGlob): preserve line count for sourcemap (#11122) ([14980a1](https://github.com/vitejs/vite/commit/14980a1)), closes [#11122](https://github.com/vitejs/vite/issues/11122)
* fix(importGlob): warn on default import css (#11103) ([fc0d9e3](https://github.com/vitejs/vite/commit/fc0d9e3)), closes [#11103](https://github.com/vitejs/vite/issues/11103)
* fix(plugin-vue): support scss/sass/less... hmr on custom template languages (fix #10677) (#10844) ([d413848](https://github.com/vitejs/vite/commit/d413848)), closes [#10677](https://github.com/vitejs/vite/issues/10677) [#10844](https://github.com/vitejs/vite/issues/10844)
* fix(ssr): preserve require for external node (#11057) ([1ec0176](https://github.com/vitejs/vite/commit/1ec0176)), closes [#11057](https://github.com/vitejs/vite/issues/11057)
* fix(worker): disable build reporter plugin when bundling worker (#11058) ([7b72069](https://github.com/vitejs/vite/commit/7b72069)), closes [#11058](https://github.com/vitejs/vite/issues/11058)
* fix!: make `NODE_ENV` more predictable (#10996) ([8148af7](https://github.com/vitejs/vite/commit/8148af7)), closes [#10996](https://github.com/vitejs/vite/issues/10996)
* fix(config)!: support development build (#11045) ([8b3d656](https://github.com/vitejs/vite/commit/8b3d656)), closes [#11045](https://github.com/vitejs/vite/issues/11045)
* refactor: use function to eval worker and glob options (#10999) ([f4c1264](https://github.com/vitejs/vite/commit/f4c1264)), closes [#10999](https://github.com/vitejs/vite/issues/10999)
* refactor(client): simplify fetchUpdate code (#11004) ([f777b55](https://github.com/vitejs/vite/commit/f777b55)), closes [#11004](https://github.com/vitejs/vite/issues/11004)
* fix(html): transform relative path with long base in /index.html (#10990) ([752740c](https://github.com/vitejs/vite/commit/752740c)), closes [#10990](https://github.com/vitejs/vite/issues/10990)
* fix(mpa): support mpa fallback (#10985) ([61165f0](https://github.com/vitejs/vite/commit/61165f0)), closes [#10985](https://github.com/vitejs/vite/issues/10985)
* feat: align default chunk and asset file names with rollup (#10927) ([cc2adb3](https://github.com/vitejs/vite/commit/cc2adb3)), closes [#10927](https://github.com/vitejs/vite/issues/10927)
* fix: make `addWatchFile()` work (fix #7024) (#9723) ([34db08b](https://github.com/vitejs/vite/commit/34db08b)), closes [#7024](https://github.com/vitejs/vite/issues/7024) [#9723](https://github.com/vitejs/vite/issues/9723)
* fix(config): exclude config.assetsInclude empty array (#10941) ([18c71dc](https://github.com/vitejs/vite/commit/18c71dc)), closes [#10941](https://github.com/vitejs/vite/issues/10941)
* fix(ssr): skip optional peer dep resolve (#10593) ([0a69985](https://github.com/vitejs/vite/commit/0a69985)), closes [#10593](https://github.com/vitejs/vite/issues/10593)
* perf: regexp perf issues, refactor regexp stylistic issues (#10905) ([fc007df](https://github.com/vitejs/vite/commit/fc007df)), closes [#10905](https://github.com/vitejs/vite/issues/10905)
* refactor: move CSS emitFile logic closer to rollup (#10909) ([92a206b](https://github.com/vitejs/vite/commit/92a206b)), closes [#10909](https://github.com/vitejs/vite/issues/10909)
* refactor: use rollup hashing when emitting assets (#10878) ([78c77be](https://github.com/vitejs/vite/commit/78c77be)), closes [#10878](https://github.com/vitejs/vite/issues/10878)
* fix: don't throw on malformed URLs (#10901) ([feb9b10](https://github.com/vitejs/vite/commit/feb9b10)), closes [#10901](https://github.com/vitejs/vite/issues/10901)
* fix: gracefully handle forbidden filesystem access (#10793) ([92637a2](https://github.com/vitejs/vite/commit/92637a2)), closes [#10793](https://github.com/vitejs/vite/issues/10793)
* fix(types): remove `null` from `CSSModulesOptions.localsConvention` (#10904) ([a9978dd](https://github.com/vitejs/vite/commit/a9978dd)), closes [#10904](https://github.com/vitejs/vite/issues/10904)
* refactor(types)!: remove facade type files (#10903) ([a309058](https://github.com/vitejs/vite/commit/a309058)), closes [#10903](https://github.com/vitejs/vite/issues/10903)
* fix: inconsistent handling of non-ASCII `base` in `resolveConfig` and dev server (#10247) ([16e4123](https://github.com/vitejs/vite/commit/16e4123)), closes [#10247](https://github.com/vitejs/vite/issues/10247)
* fix: prevent cache on optional package resolve (#10812) ([c599a2e](https://github.com/vitejs/vite/commit/c599a2e)), closes [#10812](https://github.com/vitejs/vite/issues/10812)
* fix: relocated logger to respect config. (#10787) ([52e64eb](https://github.com/vitejs/vite/commit/52e64eb)), closes [#10787](https://github.com/vitejs/vite/issues/10787)
* fix: throw missing name error only when 'umd' or 'iife' are used (#9886) ([b8aa825](https://github.com/vitejs/vite/commit/b8aa825)), closes [#9886](https://github.com/vitejs/vite/issues/9886)
* fix(deps): update all non-major dependencies (#10804) ([f686afa](https://github.com/vitejs/vite/commit/f686afa)), closes [#10804](https://github.com/vitejs/vite/issues/10804)
* fix(ssr): improve missing file error (#10880) ([5451a34](https://github.com/vitejs/vite/commit/5451a34)), closes [#10880](https://github.com/vitejs/vite/issues/10880)


### Previous Changelogs


#### [4.0.0-beta.7](https://github.com/vitejs/vite/compare/v4.0.0-beta.6...v4.0.0-beta.7) (2022-12-08)

See [4.0.0-beta.7 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.6](https://github.com/vitejs/vite/compare/v4.0.0-beta.5...v4.0.0-beta.6) (2022-12-08)

See [4.0.0-beta.6 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.5](https://github.com/vitejs/vite/compare/v4.0.0-beta.4...v4.0.0-beta.5) (2022-12-08)

See [4.0.0-beta.5 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.4](https://github.com/vitejs/vite/compare/v4.0.0-beta.3...v4.0.0-beta.4) (2022-12-07)

See [4.0.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.3](https://github.com/vitejs/vite/compare/v4.0.0-beta.2...v4.0.0-beta.3) (2022-12-07)

See [4.0.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.2](https://github.com/vitejs/vite/compare/v4.0.0-beta.1...v4.0.0-beta.2) (2022-12-07)

See [4.0.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.1](https://github.com/vitejs/vite/compare/v4.0.0-beta.0...v4.0.0-beta.1) (2022-12-06)

See [4.0.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-beta.0](https://github.com/vitejs/vite/compare/v4.0.0-alpha.6...v4.0.0-beta.0) (2022-12-05)

See [4.0.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v4.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.6](https://github.com/vitejs/vite/compare/v4.0.0-alpha.5...v4.0.0-alpha.6) (2022-11-30)

See [4.0.0-alpha.6 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.6/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.5](https://github.com/vitejs/vite/compare/v4.0.0-alpha.5...v4.0.0-alpha.5) (2022-11-22)

See [4.0.0-alpha.5 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.5/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.4](https://github.com/vitejs/vite/compare/v4.0.0-alpha.3...v4.0.0-alpha.4) (2022-11-17)

See [4.0.0-alpha.4 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.4/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.3](https://github.com/vitejs/vite/compare/v4.0.0-alpha.2...v4.0.0-alpha.3) (2022-11-15)

See [4.0.0-alpha.3 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.3/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.2](https://github.com/vitejs/vite/compare/v4.0.0-alpha.1...v4.0.0-alpha.2) (2022-11-13)

See [4.0.0-alpha.2 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.2/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.1](https://github.com/vitejs/vite/compare/v4.0.0-alpha.0...v4.0.0-alpha.1) (2022-11-12)

See [4.0.0-alpha.1 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.1/packages/vite/CHANGELOG.md)


#### [4.0.0-alpha.0](https://github.com/vitejs/vite/compare/v3.2.5...v4.0.0-alpha.0) (2022-11-07)

See [4.0.0-alpha.0 changelog](https://github.com/vitejs/vite/blob/v4.0.0-alpha.0/packages/vite/CHANGELOG.md)



## <small>3.2.6 (2023-04-18)</small>

 * fix: escape msg in render restricted error html, backport (#12889) (#12892) ([b48ac2a](https://github.com/vitejs/vite/commit/b48ac2a)), closes [#12889](https://github.com/vitejs/vite/issues/12889) [#12892](https://github.com/vitejs/vite/issues/12892)



## <small>3.2.5 (2022-12-05)</small>

* chore: cherry pick more v4 bug fixes to v3 (#11189) ([eba9b42](https://github.com/vitejs/vite/commit/eba9b42)), closes [#11189](https://github.com/vitejs/vite/issues/11189) [#10949](https://github.com/vitejs/vite/issues/10949) [#11056](https://github.com/vitejs/vite/issues/11056) [#8663](https://github.com/vitejs/vite/issues/8663) [#10958](https://github.com/vitejs/vite/issues/10958) [#11120](https://github.com/vitejs/vite/issues/11120) [#11122](https://github.com/vitejs/vite/issues/11122) [#11123](https://github.com/vitejs/vite/issues/11123) [#11132](https://github.com/vitejs/vite/issues/11132)
* chore: cherry pick v4 bug fix to v3 (#11110) ([c93a526](https://github.com/vitejs/vite/commit/c93a526)), closes [#11110](https://github.com/vitejs/vite/issues/11110) [#10941](https://github.com/vitejs/vite/issues/10941) [#10987](https://github.com/vitejs/vite/issues/10987) [#10985](https://github.com/vitejs/vite/issues/10985) [#11067](https://github.com/vitejs/vite/issues/11067)
* fix: relocated logger to respect config. (#10787) (#10967) ([bc3b5a9](https://github.com/vitejs/vite/commit/bc3b5a9)), closes [#10787](https://github.com/vitejs/vite/issues/10787) [#10967](https://github.com/vitejs/vite/issues/10967)



## <small>3.2.4 (2022-11-15)</small>

* fix: prevent cache on optional package resolve (v3) (#10812) (#10845) ([3ba45b9](https://github.com/vitejs/vite/commit/3ba45b9)), closes [#10812](https://github.com/vitejs/vite/issues/10812) [#10845](https://github.com/vitejs/vite/issues/10845)
* fix(ssr): skip optional peer dep resolve (v3) (#10593) (#10931) ([7f59dcf](https://github.com/vitejs/vite/commit/7f59dcf)), closes [#10593](https://github.com/vitejs/vite/issues/10593) [#10931](https://github.com/vitejs/vite/issues/10931) [#10593](https://github.com/vitejs/vite/issues/10593)



## <small>3.2.3 (2022-11-07)</small>

* refactor: change style.innerHTML to style.textContent (#10801) ([8ea71b4](https://github.com/vitejs/vite/commit/8ea71b4)), closes [#10801](https://github.com/vitejs/vite/issues/10801)
* fix: add `@types/node` as an optional peer dependency (#10757) ([57916a4](https://github.com/vitejs/vite/commit/57916a4)), closes [#10757](https://github.com/vitejs/vite/issues/10757)
* fix: transform import.meta.glob when scan JS/TS #10634 (#10635) ([c53ffec](https://github.com/vitejs/vite/commit/c53ffec)), closes [#10634](https://github.com/vitejs/vite/issues/10634) [#10635](https://github.com/vitejs/vite/issues/10635)
* fix(css): url() with variable in sass/less (fixes #3644, #7651) (#10741) ([fa2e47f](https://github.com/vitejs/vite/commit/fa2e47f)), closes [#3644](https://github.com/vitejs/vite/issues/3644) [#7651](https://github.com/vitejs/vite/issues/7651) [#10741](https://github.com/vitejs/vite/issues/10741)
* feat: add `vite:afterUpdate` event (#9810) ([1f57f84](https://github.com/vitejs/vite/commit/1f57f84)), closes [#9810](https://github.com/vitejs/vite/issues/9810)
* perf: improve `multilineCommentsRE` regex (fix #10689) (#10751) ([51ed059](https://github.com/vitejs/vite/commit/51ed059)), closes [#10689](https://github.com/vitejs/vite/issues/10689) [#10751](https://github.com/vitejs/vite/issues/10751)
* perf: Use only one ps exec to find a Chromium browser opened on Mac OS (#10588) ([f199e90](https://github.com/vitejs/vite/commit/f199e90)), closes [#10588](https://github.com/vitejs/vite/issues/10588)
* chore: fix dev build replacing undefined (#10740) ([1358a3c](https://github.com/vitejs/vite/commit/1358a3c)), closes [#10740](https://github.com/vitejs/vite/issues/10740)
* chore: remove non used type definitions (#10738) ([ee8c7a6](https://github.com/vitejs/vite/commit/ee8c7a6)), closes [#10738](https://github.com/vitejs/vite/issues/10738)
* chore(deps): update dependency @rollup/plugin-commonjs to v23 (#10611) ([cc4be70](https://github.com/vitejs/vite/commit/cc4be70)), closes [#10611](https://github.com/vitejs/vite/issues/10611)
* chore(deps): update dependency @rollup/plugin-dynamic-import-vars to v2 (#10726) ([326f782](https://github.com/vitejs/vite/commit/326f782)), closes [#10726](https://github.com/vitejs/vite/issues/10726)



## <small>3.2.2 (2022-10-31)</small>

* chore: remove src/client from package (#10703) ([816842e](https://github.com/vitejs/vite/commit/816842e)), closes [#10703](https://github.com/vitejs/vite/issues/10703)
* chore(deps): update all non-major dependencies (#10725) ([22cfad8](https://github.com/vitejs/vite/commit/22cfad8)), closes [#10725](https://github.com/vitejs/vite/issues/10725)
* fix: remove loaded input sourcemap (fixes #8411) (#10705) ([eb50e3a](https://github.com/vitejs/vite/commit/eb50e3a)), closes [#8411](https://github.com/vitejs/vite/issues/8411) [#10705](https://github.com/vitejs/vite/issues/10705)
* fix: tsconfig `jsx` overrides esbuild options, reverts #10374 (#10714) ([aacf6a4](https://github.com/vitejs/vite/commit/aacf6a4)), closes [#10374](https://github.com/vitejs/vite/issues/10374) [#10714](https://github.com/vitejs/vite/issues/10714)
* docs(changelog): fix broken url (#10692) ([f937ccc](https://github.com/vitejs/vite/commit/f937ccc)), closes [#10692](https://github.com/vitejs/vite/issues/10692)



## <small>3.2.1 (2022-10-28)</small>

* fix: prioritize existing env over .env (fixes #10676) (#10684) ([e2ea6af](https://github.com/vitejs/vite/commit/e2ea6af)), closes [#10676](https://github.com/vitejs/vite/issues/10676) [#10684](https://github.com/vitejs/vite/issues/10684)
* fix: remove picomatch type import (fixes #10656) (#10678) ([1128b4d](https://github.com/vitejs/vite/commit/1128b4d)), closes [#10656](https://github.com/vitejs/vite/issues/10656) [#10678](https://github.com/vitejs/vite/issues/10678)
* fix(config): resolve externalized specifier with internal resolver (#10683) ([b15d21c](https://github.com/vitejs/vite/commit/b15d21c))
* feat: Add support for imba in html scripts (#10679) ([b823fd6](https://github.com/vitejs/vite/commit/b823fd6)), closes [#10679](https://github.com/vitejs/vite/issues/10679)
* chore: join URL segments more safely (#10590) ([675bf07](https://github.com/vitejs/vite/commit/675bf07)), closes [#10590](https://github.com/vitejs/vite/issues/10590)
* chore: update changelog for 3.2 (#10646) ([f787a60](https://github.com/vitejs/vite/commit/f787a60)), closes [#10646](https://github.com/vitejs/vite/issues/10646)



## 3.2.0 (2022-10-26)

### Main Changes

#### Multiple Entries for Library Mode

Library mode now supports multiple entries:
```js
  lib: {
    entry: {
        primary: 'src/index.ts',
        secondary: 'src/secondary.ts'
    },
    formats: ['es', 'cjs']
  }
  // => primary.es.js, primary.cjs.js, secondary.es.js, secondary.cjs.js
```
Check out the PR [#7047](https://github.com/vitejs/vite/issues/7047), and the [`build.lib` config docs](https://main.vitejs.dev/config/build-options.html#build-lib)

#### `build.modulePreload` options

Vite now allows filtering and modifying module preload dependencies for each entry and async chunk. [`experimental.renderBuiltUrl`](https://vitejs.dev/guide/build.html#advanced-base-options) will also get called for preload asset paths. And `build.modulePreload.resolveDependencies` will be called both for JS dynamic imports preload lists and also for HTML preload lists for chunks imported from entry HTML files. Refer to the PR for more context [#9938](https://github.com/vitejs/vite/issues/9938) and check out the [modulePreload config docs](https://vitejs.dev/config/build-options.html#build-modulepreload). Note: `build.modulePreloadPolyfill` is now deprecated, please migrate to `build.modulePreload.polyfill`.

#### Include Duplicate Assets in the Manifest

Laravel and other backends integrations will now get entries for every asset file, even if they have been de-duplicated. See [#9928](https://github.com/vitejs/vite/issues/9928) for more information.

#### Customizable ErrorOverlay

You can now customize the ErrorOverlay by using [css parts](https://developer.mozilla.org/en-US/docs/Web/CSS/::part). Check out the PR for more details: [#10234](https://github.com/vitejs/vite/issues/10234).

### Features

* feat(build): experimental copyPublicDir option (#10550) ([4f4a39f](https://github.com/vitejs/vite/commit/4f4a39f)), closes [#10550](https://github.com/vitejs/vite/issues/10550)
* feat(css): export preprocessCSS API (#10429) ([177b427](https://github.com/vitejs/vite/commit/177b427)), closes [#10429](https://github.com/vitejs/vite/issues/10429)
* feat(preview): support outDir option (#10418) ([15b90b3](https://github.com/vitejs/vite/commit/15b90b3)), closes [#10418](https://github.com/vitejs/vite/issues/10418)
* feat: include line and column in error format (#10529) ([d806c4a](https://github.com/vitejs/vite/commit/d806c4a)), closes [#10529](https://github.com/vitejs/vite/issues/10529)
* feat: reuse opening tab in chromium browsers when start dev server (#10485) ([1a2e7a8](https://github.com/vitejs/vite/commit/1a2e7a8)), closes [#10485](https://github.com/vitejs/vite/issues/10485)
* feat: update esbuild compilation affecting fields (#10374) ([f542727](https://github.com/vitejs/vite/commit/f542727)), closes [#10374](https://github.com/vitejs/vite/issues/10374)
* feat(proxy): Include URL of request in proxy errors (#10508) ([27e2832](https://github.com/vitejs/vite/commit/27e2832)), closes [#10508](https://github.com/vitejs/vite/issues/10508)
* refactor: delete dependent pre built proxy modules (#10427) ([b3b388d](https://github.com/vitejs/vite/commit/b3b388d)), closes [#10427](https://github.com/vitejs/vite/issues/10427)
* feat(server): invalidate module with hmr (#10333) ([8328011](https://github.com/vitejs/vite/commit/8328011)), closes [#10333](https://github.com/vitejs/vite/issues/10333)
* feat: build.modulePreload options (#9938) ([e223f84](https://github.com/vitejs/vite/commit/e223f84)), closes [#9938](https://github.com/vitejs/vite/issues/9938)
* feat: customize ErrorOverlay (#10234) ([fe4dc8d](https://github.com/vitejs/vite/commit/fe4dc8d)), closes [#10234](https://github.com/vitejs/vite/issues/10234)
* feat: dynamic import support ?url and ?worker (#8261) ([0cb01ca](https://github.com/vitejs/vite/commit/0cb01ca)), closes [#8261](https://github.com/vitejs/vite/issues/8261)
* feat: include duplicate assets in the manifest (#9928) ([42ecf37](https://github.com/vitejs/vite/commit/42ecf37)), closes [#9928](https://github.com/vitejs/vite/issues/9928)
* feat: support import.meta.hot.invalidate (#10244) ([fb8ab16](https://github.com/vitejs/vite/commit/fb8ab16)), closes [#10244](https://github.com/vitejs/vite/issues/10244)
* feat: support postcss sugarss (#6705) ([8ede2f1](https://github.com/vitejs/vite/commit/8ede2f1)), closes [#6705](https://github.com/vitejs/vite/issues/6705)
* feat(assets): allow `new URL` to resolve package assets (#7837) ([bafccf5](https://github.com/vitejs/vite/commit/bafccf5)), closes [#7837](https://github.com/vitejs/vite/issues/7837)
* feat(client): add data-vite-dev-id attribute to style elements (#10080) ([ea09fde](https://github.com/vitejs/vite/commit/ea09fde)), closes [#10080](https://github.com/vitejs/vite/issues/10080)
* feat(lib): allow multiple entries (#7047) ([65a0fad](https://github.com/vitejs/vite/commit/65a0fad)), closes [#7047](https://github.com/vitejs/vite/issues/7047)
* feat(optimizer): Support bun lockfile format (#10288) ([931d69b](https://github.com/vitejs/vite/commit/931d69b)), closes [#10288](https://github.com/vitejs/vite/issues/10288)
* refactor(types): bundle client types (#9966) ([da632bf](https://github.com/vitejs/vite/commit/da632bf)), closes [#9966](https://github.com/vitejs/vite/issues/9966)
* refactor(types): simplify type exports (#10243) ([291174d](https://github.com/vitejs/vite/commit/291174d)), closes [#10243](https://github.com/vitejs/vite/issues/10243)
* perf: cache compiled glob for `server.fs.deny` (#10044) ([df560b0](https://github.com/vitejs/vite/commit/df560b0)), closes [#10044](https://github.com/vitejs/vite/issues/10044)

### Bug Fixes

* fix: add a warning if css urls not exist during build time (fix #9800) (#10331) ([9f268da](https://github.com/vitejs/vite/commit/9f268da)), closes [#9800](https://github.com/vitejs/vite/issues/9800) [#10331](https://github.com/vitejs/vite/issues/10331)
* fix: increase error overlay z-index (#10603) ([1157941](https://github.com/vitejs/vite/commit/1157941)), closes [#10603](https://github.com/vitejs/vite/issues/10603)
* fix: revert es-module-lexer version (#10614) ([cffe5c9](https://github.com/vitejs/vite/commit/cffe5c9)), closes [#10614](https://github.com/vitejs/vite/issues/10614)
* fix: when the file path is an absolute path, parsing causes parameter loss (#10449) ([df86990](https://github.com/vitejs/vite/commit/df86990)), closes [#10449](https://github.com/vitejs/vite/issues/10449)
* fix(config): resolve build options with fallback (#10645) ([f7021e3](https://github.com/vitejs/vite/commit/f7021e3)), closes [#10645](https://github.com/vitejs/vite/issues/10645)
* fix(deps): update all non-major dependencies (#10610) ([bb95467](https://github.com/vitejs/vite/commit/bb95467)), closes [#10610](https://github.com/vitejs/vite/issues/10610)
* fix(hmr): cannot reload after missing import on server startup (#9534) (#10602) ([ee7c28a](https://github.com/vitejs/vite/commit/ee7c28a)), closes [#9534](https://github.com/vitejs/vite/issues/9534) [#10602](https://github.com/vitejs/vite/issues/10602)
* fix(css): strip BOM (fixes #10043) (#10577) ([e0463bd](https://github.com/vitejs/vite/commit/e0463bd)), closes [#10043](https://github.com/vitejs/vite/issues/10043) [#10577](https://github.com/vitejs/vite/issues/10577)
* fix(ssr): resolve with isRequire true (#10569) ([7b81210](https://github.com/vitejs/vite/commit/7b81210)), closes [#10569](https://github.com/vitejs/vite/issues/10569)
* fix: prefer exports when resolving (#10371) ([3259006](https://github.com/vitejs/vite/commit/3259006)), closes [#10371](https://github.com/vitejs/vite/issues/10371)
* fix(config): partial deno support (#10446) ([c4489ea](https://github.com/vitejs/vite/commit/c4489ea)), closes [#10446](https://github.com/vitejs/vite/issues/10446)
* fix(config): skip resolve builtin modules (#10420) ([ecba3f8](https://github.com/vitejs/vite/commit/ecba3f8)), closes [#10420](https://github.com/vitejs/vite/issues/10420)
* fix(ssr): handle parallel hookNodeResolve (#10401) ([1a961d9](https://github.com/vitejs/vite/commit/1a961d9)), closes [#10401](https://github.com/vitejs/vite/issues/10401)
* fix(cli): when the user enters the same command (#10474) ([2326f4a](https://github.com/vitejs/vite/commit/2326f4a)), closes [#10474](https://github.com/vitejs/vite/issues/10474)
* fix(config): don't use module condition (`import.meta.resolve`) (fixes #10430) (#10528) ([64f19b9](https://github.com/vitejs/vite/commit/64f19b9)), closes [#10430](https://github.com/vitejs/vite/issues/10430) [#10528](https://github.com/vitejs/vite/issues/10528)
* fix(css): remove `?direct` in id for postcss process (#10514) ([67e7bf2](https://github.com/vitejs/vite/commit/67e7bf2)), closes [#10514](https://github.com/vitejs/vite/issues/10514)
* fix(html): allow self closing on non-void elements (#10478) ([29292af](https://github.com/vitejs/vite/commit/29292af)), closes [#10478](https://github.com/vitejs/vite/issues/10478)
* fix(legacy): restore entry chunk CSS inlining, reverts #9761 (#10496) ([9cc808e](https://github.com/vitejs/vite/commit/9cc808e)), closes [#9761](https://github.com/vitejs/vite/issues/9761) [#10496](https://github.com/vitejs/vite/issues/10496)
* chore: simplify filter plugin code (#10459) ([5d9b810](https://github.com/vitejs/vite/commit/5d9b810)), closes [#10459](https://github.com/vitejs/vite/issues/10459)
* chore(deps): update all non-major dependencies (#10488) ([15aa827](https://github.com/vitejs/vite/commit/15aa827)), closes [#10488](https://github.com/vitejs/vite/issues/10488)
* chore: update magic-string (#10364) ([23c9259](https://github.com/vitejs/vite/commit/23c9259)), closes [#10364](https://github.com/vitejs/vite/issues/10364)
* chore(deps): update all non-major dependencies (#10393) ([f519423](https://github.com/vitejs/vite/commit/f519423)), closes [#10393](https://github.com/vitejs/vite/issues/10393)
* chore(deps): update dependency @rollup/plugin-alias to v4 (#10394) ([e2b4c8f](https://github.com/vitejs/vite/commit/e2b4c8f)), closes [#10394](https://github.com/vitejs/vite/issues/10394)
* feat(lib): cjs instead of umd as default format for multiple entries (#10315) ([07d3fbd](https://github.com/vitejs/vite/commit/07d3fbd)), closes [#10315](https://github.com/vitejs/vite/issues/10315)
* fix: make client type work with `moduleResolution=node16` (#10375) ([8c4df1f](https://github.com/vitejs/vite/commit/8c4df1f)), closes [#10375](https://github.com/vitejs/vite/issues/10375)
* fix(config): don't resolve by module field (#10347) ([cc1c829](https://github.com/vitejs/vite/commit/cc1c829)), closes [#10347](https://github.com/vitejs/vite/issues/10347)
* fix(html): handle attrs with prefix (fixes #10337) (#10381) ([7b4d6e8](https://github.com/vitejs/vite/commit/7b4d6e8)), closes [#10337](https://github.com/vitejs/vite/issues/10337) [#10381](https://github.com/vitejs/vite/issues/10381)
* fix(ssr): track var as function scope (#10388) ([87b48f9](https://github.com/vitejs/vite/commit/87b48f9)), closes [#10388](https://github.com/vitejs/vite/issues/10388)
* fix: add module types (#10299) ([0b89dd2](https://github.com/vitejs/vite/commit/0b89dd2)), closes [#10299](https://github.com/vitejs/vite/issues/10299)
* fix: css order problem in async chunk (#9949) ([6c7b834](https://github.com/vitejs/vite/commit/6c7b834)), closes [#9949](https://github.com/vitejs/vite/issues/9949)
* fix: don't duplicate styles with dynamic import (fix #9967) (#9970) ([65f97bd](https://github.com/vitejs/vite/commit/65f97bd)), closes [#9967](https://github.com/vitejs/vite/issues/9967) [#9970](https://github.com/vitejs/vite/issues/9970)
* fix: env variables override (#10113) ([d619460](https://github.com/vitejs/vite/commit/d619460)), closes [#10113](https://github.com/vitejs/vite/issues/10113)
* fix: isFromTsImporter flag in worker virtual model (#10273) ([78f74c9](https://github.com/vitejs/vite/commit/78f74c9)), closes [#10273](https://github.com/vitejs/vite/issues/10273)
* fix: properly close optimizer on server restart (#10028) ([a32777f](https://github.com/vitejs/vite/commit/a32777f)), closes [#10028](https://github.com/vitejs/vite/issues/10028)
* fix: respect `mainFields` when resolving browser/module field (fixes #8659) (#10071) ([533d13c](https://github.com/vitejs/vite/commit/533d13c)), closes [#8659](https://github.com/vitejs/vite/issues/8659) [#10071](https://github.com/vitejs/vite/issues/10071)
* fix: respect resolve.conditions, when resolving browser/require field (#9860) ([9a83eaf](https://github.com/vitejs/vite/commit/9a83eaf)), closes [#9860](https://github.com/vitejs/vite/issues/9860)
* fix: support process each out dir when there are two or more (#9748) ([ee3231c](https://github.com/vitejs/vite/commit/ee3231c)), closes [#9748](https://github.com/vitejs/vite/issues/9748)
* fix(build): fix resolution algorithm when `build.ssr` is true (#9989) ([7229251](https://github.com/vitejs/vite/commit/7229251)), closes [#9989](https://github.com/vitejs/vite/issues/9989)
* fix(config): resolve implicit deps as absolute path (#10254) ([ec1f3ae](https://github.com/vitejs/vite/commit/ec1f3ae)), closes [#10254](https://github.com/vitejs/vite/issues/10254)
* fix(css):  missing css in lib mode (#10185) ([e4c1c6d](https://github.com/vitejs/vite/commit/e4c1c6d)), closes [#10185](https://github.com/vitejs/vite/issues/10185)
* fix(deps): update all non-major dependencies (#10160) ([6233c83](https://github.com/vitejs/vite/commit/6233c83)), closes [#10160](https://github.com/vitejs/vite/issues/10160)
* fix(deps): update all non-major dependencies (#10316) ([a38b450](https://github.com/vitejs/vite/commit/a38b450)), closes [#10316](https://github.com/vitejs/vite/issues/10316)
* fix(deps): update rollup to `^2.79.1` (#10298) ([2266d83](https://github.com/vitejs/vite/commit/2266d83)), closes [#10298](https://github.com/vitejs/vite/issues/10298)
* fix(esbuild): transpile with esnext in dev (#10207) ([43b7b78](https://github.com/vitejs/vite/commit/43b7b78)), closes [#10207](https://github.com/vitejs/vite/issues/10207)
* fix(hmr): handle virtual module update (#10324) ([7c4accb](https://github.com/vitejs/vite/commit/7c4accb)), closes [#10324](https://github.com/vitejs/vite/issues/10324)
* fix(optimizer): browser field bare import (fix #7599) (#10314) ([cba13e8](https://github.com/vitejs/vite/commit/cba13e8)), closes [#7599](https://github.com/vitejs/vite/issues/7599) [#10314](https://github.com/vitejs/vite/issues/10314)
* fix(sass): reorder sass importers (#10101) ([a543731](https://github.com/vitejs/vite/commit/a543731)), closes [#10101](https://github.com/vitejs/vite/issues/10101)
* fix(server): handle appType mpa html fallback (#10336) ([65dd88b](https://github.com/vitejs/vite/commit/65dd88b)), closes [#10336](https://github.com/vitejs/vite/issues/10336)
* fix(ssr): correctly track scope (#10300) ([a60529f](https://github.com/vitejs/vite/commit/a60529f)), closes [#10300](https://github.com/vitejs/vite/issues/10300)
* fix(worker): support comment in worker constructor option (#10226) ([66c9058](https://github.com/vitejs/vite/commit/66c9058)), closes [#10226](https://github.com/vitejs/vite/issues/10226)
* fix(worker): support trailing comma (#10211) ([0542e7c](https://github.com/vitejs/vite/commit/0542e7c)), closes [#10211](https://github.com/vitejs/vite/issues/10211)


### Previous Changelogs


#### [3.2.0-beta.4](https://github.com/vitejs/vite/compare/v3.2.0-beta.3...v3.2.0-beta.4) (2022-10-24)

See [3.2.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v3.2.0-beta.4/packages/vite/CHANGELOG.md)


#### [3.2.0-beta.3](https://github.com/vitejs/vite/compare/v3.2.0-beta.2...v3.2.0-beta.3) (2022-10-20)

See [3.2.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v3.2.0-beta.4/packages/vite/CHANGELOG.md)


#### [3.2.0-beta.2](https://github.com/vitejs/vite/compare/v3.2.0-beta.1...v3.2.0-beta.2) (2022-10-14)

See [3.2.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v3.2.0-beta.4/packages/vite/CHANGELOG.md)


#### [3.2.0-beta.1](https://github.com/vitejs/vite/compare/v3.2.0-beta.0...v3.2.0-beta.1) (2022-10-10)

See [3.2.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v3.2.0-beta.4/packages/vite/CHANGELOG.md)


#### [3.2.0-beta.0](https://github.com/vitejs/vite/compare/v3.1.3...v3.2.0-beta.0) (2022-10-05)

See [3.2.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v3.2.0-beta.4/packages/vite/CHANGELOG.md)



## <small>3.1.3 (2022-09-19)</small>

* fix: esbuildOutputFromId for symlinked root (#10154) ([fc5310f](https://github.com/vitejs/vite/commit/fc5310f)), closes [#10154](https://github.com/vitejs/vite/issues/10154)
* fix(hmr): dedupe virtual modules in module graph (#10144) ([71f08e7](https://github.com/vitejs/vite/commit/71f08e7)), closes [#10144](https://github.com/vitejs/vite/issues/10144)
* fix(lib): respect `rollupOptions.input` in lib mode (#10116) ([c948e7d](https://github.com/vitejs/vite/commit/c948e7d)), closes [#10116](https://github.com/vitejs/vite/issues/10116)



## <small>3.1.2 (2022-09-17)</small>

* fix: use isOptimizable to ensure version query (#10141) ([23a51c6](https://github.com/vitejs/vite/commit/23a51c6)), closes [#10141](https://github.com/vitejs/vite/issues/10141)



## <small>3.1.1 (2022-09-15)</small>

* fix: ensure version query for relative node_modules imports (#10016) ([1b822d0](https://github.com/vitejs/vite/commit/1b822d0)), closes [#10016](https://github.com/vitejs/vite/issues/10016)
* fix: no quote on attrs (#10117) ([f541239](https://github.com/vitejs/vite/commit/f541239)), closes [#10117](https://github.com/vitejs/vite/issues/10117)
* fix: prevent error overlay style being overridden (fixes #9969) (#9971) ([a7706d0](https://github.com/vitejs/vite/commit/a7706d0)), closes [#9969](https://github.com/vitejs/vite/issues/9969) [#9971](https://github.com/vitejs/vite/issues/9971)
* fix: proxy to secured websocket server (#10045) ([9de9bc4](https://github.com/vitejs/vite/commit/9de9bc4)), closes [#10045](https://github.com/vitejs/vite/issues/10045)
* fix: replace white with reset (#10104) ([5d56e42](https://github.com/vitejs/vite/commit/5d56e42)), closes [#10104](https://github.com/vitejs/vite/issues/10104)
* fix(deps): update all non-major dependencies (#10077) ([caf00c8](https://github.com/vitejs/vite/commit/caf00c8)), closes [#10077](https://github.com/vitejs/vite/issues/10077)
* fix(deps): update all non-major dependencies (#9985) ([855f2f0](https://github.com/vitejs/vite/commit/855f2f0)), closes [#9985](https://github.com/vitejs/vite/issues/9985)
* fix(preview): send configured headers (#9976) ([0d20eae](https://github.com/vitejs/vite/commit/0d20eae)), closes [#9976](https://github.com/vitejs/vite/issues/9976)
* chore: cleanup old changelogs (#10056) ([9e65a41](https://github.com/vitejs/vite/commit/9e65a41)), closes [#10056](https://github.com/vitejs/vite/issues/10056)
* chore: update 3.1 changelog (#9994) ([44dbcbe](https://github.com/vitejs/vite/commit/44dbcbe)), closes [#9994](https://github.com/vitejs/vite/issues/9994)
* chore(deps): update @rollup/plugin-node-resolve to v14 (#10078) ([3390c87](https://github.com/vitejs/vite/commit/3390c87)), closes [#10078](https://github.com/vitejs/vite/issues/10078)
* refactor: config hook helper function (#9982) ([9c1be10](https://github.com/vitejs/vite/commit/9c1be10)), closes [#9982](https://github.com/vitejs/vite/issues/9982)
* refactor: optimize `async` and `await` in code (#9854) ([31f5ff3](https://github.com/vitejs/vite/commit/31f5ff3)), closes [#9854](https://github.com/vitejs/vite/issues/9854)



## 3.1.0 (2022-09-05)

### Main Changes

- Vite now uses [parse5](https://github.com/inikulin/parse5), which parses HTML in the same way as the latest browser versions. This migration gives us a more robust HTML story moving forward ([#9678](https://github.com/vitejs/vite/issues/9678)).
- Vite now supports using objects as hooks to change execution order ([#9634](https://github.com/vitejs/vite/issues/9634)). Check out the [RFC](https://github.com/vitejs/rfcs/discussions/12) and the implementation upstream at [rollup/rollup#4600](https://github.com/rollup/rollup/pull/4600) for details and rationale.
  ```js
    import { resolve } from 'node:path';
    import { readdir } from 'node:fs/promises';

    export default function getFilesOnDisk() {
      return {
        name: 'getFilesOnDisk',
        writeBundle: {
          // run this hook sequentially even if the hook is parallel
          sequential: true,
          // push this hook to the 'post' stage, after all normal hooks
          order: 'post',
          // hook implementation
          async handler({ dir }) {
            const topLevelFiles = await readdir(resolve(dir))
            console.log(topLevelFiles)
          }
        }
      }
    }
  ```
  Read the updated [Rollup Plugin docs](https://rollupjs.org/plugin-development/#build-hooks) for more information.

> **Note**
> After Vite 3.1, you are no longer going to see `[vite] hot updated` log messages in the browser console. These messages have been moved to the debug channel ([#8855](https://github.com/vitejs/vite/issues/8855)). Check your browser docs to [show debug logs](https://developer.chrome.com/docs/devtools/console/log/#level).

### Features

* feat(css): format error (#9909) ([632fedf](https://github.com/vitejs/vite/commit/632fedf)), closes [#9909](https://github.com/vitejs/vite/issues/9909)
* perf: bundle create-vite (#9034) ([37ac91e](https://github.com/vitejs/vite/commit/37ac91e)), closes [#9034](https://github.com/vitejs/vite/issues/9034)
* feat: stabilize server.resolvedUrls (#9866) ([c3f6731](https://github.com/vitejs/vite/commit/c3f6731)), closes [#9866](https://github.com/vitejs/vite/issues/9866)
* feat(client): use debug channel on hot updates (#8855) ([0452224](https://github.com/vitejs/vite/commit/0452224)), closes [#8855](https://github.com/vitejs/vite/issues/8855)
* feat: relax dep browser externals as warning (#9837) ([71cb374](https://github.com/vitejs/vite/commit/71cb374)), closes [#9837](https://github.com/vitejs/vite/issues/9837)
* feat: support object style hooks (#9634) ([757a92f](https://github.com/vitejs/vite/commit/757a92f)), closes [#9634](https://github.com/vitejs/vite/issues/9634)
* refactor: migrate from vue/compiler-dom to parse5 (#9678) ([05b3ce6](https://github.com/vitejs/vite/commit/05b3ce6)), closes [#9678](https://github.com/vitejs/vite/issues/9678)
* refactor: use `server.ssrTransform` (#9769) ([246a087](https://github.com/vitejs/vite/commit/246a087)), closes [#9769](https://github.com/vitejs/vite/issues/9769)
* perf: legacy avoid insert the entry module css (#9761) ([0765ab8](https://github.com/vitejs/vite/commit/0765ab8)), closes [#9761](https://github.com/vitejs/vite/issues/9761)

### Bug Fixes

* fix(css): remove css-post plugin sourcemap (#9914) ([c9521e7](https://github.com/vitejs/vite/commit/c9521e7)), closes [#9914](https://github.com/vitejs/vite/issues/9914)
* fix(hmr): duplicated modules because of query params mismatch (fixes #2255) (#9773) ([86bf776](https://github.com/vitejs/vite/commit/86bf776)), closes [#2255](https://github.com/vitejs/vite/issues/2255) [#9773](https://github.com/vitejs/vite/issues/9773)
* fix(ssr): enable `inlineDynamicImports` when input has length 1 (#9904) ([9ac5075](https://github.com/vitejs/vite/commit/9ac5075)), closes [#9904](https://github.com/vitejs/vite/issues/9904)
* fix(types): mark explicitImportRequired optional and experimental (#9962) ([7b618f0](https://github.com/vitejs/vite/commit/7b618f0)), closes [#9962](https://github.com/vitejs/vite/issues/9962)
* fix: bump esbuild to 0.15.6 (#9934) ([091537c](https://github.com/vitejs/vite/commit/091537c)), closes [#9934](https://github.com/vitejs/vite/issues/9934)
* refactor(hmr): simplify fetchUpdate (#9881) ([8872aba](https://github.com/vitejs/vite/commit/8872aba)), closes [#9881](https://github.com/vitejs/vite/issues/9881)
* fix: ensure version query for direct node_modules imports (#9848) ([e7712ff](https://github.com/vitejs/vite/commit/e7712ff)), closes [#9848](https://github.com/vitejs/vite/issues/9848)
* fix: escape glob path (#9842) ([6be971e](https://github.com/vitejs/vite/commit/6be971e)), closes [#9842](https://github.com/vitejs/vite/issues/9842)
* fix(build): build project path error (#9793) ([cc8800a](https://github.com/vitejs/vite/commit/cc8800a)), closes [#9793](https://github.com/vitejs/vite/issues/9793)
* fix(types): explicitly set Vite hooks' `this` to `void` (#9885) ([2d2f2e5](https://github.com/vitejs/vite/commit/2d2f2e5)), closes [#9885](https://github.com/vitejs/vite/issues/9885)
* fix: `completeSystemWrapPlugin` captures `function ()` (fixes #9807) (#9821) ([1ee0364](https://github.com/vitejs/vite/commit/1ee0364)), closes [#9807](https://github.com/vitejs/vite/issues/9807) [#9821](https://github.com/vitejs/vite/issues/9821)
* fix: `injectQuery` break relative path (#9760) ([61273b2](https://github.com/vitejs/vite/commit/61273b2)), closes [#9760](https://github.com/vitejs/vite/issues/9760)
* fix: close socket when client error handled (#9816) ([ba62be4](https://github.com/vitejs/vite/commit/ba62be4)), closes [#9816](https://github.com/vitejs/vite/issues/9816)
* fix: handle resolve optional peer deps (#9321) ([eec3886](https://github.com/vitejs/vite/commit/eec3886)), closes [#9321](https://github.com/vitejs/vite/issues/9321)
* fix: module graph ensureEntryFromUrl based on id (#9759) ([01857af](https://github.com/vitejs/vite/commit/01857af)), closes [#9759](https://github.com/vitejs/vite/issues/9759)
* fix: sanitize asset filenames (#9737) ([2f468bb](https://github.com/vitejs/vite/commit/2f468bb)), closes [#9737](https://github.com/vitejs/vite/issues/9737)
* fix: Skip inlining Git LFS placeholders (fix #9714) (#9795) ([9c7e43d](https://github.com/vitejs/vite/commit/9c7e43d)), closes [#9714](https://github.com/vitejs/vite/issues/9714) [#9795](https://github.com/vitejs/vite/issues/9795)
* fix(html): move importmap before module scripts (#9392) ([b386fba](https://github.com/vitejs/vite/commit/b386fba)), closes [#9392](https://github.com/vitejs/vite/issues/9392)

### Previous Changelogs

#### [3.1.0-beta.2](https://github.com/vitejs/vite/compare/v3.1.0-beta.1...v3.1.0-beta.2) (2022-09-02)

See [3.1.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v3.1.0-beta.2/packages/vite/CHANGELOG.md)

#### [3.1.0-beta.1](https://github.com/vitejs/vite/compare/v3.1.0-beta.0...v3.1.0-beta.1) (2022-08-29)

See [3.1.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v3.1.0-beta.1/packages/vite/CHANGELOG.md)

#### [3.1.0-beta.0](https://github.com/vitejs/vite/compare/v3.0.0...v3.1.0-beta.0) (2022-08-25)

See [3.1.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v3.1.0-beta.0/packages/vite/CHANGELOG.md)



## <small>3.0.9 (2022-08-19)</small>

* feat(ssr): warn if cant analyze dynamic import (#9738) ([e0ecb80](https://github.com/vitejs/vite/commit/e0ecb80)), closes [#9738](https://github.com/vitejs/vite/issues/9738)
* fix: dynamic import path contain ../ and its own directory (#9350) ([c6870f3](https://github.com/vitejs/vite/commit/c6870f3)), closes [#9350](https://github.com/vitejs/vite/issues/9350)
* fix: legacy no resolve asset urls (#9507) ([1d6a1eb](https://github.com/vitejs/vite/commit/1d6a1eb)), closes [#9507](https://github.com/vitejs/vite/issues/9507)
* fix: print error file path when using `rollupOptions.output.dir` (fix #9100) (#9111) ([3bffd14](https://github.com/vitejs/vite/commit/3bffd14)), closes [#9100](https://github.com/vitejs/vite/issues/9100) [#9111](https://github.com/vitejs/vite/issues/9111)
* fix: skip undefined proxy entry (#9622) ([e396d67](https://github.com/vitejs/vite/commit/e396d67)), closes [#9622](https://github.com/vitejs/vite/issues/9622)
* fix(hmr): duplicate link tags (#9697) ([9aa9515](https://github.com/vitejs/vite/commit/9aa9515)), closes [#9697](https://github.com/vitejs/vite/issues/9697)
* fix(import-analysis): escape quotes (#9729) ([21515f1](https://github.com/vitejs/vite/commit/21515f1)), closes [#9729](https://github.com/vitejs/vite/issues/9729)
* docs: fix typos in comments and documentation (#9711) ([0571232](https://github.com/vitejs/vite/commit/0571232)), closes [#9711](https://github.com/vitejs/vite/issues/9711)
* docs: update import.meta.glob jsdocs (#9709) ([15ff3a2](https://github.com/vitejs/vite/commit/15ff3a2)), closes [#9709](https://github.com/vitejs/vite/issues/9709)
* chore(deps): update all non-major dependencies (#9675) ([4e56e87](https://github.com/vitejs/vite/commit/4e56e87)), closes [#9675](https://github.com/vitejs/vite/issues/9675)
* chore(deps): update dependency es-module-lexer to v1 (#9576) ([1d8613f](https://github.com/vitejs/vite/commit/1d8613f)), closes [#9576](https://github.com/vitejs/vite/issues/9576)
* perf: avoid `ssrTransform` object allocation (#9706) ([6e58d9d](https://github.com/vitejs/vite/commit/6e58d9d)), closes [#9706](https://github.com/vitejs/vite/issues/9706)



## <small>3.0.8 (2022-08-16)</small>

* fix: allow ping to http from https website (#9561) ([f4b4405](https://github.com/vitejs/vite/commit/f4b4405)), closes [#9561](https://github.com/vitejs/vite/issues/9561)
* fix: use browser field if likely esm (fixes #9652) (#9653) ([85e387a](https://github.com/vitejs/vite/commit/85e387a)), closes [#9652](https://github.com/vitejs/vite/issues/9652) [#9653](https://github.com/vitejs/vite/issues/9653)
* fix(ssr-manifest): filter path undefined when dynamic import (#9655) ([1478a2f](https://github.com/vitejs/vite/commit/1478a2f)), closes [#9655](https://github.com/vitejs/vite/issues/9655)
* docs: update WSL2 watch limitation explanation (#8939) ([afbb87d](https://github.com/vitejs/vite/commit/afbb87d)), closes [#8939](https://github.com/vitejs/vite/issues/8939)



## <small>3.0.7 (2022-08-12)</small>

* chore: fix typo in error message (#9645) ([7121ee0](https://github.com/vitejs/vite/commit/7121ee0)), closes [#9645](https://github.com/vitejs/vite/issues/9645)
* fix(config): don't use file url for external files with cjs output (#9642) ([73ad707](https://github.com/vitejs/vite/commit/73ad707)), closes [#9642](https://github.com/vitejs/vite/issues/9642)



## <small>3.0.6 (2022-08-11)</small>

* chore: narrow down rollup version (#9637) ([fcf4d98](https://github.com/vitejs/vite/commit/fcf4d98)), closes [#9637](https://github.com/vitejs/vite/issues/9637)
* feat: show warning on 431 response (#9324) ([e8b61bb](https://github.com/vitejs/vite/commit/e8b61bb)), closes [#9324](https://github.com/vitejs/vite/issues/9324)
* fix: avoid using `import.meta.url` for relative assets if output is not ESM (fixes #9297) (#9381) ([6d95225](https://github.com/vitejs/vite/commit/6d95225)), closes [#9297](https://github.com/vitejs/vite/issues/9297) [#9381](https://github.com/vitejs/vite/issues/9381)
* fix: json HMR (fixes #9521) (#9610) ([e45d95f](https://github.com/vitejs/vite/commit/e45d95f)), closes [#9521](https://github.com/vitejs/vite/issues/9521) [#9610](https://github.com/vitejs/vite/issues/9610)
* fix: legacy no emit worker (#9500) ([9d0b18b](https://github.com/vitejs/vite/commit/9d0b18b)), closes [#9500](https://github.com/vitejs/vite/issues/9500)
* fix: use browser field if it is not likely UMD or CJS (fixes #9445) (#9459) ([c868e64](https://github.com/vitejs/vite/commit/c868e64)), closes [#9445](https://github.com/vitejs/vite/issues/9445) [#9459](https://github.com/vitejs/vite/issues/9459)
* fix(optimizer): ignore EACCES errors while scanner (fixes #8916) (#9509) ([4e6a77f](https://github.com/vitejs/vite/commit/4e6a77f)), closes [#8916](https://github.com/vitejs/vite/issues/8916) [#9509](https://github.com/vitejs/vite/issues/9509)
* fix(ssr): rename objectPattern dynamic key (fixes #9585) (#9609) ([ee7f78f](https://github.com/vitejs/vite/commit/ee7f78f)), closes [#9585](https://github.com/vitejs/vite/issues/9585) [#9609](https://github.com/vitejs/vite/issues/9609)



## <small>3.0.5 (2022-08-09)</small>

* fix: allow tree-shake glob eager css in js (#9547) ([2e309d6](https://github.com/vitejs/vite/commit/2e309d6)), closes [#9547](https://github.com/vitejs/vite/issues/9547)
* fix: ignore tsconfig target when bundling config (#9457) ([c5e7895](https://github.com/vitejs/vite/commit/c5e7895)), closes [#9457](https://github.com/vitejs/vite/issues/9457)
* fix: log worker plugins in debug mode (#9553) ([c1fa219](https://github.com/vitejs/vite/commit/c1fa219)), closes [#9553](https://github.com/vitejs/vite/issues/9553)
* fix: tree-shake modulepreload polyfill (#9531) ([1f11a70](https://github.com/vitejs/vite/commit/1f11a70)), closes [#9531](https://github.com/vitejs/vite/issues/9531)
* fix: update dep types (fixes #9475) (#9489) ([937cecc](https://github.com/vitejs/vite/commit/937cecc)), closes [#9475](https://github.com/vitejs/vite/issues/9475) [#9489](https://github.com/vitejs/vite/issues/9489)
* fix(build): normalized output log (#9594) ([8bae103](https://github.com/vitejs/vite/commit/8bae103)), closes [#9594](https://github.com/vitejs/vite/issues/9594)
* fix(config): try catch unlink after load (#9577) ([d35a1e2](https://github.com/vitejs/vite/commit/d35a1e2)), closes [#9577](https://github.com/vitejs/vite/issues/9577)
* fix(config): use file url for import path (fixes #9471) (#9473) ([22084a6](https://github.com/vitejs/vite/commit/22084a6)), closes [#9471](https://github.com/vitejs/vite/issues/9471) [#9473](https://github.com/vitejs/vite/issues/9473)
* fix(deps): update all non-major dependencies (#9575) ([8071325](https://github.com/vitejs/vite/commit/8071325)), closes [#9575](https://github.com/vitejs/vite/issues/9575)
* fix(ssr): check root import extension for external (#9494) ([ff89df5](https://github.com/vitejs/vite/commit/ff89df5)), closes [#9494](https://github.com/vitejs/vite/issues/9494)
* fix(ssr): use appendRight for import (#9554) ([dfec6ca](https://github.com/vitejs/vite/commit/dfec6ca)), closes [#9554](https://github.com/vitejs/vite/issues/9554)
* refactor(resolve): remove commonjs plugin handling (#9460) ([2042b91](https://github.com/vitejs/vite/commit/2042b91)), closes [#9460](https://github.com/vitejs/vite/issues/9460)
* chore: init imports var before use (#9569) ([905b8eb](https://github.com/vitejs/vite/commit/905b8eb)), closes [#9569](https://github.com/vitejs/vite/issues/9569)
* chore: node prefix lint (#9514) ([9e9cd23](https://github.com/vitejs/vite/commit/9e9cd23)), closes [#9514](https://github.com/vitejs/vite/issues/9514)
* chore: tidy up eslint config (#9468) ([f4addcf](https://github.com/vitejs/vite/commit/f4addcf)), closes [#9468](https://github.com/vitejs/vite/issues/9468)
* chore(deps): update all non-major dependencies (#9478) ([c530d16](https://github.com/vitejs/vite/commit/c530d16)), closes [#9478](https://github.com/vitejs/vite/issues/9478)
* docs: fix incomplete comment (#9466) ([5169c51](https://github.com/vitejs/vite/commit/5169c51)), closes [#9466](https://github.com/vitejs/vite/issues/9466)
* feat(ssr): debug failed node resolve (#9432) ([364aae1](https://github.com/vitejs/vite/commit/364aae1)), closes [#9432](https://github.com/vitejs/vite/issues/9432)



## <small>3.0.4 (2022-07-29)</small>

* fix: __VITE_PUBLIC_ASSET__hash__ in HTML (#9247) ([a2b24ee](https://github.com/vitejs/vite/commit/a2b24ee)), closes [#9247](https://github.com/vitejs/vite/issues/9247)
* fix: inline dynamic imports for ssr-webworker (fixes #9385) (#9401) ([cd69358](https://github.com/vitejs/vite/commit/cd69358)), closes [#9385](https://github.com/vitejs/vite/issues/9385) [#9401](https://github.com/vitejs/vite/issues/9401)
* fix: normalise css paths in manifest on windows (fixes #9295) (#9353) ([13e6450](https://github.com/vitejs/vite/commit/13e6450)), closes [#9295](https://github.com/vitejs/vite/issues/9295) [#9353](https://github.com/vitejs/vite/issues/9353)
* fix: support stylesheets with link tag and media/disable prop (#6751) ([e6c8965](https://github.com/vitejs/vite/commit/e6c8965)), closes [#6751](https://github.com/vitejs/vite/issues/6751)
* fix: url constructor import asset no as url (#9399) ([122c6e7](https://github.com/vitejs/vite/commit/122c6e7)), closes [#9399](https://github.com/vitejs/vite/issues/9399)
* fix(glob): server perf when globbing huge dirs (#9425) ([156a3a4](https://github.com/vitejs/vite/commit/156a3a4)), closes [#9425](https://github.com/vitejs/vite/issues/9425)
* fix(glob): support static template literals (#9352) ([183c6fb](https://github.com/vitejs/vite/commit/183c6fb)), closes [#9352](https://github.com/vitejs/vite/issues/9352)
* fix(ssr): allow virtual paths on node modules (#9405) ([e60368f](https://github.com/vitejs/vite/commit/e60368f)), closes [#9405](https://github.com/vitejs/vite/issues/9405)
* chore(deps): update all non-major dependencies (#9347) ([2fcb027](https://github.com/vitejs/vite/commit/2fcb027)), closes [#9347](https://github.com/vitejs/vite/issues/9347)



## <small>3.0.3 (2022-07-25)</small>

* fix: client type error (#9289) ([b82ddfb](https://github.com/vitejs/vite/commit/b82ddfb)), closes [#9289](https://github.com/vitejs/vite/issues/9289)
* fix: don't modify config (#9262) ([bbc8318](https://github.com/vitejs/vite/commit/bbc8318)), closes [#9262](https://github.com/vitejs/vite/issues/9262)
* fix: entries in ssr.external (#9286) ([d420f01](https://github.com/vitejs/vite/commit/d420f01)), closes [#9286](https://github.com/vitejs/vite/issues/9286)
* fix: externalize explicitly configured linked packages (#9346) ([c33e365](https://github.com/vitejs/vite/commit/c33e365)), closes [#9346](https://github.com/vitejs/vite/issues/9346)
* fix: make `resolveConfig()` concurrent safe (#9224) ([dfaeb2b](https://github.com/vitejs/vite/commit/dfaeb2b)), closes [#9224](https://github.com/vitejs/vite/issues/9224)
* fix: scanner and optimizer should skip wasm (#9257) ([c616077](https://github.com/vitejs/vite/commit/c616077)), closes [#9257](https://github.com/vitejs/vite/issues/9257)
* fix: ssrLoadModule executes code in non-strict mode, fixes #9197 (#9199) ([5866cfb](https://github.com/vitejs/vite/commit/5866cfb)), closes [#9197](https://github.com/vitejs/vite/issues/9197) [#9199](https://github.com/vitejs/vite/issues/9199)
* fix: support multiline dynamic imports (#9314) ([e66cf69](https://github.com/vitejs/vite/commit/e66cf69)), closes [#9314](https://github.com/vitejs/vite/issues/9314)
* fix: support vite client in safari 13 (#9315) ([2415193](https://github.com/vitejs/vite/commit/2415193)), closes [#9315](https://github.com/vitejs/vite/issues/9315)
* fix: worker relative base should use import.meta.url (#9204) ([0358b04](https://github.com/vitejs/vite/commit/0358b04)), closes [#9204](https://github.com/vitejs/vite/issues/9204)
* fix(glob): handle glob prop access (#9281) ([0580215](https://github.com/vitejs/vite/commit/0580215)), closes [#9281](https://github.com/vitejs/vite/issues/9281)
* fix(scan): handle .ts import as .js alias (#9282) ([0b083ca](https://github.com/vitejs/vite/commit/0b083ca)), closes [#9282](https://github.com/vitejs/vite/issues/9282)
* fix(ssr): no external symlink package (#9296) ([ea27701](https://github.com/vitejs/vite/commit/ea27701)), closes [#9296](https://github.com/vitejs/vite/issues/9296)
* chore: adjust comments/typos (#9325) ([ffb2ba3](https://github.com/vitejs/vite/commit/ffb2ba3)), closes [#9325](https://github.com/vitejs/vite/issues/9325)
* chore: fix code typos (#9033) ([ed02861](https://github.com/vitejs/vite/commit/ed02861)), closes [#9033](https://github.com/vitejs/vite/issues/9033)
* docs: fix `@rollup/plugin-commonjs` name (#9313) ([c417364](https://github.com/vitejs/vite/commit/c417364)), closes [#9313](https://github.com/vitejs/vite/issues/9313)
* docs: fix server options link (#9242) ([29db3ea](https://github.com/vitejs/vite/commit/29db3ea)), closes [#9242](https://github.com/vitejs/vite/issues/9242)
* docs: update browser baseline features (#9316) ([b82ee5d](https://github.com/vitejs/vite/commit/b82ee5d)), closes [#9316](https://github.com/vitejs/vite/issues/9316)
* feat: supports cts and mts files (#9268) ([0602017](https://github.com/vitejs/vite/commit/0602017)), closes [#9268](https://github.com/vitejs/vite/issues/9268)
* feat: worker config call config hook (#9212) ([3e510ab](https://github.com/vitejs/vite/commit/3e510ab)), closes [#9212](https://github.com/vitejs/vite/issues/9212)
* feat(css): use esbuild.log* options when minifying (#9210) ([88baa53](https://github.com/vitejs/vite/commit/88baa53)), closes [#9210](https://github.com/vitejs/vite/issues/9210)



## <small>3.0.2 (2022-07-18)</small>

* fix: fs serve only edit pathname (fixes #9148) (#9173) ([28cffc9](https://github.com/vitejs/vite/commit/28cffc9)), closes [#9148](https://github.com/vitejs/vite/issues/9148) [#9173](https://github.com/vitejs/vite/issues/9173)
* fix: prevent null pathname error (#9188) ([d66ffd0](https://github.com/vitejs/vite/commit/d66ffd0)), closes [#9188](https://github.com/vitejs/vite/issues/9188)
* fix: return 500 on proxy error only if possible (fixes #9172) (#9193) ([b2f6bdc](https://github.com/vitejs/vite/commit/b2f6bdc)), closes [#9172](https://github.com/vitejs/vite/issues/9172) [#9193](https://github.com/vitejs/vite/issues/9193)
* fix(deps): update all non-major dependencies (#9176) ([31d3b70](https://github.com/vitejs/vite/commit/31d3b70)), closes [#9176](https://github.com/vitejs/vite/issues/9176)
* fix(dev): build.ssr is set during dev, fix #9134 (#9187) ([99b0e67](https://github.com/vitejs/vite/commit/99b0e67)), closes [#9134](https://github.com/vitejs/vite/issues/9134) [#9187](https://github.com/vitejs/vite/issues/9187)
* fix(ssr): strip NULL_BYTE_PLACEHOLDER before import (#9124) ([c5f2dc7](https://github.com/vitejs/vite/commit/c5f2dc7)), closes [#9124](https://github.com/vitejs/vite/issues/9124)



## <small>3.0.1 (2022-07-18)</small>

* fix: avoid errors when loading the overlay code in workers (#9064) ([a52b45e](https://github.com/vitejs/vite/commit/a52b45e)), closes [#9064](https://github.com/vitejs/vite/issues/9064)
* fix: check server after tsconfig reload (#9106) ([d12d469](https://github.com/vitejs/vite/commit/d12d469)), closes [#9106](https://github.com/vitejs/vite/issues/9106)
* fix: disable keepNames in `vite:esbuild` (fixes #9164) (#9166) ([e6f3b02](https://github.com/vitejs/vite/commit/e6f3b02)), closes [#9164](https://github.com/vitejs/vite/issues/9164) [#9166](https://github.com/vitejs/vite/issues/9166)
* fix: externalize workspace relative import when bundle config (#9140) ([5a8a3ab](https://github.com/vitejs/vite/commit/5a8a3ab)), closes [#9140](https://github.com/vitejs/vite/issues/9140)
* fix: mention that Node.js 13/15 support is dropped (fixes #9113) (#9116) ([2826303](https://github.com/vitejs/vite/commit/2826303)), closes [#9113](https://github.com/vitejs/vite/issues/9113) [#9116](https://github.com/vitejs/vite/issues/9116)
* fix: resolve drive relative path (#9097) ([b393451](https://github.com/vitejs/vite/commit/b393451)), closes [#9097](https://github.com/vitejs/vite/issues/9097)
* fix: respect .mjs .cjs extension in all modes (#9141) ([5ea70b3](https://github.com/vitejs/vite/commit/5ea70b3)), closes [#9141](https://github.com/vitejs/vite/issues/9141)
* fix: return 500 on proxy error only if possible (fixes #9172) (#9175) ([d2f02a8](https://github.com/vitejs/vite/commit/d2f02a8)), closes [#9172](https://github.com/vitejs/vite/issues/9172) [#9175](https://github.com/vitejs/vite/issues/9175)
* fix: server.proxy ws error causes crash (#9123) ([c2426d1](https://github.com/vitejs/vite/commit/c2426d1)), closes [#9123](https://github.com/vitejs/vite/issues/9123)
* fix: ssr.external/noExternal should apply to packageName (#9146) ([5844d8e](https://github.com/vitejs/vite/commit/5844d8e)), closes [#9146](https://github.com/vitejs/vite/issues/9146)
* fix: use correct require extension to load config (#9118) ([ebf682e](https://github.com/vitejs/vite/commit/ebf682e)), closes [#9118](https://github.com/vitejs/vite/issues/9118)
* fix(esbuild): always support dynamic import and import meta (#9105) ([57a7936](https://github.com/vitejs/vite/commit/57a7936)), closes [#9105](https://github.com/vitejs/vite/issues/9105)
* feat: allow declaring dirname (#9154) ([1e078ad](https://github.com/vitejs/vite/commit/1e078ad)), closes [#9154](https://github.com/vitejs/vite/issues/9154)
* refactor: always load config with esbuild bundled code (#9121) ([a2b3131](https://github.com/vitejs/vite/commit/a2b3131)), closes [#9121](https://github.com/vitejs/vite/issues/9121)
* docs: update default for optimizeDeps.disabled (#9078) ([4fbf9a8](https://github.com/vitejs/vite/commit/4fbf9a8)), closes [#9078](https://github.com/vitejs/vite/issues/9078)
* chore: 3.0 release notes and bump peer deps (#9072) ([427ba26](https://github.com/vitejs/vite/commit/427ba26)), closes [#9072](https://github.com/vitejs/vite/issues/9072)



## 3.0.0 (2022-07-13)

### Main Changes

> **Vite 3 is out!**
> Read the [Vite 3 Announcement blog post](https://vitejs.dev/blog/announcing-vite3)

- New docs theme using [VitePress](https://vitepress.vuejs.org/) v1 alpha: https://vitejs.dev
- Vite CLI
  - The default dev server port is now 5173, with the preview server starting at 4173.
  - The default dev server host is now `localhost` instead of `127.0.0.1`.
- Compatibility
  - Vite no longer supports Node v12, which reached its EOL. Node 14.18+ is now required.
  - Vite is now published as ESM, with a CJS proxy to the ESM entry for compatibility.
  - The Modern Browser Baseline now targets browsers which support the [native ES Modules](https://caniuse.com/es6-module) and [native ESM dynamic import](https://caniuse.com/es6-module-dynamic-import) and [`import.meta`](https://caniuse.com/mdn-javascript_statements_import_meta).
  - JS file extensions in SSR and lib mode now use a valid extension (`js`, `mjs`, or `cjs`) for output JS entries and chunks based on their format and the package type.
- Architecture changes
  - Vite now avoids full reload during cold start when imports are injected by plugins in while crawling the initial statically imported modules ([#8869](https://github.com/vitejs/vite/issues/8869)).
  - Vite uses ESM for the SSR build by default, and previous [SSR externalization heuristics](https://vitejs.dev/guide/ssr.html#ssr-externals) are no longer needed.
- `import.meta.glob` has been improved, read about the new features in the [Glob Import Guide](https://vitejs.dev/guide/features.html#glob-import)
- The WebAssembly import API has been revised to avoid collisions with future standards. Read more in the [WebAssembly guide](https://vitejs.dev/guide/features.html#webassembly)
- Improved support for relative base.
- Experimental Features
  - [Build Advanced Base Options](https://vitejs.dev/guide/build.html#advanced-base-options)
  - [HMR Partial Accept](https://github.com/vitejs/vite/pull/7324)
  - Vite now allows the use of [esbuild to optimize dependencies during build time](https://vitejs.dev/guide/migration.html#using-esbuild-deps-optimization-at-build-time) avoiding the need of [`@rollup/plugin-commonjs`](https://github.com/rollup/plugins/tree/master/packages/commonjs), removing one of the difference id dependency handling between dev and prod.
- Bundle size reduction
  - Terser is now an optional dependency. If you use `build.minify: 'terser'`, you'll need to install it (`npm add -D terser`)
  - node-forge moved out of the monorepo to [@vitejs/plugin-basic-ssl](https://vitejs.dev/guide/migration.html#automatic-https-certificate-generation)
- Options that were [already deprecated in v2](https://vitejs.dev/guide/migration.html#config-options-changes) have been removed.

> **Note**
> Before updating, check out the [migration guide from v2](https://vitejs.dev/guide/migration)

### Features

* feat: expose server resolved urls (#8986) ([26bcdc3](https://github.com/vitejs/vite/commit/26bcdc3)), closes [#8986](https://github.com/vitejs/vite/issues/8986)
* feat: show ws connection error (#9007) ([da7c3ae](https://github.com/vitejs/vite/commit/da7c3ae)), closes [#9007](https://github.com/vitejs/vite/issues/9007)
* docs: update api-javascript (#8999) ([05b17df](https://github.com/vitejs/vite/commit/05b17df)), closes [#8999](https://github.com/vitejs/vite/issues/8999)
* refactor: opt-in optimizeDeps during build and SSR (#8965) ([f8c8cf2](https://github.com/vitejs/vite/commit/f8c8cf2)), closes [#8965](https://github.com/vitejs/vite/issues/8965)
* refactor!: move basic ssl setup to external plugin, fix #8532 (#8961) ([5c6cf5a](https://github.com/vitejs/vite/commit/5c6cf5a)), closes [#8532](https://github.com/vitejs/vite/issues/8532) [#8961](https://github.com/vitejs/vite/issues/8961)
* feat: avoid scanner during build and only optimize CJS in SSR (#8932) ([339d9e3](https://github.com/vitejs/vite/commit/339d9e3)), closes [#8932](https://github.com/vitejs/vite/issues/8932)
* feat: improved cold start using deps scanner (#8869) ([188f188](https://github.com/vitejs/vite/commit/188f188)), closes [#8869](https://github.com/vitejs/vite/issues/8869)
* feat: ssr.optimizeDeps (#8917) ([f280dd9](https://github.com/vitejs/vite/commit/f280dd9)), closes [#8917](https://github.com/vitejs/vite/issues/8917)
* feat: support import assertions (#8937) ([2390422](https://github.com/vitejs/vite/commit/2390422)), closes [#8937](https://github.com/vitejs/vite/issues/8937)
* feat: accept AcceptedPlugin type for postcss plugin (#8830) ([6886078](https://github.com/vitejs/vite/commit/6886078)), closes [#8830](https://github.com/vitejs/vite/issues/8830)
* feat: ssrBuild flag in config env (#8863) ([b6d655a](https://github.com/vitejs/vite/commit/b6d655a)), closes [#8863](https://github.com/vitejs/vite/issues/8863)
* feat: experimental.renderBuiltUrl (revised build base options) (#8762) ([895a7d6](https://github.com/vitejs/vite/commit/895a7d6)), closes [#8762](https://github.com/vitejs/vite/issues/8762)
* feat: respect esbuild minify config for css (#8811) ([d90409e](https://github.com/vitejs/vite/commit/d90409e)), closes [#8811](https://github.com/vitejs/vite/issues/8811)
* feat: use esbuild supported feature (#8665) ([2061d41](https://github.com/vitejs/vite/commit/2061d41)), closes [#8665](https://github.com/vitejs/vite/issues/8665)
* feat: respect esbuild minify config (#8754) ([8b77695](https://github.com/vitejs/vite/commit/8b77695)), closes [#8754](https://github.com/vitejs/vite/issues/8754)
* feat: update rollup commonjs plugin to v22  (#8743) ([d4dcdd1](https://github.com/vitejs/vite/commit/d4dcdd1)), closes [#8743](https://github.com/vitejs/vite/issues/8743)
* feat: enable tree-shaking for lib es (#8737) ([5dc0f72](https://github.com/vitejs/vite/commit/5dc0f72)), closes [#8737](https://github.com/vitejs/vite/issues/8737)
* feat: supports cts and mts config (#8729) ([c2b09db](https://github.com/vitejs/vite/commit/c2b09db)), closes [#8729](https://github.com/vitejs/vite/issues/8729)
* feat: bump minimum node version to 14.18.0 (#8662) ([8a05432](https://github.com/vitejs/vite/commit/8a05432)), closes [#8662](https://github.com/vitejs/vite/issues/8662)
* feat: experimental.buildAdvancedBaseOptions (#8450) ([8ef7333](https://github.com/vitejs/vite/commit/8ef7333)), closes [#8450](https://github.com/vitejs/vite/issues/8450)
* feat: export esbuildVersion and rollupVersion (#8675) ([15ebe1e](https://github.com/vitejs/vite/commit/15ebe1e)), closes [#8675](https://github.com/vitejs/vite/issues/8675)
* feat: print resolved address for localhost (#8647) ([eb52d36](https://github.com/vitejs/vite/commit/eb52d36)), closes [#8647](https://github.com/vitejs/vite/issues/8647)
* feat(hmr): experimental.hmrPartialAccept (#7324) ([83dab7e](https://github.com/vitejs/vite/commit/83dab7e)), closes [#7324](https://github.com/vitejs/vite/issues/7324)
* refactor: type client maps (#8626) ([cf87882](https://github.com/vitejs/vite/commit/cf87882)), closes [#8626](https://github.com/vitejs/vite/issues/8626)
* feat: cleaner default dev output (#8638) ([dbd9688](https://github.com/vitejs/vite/commit/dbd9688)), closes [#8638](https://github.com/vitejs/vite/issues/8638)
* feat: legacy options to revert to v2 strategies (#8623) ([993b842](https://github.com/vitejs/vite/commit/993b842)), closes [#8623](https://github.com/vitejs/vite/issues/8623)
* feat: support async plugins (#8574) ([caa8a58](https://github.com/vitejs/vite/commit/caa8a58)), closes [#8574](https://github.com/vitejs/vite/issues/8574)
* feat: support cjs noExternal in SSR dev, fix #2579 (#8430) ([11d2191](https://github.com/vitejs/vite/commit/11d2191)), closes [#2579](https://github.com/vitejs/vite/issues/2579) [#8430](https://github.com/vitejs/vite/issues/8430)
* feat(dev): added assets to manifest (#6649) ([cdf744d](https://github.com/vitejs/vite/commit/cdf744d)), closes [#6649](https://github.com/vitejs/vite/issues/6649)
* feat!: appType (spa, mpa, custom), boolean middlewareMode (#8452) ([14db473](https://github.com/vitejs/vite/commit/14db473)), closes [#8452](https://github.com/vitejs/vite/issues/8452)
* feat: 500 response if the node proxy request fails (#7398) ([73e1775](https://github.com/vitejs/vite/commit/73e1775)), closes [#7398](https://github.com/vitejs/vite/issues/7398)
* feat: expose createFilter util (#8562) ([c5c424a](https://github.com/vitejs/vite/commit/c5c424a)), closes [#8562](https://github.com/vitejs/vite/issues/8562)
* feat: better config `__dirname` support (#8442) ([51e9195](https://github.com/vitejs/vite/commit/51e9195)), closes [#8442](https://github.com/vitejs/vite/issues/8442)
* feat: expose `version` (#8456) ([e992594](https://github.com/vitejs/vite/commit/e992594)), closes [#8456](https://github.com/vitejs/vite/issues/8456)
* feat: handle named imports of builtin modules (#8338) ([e2e44ff](https://github.com/vitejs/vite/commit/e2e44ff)), closes [#8338](https://github.com/vitejs/vite/issues/8338)
* feat: preserve process env vars in lib build (#8090) ([908c9e4](https://github.com/vitejs/vite/commit/908c9e4)), closes [#8090](https://github.com/vitejs/vite/issues/8090)
* refactor!: make terser an optional dependency (#8049) ([164f528](https://github.com/vitejs/vite/commit/164f528)), closes [#8049](https://github.com/vitejs/vite/issues/8049)
* chore: resolve ssr options (#8455) ([d97e402](https://github.com/vitejs/vite/commit/d97e402)), closes [#8455](https://github.com/vitejs/vite/issues/8455)
* perf: disable postcss sourcemap when unused (#8451) ([64fc61c](https://github.com/vitejs/vite/commit/64fc61c)), closes [#8451](https://github.com/vitejs/vite/issues/8451)
* feat: add ssr.format to force esm output for ssr (#6812) ([337b197](https://github.com/vitejs/vite/commit/337b197)), closes [#6812](https://github.com/vitejs/vite/issues/6812)
* feat: default esm SSR build, simplified externalization (#8348) ([f8c92d1](https://github.com/vitejs/vite/commit/f8c92d1)), closes [#8348](https://github.com/vitejs/vite/issues/8348)
* feat: derive proper js extension from package type (#8382) ([95cdd81](https://github.com/vitejs/vite/commit/95cdd81)), closes [#8382](https://github.com/vitejs/vite/issues/8382)
* feat: ssr build using optimized deps (#8403) ([6a5a5b5](https://github.com/vitejs/vite/commit/6a5a5b5)), closes [#8403](https://github.com/vitejs/vite/issues/8403)
* refactor: `ExportData.imports` to `ExportData.hasImports` (#8355) ([168de2d](https://github.com/vitejs/vite/commit/168de2d)), closes [#8355](https://github.com/vitejs/vite/issues/8355)
* feat: scan free dev server (#8319) ([3f742b6](https://github.com/vitejs/vite/commit/3f742b6)), closes [#8319](https://github.com/vitejs/vite/issues/8319)
* feat: non-blocking esbuild optimization at build time (#8280) ([909cf9c](https://github.com/vitejs/vite/commit/909cf9c)), closes [#8280](https://github.com/vitejs/vite/issues/8280)
* feat: non-blocking needs interop (#7568) ([531cd7b](https://github.com/vitejs/vite/commit/531cd7b)), closes [#7568](https://github.com/vitejs/vite/issues/7568)
* refactor(cli): improve output aesthetics (#6997) ([809ab47](https://github.com/vitejs/vite/commit/809ab47)), closes [#6997](https://github.com/vitejs/vite/issues/6997)
* dx: sourcemap combine debug utils (#8307) ([45dba50](https://github.com/vitejs/vite/commit/45dba50)), closes [#8307](https://github.com/vitejs/vite/issues/8307)
* feat: sourcemap for importAnalysis (#8258) ([a4e4d39](https://github.com/vitejs/vite/commit/a4e4d39)), closes [#8258](https://github.com/vitejs/vite/issues/8258)
* feat: spa option, `preview` and `dev` for MPA and SSR apps (#8217) ([d7cba46](https://github.com/vitejs/vite/commit/d7cba46)), closes [#8217](https://github.com/vitejs/vite/issues/8217)
* feat: vite connected logs changed to console.debug (#7733) ([9f00c41](https://github.com/vitejs/vite/commit/9f00c41)), closes [#7733](https://github.com/vitejs/vite/issues/7733)
* feat: worker support query url (#7914) ([95297dd](https://github.com/vitejs/vite/commit/95297dd)), closes [#7914](https://github.com/vitejs/vite/issues/7914)
* feat(wasm): new wasm plugin (`.wasm?init`) (#8219) ([75c3bf6](https://github.com/vitejs/vite/commit/75c3bf6)), closes [#8219](https://github.com/vitejs/vite/issues/8219)
* build!: bump targets (#8045) ([66efd69](https://github.com/vitejs/vite/commit/66efd69)), closes [#8045](https://github.com/vitejs/vite/issues/8045)
* feat!: migrate to ESM (#8178) ([76fdc27](https://github.com/vitejs/vite/commit/76fdc27)), closes [#8178](https://github.com/vitejs/vite/issues/8178)
* feat!: relative base (#7644) ([09648c2](https://github.com/vitejs/vite/commit/09648c2)), closes [#7644](https://github.com/vitejs/vite/issues/7644)
* feat(css): warn if url rewrite has no importer (#8183) ([0858450](https://github.com/vitejs/vite/commit/0858450)), closes [#8183](https://github.com/vitejs/vite/issues/8183)
* feat: allow any JS identifier in define, not ASCII-only (#5972) ([95eb45b](https://github.com/vitejs/vite/commit/95eb45b)), closes [#5972](https://github.com/vitejs/vite/issues/5972)
* feat: enable `generatedCode: 'es2015'` for rollup build (#5018) ([46d5e67](https://github.com/vitejs/vite/commit/46d5e67)), closes [#5018](https://github.com/vitejs/vite/issues/5018)
* feat: rework `dynamic-import-vars` (#7756) ([80d113b](https://github.com/vitejs/vite/commit/80d113b)), closes [#7756](https://github.com/vitejs/vite/issues/7756)
* feat: worker emit fileName with config (#7804) ([04c2edd](https://github.com/vitejs/vite/commit/04c2edd)), closes [#7804](https://github.com/vitejs/vite/issues/7804)
* feat(glob-import): support `{ import: '*' }` (#8071) ([0b78b2a](https://github.com/vitejs/vite/commit/0b78b2a)), closes [#8071](https://github.com/vitejs/vite/issues/8071)
* build!: remove node v12 support (#7833) ([eeac2d2](https://github.com/vitejs/vite/commit/eeac2d2)), closes [#7833](https://github.com/vitejs/vite/issues/7833)
* feat!: rework `import.meta.glob` (#7537) ([330e0a9](https://github.com/vitejs/vite/commit/330e0a9)), closes [#7537](https://github.com/vitejs/vite/issues/7537)
* feat!: vite dev default port is now 5173 (#8148) ([1cc2e2d](https://github.com/vitejs/vite/commit/1cc2e2d)), closes [#8148](https://github.com/vitejs/vite/issues/8148)
* refactor: remove deprecated api for 3.0 (#5868) ([b5c3709](https://github.com/vitejs/vite/commit/b5c3709)), closes [#5868](https://github.com/vitejs/vite/issues/5868)
* chore: stabilize experimental api (#7707) ([b902932](https://github.com/vitejs/vite/commit/b902932)), closes [#7707](https://github.com/vitejs/vite/issues/7707)
* test: migrate to vitest (#8076) ([8148f67](https://github.com/vitejs/vite/commit/8148f67)), closes [#8076](https://github.com/vitejs/vite/issues/8076)

### Bug Fixes

* fix: prevent production node_env in serve (#9066) ([7662998](https://github.com/vitejs/vite/commit/7662998)), closes [#9066](https://github.com/vitejs/vite/issues/9066)
* fix: reload on restart with middleware mode (fixes #9038) (#9040) ([e372693](https://github.com/vitejs/vite/commit/e372693)), closes [#9038](https://github.com/vitejs/vite/issues/9038) [#9040](https://github.com/vitejs/vite/issues/9040)
* fix: remove ws is already closed error (#9041) ([45b8b53](https://github.com/vitejs/vite/commit/45b8b53)), closes [#9041](https://github.com/vitejs/vite/issues/9041)
* fix(ssr): sourcemap content (fixes #8657) (#8997) ([aff4544](https://github.com/vitejs/vite/commit/aff4544)), closes [#8657](https://github.com/vitejs/vite/issues/8657) [#8997](https://github.com/vitejs/vite/issues/8997)
* fix: respect explicitly external/noExternal config (#8983) ([e369880](https://github.com/vitejs/vite/commit/e369880)), closes [#8983](https://github.com/vitejs/vite/issues/8983)
* fix: cjs interop export names local clash, fix #8950 (#8953) ([2185f72](https://github.com/vitejs/vite/commit/2185f72)), closes [#8950](https://github.com/vitejs/vite/issues/8950) [#8953](https://github.com/vitejs/vite/issues/8953)
* fix: handle context resolve options (#8966) ([57c6c15](https://github.com/vitejs/vite/commit/57c6c15)), closes [#8966](https://github.com/vitejs/vite/issues/8966)
* fix: re-encode url to prevent fs.allow bypass (fixes #8498) (#8979) ([b835699](https://github.com/vitejs/vite/commit/b835699)), closes [#8498](https://github.com/vitejs/vite/issues/8498) [#8979](https://github.com/vitejs/vite/issues/8979)
* fix(scan): detect import .ts as .js (#8969) ([752af6c](https://github.com/vitejs/vite/commit/752af6c)), closes [#8969](https://github.com/vitejs/vite/issues/8969)
* fix: ssrBuild is optional, avoid breaking VitePress (#8912) ([722f514](https://github.com/vitejs/vite/commit/722f514)), closes [#8912](https://github.com/vitejs/vite/issues/8912)
* fix(css): always use css module content (#8936) ([6e0dd3a](https://github.com/vitejs/vite/commit/6e0dd3a)), closes [#8936](https://github.com/vitejs/vite/issues/8936)
* fix: avoid optimizing non-optimizable external deps (#8860) ([cd8d63b](https://github.com/vitejs/vite/commit/cd8d63b)), closes [#8860](https://github.com/vitejs/vite/issues/8860)
* fix: ensure define overrides import.meta in build (#8892) ([7d810a9](https://github.com/vitejs/vite/commit/7d810a9)), closes [#8892](https://github.com/vitejs/vite/issues/8892)
* fix: ignore Playwright test results directory (#8778) ([314c09c](https://github.com/vitejs/vite/commit/314c09c)), closes [#8778](https://github.com/vitejs/vite/issues/8778)
* fix: node platform for ssr dev regression (#8840) ([7257fd8](https://github.com/vitejs/vite/commit/7257fd8)), closes [#8840](https://github.com/vitejs/vite/issues/8840)
* fix: optimize deps on dev SSR, builtin imports in node (#8854) ([d49856c](https://github.com/vitejs/vite/commit/d49856c)), closes [#8854](https://github.com/vitejs/vite/issues/8854)
* fix: prevent crash when the pad amount is negative (#8747) ([3af6a1b](https://github.com/vitejs/vite/commit/3af6a1b)), closes [#8747](https://github.com/vitejs/vite/issues/8747)
* fix: reverts #8278 ([a0da2f0](https://github.com/vitejs/vite/commit/a0da2f0)), closes [#8278](https://github.com/vitejs/vite/issues/8278)
* fix: server.force deprecation and force on restart API (#8842) ([c94f564](https://github.com/vitejs/vite/commit/c94f564)), closes [#8842](https://github.com/vitejs/vite/issues/8842)
* fix(deps): update all non-major dependencies (#8802) ([a4a634d](https://github.com/vitejs/vite/commit/a4a634d)), closes [#8802](https://github.com/vitejs/vite/issues/8802)
* fix(hmr): set isSelfAccepting unless it is delayed (#8898) ([ae34565](https://github.com/vitejs/vite/commit/ae34565)), closes [#8898](https://github.com/vitejs/vite/issues/8898)
* fix(worker): dont throw on `import.meta.url` in ssr (#8846) ([ef749ed](https://github.com/vitejs/vite/commit/ef749ed)), closes [#8846](https://github.com/vitejs/vite/issues/8846)
* fix: deps optimizer should wait on entries (#8822) ([2db1b5b](https://github.com/vitejs/vite/commit/2db1b5b)), closes [#8822](https://github.com/vitejs/vite/issues/8822)
* fix: incorrectly resolving `knownJsSrcRE` files from root (fixes #4161) (#8808) ([e1e426e](https://github.com/vitejs/vite/commit/e1e426e)), closes [#4161](https://github.com/vitejs/vite/issues/4161) [#8808](https://github.com/vitejs/vite/issues/8808)
* fix: /@fs/ dir traversal with escaped chars (fixes #8498) (#8804) ([6851009](https://github.com/vitejs/vite/commit/6851009)), closes [#8498](https://github.com/vitejs/vite/issues/8498) [#8804](https://github.com/vitejs/vite/issues/8804)
* fix: preserve extension of css assets in the manifest (#8768) ([9508549](https://github.com/vitejs/vite/commit/9508549)), closes [#8768](https://github.com/vitejs/vite/issues/8768)
* fix: always remove temp config (#8782) ([2c2a86b](https://github.com/vitejs/vite/commit/2c2a86b)), closes [#8782](https://github.com/vitejs/vite/issues/8782)
* fix: ensure deps optimizer first run, fixes #8750 (#8775) ([3f689a4](https://github.com/vitejs/vite/commit/3f689a4)), closes [#8750](https://github.com/vitejs/vite/issues/8750) [#8775](https://github.com/vitejs/vite/issues/8775)
* fix: remove buildTimeImportMetaUrl (#8785) ([cd32095](https://github.com/vitejs/vite/commit/cd32095)), closes [#8785](https://github.com/vitejs/vite/issues/8785)
* fix: skip inline html (#8789) ([4a6408b](https://github.com/vitejs/vite/commit/4a6408b)), closes [#8789](https://github.com/vitejs/vite/issues/8789)
* fix(optimizer): only run require-import conversion if require'd (#8795) ([7ae0d3e](https://github.com/vitejs/vite/commit/7ae0d3e)), closes [#8795](https://github.com/vitejs/vite/issues/8795)
* perf: avoid sourcemap chains during dev (#8796) ([1566f61](https://github.com/vitejs/vite/commit/1566f61)), closes [#8796](https://github.com/vitejs/vite/issues/8796)
* perf(lib): improve helper inject regex (#8741) ([19fc7e5](https://github.com/vitejs/vite/commit/19fc7e5)), closes [#8741](https://github.com/vitejs/vite/issues/8741)
* fix: avoid type mismatch with Rollup (fix #7843) (#8701) ([87e51f7](https://github.com/vitejs/vite/commit/87e51f7)), closes [#7843](https://github.com/vitejs/vite/issues/7843) [#8701](https://github.com/vitejs/vite/issues/8701)
* fix: optimizeDeps.entries transformRequest url (fix #8719) (#8748) ([9208c3b](https://github.com/vitejs/vite/commit/9208c3b)), closes [#8719](https://github.com/vitejs/vite/issues/8719) [#8748](https://github.com/vitejs/vite/issues/8748)
* fix(hmr): __HMR_PORT__ should not be `'undefined'` (#8761) ([3271266](https://github.com/vitejs/vite/commit/3271266)), closes [#8761](https://github.com/vitejs/vite/issues/8761)
* fix: respect `rollupOptions.external` for transitive dependencies (#8679) ([4f9097b](https://github.com/vitejs/vite/commit/4f9097b)), closes [#8679](https://github.com/vitejs/vite/issues/8679)
* fix: use esbuild platform browser/node instead of neutral (#8714) ([a201cd4](https://github.com/vitejs/vite/commit/a201cd4)), closes [#8714](https://github.com/vitejs/vite/issues/8714)
* fix: disable inlineDynamicImports for ssr.target = node (#8641) ([3b41a8e](https://github.com/vitejs/vite/commit/3b41a8e)), closes [#8641](https://github.com/vitejs/vite/issues/8641)
* fix: infer hmr ws target by client location (#8650) ([4061ee0](https://github.com/vitejs/vite/commit/4061ee0)), closes [#8650](https://github.com/vitejs/vite/issues/8650)
* fix: non-relative base public paths in CSS files (#8682) ([d11d6ea](https://github.com/vitejs/vite/commit/d11d6ea)), closes [#8682](https://github.com/vitejs/vite/issues/8682)
* fix: SSR with relative base (#8683) ([c1667bb](https://github.com/vitejs/vite/commit/c1667bb)), closes [#8683](https://github.com/vitejs/vite/issues/8683)
* fix: filter of BOM tags in json plugin (#8628) ([e10530b](https://github.com/vitejs/vite/commit/e10530b)), closes [#8628](https://github.com/vitejs/vite/issues/8628)
* fix: revert #5902, fix #8243 (#8654) ([1b820da](https://github.com/vitejs/vite/commit/1b820da)), closes [#8243](https://github.com/vitejs/vite/issues/8243) [#8654](https://github.com/vitejs/vite/issues/8654)
* fix(optimizer): use simple browser external shim in prod (#8630) ([a32c4ba](https://github.com/vitejs/vite/commit/a32c4ba)), closes [#8630](https://github.com/vitejs/vite/issues/8630)
* fix(server): skip localhost verbatim dns lookup (#8642) ([7632247](https://github.com/vitejs/vite/commit/7632247)), closes [#8642](https://github.com/vitejs/vite/issues/8642)
* fix(wasm): support inlined WASM in Node < v16 (fix #8620) (#8622) ([f586b14](https://github.com/vitejs/vite/commit/f586b14)), closes [#8620](https://github.com/vitejs/vite/issues/8620) [#8622](https://github.com/vitejs/vite/issues/8622)
* fix: allow cache overlap in parallel builds (#8592) ([2dd0b49](https://github.com/vitejs/vite/commit/2dd0b49)), closes [#8592](https://github.com/vitejs/vite/issues/8592)
* fix: avoid replacing defines and NODE_ENV in optimized deps (fix #8593) (#8606) ([739175b](https://github.com/vitejs/vite/commit/739175b)), closes [#8593](https://github.com/vitejs/vite/issues/8593) [#8606](https://github.com/vitejs/vite/issues/8606)
* fix: sequential injection of tags in transformIndexHtml (#5851) (#6901) ([649c7f6](https://github.com/vitejs/vite/commit/649c7f6)), closes [#5851](https://github.com/vitejs/vite/issues/5851) [#6901](https://github.com/vitejs/vite/issues/6901)
* fix(asset): respect assetFileNames if rollupOptions.output is an array (#8561) ([4e6c26f](https://github.com/vitejs/vite/commit/4e6c26f)), closes [#8561](https://github.com/vitejs/vite/issues/8561)
* fix(css): escape pattern chars from base path in postcss dir-dependency messages (#7081) ([5151e74](https://github.com/vitejs/vite/commit/5151e74)), closes [#7081](https://github.com/vitejs/vite/issues/7081)
* fix(optimizer): browser mapping for yarn pnp (#6493) ([c1c7af3](https://github.com/vitejs/vite/commit/c1c7af3)), closes [#6493](https://github.com/vitejs/vite/issues/6493)
* fix: add missed JPEG file extensions to `KNOWN_ASSET_TYPES` (#8565) ([2dfc015](https://github.com/vitejs/vite/commit/2dfc015)), closes [#8565](https://github.com/vitejs/vite/issues/8565)
* fix: default export module transformation for vitest spy (#8567) ([d357e33](https://github.com/vitejs/vite/commit/d357e33)), closes [#8567](https://github.com/vitejs/vite/issues/8567)
* fix: default host to `localhost` instead of `127.0.0.1` (#8543) ([49c0896](https://github.com/vitejs/vite/commit/49c0896)), closes [#8543](https://github.com/vitejs/vite/issues/8543)
* fix: dont handle sigterm in middleware mode (#8550) ([c6f43dd](https://github.com/vitejs/vite/commit/c6f43dd)), closes [#8550](https://github.com/vitejs/vite/issues/8550)
* fix: mime missing extensions (#8568) ([acf3024](https://github.com/vitejs/vite/commit/acf3024)), closes [#8568](https://github.com/vitejs/vite/issues/8568)
* fix: objurl for type module, and concurrent tests (#8541) ([26ecd5a](https://github.com/vitejs/vite/commit/26ecd5a)), closes [#8541](https://github.com/vitejs/vite/issues/8541)
* fix: outdated optimized dep removed from module graph (#8533) ([3f4d22d](https://github.com/vitejs/vite/commit/3f4d22d)), closes [#8533](https://github.com/vitejs/vite/issues/8533)
* fix(config): only rewrite .js loader in `loadConfigFromBundledFile` (#8556) ([2548dd3](https://github.com/vitejs/vite/commit/2548dd3)), closes [#8556](https://github.com/vitejs/vite/issues/8556)
* fix(deps): update all non-major dependencies (#8558) ([9a1fd4c](https://github.com/vitejs/vite/commit/9a1fd4c)), closes [#8558](https://github.com/vitejs/vite/issues/8558)
* fix(ssr): dont replace rollup input (#7275) ([9a88afa](https://github.com/vitejs/vite/commit/9a88afa)), closes [#7275](https://github.com/vitejs/vite/issues/7275)
* fix: deps optimizer idle logic for workers (fix #8479) (#8511) ([1e05548](https://github.com/vitejs/vite/commit/1e05548)), closes [#8479](https://github.com/vitejs/vite/issues/8479) [#8511](https://github.com/vitejs/vite/issues/8511)
* fix: not match \n when injecting esbuild helpers (#8414) ([5a57626](https://github.com/vitejs/vite/commit/5a57626)), closes [#8414](https://github.com/vitejs/vite/issues/8414)
* fix: respect optimize deps entries (#8489) ([fba82d0](https://github.com/vitejs/vite/commit/fba82d0)), closes [#8489](https://github.com/vitejs/vite/issues/8489)
* fix(optimizer): encode `_` and `.` in different way (#8508) ([9065b37](https://github.com/vitejs/vite/commit/9065b37)), closes [#8508](https://github.com/vitejs/vite/issues/8508)
* fix(optimizer): external require-import conversion (fixes #2492, #3409) (#8459) ([1061bbd](https://github.com/vitejs/vite/commit/1061bbd)), closes [#2492](https://github.com/vitejs/vite/issues/2492) [#3409](https://github.com/vitejs/vite/issues/3409) [#8459](https://github.com/vitejs/vite/issues/8459)
* fix: make array `acornInjectPlugins` work (fixes #8410) (#8415) ([08d594b](https://github.com/vitejs/vite/commit/08d594b)), closes [#8410](https://github.com/vitejs/vite/issues/8410) [#8415](https://github.com/vitejs/vite/issues/8415)
* fix: SSR deep imports externalization (fixes #8420) (#8421) ([89d6711](https://github.com/vitejs/vite/commit/89d6711)), closes [#8420](https://github.com/vitejs/vite/issues/8420) [#8421](https://github.com/vitejs/vite/issues/8421)
* fix: `import.meta.accept()` -> `import.meta.hot.accept()` (#8361) ([c5185cf](https://github.com/vitejs/vite/commit/c5185cf)), closes [#8361](https://github.com/vitejs/vite/issues/8361)
* fix: return type of `handleHMRUpdate` (#8367) ([79d5ce1](https://github.com/vitejs/vite/commit/79d5ce1)), closes [#8367](https://github.com/vitejs/vite/issues/8367)
* fix: sourcemap source point to null (#8299) ([356b896](https://github.com/vitejs/vite/commit/356b896)), closes [#8299](https://github.com/vitejs/vite/issues/8299)
* fix: ssr-manifest no base (#8371) ([37eb5b3](https://github.com/vitejs/vite/commit/37eb5b3)), closes [#8371](https://github.com/vitejs/vite/issues/8371)
* fix(deps): update all non-major dependencies (#8391) ([842f995](https://github.com/vitejs/vite/commit/842f995)), closes [#8391](https://github.com/vitejs/vite/issues/8391)
* fix: preserve annotations during build deps optimization (#8358) ([334cd9f](https://github.com/vitejs/vite/commit/334cd9f)), closes [#8358](https://github.com/vitejs/vite/issues/8358)
* fix: missing types for `es-module-lexer` (fixes #8349) (#8352) ([df2cc3d](https://github.com/vitejs/vite/commit/df2cc3d)), closes [#8349](https://github.com/vitejs/vite/issues/8349) [#8352](https://github.com/vitejs/vite/issues/8352)
* fix(optimizer): transpile before calling `transformGlobImport` (#8343) ([1dbc7cc](https://github.com/vitejs/vite/commit/1dbc7cc)), closes [#8343](https://github.com/vitejs/vite/issues/8343)
* fix(deps): update all non-major dependencies (#8281) ([c68db4d](https://github.com/vitejs/vite/commit/c68db4d)), closes [#8281](https://github.com/vitejs/vite/issues/8281)
* fix: expose client dist in `exports` (#8324) ([689adc0](https://github.com/vitejs/vite/commit/689adc0)), closes [#8324](https://github.com/vitejs/vite/issues/8324)
* fix(cjs): build cjs for `loadEnv` (#8305) ([80dd2df](https://github.com/vitejs/vite/commit/80dd2df)), closes [#8305](https://github.com/vitejs/vite/issues/8305)
* fix: correctly replace process.env.NODE_ENV (#8283) ([ec52baa](https://github.com/vitejs/vite/commit/ec52baa)), closes [#8283](https://github.com/vitejs/vite/issues/8283)
* fix: dev sourcemap (#8269) ([505f75e](https://github.com/vitejs/vite/commit/505f75e)), closes [#8269](https://github.com/vitejs/vite/issues/8269)
* fix: glob types (#8257) ([03b227e](https://github.com/vitejs/vite/commit/03b227e)), closes [#8257](https://github.com/vitejs/vite/issues/8257)
* fix: srcset handling in html (#6419) ([a0ee4ff](https://github.com/vitejs/vite/commit/a0ee4ff)), closes [#6419](https://github.com/vitejs/vite/issues/6419)
* fix: support set NODE_ENV in scripts when custom mode option (#8218) ([adcf041](https://github.com/vitejs/vite/commit/adcf041)), closes [#8218](https://github.com/vitejs/vite/issues/8218)
* fix(hmr): catch thrown errors when connecting to hmr websocket (#7111) ([4bc9284](https://github.com/vitejs/vite/commit/4bc9284)), closes [#7111](https://github.com/vitejs/vite/issues/7111)
* fix(plugin-legacy): respect `entryFileNames` for polyfill chunks (#8247) ([baa9632](https://github.com/vitejs/vite/commit/baa9632)), closes [#8247](https://github.com/vitejs/vite/issues/8247)
* fix(plugin-react): broken optimized deps dir check (#8255) ([9e2a1ea](https://github.com/vitejs/vite/commit/9e2a1ea)), closes [#8255](https://github.com/vitejs/vite/issues/8255)
* fix!: do not fixStacktrace by default (#7995) ([23f8e08](https://github.com/vitejs/vite/commit/23f8e08)), closes [#7995](https://github.com/vitejs/vite/issues/7995)
* fix(glob): properly handles tailing comma (#8181) ([462be8e](https://github.com/vitejs/vite/commit/462be8e)), closes [#8181](https://github.com/vitejs/vite/issues/8181)
* fix: add hash to lib chunk names (#7190) ([c81cedf](https://github.com/vitejs/vite/commit/c81cedf)), closes [#7190](https://github.com/vitejs/vite/issues/7190)
* fix: allow css to be written for systemjs output (#5902) ([780b4f5](https://github.com/vitejs/vite/commit/780b4f5)), closes [#5902](https://github.com/vitejs/vite/issues/5902)
* fix: client full reload (#8018) ([2f478ed](https://github.com/vitejs/vite/commit/2f478ed)), closes [#8018](https://github.com/vitejs/vite/issues/8018)
* fix: handle optimize failure (#8006) ([ba95a2a](https://github.com/vitejs/vite/commit/ba95a2a)), closes [#8006](https://github.com/vitejs/vite/issues/8006)
* fix: increase default HTTPS dev server session memory limit (#6207) ([f895f94](https://github.com/vitejs/vite/commit/f895f94)), closes [#6207](https://github.com/vitejs/vite/issues/6207)
* fix: relative path html (#8122) ([d0deac0](https://github.com/vitejs/vite/commit/d0deac0)), closes [#8122](https://github.com/vitejs/vite/issues/8122)
* fix: Remove ssrError when invalidating a module (#8124) ([a543220](https://github.com/vitejs/vite/commit/a543220)), closes [#8124](https://github.com/vitejs/vite/issues/8124)
* fix: remove useless `/__vite_ping` handler (#8133) ([d607b2b](https://github.com/vitejs/vite/commit/d607b2b)), closes [#8133](https://github.com/vitejs/vite/issues/8133)
* fix: typo in #8121 (#8143) ([c32e3ac](https://github.com/vitejs/vite/commit/c32e3ac)), closes [#8121](https://github.com/vitejs/vite/issues/8121) [#8143](https://github.com/vitejs/vite/issues/8143)
* fix: use Vitest for unit testing, clean regex bug (#8040) ([63cd53d](https://github.com/vitejs/vite/commit/63cd53d)), closes [#8040](https://github.com/vitejs/vite/issues/8040)
* fix: Vite cannot load configuration files in the link directory (#4180) (#4181) ([a3fa1a3](https://github.com/vitejs/vite/commit/a3fa1a3)), closes [#4180](https://github.com/vitejs/vite/issues/4180) [#4181](https://github.com/vitejs/vite/issues/4181)
* fix: vite client types (#7877) ([0e67fe8](https://github.com/vitejs/vite/commit/0e67fe8)), closes [#7877](https://github.com/vitejs/vite/issues/7877)
* fix: warn for unresolved css in html (#7911) ([2b58cb3](https://github.com/vitejs/vite/commit/2b58cb3)), closes [#7911](https://github.com/vitejs/vite/issues/7911)
* fix(build): use crossorigin for module preloaded ([85cab70](https://github.com/vitejs/vite/commit/85cab70))
* fix(client): wait on the socket host, not the ping host (#6819) ([ae56e47](https://github.com/vitejs/vite/commit/ae56e47)), closes [#6819](https://github.com/vitejs/vite/issues/6819)
* fix(css): hoist external @import for non-split css (#8022) ([5280908](https://github.com/vitejs/vite/commit/5280908)), closes [#8022](https://github.com/vitejs/vite/issues/8022)
* fix(css): preserve dynamic import css code (fix #5348) (#7746) ([12d0cc0](https://github.com/vitejs/vite/commit/12d0cc0)), closes [#5348](https://github.com/vitejs/vite/issues/5348) [#7746](https://github.com/vitejs/vite/issues/7746)
* fix(glob): wrap glob compile output in function invocation (#3682) ([bb603d3](https://github.com/vitejs/vite/commit/bb603d3)), closes [#3682](https://github.com/vitejs/vite/issues/3682)
* fix(lib): enable inlineDynamicImports for umd and iife (#8126) ([272a252](https://github.com/vitejs/vite/commit/272a252)), closes [#8126](https://github.com/vitejs/vite/issues/8126)
* fix(lib): use proper extension (#6827) ([34df307](https://github.com/vitejs/vite/commit/34df307)), closes [#6827](https://github.com/vitejs/vite/issues/6827)
* fix(ssr): avoid transforming json file in ssrTransform (#6597) ([a709440](https://github.com/vitejs/vite/commit/a709440)), closes [#6597](https://github.com/vitejs/vite/issues/6597)
* fix(lib)!: remove format prefixes for cjs and esm (#8107) ([ad8c3b1](https://github.com/vitejs/vite/commit/ad8c3b1)), closes [#8107](https://github.com/vitejs/vite/issues/8107)


### Previous Changelogs


#### [3.0.0-beta.10](https://github.com/vitejs/vite/compare/v3.0.0-beta.9...v3.0.0-beta.10) (2022-07-11)

See [3.0.0-beta.10 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.10/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.9](https://github.com/vitejs/vite/compare/v3.0.0-beta.8...v3.0.0-beta.9) (2022-07-08)

See [3.0.0-beta.9 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.9/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.8](https://github.com/vitejs/vite/compare/v3.0.0-beta.7...v3.0.0-beta.8) (2022-07-08)

See [3.0.0-beta.8 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.8/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.7](https://github.com/vitejs/vite/compare/v3.0.0-beta.6...v3.0.0-beta.7) (2022-07-06)

See [3.0.0-beta.7 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.7/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.6](https://github.com/vitejs/vite/compare/v3.0.0-beta.5...v3.0.0-beta.6) (2022-07-04)

See [3.0.0-beta.6 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.6/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.5](https://github.com/vitejs/vite/compare/v3.0.0-beta.4...v3.0.0-beta.5) (2022-06-28)

See [3.0.0-beta.5 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.5/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.4](https://github.com/vitejs/vite/compare/v3.0.0-beta.3...v3.0.0-beta.4) (2022-06-27)

See [3.0.0-beta.4 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.4/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.3](https://github.com/vitejs/vite/compare/v3.0.0-beta.2...v3.0.0-beta.3) (2022-06-26)

See [3.0.0-beta.3 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.3/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.2](https://github.com/vitejs/vite/compare/v3.0.0-beta.1...v3.0.0-beta.2) (2022-06-24)

See [3.0.0-beta.2 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.2/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.1](https://github.com/vitejs/vite/compare/v3.0.0-beta.0...v3.0.0-beta.1) (2022-06-22)

See [3.0.0-beta.1 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.1/packages/vite/CHANGELOG.md)


#### [3.0.0-beta.0](https://github.com/vitejs/vite/compare/v3.0.0-alpha.14...v3.0.0-beta.0) (2022-06-21)

See [3.0.0-beta.0 changelog](https://github.com/vitejs/vite/blob/v3.0.0-beta.0/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.14](https://github.com/vitejs/vite/compare/v3.0.0-alpha.13...v3.0.0-alpha.14) (2022-06-20)

See [3.0.0-alpha.14 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.14/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.13](https://github.com/vitejs/vite/compare/v3.0.0-alpha.12...v3.0.0-alpha.13) (2022-06-19)

See [3.0.0-alpha.13 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.13/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.12](https://github.com/vitejs/vite/compare/v3.0.0-alpha.11...v3.0.0-alpha.12) (2022-06-16)

See [3.0.0-alpha.12 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.12/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.11](https://github.com/vitejs/vite/compare/v3.0.0-alpha.10...v3.0.0-alpha.11) (2022-06-14)

See [3.0.0-alpha.11 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.11/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.10](https://github.com/vitejs/vite/compare/v3.0.0-alpha.9...v3.0.0-alpha.10) (2022-06-10)

See [3.0.0-alpha.10 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.10/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.9](https://github.com/vitejs/vite/compare/v3.0.0-alpha.8...v3.0.0-alpha.9) (2022-06-01)

See [3.0.0-alpha.9 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.9/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.8](https://github.com/vitejs/vite/compare/v3.0.0-alpha.7...v3.0.0-alpha.8) (2022-05-31)

See [3.0.0-alpha.8 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.8/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.7](https://github.com/vitejs/vite/compare/v3.0.0-alpha.6...v3.0.0-alpha.7) (2022-05-27)

See [3.0.0-alpha.7 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.7/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.6](https://github.com/vitejs/vite/compare/v3.0.0-alpha.5...v3.0.0-alpha.6) (2022-05-27)

See [3.0.0-alpha.6 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.6/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.5](https://github.com/vitejs/vite/compare/v3.0.0-alpha.4...v3.0.0-alpha.5) (2022-05-26)

See [3.0.0-alpha.5 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.5/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.4](https://github.com/vitejs/vite/compare/v3.0.0-alpha.3...v3.0.0-alpha.4) (2022-05-25)

See [3.0.0-alpha.4 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.4/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.3](https://github.com/vitejs/vite/compare/v3.0.0-alpha.2...v3.0.0-alpha.3) (2022-05-25)

See [3.0.0-alpha.3 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.3/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.2](https://github.com/vitejs/vite/compare/v3.0.0-alpha.1...v3.0.0-alpha.2) (2022-05-23)

See [3.0.0-alpha.2 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.2/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.1](https://github.com/vitejs/vite/compare/v3.0.0-alpha.0...v3.0.0-alpha.1) (2022-05-18)

See [3.0.0-alpha.1 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.1/packages/vite/CHANGELOG.md)


#### [3.0.0-alpha.0](https://github.com/vitejs/vite/compare/v2.9.12...v3.0.0-alpha.0) (2022-05-13)

See [3.0.0-alpha.0 changelog](https://github.com/vitejs/vite/blob/v3.0.0-alpha.0/packages/vite/CHANGELOG.md)

## Previous Changelogs
### 2.9.x (2022-03-30 - 2022-08-12)
See [2.9.15 changelog](https://github.com/vitejs/vite/blob/v2.9.15/packages/vite/CHANGELOG.md)

### 2.8.x (2022-02-09 - 2022-03-01)
See [2.8.6 changelog](https://github.com/vitejs/vite/blob/v2.8.6/packages/vite/CHANGELOG.md)

### 2.7.x (2021-10-28 - 2021-12-28)
See [2.7.13 changelog](https://github.com/vitejs/vite/blob/v2.7.13/packages/vite/CHANGELOG.md)

### 2.6.x (2021-09-20 - 2021-10-27)
See [2.6.14 changelog](https://github.com/vitejs/vite/blob/v2.6.14/packages/vite/CHANGELOG.md)

### 2.5.x (2021-08-03 - 2021-09-13)
See [2.5.10 changelog](https://github.com/vitejs/vite/blob/v2.5.10/packages/vite/CHANGELOG.md)

### 2.4.x (2021-06-27 - 2021-07-27)
See [2.4.4 changelog](https://github.com/vitejs/vite/blob/v2.4.4/packages/vite/CHANGELOG.md)

### 2.3.x (2021-05-11 - 2021-06-19)
See [2.3.8 changelog](https://github.com/vitejs/vite/blob/v2.3.8/packages/vite/CHANGELOG.md)

### 2.2.x (2021-04-19 - 2021-05-03)
See [2.2.4 changelog](https://github.com/vitejs/vite/blob/v2.2.4/packages/vite/CHANGELOG.md)

### 2.1.x (2021-03-15 - 2021-03-31)
See [2.1.5 changelog](https://github.com/vitejs/vite/blob/v2.1.5/packages/vite/CHANGELOG.md)

### 2.0.x (2021-02-16 - 2021-03-02)
See [2.0.5 changelog](https://github.com/vitejs/vite/blob/v2.0.5/packages/vite/CHANGELOG.md)
