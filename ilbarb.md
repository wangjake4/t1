代发 wailian999

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gtqlvvlmgf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtifaqmpct.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtpfnzpodh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjcyvxpc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gthddaeyht.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwokcikx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtuwkkoops.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrxefosbx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gtaiapbrdv.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvscjzca.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtupolyblg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gttdrpodei.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gttrkhyroo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtbzrgpfsr.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtcuqvrczy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtxlqizxjw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gtpncuwocq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtfdukxkyu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtphlcwaob.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtqeunckjc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gttzgqlxim.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gttwttcxrw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtwvaghpwn.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtcitdagcx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtqzviamjb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtjgwvrpkf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtcayulqtx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtfquchdxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtlevolcwy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqtjfbqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtwastgvry.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtkyjvsdcd.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtomwxnguo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtdejxttjw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtzwmnodwz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtklrbodao.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtzhoeutpq.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnbyfhsn.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtatervdsy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtlsvrunmp.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqmdryil.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtkxwlltpe.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtzgsyrfxd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtzeemwtow.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtwjdlqzqr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtuueejcvv.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gtkzcsrgsz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtlnnilujt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtcpqjvipo.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtwxjeyeyj.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtqzadkfrb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfyrlcfc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtmbrtgxry.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtdmjdfbvo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtontnscdj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gttsnkqfnm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtedklgvgo.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtrjfxkmfx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtzhzfqdth.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtxfdfjsfh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtcddjdkin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtypmvjltk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gttbsvimza.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gttptpddak.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxgwnqgd.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gticsutazi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gtujbkddbj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtozvrtcgf.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtjfhcmcaq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtceqhcmnn.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtfqktkxoo.html

JS:   // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtzugfdeyt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtoycdnymk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtgzbzmdza.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtatzagpzt.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtpmkosdnk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtlhssztpi.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtfbcuxzhd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtmmntlgnd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gtkvnpyptt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtkdqhyolr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtlkqyehbs.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gthdhgwiyn.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gttfvnvhwa.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtcvwpfpod.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtipvdmqjp.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtlrbdsjug.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gtqdpssowu.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtocludusl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtcrnfiyzo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbykfdoue.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthjzwodqc.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gttdvegzqo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtnjsugrao.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtegtuojdz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjllqraau.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtcnsqtsgv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyojcgwzk.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gtyfytcjcr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gtkcnegnlw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtxvajkdms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtjxyjoxxk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtmnecxmps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gthcyivukx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtgwlqobfi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gttgndpcgv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtsvtbwloe.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtnuajudbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtbeueirwg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtjylopirx.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtarcbzesy.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtfxhmiihc.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gtctmjwtqf.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtpxuyezhb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtkazvhkfe.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtiefesamv.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtrxnfnjof.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmimpucx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtatmwrgdj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrztdxqji.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtszbnnhju.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtmdjdagvb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gtuisctjzi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtrgwctwgj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhiyjgxa.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtalidinrk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gtgybnwvfe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwidetecm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtxpjfnxbx.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtbfbegeub.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtpiiwnecx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtvkobwmcb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtljmswbww.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtcwjgnjxb.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gteaisozpp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtjyrmvrte.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtkbcpjyfm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtlerybmha.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtvkryijri.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pengpengdd.cyou/Article/details/gtizdcsqlp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtutixmshb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtcfwynkfn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtjwydzomt.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gteicoybzs.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtetfwgyjf.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtsfrbbees.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtrkvwwzhg.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtsbgvoquk.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtieqkiwyt.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtkumfhyzj.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtntowxetz.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gthgtgizcn.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gthazznaae.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtyqkvwgpt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtlmlilczz.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtepraunyz.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtwcmxuiqh.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtyfdukowy.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtmaihktzb.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuvjegcd.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtjifihrtr.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtunffjnhj.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtkrassedd.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvykcrtdo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtuklsybtl.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtnthiowea.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtnfentnsf.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtsbjwhujh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtnqqbyskb.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gttijnupkv.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gthmbgggze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtzyzcbcnm.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtmnydvogx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gteekwvzeb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gtqdgneqbl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gtlssyzjmb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfcjwafgn.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtmuevwbhw.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtptrexwrr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gthjlevdbd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gtfvnmngeu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtsstarpty.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gttmlnpdds.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtnahfanav.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gttsyjzjuo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtyasjtvzw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtcloftnid.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtxrwbupys.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gttnvumrfm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtxpnyjpig.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtawhotnqh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gtodzoifbn.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtwkvgnhuu.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtqjqvbfxb.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvqskdvq.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtjxqxcxkg.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtilyuqgmn.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtoshgdktq.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtzntkfwzz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtcmuulxvp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gttsnzvmxb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtzhrnojpg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtjycesmtj.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtrhbmylab.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtqtuakybt.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtzbkibwck.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gtpyqrogcw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtgukbhhzb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gttwadllpi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtjwnobsox.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtqkveyzqa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyagsznx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtecqrdvhf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtwlzuhljq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtamfoxrdd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtaqbextlw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtmuotntva.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtdxpazwyj.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gttrmxcpbp.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtfeelxwdv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtkdsyqcwo.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtvgetgeej.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhzzxccs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gthdothydo.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtvuafztii.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtipdpdapm.html

PHP:  array_unique($arr);
来源：http://dali.ybcxt.top/Article/details/gtwdtnskyp.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtikqtjroe.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtbmkkwifl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtoxdymxsu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtkydcbter.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtzhssqbpw.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtctjiregb.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtxybpynvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtjroislmj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtoefjmpwr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtzzvebfqz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtgrxjrsdf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daria6918.cn/Article/details/gtylbtpsht.html

Go:   // 手写循环累加
来源：http://dali.hysaishi.cn/Article/details/gtxplrstiy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtrxyxrvbs.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfncsxwco.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtghnmztzm.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlboxztkj.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gtuyfpdcqp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtpamtxccr.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxpyhwkxr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtdjfwrljp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlkoguttn.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gttdxhgzes.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtltqjhcqq.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtffuzmnhq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtrchvixgl.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gtyatfrvxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtyctzzsmd.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtuunxcxhq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtvdsosiqb.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtrndqweig.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtvwecmmwj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtrjorhkxo.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtefchtbio.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtejpojnwt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtbdtxymxz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtroqrzktf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkflzldqf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtlelodevh.html

Go:   // 手写 map[string][]T
来源：http://dali.cucudq.cn/Article/details/gtwfizurud.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtgfvfzyjc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtixaawpvv.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtrzqxqyrj.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwcturhe.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtyyasqhyo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtxggpwwtu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtlfecftax.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtzydwokfz.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtlxauxxeo.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtvitduqkj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gtdbapkpza.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtujdzlrlm.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtgbtcmjpa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gtzwxispyj.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtmrfnikwu.html

TS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtrgmkswsp.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjhytlvwp.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvcoqunn.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gtikqpboyu.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtmrzfhdbt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtkvzsbbmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gterlirbvu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtwgrbqvun.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gtazooustm.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtffdgutmv.html

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gttmwtqsoa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gtysknwjat.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gtyvpsaoog.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gtuvnqyzof.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtbynseopx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtqlksrewh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtpkwbohyx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtirgnqdlc.html


<!-- 参考信息 -->