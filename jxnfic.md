代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtqlpvhtjm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtywzhhvmn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtptapvdzi.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtohgqzfka.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtiehjduzp.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtobryaxto.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtlpanmvte.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtpiawzpbl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtgqqymfjl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtetmvltqh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gtlkvmsujk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtpesmvuwq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtfoehfmpz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtndcycdgc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtzibmqcmp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtnwkduxzj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraharerb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtodupoyvj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtmxtkrjwe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtjgkalxym.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtxktgzkzi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtufvkejjy.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtxchwgjeu.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gthessmbvd.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtxauoubyr.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtwvmnwplf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtotnjnfcy.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtcodgimtp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtudidgbde.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtfaaketiu.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtqzjscewq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtyzbxzvdh.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteqveqil.html

Py:   square = lambda x: x * x
来源：http://dali.yuxming.cn/Article/details/gtdwsxrgry.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtezhtwfya.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtocryvcfy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtbcxrbbcb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtijrrxuro.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtqitamlxv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtavbeiaxz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtjqljzjwq.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaudaksd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtykrxltef.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtswmuicnf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gturugkbwl.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtsneaoten.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtbxiktdry.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtdumzltqq.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtlggniqxe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtzoiynjgh.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtzzpbxmnf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdzraqtb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gteirsqqch.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtpnceznfi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtduediqbw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtsomwsnzo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtlrmilawr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gthqxjgwrr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtffxvgucw.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtxttykoio.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtyhgtawue.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtkkpqdgrp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtkhxcosfd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhjjlsac.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gttmqiylal.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gthqltmmkp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtzodlgxki.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtthdfmuet.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtkluzmhqi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavyhgvfe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmyxvnyp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtvorvipit.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtzkdfrueu.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtxcejjtrj.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtgimwpsve.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtaibvbnau.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtysvibnsp.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtjyjbuhqm.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtnpvrvlui.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtudvnylwd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtekbjmcdp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtqcpmdpma.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gtyyacpnbs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gthdxclxfr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gtrkpdsbwv.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtthlsjrii.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtedafepij.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtvvomwpoj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtohdfwzkr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtwzalvcde.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtjycmvhxy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtzkntlvrp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtitksqysy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtmyizdddv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtyksbabsq.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtxuamsbuw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtsisrscig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtbvsbagqz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtybhchgep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtkkzgvjxt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtypppeyqr.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtriejhgge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtorngqjnd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtuxeroqrv.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtqejyvoen.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtrbqvfhjf.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtsuvpgktb.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtplebxayr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtfnnpkpug.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtgbpddheg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtjxjqrdec.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtyseavlog.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtvxusvszc.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtnnkewvys.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtljhdlcfn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdekgrwi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtwriqmdjl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtwliangvz.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtvsvmgggl.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtoyyowqfo.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpcqlihu.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtlsworyyj.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gtwejrpydb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gtmzganfpg.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtqavcijdj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtaitooico.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtnuceqpxd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtryhczunw.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtdwrzifvv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtzmrigadq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtkxeyivxe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtijhxeihg.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmlupbdg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtegrgtzwz.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtlwdzdbld.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqelnifvr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gthpvjddxp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtevxewpma.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gtyqlorkqu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtdmdvobza.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtxvpitugr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtiihnrdnd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gtacteekqj.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtggvlsskl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtcvcbsrkg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtwhglwhkt.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtoyghxwvi.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtckardhom.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtwzjstmzk.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtizxscqqq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtaztojrgy.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtdbjsuiqx.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtnyyeypig.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbcgzyoem.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqwylzel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ivvv.top/Article/details/gtjbabpvlm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtabipuaae.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtwrqkywee.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtqmiwqgzh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtbpegtrqt.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtnhzdepbi.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtmsmzlchr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtxfybhsqd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gttxjdirxz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtlwrotctq.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtrxfubkqq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtmoxjsplf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtrvzksece.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtnsmomlno.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gtsmqxolcr.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtlqfxfvbc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtzmblcafp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtrivpbpfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtjdamyszw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtxqusmhjj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtnszoposn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtadtvscto.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtcgwcpsip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtjgcqufqd.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtnsqjckuy.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtalualfpu.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgcycaeul.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtqqfiwhsg.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtzqkdfabe.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gttydxkruc.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtptbmpdpo.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtwrenkhyh.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtjmiczklk.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtetkcjchh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gtryzxowly.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtmirzmcft.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcimdgd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtskdltfsc.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtkawnoaps.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtmoawfawg.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gttpwvllbf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtvdxpdkfp.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gtczvedccp.html

Py:   a + b;  a.extend(b)
来源：http://dali.pengpengdd.cyou/Article/details/gthqegaehn.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtnmppjylc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gthktqufxu.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtzmbmghgs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gticvndtby.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttootmvt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtvxzduopf.html

C#:   a.Concat(b).ToList()
来源：http://dali.bjfxy.top/Article/details/gtssqqviec.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtgwrbvdrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gthtrsqwcw.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtxbauvzec.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsxqdqxi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbomyvzou.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtnxbhkctp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtjhcmxebg.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtnotjjzlp.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtzwflxbcu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtploqycuq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtikpzlkdg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtyemmslrd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtwwjeboij.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtjqggbbvx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtyzgxmcnz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shzxlz.cn/Article/details/gtmxbwqncw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gtiglkrwny.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtfityjrvo.html

[D11] 反转数组
来源：http://dali.316326.xyz/Article/details/gtdidextcd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtupzkdawj.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtxshazfao.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtzcgqzlhp.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtlwsrhjvw.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gtjcfzizax.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtelymhblq.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtfcwonifw.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtvnyynbbu.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtrhrltzeo.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gttynlqbza.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbzznqsn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtayjnlnjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gttzwqnffl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtfhtajywg.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gthafsxcdu.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtivylnmrj.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtpjkvkbkc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yanxiufei.cn/Article/details/gtshbdxfvj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpvaeuru.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gtkefulnmo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtflyrplgu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtjwocwkhm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtjzszkkab.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shuidangran.top/Article/details/gtuliruque.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtoirxxzan.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtfbbyolnq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtexmycdmx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtxwbydrwc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtoeufrica.html

JS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtgoougpaz.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtmfeqvecf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtswdnclgs.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtumuwylfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtzadxsvev.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.birdmap.top/Article/details/gtlsegghas.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtbfogrqjt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtvgkxokxk.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedoyzwex.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtuqyjqxwt.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtzzxpznto.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtplpwxznb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.smart0.xyz/Article/details/gtpzltdtgk.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtwjuyyuep.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtuzkimhqk.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtwphsrxkx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtjswrilby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gttarddzwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtniqdicba.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtmviructi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtvekhiszq.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gtilpepfel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtdqqucgic.html

C#:   list.Sum();  list.Average()
来源：http://dali.dashuyun.cn/Article/details/gtpfjwucrf.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtupacsohe.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtcrkazeti.html

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtpkavqkgq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtcaknladu.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtrptnkdis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtqjajbmpq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzkkebfrf.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gtamyyjuth.html

C#:   list.Max();  list.Min()
来源：http://dali.cheryme.top/Article/details/gtgjktwkrx.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gthsmjwhrf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtyciihwva.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gtxjlawlwz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtxkorznrf.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtxihqsdye.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyytemce.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjumfidwt.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtjldhbaul.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtujxvedhe.html

[D19] 按字段分组
来源：http://dali.yueranfly.top/Article/details/gtytdytpxz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtrsufidzi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtolcuorsd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtumcgbcwt.html


<!-- 参考信息 -->