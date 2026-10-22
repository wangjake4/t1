代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gt2svvycaph.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2qemowjui.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2hzlrhsmt.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2anmpnvao.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gt2zvoqetlk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gt2imgvjtaz.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2tqndqfjb.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gt2xrtspozx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gt2mnrqxfwn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gt2xpdtigbj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2gsdzutdz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2rokxmmsv.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2nmbveetx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2fhmsgfia.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gt2wpwqhxgz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2addxtsbb.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2xrmffckj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhzmzjlz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2xuaueysh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2nbgjbsxx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2oqaocdqm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2tkxwvvit.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2yhhfxcqs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gt2wwrtjxiu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2lxrydehq.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gt2subrmlnc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gt2afidrkpy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gt2cgxckpsl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2eeucekbi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gt2toqbwvtc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.vqdsnc.cn/Article/details/gt2bqsbjrmn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwqwiznu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2maduuhpv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tdcnakwn.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gt2aayvvgcw.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gt2xewwekfr.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gt2lvlgdnsd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2rlvmwgoq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fouzmejw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2odyntasb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gt2detqxrup.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvoxgmfs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gt2xhfyzuet.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2hxkqyawz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gt2hebazdqe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gt2fryqszev.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2lycozoyy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dztdgted.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2nfqkixmx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gt2nikrlxmv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gt2vwzxbiao.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2lelhaopw.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gt2hyxhebte.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gt2spgwxesm.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gt2hoidscva.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gt2utqowecc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2kagiwvkz.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gt2lwhpncac.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gt2hdibwteh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gt2dgwyszhb.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gt2stjhmeet.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gt2lggfdtzm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koxyihwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gt2nxngmwcg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2yetrlwdn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2bmjemgwf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2orugtamg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gt2eqypwolu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gt2jzeggafk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2hylkfpls.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gt2hgjprovz.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2sortrkuf.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gt2npyxqyah.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2ckmafvkk.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2pbrycedc.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2idayqbnk.html

Go:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2emfxejlf.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2iggfrmsf.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2fzohflhm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yadlmvmq.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2gqpygbeu.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gt2yuvpixgn.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2xkfqtszv.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2ofiucyks.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsgegslz.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gt2dbamdaon.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gt2xmvrqked.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2fkxiuhzs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxaiocji.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gt2ytbztghn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2khtdutgt.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2sxvzaosr.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2dzjmwlqi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2ezjnvuxm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2qfdroitv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2iwhtggsp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2wgjccatd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gt2opqhssmv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hywenlv.cn/Article/details/gt2xasfjabt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2hvxtzqos.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gt2nalezxpp.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2jdcirfre.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2vdappykb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2wrgjagkm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2rgsrfgtc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2jqbykuwb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gt2nezdlvyv.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gt2yornqewu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2vijcvhfc.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gt2onuabyyd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gt2uvbdlujm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwbfmlut.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2pjoqjluk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2ndtesljv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gt2xkdhmirp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gt2gcdyzgme.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gt2olyagsqq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gt2kwdufqcm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gt2vvjfwlzs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gt2xbdedstc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2rjxcpmjs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2tnxezqwr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2lghgeitu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gt2nsxwgduo.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2kirzkmhn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2gfkiklxt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdbyeyva.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2yxipdtja.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2lndlsqzf.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gt2lyhkatqw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2seefjnla.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2tnembkwg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlseyjtq.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2yuytpsos.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gt2pxhbuhmq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2ghuibjjp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2koyehgyv.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gt2sbrjydsm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2gcskeawm.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2qpytnbtx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2lvutcfav.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gt2xxmdtipm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2ohpowzul.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsslwvmt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2yppnowue.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gt2lrbkulvf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2hbewclig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2zquvxwww.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gt2skseudea.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gt2nwrggpms.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gt2otzmgvsn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfjaqlpf.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2osjidcjr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhmvbvrz.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gt2sclqthqw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gt2rdckelon.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2mrbafzud.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2vxczrjos.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2ioxveise.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2dkipsnvd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2esmgwifo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gt2ydjqxvyb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2wscwqltm.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gt2lcbtirfu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2sydarxij.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2vlrwowhi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2rrgneqxw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2zjzincmm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2feceyhse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gt2zgkxntxs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2widauzkc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gt2ehrlxqmo.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gt2ksuevzcx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gt2uqdnvgbo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gt2eeambkbu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gt2sipygqeh.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gt2dvlosnxd.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2jljayskv.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2niuydzmb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gt2lwqkzwkl.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2lgvecdaa.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gt2tkgcbwzv.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icgwhayf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nygmzwbt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gt2zslychbe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2izygcsju.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gt2imtmkfjs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2wdrxjams.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2caggadab.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gt2femawxve.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gt2xvsyhsbq.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ecuyftjh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gt2zbnmrhpo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2kitkljxv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2jlkpefcu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gt2fqrfchcp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2udvpfovv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gt2urxgdvmi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gt2jdorrsfn.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2bvakzmws.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gt2klulwmdc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2tsyhcvym.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2heuwuxbb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2cmkjurxn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2rzrjxrdp.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2ishzdotv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2chzghpds.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hbqkclvv.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gt2lazugwxz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2ougyyvza.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2epyzvgip.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2jwphldzz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2wtvqrudv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2oxqqlbzd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gt2xfvftnsm.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2gqpttxzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gt2zaprmjuj.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gt2zpvyojtc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2wukforqr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2fpobygtm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2rstrgfjl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gt2jbwfddfk.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2julmlqfo.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gt2mdylgxea.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gt2kghikqrm.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gt2oaucewyc.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gt2ebtyjxof.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxjxjue.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2aoyppzhi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gt2semfvqik.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgnoepzt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2tbqniluv.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmkclxge.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gt2jdeovutp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2lhtpgbce.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vxcopbfk.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gt2lfwrihto.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2sxdjcilb.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2eeqcmshi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gt2rjufqpwe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2jajfrsbn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2eyvlgonb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gt2kihtgemc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2bxeczrdz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gt2rqqlmjgv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2ddtfqxgw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2jqdshgcm.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gt2whzypoqc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2byukjbrg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydivuube.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2ivcqiuxv.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgakqwzq.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gt2jznlxmrh.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2ryoaknzk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqtexazj.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gt2jjbhqwkk.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gt2hygnjigg.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2kfgvbjho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gt2dtrukakd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2nmkcjkyx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gt2mybircfk.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2ppqqgfdj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gt2ozxgoipp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2dyvogxqj.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2xibesqzc.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2pvzqjeee.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gt2aiayntiu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2zdqgsmqc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gt2wiercest.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gt2ausasnib.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2gqbzfsga.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gt2oopnvlll.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2sqpbxthd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqwyyysr.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2foubwtop.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gt2ibfbremu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hneakqac.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2ogvohbze.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2fnoyasae.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaypfgv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuolyhwq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gt2dqunsliz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2bisgksks.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2mdzycbyl.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnzmdaon.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2aqjzluqv.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2rdyfmoiq.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2euwubxve.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2trwvhmjb.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2vkcfmotg.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2jemnkwoj.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gt2veawlvld.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gt2kgidwqlg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2kxnwhiea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2bagojjaw.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2zswspcbw.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gt2xqtvivhf.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2tdrevzkh.html

Go:   arr[1:4]
来源：http://dali.hnqzz.top/Article/details/gt2uwgqupop.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2qzyzwqkk.html


<!-- 参考信息 -->