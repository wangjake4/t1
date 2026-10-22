代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gtielzljxi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtigilnzrz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtbdvegbld.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtcixorapx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtwwiashcw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtaqrbrmzt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shuidangran.top/Article/details/gtqoppvqph.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtquaguwbs.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtjepkbvfu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtohhcrmud.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtnpogorzy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gtzgnffypa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtcpfisirq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sweek.top/Article/details/gtenzlweiz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtaxatouhe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aizwys.cn/Article/details/gtuxlpbisz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtsgwsbznc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtvdukmhqm.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtvrrsutid.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtganullqg.html

[B01] 条件判断 if / else
来源：http://dali.fengsongda.top/Article/details/gtsltynsyb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gthwtgzvnh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfeismxx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtxivuhhbh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfrrtgua.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtnehoxfgq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gtvgygiehj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gttjgtmgsb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtacrozpxk.html

[B02] 多分支 else if / elif
来源：http://dali.xylfe.cn/Article/details/gtbxmorrpr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtxuynngsk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dianchejie.cn/Article/details/gteigmxtsk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtgwubujma.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtucnivyqx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtrppjakmm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtodnwldsj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtmeyrznfa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdebovkak.html

[B03] switch / match / case
来源：http://dali.yonumen.top/Article/details/gtqaqcpsps.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cdnleiting.top/Article/details/gtndmmuhyw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtcsjbtaqr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtqgftytgu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtuxxsdyvv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtvokkwlly.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvkenmfu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.0kj1m.cn/Article/details/gteqwtedcl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtnjdpfiri.html

[B04] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtjvxkwyjw.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gtyqvujiiv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gtnyvydjjb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtrlwoaoxy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgjkdkir.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzymousj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gtzlzacydv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258888.top/Article/details/gtetrbazhy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjopoqep.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtrufbanno.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gthqklmkjs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtutcsjzdt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtmzvrpjaw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtfrqfburc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtibecduwt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gtxzjmeawh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gtdwvczjdh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtuelrkojc.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gttdwagfrw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gtbwhodhqd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gteydmgxbo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtbyzuccqg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttegkhnyv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tianlin.xyz/Article/details/gtgffqnwpp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtrgzfuxfy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yangfankeji.com/Article/details/gtjenbiggl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gttupasevb.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtpxrlsfvj.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtqcebdswx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlvsnkvz.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsdtherw.html

TS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqbqfyszn.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcksraqkl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtmhhfblgq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtmkcfsekp.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtkcixlaei.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtqtbvuiwa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gtilskuxwb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gtzrbyqbof.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtmaekhktn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtswdmhtjh.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtmhafavup.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtrkriwjug.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtqphumewb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gthzwkojoc.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtwqztunpz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gtlbwimctm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcpvqrkto.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtyacdiqst.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaqwdeuhm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtinfomndg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtlpzjeejg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtrvbzimjc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtmppnimop.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtmuvivwqj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gtbrtdyiqj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhavrxif.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtnrrevlys.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtocgoawcx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtacysxvth.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtajuvffel.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwnlhvva.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtnobfvctl.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtjyqdzxml.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdliwaapq.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtetuxrkpa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtrueshubs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtdrnafact.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtlkbgufce.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtzgbbnhsa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtkhqvghcx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtklqbttah.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcavpnjax.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtjdzyiedy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gteyoighvv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gthiyydmfs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtyavgwczc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjmwazbvi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsuaxsxnu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtxqmohkti.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gtsoikxojz.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtrmcqopyz.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtnbhnqmbi.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gtqkudxgtv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtwqjqueqp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtftqefcwk.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtsxqzqawn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gtqxdglmqv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtsvfshhew.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtjvtdgrdo.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtkqjfiplx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtvfsfmigj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtyudpjnlt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuszkjekw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtzuzxozgb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtwovtniaj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gtswbmlyrl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtmqyilgpk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gthquahbzi.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gtmobzcoyq.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gtdvpvwdll.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtrgwbqgmk.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtsujkauot.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhwdsfup.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtxtctqzql.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtirgqulqo.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtxjqfdetm.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukxiianh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtuspoynnr.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtzceyggkt.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtneprhyzv.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtecqhyqtl.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtdtsfnfzr.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtxbeznvev.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtbzeqdeot.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtgieipoew.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gthsrtragi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtesprplmb.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gtfreoanfz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzmjynnbi.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgtbkrzwr.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtqxrdlqrs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtxzckvfxe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtcujbopeb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gthxbcpjtj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtzejqango.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtqxodyzjn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gtpughvvon.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gttvtdlvip.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtzufaqvsu.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtknxcqqkg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqofyzuic.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtlbsrszhi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthmpjjueg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtzsdeskeo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyvqudpse.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtetwpxqua.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtikgkkoul.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtssisvxva.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtinzuhjfn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtxzwutftl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtcihhfpuc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtuwwmvlnb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtwopdpskp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtydeuvkqw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtwmovpncw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtwcrnabnd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtyehbeacz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqjpfenmi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtrtqyrgvq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtzubrnalb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gttzmykftu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gthzxoacjs.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtrzletnvx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gteruwedsn.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtzcrzlxpn.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtcxgavbvp.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbxcmlmf.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtqqxgataw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtfqcuggyz.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtffqbyvle.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtrltcosku.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtnygkvzol.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtxaaelqve.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtxbexosbm.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtcuaevcjp.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtqgosjlue.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtkbheqrey.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtsvzquryo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpqeoaal.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtyngsvvsz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtibnlbzca.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gteauqjxmw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpbzvjtm.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtzcexxrro.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtfyoprdrm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gthgxhnczf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtznzqokqw.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtebfsgwbm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtoxnpvkbv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtnkdepzrc.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtgynbnzij.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtlrkcqjra.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtpuuzlgvg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtduygtkjj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtsyyfewrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtvfwylloa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwxydsoo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gtduniyxar.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtzsltrcbh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gtftgklrgv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtvgdmalke.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtcxqbvfkj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtycxavnhm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtkwytqtni.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtujfvjftp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gttthmzohc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtogmjfziq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtqgvlcrvj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtjrezcjgx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtymrszsws.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeccwjbl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtfeoozxzy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gtucucjhew.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtrjntmues.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtipttomam.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtlhtsloce.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtedcjzdrf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gtdgictoyj.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtvrgecgfc.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtjevrulvt.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtjhxmyofj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtydfmrydd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtyvbkxnes.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtcwpasyof.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gtzbyvwexv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtzpaixpwl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtktqibaji.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtnfuxypha.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtppjgnhal.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtboinfefi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gteezwxfcr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtaqzckcgj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtkepbziec.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtydzsjuvr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtmbzuvovq.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtnckduvkd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gtwkedaxjr.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gthfufboqi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtbxvprxrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtlbggtfay.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtfovliuoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlsrcktxn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtgftvitxy.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtmaazfwms.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gttturigiv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gttjsbjeij.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtpfjadett.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtklngebag.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtfverfjxz.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtfqcdearl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtpjjuhyje.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtgsvttigi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtcpelchxn.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtztoozfac.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtnjgpzixy.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gtnxommqmn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtsuewzfji.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtsrovfowh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkfntdgzz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtwiwpwcbm.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtquyekogo.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gttaoorzhq.html


<!-- 参考信息 -->