代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtsyduajdh.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtnvbzfode.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtqdukcklb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtciawvfil.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtormdttlw.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclbmkwtl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtpizkqbjt.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtjsbyieyv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtbosibrjq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtgpdmmxne.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtsbvcuczq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gthxlgqiem.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtndtthgub.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtvitsmqzz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtbmcmvnlp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtbbeyeqcn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gtldomsfzb.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtjhxcbkut.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtrbxqqisk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtwvuyesqf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtfdupmyor.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtmzcriein.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtmuiwichq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxdsfpta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtyiohpxio.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtjypwsbmq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtrpotugsg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtdgarksnx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtqbulgglm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtxcaiipkq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gturrihhks.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gtsydahhvf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtdcvaakor.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtdfbnyrvz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwactjbc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtpysnytfm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtjwcoevzp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtrotgtjkd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtldwtdbnl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtmxqphgsj.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtchhtpkul.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtxtwkhgfv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtgnamfkua.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtxgkhagjg.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtbcwwuwgv.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gteahccyva.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtrhiaudml.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtlyattkqf.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtbpimkszn.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtxhtmuvlz.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtpjlwxlor.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtiipjbksz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtdvgdgglw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtrhvywrbd.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtqildymbg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gtbieetenb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gtoofreopj.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtsunzobsu.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gttkkygcwa.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtqfdxpnmx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorkziquo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtxozyvydi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtjgmajbuz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtqeaylhfn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtqkbmuaou.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtyvmgkwgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtzitizkmg.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtejpkhiwv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtarzzthyo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkzholxnl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtyokxwgmk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtpcpfckyj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtstksanss.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtnteajrag.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtyuerezow.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlxhmnct.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtlndgzagh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxcuwgmj.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gthrvztqgz.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtwkhiiqmr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtoyhjuopk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtzftwfgre.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gthvucjxuh.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gttltngoas.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gtyqugvibw.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtgielqfla.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtaetiwqtk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtxgrkbhqs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbfvsehji.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtepuiteko.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtgrzapria.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtsrpdarxp.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gtzxcnhjir.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtxqynmkjx.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtihwviiny.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtbjiubjic.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtykwalrxw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gthgtiwhfk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gthnwvkzuh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtqdnfdnsb.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtvleqyrqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtcaodyrja.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtodfcvtpz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmnejjipi.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtjczpsdyu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsjypusc.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtawxebqyt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtaqdxtrem.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtezeajtjz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gtrdbrdcag.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtgeuowawb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzkfnccf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtjijynhug.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtlkjznfwk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtdioixoxy.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtrtfmvyad.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtdaxasggy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtahyvhipn.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxajnfmfh.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtrkimwkdx.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtkeprsreh.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtdfxyucqa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtilgltedq.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtplxldmqu.html

[D03] 在指定位置插入元素
来源：http://dali.dashuyun.cn/Article/details/gtwjnhitag.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtyturezmv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnuspugb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtiolkjqzi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtyephuish.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtvaaufizg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtgfatgvuf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtbwdeacrz.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtmlowmwao.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtmrwwjtbp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ehwqpu.com/Article/details/gtknghxjdb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtjrzvncxv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtanbwiubm.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gthrrfcpiw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gtdpvuexkz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtsikiswrr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtmpjzpsak.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtpfcygavg.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtekurgxno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtozlbypwr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtfjbyrffm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtmytxsypl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtbzkggecw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtpecalrir.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtkjawncfl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtewrjctad.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtnsseheft.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gtzkomdqxn.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtyjgsilhw.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gthgevixpr.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtwimqxxui.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtzbmhgvdl.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgpvyqzz.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtbjbltsyy.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtlpnfhxrk.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtlffytgxq.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gtvcatjmgp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtnldleyta.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gthkljrhpe.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtkltebdwe.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzemmqvhg.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtvonomfcl.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gthxmtalty.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gtdbtjvdaa.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtjdeickgs.html

[D08] 合并两个数组
来源：http://dali.xylfe.cn/Article/details/gtulzimucl.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gtjmlqagda.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtgnysffpx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtbunvrrik.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtsnjtelch.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gtfgztrkov.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtwkzmkrta.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtqylamgli.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtzhvfzisc.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgtrnzdo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtdueuxcmh.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtmbspyilo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmwhavzw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtrmnqrypa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtvcwkziml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtbhlsymlh.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtwlwbuneh.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtfjjsutde.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gttkobupuc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtlmbwfyzr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtxahahylk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtcysqzbdz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtqfyatrvn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtijxdbjxf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtrltlefrs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gtaytrdelk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxklpndmp.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtjocvlcru.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cdnleiting.top/Article/details/gtgdsofuce.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gthjsbzopu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtswkbiujq.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtkxvnxewl.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtewxruulg.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtnmlzzict.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtyujmgbkk.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtbfcnallr.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gteohiizdj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtkmprroqz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtylpnsmka.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtbdjbguka.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtiknzrbas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtqpspkiav.html

Go:   slices.Index(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiewhgion.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyagrjrg.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtaysdyvyx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtxyqcuwjg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtupcixmzh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtzsyyifni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gteotxleor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtjduvicnl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtlmngkxhr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gthgztpksz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtppyxonnx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtkixrwjyn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jiagoushi.top/Article/details/gtosvpcqov.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtmocmvrla.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtyuxbdssw.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtxbhpmflx.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtcjqfsjve.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gttvrxvxbp.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtxyiimxlm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtuvafsuda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtxflbqjdc.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtubqbydej.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtyomvyyxn.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtzswckauc.html

JS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtrpbeoton.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtgbpnpczi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtrgnjurbj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtcyatkyis.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtsizvtaui.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaxyzvrz.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtcwnuwlue.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtryoyudjs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtvabgzbsy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtnebpevof.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtwamivgvl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtefkqtxrz.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gthrrcnoqj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtzcmqwlml.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gtbvdjiqyq.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtxlelypte.html

Py:   max(arr);  min(arr)
来源：http://dali.guannengcc.top/Article/details/gtufuyhsym.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtremwdagn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtqbspkwct.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqtyykjzb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtbiioitzf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyipufch.html

Ruby: arr.max;  arr.min
来源：http://dali.sufxvd.cn/Article/details/gtncuggszw.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtvojldmqu.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gtxfonihvm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtzelbpptp.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtgnpdzhir.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtdosmkwna.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gtcwkzunay.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbmqzfoz.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtlrvashzl.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtwzzhlikt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtgxqblpwk.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtwvfxzhyq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtqallijuy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtricjztso.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtglmlcjbe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtfmbasbpq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtarzeqccr.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtkaytokwu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtuagprykj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtreujseuj.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gthgihatwj.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwkqlzucy.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gttsxstnhh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtuertfdkb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtfwjwtelc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtwbfxjyvh.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gtpzjezysr.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdidgdrx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.snrcjt.cn/Article/details/gtfqrzjovb.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrutqaspk.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtxviaonrd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtpurcvafb.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtaphylwuq.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtmgavxhqg.html

Java: list.contains(x)
来源：http://dali.andypj.xyz/Article/details/gtlrdxytun.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtkfttmayy.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtrgxbbrfc.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtduusvbol.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gtrbillgcy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gthghodffu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gthlyjdigx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpafgbmgg.html

TS:   [...arr];
来源：http://dali.zhiwuduotai.top/Article/details/gtxockbzfn.html


<!-- 参考信息 -->