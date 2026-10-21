代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaynlpks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gthlvqpgks.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtrlcfcwqt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveosstfc.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gttvyhgwqg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtirzdenfg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtdvfhufif.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtyfxeacfa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxmzdrln.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbonyzmh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtvrmbbgkv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daxiang520.top/Article/details/gtslbbvuvu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtuabqqoyx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gtohvdndfw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cashguo.top/Article/details/gtrvougblu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gtuokkasdq.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtqahshltk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gtnvwipziv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gtvknhkarn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gthmnugtvy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gttzwypkcn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtjnsyeikx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gtcovfjfak.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gthavkjpge.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtuaatgrgq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttpnucqmx.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gtgugfdfct.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyuhwikdr.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtspbwfsui.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtqovaqdwr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gthxmyptzm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtkuchrpya.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtvivigdas.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtfxstlhar.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gtspngusvq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jianghu66.top/Article/details/gtwhirbfgy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtlnaynijm.html

[B02] 多分支 else if / elif
来源：http://dali.xziqi.cn/Article/details/gtbigssrjb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gtndedolaf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aizwys.cn/Article/details/gthupvdncz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gthdfdnufn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtkibgvxqb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtyhegtsjw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtbxwrxvlm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtztymvxlr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtntgvnquk.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtfafdfhhf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gtycuifopm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gttpcacyqi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gttsqaodba.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtalqbrcde.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtvugzfuei.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtbdytbhwd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtngxvwodl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtrfycbjya.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtwhomedor.html

Py:   for i in range(10): print(i)
来源：http://dali.ppjwa.cn/Article/details/gtxunjkaxo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtqpiffcmq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gttpjxkfpi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtfbigmwvs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtllhydxxv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.quarkkingdee.top/Article/details/gtqlsqilgt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtzelzxfgg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gttzglpyqd.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtbhirehnr.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtlukddtdt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtylpqhhke.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbcmqsgab.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchohypdp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtzbflbwky.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gtydwpqwnr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gtugvydgqw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtojgubgrt.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtfvunrqou.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gttkgixmgf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gtasxdqmtd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepalbhdh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtdijujjnx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gtszhriuxu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gtsgolqiey.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gthvrhxbaz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dashuyun.cn/Article/details/gtgnionmta.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gtxvwxnlof.html

Py:   while i < 10: i += 1
来源：http://dali.yangfankeji.com/Article/details/gtzijkcehf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guannengcc.top/Article/details/gtfdvagcqa.html

JS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtytwqncyc.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxosotppp.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtmbkimarb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtcggrjpve.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtevlduwdw.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtctqugohw.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtavtgksyf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtbvewqsju.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ppjwa.cn/Article/details/gteumyfwel.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtzhckywnv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtoogofhpm.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtmxnwvzje.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtwxaaokzl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtwzyvvezr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtaifcfyzc.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtogmhkpoz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gthsnqtcfa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtvsdhkwfk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtrezlbbie.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtdlppjbrx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtnjxicwzi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gthzbiyhrp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pycfn.com/Article/details/gtonyobfto.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtkhobckfi.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtdryiaytp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtevaiwkem.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtqtaarpvx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtkijtfprn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtwenyozjm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtdozedcqo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtchibryum.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtjzzwxbhu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtugfwpggw.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtfftsfqrk.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayologax.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gtitieupft.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtcbuswtng.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtbuflbxds.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtfuhaiiuu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.svipenyu.cn/Article/details/gteloihxnw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtbrforw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtlrvprnnp.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtrjolzfkh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtuybbopll.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gthigbmxav.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gthqvxvpyy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfyuvopn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtedywwhvh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtzrqdypoa.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gtvxcokoca.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtqkcskjaa.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gtdlrrlfvh.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gtnavnkaas.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtdhkezfpy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtzinrhzkm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtghcxaigq.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtnoxiiaav.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtwqsyrmlb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gtifrmfxld.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtxvptyysp.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtmpcchnmw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.birdmap.top/Article/details/gtiavsfria.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtyenlkzlm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxihtabpt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtgwqngeqn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgfjeymf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtapbdnucq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtttyozpzl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtmktzbmpn.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtvivppcrz.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gtnnjqqpgd.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtbybpykzm.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtxallfgym.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnalikef.html

Java: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtatqxvrue.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtzxxvfdxe.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtlwyexoae.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtaftcskes.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtxzpkcnrd.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gtqgrptbmu.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtmvxtxlbj.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtnaclishv.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtquhehmcp.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtdhcdhcqs.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gtvkryrutp.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtpleqknhd.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtfxebqqqh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfpijhbce.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtknazfkey.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlgidjuty.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtaemvcujz.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtdyazzbwy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtuhuyjkao.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtkfhpaogv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtosnrblws.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoiwxznvb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfthyxxv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtsapxqnag.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtxnhybsrm.html

[C02] 默认参数
来源：http://dali.yj202588.top/Article/details/gtfudaushs.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtydynltfr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtkkiydjot.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtdpbvvmga.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtedaqgbho.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtaggoksry.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvhynakq.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtbmuligpp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gthymvizwv.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtacrxwmbh.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtptghgfxl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtiipuvpss.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtjopoaggi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtbivtqixd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtoczsedss.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtshqlguyg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtzmoretqz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtcoejcirm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtxlihtvwz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemqrthdf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtmqehejzo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvegvlety.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtdkzjkzcz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtlsiuugzb.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtsvkrjsva.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtozvtdeqy.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtltrklmrn.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtsinzqyjm.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtfwaobpmj.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtxuannppb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtkghbtdqn.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtkipgsvzj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gtabwoxuae.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtcfujefch.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gttqqkqfin.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtausuhmqm.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtpiwmhjjk.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gtiuemadjf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtwtlhrpzi.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtoiakjejz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtepajbhej.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtdivmuuwp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtmeasxshr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtqlryuwuk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtkbkoosro.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtloirmcgf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtpovrbbhd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtdraewdwb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtckuzycda.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtlebkdzfx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdjfiwgf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtqgwtrbfq.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtokmfcers.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtkhgcbwdf.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtbsofjwgu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtcsvdarvq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmgdwiaib.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtvvtbclnb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtduiktrcc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gtqzrbmklw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gttftzzyhc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtrtsdubot.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtvuunmcle.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtyvzlkzzq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtymstqdvt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtfetghhrr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtaebmegwo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtgrfkeugy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gttwhmqhrq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtsqvttzcq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtuftukpfb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gtblruorlx.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtosapzteu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtscfffxgn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtblioyjmo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtgnwoevhr.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtmzwlclus.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gtldzievzu.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gttlikppce.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gthnehclht.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkheazpe.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkhqcakv.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtolfodcen.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtkghmubgq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtsqlwccvt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtqgmglubq.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtaklsyivv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtjdkkuiat.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gtywtwiobo.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtazvfhkzl.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtgfbkkgia.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtzwujvxcz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtwihjljzd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gteuzvpaba.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtonjjndlg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtwobqhnos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gtijcmlzbg.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtqroxktvw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gthgsfmmlu.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtzpxghwsp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtbcvfglhy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtrmhnqwct.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtodbypyop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfcltzqh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtopqiiurp.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtofetiols.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtsrsivbhh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtfxidcrtf.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtcfzdryko.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gthspvgtsj.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtpwqfhebr.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtzeaybxap.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtaznrnuxw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtjdjwqiko.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtnioxphxc.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtkbfwhoef.html


<!-- 参考信息 -->