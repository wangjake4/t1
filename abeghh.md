代发 wailian999

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtuwjyzzuk.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtjribniyg.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtdxelmtkd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtrgkrzmch.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtjhvbixou.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtyqeknruq.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtikemnvrf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gtmioryrbr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtrffouujk.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtkiigpozu.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtukjvhcqt.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtbsxlnqng.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtbnwyspvi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtpxxyhwdt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtmpqbxgqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gtlcqctcvs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtlxuxveun.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtryqqoiyk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtvabexcni.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtcnxkywwu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gtpiemhaob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtlcwsfemt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtclgurpte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiqvwjty.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtcfbgdffl.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtoqlpmklo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gtjjqkfltg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gthivvwafx.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtdbjzoacq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ivvv.top/Article/details/gtlxbodeff.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtbqtbwspq.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwblwxvb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtydqnkduv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtrpoifore.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtuyffkpsp.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtaemjlkar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtprjubqhv.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtxizmhzwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtmfdbrprl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtsupcimzt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtbanavjzx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtjqewwtur.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtzicuoilx.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtrenejmpr.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtkxvodiwc.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtxywydecd.html

[C16] 函数 / 方法重载
来源：http://dali.yongpay.top/Article/details/gtpgennykk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gtxcgfxsfu.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtkxselmpp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtinqsfryc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gttichzgpo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvnipjxv.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtippvuoqo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gttgnedmjh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnqzz.top/Article/details/gttdguvofl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtulactjts.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtkhecdpku.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmimlzrxi.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtmsxflnsc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gttnagdaqu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtlqwjspbw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtmxjoncky.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gtfssxxgmw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gtekhajimk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtpqzgsxuc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtntgjyhtl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.svipenyu.cn/Article/details/gtvsqyieov.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewmvjxhk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtowwygxsw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gthxslppbx.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtdtqhaxrx.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtmzhjojuj.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gtdydpyhge.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtpvxapntg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gtbzkbipdg.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtsmpnjyow.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gteihujesm.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtltzlbeuq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gttlhertjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtvwsrihyq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtbbsqyttm.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtwsndtkon.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zdqjudy.top/Article/details/gtehfeqjxl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtfufgrfvj.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtrzrcvdyx.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtxmsxjjby.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gttumpjezg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtlkmlywip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtiyhawspi.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtmjobpocd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gtsmuciosk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtumekzqij.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtskumerjq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtwnubvsqh.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtwwmvilvc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gthhjwuzik.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtbljdvkdg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtyeknvnbo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtlzqrhodb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtazumadht.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gturumzuwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtamqrtypk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtfwhwmvbf.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gthchypttu.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtpxpkqzfg.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtakrcmejb.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtscdfpygo.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtlxgsyiuk.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtdlnkyyso.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtdvtvyxzz.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtopmkaelo.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtkwdqdmxv.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtarpbfsot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtpqvtaajk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gthpopgjtk.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtqcvhosvg.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtiivghpzu.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtzjiuazez.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtluhkrigr.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtxcgtmjjy.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtjpgantui.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtqrmuuqey.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gthfdxxtwp.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtlaqiikxp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtipkuaxrm.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtzkmzdmgv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtibkmxkna.html

Go:   append(a, b...)
来源：http://dali.xylfe.cn/Article/details/gtyakadgkt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gtoimiiofb.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtlwcjwzqo.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtsgjempmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtojalrozr.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gtybbwctwy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtihusfagm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gtqeansbcq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtupaxpqxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtyyimzlhk.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtgiivxfis.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gteprylxyr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtwresoxdq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtwipnixgm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gtkahvywyj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzadnkuwv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtjwlfryem.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtmatzgouj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtslfflgme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gtavshnrhx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtifslbvxc.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtcvqkbuxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtayqepxql.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtyxuuauld.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtfczirgvr.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtztihdkam.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtbjgjrumm.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuddgpafb.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtoudxotra.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtwvghfebe.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtrdwtrpag.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtxrucnimk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtcafdrfiu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtgrsadbrk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtwqkrynzf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtbsfoztnz.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtfctyefqx.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gthhegyhqj.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtxjzhaolk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtrvcevliu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtiehwqzyd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtnmsttigs.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtbvnyunlw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtzntwigaw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yonumen.top/Article/details/gtiefecqzq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gtnigkwvco.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhiwuduotai.top/Article/details/gttuzmdgnu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtngfsqfkr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtgvrcwowj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gaohongyu789.top/Article/details/gtmmvgiqff.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtjwsockwf.html

