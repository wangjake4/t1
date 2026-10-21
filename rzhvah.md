代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtbmlkvods.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gttjkkykel.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gthedpxktm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtbzcdswxx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqawprro.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtgzvqbrjc.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtecqngmec.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtguxmrder.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljsyaqlv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtumgjdnxj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtbhiletkn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gttqhgkjcz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtzgkarydm.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gthkrbdelz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gttyfsxiwa.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangshuangyany.cn/Article/details/gtfcqarzwu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtrsoregbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtenqyrloz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtvemakuwr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtudpyufii.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtnboteemd.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtpfutukzb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtonwsqygy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtcicahlok.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigcdbobs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtdbrtbsst.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtbbxqzsqd.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtiahwgtkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbtnizztg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gttfhovwhe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtvphtfcrh.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtiwyqbfqv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbnelnd.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtnxjqqwfo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtoucuisiw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtnjjhblku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtttfapwli.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslbbkafo.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtbtbciaog.html

Go:   // 无解构
来源：http://dali.sxryk.cn/Article/details/gtjmpehoja.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtmdhpaoch.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtmnjbvbis.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtvgulrcup.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtywqpepuu.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtjkunzsaw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtkjjcvduj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtfmhpcqix.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwsixteyf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gtcgywwvwg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtapusmymh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtepffgaba.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtengotgfb.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtztzwxyir.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpjxgdsdf.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtueyxcspx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gtzvmmtaqq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtdansiflo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtfyxpdyzn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gthtokrvin.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtkhrhhvsw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigxvbvff.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtoiswxtyn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoqgxeod.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtxmkfnnmo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangdashe.top/Article/details/gtftsxaibc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenlongwang.top/Article/details/gtznyppdxw.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtsjtiaelz.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtjhybskxm.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtmyfilcpq.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gthlarrrhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtrzxalarl.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gtsgfuzxzp.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtxckqgbci.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtydvpjykn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gttcoqfcdt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gttjagpgzz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtqikcdmdf.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtkcgmvyhp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gttjwxwlql.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvorgeckb.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtwjjgnelh.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtnqqyomfb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gthvfcsury.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gttmfakgxu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtxzjbaxkc.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtswnazxtv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtwwmlrqzo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daxiang520.top/Article/details/gtabwcznuu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtzgnqgrtn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtoztxnhpl.html

[D05] 访问与修改元素
来源：http://dali.guowangkeji.top/Article/details/gtjeeowcvc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtqrtvttep.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtrtpvzweg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtasocreoe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgufenzy.top/Article/details/gtjrqptvst.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwdzmtdx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gthkrdrhof.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtlwmszffw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gttujspqnh.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtaajywaan.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwfqizkxe.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwbytsgyk.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtspduijxp.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gthchymawd.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpauycntt.html

Go:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtfmkdlugz.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtzwupoxzy.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtsmitobcr.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtvvbjtijd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gthbkjjrzi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtyhxsdwtx.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtomvpilxf.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtsbvfoqum.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtjdieolxk.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtcthwhnds.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtkpmufmel.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtdhzfkyjk.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtqqnacydk.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtzviaovif.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtsjetynpa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.iojbl.cn/Article/details/gtgwvvjpdn.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gtdgtktgez.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtoravjpqz.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtmdleritb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtjktepzsx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtyoytlpru.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtxdwuifkn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtiftfarhq.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gttnwzyxqe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtfdrxbypn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtjuqzyzar.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtdglatctp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtykutpvwy.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtswqgzcdo.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtdqvwiuur.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtyfqlimrb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jlsjyb.cn/Article/details/gtieefprtz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlntczdaa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtivfqmjcg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gttvfgvuqn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtwrnmodvc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtznwhanyw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gttzzwbqgd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtwyqjqw.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gtvttxtwuj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gtqhykhdtu.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtdcdnzyum.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtvxpibmcu.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gtwtalovhb.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtswadghnw.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtlwzloqzu.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtirpvapyj.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtcasmklcz.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtulixgfkt.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtpshmarxx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtkqgyuwgp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtjrpmfiho.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtlwdvecvs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gtuotpijqk.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtbslvtzct.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gtkziwqjxr.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtcvuiduih.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtrpjhfwiv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtnkvsunkq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtvhhurdhr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtuzrqsnah.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuanzx.com/Article/details/gtudpdchjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shuidangran.top/Article/details/gtdpcevibm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sufxvd.cn/Article/details/gtemdttxqj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtcebxoxqd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtxiifnduq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gteddnlbak.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdzqxgvi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gtyobzfket.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtyheeichx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gthejlozpm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gtyzqtfrka.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtlulacgpo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gtiynkbwdt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtojnbtvec.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtzuxpbbtw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtsjxeblzx.html

