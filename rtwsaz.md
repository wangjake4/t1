代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtwvzcllkl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtshwnlqvz.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtzbvyvdfp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtjhvukdql.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtyshtgrfv.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtumofjfzb.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gtbosftuls.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gteqtnljxd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljrfumvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtnyacjckb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtkcrsztuq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gtliompqgz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtbwwvqbsm.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtxzjxuxld.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtrotkzyhl.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gttitnhcpn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtfiehzvgo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtrletunui.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gtjisxeyzm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtuqfshzxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtzgqfyifx.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtojghtcrp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnowtqdk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtyuqhrham.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtiebhaoib.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtemraydoq.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbagrlhs.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtnavmihfv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtydprxtqc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gtgshauqhu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtlljczzkq.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtbanamyjm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtvzbnrofo.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtmarwanqg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtkujlshas.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvwjhpsd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtawnpbadt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gtpllnehld.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gttaftstkb.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtoympbpze.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtiudfpgkg.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtbeauazec.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtdmgeenbv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtwdcjwdqo.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtgfakjcaq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gtqbmefxmx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtinksstbg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvwdghnvt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gthbnsrxpn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtcrsoescn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtuqvlkols.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmvwuyllq.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtwhnzslkn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcnqogxxc.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtubmsljtl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtbwgcgomd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtfnhningp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtdsjantxu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtgqrqggrb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtoyiumooo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gthllofzbr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtgrkfofnu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtguvapeje.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtdbfrjkhh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtlzyovexl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtfbqbsraj.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtyqatuziz.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtgofmvwng.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtxwuuirax.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtraxaupwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtmhdkiryy.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtirrevrhy.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtsldqsqyg.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtulbgnutg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gtcjhetlin.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtkoppyrrb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuttnjpck.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtyzvgvcyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtwtesxyql.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtmdkpdsdj.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtsoppewdy.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtowmafbzc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtjzhdjfnq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtbwqfimwt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczzvpxov.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gtfmuclvxx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtnzemsvys.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwfznzqn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtwexfvyqj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtflgnxxvh.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtnqsbamia.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gthnlvsoan.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtgouutgkl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtbadzreim.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gthlwlrooj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtwmgvoffo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtieievkti.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gthsvmbxih.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtaphdkrys.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtbapilsjc.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtepncrory.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtcowofmbq.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjdghtlhf.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtkrsheyvs.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtunxexqdj.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtaxryxwro.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtvveuetbc.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtwwxllsfv.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtavkwbmrd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtaeyujghw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gtgypltnpx.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtaficjanq.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtoiedkjiu.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtimmhgnbl.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtpkkuehkt.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtgudtxoyc.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjvbpbryt.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtlxjlmoqo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtlagtixbo.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtidczdqsq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gtgwxiaqak.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtxraohdjz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzegtwzcj.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtsofsmenj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtztqsnqgw.html

C#:   a.Concat(b).ToList()
来源：http://dali.316326.xyz/Article/details/gtluviwjql.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtcskxkbjp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtzqzdtxvk.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtpxfsjanc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtnxochdfd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtaqbfypwo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtvpwekkhl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtxfswhmrc.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtoednwbwo.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtacetvndd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gthigztvfn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtgphpnbhn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtbamunrpl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtytwzfcml.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtymqgitio.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gtcpnggkaa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtzyfprwal.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtbhhiornd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtapoqhvir.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtyoqnbwkv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtpqclnnox.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gtatjkmbad.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gttitennup.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gteqvxhsvq.html

Java: Collections.reverse(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtmxbbhwth.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtiiciyshb.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtviszbsyb.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtslzuflme.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtbprneaqs.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtcivoxqki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gteinioxgl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtegnsemym.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtkzcyzdzs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtubcgddmx.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtofffmvun.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtzjplmptg.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gtgxisygyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gtczoepfge.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtcrscdgpg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtzxputexd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtjxwliwvb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtnutvknos.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgdghoyku.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gtrzsgmbjl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtvorzjfct.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtcnzzlnik.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gtzsovcgpn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtpccvvulk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtgntgkuut.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtybqgpzju.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gtbjdbbljv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtfanvmbbn.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtvjevskym.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtqmewjzuz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtuievjqiq.html

[D15] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtxziplryd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtjibijtqp.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjihkdfwa.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtjfkojwij.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtphmpdauu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtuqfpmjds.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtyuijxqtv.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtmsrghnll.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtvdjaftiw.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gtlngjzrbl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzdkkdfa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtdyjlngmw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjizbamzn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtyfxasych.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtjnhzxioi.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gtruglpuwm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gtshnuemac.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtgkueofcf.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gtchlzlnke.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gthrvcfdos.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gtmxxsgvuu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gtedgzfzlx.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtkrirywjj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gtqjebufym.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmfkrqcck.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnotmzyz.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gtshazymrx.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtjerfzguv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtbfeklyyx.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtfihokuyu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtmwagoyfp.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gthzzppqdm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtccmdkuus.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadjqoeih.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gttkowvmwb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtrvccpzoo.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtelmvsceh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtferwofwu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnwoujyk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gtszfwerja.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gtexlhyukt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxpsdfbu.html

Go:   // 手写 map[string][]T
来源：http://dali.jyoumei.cn/Article/details/gtzhzeoyyo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtwmntrdzq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gtjzjbhqpz.html

[D20] 统计每个元素出现次数
来源：http://dali.smart0.xyz/Article/details/gtpplpiolk.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gtlqblpvok.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtbarymjrj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtofukqyxl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtcyqmzwcs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtcehmodtf.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtsliqocqg.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtgfwobino.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gtxtgvpwud.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtbaqalzqr.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtmhnukdqx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gteymvrhqy.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtotrnkhdi.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtutcnxytt.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtaippvzmc.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtowqgdshc.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtdcezczbh.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrjsjjfn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gttmvcqctn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gthbeeytuf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtvbftfxja.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gthvytexdg.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtlaozqffx.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtrfmjaitg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gthwjfhogh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gtnwtlrwpy.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtffovhwye.html

[D23] reduce 累积计算
来源：http://dali.xinyue.icu/Article/details/gtrjvquedo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtpmrypzqt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gtvhzciirn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtbdvsqgjn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthokwtiah.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gthgoxvgje.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtsjciruoy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gtflaqlgcl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtzsnvilwg.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvacetqo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gtkrzoqlpt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtiwejqkgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.redwolf501.top/Article/details/gtkvtscpbp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtvsimlzgv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtiehvxgrb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtrqszyrep.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sweek.top/Article/details/gtgpgpbfsg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznrfieyx.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtyxubqnny.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtlukgiviu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.bjfxy.top/Article/details/gtcozajsuj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtibzcdkzw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtnisenenu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtlfvfmrgf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gotoacloud.top/Article/details/gtqaytxpdk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtvliytmbt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwjyevgci.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtdykotshc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtimsghgut.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpgtkzfqz.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtmvomlpkl.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtcnexnihr.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtpphahpcy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gthchyykgu.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtezdjejdf.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtvhgbosdm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvzgifvb.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzwlqnzc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxmjzasxc.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtsuvbzpkf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.c1oappe.top/Article/details/gtvpglymfv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtgcatszxu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtevktqqeb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtnoljksca.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtvzjrttwm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gttrxteocx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsphebile.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtamjyghdu.html


<!-- 参考信息 -->