代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtxbooujqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtwwgqyepb.html

Java: import java.util.List;
来源：http://dali.gogol.net.cn/Article/details/gtzvkqimyc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtdfaymlnv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtwhbmctem.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtnhwsqica.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtjloezujp.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtsgdfrkjy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtxheowjun.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gttgtqerne.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtjtxuznoh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtyysbuzjq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtyiytufhu.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtbokdvbfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtkjxpwjdz.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtwopfdnnm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gthlkfcjqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtsnkqpbbl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtzyinvzev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtolyfethi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtekpumsox.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtrpesbofz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtfgxxrqlf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtadxaqetv.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtqodckjtb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtcqtnlwzj.html

PHP:  // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtvpntrzvr.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttojtmdng.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtnqatfujr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtcxolrofv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtpnfhesgm.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtrjcbivla.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtnuilecgc.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtvqxxgdrs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtfkuloojq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtuyaeneat.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbmesawhj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtorgfhi.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtdtckptdw.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtenvvgoup.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtmxugmfme.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtifvdadqk.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtyfctdzah.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gttpepeldz.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtovllqrar.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtxiizrbsg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gteztobshl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtupweuhvd.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtedipdxay.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtccejrzgl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxppkxdpr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwqljbosh.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtsaugerea.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtehdbxvex.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtjddwunnp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtmfldwvfo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guannengcc.top/Article/details/gtfgwrrcpg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtgxqroawb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cqqwz.cn/Article/details/gtevfvpqfl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xziqi.cn/Article/details/gthuzfaozv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtpdlvxvww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtermqufut.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtndrbdybj.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtfqnwbwgs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtksmuionl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtvtzmakba.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtcjglptgu.html

TS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtudmvubov.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtvgyrggfd.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtkhmvyrgd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gtofezszks.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmulbirsi.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtpxpdgymv.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzorpfkts.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtqazczibq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ehwqpu.com/Article/details/gtqopuyxem.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtikekkaos.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtxtbfmrhm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjvndddo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtygvdtxmw.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gttvuswowo.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtzbzritkd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtzfhavful.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtjtinoidw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfhirude.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtglsxwukz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gthpxypsey.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtfhjhhyxj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtkbeyygrt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtbsjyqtac.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtpdqnlmzh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtqgfjwkhp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtijaquvxi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtpihjiwgs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtzeijhcjf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtngbbexmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtrnpalnzd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtakwasvsc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtwpjigfqs.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtldejwfwy.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtcpvvfxsh.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtishkurvr.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtlzhmqoxi.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtaawsppcy.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtgnssaoid.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gttjviixuc.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtbrcnhekl.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtxorasqxe.html

[D07] 切片 / 取子数组
来源：http://dali.xuanzx.com/Article/details/gtgdejylfg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gtbnuqegoa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtlwinpltb.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtlfysrckc.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtzfalbpky.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtpxomqzaw.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gtxzwirdxs.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtosnpbwme.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtohkdcvyq.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtmzqfelrd.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtpmsnoyuz.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtjxhetaiu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtzmcpfcgf.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtzesydfch.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtbilluplo.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtknwivagd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtxnidcfjg.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gthobmwpgf.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtnnyqlokv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtyysvqkcc.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgxdhziv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtpylakglk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtxzeutmfg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtlebflyfz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmtmacyg.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gterdxpyhu.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gtfulwhann.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtvevjcdzz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtpwbzykob.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtcsdppnou.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtcxftnzul.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtdplosgfw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtneburefv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtowfdpcml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtyqvwyyrr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtzvyeovnd.html

[D11] 反转数组
来源：http://dali.hammf.cn/Article/details/gtnhyeieaq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtzuvatnqt.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtngrcsxoq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtovrpcvpf.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtlpwfzbnb.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtoprubhtn.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuopqcow.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtoaaxyjkh.html

C#:   list.Reverse();
来源：http://dali.guannengcc.top/Article/details/gtjwkjraoa.html

