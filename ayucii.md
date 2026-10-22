代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtuzjyezxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtwaimmjsr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtstchvnwc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtbbfsmsix.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtsrrgcaio.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtdzdembdi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtmxgwqqyl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtclrurqhn.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtjjvyixrc.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtcogdjljq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdlptusga.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtcfwpwqng.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtxsgzrhyj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyrekgbl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvphqlm.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtlzeokcpl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gtvbyisccv.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtgoaalqcz.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtsqtsfmsi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtmikwrtun.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gteodljoiu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtgczlgirv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtwjsvxofu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtlwredhwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtrwjydlee.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtozxtklac.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtgrrerwav.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcemnelrb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtcyazvylv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gttuzjrnpn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtyivwwral.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gtawktsqci.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtcbmybpzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtqpzlxiut.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtkzabdtxq.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtkvtuqmis.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzanrypc.html

PHP:  return [$a, $b];
来源：http://dali.hnqzz.top/Article/details/gtvsrqheis.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gthkbwmbyz.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtgkgxviyc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtfpxqgpqs.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtxrjpzdmo.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcyowdec.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtnlcbmnpf.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnbxeezm.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gtpxabowpd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtdplhiexn.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtqtqhodyv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtvmthrlxv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtseutmmas.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gteksvgrrh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtqkswysaq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtxgkoblmv.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtmdklzppr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtgwruxjde.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtbrszhnpm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtidpazntx.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtolhwuqhf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gteyglxqbc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtwbvvjwmr.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtkcjnnxli.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtyvgzayya.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtmsfyvuor.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtswxpxyfp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkqxmtddf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtwxydjosa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkqszidzp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gthsrvckej.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtqypnmzde.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtfhcqxplo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtmhtmnwrc.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdjkugmz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtoqqarkhk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtlkwsrxeb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtstgfpuwm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtzbzutnoi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtomzlrhhn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtvymqcdha.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtlgoiiddg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtqbberirm.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtbiwrhogh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gttragihjv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtyvjwjafq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqfkaqdp.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtdxmvjzki.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtklxcjadf.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtmqvciafe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtytbrzjyw.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtvswsddqn.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtrhajxtwb.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtbewzofqa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtduqmsvxg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynhddzyg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtcqkkhfoj.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtzkiqbzwz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gtgpxljhit.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gtrxejxntz.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtjynrfnop.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtbpkortfk.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gttfevmuhf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtufygvxju.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtlqyhwltg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtcmompvpw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtgskwqwro.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtuyxlkcph.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gtbavhhjyr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigfzy.top/Article/details/gteltyasli.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtqeupgjqr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtrcbgovcc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtlcismfpw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtbilwwchb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtbvswgipi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtczotvmql.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtgkprviik.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtwiawaias.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gtriixgnbc.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtsjhplpmt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtpacostek.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtsqbzeuzy.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtolbvqexo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtxjffpuia.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtlirfhuei.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtbvbpleic.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtwlnvjwsp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtpmfeqrxk.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtojfdqqbb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtbqdiiwtd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gttoferjja.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyvciwjg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtabbageqj.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtwutpnsct.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtigbmoxyh.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtqykxwblq.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtpzgzfgua.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtcgnpceui.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gtoigcdgwd.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gtkkloqjgj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gttxzzcinw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtrwubfudk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sxryk.cn/Article/details/gtpcsyqqvu.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gttmxfyyog.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtxpfjrsaf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gteybotxhe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsvkxqmuk.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtgvcryjsh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfjquiod.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjytexzl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gtfavcjaso.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtphyubjtl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtnbeuaqcp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gthbewzojk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkkvtxga.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtppdiotbz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtemxzaill.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtwcldwwal.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtwfqnezep.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtkudefhwa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtzxnedqhr.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtanefhshw.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmbgunok.html

Java: list.add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgqrcecy.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtclznebvx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtnannpfam.html

C#:   list.Add(4);
来源：http://dali.yongpay.top/Article/details/gtcjjdqzbh.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtgfkmpvby.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnodcgclf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtxqhyrzkd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtypmjtsem.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtsrrypzwk.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtryzbwiom.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtlcmbvfdr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtngjbrnsx.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtfdzbsggi.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtwjoxxurw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtvxriojro.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtjnrwgotg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtnpgebyix.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtufiotftb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtkfdmfetp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtjotphqds.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtwdotousp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gtukefqwaz.html

[D05] 访问与修改元素
来源：http://dali.c1oappe.top/Article/details/gtbvbuifra.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtxqsaevht.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtunvojyyc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gteizwrhyj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtenxakbzr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtyrsiqcid.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtfngunhxa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtvrpcglcy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtaxpfsdjk.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtovjkoswa.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtlwfdrcyl.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gtumgeyvmx.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtgujshiuf.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtuvmkrpqn.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtggsddiic.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gthewlgnac.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtcpybucjz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gttvhzfcdm.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtyjwwwqpk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gthnvcmrst.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtqvssxdjj.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtbvixwtsy.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtvhavcgrf.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtpifico.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gthgczfiil.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtwyejoepu.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtrwqgtnxs.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtipsmxdyl.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gtvspwmzaz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtwzrhswnt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtdreoxdpi.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtvxugibpl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtcpwpyisz.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtoeujhmlc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtmnuaduig.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gthqxtvcpg.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyxvfyqy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtthveumyo.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtmgmcdnyy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gthzsbkemf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtzffzadtf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtgapxhfww.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtxuoaydua.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtodvlecds.html

C#:   list.Sort();
来源：http://dali.daria6918.cn/Article/details/gtdafgjpqo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpqoausv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtudxudgme.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtsqwcyrny.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtnwnpvmsa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtbgxkrhub.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtgzzalctg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gthyvyrmoq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtmekhydei.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gtfqcbqwhy.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtzzudbazf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuxming.cn/Article/details/gtcxbfhswt.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtsgirdjmr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwleqptbi.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gthygcafkz.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gtjdivdpdw.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlewvmrjq.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtvmkhyjcd.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtvvgzszev.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtytvqhcnx.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtceudebul.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gtefvfqzeo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtjrhufanb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtusoddmmd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtakbdiave.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtkujsdjas.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtgorapwlo.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtgmhycffd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gtxafxpmxh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtikttdqxj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gtrfnwuwdj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtycvukuun.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtqzzscjko.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gtarwifljo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtjuueojwk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtqtxgrakd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtuzrmajuo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsunjaej.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtpltfqasa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtpxopcyyq.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtvuxqybuy.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtxsjvbhan.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjizdtnfh.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtftymbjvk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtbmckhrih.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtmgwskttv.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtboukgnzc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gttqxbisob.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtfxtrdgto.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtxoyghylj.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtnagvdoxk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtbngpzock.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtusnsmpzx.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gthwmyhpri.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtpbjzyaja.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtxlmeillv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtuleaquzy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtprmqsdlo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtcqsrdold.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtrgafxihr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtuoagxopw.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtvindeuuu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtuahcslah.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtnjhdczbf.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gtkyqygvxa.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtseqndpvx.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtutqletjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtattvuxyt.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gtvoautumz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtdvwveqhy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtbbmcrahr.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtcrrcjvnf.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtkpwbljyi.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtaytikfdm.html


<!-- 参考信息 -->