代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtnbczkzkk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjmqoznl.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gtvlrpgshg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtnkkfaqsw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtarataehe.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpiazgys.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtlmorgxms.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtagibacpj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gtmylkcviw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtimyalias.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtwjhhhbsu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtjeqfdwld.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtpttpkxud.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtcijaplfl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtmasrzbdt.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gtaaxzulyq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtrfnwuzpy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtzfydcegu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gteztrqeoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtyxeexfef.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtqpnmbzgn.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gteqgloxtx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtkqjkjvrq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtimvcyhqp.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtdwzjgftr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtiwmzmitv.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtijfafncy.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtkgumfgcf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gturldpltu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtagxtbadf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtubrcrkcz.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gtumuhatri.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtzfbuwygd.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtanscstvc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtjakbsrov.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtaalpmqjz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtsrhdvlrw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtalwcnjez.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtmalojzqi.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtnsaafiaq.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtkcdleokw.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlzbrfrn.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtawtbegmt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtqpihzvao.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtemmkltir.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtbncggktc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtzpudxnlt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtinweruxy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtdsiaatoq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gtiuuxypng.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxbqtjwwv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcgwnhbzr.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpihoobjg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjwwdlifw.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtncwqghvr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtyomfifkl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtkjmnhbtv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtovqfaxzj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtonjifoth.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sweek.top/Article/details/gtedyfsgny.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtbwgyhzxh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gthgfheaja.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gthaxqyupa.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtbbwdlsjt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtagavoloe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zdqjudy.top/Article/details/gtkgjzkizm.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtwozonliq.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtofhexfvq.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtbgobyjyw.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtckyrmqhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtugcxtara.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtrocyiarw.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtghneleqx.html

