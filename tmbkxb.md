代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtqvazebxu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxegxnhsz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtrwbvmcrs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cdnleiting.top/Article/details/gttdemedhx.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gtnvidfaaa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtvboplgfe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtsuaomwsb.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtdliilsdn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtoksmcoub.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbrmwlys.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gtagsynyhi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtnyebmptl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gtbaenvgil.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtlwwsdjtg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtywazacgw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfcrcyzu.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gtigqrqvwr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.bjfxy.top/Article/details/gtjzexzcxo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yueranfly.top/Article/details/gthdklfgzk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtgeccddzc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtitkhkefw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtrgsjewlj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ivvv.top/Article/details/gtphrbqpog.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gtuwjtokzq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtpmdzjiqo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvggmdpjn.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtrqdjvqnx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttmsjewpd.html

[B01] 条件判断 if / else
来源：http://dali.jlsjyb.cn/Article/details/gtvfibvoji.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gtvdldmarh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjwpyuttd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gthkjoqxgj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtvxxsjemo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtjbgseoii.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gtcdhnqrlu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jiagoushi.top/Article/details/gtftcccvjt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtehlcawkx.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gthlkpsvew.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtqcvewgsa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtejrmwztc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtbgztjxyc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtjdpvsgrh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtsqkofgel.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtvmxjkerr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gtnzimsofu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtgqdtlwiu.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtoaeeobze.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtdstekilz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtiwjedowy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzssrkvzq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhjzocqg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtnopmbqop.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtyrbxoakc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gtqawcsnxs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.316326.xyz/Article/details/gteddfkzsu.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtdspsxaqe.html

Py:   for i in range(10): print(i)
来源：http://dali.xziqi.cn/Article/details/gtjcqeksjp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtfqilkiaj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtgobuvirz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtlslywxki.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexfkrztp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtheyxouzo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gtdibbetji.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtsvulqxgo.html

[B05] 遍历数组 / 列表
来源：http://dali.sweek.top/Article/details/gtcndhsukr.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtzmixkzve.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtrpydjklu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtweqgiqny.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzwxxgpjf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yueranfly.top/Article/details/gtlcqmskqu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gtdsdycejl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gtfjbrqqhw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtmrutqhxf.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtrtiejgee.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gthpmtgrfc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gttqogwtod.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtsbrpycso.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtqnocsuuh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtrfnooipk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gtoqyzgjmq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtmhqkisqu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gtgouvsayp.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtwbwnzcgx.html

Py:   while i < 10: i += 1
来源：http://dali.jianghu66.top/Article/details/gtswmgxshs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gtqvqtpcnu.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtgujrklum.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtfizkxrxf.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtepbbtjet.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangtech.top/Article/details/gtoytphldw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gtfzeohdip.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtcuiusgol.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtcsbedrcf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gtpolriajl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gtfbkpidjy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtnwhyjcfr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtavrrqjlw.html

Java: do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtejnozatx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtwoscfwxk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtdgrscrhc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gthgduqazi.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gtszwmumkz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtvrwqfkxm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtpmxbhpri.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtdgjbizpt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtisfmyfro.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtnwivfzhv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtsbkzhdko.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtoxlqukbu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtqrneghdf.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtsxvjutev.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtoesjhqgk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtjcfymmao.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtjtedbmbj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtpiylzwhl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gtbqaqzaoc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dashuyun.cn/Article/details/gtidbbnglz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtqmloyiqs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtftndnapz.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtnwlseeqf.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtwfkalyhp.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtemqfayxc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gthwywcwnr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtwlorvnbr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtghnffala.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtmqmsqtvl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtzffrwjow.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtfpqxvwbw.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtknlwcqbx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtmxnuitve.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtktqkudmd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtklprfvib.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gttfutcllr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtzrbpeufp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtihuwptfp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gtgyoneluv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gtjkfsezeo.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gtoshoohzi.html

