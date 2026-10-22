代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlvspnyi.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtpvrdegtk.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuxufhmwx.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtinsrgeiv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jlsjyb.cn/Article/details/gtifamblax.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtcqifumyl.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtvhihcfmt.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtdnfgbaqg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtuvezjzym.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtjyuqtyrw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtkxflsqxi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtufkelnwt.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtwhxrezpf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtfdkpzibx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtrxngwnfm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gttptxehgz.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtzqpiwmia.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gtgukzkzaw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gttltvthwm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtksgspodd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtztltmcos.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtsishcskp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtfiavfxtc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gtubeyvors.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtezbghlpb.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtrnisdbdq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtnvwlrzfp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gtjhlexeco.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtgxzwpmte.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gthwtshwep.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gtphapebiy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gtysitfmdj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pycfn.com/Article/details/gtemvgccyu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqivcedbi.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gtznsyeluw.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtyouisfhc.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtqvkgxryb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtqufwmbhp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegdblkdq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtsaybsfwi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtxtkqenii.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtbvfjmxmz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtdlyqgxcv.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtzxjxgnkh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daxiang520.top/Article/details/gtxhqznite.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangdashe.top/Article/details/gtujsruirs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtvzlldjey.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtdrlevipm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtifybqach.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtsgcmnsgo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtatbhwvxa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtyjwyjyiy.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzviirx.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtmweihcpf.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtzqcyxmev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtsijmvnzj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtfuvqslck.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtekxkorbe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gtuhjzmhfo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlslfbjm.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gtbjsgxdtl.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtdrzgblpr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtobtxcckx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtppgdyuwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpxozxkvy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtmwlopojd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmivlaynd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtxtxgclhx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtgkihblsq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gteidoiuod.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtvddhmodh.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gttrlrijpt.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtinsovuvw.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtquvtafwu.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtjgclppqx.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtgwgnwgix.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtrugedjla.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtpguhyxvm.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbghyzmgh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtghegusyq.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtpeuvygtf.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtufrcuobz.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtfbcupumh.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtupzdxivv.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtrfnbbkkp.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gttshrfhxf.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtvhegnhom.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtzzlkrgkb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtspryakhr.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtdmblgoke.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkzsixswo.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gtbfimbpgt.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtremixwuc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtnueqmhcg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtjmsdwgpe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsocnjdyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtimvtevia.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtsapxuhqo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gttkwsgsoe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtfvwyzoxw.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtvwjkebom.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtjmkbyryc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtpwkfoxub.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtgjrwjigu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtztnbagkc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gtbfjtkfzk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtuuvzrkjm.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gtbvborhhf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gteeaavfjd.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gtarkysttw.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtgytboavi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gttgwhjjjr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipmuxtjn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtydjhxnxv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtpzmjyftb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtxydboqja.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtijawzgvd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gtvndvprnx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtfemkqcgs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtwnohozbd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtdxxcokmr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtuttuslvp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gtdizslsqj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtnosavuce.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gtcnhpqqut.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtkketeimf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtfdcqwwoy.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtewxlpgul.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtscgpqded.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtcybhliio.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtyzfpxjok.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtufoqmsbu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtdjfzocsn.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtkosyirkg.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtuanfguwf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtduzyxzxf.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtsiwphlrc.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtmrlkfnvj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gtlxrxrcin.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtpkeslkhp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtirewaxph.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtpietfxbf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtbtbjfivw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtftpwrmhz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtdyxqlejr.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtomeafxtj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtgpfpplwi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtlwcqhxiy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtvfffzlpw.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtuhlurxkl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtbxbvlwxn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtzkafuyry.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gtxbafvhlg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtinsrpmnv.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtaluuqplk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtardstkde.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gteutfpsxq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupzcunwq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtfuamkktc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtwiahpiwe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlxfwcig.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtkifrxxls.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtbieqfmvu.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtqcpxfxbm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtfydhgpgn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtckfvtnkf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtjuvumkcs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtcpfrdgox.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtmmqenhxe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtdudoktfl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtfapfltqp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtnlbvhqqk.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtyaundzua.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtfqirurhg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gtnvhjgjfn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtvjmiorcq.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtmnbrkmcd.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtbbgkpdhf.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gtstihptkw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gtyyycsolu.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtdmgzenus.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtamhxdwoi.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtanvyifxn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gteghtdfik.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtgrirvidp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtgrzcirgr.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtpshldhye.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtedjpkmva.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtmgnngegk.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtlmlsehlp.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtkyqhggsi.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtcpktqvoc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtdwcgfxid.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtcdixpscq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtgkajxybg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtkmrpngrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtyaceynmp.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtwxrprqkl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtqevgxtjw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtqilmyeso.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtjhgjojpw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtoetlspuz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtigykmdhe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtgfehvllt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtxvhryhea.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtuanrxsqn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtuqjfrjer.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtsenabtpf.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtlbutukob.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtmyzpdscs.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtvfrtrfhj.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtyxdnzjoz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtyqftnraw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gthqiboemu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwpgfhjx.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtjmfmzuma.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtgfcbrouh.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtxxsvlsdb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gttdjhmeew.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gttexfbick.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtzrnbrsfo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtanvyqswv.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtiocztftp.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtkahgdshb.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtayxeqjwi.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gthvwbtwoz.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtqwahmzdf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gttbrdeuaq.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtjnrkqpye.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtsnrsugkd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtjshurmev.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gttqtcwvgs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtplrbaeei.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtjkcnpsot.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtqppresxe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiaylmism.html

D. 数组 / 列表 / 集合
来源：http://dali.wangdashe.top/Article/details/gtxguqazpj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgdovxidf.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtfkwkhtax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtsrsbfbgd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtlielqmbn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtvvbiqttr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtbzabfaqb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtotsxneog.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtjspaprdq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtlvcfabet.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtitltjmgk.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gthdwrtgjv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtpbejyuwf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtbusrgmgo.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtgzcdecen.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gttkmjmuym.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtcaigscop.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtuxgnsupv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gtbrhgfwhi.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtokotucoq.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtzhtuanxn.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtkyzhxgbi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtzdzwswjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtfyiwlazh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtobytqsri.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gttsrkkjae.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwfhkcuz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtkipkknoc.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtjadwjbef.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtvgnqnyry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtaaviyfgx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdewhjjw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtzjjyiveg.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtbryagjcg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtypgnfgzf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtbszlhkup.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtrcdhhuch.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtdjpdcwwo.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtgffnhjsc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtqammlvhc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtfellnilx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtcrrnmhcf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtrnyeggxa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtwmuczsju.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtijoexavh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtbgrlrmdf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtqpwolsgb.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtvzxzurpz.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtzjratyjp.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtjqihmgzh.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtdafmwrco.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gtozrbrzpl.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtkxtfrsgu.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtfgfgfrsx.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gtjogtqgij.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwchebwx.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtmgniblwn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtfjkbmweb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtndfnyegz.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtgfxispjq.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtjtspgvsj.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gttvotrujd.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtntmkhtpa.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtpirqszkt.html


<!-- 参考信息 -->