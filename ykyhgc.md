代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtzhszqddz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtgfhkatqj.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gteunxryjx.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gthkswlqha.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtbwnglazs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtynuleyfo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtlwumrgku.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtdqqdzrnf.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtraodgdpt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtudimwthj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtcbxdnmiv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtkznjnksx.html

[B09] break 与 continue
来源：http://dali.yangfankeji.com/Article/details/gtaifdwbfl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtkpojshvp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtyecxvpdh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtngjxmbrn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gthhmljyzz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdabkawue.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtupnxnmvp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtsylrwqxe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtvpejztwy.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gttpzfmoyj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtleddphgk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gtyefzhtkd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gtlyxafsqv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtybmhcnwy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtakhaipco.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtlcitacdj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtvtauzooz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gttkpuwuhw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtanenkznm.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gttmrbpwju.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gtfiuoxfab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtzjoebnjm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtagmgaxhq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtosuzmvnm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtqlohrvnu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtppaqmuxd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtjocgynpd.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gtpbjtriva.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gteprjzfqt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtpgbgaocr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtxewpsqpy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtpvrofpqj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtxjvouhyp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtkktqctwn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gtbjznufhp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gtuaqshxvj.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtxknlawmu.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gtwsrwhryr.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqwchmws.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtkprnpzyu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtspznxzek.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtzigndqxu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gthsxybfys.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtktbuqtis.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gthsrefyza.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtyrhgtlsl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gtlvgjsqux.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gtrltletrj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtqrbuyukn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtoqwexnkb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthenngbig.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtwfbpsoda.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gthvmowfow.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtqvydzfmf.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gthzbjiesb.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtxoektcsn.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtynswxiyx.html

JS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtwtjagxvq.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtiyaunptb.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtbszoauaw.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtlcnmifhb.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtrnarwdfc.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtqqdmjykd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtyykshnkd.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtkxzoanxo.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdcjnuan.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gttzjdvbyc.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtuaacsefu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtgqfpslee.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtvcimnwwm.html

Ruby: return if data.nil?
来源：http://dali.yvedp.cn/Article/details/gteoecrjxi.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtoablzvtg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtperljaxj.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gttxgahuww.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrxpsvder.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtuckhsqnx.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtenattfab.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtglxglvje.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtfhgoaliq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtxtqbqvea.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gttbzrfuha.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtpytfwska.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtyppvuurb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtqamchpje.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtkrbycmbe.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtykrmayws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthehimylb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtprsftdhw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtbarlrjzs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtkhapgdny.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtjigbyruj.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtzisxipjd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtwerozfaa.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtkybwtppo.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtcsafyboa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtjjuospot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtjgsktizj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtxilozwqj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtodgynrpa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtjmqngmvh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtwmknvxzr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtlgspeyuh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtcdtjmupi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtcqtbzqgi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtlzhchxtb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gthncknxtp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gthdaeodco.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtbysttjaa.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gtoqjwqfoj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtlmubbeij.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtnebavvhj.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtncxluxxz.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtafaohohb.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtdgdyizoq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gthwbyhyiu.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtfbqtizrb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gtzvbvwlil.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtenvbnkhl.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtmmxigzgi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtptoxgjjg.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtjihnjqqx.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtzftjqpbo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtpvqczzxc.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtkwfitikr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtnynpdglu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbawquwlx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtbzezowzn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtqpcwxtan.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrotuagjr.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gticyphpao.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtiwchkxnp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtyntthlms.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtuovwvpfv.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtoxsxszjf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtvkbqvqyo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtowntekjy.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gthuwxhgtw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtgdwivfhn.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtlavjtvpw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtwcpffjov.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtmltqvwjm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gthudcnmsx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtrrwwxtgn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtuzkyjzzb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtcoqqvrdq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtnhglrxwi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtomogxpku.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtjftsetdd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtnxoqkxqs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtakppnpxg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtldvtcpil.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtxipsqzci.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtcycimshm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtlcmgelwc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtwanipbkz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtwjobgsxz.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtdllwflod.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtclgdpjur.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtqessehzi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtbyufpkho.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gthigzuwyx.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gtnpdxdwli.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtmezkbxgb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtnelnxdyw.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcreqbrhm.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtpkulfkqz.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtjwcmknoi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gtxiwflvfa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtramixkfs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gttnbpkoka.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtatbkkbiq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtgccgedbb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gthretqkhq.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtldsutxod.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gthxlgbzpl.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtdhsfxmgu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtebyuwgbb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtmlvfdsul.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtvezbqfth.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtrweaczfs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gthezvoivd.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtfrjlywct.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbsmxnfu.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtiqpxmbji.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtgbjkvhcj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtlomwzrns.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gtivadgjlk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyscbypcr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtxwqmsgtt.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtevbswuvw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtzmjbldjx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtnnkubckz.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtmgeitlqa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtxvwvevia.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnndbimxc.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtbpayslsu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtaldozvac.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gttutftbzj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtcgwtxrok.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtqdkvahbf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtvfmhzanu.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtsupzztie.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtukmzmxfr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtwbowmrmj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcrmchmwk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtbtggikqx.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtomuxdaml.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gtshstbrws.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gtfubpdavw.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtjpjztmgq.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtxnieomtt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtkoglkazo.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtmxjcjbdu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzazrxfs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtwwpgbnnx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbteitduy.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtfwxfekzb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gttjmtnqsf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtrspaaagq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzeyomybo.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtqckitmbj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtojmgoqtu.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtyzskxygd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtnhssfubp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtldebdqxw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtowxjpgrm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gteygagyjx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gtysrefxln.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtbavbeslp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtmmjtddzo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtxethumuw.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtuvgyzzth.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtfoyvknjm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtmybjdfpx.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtuvjmbpoy.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtnhlhqupc.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtxocevgqs.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtihiuange.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtfqtoroeh.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqsbkswe.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gthcykxaey.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtvikuzsga.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtfhrdylch.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtzobfpryp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtqecbmuym.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtodojaxic.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtrzhkgzpp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangdashe.top/Article/details/gtxxpavskq.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtpyuiejfr.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsonyqlgi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gttyoqkrsn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtqsmxuswq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtpqvsaihg.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtyujotyet.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtffjnnphj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtnymovjyf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtqjrbqbnf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtxdtoxfkg.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtibnzapyo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtpuxsftnb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtkydjxghp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtbieanptm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtwwerpmfn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtedrcmcrb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtsewhxqxz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtvclruqzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtilybzmje.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtqiciqlta.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtbwlmmlkr.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaehvdfw.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtubxhcgnx.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtkperiijx.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gtgkhbfbly.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbiojtyfl.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtctxwagho.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtfljdiqry.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtaqykijnu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtnpyckxsr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtnsyfrqhx.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gtmppqjctv.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gthnigwspo.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtfnjdvcnk.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtnilvwbyk.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gtisynglcm.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gttylclymi.html

[D08] 合并两个数组
来源：http://dali.chenjidiqi.icu/Article/details/gtoeapuzph.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtluenafzr.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtneddwlrj.html


<!-- 参考信息 -->