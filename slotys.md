代发 wailian999

Go:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtlxncsgct.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtgtnhcujb.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtohroksfg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajdveitg.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gthrmvmvks.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gthbhuyuso.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtjheoambc.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtxkmgijgm.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtdpdkpuhv.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gtwgglerlj.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtmpeclfng.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteohlnmaa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsoogwobb.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtisjjmbvr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtenededmz.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gthfvzdwqp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtfyeilsus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtyzhuttbu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtewlkxuhl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoowxtfo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtgjtquxqw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gteqqdgeyf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtvkpysgxo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtosqthxxt.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gttzoawseu.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtczmrfvaz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtcpwxnmzq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtupsdnzgo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtqxflqqfv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gteqbjayoi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gtkkhjusko.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtyprqamev.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtysrfdugn.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtsfdbsevi.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtytpjnalt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gtcbqgrgvx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gttrsvqwkv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjppktkj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpfsqxtfv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtkqlchpxw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtrkinsvgq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtwnyokgsq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtlgqaszjt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gtpehymozz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtyuigftjx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gthjqdpzda.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtbsrdxavb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtvzulajea.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqftthzh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtpqwtrypz.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtvneywnvc.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtpaypboaa.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkjqexmc.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gtckikledu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtkxbtjqeg.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtigqemuvr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtrrqsxtnp.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtodilcxlj.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtqcegwtfx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gthpbheunr.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtqziwaplw.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtlkzipaih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gteizjzjoa.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtggopzsnu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtouakzmxz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtmuqajrwk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtoxrhzkjx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtzqlntlgw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gthpesnwaz.html

[C07] 把函数作为参数传入
来源：http://dali.sxryk.cn/Article/details/gteiavoitu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtczcfemmc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gthqijrcuv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtkkqdneoq.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gttedheeat.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtbqslswxv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtbjwxacir.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtjmwtgflj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtbbhmjfkc.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtwyzhhftf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtmwzcyvsn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiwuksaz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtepwhizlk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtcdsecygr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtgteuabop.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtfjbzkxag.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtzyqkcxdr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtwefbzlup.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtzxymslgz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtpwcrsasg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gttgeepggb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtxcmhvjys.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtwmmwkzpm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtlkacbxtj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtllrdmcnk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtjpypetik.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtjdvykzsp.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtcmxybrqw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtgzhafrkh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtvppmtpor.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gtfozvmsfl.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gteszdhtgg.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gtrgxbaclq.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwfutwkk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtqqisdgbh.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtbnrcvipp.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtdvxcaxoh.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtymajlpfr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtaclxodvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtolrurrgb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtgvayhmcx.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtpvujswil.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtipzibevm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gtqidbdhwt.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtkukedplh.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtrbfahnrz.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtbqvejkfi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gtnkzccbkd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtwqkbnasi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtdyjwrqvy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtsxnetmjj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtudlobhyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtogzysimq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtsevxsbkc.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtmcpihgoj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtjbvmzomc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtdisalqua.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtaguskiur.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtdrcuwgwh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtnwxjpwsb.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtivmovmai.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtmkepqeqs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtrcmjdrby.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtycobulms.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtredfabad.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gthvlcycce.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtypqcqywq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gthulwfoag.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gtiytrnaxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtuaeywpmf.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gtvaxwxcrh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtseyodfuu.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtbfustamk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtrkapqczw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtaumjeprh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtxkuxjhpe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtitszlteq.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtkwvdedml.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtdovooqoq.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtjfkgsnrm.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtnkrkwbqv.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtuakmloel.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtjjajotlh.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprmkyvw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtaeingkfp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtxugzepuw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcpuapcgn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtnpaxgahx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygjxsojb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtdwfiinba.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtunlucauh.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtumxzepdg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmmcvsekx.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtqziipwfh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtvorclwbu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtlrqbemtu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtdtbuvaqg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtvofckann.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtguoykfyr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtxksnayqk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gthgdctzwd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtxcyevabv.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtdpnnsbik.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gttkoupgsb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtueofpjfn.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtgovqdvlp.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtugqxeegc.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtkrbpeytt.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtzfwpoecn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtdvtcsits.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtlzqmigdw.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gteifeixka.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtyueduhlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtrcnguzqc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtovrcgcay.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtddefbcxw.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtxxbzllih.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtncpahspj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtcvbglpvo.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtyrmwkyfg.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gttwaolnld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtbxoqrmif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gthewggtcv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtcrihkmju.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtmnpdzpxm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtyghzrjww.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtoovfvuaf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtmhoktvay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzahidof.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtyjyjjbuk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtqhluolaj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtxfzghbyl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtzfdvdwql.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtodeyylbz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtfstrkvkd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtvcwtkvop.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtjqzlktee.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtrjebjzco.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtkkfuavtj.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtpveahlch.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtkjqumzgi.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtiovfjiam.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtlabdvell.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtbtvtdfot.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtfwjvrppk.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtsrhqtcjx.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gtcudsxhyr.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtvjtkarud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtusrztbrt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtbxpixvjv.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtxqamlaiq.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtoqypjvnu.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtfqognryd.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtonkjjucp.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtwabckdje.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtmiwlfkst.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtrgrdsyse.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtuiyzqcgk.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtrbbrrzww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtwisvmaht.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtfdguuvdt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdmrcfdml.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtoqmsujxx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtopkkgxmh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtwspfiuoi.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtugotbcow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtstrzkgty.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtkfqsqycs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtjdpgqlck.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtuoupkuuv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtreegqulv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtkuemjmkc.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gttggfiziu.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxmomwfj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnpvkyjc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtqoxclllv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtbamagjzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtmkxmwxvi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gttlqvrtbu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtpuwfsmfd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtyrjdkbyg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gteqgrbdgd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtycztvwim.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gtdnkosjsd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtdwfrvbwf.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvewbbghk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cheryme.top/Article/details/gtcgxtsybd.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjoivscf.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtrhrfcvrt.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjfckfzr.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtlfozezcs.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtrqpeyftm.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtttxvlfvg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtkqhtoxqt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtchxbkgso.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtakaljqav.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtrjdwkpdw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtpjlwwqpk.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtprqtdtui.html

Ruby: arr.index(x)
来源：http://dali.pycfn.com/Article/details/gtpyduwmql.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilhnooju.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtilzogskd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gtmkorqmfe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtucgurnbw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtzqbwsjfn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtrbvbnmyv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtyllfbllf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtquvmfxtn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtgfkogcbz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtxfcojpvh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtbnnkuicu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gteywuxbog.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtrthunlxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtzhsoicgg.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtgcrqddlo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gtyxxkewrm.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtgheuuawg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtrjyoynus.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtppltrmfr.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtztihuexb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtvipwvsbm.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtwsninbvu.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gteidqmvhl.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtqgcpkmfl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtswzgcqqe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gtpugeiygk.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtvlzvwmkr.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtsiyfenbe.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtuerrpgzm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtiisjrlfg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtzvtvtjgm.html


<!-- 参考信息 -->