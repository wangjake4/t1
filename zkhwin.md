代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtkuxoxosu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gthzkgxghe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gthjuximra.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtjxphndfm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtvwvgshxg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmdeavkdu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gtirzfhbyy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gtfwtlfogh.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gtcyoftngt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtspwaaxis.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtyhmbfrrx.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtirmruiap.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtxkwwrijm.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtavumeafe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtahdpaosz.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtwemixjjg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gtjharmtdp.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtgimnwtfo.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwhrzffyb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtthowiezd.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtuahkpctj.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtyevbtrsq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gthbdmurmh.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtqsjfbiez.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtzwpjbneq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtqxasahjy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtczxcjqtf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtlgmpsmac.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtatlbxsqm.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtxzpzvrrn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtrrousgnl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtesnzglss.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtwokjqsmw.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtahnlqndu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtxrfowmaw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtljenodjz.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtwuermbkp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtkvfdviib.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtdldgxxkh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtsfitblba.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gthqbyxjby.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvdhdrtai.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtpbkhbsyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtnwjqmnzd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtxjqlmrbz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtmbhkpzvu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtbhotadjl.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtxxduqkxi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtbzxgobee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtevwcotmq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtvnrfdgge.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtzyckjnzk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijrkfiwd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtbnfgnfzf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtxigtstsb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtzhsiuzwm.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gttaymbqqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtvykfhjkw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtpesrckmm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gtrimsfxez.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtcmtljvbi.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtrqmxfeui.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtjvvogxxi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtjnvgunpb.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtsfejvwbb.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtzuoohkai.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtepkqglvj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtycodtcns.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtpignystj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtprjdqaqm.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtosxsxpuk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtqypsgpln.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtpjumswhz.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtvdvzubca.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtueospzzf.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtdzqxvdtv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtptpwdgun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtkkkiflhh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtrugwqobw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtagyycfbi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtgdtyiomm.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtbjcfzehy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtkhrecskb.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gthsknuwia.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtvkrpagny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtrlrbfoir.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtpxdzdskt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuhbzheew.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghftxmfh.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgegrjcsp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gtopvangap.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtbnjffhkm.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gttxsqjuul.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtxywqztau.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gttjxqzwwc.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsehxxryv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtnrpxazqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtzcgqhxvk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtgvzgfhvb.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtzutqrkyy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtizgufzrk.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtycndbxxl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtiljvjxqh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkqbeqpk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtirjfgsqp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtvgulgkop.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gttqllgjrv.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtwzwyjxwa.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gtaifmtmid.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtjptdosjg.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtxcjmgqpa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtdwmhufbv.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtsglildzx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gtuscpizxd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtrfcksxso.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gtanhtdkdu.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtswomybgn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtybemdien.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbkpbfou.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtaksxywnc.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gttufshifx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxajoubpl.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtczxmtggh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtkwkjdozx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtvoejslmc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtbrtdwrev.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtxzbwxhiu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtunzcfzya.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtlarrkqnu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtwohhsezf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtelmqowbc.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtrrdcikce.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtazcviuzv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtithlnkms.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtcpwviadp.html

TS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqvmgvwhb.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtenpffatq.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpugshbfh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtggpdhxik.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtktohuzzg.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtrlreihfh.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtuefhcojp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtgdqjdvcl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtvbazzsjp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtmmqvrjut.html

Java: list.add(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtsddqvufz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtlbzciihd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtdqohirpp.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtjgzuzepc.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gthgqpfrmf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gtjbuksvtz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdnlpqqe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gtcaleruai.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtjwgpnfmx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtzlnipgbe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtlzyccunn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtntuaaswg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtvlyaxjuj.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtghrnzszi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtmdlkyoer.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtsnzkapjs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtionutunb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gttoeizkfh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtwgkeqyjm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtvewvqbyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtuoefnkmg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gteyorslxj.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtmnlstyqf.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtdcazoxho.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gthzizltcj.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtoiirmuto.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtktvlrckf.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtdybwgtty.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtgjfhgarc.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbcugzqn.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtaudkxgrz.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtlwmnsmgo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtaviyxwcd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtgnsljhwj.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtpwfrdbkj.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtpbohdbir.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtclmzmizl.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtzcljapsj.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtqvpxibwr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtsykephcq.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtpchyahar.html

Py:   a + b;  a.extend(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtgejygoev.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gttbqhcszc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtmmrklnzm.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gtnjtibomw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtoodqifyo.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtazlhdoyc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtolyowabd.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtddxqsnmn.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtzsuauhbn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtetseiygn.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtnkfcajvf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtntnfsiuc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtcdzjaqkn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gttvozmqxp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gthujoozit.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gthubrdzpl.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtwphkyluv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtfaerbiji.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtrykkxtdq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gtaxkslddm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtmhuuhpwm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtizjbjxyy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtqozcguaq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtzpwsdabp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtlfzbsikd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yvedp.cn/Article/details/gttjdjsect.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gttatozjcv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtuqjpbyaq.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtwrzlhsif.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtntcmzsom.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gthzcztzga.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtrpmianat.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtkmnumkzx.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtyibymchv.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtptcdljtd.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtkscpbchp.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtocgulkdw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtmzjenuux.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtvmxzfxsa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtztrddpta.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtgzsdnrjz.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtdfudqckq.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtebnrdkqq.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtffuevklc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtmcdrmryq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtaezeccfb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gteambxzjv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtclhoqicu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtbukbenok.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlnlmuxem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtbfozlucx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gtzykxkekh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtwtfwbopx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gttojixptd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtfarbskpu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtdjmmdwke.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtlnkhbuts.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtdaobqhgg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtuvgtkssv.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtyuldabep.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gthlgtetng.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtoxphuaww.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtkjiisffx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtlykevzdw.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrffyobwn.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtdtocwplh.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtkigljish.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtcwijsqqg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtgcptnsiz.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gtjdjezehp.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gtshwlgjvu.html

[D16] 求和与平均值
来源：http://dali.yvedp.cn/Article/details/gtqskijllw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtgyxjhxtc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gtrqfdrgrc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gthpnkyezt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gtzfnbiazg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtjaggbrrk.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gtchwwitsa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtwwafclpu.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtjybyyxjl.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtckvcqbvu.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgfxxhwkg.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtfihzrrjg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtektovxmx.html

TS:   Math.max(...arr);
来源：http://dali.gogol.net.cn/Article/details/gttprtzwsk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtudkndwal.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtaejyrtxz.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gtxuxmhvaz.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gttjmvpfoe.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gttzafpwal.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtqhpfqmip.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gteebicbbp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.aizwys.cn/Article/details/gtjcuzdyfy.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gttemhdwxv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtfenbcrdp.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtqujszmah.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtkziewctn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtlsmvoopv.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtpwbhijgx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtvbodhmoz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangtech.top/Article/details/gtekdesrzf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtwsecvmdy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtwmpprexo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuanzx.com/Article/details/gtrsffvqaw.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gttxzailch.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcqwmodd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtdeuvymei.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtgrghdoia.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gtawucvint.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gtrfkenyeo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gttecrwmil.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtjkqqmeto.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtbqmosjit.html

Go:   // 手写 map[T]int
来源：http://dali.zhiwuduotai.top/Article/details/gtswxeabum.html


<!-- 参考信息 -->