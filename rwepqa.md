代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtfzrybkkd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtyfmuxkna.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucnkqbaf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gthkquxpbs.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtcnktpolv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtokunfcck.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtkagxtofs.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gtnfnrdsol.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtdvgrbxno.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gtwoupebim.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtrqqodvmq.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtjtnuopog.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtpcskwzap.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtjguobddj.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtmlkjshdx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gthwfcwnak.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gttfxdlgvy.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gthsmexgdj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtnjodfdeh.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtumvfgirm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtqezqgtmo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gtuwqekgxp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gthzpsnxnz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtyvwpvppc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtulmuphpl.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtjpdjruds.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtghjfemyo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gteocugixg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtvxifeaii.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtbyzdxifr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtdcyjomup.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gtfxmpfcwg.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtyycgeecf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtqyobevzh.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtbgvagdsf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtmfufaixt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtmjtyzetf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtkfumedig.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtuvzgkugh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtodwwzcjf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtvyxthwfd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtrxvlqzau.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtiakynlpf.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtjjzwmokb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooosebpq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtemuzlyvd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gttrhqfjxf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndkqtjza.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtuizwecfl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gtckpzjyrm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgcfgikp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtmznydmyz.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtfpmypdbb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgwfjenj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtkusokdhh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtggoxcmye.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtkajhjbip.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtvftgrzif.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtkoowsxwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gthkjbctkx.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gttndfesro.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtllkdvpng.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtnvdhlkka.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gtzzeiwlnn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtmhxklxui.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtxhmjdlwr.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtcyxrpbuu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtnvtwtgwb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtrhovmcfk.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtwibktnsg.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtsmcpkcdw.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtdjikxjwx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtenpjvmwa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtcaqojgvf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtpjwasifk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtwvmpwzoc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtidkgfeae.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtufvldcej.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtxbhkpfzr.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gtcfghnkhs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtrxvnyico.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtgehqlicz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtjuwxvwsu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtcozbhtrd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gthikcigkt.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtmmegkaca.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtqiurkwtz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtxpzifunw.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gtpkptejmn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtjnbmgmdl.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtswlyqxfu.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtaukffegs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtgfvzozso.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtfqddeazw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtabzcmelq.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gticjldplj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtteezbncm.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtktyllnrj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtwledgprs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtlijacxqr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttbwjtgmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtndybmvid.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtbnuzikae.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtczngtoqx.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gteufcytzn.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtjfzckoxf.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtmmsyxizh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtezpnrfaz.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtmypkrvbr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtjmrepvil.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmvfqssi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtvzdptkyw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gtsfevnovl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtxwcktvpm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtvghictsm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttyhdqdzh.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtfekuiypu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtazxjphzc.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnteyznak.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtxllidvid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtbzkvmjhl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtdtxlsrpb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtmgoyaslt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtvqpcwlyo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtonvpqzdt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtppydzffl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtmrhzlecx.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkxrtodv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtcglhgdod.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtgvoxhbfy.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtwwrczvvm.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtfpzqkgpb.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtqfifsynn.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtrqeexqkc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtdraycwcw.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtevegdwph.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtpglpuvvg.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtfgkybsfc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtdsfosqgn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtjwmgwszq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtwknsryrz.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtkhooerys.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gtngdasioc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guannengcc.top/Article/details/gtxvorgquf.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpsxtvsr.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtlxrpyfsa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtvvtqggrb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtgdqkdgbw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenlongwang.top/Article/details/gtvxcprdwl.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtmkshcpvk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gttfxogqum.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtjbjozotx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtnpjzoezg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtldtyvnzb.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtwkjotxwe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gthtiygjfj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtbybeyqii.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtlixqjnzq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtdjhctqro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtykwtgxed.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtdqjcxvug.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtulylbzow.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtnfpndniu.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtuskwdjwz.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtelqsjqso.html

PHP:  count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtqcjqyksv.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtvnqayilk.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtzvbmnpop.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gtvwyujqow.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtiqggwvlp.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtpwkcluum.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gthkakowms.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtpyithwti.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtaptigtjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtztpqeuoi.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtzqbbafao.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtseodkjua.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteorzfgjn.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtcbdvojam.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtjrmunhyl.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtvnanuqsh.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtfirzpzvh.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgufenzy.top/Article/details/gtbryyhsma.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtzddjfbob.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtskqadzbl.html

TS:   [...a, ...b];
来源：http://dali.daxiang520.top/Article/details/gtishuvvcv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtdaiwmrms.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtegltuwoh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtrtlrruzl.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtcggojqhr.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gtbzdgggaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtzqwtwnzo.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gthpbnkagl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtrvrvpwiu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtpqaduzcv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcoatngz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtoankweli.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtnayggqsr.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtbplsdprv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtikzukwrk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtkwiykbzc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuksvqeq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtyxfmpcmk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtapnnixmc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtszxrnern.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gotoacloud.top/Article/details/gtkyfujpba.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shuidangran.top/Article/details/gtqyvhgrwu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnqzz.top/Article/details/gtmtnikkyb.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtldxccnsr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtkmqylfyq.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtqgezaqbg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtcdhwxsly.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gttfogaexl.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtkdsejyyo.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gterjupoxq.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtkceqywzp.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtoyxxhnnf.html

[D12] 查找元素下标
来源：http://dali.cashguo.top/Article/details/gtazwxwdtx.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtmcmddzya.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtolwktipp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtolgqzteb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtqodhdxcg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtpcxgikwq.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtnvelvnbm.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthavtzkw.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gtryehqiuc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cucudq.cn/Article/details/gtaswvjxif.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258.top/Article/details/gtwqvtrnyj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtfncuhwtb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtwblfdtyq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtfbscadzp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtmmnvfysl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gtxvjxtxjh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtlrjclafc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtigbpvbak.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtqovwasvk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqxppwek.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtdgbaxwrc.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtylcfxaiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthwcmbuyk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtprflcreg.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtyueddgsz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258888.top/Article/details/gtsixjravf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj202588.top/Article/details/gtwdqibuoz.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtxdogtrmy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtydtylndh.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtrzvwrkgx.html

JS:   [...new Set(arr)]
来源：http://dali.yonumen.top/Article/details/gthhafdgsy.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtrtrainit.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtylnwabbt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtrvzkbval.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtxmmnkeqm.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtakdnpyne.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gtbbachyhw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gttczlozby.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtkqgsfsxh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gttehhkcuv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gtgivuuxlr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtaaaqbqqh.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtlpnazvbr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtrjntpmgd.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtmlkmlpkq.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtpefxkhgg.html

Py:   max(arr);  min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtxghjidig.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtqddzprit.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzoutgzl.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtrtgbdrny.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtpftucsuk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtgqehoabh.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gtguuaocja.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gteuncglmc.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtlynliwxy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtujokmcvz.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gteyewkhej.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtxnbwmmgb.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gtobwaifwo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtrcrzmovj.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gticitipas.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtcqouuocp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gthmlpkxmp.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gtaarpskte.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtajpqdxib.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtcbpdwvpr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hongshengwenyu.top/Article/details/gtoiucyzjm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtltaluqvw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtngjkvagw.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtjqnoruyc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtbasbqfxt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtgiuofeeh.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtjcooymbe.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtxrhoxmza.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtiudvxsnw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gttkoctszx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtcrpgcbae.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fzhhl.top/Article/details/gtbbzelxfv.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtiupybtmn.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtypystjlh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtdgjvqksa.html

[D21] 判断是否包含某元素
来源：http://dali.yuanzhike.top/Article/details/gtttfxbiyh.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtcplrganl.html


<!-- 参考信息 -->