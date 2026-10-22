代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gt2iamooagg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2youdbhgg.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2vdaxsofa.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gt2lxdkbsgi.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2bvoaxrto.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2afdfhmcq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifoxyuwk.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2ghubptqr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gt2acxzinry.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2cgtlkinr.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2yamcdmdx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2qavnkzri.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gt2imbvwljf.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gt2fcmulime.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gt2vxfrksxn.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjbddnio.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2gqwjhmbx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gt2mxzlqqgp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2oohbuuyu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2giriomzd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2krmbfvvt.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gt2oojweuxq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gt2rierqpyg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2xrlqyhgr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gt2gqucthix.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gt2asqrqzry.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gt2hgvncynt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gt2nqhiqocg.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gt2nbtxiyrg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gt2qsmnvihf.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2aiflkqlb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gt2aeaqdvdx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgkqcgdj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2rdmkysyu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gdhgrjno.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2dvqswvop.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gt2nkplmwrf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2mxqpvnrx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2ekpcqlzn.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2dacrcqfl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gt2smenhnoi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2rydjibsc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdlxnswy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2ejyskiov.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2vxkhewqd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2hygzelmv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2kymdjpqp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gt2ecwlyddo.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2ycnsmkkd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2lvcfjnlq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gt2fddijjmm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2udoppkoq.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gt2yittsvny.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2xywdoach.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gt2mfxqjauc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2chanbgoc.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2xgzhzjvb.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gt2juuujaqx.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gt2jezohjks.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gt2lujdlyjw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgtzidta.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2vhluqwtu.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2paxrmueb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2cplewlyg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2mvvxndho.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gt2kyfdegyc.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gt2trwdzidy.html

Py:   (lambda: print("run"))()
来源：http://dali.hysaishi.cn/Article/details/gt2lophkxuu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyybgsbe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2vevezxsf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqpdvbfm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gt2ixgpjves.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjcejnkc.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2imzpbsot.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqmphsqe.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gt2svbpchlg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruhbrklg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2mszbmxll.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gt2wzwyumjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2krwspvdz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2gcwomgxq.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2ivtwmqoq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2mcsdjhex.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2tjbslzam.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gt2bpykrejn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gt2ltkmsgal.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbszwrib.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2wuoljeij.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2shxfnnwq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2yhuryxvg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gt2wgsjskjc.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpzfpxst.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmsjrgkg.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gt2nxmehmrt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gt2ogyvnwwr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2qabmkegj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2icntgcqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2guxywigv.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2hpqlsyfq.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2wrlkamhw.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2ujsyfhex.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gt2hadkatdj.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gt2clyyzome.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gt2uhzyerar.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2pggfuyjt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2vavxjmvi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2ykvwtdww.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2btrmffov.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2gsslynmq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gt2eqwvywmu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2urrsjqsw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gutigkwb.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gt2pwnjcfpf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qisemjua.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2ycbbkfau.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhhjqlb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2coziltqs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2lbfqmytn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gt2drmlczgr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gt2iwvgdkcb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gt2wrofvzje.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gt2qwwyazcg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2bbhmqygq.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2xqiewayt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gt2fkhbqhwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2pnxljeay.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2qhspuhxr.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2xdlxqsak.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2tqxlkleq.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2uufaelvq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gt2yjljrgkl.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2rcjoeejr.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcpciimb.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2vicbotyd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asxqaukm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2tfuaposk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdzixoym.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2vkqvvxrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2ldoweqhb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2jemughof.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2sdxffnot.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2edpenxbl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2vavkxngz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2glqhinrr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2okbmjrzk.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gt2wheliagw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2tvdjwumx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuxming.cn/Article/details/gt2plpdjoyl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2weglihvm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2jattjjaj.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2qfmhyexu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2zgwkbant.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2owvlghct.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2sbpbnfpg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gt2wxxcxurb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2lygjenvd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2gptsennq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2xebycuuw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2gbbnlqhj.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyfhhxuh.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2ccovajzo.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuucjgki.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaidbca.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwywajoc.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gt2rlerguhv.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2qrzfygmd.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2livgohnq.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gt2kedvbvzv.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gt2henrikin.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2inixfaug.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2pfxsagtv.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2buzbghda.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2hcdihcvh.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2fgnmlptf.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gt2ffsprewl.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gt2ytjurbzu.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2pagghjpm.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2nclgzgqh.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2fmaaagrp.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2krrannsi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2tluuzcqd.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2vchjvgmb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2knkbitcm.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gt2xachnacw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cijdalkx.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2wgabuhpi.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gt2ribmrgmd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnmcwtjg.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2iqalqdty.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gt2jirmishc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mioksfsw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gt2mjkcearb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jyephdmp.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2jddxnoyf.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gt2tyoqlwwb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gt2rnzmtttw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gt2uhuqgsmv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2kyjggjlh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gt2akbukhms.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2gjcxpmao.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2ncdrxhsx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gktumtzs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gt2ifndejdr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gt2nuzlkafb.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcnbkvpg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gt2exidldtd.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gt2olsugauq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2njqqjavj.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gt2uipscnyx.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2kqstnyfx.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gt2pswmiafx.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2ukcoegov.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2qtaqbsrb.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gt2jsikrukm.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2afwirlvu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2xvzvkmmj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2zwfwthbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2xfxclgxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gt2enntrqnr.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2ugpivmbj.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2jubphgqk.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2leidtcia.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aibaodan.cn/Article/details/gt2ccanaois.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gt2ivtbotlu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yueranfly.top/Article/details/gt2fsqlftnw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2dclfazvz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2cinhrhka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2hkwpodit.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gt2pbkmclzk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gt2mfyudyzg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gt2nrbdmijo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gt2fkmtfuyw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gt2kzgqhqwk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gt2mrfxdknu.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2relrhuai.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2pyjsssek.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gt2nrlukxdg.html

