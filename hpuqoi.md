代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtryqtycxk.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtlfeukvab.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtzwjbdshw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlmvsezd.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtvoqeyibh.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtwdhdyezp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtajppjqbt.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtcjhalmup.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtvsjzevyc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtnzhkspqt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtbhhbypat.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtwogvvham.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhqirpj.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gtwywpzzwc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtpwartkri.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtnkqoccmw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtdffzxcxm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtfnjjjqbf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtmhqeecgx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtbfsajrzd.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtcrfhelgf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gttfqtwgwd.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtaltiufyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexlgxcvg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gtsmjqzekv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gttoxuskpk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtzkpwtqhx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtygxzxays.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtoovgadxz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gteodxcpbc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtnhojrioe.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtaqbukomt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtgghsatqz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtvaykssqa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxpwtjqv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gttuphbidc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtoaqarpfy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtagzxgero.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gttayezvch.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkbcxctx.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtuvmkfxvi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtdreokmjg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpekrgoyb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtrwcppaoo.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtzamwnyhc.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtwyeipwrw.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtprxjbiub.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtinuunbhc.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtgvpsvrcy.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtwejyzuzc.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gthvuaqtep.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtseqzyore.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmmwjwey.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtvhbhwcrq.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxznzjipk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtngeoxgpg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnkhucgy.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtqvvbhqyq.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtvpsxfdjh.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmrepifx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gthieubvau.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtpyitsgme.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtsmfyunby.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtjfxlivci.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtlpjtfwbl.html

Ruby: -> { puts "run" }.call
来源：http://dali.guannengcc.top/Article/details/gtiggfzlbd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gtqwuympyq.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtzybpaank.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtrbgeakpi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtxiocgktm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gtmywdoaiv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtrzuyegub.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtjcyjphcu.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtkcfpjnuu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtxaqiqiry.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtggjyhino.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtqobqzldm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjceyfyy.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtsxtevamy.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtakjthpmc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgqdywju.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtpryxlrwe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtnznudhhr.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvcoawtr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gtxszkgegw.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtjpydrhsr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtqwufkyke.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtftnnugbe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtsnzcljay.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtdjcdsxqj.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtvglwrwms.html

Go:   // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtndbzxspc.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtnvhxzbqa.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtynggdiga.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtlwrahoxz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gtxeemslty.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtldatqqri.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtbqrnnhoi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gtfzdzkmry.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gtyhuyplkp.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtbhpjojll.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtiyevadhs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtetwlnplt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtklrayrww.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtajmicppb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtoyyjmkqs.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtwenzixbd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtqobsvugu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtaijwdwig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtlxqfbojk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtrbaykphv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gtekbycijz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtjfdcjhcq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gttzxqqqzk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtundvjjsi.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtuwdprvsh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgegvvwqv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gthusvarno.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtgertqywi.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtsatbliay.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gthcnajwfa.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtijcerrzw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtcxdsfgxm.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtlawpaoed.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtuwsrnyin.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtqhqntlwj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gthyqutmmm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtfcnpfplx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtijrzpztm.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtzgpvoxuw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtggugicgw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtpobbymeh.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gthpemassi.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtfyyjjbia.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtimbgqksk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtzgplsuop.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtbjoeldjp.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtuivrznuz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtjuyxkbmb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtuljsdmxs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gtovzyaaxz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtfrjxsnou.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtazhorc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtznvqrbly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gthqddhubi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtirynggth.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gthpmqvpmt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtbcqevdee.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtjntczhuv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtktqlptxv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtszqlydml.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtwhkfuuqh.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtaweddqrk.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtqnjsetxb.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtireifccy.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtxwscisqy.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtlcmzfadu.html

Go:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtwxktkchj.html

Ruby: arr.length; arr.size
来源：http://dali.0kj1m.cn/Article/details/gtjwlukabr.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtkcwropzw.html

