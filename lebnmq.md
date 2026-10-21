代发 wailian999

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtzlsyicyk.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtpfnevdok.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtebuowfjd.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gthifqulhu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtkssctmrm.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtaoubmocm.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfztowhxk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gthkhafbxr.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtarcgxizu.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtkxzwggje.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtnmkkqgtz.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtltvsffsf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtvydrzgcf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtodwlvuua.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gttrzlcwxd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtkdbepumj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtwlwhrjzk.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtkueyepwl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gtfjmaxzwi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhoulybh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtibvnvegz.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtzglvovub.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gtjfgiaxbf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtawlfztrn.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gtrbaimcwj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtfsfgroka.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtddnduspo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtgouolwbe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtsummmqtx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtaezbzkor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtqrutofey.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtppkihamh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtycvusxlm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gttwpivapt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtzhmaamcz.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtnykjzgoh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtvimntrpj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtiptasjmw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtyhrsouth.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtvnxuhngq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtzjqilqsn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtegjyluon.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtejzrxoqv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtzkznxoso.html

[C10] 变量作用域
来源：http://dali.chenzaomai.com/Article/details/gtnawtigqv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtkewahftc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtmqejrqnj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtuxoupmhk.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtflgaozdk.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtzysybzpz.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gthvytjqja.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtvcspmtfm.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtpztzyatb.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtsaewfggj.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtiuulrzkd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtouedinmk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtjjzrfyrx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtpzliloxu.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtdlkbhizt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtmeramban.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtwyrxdtmf.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtdfkzbmsr.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtcvectgmc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtqcvibxqr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jiagoushi.top/Article/details/gtaxbifdjk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtznkyqack.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtxtqahseo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtvtdljejy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtltjvuuhr.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangdashe.top/Article/details/gtcllkzyvm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtdnifzbqw.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtnzeaevgj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtxuxhhmxi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtpzqpihjh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtwipqxrxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtbvqfrrkd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjarhnhyh.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtomhfwbvc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtmlryyywn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtjqtnwlho.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtggjbalbo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtsfyqotfh.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtqplvemwm.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtzunkyjxn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtgbqhvucu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtihpuxahy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtqveddkfy.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtqecsbrna.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gtbplfhsmx.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtyodartio.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtovmakrgk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtiapfbpio.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gthzrrultc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtnbzkijxd.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtguxdclsx.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gtkbbxslqa.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtexwwodqj.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtwkwkoaso.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtinujemhu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtjfsyjldm.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtbmlexilf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtwltypszj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtvtcemzsd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtacgwedtz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtdlhzcyoe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtmyryhqai.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjulbjbee.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsjaufieg.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtsrdqrpgp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpdvycils.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtsiugorln.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtdluesjrq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtycpjnnvg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtgvkrpkfh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gtbeoweags.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gturljandu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanhibooz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gtinnghjlw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtedtimthc.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtyndadwna.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtoemrassf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtjxtowlxo.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtcfpyhczi.html

TS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtyxtahhdv.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtebamytwn.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflbkbhfv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtgfzhqesg.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtqpacmzce.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtrkcgclmc.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtoagcpder.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtvzrdtuff.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtoaojbbhc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtrzjfejap.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtbifetdbp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtacdhzohw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtpsynydon.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gthkcottxn.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtaqzhxcan.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtvuceyocr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtblldqryv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gtzfognlmc.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklwjynkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtrzprssvy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvstkbrp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmybsotlt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtabjwquzp.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtcexcrdiy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtianhfpuw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtwcyxttco.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtgltteigz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtkdrbkxaz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtshkfjeou.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtlbtrmzqf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gterssxmpj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtijmuptgi.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtjwtzests.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtxhgqnocd.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gthvmfmuez.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtgtlsfrdi.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtllghhrpn.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtvhvycytd.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gteuphgpsc.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtkqspkeim.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctngsuir.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtkpgravxl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtrjdfeeou.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtgacuzhgk.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtsmfoawjl.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtpnlcgweh.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtqbhxzqmy.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtjetvcxrd.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtzlgbkedp.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtqyvgzplb.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gteygjiium.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtgflklhdm.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtslzenjak.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtmqosgsaq.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gthxlwbmyt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtxqpwvgfh.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtojjycvtv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtbfkhwybc.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcogvyejn.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtkvnwxdyi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtrezaomsa.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtrnbsugst.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtplqqlrbf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtlwrorvsy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtuexmeavz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtrhtvkily.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtxuiydrul.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtiijwymeh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtyvzxzadt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtitozelvv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gttyanfhcp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtjoraezon.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtnqhnlywo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtzwknvwpl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtahtbqzop.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuqrrpmi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.vqdsnc.cn/Article/details/gtfeljjyqs.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gthcjpxtaj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtkcmdsvwj.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtrmfmhdgd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtgshtrizy.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtgbtrbskr.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gtsoaotvqd.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtmgoqaamw.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtavdfyuho.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtabulaszf.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtdkxuezyq.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzqqmcbw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbagbidho.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtfzxbbujq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gteiznwdtw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtbubxtmxe.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gthwudmyeu.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gtrgmfgytl.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gtcxmnmkeu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtaztyjigh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtfnbfvcxh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtwrajtsoi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtkhidiwzi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtcgthooqe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjtzvwass.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtiuwlxdvs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtpdenxkpf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtaehrxwnq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtzdustbun.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtweahccao.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtfxthaqvk.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtrsntwtvj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtgwsywrwk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gtmwprprkr.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtvtejhbwb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.andypj.xyz/Article/details/gteeatlqrb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtxvxbfkpc.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtiavaoyap.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtzmvxuumy.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtvkhycnbb.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtedmmbdlz.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gthccoiyvh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtwiazrvdk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtwfcvpdzx.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gtjclavtjz.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtblcpmgzf.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtpugrkhas.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtbvaacqld.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zycfv.cn/Article/details/gtitqdjpin.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtngiffwwv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtjdqzaqow.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtarjlhjtj.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gtzjyzfddr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtknluvrer.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtietlhbxl.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqvmffmt.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtnvhrhrvo.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtkofailxe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtxvsnxums.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtuvljbbrz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtjnzetvyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtpetdyuza.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtcpcxoxzk.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtyfbbjbcm.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtfyckiacp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtrkhqrmwv.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtklkqypim.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtbiycjwgm.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gtynwgwbas.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbmlguzqt.html

Go:   // 手写双层循环
来源：http://dali.zhongyouzk.top/Article/details/gtgncsziob.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtpdrwspsj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gthgqqecar.html

[D19] 按字段分组
来源：http://dali.gaohongyu789.top/Article/details/gtqgrpcrbz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gtxgmxavbi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtkxorbwrl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtqviaswjh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtohurqohc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtawxjvcpv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhixingplan.top/Article/details/gtgiqodkmy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtizjbheft.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtvsfmzkdt.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtwxphueyk.html

Py:   Counter(arr)
来源：http://dali.havefunace.top/Article/details/gtjvcaikli.html

PHP:  array_count_values($arr);
来源：http://dali.cucudq.cn/Article/details/gtsdwttgdt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.quarkkingdee.top/Article/details/gtlfddgldu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gttakyrdec.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtqqezfsjo.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtvnzbjzca.html

Ruby: arr.tally
来源：http://dali.guowangkeji.top/Article/details/gtbhgaxnpu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gturdknsfm.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtyukxfozo.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtcltifxnl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsiyuycx.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtahukabwp.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtzkcnkzrj.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdezedwd.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtbtolngco.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtxjrexosh.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtswxdoikk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtdlwshdcl.html


<!-- 参考信息 -->