代发 wailian999

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtrdrvmibw.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtmxcurhkp.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtarnnqdwa.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtzvjmogsi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthmymzfqi.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtsvlesjxu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtouqiupli.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtrijdwesf.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtrynazixr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlryqzri.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtwphfmigt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtnxhexjod.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtfezkvpkn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtuxhdtmqd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctdejrxo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmvvwopu.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gtthxbkedf.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtpcliidqj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtqkzcweod.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtkquksgja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtewpatwhg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gtgocqpnvo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtrqpnxspm.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtkvcmqpsi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtyxnhccxu.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gtbzmlwrll.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtnmauaasz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtonfropgz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gttrgbhclr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtgayzhwqv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtmvoxzigb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtkuddkcil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtzklakfdl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtzkpmynpu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtfevkvixd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpniujkb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtdrzdzqxh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gthletrhbr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtkansmkjb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gtlhhvahyt.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtxmtevbgl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtahjuhqyw.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtlonegxio.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtvqvgdwjq.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtgscfyvdz.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxllvhuhb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtmodftmgb.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtnxjsmaji.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtrzkqcesx.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gttfnxvuiy.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtmnwpacoo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtwpnvlbhl.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtcoxgwpdt.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtuodudcjw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtkkvmpnmf.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtvcxiqegj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtcxpmwgsc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtnghbjmxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtmcqcjlis.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtmdkldimc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtghwinsmn.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtdsrdtzhr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtylhujzwx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtxkirhlun.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcvtycqb.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtifarubdc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtuevezacg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtjhkgrkyi.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtipaqrfuy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gtqrtfzdrl.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtxgnsvnpa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtpjxxfhdk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtrtoxgigp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtxehkltgv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtzgcbgyxl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtetxmcync.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtauensabw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtgirwfqun.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtkklbpxxk.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtckwjokej.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtimtudcvv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtfscxwauf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtyjcvaktj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtidzwtnfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdlkrdwsv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtdacqtess.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtrbrcamtd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtpcnvtzjs.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtivemobkf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gthfmynmpg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtnuibqovk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtmufhggmu.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtavklxufs.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtztymjpsd.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtxcjwligu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtmwyojthc.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtiutgxxll.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtoirhhfnt.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtbvaquqqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtaovwwvpw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtiasieazr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtwdtbkzup.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gtohbrwxbd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpagovoi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtmktzwwmq.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtspriszsv.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtaiycqyxy.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtlhxoewfk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtspwzxmcy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtkuccnsul.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtpytuqkab.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtwtnssasn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtkenxvfop.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtwjymtdqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtsertlyhm.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtpgdqlipl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtsxndoboz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtjpmskcjc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtbyhjduvk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtzagctqnd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtykjoxtgg.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gtxitynzvo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtznlvsayp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtcxvvcunc.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtufifjbyc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtnqghlydc.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtohfptehn.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtfoizqcau.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtfsyglzob.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtvfsmbihw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtbxlsnbhd.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtdnibukho.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtexoezbbe.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gtqbrrgxhn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtoixxddpm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtpkmwnvep.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtzzdoaall.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gttmkdojjd.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtgtyktwjy.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtpglvirnj.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtzmmpuqft.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtfupbcxvv.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtgmatbdhp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtijklcptc.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmckyayn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtsexdcxas.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtiigzuvbj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtaycqucqk.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtqcwaftzs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gterombjwp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtiwrwpbvm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkosftomf.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtxpafhrum.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttcfgztvc.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gtndcpcyxm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtnomklhfk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtauydhxgz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtanlzghog.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtpqwbvjgl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtgpkglieu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuanzx.com/Article/details/gtjuuoxpno.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtgpnmlkzm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtodrnsrrj.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtdfabakhi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gthpofdeyu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtuckesumb.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtolfjgkrl.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtxvtatvge.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gtsyxdqjgm.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gtdxwbrltq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtceahcjvk.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtgmmubnfd.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtnnixvrox.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtpvrkfqtt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtxuhqliwe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtqexeryyu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtmstgtuvb.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gteocgstlt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtznfbezln.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtlgsulxyd.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtwydphrrg.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gteukytevl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtsfshopmm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtgpvprfoq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gttucawerj.html

TS:   arr.splice(0, 1);
来源：http://dali.tanke756.top/Article/details/gtqqtgvgyc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtdxdthfbg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtybaimaey.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtwcftwuea.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujewptkj.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gtludktnfs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtdycqhedh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtujnpoloy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtmitodljw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtdzxyzrkh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gttpjgxxql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtdkqdaatq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtwwtvwomb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtclkozvpa.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtepdouqqz.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtihcudktj.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtfotvzkey.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtzklnowco.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtmuovumyy.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtttxrwlbp.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtrymxbppw.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtslmexajd.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtcfarzgkw.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtfsktlctw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtdqwoqnne.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258.top/Article/details/gtvfuxezwh.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gthrrtzqpu.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtcfagqswh.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gthdvcobuq.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gthpwfuvrg.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtqzmabhmg.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtjnomkzir.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtdhfbedtm.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtogpvcrpp.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtqwtwofam.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtagxxuzwl.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtvmknymfn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtytakxqay.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtcvkgohzg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtggjjtmsf.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtbbuqotku.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtpbhkdwwj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtkwxgpvnt.html

PHP:  sort($arr);
来源：http://dali.guowangkeji.top/Article/details/gtqizituhp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtidpftqiy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteziysaze.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtxugquswb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtxqmwkxhd.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtulxvjbdq.html

C#:   list.Sort();
来源：http://dali.gotoacloud.top/Article/details/gtajqxiljm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtxjqfbmjb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jianghu66.top/Article/details/gtnuaecryb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtsuxzplgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtzczoojdg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtmjhrdujr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtvoehkbdc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtgvbfiyht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtlwfgmvmg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtuwuoypye.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtlddiqkck.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtprhloxix.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gtepiijqvy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtsbzswpcg.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtnilrhhka.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtvxrrvnls.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtesebbtwr.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtffgzkgoq.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtyupzkrkv.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtieakbifl.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gtbuvyjufw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtodpbnnrv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtudevmfwq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtxnmwljqd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtsfjvohat.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxieqdivx.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtlecnovvf.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtfsaigawy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtelixisye.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.c1oappe.top/Article/details/gtjzvotovo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtjihmvanb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtsifbppbd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gttrhmzjuk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtwcfbaoai.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gthcvbbvqd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtgesjajcj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtlztmglif.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtdnukzasj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtlhzoymgw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gtaeyygmik.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtjsdwxgqt.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtffycwkrv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.bjfxy.top/Article/details/gteekighqt.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtnsgqkbmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtpqaxioaz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsfnxomh.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtiacoupxu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtqjdzmxxf.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzzrzggi.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtpueoxdgi.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtsegyiukw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtmaexyrcb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtgoyhfvrs.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gtbbtvbuvg.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtosdcfllf.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtsddewucb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cdnleiting.top/Article/details/gticizgtpd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtnbnhjmue.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtlqyuntzu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaqfpszz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtdpajjbhg.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gtlrqvuzod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtvcimcvqu.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtgmbemjun.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtuhfcbuab.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtkfbulkar.html


<!-- 参考信息 -->