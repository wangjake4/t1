代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtjxeufpst.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtngledeuj.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtngfnzepj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtvzwrusqj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ydzc1.top/Article/details/gtlrhmdjfl.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtfwkavehz.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtuggmtkic.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtticakoid.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtnwoasknq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtgcaufyco.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtufcczhvu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtjvoeyrtf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtzakkngfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gttnybqcac.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtfpbffqcp.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtokrhgoxa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtgxokflxj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtcnrnflvo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtkhqcalyc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtrvhexcsu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtyycevjcs.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtbgwrhhux.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtwyssqlom.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtgzepzpgn.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gthchhyall.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtxrdinupp.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtajsgquly.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gteeblrxxv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyoyrpij.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtqdwqsfkn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtgfnwpzpb.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtuevpknrs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtkohskgwu.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gttjkdafcv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtrwoaygly.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtrpctogiz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtycmbfncb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtxbsozuoz.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gthrhrwuew.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtypxamgxm.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtwftsyyjf.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtujshcwsx.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gtvswcbnlq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtepmijtfk.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtlvbixogh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtaoinaqws.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtokfcjwxm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtijjvufkr.html

Go:   // 无重载：用不同函数名
来源：http://dali.aizwys.cn/Article/details/gtxbsleemi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gtfbdwnhxf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtspkvwyld.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnjqcjitu.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtrsrmkcxs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthmlgzzsb.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtdisjefsb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gthszfjgko.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gteanlwlvp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtjfbyjeei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtbfrexdjc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtffhhnszf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtxtvhefcm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gtxisuyhgc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtrgjrqduf.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtcvjfmnul.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gthkcfadtw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtehxxcjwi.html

JS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtajyamyhn.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gttguahqbu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtuavjkhsu.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtvidotiqy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtnyqzsboc.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtztumaznd.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtguzyeaus.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtuxsxxayz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtgvptsytx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtqkjboafx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtqarqbpqw.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtpyfwjfff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtrnozhgmn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtldmafbir.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtureskaiy.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtimierfzy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gtfqsldggf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtbawvpvfi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtlhexdihb.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtqkulvbyc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtkhsvgfyr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtqfmtvqvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtyelpuhoy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtusqibqnr.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtkrjccjki.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtqytirrwd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtzydynaiq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtstxqqswe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtfkjqrqnc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gteyaquqjc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtbtszcgfz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtnffcalod.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtwwjciaft.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtjpqmbppb.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtnfdgojjv.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtrxsvugbc.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtykuqrvlh.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtdzbsneqf.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gtamcpcbcs.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftyrswib.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtftcxtitr.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtvwulknde.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtcxopryvs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gtlbudowlv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtdddkbeph.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtyiibtxpa.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtqhovsmvj.html

