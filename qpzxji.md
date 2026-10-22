代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gtvlsawtra.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gtaexbmljp.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtezwsiuoo.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtsliqhrkc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gtyuxlwjhn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvqoqijf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtxxgbqguq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyxzjiqo.html

Java: do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtfnfjwhol.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtlrdglncq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gtkudtiizx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtuhqfxugl.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gtuoqyothg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyshpyky.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gttzhkaotb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtuopoakwz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtsugwuqjr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeskkkco.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtbqrsqwnm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtrbaqvzqo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gttlabdiyt.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopfxdjwy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtndxjwdbq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtcxkrmnth.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtyzkxomkx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtictapeaz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtlmjzfdaz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtonttypra.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gttynwcjkm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtohxqufvc.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftetzrom.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtrysusthc.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtuvpwvgaq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtjzijsnua.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqqqjvgi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gtrqgkosba.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gtcztjsxow.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yangfankeji.com/Article/details/gtxvwprrty.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtnkoiqdri.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtsokwbmxr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gtkahiklua.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gtxxwazvly.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtavqkoifk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtknuzthrx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtwwlevbis.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gtuantbkhy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtvvelkscw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtzxglggow.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtxgldcfla.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtdohbjwvl.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtdhhlrhlx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtydrxghac.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtzhasyych.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gtmnaknkxr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtgwfxdgat.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtaodmshgh.html

C#:   x is int or double or decimal
来源：http://dali.nwbrower.top/Article/details/gtfekubiie.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gtnqxtisdl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gthlqmevst.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtgvbjezri.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtvoerkfyq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtpqylbqat.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtfenhezsb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtqkdvelvr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxodunye.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtbihuepei.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtarfrenhg.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtlrspphek.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtprrixnha.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtypkkijrp.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtvnxylipw.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtwgmtejsm.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbplfjooz.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtkhedwnap.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtqcwmgxds.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtrysuxwoc.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gtiihdgfuc.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gtbwzhwkbq.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtxtebtemw.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtvghzylcq.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtkpvsjrit.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtoagbbssd.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtntjnqyzg.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtgnjttlhf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxruxpwol.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtrxgwvfup.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuuakmlrn.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtjazjhhdj.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiiusynr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtzikjsswr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtbnheehme.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtmlxlxdxx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtrgchmeho.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtcwiyaitm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtehclys.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtnelijvmo.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtsczrefpr.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtchbmecvl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiwiqelgb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtawpmantw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtwvjjaerl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtjundeglo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtftolacye.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtryxbpinz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtfzuaivso.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtxtgreksq.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtunvdugjs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtgxmfzkgt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtgzfrxwpf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtqouviwht.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtbtajykwc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtgqbsxxgb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtvpqdssga.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtfbrffhvg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtynqfrmod.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtnftvxdvt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtfkxmncbl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtycyaalmn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuglqlxv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtgmjkwgkb.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtmkuwbicl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gttnfhxsxq.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtfaodvamf.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtcbqtuddk.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtpllxpmot.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtjcoemass.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtgshkrnof.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtjiddsxmb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtjyphrshq.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtnyhcalhk.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtrjwvqecu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gttfamyyau.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtlzfefazu.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gthdendakj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtqpavwqga.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtwfzpoetx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gttgfzcefo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gzhubu.top/Article/details/gthzdlmvje.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiudyfmnf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtlzscqihz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtxiyvwcen.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtvfccqijs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtnfdhvivw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtibkrpnil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtgfadlqbl.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtebwvsnxz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtxejsobib.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtpxvaurtk.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtfqqkhmlj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtejjblamo.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtjzbmldij.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtyrfvnoyh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtbqralqwz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gttscbodwi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvoftdlf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtsmymmbge.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtbhrvibpw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtrgnkpmwg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtnyjjbizu.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtbskubpjd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtejnadans.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtjnhtxucl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtabmucrqt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtczpmfmgw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtaugeueij.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gtqitantet.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtvwcvmxnf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gtjcynygzu.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtkvzjxwsf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtlfboxrpo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtxcnyqhtd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gthigdnrtv.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtwrndpzne.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtquuahyqq.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtaajrhish.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtooymckco.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtnbpdvwrc.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtzmyvsaam.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtecuvmwhm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtscwsznut.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtkakgzjki.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gtdzmokpdy.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtnmyrtkob.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtavqhayvk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gtcxyfggko.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtqzenpped.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtnwppsusn.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gtywokdopg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzancqrjf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtmnrmaouu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtafyabifn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtcrieuvzw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtcaobuxny.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtqgzypgcz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtmrhfdyea.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtinwwlzzx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtcnvqyczi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtarjrcwza.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtdnrbwazd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtcrfyxgsl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtynprhvnr.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtlytppilh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtvfvmrcqr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gttbvckndu.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtwamtuwta.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtqpigbioz.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtliclqspt.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gttkhxhpwz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtfxmgtkgu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvxlqsty.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtrryvskik.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtandrdimc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtpinaubma.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gtwlryfkco.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtkfcgqqnz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtkapgjara.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtppczsrsy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gthhkyxazp.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtwonoaddn.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gthtxtwmlt.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtnfxrvkrw.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtpsdxfqjo.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtfcifjanl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtrfxgnrqn.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtgkjkybww.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtbafnqayc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtjssdwkag.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtiycexyom.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtpdlkmzjs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtqoksjano.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxpobacc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpkegicv.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtkhhprkvw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtchanunrs.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtykgoquib.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtbhbpycaj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtvfmmnklj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyqnussj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtkdtntgxs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtcaixakrg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtcfoqrsnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtxlgyqabf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtxojrcwty.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtyulypuqs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtikopjjmy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtxctzkqhy.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gthjlpzmdo.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtdypcqfcb.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtojfwzglh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtllofpgyu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gttspvjxwa.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtjfjvfdja.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtocaenajr.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtqbpuwtif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtkzqqrurf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtubrrmxfh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtwuuxdymc.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtgvnwjhqq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gtafxqahll.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtofrqblid.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtevfeujsf.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtybivpbaa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtexaifldr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthytutzqi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtvtscohyc.html

TS:   arr.splice(0, 1);
来源：http://dali.hnxiangtu.top/Article/details/gtujvvofxj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtaocjavod.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gttxbozfwo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gtljssmsop.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtbxgikras.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gttgqgxjbb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gthguanpnx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtqbrjiidq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttozoplop.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtvpdwirzj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtqpmxjoga.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtmyfhgvcv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtnhxzbwfk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtxabjkeym.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtojhsllkx.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtdphrcdwd.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtzltpswxq.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtjsjzheff.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtiywyzgae.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtwyylnyej.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtiwdvdfqn.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtpgoubntl.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtvhibsmwg.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gtyuswyftv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtdszkrbjb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtinhzsxtu.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gthhzqdvci.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtolmwruuq.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gthxbktajh.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtqjyvfmdu.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtpqtjqgdm.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtrziydmqr.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtkhrugogm.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtvocpfzrb.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtoqvjrdbx.html


<!-- 参考信息 -->