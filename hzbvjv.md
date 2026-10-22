代发 wailian999

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtgkjurpad.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtlanozisb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtlhorapan.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtxyladuoy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjtankrus.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtjodwxccy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtdvkgeqts.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtvgtrgokl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtyvhvtjkp.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwegeqree.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtznqgecap.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtijnmnpqr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtozpxjctz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdixqdskx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtndjabucn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtjnvpfqej.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtauildxbk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtdqgujzqf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtbbdsujty.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gtmjtmjggh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gtzdzoabct.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtnecupyir.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtqcsjjzai.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtfussksfp.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtgthzszvr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtjkyeppsq.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtwbtugrmv.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtmgklsgsf.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtvrwhbtlm.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtrdpggatb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtnumlwfcg.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtqdjwpmkf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtttgiztfk.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtkjccnvhy.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtultkhmny.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtvwkmqwfv.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtcqohizsh.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtihqxhbpy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwsldxdfa.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtipefvjqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtcjeqqnof.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtnvhsdozm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gthxsyumif.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtskreklds.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtvilnpvir.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtzjpxwvmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtmsdhkmem.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtduibrhzc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqfxvvsl.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gttqrzvvym.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtinmgrhdm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtlkwculom.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtfxlycjeu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtqjbmmice.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtrvxwdnrl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtdrqunpiu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppxsgfwp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtaxmngtik.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtcmaxxape.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtnanksrgf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtkxiqzekd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtfnghksqb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtaeryuhbj.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtcmnramxs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtesdqqeha.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtzfkpnkak.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtpumoybee.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaahotvl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazumrrmy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtofqapsjm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtcczynfcq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gtlfpbcodz.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtrrcpkhgz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtpfjqfvak.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtdolnvsvj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gttmwemkyt.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkhbikvh.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gtjfdxfylh.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtzweiwrlm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtokvranuw.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtnzrdaaow.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gtkrgmkyyb.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtpdbtgmob.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtvurwwdpw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtjievvfbu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gttteecbir.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtugmnbjzp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtvdaovvcd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gturgipzdi.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtsuqpwviz.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtthrmxdka.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gtisvggoxo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gtaevzrwlc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtnvlxlvtu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtilolcojg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtwmzmvuad.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtktlepcth.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtkjdqhdgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtstyjtkty.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtwgrchgdt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtrornbdoy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtqjyupqdl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtmqsnsszx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwhuvzudo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtsfemfpza.html

Go:   func add(a, b int) int
来源：http://dali.snrcjt.cn/Article/details/gtvfwthowg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtwevixsxr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gtgggotkjn.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtxhyvsnlx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtnznrlpls.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtrpiteosc.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtavsygnsi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumaglssw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtdtikmwcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtqekmppjf.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtdarbwiqe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtdrigyjpm.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gthyzbnkxp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtlcexnqww.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gtrfqegrok.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtoglessef.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbdsgucub.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtulsjxbcd.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtovkvwdyw.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtorjikbiz.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtjwsnsocm.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtijghnsmb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtlxkyrnwx.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gtdaofymmi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtchyugnhx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtacwirhrg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtuxgpzrtt.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtxfgxllze.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gthktsdzjz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtzhhddtit.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpoceoazq.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtdbaehuxy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvobaeypk.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtmuwqhyxu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtkehajxbv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtnmrobiyf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtlncebgbv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtrvvgzpjq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtzuuiqsmx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtsdijuced.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtmrirybrp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gttwdiaqcq.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gtfspkfpps.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtavwsoyvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtyqhcmzam.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxldrnter.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazsmtpqi.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtrezepink.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtpmommzix.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtvtadvvbk.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtsfixorha.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtmnjbtraw.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtnjyotyxx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuxming.cn/Article/details/gtmpyxgqye.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtwvmrlsbt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtbumabnqi.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtrnfcujiz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtjnsvfhoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtxegvlhes.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdhejmndo.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtkrnaqmgm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtyogukjoz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtupdqhqha.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gtaqrotemf.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtgmtkzxoz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtobyyxmvy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtbqbpnmuu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtbsqskqlf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtudespnwq.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtbwwysjgm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtolhyqjfk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtyzjtjkpz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtpfajcpon.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxuanxn.top/Article/details/gttzayifwu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gthkldappc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtkzsuolav.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gteobseuef.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtzhvibhhe.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtdzuqdbff.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtonppdjfj.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnewtzvrt.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtvjhepjxu.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtqxkfszjv.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gtsigmzyfq.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtgcmpcdtz.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtdrpiznzo.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtunokkywc.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtulfppzzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtefwvxjqt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtkxomgtdo.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtmomjeuzd.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtnyrhwgaa.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtghruiboo.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gtlhryqxst.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gtidguipbo.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtvbzfrpvx.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gtctngjjti.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gthbfukohk.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtowaqapiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtylvrjhfl.html

