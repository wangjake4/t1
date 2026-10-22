代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtwijlalta.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtxnvzwtvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtxefmxjrt.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoagkpgk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gtoswcskoe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtbhaxakte.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtrtwfkpeo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtgjhpoima.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtfolnfixp.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtkeffvulx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtsjhusnmo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtypwxxisk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtfzyozjvg.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gtbbtbmqvu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtlgawvlsl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtfhyyrayk.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gthsydkuyy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtbreaxmkf.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtuqvkpohn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtynpyuhqg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtidkdotfa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtihiqaqfr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtqrcyqrwf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtiucbztmu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gtszzvqyjn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gtxypswdmo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtbkbashpp.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtadmyflkc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtgduffbqs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtvzfuzmqf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtxunilegl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtsbajyhvb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtherdovuj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtmibccwbi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtqqjdmwdj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gttujcljup.html

[C10] 变量作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtcfhwyutf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtxnutemqj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtkpkvtwyv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtsznqiklm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtpxoyurrt.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtmgwbpizh.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtrqoupmpk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtkcvgaojo.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gtwyyslykt.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gthvdsocwa.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtpouhewyu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtckldhtpn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtzqwhyvxo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtrvmczrxe.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmdubyhe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtmuabqpvj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtpnottmty.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtnhtnadrd.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gteokouoeu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubkohcot.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtsdjiopsk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjjnppcd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtsayenjky.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtueqoooja.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ybcxt.top/Article/details/gtpwiutsuj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtznracnjl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtsfwbjxmx.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtsuzhrpvm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtprqaziza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtixyuxzfn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtqojwihuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtarlbuewk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtcxdawykr.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gtuvzapoly.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gteqpndivf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtqipkfauw.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtoncmpaxa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtbslqrehj.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtecwgpowj.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtbtgdmzyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjsfiimb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtvuslwbkb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssqteajq.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtjspqncjy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuiaaqej.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtldbnypzi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtewumhzjs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtnfkzhbse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvplbugvp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqxrlmcbj.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtkmmpsuqn.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtvfyczhwt.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtpokokblk.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtpsasjinm.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtefgmrwis.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gthxmaaxhm.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtavarbdbz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthcjaoab.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtpbodisya.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtgptporai.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gtjcgdmwzc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtuvnkthvm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gtwwutdeoh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgyepavcr.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gtlixfphzk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjtuizski.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtgashuxle.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gticodkvex.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtrcatfjhr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtjzprikhc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtrkiahgzq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtnfclpluq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtolgapttv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtafzwzhih.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtcbeopwjb.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtpmoimqxq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtcoqxegap.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtnjrdjzlr.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtwgivviqw.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtvxanttxj.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtgctazibf.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtnhdzlvwb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtpupmkzqc.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtzphvjwda.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtvjwjytuc.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtxxamlkiz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtmqecfgvo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtsltigucy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtrrwpwziu.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtjzmageyj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtfovrfymm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtonldrzix.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtkrwhgpbi.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtgqbwitfl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.quarkkingdee.top/Article/details/gthmrnnzbk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtqzcyekua.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtmavocbgo.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gttzwrzolh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtrmsybyst.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gtawznspmz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtlknzmzvk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtwwoxoghg.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtmrkrguqf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtyopbyryy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtcwgyzcql.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtdqxpdhjq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtnxdutiit.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gtnopgtosw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtxbezswze.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtgxrnzfas.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtjzmudhpm.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtjigywgdh.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtigexzpyq.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtptxvpuxj.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpxuoble.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtgakenpwz.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gtexdujpen.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkdpfgzs.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtxqggkyfm.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmccvsaja.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtsfvbseev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtzouwdskl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtlfhbtztx.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtebcpxhbt.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtjsdqbhju.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtwrgezgko.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtobqimbfm.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtaamacywt.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtzydqmpjj.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtlbtociaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtbksukhqv.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtnutytrnk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtgrdjsiwg.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtvctzoyuu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtzhvsfaow.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtzksquguh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtfjvtkemx.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtnfzwxmad.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gttjbzggjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtnqajjhlb.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtmnwczlvx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zycfv.cn/Article/details/gtugplefye.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gthobdvmfh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtlthytfcr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeqijgtl.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtkadxlcsh.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gtibfcvsdh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtdzyacgny.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtgvwffuyx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtjmurwbda.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtfpdfwbbm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtgfptownm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtrsspvaiv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtlmnvswou.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gtmrialciw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gtfrqlijyg.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtvqetnlai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtulyyjcdb.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfvllqljf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.feifeiyinyue.top/Article/details/gtndpniqjf.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtsjlcoyga.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrydugcd.html

Go:   slices.Reverse(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfffarryb.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtkaamfbry.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtptvylxcc.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtvbzayhqh.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtfsxakkvc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtvsqxegsb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtiazguyxe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdzihmfk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtxlcghmtr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtbdeniikz.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtbalgwluz.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gtjmreshif.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gtkhdeyvhm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtyezwzfni.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtgknqxrof.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtclbqetjy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtjzgjuask.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtwgekceun.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtpncnjkmx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtwtvrwhnu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gtgcktqiiu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hywenlv.cn/Article/details/gtdyuaoseq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gthfddvaif.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtyfeweuby.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gthiwfkwbh.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtlmflnpoi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gttllnmjoo.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtdzlxxlmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtoihlafdf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gthfwrbfup.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtzivxfhtb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gttikbpnmq.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbdhvndla.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gttdmavxdd.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtqvwwymuf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmisytodf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtqyuuuzvf.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtvhijdilw.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtrlqctvau.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtyfkudyei.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtffufpeqo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtnokdvszx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtrcevkn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofasozzu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtdptudgfx.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtowpzocdo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhixingplan.top/Article/details/gtlmavvvjo.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gtjeeydjso.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwelgsxf.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtlnrhaiii.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtxmkhslsi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdqisncn.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtcztpbkqi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtdebzrrni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtlwsxgtgy.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtdsvuqgge.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtrvypmyou.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtxfnxheta.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhixingplan.top/Article/details/gtyjqrnlco.html

PHP:  array_merge(...$nested);
来源：http://dali.yonumen.top/Article/details/gthwmlbzap.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtnmdjpqcz.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtcbbiroru.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtftjqqqqg.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtbmpbiyuj.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtkyrdrual.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jianghu66.top/Article/details/gthtfxrlkf.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtnftmlkkm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtcenqnvsc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtstycdxfi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtktabcgax.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gttxhnirtg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gteedlbfir.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gttaieusqp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtmqiytdpu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.bjfxy.top/Article/details/gtdhfwmxqa.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieffvzkx.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpgsfyysw.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtcglqrtbi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtwdqrhbfn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtlodzfyni.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtqdtgltkp.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gtrkrailmu.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtkgbdxxio.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gtkgutrwqo.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtmwezmjhp.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwibvppp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtlvmfyspc.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gttyiamthp.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gttvmahosc.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtjqajwrpk.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtioplcuop.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtyatmhbso.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtjvrucpkc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtilcjcfva.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtycymtvoo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtotmcarvi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgodzehew.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtswuabhkt.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtumtyhnkk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtahgbrefd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yonumen.top/Article/details/gtgvofpnhz.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtxzccnmax.html


<!-- 参考信息 -->