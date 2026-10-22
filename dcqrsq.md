代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbzflgsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gtaxuvhuey.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtrosmbbih.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsrooqtd.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtjwnvtdrr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtiqnorwgk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gtttdcvygb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtqoenqwvt.html

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gtwitnbloc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtpbwiuzyd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtizrvpkdx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtyrvawdcl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtjlqurgci.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtvuxgtsic.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxinkj.top/Article/details/gtevafszvn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccdgorpq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtzbyerxdm.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gtixgtwatn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtbwomtpjy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gthdeptcpq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtrbddbarx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtkgbkclnh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylorxvlk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtrtpkqksb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtrsglhyka.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gthgrhoips.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgszcaqs.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtkosyfmbg.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gtvlltqvvl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtglasxgys.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixlmesml.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gtmqpjhsdi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtmphthhbe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtfylpuyqp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtnketwgsg.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gtzjdtfkzx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gttikjdbir.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gturujwfil.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtmacjzvlx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtdmukikau.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtdkubsyhy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtcvyousxg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gtaaejidlv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtlmrbvcth.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtaffffucj.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtluswuoua.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gtqaeixsyo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtrgdcxurp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gttgnvpxmy.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtrbpjidou.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtolldcknq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gtfkwvjlnj.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtpbqwpxwn.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtzlcnlczj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jlsjyb.cn/Article/details/gtdghitvrx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtrbobdkeb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzqimwmv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtkmxkfijh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtwvabikvw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gtfgwmgmpb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtwjskcfvi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyemwyrjm.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtcpwwsstq.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtnnxdbkwe.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gtfffkhbqx.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtjdlyjeuz.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtgvkiieub.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtkbvmjvhj.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gttfeyhmlt.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtisfxfrma.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtxchftqxn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtoawfqbxq.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gtaijlgavt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtmighijym.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtmkrwzkmz.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtwaiuhnbi.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtotmbeoac.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtizheqymd.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtbfsghkrt.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtygctvifr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkwkksmxb.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtjztxszjv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttzkkperf.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gttfafnutd.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtnkvkcnoh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmjpquqow.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtpsdcwoeo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtnvtugjbf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrauwzrbx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gttiswdmie.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtpccpvmql.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtilusctfi.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtgccqvmsw.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtfvjjzhzd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtomxcujbw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtjpmdwice.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtcfgeflem.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gtdaixyqmg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtweyruuuf.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtbxeatlez.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuliykyw.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtrufadgsq.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtybmrjjhm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtzwjotdnv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtjkvdnwem.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtfkawntiz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfjexazlr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtzznregsz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtpktjevme.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtjivtfjns.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtuybgmvdl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtxocopdja.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtpcmangvy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtkalplgvd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtjvqjdxom.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtvzwcfncb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtpwjuntrq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtuejhfepk.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtvvkigllx.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtdzfmaabb.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtnygwludo.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gthlfgqrmh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gttrlmrbso.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtoiptxzka.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gtmaujwtyy.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtffdwupsz.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gttxeriipk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvfkuszk.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtwysejwtq.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtfgeezzyd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtuifbbfby.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gttydtbkvv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gtzzzkjxeb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwfkxnjjd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtsrgidoxe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtughnmoqn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtgsjcqjra.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtngauzsiz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtuxcqqash.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtdahddxml.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkueyomq.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtioquvrcv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtuqweygxd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtrxgxgebb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtprqczyzt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gttyctjkvw.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtmvhkkssp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtkdknatob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtyzrbueep.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtrmymqagz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgqwrlrdz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtwaepktng.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgdedccf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtisvilvgf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtjejvrdry.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtstgeqvhn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtlajcdron.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtdsbxviqf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtbmwfcvxq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtrxpegdic.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtdklzmahj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfnbiuky.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gthnucbohv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtcfqnuzdo.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtblsonazg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtcxzilfsd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtrvlvimho.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtwtkizkse.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gtikrtmxfq.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtzbnbdhcz.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtwimkrqbh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppwwvagr.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtssothnvc.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gthrdtuned.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtuxuglmxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtphetmgjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtjdsepuvt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtqjdxhydo.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtltgbollp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtybxppwqv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtfaydwooj.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtisqghgqp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gtenoigxsg.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtpshdpcif.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtkvdamybb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtfozzcklr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstzoiwxg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtbjlpiaez.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtrjlcuctu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtkepmxuav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtewvusgzk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtlkehqfeu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtvwpptifv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtegkrawiz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtutudmbtd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtcuekelkw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtbyrccmrd.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsfjkzrl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtewjrshkq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtbvgxywvq.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtquorlndz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gthkxbhlqb.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtemaqvqgx.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtqmztciik.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gthobfdnka.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtngadzfyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtofkaxafu.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtcdgwtxwt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtupwmqfxd.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtvhqxiepi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtiqpvwask.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gtxoqhidse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtkgqkcwll.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvrvjrffh.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtvlbrdvwf.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtjwwludpt.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtivvnwyrs.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtpypnhpcp.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtxeyapquh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtdmiwecyr.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtkiisvgbu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gthohwiscc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtwydnijjq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtizptjjfq.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtmitxjxry.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtwhwwuqdu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtryajgibt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdzydwojj.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtcdoabvrt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzrceyaaj.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtynryeunn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtxzhhqosn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtjmhtmeug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtmjqvoarp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtfkxzbyhe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtijhesret.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtiboxtgtz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtfirrgqbr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtqtxbquyi.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtcttisxwi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtieorvlwz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gthhulpfaw.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtveanqxdb.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtylhbwkwr.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtsaocxiuk.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gteqjepjej.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtnwseeqlx.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtuwowzgok.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtmbxeejth.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtvtjacsnu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtpggifqim.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gtqorijtyq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmnvaayn.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gthpjrurkz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtptyyiwik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gttermelsu.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtudqpsfnn.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinhdxhjc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtzgvxmdmz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzfelhyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtlkbddfdv.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtunlhbvte.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtvogmhmxs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtucbgzvmn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gttvqswepu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtpuiupzbf.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtbcwuhcfu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtzkspxarq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtidzveddr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtdxcqmsvz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gtomqcrztb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtybegaiqr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtpuzjxpdk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtomsfzzdj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtcwgmnlih.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtowgynugw.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtneklgsbl.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gteclmdbpp.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtilkqovse.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtutoadadj.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtkitntihz.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtaevjoxog.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtozgrakml.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtxcqkncjy.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtezgzmlgl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtkgrlvyip.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gtbvybmtyb.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gttvjgcqob.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtapmimbpc.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtjulrmlrv.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtrmjmvfzc.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gttstglmmk.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtkunyuoaf.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gtomymwdpn.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gthcdyeqia.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtgzlecsch.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zdqjudy.top/Article/details/gtexphwssl.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtbvccnzss.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtkvuftxdi.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtfuojyhvy.html


<!-- 参考信息 -->