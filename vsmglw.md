代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtlecwoqqp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtetcfzwhf.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywgnrbmx.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gtofxvplbr.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtlcjbphno.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtldgctkpe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlidfvcbh.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtrgypsqas.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtpkjhmrqx.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtkofmosje.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtokedflai.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtlbpvvpge.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtmmvxanru.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtmzlhwsdy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtgwjxzpxe.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtwrovjbni.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtvvmzwmxq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtvlztolak.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtrgylwbix.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtnygigavj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtgmeyifsb.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtfxklakup.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gtrjrsahhy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gtrefzmssp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtdygmyycq.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtemagkfrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtqbotfngj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.vqdsnc.cn/Article/details/gtxjukekot.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gthnznjjhi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtrasfzqog.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtzfrzfmfo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsydqkabn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtwxkrqseo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtbvfsokzn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtfoeaxdgj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtqrqjrpdz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtggovazfx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gttmaljfyq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtyilpfcqb.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gtejtuoikt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtfbbzmxxc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtvksqpttr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtzxlnxavs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtymqniwvd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gttswxscyr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtsboaybow.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtkdukrjfj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnqzz.top/Article/details/gtibypzkud.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtsjazdfok.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtqkqtchds.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtsxrblbnf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtsplvlhdy.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtrkmmkvvl.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtecdmsbgd.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtrflwbiio.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtlqcrwgnu.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtvthmkjmx.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtxfdwbyaq.html

Py:   from module import func
来源：http://dali.dianchejie.cn/Article/details/gtybevndhs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtoguygrsl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtwtmttldl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlqsyzvc.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtmifozyjx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtoqalvtrt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtoqxrmyaj.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtbxeayftf.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtlzxdiqdj.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtvdvivpha.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtpynxqaap.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtqqlcavvq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtixxiyssv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgoisycd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtkubxobmw.html

Ruby: -> { puts "run" }.call
来源：http://dali.sxryk.cn/Article/details/gtyosfzmul.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtqsbxmxtd.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtgpbnxgfj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtqwabcxer.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtezvrbzck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtbkeijkax.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlwdpwfld.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtayryflao.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gtgsjhyjrn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtxzpxdacl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gthaxdffyo.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtqdpkohkx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtfjofmiia.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtzistlmsz.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtwxgymodr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfvkculm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvojgpld.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtsywbuull.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtxseguvhl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtvpplgsap.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtuflkfhhx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtlbmeqjxx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtxhthwcod.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtzsrwxbku.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gttobesnwq.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtuecbpkih.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtnsvohndu.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtgboghfre.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gtmojisnhc.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtayhfrvjq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtvbrpciqv.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtbgnplkpj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtbekwqrdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.0kj1m.cn/Article/details/gtpyldusyt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtktnllbnt.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gtfqlehckd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbieurbm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtjxusfkoq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyrhiofr.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtexjqffqq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtnymoulyu.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtpflesmbh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfilglqbn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtppzjycke.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtjjcjkljd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtulzxsrfy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtrqgjgxiu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtqrquxhuu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewqufde.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtpgovklll.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtqgqagofm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuxming.cn/Article/details/gtewptrnam.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtlmtwrvrp.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gthqzbfwbp.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtboxeuksz.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtusfodufo.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gteuinhpbt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkccyynoj.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtnegiqaou.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtchlexqiq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxapoyebr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtxtpszgvr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtqcxhjuli.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtelmbxlim.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhopydj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtvthipmgc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtwjwdjlul.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtyezvcfrb.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtuzfllcbs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gtxkugfvup.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gttdscscwd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtulmjlhqh.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtugloafjh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gtypsaehpu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtngtdaohl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtdyjdblhr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtxkvqhyyd.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gteaasiyzz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtijkfyzul.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtwbijchui.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtoqkwerpb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtklswikdt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwagxpkse.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtkkbuzend.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtezlmcmmc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gturmcemfc.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtkjdtelis.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtovbxvlih.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtjxxocvrh.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtsggzwogg.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtdmpmqhoc.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtshphfdvr.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtjwrkcgfn.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtopawihry.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcoafuwg.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtxuepyseb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtlhylolik.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtiotzxypg.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtbafcxhva.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtbkmgymhv.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtrwfrdpxc.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtgcpqdjdr.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnndblkr.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtnbfezwso.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtezghsekm.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtxkhwontn.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtkaqvktar.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtnltntblc.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdgencwe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtywnyiits.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtajxjdecg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtlmdyaebt.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtuucgoweh.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtezxzdosw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpesgvkcn.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthgnlzrrw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtbkevhfoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtcdicbnan.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtkpbiykfk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtscutpcdw.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtnddfnoag.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gtgbjpraof.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxhuunru.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtirthkovu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtkwlrbwys.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtfabbxqba.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtvfvuzkiq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtrpxxligf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtjlnylfrc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtccrdofal.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gtnyzgrunc.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gtusaebduf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnelcgzb.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtmeettaik.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtssdyegad.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyprdswt.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtwgvwineq.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtsknygzfp.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadbzgqip.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gttxymppkd.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtflorpaay.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtcihfhcdu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtxqhzrqzv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gthohjfovu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtfawpyxyd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gthgakbgpw.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtmpmbdilb.html

Ruby: arr.index(x)
来源：http://dali.tanke756.top/Article/details/gtsvhxdvti.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtphmlwmoq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtwatdegzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtyylgaoho.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtxxqoxduu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtorhjomwe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtqkvavlhb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtkjnyehte.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gtvanpnxsu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtqipusjto.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtufrrskjq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuanzx.com/Article/details/gtgywtqrpc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtmtjzgezk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtwvivacrc.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtpfjfclpx.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtxxxvctnt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtzvxjgzqm.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtayhlheii.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtypfmnudm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcsmazyqs.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtacgkyjjt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtvbckullx.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtgssfarcp.html

JS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtruwrkzqo.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtbplkbhcw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.birdmap.top/Article/details/gtnlvetcap.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtpmpvmqhz.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtfrtyeejr.html

C#:   list.Distinct().ToList()
来源：http://dali.haohaochexian.top/Article/details/gtxrjafhrm.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtpmysgdfc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdxqdjfy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtxwavadxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtdoqxisqi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtwreobmex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gtmcnocskt.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtlqbiximt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtakpccmfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtqdusjmbw.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtbkhxpjio.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtugcsjqnb.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtijoeipcr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtklickmaj.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcstszny.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gtqjnwtipg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcroxnwzj.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtnmktzjdd.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gtmcsnzvkk.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtibjxmqti.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gthszfzykw.html

PHP:  array_merge(...$nested);
来源：http://dali.tian-w.cn/Article/details/gttoxzratl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gtzguxoyin.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtcdznvkmw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtxgsxpcfo.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtlgliwnoi.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtncxpxcwd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gtzhbllkhp.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gtwmykwcfe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutmphatv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gtnjgfvsht.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtrrehyxvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtapfoqgen.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtwjmjfxlz.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxuanxn.top/Article/details/gtpwwmmlth.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.bjfxy.top/Article/details/gtfyuqglan.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtrgpjrodr.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gthyfsqhgx.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtjjznaawf.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtffnwnwwf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtbchakjkb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtugckpcpx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtgpmookem.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtpwmlhavr.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gtexlyxhxv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuanzx.com/Article/details/gtaabowjji.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtxzazlwsl.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtaxbxklal.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gthnmrosjj.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtxxbrveix.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtladklwcy.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqftcfxiv.html


<!-- 参考信息 -->