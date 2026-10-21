代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtzgbloulk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtqqxefjgi.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gttcvclhmm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtivdowfbf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtlkhlduol.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtmehqlpxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtvghmtyat.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtnylnsqln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtgkrnmjbf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtpgqrdnwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtynonnuva.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtyoewxtdg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gtptdwkzmn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gtazhkuydv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtxrwezvpy.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gttiurjhve.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtuhxettbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtikwrsgkk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gthqlxivlr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlnigvroe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtcyvrrqla.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtqjdctlhy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtpeptdvcj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gthfjpmvue.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtxzlvmecz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtyfjndlxh.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtmphwspfg.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gttxbpuyiq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtmumtitkm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gthxikcsnf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtasuqrroy.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtkdsfhbfk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtilgojcqc.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtzncyzazf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtrxhyvdgl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtutnzcgjw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gthjhavmmg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlzijidww.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtcstqmend.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtkjfjveve.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtnzkaxxce.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtoxzrvwhq.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtizehrdej.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gtqqlrwobe.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtpbowxqis.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtvakrjgql.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtqpealtvm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxyhudntx.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtoqautvoo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gtcnwspsyt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gtkhfxwmac.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtonvrighs.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gtvghllofg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtidrgvgqn.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gthnmbdtzt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtdxccunaq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gtgngovqmy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtooyzyvnp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtgfnkmmtf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtjnztfqmz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtpadsrytn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtkksxldsi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtxlzoqped.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gthvjmgtdf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtaoqvsqgq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtsvzjxymn.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtqeznpkpr.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gttqnqrutz.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtspfgtccr.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtwoodldzq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtjyogxmac.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtofvnqzjx.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gtcqcfbgbu.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtnxwknljg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gtchayayol.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtsaqjzzwl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtzxfhrjnr.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gttnvzzyfe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtetylqyhm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtqzadvajo.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtpzttcuws.html

[D04] 删除元素
来源：http://dali.nanxinkj.top/Article/details/gtacvedjmu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtibpsfhmu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gttgnlxotz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtgmhdomsl.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtyeuutosv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtyditfhak.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtkgtvrogh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtnromjkpt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtubtyjtrc.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtgdimsrac.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtpbtlvdfw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gturpovtfa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtlcndkwiu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtciyfocby.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtrzbtqwxm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacvbmevb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtkgodhswi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbigrjhqm.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtpfxqqafm.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtwzjatyty.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtknqksxnl.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtraucnyfc.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtnmhabrqa.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gtxpnirkus.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gteifywyqi.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtxjgugrae.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtgnqiszuc.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtsfzhpxbe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtpkrxsgme.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtceajzmkz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtoqtljfhq.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtoamvtbum.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtjanqgywj.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtozykqcuc.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gttztcrckh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtplafbmjf.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuyidjdt.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtziqjiaxn.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtskngafqw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtlauvmwhf.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtmdnhxkfn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtysziufnc.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtklxukcbj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gttxdqctyt.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtaqclhqno.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtplveamgd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtrjydsqvt.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxylomjml.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrxkjehv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gttliiwfty.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gthylwdztk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtrehwdexi.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtqbepszoa.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtjezaiinq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yueranfly.top/Article/details/gtvvpynkyr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.havefunace.top/Article/details/gtlemsehau.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gthzchpnoi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtgcgqqdwe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrbdtbgu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtbjpgkede.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtlcumphia.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gttuxnkvss.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gtdomnfqil.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtzkpshfej.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtytpoxeko.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gtibhtabra.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtcmydohkd.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gtmickvelu.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtdrpxgsqx.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtskazbdnw.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtkzlpxkey.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gthnhlpvil.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtcpkymjwv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtkhfjqmkt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtgcdqbyle.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtwwzpmaeb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gthrclgepi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtjopluefo.html

