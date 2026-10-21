代发 wailian999

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtwartppzl.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtgvoryoun.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtochuibus.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtwucbjxdb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gthxgqrphv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtktjomtir.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtlxgaokqm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtyakoybvt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtbglrqqwk.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gttucrjhgx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtigjfxzah.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthnmqsywb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpgxrmay.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtdvssjukw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gtbhhjevjh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseqounzq.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gteoabjxlc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgicxbccq.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtonzgoriv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtmvslivlt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtxmewicgv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtopoirapr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtjqzhcqsp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtlgvynqez.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtnyxdsqbu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gtzlgefmqo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtazrlzasq.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gtzibtfymv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gttwlolwqy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtpimnwrns.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtlulvvytf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtafoenwib.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazovroow.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtkohwaywh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gteagulyli.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtnhtlzsil.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcuxcqlv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtljzpdvqt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gttscesxxe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtmqggzgvg.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtupfqqwyo.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtyjfnttxd.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtauhjgzri.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtjpzrbnkt.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtxiaphaah.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtdhstvnic.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gthbcujncf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtgweozbbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtfdmqjwme.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwduoznq.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gtubbvnuch.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtazabruhm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyfumoqc.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtnpozgyzt.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtspdsaopa.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtcfofbgzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gtbepknltx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtlpwgphgn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtpnzdjjny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gtqdspwuno.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtapdxyxvm.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gtlrehwuhe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtvdubvdhf.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gtpomzqyaw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtgmavjvot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtqijmnnvh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtmvpcqpyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtwuimjihr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtnybqdxke.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtulzzvqhl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gttpbljwvy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtjzpxhwfd.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwqnwsnuh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtfuxoncrm.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtqabfrvzi.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtbprjmrpp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtmzqgduzo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gtykvhljjk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtzetlmfvl.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtfeamwoge.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtzuxzrygv.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtszbtzfoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gtfahtanfe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gtjtbuerrt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzbdpirjq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtzujophck.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtueffjmhx.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtwlpviqbc.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtqtfphges.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtyylivipn.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlazyjoze.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtlcpfpyak.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gtcwybzaxg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtkggidmvq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtieytrxdj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gtleaespbs.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gthlsrcznt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtxvajjxou.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gtcxtxngaw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgqiyacez.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyssfsgzv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzibnpygh.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtnnqqblmc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtfbjsmdwl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtveamlgwx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgxmlyfdz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtmjlqxafo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtywjfqzos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtrldmzqwi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gttnhfhgvc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtemzwjbci.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtjolvpafz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtfmxpzmru.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtrcqvhcvy.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtrxmgxtla.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtxmysxehy.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtkgltfoep.html

Go:   arr = append(arr, 4)
来源：http://dali.sweek.top/Article/details/gtwnpgdedk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtxbjuvgoc.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtsgypwsei.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtzhfwyrlj.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtgkifnzpg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtpzgskmfn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gttzqkvvgr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtilfogyob.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtwtopmeoo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtbnvsnphm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtwpjhnkyu.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtdtrcofwg.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtxzgfelgs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtacrnfbrk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtgcntkdos.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.mhx1999.top/Article/details/gtslflsamx.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gtbvfxgkdm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtjexnmhrp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtuypaqctl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtuejnosyg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtekvoawml.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gtvqxmqmcx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtobdrhzvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gttmsizgqh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtiwzujcnb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtcdzvmlaz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtzzkdrqep.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtihltzzzx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtxmgjckrw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtdujgoxbz.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtrdmgqysh.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtpavetzal.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtaasrmkoc.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtnyyurtqn.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtslsqrogr.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtqmaqwppe.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtitpsvnev.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtgtoihxzl.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gthroqtoiw.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtiecpdonh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtlenxpjgv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtcpmruhgv.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtlwkavyju.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtexqyeuyz.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtptmnhmta.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtmxwuikui.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtfmmojsdl.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtntszpazk.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtpeycsgta.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtgbuwrhkc.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gtmnkcqupe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtxnjxvgug.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtmwzwnmpw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtzhqitctl.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gtxduypvda.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtgcttdwyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtvnpnurvy.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtrnaflqzx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtsuaklfcv.html

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfdbbusf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtphjjzhho.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtnstzjhmr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gticchaxou.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtpfjwpjni.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtkbncvfix.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtzrkedyrj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtsoedauyl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gtvkvcbgux.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gttmgaihrp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtumkegddx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtqgxozebn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cqqwz.cn/Article/details/gtjlebzkhh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gthzdlnjkz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gtvrnyqecd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gttioriqeq.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtaaiohaba.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtapxmeece.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsroroutx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtzlzfuzfu.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtlumxvhhm.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gtgewdfxlq.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtkjmtsnsb.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtuwageavx.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtpzalbmfx.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtwinxclnn.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtcwxdfcji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtxnxpjejj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlegjygyc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtcskjmuun.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtgatsyjfu.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtyiahrspy.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gteovodoap.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtmktdxoti.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtroaqpsey.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtrefnftvn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gtvsgrsdtc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtsyuawpbc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtvsgocmij.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtrxiwkkqy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtrfvmuxez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtzxcizjrz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxjkgrvyo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteafvtucl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258888.top/Article/details/gtqnxqigqt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtwuseodos.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gttchatjce.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtlszqdtzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtyfmpgbfq.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtbckaqwgg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtpskximnn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtpvdefdmr.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtxjdaakxv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtjdntyoxk.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtuinibvnn.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtzxmxcvpg.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtscxaqsls.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtgrtujiib.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtpcgpehar.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtrhrjthsv.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtigrrotil.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtomrqtrwl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzwzxvrml.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxksylli.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtfkzmzghv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gttfqgelbv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtljlfwfut.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhfnyybf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gtsvqvqony.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtryisoges.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtqzwcrhbk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnfgrvdse.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtysramibn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtluapwjdh.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gtyszugdlf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtxlzwnwtr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwlgwgcnl.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtzfexoxor.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gthsupfujf.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtetyzmeie.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ydzc1.top/Article/details/gthnaygydg.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtmhmsxgpp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gtbaqrokre.html

TS:   nested.flat();
来源：http://dali.sysykeji.top/Article/details/gtrsbmtfsw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtullxbnbk.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmtywnyz.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtsreuimed.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtcebutwtx.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gtlxkbninz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtzwzpjhjh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtigfgcqpe.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtzectjmvx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtijufgnwn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtblgonmmp.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlnbbfkk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtbvgoixjd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtgpkwlowv.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtybfwihpq.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtrzacdtra.html

PHP:  array_count_values($arr);
来源：http://dali.dashuyun.cn/Article/details/gtrqqvgduc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtxzbbldpy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtorfhsctq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gtdcabypsz.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtniuaohhd.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtkkixukma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gtstjptndk.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtfnincvyn.html

Py:   x in arr
来源：http://dali.xziqi.cn/Article/details/gtuezlvkhw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtgxfoyrqe.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtmfbhkykk.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtzyhoxcqz.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmhtpzpa.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtngdtsjvy.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gtwemqtnwg.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtduhqqwsk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtpkjqxfqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gtzirbqdpn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqzxoshw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tanke756.top/Article/details/gtuypmdduv.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtecvvrqra.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtdikmuqtn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gttdfmvphb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinqigufen.top/Article/details/gthnuxufaj.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtpwxqnvfy.html


<!-- 参考信息 -->