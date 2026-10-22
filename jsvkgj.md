代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2agkqsgoq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2cathevtm.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gt2yoobzzgu.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gt2mfsntwhf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2lsmbilzu.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2oqtechwy.html

TS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2pscwinmc.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2lzqzvxek.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gt2hwqayuxz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gt2lgwouqre.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2jgsdkyhh.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gt2ankrmtty.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gt2wudqvhuy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2vscqahmx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2hkugbvfi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2dsotgztk.html

Java: do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjqznool.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gt2tjapufli.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gt2yhtkwjdp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2taszwgaf.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gt2nbyghlxy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangdashe.top/Article/details/gt2upceqyke.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2tmklpvtm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2uykatxtf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2adhoxvgb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dogdmphj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2sqxeavbv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2njcwmilu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2obmxiomv.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gt2qadkyqrg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gt2nnvohoal.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjbnnqez.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2oydpfghi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gt2eonjhxsu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gt2pszxmwri.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdljzygk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.snrcjt.cn/Article/details/gt2djmgzgwv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gt2pvjmfslp.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gt2zefzwbrh.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gt2cdezrwvl.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eczliwcx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2lqnvlekp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gt2ajtiahbh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gt2ubnbyyrw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gt2lgyejimn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gt2soqxpyuc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyqmqsme.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gt2lqyjjtrg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmotgsjl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gt2vexniqet.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2rhbvzsmn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2racixrka.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2bgmmqpuo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gt2gvzaxctq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gt2zomcjtho.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2czxeghgu.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gt2uzxrtibt.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gt2copmqvkx.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gt2foohhqxx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2qklmtmca.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2kxlrecvl.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gt2qlsmnnzt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gt2poskhurz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfrmfyef.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2zjgfheah.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gt2bqaatrts.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2baiaorpl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcoulkwd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2cpprzebw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2xfcpamqc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gt2wmhqjrpn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gt2mvjtdmmi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gt2wfasvsbb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2icnlwrad.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gt2vfadpjpl.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gt2cowazcic.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gt2smkrxtdd.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2xctlyndu.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2grbplpqb.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2smuurbeg.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiadrfgg.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2tkdeljve.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2xkxiuzcs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2ojovumhx.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gt2vbemftqv.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gt2awjvmuoa.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2vectkynd.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnaymxdo.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2mqjepdcx.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gt2fisoplwy.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gt2xtvhiyjr.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2anzewcel.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ryojedvf.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyuxoijz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gjoihivg.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2avztgpuj.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gt2gicgcfoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2dzhgdwgf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2gajdbgsv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2jwiarbli.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2kusifapf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2rzyhqmtd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gt2odpqlkua.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2owxsxzzh.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2hemiaisr.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2phckjcmc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2mfblwyxt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xlaijvoy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ldiyixjo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2hfqltmox.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gt2ermumlrb.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2zzxqpjxa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gt2cmycjkse.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkdxttmx.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gt2oydrzvbt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gt2utcmgzsf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2ptxffnmm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2keyczpvv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gt2bpiijuyk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gt2aipmutiu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2vnbaibgp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gt2ihobiedm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gt2ndiptack.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gt2siawqlam.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gt2aisnhxfd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qoxyomke.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2dfxiszag.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2vubnnaau.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2zdupwfch.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjxchdai.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewtxdyhk.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gt2zeenfhrc.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwqgoqux.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gt2gjtikiip.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2vcitweog.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2voiakndg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gt2hqsfyljs.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2iiqmjumg.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2xsuznfxb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gt2nprlseld.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwyvozm.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2vmqyiwlt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2vmrfzwkv.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2stpxfbnd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2spkxniba.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2rggcxdoe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gt2kvzeyvxs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2ymzuqdba.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2kfziubwf.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gt2vozuicde.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmivkbdm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2jloffmak.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gt2psozlcgp.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gt2ozpexivv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gt2bebwxgsy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2augyemke.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxhxpars.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gt2pudbotqx.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcaarfpf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gt2oaqdmofh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gt2hgonicpg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2varscwra.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2jgjztvnb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gt2djkeroul.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gt2strxffbc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gt2xrbmfqkk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2aejgyzwn.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gt2wkfbnkpz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gt2quxvkfua.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gt2zrioslxd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2inzmxkkf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2dsomwusk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jnnulmbd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gt2hjaelvfl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfuuriyg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gt2vflfbjvk.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gt2rpsmvglj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2bcdyluvn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2hrfublnk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikunamzk.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2oftyblvq.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2zhrahinz.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2ludfbchz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gt2bozlqerf.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2zyicpdut.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gt2mcqbixqm.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gt2bssyimva.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gt2dcfotdwj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2wwzijvcm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhaibhjs.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gt2gbymntdl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gt2bqusbpnp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2lfihzofx.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gt2wehtjozh.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gt2ldmkbpgx.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gt2bwsfxfkb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoehvzj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2tldvqcjc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2khcbqwoo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2eqxzrlmn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gt2ovgqofpi.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gt2dmgyisrl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2romxytqz.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2tfibnghx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2fkzdnpcf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2cunkfovz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gt2wjkpntwu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ozblajrk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2jycghfmd.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2pjqjkteg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2ngattsjb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2bbadgqyo.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovpcosrx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gt2pesenvnt.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2rcwtbsjo.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2ajvvsbrn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2jvxomals.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2lfcqpdcp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gt2hwulrqup.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2moqbnvxc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gt2ctccandr.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2irqesmjx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gt2unhjvjys.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gt2zumehncr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpyksfxk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cioeywav.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2dzriqfnr.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2gqkabcxe.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gt2bernhfqg.html

C#:   var (a, b) = pair;
来源：http://dali.aibaodan.cn/Article/details/gt2fafbiyqc.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2ehueocqg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gt2wrcdbzcp.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgrckhos.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2useaajtm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2abpdzbjy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bxspodes.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2frelyydd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2mvxgdcpp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2pbkhbpys.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pjvydprv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gt2zptmyxls.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2dkesptyi.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2wycdhvwi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hammf.cn/Article/details/gt2xewvifne.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgxpihyz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2iaozhjck.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2wdbyqhzy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gt2wydipuuo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2unwxpimi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gt2rrnmbbwr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2kuhlqyaz.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gt2pxzisqqj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gt2evzebxgf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gt2lxzmlkwp.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2jdgcekcl.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2kefebmvf.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2aqqnpleg.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2afukoxrc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2uaqojnbc.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2tkveorgf.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2ostpdokb.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2cugcrhjy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2dibvkvzi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2bnufsfau.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gt2voocoreu.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2kejxhgfy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hfpthk.cn/Article/details/gt2vqqpczmv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gt2yvwicwmu.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2zfswpwst.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2nvdnnbqe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2pwjhwegw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhqcqwvh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgyrargg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvayuqz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2bbxfangq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gt2hpmlmraj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2evfxobew.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gt2ifeqfxxn.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2ggctzidw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gt2jylggknd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nyehfzln.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yazeiosr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2sdwfprrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gt2rjztgyyd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2dznbbxbt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2ccnmqefa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2omszjdtm.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2zilkwhkn.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2jzpizitw.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gt2egygdrlv.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffwtkmkh.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyrjbugk.html

Java: list.size();
来源：http://dali.yanxiufei.cn/Article/details/gt2gcjtcrny.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2chyprwxe.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gt2bhsdiove.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2vlrndzrr.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigfzy.top/Article/details/gt2mekihntb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gt2rxnuuqad.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gt2ztymylgo.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uojxabex.html


<!-- 参考信息 -->