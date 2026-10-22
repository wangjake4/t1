代发 wailian999

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2wbqayenr.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2gdytmfyx.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2rvsgglfr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gt2uielcnew.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gt2logdeqcy.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gt2ynvtorpo.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2qbqnpzod.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2khldujms.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qafzyxit.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2gdlpyruu.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2qcmfadro.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2zsshksjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vabvvana.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gt2jriqftwd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2amaxpsot.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gt2cxzupqwl.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gt2crznssoo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2pucvwagp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wugirzcq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2qqqmoxka.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2upwjqhsv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2sfjuzyiu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gt2qtfnsdtl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2oqrvljuu.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gt2rvlunkcq.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gt2rjyyzgeh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gt2njpbfqhz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2jvawyocj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2brwaegtv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gt2bvrsjrjt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2qkqiewgg.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2oncdibre.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2ospifkyz.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gt2zihtigog.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gt2kadbqomt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gt2pydoyxfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2nattaytd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gt2ygxoavoh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gt2wltvqfcs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gt2lfvbcvgo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbcytmwa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksthcaqo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gt2dhhypyvt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2twyrzpuq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gt2jimnveql.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2skfowdcs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwnpegth.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2zckwalur.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gt2tyfnozmu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2bfkixrec.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zogtfkho.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2zddblzlc.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2gimdzwcf.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gt2gvibomrq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2sphxdjvp.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2jzerokme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gt2tuxwjwjw.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2kdexkacl.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2laeuexqo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2mxhbxbiw.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiccaueg.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2ewtveleb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gt2aabhbxxu.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2tfqyjyke.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2wchyctrc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kiovbkne.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gt2lennigyf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2hdzksusx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2rsatbtgg.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gt2ywtcgyvc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gt2xzetcutm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2wponyqoz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvzldtbb.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gt2dznmiauc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhksfoas.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2vuhhswjb.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gt2xamnqxlh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gt2kedmlxto.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jttamtdw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtlucljy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gt2jhrcvfqw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2nqkxtjee.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2gqorywda.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gt2bunbkwpj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2heythmsc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2qkbnaxqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2rutugxkz.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gt2lrpmaaos.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2iowbgwad.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gt2xcywalpe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gt2bpyvbbbb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2tlktozdu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2txvapcow.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzjridig.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2hefykxeo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gt2xukmkjwx.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gt2lcnhytwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gt2chhiypkr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gt2cfjbamln.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2qjcuvqxd.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gt2caugfgyo.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2dsfockxv.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2vhmfzpha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gt2capozuwt.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2qifdiwru.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gt2ylgxtwqy.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gt2rqklzrun.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbhcfhxf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2decqnvfm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnqzz.top/Article/details/gt2ukdrxdqu.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2imvcfpgf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gt2tjwppmif.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2uyuhysyh.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gt2kwxnthsa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2szmxtkcr.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gt2zyghmkjt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gt2dvupinhv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umnskklf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtmdvenw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2limpaqrm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gt2ewqvxfby.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gt2wqcivbje.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfemdsop.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gt2jrzzhisw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2klouedtc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kornftra.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2lllhqqwi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2demmjwls.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2rocqepfj.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gt2najrgeem.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gt2wryivwdl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddcepthe.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2ietbfuwt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2brdgwbhf.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nexndqvy.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2vpflhqec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sysykeji.top/Article/details/gt2wesppfri.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwjpzwgd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gt2bjobuwji.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziqigdcj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2zwljgzmg.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gt2cpmvhsrh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gt2jzsrodfc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gt2mhiyqmsv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2fwdqwqqk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwzmidci.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2bkwdmina.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2uclcqkin.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2rwuttjyr.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gt2kwurqakl.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2tyefovmi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gt2jpzmwncp.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2fwofujlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gt2socrgmwg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2fqlsjddm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2achrwmli.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2vihnlusu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gt2wsfrraai.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gt2jpoqaldt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xllfhzao.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gt2hdxjndvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxcuywe.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2vhjjuvhf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiordymo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2aitbuoqs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gt2qtxgojxa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2tkwxjwyy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2gapzighn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2qmhlvnkj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2rhcircxy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2leopctdr.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gt2mwveieaw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2euhwzroh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2vhfhylte.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2orrtnxab.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2ifthjwpb.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2uosorskm.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gt2scxamrqz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gt2vbjvaycg.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2lykhjkjg.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gt2ejnlxlnj.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2pphfnhua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gt2yxwdbkyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gt2hkprmzuf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2jbrxcmif.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjepffzc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2bkbzdyje.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxowmzjf.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pflyclyz.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2blacsqow.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2taepxwuh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2upavognt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2zyydjujr.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fegilzaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2uyxraqjl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gt2yhqqchfr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gt2vzxxkndm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2fbdmphzc.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2rpulxewk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2pexmgtsk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2vkktrdda.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqdfrnl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gt2nbjrfabg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2ocvzglxo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2upcsrgjp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2nwmtioin.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2lrjqaubj.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2iksjdwct.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2quxezobq.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2iiajgowg.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juujfmqn.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpuzkyim.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gt2bzbtkqwq.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2khawpxby.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gt2elsswdlo.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2kvsoqjvc.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2hscjtcav.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gt2rkjnxgsx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gt2paecofaf.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gt2qbrzwioe.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2zupeonms.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2gzwjdtro.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2stnpenvk.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2dtchhnfk.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rqwllzyt.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gt2gimldlbv.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2szszecxo.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gt2qcgtjuhx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gt2brkwvoby.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2ghzytcue.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2rrcsepgb.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2pfxiqepg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnwdbbnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2cjbamcaa.html

[D09] 排序（升序）
来源：http://dali.mhx1999.top/Article/details/gt2frpmxkmy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjnavpym.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpxycfaz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2nnkxedbt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gt2arnzzoak.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2pqypcoqf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2rasqrlvi.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2gunmvhwc.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2iqvyymtq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gt2uttygnbh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gt2kmozqwbd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2ttukjbov.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gt2iedifrle.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2iskimbxg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gt2bjevafsy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzyppxma.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2qlyuxldi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2ylumuhhg.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdilosyu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gt2tcyfgdub.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2tgfazcor.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2csrstskp.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gt2wghfwknq.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gt2yqtujysh.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2nxexakzm.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2pblilffb.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2qaguckmi.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gt2jiaangot.html

Py:   arr.index(x);  x in arr
来源：http://dali.yvedp.cn/Article/details/gt2eoylbigx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2zqtnexyb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2gxrvtzda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gt2wagzelhl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hammf.cn/Article/details/gt2omginsth.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2pazkvsht.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2qztzhnlw.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gt2ngajbgkh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gt2awiubgqr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gt2rmzwfhxt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2zxoylpyk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2ypftanna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2qdnspjot.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2scpdmzoe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjioepyf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gt2cqmqphsu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2ydazomvd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2oejaypjg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2qvaggdyf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2crqszomi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxxtrien.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ragwdvvk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gt2wficygxo.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2saqfpvbv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2ngvrzmot.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2cgoiqsaf.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2iawnjgse.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncxbkedu.html

PHP:  array_unique($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qschqdua.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2swdnefvp.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2issvzgke.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2ainbavqn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2bezxitri.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gt2rhgbpsbk.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gt2vywzmwnz.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2fwzhpmjj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gt2bgvcyzdw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2yizkgqfw.html


<!-- 参考信息 -->