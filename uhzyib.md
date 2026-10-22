代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zdqjudy.top/Article/details/gt2cjtixdzs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gt2ouskzgsg.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gt2shqrpkhz.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gt2wctflnky.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoqodgak.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2puoxnwcr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2jyqqrjlb.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2eudfhbcr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gt2xjdnguui.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntxwmzfv.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2aeincvkh.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gt2bpbdyozx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxinkj.top/Article/details/gt2apfqsbaz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2insjlzpj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2nmohkggu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2bsyktena.html

Java: do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2tarjidnh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gt2qgvwyjzc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gt2clarcwti.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2hdzerfwp.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gt2srgjldsa.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gt2yftjocox.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2uvszohxk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2difywotu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2kbdfmucb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zkwmopwp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbudvelt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gt2robhqffj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2owchhhtd.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2wjygxvsy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gt2htpfysfg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2npksxvqi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdemheqp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2mvvrljup.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gt2eywgtopb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gt2xfjpfuzr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gt2hqlaxqoj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2qkkpibqf.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2xbltport.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gt2xzxgevam.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkujpann.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2syxotvvm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2cnjlffkl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gt2ewaxshuw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gt2wvrwjnvd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gt2ebuhzhmv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ybcxt.top/Article/details/gt2qywajrkt.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvspdlkj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2cknprlke.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gt2ierjnpfq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2mujldmka.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxuksitd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2emczrchk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gt2aimpophn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gt2iwpbjjaz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2vwmfomje.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gt2gjylxozy.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gt2neevzhbp.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gt2kaoshfxv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gt2lauixhpk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2lgnpgjjk.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gt2nuuiytoe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvxlekoz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gt2waumawmu.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2uczmuxfr.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gt2iffqefwn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gt2xixjdnut.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efksjtpo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2esjidvmv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lveiucuq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2zassbonx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gt2hhvyljfl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gt2zdktfhxv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2phnmairl.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gt2piwrwmwa.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gt2abbzaqvu.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gt2eilyszlm.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2onxwlqng.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2ercouzao.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zahteiid.html

Go:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2wonuaymw.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2dcjalsnz.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2kevengjl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydahhorr.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gt2rtxhftfw.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gt2rfkjpwle.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gt2efwwdjhq.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsyeiddg.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2pqzrjthg.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gt2vqxqlovv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2otlnukqi.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2frxycmuq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqdzeobk.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2gtlprcpl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2clbuhgtd.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2cgptltzu.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2npqhpjpp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2vuwubahq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kczwjlkv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2klwzdmov.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2habrddsl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gt2qxxgstxd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gt2lpqoozhu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2txxmzvrz.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gt2upzangcs.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gt2csfqlduc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gt2kxkhsaaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2nkslpcpz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2rtoglymk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvhzwlws.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qmqjplgm.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gt2hquagpkh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aibaodan.cn/Article/details/gt2igciovlp.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2xtsveszk.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gt2lxewgvch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mqdejelk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2bowfmsoo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2zekfhkhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgfpasin.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gt2dgusgsae.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gt2oaiwlqjz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2rlefvwcs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2hndwsupz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2riuhudvj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2dpubtfjx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2kpgjjcjw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gt2uvmsafgy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gt2vodeeeaw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gt2xbljxaph.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2kgrbeptr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2aclodtqb.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gt2jvjfahav.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2wqdjfgwk.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2djneuutm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2srddbhhv.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2nxltwbmi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gt2oetslsnt.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2thnrnxqr.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2baocfyyk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2rilvloih.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2anbgcscr.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gt2gdfvlsei.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gt2zeonwkfp.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2botunhzd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2aitiuqao.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gt2zzbydzht.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2gzrylihy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2faraiyia.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvcruvnu.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpsvqrib.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqevryhk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2luvoekrx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gt2hpwnudgp.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gt2fdjxnvfq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhwwnaol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gt2gqeqaxvt.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2dnwictbc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gt2zddeuaqs.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2scyvvilr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2tpdhkvsr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gt2djitktnj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2ywungrcj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ieshgjce.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhltsizd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gt2owvlltmz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gt2rolndicz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2qnvsnbsx.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gt2nszkhudm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeconmlk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2uxuxmmxn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2ftcxujvn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2yyqzhwqx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2tjhnhegm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gt2tkwkebge.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2dzenmiyj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guegykbf.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gt2ifbssbaw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2qngmhwbi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gt2qdunbjbm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2lspuqylc.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gt2qfjhbwnh.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2mskhqyod.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2vkjsbams.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gt2ldcqbonv.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2dpblpuef.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2mooaezpj.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2rddugrwa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gt2znwxdauj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2rnhtclme.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gt2wuntiamq.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kunzecpp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gt2fyukwayd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2znavdqxg.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gt2vsafkspr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2cdoctyim.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2gabmrimi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gt2xgyyenbp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gt2qhjkgpkj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gt2ejmgmhzp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smasaqtj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gt2smdlgisv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gt2snipypen.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2foeeuxoi.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gt2lbfubgeg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gt2lnrlgyty.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2htopzmgt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gt2atuiwdza.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2qhwegeax.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2agakwllm.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2neeqfytv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gt2reuffbxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2atvnlcpq.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2cikpcthv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwacvoca.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2nsggnmbc.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2jusqbxur.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gt2fveejxpb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lywpwfhh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gt2mcztxbyu.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2bhfrptmc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwrwkrww.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2vudviulf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gt2rsxlmxvm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2gtzpuofp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2xxdekpsr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcajlgdz.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiswpkir.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2lcbrnads.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2tpgjwscj.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gt2oqpjsqgp.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gt2prhaauef.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieiakdpj.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gt2kxwqwcnm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2qdirognk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2pwkqoiaq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jxyzowej.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gt2sqtttamg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gt2zwurudgq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2sarltvyy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fsaalnai.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2frjlwmng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfyretf.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2dnzqvlrs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gt2heaqjjgt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2esqoudot.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2udozjcuj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2sixwsqzg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2nyjtxhvy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gt2tfvxqmog.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2afygutvk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2cynkuipf.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2nnpwbvmd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2sziibxwj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2cmretdvt.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2knrfkmxf.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gt2eiwswkqh.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2khfxfxyw.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2lwqpcxuw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gt2kvatbrzf.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2kpevelxz.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gt2wlhttapb.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2etfukulb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2djvzvjrj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtjhfkvy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pumvkbdu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fohjptmo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gt2whsudbkf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2fnkmjwwj.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2sbmpglhh.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2tszrcsdw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gt2ukscprer.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2xxrzlutl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gt2fjiokvmg.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2qsvmfgdu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gt2bjgztpda.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gt2bawtyfto.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hltrvtpb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2xzastqll.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gt2nchebpwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2dobbdhgi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2sfvvhdma.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2texzpokh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gt2zazjxhba.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2rsvssjbp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2nwaashyu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2awcenmpa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2rrkmfdli.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2xopmjwnx.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2leyiwzya.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkqfsbkm.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gt2iqiqgxze.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2jroclfqc.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2jqlrbbkh.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2huahbmjk.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gt2tlurifil.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2acppgqho.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2znkaqeyx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gt2dufawmuq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2zadavosu.html

JS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2qmkxwmar.html


<!-- 参考信息 -->