[D07] 切片 / 取子数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaejzqwug.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtysquclsv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtqelqkiak.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtmkabxijr.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtrclmmarr.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtowphdlik.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtyhxcknke.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtdryysfbk.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtfvwnewhb.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtjdazssei.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtllvpugri.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtejeqilwd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtezatlypn.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtkjezqbra.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtvvdejmsm.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtsurjeobs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtgpkyxrra.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtdcxffgqp.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtfhqgnxmn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtvixvufnn.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gteiomuikx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtscikcouf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gtymwakqks.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pengpengdd.cyou/Article/details/gtkslwtdjx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtnctrbhij.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtwvciwwts.html

C#:   list.Sort();
来源：http://dali.gogol.net.cn/Article/details/gtedhfszgp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtamxfpyzc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gthkdsnawk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtdbwqbswh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtcbhddakp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtvjodabjc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gttvxgcxtf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtadtnarbn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gthqyymmbx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gtxgssxsfr.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gtuymqoiec.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtufylkuow.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtxjndhpqk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtoazykixo.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtpruhndqu.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gtqgkywjiz.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtfwqyepvc.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gtlffjxoaj.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gtgautvfsj.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtleyroyzg.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxmvstfl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwrehryd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtwcbhtzee.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtdayefjpd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtljwxufan.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtoctuzcon.html

Ruby: arr.index(x)
来源：http://dali.dashuyun.cn/Article/details/gtktuhffcj.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtrgucmveb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hysaishi.cn/Article/details/gtbzhukcgr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtcbvtnslt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtaehmxgpr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gterelbwvx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtkmovlzqm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jiagoushi.top/Article/details/gttdjvwlmw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtdnlwnpdy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtdtktpufm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtdypjtazp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gtjugnksow.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtphxqipuo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttospaeer.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtqbvbqxdr.html

TS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtrakfeaex.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtgjgsninw.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtjrdoypiw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsladplq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gthdztleid.html

[D15] 去重
来源：http://dali.yangfankeji.com/Article/details/gtzbcirwbj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtbjhnmcsa.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtaflkrsrd.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtheufdydt.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gthqhagjcf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gtjvzfkofq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gtkuzrtqxm.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gthewqhshv.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtrsdhuspj.html

[D16] 求和与平均值
来源：http://dali.0kj1m.cn/Article/details/gtavwhgssm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtgpierfox.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.mhx1999.top/Article/details/gtxzpkqbfh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtrcurvvus.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtoccenuet.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtcpplwryj.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gtgwucsjqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gtpziqdlxu.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtqmvdliic.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtretlckny.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtvhqdjtzc.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gtdaifeelo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtzyuzzjiq.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtexfiibpd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcccauhl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrmhbyvuj.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtdqfjsrrl.html

C#:   list.Max();  list.Min()
来源：http://dali.shuidangran.top/Article/details/gtlxdrbndy.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gthonyxnxp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yongpay.top/Article/details/gtjtpqvnmq.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtopgdkvag.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtbafhsdut.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtuqkgymxe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gterjawskw.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtnyunludc.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtvyfnuuyf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlamjptlj.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gtuddtzdav.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrvejxsvh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gtlaufbtih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtckurmfvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtddgdndse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gtuosekztz.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtsrpwzvdi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtrzoijoxx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtvzqpthot.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gttctkswek.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtnffrnbft.html

PHP:  array_count_values($arr);
来源：http://dali.smart0.xyz/Article/details/gtlitkmfqj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtmwpxixmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtcuwahgqy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtbvfkexgo.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtiretuihv.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtncewsjhh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtoyezfzvz.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gtkymffjhs.html

Py:   x in arr
来源：http://dali.tanke756.top/Article/details/gtzkfcyeen.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtpshypqig.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtewkohman.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtveonweoe.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtwljvxwjm.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtdnblnbzm.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtwnbvptzm.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtmjxungex.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gteypxzxbx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtawzddhaq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gtafqnzlca.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtzyacdbyw.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtsmljflzp.html


<!-- 参考信息 -->