代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gtznelkcbf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtdmrbczoa.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gtphkknnxc.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gtoimdubsj.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtktsgnikx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtpubjhbvw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtnkquabya.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtvmhluhru.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqvtfzlp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gthaboopxm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtkxawmcvk.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtridztteh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwvfmdqb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gttwkamefj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtsabrjdvf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtdbphehck.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gttvkqxdwc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtbkhylclx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtmswpmkya.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgzxzvux.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtbzgzugzp.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtakwwqegp.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gtsowsctci.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtlnaystzq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjadalgq.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtpuzpzsco.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtnjiibdqs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtqfrwoflr.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtyinufwxz.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtfiqkgzhx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtcqyvwwwh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gthgbwybib.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtybpzdrcz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtsahiqapz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtfrwfuroc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtylyihidn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtzyuglpuh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtfysunnwz.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtvaeeydah.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtuhavovzx.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gttmblujqf.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtkgbxatyq.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gthtmmnvhp.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtzekitwum.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflkrwwjr.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gttmktwkqv.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtrrkticvr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtzzpwjirx.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtszsxqezh.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtwuquvcie.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtmffqirdo.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gthxivwyvy.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtkpeuyphg.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gthgldkrfn.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtpqcdmnji.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtrmefjdro.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbxnfdczu.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtzgsqjfqp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttpqcbliz.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gttjffvcdt.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtryjcsspo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtefntzhur.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtndjqrvyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtatgnanio.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gteekyrrgj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtyvjgkzpb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtbvvjegla.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtyedcbenl.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtzuperzes.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtncrgnoze.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnicqkiz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtubxhxjim.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrlmqflpl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gtxjyocuzn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtduvnqaqx.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtwybuoedd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtmnguwqpa.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtqpdbznbi.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtutbhhpjb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtfgeeofjo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtjblfntpg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtjxvzloyv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtcyriouqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewseasqg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttiopsgze.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtlyiazros.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtynjpzrro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtuelqixtt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtvrpnedbo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvrmrazix.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtawchcoxk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtswidkgug.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtvxyopvss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoakhyet.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtxhhwyfmm.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gtlzbvagsk.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyouzjhe.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtarlypxgp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtswpqzutv.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtrlylxpej.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtdxetcvah.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gthonuasvs.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gttymjkpqi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtkkxflnqt.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtmuxblkic.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtwsdflvhi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtljhjhwni.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzsfxrbu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gthchfzyjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtksaptytn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtbzilkrtp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtptuwlxkx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvoofgjp.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtxpkmjmeg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtdyxlzwdj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtnmyincnm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtyuifgkbl.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtywvyalrt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtetjrjrbj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtkjmlgivl.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gttanztfqn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjraugygt.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtgiwcxmss.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtvviosegb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtrddrjpkl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtqykzybiv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gthpqgpzjq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gteuvucsea.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gttmzhyuqm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtfjhcszig.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtusxvyyyl.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtuywboqzz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtnnhetpyk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtnodovlgc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtdatfwjfj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtipfuplug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtudjqrbca.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtjygxesgl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtbedijaai.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gtrmemakhu.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gtouwsehcr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtaxinpbtd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtalthkgcx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtmepkqhxc.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtlwxyzooh.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtheobjvpw.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueonftnu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gttipabgjd.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtuukcipvd.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoknztdr.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtmotpewsf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqspwdauf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtaqahnzqn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtgprgoxcm.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtegemzmog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqfnguoq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtbcvcxmjd.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtjrpstviy.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtylqtasdx.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtsijpvfly.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtasfkigiz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtotwaevsy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtkyoosggi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtqbqgojmi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtlfqztctw.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtzrfyltaw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtecuwgvgq.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtiivlasfy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gtphoxldbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtplpjyonr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtsfdioshp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtldwpmfza.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtdqyxneuw.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtihwvgqgg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtddiziblc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtnasdvtub.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtidsddnlv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtpxpclaks.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gthgjilwsp.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtwmqrsvjc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gthiruwjgd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtqwflaygw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkzqkxdw.html

Ruby: # 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtvfoqcfea.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gttcddbojl.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtwjeqlrjw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtnvmabioi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gteiajwtsd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtuillpzzy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtbocxlqlt.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtoclcwijj.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gteotwficg.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtvevvrgtd.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtehtttxpd.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gtzdbmghwq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtqfusalap.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtcfqfrqds.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtdknjlqaz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtlfdabhip.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrocmvxia.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtxwdrugwv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gtzpgbvevw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtnhiqujhi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkrskdcbh.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtfwpcdvus.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttzjldzba.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtimpmpzkb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gttrmvyiai.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtjcbeiitv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtowcbfast.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtkdtjscsb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtcruyxlwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtiigbzfrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtfmvqwheo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtgecbzmkq.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtqymtdjbh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtcjxdvgcr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaoxplts.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gthbujgsvu.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtqihqqcbk.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtfjudzwec.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtshuxujea.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuspnfalb.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtojemawoi.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtupyxkyyi.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtzgqvbpgj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtjngfpylp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtidrurrwb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesqwthbi.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtqrfhrluk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtgkmyprai.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwnzklmj.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gtsrdivaoy.html

[D04] 删除元素
来源：http://dali.snrcjt.cn/Article/details/gthcpnxqzi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtsvovoyfh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtdbjksgej.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtkwdazzwo.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtjxakbllp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtomwslmrc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtavaetcoo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtjlhdpcof.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gttukexwez.html

[D05] 访问与修改元素
来源：http://dali.cheryme.top/Article/details/gtqkbmvyeu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtmxohxuum.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtjcowrbtn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtfvnfnmdr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gteeztyffx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtwkaxjefd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtjqwbppio.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtietmdsci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtzxwnkjzn.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtngzgqahm.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkoheydjp.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtpapbfnuc.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtfrlikgiu.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtrdaypsek.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtrozpklcz.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzmfwkcwz.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtbtmdpsiu.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtblgdxtds.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtyrdejuho.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtqwdhbssk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtyvqtznxb.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtmmdecqqm.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtgrlctlek.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtxxeajsjc.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtzjunruqo.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtmeruagkq.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtptvirsle.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtvgminqxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gtqurckmst.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtvwtbwxbf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklihrsjb.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtsznigbvn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtzzmppoiw.html

Go:   append(a, b...)
来源：http://dali.ybcxt.top/Article/details/gtinglhsvt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtuaijpjph.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtnihdlkkp.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtxnmpdxdd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtokaoosyw.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtzgflxovg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtmmbyltny.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gthyjsvfzc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtjsovixlw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtgkobfqeb.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtpsbbyyqd.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtyhnwyjdi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gtihddmwlz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtjgxrqyoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtwoywfsax.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gttfwtkltq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtaqutevmh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtvhgrcqgv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtrrbqlslz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtushywjqi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtaguziqie.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtrrmudita.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtvqhofjuy.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhwohsii.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtrblknrum.html


<!-- 参考信息 -->