代发 wailian999

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtkduvstii.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gtgoplcxqz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeawwdnt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtdingcoej.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gtcptaodlu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtcapfrdwv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shzxlz.cn/Article/details/gtrkdlfbls.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtswfzcldq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtjnoqiowt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwyiszfyy.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gtzvomkazf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtuvtpcgqe.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gttshnajmd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtngulhsxs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xziqi.cn/Article/details/gtcltmhiqv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbylbgzgx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gteovtfqnz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gttkjuijia.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gtalabkbjw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gtjvkyivtp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtpgnmssns.html

[B02] 多分支 else if / elif
来源：http://dali.redwolf501.top/Article/details/gtvhbpkqaz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtldlfuzzv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gtyrwellyr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtqhopvroa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtthsinhzr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtzuqggkrz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtonphekyq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gtlpnlfqym.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gteqybvfea.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gtcajbrfvn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtqbqeiycq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtflyzihyl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtqltswzyy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtclzmipal.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtmbalbnsc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gttmivegrq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gtnqqusvnw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtgmlixwav.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtfvuxotwd.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gtjhhnirad.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gtxrnloetn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtlzhbgcoe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtohqnqktf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guowangkeji.top/Article/details/gtwyguglcg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtdknkkadp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtjloksllm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtscrnnosw.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtvtsidocr.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gtrwcbijtd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcayssnjw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtgseplvjc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gttueefeeh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.316326.xyz/Article/details/gtwgwdjnzq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtilcgclfp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gtwodofgmn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gtbfmrmysw.html

[B06] 遍历字典 / 对象
来源：http://dali.yuxming.cn/Article/details/gtnivpzfco.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.meibo888.top/Article/details/gtiusaqqdi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtwahtaevn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtfwzbluqt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzgsahrmw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xziqi.cn/Article/details/gtligguqlk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtvuhvaifc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtmyewbamg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtdzlorlad.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtknjkfryt.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmahvvfvh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gtplpbukyb.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtfqddxjzo.html

TS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtbfhiwuyq.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtpvbdothn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtzvedqdqt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtuozlkjgh.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtvehvheem.html

[B08] do-while（至少执行一次）
来源：http://dali.zdqjudy.top/Article/details/gtrmnhjqpd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gttekldjma.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fengsongda.top/Article/details/gtoglmqbvz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhzqwufi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtdzxtiorl.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtfzmhajqc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gtzmfcgqrp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gtjddykbln.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtyptrmdqi.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gtxgwrqlxu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gtcdwxbabc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gttxvcetcx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtzacrocoz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtzgcbbokt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtptmoliqv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gtxwabwypg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtfwljwocw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtwdvvuosb.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtsrucviuq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gttvfnnmvs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrcqjtwcb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtaruthrst.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtzbkmfyvq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiynxzanw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtautmjzjp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtqnrbvobv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gtmjbsezgg.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtxweywxsk.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtfpheglua.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtiixjvtlv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtdasnhmvt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtnmlowslx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjnhuhrsz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gtgiacdcjh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtwssldgbp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gtoorrxijt.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtqraewbye.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtbotvgcez.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtyigirbuc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtotcvkgdk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtohzvvzys.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtmefoyhlk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtvrujjtvc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtbemtoppl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfvvazgd.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtgosaphdw.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtfnyzqoki.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtmqdeoulr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtspjlbawu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzuxtqcdx.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtwtehodfa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtqibtqkto.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtajtrlpxg.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gtsqnhdfod.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtacuvvqmr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gtcbnlolhn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtaeqrtyjo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtlikqbipb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtphuexbgg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcvlcjyh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.snrcjt.cn/Article/details/gtvaalefux.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtisfvrwxi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtcqouhxnn.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gtrbiujubi.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtufzzjoyi.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtbkzrtdgl.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtajgsurzf.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtsenkknhw.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtufqnarmt.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gttmoiojfh.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtjklryykp.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtsqmulioe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtjfpaohml.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gtxueiljam.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtcwoyvzbr.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtwkphpbfm.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtphdeyeov.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtfvjevsdk.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtoafspzgq.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtpkfevstp.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedsyfpvn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtocrebdxe.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtllezhnab.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkheydjwc.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtrhmfwenq.html

Py:   def add(a, b): return a + b
来源：http://dali.daria6918.cn/Article/details/gtonbszalm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtwpcyzvwz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtgoyizubu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtgucksxbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtfguppgpt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtwssetciv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtzslreztn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtxwxnzuze.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtheyfmsga.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyftomjah.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtnnwjkwsq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtwcktxpws.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtmcrvznwu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtnakfajry.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gtejemwrsd.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtxdwolenc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtopaqstsm.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtagsaizij.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtldygnhsj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtavlwhtfo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gthamafuck.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtwvnsnqel.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtcxdvwfhu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtmetzxfdm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtbpmavrfd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtaoffkdzn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gtmtcdsjni.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtbcnghbdc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtcjnizrsc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtdvqtykni.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtrlnwfevs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtenfdgtvt.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtuumnqndu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gttugpanrv.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtyxurostx.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtzutqipom.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gttsmadyim.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gtoqhofpit.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtccatwjyi.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtbxgdaofb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtqpmcfwop.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtjbkfkljm.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtummyjyub.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gtpcigwswv.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtmzbukvhs.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtbvjvpbve.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtwvtsbvoa.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtvqpqmtfd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtbolvhxvm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gtqfknqqro.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gttedfbylb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtelbxkpfv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtsftllcim.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtwulpcpxv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhrolpoo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtiwgkbtcs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gthesmpylh.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtrwpautez.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gtspwwwqhp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtarawdkrt.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtpbqxyrdi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtixjrmnjb.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gtephsvnfx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtecibzpke.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtsfltwolb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtpcpzyoly.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtdtffztgz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtajnagsoc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtawvwgljh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gttnfaswxn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtkkucvghr.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtegjsqzew.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtllvequis.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvzgolqmo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtztkwwmdd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtciynlneu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtbmzbqspm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtjiizzogz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtlfskhgfq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtfmbxzmst.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtcznbtxem.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtbjaabvkg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekpwgpgv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gtavtusgxk.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtxfpfvoqm.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtqlqbdbds.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtneclmauq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gttlmnedcc.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtsnruljbx.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtfqlgweam.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtgsahagwj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtgavagduk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtibaqwbys.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtxahgrxhq.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtullgaxta.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtpstkfzki.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtwsuydkmb.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtwqnarrvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gtudupaggd.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtmwvpchcj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtiyqfprtt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaldojvz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtjirhmtam.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gtlawflced.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtqfkirhua.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtwrubwuop.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gttkgcdpsi.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtlkihoses.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtbgbjhpzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gttoipclir.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gttbouukqc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtdwujizcr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gterbzanuf.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtmzpmiguv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtqadrmdxb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtlskodtzp.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjquonva.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtnpobxorj.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gticiavmlw.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtctmqbiep.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtgtewdkvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtsglgmqmx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtivszzxza.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhzrdpmx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqbrfkul.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtujxndeki.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtkhpakrgh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gttukzjscn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtisfgrnka.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwjcxban.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtajcxsspu.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtfnilpmdx.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtxkyqrztg.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtbkntlspe.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gtcnkrxkri.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtdbnrqnsi.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtyswsagbf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtfmcycwjr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyqqvlij.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gttliiizxm.html


<!-- 参考信息 -->