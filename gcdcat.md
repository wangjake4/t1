代发 wailian999

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gtvtaewjxy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtvionygzi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtjomepwnz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtyykrwmzx.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtpzcjtuix.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gtxnmperwc.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmhrubmk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtioxwveqs.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtlogihwqv.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtdaivvhze.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gteibsxrki.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtnzumpkcz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtsruzsxye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtotfnuzuu.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshivuofa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtccalelht.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtmsudzqcl.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gterdcnydn.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtmpsmriuz.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtxakorvnd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gtnrzazpcz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtthhipenq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtgaqscfhk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtnygwtlrm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gtkagquwae.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtenwrytyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gtrrcjpaww.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtpiatuoor.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtrawlojcr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkgeaizqi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtohiqvvxr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtadqcjefo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtfqjxvhso.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtznxhcdrg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtmvguhfke.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtulebqkjs.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtrwravdjr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gthopgjisq.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtlviwnzgy.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtrkcgttzk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gtbjujniix.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gtzuvaprjp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkryworkq.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtsvlgfekf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gtdvpcmeqq.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gthwtbiiwy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtitfpaywp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gthysuchnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtibplsrtz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtidifhbzt.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gttvuygmfi.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtprnqahfk.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtanbtvlsu.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gtgkbmffof.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtspdthumz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtcypzjfpr.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gtfjbpjswf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtewlygqrx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gtyghacojs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtgavxgcel.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtgzrnfplq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gttfljvaci.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtizleifvc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtthgknqso.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtdkxsqmms.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwpnvntnb.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtfpgsvfzn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gthlriguuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gturbevxef.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjlxitwa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtdhdobsxi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gtzjxamyrp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtyxraqdrt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtrutsqnnc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtvtkfcomc.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtcdojfiwe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gtmitsdfip.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtmtgepvgw.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtxjpdmiag.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmljejgpn.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqsmxrrw.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtukeqbkbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtbgsowedd.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtzjncjzid.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtcotrgqpv.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtinvloqur.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtwkfajkxd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gteizypjfd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gtkoaubocv.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtdbpzaqca.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtfpxbttzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtpcsouwsl.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtnuqoburf.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtsnfeybbk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtjlvjrfay.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxrspnzuf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtdriuvvbp.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtvuwkrupg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.havefunace.top/Article/details/gtenrpxefi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtrnfyfcnu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtqofkxlww.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtsqekrvsz.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtordxmpya.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtojmuwtii.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gttgnbakbm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtjzdhdbqn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtmalolbtc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtyektrdin.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtlattkhds.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtjyqvlgzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtnikohmju.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtggjbxwjp.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtiqozfbyl.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkfaiakzh.html

JS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtvgzsrayt.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtdbzepmnj.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gtknaxzkoi.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtihtubyrw.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtjvhfivvt.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtysjgslvi.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gtiayufpor.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gtogscwzgz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gtkxwtetuh.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtctdkcxvu.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtlbumdoyq.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtqyhqwauy.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtswjbvqik.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtjctyofmc.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtonkqcozd.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtslxsjnmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtkbmaouep.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtgmaxhabw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gtqtegfoop.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpziqbxpw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtszdrowiv.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtdmfgtrij.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gtsnpagmxh.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtvhddwliz.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtzrdrudwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtsjoelafh.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtucaqjxtp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gtjtiaplxt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtbvvsrpgp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtggjsdfsd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gthukboedb.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtombocnca.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtxuqpkuwb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.mhx1999.top/Article/details/gtsdaehldk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hywenlv.cn/Article/details/gtglrefafe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtotcjxlth.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjhuzpx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtgcighnfb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtkjqwzpbb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtcaadduxc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtfwauwlai.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtcuslxthv.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtertkvfkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gttuhtvdht.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtjxpxqaje.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtgtrajags.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtkjystwif.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtrvkrsgdi.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gtlqmjexsi.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gtrbyrbpoj.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtamvjuovq.html

