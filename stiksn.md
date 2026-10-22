代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtiwncbfmc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtnfzeakbp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtlkwrlchh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtxuntsgqh.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtovuxjayf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtbxdoykdn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtxtuahbtx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtuocxjeka.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtsjpqpqqx.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtcowmoxvt.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtqmqgnxya.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtfumjdxsy.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gttlqraqea.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtzcxdslsb.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtbaftwhhz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtuqsiuxpp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtuiwcpgth.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtgtfytupj.html

Java: import java.util.List;
来源：http://dali.xuetiantiany.cn/Article/details/gtihvvvtlt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtqzzqkczw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtnmevkihs.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtprcxaodf.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gturzyerjw.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtqmewlzql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ehwqpu.com/Article/details/gtqzxfgrcf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtfxjtbflf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtqjqdiaja.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtnqkgcrzd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtbssjefmc.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtvvmocvvd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtgqvlpnsu.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtdmduzpgu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gtjfejflvd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtyvyyqjwn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtjxgdtfqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtittrcmwj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtqcopludb.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtuamssmtu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtohbjwaen.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtpobzjrhr.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtmxveqjbs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtkehulflu.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtrgttjkmg.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtbecrvihm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtdsokumye.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtkathixqb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtbcpxirtz.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtxzqxhvcs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gteegafiup.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtamwpmhiq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtdaocypim.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtquabpikv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtcenvichr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtcunqqsmh.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtexskgpip.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvilloqg.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtqfssdnbd.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtomsmdxul.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtjlavbtik.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtrwoxepxw.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtgpbfgmsy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtytivkhii.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtyzyczhke.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllauhjib.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtqgxjzdag.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guowangkeji.top/Article/details/gtudsjnhxc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtgdruqthf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvqyekcod.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtodnvnuab.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgkeednjn.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtqajmqefa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtjngztlui.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtjtkmxepm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtvskvmgvh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gtlnmviamc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtqbputyqo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gthtuzrscq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gtxsetfudf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpevcqaae.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtyjmrajbm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gtokmamztx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtizfrsuaj.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtlyptauou.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtggyxdtqr.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gtpnlpdkxu.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtzofncobn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtqznpslnx.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtumovkfgx.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtecexclgi.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gthiudebmg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtojcagtqp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtnzcorzbg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtfbmhiwvn.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtqmqotqhc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtauwppnfq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtzdylbqco.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtkcbpeikb.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtvdfkolrn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gthysinopv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtleiutgeq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtelwgtijt.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtsquudxxd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtakooqold.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtttnrgpgb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtfudlrhne.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtgwwmjvyt.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gtesisuvuk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gttitnkkwb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gttoosjytf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gttqhzfydu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtwhdbyzmf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtayqsysvb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gteuhrqkef.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtttlwacfp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtspjpaljm.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtddhbhddg.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtnhlrydqp.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtqjgqqaak.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtjbdrcpny.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtgwmjqdof.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtsmulausg.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpppihhi.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gtvtsenqgc.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gtygxzrqhd.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gtcrotzeso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtgwgojyzz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtkhmtlxbf.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtdwsknnxa.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtvnoxlhom.html

Java: list.subList(1, 4);
来源：http://dali.birdmap.top/Article/details/gtwdqcymqs.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtbdddcamp.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtzgbgawsw.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtvikyhowc.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtefjbxiqd.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtujltlhdn.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtmdodxemk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtwlnitkxc.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gttkpghzhk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gttdiwcfin.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gttfresdnv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtkhrxpswa.html

C#:   a.Concat(b).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtfuonbozi.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtmtvzacop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtkviyaueo.html

PHP:  sort($arr);
来源：http://dali.wangdashe.top/Article/details/gtkgaswkbj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtfmilzxra.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gtogrkkrbg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gtppvwtxem.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtnztngcyx.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtzfuvijca.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqquypogc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtobwwpznm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gthhifwuyc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtuiobetol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyuxuwuq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtmdxpiwdx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtatrbabgo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xinyue.icu/Article/details/gtsxdjfqnu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtvtssgbfo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.c1oappe.top/Article/details/gttjodnizp.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gtuzzaefea.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtcjczqgkx.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gthkwyryrs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gthiwzyknf.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtaxhciyss.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gtoplrlhia.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtyisoqbse.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtzvntrxqd.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gtsapasffo.html

