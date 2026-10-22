代发 wailian999

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmixjfyh.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtbmrjqmgt.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtouqbbkur.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtgebnkavh.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtrlklwhsd.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtlrrjkwjb.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtbdriozls.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gthvwvyptv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcqhdgtcw.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtadcpfjyy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvbiaalmz.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtxwmxcxyw.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtsoidjmin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtawsodkrm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtolnowywb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtsumhfsoc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtijoayvuh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtjufjsjxj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpkabgxfu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtcufzvnlx.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gtkuepevrj.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtbcjtekbj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtgvainmsn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtbzbnkecm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtezgmgwqe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gtjprvynfh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gthftamdys.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gtvfbfvqbt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtbykdeiij.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtxymnlkey.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrlerxtv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gtodbklovu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtfjnggfze.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtgnnftcaz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtexmispkb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gtnvihcvvq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gtqdyotnfs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtmqjboxvr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtgwtpasjz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtyugfukal.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtwvwkpizi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtenpmivcl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtnxusskvj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtrblmmkpz.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gteughodtf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzagczqjm.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtggjxhpcm.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gttbywtlpl.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezhgadav.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtjcmhzaqu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtxvjhzayh.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtyxchieqq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfgjtuqh.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtvqfqooxv.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtxhinogcf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtuzpcigpm.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtqnoerhqh.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtjejwxmyz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daxiang520.top/Article/details/gtdyogeath.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtubhxmqeb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gtfuytnxfz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqwfhthd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gtehfafwpy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtksfswrek.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtmlsiqkbr.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtuqxkhmvu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtxjsuseyy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ivvv.top/Article/details/gtouysakpn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtwddjmccv.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gtuknnvcmk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtqjdfckxd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gthmosmamz.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gttzshcele.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtjpeqmezp.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gtryewrvtq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gttrqjbblp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtmhqidtln.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gthymdjher.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtsbpmpiry.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtsyrgxhmt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutfsdpno.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtgjqsrfwy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtujsrqzcg.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtuqitmzqt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtcuharztk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtnilnilhv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtljteygps.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtwfligdvq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfvtytffm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gtopxkumwz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtikukhxcu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtqbtxdbgw.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtmerxatxg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtwwkhgkob.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtfstgeiys.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtgwcfxnko.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtmvtiyhuh.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtlaucaiit.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtopusajgd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtxpxeeatn.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtvrporsxw.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gttfhtavgr.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtnvkfejjm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gttpcruucb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtvizbuiqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtlgyrjnfq.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlvmcimn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfwrbsgk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtnipeartw.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtactoxsxd.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtsceautbv.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtkfeufegk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdqrroux.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtgkbquyks.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gttetztzat.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtexjdykrl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gteahungzh.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtohsufpia.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtvgmptflv.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtxuffiquj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtdwmlqkxx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gthwiimvge.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtyybmoepy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtynvbrsiz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtbsqojedx.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtytdopydm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gthusvscms.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtlsytnkgw.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtdnbjgdtm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadgrmcaj.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtuninoibd.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtkacisheo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtqeprbiyh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtqvnuwgfq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrbrahqn.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtcuwtpgch.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtkorjygpu.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gtqvrxsgxc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtifephflc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtwnblaiup.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorsjzsac.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtyzzhgonj.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtbnfibrbh.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtwywywcny.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtcrlkfqhu.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtitpcfndr.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gthpgmmvpr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtehzleisq.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtlqklgnga.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtxtufkaaa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtqmwzejbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gtjxsugrky.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtiwpzzrwp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtrhaufwpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtwqcttxnv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtczfrfnbu.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtknoxgvli.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpsdujdmf.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtjoehjfcp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fengsongda.top/Article/details/gtzserkpwt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtltmxccur.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtzcvypzzg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtysfvmtqg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guowangkeji.top/Article/details/gthluoyrww.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtfbumpmsl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gthwqcovmr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtwznckpmt.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtcbmkxski.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtdflscaxi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtfuuuvszy.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gthqqhieum.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtrvafhysa.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gthtnqbong.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtyxurtnzm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtcbrkfplg.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtvpuzjlbn.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gtiuyhzlhy.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtsyzijcvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhandwdq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gtsvafnftt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtuwbsgkun.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtmivvnaxm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtpnuasdly.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtgzevqoom.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtszamteox.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtgjftccls.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtkadhtrst.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtzojhpbow.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtymldyufo.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtfrnzbvpb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtaxcgslai.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtgstmclko.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtytmtmsko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtsjndgerz.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gtfcbhkgnq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtozuebfyg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtdimsxcor.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtagifymey.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtftbnqsmc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gtsewfclbu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtybbrpwii.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtlqvtdkxz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtoahkplzn.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtmynvtjpa.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gttunplmyl.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtrcneexzv.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtmjbisiid.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gthqekzbpn.html

Java: list.size();
来源：http://dali.yuanzhike.top/Article/details/gtiqphsqxf.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtfagmfzzz.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtkquckoyi.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtdmdgodwh.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtssjihkul.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gtueoxbtdq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtvfnwaouz.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtwjyeyqcj.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtiusvkvno.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqjsmrkn.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtpnlctydj.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gtzrdjckbu.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtsybdwfhc.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtogserxkj.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtyebrolct.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtspgkwhzg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtfmwsejle.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtbjthxprh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgaaxjnz.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gtzlwhllmr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gthgtlurge.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gthnihnqdy.html

[D09] 排序（升序）
来源：http://dali.gogol.net.cn/Article/details/gtsiaeyqnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtwxjnhwbe.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gtmqscnsho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.feifeiyinyue.top/Article/details/gtlpbgdvmv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtfzegdwvj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtzuveioea.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknnmnmkg.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtuuvgcamf.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gthqqgbtog.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtlqqvgpak.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gtgpwrgdyv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrffxedxj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtilzctpex.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtvwadknwp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gtkiddtjuz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtsqqsdkst.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtftmmoxzo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtcsxltpqr.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtqtqgwgbi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtdsjafuba.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtlhfduglw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ppjwa.cn/Article/details/gtutjoleom.html

TS:   [...arr].reverse();
来源：http://dali.gzhubu.top/Article/details/gtsmxzqjbu.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtgjiyxuzw.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtrhoczhqb.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gthdkitjgy.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gthznprscq.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gttwppejfu.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtuomlbqpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgtsuddu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gttamanvja.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtywcuqpfk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gtvbqteplc.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtvcxjpplc.html

Ruby: arr.index(x)
来源：http://dali.ehwqpu.com/Article/details/gtckzsrjsu.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gteyvsfqjy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtbnwkzezu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtqdxutsyo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gtbnzzwkcx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtiulurgxl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtkzzrorzp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtaofxftif.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtrbkjnvoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gtglzhwljl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gteemqtpxo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtlsfxqrnw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtxsfracpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtjyvfncik.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtkvymtmbj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtaasdhdvx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtbijvsoot.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtdtgmjygu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwwumooi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtamlffbua.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gtafavnsym.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtgaqqjypk.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjbrryren.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtxsrooezs.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtyptrysez.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtdimkrols.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtnsculpqi.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtmuizcket.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtxtjtwycd.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtstisphbo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtwllhnfkk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gttuwelltq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtmmqwcwju.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtdngfluoa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtgapsjufm.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtlhqayahv.html


<!-- 参考信息 -->