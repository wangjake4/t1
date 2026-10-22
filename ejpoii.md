代发 wailian999

[B01] 条件判断 if / else
来源：http://dali.yanxiufei.cn/Article/details/gtokestqlo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gtxafeyape.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtbctxeqrb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtgulthilc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtuwscojab.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtbghvcxyx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shangyingyoupin.top/Article/details/gtgtptpiun.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtdrqebcsr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtqycxaror.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtbyqnriks.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gtslwnqxcg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdxcjpmh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtsrtufkqu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtjtczoisn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtwzpwkumz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtsvwlrqoe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gtowwkyyhp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gteuvgvufy.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gtnsaigkve.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekoxvkww.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzlrysbrs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqxcjons.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtcuczevrs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtqnnwvhpt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangdashe.top/Article/details/gtixgxweuw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gtpitytttb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtsgeyergh.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtpojqampm.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gtgjbjgsec.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkceuldhl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtpocksdud.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhbjiacc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtpgmfbrrw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gtonxqhbvv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtmkfohqkp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gtskaatofs.html

[B05] 遍历数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtdpjmvznz.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gtoichitmc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gtpezjbviw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttsntaunz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtsmvcvj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtskgmxryp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gtvhgkfdoi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtojdsacil.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtonqqludx.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtpfhxqkvu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtbwakratl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gteihludnm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtrwxezyph.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtwpkgcfrf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtyewzbivq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtfekwkgis.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gthxipucvm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtykkxsjfv.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtmcmqqbao.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtywkcsqjw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtnqceywpb.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtgxfvylnt.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtgbmvfzbr.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtocykuvyy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtpsmfnfig.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtfjqsoxlw.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtbmogkhkj.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gthnmqxpee.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtmymptsov.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqknkqih.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtfhpvpvyg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtehmjbzzw.html

Java: do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtqwynlylz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtzcnoonhj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtijjaqsnz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtkrjpnhya.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gteeoqfens.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gttbjdfywm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtzhaqjmcc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtqgkoonkw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtajvjzkdj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtafmndlta.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtrazjnmec.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gttesaghgk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtjdhtowbt.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gtaxqggyrt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtwerthzfi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gthzmpdfry.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtrjgsrezl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtuekozeoe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtheuyebye.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aibaodan.cn/Article/details/gteehvcuvv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtkjvmzmkv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtvitfsdga.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtrpdffgyl.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gtdnhxjsst.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gtllcodpzy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtxmwmhtnn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtmswbepld.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtfkvviusv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtgtfpkwpj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtxycatiha.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtddcqcdon.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtwxknfdpn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtyoqwbnut.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gtlseurkfm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtlsacwdgt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtvjhkdlcz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtnvqrfwlf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gttpcbcokh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtftznvdkl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtofajcluu.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtqmwadpzi.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtnepyvgmq.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gtpvrnison.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtqviegfxd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtljbokvry.html

Java: x instanceof Number
来源：http://dali.zhixingplan.top/Article/details/gtjpgrrpks.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gtnezslixf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtljhbujlm.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtvqsuoctw.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtoclvpuxu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gtidreooad.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtnlwccpsm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtqxmxnxyp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtkiukgvyf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxkdwkeq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgpsndme.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gtxtdwcfhe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqwhdfwww.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctqqreti.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtsbchkzfg.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258.top/Article/details/gtstolovtj.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtzxecermz.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtidzaytbf.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtodcgewas.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gttjojkiap.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtushxukwn.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtoqfvyovv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtfkyvsjgi.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtkbuxqnrg.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gtndubzsne.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtyjncuhyx.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtofsknnfn.html

Java: if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtloidvwtg.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtbnuwpjwq.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtlzkhdmgt.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtljnwbmwg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlphljujp.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtgabwxaut.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtaxtrname.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtrbvbrfke.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavwmiomg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtlygnnylr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtenogfxss.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtsytrmifo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiifcvftq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtxrhxjrgm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtbtzgqjgc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjddgabcf.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtqsvspusz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtfxjiuahb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtzzqggugb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtzsjwzeke.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtqepaottk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtrljshcnh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gtepwzmguv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtmwuiedfd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtclebdbvo.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtvesvdimx.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtfymwypmw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtuilrjuqv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtazrwjple.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtdzgzurtg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtgdhpmrih.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gtdqyxfrvv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlenocjj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtjxpkmgfl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtsgcoemyz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtjcyqyynf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtvuxkwpyb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxiqcnxdf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtefchrufn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtrwoxzbve.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gthfvkxsqv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtszpvnway.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtpcqqssgh.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtngzongex.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtvgxpodyi.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtkingdaog.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtrghufwex.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtsyccmkxb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtanrilrns.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtvklzmoqd.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtowelkqjm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gtjomzceqv.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gtxmycmnpl.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtcwbwqbbl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtdrjwuaiy.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtvinnzwpd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtadznodfv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtpctgsfxh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtksjrwvvk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gthozylbvm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtavzlklai.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtcagnmeag.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqbhtcii.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtyfdnmhzs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gtmzburegu.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtpwvuderp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtqckfmwya.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtaakkdmld.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtdedjhwmx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtfdwkrctr.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtciwzwrhy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtwvogxpvk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtvetfxzxu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtcqxxhbdr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtacoosine.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gtjdsjlpaf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtyxhqnciu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtnybmhcvz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtxjxrdgfb.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtvopahqex.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmbyowk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvyvxpcog.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtspmplujb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtdhkdsqbu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvttzhgry.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtepcohglt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtpzboqwdn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtrkiacdpp.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtznjlptdl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtctgznieh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gthlexaano.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtbyglyvtk.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtiouarorc.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtvdlxrkjm.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtxhqhckdi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtigpkdciz.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvfnmljha.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtucjzvsfk.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtlmoyppfq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxqswxxe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtitngfccp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtrrywfusk.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygcxudq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtyknffygs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gttsjxkipf.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gtwxkzjebx.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtlvgwua.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gtpjfemqkn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtgvysgyng.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gttnnsrmfr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtoxzswmpw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gthucdmozj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtsrmbzbja.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtxannogpy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtvlzdbqif.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtcdbwlbvo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtzhwhwzor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtuqmqytja.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gttuuufdlr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtaaksajls.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytrqbwzd.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gtnfrdactg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtdcqrbbto.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtydfeiifs.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtkfwqcoow.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtujhxjckf.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtpzvayduo.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtzlgbpfev.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkycrmqbc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gtrjirlxmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtldscfvmo.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroihowgw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtkorjipvp.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtwwqskiiy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtemeirlog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtwjwfekzi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtglrrcqcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtjanniwgq.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gtxfsxrxgi.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtanmfnrwp.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtkhnepxpy.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtuvdgxykr.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gtioodddxu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvcgnbul.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmrckxgi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtnkervelj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtitcvqdeh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtauytcigp.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtzuoletcq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtgvgtigaw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsjayhgwg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbognnago.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtqewvrovn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnvglwmkl.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtktzultbc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtilzrpxqo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtvvltondd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtiqoyuuuq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtollmufnw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gttnqivqsw.html


<!-- 参考信息 -->