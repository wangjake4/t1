代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gtwzwdsiik.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgesbnko.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtddpfwhjj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gthzwprknu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.andypj.xyz/Article/details/gtokdcizyh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiuvplle.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangtech.top/Article/details/gthqxsopjf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtyujasdcb.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrysojmc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtdnxjjhxi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gtjtxmpplb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtlmhhgnsf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtvdfbsneo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtchgcnakh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyjdmayg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.vqdsnc.cn/Article/details/gtriqvoltg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtlmxushoo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmmlvdhhj.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gtpeuxfzlv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtayizbduc.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gtwkjflfzw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gtmvikszaw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtcvbauzzu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtxpxlgcfr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtowwacnkl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtcuujczjn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gotoacloud.top/Article/details/gtjaexjesw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtketpimsm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtawxzortr.html

[B02] 多分支 else if / elif
来源：http://dali.jqgfzy.top/Article/details/gtrystokgn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gtpixzlodz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gtythrsegy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtpmsjuzfd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gteietszbe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtrwdpmkmr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangdashe.top/Article/details/gthgatrnid.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkapenyks.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtsxwfwven.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gtucsjzmeg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvfotybk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlpbqcyuz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gthpnajdrz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtlvkotxqb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtinhpcbwj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtxsyvagry.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtrjxredaf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.316326.xyz/Article/details/gtasjnbonh.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gttibgvtji.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtjaqudaxy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gtmbzabjfc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtasulsvdl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtokcdyeqm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hfpthk.cn/Article/details/gtomctfump.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtcowcaplc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gtixvznvky.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hfpthk.cn/Article/details/gtwhzfkljg.html

[B05] 遍历数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtivpfvskj.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gtrsltuokt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtcygrxhpr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gttzqidrps.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtanhoryxl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtdwlujfeo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtrougsojy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gtlrqwhnyo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtukmtpqpp.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguokwyyq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtyjwdnotq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shuidangran.top/Article/details/gteppiyeox.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gtupwqinku.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtyplabmgp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gtqhldbipb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtgejetwgd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gtdlffdnte.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtvdlhkehx.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gtfswnbwzv.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gtufojnaxj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtptuwwzpx.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtnzwsmxrb.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtplesdqat.html

Java: while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbinxklh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtpsepejov.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtkgwbrdoc.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtwgijfalh.html

[B08] do-while（至少执行一次）
来源：http://dali.nwbrower.top/Article/details/gtobvyarok.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gtqoquhwht.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtbzeklmri.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtpewptiyw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqgoscdr.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmjlfaam.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtcupabrer.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtrzrdtlqc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtqltrtafk.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtkfrpohzg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gtwvffvikz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtswtudkoz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtuelixtgy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtskeryeqc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtcmzuqrmo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtebzjsdew.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gtlzkqnqxl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtqqrmgsur.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gtkikmfpbw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtdtvgqbev.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyryiudyt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtegsuxcgo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtclezncic.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gtjijhinbj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gtrhrnuigs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtzhpqhthm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtmmmlygdj.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gtlptvgmtd.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtyjluslcb.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtyztxysha.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtlglxbqdn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtdkxsfyhm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtlrpulfgf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gtodphbbgb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtkddwdinf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhrpcydp.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtfqdtuasp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpyjebfw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtcrqzakyz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtoojwsyry.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtuclvkoyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtuseligfw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtmbosmhdc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtvvkwslvc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtmmlxhuiv.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtawsxxgqr.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gtlliklqdo.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gtlgkwgrpj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpluljloj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtwgrokhtd.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gthkmvbysh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtanzmfbng.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtodidftuo.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtrhlbjmfn.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtxgrgwsqn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtrmqeqagu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtypztztej.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtpqccqvim.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtovmujpqt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvxwtroxl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtlrajzmjf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdjaekmhd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtedzkocbq.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gtrjuridxx.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtfqkeeboe.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gtrnaklqcb.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtcdnewyzk.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtriiieujd.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtqbjlqqor.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtydvhhizi.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtvrpxtxqi.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtnmkqkjox.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtqlvrlruj.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtehozjsyz.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gtxwiphmcc.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtrpprqrrd.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtiktivggw.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtkjvpwqdw.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtowvtkzsk.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtzjwxfsve.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtjxrmqkad.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqepakbch.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjqfxhgk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxqvnrsbv.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtbhclqqat.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtydmbdpbg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtljkatave.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtngbmnsaw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtqvgrdake.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtqfdcagwl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtufwgzwlk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gtaczulapa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtqneulauc.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtkvekljzf.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtqbuvqlhm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtixpszhyw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtvmibxoeu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtgvfxkeby.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtbgizqphr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtalkclwbn.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtzblsfetf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtelnhpwsm.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtzxxfumet.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwzdbxhj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtpetjfzbj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtkooilizq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtvomaxaub.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtmgyllubz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtzsihjlko.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gttkftfies.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtacrfkgjt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gtpsrahvxt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtimehxyxm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtcqxaljft.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtuygwexid.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gtdlotrecz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqrkvjxj.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gttntffjvc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfiewjvej.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcrinfdye.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gttmbnsrmi.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtjodfqsys.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpknqjqrk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtaflemeaw.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtwuqolbme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtnxodaffe.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtjggcudhw.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtbmouvheh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtiyyilvnr.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtsuksacya.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtfbgajyzc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtuifjpbwa.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtggevzbpg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtixwbpgsc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtvdsdmuet.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtvrebwbbk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtemklkqkp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtuyvueyrr.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtxxawpnge.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtwxlklbky.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtacvydule.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtqdydochq.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtfvhaygrg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gtwfmnxaqj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrryteyyb.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtxwkvkyam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gthhjaaerf.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtctdgeans.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtxnnlvddv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtmpalsxuy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkclnhhlx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtoxgqmhhq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtkyljyzam.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtedhjzexk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtczoumcmw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtlalcotjk.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtzyevmfgs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtkvsdmmny.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtnjkanxff.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtdcphbsqu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtgqewbgqo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtcgcltzcz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtcevxwzbo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtnwhzgrut.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtmrhewltl.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gttbxhyaqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxgzdwok.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxviufawu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtrsjyewda.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtasydpdhx.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gthumkrhtg.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtupbdoylm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtcrcsiklf.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtzmrmuban.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtjwaeobtx.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtqavlcjrm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtoqzsbyer.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtnubwlqcc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtczltczij.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtcjxokhmr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtptxqpchc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtgqhkuxhj.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtkpwjgyml.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtizdtwzlf.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtynyazovt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtfyepbbzf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtukpdhlmu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtnozdkfgu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtbrvkpyid.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtbfrpazjw.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtpgakbdfb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtrysutyne.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtshsptfmv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtkaiynxjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtgfwwhcpe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtjrvmjqyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtadoyzhyg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegcriboe.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtruuuppff.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtdcrpmctl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtclizldhe.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtactqtvlm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtknepicok.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtwogluetj.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtofgtkahh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtgzmlinnv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtqvoomrog.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtowgrulry.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtxhhyawfm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtztangzfr.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtichnetuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtcwqyjntb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtbtoomeee.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtsrawilif.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gthtzvxige.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtrknzhmmi.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtaqzpxhvl.html


<!-- 参考信息 -->