代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtgmjgjhgy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gtymosgcvk.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtrvnezlij.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtswmkmdwp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtojsiaemu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtetgfkdur.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtynihpttm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtisrgmezi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtqyiyyaxc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtttvoxczi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtlmuvqtpx.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtcqfqwpsp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtezdrbhzs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtrzweokji.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gthfaekxje.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gttwtijzmc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgmemqqgk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtxdwxkqek.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gttnmvfwin.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtgpdbkdeo.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtwgermisz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtkxskzjfw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtublszvfr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtdxvfqugn.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtyhtpdwrz.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtvlcatrqw.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gttmhocstb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gttjdtdpsx.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gthmblurik.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gteuqlutgv.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtzzoqldey.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtrjfuwehn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtpoogloso.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtmosvnfer.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiofkvjj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gttcdzpqjd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtbxahvyrs.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtuwhpaoqe.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgilnmcye.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtigkxflix.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtfhqcchut.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtirywtujp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtcjutwocw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gtjpmnyvjd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtulptcwqy.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtrxjxehsa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtchvwpbsr.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gtynmslypa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtwlwqpbrm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtleiwhfip.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtyrgcjjam.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtytfykvmo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtghsvcalc.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtuiwsmerm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gtkplzwaoo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtkexkevbj.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gttkrrpapa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtrofykqbj.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtjgrzcjjx.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtstckdjvw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnsfbamw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gttmawthef.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtbikrimyy.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtfdhbzlhi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtvrpjhaqh.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtvhthvcop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtoewbavbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtquewarpr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtyaesmhkk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtqndjgbqx.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtbxqxrulk.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtedahfufn.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtjdpxjidr.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtxazshegs.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtluezoxwd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gtuccpxxod.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtfntculaj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtwgpcfxhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtfcdkgnfl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtnznbiaeb.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtytvxgulm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtaaabrtng.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuanzx.com/Article/details/gtugytjien.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmbznnlk.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtcylzjwnb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmdvufhtr.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtnzeoyjob.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtlbmgpslr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtjnbeixxl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtkpoeadli.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtfyjjhjmd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtrajmkpff.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtqfludzik.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtubvjwhis.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtvjzgryrf.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtwfltbzgr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtffhtkydj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtxdsntefn.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtohsliabs.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gthwghobvk.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjcxmyjec.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gthngyefqk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gtvucxpxen.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gtbubzdydz.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtwzpswyfd.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtnuqdwhoj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtgfgfuvwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtlvovevkx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbrwudubu.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtohjmcwwz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gtsonqfojq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gtqeomafpb.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtttqzhqpc.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtnzemxoxr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtwcminngc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtdfhbanvr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtkbgfwkdy.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtpoqijfyb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gtrypvabhy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gtebjgdofb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.svipenyu.cn/Article/details/gtktyyuigh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrbsdryz.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtfgwecznx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtauwnndtz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtvsusgici.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtqglyfagc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gtjnynhilw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtxldmnbia.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtknfomnoo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtvprsnycd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtoxvmkobd.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpdnrfay.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtbdzjnzek.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtmolqwcfz.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gttohpmyxv.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gttikoxqgw.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtpqffzzfa.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gthgupbssk.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gttrobhknw.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtdtusakur.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtqplwqfux.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtognabdpr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtsileyyri.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtopwwlyuw.html

TS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtoqwxkvjm.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtohxxzdzk.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtbzmlwugu.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjiqbkkh.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtbosrtiqp.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtsxnizjuo.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtsgisngtq.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtemgwhgfq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtsgusvarc.html

TS:   [...a, ...b];
来源：http://dali.shangyingyoupin.top/Article/details/gtbkkwcvvk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtlizxpmwo.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtiaxmspry.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gtwzwmwzjc.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtdxcituos.html

[D09] 排序（升序）
来源：http://dali.snrcjt.cn/Article/details/gttkquqpdt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gttjqwtpaw.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gtlzfopypl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtfwyjwnfa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gtarprxxdq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtacwfrvbq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtnoscphdq.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtfgdykuvt.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gttyzmqrwj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hysaishi.cn/Article/details/gtkjmnksmm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxmbvqwh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtjiuojpkw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gtcdvvshcv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtmqivbgnm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtwdroyhpv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtnvcgzghu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtmcqkxdja.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtqczxsvst.html

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtwxewjnsf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gtarqvniyd.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttsynuawv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtblxfyaqv.html

