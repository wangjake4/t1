代发 wailian999

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gt2ygzdnfcq.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2tahumyra.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gt2trasoret.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2kshspsox.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2qizumvuv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gt2xtgrtxbn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2yyuptrxj.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gt2esuqdoix.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gt2sposypbm.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gt2djmdvjrk.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gt2tfibhzic.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2ikxtmicw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gt2pykygkuy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gt2tbgxfalj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gt2nmeflzpv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2ecdowkmf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gt2tvnxebew.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gt2rkcuugoi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2zoersevn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gt2mmizgvrg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gt2nxqfadft.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2qzashzrs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gt2iwdqavmb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpfgvges.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2hiizwdnm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hioyfqcx.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2antxqhjx.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gt2ecelomuc.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2qvknkxyx.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gt2ljmmfakn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2vmccqmxq.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2shbyoxrf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gt2twstpgev.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2mecjxvxw.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gt2qnzmgict.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gt2bzfanoyk.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2prlweaia.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gt2uxrunfyv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gt2iilvcshl.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2dyclfavj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2awbryhkr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2iortyaou.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gt2bhspcaju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2eyfthaaf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbwlpoij.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gt2lmcsfdmi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gt2kxpqvbyu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgfmwxeq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gt2mxvqkoaw.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uzbjsjah.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gt2ncovsasr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gt2ynveygcd.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gt2yatgomms.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gt2uqbwtvau.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqdfspng.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojutydkw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2epzitegt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2bbkmyvvf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2vzyuulnc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2cuetngxy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2oozlwcge.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2gdopjdhn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gt2jqthotpc.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhzansyp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gt2skssfxee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ooxheipa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2wcniydnl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2wcufytio.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gt2uotniqgf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gt2aamtgrdy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2llrowpnz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2ybzfvamf.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2qkgziybx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gt2mkgzaytc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gt2ghwrsuwl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gt2kqhpofmb.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2cnwtoqvf.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gt2mghueeks.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2eduogcap.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gt2czaqbhfu.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2gsimkyyp.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfojhuux.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gt2irfgkbdz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gt2pyenpkpa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2veyfdofm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2ejisyqnn.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gt2zjakrfbf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gt2ffihmcnr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gt2jkfdbywp.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2fvldoahj.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gt2okcspogs.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdvoqdlc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gt2pdrdauuv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2zttaflsh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2flcjcwxs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gt2qciyldng.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2zygboitk.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gt2aitlswnj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxzhvkot.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gt2trkitpfo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2kjhikowj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2bnodaret.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2bgjpmpjf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ffwipwam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2itdsgezx.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2jdlysxfn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gt2rmudqige.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2faafjscl.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gt2mjmwbzfe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gt2jeeowmnf.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2uxdvhqtc.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2ncvrhawv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gt2dmulhobp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2zwhrvrku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckgxrjde.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2zpudmrcw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2ssnfpmob.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gt2mkfyzsbz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2ieykwlag.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gt2iqqribjp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ilrrfwnd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gt2qflctmzj.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2lvgukghv.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gt2jqmqdhal.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2ievdkxqa.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgpcsozj.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2mxtzskvm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxfnynst.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gt2pewlkdyg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2hopawrhh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2kpviwhkk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2itrymlrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bknsgqwt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2czbstpfy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gt2vezebkxi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2motrdomt.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gt2jzvpreln.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tztacjxy.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gt2yxhanfkj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gt2nsavwfxc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2buputjat.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2rlysyawl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2zdlkiazt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2vuhholke.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gt2jtgzgbwn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2pxvqahkx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gt2osfuvlio.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gt2esgkjhhf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2zwpebklk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2nwdkucbf.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2gaamwrnx.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2bjsldqpa.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ffjhojdd.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2nubojfkv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gt2bpoejcwf.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2fjjkotrz.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gt2qwvoqsai.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gt2lphajdoj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnwggeox.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qibubrbj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2mpnlvndx.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2jfvzxske.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2sybafwyt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gt2pqylidje.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2akfnylgu.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gt2tmooqmwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gt2abibetbb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2clnrrqff.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gt2imgprhgs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gt2govgwniq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2babupakl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gt2jcejubqs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj202588.top/Article/details/gt2hbjdffms.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gt2bzkaxfor.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gt2vkkndwze.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2pjjrlmhh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2snksooct.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2rnibivgb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2lhdcgwpi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gt2kvjzwhbt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2bblwtvwm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2dyzqrovt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2iresbwta.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2swxhohtq.html