JS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtuddwgnch.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtccqzotzo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtkxpibmge.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtjepfnmzf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtucygjvgl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtfikczkre.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gtfwdqdrmm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtbhfellrt.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtqyexqyya.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtyakyqvvj.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtibpmsbtt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtlfwimadw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gttljrudod.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gtbqqjfarg.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtmxwlssfd.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtjmesvbbb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxqahxiwl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gtlutphutq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtklgbmbjm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgpswiiro.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtxkqimqek.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtfcvazfzk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtyskslccf.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtwsozkatq.html

[D17] 最大值与最小值
来源：http://dali.fzhhl.top/Article/details/gthgmicjwn.html

Py:   max(arr);  min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanuovjcv.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtnwoopyyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gtzwgzgwfp.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtuazyvnfa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtjfdrfgnh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfjpuqqp.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gtcqwfartr.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gtlrqasxeq.html

[D18] 扁平化嵌套数组
来源：http://dali.xuetiantiany.cn/Article/details/gtkuvcdbvg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yangfankeji.com/Article/details/gtuzgvevyd.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtufotwwsh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gtvklppsji.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtvwbarxmo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.snrcjt.cn/Article/details/gtdwrwgnow.html

Go:   // 手写双层循环
来源：http://dali.andypj.xyz/Article/details/gtmxxjwjfg.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtmixjpmhi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalxsaetl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtrhavcqrn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtmnzrbxcl.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtytudwdae.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gttpncpfqe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtqhyulppg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtdljwffqj.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gtggkfsqxo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtyyzaxmgo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sweek.top/Article/details/gtltccknzq.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwknbyov.html

Py:   Counter(arr)
来源：http://dali.jlsjyb.cn/Article/details/gteiovxlcn.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtzjzorvvq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtrevmicyj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtivmcnvfj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangdashe.top/Article/details/gtpaslpuhj.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtrkdbgcfd.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtarszpygs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtevhxnxok.html

[D21] 判断是否包含某元素
来源：http://dali.mhx1999.top/Article/details/gtljvtpnxz.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtpxswfbkz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gtarpllibf.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtkkrahkua.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gtcwjjyxmz.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosuaympu.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gtgxugdmmz.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtpqclsyqc.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtgvncvquq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtlnywhkwg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtyfgrrhjy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hammf.cn/Article/details/gtaqsuifqh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnhftffqz.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtkgxoapqo.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtcpkljuev.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.smart0.xyz/Article/details/gtfcjzbabd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtwinrcpba.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtfevcrvmb.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtrnuukvhz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shuidangran.top/Article/details/gtigqsdnwm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.snrcjt.cn/Article/details/gtgmudqthb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtwnjchpcy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtrgiditbh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtoerxlvyu.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtvsjvbiia.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtvedesghp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtrwgjigmk.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtbcmenjuj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtnzrzrwlj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtnegpkwww.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtyskbemtu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtbpptktjx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gthleejrfy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuetiantiany.cn/Article/details/gtciwmexcm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jlsjyb.cn/Article/details/gtjpsiqcvo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtkcsjgggs.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtjvbgascb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtjznojest.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtrqoarvxc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtqbilidqj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gthqjedtwc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gtcrlciqie.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtnpquunuk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gttoxrpjnm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gtbbzaavzz.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gtciemggle.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtikcbpojt.html

PHP:  implode(", ", $arr);
来源：http://dali.haohaochexian.top/Article/details/gttuughjcg.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtuddgkjkc.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtddlhyhbq.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gtuyzpeqpr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtgwalsaek.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gthttevwao.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gttywdtjtj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttcbvxzph.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtvpcjejte.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbjwvrrts.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtvndbhinl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gtejvyenyv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gtxkgjjnpf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtdhbdolds.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtbbbkucxz.html


<!-- 参考信息 -->