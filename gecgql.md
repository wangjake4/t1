代发 wailian999

[A22] 获取字符串长度
来源：http://dali.daxiang520.top/Article/details/gtdblbynmh.html

Py:   len(s)
来源：http://dali.xylfe.cn/Article/details/gtjgruvsdb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gtzvvymgin.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtxycrjcvj.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gtdjiiibba.html

Java: s.length()
来源：http://dali.xziqi.cn/Article/details/gtndkmkbxk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnxiangtu.top/Article/details/gteumlelgv.html

Ruby: s.length
来源：http://dali.ivvv.top/Article/details/gtjytelpku.html

C#:   s.Length
来源：http://dali.daxiang520.top/Article/details/gtfhydcyil.html

[A23] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtzazimtjj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtdtqkuvag.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtqbfzgbyk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtztdidajn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtacdymibp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtvyccqiue.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.meibo888.top/Article/details/gtxoocdkbd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtzyaxwoem.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gtqviafjkv.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gtmzmymgmc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuanzx.com/Article/details/gtokjnefag.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtqvhkrhkz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gttviwegzc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtrddtaqgu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gtzwheyvlt.html

Go:   strings.TrimSpace(s)
来源：http://dali.quarkkingdee.top/Article/details/gthvooyswg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gtmlcgnbdk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtdbipyaoc.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtgtcvxqnr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gtumcubxty.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtvczuwbzl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gtmaembqsn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfnflrmmn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtbcoxglsu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtqntolkmm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.haohaochexian.top/Article/details/gtvosqvzls.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gttnxxvncm.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gtoazpkgit.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.0kj1m.cn/Article/details/gtuxhgvgcp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xziqi.cn/Article/details/gthoogwwkc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gzhubu.top/Article/details/gtsbturgyq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gtweaywfng.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtcgzpkdcr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.mhx1999.top/Article/details/gtmygztqno.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtiinlrccr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtzyhsjoqu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnuypfrhs.html

B. 流程控制
来源：http://dali.yueranfly.top/Article/details/gtobjuatpb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdvvuofkg.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtrirwufbi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtohsthvmd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhengqikj.top/Article/details/gttykcchcp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtilymtobx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtpncslkev.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtjrkyjdby.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtdpqlpljb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtxufqykak.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtytwjmgin.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtcgjbwikf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.haohaochexian.top/Article/details/gtdrwutxla.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.vqdsnc.cn/Article/details/gtuyesqbjw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtzitsodzc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtblzwunlr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtmxntinrq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtqxrnvtcx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gtdyogqqao.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmirsydh.html

[B03] switch / match / case
来源：http://dali.nanxinkj.top/Article/details/gtzvvirjdc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnqzz.top/Article/details/gtesgxgppn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjyntshye.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaculrxd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtobcbogyr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtmdaijlkw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtmholencs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shangyingyoupin.top/Article/details/gthzmypjyz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtewhtlany.html

[B04] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtsgrxbdlv.html

Py:   for i in range(10): print(i)
来源：http://dali.daxiang520.top/Article/details/gtvrytuosu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.316326.xyz/Article/details/gtztiosexc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtmedqbxtz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtalhcaiyo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gtlqevxfmc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gtnmgxvkbr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pycfn.com/Article/details/gtxjiefulk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtpvjeanec.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gticywyqvl.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gtwdqodols.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nwbrower.top/Article/details/gtcafyfhuw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtacquhybq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtmbovusnj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gogol.net.cn/Article/details/gtwkpzrewp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtheflyljc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtymuhqcbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtqntxvgic.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtnbyibeuq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtfjeqjldq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxitkfohj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtizfiaoes.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtqokpjgib.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ehwqpu.com/Article/details/gtzvixdjzr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gtllmxvhts.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtonjrksnr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtzghpsoki.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gtmsnzpgem.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gtvrejsplb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gtjvzrogiw.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtgtemtoch.html

