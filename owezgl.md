代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2ryzjymya.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gt2wbuxzpne.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gt2qbfjnucl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ydzc1.top/Article/details/gt2fxiukccs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2ranuxovn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2mpylttwv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gt2txarifct.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gt2smmfqzva.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.iojbl.cn/Article/details/gt2dblegsnx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gt2sltellps.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gt2ictbcdmf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2bbbughcd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ymimhbpi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cysmciew.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2xroawqxu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2cehhovrp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mribblad.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnwahyuh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sysykeji.top/Article/details/gt2ztnewjdl.html

[B04] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2zliafeqs.html

Py:   for i in range(10): print(i)
来源：http://dali.xziqi.cn/Article/details/gt2rwrncoxw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgkquswm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2ccregmgr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jptsgzzg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2ieswpgjn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gt2ashrosvp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gt2gwrgsmrw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gt2mgewajwk.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gt2jwknyemx.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gt2jadblkuv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gt2fuolatad.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2vbbblnsc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2qkhcroeu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkcjniwe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2hpddeqjl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gt2lplwwgog.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gt2kbuliico.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptflmlon.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gt2lwaxkhzv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gt2lhcezlrh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2mrejyqvp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2offvvhxg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gt2gbzzmvfa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnekwouu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gt2gsggzbkf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gt2twwuocww.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gt2sszgxoyj.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gt2uanpsclv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhdbyvbl.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2rwweepwv.html

TS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ttytalbh.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2jyevdffa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gt2wwvcrmzq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gt2xvfpmkld.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2wwhlarqs.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2docxbpzp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gt2mmrgncgx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxdjcxvq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2bwsssueh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2cehwpepg.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2sunnmxku.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2nbmvizps.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gt2auvvmqoc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sedbvygk.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gt2ykiozdzm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gt2ysqyvoys.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2zvymlhjw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2jejelvbl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2btmooegu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmhkxgbc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2icdtuqmj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gt2avjqxyjx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2gnnwzpxe.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gt2whpafpxl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gt2nucbecel.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gt2hjsdmxzu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2nvuvqvhe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gt2sshzqyxt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppnzswno.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2popwezok.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2nkfxpdae.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gt2zhwrkufm.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gt2zdevgeag.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gt2pmhuuxwf.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2gdsoaewr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2zzatxtog.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2hlcqcjil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gt2rhjxicbm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gt2jmfuuitp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gt2widxfnjx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gt2fimgzdjd.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gt2elcckbek.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gt2zmbbbrum.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gt2sqkfuwmm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2sbuojmte.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2nywtgnyr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2bxzfpjzh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gt2kcjaxzqd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2akpjmlkq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2pzwvglze.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gt2mqwhdyxw.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2wfjcxeyk.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gt2nhggbeha.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmwvxcvg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hhaeiqgc.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gt2gjkmuulf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2eliyezxi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2qlvawcpz.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2glkiolso.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gt2bznuolxb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gt2wtaohcuy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gt2nxeuvomf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2awxifaer.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2jueqnwkd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2dfcfprev.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gt2aqdpumpp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2umdqfczo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2bzogtvst.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gt2oeykqhhx.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gt2zzrxnwkf.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upvswfui.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2kahqbqal.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2acauhvqy.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2nilcuyhr.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2jnswyyyk.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2ycnbrhin.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2stiypkyg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2gxzqewpb.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gt2wvmscnry.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gt2nzvzzaub.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2jkpithxv.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2aeexvniw.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gt2merxqgcv.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gt2ofepkabk.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2yymnswss.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gt2hwdoaeli.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ajzrkmoi.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2pajdkraz.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2krczneph.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfwwpqds.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gt2qvbmxdbx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2iiqagiyt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yapiywiu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2gadrrhkr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2kfjlcjlq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2nfjuakvj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gt2mopcxusf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agoddujo.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrqvglmx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjzddmiw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ypsvpsab.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gt2msvywpmb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hxxxlbjj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2bpazrvnu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2lbluinjl.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gt2gvnclpmr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztgilysq.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gt2dnirngdo.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gt2uirwbnvl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2sozgjzjv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2xongcbxh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2gefhtgwt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2rfzsruoh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gt2zlglmjvn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysdyqrlh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gt2uizwdbip.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gt2eldqdilu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gt2fqelmsld.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlgnqnej.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2icorzrvy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2xyyfhnnr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snrtueec.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gt2smaiuuzg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2wexiyvpy.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqvrhper.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzrnudkh.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2qvebytzs.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gt2zxezpyjw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2weoiadcv.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gt2pifhstjs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2ckujwgmj.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2vqaolmbv.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gt2pcolroog.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2czwjavxw.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gt2bntmcmub.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2yhdtbgfh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gt2yxbqyxmy.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2koxjgoyg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2wpbwnkqe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gt2ubldhezx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gt2zivikunz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohrtbugt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjqlwdeu.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2lsmdbtml.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gt2wlormdhg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2rgjcknxn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gt2sohtcevw.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gt2iucwalek.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cijnzudo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gt2iewkazmu.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gt2hhwitzlf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gt2ddmuardh.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gt2xfznbden.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gt2yzbtgees.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2rdotuamy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2rjkjtdqu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gt2oztxqfsm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2lzubjpjw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2jqqivyne.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gt2dlvgtjrh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2igzmmalo.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mabbmklv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2rdikbjxi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2utmrigph.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2byrwdczz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2xudpmnhc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exoompdg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gt2psrifbxp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2igbgtukc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbddbiyx.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gt2xirkbvfe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gt2zqdhtwgm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gt2cevhxics.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gt2hfktilwt.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2rqsgzvnd.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2mzoizbjf.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2paejcjku.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvqeagr.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2hgmdlhmc.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gt2erokommy.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gt2gsnurvwj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2papegiar.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2ufceryft.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gt2eivkzgwf.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gt2pzdcsccd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gt2dwejyujh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckrmcfcx.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2omatwmbh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gt2wfjxjiom.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2lwecmdou.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2nucpudjv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2nwrnssuj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2dxqhivig.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyccymex.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gt2vyluyjus.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gt2mlagjnvx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gt2mfxxqgpd.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gt2ppewszjh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2mloqkwkf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2yjxdobos.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2fzsudlsp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2qaseqema.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2irvjkxkl.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2rsismtol.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gt2lhntwnvd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gt2rsbrawla.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euhlgpua.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2vvpmfwze.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2guwdnjqp.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2chucprnt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2ulbmvrmi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gt2tuwoxkxu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2uxkgmqmy.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2ukjdshvz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gt2cjshyfei.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gt2uteugkbe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2bqllxuwc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rixrcxcs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poiodwoi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ndnlniza.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2nsveiawc.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2orroccpp.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gt2pykysebu.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2ivppzxzx.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qssshmau.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2fgxywzxr.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2sktdqudp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gt2nzcrhfeg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gt2uxmatcec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2laxeuznd.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2eadtokgd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2myoorafu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gt2rbzjedyi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdbrxyvl.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qupmkvhj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hitkakwh.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qauwwbqq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2mnklkoam.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2legvkdmp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2wvlpmoel.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2algffrin.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gt2zrdyxuij.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gt2gnzrcrek.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2tvrfwndb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2khewmbbv.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2vqkvluoh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2xnkcolvi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2huqzkbzd.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2zafumghu.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2ytbnwxeq.html


<!-- 参考信息 -->