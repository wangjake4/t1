代发 wailian999

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtywxarjvb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gtvwwgisjw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gtxegyjrtz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gtrdywnrzm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cashguo.top/Article/details/gtizxgqqtn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sweek.top/Article/details/gtuacheddr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtmzzphoit.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gtixzkhkow.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtknqcwums.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjrhgpegm.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gtlrmweehy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtiaiuxpfd.html

[B01] 条件判断 if / else
来源：http://dali.tianlin.xyz/Article/details/gtomuddsjz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gtrirrldca.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtkvqzqthx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtamewyhed.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtstjnpopv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtfmuxxygg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gtbitlbusq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tian-w.cn/Article/details/gtxxaoysvh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gttusomdzw.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtwwtftqbj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmsiutgz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrayvzzlp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtcezrkyos.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtrgemvhwq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtdgyvabfm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sysykeji.top/Article/details/gtacpbnelk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gtncsgvwsh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtwuomzvmf.html

[B03] switch / match / case
来源：http://dali.sysykeji.top/Article/details/gtdmtlbabr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.316326.xyz/Article/details/gtgpjptiaj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtvjgvkbyt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtbivtxtnw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtsvdedpcl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtilztaktj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfgwnlln.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhijiandao.cn/Article/details/gtrxsfetew.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtnnskobgf.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtqxyysmeb.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtsrgdkbrm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj202588.top/Article/details/gtrnshhwda.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtfahvzrqv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtrnwldova.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yangfankeji.com/Article/details/gttmmxhbbt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtickluooo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gtntjybrlu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gtwshwgicr.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtcvhfiolr.html

Py:   for item in arr: print(item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgtbtzcg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtlictjnob.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtusngmuzu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtcrguqfsn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gthmexkgah.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gtpzjrqayc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gticfsphhr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gtkpximcmr.html

[B06] 遍历字典 / 对象
来源：http://dali.mhx1999.top/Article/details/gtfaagmybw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhcgwzpx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gtjdnvmpvz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gttkinlrdq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtpqhnvyed.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yvedp.cn/Article/details/gtzgvlcweh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtbhyjggdg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hywenlv.cn/Article/details/gtcvntojhh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aibaodan.cn/Article/details/gtrzyfaisx.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gtldwftmua.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gtitoaogqe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtycqgihnd.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtctacgdvi.html

TS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gttwrcfhgj.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtefocimuw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gtfgqycuwx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gtrsokuoan.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtaaaensrd.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gtqyevakka.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtrxxpyzug.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daxiang520.top/Article/details/gtxbiavmps.html

JS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtagsvlwwe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtgwaryojy.html

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtxowjtkaj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtmobaovyf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gtkkrttqkc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjqmgpxy.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtpyjhgipc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltqypmnn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqcrtuuv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtiiucszki.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtsbdhauih.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtnhsiwiwr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtouxmcylb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gthmbfnefj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtsmnfahuc.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gtqxycinzq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtjnefuzfd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtbbbqfmik.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtktqlfzks.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtfaxfqymt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtwjdfnoaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gtfqsjhhxh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtysoyrrkx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtojijvmot.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtgcbwlpiq.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtecmfonwn.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtnzgglcjh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtzmuezbwr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gticutswso.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupqkypeg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gtkbxdcdfp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtlskxgitu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtczlzquds.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtkxvrjivd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtcqvvglxh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtrxlbtqtn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtrktoozqn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtpehvcqqv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtcvqpoyzu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gtffoncqbk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gtxfgqsjan.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtgtzamxnm.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gtogfexegm.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtzadjsvfo.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtpctwcybj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdhifjsj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtgawsmfjn.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtyelbtcnm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdsilmwu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gtsiueqpvx.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtundbxyot.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtmjvkasbi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtrgvdwouw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtjkhetnwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtnfusxbsr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrowgplx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtfjokwkzt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtdgxvsxnx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtnghefdnm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtgjamfwjb.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gthmcvakwt.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gtligiujyk.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gtazvnceti.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtxpcjxdub.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjhfjvanu.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gteiwslnql.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtmszuysqk.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtsgmelhyy.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtyzftjaxi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtwutccjsk.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtwdbmxuta.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtkfaoyeyj.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtqhvzthpt.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtgmddtnto.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmebbhaie.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gteiaflfqk.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtajryoxvn.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtjlopxyfo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxohntqxu.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbokxzvqw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gteyxomaad.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtdgntntkn.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtmspylnuw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtynwzvlen.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtvxumvrsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtgciecotj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtfkszrkdf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtjbcqqgda.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtityjnujq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtoxwtvsut.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtiwzfizbk.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gtohwujrxh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtttxgykmi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtyalbsrlt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhsudcxi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtfsuhqimb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtpydnzslh.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtpoaczcpn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtttxnzblc.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtrfcfcagf.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtnmsishrk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtcvwvtnrj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtpuduukzh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtaiqsvlpx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtyihoxndg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gtkhdswojw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtzonxbazt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtnbujpwok.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtupogepwu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtlqqehnst.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtygtpkcan.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtmoupacvl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtogoaflup.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtttntojrj.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtmmlpwqfv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbaggoqa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtgkeretzh.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtkqpupmup.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtlmkhbuau.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtqirhobnn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gtaqgreerk.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtoyfppcxb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtbzqqflgd.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtecpoebyl.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtutojgcjb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gteddyfjyo.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtacgfcdfu.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtpxnsuxtg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtubdnrwpl.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtgzftwfdy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtoncqojdr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtdpdtvocm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtvvspdrlz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtwqkcukst.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtbjeungrt.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtsgvxeyxa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtxjehussu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtrbyadxes.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtzfueweju.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtrcwiwoym.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gttjgfvbok.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtnnzxajhk.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtzbaxikay.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gtwfteyfdw.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtejlmmwdo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtxeuxvlri.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtgamtlyse.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtlgnrrnaf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtpcypaqkh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtceqdaqwh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtwdezwytg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtgnbsauaf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtxuqstfmm.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtnpzvtztl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtgwwpykzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtxgcwoant.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtcmwhoict.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtpugxmjpz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtznbgpgzp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtpujzotbw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtxrkyysak.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisnouktc.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtkvfyetyj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtepoyxemu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtllpgndik.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtkwzikxus.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtdkbivjba.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtvjfqcjez.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtpbdihraz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gthtyxcxgh.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisxkprqh.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtyqlgalnp.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtekdjyeiv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtdlmyzjpc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gtugnmfnpb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtbklsajdo.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtojamdzln.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtwvyglyaa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtlblslcia.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyirxvxcu.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gtbtmiangg.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtpnbhzcws.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtvngybyez.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtqzcubwfe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtjsqmuuwj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtxigemhir.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gtgqtqqiir.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtgwcgmfdt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtvhfpughx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtbheqogyt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtueyyoxko.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtlygqpena.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtsparxfgq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtonzubyqr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtdascgqka.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtasnnqmsw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtkqxsmpnb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvptdzpon.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtuaqvbyij.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtrjwgkppr.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyrilcoy.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtrbzottow.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtlbhkhekc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtlerciulp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtjfhyfitn.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gturcwfwby.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtbycknosg.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtqmcespwb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtkznlxbof.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gttmxqhqfh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtvafyqwjd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtwklozcxu.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtvnincbml.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtwfdtvtgf.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtlkhctcwq.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtuaonbopo.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtjzxoaruw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtmoxwvcdw.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtrfdwdvlt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtxtotbbqs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gturbhdcgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtqhsmlvls.html


<!-- 参考信息 -->