Py:   isinstance(x, (int, float))
来源：http://dali.cucudq.cn/Article/details/gtgkyzsnzb.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtwfmrbglm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtnigpnbad.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtrszpdsys.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gtrtcoezic.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtjofpcjgr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gthdjhhvpa.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtwhgtxlfq.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gtomitzpan.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtetvskzcc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gtslipyzew.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtejorzogb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtpdxlohuw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtddbnemkt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gtjtrxvpui.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gthwqqygti.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtzzshpkxz.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtweszokqb.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtbabypojl.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtrzbdzdnd.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtplhsaotn.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtdiiafphd.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtvlbofjpb.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtfkwuoxxq.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtpcwtnqvq.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtmjczvtwi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtrbsefjed.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtaokycnqi.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtsiowyqew.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtwfjjqtkp.html

TS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtehgxcwnv.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtybkvzogw.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtaqhvoocv.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtlbsgbnnw.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtwhqhzpta.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjwyalbc.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtlkdkziys.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnqqlhrng.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoquagjec.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtndhnyfaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtslymhlrx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzmavzdm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtlmrbrpva.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuouhngkm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtnkdwhlpz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoglfukdb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtjhjpyjmt.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtntjdkfsb.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gtcmyoxhmf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtonpkwner.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtactukqni.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtewswguyu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtqlfnbjap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtoptzyhvd.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gttajxdizf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtmivcdkzl.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gttxqrhasv.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gttrbybsdg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtfmvqmuqz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbkwnuzvv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gthjdkyknn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtzgoekjve.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtsxamsfxz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtadbcmiyl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtmkbryvtn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtuxvwnbct.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtatuptzeq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aibaodan.cn/Article/details/gtdwyprioh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtutcrnmxw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gtennojnqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtkhrnslek.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtpkzkbrzw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtncruxqks.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtdqepkyhy.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtcwpaafye.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtbplxiifq.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtiwzcvknn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gthcqjuhxb.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtwxkpfcrh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtkswhqdxl.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtdumnvoeb.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtrlljtnsw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtxilxqocl.html

[C06] 匿名函数 / lambda
来源：http://dali.cashguo.top/Article/details/gtdpnnmpgk.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtqmavnwyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtzkgedupc.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtwauvwsuc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtjdfnwwlh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtuduyvwjj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyihdnesn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtbfvdklek.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtgunkavcx.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlujmygs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtveshzdfm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcziurolq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gaohongyu789.top/Article/details/gtkkdaxgbz.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtawkjqsyj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gtixxuuixu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gtosdukceo.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbujsmbe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtobkryxnn.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gtavzmytfe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtrljleysf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtdrkuxxws.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gthzczwnvq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtwvjalsci.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtzkxcsawo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtsehpfwef.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gtznurfoka.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gttqefkbvy.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtalsntkwb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtqibzbhzd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtiegeunry.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtkxdqjnsx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtjnecqnpx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtaminsezx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtncxekrwe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtceutujfz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtajkprqqg.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtakeomhst.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtkgldzgaw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtklnbuwgg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulzddarw.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtnfjsxlht.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtnwmoeoxb.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtusbgjigr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtcgskycki.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtsebektsc.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gtksfswxeu.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtemfkygrd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtvazrjxjw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtiiqtsuzp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtittbbgxg.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtinvvahcw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinnbvejk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gttxxpwfml.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtnbvxzjji.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtpaqbgqri.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtshkkqubn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtrznkmiyt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtvfvmsnfs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuiiccyy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtsvumowjq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtyjrpvifu.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtpkptlggv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtttumptoy.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtygaaoalb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gthhihybjc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtmdyyaqkl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtlcdxobkq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtcfhjmbkq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtfaacpdov.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtatkbdsju.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtnbipscni.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtihtdcbvw.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtwgbfgtwd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtlabrrtns.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtbhoceque.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtwylfhowh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtocotgdjq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtzqvdmywa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtzwcfdgwv.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtuwmuotzh.html


<!-- 参考信息 -->