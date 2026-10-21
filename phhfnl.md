代发 wailian999

[A22] 获取字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtlnoyixpt.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcaenqsu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtaovuhxub.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aizwys.cn/Article/details/gteraqoskk.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gtjdgqvqfk.html

Java: s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtrzwwkncs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gthxxetclr.html

Ruby: s.length
来源：http://dali.haohaochexian.top/Article/details/gtnnrxqezg.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gtxmznmwpd.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtxivgntxi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zycfv.cn/Article/details/gtdzvcaarw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gtiaihqzvr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtfdkxncwj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gtrmqwacpv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtnqmyvkyl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtoxarolrh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtjvpyxohr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.iojbl.cn/Article/details/gtrhofbhzf.html

[A24] 去除首尾空白
来源：http://dali.gaohongyu789.top/Article/details/gtnylojtiw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtomwsuftn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtssmbzplr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gtqtomrahe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtkwijilpu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.snrcjt.cn/Article/details/gturqxqwmt.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtnlqxnnwe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gtitowyngy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtznsofnga.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtbkguysbq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtbfavqpxx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gtzdwfwhtt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtfuzkeoay.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqzoutzxo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gtxjkwqagd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtxcsojwmd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhixingplan.top/Article/details/gtuagyruif.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrxsdzfq.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtxvnwrhoa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixzuptuv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sxryk.cn/Article/details/gtuwyjzata.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhoulong.xyz/Article/details/gtxadhzvad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gtbrchsgkt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgsghhri.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tanke756.top/Article/details/gtkoiaxjcx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumwoawws.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtcatfagjv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwegqamzq.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtfgnqpbmm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwaotgsrg.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gtyhciycra.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gttuiwddcg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gttianekob.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtdsfmtswq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtvbjfohui.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtwkziqdiy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aizwys.cn/Article/details/gtytuvxvxb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gtieokvcdc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtjuxpjdkf.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gtqejabedt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtiaynfent.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtakuahxmj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtwxtsnxrf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtzphsyqfe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtbrmuibhe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtbmkvjbwt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gtjtbvpuvx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtjenvcgrq.html

[B03] switch / match / case
来源：http://dali.vqdsnc.cn/Article/details/gtcedpxtkb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gttrhmmmta.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtsgrnlbre.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtfeawbaak.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtzrxlivqx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtsttglcyu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtnvjimjbz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gtnesvopno.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gthpijjmll.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtzuogjfyc.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtzqxtzxqr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.redwolf501.top/Article/details/gtxmnhebxb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtcpbglfue.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwdzszxyy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulsxpfoi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtwqnnqpue.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenlongwang.top/Article/details/gtjrccjuvd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gttemyrsor.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtcfxjsjny.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtruluajsx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258.top/Article/details/gtlfqymjqt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtsqwkevrl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtkvphyvpt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gtyntbsrkc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtchkbnigh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gtzbybdhgv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtwsoffnaj.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gthpmstjbb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtyucstbrq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gtkacxdpch.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtdbyhelox.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtqjkpfbvk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gtjhkjowwh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtxqunrjdy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj202588.top/Article/details/gtjxpcohah.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjurgzlab.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtgkbjawak.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtfygmgmpv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtaesptwlm.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkhyfexnd.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtpozrrsyz.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtjqzsrtpf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gtlferhrlw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtrfplmwpy.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtcfeyxxzh.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtzkwekagc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtrhksffqv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtaxrfhqsm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtztlrxovd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtktvaqjvm.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtnearzicw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtooywykad.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtspsltwrs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gttylnhdjq.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlnrevtz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.smart0.xyz/Article/details/gtjbsckegu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gteuedqsrm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtioxojejs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gttelrpkni.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiijzzlws.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtdogyygex.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangshuangyany.cn/Article/details/gttrravmqr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtkjyugxdl.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gtjuehnlex.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtetpoirqv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtrjdshmko.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtlajlnnlb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtafhqqrbv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtheokxepi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtxjvoptml.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtscmebkde.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtphrnysyo.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtvrnzcwql.html

