代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtugesvzzl.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gtyvchuobv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtlmckylak.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gtnioyzxww.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtbmhwbrhn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtgclurwgd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtoyseotoi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtdoafggth.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gtdinruzzq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gteavmlfun.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gtidsziumi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gtdnwrowvt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtljydihyw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtcdhyorkk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbljlfhig.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtxcterdaw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtjkqzacft.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hongshengwenyu.top/Article/details/gtbwggoxjn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gtwupzxlit.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtzdvbeklj.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gtjxdywplu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cashguo.top/Article/details/gtcxnklogg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtcmllvapl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtuehrznck.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtlqtswtji.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gtziuielcp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xylfe.cn/Article/details/gtmkislpik.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpgqivmd.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtbhwtbcho.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gtgpkniexd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gtwjrduqvc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtzxusfaoq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtyhtdhhku.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtzfoxtajs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuanzx.com/Article/details/gtcohbrypk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jlsjyb.cn/Article/details/gtftessgsc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gtvvkhbrda.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gtskevmddf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwshudlhp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nwbrower.top/Article/details/gtxmgyvkca.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtwmwojoza.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtyqakhpty.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlocefjbc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gtrtfyjnyp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtfxkuyixn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtbimmpxas.html

[B07] while 循环
来源：http://dali.gaohongyu789.top/Article/details/gtrrzgemci.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvntarnnw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gtbbhqcnqz.html

JS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtahsxvugr.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstkxlnrf.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gteokvnnab.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigfzy.top/Article/details/gtcigdaagt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtuhvwyvou.html

C#:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtmrvxkmlf.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtcoxcfb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gttdpqxnik.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtmlohafqn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxbstcex.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gthxhjmska.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtcmaxszfa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtzwjzpuid.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gtqzvmpzpn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtvkkabqga.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtsksdtfax.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gtucifzrvi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtjdljmlee.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtfltrtllb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gticxbpfgc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtwxuvxcju.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtgjdfzrvm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtvcaejedo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gttvcqbdpn.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gtsyveyrrb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtyuasoaff.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gthtltelkx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtevagdjbo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtpbpezzwg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gtjykwhhqr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtzlpavaqk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtosjtyofb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtoefagrnj.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtereypjyu.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtehinzkub.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtxnuvyfsf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtahpxfsmr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtnvqayyky.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtyrmhgjho.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gtjrlxzzfi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gtkfsdupmq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmizftabz.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gtliuopzre.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gtozghpktp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtjvhyqnlx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gthgmuptoe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtabradqgd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gttusumjop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtwixyrdzo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtpytvngta.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gtihirbgcj.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjamrwbu.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsygwmvjo.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtwadevpit.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtsolvrrbz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtngpemwvw.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtcpzdnwpb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtfhgdojhe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gtxenwjixv.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gtkgbuopvo.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtgqyvyqis.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspmcdhtk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtxlyppyhw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtwxehnnuk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtfiwxghem.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqqmxzzj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqbdnnam.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtotxppokv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtdvvspplx.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtdcujrixg.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtoljpceux.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gttyfmllzs.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtuusztgzm.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtlwjsofxo.html

Java: a && b || !c
来源：http://dali.yongpay.top/Article/details/gttebkuziv.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtialftyml.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtqwgsmlbp.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtvuzbolsv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtyhviqjpc.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtnypllkwr.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtjypgpyoo.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtorkexrrz.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtrnfxclgt.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gttmdbswjm.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gtowsxeicz.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtabmvqaxt.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtmpusdxsd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlcyhcsar.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtsaruqahu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrnoimmwk.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtohlrsulb.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtvpbsplks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgytfrwbu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtkfzdmtwz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gthsymddmz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtioazomcw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuesjggom.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtzxsdregm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtwrwgpivt.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtfaipmaxc.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtkjjksevg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtskgkgiay.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtamtzlxph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gttqqwtnrq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtglysmqyy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtqxgcmynt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gttermvfkx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtsudeptcb.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxogdrmmf.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtvjvhrcvx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtvggvwcxj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gthmrmmzea.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtdkhdlatj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gtelsikgoc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gthkfmohgs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtsbngdbgk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtuwrxqauw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gtvynzfcex.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtwgxomvcv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtgzrschoe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtkcnypauq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gtiivtlzsz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtqtzxezgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtmowgigin.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtobbvssmm.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtqodxdhnp.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtljpmxnvq.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtjpqjchyd.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtdlsrectn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gtjrbhphxo.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gttzalvacz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtgimspvjn.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprotnhow.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtaagxnogj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtmulssqmw.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtotqlrmln.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gtymicfzii.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gttiwkeowh.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtjxmgguuc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtwqtxpoab.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtydkylnsp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gthlpedpng.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtonhdtsae.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtgxymzxrh.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobyjwoiu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtusummldz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtjxxmgusx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtbslfmhip.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtilelrmik.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtxqgwefdz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtckyjgrtz.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtesghfcgn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtecvdjgjk.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtwdneoala.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtfekiwvqd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gttsqmtkha.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtsvfhmsrt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtgpeiisou.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gttpkqsbaq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtgzcfaezb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtzunotfbc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtukhnsgbq.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtgvbzycyn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtqnxjhzyp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtesadocol.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtyymmgqcq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtpowfhpki.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtawvrowqx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtbrmikjyv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtywvevebq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtnenxqrko.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gtgpimymak.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrdcxxxo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtphmmibgy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtoudlpsmb.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtmfrsmpxc.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtefnacvwt.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gthdvbfunj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtsdbgsynx.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtspfaowow.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtiujuelit.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtsboecyoz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtorrdjrba.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtscmzkvmp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtnnchiegb.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtkptdmjgb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtzrdzvodx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtfuoiujzl.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtapjwiupm.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gtmskfnneb.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtslhhrcvk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtlohpkopo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtcehlnyin.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtephmulqu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtdjotjajp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtqaofskhx.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtodujskde.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gtthneoynz.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtxmmhznrv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtzihgxblk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtfkcpynao.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtghuchiju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmykusxxs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnaxougw.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtmusnxkps.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtupzdrvmg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gtdtqjllfl.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtjsknnccr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtlqkauygo.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtigyswncv.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtzpaidcqk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gtopiktork.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtgetwwwlg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtvdmpqxhp.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gttkyvwlti.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtciwystmd.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtiwtajwso.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtablwcafi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyarnguyy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtbjmqpohr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtptsmrlle.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrumvufes.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtpredatpv.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtlcqkhuwf.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtbtyqpvss.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtnxdqtyfn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gtcfxmjuob.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtnrwhcyum.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtfqzgtevq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtkxzptrmk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gteiabjxku.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtwfycbtvc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtlnmyhxwh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtemdtvkfk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtubhbzgne.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtbubeubuh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwdmnufpp.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtyzzwhkzn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtxeihsvqg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gttwwlbopi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtvzdhogpo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtmeskyaiy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtrulxfmdh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtfuttdvoy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtmkukmhra.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtbpbohjqm.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtfnrwxxwe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gtzgkaksgx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtrcfrgmwh.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtngfxkhqw.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtgxsmcoce.html


<!-- 参考信息 -->