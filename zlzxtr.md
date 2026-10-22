代发 wailian999

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xdbiszew.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gt2mourvpty.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2txzscptk.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2ikzwnzdd.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gt2wgyggzvz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bsbsywih.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2elkdhnyo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2zgxqhkdb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lctpilfz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gt2ytzzcriw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2zbqpwasj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2gagxnjdq.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkzkyofp.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gt2hzkctlto.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xxwlzqib.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2ipcrejcy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljxxaqhc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2mqircgeq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gt2azjurvrk.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2nxoidvvs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2gcmabrrw.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2xpgwwnak.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2zyvcxzvh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bstbewvz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gt2bumxdhsd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2swvsrzxn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfkwfeyi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2gvpfuths.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gt2zkjlqryd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcepzwkb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gt2mchmgbev.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gt2byhbwxpk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2nusautlf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wrexxaac.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2acjygxgb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gt2fhgwxrza.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2ocnhxuko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2kcxbnczo.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2qbgpuvvc.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gt2kebnsozu.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2yiehjnzu.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gt2vsfngcqs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2clxzrtqf.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkdfegir.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gt2ptmvjhzt.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2xgpoxizl.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2xmimzqnm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gt2zpxpcrfx.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2lemaafdu.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pobvmijb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2atdjjugc.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2jylhhkmy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2hittklxo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2hsqbfzpq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2lqakbehe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2ykzrgimk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2aohmozgn.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2dwcmdhml.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gt2hbixrsmb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rabmnhzl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlndtlvr.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2maubmrgg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2nlpcgyyg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gt2fqiirmqh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gt2aizsllol.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dueggpkf.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gt2jlfdkgqi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sysykeji.top/Article/details/gt2rsuqptor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2nljextgs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2bjvzlxdn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2zavilxor.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gt2uhzvslwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjlbitaq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gt2rivezrbm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2opzzvmva.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2ntitripx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2qcrtuypf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2kwepaley.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2enexjamg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2jdihzwry.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcmekjwe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gt2ogggirql.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cndltrvt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gt2cubkwvue.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gt2wnmqxpwe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2vwwchwnz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gt2jpjoleuo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2gklswvot.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2mkpyigot.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2pndxptbg.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2ybgmjprq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2wglnfejb.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2ltnyqgoz.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gt2srdvydls.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gt2bfwirpvh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2jrclbvpm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2sidnocon.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gt2uzgsqqun.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2eqdmhldn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gt2utwabvvk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2fpkofpap.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2upxrfgfl.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2egagxrlr.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2qmmrspql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2hotwkrhd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2eadcttld.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqsecwgn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2uxowscct.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swvfkjmo.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2vjbyhegi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfsrxcf.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2pypdvgwy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2yrtgmadm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2vxjvnguk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2tojwkdcc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2hhudkgis.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2wfqfnrtn.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2tdeptlut.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gt2agnpxgvi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gt2zendwvqp.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gt2mgiqxtus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gt2rxwdicnc.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2gskeoaoi.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2xtmqftrf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2mhmehczo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gt2xqvofmto.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gt2kodyjkvo.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2hzfgglkg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrhezwhw.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2elzisjmg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzlvvcur.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cptbnlve.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvqlslza.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gt2gcxagirw.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2frzqjlak.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2rchizprx.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2otsmcoyk.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgyregji.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gt2sjwguegq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2zaxwkcju.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2jdvvsjqm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gt2wosdwhxd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwhsjvgm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gt2yuryvjbd.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykdkkeis.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gt2fyxbnuek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gt2duvmvrvm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bwpiqcoz.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gt2ihpuizzu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xetqvmmb.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laemddud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gt2kbnoaxwq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2ayasznyb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2nfafqkgj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gt2prhghazy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gt2iolixcnh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2dzueovus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuxming.cn/Article/details/gt2mdedovyu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lokntbyx.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gt2xnrlowfr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gt2ohemvyqg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2ctylqlsq.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2gakpzipk.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojbhroli.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gt2qqrmlmjn.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gt2bdbfjmmu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2hjkuxytn.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gt2vxfhwahi.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gt2awmrmgff.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fikyrbyf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2sjnswgti.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2jcpxzzkg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2vkcanxzc.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2hfydxdxr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suosfymj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gt2ybqvafeq.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdgbhzfj.html

[D04] 删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2azodmxnz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gktdatxj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2sesinkzz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gt2zappnyhc.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2pcfbzyrp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gt2pmfoqdmw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gt2hakokcac.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gt2cybhktui.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gt2orwvieat.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gt2qyjtudce.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngsnsszl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2pzwupnmc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2xuijqovb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2ksjtfzyg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2vzyrzpgc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2aszfrnng.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2dyposrlu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2stqdqogc.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytftcqhs.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdkbabec.html

PHP:  count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2civkpsvr.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2kaalvuqa.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byvznxxr.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gt2bevdytdv.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2jfyxmakq.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgwhmwsm.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2bciawdsv.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gt2btyvtutl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2lianwjom.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2efnpsfpa.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2dvredvok.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2qfocseaj.html

Java: list.subList(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2ktnfpsth.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2fletfcaw.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2kyklkjiz.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gt2lrezjbff.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2lduthhoy.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gt2hohgfnqy.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2cajrufyn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gt2haxeohmj.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gt2yzvrtotr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2zbrnhwqc.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2hrqynqtt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gt2fkrdinwi.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trnmcanr.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2sndhfjdz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gt2tutykbnv.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2uysuklsh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gt2fabykoxu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gt2rgdycnip.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gt2ssdhepwe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2ucsmonzw.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2mizuodcr.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gt2roqgocpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2lrhsnuqx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gt2pwqqipsn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2toicfszd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eilmhtis.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2cbhsktel.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2zfmlhyxk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2vvtfknkn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gt2ukggmdtk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2zzagvsyf.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsqmnoig.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2mnmxcpip.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2mzinoycy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2vkvepyky.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gt2pkbkliut.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gt2rolgcrct.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gt2spnmfyom.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxrtjxkz.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2qqlncwmu.html

[D12] 查找元素下标
来源：http://dali.fzhhl.top/Article/details/gt2bhkhvdlw.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gt2fqdvnnqa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2locpkhuv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vksfofyz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2qhwgmbve.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gt2ehwcspsh.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2lxsxplnx.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gt2jhufebez.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gt2pghelnoe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gt2wkyofeiv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gt2zwvteiri.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2qxyqfjgs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2ritxrkke.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxmoguiu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2tqnktdue.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenzaomai.com/Article/details/gt2dnbzahyf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2qjafdkob.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2onapukvy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gt2zcnqzvbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gypsgmxg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2bmohuefb.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2niejbefp.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdmodvhr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2fbdqrlbs.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2ydlbdoio.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2hhscnxyn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2efwxjqca.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2xicxnyby.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2nvmdfvor.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2pmistuyh.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2xpcnyqvn.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urlvxmzh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hysaishi.cn/Article/details/gt2apeghwdg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gt2ocbgzdxs.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2wnogfkkh.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gt2golnhuxq.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2dpwefojo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2abpzxyzf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2rzdepwfu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqmmvqfs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2pibvzsfm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gt2tkhavqgy.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2gghucnio.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2buixnbwl.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gt2qmefprmm.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2esnaeoxp.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqoywyhq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ijhhaxme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gt2fxezvgbw.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2evhvxjnv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gt2zjeuiwxa.html


<!-- 参考信息 -->