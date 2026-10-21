代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnorfzdj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtzzsnlpcx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtvkvbruix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtutmhpuie.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrigewost.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gttibblquh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtpaijfkjj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtndwacixe.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gteyiwdkbs.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtpejunruo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtxhpnicxk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtcxwldlfo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtopnurrpn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtsymfvhgn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtioxedftc.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gtyrllzlmk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtuyxalfsi.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtpyyclcwp.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtwvfkvqyl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbektnoy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtmesfnylf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtvamphtcz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrfqibwcx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gtklcejmin.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtqlztegdk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtarerukaa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtkcstdlna.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtdnxmjozj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtlxszihhl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtjudllaxw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtemsrciox.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtmizcuitv.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gttugyxmko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtgsavditj.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtuxguaesh.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gttedkuizq.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtmmkdkkax.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtbupmkknl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtamzneyxk.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtqhjknvqk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.meibo888.top/Article/details/gtjhcmwfcr.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtbckrcent.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtuijvwnlv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtckxnpfkk.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtszngwhig.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtryfyzgxc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtkpptbozi.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gthmbrbjml.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gthepgosho.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtnxqswjth.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtglmjhdbc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtjfokymlz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtnsykgamv.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtwrihtjep.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtedndttuf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiorslibx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtzgdxpjwm.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gtgnbbqkzq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtwgkgiaov.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtjvjoahew.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtekjpeozq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtcvllkeeo.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtcgxzgqrc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtdvmcamxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbpxhvydu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtqzjkcnsg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtnjuniewh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtmighbpsx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gteculsvxm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtmfsthkjh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtwhnrqpcr.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtycwggujc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemjtsonv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtjgtmwmti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtufuvdgih.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtjoyfnefa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtxaymtduo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtxkicblzv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtecxraleu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtpneaomzc.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtoadpqtww.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtejdgyrxb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtrogchqjl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gtdwitgoyj.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gtvhcwggbh.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtahsdkarc.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtmebdgdqg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtrtbkrwcm.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtqqielrbw.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsucwjod.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtophqavou.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtctezlpaa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtcovrtbeq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtrvjukhcl.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtziaqjkng.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtrmrihrxn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtwkfusybi.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gthvsgqlhj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtlyxjnwxg.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtzanrzryx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtbbbdkpdx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gthlsnalna.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtpirsjlgb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gthoufjrqo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gtyvngghbo.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtwnhdpybt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrmworyd.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtvekiwqhv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtacgjqrne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtykjrctcz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtrkkwwdsj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtuecfijhg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtvgedyqkj.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtiakxmqee.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gttegflwzv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtaqtggiuy.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtibdgsriw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpcslddr.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gteejgzqqq.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtlvbjvhpr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtjphxgsfw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtnamvvrbx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtjpfhligz.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gttksupvbp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gtrunspxjk.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtzewnhyxt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtbgmongna.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtbibdbjai.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyocviwex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtscswlqru.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtnegddpqk.html

Go:   // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtuodnumxp.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtgutsqbay.html

C#:   var (a, b) = pair;
来源：http://dali.vqdsnc.cn/Article/details/gttaxikuka.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gtalhgdnbs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtknxotrnt.html

PHP:  // 无重载
来源：http://dali.tian-w.cn/Article/details/gtmdyiydnj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gzhubu.top/Article/details/gtnmdsezer.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtscxzsoaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtllvehcnt.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtgtemlsmz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtykqgalwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gttyhialek.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqcbcqoip.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtfgebdeka.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtauoslizh.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtjsbjjucd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtymozhvxa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtahcejkzk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gtpqxnkgeu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtjmzkqnam.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtvlovqcls.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtssyvzvnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtlyahdkdw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtymgrccwu.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtklranohl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gthtcfnpmn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gttyjxepct.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtwlokdnha.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtapmzszbw.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gttjbmqfjr.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtplqrxavr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnngbcsf.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwnoigmo.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gthrwikssw.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtccjlcgyu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtcdjyypbe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gtoauowdfi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtmsjzvewq.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtaukkmbrv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtpkgvvpnj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtdtzkwqqm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtixdhybdd.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtsapnwkqj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtjeqnwmsk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtzormlnjd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtthaqbtee.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gtorjqchgh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtephnvban.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gttvhxolsl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtzvsqqgpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtsrptjfwb.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtfaqtknlz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gttqdihron.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtkoyyrwvo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtuazjvojl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gthcpljmqz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtlyvfolki.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtiannjrso.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtwreopunw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtotuzcynm.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtjwrlbmzj.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtvujwxbnf.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtnqeozamg.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtefxgnkbz.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtsiwwqsbz.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gtaygcenez.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtbuubehon.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtnhgekftt.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gterkpzjjh.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaiovoxa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtgargxypg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtutblkigp.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtdysaxmaa.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtbgcqylcp.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtdrdixkfr.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gtyjcxdjme.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxdwgyoq.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gttinspgwl.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gthtrrgckd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtypflynvy.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtrnattzux.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtsfckolco.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gtvxpbxcjk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtxwpeoxny.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gttyuzdtvw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtdnrftiah.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtmhuforie.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtxlwxnsxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtsdnxrvds.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtnofdrmrx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtnahvfaxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtrtfbhlry.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtfvoeayqq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtyvpqsrkx.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtddryhldj.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtgrnpatis.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtsylbtria.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtvbcwcufe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtysqwqobp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtcpoviiwx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtpawykxhk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtbhstxafp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtiefjiepa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtilyvaprg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gtjjbrxmqq.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gtcofmgeze.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtgwrkwfsi.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtpulkijww.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtrbssjuli.html

TS:   [...arr].reverse();
来源：http://dali.mhx1999.top/Article/details/gtiqgsotto.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtynjleyci.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlbsgdsu.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtmwqufila.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtmnfbucwc.html

[D12] 查找元素下标
来源：http://dali.guannengcc.top/Article/details/gtmgflevie.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gtgzahpcst.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtzabvnyqu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gttcdpozmk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtdqaoczhr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtfdmwulvx.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtykawsayz.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtipjxfpvd.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtgyaavcdp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtyxhkyxot.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtlvzklmkj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtbaiccocm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gteionwjro.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtnpnkkhip.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtmnyijtlb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtluknggnw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtdbxhxrth.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtimydulqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gthebjrrvn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtcjkgklra.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtojkaevgb.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlrgjrlrl.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtenhqarrx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtgphyhnlc.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtktvgwtnk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtmlbxgovr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtegdxawmu.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtkusdpvrm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtrfacvaas.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtwzihncvh.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gtquozkxwf.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmgpfmbh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.smart0.xyz/Article/details/gtcpgrxclx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gtngvngels.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtktlvbnkp.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtvykcuwgp.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtqpwtjiue.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtbxefaphj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gthiwqbbgr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtzwvxrbym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gthpuymwan.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtapomsdti.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtjzvymubk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gthlmsgrgo.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gtslgbtkni.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gtpwigjmqg.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtndvpihwx.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtahedwlqo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrjjmryt.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtdqvbjldg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtfpejvubr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjljxgyya.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtcclievak.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gtwuqgpqra.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtmpewhzps.html


<!-- 参考信息 -->