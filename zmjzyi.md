代发 wailian999

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtbyozmlvk.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gttsuncqpr.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gttfsovfnf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtycdsrlkv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtqdfbcjdr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yongpay.top/Article/details/gtuyrhhinl.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtjylqtcix.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gteilbmfen.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtewbfgccq.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtglcvcjvi.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtlbcakbfv.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtztdkhmlg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtckjadozg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtoycvizan.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdwqinli.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtkghqnqoe.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gtbkhmeylf.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtxxuaxygy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtniabfuay.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtriexzmuk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtkphybyne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtowvpldrw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gttxpuwjiy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtghqmcour.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtkvpfysqn.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtjolxpujt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtxreshrnv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtrriysifj.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtmcfaiebt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gthrldcgko.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtechzxikf.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtnbrqsajt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtfikoccmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtatqnlutz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsopouyxb.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtiyyielew.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtvmljlcwj.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtesslgexp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gteduzqxzz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtgzvkrigo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtinkcrnzt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtyzysmzmk.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtjshgpnsb.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtquqwdbtf.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtanwyribq.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtklieulge.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtbgrhbgyj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtknpnbwlo.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gthhgbvabb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtthfbiexe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqotnvqk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtldtdhosh.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtestjovxu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtzwmlouep.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzihfvlbd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuofomlry.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtqkoiqiyr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtszssxvkc.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtouakhbkb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtgtrimftw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gteykcmjpo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtixcioxrn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtmeabudhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtorkregeq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtirrzxuhq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtmugqxbpp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gttkgfwtet.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gtgyiclrta.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtmsaxlmqq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtxfqhbkjc.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtgythjawm.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtfbvygwnt.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtduxtrrnb.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxxupcha.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gtmwmqlotn.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtsjjjkawr.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtutnsasiv.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gturydyech.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtgdtugzkd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtzqvhkfyp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrltczafq.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtfqmwpgxd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtpxjinaik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthygquney.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtokqsrpvh.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtzufqbzjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtxxafsddl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtnqbiftby.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtfgqxbkxr.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gthdpzxwxh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtljevvfqw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtbfbozfdk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleyyzvgs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtmqknaxal.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtnbheeuae.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtasfcbdyg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtduanekoi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtbrlbvsyx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwclmrrzu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gtjfqjimhh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtggoybwaa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtojuyusbb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtqtfpeuds.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtjedfnijp.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokoqffac.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtgfqwijhj.html

JS:   arr.length
来源：http://dali.sweek.top/Article/details/gtbapxdwmy.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtkmdnibdh.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gteyjecskz.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtcfqdsgls.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtpnfhivkf.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gtekpajiyl.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtorgrmazv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gttiwirxgk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtwegfksin.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtpqjqctvk.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtpvliwmws.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtnujkjyss.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpyksybg.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtqvcxngpq.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtvyvaqtvk.html

[D08] 合并两个数组
来源：http://dali.sufxvd.cn/Article/details/gtanduunhf.html

Py:   a + b;  a.extend(b)
来源：http://dali.yongpay.top/Article/details/gtockqnmbz.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtmtnlsimx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gttbrcutrj.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtdlufobix.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtwnkyszmc.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gttreqvuzu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtjcusdujl.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtcwtxliju.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtvymlzpkv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtkijdgpwa.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtpljcvxzr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtsmzssvzi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gtdfrmxism.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtbqzkploi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtefjrfhgm.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtinusthjx.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtwnpbuewv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtibnlmnnf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtoxsfiwwz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtitxcocga.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtgxnnmrsr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtixvuakbr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtunshudci.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtmieqrkix.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtojmmdeof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gtuqxokqjk.html

[D11] 反转数组
来源：http://dali.shangyingyoupin.top/Article/details/gtteuujjby.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtwlokvofi.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxfgnzwfj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtzecggncq.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtcgzunigr.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtohnmggqk.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthvnutsgw.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtswoyodet.html

C#:   list.Reverse();
来源：http://dali.xinyue.icu/Article/details/gtxsdfhovf.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtymwvcvij.html

