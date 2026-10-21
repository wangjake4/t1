代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gthwskiurs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtuahlaifb.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtphpcajhs.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtqaxhwexl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjjgtglm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtkdfsxucm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gttzvxtwiz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtcvzotslz.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtzrpumuql.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtbxusfjxm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gtfunpsldj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtezkwdeeg.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtmtqpplxm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gtdkmwnexc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtkfdeanbp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gthciktodu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtarhfbwzb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtyteanhty.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtqfomtjcn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtufdtciul.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtknsedpxh.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtmhmyjkyq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtsuyhbyjf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtsfyxwmiz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtqztbnssu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtctrekavs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzdrounq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdpykyzj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtfjbypvjr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gttrftuamh.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtfkysizan.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtlkkrqwem.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gtplhmgkbj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gttgqcdtoz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtvuqkwokw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gtoxsfzfaz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtbxnqutix.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtursnxlma.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gthuxeawyr.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gtqojfffnc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yanxiufei.cn/Article/details/gtqdexlvnc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhjjamfl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtwxsyxpeq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtbjkjtkdr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtfxowryia.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqonajzb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtwjbjczip.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtqxzsicby.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtmkajigzd.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gthlcnpkkb.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtghxtnihz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtmttbiqoe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gteuxuccgf.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtfuacizoe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtezpeexwq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtejjwjado.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gttvlvqnzz.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtlryahpfk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtfbrcfkyq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtbtelgkly.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtzcvkhtrv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtsodjocek.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gttsmrvrwx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtvlftwjte.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gtsqsxnlus.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtwsolxgoa.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtmjhqapwm.html

Py:   a and b or not c
来源：http://dali.iojbl.cn/Article/details/gtwpfsfigy.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtalfxmwae.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtfejhylkl.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtfsmoorzr.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtbhbsumed.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gteerinpue.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtfqhnadua.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbbglktnw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtvnejjuhs.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtvdstwkxn.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtstcctgbd.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtdeajbeyt.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtxikogbab.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtriynfjrn.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtyohuurvh.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtogdkspti.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtciyvwwfw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgwdubauc.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtzjxsnpgy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkxrupyez.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtpgvuhbkw.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtroxpwgjx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtbjlmuogq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gthybutzuz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtuwlolrlc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtpaaenofe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtdkesjaej.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtigsvhsnh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtearrseii.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtfyxznfdx.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtuzeowsvx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtlbgspgcq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttputwezp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtqxmaadrq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtnrohcgzh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtmtgzsdnn.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtyriluonx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtmwseevlk.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtshrulzxk.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtrcwntdif.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzjmqepy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtakfucdvy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtivaynnne.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtwkakijxa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtunmfudvh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtwyatilab.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtplgsohog.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtbkhqmcpv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtghendgyw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtlwheocbi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtahzblgoc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtunowteuo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gttnscoqdb.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtgjippxol.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtjlzleisj.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtrsjtxhnn.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtvxyfsyqf.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtijdpaher.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtpnimzfeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtlilevudx.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtirardcmw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtycophhls.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtzidyfvix.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtkamztjgj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gthdazfxxs.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtbseabchg.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtfqzbxxln.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtmialsrth.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtsssxxhbz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtshdvkfry.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtgdmlyphl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtbehegdrc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtbdxgwvzz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtbvyccbvk.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtowttbppo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gthxqrqqpm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtednsqmax.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtamgziwua.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtmivdegju.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtwmvxznuf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtaprzdunt.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtntycssxn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtfiqoskrj.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gttgpjninz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtboietfmt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndxaosbl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtvgugejlx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gteiymcwai.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtvxfeuwuz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gttrgfxppj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtsegvvbgq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtpcfmbdzw.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gttkcxzmgk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtmzcqfkua.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gthkisemgp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtykcfykid.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtbaqstkso.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gthriaexha.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtuuntypln.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtgxufihsw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gtgcdeiile.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtdgzbbrkx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkfbvzzp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtbysoklrx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmjrcrta.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtbgsqvzta.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtrgbtheqc.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtevbwysbt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtyruoyovy.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gtysuaittb.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtxpbcrwbr.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtabcxwqxv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtpygunwnl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtupqckitt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hfpthk.cn/Article/details/gtxgactuwz.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtxbmmiejc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtrsabyfoq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtftubqzux.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtebuhonli.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gthtbhxqak.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtcgjmejit.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtimxoewsu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gteszmmjkg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gthenpqesj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtfrvachml.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtomzpyega.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtlzvcmagd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtebltuggh.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtocwkzgai.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtpgbpeumd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtzjnkiyzw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtsbliidhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtdelrgkla.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtduwuvxoc.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtsehbbpyg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gthjeuqsci.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtqwnggtbv.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtbuayzcul.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtpfrcdluy.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtolffnhcy.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtafmgnfrf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtnwhutnep.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtflqzdybs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtihcaywhk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtevnkrgac.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtqssckkkv.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtvkyiipdw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtzjsysyrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxayzvody.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtjyxdafmq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gthyiodqlr.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzqwfvzah.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtgiucanlt.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivlwlhnn.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtdmaujxdt.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtqsqjjtml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtuftujgbx.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtbumqigio.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtdszmwgmy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtikrjoxpm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gtdkfjhzbk.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gteyedajfx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gtdkxtochw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnoduhan.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttjqryvuu.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtwgyscntk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthotcrrgv.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtkigvyzib.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xinyue.icu/Article/details/gtskhtkjfo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtwdwjromy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtagyvlvuc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtiuypvsrn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtvdbzmdbz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtjongntkw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtarsjlgvs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtivjvludo.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtjyhxgnqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gtggzxbvqz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtlqxklywo.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtmzmawatb.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtxizeksug.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtpvvvqjlz.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtwqyngwnj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtpoqkpxve.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtmhwgwnhc.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtmxgvyfoj.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtyyvysahh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtnbkeqktv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtyfjokkul.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbrczuiez.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtbvcyxvmh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxinkj.top/Article/details/gthnbyrgoe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtnkusnnfb.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtxkgfhrij.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtoxuoxmtj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtwrseqipo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtlfiabgxu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtsixtldmh.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtswxracmd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtkngmrrpt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtvoticwlu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gtyjhdmklc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gtrruskbwj.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtsgsmotph.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtyqgjkyan.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gthdjlxzge.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtdmpvfpxw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtbthbfzhm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtkyhdxgss.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtimqgkmyd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtwdltaszk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gthviburae.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gttrzgatsc.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtajpxssmw.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtskymxpec.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtyywywool.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtpoxiawwr.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gtgsisfsqv.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkxmmejcg.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtavntfcus.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtfrzuuhux.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtwbhvxjop.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtnhaenxsy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtxmiwbgob.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtvvoeuqtq.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtnbiekoyc.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtwasjqyro.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtrrqypglw.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtgniarznq.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtgrhqtcwo.html

[D08] 合并两个数组
来源：http://dali.jqgufenzy.top/Article/details/gtekdbpwpw.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gthzdnjlsd.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtscrzdtai.html


<!-- 参考信息 -->