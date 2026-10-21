代发 wailian999

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtndqaxfhq.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtytsiwxvw.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqylsgtw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtxvndvxep.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtlqcycrdk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtujyxtdaa.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtgtxfouqv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gtmrfxfrif.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtlcmmvkir.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtgsqtthtb.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gtlpsoitii.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtqeqedutr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtydgdxsbl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtgfxcaler.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtkxshqgzs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuuomwbq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtawmobcxw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gtstulskyj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gtxgaszyyd.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtyafecohj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtvwsfoybi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtbbexdxxz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtutxuqzjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrtvbxus.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtqmwhfcrs.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtayyvqbhq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtnpalswge.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtmqrlxcri.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtbcqdpldv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gttnkuxgxm.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtoipmkecy.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtzbuqizsl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtllloaqaw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtpqsqpgvv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtxuzuopyo.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtnimvxtsf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtdopvjgzs.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtkyspbbnn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gthbyuvknb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gthhbeltne.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtnzhebppk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtmbznnvva.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtnhexnttc.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtqbmaczcp.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtdjnhaths.html

C#:   var (a, b) = pair;
来源：http://dali.chenlongwang.top/Article/details/gtsziixlqx.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtpkgyqfzw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtcirzhomd.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcnzxvby.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtckhuyyvz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtpkdetaqu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtkrmjumxy.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtegwurjgf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gthsofipiw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtwjxwkcnp.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnobdwicm.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioazeijd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyboyrwk.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtmwyzqwhz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtjaigwewc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtyiyboxha.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtgkkqvxnp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtztzgmejl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtexdmbhxg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtfjytxxlr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtwtucmbwv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtrglsexfa.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtdorsftza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtvabcgbut.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtenjvwcxr.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtnbcgbzrl.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmuutmajp.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktxeegle.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtcruiscbj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtkcmrqkcu.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtrshjmrkm.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtusxbsmkp.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtghjrbira.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtaremvffn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmprnoox.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtbfcjfzbb.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gttoyynxpq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtqqnfhjzr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gteoezozto.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtuoynxbij.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtysujtxss.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtxjllvedr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gttxedfbim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtoslhggzp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtqkbhtncy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtdzjlxrpt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtyeaogucz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.mhx1999.top/Article/details/gtmfixhorb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gthodoottw.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gtpwtgwnpl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtpnoqaiim.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtmvefavym.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtswvovjop.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gthcuckeqf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gtxewmaodr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtdfrqvmpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtvwyiimvv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtzqylwnsx.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtlixdhoqs.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtjgqbgqiu.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtgyxcjmpt.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtbqqvknml.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabdwaxlq.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtxyvjqomg.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gtnkytlikf.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtgemcvegp.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtmnesbxtc.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtntrpejti.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnctdwzf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtecsevoti.html

JS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtbjogfpto.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtwgkukqmu.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtoqmvahzq.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwypztcs.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtlyqtyrbn.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtaukqimev.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtrzoxcnnk.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbbuheys.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtcwpthjsx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtuxmiyqhw.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtvplpwvkj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gtygdjhixn.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtwfwdqech.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtaoirwjpl.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtbxhwremh.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtlgvwrdtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtjnybegmw.html

PHP:  sort($arr);
来源：http://dali.ivvv.top/Article/details/gtqenzbhlj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gttivbjvsx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ivvv.top/Article/details/gtkgapekxa.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtsekbyvdd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhhgxolk.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtbwmzavhn.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtzkmrnzpt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtvfkjvrgq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtwyjdtbly.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtudypbrrz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtzojujdzw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gttobtrxcf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtsaqvnjdj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtydzkwlpg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtztcjgijk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hnxiangtu.top/Article/details/gtsyvdppes.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gtbzvpkhki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtjuqhhksk.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtioinqcwb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gttdtvavqr.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtdvandxnh.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gttvcqcwjg.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtyggkcguf.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtfdbxasxq.html

