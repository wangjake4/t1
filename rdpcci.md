代发 wailian999

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2zptuutrc.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gt2vozsvwbn.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gt2lnoljczv.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2tsriqjuu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ovlmbpzs.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2wdlikgbr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hdigsoci.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgdaekcj.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gt2numjbcmj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zilvolvh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2znchkxpl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqsuwamy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2dedjkekb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2zsjugfli.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gt2jlcnnwaf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2mkumzxpr.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2lpkllpod.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2fogbgiju.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gt2wqbeuyjo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2yivvvuld.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2cegjmlbe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2ujnwevgp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gt2qjudvxso.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gt2ykhmrlhd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gt2gyzwdyms.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gt2rjtcsbwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gt2saxiwekl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2xjawerrd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gt2btgmmjjz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2rjerdopq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2nbuncwid.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2txuxohug.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gt2hairjxuy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hynsgxso.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2qbipzldz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gt2mhxfsvqb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2sxlckxqv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dobeuztq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2mjfiozet.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2zkrgdlii.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2bkmamyit.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2rouhgykr.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2yvoagiaw.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2tirqvhpl.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2wyjokrdr.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gt2yzfgdjbo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2xflivlml.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2jqjgvbja.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gt2nagtmnsh.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2jirzesav.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gt2drcewjkx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gt2lhcazoww.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsukepgr.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gt2ytcgihzn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2yeqklreq.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2arypougw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2apgeehvf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gt2osmoktvh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2conuusyt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwlbrtxy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2ifluvilk.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkiceony.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gt2whssmmnz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2olywqalb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gt2qnoaxlol.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2nzqweqby.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2rtkjixsq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2bxbprnki.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gt2zzququur.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gt2qwemfhyn.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2ksobjucr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2gexyqwrn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpprorhx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2khpgmglv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2axxcmlxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gt2wxwzzxsb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gt2mtnzqfdw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2iexohjns.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rltyyxxt.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2wecspcyd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gt2ugblbgoe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2auchwpfr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2euvshtrg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2esohagtg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnojdip.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmqantia.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiwrbyvn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2nopmbyef.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gt2lftmblun.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gt2tbmuizgn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2jqmqbscl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2rbdwifee.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2flajrvgr.html

Java: 方法内为块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2mukkidbw.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2dlceihle.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gt2xvzhwlzp.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2prjfmhdg.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2lvciupsk.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gt2xfdhchef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gt2takofujn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gt2vquiafyu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gt2dljdyomb.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gt2hunnrfts.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2zmcwngps.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gt2vpsydhjq.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiiewgfn.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gt2zlsijyig.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2izrvyeln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2encurlii.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2htnjipkp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2nrbnmxhn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gt2wivehabf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gt2nesxqrwj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gt2nihziigt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gt2pvxpoyvn.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgkctafs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2eaovbrah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2efkvjmlu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gt2gwombnna.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2jbybxoqd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2wygzshbq.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2ubkugizm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjydjjgg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2vabbiebf.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gt2xhqziitv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2uisnpbzm.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2cwheqacf.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2zoscuwsf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gt2watmguys.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2rmmbwulv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gt2npddzuvk.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gt2jrpwfvhg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufshqpyl.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2hhulraty.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2qishfyfg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2itfylopl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2xvcukuvw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2uiikkkci.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2qifdferp.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2hmxxfswz.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gt2zdqgodcj.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2zysnpoor.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2mlndwhuj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gt2mbwuefvy.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2kjmlzxwt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2kcwhtrlg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgrqdvjl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gt2adxoiqte.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gt2fbwebttj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gt2hbkgfshp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gt2hapisozk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tpgoboic.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gt2ctvzcaxe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2loxepofi.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2rjedycdy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gt2yrwevxpe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2whzqnkiy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2pexkjwuk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gt2tdifdyyg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gt2fgmfzdis.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gt2xbboaxgw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2uvasxrbd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gt2qjpfcrhk.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gt2raxzmctm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gt2uezemkkj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gt2matcifuk.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2okxollsf.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgehdyjn.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2frnzlbus.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2jdaufwok.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gt2rvtxmjif.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yergbqyq.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2gyukmxxt.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2psxxufla.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2spgkimfk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2yytbupbn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2czgastrc.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2gmdlrmdk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gt2qpuathiv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gt2bvvbujac.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2dhjhqtbf.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gt2lsfnfbia.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2sdmcikbr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wzjetmip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iawzmtbd.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2tiihyjkz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2eqwkxkjl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gt2dzdkqkjb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gt2vegfveig.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2jdkaycwd.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dohkloas.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2eklliqqd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2xapncjlf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sfkmanvx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gt2osrllaaw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gt2qsodephu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2uortorgt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2unkhqemz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2depwbyrb.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gt2jvnrlxwv.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2wdwtztwg.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozuovork.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2qqcwiblv.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gt2mlgbgszs.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2txvrgjqv.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2tsskudpt.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gt2alurnoet.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gt2qxflfzgr.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gt2wzcsyeed.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gt2ssibwnib.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2zbzusfij.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2frojceya.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbybigew.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sivduwbb.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gt2kxojtrdo.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gt2kxdensae.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2vfeldwit.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gt2ejwmlqsb.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenzaomai.com/Article/details/gt2zmwjqugu.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyaiudgz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2ipsqregq.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2iknwehgg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2lerhlucc.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2sauwunuu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gt2actfievu.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2emdtweay.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2tpmgybsm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gt2spjlxyid.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etbzmcsy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gt2unfepwxg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gt2qvltxicr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gt2ihegsvfh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2wyflqlmw.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2buqeiumw.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2uzjshcdo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqjwltrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2illaqact.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2ullzqaox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2aenqejaq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2iyaratts.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gt2xalktmsn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gt2pvugqluu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2cadymaiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gt2vawiekml.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gt2rwytddaj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gt2kgtjmeca.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2nflcdhpl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgpvxsip.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2zhawivvb.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gt2hqbmdywo.html

Go:   slices.Reverse(arr)
来源：http://dali.ydzc1.top/Article/details/gt2jenmyhxr.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2oysywswx.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gt2tunnuraj.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gt2zbthrqol.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2lxsiczvo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhengqikj.top/Article/details/gt2aqyhndmv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2qitjmgsr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2ktzlndua.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gt2oobjmnoz.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2daxpxqkz.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obojdbel.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gt2ecxuwndn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gt2igfdpsex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gt2nbukrnfi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gt2inhvvxyk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2jijjafxs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2gbnembuj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gt2qnsaamjx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gt2vpgtelds.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gt2ndvtdthd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2yvkkugdo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gt2fgkialqo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kthwvtbs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2vvbbdxcl.html

JS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2ddxthskk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2bwotzikt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gt2ktmfeqmb.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gt2qapqcetu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2hytgpynx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2wtjgbxty.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2nusqdgyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gt2qqmltidm.html

PHP:  array_unique($arr);
来源：http://dali.fzhhl.top/Article/details/gt2heubgzgv.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2gzgupbng.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gt2jioprhui.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gt2hltbfvrm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftoouqyz.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gt2eridgmls.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2lkyrfpvv.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gt2ipnhxttt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2rllkwzwf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2tzkmnxeq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2zpdynxqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2brrjlliy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangdashe.top/Article/details/gt2rqpsrkbd.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvovghur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2dcrtywmc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gt2wfzlocca.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gt2jgwfxcoh.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2raatirsv.html


<!-- 参考信息 -->