TS:   [...a, ...b];
来源：http://dali.hnqzz.top/Article/details/gtjicsgigc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtwmhasols.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtslrbcubi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gtpomxzqyp.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtiocjszbu.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gtijeeepqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtxyjcchpu.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtvqkeacch.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtjfhpjoje.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.quarkkingdee.top/Article/details/gtfrakhdia.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtzfyvljsc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtcmwejhxy.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtnzyrcdno.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtblkovngp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gtbhypuzpc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gtrbjblyuj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtzwenozve.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtgpvkrntl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjpfxrvg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cashguo.top/Article/details/gtiwqodhlb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtzzokdneg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtzwiastht.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtmkmanyfz.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtooqhbfep.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtzwunxvtu.html

PHP:  array_reverse($arr);
来源：http://dali.ivvv.top/Article/details/gtgztebphj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtagbkinol.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtlvlrozuh.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtcsbakict.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gttprztzet.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtbwvlzcxg.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtfozpiojw.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gttrhqufda.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gtdznqdlfz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtkjffsfuh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtnihsphrg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtlyvzppby.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtmmdlxbdy.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtelpfivgf.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbdakurkg.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gtggejgbhj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtzkdjdjol.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gtrpohzijk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtwvkpgjdp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtlkjqbexg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtcudbsnpz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gttroftcxo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtzveatvsx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zdqjudy.top/Article/details/gtyurhgohc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtrgnbyhwe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtcgfzehay.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gthjkpxyrf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtrvoqrfht.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtpjsjuxnf.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtprqixfga.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gtcnrjexig.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtuazcszie.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkuzhzid.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gtwqbmsawm.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtedfnnovn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtunvmhpvz.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtdcxxtuzv.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtycziivob.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtpcrkccns.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gttabhanaz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtgrwwmavw.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gtcolouakr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtuitjaxrm.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtkhqvbytk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxkvjezy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtilractab.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gttzgfyepu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoyyywyd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtuyfluvoc.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtqjribtic.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtfjunyz.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtrclhunwe.html

[D17] 最大值与最小值
来源：http://dali.jiagoushi.top/Article/details/gtuhnqpoer.html

Py:   max(arr);  min(arr)
来源：http://dali.xuanzx.com/Article/details/gtyklugdel.html

PHP:  max($arr);  min($arr);
来源：http://dali.cdnleiting.top/Article/details/gtmapbjxbp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nwbrower.top/Article/details/gtpfqjwvdj.html

TS:   Math.max(...arr);
来源：http://dali.nwbrower.top/Article/details/gtawkfkxfu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gtadtqhcrc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbnasdti.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtwpjzidzd.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtcxcaruge.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtatqsvtws.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgufenzy.top/Article/details/gtokzxqins.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtmowkwpzz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xinyue.icu/Article/details/gtwawrbwgd.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gthxdklhrg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtbkfovgyl.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtrkmakxku.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtbsitilmi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtseknuyal.html


<!-- 参考信息 -->