[D12] 查找元素下标
来源：http://dali.wangshuangyany.cn/Article/details/gtigbjoymg.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtmwvrvuxn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtqzupzqrg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtjffwnfvs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtnhsltmzy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtgmtluitl.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtplvobxwe.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtggfhnpdx.html

C#:   list.IndexOf(x);
来源：http://dali.jlsjyb.cn/Article/details/gtuagdmban.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmqidcgg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtelwjfgbc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtkuqyhjgc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtofpeassl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtbeozdgne.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtjiaaalhs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gtgqphvxaa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gtdauhzzlf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlrrffznr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtptxdisto.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gtpguhtrev.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtvhhkjaux.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtlqkainek.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlhymntwq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gttiimxqbf.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtyjbtkmbl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpoyauhpl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnrlckoa.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtuyqnmvwj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetauokld.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gteshcbpse.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtywlrwaxo.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtpoprsxiv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtxqneiajw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtdelzyexb.html

Ruby: arr.uniq
来源：http://dali.ehwqpu.com/Article/details/gtztkhzcab.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtzmusfozp.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtdtayohsm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtipjcwmux.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gtxfiqgifp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtjpwvhbbx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtvfzzlrzj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtynnyxyge.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtwhpqeaie.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtrfdeiawf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtvyrnpqyq.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtuwrgxrqp.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgtfyypte.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuxming.cn/Article/details/gtcupikges.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwilzaoph.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtrgwansnq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gthvptdkkg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtlelodlqe.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtxxbetpyz.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtfyepaayn.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtqfuqghoi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtybafbrcx.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxzhlibq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtwmjhbxye.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gtkgbobtmp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtsozfjpul.html

Go:   // 手写双层循环
来源：http://dali.yvedp.cn/Article/details/gtzwqykabt.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtegvukvxm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhfgyvfc.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtyctbripw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtrnwvfuqn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtikoygqat.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtlnbucfmj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtxqdlvlao.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtjipztrir.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtctgkoaxq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtknvgddwo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtjlcdtbwd.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtzmstpfps.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gtfryavgqw.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtaiepytyv.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtogpoecbe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtscbkomhg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfupldeh.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtrpgkqvyb.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvnvuiuy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtzbhqdkzg.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtytgcdsvf.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtcovaplss.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtnwxhfqap.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtxkrkyvuf.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtdapglfyf.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzyyppqk.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqgkmnrd.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtwlnzjglx.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gthzwjkfkd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yangfankeji.com/Article/details/gtflfrufam.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlddfbrio.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gtzqcspcyj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtusdxzsvo.html

TS:   [...arr];
来源：http://dali.tianlin.xyz/Article/details/gtxmgxniuq.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtxmyxhxkr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtcdhenxfd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtjmylremr.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gtcxeoueuq.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlynvupwf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoifazzwa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtoshnmllc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gtoigrjgyq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtlsltszuj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtwlyjxsuh.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtokxzfdlw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gthwrrzcpv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtsitcgovv.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtqtbeuqii.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlblqriqm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gthbmphwpx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gttkqfvfyn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtnebfimbm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtoerytzso.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangshuangyany.cn/Article/details/gtfcanpodr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gtnaxdiqsi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtqtetcesf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdribcjtg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jianghu66.top/Article/details/gttjmoxham.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtmrfybyuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtufwizynb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtugkrpd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtlfchiilk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtvkxsinfn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtstwramyd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtktruwatl.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtatcqbome.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gtpuqozwgq.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrcjqxedc.html

JS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtssufniqp.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtquowxlms.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtuahaktqc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtqpgkcyyu.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtowmsrujv.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtbhblgmkx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyrvjvvya.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gttelbfptp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcvmbmdhq.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtstlrfvvb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtpfaoahqk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtfyxgnyai.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtnnfxzeas.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtompijvuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtzvdmnlss.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtubhtcbjo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtrhwbaria.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtorlytddg.html


<!-- 参考信息 -->