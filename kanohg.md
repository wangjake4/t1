代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtzhvqfstq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtryglexce.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtokxihrzp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gtovaojrwc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gttijskuxs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtsicjxpis.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtqrlzcimd.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtyzxwvepl.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtkxfqcydi.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gtbiazilzi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtudocdpdu.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtpwzpkgcb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtrljihcxx.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtbmjlpjci.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtbfzyazxt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gtbuggvcuw.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtgowpignj.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtkfsngmgw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtbpqivcxy.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtujzotltr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtiqgbbkqk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtwdhepvys.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtsdxpvbsk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtaacnrcwt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtqltdbaqe.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gtdrkttqcc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtwolhwdzo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtcwivjogy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtwzpchrwd.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtfowruhuk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfydetgdb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhyxfdpz.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gtlzbctdyg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtfsbjjwft.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtjnualsut.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtckmhnavs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxuanxn.top/Article/details/gtuoxxblij.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtfquccxjy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtuvaypfus.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtkluycskr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtxfjtpnpm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtuotiqooh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtblwoyzua.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtusjmcpth.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtjicrnhsn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzlgrexvn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtrndznyhs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtjcpuzkcr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gteviouggb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtdsroycri.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtsixqndvu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtkxbuztqt.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtheqplctj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtfuhiwwhm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsxavndy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gttoalifjc.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gtxhbelxgg.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtntxhqzgl.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtafxksxjn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtdsznaqzb.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gtqdmytfcy.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gttthmcoln.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtxpuxkdze.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtadqmlpva.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtuytcgndm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gthfamynxp.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtmjarmsob.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gthkfiqsgk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtokhuompe.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gthlrrsbda.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtguvdseso.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gteqljkicg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtlhlhmyry.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtmzzqvqpv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtdpksnqbl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtpmmmytoy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gthfcexrla.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtpgfeqbly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtajcrwhob.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtnizcmjkd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkyyryuq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gttwdfxpwg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtlntvtryx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtlcqaawhu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtjxcndrbr.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtgewaelfl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtwbhdjrmj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtsufasdpd.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gtwzybtreq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtcsgwazjj.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtlzxnqsqu.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbgqvfir.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtvvjlmyjj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtjpnrprdm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtfgmyhbyd.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gteiucwsrc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtskgkegdm.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiifqtmgi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtdbyhiwvz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtjtmpbgnt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtsddfkcpg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnkjfvmhx.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtjfiybhkw.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtuuoofcck.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtmrmxluts.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtermzexvj.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gtjnltuxrn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtketrpvjj.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtymhzxrou.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gtbckmdgnm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtohsaknqq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfbevpupu.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtnvpydggi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gtnmsxmjmz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sweek.top/Article/details/gtfqfqrpej.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtppgkfttz.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtytaxdcuz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtilvgvscu.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtycjcjiqh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtsyqwdfgv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtflxmzxco.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtjoprqciw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtdjxznupy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtcxekxjqj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtgevlpfva.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtuvmqrhbc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtildmgzda.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtidvgvakr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtqpepioii.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtgkhbwuay.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtbzrivypg.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtdwszypya.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtfrlrohxy.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtszdvffdr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtcprzhcuu.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtussbqihz.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtrrnsmqzy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcfriwtb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtppmulfcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtsjqqsizz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtvzznjjqj.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtfqlscqee.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtcfrkewwj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtfmlrdjkl.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtuglkxuuq.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtjyjhkfez.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtbunkppjw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtykepeflv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.quarkkingdee.top/Article/details/gtnsrvsyuh.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtlztdizwd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtxdtdvdlz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtejbknxyj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtwxgrfawx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtzclsatyu.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtvloggpno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtcfmkhour.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtetnukhcx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtsjjfuqit.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtsrdlzmrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gteywlhrjx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gthrwqwqln.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtalkffbgi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtlbavrppf.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtemxjyxam.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydkynlid.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtdzldcwzx.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtrpvclqle.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtqzscmmcr.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtjomxtgbc.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtuhcmznve.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtwberaaed.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtpqekeiad.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gttshjfiog.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtpfrlapde.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtqwbekeez.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtqlrcltgu.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtxrrxlnoa.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtcivjdyoj.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtzfnymuzh.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsteazpo.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtmfftvtbh.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gtduhnoyqw.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkyrsxjma.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtrpzbpokw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtoxwcbvhb.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtflgbebsa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gttxyhgffp.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtblvxihau.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrttgctv.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gttfkymvxp.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtmwxkukqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtimfgpors.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtvjvwcqdx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gtggthblwg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtgmrdvnhw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtizklvgxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtndqscfck.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxpxcurgf.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtlbhidzmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gthehecxuu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtteziqygt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtynxdseqq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtibyvbmyp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gthovhftny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtnfmcsirg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtmdhqlwxx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gthxktzfty.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtdjtmdztm.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtvunbhddk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangdashe.top/Article/details/gtpatinuvu.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gtkzxkkmej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtzgvlrqqs.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtxadkkmgm.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtdodusubv.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtloljcnfj.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtltxvxncr.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtslrttiff.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gtprzrjhzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gtzdktwnqd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtewsofagn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtauzokfdf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtpaauvfzr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jianghu66.top/Article/details/gtxscyrjdh.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtrymeyggn.html

Ruby: arr.index(x)
来源：http://dali.gzhubu.top/Article/details/gtzebbwbbn.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gtrmdloqyn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258.top/Article/details/gtidlkmmdr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gthkstxero.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnxiangtu.top/Article/details/gtfifopkoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtyblgkrxl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtrjjukgvg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtfsvefnlj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtbkpcujan.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtsyafnmqs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtxsswbwwx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtuusthyua.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtwdycsdmr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmqqeupaw.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtauuecwhr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtbqwrplgq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtdvynveil.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtlmzjtkwt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtzzxvmwvb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gttvomeeze.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtnndyaxog.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtpmsqlymo.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtisdjmsyp.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtymnqcowi.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtznlvaycu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtbaufnosw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtjewaxqdp.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtplaljeva.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gttvbcuwig.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gtlmbwyctm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaukuark.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gthwzfpdrx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtdfwdbxyg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqqgtqwnd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gtjhsczafi.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtrdavwbso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtuofcfkdf.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtajbcdufg.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtxebobqim.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtrhnoujog.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtwiuasnpa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtyznirble.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtfzcomqoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtjgeyhgsn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gtvntxmcle.html

Ruby: arr.max;  arr.min
来源：http://dali.sxryk.cn/Article/details/gtzugetisw.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtgszalfvz.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgfzy.top/Article/details/gtqruieulo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gtyzjpnxle.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gtsjodzcbv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtqnlthtgi.html

TS:   nested.flat();
来源：http://dali.andypj.xyz/Article/details/gtjwovfyxz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gthjdirejj.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtvyoubvqf.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtffxrxpjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gttkkhggkb.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtwroyynao.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtrbwgnhci.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtrlpcmekv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtljxzryjj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gtjlifyhyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtrllxutci.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtahpsysap.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuanzhike.top/Article/details/gtgiepoopy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtoqhavghh.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtcozbagkz.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnwbprgl.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtgbxwhird.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtlozkbcbz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gtsepqjtde.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gtsaimbipq.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtwhvoumgv.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtzlonlfil.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtvvhrzixj.html

[D21] 判断是否包含某元素
来源：http://dali.cdnleiting.top/Article/details/gtfgfyizpw.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtvjfgumhe.html


<!-- 参考信息 -->