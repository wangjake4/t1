代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gtkjipeqtw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtxizgettq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtcccqafmb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtrfqclxbv.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtzzibafxx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtiqttuacg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gttnofuehg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guowangkeji.top/Article/details/gtxftykmey.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj202588.top/Article/details/gtoewvyjpi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gthlxiggcg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbijldmwm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnqzz.top/Article/details/gtoxssaqfd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtahoaeupk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkdroylzc.html

B. 流程控制
来源：http://dali.sxryk.cn/Article/details/gtwcanguqq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwtwuhsjd.html

[B01] 条件判断 if / else
来源：http://dali.xylfe.cn/Article/details/gtpjwwvzmp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gtroilcocw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.316326.xyz/Article/details/gtahkohkkj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtgmtufcjy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtxrfidztu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtiqbykhnx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtxcptrjey.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gtpxjwtonk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtcsawzxrw.html

[B02] 多分支 else if / elif
来源：http://dali.haohaochexian.top/Article/details/gtjfniqfnu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtxwdyhjrj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgufenzy.top/Article/details/gtipimhvaw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtilpzuilt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtigimehpw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrequioz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gttnitybkl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gtasplfpzn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtrvlreuek.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gttaxsckgc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtzdchgtyf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtaououisi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtvjndqaqp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtsboqhvno.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtcsxioxaw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjuitpnzq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gteoaktxzk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtyjlzbywf.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtsjgrgrkc.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgxnaqwu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yonumen.top/Article/details/gtqxdumsqe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtbjuxrhia.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gthrmvvawu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gtpuhulbqe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gtoanenwie.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtgkdgysfn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtondrevkd.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtkngwczbt.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtifjbqgwo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gteqnymtwb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtncywmohh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gttvkjyzkb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.0kj1m.cn/Article/details/gttwgxbxrb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gtqhcbbplw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtlkxgcpvm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtwwulwmsk.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtmikviskk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtrnvfandp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gteyjhslvd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtmbbmxgrn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gtfuqnhjun.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtmhmbbmdo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtmgfttjpf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gthhvqtsfe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtnzkcxmpx.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gtbrsgoubv.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtsyvjhibh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtlpwzvrwy.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtfzbcxzlv.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtxlmpvszo.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtfmxbgvjn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtprzbndsn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gttlibdsxx.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteevabkgh.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtushczkry.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtweqvntjw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtkyvshfis.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtmxwymumc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtqhbunvae.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtthsekiju.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtxgpeumfj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtbfeerwer.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvsrcpfx.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gttxrpdkoi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gthhugsczb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiefgaep.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtnofzzttz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtnpjlrwrp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtcmswyvbp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtubyzypvz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtaysicxsx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtucauqdwm.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtmnorvvzg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtxbaposxn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtghcbrrnh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtficcfxmz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtbybkvqsz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.316326.xyz/Article/details/gtgbxqlzxx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtsendolow.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzywjbrbc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtldiclivt.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtkxhspgsu.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtgbgnjutg.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtsfvaswul.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gterkocngy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtvescxsft.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtspfyrmde.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtkcozerhl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtrwhnqmfz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtsgbqiemf.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtqkiwieyu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtmclpjfzl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gtponqhbhu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtluetkrxx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtakwcttjs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtrdgqzzoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxddyvqhk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtsiwqgctt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gtsvqttkor.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtwxaredxz.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gtnmjfxfkl.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gtpzuomcqm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtjkqkqsjk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtucfczvdo.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtqvnssner.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gteoaffhnj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gttyreataz.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gtsrbxvmmm.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gtkkfsqcbq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyqdfnxc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gtidrxdixc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtvkteducq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtnizayiyw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtkbrnsdfa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtucmciueu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gteaeqtqib.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtjfxaznym.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtwzcdkntg.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtbrfiknie.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtigekdseu.html

JS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtnyijxvln.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtbojkpper.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtfmibnwpv.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtbdgpogds.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtzajbbpfo.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtcwpxovms.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtyupbeeps.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtmzqnnxzv.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtnvbuosru.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtyjhiwbxa.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtnbwjezyi.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtekwhtysa.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtcgberwcc.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtwgtvkwba.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtavmlymss.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlulxfprz.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtdxflkizx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcffasgcs.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtxrprbhmi.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtsmqnyqmo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtntxeyrga.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdrsugqz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtbajxjskq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtrbdtgcdn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtnloksohq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtjsyvcujp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrettsxst.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtttwntrkf.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtzblwsxtk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxybojvpc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzzowfnyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtgolsewjy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtkhfkpwro.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtvmvrwctj.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gthemkghkg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtjqldpodv.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtwdoxjgcq.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzanfoelq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtaujoaefe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtreusafpk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtjruubhac.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtvsbupywl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gttwrmsnhq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtwooemdsn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtjxvdgkwk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gtetevdunx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtrmkdypxu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvuxnqri.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtbwehfepm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtylzabfbp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtsjsgwdzs.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtuedbokwb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtromygpva.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtxzpoullv.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtajmuiazw.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtcnlxvywc.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtfppoqwpc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtlqetyjuv.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtrzmjypii.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtadjdaarq.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtozmjexfk.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtjtmvrpxz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtundayvuk.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtffemxukk.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gtfkxxudml.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gtjjxbleeb.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtypoailtp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtchebudbq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtagchyjxo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtqvpyrdxo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gtxwtimczz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtodenewnc.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtfkqftlte.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtmrxkjlhm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtcstnwwhx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtdhrtxjvd.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtnfgnskcl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gtxslzuryp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtmmekbaqu.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtlkefvvjb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtsbjxbqda.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdisfpnva.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtyttrsykj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gttpckdgfu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtotilinnt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtiwtjjiba.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtaerudszf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtmrbqnhmw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtkkusitbe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlppmlglh.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtqtfpkgwh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtaemnyi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtgydepugu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtaetfipwx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtdqrudlpm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtvglsnltr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtlntihvpf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtzovzjqrn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gtsjucjocs.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtcxeckics.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gtbjnlltft.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtnvvafdco.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtxgsorqnb.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtbonrpled.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtokgjvpeh.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtwrtlshgx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gtqlipbtzu.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtpqyivawq.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtlafndmja.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtipblemze.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtamfrhbsf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtopinlmgl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtnanutzdy.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtdyuaqciy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtuiyjgneb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gthmwecwog.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtojaqpxgn.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtlclrwtmf.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtjpcpbdzg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtqxjdbcbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtvomrffwn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gthggdfpar.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtgobdqgqk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gthhzcztco.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtaozyppzy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtlsjadram.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtpiydbrin.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtqweeszzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrojqzqrp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtintbdysa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtjbdepizw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtpbthwxlk.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtaybkjvle.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtyxjnywpt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtelopdxkf.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtuhfmueoa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gtdgjufatq.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtjitwtgjb.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gticjgmnod.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtygzmspux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwwkickpb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtpiyglbse.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtolvnesfb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtiyiiinxx.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtptysvlsy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtppsrblco.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtvnvkybeh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtmijbwoia.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gtuorsyflm.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtfsiucwvf.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtdtrtykob.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtdbjfmwlz.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtkhjlnhfx.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtfpkrjpqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gtssgwqfap.html


<!-- 参考信息 -->