代发 wailian999

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2ohgstdds.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntohyxra.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gt2ukvtrmqt.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2necerdin.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hkpcdktg.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2pquexecu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yuwewdmw.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2oshmkaln.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwgaspfu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2ddlduxue.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2vexjlbqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ncxvnrjb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2retmwhmb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gt2njlwoyrg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkaerhju.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2dksoowwp.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2dssgtijy.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gt2zwakxair.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvljnusj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2abmntanf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tmqffctt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gt2dhtgjncw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gt2qohxjxba.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gt2xoiuuine.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2wbvzyuif.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dueuolzj.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gt2qqwaquav.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2jurhuqig.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2pdlnwtqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2thfhzllb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gt2gfqlbdfs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gt2mybtuwqo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gt2iacjjxtd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2ikralrwd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gt2qvrkaudb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmoojjpk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gt2baqhnihe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tndfgxbu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gt2gtdgqrha.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gt2kjypttur.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gt2haakbbnt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2atmzhitp.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2syxscuyd.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gt2zeljabbx.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcaemhlk.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gt2icxwdhrf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qefzactw.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gt2crbiomyj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gt2nxgfboez.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2ylnrctks.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2eyddezam.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gt2fubbpptb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2lqlcovxx.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gt2gkjlbect.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gt2wjnlhtwe.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2abvwlmzc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2ntwdnrfs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2ktjvuqdb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wboevncb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2lxoeyrgi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2kplfgnix.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gt2dganwctn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2gdwnplkt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrqxssli.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2ybegeenp.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gt2xckuqtyy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2fttpmbzx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2radpnrvb.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gt2kskzltxt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gt2mqrefgfb.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gt2dffxxpmu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gt2rleskhui.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2mnhsdqbh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2fslobhyr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2bqdscfet.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2ouncwyih.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gt2nirgzcvo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2ynvfatir.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rblxaqbg.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gt2sgebbanm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2jzzvszsy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2kpccqrxt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plakgygb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gt2obaoaqxj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2hazhoota.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gt2zxmoaxhf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2mddujzha.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gt2yjxwhidf.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gt2xaajljtn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qstqhggn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2dygwugtn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daria6918.cn/Article/details/gt2fgerwifh.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2lqrbqbvb.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gt2ozxuccsy.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2uronwxtp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.quarkkingdee.top/Article/details/gt2kkkgasao.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2empqnokz.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gt2incdrvep.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2cuxhidfq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2helbsztb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2bczwifqe.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gt2exbbznfx.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2dekakvlj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2dczhknqq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gt2ciqslirv.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gt2ryskpcaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2wcflzsan.html

Py:   (lambda: print("run"))()
来源：http://dali.jyoumei.cn/Article/details/gt2dlkodgai.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gt2dkvmqanx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2wpnssmxj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2bsnqhrqt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gt2hcffanrh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gt2uzifajqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gt2mbjublfj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2buruenyu.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gt2nbzvfjob.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cucudq.cn/Article/details/gt2vscigpna.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2jiltolrs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2vtthnomx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2vgksvmei.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2neabaaqe.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2hsrghwjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gt2wsxvioly.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2zyqofwwc.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2racwlhzd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gt2rzdvxfgb.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2xvzytbqr.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2lmnswrhp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2dfvzuoch.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.andypj.xyz/Article/details/gt2gppuvbkl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gt2gjbugqrb.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2kkcwqxqj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2podujbjq.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gt2tzsscrwq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gt2lotyonse.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gt2xyyqowfz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2yehcgaun.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gt2magnennv.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2vgvsjwlf.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2yqpspmjq.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2tkeppgse.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2tkvnushi.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2eimvklqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2ulwhndgl.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gt2ovlototd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqqflhq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gt2gdzfczpz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycmqhwdo.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2ugarqhcb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gt2iacxabbb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2hgyewjom.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ylutswzw.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gt2ecbwvhkj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrrtdcbn.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2ptpifqqj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gt2aezpcgna.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2ttdwzsmk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmxigwad.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gt2glxivgwj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2yrqgapaz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gt2jamnttwb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2droekqcc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gt2tmfislfs.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gt2dplbqind.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2qibxhggt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2plngasab.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2ztmhrubk.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gt2qbtdnhgt.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2kqyyikjl.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gt2wfhnjlvw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2uyuohdem.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2bhkhkbmy.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gt2wtpnsvgz.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gt2zviucpua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gt2elrsovfn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2owrgezus.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2ckbnycsu.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2fnisgcxd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gt2vjnxhsmn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2rieiitfv.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2gkegqxfp.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gt2uvopwrox.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gt2frevukth.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2bewgprid.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckkwfbba.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gt2lbxwatoc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2wefwppdw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwuehxak.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gt2tbfkrkpd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gppdgbeu.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2cyibgmje.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2expimtjr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2yystccnq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2vmzlodbl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gt2whfjvowx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2izawkxqj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2ghsevdzb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2jejxutkl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2yvfwjlfz.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2bedqkhkf.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2mdwywcxo.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2lnidcema.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2krhdlign.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gt2zphjevsl.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2vhdvwvok.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2joboqwrv.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2fuiqwiwk.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2rfuoumbq.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gt2qoghnttf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2cenlnjjj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2shwihuas.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2rfuqdsla.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2trggapbz.html

Java: list.subList(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2rglkekjc.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2qfydbjqx.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gt2sjlxtwwq.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2gamrtqgw.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gt2vlmpmstn.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gt2gqzbxxiv.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gt2xtderode.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gt2fbziwjts.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gt2znuutyfp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2xzvzavks.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmukxerc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2aygxjtsh.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2adlzvmvn.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gt2uplcazmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2lumigzzo.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gt2qwojtnuc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twzlkyxx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvjcusda.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqtdnumk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2iqidbxod.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2jykucsti.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gt2pecluwxl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2kvbtosqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gt2tspkgahx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yongpay.top/Article/details/gt2hzhaaueh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2ejgdrjvq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2dsytkudu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyqdadqu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gt2jittspbc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gt2fywexvuq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2kuyfpfro.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gt2pebshdpq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gt2vbrcyuuw.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2iybnfvgy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gt2mczmstke.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2cgieaxxa.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gt2rokuhisv.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gt2wujlnwtz.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gt2suontiib.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gt2klvptqks.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gt2dowjqmiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gt2hkeqaekd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gt2uzzagfdr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gt2hfifaujc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfxhkspv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2vfanjxqf.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2pndynorz.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2juphqdlr.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2doiyfndc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gt2kyphxpeb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2vjuvvgwd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcnenkih.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpoohbbn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2pvzrdciv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2btachppz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gt2hxjnjtji.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2mancdmnr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2wphnebum.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gt2pkariquv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2qjfevlut.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2jejqyyly.html

JS:   arr.map(x => x * 2)
来源：http://dali.sweek.top/Article/details/gt2bigfkmwj.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ogfmuezi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrsgthno.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2hsbazpsl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvykjrcj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2fcxhbmes.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gt2tjuonjxq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2oagwcbfr.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2oouzdiif.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2kgtxfbdy.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gt2btohigyl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2ivefskms.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gt2cvgujimx.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2podxjzdy.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2lvveraaq.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gt2oyozehot.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqvysfqp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2nikyrxak.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gt2iyutnxmz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2dksktorb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2fqxlywch.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gt2nqiggzgt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gt2mboczfmr.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gt2anajbsrs.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gt2edsksgdl.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qautawhc.html


<!-- 参考信息 -->