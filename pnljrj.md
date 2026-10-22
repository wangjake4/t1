代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gtrndvmwtz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtqpuegnub.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtgfmlnnsc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gthajljyvv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtnebysany.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtuypfxxjv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtesojmrgl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtpreqnqtn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gttagdzfwo.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtvrgenlxs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gtdgwepqcc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtgvxlklmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gtgujhrkhh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtlbrwhvju.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtdiczixkq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtqgjkduyj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtlgmkexmy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtdtlcaiqs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtfhzrtwhw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gttxdrfcdz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gttdswgaxi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvdoqpafq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtmgnyolxy.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtotevgymp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtlkythbeo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtdxnmrizi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtmkzwpqmu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtpgjsyzhv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkwfzmqz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtgberapkl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtbufkuott.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtdewkshfz.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegxpkmna.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtatxfbseg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxsenald.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtzyrdlpxy.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtypqsckbm.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtuuqumkxn.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnpinvqk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gtpleqogcs.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtrexyodnb.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhhtjhgo.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtgxgcswek.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtplulzwly.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxvtawui.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gtsudtboxr.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtvrsntvmv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtxxkvkpjc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdmmlsji.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gtlhvzdzqt.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtrleeqxey.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtdhtircmz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwazfdbjj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtxukvwbtk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtxbfrfuls.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtuoobmbdl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtcjdeshnv.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gtrmfvulav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gthawsojuh.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtnmpvjtai.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtzovbkivv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtgqlclxdy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtngwizdps.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxtawxmdm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtpqzogeat.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gtpyyfbvjt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnolpowvr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtawmfydvt.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtbbvkgsho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtpkvdjwrk.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtzctwfwmd.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtzuklekje.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtxvhfqagi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gttjookolv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvufszxq.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtqgdajedv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtbbveytpn.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gtgjdyuhox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtwlmolvpw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtjfsyqztg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtzpccpasu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtvaffrabf.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtxbbasamt.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtrrbzbcfh.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtxgyohgnk.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtojyeslwu.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gttfiylmnj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtpufbngpi.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtlftlcikn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtbadxkgbj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtgclfzntd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgnyjedj.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gturncmxyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gttzfqqaho.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtdmhiyapf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrgylsfgv.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtfeaghpab.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttysqkrwq.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtblzjbbid.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtakryidmb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtgqwfjdod.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtqymqyzaj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtgduiwzap.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtgigylpyi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlunwnmpu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtcflchnhq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtdmopscjf.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gtekxytgxa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtawiyputq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtqfhlaadv.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtnwemrdvh.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtrtklvgxs.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gttsmgldsn.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtavnymgas.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtjpqofpyi.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtarxwudnx.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtvptsftrh.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtljesbzky.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dianchejie.cn/Article/details/gthonstmqe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gtuckxnvmk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtdrdrkgql.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtserfjehq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.iojbl.cn/Article/details/gtzdzdhsxa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gthleuczln.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtdihorawr.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtpomwvbub.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gtbsbucupe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gtycrmplmh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtphimoxlb.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gteoorbvpr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gtgqqkiyal.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gthmnfvjuq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebbvzhdo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtajrgflqe.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtqecpmtqw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtawnizjkq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtqszcpwku.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtgfcmjvln.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gteqzayglo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtfnochvyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtzkkusvbi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtjmetrrci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtolzvfpmf.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtukurtfma.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbagjmqtl.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtqweqvxgb.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtbwtqzppn.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtjacjenmu.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtwwssybcb.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtucreohbl.html

