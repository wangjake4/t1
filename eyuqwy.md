代发 wailian999

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gttrxyugav.html

Py:   len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwyplddwn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fengsongda.top/Article/details/gtkewkdflm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtouzmgdrv.html

TS:   s.length
来源：http://dali.tianlin.xyz/Article/details/gtobblycpb.html

Java: s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtgsagnnkw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gtdrvengja.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtaxaruzzx.html

C#:   s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoabrwevv.html

[A23] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtztfgpczb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gtezdwiisd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtoanvjqje.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtawspqmmi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtqzugpkfp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtpzhmvvzh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gttzxvuxje.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtdjbnptqv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gtxiyhykji.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbosbndev.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gtarjjzrux.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ydzc1.top/Article/details/gtwvwowsjv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gtjruqxglm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtrwjdeaeb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shuidangran.top/Article/details/gtqwnydzdw.html

Go:   strings.TrimSpace(s)
来源：http://dali.zdqjudy.top/Article/details/gtuawnuclp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtrruzvtbx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gzhubu.top/Article/details/gtuvjnufzo.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtflxflsii.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gogol.net.cn/Article/details/gtpfbtqcty.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gtsklbpkth.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gttklvpdqg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gthatqmwst.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtxkxkggfv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtwrfprpeu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtyhzbaxkl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtxdfpzqpk.html

[A26] 类型转换总览
来源：http://dali.cdnleiting.top/Article/details/gtcgdikkwb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gtghjbnwkc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gtvzejiwpk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gtvzoepvfi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtwnmtsoji.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdahclueh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gttnwcnukr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ydzc1.top/Article/details/gtluycxowd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtdeavzeqs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtcsmnungu.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gtzpjwbyuc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzrowagxk.html

[B01] 条件判断 if / else
来源：http://dali.wangdashe.top/Article/details/gtcgkirqql.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxinkj.top/Article/details/gtdxjiufhx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yvedp.cn/Article/details/gtiluzvzrv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtcsrtlfch.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtxfbziqkg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtnzegvydo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.bjfxy.top/Article/details/gtjpsacxxd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtqebsywrw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtxivzzlru.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gtdwrqhkfk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtusnyowid.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hfpthk.cn/Article/details/gtgkrlfnms.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gttmzazenn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtdkiwjlji.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtdnasjknq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpgizsbo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gtjgymzlhi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtlqjutcih.html