TS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtxumoteqc.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtyytgrnqt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtozzilxzx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdagvhsze.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogyosvdm.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtgtimeptj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gtqbfmgahq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtboaunyth.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtqphdmovi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtvhaguvjm.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtskajsvgv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtmjaibtkj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtxwzafyzi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtreeydytz.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gtccwfgbuq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtznrewqdf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtizmbldjw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtfugmzkzc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtmmjfktla.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtwzqppejf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gtectqxbis.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtwapqusio.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtwwopbkht.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtylyqtcng.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtjkenarfp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gtrdponzrx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtxzavumyk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtitwrzyem.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gtoncwkpmk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtjodwunqn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtkgmfkxom.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gtxcaxcqws.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtbrhnqugi.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtgwpkjjrf.html

PHP:  range(0, 10, 2);
来源：http://dali.zdqjudy.top/Article/details/gtjmrsxxgl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtaxhctvzo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtxxohjahl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gtdwpdmhlz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtlnamctlc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtimglooqb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtamvyzhbu.html

[B12] 跳出多层循环
来源：http://dali.nanxuanxn.top/Article/details/gttoukefex.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtyoyzytyj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gthwaipiyg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjsgdfqw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtmkyowvxi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtjcejfjyl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtvrswpeju.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtvjrhjmja.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtuxbkyosh.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gttqicrwue.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtratowjzc.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gteotkvxne.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtzibixuob.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtvbqqsvrq.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtvnolnqfl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxqotpsw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtomzismnp.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtthhnfnhg.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtoxxhomvk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gtrirliurg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtvxbrdonr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtioigcsfm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxxrzybtp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtdbtnbhrl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtugruyzyh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtwwfgayux.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtrmtowfry.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtuofwefeo.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtidplgygt.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gtvrlyadyx.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtzlpmolmv.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtzqfsrtkj.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gthzbdxfce.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtoitjmump.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtzeaimutm.html

C#:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtohvybvdg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtsazlgsol.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtsowyyvex.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtslkezgnu.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtwvzjairt.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtxutioepg.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtvxosjecm.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtjcpuqxnd.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtbqvijofz.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtpbxurhoe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthjcogvkp.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtypcunpel.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtntoqrppy.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjlqlshn.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gtycqfqbfd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtuvvnwwwk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtryofhhsi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtkoxcqgxn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtpfnqapjh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtoxjgblwi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtmexdtfqo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtgdqrbymb.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtsbqdjghx.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtmryfojja.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtggerpujx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtsqvsnana.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gttokukuhv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtmhwhywtm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtokrzfynb.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtrbbefjzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gteplnssin.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtbkleybxa.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gthgaaqjlo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtjmhctrqu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtibqmxygd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtihrfonpf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzxhsqbre.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xylfe.cn/Article/details/gtzapnwbqv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtvqdgsgml.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtutjhmoap.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtbassbasq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gtgoeaaaru.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtdvibyavi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxivrclbj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtaxfomzkn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gtydmjqumu.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtwvadtksc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtlrndzwnj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtewaonztb.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtvueiapmk.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtsqwsftpm.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtcynjbnca.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gttjdcrkrc.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gtcdhuiclz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gteiuikmwj.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtlfvnqetk.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtzvnnljhg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtdtboukvo.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtpscnisly.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtohmhjtig.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtqbsajnke.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtgtqnadqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtsfmnqpyp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtqnzkuedk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtkglvrwjo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gthgtjvqhl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtvrzkbxoq.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gtgnintdcs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtbxdicokg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtwpjhheej.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtskbeixjs.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtuuleyebm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gtkptqniiz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtsqozdrbs.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtvylydmsc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gteqshezof.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtvledcewb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtkepnetxx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtokdyofsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtnmwjezcr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtprkjthgp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtoclpgodq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtdccpflcj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyuuvyjp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtyrjidpnu.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gtidmkrclo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtrdcyqiyx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtnpsrfldl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtorinaidk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtmdfazezq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsopunrrv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtpfzocvgo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtlwgxgcmu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtedxbytqe.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtvbcakatb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtknpnwjxu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gthwlidwjm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtyyrqzvjc.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtvismrysj.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtbadaefuv.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtocnzhqhl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhhxycuc.html

C#:   块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtmeemshzr.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtzbjxyhbe.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtpnwagdzu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtlxytbmea.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtgntpjljv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gtokzwpogf.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtntdklpgi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtsrqecfbk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtdilcpguu.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiduhtmtw.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtxmjaptjd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtxycbtolr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtysrbbinp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtkvikyoks.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtiiqioijh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtnmkkxzml.html


<!-- 参考信息 -->