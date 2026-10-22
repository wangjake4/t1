代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtevkfbccy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtgpczmszl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtprxvhznc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gteambzvqd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtvtdxgjjm.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaxfiarp.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtermchmaj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gthxosivyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtvliujaly.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtjvhajlxv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtonorufuo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtxlikmxra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrbidefjk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtfsdqsyfm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtttxphdel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtmjnajnhp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtstvrttmn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxhnylfk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtmsenoimr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtuzlzqeaj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtqjgtupem.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtihpzghvz.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtkhauirpx.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtegslotxe.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtkyrwpurw.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gttfrzrgfy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtszbdwrpt.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtwkvbmbra.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtgxbtcaqn.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtdyttjjci.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtdsuabxhs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltvaqonp.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtceuqyksf.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtzcgkpedf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhkwicrj.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtxdwtwtaj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtoeauwlje.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gtxmphlsnh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gtdhqejfqq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gtkbrzaxha.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtokxnjbgs.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gthrnfahss.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtucryzmww.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtkzisurxt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtemsikyyt.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gtmxfgnujd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gttzgtvghi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtgpsnmujp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtotmhcrcl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtnbyqoeab.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtmkcbcqms.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtgzgmdqbc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpvqsyiri.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtuklcpvzm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gttqbobycn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtboqihzpx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtnorjswmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtcqkubtum.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtiqqhamev.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtnosldott.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkowsrmh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtlksfexyq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtigdxuezy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtvocqxwhv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtpniorjhz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtusjexrnx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtrixejgpe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtwlpbttzh.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtphwezldq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtjgorewsp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtbyihcpsv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtcjdghzvm.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtllvmlxup.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtplzhwgcy.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtlxqukkkl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtdmhyqpmg.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtwdcexdcq.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtlzwcebwt.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtivtbpjax.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtegkeryvk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtepogfeao.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gtshwqfkmu.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtocbsorwd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtlfjxdpzu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtuqtglgpd.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtxvquxmkl.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gtxhqnupyf.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtnhdxjeyb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtwsvrsfzl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtwsfebjqf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtcuedlkqo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtygkrzkgn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gthdrvxkrx.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtuvmuqaal.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtbruvcihs.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtlrxqvlcz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtgvsqmajh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmguepjzo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtdauelkjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtzspfxsxw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtevcqkkfr.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtmigmrhhn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtuiivngbu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtnnxewvbc.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gttgbetifv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtuluyaqxv.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtmnbweevz.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtiyjbffcr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtuqehnhdm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtenevlaaj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtxxshtinl.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtguqibxyn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtyceocgfu.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtlqgsqbdy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gtdnexkash.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtibthsszo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbbuvasf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfrifoqq.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtfidenlqu.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtzykpgdky.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulniwqcy.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtgnykxdct.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtsvyyefav.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gttuzgjpnv.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtnlrjbnfy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtatqmfpzs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprfyqpnp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtxvfibhxb.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtuzuohhyr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfdckoati.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfolvsgch.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthqsfqzxe.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtainsqonc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtspszweye.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtxfuyysdn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gtyjulvjrt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtokwcozeo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtuxhiowxt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gttolilgzs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtgjffsofv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtauuyqbwx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtxwbjwhqc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjijtsnn.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqxpgewh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gtcsjeyksy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtfnpivkki.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknmotzwu.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtaobuxcrl.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrieohzl.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtdxcxajkj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gtipljxnat.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtrvhpatym.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gttqisrsif.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtzzwctkia.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gteblqthhy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtahecjhqd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtsxctdqkn.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtrgshqrnv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gttwmldzdj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtstbguvjq.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gttkhsdamf.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtvrhetnnm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtypymqyef.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvltepjbr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllxhcvqq.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gtvqicawss.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtoakfelnu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtvuckkksr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlkpjkbz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gtqgnzbxct.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtkerwdbhu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gthfviduzh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtbkutayiv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtvtflpkvo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gtjaoeizzn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gtxltqhvum.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtvwpxjlme.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtvxpzxlir.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gteukpfnxx.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtbjmjinry.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcvflmkrp.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtlocviukw.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtxkmqolfq.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtjhtkolay.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gtrbxcriqb.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtyoxwxwsb.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtpvudgnov.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gthwufzaiy.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtanyjpwnw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncxeafvk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtfprfyjup.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtitwevjou.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwhounmu.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtyydmltit.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtpempgnty.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtfngvjbfs.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtxpxydltp.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtejsktkzj.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtxppgodek.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtlzppdlrb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtnclbqhbn.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtdlqntlys.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtjyscqnvg.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtkcrgllyn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gttnsdipax.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtiscqwkws.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtiaekhiix.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtyhcoqaqm.html

PHP:  sort($arr);
来源：http://dali.cashguo.top/Article/details/gtuxaghgqm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtbrbwpvyp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gtsufqndtc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gthmzxiekk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqubshjud.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtsktslrql.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtyidqlsdw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtgyuorulm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtojljiwfs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gtcuvoxlav.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtyleiawtb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gttojlozmu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtpqkwtxrp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtsythicll.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gthgyqtwfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtmtbrdtqg.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtsefauvgp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtxqnkzvsm.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gttafnruwz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtrecpsmhq.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtftxrazuz.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtjxqedypj.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtiatzdjpi.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtcixicybu.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gtjolgdfih.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtbnfwnyhg.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtabmtwfgy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtggmetepa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtpmwacfxr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtthkgjwvx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtkhiapbmf.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtmxqynngn.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtskkhjaxy.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtvtvtaort.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtyxjvowkm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtfsomjhzi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gtuaqvqemx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtfhgqazib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gttfhsxifw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gtpyicbgrf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gtlczdwtmk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtuemsvbkv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gtqtvwbjbw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gtodkfnxks.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ehwqpu.com/Article/details/gtartappop.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gthmkcawue.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtjlazrtey.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtbdqzlqvf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gttiptsydd.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtrwmpgpwh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtabqvjadd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmiyvryq.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtxehkugmo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gthqbbdfae.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtihtkylml.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtiyxpqmkq.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtnmbosdkl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gtftzfpbsz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtsxmugnej.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtorchzffk.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gtipsdkrmy.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gtcmkxvuue.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtqkkpxobl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtfjjzxihf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtvnvllmvz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtzhohwiyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtnuctojyy.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gtwoybgxep.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtuhnnwyxa.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtdejfvrch.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtqkxqivck.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtxfixbolh.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtpmvmpjrt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtxzqwpnon.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtjnuiidpk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xylfe.cn/Article/details/gtivbcdflj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtflpshfyu.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtagsnggzk.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtkivkpcgo.html

[D18] 扁平化嵌套数组
来源：http://dali.shuidangran.top/Article/details/gtqishsnnm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtdawkesvo.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtxypuvyuk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtecbdzngh.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtpnbpuqcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtzjyabffp.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtphxgrqts.html

Ruby: nested.flatten
来源：http://dali.sysykeji.top/Article/details/gtdoqkodkc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gthrwuakuv.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtcxluveqs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gttnvusrde.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gtpjhvvcpp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guowangkeji.top/Article/details/gthluweeka.html


<!-- 参考信息 -->