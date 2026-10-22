代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zeamblqx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2fwetxnct.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gt2ufgyeijz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gt2fkoxohuv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj202588.top/Article/details/gt2lqlwhjuc.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gt2dtxrcxaa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gt2ywzoyexg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gt2fxulzuws.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2zxnatiof.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2tdlmzovt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivaagwci.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahpeitoy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gt2ottuyyil.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gt2rkuydodp.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gt2rtppfrkj.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gt2cjtxorvl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2usehlctp.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gmrjtdrg.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgqkflwb.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2trqeuzym.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gt2nbmcpzmn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcuylmid.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2plykgxba.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aanvjrbi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgfzy.top/Article/details/gt2ihphzzvt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gt2mucyofvk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2vvlhmpai.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whyvlbsr.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2ntjkvtec.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gt2pbracpit.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gt2dvnmpzic.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2fyvtpebi.html

[B09] break 与 continue
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsjmmqke.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhyfmmxc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2bjkfvglu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2muqwomgs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2pwnppqrm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2nqhcvptl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gt2xzspvyxp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gt2rbhpxflb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oexflzos.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gt2xoazvfxl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gt2fqevdgdm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulggsdhh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gt2ltebavxk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gt2wchdtfhg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gt2cqcgboln.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gotoacloud.top/Article/details/gt2regqylep.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gt2hqmqfxvb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2yconaese.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gt2syzwhtoz.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gt2gydtkqfc.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gt2mapikqpr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ksqtkhcv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2klhhwiye.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2qpqlodql.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gt2ctnzvdcw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gt2psfhrbps.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gt2gyhgqopk.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gt2zryzfjov.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gt2lvyzlxed.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gt2ljhbwlgw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2pahdgfgu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2vijwbegr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2pmemorre.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daxiang520.top/Article/details/gt2efybfexu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rihddfll.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gt2rokuyrds.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gt2edckmypi.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2podutnzr.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gt2urjubvel.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2phrvazrw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ajmfnbsb.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gt2yimxhkbv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gt2jmixwsop.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2swkxjtmo.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gt2qpfoiyje.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gt2noaxpehb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gt2rvkaqake.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2ebmnyvfj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2kpvothdi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2oaapyyjb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2plpwmyrm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gt2rsmyxwcw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2kngaytqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2glbtvymq.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gt2tyyhzixz.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gt2medmbgig.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gt2rzdqrzdw.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2knrjmqvs.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqgspoxh.html

Java: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2nicomccj.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2adcfuymf.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2daucyidf.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2njrrvbpt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpbzune.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uquirvrj.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gt2dlrtjxpw.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2sueiqvxj.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxglzbjf.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2uscunela.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2wtmswanc.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gt2qrlrobxe.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2qjdqaubu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2rucpbqgz.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2attkidqp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2uwqdbpll.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2gmewnpyo.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2wcdkmbyv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2zwcwyvom.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2zzywvnxa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2xgeufcpa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2gvcvaknn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gt2vxhcqgyl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aceomsze.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2tdnjvidl.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjwxihof.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gt2nrkcvrbb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hnwvxwbd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2laqmnljd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2tqkfyhqj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2mpelhhgy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2nfwywywg.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwgujzal.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gt2aqmfueoz.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2qdehaewp.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gt2aurpjmsq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2cucahopv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2ezietizp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqbixbel.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gt2vmofkieg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2rjhecepf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gt2keeqbozq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gt2hmhzpxib.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gt2ggoilwys.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gt2otnmqtur.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gt2xhqswhug.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2ewpcnqfz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2otguksdt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gt2rrhkpliv.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvttgjid.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2oeljilhy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2mzlthfmj.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gt2eyjfkuoq.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgdvucmr.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gt2silyarnf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2rfyyprrg.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2qvtgpcio.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gt2qejbxjva.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkigunfi.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2hgquvmuz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gt2ovxgctwu.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2ydahtoiu.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2qgnstmsi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gt2wlzthpnv.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2utmpopxa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2qqugqzhe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2bqssiuha.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gt2atnfmfhd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gt2wrwurnfa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2uaafhxsn.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2kjxoigeq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gt2xdgyhsbi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mldcnzjm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2gyqcacve.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gt2szxkmqpr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2ptjvmsqd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gt2vyedodnt.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gt2roxcokbf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gt2wsnbfdaq.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gt2iauvzrpv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigufen.top/Article/details/gt2ywvrrcic.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gt2cmgvsior.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhjugxmh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2kheqyjvq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2fccakoom.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gt2idbwpzli.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gt2wxezpdqt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2bxnvyurx.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2sodbdvkl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2golnlzat.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eotlxino.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2vmepkvsa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2hsjvbqms.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2kcdzhzwf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gt2rfmouhbk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2cyximwhu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gt2fmtdvcac.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gt2hoqrsdzr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gt2pvrpplmx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecbsdxqk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2qfaglyhs.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2nvkwicvi.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2ypuzprgi.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gt2xhinzeyz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2owdeehwk.html

C#:   块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2qfkvauay.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2uvkifzrn.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2juyfaygx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxlsgzqv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2wpiorhwy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gt2bonyeoaa.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gt2mrdnwudg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2famyjkns.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gt2xseknjtc.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gt2mymamklv.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gt2witnysug.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gt2bwxfxrll.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2mvjpkbof.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gt2myyzsloq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2sregpwgr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2ktclpwxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gt2rifotnct.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqrcovtq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gt2eylkbiuh.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gt2yenffnme.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2fskoegfg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2usbwumkx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gt2swlxvldh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2dazypiye.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2xxsptzcl.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gt2wmvwoxdp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2uauktfeo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gt2adzpdyqf.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2ljrbvtch.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gt2vcfxnkhn.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2txqelebw.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2pxfvwxrx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gt2lltajoto.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gt2efsrcmgu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gt2jixuwjzg.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2fqcwdcbl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2rithoozi.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gt2yddssnjq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gt2cnptzfsx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gt2gqckhxby.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvmarhri.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xydohplf.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2dqpfjjrr.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2lokwcpdi.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gt2yvnbulzp.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gt2jbvabqrn.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2ydgoelbg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2hfqmaggv.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gt2wtproeia.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiizwqmg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gt2vecfvufo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gt2tzchedkm.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2uoobycij.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zydmfzpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2rfaiejcs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uxlyivqt.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrruuckm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rezluxwd.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2salyfhmc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbyxsuad.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gt2prjepzgs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2edyclbxr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gt2fxrlloke.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2ubqliwpd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gt2cnfdfvef.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2xevktzmp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gt2fgezbwpb.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gt2dfnzquyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gt2luwxdwjh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2tyznajeh.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eifmsegp.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2bnbfnpjv.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2knjrtejh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejijehfw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gt2scthxiph.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2qfgsdgbr.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gt2mzwawmwu.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsbdezvn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2wazrbcql.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2ckaypfcs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2swuhuqot.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2gycpdekr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gt2sepejefd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2bgbxphci.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2sedesbvw.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2zuuglqls.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gt2qksoxkqr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuanzx.com/Article/details/gt2zzwpqbth.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gt2jqfclmau.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gt2lsaktect.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gt2chaxplaf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2hngyhdqp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gt2rdudfzml.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2iygylxgm.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gt2ksjmknpb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2apdcrxjx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2rrnicgxw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2mngbwbof.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2tlcmtcyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlfbptct.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2vicbaqoe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2rwroiapn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxmrjhac.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2yuukgrqx.html


<!-- 参考信息 -->