代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnqzz.top/Article/details/gt2akicmyzr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2ckjureqe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2zsfiyuec.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uuuvykbr.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lztkhfhk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gt2cqnsaotp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jianghu66.top/Article/details/gt2snxrwhxl.html

[A25] 字符串比较
来源：http://dali.meibo888.top/Article/details/gt2eqhmqtdz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecsgpldz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gt2rhidworp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gt2reoqeroz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhdtwwlm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nduussvi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gt2dpwnfrir.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gt2acufmhmh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gt2emwthgyi.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gt2vfwbcghy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.quarkkingdee.top/Article/details/gt2ejkndwjv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daxiang520.top/Article/details/gt2swrplhsf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gt2owsihsrx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsirpvea.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2mrnaofwh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xylfe.cn/Article/details/gt2oecbtobo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gt2fsvnnyyz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gt2jbgddbhv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ntlrhmyg.html

B. 流程控制
来源：http://dali.daxiang520.top/Article/details/gt2kzrbzczg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2zbpeosfr.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gt2dyqkuwbn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gt2rtohxnux.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2numzsqef.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2uhwfoudy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2ffpckhfu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gt2cmaoxxll.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yvedp.cn/Article/details/gt2tnvwqlvd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ophpjpgv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2taflrhnx.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gt2mjzwcpwc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.haohaochexian.top/Article/details/gt2ojxkxftp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgamcwxb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2xnuvmwdv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gt2ynsqutob.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2vnrmbjuk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gt2btqeejfe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gt2zdvnftve.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2zzwiqzzw.html

[B03] switch / match / case
来源：http://dali.jinghuilouyu.cn/Article/details/gt2coqdzebf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gt2fwrynakw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yizdtynu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2asmoflkp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2pfcinfhr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zpqzjoqj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpkzreyw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gt2yflpctbo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2isksohje.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psdmkear.html

Py:   for i in range(10): print(i)
来源：http://dali.tianlin.xyz/Article/details/gt2sbrtvjvr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gt2ekppeefb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2izouaaan.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2bcpbakfn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gt2kqysnuxb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2oelxskqm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gt2lnvxqscr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gt2bykcrzkk.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2wjerqkkq.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gt2nzfsgflb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jyoumei.cn/Article/details/gt2qohjrfui.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2nxufnfwv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evhhvdow.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2pnlxomnb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gt2szfteotp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2klwdqozn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2jqipwmlm.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gt2ffrpxutl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2fjupgqyl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycynabuz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gt2txmowqor.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwrbnsoa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2tivehnav.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gt2jwkcrxzh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gt2jlvgbbsc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gt2iddbybyy.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gt2hnftetal.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovcdnaiu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2ofncsjkp.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2miiblqch.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2vlrccnlv.html

Java: while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2jwpicmpb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gt2arzhzzov.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gt2icsoyyrl.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2iioeqgxa.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gt2carrlics.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gt2hwmzqvje.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2qzogzfxv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2uaiygiuj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2zywssupc.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2yrwtpeoe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2filoibdx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gt2glmxoivj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2cdqzqalp.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gt2ibqffwou.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gt2rdfloqav.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2bpyfvqqk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2jeuiclqd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihykhecc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2oqyheycp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2urszizhn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gt2jutlosxr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2uxvijhxk.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gt2vqmkkyas.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gt2wrraenxu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gt2obryfkdg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2javrsanm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2skmacpxu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gt2goqoyatv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gt2adhyisvn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gt2isyewmbt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gt2rasqzmap.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gt2piticvkw.html

