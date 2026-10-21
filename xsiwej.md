代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtyfyfwitt.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtmlkhkycm.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtsojcsfdr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gthmnnuyjm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtyimvlqaf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpdhheuf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtejrfspvf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtlaaybmpc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxbmtvawe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtumcdneti.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtuiuaqlmw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtcsunwicl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtnfhzutpa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtvmrorsbi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtggdvwnyn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtxeimpeda.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblhsebkc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtvqopbkht.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtidtfpzhe.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gtfaohurza.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtoaxnfrvt.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gtiqvoptju.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtlkyegugd.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gthdejgkhg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtsybaklrf.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtqmpwtdgd.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gtyjfwbqbe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtvbthwdoh.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtmdirdjia.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtegodfpfl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtqwuzbazc.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtvbkbrahq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtvqpcncry.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomehplxe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtvxldmkzr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gtrptvkops.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtzkmwmjum.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtoxfxceuw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtusyuwszz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtczalfpnn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtelugjrzg.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtgqrsbwgy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtcrbyxscc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtueyeoaxs.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtabkdnvde.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gtmezxlobg.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtbxnxnfzf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtntqqvxjn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtsfcrujtj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlklphvza.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtvbhhvtkm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtcvplnyzz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtkgwmiivv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtoaledvwq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtlszvywoy.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtfvsdftwm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gttgbpqknw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtwowrqaiv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtnmeurdtw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtfsyqdksg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtdjjxqslc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaexarhy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtycoyvbdo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtkpcgectw.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gtibctrumb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtltqlintj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtbgxhvhoj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtyhfuumva.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtrjitijiw.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gthfzcwpun.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtjkxiroha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtiynupfwl.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtezpauefg.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtlbooibxl.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtscyhebqg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtrlpyvnvj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtvncgoyyv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtmpzrmuos.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gttrhxptib.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtgzybwmfy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtbewmxvob.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtvtkfvobe.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfgnarzk.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtpawkqzel.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtbkxdczux.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtxvbwcgmj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtozahlzac.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtzimnzvrk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtrswoeyar.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtwpmznejo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gtmzcflfex.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtwdqnxmwt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtwghjqmzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyhtvgocu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtvtdqgslh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtecdxsifn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtpohceaya.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtpueruodq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtzwczsrhp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtycaofunu.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtksbbmlgt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtvairhdha.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtklijfods.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtwmuhmvab.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtslhdakeo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtupovyqnb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtfyusktwn.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gtfyuzbeja.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhflaboy.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gtvvidatkn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtcsxsslzv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigufen.top/Article/details/gtpyckflzh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtylscngzv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtozcwtqjz.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtwxcjiupt.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtjcowucpm.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtdmcvqdjp.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtqkjjwjbn.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtlslwtcae.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtemskulgx.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtuniuendb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtfnfuptas.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gtihbcozrc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtazfccnmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtlbgsqkbv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtwzrtnpka.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gthjhgfwef.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyczdddbt.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtpcxrwfhb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttcwzeeey.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gthhtfoehe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gthtkifsxd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtpxnijpwo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtqdjktrjw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtfgpbwadx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtwuasrcue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gtpyeyvmze.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtxdidomsj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtxbhrfgvp.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtadwmhdjg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtifmfdovc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gtdbifczvl.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtzmqlnlcc.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtcwwgwqsu.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjenwcrf.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtxfneewzx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gttmhhuueq.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckpidfvf.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtfodhmtte.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtgneyjrbb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gttcjeqnwx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gzhubu.top/Article/details/gtlzkfqfcg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtjqdhuzqb.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtgtjqrrch.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtwppufgyk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtjtrcndwv.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtoyiadavi.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtvmsogzgg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtdofnpver.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtlsrqleri.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gthjcntmde.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtjfcaygmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtrfwvjzwr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtjjcphfbk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtqngrsngr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gthlhizmpo.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtruriuqgp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtlncurkxs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtakrolrrx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtmwbshuuw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtbaskwmcp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtrcnzwrji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtiobwhlqb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtcijcxaoy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtdsgxcarp.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gttvdyazcc.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtsmhdrldo.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtxiiuxzvn.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gthmzkagee.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtvcdkcuih.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtltcqksat.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqyboeahl.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtiipvivis.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtyamhpwqz.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtchbxakoq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtwvalwxfi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtccodvzxu.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtvktsicbu.html

TS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtbythedvd.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtbyhthqbf.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gttghyqbtv.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtzwdnklhw.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtkwewctdr.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gteyyvepyq.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gthrtfonut.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gthfrjmepe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtxfwohtwj.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gttdgpvpsm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gttxwrywys.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gttghmuazw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtwtthajts.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gteexnxjkf.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtfzsqcrpk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtceybsmue.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtdgshomwn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtoflvunvu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtzewwkezn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gtpbjburqz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtizjojvdr.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtjuhyijcq.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtwyfwbdyv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gthpscpxjp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdjvtpfz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gttfkhysbk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtmufxoflk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtkkxnwnsb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunbvepzf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtairtanwt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtgobzdrlh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtajfrmqjd.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtyznalghm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gtjnkxqlhm.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtavjceahk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiranleyq.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtcxskuvdt.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtyggqfawl.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpczwhxcj.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtosntfxdr.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtmqrvfdtr.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gtidriaxck.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtgfuutgap.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtpehycxtc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaongswp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtbpzkzovx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gttbzoxsol.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtbhpdcdfb.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtfmkqcjge.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtlfidqrdf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtjetcpcwz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gthzgrbqbo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtriloej.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gttzekmobg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtizyhpmwl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gtkvxfvxkd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtdacbabhk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtlhhycjae.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtiarptpuq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtrzuhxjiw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqqcwgkr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gthzevyzjm.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gthuxrgtod.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtzmjxcssr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtteiugado.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtmgjgkttp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtwlcajhbs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtgarildvq.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gtcghgfhst.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtnlnelmdv.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtxgsxsvaj.html

JS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtnesrefbh.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gturlaxotz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtzwxdrqpf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtibqytmam.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtbvrlakho.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtdujmjyyk.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtkskeriwc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gtzxtlzvsd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tian-w.cn/Article/details/gtcudfmhlk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkqbvtkez.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtipwpkgft.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtutetbgbl.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtmxpashsp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtluuihnaj.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtfpqzxdsv.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtuekpshtd.html

Py:   max(arr);  min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtagzxxawo.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtbzptsjry.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtwebrjqan.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtklycwqlj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtncsfkiqp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaypwaqo.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtbeemhnfh.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtsoojvyrv.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtibvpakxi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtccaqlyok.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtxsdwrqyr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvahfljx.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtrpgvfhqx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cucudq.cn/Article/details/gtoduiprxp.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtszzfrpkg.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfborbfy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtynetncgb.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtvbdkrbwm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gtjdchdzry.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.meibo888.top/Article/details/gtunvnxrzk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtrtaucfzt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtxlynxqjb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtmjkxehru.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gttsajflcw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gtqddmhryr.html


<!-- 参考信息 -->