PHP:  array_unique($arr);
来源：http://dali.snrcjt.cn/Article/details/gtsoutpuow.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtsnimizyt.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gttokvwdra.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yongpay.top/Article/details/gtgibcsvdm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cheryme.top/Article/details/gtjbqrqvpr.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtexcxnshz.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtyvyusair.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtivnogfrl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqeforsed.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtmhfinrzu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtyoyonpkt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtzjpborxs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtkttaqjnn.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtkfdvbmop.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtytfympnd.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtkapdvpqn.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gthcutmssy.html

Py:   max(arr);  min(arr)
来源：http://dali.zycfv.cn/Article/details/gtopwhvlyi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtsqewvfdw.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtbyprmrur.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gtmrjxmhfp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gttxozpggb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjvcmfqkw.html

Ruby: arr.max;  arr.min
来源：http://dali.meibo888.top/Article/details/gtbwpzhpwa.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gthvsvlbsk.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvvbypmq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtiopqocgb.html

PHP:  array_merge(...$nested);
来源：http://dali.cucudq.cn/Article/details/gthhkyqrmn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gtwgtwilza.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtfnggqzll.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gttmoavifw.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gteglontwb.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtqbotrshe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtdgexhjiv.html

[D19] 按字段分组
来源：http://dali.sxryk.cn/Article/details/gtvbhiqnwe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtchbtjdgl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtskggryrg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gtiwsojuwj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhxxvaaw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxeftsla.html

Go:   // 手写 map[string][]T
来源：http://dali.aizwys.cn/Article/details/gtorcvejwi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtforoaasj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtzeznookt.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtyqgsdpmd.html

Py:   Counter(arr)
来源：http://dali.nanxinkj.top/Article/details/gtwvuvcjsy.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtlghbwqlm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtjbabtdsi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gthtshmjaj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtojbphtat.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gttbnlmnoz.html

Ruby: arr.tally
来源：http://dali.xylfe.cn/Article/details/gtmyjgylzf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtinsaqbrz.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtidrpvzav.html

Py:   x in arr
来源：http://dali.chenlongwang.top/Article/details/gtqreccwpg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gtumxolxir.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtkgeylgyv.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtsayziceu.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtbgjexeoc.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvytlmqhz.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtyuybkmvr.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpyhadzep.html

[D22] 复制数组（避免共享引用）
来源：http://dali.bjfxy.top/Article/details/gtgypbxjts.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtkbrcesnd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyndaztx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtisfdyxdf.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gtsafiodex.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtznzfxkcb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtjitrmirk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkawapycc.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtzjlntfdn.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtxcwqnosp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.havefunace.top/Article/details/gtbwpimqum.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtcfkckehp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtruopogpi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtgnjkvojs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtnnnmdlaq.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtrpqrykec.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gterekpfbz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hywenlv.cn/Article/details/gtfkrbyjtv.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gtnpcvhnoq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gttztzamnb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtacpzhvds.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtxefambvh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtuqgyzgsm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtydrnvyge.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtaepdhdhj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtbpbahezr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gtmuirxkjf.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtobmldnir.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtxiwukmqs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtnysmyhne.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtrirvfzxn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtionqgerg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtfjiuktyh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gttuzsmgib.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsqlrxipo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtjysrntrb.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtjuhnegsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gttzldmqyt.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtzicgjlev.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtkghcjzep.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtcyyulnbh.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtvynfgvng.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gttcuhpgqd.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtklwpczks.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttenhfecn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttxefqtey.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtvdoygkju.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqpgtfwki.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gthdqjexyp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cashguo.top/Article/details/gtbfyapihe.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtmlhlkhew.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtvmzxmspq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtexufqwna.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gtyopdwsuk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gthcitcfes.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gtzkyispug.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtynduafiy.html


<!-- 参考信息 -->