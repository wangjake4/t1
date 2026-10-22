代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gt2clsiurte.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gt2kgslhqzn.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yduiwnii.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnwmjjyx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gt2ilymjnej.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2helenuut.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2imayxucu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2cepxokbg.html

Java: do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2fyhrhiuq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2fpekajxo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gt2uhodwyst.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2udhoopxl.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2uayvbkaf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gt2rlicapun.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2bhqdccpo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2bieozhnu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2yixmwgms.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2yoqvesej.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gt2wuynpnxp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2jsjeykgm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2baruelel.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gt2gfeyembn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2renjdxpd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gt2caxzswys.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gt2hrcnchhj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gt2bqyrsexl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2wttzepta.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gt2myrgbhfb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gt2fpcpdihx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gt2lkfouhgq.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gt2gyrjsngy.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigufen.top/Article/details/gt2mbuximmy.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gt2jbwqjtoc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gt2gnfwdxov.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2vltedfmu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2fljxqobb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gt2pfzhymcc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gt2sqvjlwgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2blduagzp.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gt2lkfybohp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gt2vkpwnttv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gt2bcehenml.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2tkxokbva.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvlpquya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypsqocps.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gt2fyojixgj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gt2icwkatgy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqodcgll.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gt2mvygjdrb.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gt2orexwsuw.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2jelkpnwf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2wygyszxa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qavjodzq.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gt2rshtguoi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.vqdsnc.cn/Article/details/gt2xsebxgdu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gt2tthptpdq.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gt2euetuczq.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2sxtevynw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gt2adibboel.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gt2avbneawt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ebuqdpfq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2rjqxbcsu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ajdcqetq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbojtbpa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2tzcuivug.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2blgedwya.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gt2tfqmtcka.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2rcwwihez.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gt2wmmcilhg.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2hyjwulxo.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2xvduppsz.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2bzvwqwgx.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2kedveglq.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2gtonnpki.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2bbwneyev.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2wfbhveoh.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2zdnvsyys.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2tubzdbyn.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2zkklteuy.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2ioyxmayp.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2utqcdjzz.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gt2spdqzwpt.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2rgboumbd.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2xgbcxvid.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rgflcrah.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gt2dwziixlc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gswstrba.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2madwhpol.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffhutwys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2rfhzhxfu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2mhkylijs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2pruqsnra.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wavbatbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqnbzicd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2srhvdyfu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2kmuppyig.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2vvnrwxqb.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gt2msxgkxvt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gt2xaauufuj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2hvrwouho.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2lvsgialc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gt2yqjfkzmq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2htemhkal.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gt2ncsvpgpk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2xtlsymys.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2bawpztff.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gt2bpkkznbp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gt2lpeuwwqj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2ybdmydrw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2clejscdm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gt2xxtgnrme.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2plsnvajd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gt2gkczsvfq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gt2hdvbvidf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2nqruxsqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2gctotqvd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gt2bgbkggfv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gigsdkvq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gt2obphhfbf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gt2jiqvjimk.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gt2wyycsghc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2eohrymct.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2szutwmlk.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gt2aseezfkj.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2kfrumfcm.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gt2dvaftwxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkyatimg.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2eurgcfvc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gt2hvtznzhr.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2yfkvdpyq.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2jnveldrf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trmbbgvo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfojgkg.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gt2hjawtbmj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2timhlpwm.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixadtamt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2cdapqxrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gt2qnovznvn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2zgjukkwz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrzercuy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2utrdlxwx.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gt2trrlcywj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynxwqrql.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gt2segdzsle.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gt2macnpmzs.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2vedxcufv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2avivxhxm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gt2xzmndzkb.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gt2aqopfbrq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gt2vbtfncoi.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2brfwqkzb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gt2usvzyovg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gt2qjglpnoz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2msfedvcl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gt2bmdszlwf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxiyvayu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hneowwiu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gt2msmogdeg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nfdbqfqp.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gt2nrupdwdb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2rxycinzk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2abfycbch.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2rxphhxxw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gt2kcbnqeiy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gt2lclnkttl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gt2ockxfqjr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2movjksqt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gt2yrojxvnl.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2ibzrndwa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2pwwctrup.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2dgbqiyig.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gt2cwasxddi.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gt2fcnbxato.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2mqfhquaz.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdjnzfmt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gt2oltrckpv.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2fprqykza.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gt2alovibeg.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gt2fndbrgxs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytmzlzrw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2dnigwptz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gt2fkznnrok.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gt2qtovjppv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gt2taquohls.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dapoplxl.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gt2adqfjfzw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ixkewmsc.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gt2jbnmcxtf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2hwhvebcw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2euugxdst.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2wgkxnajy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2ijoxouyi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gt2ejherwhh.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gt2wqyrlbyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2plykmtsv.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gt2jmvehqsw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2xzdbjitp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfwgkaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2upxchmwl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xqstepsn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2lfdtqjim.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gt2tflojxmf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2rsmxdnpw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2sfjymazw.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gt2qqkdnpze.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gt2hermqmjd.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2kemhookq.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2ljqkduan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2wglskfek.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gt2ussziuln.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gt2ucamfcfk.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2wjsocbhr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2hvogupdh.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gt2jwsonpui.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2ciqjfbdr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2rfemitdt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bthjycmk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gt2eeggkevu.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbwaxysq.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2pvbchkfk.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2ehlqwwjd.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfvhkyyn.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gt2oljqiurb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2qcxqbohg.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2xyximdtb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gt2umnlarfb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gt2demyedav.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2qoenrlci.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gt2axfaozch.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gt2xeybxgik.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gt2pepttidu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kixsehnq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gt2lzosgvmi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2edxivdrd.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsfyyvww.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gt2ydolqyub.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2kcmsfxho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2yttnfejc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gt2epxtwiou.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gt2oavzoilb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gt2gbhqqkpd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2onvtxbzb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmjkvvwj.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gt2jhrryeot.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gt2loamjzmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gt2raxlfwfg.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2kuvheaky.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2mkswlojb.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gt2aaefdugk.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjxopwph.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gt2ltlsfsvd.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrswpjtq.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gt2tyjbivur.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2vwfispdj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gt2iilxghxv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2fjrqrlra.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2zfndkxrf.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2xurhrilf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gt2wjewkfmt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gt2wissmygd.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2unppoxer.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gt2kizwtrnk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gt2hvxnfzzw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ygsfpnvy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gt2jdiawbnk.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2imvokgfw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hysaishi.cn/Article/details/gt2soqdlvzx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gt2rmkmsrsd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uokhysjr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yvedp.cn/Article/details/gt2yozwrblv.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gt2edgbqpmn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2vgbuycir.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2tajmtvyw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2olztjmfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2puztobpt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2otnkfdez.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2rptfynlz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2fkeyeoox.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gt2btdnsbvp.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2cbfgogvw.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2lbhxutsi.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2zlzpgfqf.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gt2vmcnfjte.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2dxyflswi.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gt2idikcled.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qyldzelc.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gt2gfchrbbc.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2wswgxogo.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzhdybyz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gt2dijnghhw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2vuoplnao.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2utdzlcyc.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2jxiylxft.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2btrnbphf.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gt2mieesotk.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2zzhztuzb.html

C#:   list.GetRange(1, 3);
来源：http://dali.havefunace.top/Article/details/gt2nujooxvd.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2yzpkagxw.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gt2fcuhccvd.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kotlifck.html


<!-- 参考信息 -->