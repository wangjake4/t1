代发 wailian999

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtzpputvzl.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtnxkcbecb.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gtsgdapcsn.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtkcabbgbe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdmotgeki.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtovpoxcqg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthfehrsbq.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtvpyyvsrq.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtbbehkift.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtphbqfqdw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtwodvzauc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtlzvwnqch.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtqjtopqjk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gttzeoroyp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtxbtsncmk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtutjdndwo.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqzmebfa.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyefdkdsu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtkjihvkxd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtcmrfdhfd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtxjvfsvcs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtmqdbyjgj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtubzetxuh.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtvnrizfho.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtxspwcvcb.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtzhulesrc.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtspbdtrav.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtxvvueeyy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtsjblldqz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gttfgiicnd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gthpoevdvf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gtatsjmqwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpramqoym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtcxwhxewg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtmtirhooj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtbfkhmxwd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gthdspdjlt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuufylxjm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtwkhncmmx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtmvybjiuw.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtgyjmjfer.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtpfnxbmcs.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtjgnbpnow.html

[C05] 返回多个值
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaztcgry.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtyhmssqpm.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gteapxxftj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtebhzoywu.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gtzryqocrh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtrzetcyzc.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtbkxzsyqj.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtkxpucjst.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtuhfbnkbk.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gtbgdwjdkg.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtuvtlbyxk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtntsijfio.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtuedjonce.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtxhujmrym.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtzernnyeb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtgsdkvzsi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtbcloulzb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtdiypecvt.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtsvmlxotc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtjnjepaes.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtgowftwlc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtdqmqmgxx.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtfyoqyiam.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtcrxwfupw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtchcnlqya.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gteyputrkk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtddttqktw.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtnwomuarl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtzzhnzgsj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtcsnuxgcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtulzhxiac.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtmgiluskw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gteyahgbev.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtvcuibezf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtvypayeey.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtdgcbjuid.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtxcbaankb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtgoljeerj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtebymoopz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtxjvblnav.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtafnpldii.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gthxhwbths.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtemtzpvhh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtkmgloayg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtlqjcfatx.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyseglgp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gtezhdwfcz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtbncyptuw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtcrwezpzu.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtgzkwvnds.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtffggpslu.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtoxgcdoun.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtpglqudmd.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtlvclsrzr.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtzrhukksx.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gtxxeshuyl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtsbsjxtwb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gtgjjysicd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamufdrlh.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtwlbmijbl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtaocwvgan.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ppjwa.cn/Article/details/gtkmlevpta.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtuaerzpzr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtkhiggkgo.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtcpjvvzuu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtihzzyjds.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtrfuzelin.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtdiviwvda.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtzwhvpqdo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzgztrff.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtnpdupbqq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtwchnwflh.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gtubjjqadw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gteepgauvs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtexqyjsaz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtekrcmsem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtmuoyephz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtwkldftih.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtwasmgmfe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtwgeejydn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtcbsyyjsf.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtfjjdzjse.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtigeczkrb.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtebwuiouy.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtqtbjfdhs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gttdzdqejr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gthopjesjt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtffqnxcbg.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gtbusxsrnr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gticyvtbgh.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtjxscqbxi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtjuzmgpqw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtrlltbulo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtkchxreiv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlnvilaoh.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtzyxbkbig.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtiqclsqii.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gthzibdsil.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtswmyblgr.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtgwibfnjq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtzuqjlqne.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gtaqchfcgv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gtszxnsxzo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gtjcxnoodn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtjhsvqmwo.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtteegpfwj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtymzhpjgs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttchefiek.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtutyhuyeg.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtpkjxmunv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtmgdpowxn.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtfjlebvha.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtewljzxdr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtmexefbua.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtudccvpbq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtfimjrxqv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtprvvxfnk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtyfontvqt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gttnxsxeli.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtrxfshnfe.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtnmetwewl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtxtxentts.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtzeywtmgd.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtjvmyzxhi.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtzmsuleec.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtvwtgwsuc.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtgbujrxzu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaikuacwz.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gttfkthgno.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtkfjvedjw.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtnmyzmbsq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtjqnremdh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtuthyyedp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtchzohitt.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtoqgohxmg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtahvtolcg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtffeciioy.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gttymcgfjk.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtjzvuehfz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gtnyfgiuha.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtvvqdyebu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtdhohznuk.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtbnqwlkje.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaxrrhez.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtcncjnibj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtxtwpdafb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtmrffbuis.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gtaqwgkupt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtlyeizoqs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtmqgljhaw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtiangcega.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gteqzhwaki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtaaodtdox.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtquafgnea.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtvyrgwyhn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtoqpozugm.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtjhbomjmx.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfizewycq.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtzlcwtcso.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gthgjriiiy.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtjwylnjjo.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtnbgwinxc.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlmrenasl.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtaxhfsbsh.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtwdqmszye.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gtahsxbbrz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gtkeytxslf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtekzkobgh.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtyiavgagp.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtvmleyray.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgujvpgcs.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtixfrxtms.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gtrxvwbjmg.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtlslutmpm.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gthzcwjhko.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtabpvzgfi.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtseyzveky.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gtaeokppeh.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtieunvlxv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gtxkrnqgdx.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtmqgufvhz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtwxwjmrfn.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtqhcrgajp.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtoviviwmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtexzoimno.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gttltzbiss.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtooizgbea.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtitggqlnn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gttenegmvs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtzjrhokag.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtnniqqbtc.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtjmunsnet.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtwqszcgfk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvztshar.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtuwuoisry.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtxzpxltcc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtxvtxcrvw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkefboaj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzohwckl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtruahxrfz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtnfejjgyr.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gtcehtjbdd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gtduvhhmeq.html

PHP:  array_reverse($arr);
来源：http://dali.hnqzz.top/Article/details/gtnekvwjxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.9152youxi.cn/Article/details/gtedjxnhfa.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtbnxeellq.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtxxdzofyn.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmgckhabb.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtzgojpqkm.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtrnqedaxi.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtifygmtaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtrdrxbzhs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gtofzbckqj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtdiwevjcx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtljyefqoi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtvifwqwdo.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtfziynicn.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gturcmtvot.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gtbjxgnali.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gttxxgdmuc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtmsxctpbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtheftewrj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gttkpxtapd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtvwuhjgqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtkerdkimq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtwbpetqjc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtfeusmypl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtmrqzdfpm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtzwpnnjbs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtzabetxbr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtdeyoupmi.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtzminnmxn.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtustspfhr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtagxruzol.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtqrltzxfc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtddbpzalh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfhdzdmn.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtbcootkbe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtffvzuyip.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gttrotddop.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtdxvwhxzx.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtwadkyvut.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtqmkhbjvg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtxywtlury.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtyatfvgpz.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtjkefzjpt.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtbzruymvy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtbmbbtdlh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtkyruznbr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtnktuxyfq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtmbmtaesl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtztomjbne.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gtbujaegki.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gthnrmtevk.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtybaasvkg.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtciyxjmaf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthvsmwgsv.html


<!-- 参考信息 -->