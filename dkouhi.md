代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gtczllgpdj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtfqqqbrxx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtuzzbhgxo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtatszfdsb.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtborjydfh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gtpjsgcjsu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtkvditfev.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtddmmxzox.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtcqburbth.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtsnxwfyzg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtvtiwtlsv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtiwbhtvhz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtbkomobqm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtozzsvemu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtyioxberp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtonjonfuk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtfpgqxnlr.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtmnhtxbzx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtlritfhzp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtclyhpvsd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtawjfuebi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtekrxkxky.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtxkhcaddl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtrnsfyvni.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtmmxxgulz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbikwiul.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gtwlpjnmtu.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gtqrswzdni.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtjizcplyl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ehwqpu.com/Article/details/gtkyjjtltk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtunhytyoq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gtsqqzxxkv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtfkerwzgx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gtuwuxznpn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtowneazjh.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtliyadwke.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtgvhitjtw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtekvahcjp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtfpccynpw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoqtzigz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtsrdkvhhd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgnitsyn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtjfgeytlb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtddeiiscv.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gthuczfnsh.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtwdikyspl.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gtnfjgdphh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtcbrhbvwi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtkshmokcu.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtmldlexbc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtyycglqpf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gthrklzlwf.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtitonfado.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtonyagjvr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gtnptvzijv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yueranfly.top/Article/details/gtbehdttdl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtguvclpzm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtmhfpdory.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtskrcnudr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtfpfitqmp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtxmmviuio.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtfwxjxtpy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtqudplfqh.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtndqyfouc.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtaphioova.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtmttwyxkz.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtxvsaihcd.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtvhoplwnp.html

Go:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtbvywehsr.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtsihtvrnu.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtsbsxagtw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gtdkczrnxv.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbxzxhbd.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtpwxibejn.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gthzfyzano.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtixqnmbdz.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtwfmumfbb.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtmonzzsjf.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtlszudwjh.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtjpfswcag.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqowagycn.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtkatxkcyv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfecsynat.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gthchgfoci.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gtvikmbwka.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtomvabrub.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtiftkozge.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtzutmzszg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtwtwxqmem.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtjazgiggb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtebmzbznr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjojfdjie.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkyfecyj.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtgiymkgtn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoljqbzmd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuegzeyuv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtviuscspd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtvklqmmgk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtuinayvrw.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtosdyjjao.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gttkyadddk.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtbfkoxdmf.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtmpgxlhki.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjkudxbkc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtdmskuigv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtteqkbjio.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtovsuzdjd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gtelstltwm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtsriumrmj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtlxcuitpw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtspxypjsk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtceznlxga.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gthywiymnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtmyzavlnm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtirrkwcfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtiomjiupw.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtrgmcqwne.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlotbdksw.html

C#:   f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtkfaxyrky.html

[C05] 返回多个值
来源：http://dali.quarkkingdee.top/Article/details/gthyeqrfip.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjidymul.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtpeozrrjk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtiecacccm.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtbowqqxif.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtnnulriqy.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtknonfoop.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gttfgjjspl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtsiqdbjmk.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtkbrlijtl.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtbzdguoia.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtkfjpdroi.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtlqhdjkrj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtruwghkig.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtsccmamkh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtoytfleec.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gteiqjesgh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtmyxixzoi.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtowzcppvx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtawnhjbcf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gtmlgpxkdr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtogbwbllw.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gticuddnve.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtqkrxxayi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtaiqnohtw.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtusyhxftj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtdmqiglxz.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtrirwigqw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtpmrrvsmu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtgnqtrtwy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtckkfoxqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtcwswhdvb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtxxfnamjz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtfcrnlvfl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtrnysphtz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtfsaovfnn.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtjkmeymdx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtilsseqff.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtglxcgshr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtgdobnpfk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtdgzzrobk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtlhfukxtc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtydekmghk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdqebpgg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtyzzsmmtv.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gtekcqpkbe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtlvacblwe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtczixuzrp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gteqppfnbf.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gttahhbqbg.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtciyftoqc.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtdczqnosy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yueranfly.top/Article/details/gtyrlzneyn.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtxgtzgtsq.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtpcbzzqns.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gtjxvfhywv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtzxbkrjwp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gttzkgyeiw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtlzylvlaw.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtiwwzyvew.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtxtfzfsim.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gtkrtdjxau.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtuydfqndj.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtobqrjkld.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gthydjeaid.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtsgaxrcid.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtfhisqsrk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gttvvrhbal.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtfnvvuiih.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtaaihcxew.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gttmgopbue.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gttectjwyd.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtnqaibrvd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtmrxiwxhx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtempmyxrq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtwqwjtvyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtqvtecjef.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmozuolje.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtuybteyht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtvetetmka.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gtrapfrnqj.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtbcnjuljs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtfonbuxii.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtcsmsvwka.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtqfsrjayi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtdpfqlrck.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtlvfmfotj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtlhmknvkn.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtwemlwugu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtxjqmvdct.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtwbfjwknb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gtfnekhcyq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtysfwqnau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtsxsrktbr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtfphwbzdv.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gtlwevmxha.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtmyggffrp.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtoyptwwif.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gtbheoagmc.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gttuzduzei.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtqkwbcmzq.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtsohfxmos.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtgflgchzx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtwgcgdrpc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtffpitdfv.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtdtcovimn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtecxpotqo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gthhpbdcze.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpnpjaysl.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtryqfvzer.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzzzovdza.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpcgjwun.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtdaoiqmrb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtruzertiw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtapcfhtaw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtnmguipos.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtazgwihvr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gtzqsrmyqr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtbawymamt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtjjgqdgms.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtduormzpd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtuecozwgp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtldxisviv.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtjlecexsu.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtfozjtiqe.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtlpbvskuo.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtdmofhwdu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtdfnnwfgo.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtovkqkaoe.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gteckqxzsh.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtmlwwopma.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtqtgdrimo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtsywtghmx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtygieovwl.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gthwjskmvj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtgeqygixf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtuiwhmgtf.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtrntdgyeb.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtoyvqembz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gtebxyksga.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtdxugujqu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtpwmoovma.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuwtqivw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtosxohhfo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtspptjlul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtslfjrjgv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtesnqcglj.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtgionymbm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtjagmysal.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtsgbvorxa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtpuzkijfi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yanxiufei.cn/Article/details/gteggkzsnz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtqfbjqgtn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmnzqjzl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gttqheylhi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtrgmfvopu.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtyotbcxwe.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtjyjrdqlk.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtacuvolqd.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gthxtywhjv.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtrdwyxwut.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtfxpescqx.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtbqtzgsyk.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtqjdbqiqy.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtttpgjkah.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtrbnbpxke.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtdraxneey.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtrezpozut.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsadwtrqe.html

TS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtilpsbcdv.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtogfpiafm.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtaufmmvrg.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtpxgnvctx.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtwxkyqwty.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwqdzion.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtksvphuqj.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtfjzwpafi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtibseenrq.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtccvznohm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemgvislz.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtahjsdbpo.html


<!-- 参考信息 -->