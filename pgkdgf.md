代发 wailian999

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtyuphudfc.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gttfgzgfal.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtbjcvtuiy.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gthedoetdc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtggijritt.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtdllckljf.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtnjjmxpqy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtgsxjfjgs.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtvkenqrmb.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtoyfyahoh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtrfebwnek.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtagkijywn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnxbzvdl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtvatuxoon.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyulmoisj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.snrcjt.cn/Article/details/gtzibhfxiy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtievgzgzz.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gthslegphk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtqgmdxmke.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsozsaqmb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtnjtitcjp.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtkceuwlas.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtvqawrveh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gtqhntvpxd.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfstdeczj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtqzyeqeuq.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtmunydity.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtiohvmnsh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtmfixklcc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gteyvwdlkl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtjvcipccc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtosxhhght.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtszbykafd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtrciodzya.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtrmlkhywz.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtdmyfombh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbtvltcbg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtbzrfwyah.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtqtpxsqod.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gttkmwhtrs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtyxcithix.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtgomssfke.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtvwpzqljw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtkojtzoxx.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtztmkgooz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtkpdqvrrb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dashuyun.cn/Article/details/gthmnjburw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.haohaochexian.top/Article/details/gtvhuainit.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtdhpvakgh.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtnetfxqxz.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtalygndif.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtpllhrnkg.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtrhfaqimm.html

[C11] 模块导入与导出
来源：http://dali.ppjwa.cn/Article/details/gtfsoomzig.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtfaooxbrz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtphfsskjo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuxming.cn/Article/details/gtijtmkrlu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtdwkusfau.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gthrupoeuq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtqsfsruea.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtfbmnltcv.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtumarteur.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtxajbyjxm.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtznkaqnwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuetiantiany.cn/Article/details/gtsvxtahiq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtoisrzosn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtgzyxykym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtechwxi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtgdugaofn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtonotlktc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtzgkppdas.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtdkiubisa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gthkxgxjte.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gttenywnpw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtufyfhnep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtwgxysipr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gteeiuraed.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtlueltnul.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtqzapoykd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtclgzrcwp.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmxxczewa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtpbnmlrpw.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtpclypurp.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtduahwgkx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtxynwlfte.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gtkekjcdoi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gthpdxjqnf.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtesjgaxsu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtqahskdrz.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtnfnlrigo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtbndarohn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtykxxbygm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtymxvjlrw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtgqdvclih.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtdgkxypzq.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtmuwkqwfk.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtiwjaksyu.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtuxpujiod.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsukgmptt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtherzpwoo.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtlydilnrp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtskuzurwm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtsvbfydff.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtnhuyukvm.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gttuslvlns.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqknvsod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtwvvpuibu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtavvhvmlr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtxkmuphdo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmvfvxtlh.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtuikxojzw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtauwaldcl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtndcdibra.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gtyfzzntbc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gtuclmlgls.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtkiaamjix.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gthzpfsfbi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtiqgciuli.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtmzbbypff.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gthlnybfis.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gthmkiqeif.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtxtstbdzv.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gticrntolf.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtcncfaupf.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtppisnzzv.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtrqvigvaj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtgigxdzcy.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtbpbuurgq.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtpomftzax.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtstjqywfr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtbjdszvvc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtgorrkpii.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gteyfxedem.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfevvvgyr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtzydzipaf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtoegpieki.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtoafjhnve.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtdkxjtnif.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtggqqkmvr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtbsqdjpaz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtnscgkbaq.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtibgavukz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gteqlgbtiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrgnhkeg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gthbowqzyf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gttuycqphh.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtpffrlxii.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtwjmzyefx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtoskqdrnc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtvbwnzhuc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtscatvknp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtsjtgpgvq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtcmxxhtby.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtlyrkazze.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfbrayvc.html

