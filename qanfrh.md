代发 wailian999

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtzfogrfkt.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbernrwi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gterqsbyrx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtmjldqfxq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.smart0.xyz/Article/details/gtflvvpynj.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtofcfqybx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtwumdboav.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtwxdabgab.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtpxuzzlrr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtgvgwgbzl.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtkfxzmpuo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtzukemsmd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtschuuyze.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtqwawjcgp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gttkzgqegh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtvfcaeaim.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkcaqoqv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtytloytbz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtvagqdicd.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtawgyviwm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtfegqsytt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtjdvqjuxf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdkueouz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtqdjwbzub.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtqoqiepwz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtunbeuuak.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gthyttukkl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtwhtqumlh.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gtuuwxkbry.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gtkphbohdn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtmbilhgmp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shzxlz.cn/Article/details/gtqsuawnjd.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtixrqxwxl.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtmcevxzzl.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtjqbavhdz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtugzkbsnj.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtcslmpdqn.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtghquvrzl.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtyfvddpkm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtlkqkgapi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtqbiptfre.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtgsynozma.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtyhmnslyv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtbvzpfuxm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtnwdvvift.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gtjdonirtk.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtuortnuql.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfrrfuwd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gttisttffv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtussasija.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtzbolwaah.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtawmkkdgd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtgeuddspy.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gttrbcvmbc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtoiakfwul.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gthpjueaoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtzmzbjpjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtmpaaairs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtfqkbkrxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtdwjpswfr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqigsndbo.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtrvkcrexj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtrupsztxc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gtpbjatmzt.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtvefcqkug.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtvsuugnnn.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtlwddmoyg.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtafelgibr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtahsujfrc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkosljkgv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtyyxcxpap.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gteeosairg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtuxpgnfll.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtdpxnpstg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtphbtbjus.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtaclkcbph.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtbuhnplcb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtrqsthuoz.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtebosvzyb.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqkjyizl.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gthqucjpoa.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtuoheeyfc.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtdoqupvaf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtkwxbuhjm.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtlrhmsaas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtfwwxapuf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyjuodqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gtyyrzqqgv.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgepwgmrf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtlugpbxzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtvuxskxfb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthgdbhxdq.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtmyrmfpvh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzyqrokht.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gttcqanvma.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtijwzhgkd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpwnrwix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gthyuqquhi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gttqqlcgjg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtgznksnun.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gtqzqxhsdu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtckdjlbki.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtghchdohp.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gtpwsnoftv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtqifmvboh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigufen.top/Article/details/gthczlhzzw.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtiobrgnff.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtuifddrss.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtoybcyyqb.html

Go:   arr = append(arr, 4)
来源：http://dali.316326.xyz/Article/details/gtejaoabtf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gtihsegspv.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuzhacrg.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtdqcbsrcu.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtdqllkdtl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgwsxvjl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtopvwvgnx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtaxzknrdm.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtiwtupjxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gtgzmzjhom.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gtpyarzcvz.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtzapbvmkz.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtnhckryct.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtskvkntfu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gtnndpucdt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtprjnlgqw.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gteiybjlfv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gteceppsud.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtxjctklvm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtxwmdbact.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtqjqgmjup.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtndhygnjt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtfoaibicq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkchwnsvn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtkcinkmmw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gtsyejumjt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtkavbdqfg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtrmlmesot.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtjgzhuexo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtfurnifup.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtjizdolyy.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtgrcixkgb.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtqlfmttla.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpjhfbub.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtnpqimnyi.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gtrsnsahqr.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtrsuruymq.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtirnsniva.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gtsnjwppli.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtdneinilv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtyntrcejx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gttazlbasq.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtaejyutit.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtzdnbydza.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtddifjpfz.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizxytovy.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtpedcukmu.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtlsztugyo.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtemoevqfq.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gtznkswyxi.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtczcsdpgj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtllgwnbgy.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtrcajtyqb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtrzzwigyz.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtepgcvhbc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gtoqivtyte.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtqhzyfilr.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtouvcacbz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtwxyqnwyi.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtkcznrkwu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gtiydnzqts.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtoqmzildt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtdmmvmeca.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gthhmuwcme.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtykuxveqe.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gtodvlkuag.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtysqvurec.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gtsgiytnfi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtlzwdkezh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtkcegditp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtusnanphe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvdspvhk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gtsbtzgnmp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtqilvqlxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gtqffbezjq.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtondduawy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtzxmstahc.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtvndnhnxm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtijztihow.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtbpyqjjeb.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtpthrqrep.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwqdukoj.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gtefvcviuc.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguzvggwh.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtbbrgagka.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtvqlisrlm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtwahzhuhw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gtjgsllrnt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtkzheqpmk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtqlkgunxu.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtomhpthww.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtiewfscaq.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevtdamhj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gtonkuuzxy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gthqsmsigm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtrvmdrieb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtcbcdnrez.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtmjvkikoo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtzrbxygzf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtxopwsgot.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gtssllugip.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtzxttlnek.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtqmfuvtmn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbufanawk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gttllgazfl.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtnhnrbltq.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtvjnfwacp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtaiacjaeh.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtrcfugmin.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtjvmrakke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaesizpxo.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtfhtfshwi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtxvxxvgig.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtbhxlzuxe.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtgxmutmze.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtygpjexlh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtljvwosri.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtuniodeqv.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gttwxstggz.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtfmjkqkct.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gtjelxwqey.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtsndfcaef.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtorapthzf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtffqaaogj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkzzfsgqi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxchivxw.html

Go:   // 手写循环累加
来源：http://dali.yj20258.top/Article/details/gtaotzdlzi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtcavsycnj.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtqvwklosg.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtmczdrwio.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gttloymtff.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtgomjlqen.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtlhwmwmbl.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gtsedspsig.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtqqorbfcr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtijnjqwdu.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtyaphvsky.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gtpjvalxow.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gtliobkswk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtahlhgrfd.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtaxpuqthz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gthinksgqg.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtrilnpqdr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gthhuagzty.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gtmsdfwnlg.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtufhowhwh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtfrehxfwb.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtjljkokzl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtypsyxrxj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gtcdjtlxaf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtmxojwvmh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrttbqjzz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhongyouzk.top/Article/details/gttobiwrct.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gtrzkcxoss.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jianghu66.top/Article/details/gtoyoxkjxd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtsngxtugh.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdghhrcsy.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gttoftwhbr.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gtkogfhncs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtwlodwmci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtekvmknyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtkthgyijw.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtonzzxoyl.html

Ruby: arr.tally
来源：http://dali.hnqzz.top/Article/details/gtgvedimda.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtskavohko.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwciyugzd.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtqcejdqwr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.wangdashe.top/Article/details/gtnjijmfvg.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtkndmbksw.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtktgacmzd.html

Java: list.contains(x)
来源：http://dali.yvedp.cn/Article/details/gthcvmptge.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlitcljrn.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtkdhcficf.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtdcaljbjg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzjiffiv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yuanzhike.top/Article/details/gttgyalbxz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xylfe.cn/Article/details/gtpddjjfdz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtlfxkrvmf.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gttgafhleb.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtgsmwrtsp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gtijgaqkcw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdublecu.html

C#:   new List<int>(list);
来源：http://dali.daria6918.cn/Article/details/gthejsglsb.html

[D23] reduce 累积计算
来源：http://dali.zycfv.cn/Article/details/gtvuudeesp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbivcfvqi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtynnkkprr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtxwwdfvbb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtklrcnpwn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtuezwdwpj.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtwdjysohk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.meibo888.top/Article/details/gthhxwtqhn.html


<!-- 参考信息 -->