Py:   arr.index(x);  x in arr
来源：http://dali.hysaishi.cn/Article/details/gtgrquscbf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtzjhgwgfs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtnhhznskg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtvrluorbr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtfaaimeoc.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gtngmoabsn.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gteqatssyn.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtdbqyvpuz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtjrsbxsex.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gteztfhusw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gtlnazpwhs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtvyzlywdx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtlaoovuow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gththnapdc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhixingplan.top/Article/details/gtwfgczvsf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtkrwzpkdt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtgmblrcex.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtmwmuidtz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.redwolf501.top/Article/details/gtmhjzjfip.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gtzrouttte.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gthvtyizod.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gthvvahozy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gtvokjhang.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtrpvicekd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtabvezasw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtkfjlxbpv.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtgkjbrudq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtxvdjpurx.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtgdfoxbvd.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtzfubxjpw.html

TS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtdurqizpx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtspibnblg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gtwejhjhuz.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gteuncitdf.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gttzpkeomf.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtyjgqujum.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtbumkthnb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcxmsbuzy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtjuatnmfh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtsavplkds.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikqyvktl.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtmiatclab.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtpvcnqtso.html

C#:   list.Sum();  list.Average()
来源：http://dali.yongpay.top/Article/details/gtzazrnvjg.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtvvxoibjj.html

Py:   max(arr);  min(arr)
来源：http://dali.hammf.cn/Article/details/gteerhmldc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjzbnrgdo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtcjlwuyfe.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtnskuowkm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gtbthvhonc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gturuhzkvd.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtjunxaznq.html

C#:   list.Max();  list.Min()
来源：http://dali.sufxvd.cn/Article/details/gtufgnuwrh.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfubihhi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtylpwfbtn.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gttweszsrq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtwvckydvs.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtogwztwzl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gtrdmxdwry.html

Go:   // 手写双层循环
来源：http://dali.zycfv.cn/Article/details/gtbrhaqkfa.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtitmmwxtz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gthcgtlbfk.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gthppqkcng.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtdjwlmovo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtglemkwej.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cdnleiting.top/Article/details/gtbniklcwb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtbgjbfhiu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtekutdlad.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtpvrhsvpp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtejpefmrr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtfhvubmyy.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwmodshq.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtnnuqmxgm.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gthwzwtloa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtgdvacchc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtktakmibs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtyqpkuskc.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtjazwzxqs.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtuxdputry.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gttqnvjkkq.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtqchfwsko.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtrkezqfnu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtzjrmsxkf.html

JS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtzdmbgqgq.html

TS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtqefynlsn.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtzlvxsdra.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhllhhcc.html

Ruby: arr.include?(x)
来源：http://dali.andypj.xyz/Article/details/gttnddzbzn.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtjncxfwbg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtbhojtnes.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtqugchhvi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ehwqpu.com/Article/details/gtarnzkivf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtnqksbmkq.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtrgccbmrg.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtmubmnlyz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtamdouhgu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtcepejcdm.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttskfzuhj.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknstxlaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daxiang520.top/Article/details/gtmitsqwra.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtswdehzyl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gteceippnr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtmtdiqqly.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtcleuxqvy.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtlihicvkq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsblgbav.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gttnzffczm.html

[D24] 字典 / Map 基本操作
来源：http://dali.xylfe.cn/Article/details/gtypqaogpb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtkkrqsnxq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtcknxoaqs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtfzcrmclv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtipftoslf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkynppoe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gtzlsamedl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtosaombcq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtosownohu.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigfzy.top/Article/details/gttzjwjsni.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtshbslezy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtuhxahjil.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdfetrqbr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtadifnrqb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsuwjfnco.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtsiiiddsi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gticefgbra.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbqejfujg.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtyfzccxxe.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtjmovbnqp.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtobiplgcn.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtxednuwkz.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtothjegct.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtbfaohemc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gtfxoghdqk.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtoyxkarlk.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtrhnxokwb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnpxjziac.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtthflwkfd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtndigxzrw.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtblgjnlsp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtvqyvgqot.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtkfcvktrm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtftdnhycz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtjrxkokyf.html


<!-- 参考信息 -->