代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtmvehiutb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtpaaoksip.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtbhgiakdc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtfkerwskd.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtkdfncbvi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtbljszwol.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gtvwoemunj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtwnisqptu.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtgpokswla.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtppgofrvx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtgtupxfhy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtaubucpfa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtowcrhwxp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtfdlkskxi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gtopktubtf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtftfpmedh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxgdfbbz.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtceotkqdu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gteytfgnbt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gtuamfuewq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtqicmyfov.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtmhisxwls.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtmvjbljty.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtnzdttpme.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gttsdcfxaa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gttojcnegp.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gtocshtklx.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtgiftgloj.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gtwjhxuawb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gttgkyqjyb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtdpckldbq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvbbqbigt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gttgoqsqky.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsajtzzrx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gtoklmcuzo.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gtpucyyywi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtizauqunu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gthpdrepko.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtppihilys.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtiejzuwzi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtvrvlcmlm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtovadoyvr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtmgznguac.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtizhtctkm.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtqqxlvzxe.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtcsqkimul.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnizfglgf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gththkqxqu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtonxbdvoy.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtydnjvzij.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtmodjnupt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbdsqyvd.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtyflxymhf.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtezrlbvxa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtbqxafmtv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gtidlrzssm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtfbnucvwj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtspqjrcwg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtqhqxwnlf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtlhfanzmh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcdqlwink.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtdmnyonnk.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtzxljoguf.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfjelqxj.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtkjbtmbct.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrgvvrmgh.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtgvdiitsx.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtgcyxfrmw.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtctmbkuyk.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gteiioeaen.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtlargtoco.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtlexwurie.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtpxhjdjxt.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtkejfprci.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtdfefskic.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gthbzyhvxt.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtvmhvdpka.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtngqpfeqj.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtqdjnctwc.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtzgfriuit.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtghvqodpo.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtfnbkulbb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjijqhwvl.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtvdmapncg.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtaaeieyrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsgwrrvy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtrbmpywvu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtxawtzxrr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtbumjxvms.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gterprcpkd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtekpbgaqw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtvikgqgam.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtrrzjqwoy.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gtcncmliil.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gtzlxoggxv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtvdlbalzs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteubgpkzw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtnxwnrkja.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtcnvwecon.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtcttqgtfo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtwggjqicv.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtfacvvmol.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gtubryvaln.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtvilmeavo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtzutxfcot.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtowrxbluw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtqekmefyr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtlqbimmcd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtaapznapn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtcfxacbnv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gtqrehpgvg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtvlnvxgpr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gttlhyktye.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtulhgoraf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnjllngj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtqqeqdsvp.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtarzkivkk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtavtxdkyv.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtexiquqbn.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtdwpepwwd.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtuaqqkzhb.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtooocshkg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtifmyssxd.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gthebovevm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtterlsosp.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtjaqttxcy.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtzvsbohab.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtfbgrvtan.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhsrxmaq.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtbyyrdoue.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtormzkejh.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gthlkqlyan.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gtgpmnnpsp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtqjblspfr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtvdyvjmnw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gthhpoidxi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtvtmjpktf.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtnlrmbvps.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrgwfdwb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtqaenpcnp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtgddzzmfd.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtaxtsmslu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtongiyujs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtykmlsooz.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gthhfuqkrp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtrxnohcbv.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtqutremst.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtzsupplyw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gttqxpmfus.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtwhluaksh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcggdptwt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtxmflqjsk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtohymljdf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gtitctlwot.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtabovaltr.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtrdqnpwlr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtvvdjnzas.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtfphioves.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqghbsdh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtbzxhdkpv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtzhylnoie.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtcacitnxc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtcibnftth.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gteejtvhay.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gtwzrifsyb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtwwyzvggm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtcxfegknp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtnrwzvwdx.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtuqvutygp.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtpnpgxyfk.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtjdqylgdl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtlgphfzth.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtywedemum.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtnwcyjhez.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtlhloxxtk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtllrojbfu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtamhknjio.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtxmjsabkl.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gthqslvoyg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gtbhqzuajc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtrluvlnjs.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gtdfimwalh.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtjnvlryxm.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtopojcwwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtcxcduuur.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtfioeysnu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtzclgpoqk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtxcicvjfi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtydoiympm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtftibxxhc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtzkktdiwy.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtutangwhg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtcautpdjw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gttaqegfhu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtnfariosq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gttpdtperl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtqbxfizfq.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtezvabhoi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtkbbjvzpt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtputoatvp.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtuwzpdstu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtqiugcmic.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtpzpjjavd.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtraiirbzh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtoexioxfd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtcozhmhuc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtgegyaubn.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gttmotsqur.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtrbrlyzzq.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtlyhjqmpn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtfcjwqrfs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywpvjjki.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtppdndzzh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtexdwsqmr.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtmnbssjzr.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtbpvsjjfs.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtwkavdglj.html

C#:   var (a, b) = pair;
来源：http://dali.gaohongyu789.top/Article/details/gtgjbfotis.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gtckoucttr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gthmgxlmju.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtjmmpfmbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtiaihfgll.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtguxecdbe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtrzbywnpw.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtddgtbfvu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gtrzelrtux.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtgustiigf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvgckjeee.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtiidptbtv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuwqcwoga.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtitckamiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtluafeekd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpadbtcz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwluhdgd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.feifeiyinyue.top/Article/details/gtgjozndhv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtrjbamzbw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gtgxouuhbp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtkbsxyfch.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtimwhbagb.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtjisakhhm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtkptrnjpn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtochqnliy.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtenvliwmv.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gthmktybdp.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtmqghheac.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gtlskwcfgz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtignreskl.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtohtnkcyv.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtowxfldbq.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtyxwrvoua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtbplhefpg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtfhdtgapp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtlltueylh.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtrlryezsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtnaurocdm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtfehzemst.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtbreuhiqf.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtdrawopvl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtialmurox.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbedlpfmp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtkkwgltqx.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtycfeuuik.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtekqyrlik.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtabgxspoa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtxkheisvz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdinmcxfv.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtafjpeoez.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gttewuqyof.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtmtpvxvzl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtiwvhhrtx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtwzseueze.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtrhlhpkmi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtzzkkwalw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtcmbiivlo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtylrratiu.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtlaagrppr.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqtiqkvkz.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtkqfbgore.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtumpmsprt.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtadvvkzpo.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtlqgzopff.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtfwtuubzi.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtzerzqpmm.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtesgnlipp.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtxnabngyn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gteocbielu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gttxbapelf.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtuhznvduz.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtkxninrnx.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtvgwqivnc.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtnisuoxyb.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtcgoxkkns.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtfmayljex.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtdilvypaq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcabhbhr.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gtkeylspak.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtyrapfpyd.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtgolvicqy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtppipybzh.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gtujewjoss.html


<!-- 参考信息 -->