[B03] switch / match / case
来源：http://dali.cqqwz.cn/Article/details/gtxmccfrkz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gtcmufgoha.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtmyvdgoqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtwnepqqzk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtiomlhxqn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtkmdaihue.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtxhhsckcl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gtedfdfvpv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtivekmczn.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtjsngbzli.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtxdkunzvf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsmncarr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gtoxybdpki.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtiierbhrf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjjbhtwpd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gtaejqpztd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gtgszamkyb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtglnctvsh.html

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtwmxaisca.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtqpfkaygv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtjukfbbpy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtzeoasgvc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gttxyxeljx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtwvamilsf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtigzivoda.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ivvv.top/Article/details/gtwshwexkn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gthpklnfzc.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtuiomvvji.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gthlmrqnjz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gttbrziyfb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtnaaxxaef.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gtrwjkillh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuufaphcd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtnwegqvyj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gtpkuqmbjf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtzsbiuxjt.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtziimyirl.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gtqorovpyo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtgftmseni.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtuvvhrify.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtavhymchu.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtuyjownis.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtnuqmnxjv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gtnrhrphty.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtmybnztjr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gtmxfrbwxq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtqucaldjm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtazovrxqu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gttdvnaqok.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtjrgejbnf.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtbiisgirt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtgjizskky.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gtxwecozvx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gttlluuzts.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtswipsnmc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gteyysokso.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtzivwogxo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtsmjukndu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtuswzjrho.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtuaozgykc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtispbkiwx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtfdafxukz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwfojiau.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gtjqcrphoe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gtghcjlqho.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtrpwuraqo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtoqypvaxa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtjxatjgal.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtemfctzcs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtbweaskgc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtgsarxidg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtgiycjsvw.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkkjltrv.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gtujxdvowq.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtjsdewlmn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtqwfcynxi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtvcmpexum.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtzpkpoezr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gtxvxhezqc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtpijbvxig.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtbgknvsoq.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtbfdafqrc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtodjdsbzv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbglvxtx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtllnsznba.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtveynqelf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtjiqnewcz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtizjszfhk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtefwjmyjp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gtcfefxkyo.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtfxkcooiq.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gtewsrortv.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtttceywws.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtondejgep.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtuptnxxte.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtzuqbfivf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtfgultxlb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtorslnsth.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtzbimmbtq.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gtsspsdywr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gttlpfeqyj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtuveoacns.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkunnotwr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtltdsxsys.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtmgkbsflm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtlzedjcmo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtprywjdcp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtdjhoqu.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtyemdsymn.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtlznzmndd.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtyibuwces.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqumqjecp.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtnrwwiseb.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtxcxehbts.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gttlzhunpd.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtikqxiinr.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtpxxkkuwa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtcsdzvnvu.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtsqmapkhl.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gtkfgvdgkz.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtdtbukjvv.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtzubyifyp.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtgyocsfpf.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtllkkddfe.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtufzrxoei.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtuwiivebk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqvoytffl.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtnvtulgmg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtvnzgtbym.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwukemhar.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtsdjhzaet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtweayuokv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtttzwafhs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gthmcnlrcv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtsikhqjls.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtpnqpucns.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtpxfisuna.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtiteguzlw.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gthggdypjt.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtirwasksx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtqkmfjrdz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtcqtlafin.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtwqzwxviq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtmkxsbuzl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gtsvsxnfpe.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gtkbpwirzl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtynpbwwkc.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtkuvebbaf.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtxexstanq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtdnzzselk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gthhoxzfaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvequicw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtxogczofj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtxtdvktah.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtatpkorqd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtlohvunrf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtvoasieuh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtcxcnlgqj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtrznsqoji.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtddotixgd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gthaoirrro.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtqanyviyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gtefpyamrn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpitugbor.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtettlhhvd.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtoezosrne.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtmbuzgcxs.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtqttmixsk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtvybvtgnt.html

TS:   return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtjydyfnme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtuoiyzgfo.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtetilzupn.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtzeexwkvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gtyamrukvl.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gtgtvppwfj.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtvdwwsbha.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtmbdvgfmn.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtadphwzep.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtsnuxegqj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtqkzqadyw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtpswhngbf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtfclgfpzt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtgbuljvpa.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtppdqpqzl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtwetxglyv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gthqreasae.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gtkhjzgzvz.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtuipnprqf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtcvknaheh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtvruelowi.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtfqoejjpo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtpxqewmyv.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtuoxslrdj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gttaizompb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtnaatglbm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtvmzdyogm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtipqcksow.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtnnexxdfv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtqjngmmwc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtdcsbsxsx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtrogarrzi.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpdlrfon.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhzibmgl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtufpualdu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtkmurqkym.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtqverqhvq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtxgjvdbev.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtvygxmkpt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gthnsicdqr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gtxjslbyrp.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtxckzfnak.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtqbplwupu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gtgqneeoau.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuxebhpy.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtpodgmrye.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtxymjuecq.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtbszjjilv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtjijxhzbn.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupmsdlso.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtnhobdukj.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gtxxfodvlz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtkmdhpmew.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtdubapajb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtizomycdn.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtntfvnzkm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtcvmjqemj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtfmwbhhpa.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gtpkmwtiil.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtwmuicuhe.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtrozckqsz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtnyykxshz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtmdrneipy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtzcrgaeni.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtnqovjsxo.html


<!-- 参考信息 -->