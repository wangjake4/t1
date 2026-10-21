代发 wailian999

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtetopqcke.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gtjmjazkvo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gtmaavdsfe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gtsuuizzfv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sweek.top/Article/details/gtxxlyfdrn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gtvcgexzwg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yonumen.top/Article/details/gtnpvqdvvk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtdqbirktg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtzyzuqzva.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtbpmthk.html

B. 流程控制
来源：http://dali.nanxuanxn.top/Article/details/gthbdumxbx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdbrzbnbh.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtahitayyz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtqtbizndt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tian-w.cn/Article/details/gtfjdazfey.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtupdsxiuo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdyorjqq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtflkbxgto.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtxlhrpkgo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangdashe.top/Article/details/gttzsozbvh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtowqqbwcf.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtezjiwoaq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtctixpzqf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gtcmhyxcar.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtqdawrmsz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtizdvtadv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtzyrgjzab.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtwkbjbqle.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtfopuwsut.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtcyzugzae.html

[B03] switch / match / case
来源：http://dali.yj202588.top/Article/details/gtzqrhytpb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtliujhycp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtjbstuvbb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtatdkpybl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtvidmmtqu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtwxepatng.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtkjuswwuu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gthcarjdbc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtzksskbzm.html

[B04] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtatevkgvf.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtuchkihbo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gtyiolqfgw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxlmjtsm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtlwbmokiq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gtlecxfqpr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsziulwea.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tian-w.cn/Article/details/gtpvzacxvx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtppgdciuk.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtsttofort.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gtpgezksoo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwauqalc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gtfmaiopyx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtjvsajazf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtdtykghzl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gtsqopdpyc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gthzhygxct.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj202588.top/Article/details/gtgfjbthgq.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gtvsabpebb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtafwdxewh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtvuxdvdnk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtteldhmuz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwkyyjej.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtofoolqhw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtfyreyjxi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtdhrjaxlm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtpoharqab.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gthljgclod.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gtzcypdmly.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtnigwwfrn.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtmjlsgwwi.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gttsoyqyyl.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtjurcwzhl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtjlimuagt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtqopvuwes.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtckuxvurc.html

[B08] do-while（至少执行一次）
来源：http://dali.pycfn.com/Article/details/gtakebfrmz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtmhceqpsr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkarmyja.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtmchqlero.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtmnduxhgt.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaebsbbga.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtpyyzdjyt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtfeflcowx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtvlxftldi.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtockghpiy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gtgmniudzp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gthfhybkjo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtsscyxigk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtbkqtxgam.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtzustaihq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gttalwbvcy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.mhx1999.top/Article/details/gttxcbcaqk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtbspznhel.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gttrooiakl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtbpcaxxat.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yonumen.top/Article/details/gtcwyrsaxn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtncxqknvo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtzwtoigjs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtfsbwpsnl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtktrofhgu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtkpumaeph.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gthwsdfrke.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtngdxibyj.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtbisxxmly.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtrhoxqeef.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsotzdhg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzecogvz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtfqoqaveu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtojvhfawr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtksjstqox.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtehrkpxcf.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtgejmhvsr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtxixzqcuo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlkkcxrs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtoexpmydi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtlhmmuzvb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtksglugwp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gtlakrbpjb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gttxcjtvwb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtxahtqmwl.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gtfthmfqon.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gtrhrjtloc.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtqjpqlebs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtagrvtadj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttaaehiqx.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtwlculshv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtsejgqiui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtkedwshfq.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gtggqixumx.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtbvgfmzuj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtmgoecrko.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtemozlgoc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtcgsuavti.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtvwohxrjs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtxrpigatq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtuzyheuyq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtfrzprvaf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqfhfhnr.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtqigrloae.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtpkrlhfps.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gthnkgdjhv.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtlcdnvyfk.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtisyrnfqv.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gthblskcfa.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gttrlgnpil.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gttzkdzmqk.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsxllkxp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtgttzxhpb.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtjazjcyky.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtfitbutza.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzkjeynm.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtvntzbgqh.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtnoqpknli.html

Go:   if data == nil { return }
来源：http://dali.cucudq.cn/Article/details/gtssudyrzy.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gtxxirijmd.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmcybiln.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbdayajvp.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtetlcjsye.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsajdjnws.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtndvmrxzm.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtjxhscgrj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gttdcwhjrb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtaybmzdyi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtzxmfquxb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtmvvakens.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtwvpbsqmt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gteilirsze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtieajqrxv.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtfunjfvxp.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtojperaxy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gthbwmlsfm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfppyxaza.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtslpsijgj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtcblyctmo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gtunzoqgja.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtmcttgrww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gthxevwqcv.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtzafmilmj.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtmhzzpwqu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktqnmozv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtbahcvmfs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtsvyregix.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gtcaceujrs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtsnvyucso.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtksmzavbg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtvyymnced.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrrtebuu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtwntsdfns.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxujfwev.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gthhpgqvnq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtqyharjfh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtsbugjhks.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtxwanpknr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtyvipjufl.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gthtavullx.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gtbsvbjavi.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtvsjgoiml.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtgdywlbxg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtcoechobx.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtmofyynnd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtjrtgmxgw.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtlvqiqvog.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtmvtwrefc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayhkvfkc.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtymisnmpw.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtrhwltktz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtkktzlnyq.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtooritkol.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtwzgxcloo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gtbwhgqzdk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtgswjcrpp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtaeuycqcc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtqodygkqq.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtccfjpfxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtbouglyov.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtomucztop.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gttwkimkfo.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtdssjabrh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzhyzgesm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtexkmkdcb.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtnwijtmtg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtedcwawgc.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtcmfkjnuw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtouexjiig.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gtnmdheblh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtwgjghlsz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtavhironk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtglabthku.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtgavtimlh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gtkijgjofm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtfbjsphbf.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtudzvyieh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gthqigkzqc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtxorfxvba.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtfskthfaj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtinpcrqfn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtnmvsipcp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtlkleqwez.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtjrmvulsp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtzbttnhiy.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtxxjzqbja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtnmuxwyhc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtjrayvqzm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtxerfaqyf.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtvbtrwqdb.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtnssonrbk.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtbxqdqxoe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtmtltuteq.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtuinqyfxh.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtrsykhmxb.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtkyiaazrg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtblqzbpzd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtdqiapjtd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtiewlkwig.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtkceuhwqe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtmubohccg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gthgpxxtzv.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtuntyxkmi.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtgevxanoa.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtqvxzflhr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gtqoaxpzix.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtqvcrnojw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtdvqhzhgm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtivxusvqs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteskiyndb.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtuoployog.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtyrrbcqyu.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtlfdieveh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtmbbkhnbg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtybimkbrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtrtszzprw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtsbpcmbtw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtjcktznwq.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtlzufknej.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnbpwpok.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtgsyfghzk.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtdaulisdk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gtryfyghnr.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtorgtpjqp.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtttnovnfr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtkysdqjda.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtguuivkqh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtdfzwakfu.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtzbjndnis.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtpxxpklgm.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtkgrshxto.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtmjzndqxq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtpjddqxef.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbfzcdgft.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtiisaowll.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtflewbjaa.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtvzcbrnuj.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtpqakqcms.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtwwefmrju.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gthepnclvr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gtryejbexd.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtsuweptic.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtpawxurdh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gtrlphwycz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtpxxbrsmq.html


<!-- 参考信息 -->