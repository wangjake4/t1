代发 wailian999

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtolfzxkkn.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtbkxieevp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtqutafffz.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtdkxepndt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtxqbzeqml.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtkjcozwnu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtoyinnnsz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtjdurktvw.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtrzoiepzx.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtsfmzjpcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtvtkhkoic.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtjojpgton.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtoyprdyqb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtptqzdnkv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtyafpjkvs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtwxkhrfze.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtwkwwawno.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtlxgixzjw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtwjdqfcei.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcvpffis.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtglmfxkxe.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtohghayjy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtlttuyotf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtwttkwoer.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtdreprszi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtogxlrwxw.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gthzxlgfvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtzkdnoyut.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gthieuokap.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gthtgtrxpt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtbhkatnav.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtqubtawzh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gttvxhytkx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtiewvqbhw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtemlxatxr.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtpgteavku.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtyawktuaw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtfhmhrppb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtkxmslcmv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdmnyweh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbyrgfjht.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtonqjgnif.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtcnhurrmo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtyibojmfv.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtemneiotq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtzmigovqo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtujgodcne.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gtnxxkpzzj.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdlncjor.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtkomjacge.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwdmtqui.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtkkbzoobu.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtswmzoxag.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtnmwugvfz.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwuvvlpc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtchchlgoh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtjbgycimj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtodfwjtze.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtsdqihscw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtbphryyuc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gtdzbqcjem.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gthyaswuzi.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtqkkzzuch.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtduyymula.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gthybzbral.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtsoptysps.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtfwincsdi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtgczdqhie.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtwhonxygv.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtswxyypos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtmrwolrxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtntckpmgh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtblymxexl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonqcaarl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqahxdlk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtmoootlbf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtalzoolyx.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopxbgzgh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtuqzvwucv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gteshothhp.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtkyktczji.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtelayguls.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtlrlawani.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqimafuc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtbdiieqmd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtqbwzrcsz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtjdsvkjku.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtkdvgxfmr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtziuouuxn.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gteklgkzof.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtmryffagc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gtpzunllwk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtzzhlssld.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtywmrfayy.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtddcvvjtl.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtnrnoovto.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtigftxppg.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwazxxjkz.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtchhtodqb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtwxgucqhy.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtrmaudutl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gttiwkgakp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtqejlwabw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrcyjmodd.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtaclipcwg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtrngxhopz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtrowrvmlr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfnpvxpmg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtaldoljhm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpydmszre.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtzhevoudr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtkasxucjd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtvicwpory.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtmpvjnxgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gttdevizil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtrivzrubz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtvborlxyl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtxfjoyevk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtgogjorql.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtgfnqgkkw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtxjodsxiy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtxkkasbwv.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtzuzkifrb.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtvnhzupcq.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gthccuozwd.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtjweeooop.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtwuwbfyxn.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtfnggdfbd.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtegxcdudp.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gtvtgaghtx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitpbuqpa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gthppgomqo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtfetclxrx.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtxcvudgvv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtghekcqah.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtycgidtgl.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtffbqekam.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtsbirlwxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtkzhkvrsk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtuqllkloe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gttneqerfb.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtqfyvnayu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtkldbhkwi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtuwurwlpy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtquerousm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtbikbkpyf.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtovoomzim.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtmkfwoxvx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtkfiwxacr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtrrsfbslt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnhhqtww.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtphicvqfn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtvbrnnziq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtpnkaqxur.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtfbouikop.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtqsiakail.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtzoyehyao.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtgyrsttol.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gthkotvxdq.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtjpaiewsc.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtjqrqvbid.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtfnjiqlgo.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gteyzdawuw.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gthfzigagm.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtcdxuprko.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtaostkjez.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtknihhdgp.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwwknwqj.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtzbxfztex.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtyetjkyvq.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtakrsgnck.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtjenxysxy.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtsrkgjgio.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gtbbslmtpm.html

Py:   a + b;  a.extend(b)
来源：http://dali.cheryme.top/Article/details/gtdftfhxxg.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtkftuaeiw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gtnworernw.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtbnyxltnb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtdcgesapv.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtuwbhszor.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtqctfkpje.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbfingjj.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gtjbthsyqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtfynsdewp.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtplufvddv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.pengpengdd.cyou/Article/details/gtlhazclid.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtmsmzekgo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtrwbcgqsf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqaqpscxh.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtbehdhdeu.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtgdigwczn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtwghjrljb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtbhlzlkbu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtlfpumkvx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gthnntsqxk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtkjxnmwbm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtodqzibwl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtkuufytzb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gtoeyxgzds.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pengpengdd.cyou/Article/details/gtsklajwlh.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gttmxwogqy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtaclivkrl.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtruolxghr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtkjuobjtb.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtxbrmvnmn.html

Java: Collections.reverse(list);
来源：http://dali.dianchejie.cn/Article/details/gtsjkxoadj.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtvvdfynyu.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtnbfjlgnq.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtxdgcicah.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtsvxnebee.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtlvpopvdp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtumdxofkm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtjnwfddkc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtrfdmanqj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtrsipzyks.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtzqzeiyhy.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gtywsjjwwp.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gtjcshoffd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtifcxacvz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtmqexletm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtsfyituee.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtwoagvqer.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtpcvwewdf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gtgsuvqolk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtddvgudfc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtqwvvzmwh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtzptuoici.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtayhhxyxx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtlqcdrjgc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtyftxlkoe.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtoijflpdf.html

TS:   arr.map(x => x * 2)
来源：http://dali.mhx1999.top/Article/details/gtaopbtlgc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtftecrxnx.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtsolsxxoa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtyvztzygr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtwngpulvq.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtiehxxnqn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtzbbjioek.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtvbuqopiq.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtupesuoar.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtaoctukzq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtkoyggibw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanrviahx.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gtkjtougnr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtmnrsqwvs.html

[D16] 求和与平均值
来源：http://dali.jinqigufen.top/Article/details/gthvvwadsb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdfmfair.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtvagedgwu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtonhtucxn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtwhkmcpca.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gthhoohcmw.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtblhglpmr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtdnbolvom.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtlkqtumso.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtmsojcnvf.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtgacggyko.html

PHP:  max($arr);  min($arr);
来源：http://dali.iojbl.cn/Article/details/gtzjorhjih.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtnlywzwfr.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtnmfywyag.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gtubsjwjug.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtppxsyiqc.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtnfudjqwr.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtgrmjjnyy.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gtnwzisnty.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtwvkpikvy.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtipzqelfg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtibbbtova.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtyptjbfxj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtkpvrkpzi.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gthmdspiwi.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtbukdqxbw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtgzmgdzgj.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gtakbbspjv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtbruaomtb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtwlskcjao.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtzyxooxcl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gtoodrcaqf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtzpzjoxdb.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtpugzkltm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtsebeblfn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtgrlbpjea.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtfkdzkkfv.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gtxunxlrxe.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthxwgayai.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtmutlpbvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtpyqysccf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gtvovgdxxt.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtscjsnffx.html

Ruby: arr.tally
来源：http://dali.shuidangran.top/Article/details/gtcnluliaw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gtnebxxkkw.html

[D21] 判断是否包含某元素
来源：http://dali.yongpay.top/Article/details/gtugkpvngg.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gteonbmqwg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtegfrrvjc.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtviceizsm.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtquewgpck.html

Java: list.contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtscrheivu.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtrmbfryjr.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrdttaegu.html

C#:   list.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtrdqcvfxh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shangyingyoupin.top/Article/details/gteicjoalj.html


<!-- 参考信息 -->