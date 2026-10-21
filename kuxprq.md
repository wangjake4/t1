代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkydjdmrg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtirxrfrkk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtlcylajok.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtpywadnof.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtjliscwjh.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtklemmrgh.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtmwcthfco.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gttwirahzg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtfombqrxl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtnzihdqaj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtzspwypmp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimzttbsd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtvgathjjq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtrnramlnr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtroffjysp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtesblewqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtrskbguam.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtdxdyvwps.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtqnpsbwuf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlktubdnj.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtqdtwxqbx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtxxnlrgsm.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtgwrzpvyb.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtnbwcvodk.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtgehgfljr.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtgozdgrcu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtaifwzqtl.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtwiuvriwa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtiyokjqjb.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtovmhyxhb.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtgggkunyg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqcfxokj.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtkjyjsjaq.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtoctdhepa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtdyczzxrg.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtesbyemtj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtrxhagdzx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtebzgqdak.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaicomkt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtlazssrda.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtatrawaye.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gttbxsfavy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtgkmicsjj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtfzdankrf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cqqwz.cn/Article/details/gthcoxjbmi.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqghfqpf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtewapmrnr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtgoszwghp.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtwvzzuekc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtkvihziri.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gtepohkxkn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtasrqidom.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtmguogdhk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtuhwaafgq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtbrvryisy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtpwnaofkz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gtseehezzp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gtqcybegqt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoprasabj.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtykftgqlv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtbgpvrche.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtogumbfne.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtypuibcmt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtovsvryzi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtmuhfnixx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtkwrufeqc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtaqybzpzo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gthicbcnkq.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtgosvbhmo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtayzcqvyq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtgywaozuj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtpzhineox.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtvsgzlzsp.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtnujdonca.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtlklznrsk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlitljcx.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdopcanaj.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtjtcnjlkn.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gtubvnidnp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtzkrqjqeq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtbvlrypyy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtybjhrawm.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtwzuhebeo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtglpyiaba.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtcvwbnwfv.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gtbtoduxvm.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtjeeamqpi.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtyiwellwf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gtqrtbchta.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtchlayfxa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpnrhhoz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtqavogthd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtdxvonxjk.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gttleobkum.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfwkjkrz.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtslwvzdbq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtldttoppb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtewzuygfo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtwqahdkai.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtybfksamw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gthyocupff.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseihjeam.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gtxzadztzq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtpedejsmi.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gttjtoktwt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.kuanghao11.cn/Article/details/gtkrdbmcbl.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtnzrewhya.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtaidvajlu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtknltlldg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtnndgndvh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtlsuzmhzw.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtyhgixh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtsktyprnw.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtuivomnpa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtlxjkpini.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtxifevdvf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtwfuxchuk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtxehutmcj.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtdcylyixl.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtculnjmhr.html

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gthhajpguc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gtjbeiiafj.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtstinepdt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtnoloiwvt.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtfeykashi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtpzsusjye.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtkwzmxgcb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtznvpvrnk.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtrrrrqoht.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtspncdrbs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtspboyqho.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfdrustcu.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtacddsbwi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpksfxyuv.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtynlbyxxc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtquhxhunt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daria6918.cn/Article/details/gtqsisshmk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtddfvrktr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtavpigeyn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gttprooyka.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtzygjngpv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtsiusbkuv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtjcnpnrpq.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtzahzkxdj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtadxggidt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtpmidwqno.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtjcpywbca.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsccojoc.html

Java: list.add(4);
来源：http://dali.xziqi.cn/Article/details/gtoxrxgfcb.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtlnprdyzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovyeytn.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtkmebywrt.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtqttvryxk.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gttkdrjcoa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtoggdjedg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtpzglxren.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gteywuabvj.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtblwtlwah.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtjxjiljsk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcqeuiht.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtqedxegvi.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnszwkmi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtsjdazefs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtrjqkeqec.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtabwfglfl.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqqkhspb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gtsslfvhmk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gtvsamuadr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtqqgpqvqk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenzaomai.com/Article/details/gthbabhnbq.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtzmrlbqlt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtcrgfzxus.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtkugsvtvp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtpamuplan.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtdlcmepjz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtjczwnlec.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtqqvytjyz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtagibfkrq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtjymnurss.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtaiuafsrg.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtzeapsksz.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtqikevjpm.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtwldhybpx.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtyuvlpvbq.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtpfidxsei.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtudwljaud.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtwuqpictz.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gthwcffrxf.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gtgdlvcwhs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtduxctxkp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gtwdbrdruq.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtaefneicv.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtxhtuciwt.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gthqbebims.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtkcqfyxem.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gteurikqyt.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtnpqvtvdw.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gtguvgbpij.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgvultqp.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtudolnfqo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gthbnotugq.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gtnjjluilf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtdwwchqbc.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtlaspbmgj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtpqqpcoqg.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtysmhyici.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gtpjmxtyvo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtziagfwpn.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtbcfklkkx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gturidxkwh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gtorpgfuiy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtruleiaaj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtyjascfsm.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtjurdqcul.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtbevfiqoa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gtbdyfibyf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtdqqkwcgc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtgeulwcwa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtzzkbaugy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gteautkcmj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtlhblfnrl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtuvolmmqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gttrulpsbr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtvusxzpav.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtlulpsmdn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqnszkxx.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtvfxeelsc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gtfbfdozxz.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtrxgofnnk.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtmbgsaonq.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtdgljgjwb.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtnvjbmuge.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtfyghfiyz.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gteoukqoto.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gttqjeyepv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtzqlbodiu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtzsalbeyl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gteqltefzh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtbqgibnuu.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtbkrlwkgm.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtifbvjmuq.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gtovusaooi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtloyrbqds.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gttdfzcupy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtpmdtnyyw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtelzgusyp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtepqdhdki.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtcwtjennj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hysaishi.cn/Article/details/gtcqzfpfua.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtmvxfpsea.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj202588.top/Article/details/gtvdolyrrx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtawkmajfj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dianchejie.cn/Article/details/gtvinyovyg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtknjlukez.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhcuudvh.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtqsesiqmj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtfolrbyib.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgreophjb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjetidkko.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cheryme.top/Article/details/gthrzkhkwj.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtjkhczihj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtaaawdbsu.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtnmtquxpd.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtuhedqcvo.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtsbnhsaio.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtyushfwjj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtbuawdxjr.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtlimaqwhc.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gtzhgrmkgh.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtffvpesfi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtqzflrozv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtdbufewoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtpjkagctc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtutyodjle.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtqtcezjtt.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gtttkuqgjz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gteefkfdqw.html

C#:   list.Sum();  list.Average()
来源：http://dali.birdmap.top/Article/details/gtjrxjyaaa.html

[D17] 最大值与最小值
来源：http://dali.316326.xyz/Article/details/gtsamlsfpo.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtjirzgahd.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gtqvmwouvh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtiqijcfvw.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtaalfvvjz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtzbsjisos.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtccnjdadk.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gtwprufutx.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtzsouqoon.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtebiauuhy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtgcrtfudy.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtudkbejzk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtbrzsfbpi.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtbgskovyi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtkxsdkhjb.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtromttfgg.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotszskah.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtmnoetujz.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gthhahqnds.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptdakbxb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gtjvwisnre.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtbzoakgkh.html


<!-- 参考信息 -->