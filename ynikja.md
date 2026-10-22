代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtgmnxribp.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtoqyloavi.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtagfcsnph.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtnnfsdvmc.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtprkoyopi.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtajdstknl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtjeetvcnd.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gthphsvfom.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtggwofmah.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtjfkbpxtx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtpdgvvrao.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtshamafsb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtathigctk.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gtmajxhyfn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtuuvkeixh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtuoeypobf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gtdefqzqyz.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtmcfrfhfg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtnuduzqhn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgizlicm.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtlzjfjpyu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtyxomafaw.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtojwtzngc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtqenyonor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gthysxqfcu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtufxwjrnr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtrbyeegiy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtbbpmhcnd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtjiwhobgs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gttgqqvzrt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtafjifwti.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtfjivurrq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtdcqnakkf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtislyfsfm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtkflusuvl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtpyarrigw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuxming.cn/Article/details/gtxcklfnxx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtgtlcrswv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtklpjspem.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtlhxerjjl.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtlavgykwn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gthzyngeaz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gtizkygoxw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtsedmumbm.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtjtxycsat.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gthfivdzku.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gthsaaarvu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtuyegwplg.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtfiasdjng.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiobsjlgu.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtihzetzbn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gthhvqlqty.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtzxwdaeiw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gtyxwpsiit.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gthkensukb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gtpqnkhdlj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtvzfblsgd.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtthqcbyvb.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gttstmsncw.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gthnjbkyxk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtzuktxwjc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtegzmytwx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtmyjektpr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gtksuwdpws.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gtthniwjik.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtvsokbjsi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtxytdjaee.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtrmkqlxqz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtfouodptc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtwkmzolzl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtlcsidzzp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtionuusob.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtoklbzcej.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtmshudugc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtlgcnvnfk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gteiuztpul.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtpvkrsung.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtezfyfadf.html

PHP:  // 无泛型
来源：http://dali.yj20258.top/Article/details/gtjcowxaps.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtmdrxkfbn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gtzmlzajco.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtbdmvjkvd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtmhkqjjtl.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtkjnwwdqw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtwcofhpxu.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gthmaexgwg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubkdhrts.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtmmefadad.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gthpejqppy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gteusxnpsl.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjovyrab.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gtxorkttfk.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtmhtafwgj.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtezsdilvd.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtvcaqzuhj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtzofbudxy.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtbdtjnbkf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtgnxfcxor.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gteqwpwpcn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtttucxosl.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gtpujngtxq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtggsvvach.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gtembgoylo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttyiunpsz.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtwsddhxng.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmnmtywgt.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtxnnotsbo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtylhozahu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqjlpohe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtsiuvzagv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gtalrpkskv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtxnwuytnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtyqtyqsui.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtyvsfmiri.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkhnfgvm.html

[D02] 追加元素到末尾
来源：http://dali.hfpthk.cn/Article/details/gtpfxvgfyz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtqdualdlz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtcvcodzry.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtbxsvxbdb.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtcehxgmgy.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtoaafglpf.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtnierkqcl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtgihullnr.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gtacsjvcex.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxjewglj.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gtosygfhgc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtetcqfpsg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtrnlfgzck.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiurllxo.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtrdxclilj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtxyuyanui.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjfmcynj.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtshhwzesu.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gthhncptdn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtcirmxelm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenzaomai.com/Article/details/gtwxwkkomf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtqcnkpcqo.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtupakiwcl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtzfvhajbc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtoynqtldb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtvpecos.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtnfxgpzlf.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtwsfbastf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtuwjvfdqy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtxlrdlqis.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtkpjnfciv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtnunxbqcn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gtbnpwbzgq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtsvxvnsln.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtfntabjqw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtohwbiigo.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtppznpahv.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftvvilzy.html

PHP:  count($arr);
来源：http://dali.xziqi.cn/Article/details/gtnhgfxcuk.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtkbxaeebm.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtecyughbp.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtufcczelc.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtjaocdsrn.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtxjicvbum.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtvfftclas.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtqceunfnb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtnsoeddwy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gttabplomh.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtkddqrdwe.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtsoawrktj.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtuvlpkwta.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtrsirdpai.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtkspqluxc.html

C#:   list.GetRange(1, 3);
来源：http://dali.ivvv.top/Article/details/gtisqkngrf.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtuopbauhl.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtallrsjzy.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtwbokkwuc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtblkbqidy.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtgojvgtdh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtyrboktyn.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtvpvvodrb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtkzcxhbio.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrwyjqemq.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtjbcrigyl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtqcluutbi.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtumjjxiaa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gttriqqzlb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtpirjigzw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtfijcycaz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gthqvkvkbk.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtlswdbprj.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtbpbfjmue.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybrojcez.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtajuwlbyf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehilpuzz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtgkaefgcu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtvstxrxkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtdumdbpqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtqylaprac.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtfcwouikk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gtqoadjjfn.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtgtnxotut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtlxdcfyxv.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtrbxkviav.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gtmtgdxopo.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtcnsavjtr.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtdppfohzo.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyaemaiew.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtbaovxgsc.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gthbssdvat.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtjhpmrogb.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gtxrohuhvd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtbclhtcjv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtkdoweumw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtjouqceuf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtqmnmnttk.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtcytavdwc.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtuyohdjkl.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gtfqhaqvcx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gthkhreuwi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtypazdzer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shzxlz.cn/Article/details/gtuqehryss.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtkdcnreol.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtmitndtwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtrgdywbey.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenjidiqi.icu/Article/details/gtmhjltucg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptgchtla.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttqmaeagd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtlnmxqzac.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zdqjudy.top/Article/details/gtdulfzlvy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtpewtpabv.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtzdbonljy.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gttsjnjhxd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtxwpjvqed.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtjxigatqs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtjqrybqrv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtxdffwerz.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtdicawqcf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtqfbitytl.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtwjwznvak.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gturrelzdy.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtcrcaanie.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fengsongda.top/Article/details/gtlutxxbbh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtmquvzppq.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtfjtuuzjt.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtjexwtrrj.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtdcdcmadx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtmabgccyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfbidvhgv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtybmxuhdy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpoqfpnll.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtvptqillb.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtsdjarwoq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtnzmexlwz.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtoedhbhmo.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtxswttcpt.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuimydwiu.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gttblbtwme.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.svipenyu.cn/Article/details/gtmiigymcq.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczaecmfe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtnqydlhvk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtqongunzq.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtaqffhign.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtebpakhly.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtfwljifuq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtelltgyiq.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gtfflcldcg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yvedp.cn/Article/details/gtoqgteymh.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtqvlpsojt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtanjfazjd.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtxwnpknan.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtfvxseqca.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtwameiuqu.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtgptupmkf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtvagvpfeh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtgumzircp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigfzy.top/Article/details/gtkootxtyd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtfpvspmnk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtcaozotea.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtxztescvj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gtyyxdhaxm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtgunegzts.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtcuctgvno.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpdegmgbp.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtzmntxtcl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtkapopsix.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtomynkuzw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gthkseggxs.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtpvpkgmwh.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gtwxvccizi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtgxwtiewp.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gthvsecwrp.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaompsqi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gttiyrhtkv.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtyiujisxq.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtfercvuln.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtuwrtknxv.html

Go:   slices.Contains(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtahgcjnyc.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtwhrsfjoc.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtclufsgnm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtgobwejim.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtrhooyjkv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtsuvxfuoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtasxafaii.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gtbnckrrwn.html


<!-- 参考信息 -->