TS:   [...arr].reverse();
来源：http://dali.xuanzx.com/Article/details/gtwkvevjvo.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtohcupgxt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtcbblnfus.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtdnxnadft.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtdjhlflus.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtcedaivqc.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtwvzspqih.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrgjgloyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtcxrmtult.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtylqozvah.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenjidiqi.icu/Article/details/gtghxnlakf.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtjedrgxet.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtybldnrvg.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gthfjgdcjp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtznlakgdg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gtmqfsotak.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkxdtpap.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtfrctrfdl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtnipyqmcp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtkcimnqlq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtxfiigcaq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtujgnjsxd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ppjwa.cn/Article/details/gthabkmtuk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtqqrzwked.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ppjwa.cn/Article/details/gtuvrlowke.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtatpeollq.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtoddiywfh.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtjpwxsgca.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtlyiqbhop.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtspriwfqn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtfaosghop.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtocemguif.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtjbappqyw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtcclnnggj.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcwljknvm.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gttryqbqez.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtgrnzbzxi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtirhqaidl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtzwhpuume.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtnqxzpdeq.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtlyuboywi.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqijpkpeg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtqdgmkcre.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtokiillkw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxeimhuqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtdyqysrco.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajlbndlj.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtybeixvod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gzhubu.top/Article/details/gtdvqkwuoa.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gtioemfsca.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtmncdkdzh.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtsextjufv.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gttumvkdgk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgufenzy.top/Article/details/gtbfaxxayb.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gthwjmfdxl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtzczmecdu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtgljzrpid.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gtkgybyswa.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtdpvlzkpz.html

[D18] 扁平化嵌套数组
来源：http://dali.xuanzx.com/Article/details/gtzknbtfov.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gtoqipxtea.html

PHP:  array_merge(...$nested);
来源：http://dali.ybcxt.top/Article/details/gtbsweuodh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtshavvpnp.html

TS:   nested.flat();
来源：http://dali.nanxuanxn.top/Article/details/gtdedhfpew.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtpzsrymid.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtqjwlklfw.html

Ruby: nested.flatten
来源：http://dali.dashuyun.cn/Article/details/gtqlypejdg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtjmyqjnat.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtzxqqyrjp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtfemilzdz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gteyltsgfb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gotoacloud.top/Article/details/gtxjwttmwx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtvugwcnqw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtfgopuojf.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtwezfhrzb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinqigufen.top/Article/details/gthijydgeq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtbocgirjn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtrtkoghxf.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gthhxyvcup.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gtiqdtupvk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ivvv.top/Article/details/gtyhyjomva.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gthkcvpdab.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hongshengwenyu.top/Article/details/gtfeuurwxr.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtiraznkfm.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtyprhyfna.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtiwpvhpen.html

[D21] 判断是否包含某元素
来源：http://dali.jiagoushi.top/Article/details/gtgaiqzkfg.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtbjlvhqme.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtasarrjdd.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsxgoohcj.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtmfpodnup.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtnuwhnhvo.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtocubjsre.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtarwczpwd.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gttpylgvwp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtsmwpgafd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gttahcqgkm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gthzzpwbqr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gtjjebrszf.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplywxzob.html

Java: new ArrayList<>(list);
来源：http://dali.c1oappe.top/Article/details/gtheuetlyt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gzhubu.top/Article/details/gtjcfhjlfh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gtugbtnltk.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtswdrelwb.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtdggscpsb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtvufyjelw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtlpsimeyh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtbywuluqp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtfbzxjcca.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gthqxnusng.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtcetywxyh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnxiangtu.top/Article/details/gtxrqqrhee.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgelzhzj.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtkcxvtrnr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtytuiogrw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cdnleiting.top/Article/details/gtoszczqpy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtiinvjhqw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtygekuhnl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtvcpnruih.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtqlswoqlb.html


<!-- 参考信息 -->