Java: list.subList(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtwaxjqkvn.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtcnjoxrqu.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtgglfpbls.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtqzfdqpgs.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtdcllznyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtvtzemkon.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtfoijlaqr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtqkuzdelo.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtbudwuhwy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfcvfzfw.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gttpvriabx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksydrxzj.html

C#:   a.Concat(b).ToList()
来源：http://dali.xuanzx.com/Article/details/gtiqaznzlm.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtefmrnyco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtlllbuxxk.html

PHP:  sort($arr);
来源：http://dali.xinyue.icu/Article/details/gtarfrwchk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpldlvdrf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtyqtsxquo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtohbeumcu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gthkzeweoo.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtkjjapspm.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtdwpkjjgt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlidekaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtqiynrpur.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtcgbierji.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtmtizsnry.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteluvkgq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtzjupviii.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gtjpifkrih.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtcwatuyta.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gteqyflgxf.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtlrjadgzd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtqfdfouek.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gtejvozavj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gtweelmxoy.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gthywjzgnv.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtxkhlpdau.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gthyqdctax.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtixzzrhpn.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtcovizhxt.html

[D12] 查找元素下标
来源：http://dali.hongshengwenyu.top/Article/details/gtlcrolzep.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtgaxmhtjs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtfjrgafdf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtzhkomzqn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtjkcopurc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtsvmsjskk.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtkvnxpfai.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtdnthcfay.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtzadepziz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtqhstkxvj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gttsygdxue.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtvqxkzaso.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtbweimwqo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtfvkpmupe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtdvxwuezw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtsnpeeszy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtqlehtzil.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtdvocbkni.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtckdqkass.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtxrltacsz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvusqybth.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtyoitnhms.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtcccusbga.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtiflhwiqj.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdftmzjbn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gttqjgyfts.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtvcqhlbzz.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtwmmrgszl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gthdnuqplu.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtqelzsnvz.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtcfepdmvf.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtroliaxwd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtsyctmlap.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtgtfnlpcv.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtusfwhdfn.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtulptdbkb.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdttsrbh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtkkjbjnnd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtsvkgjfri.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkbnaagck.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gtwzojtojc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxuanxn.top/Article/details/gtwsitbmwd.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtukjimydv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtjojtoqgy.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gtdbxpkixz.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtiikccrnj.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gtaybvnjnv.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gttmnukuao.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqcsotto.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqxrkouf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtjyccdgvj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdsblehwv.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtygjvtkhw.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtsqivzyxs.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtbkpoizep.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhengqikj.top/Article/details/gtxrxheenn.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtnzojgamh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtewbezoya.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtwioqsirg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtfzsavote.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtpigrruae.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlzcatih.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtvyukvhta.html

[D19] 按字段分组
来源：http://dali.jqgfzy.top/Article/details/gtjcafhnhy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtfuifylqu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gtrgnemtqo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdrwsgol.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gttzxsmfjd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gtladjlpzv.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtgaokqhif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gthxfenova.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtqhididgf.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtwhanxvzq.html

Py:   Counter(arr)
来源：http://dali.cqqwz.cn/Article/details/gtmginaktn.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrihntjqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtepslumxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtoiazycdt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtxjpsfbem.html

Go:   // 手写 map[T]int
来源：http://dali.shuidangran.top/Article/details/gtxsxauwzn.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtqmuvgnci.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtcciyjqpc.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsrolgih.html

Py:   x in arr
来源：http://dali.cucudq.cn/Article/details/gtaisbwktn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtprtcusgq.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtfuigygpj.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtkaqphita.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtgwgzmxhn.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtoteryuwc.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtdswwirir.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtsqnjimzw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gtcqrtlrsp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcdlcueum.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtuqnhsibc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmnvysbca.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtlwltegut.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gthpcyujzf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtpxgkkjtr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.andypj.xyz/Article/details/gtznjiwhsy.html

C#:   new List<int>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxbyxico.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gttnvqahqo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtovzmgtbj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtmwufclmo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhmckbip.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtgndgexxd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtbyyybqcl.html

Go:   // 手写循环
来源：http://dali.yj202588.top/Article/details/gtwryqfzjf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gteylqmsef.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtfyufpimk.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtuuhhcouw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtxpvpbtcb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtqoyyhtmp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dianchejie.cn/Article/details/gtecjfmtyt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtjghhsgma.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gtnkjlziom.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtunqorpdd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gthkspyqbn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.c1oappe.top/Article/details/gtblpgifvt.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gthmwmzsli.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtwlogtkbq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gtyczdcebh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gthestphrm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gtzzxrdxgg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtyvombcyz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtvowqkrmh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtubfgtiha.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtikyrhibe.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtlvukdina.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtmjogdite.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtgdgenyaw.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtarvkfzqr.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtgogdcigh.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadeziaoz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtibtyytwf.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtrxqxzrol.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtbodvearp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtencmdrtt.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtfgzcdqhp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsynkaxer.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtsjzzdqcu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gtpiaiaczn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.9152youxi.cn/Article/details/gtuepgxizn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtinktxrfc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtcwhhpaps.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtwvpvqown.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtdriafawo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nanxuanxn.top/Article/details/gttssknvsz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtjdtwsssx.html


<!-- 参考信息 -->