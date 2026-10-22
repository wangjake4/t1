代发 wailian999

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbytrbffp.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gtjklgrbog.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldizkshj.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtfsahdaxw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfswzloq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gteybdhavl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtdaujyhjh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtkrfhcfwe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtahixdujl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtlfavmllt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtnavnnpfg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtbnhizvmv.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtrcmefepl.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtednmrmey.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gtxwfquvjj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtevpbkwto.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtntxvcdtj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtzgxtvtjx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtcamxzwyo.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtzdsyqlyr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweqlqneq.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtjemvhmat.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtqworzjii.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtbyyeccrv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtlxagsrxg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtkqamxiog.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkrmrthy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtvdezshzr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gtrpmobsns.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gtqzaickcu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gthtqtkqaj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtvsnhhylv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtsvlyfdtb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtqceamvjf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjysgdnb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtopwjrruz.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtflgvysqo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtuptdovvd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gttmqkzgep.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtbohdijzh.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtjmhdonji.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtrwccwube.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtyesawzvo.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtqnivplva.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtwizvenan.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtkqsixqov.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtkubpykkg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gtiljdvvlg.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtjiyhgpye.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtvasjhpku.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtdoirrujk.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtlanfqtqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtccmsahzt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gtcqxtzltk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtcfmipgxg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gtoocbtqps.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtyqyridjg.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gttmafgnqe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gtklxdcoqs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturschwru.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gttcuoeotm.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtrytnlxfi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtdaegszoa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtoenhjcik.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtdjbanjwo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gtwdqfsitx.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtbbrmftvr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtmazjanvf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gttvfkvmgo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtdrfjyquc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtbezqruvx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtmpcpudyk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtrcgyewgc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtztchfizy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtglsujlub.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gtuoxfmnpn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtsgdjvjtc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtutpblhxh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtuiyumbax.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtyujynfdg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtokwmxlju.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gtarllsxyc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtjhushvar.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtjcyerurj.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtsbxjsrdo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtwqyccdcy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtjbqkhzoa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gtgpvzcktv.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gtjbcdldpp.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gthprrddzz.html

Go:   花括号块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtczhefplg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtlcjjvtjk.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gttvqwctff.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gtjjieabaf.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtfyaloxaq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtpdopkvfj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtcckqorda.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtkcktpfme.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gtzgisimqi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstnltgfx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtacwxkfmt.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtdwpitphk.html

[C12] 立即执行函数 IIFE
来源：http://dali.tanke756.top/Article/details/gtimhhaelz.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtpcrpseec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdacqvtyc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtpvcdmegx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtefxvtcqm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gtiggxawpq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtcucpaqdi.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtajhstipv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtmrqiqcgx.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gttgxbumze.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtmaamiquc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtzpxojxzr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gttacznxtl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtfurmrigs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtgtgtpwen.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtsortmqfc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtfmsdwlld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtrtkcxhpg.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtloenuxip.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtynuseing.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzzqnqeo.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtzqnmdwit.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtlfuunfkp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtidccrlfz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtpnyxewfw.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtsulbrmuc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtqlihdbtq.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtmifpgctt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtoyeioowi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtzfidnyup.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrbypmarc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtjanvvelo.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtrptmaywn.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtfvioleyo.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gttgvlqssm.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtzookdpog.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtrizmksou.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gtpygmuony.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtxzyoxpda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtiiuwhrve.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtiopafkmj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gtokrnroyz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtqgpfsavt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gtzktdhkum.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtpgxjbawn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfvoqscci.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtfppkzjbc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtivzrkoxh.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtvthngbit.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtazebiooz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtfdxakysp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtlnbhadvn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtcyapthjf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtejcemjwi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtqcookjku.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtxnitktmw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gthecfrefi.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtlmrdlsdd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gthrfehxru.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtzrjnckmm.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtycwonljm.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtzsrnjfvl.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtxopaxoeg.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkettoiam.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gteukxbwqv.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtyiznvnig.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtszmqpkhe.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtsrzoepje.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtgcyxfwqz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkopjhvz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtekcmnsjy.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtaorjhvrl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtncazrqgc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtjzhphump.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnnvhsuef.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtjfeuvjmc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtxbbiyxsg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtufnglyup.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtklejyhvc.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gttaldhjqn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtapmcuiwi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gtnmzsxwcr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtmcafbyxg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtdooojbce.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtnutqoocm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtckfysjow.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtdujvhybs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtymzmgnur.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gttyqxhupl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpjihcfa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtnumfttqt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamewonzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtyxsojpag.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtfkcdjwdu.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gttmmwspzb.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtqsyzdcsn.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtvswgkbqr.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtweifftbl.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtfvilrjpg.html

Go:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtnhuamdfo.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtjpculxsy.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtlqgijyob.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtzinvjelf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtvowrevzc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtcuenfoho.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtqikaitpw.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtayeksszs.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtkfdrdqjh.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gttrtieter.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtaxmqxyti.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gturfpothu.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuwhtncp.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtxhhwtrlt.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtwrxybndv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gtzbnlsypv.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gthxnaedqn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtnnaqsedh.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtvevgwqes.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtdzgvsecf.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtzfjpcync.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtybywjcro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtiogzahmd.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtgctmkeue.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gthfivcvgh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gthpdlfmsl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gthoqlrbzz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtjibuuzvi.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtakqtdtep.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtpsfvmmcc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtqvgjmera.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtckzawbdx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtuzartslj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtfxsfbujt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtehcfvhlk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtdpqozmew.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gteuaefdsb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtnudpoiox.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gtwsrinvlz.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkadjpkqs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtgsqkpmcr.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gtmzdfzxjr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtubkwxglk.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtalufdpbx.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtjpstlkqu.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtgorawjnj.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gttoynkrbh.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtnglpwgga.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqovyfos.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtqqgiqggb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gteuvpmjcw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtyyxxfluy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtrfohsmcy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtjoztauma.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtutevbsor.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gtlgjkgquf.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gthjlqzeup.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtxmrbmabt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtirajqwpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtwljerimf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtnhkwqisv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtgxudpopa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtvcgrehbb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtpxynpbka.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtjjpxqkbo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqavqotfe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtbjcjryxx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtxqxtjbdl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtgutgeknr.html

JS:   arr.map(x => x * 2)
来源：http://dali.iojbl.cn/Article/details/gtgiwwayvh.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoujszyen.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtfvgxcjtc.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtuooczktx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yongpay.top/Article/details/gtnyvcwhgl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtdpoqotcn.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtylnjttfc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtlaoribqf.html

PHP:  array_unique($arr);
来源：http://dali.dianchejie.cn/Article/details/gteyplfuio.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkkxokxx.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtjqtemaod.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtlkmwkyje.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtgzfrftjf.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtdbldcxrp.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gtcprrhobt.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtclxtpggf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtvxbdcyem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbezatcca.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjbxcqgnv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtzmuvwrkv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtqxpgntfv.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtwyekacax.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtonreqssx.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtbzvmwiyo.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtdvcryxfe.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtddyddiop.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gtuwkiohig.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtsiclzrvc.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtmveufjpl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtrkrfouhn.html


<!-- 参考信息 -->