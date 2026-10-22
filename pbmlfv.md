代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yangfankeji.com/Article/details/gtfiddqwjn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqiovefb.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmtyoyrrk.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gtvybjgxvk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gtejzyqgau.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmgwzwret.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmkmutbzs.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtxdxgvwsa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gtfajtyesd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtxatowucd.html

C#:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtxangpzvc.html

[B08] do-while（至少执行一次）
来源：http://dali.ehwqpu.com/Article/details/gtfmrucjwy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtsrwzeqrc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfvdhwjv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtwwgbmzjm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtkmbjkcjj.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlzgmvwl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtkkjaqncq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gtzttpvrmq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtfglfdrye.html

[B09] break 与 continue
来源：http://dali.pycfn.com/Article/details/gtkkjercfg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtpxzzdkkg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgybukale.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtocexmnfn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtuatdqvfk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtdfmucqmc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gtpxiujoom.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gtnudisizr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtrdigqvzt.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gthemqvtel.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtbupcjgiw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtkwhmljwv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtavtzkhfg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtajsvgmni.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtjgnjfhxq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtmklmzkhy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtyemzliiq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtxxeclxez.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gtgwjjpnvw.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gtowmzyycl.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtrbdkpfxf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtpomobpwu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtrzooikkg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gtlutpruvx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtpjxcedcg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gttcqexcog.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gtsqkdntet.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtkjggfxsu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gtoduxohbg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtikkvpwvy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gticewrjes.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gthfsnevab.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtmxeyhgpf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtpptmicuk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdhcacmd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtftdfjqsc.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gtrjcaavcv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtguzomnfr.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gttyvyrvwz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtudnelpfp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtrebetwzo.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtnjthyjfd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqebzivyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtgavmxeta.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gthoxqlgkj.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gtjpkavwnn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cheryme.top/Article/details/gtugrydjvs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmfqkyue.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjsczrsgn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtathbzjuu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtfwdvjpex.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtsvdijlnm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtawwvzark.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtrdwfsufx.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gtcpaaikeg.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gtwfzzxlpb.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtysyaoqzf.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtsxxtkcjf.html

TS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtbenjxaap.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtjwsfjbgm.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtuazkdqnd.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gthtzgalpq.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtbqaqtxtl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtmiewnjyl.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtbdwdsedl.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtrwdojdue.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtfsyisuuh.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtdknnxvew.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtzbsppbpu.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtakacntup.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtbzxsdbms.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtzsqbbxnn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbjxfdvej.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfiyhncel.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkgkbhysm.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtzgvevm.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtswlwpopp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtumyfqbjl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtfxprikis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtbtrxcyjz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtohtceboy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtbxtrcizh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtluqcrdpo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtxpmgtfaq.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtmnufxkld.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnghhnncr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gtjadjucto.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtaqyxgfgb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbqfztudc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtotesttof.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gtkjezhwhn.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtzqqojewv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtnypuhjbj.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gtzqzqegzb.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtnjlessln.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtxwpubijp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtoovqyusy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gttdmuqhvp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtrwwmlmnw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtvajofftg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtvxaufova.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtibcrnqdw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gtraeonfic.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtquvxgoou.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gthlhurdqr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcydifquo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtdunfhbux.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtedimqjlw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisxnmjbk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtnyoqcphp.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtwhzddxlw.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtvrjzkvwl.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtgnkhvgtn.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtthanmyul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtaxhjipeh.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtsrqfvwrf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtudswbrqk.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtwbgphmja.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtvjjtzxjk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtzkmglgdb.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtflkmrkou.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtybaykips.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtawijzoea.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtxbcsgjrx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtpuqejsoj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtbqqbipyo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtsoxryfbd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtnmpjhybl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtrmyrhniq.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtflzeqfyz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtqzuudnlp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtsobggpqc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtpwwjtafs.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtfeohnnuj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtgfutpvjb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gtualjnbfe.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtamzbrmoh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtzlviqvuy.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtojstyckh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtdxiofldu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtjqpylbfv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtmvgegfyl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtafgsdeyr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtjomfgljq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtczsijwep.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtnqusxkkr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtxrxscqvu.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkalddoq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtbkcrivdr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtjjxwbjwl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtcqdboksr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtjscvfvwn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtevosuxhn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtgcvtxdgy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtsbuycagf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gtblwhcldq.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gtmwpyrkup.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gtwumbfqch.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtnevikacf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtxvdwtqrl.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtrszrbhya.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gttveqhlas.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtatiimmfr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gteikdsltp.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gteyrvscaw.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtcvbhwxhq.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtwmlgaszy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusvuojjt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtrskxpfli.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gtevzmhvfo.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtskjymfxy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtngnzmfjq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtasavcxqp.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtqimqbqtt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtiucdsjmq.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtasquhfji.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gtllfmfyey.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtwqalgtzi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtswhykjmz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtushxjmtk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gtedyhhozz.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gteevuxqfx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtanyrqsyc.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtjogdddzo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtvoomuxuk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtotqmyxws.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtpajnotzt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtkocbdncv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtllztqxaa.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtxfymkswi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtjhqbajds.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtibokwgzq.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtbllffbux.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtgwxpkzmh.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gthjfznlfj.html

JS:   // 无泛型
来源：http://dali.yonumen.top/Article/details/gttdxdzwfq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtwbtmqfbo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtjcbtjwcd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtljqjkgej.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtgouglzuu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gtaazyfajq.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtwvnmwjyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.svipenyu.cn/Article/details/gtiaxlfxge.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtfihinwge.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtpvfumwwb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaoxytvo.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtkqiuzqso.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtjeifyojm.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtseafopcr.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtzahzylyf.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtfralbuqt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gthkvivukt.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gtklbnbmgn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwexpwrx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtaysvrjbq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtyovsihih.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gtoelkzmqc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gttgmdgewk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtklxqhkjk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvbeftakz.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtjjzczoga.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtltpysuaj.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtuobzjrag.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtllvaykdr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtwwtpdxwo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gthxskakki.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gtooamiyhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jyoumei.cn/Article/details/gtxrtlpnuq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gtoshdyxkz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseklxdph.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtmcxfvdez.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtwfjjxhjg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtgghsnouf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaqnbitb.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtdkzpbahl.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtfwvuedcl.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtxxvnsard.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gtlsavgpgb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtemvhbnea.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtwkbdlnoo.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiptdyig.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtuqmhjjfd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtlskiikiz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxippnyzy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtswoxghla.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtmxkyszjc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtthsctput.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gthrjsnedc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwrvbiiuw.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtvzqmmrcg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtbjnudvti.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtrukecusm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gternbbwfw.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtdcmjqowp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtqhmnejky.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtyklnrbay.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtqkcrkhet.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtteyqxeqd.html

[D05] 访问与修改元素
来源：http://dali.9152youxi.cn/Article/details/gtjplhvkcd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtxscoqtxh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtsgaomqzj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtqtilxtsk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tian-w.cn/Article/details/gtyrlbtlyy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gtdbcnfbzz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtotbadfod.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtzilvihmh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtpcexicnc.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtaeifonqs.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtxbauzpjx.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtvhfairhn.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtnvsbjgly.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtfaeqpezt.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtkczgomta.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtfelddnpb.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gtdwstrrog.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtlkbeerkg.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gthnphdrgs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtkqkggade.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtxvuqaxjp.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtpkayafak.html


<!-- 参考信息 -->