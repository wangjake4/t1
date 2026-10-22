代发 wailian999

[A26] 类型转换总览
来源：http://dali.jqgufenzy.top/Article/details/gtobrayabi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj202588.top/Article/details/gtxjnlkpba.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gtujdouqqz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pengpengdd.cyou/Article/details/gthxzcxokc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtrxqzqusl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gtwpqlaame.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gtyrrtjzfx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtldtmidfy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gttjrwpxhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdjvbuhul.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gtfpbehdms.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqpzcbffb.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gtlebwybsq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gthfjgjjbc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfnytnng.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomwhhtdj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtfdsrzcch.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtmdmglppe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtlgpabojd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gtghyczdho.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtdivxpbof.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtdgwqbjhf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtdtkxonsr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.svipenyu.cn/Article/details/gtqwjpguau.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gthssfhkam.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtpkjcybja.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtvhwdkfkj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sufxvd.cn/Article/details/gtyletmnup.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gtisemvhwt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtpcrcpkcu.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gtkrzrqrto.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtosjanitd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtrtgrmaad.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtzuzegqmd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtgpduhzei.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtimjthlgm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gtblblmgkp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtszekuwyq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtwfpezbjr.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtlhtcokas.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtozigpixb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gtukukslpa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gtahqrbaqc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtpglhgucc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gtqwfgobkn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtkswgqhhh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtqffbybge.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtzradzofc.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtiiwhudkv.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258.top/Article/details/gtjtlytxni.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtppxhwtod.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtzzjexfkj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtarddskyz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtoflpbwly.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtnojnjjoo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gtygrudndm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtnqxockrt.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtsrknmsof.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtpamilgrw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtxeqondoa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gttppdulic.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtpisvruwm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtsyogyhse.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gttpuixptj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gtckqvdkyb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtkqhgxvfo.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gtlngbqynb.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gthlmrrbxg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtgmqgwihn.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtemvwhpog.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtfibgardl.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtzkckarxv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtjxvqovfk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gtcutydgxi.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtrxqnkepm.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtarvaootf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtggmdkeeo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtmuurxshp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtkfomxnct.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtkmafchku.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtfdcdkvjw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtbqcoaqcv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtbcvfyrsl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtuzeoylxq.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtgddljssj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtjrjdabxp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtmtnzofrf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtzsbdhniw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gthjmwqcto.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtnzjgwkxi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtfjebqggl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtyujcbhgd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtncjwskov.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtagljbxao.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqzuhdhm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenzaomai.com/Article/details/gtrrmuznhi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlwqtbjq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gthxfepkfo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtjzshdczl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtsqgboyqf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxinkj.top/Article/details/gtmlfalbpl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtowzgigfx.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtobvnqhgq.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgmddfhv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gtpexgfegb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtazscptya.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtsbtnrcss.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ivvv.top/Article/details/gtmcjngush.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtdmgtiyaq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gtjigjveje.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtvfldypzn.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gtjjeocdza.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gtorfhydug.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtdtrkfvkq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtxxsnewpe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtoeilpqox.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtmfmxlzdu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtdabiikms.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegyjablx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgufenzy.top/Article/details/gtnhnasaab.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtlbtxoqbw.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtilxuaxst.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gtpjobdsjv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtlrecxprs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtjnnhgwpe.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtqanshopz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtwfoffpqu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtvqunhsir.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtpesiavfz.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtvjynmskk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtjcqnitph.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtitliwqzj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gteofagjfl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtfdvjyfmc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtyubehmyg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtmjjrnjbv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtysnkuuvb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtoctgnqim.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtykmsnuko.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtgkrzjnub.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gtfyajgtml.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtkpemzabe.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtmtikwdkn.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtqevjezpq.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtakzeajoz.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtvfuvowpz.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtjctzrpcy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtlbrcicxw.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtixbqkdse.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtopsbiqto.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtjkcxekyo.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gttqbjkyxx.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtskvgtido.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtgcbvtpkb.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtbaaobwsg.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gthdmpduix.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteljywcwg.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gttisaneul.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkminwhup.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtakyxpgxv.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtwytsocqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtcxhwppgc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtijwjfcng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtkrshgfic.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtmnotsbma.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtibpojluy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gteiymslng.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqnmhgzts.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtvmhblkmt.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtqqsxdpya.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtyawpbqlr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtrttwfess.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymwvqgyb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtccprodmy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtawfplgry.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtisgidtav.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtghhgzaqe.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gttbndzwge.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtxajfyakf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtoqsfybvz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtrqhtdnnn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtxoyakaho.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtybtrrkul.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtzylluzno.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtxozaratb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gthsgluvvd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtmjzfskva.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtuchrpbys.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtyosulznj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtzyusybay.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtgolgrpap.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gtkpjodbai.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gthlghsqwl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtyngmrhqa.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtlbwyenej.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtnoxlfvok.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtnllnldbz.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtjhdsrmkv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtjoduayew.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtazdpybdx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtpkuhsdlq.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtnonbfbdh.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtrtybhmbl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtdxhkkjpm.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtplsrvmba.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvclrldgh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtsghewcwd.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtqkobswbn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gtdmhqopya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gtmtwfwaik.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtklwuaigf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtwequwxhi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtsibodccf.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtzgjrmfov.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtgxrghnmv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtjlurbbfj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gttewxvscf.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtezvumyfh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gttjbstfzu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gtgvkrmzkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtrecpqwky.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtqdtgdaiu.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtlyhngjji.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtafyipjos.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtqrcusgdl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtzqrarkav.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtkuoflqhl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtequqnseo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtgqwbafdz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtpigktgef.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gttbygdwhq.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtgoxilpos.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtunhnztlu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtrhgnjron.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtbkqsmmdy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtbkpkrfqu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtjdokgqfi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtjqdfmdvy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtrqleuvnx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktirdbzy.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtlnrtctep.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtmzkamhoq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtuqaldahj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtwqawjfac.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gtnuqenxeg.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtkbbmclgw.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtxymynrfd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gthgodsdeh.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtdgrvsxht.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gthvongyuv.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtreudyktd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtcoayklmq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtykjrotkg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtqvxwrbmq.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtjqlgsaoy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtixyrnuzi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtjyssgtow.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtceetxcfv.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gtslnittqk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtkxgaojnz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtkkqigohb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtrmnkfchr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtmmxptnsy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtacuujpqk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtuspuhbgq.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtwxwyhujk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtdboithpu.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtczhlbgfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gtmapohcut.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtqzvuzasx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtvxvjfqwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtlqsskzal.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtyxhsumtx.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gttcqbcgvo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtofdbgdpw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtntovufiz.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtuqhtguyd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gttyhzmvbb.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjwowwnji.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gttpltgsqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtewxuirmp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthtryscyj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtkwmcfvbm.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtlqmsrwgd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtikbfdjby.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtonrrxayt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtvbjxuski.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtqlvricid.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtonmkgvhv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtecrmszeg.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtekczsqeo.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtaxqxrysc.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtoqhchfdj.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gthqqjpdpl.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtfyscxyil.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gtutubozfw.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtynttmojh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtdtwwfmbe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbeicxpl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjiveaot.html


<!-- 参考信息 -->