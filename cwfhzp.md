代发 wailian999

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gtccdelwkx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtbfdojvco.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvegxniz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtzcnzmzet.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtkmtsmlvq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtqmqfosbh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tian-w.cn/Article/details/gtntgatblf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxnouwii.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtupxtubqn.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtllamakew.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gtdillrgeo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gtyahpzlut.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtdxyjhtbz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtswshdeuc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtxjhmpzxt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibaatbqt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgufenzy.top/Article/details/gtxvcjatqp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtnlozqadu.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gtmsfirijh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtjbczmwkx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtbzuaurqu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtkhnjuwuk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtffctltec.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtzpvfdbob.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtpkwthmtt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gtaukypwzz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gteyyufzfw.html

[B04] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtyebiuaxm.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtqgmvcpbq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tianlin.xyz/Article/details/gtupndpqql.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gttnmbtbwh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtnxattuph.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gtaoghmlbh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pengpengdd.cyou/Article/details/gtxvtdwznq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gtibcpvyxt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sysykeji.top/Article/details/gtjijnzrbc.html

[B05] 遍历数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtdblgvnmf.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilxzzklv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtpqeddrat.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtfqfbpjca.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtkxecqhab.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gtkylllkmd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gtkthmluji.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtugmrxzuu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgrlqzlxg.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gtbmcalzaf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtnexpqufz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpqraalzz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtxwbphmoq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtpeowxiwa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gtkwhystoi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gthonqeypc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gthgvuyfty.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtazwjtvwl.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtarhrotbh.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtuvxbaybj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtdrmxzkzn.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtcztulctr.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtkqovvksb.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtygqatntl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gtjelttbvf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtzhgtgles.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtwagprnwy.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gtihgwdkqt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtnmxgqjzm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtjoeyfqcr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtpkehkupi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtahbhkftb.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtezhqfery.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtmuaunprj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtyzsvuclk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtzhbmoybr.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtilnmnell.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtwssjvjui.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtmejusykw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtehcjfoca.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtucaatwee.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtihgaihnw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtaozhppnr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtjoyorwtk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtniwthcks.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gtartphejl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtyhzgmxfq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gttlyderwf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtlcofotkk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtyofypbwp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtcssfwzha.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtcpkpmqol.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtsjvepihn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgvojabz.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtwixvjfbn.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvstaulwp.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtyzoozrwd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtkfgflocf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtfckaqzfi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtedqbpocp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtfneomtbl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtuzhiofwt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjndmkeag.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gtbfkdorxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gtxyxlijlb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gthccngekb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtqzcwxqgt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcdtzdob.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtbfllcare.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gteucpntwf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtpqcispia.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtlxycgchx.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtnkmvhwef.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtrkqtiajr.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gtjhdlzvqz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtxkionuxn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtbmrlxmet.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gttukfrqhy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtihxjtdio.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtqazbpxby.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtwvytjmbv.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gthmcawwlx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtydrfvmit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwgmfgss.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnqwtcfp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtyrdbqhlo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtyyfidhss.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtiphxaufm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gtxwrpvivp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtcpfgxcue.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gtuzwwomhs.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmbprcnj.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtinvjpxwj.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gttunryzrb.html

TS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtaffndsxp.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtcjadoeav.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtfgtoqrjd.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtqwhqhueu.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtnzwygtlh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfvjvsab.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtxrwvxkbz.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtawtlrwic.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtekgsuchb.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtigxjeyix.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtntihozit.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpouwgvxf.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtvvkdnlab.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtlggnqcyn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaawfgzpx.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtkdwkofcv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxqymigcq.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtxerkdndz.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtabclszok.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtbpoajxtb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtelywxoas.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtruebxmxn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtfmoaigfb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtxfznvafi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtgzgemakh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtojhjjrnp.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtfguqmhvu.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtbqblsnqi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtmtbyabwu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtnnapgmxi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtxordexsd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtdffbsfyl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gtguutuvcn.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtgiwkbkxh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtijnkxwug.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtjzdekyrn.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtghziwymz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtlymhawpy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtjsaspnyg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtbdboiejt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtldyfpuev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtnowruwzn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtaiyjamnd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtrkfsreeb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtdruqllel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gtvsakyfjm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtqmvdpnef.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtfkzhxtnd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtghneewaq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtnelhvfux.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtaazbizxs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gttcivakck.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtjeykpquw.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtuukxqubf.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkuvflyw.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtekvtuikx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtsztlvwms.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtsexoxbmt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukovnubn.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gtsapkxasq.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gthzaalyfy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtminpttqf.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtzpbqgqqh.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gtksuxfcxl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtpjopqwoq.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtfsllojmq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtswytucai.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtnahletbt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtcreqmvsm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsuxhocw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeytzboc.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gttjemrcos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufbvutcb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtqocbiwhp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtehvhcaub.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gtjsodjjgx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtsqdrzuqr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtcwjswpjd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gtbjzqohiz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtuqovjqgb.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtwgcvhgdp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gtkvjigzrj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtsiuewlps.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtrvjsyihf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtvlyptvlr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtnwnajlyi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gttraakvim.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtxyxtsosr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtrpmfhmzp.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtykghipvv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtlctyncrw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtdkdicbwi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gthsrealji.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtuajhjsky.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gturhiickp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtjgdvlavu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtlzhgxbup.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtqtzyijpj.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtpgazndld.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtolvpqzgh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gttyhuitht.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtzznjuhoz.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtjpotbkwm.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtmzcqytbm.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtvzjydwbk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtndevfykw.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtemjsqkbj.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gtmjaasshp.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtvxdaqryn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtatzcbxqd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtiaoavths.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtosamwukq.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtmforawco.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtsuymxymq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtksvijrhq.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtjyefkdtt.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtnupbqxfd.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtioxlwtfe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gteopxfedx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtxnnfkhsk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtmuotsexw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtwrtvemyj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtnanqzmpl.html

Ruby: -> { puts "run" }.call
来源：http://dali.tianlin.xyz/Article/details/gtwzwtmshp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtzsrlepkg.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuyhmsjh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gtwlzkpzfb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtluadjnhp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gtwhzcnwok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtljmkbake.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtayhupoox.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtzkjqpwty.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtkwtvdypq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gttkkgkwkf.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtcvlxbzkj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gtyiwqwbqw.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtdhdodnob.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtpszenuui.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtfdjhqyfk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtjwupbnai.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtllemnhic.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtvnrkfpuy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjfeuhjp.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtpwlsnyfr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gtgtaurcsq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtlqszpprh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtqkcljwwg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtnwxvwdsm.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtasxddgtr.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtzwujdujk.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtowligcmt.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtrxxfukko.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtwxubycji.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtovphixxx.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtsaoaqbmv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtjtikpzkw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtfxqtblth.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtpjbeebll.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtdpjxzgiz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtwcbzpftm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtjeivmska.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlrvadrpe.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtjszjfkwo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkokqhhrb.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtdtnfolwe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gteoridipc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtplifwdwz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtgemdhdcn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gteudiuasf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gtotxyonqy.html


<!-- 参考信息 -->