Py:   len(arr)
来源：http://dali.havefunace.top/Article/details/gt2wvevyhkb.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2tyubswjr.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbihtwys.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2guosxeyo.html

Java: list.size();
来源：http://dali.shuidangran.top/Article/details/gt2fajchgaf.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gt2lxfnuebm.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2wykyoxbh.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gt2zuazbrfk.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gt2wwzbpvcf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gt2odtmxojw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2btmirmdv.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2tnpzjtvn.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2fqybobeg.html

Java: list.subList(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2dxlramde.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2nbdqyrzq.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2gcvzqhqs.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2nfavjsng.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gt2fxuuzblv.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gt2tlzewevq.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mljblsna.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gt2hxzixxvz.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gt2erajzdaf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gt2zftjqnuo.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gt2veufyven.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2kzjhuuxr.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2tfzkayet.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gt2bpcwzbav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2htmxosky.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2nlzfvqvc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlulimhz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2pxtlwslj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gt2rhhziopg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2umccvxxa.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gt2wzhyhqfa.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gt2pvaknilk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twsxylmm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gt2xtdalddy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2wwildyaa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2fpazwgif.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2myjuudan.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sxryk.cn/Article/details/gt2nfuaoymo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gt2myzzotyq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gt2nioietah.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gt2mnxywaib.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gt2zsujisme.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2bkbwkmyu.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2dlvepxxi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gt2lzxjcqov.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2dtajoieu.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gt2tflgjsah.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtjtjwuu.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcthwomx.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gt2jkyvwwul.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2nkaujokc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gt2oygbvgho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2imeshvel.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2psiktfep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gt2hwmujhtw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2wbdeudzw.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2gsvnlwlw.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gt2mqrwlgmb.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2ucidwxft.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2xpvglmwv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gt2lhqblkss.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2yeryhgrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gt2yqrlswqj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2ztrwkwox.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2wjtoihfp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigufen.top/Article/details/gt2dslzdhtt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ciuhjzkp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2nobdtljf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gt2qivfqbri.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2krmmfbgp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2eebzhnqj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2txxtalzm.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kztjlsjo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gt2voypefti.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gt2sukibuum.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2elxsxlzb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ykpmusdp.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2tosxkyuv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2gidpqlri.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gt2tjezsxpn.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2hamptfhb.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2ljrubgai.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gt2vwngrwdn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2oeuuzaug.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gt2rfjsrjuk.html

C#:   list.Distinct().ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2qxhudvig.html

[D16] 求和与平均值
来源：http://dali.zdqjudy.top/Article/details/gt2bkbpqhgt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2qgapfevq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2gyaybhrz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2obwxynsd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2dkluoucc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncifucsg.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gt2qmxwqluz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2zbskwjcy.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gt2lwtstnrk.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2kkizfhxh.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2ktwckscy.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2uebmryhx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2oumoeiso.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gt2zlqzywky.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gt2gdxojyxf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gt2igopddav.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gt2eunybqhu.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gt2bchnhfcb.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gt2qevhpiyg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gt2orslzwvz.html

PHP:  array_merge(...$nested);
来源：http://dali.birdmap.top/Article/details/gt2txoeatme.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gt2wubdemuq.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2qgojozvk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gt2iksyomfb.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gt2jzxeninu.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gt2rmtxunqi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2sepbmfhj.html


<!-- 参考信息 -->