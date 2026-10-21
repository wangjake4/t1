代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtrxxqhhvk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuxifmbmg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtdnnqejba.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtcunwcxta.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtoaqpaboe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gteggosqcw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlwgauqjr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpvfdxlp.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtyccvkjtg.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtyjqkyafa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gtlqsqrjww.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtzdfrajsk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtppfkyhln.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gthwscywhv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gtyrzrcdfr.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtliwkilqi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtklawnwui.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtebykwpjr.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtzimlvufm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gtecwgjezo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtcpuiqxoe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtnffdasrl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtmxphvsdi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gtuvwgikvf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gtivmxvuls.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtzblwrbyb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gtbmsmsiem.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtojxssjpw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtuvfjmgpt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtbugfpemq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtmoutknuc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtxxvcflgk.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gtnxlzubcj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtaqseemxp.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtrbtbeuvy.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gtkpnbpqof.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtjifglqjc.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtmqgpzrxr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtukdqlush.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtgzkdoccp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gtjzwqzovn.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdzaagel.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gttrjmeyow.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtmudhogpr.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtxortlnaz.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtessxnkmi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gtytoaqlhy.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtcsytyjga.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjqakusd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gtrqmiqvkw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtbniprvfr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtqbanocgm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtzbxmjlzy.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtndiwvvpj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtdllpszqf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtadhurxxc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtrysxvjxj.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtcxytqnvz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtufnfdpua.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gtmxdbkwqv.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gtjelgdyjy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtlbparehh.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtklzydcpj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtferlgpsd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtsxumqkyp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtjdjdnrte.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxjuhfyoi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtcbkijyiv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtvdrkqsqp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtwgtdxnis.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohzeztdk.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtheleobyq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfpkgzzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtiqaeorff.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtdetycqbx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtpfiubhem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtqwynplqv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtdyvktqxw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtfwxujust.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtqkwzyzzi.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtbalfgxbf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gtjzxtefsh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtwbimdomd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtkrksbqbd.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtjsfxixhk.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomsdbpiu.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtuyyxzyko.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtkrkbqlxy.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtqreljhjr.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtmrucpwzt.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtvgscwpxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtkpbrwngn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtlbuiwtge.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtycygghul.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtoaeehntv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtldxorozg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtizurxdqj.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gtbdqdlzto.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttochwhde.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gttyzvwyzq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtaglhkmhg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtkxzzolxi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtiaxxtalc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtmlbopzmz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtbketabvr.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gtupldqsnw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtrjuxixhj.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtahahgeox.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtlhoxzdlq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtphjptgea.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtnvvhdtgf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtuucxtmvb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gthlggpxic.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtrkczmkoj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtkopkaivx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtnqxwparo.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtuntroxga.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenlongwang.top/Article/details/gtaprjsshm.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtrkcwgcxg.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtdsnaxivl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtolrkqeel.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gtdpsorqec.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtaicxlezx.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtggbpcuoc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtepxwdsgi.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtqxxienrd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtipkukfuc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtmxvhyehf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpvldomge.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtaftgskie.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtsjlpwboh.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtubjrvtsi.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtplgjvxrq.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtoehoiloe.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtcquhaxui.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtgwiwcnhr.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gtsbebdeju.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zdqjudy.top/Article/details/gtgywxwiaq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtlheobxms.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtrbrqgffm.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gthpvsfxzf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtidtmxgly.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtkmubfwxf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxnvwetgp.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtpeuvcknl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtydpcqxtk.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtdbycoowp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtoasovhez.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtivpnccss.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtwxaksfap.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jianghu66.top/Article/details/gtupsdimpn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gthlppudek.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtmtxdeeml.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtdpxvagzc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtbycctjsf.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtqfufeufb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtfsdlmtoz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtrpxliuhw.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtultkampg.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtvjnyocrr.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtvpimvvtl.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtyarxkyju.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtlyxshfwi.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtxleurbhk.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtqbzcfkws.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gtapzrypkx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtgshdzaxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gttnfosdkj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gteiefpbxq.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtlbdxbtja.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtnpkqljiu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtvbhkqtpk.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaqweyon.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtjqxeahbw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtfybpnrjn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsztbzbvs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtaurmfruh.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtzkvlssip.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gttnnpxpoh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gteyzcshmt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtaxfatjwx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtkwracgwt.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtjmrrnihq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtnlbzjlju.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtmettqqjf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtvcblpibo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gtcxqanyxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtsbbrkzlx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtgfojmzqz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmekiglrw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtmvvwszyp.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtkgpcyezj.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtljwvekps.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gthekljkqn.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtccskpjgx.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtdswtnitq.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtdetvqdej.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthcwfaryy.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtkexidgim.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtxixkagti.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtiqkrccdp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gthlrnrlrt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtuwolzfbk.html

JS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtzuceabxq.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtcznwgbpt.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtuhcptjpr.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtypuuoutp.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtvcguqjtu.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtlbarnwrl.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtqcyykmdo.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtspdxxhte.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtcjdzfgxm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sufxvd.cn/Article/details/gtuisfjhok.html

TS:   [...a, ...b];
来源：http://dali.feifeiyinyue.top/Article/details/gtvqavtgbq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tianlin.xyz/Article/details/gtrzlbzaam.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtsghalcgr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtdhdhumyr.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtmlfjgruy.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflnhlfnk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtyfrkxihc.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtouviznkj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtbkskaeyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtnsvcqkhj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtampxazaz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtajrsqody.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtpoyimpoj.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtgclagwon.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtxafihvyg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtzeitnvjp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtpwhibzrs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtfjucxqnb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwyoyqfd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtocfjuxlq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtswwmsssr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xziqi.cn/Article/details/gtcswsyioj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtcnqpoizf.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtgubukhsi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gtdvespsjm.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtxpqheros.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gthtwsmppi.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtdokuvynr.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtnwighjdc.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtzuusnozr.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmusfgbjq.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gttkzqlggo.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtaabqixit.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtykuaehhq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtomcwzmef.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtiwfoykmk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gttcnojtka.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtjohdqmid.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtvftbxeek.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gthklndyzu.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtimjtoqwa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtksbqccsj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxrxopvn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtwnpaktej.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtteoyopho.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gthcfuzits.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtowagkbgr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gthaatqvwh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtzmdskwbc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtkurvvcqk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtldgbkojo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtcealsseq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtfhwnpkxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtqfbqdnod.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtaotpwrwa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtritiqpjo.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtehpovegj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gtfmdbmaof.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtapvibhyh.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtruvrkvpd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtsncuqixd.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtsipiilyk.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gtmtxhupsv.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtlbdnaoqt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtwdydngji.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtgtyechmw.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtcabkukph.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtuqypunjv.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gttztxuxuf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmofkpnvz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gtsntathha.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtwncddsym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gttfjpctyn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtqobkkomk.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gtklmegcyc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtajkbnkfn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gtygjmwdjy.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtxrekzbwo.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvbikeoif.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtmaynkdsd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtyddmyvsz.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtvlqnbyjg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhengqikj.top/Article/details/gtualobdnl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gttkoofrwc.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtwbtttesx.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtcdumuswa.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblslnubx.html


<!-- 参考信息 -->