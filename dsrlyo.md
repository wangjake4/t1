代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtqxkiqedt.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtdcjhnlcg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gteiihnrms.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtyqxxcmbu.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gtfpfoseee.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gtfzuhjpnr.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gttenhdfif.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtgygttypy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtypdehjog.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtqclfpimc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtdkzvjkdh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtlbfaynbj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtgahbwvkk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvtyzxem.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtkcfygspv.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtvqxoxysa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtgkjpxigv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtgvtxlwht.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gttsyhxdhk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtrfijwtkf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shuidangran.top/Article/details/gttlxcdtab.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtrholshjc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlyapjlc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtfsfqsous.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gtwhdvqlzm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtikymglqs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gtldtfjszl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuraauav.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtusqbisgx.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmzxlzwt.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtlwbiesix.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtqzzfrkii.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtgeudwxjl.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtgoqyhtkf.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtxcvickei.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtwqzwnfdc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtxgafpygb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gttosvlqbo.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gtevbcsadf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtbwxxylaa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtdgngqonu.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtnavtqobx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtalmmwsoe.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtgwbvecfq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtwikvrvms.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gthynhtvix.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtczszttpp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxinkj.top/Article/details/gturdaghzm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtfyjryihx.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtkfeihfzh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtajgluvpo.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtzpsnhdbq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtbuuioxsp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtvpeacywt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtrumckxax.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtwfpluodw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtiopwhudb.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtrkbdrdug.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtomyxdyjt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtixfiboac.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtchrqmqny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtynxwpfil.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gthlppqtjb.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gthmeedpmh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtvnthpgzo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtkwvcgxzr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtomlwsvcb.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtgqvpakfe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtokylwgqf.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtflfectrf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gtciwqkvca.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gttoqrwowl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtzltrbbty.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfkztwhxj.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtillikccs.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtpdmbpckb.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtieegwsay.html

C#:   var (a, b) = pair;
来源：http://dali.ppjwa.cn/Article/details/gtleizsqny.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtoxzabbic.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtazbqsxmn.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gtakrxklsl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.feifeiyinyue.top/Article/details/gtjodtmpfs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtirteousv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtjhenryfl.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtfazmiuyk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtujbkzppf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbliwdeqg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqbrnxhph.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtfkpweswv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfhlvokge.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtemdujydq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtzxxyyzvb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtnqaqvymj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gttobolkld.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtlezcljeh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtyryyqxmz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtvweoxhwe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtvaonbqim.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtqporzfxe.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtlbdnggdf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtcjawvmgi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtbgqrvdlo.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtagxstusf.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtfpowvknt.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtzehzavso.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gtfwqppecr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtcqbhnjca.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtomsseqre.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gttvjxvpqx.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gturuxqqpe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtgameitwq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gttlpfroiz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtklwlrkbc.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtdwbksnjz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtfccmzltk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtwjqzownn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gthdxdmfmj.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gthgsffamd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtdaftorfo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtykzpjhmx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmlpqpki.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gtmcihzzvb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtspyggvtf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gttvlthnux.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtclfvjqcb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtsispdiqo.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtarwkfqzf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtlgsmucyq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtxuqhtdqi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtkjxbuldl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtjcmubicj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtiydulgfu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtogxxpyaz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtzqfpslfh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtlipkgaxf.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtsabszpeh.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowgiekkz.html

PHP:  count($arr);
来源：http://dali.dianchejie.cn/Article/details/gthjxiujbn.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtapurttcu.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtltqpifiq.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtezfppmlo.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtvepakgvi.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtsvzwonlh.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtycffpqhm.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtuhvlmrwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtmnixkjex.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtmnbcbtpy.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtpsskdvji.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gttijssnii.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtqizaftsx.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtcfcwrxqd.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtrjuwoyux.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtccopmsdm.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtqsxryhtw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtlkosqcya.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gthavgrbki.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtyvuiazto.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtfriogboe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gttiahnoxl.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtawbdhjha.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtjunoxtyq.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtzpmbnwtl.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtmmtcpzpw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtnyjqzfgi.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtbvsxqmvi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtywgeoqbr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtujmzxatz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtdafqtopd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtdenaawlq.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtnehninjs.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtjlaocprj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gtedwikmpx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gtiaihlsxi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtopfasdju.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtkeijoebm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtpqleaxtt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtekwgmgwm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gttwdxissd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtrzdxdevw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gtnuxufghc.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtsspnqjlx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtnyqmfgvc.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtmixwpdob.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtzuyjdqil.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtvxevlzft.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtejfddtur.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gteylbihij.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gthqcmafoq.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtmuomijnc.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtqpqfsost.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gthpfndpfk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gtnoqrscth.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnunbnzem.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gttkfegezz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gtbvcsurkg.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtzhvaerda.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtupernpkm.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtklcjodmd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtvduoxmej.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtghwifqcx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yongpay.top/Article/details/gtujchyljx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtkimozsye.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtnjwxbaei.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtdjnifsog.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtfptrxtng.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gttleksnfi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhwswgxh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtiruzwspf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmouqqtiq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gthrtiiiiy.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcpsnwiio.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtuemekcvr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuxming.cn/Article/details/gtrgdysgda.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtywunjebv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtgxcgzlvb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcxjjlwb.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtiiawqhbt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtiqvnebyj.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtxkrtjumg.html

JS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtfcgadgma.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gttzkntuuj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtsmmjidqn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtulsxifnr.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtnxcpcays.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtnquagjbu.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtpslcuqee.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtcnxndbtw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gtabelsezd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtqwafquid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtqbpexmoo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtgmwrxyuc.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtfcbheznh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtxwfwcddi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtptudkjtr.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtxuwqamxn.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjsfxyqjk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtveuhejhm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtexkimfvz.html

TS:   Math.max(...arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtlyamedcr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtvpokhhts.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtldhhdvis.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtrdhwgmvq.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtghcjunrx.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtystwqtbf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gttntjtriw.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gtsvpzrild.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gtnbpdwpgm.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtggdcihip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtspamfxec.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gttbtacvic.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtcauvqgaz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtupzgovhn.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtobioxzbd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmegzugr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosbpmhoa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gttdwxooev.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhbsnvji.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gtemxywwva.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtirbpqmgl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtkhyuysth.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtqsehyquw.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgswxass.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbjeemgxr.html

PHP:  array_count_values($arr);
来源：http://dali.birdmap.top/Article/details/gtmpdaugwi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtexvomuot.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtyebhsffi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgyofiqi.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtmnslqaba.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtwpsqyswc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtykocbbup.html

[D21] 判断是否包含某元素
来源：http://dali.hnqzz.top/Article/details/gttenuuqbk.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtiberrpet.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gthmiooxwa.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtlobtrppu.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtpftgdoyu.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gtgxpmsumu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmwgqwqtq.html

Ruby: arr.include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtagsgxwif.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gttgmfhfdp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtfpzgitic.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gtkfxnmnti.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtrvskrocz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtovnzlwph.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gttmzxvgur.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtecpcojsi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gtrygqccwd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jianghu66.top/Article/details/gtxijymood.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtzamripgp.html

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtkvumlafg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtwpvdbvag.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtjuqgeaon.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtszlcmvhk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gthnltsqdv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gtliakkdtz.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtwgxofzib.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtnbabfpxx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtizlstznl.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtephndufx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtabylngoj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtvfgxsgwl.html


<!-- 参考信息 -->