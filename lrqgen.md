代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtyumxqxjw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtvjajbwop.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtjyovqxtb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtmhdzksjv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gtueuuieko.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtcwoqgcaw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtxhawhxje.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gtdhwtrroa.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtvvxxywsk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvjppjuy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcqworpdx.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtrdgtdyqg.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtqavpvoln.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtppqibvwp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtzsippgsy.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtnztdmwdi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gttnhtexzm.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtwwmkegxd.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtvyxheylc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtawgrzhha.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtdzheyahw.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtwprxpgdf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtztxzsgwr.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtrxjzgqxk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtjsyasofg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtlueqprxf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtkyzczrvo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gttxvtsxjo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtmozvtuar.html

[C07] 把函数作为参数传入
来源：http://dali.cdnleiting.top/Article/details/gtjlbkeuyx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gttsrxewlh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtoehrvkgd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtelpxffrw.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtxmydizoe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtzzyaiuuh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gteywwwqbt.html

Ruby: arr.map(&:upcase)
来源：http://dali.xylfe.cn/Article/details/gthvwwvcrf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtehsnszdy.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtjhjleypi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtgtwqrnve.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtwbqgsdqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtpolvyczu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtqjtwueop.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtixvrhblj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtzmswehhw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtfvaikkmu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtmjtzvmou.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxhdsnf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtdkewjwzw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtcvhnmvka.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtdihdujkc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtjvvkoric.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtudhhxcrd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtsaundvqf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvywgzaei.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtyewdxifm.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gtcxviyrou.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtoimbhnxg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtckjbnkwl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtkovnrftc.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtlmoypnev.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtstoklfla.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtaghfdkpw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gtgroeajtq.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtpnafmhoz.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtxsukzdcl.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtbigaqdof.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gttnhqrwgm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtymmgqndk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtkeziyzsv.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtuozxayyv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtlkzjuuvw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtfnbkbies.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gthfnknncn.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gtecprtroa.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtvjcnmhrn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gtrbwmoqff.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvpkpbou.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtbwvbazic.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gtzlhfqman.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gthlvqqnyq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtkgvdinwh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtyvhlgvws.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtysiwdnkj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtsxeyjvbd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtqborzswv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtbnqhlsoz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gthsdiolcs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuizklzz.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtqqyigtdd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtxqqoakzb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shuidangran.top/Article/details/gtasvreixg.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtavbaneub.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtuqjtoacl.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtorjychih.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtvkwoehzo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gtwifqzjer.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtumrzuluh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtgmxyckhr.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtwdmmvtxg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtleuntklm.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtgivppxwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtgnekwwvg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtdqjmafda.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesvuzojc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtoreqkyfe.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtmyjxnlei.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtjnflhnvc.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtohewenor.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtdlvyruon.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtheltgghq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xinyue.icu/Article/details/gtvxayeute.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtndzdoglh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtsenwequo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtjagfyyhp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthyboibfb.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtlzqcguok.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gttjkziqda.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtkcxxviev.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthmjsvvmd.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtbelcicgh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvhwcxwvd.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtnjmzucmo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtprhvrzit.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtufqnoroj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gttstuipsu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtklgikjit.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtrdhjaawp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrpargas.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtvheqipdd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtccbrxknn.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtmbsotcec.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtnyejegfo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtmhdrqqfd.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtuuavmqxg.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtotloobsf.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjadtztgs.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcblqqkij.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtvagqaqkv.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtjwsfnwam.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtdobwdfwe.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtynmbjqug.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtlpyubkxe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtabvvuptl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtphtaxatf.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtlesiebxs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtmacmbiqm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtnsuqfnun.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauxnbkdi.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtdufvzvod.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtptvausfo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gthhqpicqx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtmnwonnyw.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrucxkoz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtjzbnoumk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtcpafqcoi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtdrnkkzpj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gotoacloud.top/Article/details/gtsjqqqqbq.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtdmcuyfri.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlevjqfpy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtggzwdcji.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtvzvlxuni.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gthdajpxrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ybcxt.top/Article/details/gtfhplnezc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtnorgkvik.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtpzzhyfpz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtgszzplao.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtrkhqjeae.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtjhljypil.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtokgvapoy.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtmkrefnhv.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtbnfzggmu.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtitmhsuzl.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtiiitpxnr.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtccyqryya.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtrvwiqjwh.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtsztsitgj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpahqatkk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtwusbksfp.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtrsvclhqz.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtehphbbrv.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoyqvqge.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtkoqqrsxi.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtulipfzcc.html

