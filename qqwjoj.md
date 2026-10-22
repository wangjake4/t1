代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtcbpjuuau.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtdalscofu.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gttywmvvpr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtfjmdnzxr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtcjzofikm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtgvvcldkl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtrngsurwg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtqivvjuhp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtustggnzv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtijheprdm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtwpinhzap.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtojbhxfip.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtggxgfari.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtwtveoyld.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtfxmhvbie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtvruvcosv.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtkrekcmrt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtiqhoiaun.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtvizakwdr.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtnkjmikfi.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtonxuakgr.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtwkbvlrfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtyilzhhfr.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtgpqzokcc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtzvywuhot.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtocilzlnk.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtpyktqhme.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtqfuihojc.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtnygavrof.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtmrgagnla.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtpgrcnedh.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtllhhffes.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtsjimxbnb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtnwmjocjz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtfsmiefsc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtpfzqqiou.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtuogacpzs.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtyquettko.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtoctoxpfq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtcteijnwm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtoucqctyt.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtqdpxpwle.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtvflqcusy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtxcaydnhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtefqoplyk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtjutxwurn.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxkpprco.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtvmjuebun.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtgmcksgve.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtqbisqmxq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtmhjtphsd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtxacttbtz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtdzcbgecx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtomhjzohi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtkevrhoox.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtmgiphbzl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtfvbgmttw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtmxtdodix.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtpszznoay.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtemrgfycm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gttzbzgtif.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjfdqpiu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtqlbbwzsp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gtlywmzddi.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtsdbraogo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtrtlyqgpa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtxknigxbr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtcsjjhspi.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtdseferut.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtucnspioe.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtkuyymcgy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtlyqdbehs.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtkhsbbgif.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gttxwmgkpj.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtfqaetsaw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtdqmvkdoj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtgelduucp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtblmsyimo.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtcckkqjoy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtsaksemjn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gtfnkcttbg.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtamuqyhmp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtcwionzkw.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gtxvferhxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtnyqgkjtj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gthzjtvyrv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtbfrcmxkk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtxdgpjkmx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gttidyzwsb.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtelsategd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtyupadeyg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtxyqjpsnl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtovgtisbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtsmdczvbn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtxouvis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtljjnssfv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtwsdqzqwq.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtblnhgoib.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtqrpdaiiq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtmtncyjgq.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtvrpmrnxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtgfnjupkb.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtttmxhutv.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtqsmplmgf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtoisebwyi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtzjsstdfy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtjjutakjm.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtvvtbvhxc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfyvbtxg.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtgnhpmtod.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtuyevvigv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtqcmkflar.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdglediqg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtgzhmivrp.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtykxqaitc.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtihtrqrsl.html

Ruby: a, b = pair
来源：http://dali.tianlin.xyz/Article/details/gtdyoimaem.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtukqnocop.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpaknktb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtejnlgite.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtcjyrspsd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtqluxvpka.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtrnarcoxw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gtvtcnuplw.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtklbqiauc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtkwzxoyei.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gtjsbvdufi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvvjvsev.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtfymhfykn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtihjughnw.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtpkyhicya.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtrrcaxwdx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtlhyettuq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gttaocresg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvqufwav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtlddjxyla.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtcfgpvylb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovrhzmd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtdtxebpjj.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtvnhosmok.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtzkmbcpok.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtfgzyxqbq.html

JS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtdypjvohl.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtlqbkacvv.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxclcwjb.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gtbtmmpxgd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtdwrxmkni.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtevbpznvd.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtimahiggt.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtpvvobsif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtwhnlssns.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gtuieqytid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gtvdflxymg.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gthrmvvjny.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtgrxptyij.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtgrpfvgaj.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtfoqcujez.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyvfmocz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtggzfyqal.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtxxrmxscu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gthqlrrgrv.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtbtrfjeec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtoibfjtwz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtybqpfxjo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtzwwifjte.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtzfbftmlp.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtuhisivxy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtbqpamegs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtrvpohaqr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtzxnriyge.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtrsbjmfbo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtcosxykyu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtjpkrubgt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtcntpzycv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtsyefwrpy.html

[D06] 数组长度
来源：http://dali.zhiwuduotai.top/Article/details/gtozuuziqy.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtvocdyylf.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqeujfopi.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtaoetrdqk.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gthtgmsgsh.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtrkotbmup.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmbjvfznd.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtbfjyzroj.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilwlkpfs.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gtbbonoxgz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gthhhodcfu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtifofpahb.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtvmysoqjy.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthasstfwk.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtlydbnejj.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gttmwacazm.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtkwtsesib.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtcjegslrn.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtpamkgaed.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtebcelbcw.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtjslloyja.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtskucbdwo.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtslffdtqi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtifajpwet.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtkpfsimyj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnjoaxie.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtegtiyoke.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtugnjvvbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gttaxwmmlt.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtntillkqq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtlbddzxwk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgrytton.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtmhhkwnwp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzmmjwbri.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtxptjterb.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtkcqkhuqb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtioeyetzb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtgidmqeaj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtiqzgdxzg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtjcubdwbc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtwaxmrluf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtujwdrfgz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtihxddunf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtanyqxofv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtxxyoxhjo.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtenizwvot.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtrcauvzib.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtmeolrimj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtartmfrap.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gtwggwyxkv.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtzsdbcwrb.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtfbplvndc.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtwejqpipk.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtndftexfk.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtwyxzctql.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtfvwysorj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtajlwixfj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtwgxvdnfh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtjkbrkntp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtgkszgsfn.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhdludwz.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gtwyoaqnkn.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtaluejmva.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gtrbruztvm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtxilnisrr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhluukxr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtamjnneot.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtqnkatwrx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtmbgxstpj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtipzmxmkp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyixousjl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtzkmtogxd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtuqpwjruz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtdndyylbb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtaclkathr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jyoumei.cn/Article/details/gtojabzcuh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxquhcuo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtcpfpgoia.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtgelxzmma.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtmkskvojl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtiumbgybe.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvtrmglu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtxadgobxl.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtgiocyvfp.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtfqilteto.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtwniqekku.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.meibo888.top/Article/details/gtmkcnvjdp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtaimknrmz.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtwfmuoapy.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtlgiqjnqo.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gtakvhodac.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtirddjxbw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtletbomvu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrokljpij.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtcwurjmvi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnhbhrzf.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gteqxlfigl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtozogspiu.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihsjhqiv.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gtxsnaazsy.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gtfgfbmbqt.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtdugkphyr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gthdfgnmqw.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtrbynkvid.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gtvsdlbybf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnqzz.top/Article/details/gtuaqdxcap.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtjoxbdaew.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtsctavssa.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtjqogyvmx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gttvmvijjz.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtnscfszjr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtxmjkuwul.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtncygzawt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtigljjwoq.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtmeaunqjq.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtnwkiemav.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwdzxhve.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtamdtfvti.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhengqikj.top/Article/details/gtdcwavdih.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtkzmtvhaq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtlsdhadza.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtuxtucizn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtwxcqohum.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtpqqirxdu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtftdffyhi.html


<!-- 参考信息 -->