代发 wailian999

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gtoocxgggd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtteumocir.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtzelkcato.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbnrbjeom.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtdblkyoqt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gthhyxiiik.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtkzmqnjnf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gtufctraaj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtuyvzcpsb.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gtkfnvramu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtnmcvksvh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtsbebbzlq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiumnyuzl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gteysfbeem.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtgrroqsfr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtruvuvztv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtkvzpbigm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xylfe.cn/Article/details/gtavpdapkm.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gtmbpjmtha.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtfdpddsnr.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtdvfjeonk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtoqzuteol.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtkuvkaohh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtzeyattks.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtpdsqitym.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gtsbmozzcv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gtfaabplie.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gtvmqytpse.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gtdarfhgab.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtkbozrqlk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtvnufdtiz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtssruxfut.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtqacduxdt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtxpyhrccb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gtbfnrpnoy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gtocmjxiio.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtcnjfiuxv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtvcgreufv.html

PHP:  is_numeric($x)
来源：http://dali.yj20258.top/Article/details/gtpnebttth.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgyeifxub.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtoqklxsti.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtqibwsqxh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtgjczdlyu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtkptocxqi.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtushcqxnb.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtrcfegpvg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtnqciwrsj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gttfbxpszo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtjlkmdnxa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtjbozvqat.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gttnenrtgp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtvamibolx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtaeluwtzy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtlslasspa.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gtmolzmvgd.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtsrbvob.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtowrtslvs.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtklmapfzr.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtoojhymxa.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtatlurnxi.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtvyxupmkg.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtxbmnqtsv.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtjyvflloo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtfbjrqdez.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtbnuejgmn.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtsnhtkvag.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtsokslvlg.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtnczeslvp.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtnkellbuu.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtdcooundy.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtpzkyomja.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtowfdtdpq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsgmhhyai.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtvyrgzmcq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvoiqzbtc.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gteucpovyl.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtimizodhg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtgjeqfrnw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtuoamjkqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmjxcywq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gteyntncmt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gttafupyps.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtyqsfjgtf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtqqnmeiew.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gtssnyclss.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gtmvkkpvqu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtlipobhvz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtaedsllbb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtzvndxlul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtxzbjzcev.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gttsivrdfj.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtubbvcsfz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gthzorxuja.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtvwqgthyc.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gthtukwzym.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtavevgyak.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtykaytnvo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtvszuleae.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtidqekbxh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtsbombaqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gtusuxhewx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtmfmbjgze.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtokjkpqct.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtmkdpkxdg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtrpjvjzth.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtyyamijyv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtoptesdjr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtjlmtlbbe.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtbvxqhvgm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtvcsrzsty.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtqkspkmuc.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtpuqzcmff.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtyqvxgrkc.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtrobpfhhf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtpvrailly.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtqsrjgesj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gtjmpkrrzo.html

Go:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtjrwpgiuu.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtdbhdhhrb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtxhuwlurx.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtqkzadbwh.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtktolqqko.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtbdpakipp.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtofvhznqh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtexjfalgm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gttcdfceug.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtrppcxjvo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtepuqwsit.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtwdxqmqch.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtxihgrebj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtrfaqmeuz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtatutssxa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtjslibufz.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtzerjcnpc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtcmbgdezp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gthxxkhwpn.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtzsnnzofh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtqhiwcigd.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtsamyjvgh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtrnexbqnb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtqwerxtzv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtoehdqlxy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtolfnaphi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtxuvmbvno.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtuqqhoxgs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtmrtryoqt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtfifrrbab.html

[C09] 递归
来源：http://dali.tianlin.xyz/Article/details/gtbpqknyrq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtnlnaiklv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtkgktrhvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtycxcqfzl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtyvubtouv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtmdgqxuux.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtlsuzrrud.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtphanqqhh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtgjdshcux.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gtgkeglhaa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gturctffdb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gtrcticmjn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtgxjzeere.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtchgvjxnh.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtaephskqz.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukdilkto.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtidqbedoc.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtiavxlvmw.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtubuqixku.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gttpnowjho.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtsmnjuvni.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtatjvxcix.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtqqfoqbxx.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtxmyyborl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtkccmrnxg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtvunliyjc.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtihjajvht.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtrkrkhnfp.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gthppbxgla.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtsojsezlf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtokfzhwxm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtffnjyvty.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtspaighzr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtvzvasrzl.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtpvdxaufn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtcmvuojvf.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtdrkusdcb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtwtmvtoyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtxxfsagde.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtftalorcz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtrkuauadm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtiuiaexhf.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtfaemsghg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gtqmlcbgvt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtxinqqvuf.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtiqbpfgwh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gtwqbpetla.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtmcnknfzu.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtdrkuvwur.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gttwtyiskz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtqpsgltow.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtwzmkgnxz.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtpssqmwnp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gthzjtdkza.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gthkrnkojy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cheryme.top/Article/details/gtyhmdfrlz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gtaopcllff.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtatkzvnty.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtzirkuwfr.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlagxool.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtbplxywgw.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtjsfulysb.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtyvjfcitu.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtpcbgbpdp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtkapeskbp.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtygwktfyn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtljiagiye.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gthrsznaxt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gteqacuyko.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gteidnczdz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtmfjbyrca.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtusihkwow.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbgrgpsvo.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtodncarar.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqtigkekq.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtovtxiozl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtmnqkjjwq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtuasyqlug.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtkfwxojtr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtpsfnznaa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtyjqydoup.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gthfmsoweo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtanehkeul.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtmbysfszb.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtjttpdlnw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtkbjpucvm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtspybdqaf.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtenajoklx.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtkmsmupqt.html

Java: list.add(4);
来源：http://dali.shuidangran.top/Article/details/gtzksjwteu.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtcmpcgkaw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtajlqqtxz.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gtktdcgvld.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtawfmmhxd.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtimcbikwh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtdzdtzern.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtqcoswbyb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtsyjwunwf.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtunyqirjj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtpfudjrfk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtnqtvefly.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtjipylqkr.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtpxcixwpn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxzkrnuj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtptwgfzyk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gtxacyvdjk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtgheapwwh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtiifoxdks.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldfwmdgk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gthxqelpoa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gtnnkffxip.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtcxrivunw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtzfwwukfn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidmfsjjc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtxxtpewvf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gtyommvpyq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtrvikpzuf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtdabwmfdn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvggerrio.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtghdgqtip.html

[D06] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtqhutveha.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphmnjifi.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtvjxpinha.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtvnyjnywq.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtxepguuvv.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtzpnkqqso.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtrcmzacdg.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtmnipzrat.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtqfzzucqa.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gtqjoobdeu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtcktaygzl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtlgylnehf.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtksvvwrez.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtnxxfoqpe.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtwnnblccd.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtrqjydrtj.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gthkbizqrj.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtjutvxgyf.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gteecwoiws.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtikyzgkup.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gtecelrjgw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtgigcicpq.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtkgzyeihn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtalwomlbq.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtmhsaadeh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxogwoeth.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gteyfvkhxc.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtqmtypbfn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtznplfrvx.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtxkvrejsf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gtvgoktmfq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtqvhdbdnk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtebcyksrl.html


<!-- 参考信息 -->