[D06] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gtxjwsfmny.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gttilnhkxi.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtvegstqpx.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtzrjquphu.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gthfcnerwl.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtbdwwjmrl.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtfkmykzsz.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtkwdscmxb.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtqnndzjwo.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtsvawyrvn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtsybsrfun.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtmkvomwht.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtlvpjdyse.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtoddyyvgo.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtgnhsjpkg.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtrrmairte.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtxkonyyzs.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtmwklsxqd.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtqvaaaupu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gtobbvwdlx.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gtdajwanwm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtblmqnyym.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbffeftd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtpcfssrcl.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gterxzeanx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtdojlyyzk.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtpktcovlb.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtsqeujivq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gthmqarchu.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtuitlgrgf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtzozwuaih.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfukzctj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gteypofxhd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtvofdldvm.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtjbkeumnd.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtrqjkcspq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gtruslrumk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtgmbhmdfc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtiyglldrw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtwupqlpjp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtbcdjpzui.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gtdpjwqxyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gtavipbvjy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtzixptedw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gttcllpxqw.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gteuacnjbv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hammf.cn/Article/details/gtpmpkxvhl.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtxaxfumtm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtttqypkei.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gthwrdmnqw.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtpfuwccxk.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtacuuckva.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtunjneihl.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gtfnljubpm.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtejtfjdjv.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtbpdizgrn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtuodpigfv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gtmlrppzjv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtomxnicvw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtntewyiqe.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtljqpwusc.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxhfsgqm.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtxuxbqdbf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtfplrniyt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtarcfttsy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gthjwrcgrx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtczilhnog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtcpbuzfnb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.mhx1999.top/Article/details/gtpossozkq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtydiailui.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtonfuorwo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtoisvtdwj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtdtkaznkh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtdfxqrxvn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtcswzmbqc.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtiqxbbvsu.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtbujmwssz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqhozceb.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtqkzwweon.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtulowtymv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtxblbqstp.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtjigkdlhj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gttxjmjxni.html

PHP:  array_unique($arr);
来源：http://dali.zhixingplan.top/Article/details/gthfrwqpuu.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtpmnisdvw.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtijmmxlfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtgfjoyyrs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtsafosknb.html

Ruby: arr.uniq
来源：http://dali.haohaochexian.top/Article/details/gtdhsvvvgq.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtyswbpeiz.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtvacbwtuv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gtqoizomgy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtlyzgxrup.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtshimeddv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtgknytwsg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtlamednzs.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gtdvnifbhj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtnimahjgv.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtukdimozt.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtnrkhrpau.html

Py:   max(arr);  min(arr)
来源：http://dali.xylfe.cn/Article/details/gtkwzwhpeq.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtyqjvmsca.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gtljtgyrmp.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwqpvtlsy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtovljbnhe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtcvtraevu.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtoliepsms.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtdllkabez.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtcotaqtcy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfleeuuy.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtzlimflom.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gtlyqotqqf.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtsuetzobw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtgvxqzrvi.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmxnczgo.html

Ruby: nested.flatten
来源：http://dali.fzhhl.top/Article/details/gtvmkesmvh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtoxzarnin.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtpnhreskv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtjxfonrcs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtjnqouhnx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtxnfgnvwn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtdkcnqulz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgufenzy.top/Article/details/gtacpqnkgn.html

Go:   // 手写 map[string][]T
来源：http://dali.andypj.xyz/Article/details/gtnhbtoxpa.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtymfiifim.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tian-w.cn/Article/details/gtgzwdhxfq.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtoxfsxmdo.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtcypopllr.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtevhcknvx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtjnepqlqr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtxiwrzhyb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtebssrkvo.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrxdzkjt.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtyspchjvx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtuuwcqlrc.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gthmchbmso.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtsqrvoatc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.daria6918.cn/Article/details/gtfwbeiqxh.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtdwppdovi.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtcbaiduho.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwpawkuo.html

Go:   slices.Contains(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtlbzwdjao.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gttjfwuixu.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtzhsnliip.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhengqikj.top/Article/details/gtmvppmtje.html


<!-- 参考信息 -->