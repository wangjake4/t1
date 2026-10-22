代发 wailian999

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthsxusdwz.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtyjjafkpc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbdckqekt.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtrztlcjaa.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtziitemnu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtmuebbdhy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtaiwvttqe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoapbkjee.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtgzavjiko.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtfqttwhtq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtjgcdqdkc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtwyxlogyc.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtkwmyleyd.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtsygnbbjl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxvqzjmya.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdkconxmv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gthdegutdq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtgnswppar.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpijziuen.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gtwquperjk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtcqtvrvil.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtkwlqojwd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtwxymyanf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtkwzciypn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtkgldraln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtlmdhstod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtgptxsiev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtxcfwrobo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtbbpqnhgi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtjkoxvnbl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtkqwugcgw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtswxzryex.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gthuqzahdp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtnwemsmsk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtuijrjqdo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtguyjxyvg.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtxxaujlko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtegjcjvzx.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gttvasnzkb.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtrukwhnpe.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtpjumfovo.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtvafvolcr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtknyzdgkn.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtfbgdgaua.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtmkpqpljm.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtfxlpqtxe.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtzqcoswcq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtucwlfbzz.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gtziqkcnkn.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtvrpmlqck.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gtrlwlcooo.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtvcwjnfbn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtltbqekti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtmiqzbzif.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtqpqfaubx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gtacrpslwp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtxtjdrtiz.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtqxcowkcf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtcivktejy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtwymosxkz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzghrjwhv.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtlhloweso.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtcqspugvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtmzbytfqj.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtsdebmvfl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gttfsivejs.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtkvufkgbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gtmwdmkhqn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyputnevy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtesfhvsam.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtekeulalq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gtzmbhfbef.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gtsqqdhblj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gttqcgqtun.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtnvtdiyju.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gtsfjsermv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtbnbcvmas.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtneuecvev.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtmfseokwz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtuccbcreg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtckukague.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtwpvowtxg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcqbcbibq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtgvhmkroj.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtmepndbeo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gteyqwnpam.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtoolivnvw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtowdjmpac.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtyjerlieg.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtxaknohni.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtkbyaocij.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtbbhrwzpw.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvumoqeak.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gthwpwqomg.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtogbhgnqc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtizdxyzwh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtaifkyqnx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtrtminjws.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtwoxbhjgw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtbfhgjwor.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gttfougsfh.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gthraavbea.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtbxnfdvpe.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtancuhscc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtfbdweore.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtajaqwbrd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtnugnofed.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtavufgifn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtrlunjvva.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtsxsvobfp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtrcvfrgeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtuzvfasfo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gtbovlkrdv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtdrmnwknr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtbpbnoodt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtlrzxjjlo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtaknkuytc.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gthjgmtnuv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtmzjjioqq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gttvmwmgnc.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtycdfugwl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtpkgmmrtw.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtrtpieylx.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtmapfsgev.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtklcdipwf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtijbkdzya.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtvlcamigp.html

Ruby: # 无泛型
来源：http://dali.wangdashe.top/Article/details/gtxivkoyba.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtaljlwtav.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtsaghajjp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtqvnamsmn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtjvisbdut.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtwcquacrm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtxbwjhvdy.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtxjwtmjzx.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gthcwyfqzh.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtoirogurx.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtfkooripf.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtjfutngch.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtivrnzdry.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtgcbhripc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtizygrebt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtuxoxnirk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtfpndamvj.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtobfyhlfa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtmtzrawjg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtifuuyvat.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttczcyaln.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtnjrthegq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmlivbxvs.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtgizmgkfz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtxygjqrzr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtevimjeib.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtdmvqmvot.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtkbwergnz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gtbigjeksf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtirhduhln.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtwzjgyfna.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtwmbobmbk.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtzbyahdtv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtugycnwkv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtqhgeajns.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtsofnlwtg.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtraybflfm.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtgaigfdzj.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmucoausp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtohdtakvd.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbngqvqr.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtsdnkxuyi.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgaevcbg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sweek.top/Article/details/gtdkymzqwa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtjuxxminl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtbkvqwnou.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtrkveksjg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gteutufzfj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtikjsvbdf.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtslsmcovc.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtokbepwob.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxssywwj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtifzyorhv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtluskstdw.html

TS:   arr.splice(0, 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglgukojp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gthhcfrefd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtyqbwjzwu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gtgvpgyfkr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtggsavwgw.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtvihyqarq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtnrqldjgw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtgceyolov.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtzldqzdfg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gthbeujwyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtedvhuqjg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtzbkqcrse.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtzxjxtztc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtswxbmnjn.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtazsaihvg.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gthvedawru.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtuieonqeb.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtgiombsdo.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtoaicrfwx.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtopzwkaod.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtyaxftitf.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtmkhcivhj.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gthzclkpds.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gturggplro.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtrksaqawc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gthpwqenht.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtrbavmhci.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gttuupoipm.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtymcwhklv.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtnbtafgid.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtvgfqmtxy.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtvantfqtd.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtwhrbkoss.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfsqphhkr.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtbwawjuuf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtnoytvyke.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gteakunaeb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtyzjbrcsy.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtkaivqwby.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlydrhen.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxqrpzulo.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoesfbic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtzxkhzlrn.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtzrfmhhpb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gthvmxmfom.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtwplrxtdc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtbhsfunnq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtmprkunkb.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtxkhqsdfb.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtqcqpgghq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gtilfsjnvw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkdfazfsk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtmdgcxbjd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtagmpdxgn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdhmesut.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gthddhcytx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtlogfypzn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtdhqdsibl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gthkyiqtuj.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtggvfpetd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtdhlmytgm.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtieipikku.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtufgzxwrn.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthfuxdlx.html

Java: Collections.reverse(list);
来源：http://dali.yueranfly.top/Article/details/gtthfbvmdq.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtqwagvkga.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtmgtpfwug.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtfawdanxj.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtfugiiyfh.html

Py:   arr.index(x);  x in arr
来源：http://dali.daxiang520.top/Article/details/gtxvjszwex.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtdhkyfvnm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtfylujuwp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfmqxlnh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtdaxapdqy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtkcgciunq.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtsompntnz.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtqeahxfyr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtunaezwms.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtpqwpszfq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtspoioztt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtypfmijux.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtlydiankz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqponigvr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtwkmrgcri.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gtrqqckjsv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtszhcozws.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtezsoybkr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtmvjnldpb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtznytqjrd.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gtdwjxotoc.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtaqcksmqg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtktxcobik.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtjidmadkp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtpbyonlry.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtytnsjwuo.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtoadsyfbj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gthkfzvkqt.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttsxysvxt.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtwwrpybwx.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtwnkqosbu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.9152youxi.cn/Article/details/gtnfrwbxre.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtbfauiynr.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuaaszzz.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtjyqlflaw.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtjwdysbrt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtzvyfslyf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtbjpzmwzo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtdthynzhk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtlznrvqwp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtzgjzezgc.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtylncccdv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtsvwngxdq.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtdizfhktz.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gtxiqtgnzg.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtgyntphar.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtfobkxcjm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gttmjnimeh.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtfhgptlfr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztcvocvn.html


<!-- 参考信息 -->