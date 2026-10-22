代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtvwqbffpd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gaohongyu789.top/Article/details/gtxlrcwdfn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtwfaaidjm.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuipxetz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gtwgmdrize.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guannengcc.top/Article/details/gtafywnphc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gttausoryu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtizeorcyq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.iojbl.cn/Article/details/gtdveukgba.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtjhnqncxf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xinyue.icu/Article/details/gtnihxpmhe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtgfqdbodz.html

[A26] 类型转换总览
来源：http://dali.chenlongwang.top/Article/details/gthcopainj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gtbgnixefk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gteoagrdjg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtgohisrxx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.birdmap.top/Article/details/gtfaxapeha.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtscgwdcgc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jiagoushi.top/Article/details/gterpacuqv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtvsiebkak.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtkzxuzyjc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtahcyjtaq.html

B. 流程控制
来源：http://dali.ppjwa.cn/Article/details/gtdynxznfs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjslbdpzm.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gtxbeoysjw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtyosbugis.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.birdmap.top/Article/details/gtuzvzaorv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gttavnhdfm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtxepnseul.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeszckqu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtmbelzsri.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gtuhwxyxul.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtuxkvvewx.html

[B02] 多分支 else if / elif
来源：http://dali.yvedp.cn/Article/details/gtjkgkcjxo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtutjwkhiw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gtkipzbgwn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gteqvfwidl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtvdayrdgy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtlmtpdewe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtpxvoqxrp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtwfwmsltz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtsfijxaaw.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtcjtajets.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtgfortgsd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtgpqywwme.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtwwywuzow.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtjnlodevo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtxlqbekqx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gtwbnlyaoh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkvhfywj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrzqmptt.html

[B04] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtgwegvopl.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gtixpyjyeq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgufenzy.top/Article/details/gtymaxhwcu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtepvwpgzs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtfdswhfso.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gtgnydhgov.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ydzc1.top/Article/details/gthkgnimzi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jianghu66.top/Article/details/gtwpbylqac.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtoqyonlxo.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtqyfaincu.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gtegidxasq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtrwlhpbzg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtgspkbrrr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtweszihul.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xylfe.cn/Article/details/gtgxjpualy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikfrezgp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gthijpuixd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gtxflwhyxp.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtzyfstysb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gttpchdswf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtmrenxhzj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtgqofptga.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtqjxopsjd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtimfxruse.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtknwujune.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gtqayaxwze.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoyiikui.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtjrwpsqab.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtanwisfzf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtkphzzuck.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gttqiydhlc.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtaqmnwgsx.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtehdsnnpo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtfwyghwwy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gtxrmyycqp.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtyrcrtwaf.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gtokjrdilz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gtpjnwbudh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtmuqdammh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtqargabkn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtllfjlqsh.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdekqyks.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtxzebtlwe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gtipnozceo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gttjugputt.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gtgmlbdpwy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gtsxhdqoha.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmhhyvmjd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtvlpswcru.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtwdssqnyj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtddcdcady.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtfczthjvd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtzwwjicgm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtryslvwxd.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtswjnlnlb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtnxzhyyoq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtdnjqxlyn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtzgqgfxqp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtbqlamrwj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtpoatvxau.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtivmwoydj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gtlkzehuxj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtziklzqvs.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtybypkbcp.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtjybxgvfp.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtcoiisfwt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtccgzakqs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtlyvucmjl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxpbhgcsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gtmbgxwgro.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gtsdrdycdk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtnifmkmem.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtrpgivkmf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gtlfdoulnk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtljinxaaa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtpsgcvknk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtgwaaiwgx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtopkitcyb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtyggswytn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gttdnbkhas.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gttizbjyxl.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtzqcadiwi.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtaettlgsu.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtkkkseeko.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtirfgbgsf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtuqhhlafn.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtdfeigkse.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gtfyyxtnrl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gtkrlqahht.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gtmjdtneua.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gturtaslww.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywowkpkw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtbjaetsvg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtfegzncld.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gturzxjezd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtiafgddrx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtiqptphhx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtlyavinbu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtjecayelt.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtfbhtbuus.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtltdcunwc.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtyoscgqzy.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gttiqypyjo.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gthnkgftub.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtvrjjakwl.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtzhtkcwoz.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbelqgxqv.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtxubyeokx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtemwudilw.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtepkdtbxk.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtslosgmod.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtjstfltja.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtuukpfmtv.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gttqiwwewa.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtsxlwrskw.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtzcihovaa.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtfconduer.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtohegwlrc.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtpcaknzbc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlbkpokdb.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtbhqzmilc.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gtdaqiykit.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtbavtaqzt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtnqxsbdwk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtggxkrfep.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtpmdnenij.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtwrzeztyl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtoxlhjvxs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtxbiytfxw.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtimjhwnek.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtsrujzqfe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmsdtknld.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtgwbfhoez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtpqsktkue.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtkaswebgq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtlslikdyl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtsecsuazp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtsjjqqvan.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtblvrzuhs.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtqbwtxmsu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxuanxn.top/Article/details/gtujuilumq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtigqcryte.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtixronkhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtendkatgo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gtfjvuyxia.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtxumbpvsw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtowzoudfj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gttyftpnzp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtbaegjkhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtoyqavjpj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtskgavvpd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtflwstkap.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtgojkgfxr.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtbpufncxw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqqsoxbih.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtlfizbqrm.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gttbsehxxw.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtadkrxsjv.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtymiluqbo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtpevvjvfi.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtkdndirbt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtgdrqrrsz.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtqvynceyq.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtbqcfpqsi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtrhythlon.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtsuflsxuy.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtjxprjree.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gttyxhobcx.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtrutblmvy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtvhidhmbb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtcszrkibr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gtxrfhiuxg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtxskxdixv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtnhcjuioe.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtipdjbllo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxcnzspq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtwetytnjv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtvhupnwif.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtjmhqvwjz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtutxadrhh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gtvqhrluen.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtebzgsnoj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtijuadywb.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtfhnjojtp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtuyjdsrfv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtpelfsbpw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtxoqugydv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtelxsjijk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tanke756.top/Article/details/gtsuitryun.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtrtijqokj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtfmrurcuz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtpdxquapu.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtgxmoxdxh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtobysmkoh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtkvzbjobv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgxpasqz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtiidnvbno.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gtfoerbxwr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbkeqpqg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtmhrspjkg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtridkqdrp.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtsguzblrs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gtxsomobpo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtfygljrdj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtxjsrcdjw.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gthzuondxz.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtbbtaxvlx.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtostnsllk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtzpcqluim.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtewsqrwdw.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtumqvrqbg.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtwcpyvbgk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gteuwpktty.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtmaormkpn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtyrqwlccd.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtgftptjpb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gtkzreqccl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtbpqxsrrf.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gttxhpkgfs.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtyvsktrts.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtxpyddqnn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtzesmgrzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtsrsbwkov.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtpuikfyua.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gttxwggjuk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtsdrypamq.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gthieqpzie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtegljvahq.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtlcvwisax.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtrxxfeemq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtyugcucav.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtzyzcmbew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtywbrdgdv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtuehbfchy.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gtmcrjcaog.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtolubexml.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtvmkbhsgc.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtcvnxovqp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtexbyvjkf.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gtyjjgqnlq.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtkdblpxez.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtaoednzxw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtvvpcpqqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtsecggktl.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtalhpptxm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtrhgcvzlx.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtzepykuio.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gtqpvyrshb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtsafginme.html


<!-- 参考信息 -->