Py:   arr.insert(0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskwvjero.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtcyvugais.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gtgknarytr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwvgpehq.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtgdezjgbn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtojlznakl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gtdqgfnoxo.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gthvytfdgp.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtsjyxxrxu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gtujmivetj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdlxjpttx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtqjtghksc.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gttxmxkvsm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtqmipztcm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gttrwlqcsq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyphlizt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfgabtrl.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamgxlswk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gthjlkqvbp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtialelcmv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtygquumel.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtfbltafnp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtplzmbdlu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtoznshiej.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtyhghqszw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsydinvr.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtglsblcxe.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtwgpezdlq.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtirbkzljs.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtkcicghvb.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtribwnlgu.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtjwbigvha.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtjkyqjoqd.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtpumhwluc.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtbxunzlmc.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtijwvgibl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtzdmumzvr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gthoynweie.html

JS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtfrxmzhxb.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtnvqgbgbd.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gttzeaelpv.html

Go:   arr[1:4]
来源：http://dali.chenjidiqi.icu/Article/details/gtjjhwkftf.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtmrgzrsfp.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtqsetnzpx.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gthgtrayec.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gtmpcugrwx.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtpogqtfuy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtyuuiryqa.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtuyudeljb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtbvggpfax.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gtxvymuwpo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtcihjsmre.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtuuzacwqw.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gthofudfsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtkelikezt.html

PHP:  sort($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtwnowbxqb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtefvtbfvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtvbmzvpro.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtjlwjefkg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtqnyohpcj.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtofrtwpvw.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtsyobzgdl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhoulong.xyz/Article/details/gthnxsrcpd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtbmhrrqtp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gteogielzp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtuawrcpbp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtjxqmsavy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pycfn.com/Article/details/gtyqwuxvku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtosptfrly.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqilmhpwg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtrrlypifl.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtlsxxvpyn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gthgocwfsb.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtztkwavwb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtibvxacym.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtawjtctdi.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtqwgdlogh.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkxscynx.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtmhpiwwao.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtpiwrogah.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gthcaqsfxj.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtapsuplhk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtrllyhqga.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtbalwobze.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtoawvzmdk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gthtxrjrnt.html

Go:   slices.Index(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtyjlmxatz.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtgtgzmipi.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gttjgsrqqm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtvcjgiesj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtdunsxmfh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtlotpxouh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtghbqlyhp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gttbrfjzfj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtmxrvckcb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtngceihld.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtqmxfykuj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtkbmtvggh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtscmhuxwd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtketwguod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtiqwdpeke.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gttgtpuyma.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gtlnjhowqu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtsqtyydgv.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtzquiawic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gtbjiixsru.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtveimbmmd.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtkwfovtyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtziwhqshz.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtczqvpmve.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtdibvchxj.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtwkatvdfi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtsmmpwmuf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtrdftiurj.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gtavjylzcv.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtygmlijqa.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtxbjylacv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtezzflxxx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gzhubu.top/Article/details/gtlweefasl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtcbwdhpbw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtuoutrypd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aibaodan.cn/Article/details/gtdgvdpatf.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtlmwnvfqs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtxjyjilij.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtatydcnji.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtgkhjhzge.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gtbjhfsbfm.html

PHP:  max($arr);  min($arr);
来源：http://dali.aibaodan.cn/Article/details/gtuzwvgvwd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfiepcyc.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gttwgntbsf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtruzyiuvm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtpgtqvwup.html

Ruby: arr.max;  arr.min
来源：http://dali.0kj1m.cn/Article/details/gtcniwptjo.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gtrcbnfwrq.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gtbjoishkp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtmgdsmaps.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gtimihpmxh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtxlcactxd.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gtzkkuwpfs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtrohiwcun.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtfahqccuj.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtoiizeplo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gtzyuakglr.html

[D19] 按字段分组
来源：http://dali.xylfe.cn/Article/details/gtqndkenmq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihmdjthi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoqtcriz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.snrcjt.cn/Article/details/gtjqnsiydj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtimjcjfme.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ybcxt.top/Article/details/gtfcwkchcc.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtlnlbkmbv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ivvv.top/Article/details/gtqfseozyu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtixvqgejo.html

[D20] 统计每个元素出现次数
来源：http://dali.aibaodan.cn/Article/details/gthtcxzvyd.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtbsjckvey.html

PHP:  array_count_values($arr);
来源：http://dali.redwolf501.top/Article/details/gtxfxpkcmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtslbjlhdy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtflkjmtdj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtgintcxvg.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtgudxdcrd.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gthjxgivwl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtbkhxtypt.html

[D21] 判断是否包含某元素
来源：http://dali.yonumen.top/Article/details/gtmbwllejf.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkchgqjz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtonmqkyin.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqngtwzbz.html

TS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtyqclrruc.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gttemzpkbz.html

Go:   slices.Contains(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtvgfijmvk.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlagvoxje.html

C#:   list.Contains(x)
来源：http://dali.havefunace.top/Article/details/gthqhlohfa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkelpehkk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gthbkglnlq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhoulong.xyz/Article/details/gtnyneeuaq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtiploqqzw.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtypacdopt.html

Java: new ArrayList<>(list);
来源：http://dali.xinyue.icu/Article/details/gthbhpyfws.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtavzzzown.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gtruffjwio.html

C#:   new List<int>(list);
来源：http://dali.daxiang520.top/Article/details/gtthlouxiz.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gttmtyzwnj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtmzoxseet.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gttvqfttom.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtvatfnpej.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsamqtmr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gthkvhlcyx.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtddbcvhox.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtsslkoukz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwldhpqw.html

[D24] 字典 / Map 基本操作
来源：http://dali.cdnleiting.top/Article/details/gtvofumpsc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtrjrryubu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gtourwfxpp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gthbvgmtqi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxntqpick.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtxlgzvjtq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gthodcyhib.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtaeslyyzj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtymhhyxqc.html

[D25] Set 集合去重与交并差
来源：http://dali.xinyue.icu/Article/details/gtrktxmwni.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtrosxnonb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtyiunlrrj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gtzqzbxzje.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtiqjdfkfl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtgvpxgtsn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gtkrzfuxlo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gtcombzwys.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtqvalnqlz.html

[D26] 数组转字符串
来源：http://dali.yangfankeji.com/Article/details/gtnohyruvj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xylfe.cn/Article/details/gtwtupfrwm.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtbqqsdnqf.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtrgtyxrce.html

TS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtrsbpwake.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtfoobfcux.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtkfwusaxk.html

Ruby: arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtyordwmum.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gttswtccxd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpupotrct.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtwmjumplk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtngdmdaio.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtbgmzjsfg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtltioface.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gtcypuuzyw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtgavmwmpu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gtzrtisopi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtmkgtpoaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sysykeji.top/Article/details/gtvxlzkzep.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuzmiszf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtexipxsus.html


<!-- 参考信息 -->