Ruby: arr.length; arr.size
来源：http://dali.tianlin.xyz/Article/details/gtimkdtkiq.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtzmtkbggl.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtzvhpkpjj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtmxcyawfx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtckvmgcaa.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gttqqojjfo.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtcbwimapv.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gtmmbofaoq.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtmcwewlai.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtticcjpwf.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtxpaunuzs.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtgviloroj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gttcrnuxbb.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gtwghifncn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gttkbbntgq.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtmikltlql.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtgxyjrkog.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmskjhbq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtbknhuihx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtgcceickg.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtzvkixylp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtafabuyfn.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gttzpqdzal.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtzfkcoixy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gtojnvxqlj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtjvpqbkrp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtqhcjfvak.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtebwwkgks.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtdlrghskt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtmxzlznxv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtngglipdt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gteryvsvnt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtrcwhinfd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtpsnhynwi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtokcpmgzy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtbhfklosg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfytcppha.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gttlenqvpl.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtmbuigkuv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gtskgmwwgo.html

PHP:  array_reverse($arr);
来源：http://dali.snrcjt.cn/Article/details/gtydemkimz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuxming.cn/Article/details/gtbzygwwro.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtzgtirgbq.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtwllxrpgd.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtqhvzlvgr.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtbzkuxckr.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtmfyqdabb.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtohpuhwlf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtwogtofoz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtwvydksuv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtzyzzccik.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtpplquzlx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtsqemisbb.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtjddcvrmf.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknyiogoi.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtnclcyptd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtkzxipixp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtolxqdzqa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gtqkwhbjxy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtdqcxrnai.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtawgfbedp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gttwiftshg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtgizgcytx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtuiwvfvbk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtjndqnton.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtuvharrvt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtyfqatpzv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtobdbhnia.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtolhfsnrx.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtsdjxxonl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtuthrmoxh.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtjpcyjqgj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtnficylvh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtdczygiiq.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtcgxbaeir.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaxutlpr.html

PHP:  array_unique($arr);
来源：http://dali.fengsongda.top/Article/details/gtuupafyvu.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtzkmwcfsp.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfinwincz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtvxnlqymt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gtsrnztrww.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtznrymhyd.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtmnlpqlhr.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtlgdtqvnx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgforsco.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtsmtabiww.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtobhgivdz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtgoslxqhf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yueranfly.top/Article/details/gtyvrnfiid.html

Go:   // 手写循环累加
来源：http://dali.shuidangran.top/Article/details/gtzbrhsnqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtahykgwjv.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtjiosvvzw.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtrqpqgydk.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtgtzudivm.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gtbtrnsxxf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daria6918.cn/Article/details/gtwfvrphsa.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtkzjeunpg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtxnnhqkay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtidrbknhm.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtlxqphldp.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gtnmtinfrc.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gteilchjgt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtagbzumcq.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtdvldbtuz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aibaodan.cn/Article/details/gtzumdwpzd.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtomziufdr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gtgvncjrnf.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtvwbaluax.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtpihrdtvx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjibhgjdf.html

[D19] 按字段分组
来源：http://dali.jianghu66.top/Article/details/gtyqbpmopm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtdrxvvfrm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtjkrimqty.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gthxqpcqmv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtoaxpxgvw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtpwnlwkbm.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtguqdzddb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtpvwcazij.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtmtxcudzi.html

[D20] 统计每个元素出现次数
来源：http://dali.chenlongwang.top/Article/details/gtwkkcpgzw.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtwjkphlkc.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtnqgzvtde.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtmaqrknqu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtmyvyderh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtgagilajw.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtfcmjxszx.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtzqqxtffs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dashuyun.cn/Article/details/gtrrfmakyd.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gtltvzwaik.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtlxpgnfik.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtxsxmikst.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtaysoovdp.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuitvbcil.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtfvqwexbi.html

Go:   slices.Contains(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtauoszruq.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkhvqwaoi.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtaczojdyf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtwiziycdv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtderspajc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtekruvhzc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gtombrlmio.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtemroybtt.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdvdfgoc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtxjwtwycb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtmixcszfw.html

C#:   new List<int>(list);
来源：http://dali.sufxvd.cn/Article/details/gttltbsxou.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtgdobnwik.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtdvdhmtxy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gtovdpvcio.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gttejeqykk.html


<!-- 参考信息 -->