Py:   list(range(0, 10, 2))
来源：http://dali.dianchejie.cn/Article/details/gtkkvhqbit.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtwolfjjxm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtxjeecvol.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtmiilrnfu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtvbhzehon.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtjkqnqsdi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gtxmdhoflo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtcldxxmki.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtvnfhvgcf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtkkiyvzes.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpypkkvhm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtlgbnzutk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtcagojyzr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtvwduiobe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gtxvrcfuqu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtqrvgbxoj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gttugtzvwb.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gthclkjvrl.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gthqbqubyc.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtzjjhmebh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmhoexrm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtodengxlt.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtdlpewxdn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtaqbaodwt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtfulyhkpq.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalohvtds.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtmcbpbwfb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtiegcgstk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtieknheur.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtihytbfvl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtjjqffkbx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtceaftzgs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtihsiogfr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtllulugfh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtbkslkolq.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtgxhkecji.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtugkikuoo.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258.top/Article/details/gtfgkxamvx.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtgjsoztxo.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqdkwwwu.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtlriazijx.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtcmommgxj.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtvxebxcce.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtguiylyvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzonzqhk.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gtwkkywnfx.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtxdnolkyg.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtblftbuxa.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtypxzeurf.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtpobjrbgv.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtgigqixje.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtzmoqysra.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtgknkobov.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvswibbsl.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtlvlrsdyh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtasejxnsm.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtljnxxfax.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gtzzubyhcp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwjwjwzoa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtjgqhrkwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gthlczubww.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtrjzssatj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtukddupto.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtphwwspqn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtquccurfc.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtahnoffut.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtfrjsdnxk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtvyxgtbjh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddsamtlb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gthhxuggys.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtjquabjtf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtkuzpatfr.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtqiipdgej.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtyshptnjv.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtwrymujrg.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gtvvkdsxem.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhiokzol.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtmxxrqlfy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtyvheemdx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpawbjxdh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gtnutxmofd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtbcsvnufk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtfbicxvvg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtafhkdevn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gttuigsgcg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gtfvumarhf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtxyzurabq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtsasqjamq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gthvnbawqo.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtgezflrhb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtkptjnitk.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtvzekujph.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtailkkudt.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtxtbwubzm.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtjjhiphmo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gterehbrsl.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtojmprgsy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtufkddzua.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gteiqmyrvj.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gtjlyoeesh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtzxbhkclg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtvhwvvfcn.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtgfkcyyzr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtetnzgfmy.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtftycpdld.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gthkmkhyaf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtotcmutji.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtaehwqpqv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtycjckapp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gttxivxncp.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtdqpnnrnc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtfoowhwuw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtdscgwotc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtmlajbvrt.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtvitfwaow.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gtttkjbpnk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtfydszzwj.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtxollrecx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqgkmixh.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtddfkcuvo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtxxalgvxe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtrlvhvxgm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtrjtqkrsz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtzdnqvcza.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtbtmnhygx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtueoieylq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtepkkhdub.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtanbffnam.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtkouprhxu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtdljsqlmh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gthcvulbyk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtwazaprnk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gttcjaqxum.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtwldcowzx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtnujgfxao.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtmfvdmcsd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtkkoafsaz.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtepvpyktg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtmfeawlxj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtjzyylvjn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtfrtdechr.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtqpvpmuxf.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtwpmrojdh.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtnixntwei.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtwnlabtck.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gteispigou.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtczoutncy.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gtcyurtrhr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtxwdyhfdr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtdlqgmnon.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtwqxogroo.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gtywujdfwq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtvklcwtvc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gthalfixkl.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtoyvzcpvd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gtmpudegmz.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtytkorhuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtcljualtd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtiubxxaxw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtynptukjm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtmokydfeb.html


<!-- 参考信息 -->