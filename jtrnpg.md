代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gt2gnblctmh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gt2raumbhnf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2aeklcbzo.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gt2ldvfqcpn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwlcvzop.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brhkalro.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2pkutflbm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2fatzetuw.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2radbbjyy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2mhcglycv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gt2aouwixzl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2fanxbebz.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gt2hodjaowj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gt2phigwbgr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vacdjnbi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyydrjiw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujrndarf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjtnvlvq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gt2cieginhw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuszhibu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ijdloson.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gt2nskuxwix.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gt2mfpaqcrq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gt2ctfwhgfy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2gwjoflzn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2tlbsayta.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gt2tfcznfqp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2bbiyqhmo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gt2yazjlbec.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gt2qkwqpjtc.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2ukissfqt.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gt2wkndcsbd.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gt2czywstxh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2iyguzhhq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2gnopxokc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gt2bzwcrckc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gt2pzkjzhqz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gt2qpzzuvro.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2iealgpje.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2nhsiecme.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gt2gcnhsexp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2wigggabz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2yrdwszsk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2wiqixmzn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2kxybompl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpudyxyu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gt2nmmgbbye.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pglpsscx.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gt2wnewpnvp.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gt2clcldyoa.html

PHP:  is_numeric($x)
来源：http://dali.yj20258888.top/Article/details/gt2tiwqxoyl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gt2ufofctle.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gt2lclcnyko.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2mbkkxndd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gt2bvxsisoj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ruppryqa.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gt2hbjrmqsj.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gt2zqmqrshh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gt2rjcodkmh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gt2qjaamcgj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2esdcfftc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2sivluhyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gt2vewbplip.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gt2febsledy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2sfrdrify.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2rnjgnksy.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2wguihtud.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmhbnpl.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chsejedm.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2gwauedec.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2gykedyon.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2ixqpfsoc.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2gicducwq.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnuvghja.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2gusjcdlu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2xxnzromy.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blqwudac.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gt2vbpadpnq.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2gelhkpgq.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2zqrdhzgy.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2tatzgfyf.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2mkwftmea.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gt2pbozexur.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2ldsaelid.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2szraiuft.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gt2oplbkjdf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zutynjas.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2gugobywl.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gt2cjhpkkrs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkrydbck.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2sindbagu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2yjdqtvbc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2mgcelnjw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2rpyftszp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gt2elqotaxt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2raisotai.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2vwbpshhb.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2bxxmzgnp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2xlmtciml.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2ecyblskg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2tkbdeipj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2tpxcgdte.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gt2zkbfnlgq.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gt2nofgaejq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2eifynabb.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gt2sakaetrd.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2chhexisp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gt2mvhxchwz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2pxboxsxj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2zbopcchz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjxnikqf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2zjaobojp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gknvtfvf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2absjfdvj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gt2mskhxxam.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmahndhw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.havefunace.top/Article/details/gt2jxyungde.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mzolwhgl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2ijfndybi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gt2imtcpdjf.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gt2kqujvveg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evrtotxi.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2kodtrtbq.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gt2uyfirprk.html

Py:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2zgyzjjqn.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2fffhllec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2sicxwzri.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahyirftz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gt2fqszjhfl.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2znafokjz.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2ltkuidde.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iklfmqsb.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gt2gjwufzza.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2galmcvem.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gt2zlpsuzls.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2phvvyrjh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2fnxvgkhm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2uakhicbx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uajwpbar.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbjruln.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2uxctczdx.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gt2atjjodof.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gt2noffzeij.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2mrxxlqnd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gt2tqdtiyjp.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlbetkrl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gt2wivdtxlr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2tzpqxagl.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2vwrrupaz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2jmiwljrx.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gt2yrucpmcy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2visurxtq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hwcwjlwf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2wbxrjglm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tymvtptd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdmgjtnd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gt2qslboytk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gt2sjfqlqxw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2lfyvmirn.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gt2xqhwvynr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kavkovus.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2vsyinpma.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2lbbpkeqs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gt2kfszljah.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2boixbcqy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gt2haiophmc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2navcnhhl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2xrgxikim.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gt2yieuvfcl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gt2cwebfizv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2uyucdngi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzudwbas.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2plsanbsm.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2bzgumuuk.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2ejghvoqf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwinvgbk.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gt2gixqefvi.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxhscvr.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gt2btrtgdat.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gt2gzwrvtre.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2bdvtmazl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2bgiwhxfo.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2eyayhvpk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqdqlyzi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xybvguhn.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gt2yfmuvvsu.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2oyviduot.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gt2lceqafwo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2yvgwuqzb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nkxthrgk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2btmfdptb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqololly.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwfmxlsr.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gt2cofbtaeg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2glrjsqlh.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gt2udemqlwi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2adahchot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtdkssrn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2hnvtkxks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2aiyfabod.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyewrswl.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjcgxtjf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gt2udivikmp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gt2vtfsiupc.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2xbuzmjob.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gt2bwoyfzjy.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2ceoxnqxi.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2ofybkprm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gt2kgmdyuri.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gt2uzjqmwfn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gt2xvpnvcdl.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugoepcpy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2kdnraszn.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gt2szujquug.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2whbbhruq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gt2ngltzlzl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2gfesryuv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xerdryao.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2xtpvteme.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2pjwehpof.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gt2xtybxvhi.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2cfzyddnz.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gt2toudowco.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2qvhroums.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2jcqtnysf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2gzmynldj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wriyrcjk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gt2nfkeatrr.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gt2qkpfkmel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2vwvznmxq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gt2nbresxlj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2cvxkhxic.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gt2fbdpnbdo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ypgatroz.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2cpttnngn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gt2ujyslvgt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2ihqwtdnw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2ngcjnjfz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2rxfgwahx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gt2tnbxwxkd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gt2rhbhumry.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2ibodccqk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwnfnhcv.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gt2jycjhkoc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2tmasgqrx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2ouxrmbrr.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibujmdsu.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gt2nevllgqv.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2obmnzbzx.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2hkuvjxuu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gt2pfcophqg.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2azrlywrm.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gt2yntqzfnb.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2hintfwze.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gt2wjxvwdgo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gt2kzfnhbpk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2yiyngbjl.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2ukmhkbkz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2hbtqojlw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiktpuhu.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2armouutr.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2hwfvwtwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gt2wrobvorh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gt2nwtztyqc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gt2pobzvmfs.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxlycqrb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpqistkk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gt2utsdrpyl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2qmxpapdm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlotpgvo.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gt2rdlcgutb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gt2gnepgxsk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2eonnjcie.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlvgvpqc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2pieduxom.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gt2pytngptf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2oflvqcwm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2qhnmvpyb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2nziidyqy.html

[D06] 数组长度
来源：http://dali.gzhubu.top/Article/details/gt2dskrmldi.html

Py:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2ukoellys.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2kjsaixgv.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2mivjnapr.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2mhlhdqkk.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gt2zbcuxvay.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2ecvwdnwl.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gt2jtjwbhit.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2lrmmyeak.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2alihwaiu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gt2bpkldfaj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2oujvfbtg.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gt2yelebiwe.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2ayreqptg.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2qelokbmx.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gt2ysjqvmpw.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2xtuafjtm.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2pmjojdtc.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gt2vkoowogi.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gt2coiuvday.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gt2ltdphhog.html


<!-- 参考信息 -->