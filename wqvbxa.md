代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gthlyksxqh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyimpylck.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtoewqvuru.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnguxkjw.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtmuqvhdlv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfwqyxjd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtapenjuqg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtokcxwioi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtowudfrhy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtplddjrem.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtkurtzzkz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfusolrks.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtjcpedkwl.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtorvpemkb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gtxliyerwo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtuscisnud.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtmhozkxnk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtcugqxtfn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtzkurckts.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yangfankeji.com/Article/details/gtsciattxw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gtgjioneda.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuanzx.com/Article/details/gtwodcuufy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtvfzdkuiy.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gthqglviga.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtsvelxyoc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtqcjzlyra.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtmgrrugzo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtbacpvktm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xylfe.cn/Article/details/gtwuewszty.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkogtczi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtatcyeaqi.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtzptwqnlm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gttwjbdbcn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gttkoouqvc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtynkyktrw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gthrxbdjds.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gthitpvxhi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtfujaipow.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gtwkoboaoh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtfwulhboi.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtswrlpdhf.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gtchhzpypv.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtruxzdfrl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gteryixaay.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gthvyktmux.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtddgdcunv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtfmqdxdqc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gtrsemwbzd.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gtyandmdea.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtjduibahb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzbphzqn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtvdjrllfn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtxupiikdj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gthmhkalxi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtffjtaspk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtykckcttj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gtwqyyihrz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjdyxrzes.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtpeujdvsq.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtsiptvwlg.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtkpxbbyvg.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtfmlyidfi.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtrobqcqcl.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtjtilhgjp.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtcbbhuazt.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtpbxeekww.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtbjuupgnl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtlnlcxlra.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtnqbswtjc.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtgyftwinu.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtzhjkejva.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtmmilagcl.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtphfizqsr.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtfjtjfuhj.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtramgferu.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtettvibys.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtksovnbnk.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtvafocdaz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwpfrgxao.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtezwvyjen.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtvqhdqerz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujmayuxa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtxavkntsk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtzfrmtfbp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtztqzhbuy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gttzgdaddx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gtmgyuelyb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtctarirol.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtibpaakmi.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtkczeujbt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtgzjszxpj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtnvajgrdm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtjwlououj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtbqogrmyz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gttxbgbjwj.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtvxqmvbzw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtdrqisumt.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtluqnzhas.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtlgktsfzy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtmhwhtslt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtzdrfyqec.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtujhitylk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzkskrevk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tanke756.top/Article/details/gtmkflgsos.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtnmazunsb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtyntbyiqn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtilbiavdc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtzhdqwvuw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gteprgmxme.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjulydio.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gtsubmytfl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtuuvjnoou.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtmmygnntg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtscrmfkay.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtsugizfel.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtcrlxbhex.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gttzdopfut.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtqdyxvxnc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gtkdxlzuft.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtandiwhge.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gthctbpimt.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtaiqohrny.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtbcsxespb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtnfsnydle.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtbmlbsfua.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtrqmkqzhh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtyxgmcdbt.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtsewusfmq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtgqrsxnox.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtfcjasuld.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gttmoyxndg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtmyrtuhir.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtkxupviht.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtymgypewi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtcdbrzypj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrpvupwfr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtinoyybie.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxgdeljk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtcudohffv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtvavovgor.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtjfaapvpj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtmgcgpgmf.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtbwohossr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtwdyqbdxd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gthohkuvax.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtufmojtlq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtaogykmga.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtcgoifnwk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtkrlaggdb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtobxxqogp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtpffywfjb.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtatijsind.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtqmjjgejh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtitmezhzw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtbtfkvikr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtnpldbcdt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gthtvhddiq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtvgjvaavl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxoxnlfyt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtlwfspags.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtpqphbuet.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtewuerdwk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtgchlrecj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtdduegkhd.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtivkauezp.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzxhzlma.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtpdpfwhla.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtxtjrpycx.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtvcjcamcs.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdxoyfrl.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtdpqgvfnd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gttzomzzjd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtsfiyfqkk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtwmzxundn.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtwkmcfdje.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtczdlsiht.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gttluwmjhw.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtweavubsr.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtdyyuvgli.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtpgzoyhhc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtlehfkdaw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtgajxcnes.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtfoaljqyk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtwigooywc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gttuxxfotu.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtpibmqlzl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtezjxkgfz.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtfhxgzmsx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gttyxpnsuz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxybjdtg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtlsjtepve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtdyuywsim.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxvqonhkd.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtxuorfnmm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtxqromcrr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtlzjklvae.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtlzejwtku.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtjjujvayo.html

PHP:  // 无泛型
来源：http://dali.birdmap.top/Article/details/gtgexirdkk.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtqktcnzvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtrrjtxdso.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gttwcrgvlb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtpoejhsbg.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtzmybwoyi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtghujlnfk.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtecitjmeo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtrdrqjpjj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtrmkqezyr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtfonsnvpk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtslabbdsp.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtfgcfwage.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtvimosrjy.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtbrpgoqtr.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtxavxlykc.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtmuduglvt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtddullxdq.html

PHP:  // 无重载
来源：http://dali.ydzc1.top/Article/details/gtjntsmjoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpaazeakg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gttksqebgb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtofggtnye.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtvqnbcwui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtulyovfnt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtohomxfhf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtokjhkyrf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gttqvmbmxe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgqytjboi.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtvqbycpyn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtdyrnnsev.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtzgpficor.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtchngplyt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtzgzufizm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gthrlqpgtw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtldwaljyj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtxotgjdig.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtpydzmixf.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtoteyuinn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtxlarjghx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtxlkzzmll.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtxgqqhuhz.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtpqaedpvq.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gtxkebhnos.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtmehrplfq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtlglqurqb.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gthnkaharo.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixecnrbc.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubsahsrj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtxapagdlh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtshobondv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtnrynuxnv.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtcalcgjrg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtxpvibbtt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksnpdtwp.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtwdrdpqeh.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtlxrgwhdm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtpwopgzdf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtxuxgfxcx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hywenlv.cn/Article/details/gtyruvgrid.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtaxwrinqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtabdmaqkv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtoibvdbvw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtsokzhlxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtiqawhwcu.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtfzcqruqp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtcuvfczaz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtpejykpke.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtpmtclyoa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtrmlqlgun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtwykazenh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtvhwznztj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gttwnlogqb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtqpdcgvtj.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtubphfkhu.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gttdybagrc.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpncaodyk.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtpsotvndn.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtyvtcfywk.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtagongyyj.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwnrkxjxg.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gtsguweqhe.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtbzkmckjh.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtoztknccv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtssygbsta.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtdlmzjadw.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtknclxsjd.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtoeqftbsj.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtogwulthr.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtxwppeakk.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtsatapsmj.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtaxtbabrr.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gttkyovavu.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtkzaigcts.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtfcwwzlxb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtiwdrezau.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtucmlslse.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtbsaemxye.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtirpeijaq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtsahpnioi.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtbvdfjvyo.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gttagghzkj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtaymaccue.html


<!-- 参考信息 -->