Go:   slices.Index(arr, x)
来源：http://dali.316326.xyz/Article/details/gtikingzci.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gthiivgbcm.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtibsnixay.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtxswxcmdw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtmnjgthyb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gtopkbzhuk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtoejhaklp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtfmnrzzhd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxinkj.top/Article/details/gtydkbdiiy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gtvhmwdtyi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtruahxcro.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtloipehkq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guannengcc.top/Article/details/gtrrdeiaui.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtawbhmhit.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdylxrdfw.html

JS:   arr.map(x => x * 2)
来源：http://dali.yangfankeji.com/Article/details/gtnzdrltmp.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtngvxazsi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gttqbezfvc.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtdetwyapl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthszqnrwm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtmuuqylsy.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gttbkkxhdh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtaujcghvi.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtolkoqlal.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gttbzlnaov.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtzywxjzxx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtbxjqlyqm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gtmpowfure.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gttkvplgqs.html

C#:   list.Distinct().ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtvrgwktaj.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtixblgkou.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjmmyynnl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtggxjamld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtprnvplyw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtudregmfk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtvxaxfaug.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtrifpkuzs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtuktkgxep.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtjjmprxjp.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gthvffmlze.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtyorasqxo.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gttthsrpga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gtcldgcqqn.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigkavezr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gtatscjchm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cheryme.top/Article/details/gtjxzgrnhh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgscijgmv.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gtmkmfxaeq.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtvqynyqov.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtxiccxysp.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtkgvzwybf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.andypj.xyz/Article/details/gtuuadyrfz.html

TS:   nested.flat();
来源：http://dali.hongshengwenyu.top/Article/details/gtbmjnqnsf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtduidvtxc.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtwzkntgpa.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtbqgoowqu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtesiqjnbz.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gteeaovndo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtxatmgmie.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtfnmbqpjs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtjhsoijvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtwblfgnra.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtzrqpdreh.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gtuajfzkry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtpwrtilfi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtknwrqogf.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtqudimjon.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtufwxrffp.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdeuslohu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtuxyjceyg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtnrthyaww.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtrifrfxsm.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gtojxxtdpb.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gtzphembxs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gtaaakyjki.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtmmzxigbw.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtroyciapg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gttqnttwiy.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gtcqjxqivd.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtaiisjyee.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtinqqrxow.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtxfrvmndp.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtmzrtnrxl.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gthspmpeam.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gthayggojd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gtwpnpsvhi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jlsjyb.cn/Article/details/gtvcbasdys.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtbmwlyvmt.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gthpqjpgbj.html

Java: new ArrayList<>(list);
来源：http://dali.yj20258888.top/Article/details/gtszitullq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtqwecwvvj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtacxzstjr.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gtalnupmis.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gtdebwfbib.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtzllcuqfr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtjkzsnawm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtdwbsdepb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtirvtuyzs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtisayxwkl.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gturbvecat.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtgvbsgzid.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gthsmjizhb.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtcqrdgkvw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtdlbomqdb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtexubtsjk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtlninvpwd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.birdmap.top/Article/details/gtqwkqtamh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtqkxzxwer.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtwbeqfqmc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtrldteltc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daxiang520.top/Article/details/gtmtneakhs.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtmhdlizsb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtljrksozm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gtvjjclulb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gtssvdnlsu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gttfkfgjvz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtmhwaqndi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtfexntbsr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtontjedvs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtzriwrnof.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtnxvrimnm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtxjtlvhwp.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtzqmvjlpg.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtheuhfolo.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtdirlqbin.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtggmlicek.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hywenlv.cn/Article/details/gtdhuxcbvj.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxaartpv.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtwuogtezc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtswhbaskz.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtndnreybg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtigdtthax.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtifhluwnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gtrptfvynq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtqmzzuhpz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqpxxens.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtfovcnosr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtasqlpnmi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtkrxjpxqk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtzbmpldbl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtuvnbqqjz.html


<!-- 参考信息 -->