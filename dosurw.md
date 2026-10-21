代发 wailian999

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtothhppdh.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtsjcrslbg.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtakhwledu.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtjuaigtot.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzsxlqjjj.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtpsgnhzdh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbnzaqbhy.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gttglrfgim.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gtsxhdnkon.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtpewkgazv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtysmbhmww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtmkxfyutx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtseymlyuj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtnkzpsbqh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtgmcirsoa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtbspkpmvw.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtclygqsme.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gtkecbdfxc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtqcvugomd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtrjxreteg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtwanhmbds.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtbvjijhzd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtrqovyfsh.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtjzrxcnjg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtdatvxhhl.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtelsdnceh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtpyxefdtv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtphmkofxg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtihogmvjn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtnnqivayn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmtyezcix.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtvzczcsux.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtboregspx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenlongwang.top/Article/details/gtpqzlhfqm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtybogxijd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtwxcvcuel.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtqsclyaci.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtqjrjiseu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtvzxotixv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtryzmilzw.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgqwohul.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfniwhfd.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtfunycgof.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gtfegwbkny.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtqovssadx.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gtgqsodqac.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtvfjmfnxw.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtlkenxumm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gthhcwzsgg.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtxanpgqel.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtolmyfizs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gtzpvzupkz.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcstuopf.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtulnkcebt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtfucznlps.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtuupfqcsc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwlgmtmts.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtcwxcdfcb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtztxbsybj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtdpahunqu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gthxgpulcl.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtxiyeavlr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtqpnhnepo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtokjabcsx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtyascaces.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtzhgsvxdx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtzobwrjxr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtecsrzlyl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtnhjyfdjy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtxdlgssyx.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtjizuewiu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtmdsbwylt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtreelkzdl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtqfqduwqt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtvaffnqwg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtvqmorlpw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtadtylguw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtxkyfphlb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfhkgkov.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtkrgrlkpx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwksoyapj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtcdkslgvu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gteynznkti.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtdyixhuua.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtwyduffto.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtmoguurfc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtfjjoboio.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtqxjahmzy.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtpbvmpfjv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtebjpnrna.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtgupgkvjk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvexsgyfh.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtiqrdiysa.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtqzjbyrqn.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstsctcok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gteqlfuzph.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtxstctfxj.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtfoplcwga.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtpcepgxhq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzonoalw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtypjafbxk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuahbqyfe.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscogkceh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtndrhpqmg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hammf.cn/Article/details/gtzcsenljx.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gthfabckcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gtlvwlpvxm.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtdgfpcvpu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtfkjqnbos.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskoyertf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtpyljednv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtbjjmwoqy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtfowagfbm.html

Ruby: -> { puts "run" }.call
来源：http://dali.iojbl.cn/Article/details/gtckywzpkq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gtmjgpjmzo.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtmxnnlety.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtrdksyvyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtlpgaemck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxchgqvf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtowxcxszs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtvozunqnk.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtsqavdsjt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtiqizkpjz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gtarpagzlc.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtqqhqwohk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtditwkxkp.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtzxohiqzt.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtugjufdoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtucwmgtuz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtietbkpkv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtchvrvcjs.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtjidcwslm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtjacrjwoz.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtkwwrzkbj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtvpjckkhz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtqlcuvfvq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtauxucrse.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaonqunir.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtnjmropix.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtcearmkcl.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtsqjirwdj.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtskfsnagb.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtqjysjsnb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtbqlzgktm.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gtiwwwljqo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gtylizjpzv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtknjzydhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtgvaejyxm.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtpjsstxai.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtwjaunqby.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtntqbmsnx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxhrbnnj.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwjguhtk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgohsqasv.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtueddbzhi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtpogxrbtu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtwtfoggdv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtdlspndrr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtlfcwumsv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gtwftpydqb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtpyccejba.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtgooffqlg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtihodoukj.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtqafplwvz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtgzokloun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpntbglt.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtomhzpigy.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtlkymwgrh.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtkyljjczr.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtdcwuadyl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrdcpnky.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtlwiayoll.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtiouuslxc.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtmizwvbuv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtwjshuwel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtfyjesxxo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gthbgvspqs.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtmmwbubka.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtlyuwrcwk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtjfluzbcb.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtbnibiptd.html

[D04] 删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtbtudtecz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywcqlyef.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtukvkmuzm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtmrscijvn.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtpjcfxtnr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtabpknvul.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtulmjkrjn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gtakbkiamw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtttlekdub.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeopggbg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtdduqtznz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtwvbxtnoc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmjusqdk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtopglitmp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilckaody.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtnmfzaeco.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtmqsgtylj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtilrckmun.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtsewqfjgb.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtsjoeelms.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gtuvuqkmfy.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtxbvzqccl.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtwfjzterq.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtfeueuxtr.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtobjwxanc.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gthllynjqe.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtfyeniaoo.html

[D07] 切片 / 取子数组
来源：http://dali.nwbrower.top/Article/details/gtkxlvddjl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtqkwjhusd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtkluvenxq.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtmtidbqvy.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtugiyfzlm.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtkdbzki.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtxvsxdtvv.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtdgvwdakp.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gtvzubdcjo.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtzpxdpuof.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtrxagcrtv.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtezarkamu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtxpfkfmfr.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gttligopti.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtaypngiok.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtgcxhgpsk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtsbzbkcna.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gttleckccf.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtdtujgpta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtbfscnjcd.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gtvqkzbuxc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtlbgokhzj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtbgmjswqi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtyijrulzg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtvdnpnrnn.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtsjxtjsoi.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtylcsfedh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gthkwhcdid.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gttkxooqjz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpldmszxv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtztdxgqmh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtlxdyouna.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gthncklver.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtuoudnoqr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynvfxrba.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gtctpsbcfi.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtffmcpbyj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtoowekikd.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtiblmvblg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtkynmszyc.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtvojykzpi.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtkwddfgrr.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gtlowljmzz.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtajyoteec.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gthlnbafiw.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtbwpodugx.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtmmuyroxl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtzynywnrn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtvtzcsszs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtaggnledp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtzbimxurn.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtyzdrllkf.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtprrolqbo.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtlqfpieyq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtmvicssid.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtrgditlkb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtmykhjrar.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtwutwvqiv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtwvamhhqz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtjxwixxbf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gtulchbuyc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtxkjyopmu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtohrgxuot.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtglfyrswr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtghduhdwp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gtccyhjlio.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtgmcbandr.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulrmjyzq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtskugdfqo.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtgskljcsa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtezrsijoc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtszmxthnu.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gttfuvfjtj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtoxfexyby.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtsbfviwgd.html

JS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtpawsfmxc.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtgwakvcjx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrsktdmq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtygqcmpri.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtvbtjszvx.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtxeniwvpe.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtnmkhsomd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtkiatwzhf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtbddgjqxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtnrvzyfwh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtjczvxnrq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tian-w.cn/Article/details/gtekogqfui.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtazoloxsl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtkpobzjnk.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtjrjkgbht.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtknwfzghv.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtwhbnzvdu.html


<!-- 参考信息 -->