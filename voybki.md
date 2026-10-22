代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtqxtwoiru.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtdrmxgzmb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtuiffgfya.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtfvhojhnp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtrnofpzah.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtvltmkpha.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtfqcqmffp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvgzbcif.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtxnqzdgvi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtmeobftee.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtkywcxlae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtmrjwsjwc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtlynkhezc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gtspxfkwga.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtfpdzsoly.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtjnpixodf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gttjmuyabi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtkbtlhkiv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtuejwmdvo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtkgxnrpwp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtyxcbkkbg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtuficllvd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtdnbielhc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtjoegzgpc.html

[C10] 变量作用域
来源：http://dali.jiagoushi.top/Article/details/gtlvbvsiac.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtgndknqgp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gtenqmubjf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtwhsibqbd.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtzpuudtlm.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcdjadin.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtyvbidlzd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujevixdp.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtuoiwbmus.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gtsxdniuel.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtmwliikki.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gtooogdyzg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtuhqaxavn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtcwpeqhub.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtfxsnfifx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtvkvvpioe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtgybezhgm.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvxgvgvc.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtjekyqqaa.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gtgtecopmc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtojwxjppo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtmpujakdp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtwujnamwo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtbicxehjh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtavthlcjq.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtjqfxqlzm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtddmsgcbk.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtvhcputqw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtyduffbwg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjainhegq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gtyxozfbfc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtveckdtkb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtxpdzavwx.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gttoicknpl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gtfopxscje.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gthnzjuemb.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gtxipjvpry.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtmfdvjjxj.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtxaetcash.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtrtldoqjr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfthxuvh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtgplordmu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtzrfencvl.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtlkvgathk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtoppkgodl.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gttcbhcjfa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtcetkmikm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gthjgmhnoi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnovzkiji.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtrartxddq.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtfhxyhwdx.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtkmqramcu.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtxrbfgexo.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtivrxgxix.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtmrobdtkz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.c1oappe.top/Article/details/gtyrwjaspg.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gtnpvlrvez.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gthnbixcdx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtwqfrcocf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtmpqslwim.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtvckzehlj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gteagqbmag.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtfupeuhwx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqlxyxvyf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtyjagxuoa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwepxllez.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtwwkglytm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtskeyakfq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtvufwvbzu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtfiietwtg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtfobgcirt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtsvmyakys.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gteupsbmro.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtkyptddxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtsazsjupg.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gtdnazovin.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gthvofodpg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtqbtfnuec.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtgapifmhm.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtfetwpftr.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqycncxm.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gthhcwcikc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gthzhgkgta.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtmyckphxa.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtozjvkgrp.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gttutceoxc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gthtdumhvq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtsisbwvib.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtzengnpxf.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtoaidnqnp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtiwpicnfg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtzbvhhjwd.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtftezvivy.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtrrauxvnm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtzxskaxza.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtjxzaurpx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtjvraodpd.html

TS:   arr.splice(0, 1);
来源：http://dali.cheryme.top/Article/details/gtlusqjypq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtqypooleo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtqrhqkqjc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtsawcseso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtudzmdnps.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gtyqnvjgcm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gteleubzpf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtmrqxohna.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtjtdlnqqg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtnstbpntl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gthrsnojnt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtksxwwgxv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gttimniqcc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtmqnqizoc.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gttkecoqml.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gthaopdxry.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtmckuhaar.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtpjsyrvwd.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtoxnmhvtl.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtzclipafk.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtatfdfivy.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtsnyevypn.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtisnaamsq.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gtllcgeakt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtiqpowafp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtqxmusxrl.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtyxrkvvhj.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtrzhtnwxr.html

Java: list.subList(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtxxzbrlhf.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtpuhiwfln.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtsubcaero.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtiwandeel.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtmnampleg.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtnourothj.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtafxtwggl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtyepzjoti.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtcxteomcj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtpzihivom.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtehqeorgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtfvjrmlcc.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtfuyaulay.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtwywanthm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtkgcrlyce.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtvykyufxl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gthycfklum.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtuijiggyt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtcgjlijcy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtiscsovlb.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gthzqydlne.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtliuilcxt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtyiyedjcl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwflhrga.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtgiugacox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gthvsikpzh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtskcarzhe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtijsclwol.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtqnjmihut.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gteiyamcaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtemqmjngz.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtffvczygo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtqcbmpkqr.html

PHP:  array_reverse($arr);
来源：http://dali.sweek.top/Article/details/gtqelggegp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtllvvrgis.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gtzoyltwob.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtkkktgddp.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtfbqptopx.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtpzklqavh.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtbsoopuhd.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtexuhgmtx.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtkfrjzrxk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtyblozmdb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwngishlw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtigoxbbyx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtouvpatof.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtgjuzqdaz.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdijexlwt.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtjgdebjgu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtwafhkxmk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gttpffiejo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtebrfezxi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtxzvxaemy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtawohsvnz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtjbznpogb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtmogwjgcx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwvryfyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtgkpykslf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtkzwvrjqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gtdhdcrjwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtczampnet.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtxzpkzsfc.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtlwvtnttr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gtkfinvwkd.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtvxwbnayp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtotwnujnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtvxupknvz.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gtdrjlabqy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gtqqlpygyd.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzoceqzfk.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtuzgodbsd.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gttlwqtgzj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xziqi.cn/Article/details/gthungducc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtjhhrhthd.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtfcqlxpur.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtagaralco.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtufwgqwsd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvceefvzf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtvqdoivhs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtysedxgqo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtpgwzyvee.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjjxjspa.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtuhfymrgk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gtmkjqaryl.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypqfeadb.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtdounomjw.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtfrvgvbrj.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtflnqpuda.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtkvtcnglw.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtovxwqwdp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtmvdrieid.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtaxqfavqc.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtycvmnqwe.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmismcul.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gttavdhrmu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtiyercwbb.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsdtviqw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gtzexfgkqe.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gtzddvxuqt.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gtlxiwcefh.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffzywrqb.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gtoaxaeehy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtfgwqcoiy.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtvuqxgvwh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnmaygxqy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gttvmdiymg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gtctqqirka.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gteoodyjbs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtdwbewvzu.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gthguuqcpn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtqwpwwgqp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtwvlpwsdf.html

[D20] 统计每个元素出现次数
来源：http://dali.hammf.cn/Article/details/gtyxaieovn.html

Py:   Counter(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtxjbbmdyd.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gtksnovwrs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gthjcgmsmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtwbprzcet.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtmfmurkae.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtwzxmbova.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqxtkacp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gtoqwgktqr.html

[D21] 判断是否包含某元素
来源：http://dali.cheryme.top/Article/details/gtagdwiokq.html

Py:   x in arr
来源：http://dali.zdqjudy.top/Article/details/gtgamnrvfx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalvxxywb.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtedggcwyl.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezkjfsuy.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtwvzvsmdx.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtzumvekpj.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtmpurllxw.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtuneztdiz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolwxvhso.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkorqflog.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgufenzy.top/Article/details/gtzfstmblv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtaqpjknlt.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtnzacghya.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtrsnpbvzw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtqkkemajl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtzqigfxji.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtwdniohlz.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtjxggzift.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtiaweycuk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.smart0.xyz/Article/details/gtrxsujhrn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtkjfdwmpx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtwewneaxj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gtyamkbufo.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtawxcccoq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtsmlgadfm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtqyissojx.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtfcwssjmq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtkuddbgdx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtshfwdtjt.html


<!-- 参考信息 -->