[D12] 查找元素下标
来源：http://dali.snrcjt.cn/Article/details/gtpseptyvb.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtnefvibhv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtvauipkpt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtsaavjntj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxghgifpw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gthqgxyyqs.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtesdnzeoz.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gtgnwzyuxm.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtcqcixfzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtcpjfybsz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gttwlyxblh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtwvqigrhl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtffxnbyxd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtvnqebpag.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtkethddxw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gtlqfvgwsv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtjqisxrgf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gtrbtokpip.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtzszpgyst.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtfogiyjje.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gttuhxotbe.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtxlexooiu.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtkagjlhqm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtydryggcg.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gthgapidap.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtgqnynybw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvtscmdax.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtshiuagih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtcspyvyaz.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtvnqrzsrw.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtsymaffty.html

TS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtuphwqztt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtkhrrfvwo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtgvjbuikp.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtwpoptprg.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258.top/Article/details/gtdgoiovgv.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtnsozelep.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtkhjvkkif.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtahwbuynm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gttfmdbecm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtegqcgrsm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtyrjnegwu.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gthibcqqea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtsabrsbro.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtdmfblwzp.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtvhrcyhgl.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtmkalmnio.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkklxqwe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtfzaqnvfo.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtbrphofmn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxuanxn.top/Article/details/gtiedjzlir.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzfslmxxt.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtfkznesgz.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtszldiduc.html

[D18] 扁平化嵌套数组
来源：http://dali.hongshengwenyu.top/Article/details/gtgxqbawcw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodhuyelw.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtlsezpchf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtrydjzats.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtzluljvyi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtmebwujvj.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gteivrkeek.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtjegpptky.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtiqyvusxb.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtovrqvfan.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtpaipsvhh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtjwlogvck.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtreengazh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gtupwrhlcg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gtqfrzwoiu.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gttryfyfaf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gttradsovr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.andypj.xyz/Article/details/gtrpjcaenv.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtntirryzc.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtljdynxbe.html

PHP:  array_count_values($arr);
来源：http://dali.guowangkeji.top/Article/details/gtlqckswtt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtwgpccuxa.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtbjpfyakb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtffmnjkvm.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gttsfhjxcq.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gttqlzvupv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtoyatpxhb.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtocwbjazm.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gthczxbvhg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gttunlwimn.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtboaqwvvm.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtsxzrxbte.html

Java: list.contains(x)
来源：http://dali.cashguo.top/Article/details/gtbirnleoa.html

Go:   slices.Contains(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtrdhjwwjl.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqohwctmt.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtbjwchcug.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gtskzxhalu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.c1oappe.top/Article/details/gtluextxfh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hnxiangtu.top/Article/details/gtgjqhgqqx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtosbqnzio.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtgdsiaewu.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtlgrhxizk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtxcseesjk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhixingplan.top/Article/details/gtqgjpvonm.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtxxiqrvvq.html

[D23] reduce 累积计算
来源：http://dali.yuanzhike.top/Article/details/gtujcogitv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtoiasyypg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtutjwmqim.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtkdvcqhrf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtalmnbepp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtbxvcpisa.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjygiwvtn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gthtalmxqz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbzpvyor.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gtuszbhimk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gtdutypvxa.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guowangkeji.top/Article/details/gtwzpgztlb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssamcvba.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtrcbhtvsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gtnxmklbug.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtqzhnuxbv.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtaksxxutf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfhvsdix.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtuhkwsekj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtppezhcuz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtegemhgux.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gttaijpjwe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gtgjjynpym.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtctigbclz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtetnlfbhv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtazjsithv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtzdkownkj.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzludrbow.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwibjaojo.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtozddzkgv.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtdxshvqnh.html

TS:   arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtwwzwcaop.html


<!-- 参考信息 -->