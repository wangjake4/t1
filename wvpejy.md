代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtsjegymkt.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtiblsofme.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtqclfpeas.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtvryvkadx.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtxvmtconf.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtlawhwlvc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtpcmdhrnt.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtmxnsfokf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtpbfxhzli.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtepseesmi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtpifaaooy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gtqenqxhvj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gttwdycmiq.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtogmfviqh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtxpaxkonu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtkewhonfi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jiagoushi.top/Article/details/gtncmbkehk.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtxivytlhe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtisqeobhn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gttuhbehpp.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtubozavdj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gtamfksrkf.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtmjnwxybs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtbmwlvcte.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtlimgernh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtsdyhbwvh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtdoqdookr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtbjuezzld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtlbfbdsqa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtegeertvd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtskgikywr.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtgebvnsdo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsityhgvl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtwyflqdls.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtkxhywqgf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtguwxuhgm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtnyndwvkf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtcrgzyywq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtkiftepud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gtyddozykz.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtxyryjzbh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtgxxknxjx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtlcdjmiiu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gthbswwdty.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gtxtlxpigw.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtjfzfjgov.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtceiiptca.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gttkvdhvni.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtzvezhvfo.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtouhqlsjd.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtqqsdkuph.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gtzoqdepiy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtaqbjvojp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtxepmlzju.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtezuxycwa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gtzwthmpkc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gttnarmgdw.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtwiroahxc.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gteudzyhpo.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gteymhkogr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtzzhlsrwn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtgpfdlawv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gteecpxwqc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtrxxeewyo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtkawhzudb.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtaaqujaie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gtnscexrbw.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtdomzgrpx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gtoblrdzvt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtzjqxqkaw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtbgwmozys.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtwotqkbph.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtpysctdma.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtlibctzzw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtdfxfiazj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gthvalhdbu.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtbwwdgsnf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtdprlocev.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtcrdgmzyo.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtjevjuncp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gtlegauzfy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtkbswmhod.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtfwluxwvf.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtxzrbhkgm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtezcpycnk.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtyadaizaj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtgauzczas.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtfkxgfbwl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtktuxhnet.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnpwflfc.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtqqpvuhyz.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtwrisxifk.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtmborvpyn.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtkxurmvwl.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtbetxlkoa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtzeczgpru.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtsgalptzf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtjhwgnsli.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtttngzklg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyugskdaw.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtitxjvgef.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtrtgymnmv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtzuqpwptw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxvvczlyr.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtnmstjarg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtnumgnnjs.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtzsdadhys.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtvnsygjuh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtexbqjxup.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtqoiighdu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtccodqttk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtoayyclwv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtambenajo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtdemrjube.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtzuufmzyf.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtnqseggeu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtctljpmwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtznpkhoec.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtdjgdssno.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtnfkkxegc.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gthnjqcbfc.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtxmrblmqk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtecjqkhpe.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtadofxdji.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtvuznwdun.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtqeqxdsjv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gtryynlufs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtvpefyrvq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtmzjoqyzw.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtdncicwfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtxufzfsnh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gthfvydree.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtuumbxvuh.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtvovdbric.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gthejlcakm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtxixtuusq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkkgsmfm.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtdbeebdtt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtgeyqrwhd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtguuytcko.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtenpdfnsy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtqbdmghce.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtlguoqvby.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtwopemudc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtkkfhqanq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtjoplcjtc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtkeprkzeo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtflljgcpf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtarrxonvj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtsfxagwum.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtkrzkiiax.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtkjfsyixc.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrwqeoux.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtwbdioayg.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtqbwlwxbi.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtfiktorfu.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtimqhkpcq.html

Go:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjgjkeeyw.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtsjogyzcs.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtsryiiyse.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtogpbcdvo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gterikbwzg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtbwhrdruo.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtdwrgabrt.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtdzmlkins.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrbpmqgv.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtdjepjbjz.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtypxanlnr.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtannpkueb.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtkngwkuux.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtaqshzjpq.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtsgxbdvww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtxfsqmehe.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtviklokid.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtpssxubdw.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtodoakskb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtzdwxghxc.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtdjdcdhow.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpepgbqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtsivpfwpw.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtwqvwjdeu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtybghonjw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtmuisfdhj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtxkdlqysv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtemmlmsfn.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtnymfndqo.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gtepezgavi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtfvuopazu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaafyhntw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhjzhzfc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtwvdwylzj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtvamnssro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtwqyjtfip.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtkxafiazy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuetiantiany.cn/Article/details/gtlryfezit.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtaimuzgxj.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gthtortppm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtxfywggjt.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtwasfqxzn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gtrxkaogim.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtjumyqwkr.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtzbacvkmr.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtylrpgxcn.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtdrlfumuv.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtdfrynsrv.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtkrwqvryn.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gtxcrwlufl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtfcaahmmc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtdegxruyd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gtjstpezxn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtfhzuhfpu.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtjmdrywud.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gtcnfiqiri.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gteoqhfxah.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtegkffylx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtgabjszkd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtwzhmombu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtjoqalzqa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtlqfpqgbz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtinnpcwsc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlilmqldw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtvprpxjyy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtubwjicnt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtggpogsnd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtsnneimub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtydvsbmte.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtsbgkdnvz.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtpfyeupbd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtukbntpff.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtgdukknhb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtvrokqhth.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtekpcokyb.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gteoylmsqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtreixvkbu.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtkcchfhff.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtwxyipynl.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtsamseqkc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtwejknenj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtsxfjivgj.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtbharkgjo.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtnbkkygwp.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtlwivxmit.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtkiskthbi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprvygraa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtnkzzinzk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgfdzqan.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrazwdio.html

Go:   // 手写循环累加
来源：http://dali.0kj1m.cn/Article/details/gttilwgdlm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtjevyathv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yueranfly.top/Article/details/gtlsdafanw.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtvstpronz.html

Py:   max(arr);  min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjjtivve.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gttuehxmvi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtrpxtmnkc.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtbxlpollq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtcvdjxqyk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxdjrofof.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtyyelbijp.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gthuilnmei.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtzgknddah.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtinsbefuy.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtdjjvcqyv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtgaxjjvkf.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtdkwexrbb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gttyyknqzq.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gtafhtqibg.html

Ruby: nested.flatten
来源：http://dali.hysaishi.cn/Article/details/gtdyeubxpi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtghmvejwa.html

[D19] 按字段分组
来源：http://dali.cashguo.top/Article/details/gtcmumrfgy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gtbgvrkziw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtzliwsnfb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtngatfpsd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtnpcjfpld.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtjacxxkhr.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtlmgkheiv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj20258.top/Article/details/gtkisclfpb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.feifeiyinyue.top/Article/details/gthydwerax.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtendafjrt.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtjptrqoud.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtngiirass.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtyoiezmgs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtyuhvnldt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gttptewvzy.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtgyejjmcy.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtctdmliyt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtsqeezsdu.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gtqvxqbfej.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtxxnrkgin.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuohnrdoo.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtssayczks.html

TS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtalfspwqx.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtjlalvtlx.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtueozqlws.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gthuswcdpc.html

C#:   list.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtvgahrrod.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtjdjhiiqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tanke756.top/Article/details/gtzmtqmcns.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtgvubwwwt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtmljpofki.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtgbbeuuqk.html


<!-- 参考信息 -->