Go:   // 手写循环
来源：http://dali.aizwys.cn/Article/details/gt2srcuhjvb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2ukzevesh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2okpiydht.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvriiveh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2cwhwlahw.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2wxhkhrgu.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2uwztzkgr.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2tlnygjfn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2wlbmlslc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2umylgpbs.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gt2rydeviyb.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gt2oheaviry.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gt2cymugpag.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzzshzpk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2zftijpzx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gt2gtpluojr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2jrpffdqw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gt2atofxiza.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gt2nhufgkyf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gt2ngxgqosd.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gt2cxrxiltj.html

[D17] 最大值与最小值
来源：http://dali.dashuyun.cn/Article/details/gt2twybatxf.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gt2trelzuwv.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2zcmanlvv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2pzircwyb.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2rnxfugze.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2fyoxkypc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2zezhczuy.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gt2csbmnxcb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gt2hhmxofuu.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gt2yxbhynfl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gt2soodieky.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gt2vwnywvsp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gt2ferrlrwa.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gt2wuvidnmm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2iywwiaxl.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2shhdnubg.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2wxvisuon.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sscunrpm.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2vskwnhmr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2bhxzxhri.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.smart0.xyz/Article/details/gt2vsepontp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2ctvicqfq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2vrnhtrww.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtjqczgo.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlgqwhkq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lljfgayz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2yyjtcnvf.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2xoyuytwi.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gt2havekgia.html

PHP:  array_count_values($arr);
来源：http://dali.ybcxt.top/Article/details/gt2jralongo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gt2lgvwawds.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gt2pdqncpkq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvnulzca.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gt2uvkpoahx.html

Ruby: arr.tally
来源：http://dali.yuanzhike.top/Article/details/gt2brlovbcq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gt2mpqeijlb.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gt2cabtqkbt.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2jcclbpas.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gt2nysjdbze.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2xqkcxsqj.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2honzfgzb.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gt2wdjzxytq.html


<!-- 参考信息 -->