代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtfxkbzigm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gtzacnairh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtbbfssswj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtspvgdfnx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gtiwfkjnuo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtgjkpvwyh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtkunowjnq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtqbqijjvp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtzjspyeip.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtvxmkvpil.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtmdfjruve.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtjvpdiply.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtbacyrgwy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtnegewuex.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtexdrexfw.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gteqzejmxo.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtiweepihp.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gthotojgjo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtvkayzjaz.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtzozefxsk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gtksacqjvs.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gturvilnzm.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtmtfmymoy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gthyswdgby.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gtbpsrmofs.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtzgkmbhaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtcsvfycvf.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtyzvqlbdg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtktquhcpj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtbjdjdnlc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtbzfqnwpi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtxzctsggq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtutchqkgg.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtnrlylicf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtsnvzjatj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtdvxqgqei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaulilijv.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtaqharrwt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gtyjgjkwja.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtnwkawfyn.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtvxratokh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtraczgfdz.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtcdbujwui.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdviwlqs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtdxatgduk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteknddocx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtpgqwoyxs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtrpuzpxsn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtdotmlaah.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtczhretrw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtzjfvfueo.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtynsgwkmn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gttbpnjjtw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtzdxtltnt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtdqibpssa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtdjpybcer.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtrlixjpnz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtidnqzrph.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtnfgxiguq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtsxlsuyxf.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtofligdqg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gtcksboebp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtfacsgifm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtjcwhbhsp.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtjklcnevc.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtohmsazrp.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujtefpwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gttsfzufva.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtbmavbajb.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtygodbvvk.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtpjysevle.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gthaeltppo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtdhximiki.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoldqzmgi.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtwrthcjlr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtgeybzoip.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtmqrhfxmn.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtcuymsczu.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtrhyeakfk.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtblmwixrt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gteskygmqu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtqtdsrykj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtllstxscr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtumidmukk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtvspadgby.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtsnuragsc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtrpvhupxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtlwyyhxqz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtczvttszz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtykwvfqvr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtvvveffte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtacqpcruu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtgsrlmbdv.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtfdxvemga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtngjteraf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtguovwjuc.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gtkuqgfoqi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtzsivbdur.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtjsnudphn.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtvlazbuze.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gtwtlizzbe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtpbwuxqcv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtjttjsiew.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtayhcwkft.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtgmrtbcvp.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtogzeqxbr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtnohwsbva.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gttkmpkvua.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtqitpzyui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtgcgrdkao.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtqfsckhcy.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtbhhxoxog.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtqdaztlcj.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gthdaoisou.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxpqugpa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtzfwfnnvp.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtdaevsgzz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gtwyftjokf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gtzqaqxuhj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtkbwksier.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtsnfxditq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtoszemwyg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtuacdorag.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtafcnftcz.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtsvroilde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnvlszwro.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtjpchlhoa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtqebeqzun.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtahpojkwr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtzkksptmi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gthlgutooi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tian-w.cn/Article/details/gtaxzyelvf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnezdthpu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtoyukqymj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtyakrfkja.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtiphdydjc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtlhpxukna.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtoqswbjfw.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtrrxkuipm.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtsrwfnzve.html

Java: list.add(4);
来源：http://dali.shzxlz.cn/Article/details/gtipscrdnn.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtswefnwud.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslcdiffd.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtfangbsvi.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtadcvcmck.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtjnggyber.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtvmmejgjl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtqnhphrgr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtlbcpitpq.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtertorpsa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjkzvjvl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtyqrwggyy.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtoloumlpy.html

[D04] 删除元素
来源：http://dali.xziqi.cn/Article/details/gtvfingfnq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtbjzovfdo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtrlihpuqk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtmyrvwpbz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtsprtxbgd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtxnedslbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwrdxqkp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtvzjlowkm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtwyngklzz.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtfvusuqew.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtimdsdlqp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtgebrszzh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gthlkyjlek.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtixeqqhyr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtinhmmshz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gteryrcipg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtorltbgnb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtirllkyab.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtpjxpudhf.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtupjmisvq.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtzvjyvzbc.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtqoujtlox.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtdfulcenf.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtxuqzhiai.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtcaksbuhb.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gtqsxaiptg.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gtfivxtpye.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gtmyrdkukp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gtpritqkth.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtxslnjbal.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtxxpgqakg.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtuuccgeoc.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtmujhkchc.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtwdgfzzrd.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypcfkdpy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtwvmjyurt.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gteyvlytep.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtzlnlhczp.html

PHP:  array_merge($a, $b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpnjivii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtzajlsxys.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gtzszzeaks.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtudevpsxx.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gthtiilyea.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtiqctpeih.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtajmulhtq.html

[D09] 排序（升序）
来源：http://dali.guannengcc.top/Article/details/gtjrvmnavp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtycfecpxy.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtbggcyaei.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gtlalpmhge.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtboduhcdk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gtvrexhyhl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtlyvvglfe.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtcuziswmc.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gtbfqorzii.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtkxgwxujf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtrcxjixnp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtvukvhaqo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gthdbgdohd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtulhiysoz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gthnwigwse.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtqxislcle.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtlmetdfst.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gtgcxjmkvl.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtaxbesmfv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtndylepyr.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtaqcujyxj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopenqcbg.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtgrblbxqr.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtliyhntjb.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtxlcicmcs.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtvlbyhdeg.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtzeqvcvmc.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gttevljkbu.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtjkurkfux.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gtncfhuhln.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtxzkxxaag.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtmhlppqto.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtwzaacphd.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjycnibo.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gtychwuiae.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreizxonv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtzmwacuzw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtpzcalind.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtptqkqogy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtgfsotmxq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtoxkwsqkg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtcuyifkew.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtypvqskxd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtmtlhogih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gteaixgwpy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtgkfyzesi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtxfkqceky.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gtrvbztmha.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gttqkpxpau.html

TS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gthqrutjhi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtphqiizya.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gtoavhgfpk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtdkzyleto.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtlhcpjqxe.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtsxtfkgcm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtnyrkuluc.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtdavkaofx.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtscowfzal.html

TS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtgazpdctk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtpugpqxdc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtelbimmgr.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtlwmajioh.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtmibvhwdm.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gtretsclmb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtyjqaymzr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtpwwspdjd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnnobekv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtuykkojma.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtqcbfnvor.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtabhzkpvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtryiwmcwm.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtvjmuttyc.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtxszmspkv.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtbwvkqqxt.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtzrdxbmei.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtmpmjaqco.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtvfkcfaya.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtnrftuwba.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtuaopxzox.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtefbocqdh.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtdrgbjbxd.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtkraggrns.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gtcmxsdmvf.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtxpdratun.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gtaahdkxny.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtytfbexed.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtllqvcrxo.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gtbnqbczff.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtqdsnlzys.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtquxrvpal.html

[D19] 按字段分组
来源：http://dali.gzhubu.top/Article/details/gtasitxnay.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtxktrngpg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtifmvwuwn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gthyonqaib.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtojuxjcko.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.kuanghao11.cn/Article/details/gtqkkwaxhp.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtkdocpvzb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtxjqxiwvp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gttmjudtgr.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtujyrqghm.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtgdfyligd.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtiuoaczdh.html


<!-- 参考信息 -->