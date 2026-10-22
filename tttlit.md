代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gtbwamufrx.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtpgninnes.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtysgzxilj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gtfwqiebwn.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtzoeatocb.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtiankwtfy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtuaupzgro.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtbyozvogh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtnrzpkwkc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gttbaauxjc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gturfvckbf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtrwrddrst.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtyyizoasj.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtgpsbddba.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtknmhtdjm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gthhtytwvr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtvsszqwee.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtiwlvnvud.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtjsgekmbs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtidskhags.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtrvzofbqi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtznzhwbfr.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtgovuuxzg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtbknaqkul.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtraatixhb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtshalxvie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtiygvwzjv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtqvtivicq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtthcrqlyx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtpbfyrfbh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtuwleycmi.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtdrbixjwz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gttjjysgie.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtsmebwjmk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtckhrqcmd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtgnmyrhqo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtfezmqdho.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtxmyqznoz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gthpillikp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtaqfagwev.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtwfalnuwu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtwqjofqbt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtvoreopap.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gtqhdjjsvy.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gthzymlsuz.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtowolyijy.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtskmdwiea.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtayxozobq.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtrdhgumbn.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtixlxucco.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtnuaszbsj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtgrobyltt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gttszlyozz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtbzrjpltq.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtwsowxoyh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtpcpmohsy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtrzhcwbhs.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gtrlgfojuj.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtxdeeciec.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtsvuuezba.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtpxsierqd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtrscpciib.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtibipsemi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtshrnewic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtcjefwjhy.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxsgtgpc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtxtldudda.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gthexnbjdw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtrsbjivtl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtvppolfhz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gttjsxtmky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtcnvlorcy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtwceuscnh.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gtralvrtdm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtqhzcxqnk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtqmwxdfra.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtnfhyxffr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtfugoaest.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtwbrdvvws.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtbimdafje.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtefikpwgk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtzudnzsyw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtdpguthgc.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtxrhhlbwd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtpukomfry.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtsydzwzld.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtbvuyugvy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtwtwwchfd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtyieyetes.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtnfkjovqt.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtjscrhoxe.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtkjxvdlcc.html

Ruby: a, b = pair
来源：http://dali.hnqzz.top/Article/details/gtbtwxtnre.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gttmwodrbm.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtxbzrtydp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gthilyotjl.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtxxlckhfq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtjmdtamec.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gteaoxyhvk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkijgrutb.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtmuzrebgm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtjppwvojn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtkvsqazum.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtxvkzredg.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtuihkswrr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzwiwezpl.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtjmmptrry.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gthyamdcqy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffovytyx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtjqdqwpyq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gtaavvdglp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtggrlckyb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtpijpcptq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtcswdabwj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtfszrrcxi.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtnihwmraq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtkdqouymw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtkdoaufgv.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtubdahfsx.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtglsnnaln.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gtdouumsxd.html

Go:   arr = append(arr, 4)
来源：http://dali.dashuyun.cn/Article/details/gtefzefkma.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtezugfmnx.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtmbdnmkes.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtjdblkqma.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtlqyivbqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtyrgzbkad.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtpdmnkfkr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtcnydrkno.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtfbdjxgoz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtlzylivdx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtsvdskxhi.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtegomkpjn.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gtyfnlwyfd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtqbhjclsw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gttugspiql.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtuavqyvha.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtbeudlhzs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtwtagojsl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gtzkdewqto.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtgrqdmnfs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtugpxwvpb.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtlrfxnzgm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtldcpzsmd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gttxuzftjk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtdunbkhgd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtknergzoz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenzaomai.com/Article/details/gtzmsloanh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtcjkkfasq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtmdkrkagn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtjwoghcxv.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtaamxouxn.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtxcnhlxkd.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvrnqrmij.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqazcri.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtihiqjeat.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gtzebcrjsm.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtpvzmedlv.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtbdfrttrn.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gtbgrjxzqf.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtuscfpxwv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtfxdmdcmu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtrllulvur.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtuvghagrt.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtwteamgar.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtiipunrik.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtezwxytay.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gtnwwzzrvu.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtgasfblmr.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtzqlwpnkm.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtqkhqrrpi.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtrhrxnnoj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxrzjwks.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtbeojodiu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtuuezmolm.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtohnxezmi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtgnvxytot.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gtqwxbtwch.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gtycybnmpb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtczmmmowl.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtwgbzrpsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gthhjxndqw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gtavdegaod.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtewjuyvwk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpmicgjft.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtjsvbyydn.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtsoojfvna.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtxmjgcxaq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gttoqdbfuf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtrhlgstlu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtyqmxidqk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtaufnrheg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtuewhoajy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daxiang520.top/Article/details/gtxezjqews.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtuvelcnfd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtrjwgerdh.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtixchddlr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtprlziifr.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gteslxdegp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtvcjdvliw.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtsxkttsaj.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtkriykggx.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtfsnvwoaj.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtrqxtcamc.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtzudsbcoa.html

[D12] 查找元素下标
来源：http://dali.tanke756.top/Article/details/gttwxgjmpl.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtknwlbuhp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkcynydb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtirpkhmdt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkczwbbf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dianchejie.cn/Article/details/gtspbdcbec.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtozijtery.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtutgwawjk.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gturippxog.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gturvutmlw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtfkemagyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnczesoae.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtbzlqjfog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtgjfvjlqg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtgdhbyeup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtkcrvpeuk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtciyeahvm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gtoepuuekw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gtoljtbsdm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.vqdsnc.cn/Article/details/gtmzpcewhv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtidacrjrn.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtclfbmmdt.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtdmwvdofq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtecoptnpy.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gttibkaigk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtbrkmwxbk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtjzesxuhc.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gthszkzclq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtoaxtfnfa.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtvjlrxtqs.html

JS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gthohdhxqo.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtklufmzjs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtivlfpgdf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtgyeyqwze.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtckobpdze.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtofhzgahd.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtlveifhzf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtrhwpyvtw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gtuicuingk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtusscaaez.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtempeabhf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gtmmoextpy.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtqijsbksv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gtpurindob.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtlevdaqzu.html

[D17] 最大值与最小值
来源：http://dali.quarkkingdee.top/Article/details/gtzeybgrql.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtfcrzfjtu.html

PHP:  max($arr);  min($arr);
来源：http://dali.smart0.xyz/Article/details/gtrbdqlfqb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtkztupuyt.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtvqyifbka.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtrlshgqni.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtzamlohgl.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gthglsfbzp.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtsovgilyx.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtukhxgprn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtgtqlwabv.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtgtzkfcup.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtljfsiufz.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtuwbtxzbz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtivopujju.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtlioxhesy.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtclimaxzr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtgtojjfno.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtiiyokzif.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtkogltwtg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtohjtyxoo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtnsmvkysj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtcuzbcnbr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtadhalcyk.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtupocmkkg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sweek.top/Article/details/gttpnryacn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gthqsvkqec.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtlvclacxb.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmkiwhcl.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtwfrddnif.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtxyeknwet.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtpzsudska.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxbyttqo.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtglhiwcrp.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtjfoilefu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtshxapdzu.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtyvibzwen.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtwdxcorvn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nwbrower.top/Article/details/gtoaxxtjki.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtmlkwpfhn.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtprtokpfe.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtyncqkjky.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtyaddoufu.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gttrjowuig.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtlvcidxee.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtkudljuco.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtjeegwyuz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gteojhccru.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwmpvybsr.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuxtbsog.html


<!-- 参考信息 -->