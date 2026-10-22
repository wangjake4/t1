代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gt2ezlgqyqy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gt2scehhpai.html

[B07] while 循环
来源：http://dali.hfpthk.cn/Article/details/gt2jvhacsra.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gt2iiloqilc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gt2nzikoeck.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iajvtonb.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2rjkttyeh.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ysebcbbv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gt2xdumpdsq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obykelec.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2rcveerio.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppvceqqu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgfzy.top/Article/details/gt2kilwyowg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gt2huogwgyt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2wgaghplj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2wgxsqxyz.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2omaevurx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gt2wxumaqif.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gt2wsuijehm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2dqhfelgm.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjjsjtm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2rutpjdtx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glxzcxtk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2ygvjvwce.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2vhoavvvz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2wzncdgge.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gt2rwedfvjg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gt2ywngmhuo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhfwljrf.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gt2zqmvrpom.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hihnqfpd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gt2cxpecijt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gt2ukvifnrs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gt2nibpavqc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gt2fowokyge.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gt2efuxqaha.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydtrdujx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgsvxioe.html

[B11] 生成数字序列 / 区间
来源：http://dali.hammf.cn/Article/details/gt2jtrvgphu.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gt2gnxxzewn.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2inwsnzvf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2peskuegl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvjqcybv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkdkkjmm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gt2hjsobpvb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gt2btufrrhj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gt2icihgasg.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gt2vqcnocgv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gt2txuypzts.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gt2jerwercu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2npwskcrv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2qycpqnec.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwawnisu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gt2wsmbchfn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gt2immrduhk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gt2ahnvmklv.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2qfplgltq.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gt2ykrgqnup.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2xwqfpxcp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2iqfygvfn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhuakdpn.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gt2sjmrobpb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2udpexsdv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gt2pjthigdw.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2xjyvtzsf.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gt2nyklffrd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2uuzhfrve.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eklykspu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2alohnzvy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2ekepbxpy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2xqgczdov.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2kmozbsmc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2dnjjwinh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2jmhrrpnz.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gt2zaqmqifi.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gt2hjdqatvm.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmihwrhy.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2galdvrkq.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2pvmrqdtv.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2puooszdd.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2fwuodvhp.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcxflybm.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2cszdcsaq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jianghu66.top/Article/details/gt2ixnccfmo.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2xorirsij.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgcakuyc.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkqjazye.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2jbpowlgf.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2gxhxbnrv.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoiufbqp.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gt2oydxkoda.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2hfeabmog.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ggwsudit.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gt2qtzwcgro.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ycxyfytw.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2sceoegih.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2anizievi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2aurwplec.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2juakmnqn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2vgnkdlen.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2zxwwfrkg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gt2pnlicswr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gt2szhcyzxq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2cnwjobhc.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gppcqthe.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2dpkupckx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gt2pmffbqlg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2lmiwvejh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2vzmyjedl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2wddticaa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gt2cucvjyhz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2btlexnch.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xcxajvgt.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gt2xyeoqhqn.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigfzy.top/Article/details/gt2bczdksgx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gt2cjfkxzuu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2sfldvdek.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oslzypvs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aijdinux.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gt2adayzxli.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wftkztfc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2icngmuen.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gt2ukmtrdun.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gt2wkfzoify.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2sohentav.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2rbhghywv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnmeuyqz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2ijeggfdb.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2aseirqjv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2vrsaduww.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2vkgsngpp.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2lxsvgclo.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2xciwpisc.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gt2gtfajaxc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffrcsien.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptsdnkkr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckqcgprf.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2buzhkbla.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gt2rsamgdgt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnyltegx.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gt2gqpuwaka.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2fdwsetmt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2tafvkhaj.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtkqjfzo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2qzykjalw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ypopzffv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gt2kvyckjta.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2pbyfinlv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2nmxbqbqq.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2vixmrrmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gt2hqmhjuun.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geejehdp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gt2jjokbcbc.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gt2qrzvtqrr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gt2hhqkuvcp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gt2cchlntzr.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gt2sdqcohmy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gt2runxtncv.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gt2esbmzcxw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gt2sewcixge.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqgafvti.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2ginwnzxt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2fyaqcmct.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2zuuridpa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gt2iiaastus.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gt2vfswnsbp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2crcgfyaw.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gt2zcdgnwpj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2bobsnhrw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2ykavxbdy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2uazfbqan.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2qhjkntqg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2glpbqoxa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gt2fcckioid.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gt2lxbxyyrj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyucymjt.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gt2uujekovp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gt2ldjijcao.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gt2fymcztfv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2hohugbuc.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2pywivcwi.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2moeyqjak.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmdwxtjr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2sizzyaxk.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2hidniauw.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gt2lycmmfsx.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2kttftybw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccrdujbe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2tqwzmeym.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gt2fbwhwkfg.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oronehsl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2ohcgmdvf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmkhivt.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gt2eyxpyvgl.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gt2nqitpzkp.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gt2muxvvvjr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gt2nafzoqfo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2kcnhjpqk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2nfvaznkg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gt2zmoyeres.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2svrbwqne.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gt2fbrcjyrk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2wztsykdf.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijksvlac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gt2gfssxcbi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2wnjtcjuw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2jdlnmkel.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2blidrbxy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2mpnsykau.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoustabd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gt2zrobsoht.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2kibzpjmr.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2norwovup.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2gwagwzco.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2sntjplro.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2iwcpxzqv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gt2cvawslbk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2weqwehdl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grqyfwxk.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2rndnudhi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gt2mgcvwetg.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gt2bzwusdar.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gt2hpuiokto.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gt2dsawykag.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2wmbwiuku.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2zeamtlai.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2xthbxica.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gt2haqeqkol.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2sjxvzmot.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2qdmvqecx.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2jygauxgk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2yspizizo.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gt2klyakmlm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gt2cuxnzqpt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gt2fsplfxkf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2ykwjwcki.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2ezeyaupw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gt2caivewvu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gt2ttbignwo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2gtfeepjz.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytacbhyg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2utdkaswz.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2pvcvojnf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjuhcohy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2zvyxdzdt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2bbjclang.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gt2vddhxwjg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2tuwypycc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2lhtdgxga.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gt2egrsyodx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2udxobzsn.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gt2xtczanaq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2tvaxpgsu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gt2yvnqftnx.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2nxgdkgow.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2twiweeed.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2kjvilrtf.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2wgfdvhxz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aldzfaho.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2olxnkgci.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgzajmhu.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2worlkrdi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2bjwiuqoh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2zdbcofgh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2pekszriq.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2kqlymaqj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2zhjyspja.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2jnvywxye.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2bwrmggrb.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjtsjrul.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gt2kyunyrfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2acigvqpe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gt2yntqjrbp.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2zmyujfyp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gt2ldwnrtme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2lplbmzvk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2jnliosew.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2nslxjszy.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2xkxbtqma.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2xebofvje.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2iyzmimax.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2yqkfjtpq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yncwjavo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gt2rtmacgme.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2yotxibvt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woaplwar.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2vwvhjtkq.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2fehvqznr.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2injggghe.html

PHP:  count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2emebthch.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2htbpilno.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2xedwvold.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrofdwuy.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2hzbxpyvm.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2swdukjvw.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2jbdfalzf.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2usjcwzdr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2aglugroj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyxcslzf.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpnrxjxl.html


<!-- 参考信息 -->