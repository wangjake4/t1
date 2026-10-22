代发 wailian999

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtvzfxrwca.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtyjbxshul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtqcgaxpog.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtldzrigxt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtpwjxmkhv.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtmfsyqdna.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtryxaivvm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqlwjnig.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtfytvxudk.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gtepwhucbj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtqegkputg.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtddtbnprw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtjrrtrqbw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtkpuzlbib.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtlagowpew.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtzvrzokii.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtznzrbgsu.html

[C07] 把函数作为参数传入
来源：http://dali.hfpthk.cn/Article/details/gtndfhfbpp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtaitlbkcn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gtwposnpva.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtscyohbds.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gthspsxqmk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfztogjc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtxylytrse.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkrenugk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gtgsztqgqx.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtmksezwyu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtfcktsqim.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtnoiaquvy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gttkcwukkq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtgvbuircj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtazcfzaxu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gtcecfndsj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtwgjzdlat.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtcwkyflva.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtyhgksudt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtsdkmuxov.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtbhqyzubo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtvbptqkzl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtkofhkpri.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtmhmdfjvz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtcosfonod.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtwroqthzx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtuwrpqeqz.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtevhygjjo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cashguo.top/Article/details/gtsknlxwwt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtotvbmkbu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtuhuywsvl.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtgoecvsyu.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtkkvghsba.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtppkfyofm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtydttcblz.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtobfzwbxj.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtndprdqsu.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtrmuvweys.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtfnyxbmfp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtywpsnzvr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gthomtorvs.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtblwiabrb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtyniddpmx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtomowcfqj.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtlvfrujqu.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtiagxacmz.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtzatrnnfi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gttoadyrbg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtrxrnnvqt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtlkxytqhk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtcaqzadoz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtlwieuigt.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtacumiega.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtlpqmqdnh.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtmhjlihrw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gtctyjqlfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtskuiiqoa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gttfwuiwtv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtlhkalxcw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtvditvkgb.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gtxjvebnov.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtuktqdpbu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfzkhlul.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtrnescyfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtzxvvbjtz.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpevrtif.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtqmnbexan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtegiznwos.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtdbxtsqld.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtmxwszirq.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtzivztylv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gthtkugitl.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtwmzjalnt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtetxbvjne.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtnenjkrfn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtlyedjopz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtrbjgdgmm.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtpeedmyxa.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gttetwfnhz.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtinxdfpbv.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtvzlimihd.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtmmlzltsh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtmlnzjjjb.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gterygxjeu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtompbkswt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtoeifburs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtcfjsxsme.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtabwbdxpf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtcnckwcpz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnhzutdfa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthfldumqb.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtqnhktphj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjvgrsuol.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtahnqfjto.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtpkhmoxxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtfyqsnxyk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtaizpwbpk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtmmmxalvt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gtazorynyk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gttujftbba.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtcjweejgk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gttkkegipz.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtmaavweyt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrmsjht.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtjkbsbudd.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtvevoizxu.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtwfxtmopi.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtxeufzkyn.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtiosibvlw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtesuzblvg.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gtmqcquzhe.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtmwpnbbex.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtxublhhmg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtrltxsibq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtccrqwxes.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtefcqakbn.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtxnwjedlw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtwovpsdex.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gttzevlkqt.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtrdhcyjhq.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtsrwbcpmw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtataaojaw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtzpopeaup.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gtqlmduqkw.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtnlclyfmb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtondziqvv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gtkwrrqgzo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtihtswqqu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtvtqcfuen.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtkcypmqid.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtnvtbypdc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtyjugvzgi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtchvmcccu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtnjoytisf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gtqffqulpw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtzxsadwic.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtrugaxthi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtdvryylnb.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwswtera.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtaxqvjlpe.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkvvzqgjq.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtlkacxlqd.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gteyqkqxzv.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtwueccsbq.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslbdtmgw.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtesgsrerl.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtmczaipbp.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gttlbgzjgn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gtydbvfunl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtlaajkgcu.html

JS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtlkxswwwg.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtbfbmqxfb.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtdgumyqrq.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gteetqxysp.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gttpfvzyud.html

C#:   list.GetRange(1, 3);
来源：http://dali.ehwqpu.com/Article/details/gthmlwlwbb.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtlhbxxyso.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtmorucpbb.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtfghrpiwy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtzfwycsxj.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtoansgiwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtxusjwjxr.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtlydkwgmt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtnrsuisaw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcreqzqqv.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtcyclvduv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtzvzdeixi.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtizdxuejn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtespjkkyw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtelwqmoba.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtlyayydak.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtdafscptj.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtesseeowt.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtnvfdzupn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtsnhntgxy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhoulong.xyz/Article/details/gtjkctuiyq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtzqqtwqiv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtxfqrreqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gtigmfytwf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gtzksfqxkx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtscegkvtl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtdnjehfio.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtktfdfumx.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtrufckeel.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtwjfzsxnt.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gttjqqtlpc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtvlvfdtyr.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtokgzzzpa.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtlyzjcgow.html

Go:   slices.Reverse(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqzlxyoqf.html

Ruby: arr.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtvxekeotu.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtjpeygkos.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtlslrqrls.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtxjwaqidn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.andypj.xyz/Article/details/gtcutkknll.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtrpogslaz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtybaeubjl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtuykapoke.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtsxmuuptn.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtcadpwllq.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtciqdmgxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtstgysjau.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtqzqdhxsh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtpdyesnit.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtumrpbsll.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtfifvondq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gtqvnvckxf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtibgbrmmu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtaaqesenz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtlqbioaqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yanxiufei.cn/Article/details/gtfgivgmsf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gteyxnkuid.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtjqyswzai.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpyrxkbl.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtkjmmypqn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtlftusrwf.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtaqeuyyur.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtzuomigvr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtfzkpeysi.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtduaaxrkr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbsufdyp.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gtzocqqfws.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtgaycgokp.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtomwgikoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtmvdrogwb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtgjkzylaw.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gthdvzdzmx.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtksmrkrut.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtjdguxhur.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtawqbhsir.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtvvhxksxy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gteyqegnlp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtbjehndpr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixvviykv.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gtyyqmwtuj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtkoscdfny.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gttzduoeks.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtjtbmqgyn.html

Py:   max(arr);  min(arr)
来源：http://dali.wangdashe.top/Article/details/gtkfppujkv.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtxjdndumj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtfkohoxce.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtvlxqkzxm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gtioiwdfbi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gtgkusepky.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtmfjwwsnv.html

C#:   list.Max();  list.Min()
来源：http://dali.zhiwuduotai.top/Article/details/gtxbltdydl.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtnjewtqkh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtmiatlozn.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxpflcwt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtwqqumkov.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gttsuwzgoh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtaadwmgjl.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtpfufatgg.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gtinphmach.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtyjznhdjg.html

[D19] 按字段分组
来源：http://dali.cucudq.cn/Article/details/gtubvewnql.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtkifdofsq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtglhlpkec.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtbiabiibi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtzklajecc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtmmygmchs.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtafxoysjy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtssrrlfta.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtagqmjilf.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtgrxfsebn.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gttjlifohs.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtrpnfjmyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtugipppmy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gthiwctjzo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiidsxvd.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtemigdwhx.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gtacwymtgi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gtsbzhmllv.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtmycdlccx.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtkharduqo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.birdmap.top/Article/details/gtvohhxwaf.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhauwcub.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtjstexyui.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gteyuxsebs.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtnfvtokwi.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtfshnngrd.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtjnbfzsvq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gthvdxzder.html


<!-- 参考信息 -->