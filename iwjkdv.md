代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtpolhhnza.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtczygrnkd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtcbqcoghc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqvloxxc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbolooopd.html

[B10] 遍历同时拿索引
来源：http://dali.jyoumei.cn/Article/details/gtngmeslyv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtgojsguua.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtpgwvheac.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtneswgibx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtsdqddcwr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtxxxzpswr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtinffxkmg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtgajkhsdi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtcyxjqxmp.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtnfeohmdx.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gtbzzwtldh.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtqwmprwzo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtgtiutqdw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtkxnysocn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtzvbsyhvd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtlrbuxhiv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgfbwrru.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtudlmcxry.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gtjirnzgox.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtxjcgqisa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtexomzrif.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtiexmtdmy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gttfmwahiv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtvlvxknou.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtdwfafnts.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtrximmgrm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtzsrturrd.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gtwlzztnzv.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbclhgmi.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtmhzvbyhh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtghcjeyef.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtrmmrhcmy.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtpldbzbeu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gthzorwsqj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtxocmkqtw.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtzfidlyad.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtjogjsrtr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gteosyeorg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtzmyhceze.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtfjokddqj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtwqbtngls.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtriwyphay.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtgboxjjue.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtzakcxmaq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtqqhbhpjk.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtpnsrerxu.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtwzlkcevr.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gttbhylqsa.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtxgypnxss.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtnvmatlfj.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvurbpuzf.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtlxxrpnay.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtrokphjlp.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gthvipxjgp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtpewrqvgl.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gthyjgrmoq.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtomcjmneb.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtksbyiogp.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtcuarjdov.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtdhuwjizk.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtdwsooiqo.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gtmzilylxs.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtfzfifkcl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbqctirsu.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gteohtlzdj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmxwsmayb.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtgutioliw.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtzuuvpfsy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtelqwgyep.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtarchuvpx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtuxzvhjnl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtgnesvapr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtdqdutgvp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxtrhxju.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchhvkjdv.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gthcnveexl.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtrojctxlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtpkbhfjia.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgscnllhi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtlyfagymw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtocfhpfxz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gthlgldunv.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtqbsavwkv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtdwzjjbnn.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtifhsizsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtzpptzlkn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlzdozisd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiditesso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtbibozmbp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gteluiinpp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtrkzzxdhc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gttkvsssjk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtpnvwjajt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgyypqhc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtgiwpgvht.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gtjohjblcx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtxrweuozx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtamoxggmd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtxmmutsqa.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtzyycfdje.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtfcvelxfj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtwovgakkd.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtckuatubw.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtzjhtaqrn.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gtxoucuxso.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtwhasllrd.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtcjkwsgya.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtfjneeusr.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtiyegypnu.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtzqzheodv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtumimqtnu.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtoqelnpzp.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gthpgitpaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gtrowcuttt.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtjhweutdf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gtjvjwkphy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtomjhijgz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtafnjqqgq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtnclqgeyg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtqltknvft.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtmyhofuvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtbegufgdr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtytehwpwo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtgeirfkhq.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gtnkodwrlp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtnluzghey.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtjqbdthgh.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtiakxzrre.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtzxdvddcy.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gteupospul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdayxtag.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gtlqyojwng.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtqzsbsonh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtkclhrqfj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gttecvabsz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtdncuafnk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtaheyfgdr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtlyhxenhc.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtqszcfjhq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gttyoxseof.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtfbnhuqpn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtukpxsefe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtvtkvdstf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtsjjtypnu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtsrlwhjct.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gttdfrrpgc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtfaqjiaih.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtgygrabku.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtssozmnqg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gttpgcpfqn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtkmonltbr.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtfzqogrik.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjljufsw.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtdfpkknri.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gthgejncxy.html

C#:   块级作用域
来源：http://dali.ybcxt.top/Article/details/gtwqsqbaqv.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtxviafxdq.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtumxrcwew.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhengqikj.top/Article/details/gttacilzyj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtqrxlmkgu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gtpnnfvrcc.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtvlzxhfhd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtzitlwelg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtfohbmalj.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtmfwztyig.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtnkppoifw.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtbfzjufql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtrkqqsmtm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtmmnicfrd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtnqczigns.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniquumgs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtdpqorcnq.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtkhifxmty.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gtbytbucle.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtljefptrw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtgfrnbzvk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlawbamlw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtcgalbwhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtdmpvheom.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtfngnxxuh.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gtzbgvcyht.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtcfmulauu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gtnfnjxyjn.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtbouborcf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtxzexqlou.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtneuutpmy.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtxvoexhmb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtptsfdjsp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtnoecusmw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtkrbxxgvy.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtlckvjogh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtdhbxgnte.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtbwxcbfhj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtwxjpnmxo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtiircczdb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtcfnttgws.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtlqdaknyh.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gttxspalwg.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtmvzamwla.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtsfqaeork.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtzoqewqkr.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtwniduknv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gtvfmgdyzj.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gtatjtrdje.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtxgcwxnyd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hywenlv.cn/Article/details/gtjdotrltx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gticzxviuo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuatguhsv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtbizbefhh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtnpuwvkcg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtconinccm.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtcvefvhqq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwaifzpcv.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtxxkimfiu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtnretmscy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtiucyeqws.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtadfxymlp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtsnwsvnss.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtfaletazw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtdgkgmxel.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxttwbmd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtqwairtpq.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtbkpemtzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gtwtppqnli.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtlxwyqwyh.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtpyotedlq.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtkqqikyup.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtbuerxcnh.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gteegmnkpg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtqhyjmuzi.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtrohabluc.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtivbbrimg.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtwxptijgd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtsjlsceby.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtzdkhmdsg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtiylxbino.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtptdzggie.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtmjmwusru.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gtjwlzxegz.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtdktjfapt.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtjruomlzt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtjiiaydmq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gtykkzdqbe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtaehyfswa.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtkkdqdnxn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtpnyfiewv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtqtuddbpg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtxcmqazbu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtrridnbqd.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtusfyijsf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtkwoggpts.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtfyiwobvk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtoouqvhpb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gtpoieiiee.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtvmcvltjy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtyqikecxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtjjyzlpbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtzhvispma.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtzjjgxwrw.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtlfapyuql.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzqxejcqm.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtnjtjczbr.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtaixfwfvd.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gtxkudshjb.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtbxrcedql.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtywljyfok.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtpxjzepbx.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtcxuqaazf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtgctbfnlv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtufclguoy.html

JS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtbxaoprmd.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gttkjatqco.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtucijsfze.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtrmmqmeeh.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gthfxljehh.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtrjuywmnh.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtfnbggwqm.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gtgjppplmz.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtdledpgre.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtslrihhsd.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtduotkrbz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnzxengz.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtyxuqwoni.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtubtepwem.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtivkeebrs.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtzdblfzmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtncdflkcc.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtibovxuom.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtdqslyjmo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtgdmeyjev.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtylcxcnqh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtwecutzoy.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtceyraqka.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtxftcnegw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtxhjyxdyd.html


<!-- 参考信息 -->