[D12] 查找元素下标
来源：http://dali.ehwqpu.com/Article/details/gtftiyqdox.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuanzx.com/Article/details/gtbxpjjdcz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxlshtcf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtibdxlwax.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtssijeymg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtvvpulqqt.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtevklmpak.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtiijkydsz.html

C#:   list.IndexOf(x);
来源：http://dali.daria6918.cn/Article/details/gtujilxpnb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gtjgglryuk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtbpqvvgjg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtirqymwuo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtyddqbjha.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtyarrhorp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtpxzcspvo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeeajaaz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gtvzxzcbse.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtegsphblv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtnjesxzer.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtytozucjk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtrckixjpt.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtsohagmtg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtmfbywvlx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtmkpbaakd.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtgalnefpg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtufunfttv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkjihxime.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnkitjqd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtlydwbwmi.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtyzycrntd.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtzwzmnujk.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtrkmvaepn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtdjxsdhbk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtmypubmlk.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtqoaeijvb.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gtwrjegvox.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtphpquzpc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtcwuyxbtz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtsgabhbwh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtjsgvqrtm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtzerrkuen.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gthzlxceyy.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gtdbtdcxzu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtrsuzacjc.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevjrjoay.html

[D17] 最大值与最小值
来源：http://dali.daria6918.cn/Article/details/gtinthgnhk.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtpewpvsnu.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtihcraukp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtowsnpnak.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtaafntejg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtkdbhhxvd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jianghu66.top/Article/details/gtzitxmqmv.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtzpciqiar.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtlldkjyos.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtxlyzvijk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtjoslejub.html

PHP:  array_merge(...$nested);
来源：http://dali.andypj.xyz/Article/details/gtfiaeemts.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtjeqsutry.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtumlznjqh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gteijpjuhh.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gtbdstujvq.html

Ruby: nested.flatten
来源：http://dali.nanxuanxn.top/Article/details/gtyoczetwt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtvcufddgi.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtoueuuoma.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudrqtsuh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.andypj.xyz/Article/details/gtlgifmnnd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtkwtkqhue.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtnaqqrgcm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtrdqmtfty.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtlgvaqnmh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtttcokfud.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gthmlcrdmr.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtwrfugmyb.html

Py:   Counter(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtwalzsapd.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtsmbzgydx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtxdbqvyco.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtryyqlcgr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtyjjpwdal.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtsphwdoef.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtoiozwlfa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtoxufwtny.html

[D21] 判断是否包含某元素
来源：http://dali.chenzaomai.com/Article/details/gtcgjbcsab.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtaaikqttq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.kuanghao11.cn/Article/details/gtndbtnaov.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtpihevrai.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtckmmvoqm.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtskgahqll.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfekrmqvb.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gttngfwaaz.html

C#:   list.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtjkzqnpzg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jianghu66.top/Article/details/gtcjyfycim.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtrbwpfvlx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gthskgxthg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtotwadfdu.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gtvfnvupim.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtxmietfmq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtesjpflgf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtgljugffh.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtzgjmlqbk.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtphqanyqd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtyvcqnagy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtbypqshsa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtxxczxoft.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqfsqhix.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtsstanyfi.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtpyeageza.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gtxrlerljl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gtuhjfxqux.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnqzz.top/Article/details/gtsazzpujc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtoiqsruwv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtwfkqhsdq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtkfprjnnz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtlkhtiwmy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.c1oappe.top/Article/details/gtuhtktlcp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtgfkcjtwl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenzaomai.com/Article/details/gtlplrzofi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtjtlfzbkb.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtuaybsmac.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gthcgaqnua.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.kuanghao11.cn/Article/details/gthmfcswef.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtejhwepxw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrgfbazv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcwecvua.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtoaeqhqze.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphkxhuyf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjdrmdxlh.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtinsbsrhl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtugfqpcwe.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtihjhkayi.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtbbviylcc.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtctdaiznq.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtuqjfcvgp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gtemjafcwh.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtbwuhuibj.html

C#:   string.Join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtktpnvbcn.html


<!-- 参考信息 -->