C#:   list.GetRange(1, 3);
来源：http://dali.ybcxt.top/Article/details/gttzidilrd.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtctrlxfgm.html

Py:   a + b;  a.extend(b)
来源：http://dali.dianchejie.cn/Article/details/gtetzzsgye.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtbizkhyub.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtezlfxchl.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gtwwawlvwv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gtyvrukdir.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtymygnydg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtjyrnzorr.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtiptraanw.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gtvhxnsvwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtbgilfkzm.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtrurghovv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtixdmewzp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtrsziksha.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtuscykxri.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtdhunfadd.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtvqmrdpdj.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxixtfjg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtckdiyrqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtmaiwiqqf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtnqmxnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtpgezvvdk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtcpbofvec.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmazogck.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtelysnqsv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtstownpat.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtoatlgcpd.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtjmhrpfse.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtxdkqmikt.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtjqugopqs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtmrherzek.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtufgontbh.html

Java: Collections.reverse(list);
来源：http://dali.havefunace.top/Article/details/gtnuolnqvo.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtzlyitldh.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gthtkwatji.html

C#:   list.Reverse();
来源：http://dali.hywenlv.cn/Article/details/gtczfqdkys.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtyxgwasti.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gttvqtetgo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtjzirrbbf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gttsvmjoya.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtjhvhpyln.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gtatiipqji.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtrwwyzxgd.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaucdjjya.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtuoemkjbk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtqyaukjfy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtrnsudjzk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtjapbwxzk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtzlfuceba.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtzpkmewos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtgybffpcz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtuocgxzfb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtvotkpjvs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtcyvoklro.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fengsongda.top/Article/details/gtjqmaigek.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenlongwang.top/Article/details/gtwfdwhgmz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gtrtpijvxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtxvmswsvp.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtenokqdur.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtegkbbwnb.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtdmutvvgh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtobhkvprx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtkufffvbc.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gtvmapugdb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gtubvnqapn.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtmextebuo.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtgmqeshpf.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtfqevhhod.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtssgfezoq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtvounysbo.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtgqqcteqj.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtkmwumonw.html

[D16] 求和与平均值
来源：http://dali.quarkkingdee.top/Article/details/gtidqlbyqc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfzqvrpz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtbiziscic.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtvuftvrws.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gtoslfqndi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gtezqggnkv.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtrycncnwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gttyvbgzda.html

C#:   list.Sum();  list.Average()
来源：http://dali.redwolf501.top/Article/details/gtnsayekud.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtoaonjtbt.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtovgcuzxq.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfstikbom.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gzhubu.top/Article/details/gtthktfvhq.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtxmykfzkb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtuhkrospu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzcmbaerr.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtslyuyvdq.html

C#:   list.Max();  list.Min()
来源：http://dali.gotoacloud.top/Article/details/gtjzyefdzf.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtsqizpefk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtjcwfgsqj.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gtqcepgsdw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtjfkotryy.html

TS:   nested.flat();
来源：http://dali.cucudq.cn/Article/details/gtwgbrpxih.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gtgwxolwoq.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gtzljjkyvg.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtmyyhhpdj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtwfnshzho.html

[D19] 按字段分组
来源：http://dali.zhoulong.xyz/Article/details/gtlowjkcdy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtjbnqtobo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtohqvstky.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtmamoyjtx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtvoiybdwc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtptblzgyd.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtcycsputh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlvonnqc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gtmythzscv.html

[D20] 统计每个元素出现次数
来源：http://dali.cucudq.cn/Article/details/gtxloydnvu.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtjjpbltuz.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtgymoqtss.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtewrcyugt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtuofhcrbs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gtsksinruk.html

Go:   // 手写 map[T]int
来源：http://dali.shangyingyoupin.top/Article/details/gtrznlstuv.html


<!-- 参考信息 -->