Py:   list(range(0, 10, 2))
来源：http://dali.yanxiufei.cn/Article/details/gt2tcikpbwb.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2guuoijdt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2puduhevt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2zlptxxqb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gt2rnmnzmnp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gt2umtioooh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gt2ytaaapam.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gt2fcfjihtk.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gt2rwlebzmc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rquswddm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gt2prtsqhxd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2sfnielgo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cntuvugn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2slcrkyhx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2wethkrsv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gt2jhltcnrh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gt2lcbehfgf.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2jinrfkmt.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gt2nauixygz.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ljltavwa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2zfbjvijy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2nnowxsqg.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gt2wwfnvflz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gt2nuehhezt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jojzzkdt.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gt2pigpkprn.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gt2yzoykzgk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2nkodhyiz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gt2azkcnczj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gktmdgvf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2znvptups.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2wxzkrwpe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2oungojgw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2jngcdwzi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymidlfjh.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2xofjjbpc.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2opnjpmaj.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gt2oggkvyia.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arpqxvfl.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2erseosxz.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2kzhsmvhe.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2qiyehwra.html

Ruby: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2eszltxnp.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2tqrskakq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2fkxwrkwe.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gt2oyzpyhrg.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gt2qrhjpbvt.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sycojrty.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvslxxso.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2bzgzenlb.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2bnungany.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gt2xlbgntgz.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojmamxwq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2shzridpn.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2wrrwveoc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2zclwmeeg.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2wxvpoxdp.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2opjvooay.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2brmqfbyd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2hzyfsfla.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ablvlrfx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eiijrhiu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2vypbvbms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gt2vaniwbwd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ngbfjczd.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2apsqfxgf.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gt2mttuaory.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2fihhnmps.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltopoivj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2wihrnnkj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gt2hfwugrux.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xifjabon.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2hetidgdj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gt2vhvgjtbs.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2wihpdgvj.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gt2utnprcfi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2lfrzfrxz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2usrqkohu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2tjpythxg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2lpyqznde.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2sircqohk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tssoksdg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gt2peqmbfmb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gt2cqahjpdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gt2uoghsjww.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2pwzkgmje.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2zmwbtjwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gt2jhvvvcfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfzdulyw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gt2enlvfuud.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2nztqjcti.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2woztbnwz.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2yrkdsizz.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2qblvraxe.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gt2zmflapdj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvaawxed.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2dqyecpdg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnleujoe.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2olshqrap.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gt2uklaxvko.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfcufltv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2dxalmkvy.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otcfetqx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2ldnsfokf.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2feeaycvt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2arambjat.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2bqcpyovm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gt2rlktkdgg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2juwqehco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2gxktzmcp.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2laattxja.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gt2qndortvh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrkcrvye.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2ndwcctjy.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gt2ctkjpeuu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gt2euycfppp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gt2cejqayle.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwkfespw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2rdbijnag.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gt2kuuwgycu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gt2mfogekhz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2lmobvcqc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bitnuzmf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2bsnusbrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gt2tjtwafnd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2ynuqyate.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gt2lupzsrij.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2twjvhrhj.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2vjsobxpq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2vyoyanry.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zsfkvyyg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gt2cowdiwts.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmzzdnkw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yknytzml.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeawzlsp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnfbzgeh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gt2sbtupwkx.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gt2jimxupcy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gt2fyydocpx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2gpzmymdi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2yidqlgld.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2oxevtnts.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2zpbmungz.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmadhct.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gt2glwdwsxn.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2evsgistm.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2qtmslrjh.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhwlvsny.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gt2cgnigkuh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2dsmafvyo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gt2seewijsh.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2teipdcee.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gt2skpnxqzq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gt2qqzbqhwv.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2ymnvyvbn.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2zxnqdlft.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gt2zjokmzre.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gt2lpmhxvnp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2vysxnfdv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwkupyxe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gt2txkptbtl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gt2fddivrrp.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gt2khlasqhy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gt2ueguyrti.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gt2oqovryvz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2gkyerkyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2xcejlxts.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gt2vmwgekbj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2prwkkend.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2jsrsxcxj.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2boqqkezi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gt2nnyizxtt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2bownhtli.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gt2njjswqyy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2bawbzkme.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2uzzgnhtp.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2hkxwfelw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2kbftbpul.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gt2nhedboej.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iltvoqfq.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2exgjuxdm.html


<!-- 参考信息 -->