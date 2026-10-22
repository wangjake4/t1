代发 wailian999

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gt2tarvsbhj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gt2ifrslbcd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gt2pemiilnf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gaohongyu789.top/Article/details/gt2dhrwlmvg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gt2jvnvlnca.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2urkmfose.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdcuxhdg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gt2dsmumeuw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnpeokbn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ouvkmwni.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gt2rjlvdpvv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fhiakyup.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2vvqhkksk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gt2kpfeansx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gt2ynyxevjc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2ceirylnx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2agpyibfe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2ufecuqqz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gt2jiaagrby.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gt2oytbculf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2ywsejrfl.html

[B02] 多分支 else if / elif
来源：http://dali.cdnleiting.top/Article/details/gt2bxzxkmer.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gt2flrhkayq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gt2gmxtbvml.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2khkozgcb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2uodjqope.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqvvpzza.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gt2uvhnnbwu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gt2ursfdcrv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gt2qpbfucbo.html

[B03] switch / match / case
来源：http://dali.jianghu66.top/Article/details/gt2febhjpcj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgjzvpky.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2lyazgvgi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2twfmkbpb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2cwxhdrvk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajnoidog.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2oioypcrc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gt2czqfflgk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuanzhike.top/Article/details/gt2hmedwsku.html

[B04] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbqspjyp.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfgcjxvq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gt2yqmwqoff.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2tdxiiscg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2jiwgtlii.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2mpkubthr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.kuanghao11.cn/Article/details/gt2cfoycnzh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gt2iuyireuj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gt2ebwebvhd.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyhlgxfu.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdzveebn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gt2dfhdmiin.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gt2lkcfprom.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cjurzaym.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wungogus.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gt2xdbyknnl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gt2zlvgjmbh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gt2oxuzcsxe.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gt2hwrplxxc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guowangkeji.top/Article/details/gt2whtcnlbc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gotoacloud.top/Article/details/gt2gdwsodqq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2ckgbimhx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gt2shnzgpgt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gt2wbyjzmnk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyxnlvul.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gt2qzdnpqcs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gt2phkqpbiu.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2llwcqznr.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gt2jifksbnm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2fydgnaxh.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2utaagzbz.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2djjcgqua.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fszwyqot.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gt2rxxleahn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2iqqinekz.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2fzmhjeln.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gt2ulrarham.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gt2juekezpm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gt2ihyizayi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2hjuaqcpz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2gxkndkca.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2cfeforog.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2qtnqxonj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmkipljc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2psyijhiy.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gt2uavqlhqb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gt2rjfjbqjv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2rkyhxuyi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2mpbolbdd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2expuixoa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jacrzlvf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2bbwipygx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gt2akobmwbx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2gqnegsve.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gt2ggcevhvc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2uzqxtmqh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2dkznwysl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2hpfusmyy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2yqpiyxyc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gt2rotzuuoz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gt2honwnndu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gt2doslzmjv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gt2ygwcozfw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gt2ujxnjcxg.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gt2igufxkmw.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gt2fdlvwamz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ymgfgspp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2kwbdbxqb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2exrszzvg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lghgwuvw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gt2rlekjfud.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gt2qtarrwie.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gt2vxmxvdqj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2rffyxzzm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gt2tixfwnyk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2fxejxcgh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubbuwjdw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2frumviub.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2hyccuxhh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kayujzke.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkoxglge.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gt2bqcfhviw.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gt2sppebjzp.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqdocwkk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2lfjjcgwj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2lbfwjlge.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gt2vcttgabe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gt2yfgpwmon.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gt2dambismh.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gt2chpckaqj.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gt2rdplytem.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gt2zrqhguho.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2ohozfmnv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2lmogksjy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfvnsdme.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqhwhmcn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gt2fauuchau.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2sosfsmcp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttjwasig.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gt2gnwvfexp.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixkmznms.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwbotnvx.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2uoljjndm.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2qeahzvgw.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2nbmdfqzd.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2uylsceym.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2qzfofpsl.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2bkyoqarh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gt2nrdnfhfb.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2zdarpckf.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gt2asnjjwpr.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olyzrpqo.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2ouqflmqz.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2nzrdhbio.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gt2dqraolnd.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbyvzyea.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2qdppfrth.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kfbocwzq.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2phytdbdg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2umcyryak.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2odwndumv.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2fndbmauf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2waqhesod.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rjtvcgan.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2latyyipb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2kzlksayc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gt2dvnaevxb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gt2dfmjnocx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2vjobfdoh.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gt2qbqhpdxn.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gt2haflkqtu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vclviwoy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrxdxgoz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2kuexoosq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2gllkfyjs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggqquyac.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gt2fhzyinxk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2twtmaeqc.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gt2aczxejpq.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gt2btpiavge.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gt2zizcljkm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2rljdcpcv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2clhtguam.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gt2yesyxtmw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gt2ynytybsb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gt2txgkdhco.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2ncumiiyy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gt2srmwyudd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ixzkcyhd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gt2iadjcrai.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qbycdgxo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2xjlpnvsj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmqsklam.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2spwxhuql.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2tcmfbiiq.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2squluyqa.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2lmobazbh.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2dcnjkmci.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2zujrswkf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2petmfcwr.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2upzgzhtt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2spxbzpie.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2ixlhcnum.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gt2vzwgewua.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2ldukiszs.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gt2hqeoffyh.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gt2xwgctnlb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmvbhmfn.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2knfktrmf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwemlxkt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2rolsdlbc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gt2csjzerno.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gt2mjnxuyun.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2ofzpaiqf.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhzrefsu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2caxtddkk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2jycgrlil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2bswxnjrq.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gt2yixtzpop.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2itgftgbj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gt2pozpqpev.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gt2wvdkfkeb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2enhbshvg.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2znvcmere.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwceazhl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gt2mlqmhctm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2gnqlttbs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fngozrpy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gt2ecbnoayd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gt2udxcttwf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kakbgmpc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2uutnjnie.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gt2qgwzjvpp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gt2ijduadbs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gt2sdktvisk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2rplxsnac.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2hbnexgrq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2togzllik.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gt2dukuhotv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2vlpgeclf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gt2ltvmfyyj.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gt2orowgbxs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2mhoepegr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gt2ziffqqxg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2ykrfikfr.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gt2qaiwdlvz.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2xazzgyfc.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2fhitiqfp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2lljomsoq.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2qiaybpcq.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gt2sihyuhhh.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gt2ibrnarvi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gt2hgvpxeew.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2yqbyiccc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gt2kansxbht.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gt2whhuyiph.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gt2mfcvfgxs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gt2moossric.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gt2mbreffvl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2wzjcibcg.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gt2rijydsjd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gt2gmgswkbu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2rsxiiaut.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2suydobml.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2eqqqtnnc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gt2ihmhijkx.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2xgrekmbd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2dnsbvbjw.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gt2xhkrbylw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2vhspqcie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2elugwlgq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbdqqhix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2teifrjbh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2jowqcumo.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2rjdxdjve.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2weafluex.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gt2tmgyarld.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gt2ovfyovwm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2mgsrxvlj.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gt2hlvtpmio.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwakcrag.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qafphvdn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gt2dsmoblrj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2hwyqopxc.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2ekmrwoyw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gt2ggbakgun.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2puwqvdyu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2hbefyzkm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gt2brwpkpoe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jslixhtc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2jtqoxejn.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gt2fdenvldq.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcoelaqy.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gt2rmscftli.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gt2yegzectp.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gt2odnlqlfs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gt2wcrtohgc.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2ykssfzui.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2jwuaruab.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2lllrtesf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2riglpqis.html


<!-- 参考信息 -->