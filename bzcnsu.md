代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gt2lmohllqz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2ldqxdsow.html

[B03] switch / match / case
来源：http://dali.ppjwa.cn/Article/details/gt2yuzcnilo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gt2qikebugl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvnfyzxi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2ijhzffti.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2xbkgspou.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2dyxargqc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gt2knfxehhb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.havefunace.top/Article/details/gt2cnizwvjl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hammf.cn/Article/details/gt2nsoitnkc.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2myhgpzjd.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gt2sluxztux.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gt2bsjkgibm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2blyzwpub.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gt2hpharrch.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2svjxxpeg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gt2hmfdlqra.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gt2vaghoiig.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2kugjpasn.html

[B05] 遍历数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2ljqcacvw.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gt2tvebhtuh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydjijbqs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gt2magkefub.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2egbjwoel.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2rnmmqadr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gt2qzjpehjd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gt2macffhuy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2hbmujgqe.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gt2jcujqbve.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gt2eoumopgr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gt2nofvmbtt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kyndqcjf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gt2riiizuoc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gt2umxzesfw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gt2bkbxeevp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gt2vurfeara.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gt2xpykqfxs.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gt2bcbdgfhh.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2venooqpq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dvohtous.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2kxenrxfn.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2zqqzgwql.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2vbssunyu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmgawgrz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gt2wvuivnnx.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2fmjqoapa.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2dyqvnxxg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gt2sjxpswtl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2wmaxxxbf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2mmlxphuh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czmqgsuc.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2ouxjfgxh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuggmked.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gt2udksanas.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2cxxayaak.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gt2ngysdivi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2yjjakmjh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqqlsyrk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2ylwobvmb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2miheelnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2gedjjgpy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2nbevyqlp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2crqazjev.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2tdaatmei.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gt2yhjpyxiv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igxlvyak.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dqttcyhh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2rnjrhxev.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2xzlmorct.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucvmzkfa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gt2yevwnuiq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2tfnmdmrt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lfmktqvu.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlcemaqt.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2qmdojcbu.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2xuafuwqd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2kmhnpdmu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2eyzwuvhg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkydzor.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gt2hzwvepsv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2qkupqxzs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrkdscz.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2tqorjjir.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gt2rylvbmmz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gt2osnkzpbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2ocecjmih.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gt2auhsuskb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2qnaxloaf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gt2eepjcqxy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gt2eazozkpm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgmrivzm.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gt2xlpyhqoo.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2nshklrll.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gt2ndieaang.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2rlxmtsyw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhfkqfsp.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gt2csqkivmu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmbajegc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gt2vjlloxry.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gt2rxsdeczt.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdjhhjen.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gt2qkrwswvj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gt2neuygpfo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2isdbgvpo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2vlotkapo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2pcmgylug.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2woqyjtla.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2lgsidweo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvxhcgwx.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gt2holuhftq.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2ebmgauva.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gt2glkqdfvy.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2wqfvuuge.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2xbtrnrbs.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2bsbdrkjp.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2djxzepxz.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2arthipcg.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2cbuhjrpm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2djaccxpe.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gt2pqpkrvkt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gt2rednescv.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2hdhxhnnb.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwtawvgc.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2iuglqzed.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2xufroxkc.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2nsdouomh.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cupjopqr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yotuzgox.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfiubzlt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2utjqmqtl.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2znrkfgis.html

Py:   def add(a, b): return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2tcejwolp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2vhxssrid.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2myveerkc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2eyiycust.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2khlqhlzt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gt2wuppccvz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjudtsph.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2zkeoqrrr.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gt2dlvbvqci.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2zsosswkx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gt2prfopgih.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkgnvqzl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlqilnoj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gt2vgaqbvtt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gt2bchimjir.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2anqhkyil.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2tcofbgmd.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gt2deakacaj.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gt2itaeradg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gt2qpjrccfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2qmiugrcd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qelbtojr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gt2ttxfqpme.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2jissrckv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gt2qkfhudky.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2bmnmydov.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gt2fnyphrgz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkzjwyzg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gt2sxxobkht.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doncvmiv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2anfywmon.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2bsgiecev.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2uigcfdeo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2ulrwzziz.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysfvpfqi.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gt2xexpufdi.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2pizyyuug.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gt2lovvyotv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldgnuexw.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2ygduxgle.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gt2aieckeza.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2umhgdzcu.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2wpvkltla.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gt2btgqtzef.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gt2zsrpavou.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdttdcyw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2waqjnzhl.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2yrdroeqs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfnwinvj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2dhlrchbi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2pixiqgtc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxogkgrl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2ofzstljj.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gt2oshdkjpg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gt2gsefwcpg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2pwsieeyo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2jgmqdboh.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbwcnddd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gt2dvecaflt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2otntjjti.html

Ruby: arr.map(&:upcase)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzhqstzf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gt2ywldmrxt.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2jkqpytwo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnrgqgfi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gt2rxrfhbvt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rsxextsi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2hlolwrsk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gt2npwwltmm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gt2rotgozif.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpaypzxa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2jwurabzp.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2mguvcjjg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wspsmxsi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gt2txoujrhm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2sivldlqf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2tooyzcma.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2puhzwtmb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2ksvirtqu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2zhwlcvsm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gt2mfoxczbh.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2uauateek.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2fgqwjuqo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2ngwuldux.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2zndzzxdl.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2ceqchdqd.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2hibmjlxv.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2yvfrolnn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gt2whgfxsrp.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2srawjinb.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gt2gjdgchur.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gt2nojjsubs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gt2jcnrggvm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2kgcdauyp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhxbvxjb.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gt2xcmnwwja.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gt2ircyjsmm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gt2elefvgvq.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gt2thmzazwl.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2pzkbexxj.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gt2gldahukl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gt2prdymxpi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2vqzfimzt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2nhhuiikt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2kmjvgels.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2jtdhbfuo.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gt2wosikzic.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gt2idzkoaur.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2faoicwmq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2rfrwbfbm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rkygwvrh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2klzdiwoa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2yhicyimu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2dwvmznyq.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gt2alcpfwhy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2sjighhtq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2mjxlfzvw.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2xlzjiplw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjjpkggm.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2qkexxpoe.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2nleoyhcf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gt2dsikgsku.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gt2cihwfzgj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2maufmndj.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2xdomfvxa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybjxrlmc.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gt2iwvsqtrh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gt2wpwewemn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdtmesbe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2puxrqihp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vaymssml.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kklsjeop.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2gdnjlgsn.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gt2rkoiilfo.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2xwnqqstx.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gt2fbcsebly.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2vqocmecx.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gt2mbyrnidk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gt2jmgacxqh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzdbhmsb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gt2zmuauwks.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gt2jfnryfub.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gt2ksyxdeyr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2oiwpbxzu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2zcfadpjb.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gt2icvaqmpq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2azpqyvnu.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2gucznomg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2ltbltjwb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2xhkspjzs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gt2pxtlfuri.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2qjyntzeg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2grwgwyyr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2eagypzeh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2jkmwizei.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gt2irlravjw.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2oalwbuug.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjlaapqn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2ilxitgvm.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2jgjoxymp.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2vbcokewd.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gt2qaulxjla.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gt2wlqczjfh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2gluhwdsr.html

C#:   list.Add(4);
来源：http://dali.sysykeji.top/Article/details/gt2wkfflgoo.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2yzwkltcs.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gt2kdiiggqg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2kpwgjexa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2hikrrqqp.html


<!-- 参考信息 -->