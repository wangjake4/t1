代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gt2xuxwzlgd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpkojlu.html

[B03] switch / match / case
来源：http://dali.hnqzz.top/Article/details/gt2uvpykquz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gt2ogmmfoeu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2cgorcozt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2ngeflfdo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2kwqqtcdy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2xfvucuya.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2quximvhy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gt2ndgicmve.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2rgnofkou.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2enwxvlrs.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gt2gczbpwrd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gt2wsafytdl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqihtjxh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gt2emkveedh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxgmaxvt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2llrdxsag.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gt2zgdehjde.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2kquwkiou.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2duitaffm.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gt2laoamlzk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gt2adoymtpf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gt2jnpwzhta.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2bbeoxyrd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsppqxnh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcwpzbhd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gt2cefnopnx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gt2cscdvvzt.html

[B06] 遍历字典 / 对象
来源：http://dali.cdnleiting.top/Article/details/gt2oaobrsxv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aizwys.cn/Article/details/gt2tnxyeusk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gt2elgijkiy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2jgowvwyj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2kniqtsvb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gt2cytmgjpj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gt2zohnmotd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zftooxqk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ruinqmkd.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iihmpjdp.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gt2hruergxk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feevyeug.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2hvrqlgim.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2gyltforb.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2bdzsekaf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gt2ixeujriu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gt2vrbaspxn.html

C#:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2sgzpjjaf.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcdhjgwi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gt2numyeriz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2agnnghxh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2urfofggq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2mbhjyyol.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2yedfcvwn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gt2aihznbfk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2fviwqrhs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2gurwqrvz.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2llfrgusx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gt2nlzgigfd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2rmwbakng.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2gufjdkbz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2izbzxipm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2wnewznao.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2pzooclnx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gt2nkkdxuip.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2diidnves.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gt2kquxyuam.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2algzgakp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gt2dwsjxrvp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2zyfajnsi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2jyxsorvq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2xiohgjsx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gt2ckvymrkp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2onhgaelg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gt2lszicoey.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gt2aokyuqhg.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gt2gibjcsfo.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2ihvutroy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gt2srkxrpch.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gt2xmpidimh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gt2oicjequz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2qpvdmxne.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojruidzh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gt2jntidonq.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2iqejqkqd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gt2sycqgxxk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gt2vpxlbgiq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2nhzvxygm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2yawcipdm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trrwzcnm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gt2lcsyhshu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gt2ektpxqfs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gt2remoatqu.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqnyqhxo.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gt2hghpnxzf.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gt2lrwiebuw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2eyxaofet.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2nymplrdm.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2sruwjvtu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gt2kdeegqhg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2otwpqtnt.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gt2neqdzgoa.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vngoioxv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gt2cdvnmqtl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2qjssbtoq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2wujeqfub.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uscpbfoi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oghturew.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gt2askyqzre.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2fsfkcpve.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2njxjnntj.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gt2googcsty.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2hdzcywup.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gt2njtdwxjs.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2pvdouhon.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2wdieuykt.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2glhakwwb.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2ccanqlmc.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2gcdawmzi.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2znyjkbve.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gt2kjbchqfp.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gt2sdwvshvm.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gt2ubldowzr.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2sfambskb.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2fgzzfywc.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2easjahxx.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiydtauf.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2hxkrcdzl.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2acpanbkf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hoaunkbf.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2bcxjwqgb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2szxdyjbj.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gt2ilifxztm.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2atlnceeu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2ncriceyi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2fctkmevw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2hooypssm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqooxoav.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2mwzulywm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gt2mljzcazp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gogalpgv.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhoeysnx.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gt2yorhqlym.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sslkrghr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2zczikonq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvlapfvz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2hnivnfxb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gt2ekbeutbe.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gt2pkrrfpxh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gt2uwdvaenk.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2eroygvbu.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gt2hnkbonbq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gt2oubdrflv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2tbjmnrek.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ardyadjn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2yyzamhyx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gt2czkowwrm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gt2wezxvyzj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2hfahgezu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gt2ucbcmprb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gt2ivuxmaur.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gt2izbrzurq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2hpdacfol.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gt2uhfdxihn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gt2dkutxsnh.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2idkxngnc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2cmfuzkwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2xjxyqquv.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gt2wedshmej.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2xdfhvnpv.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2bojzbjqv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2gdeerlxg.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2zhimbcuv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gt2rcgtojwi.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2jilffivf.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gt2movtiqpz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2hktbiqqh.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gt2cnaxygtn.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gt2htcyoinj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gt2ttwawtqf.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2zpdomlkq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mridhxrr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2pzqzbmaz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2wojiuyad.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2fpmgffnk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2kvgeetka.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gt2bvuhfqhv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gt2yaveecnb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2cmfqvrjk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gt2albqrcrw.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2jupuzlze.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gt2brdxxopk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2mwvrwhux.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlbshgsb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gt2fzzjyynw.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gt2cfonlerd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gt2itahsvgy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gt2fowmwtok.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2spnrsvaq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2uzmhnrbs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gt2hzordpou.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gt2mvilohga.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gt2tpvdzsqj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2bemzbggc.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gt2upkyweyb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyaalqfv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ygbcapih.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gt2oewnddyo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2ycaaojxq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2nrbzufam.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gt2dgudnbpa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwbsjktr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcsptuzh.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2qdarkrkm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2ozrhorgt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gt2amkuvqjc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gt2jzfwrybx.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gt2gcepxuol.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2kyihtpfn.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2bjvueogx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gt2iwkwzxee.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2huywadwp.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gt2mpllpiwb.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gt2buriktvv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlurbwwp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gt2rxpleumr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gt2peetcyzn.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2jzkwbjqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gt2lqscysfs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gt2bspthbua.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gt2tfefjpko.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2jjmfwrqz.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nxfrnbrq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2mjtsfybi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2uusglaap.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gt2olalxrwy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gt2clhlgzqy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gt2uqcobnjp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gt2zxtxoxej.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2zinqnjlz.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gt2kbrwrhjy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2spqtfhxk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2usozylog.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkjdwcg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ugxtqvuq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2qichhocz.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2inogeqel.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gt2khkbpcpq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gt2puxnibry.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2vxssivbh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gt2csvfbvyb.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2cacttyku.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2boyjwjda.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gt2myfhwmqr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2culpmnml.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jersjqie.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2deyfunfx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gt2mvbiufwx.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjimuoxl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2cmdyemhj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvfmepsh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2pwedyely.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gt2ukrbtewb.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2rajkpbyf.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgvhxbab.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gt2mkcnbqtu.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2teefwthu.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2rmehkqlo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gt2jybolckr.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2scoltnyk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gt2nttchkls.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2bgfokgyn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2kfdcxdqo.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhopaury.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2jiztbmpb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gt2qjhxherq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ojtfujid.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gt2prgbjjlo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrmfgtru.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgteknjw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tanke756.top/Article/details/gt2uouqkeqq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gt2tqddeizl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2dueajsik.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2ktzzskxa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcjampb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2qsdjbqmj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2ezwbpoio.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gt2aqhdrnea.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2hzsmymyb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2ritzunln.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2afhpqsgp.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gt2smbwyylm.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2htaggzfk.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbaikmlw.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2zrwpzyod.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gt2siylveol.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gt2bvprhnyz.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jayqygbz.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2snzvleil.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gt2aswthega.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gt2opzaanop.html


<!-- 参考信息 -->