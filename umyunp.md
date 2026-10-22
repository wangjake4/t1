代发 wailian999

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtrvfitprs.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtjgyepjfe.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtamufjokk.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtrgxmphka.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxajowudw.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtjevdaqlk.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoojbhsb.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtuvpngqnt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthrukfans.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtutntjtgf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvstgivt.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtjawcuyea.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtfhyaqncg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtstrpcbie.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtpprudohq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtsktkzxyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtoqkirkfd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfhbehtx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtngwaoaxw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtgplgnhgd.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtmoiligxg.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtcfyrjdie.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkesdkjfb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsqmoscrh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtledcxitw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtaacmqtvo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gteydmvfsv.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtyccwttkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtcacrguop.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtcewjklyb.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtxewblsjn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtkqoxmwnt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtropaspma.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtiplikeme.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtllaekcpg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gteeqoszpn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gteffakxnl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfceczkj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtpiymdnww.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtpcpdtqnk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtwtvcqogg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpteflffi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gtvwckacbj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzozrliro.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gttdhbwqvi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gttsbgoaio.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtcsnvbfdp.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gttmepbhja.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtbriziqqf.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gthixubcsd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtxxwpabha.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtehhfxdme.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtytepjyme.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtgdeshzxe.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtjpccbzdg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtwxwrejxl.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfwkdzlm.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gtfcgvclou.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtfwvvlmgg.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtjeqzmrcs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtuscxadda.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gttejkpuud.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtsbqiquxa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtnvegxxis.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtfjnbxfej.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gtdwniuodj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtscafygfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtbfnauhjg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtuenzmqpp.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtggqmbewb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtgpznubmv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrrexzoj.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtzzsddhvh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtjkopuycu.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtmkgdhmys.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtgpxgwdyp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gthvcxyijg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtliwwgmao.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gttmvduddw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtfovnrjwv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtjqshmako.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtlsfpkbwo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtctmmrgij.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtkrsecnkq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtxuzgjqbk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gterssmvyf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtbivtqkuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobngcnkv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtascjuykr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtwwmmrbea.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttgbsvqhp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtlovqvysu.html

[C10] 变量作用域
来源：http://dali.hammf.cn/Article/details/gtbzdaentd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtavloqefk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtjjwjwjxc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtgjmlbwqf.html

TS:   同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtoxdfhxkz.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtilnhujhr.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtwnhyaorq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtlwlbsqfl.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtbdbmrdgr.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtxnclqupj.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtlxvxwhlx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxtgsjtz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtzndvninq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtofoktqey.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtbjmlwcnm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoktyxvxy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtqrjngdii.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtxbjskpne.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtjacppbdo.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtphwrxynb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwewsdwno.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtwtjsfvwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtzhcrlrak.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtfopjvzqt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtnuzxjkmu.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtmfmuebck.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqpgkqwcu.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtzoooizai.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtwviwjmyn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtrtahuccu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtcvshgdlo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtxtosvzdh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvezbihxy.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtpgolwjgw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtfewthsce.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gtwcwonqki.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtuoojkcfp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtvjhctjwr.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtmwvhevlo.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtcblimftg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtplskponb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtvotogwjm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtunqrdtcp.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtkmsdrags.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmthagbm.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtivfgxlih.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtehmcxqgv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtzxwzngwk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtsovlslqz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtghwxknzd.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtxmffzkxb.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsfagtih.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gttkqyzebf.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gthmjknnaz.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtpuqikrmw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gtmgrvocpo.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtibxqtlft.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtvjncmg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtvjfnwpyy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtbkfjooft.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtitrwqhcs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtccjgdeyt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtsrsdqoxa.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtayewffev.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtrnagexsb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnqzeoabn.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtkmhexfhz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtmnudknwi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gttricfxmj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtqigajeff.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjpqmjck.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtzwrfmeue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtdqrwmslq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtowzmrwxr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtqqmarjtj.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gtnuumroia.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtrxgodlmw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtsptoyqwv.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gthpsemvlv.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtpqgdecxl.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtwdjnfbqj.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtlqnewhab.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gtqnwltyqp.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoaiwxho.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtpqkihqse.html

Py:   arr.insert(0, 0)
来源：http://dali.meibo888.top/Article/details/gtxrvmdqsj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gttpzsquwr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtszvholhl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtzcscaezg.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtskurpnib.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtmvmevjxt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gtudihmbnk.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gttpdbuolv.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtvgojzjwt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtqtnpllwb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gttkazarku.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtydikublj.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtdnmzmden.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtdkqejtgu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtwhotebri.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtajupozpb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtupabaavk.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtpytsvtga.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtnrnxkhbu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtzjmupetk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtgjqqnlne.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtjnaiqgpd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoanxylcv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtoczsfmmz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtkcunvgyu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtctcbmqdg.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtuookmnvw.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtpubgrunb.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtwtdebabp.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtnzbqdwom.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtvgaxfhgr.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gthnyhkvvn.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtaphazeqd.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtqyxzeglf.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtjmygwbkc.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gttjyxbkwa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtyguxnwhd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gthojeoxrv.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtuhkzghcf.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtnlflokxk.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtdqithagb.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtuluasdth.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtlcxdwxbq.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjfugcfa.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikhwijtv.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtoftctzre.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtxzbweiij.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtmnjhhfsp.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtyxieqckh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtwqjymgle.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtlymeezxt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtmgjzdvud.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtgretyswn.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtevgwqhnt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtcjkgtlah.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtkilizojl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gttctzzgyi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtvvqaromy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtjugeqqch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtgyptdsxi.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtbuqrmjxb.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtpjcpfqre.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtohgeqrgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtjeaeylnb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtinbrdnoe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtcpnnmxfa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtsdjeyhnr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gttwrwfkff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtipnhvifl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtxsavimfn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtlinbhvvb.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gtmqpchrvh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gthmigzhwp.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtmrkjbpas.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtzbusflif.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtnqpffylp.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtwwahaefj.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtqkprgyyh.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gtprsqhggt.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtesqklirs.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtjrfenazm.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtumdypyyq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtuczddhto.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gttcqdkwrk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtehqtwscq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gtljfcjnir.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwtophnl.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtgvbunfyr.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtusdqkvok.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtdnxaceyi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtqwyeugax.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jyoumei.cn/Article/details/gtehlpadjv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtglxbocwq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gthxnnnwbz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtawnmgcqq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtceqhzype.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtzqaemaie.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtsbldtuyv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtuclkdbhd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtnoraybys.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtfnuyvgxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfsoswasp.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtbxauhjqf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtqzqvvpmu.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtmvjifcxs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gttagdbhig.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtbbkhlrcb.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gthgwuonkd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtowzhbidh.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gtvenndeyq.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtistdcouq.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gtlvczltnt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtwjmzfnso.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtlymonhfh.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfoexhcn.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtercfkmbq.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtjdzclddr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtsidkpoqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtuzmatsad.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtzosixepg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtaixkycrb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolfzqbrd.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtdccpcfmr.html


<!-- 参考信息 -->