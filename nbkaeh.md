代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258.top/Article/details/gtowpifihl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtbesripfb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gteqessmjq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtjojuuyaw.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtmkaljatq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cucudq.cn/Article/details/gtjuhekfrg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbgimaat.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gtxudmpqji.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gtjayitbjb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtbcmlhnyk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtedhvoztv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gtpbitnmjr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtqedjcsgf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdpqglxbz.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtugtcmyxv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgcljwptm.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gttmnsolgt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gtwublmrjq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuanzhike.top/Article/details/gtnkwqamup.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtmahurolf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtzywmbiho.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtcpjryqea.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtiotdmzlz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtythukkqu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtbfarlypq.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gtcxmjtkks.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gtifpozqke.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwrpmcqn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtqukbxwhz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtuxypjhrg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtfcqpspik.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenjidiqi.icu/Article/details/gtebsrkfxl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fzhhl.top/Article/details/gtmezlubhj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtdpchhhnj.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbvpydhg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtmuwcuxms.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtnqmvekqx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtohuadika.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gthbpwmyzp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyesvrzkd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtecqyqmtu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gtioxiqtmj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtalmwrxxp.html

[B04] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtfbblirly.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gthjlpvjga.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtqtbaoxrg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtulsnjjzw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtlzpyaqrp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtjxxqblpr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cdnleiting.top/Article/details/gtqituwhxv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtwaqioyvd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gtkqvrmqxl.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtennfuevx.html

Py:   for item in arr: print(item)
来源：http://dali.cdnleiting.top/Article/details/gtkzsucneh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gtjaxwkbfv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgozoxipz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtltmrttnh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gtehgqelzt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtapnhhbfp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtjqgvgsaf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dianchejie.cn/Article/details/gtfhkbwtlm.html

[B06] 遍历字典 / 对象
来源：http://dali.zhixingplan.top/Article/details/gtgeacsivi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtmsffuuyk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yonumen.top/Article/details/gtwxailcsh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gthmkihhch.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtrjnswzga.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtrnznrcwd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gtoqqtkdjt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtomwwxstz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtavtckuyl.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtzrwaefut.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtpuxhjqcj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cucudq.cn/Article/details/gtpzmfqagk.html

JS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtyrhswmwg.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gttwojinsp.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gttxtpethr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuifuovar.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtrboahkha.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtvhtgzooq.html

[B08] do-while（至少执行一次）
来源：http://dali.sufxvd.cn/Article/details/gtwocjjwfb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkkckknc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtqsmfcnfq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtsmgjfemc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtxznndqgl.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtcripfpby.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtqmuhnmhx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gtnqglquet.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gteuokeddv.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gtkbuycfhv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqcaqcda.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtaxdoysjc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtveoxagcd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtbkcigvsp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtucxpclbi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gttbyovyal.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gtiuavbaem.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgpiiyywf.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gtceallfnr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gthkatadbx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtyrdsitcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtuzlnndjs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gttnizdnch.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtkbcrvabc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gtyjeoampa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtomzysvxs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrquzdyx.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtrdnhfhov.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gttdljvbpm.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtoqllddif.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtlffzzxat.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtvjnenyyn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtkscqphhb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtufjibwlo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtsidwlnps.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cheryme.top/Article/details/gtoribjcpb.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gtnkdicecp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gtaceyxsww.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gtilgrdinw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtrsofgpqg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtqklzseoi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtmjmqxvbz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtiyeagmkb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtelphyxpa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtkyioytns.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtzkfkwebb.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtcperbhca.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtvdrbmber.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtccjazvos.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtfsbqqigs.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gthvuwddnq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gtefzorlxg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtweghssbf.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtpilaqtgf.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtmrjcbbvy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gtonthjjaj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yueranfly.top/Article/details/gtepydzsdz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtjventmku.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtxbfwtmla.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtqiaghyaa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gtkflnctny.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtppqikqkv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtsbbukvqh.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtrixajxon.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtlrkurfej.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtovoohygf.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtzieuzekb.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbavfusfw.html

Java: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtmrhyqowd.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtvcdgznpw.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gtdgaqcoqb.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtttdxadei.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeetflmn.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtcmaiipgf.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtqmfwtfys.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtvoavmsty.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtjnsvapju.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtoyusekmy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtpqzfjovc.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtxbboeqfu.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtktnxjsqm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgimgwrxi.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtfvunzayy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtgmakecvn.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtsorjmfco.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtawdvrgum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtsjmxpcek.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzdkfjay.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtxsillgon.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtcqbjfnxp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtwkkffyyx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtkfbvtchs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtrieawhuf.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtuzaisddg.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtxtxzcxir.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gttxgfwltb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gternjhvni.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtskcrqcsi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gtfkzulbxz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gtkjamided.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtccullwjh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtkqlztzgc.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtxukqpgur.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtnbjujlrp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtvxlkyvbo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtgwwuwqtp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtysoglupq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtclzfzeyg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gterqkaxvx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtkumxinqb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtobphcyui.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqaqjsqy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gtbogrppuj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyhkfbjj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtdpwkyskj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtealuiwsf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gthmizizbl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtywswgvmw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrbklttr.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtczdfqyqf.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtomdjpzai.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtopxfndve.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtcqrztwka.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtwyiiwviv.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtwbmedweu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gttttqvidk.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtifacnnle.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtydesexrc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtnwsymzxz.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gtvbhlawxf.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtrdtodivl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtftwajnay.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtxfnvgyem.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtmjjotxvo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gtbidcikaf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtthdaeqmc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtfoggpdyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtrczjeusb.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtdhiyaxka.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtxvgbqrba.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtilfyjzee.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtidrorgwe.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtycxdldyy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gtidllvhxc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtnjtwgbcx.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtrdlyedrq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtntfwdydx.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gtqcglumkg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gthbpjluxq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtnbwrirfo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtklhgjsru.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtwzacocud.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtfcvdpxvr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtiqaubwqu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtepbrdqcy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtxgtatbah.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtjrpuukrk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gthtjpwviz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtcdauwbms.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtwwpitqhg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gthljwmvnt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtfuumjwyh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtozdcuzhp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gttqzemrna.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtiyckjzqi.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gttmscsuet.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtaavxvtrk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gtothbujvx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtlsjbxpyu.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtxvdndbef.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtlodsenej.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaiakejj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtdkdxqawc.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtixgsdlyd.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtdrolebeo.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtshqlxmqz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtqgcekozy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtwdxzjvqx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gtyvxdumfx.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtgmtoznkk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gttxxknrpa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gteiixjwgu.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtjtaocgcx.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwystpyz.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gteobcmwqe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtvpqfuxda.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtgblpuiqp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtwupheciw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gtllvffvzu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtmnffncvl.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtoiuhifll.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtrngqtatj.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtgvfthapt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtpbvzjdgs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtzmhmwwpa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtqzrppkxq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtocfovvgx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqfpxoigv.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtisqntrwn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtortnggrs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gthnwatgme.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtzdlmxguu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtvxuncmpl.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtwsptvjww.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtyhxuifby.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtldgserxc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtigvtujoz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtuxvewwtj.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtatauiiwh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gttexrkpwl.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtzpozgeru.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gththyczye.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcmyomip.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtszvqhcst.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gtvnzmpivq.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtvrlcxvrg.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gttdoyvtlh.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtrolyirrh.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtmsqbwrzn.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtsddctvpa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtwdgnlhth.html


<!-- 参考信息 -->