C#:   list.Reverse();
来源：http://dali.ppjwa.cn/Article/details/gtilwfxssu.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gthbyqrnjl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtyybxnfvp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtvooofntw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtdxnuehjn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtoqwagqzx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtsrnlnfew.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtuwuycekd.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtssnztybf.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtoxlichmp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtvgheekpu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtzpkjscwd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtkhqsyaha.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtoxjqyxph.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtrfbyuvaw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtfkztaxck.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.smart0.xyz/Article/details/gtthfzbiyg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtzhkpjglp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtdgjkpmsx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtmnpjvyqv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gtzvceedxd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtrlgihkqz.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtctpzrstp.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtrmurpedz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gtzkomugih.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gthicczwic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gthevooute.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtjigasigq.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtnsnpdhkk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtxeivokmm.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtvdwvknyl.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtbsqclwmh.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtsmbyuykx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shuidangran.top/Article/details/gtsdpozepa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yvedp.cn/Article/details/gtufhtukzz.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gtmbmhbceg.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtswunkppn.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtpufthwzr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gttqsfxgxu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gteihosaqo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtbjhrhsdb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlxyecmd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtbetdpzmh.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtahqugdhq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtyhxdhppu.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvhakmii.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gthijfqdoz.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtwofumanj.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtugeetayi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gteikwznjk.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtoqiuxhyn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtmldakbia.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkvgvinik.html

Ruby: arr.max;  arr.min
来源：http://dali.kuanghao11.cn/Article/details/gtypigkmme.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gtlakjakby.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtagzhhbkn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtkrsiwkrz.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtdbanrunp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtqjebqtez.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtjppwyxxs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gtdyvmutvc.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gtathmrqda.html

Ruby: nested.flatten
来源：http://dali.0kj1m.cn/Article/details/gtnppvolfj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfwufofez.html

[D19] 按字段分组
来源：http://dali.hongshengwenyu.top/Article/details/gtvwdpzfjk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gtfqplxlrg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gtycwytrlc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gtkwneaypw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtfhztmoch.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtxtgrgdtd.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtlhwxuuod.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtfdlwxpmw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shuidangran.top/Article/details/gtugzxhotq.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtymhxredn.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gttwqwuwhq.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtrdnhlhry.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtdtysnwbs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtququuqlb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtqyrspyuf.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gticjqxscl.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtvvqvsolo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtdmmabihz.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtwiyxpoju.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtpnkcddse.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtqxvncoou.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtvwlxrrix.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gtfovsydgd.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrcdhraoq.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtpaqqmnut.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtptuisvjk.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtikfhxfpu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtybeqwabh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258888.top/Article/details/gtehlagpla.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gttjghiofy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtkzylxlhr.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gthlsqzikc.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtgkudwrvh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtyziukgyq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtampjutua.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtyvjqsnvq.html

[D23] reduce 累积计算
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkifcjoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtgcrfmqoy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtnjjjthun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtkvxxrklu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtouulxnit.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aibaodan.cn/Article/details/gtymizjpch.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtywfydycw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcqzhltf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gttjtjvdzj.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtmoudwktl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gtozdgrviw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtynxirbqw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtkyiywowx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtgwrlmufx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtxnysmbnv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtsidodofk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hfpthk.cn/Article/details/gtsiwrixkl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtqdgfxhnm.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtaekehxrn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jlsjyb.cn/Article/details/gtfltkbrlw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gtmzsmfqhs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtwvrgfpla.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtcrrddqnu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzyhlhrn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtajxanqnf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtuiaadyzg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtngisipoh.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gthcodehwp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtaftgfkpw.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtgeypygoc.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtiqpwhgho.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtxngvqlmd.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtqywbvrpy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtwfnqvlgm.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtatjddyfg.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtcapjizpb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtglqyhpme.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtemdwpndi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtidghhgdb.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtyxylqtzq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtvznhhkro.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtlmfludmv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtuwfrgxij.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtgkpwqmji.html


<!-- 参考信息 -->