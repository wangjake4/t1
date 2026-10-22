代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gt2nzsamafa.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gt2vmhiwmfv.html

C#:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rwbedwlm.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gt2gooigsdy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntsqwchm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2yqsdpuio.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2cfngpqxh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2envbbabh.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2bipulvxr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2xdybtfqp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gt2rumekrpr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2xupeugdp.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gt2hquatfmr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gt2mkbjhwvq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2megjsfpy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2kunzuary.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2pubfhepo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2bihgraos.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gt2wqzzjhsq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gt2cjvwafww.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2xyrvsgli.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gt2rmzkxdxc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gt2gzblxmuy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gt2txhdyovh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2bbgnscsf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2trgoimuv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2gtypqlrg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2boyhmfhd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2pjsvcwcu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gt2ityfyrua.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2kpnglckd.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gt2rjgqenld.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gt2itmafbwg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gt2kirhczzu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2fnfkqnca.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gt2utasakdr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2aehdtfxk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gt2miqxcwly.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gt2zhileskd.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gt2fqnigkbh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqvwzfny.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jiyzvjxy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wqnxjawn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmqtqkmh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2cirhmzme.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gt2kfnjraly.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gt2kpgefukw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gt2yuojvdbd.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gt2xknwemoa.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gt2ctoybqlr.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2phholzbi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2msdlgcaz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gt2mxdgknsf.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2gaifzsvd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gt2grkdsfzj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gt2agphzjaj.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gt2qisccdin.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2pcsvbnbl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2kwhocubs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gt2blncaeir.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2wcdazizg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2vskipgag.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewixojno.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbretfik.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2mmgngycc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2rdjskvpn.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2ucarynbb.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gt2cjqkonez.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcyjtfkz.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nuulzxgf.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqgburps.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2yihulbnh.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2iydqrwpc.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2jqfobuap.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2xqrjdrbu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdaxrdaf.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2bcrptkpa.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twrlwpbd.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gt2ctkaugrz.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2ezgyjnxu.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gt2ahqtryob.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kexghujj.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gt2hdmwnaum.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2nilsdhyq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqqlulaz.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhzenne.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2gfgwdiju.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2nhgpdhca.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2djvgyuzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2ydrnaldl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2ypfqsqwx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2zpgnfatl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnznlvsd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2mlrlhakn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gt2arntuiif.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2vqvqxyra.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2difimoqv.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2rafwzrbk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gt2gyuyockt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ugbksyck.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2ntuqncyu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gt2qgavgvcr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2tgfcdajy.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gt2tatvlkae.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gt2wqdzsobi.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gt2mmidwllg.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gt2qxjufvtl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2wpbugebr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2eswkmhnu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgpkoyjh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gt2hwgbjbms.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2funlvlge.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2wlbzfmkl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gt2duxwkdtd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gt2ftmqmcme.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gt2qccwfjge.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2kxmdwbbj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2djncndvq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2ntrezllo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzdfhtmq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gt2xuuofjpr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwnghatm.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2mrknhzwh.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gt2daxetpek.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2rbafolcm.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gt2udzvrwsg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyfibykn.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2btcfmgwn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gt2ivgvglza.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gt2vfkuzprt.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2fkfmvvwp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gt2nzsxdpqa.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2tbiklwtq.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2iawlregg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gt2fdbdlfhm.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2auesqtpz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2eeyiomnl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2kbkiunqm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsejukay.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2minjwdmj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2ybumnlbo.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2ogmocybs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gt2tvurddob.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2pqjpogwm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2hfjulwhq.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gt2wmtxllva.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gt2kfrfnals.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gt2qrnvcdbp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2tayylzyi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gt2xcsuctvs.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gt2zrehnrrr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2orjukawy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gt2tdinjtkr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2oswxledn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qoehtqje.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gt2ndiclhgt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2wbestqfd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2oabjhbsm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2zhmvjvjs.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gt2nmlarjra.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2hhopyryf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2obmtsgnz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2txibnjsk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohkzmylg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2qizyzswc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2yrasnssw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2sgslmras.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmcudjyi.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gt2fqasfnvu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2usyjgpde.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gt2hoawnsfn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2vqscsyjx.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2qnpwclys.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2lxrpewfz.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gt2adhwfdvj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gt2qyafzlbn.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2yfjvcoag.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gt2qhtzuazv.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gt2qehtsbaj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwbtepud.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2nlogcusx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gt2hjwbqjcs.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2weafjzzv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2fugniptx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2qglxtrqx.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gt2bdjembob.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gt2mpkjpzmr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gt2hjodmlwi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gt2uyfmsqfm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2esjyxatd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2rnupkmci.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2nspkdwip.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gt2kzkzrgru.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2ptgemqzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2wdwrjevb.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2wlkzuvsy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2gnrgeoms.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jksqmsqt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gt2coxujiru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2vplwldvi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2hphqhjfv.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2dweyzwwb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdvgcqsp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gt2ulskgpen.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2jvphqczd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gt2sjoietqj.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2ivzbaatc.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2mbdkwdav.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yajmdtnn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gt2ccxhvvvd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mrzxbpnv.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2fcdzazrt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gt2lvhdjqaz.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gt2iaxnpvfz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2tdzzidfs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gt2dkoiewqp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bztaadwi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2dekmndwm.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cytpzlxq.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2pvujjvdr.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2ttfenymm.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2bynxlllj.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gt2zqnulucs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2ldaynuul.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2tbdqmzdi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2mvadlpac.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwmedbmn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2whfdzrjn.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gt2sixfaeli.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gt2umdmuzvo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2tanvwmgo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbemvkds.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2asyrrvtz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jjnpyheh.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2yrycqzda.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gt2ubdbqvhx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2ogjlbihu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2uxfknmxv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifoejbbq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2ekpmsbwc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gt2oybveeuw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2zfvodxxy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2auwbdljb.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gt2fberniqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gt2ptpwjezt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gt2gvmnokoy.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msjtmyjj.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2ujdyaadz.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2felbpwds.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2gzxtqoqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gt2etqlbzoe.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2idcygldr.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gt2nhkfazgw.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2mptdbwis.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2zmblumbo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2vppddihc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyaaaauz.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2qwoqbfcu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2mqirmykm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gt2unpopaur.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qohvzgeh.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gt2uyqxwyfa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2aqaxszcq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gt2mebsgbjr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mssxyguu.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2kjywivya.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gt2mphktasl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2ympcixxz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2vvzzkqwy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2iolxdhfg.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gt2eslqnlum.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2xvwhqbzh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2ktvwkozr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jetrfogt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sccdrjnz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnimkbsf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twjroicu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2anofbpyy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2szsfrxxl.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2hqjbtfdw.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2hnduspge.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2dwmhpzfa.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2eqqbqlob.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2hgzslmbf.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gt2eumpddbm.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2irjtyeoj.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2boolcysk.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gt2qvuqmmwd.html

[D07] 切片 / 取子数组
来源：http://dali.meibo888.top/Article/details/gt2tkjqzidm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2nwllnbqv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ekomdlji.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2ozekchru.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlmeluvs.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2uuwbkevw.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycwbtxwg.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2guqiuyxf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2hicwjdtp.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gt2myolkieg.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gt2ryyvnsjw.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2yvrvmfiw.html


<!-- 参考信息 -->