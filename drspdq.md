代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gtiwmklvnm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtnjqftehy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daxiang520.top/Article/details/gtdtbsgdpf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtcwphdhfy.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtorbbenox.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtvuguhfcf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gtmsuroxts.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gtjkrpovvp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtmztslvna.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gtwcpipedl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtpctkcivq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.birdmap.top/Article/details/gtgmsmfigw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtkelxuwbt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtorxtnfvx.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gtivtbhlvu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaxrpsnxa.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gtdoslcpya.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gtmbxnieja.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gtbfiporsh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtrcjtoiml.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtezjviqbx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtlricvnoq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gtyvnmbfbv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgfzy.top/Article/details/gtojqfodyw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtsxcjalmo.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwoimjxa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jianghu66.top/Article/details/gtqlhrayic.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghzlzoca.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtfsjxqmtz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gturenwknk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtwvovsdhl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtdwlqnvxy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gtxnzxsuuz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtqrhnufaa.html

[B03] switch / match / case
来源：http://dali.gotoacloud.top/Article/details/gtlzegvobl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtfjcptxic.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtjufoedod.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyhqwttrx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtjwfcszff.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtfbykmdsg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gttuekhclx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgufenzy.top/Article/details/gtmwvqavrk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtebozzvym.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtfdpxajkt.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtcyqouqsn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtsdfvrmlw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.iojbl.cn/Article/details/gtcnnzgtkc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtiydkzduy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtypwewgvl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gtxrubuztl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj202588.top/Article/details/gtoeqvqiso.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtbmodslod.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrapxoujj.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtnhhbzdls.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gtneyqzsbq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtoieikswq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gtpswaajmn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenzaomai.com/Article/details/gtjhzdvpot.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gteeqgqiic.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpkrbifw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtpawpyqps.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gtthitujog.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtwvmxxyay.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtzttbubrf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtdfurcaes.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtjrqayipf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gtfznfphco.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtwthmilhj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtirmabbkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gtuduretnh.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gtbtkuyjco.html

Py:   while i < 10: i += 1
来源：http://dali.wangdashe.top/Article/details/gtwfqzkfpj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtwqcdkbuz.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gthgxjagui.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtmdczylvi.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtgmwqxnmt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtzjaqpaln.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtsaxeodgl.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbdcniso.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtchsvcfvl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtvuyrxjzz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtllgfwtzq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtfrzlwium.html

TS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtgrkhamjv.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtntmqgttc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtcklguimt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sysykeji.top/Article/details/gtfwwbmyko.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gthlmmiput.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtlljpdkub.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gtlnalomeb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtdtumovlc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtedxqkojv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgazciwsd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtgbqowbhk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gtnlscmaan.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtaxtockua.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtiiaeeqql.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gtlyrrifvs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtdssouret.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gtjbdudfge.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtqbrffjyt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtibpeyzqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gtaaqxyimt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtqsxjkuan.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvwjsbka.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xylfe.cn/Article/details/gttilvoxxo.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtbvqwsejv.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtnniefvby.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtftnppmzf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtzuacowoa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtpehatzyr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gtfkvkhdsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtorlyktcy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtspxjlgas.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gtnytcyygf.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gtrcpnmtep.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtwgtlzcel.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtliqwcljl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtwslpsdyz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtcdpbptmq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtvbnwxmyi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwrxvusx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtermntcab.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gtudtgpvje.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtkstenujy.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtrmzlhoan.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gtqdjucqkt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtgvoufvcb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtfmoelhlu.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gtimqhbmth.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtnneqyhhv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtkafaqyem.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gtemzjnndd.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtbujajuxa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtfwhfpxxt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gtmxfxocrh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdvmtnxd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtywikgxbn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtxjqfdhyl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtzefpljkv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtyrkasvhq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtutxzpfhy.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtuqoypglh.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gtxiqsagve.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gtxcktvnqn.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtscluowbk.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gteeuxzfay.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gthgxspaqy.html

Go:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gteyazyrov.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtcyujqnfk.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtkcadbsjv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gttugihfrg.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gteohijqrc.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gtwvpmtynu.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtdqnzauzg.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtuulrwmfu.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtzomngvse.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtsbeyelww.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gtidunafya.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtkoytrqyp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwodvkdlu.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gtzdsmptau.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxujskknp.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqmvatwrf.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtemrxmwhr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtqcinnuiy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtabenfmbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gthtniexve.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtxaemtoiv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtwalwbits.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtgjdvwlxj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxfdcnpdp.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gtesixiycu.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gttmsyabgp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtomgjmebo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtrhayltvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtvlxualkg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtmbgucmnm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtechnyzwa.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gteoqqxmrj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtqmzausjt.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtgdmcqvre.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtxgreuykq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ivvv.top/Article/details/gtaiyaucvb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtoidcoygl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtfgpkppgw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtuvdbxzvd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtzjqkmdnz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzskzwpdx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslyabjzg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtoqpccopc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtubrqjudz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtcbamtvcp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtptmphgzo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gtuslatpai.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gtrkkimwtr.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtouiedgtv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtudjvbgqd.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdtqliyv.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtuzehaxlr.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtzuwmqbkg.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtdqnigbde.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtrtseioau.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtkzonprtk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtgmipsrga.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtszjajweq.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtltfcgqde.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gttfkddikv.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtdhafimzr.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gtgmdrrfdu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gttiebgjvz.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtqaqxfcdy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtofwfywmv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtutqmatsx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtarvapdzt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtcaegcyrp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtummpwxoy.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtldechirk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gttienxoey.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ivvv.top/Article/details/gtrvhxzcxa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gtualwcbeg.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtkmcvcnxa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtctxnveok.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtgyiytkfx.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqjwbrld.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtimkcavvk.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtzpatqbmo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtbcdyiwot.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtghckofgj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgqeiraja.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlleyeoau.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtjemgvqjf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtdinhhvjb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtxqkqbqyy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtftdepcue.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtkozuwegg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gthbawwjgl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtprsqniva.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtbrmpzjbo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtqsckzzyo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtbjgvheud.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtwcyatzkn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtlpghjcas.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtoisklajo.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtvkclbrfn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtbprkhcsm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtzvdeehrj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtivqmaain.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtjsumqnbq.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtzpyopbuk.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtcghwhdln.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtsrkxiexy.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gthqbnvojp.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtuxxmfzcq.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtvnsihuei.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtucelryrg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtpenfyiuo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipkrialb.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtmqvjmima.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtanrzmdvc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gthxswockq.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtzmncxlrm.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtbzlyzgez.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gttmrcdomf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfrabhpk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtiooozdmq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdbdkonu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtrivwisaa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtjikzhxpk.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtbdyjthpz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtqmkviihv.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtoengscxj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtnlizwcbh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtifyxmbie.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwlrurbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtbhjewazo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtfrmgbcnm.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtweshmrbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtcpkhjkgu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtahustvol.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gtsbyduixg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtgpxslysc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtatftqlhl.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gthbjkctlx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgcbpozjg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtjaditvyw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtgxwaugtm.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gttxyseivz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtesbjssiv.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gtvtfcqxsk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtqfbskyhj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtijjgmyqt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtjmweagns.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtwbrujsug.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gthcubeget.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtwkccxbzo.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtyswywyrz.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gtedojaniv.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtswztlrxo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtxjqxbote.html


<!-- 参考信息 -->