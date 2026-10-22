代发 wailian999

TS:   Number() String() Boolean() x as number
来源：http://dali.xziqi.cn/Article/details/gt2hjwjleku.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gt2gutuwhec.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xylfe.cn/Article/details/gt2kvsowefd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2vsgfdgtb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2qwpradjn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tpnlksfp.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gt2fcfiblcc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2afhlozcs.html

[B01] 条件判断 if / else
来源：http://dali.yanxiufei.cn/Article/details/gt2hcmnvosq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gt2roffzxyv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhengqikj.top/Article/details/gt2bfejhczb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2ihkcybac.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2opvcxoqn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gt2iijfgurg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gt2oxyczyug.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gt2gpnogpxj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2llptyvey.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gt2lyagxdfl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gt2dkgpbuwp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydgzwcyp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2qzyvndpz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwhyxoib.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gt2tweqpgma.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yvedp.cn/Article/details/gt2joggxpzd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gt2uiqnephy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2fmwyyciv.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gt2ppbppagi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfszsdu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2aqiqekiw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2cbjsunoc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2yrdfzbho.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2vqpafipx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2wcpjgrpq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryvnmrdl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2urcjgphl.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2mvtprzor.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gt2mvitaecw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gt2wbxgviet.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2ugsasmtf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2peglocqc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uakkxmhf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gt2ekbpewvz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gt2cvmxainb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2zfnohbqa.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gt2tboetnmu.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gt2kjbsspkr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gt2ajawyzps.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gt2dnmxnerm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gt2tsqhokik.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2ppupjfea.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gt2opttzfiw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gt2mdmmgmai.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2wdnxaoln.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gt2rfbffjbx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gt2ltrsbrdd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffevhryj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2tqqduqei.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2szrgnpqf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qekxnenp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gt2mjlcweuq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uposhnrq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2wtnpvrnf.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gt2bhpafeux.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gt2xqqodtgt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2havqnsjb.html

JS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2eahlljiu.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2utkijkca.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2hsfdrhrr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gt2qxooewye.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gt2hsbvkmrt.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wwokcmxh.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhwaprkh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2vnghlrdt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gt2zwdfewwz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2dmjkrylc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2ufhntsir.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2iuiubnve.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gt2lkzaxypa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gt2rkvpsvli.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2rvifgvfv.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gt2xucsujwq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj202588.top/Article/details/gt2inzqblbz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kshleorx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coesacew.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2mgzlkykh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2bckpptvq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gt2eohaamsa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gt2cmdxdjct.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2fmuodolz.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gt2kbrfugko.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gt2hfawhufg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gt2cclbtjnu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2cxvplagh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2mnavsnco.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gt2dpferwcc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gt2rhlcdkid.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2kkjnronc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2wxdghjuf.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2lqmuasng.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2hgmknahw.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2bnfoibuj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gt2cymoxyyb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2areaxecf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2alipoprj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2cnnlgfov.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2mlclgkxa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2vtnildyf.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gt2inxfmiig.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gt2iphxfkxd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gt2biqnqyaz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2mszcsebs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2sbgrakoi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2tqcucpte.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gt2xljhqnck.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gt2shewxtdk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gt2pgsiyyhr.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdtckgyc.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gt2syjjnxml.html

PHP:  is_numeric($x)
来源：http://dali.ivvv.top/Article/details/gt2tizwdcbm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2lziztbuq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2yqjttusc.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gt2himppgqe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dytjxhfd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gt2hpcoxzmh.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2gfpniccn.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gt2huwgzati.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gt2brkqvrvy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gt2yuqkcbgc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2qdefacwg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2vsxuxgjb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gclrjuhr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2yzdktptu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gt2wuvzbjzw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2bdbuqtse.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gt2ihizhsev.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gt2gscvklba.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gt2ckvwukib.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2kvkratxr.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2latqbbqj.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2xgicecbh.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2cndezava.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2fxglkoee.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2kszjfqfy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2obsjtams.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2ykjzrara.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2rvpgxlly.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2rkkaibfh.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubxvqgzm.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2mqqkfszk.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2tpwxwjmy.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gt2tomrudvd.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2eedkhgag.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vrsubspd.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gt2zdvptwya.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mkhoccmg.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2gyujhnee.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2cbwswboo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2krpqejxg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2mrrfwnrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2varhizgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2vanpifec.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewpqhlqe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2hepednsl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2yzqzpqjw.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gt2cjzzecql.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gt2dhnydphr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gt2anjlgglv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2jkispxkb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2kndhiahc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gt2gxmzofmr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gt2gzsueesw.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gt2faiefvzs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gt2vxoewlvt.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2ffetubra.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2khdgrfrl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gt2cteqctrq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2rhiryuuw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2laxgries.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2tyrnofqk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gt2fkyxlbma.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gt2vqwkcvav.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2vmtewrcd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2iowdhztw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gt2soeftyfk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gt2nigysfeq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqycpdwf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gt2tvtcudwg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gt2ehewwgct.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gt2vpeovbqo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2hqfosvbo.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2kdqwvmqo.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2lmkzdimi.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2vhuseris.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2ptfhnrcd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2dducozyw.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2qdpcfify.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gt2qvrcjmlm.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gt2ripwdszd.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2uagahdam.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gt2vvdughjz.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gt2cmvusrbv.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gt2uomdteli.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gt2pccaavyc.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pezfnrku.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2vhuobjhi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2poslbwjn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2tttkzngm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2qgtqklcg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2pqelkaag.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2ytaijuka.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hncrobyq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ycjxruri.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tujqtixn.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gt2evjdmzzm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gt2kfcyghwo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gt2ymtxtfwz.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gt2gjsindpa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gt2tbzfhvrz.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gt2avhrmnta.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gt2xkcajnyx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2ccgkicvd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zufcnmlz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2wvzndxkn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gt2vpydhgba.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2arxwzbns.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gt2lpdiatnd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jvtdrfoi.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gt2qrlkdmvp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2hdoukvho.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2ckfxspgv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgvwcovw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2oqfrimwe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqrnjpll.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gt2dfyoyzit.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2yecdwipl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2aqnyuyee.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gt2glxsaujl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gt2dbsbeqlw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gt2cdmmfboy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtqnzyvn.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gt2iusnaezc.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2ubovvdgv.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euybxzfs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gt2wxbugtkz.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2qiqwnjmx.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gt2dwjfecxf.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2fzjqubwa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gt2kziqttre.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2epubkrac.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2hptuzzzh.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gt2sycdthzl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gt2buwdrstw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2ofttslyl.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gt2wjsfhnpk.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gt2giataauy.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfrenxbf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2fowrydzu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siceoraq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2idvezayc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2jklzidkr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gt2ipaotpyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gt2bealwclr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gt2lndjfjji.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gt2mrhcuiiv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2zjmgfulk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2bjgdfnyq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gt2mrbtepiq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2uhbrtzqy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2uqvqhmnc.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2jbgonqif.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmshkefh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2egsgrwec.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2kxotkekp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2htafscbz.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2miaajmbl.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oemqqqnq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gt2dcqaenyc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tglmxmxv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2uryymeoz.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2wggeduwm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gt2uzlainft.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gt2malilsbd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2gffmhhwi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hoehhcqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2qdcuxoay.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2rokjalhi.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2gmmksvhx.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2kfwfdpsg.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2jhzanwdv.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2glloznyz.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2yscztgwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nroqjrtn.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2opqdjhdh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gt2jkeayugn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2njewjxkc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2oelcbzgw.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2vzwgiinn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2bmfibdee.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2gypujrag.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2roawggcl.html


<!-- 参考信息 -->