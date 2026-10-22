代发 wailian999

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtjvmvpglj.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtgxeqfwuk.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtyswzbrbt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtgqqsvhwm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtdttgwmfr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtogggbqpy.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtnerzzqog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtvqrpdbue.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtsnkppopc.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtzixmpsui.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gteyrgfvkv.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtueqntwos.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtsplugszk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtawdsvouj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtceosgghu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtkfylmoyw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtfuteehkz.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gtsfajrrkg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtqclpejmh.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gtldltxcuo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtweptedfd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjtmhedey.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gtgcfakhyu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtrxwvxuhh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtytyxqdbk.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtzxienwxs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtpksgvfei.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtrnsdlcfk.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtdlafwxwq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtjzxdelxg.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtzsxiildy.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtusffgkgv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dashuyun.cn/Article/details/gttglepnko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvegworo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtuboefnnz.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtyibwthjx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gtxsiaujsu.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gthaljhmiu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtzuglcprv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtsxglrbnx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzhfcqpvb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtjisbogis.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gtjpgffuvr.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtkagjissm.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtvgqprkfm.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtvxqnrnhw.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtvfbtsmgz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtrlcehtzw.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtssctysqx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtblefconw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtrgurgbwy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtsntkdlvu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtpajerjzv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtlbceodtc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtwiizkypq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtustcbrxg.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gtjrpvdnsg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxwoeccwt.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtquzypahz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtqjclmwyu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtbbpduenu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtkdajzidv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtrqsivptr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gtbbaugjnu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtrffhcppt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtonszycpm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gthtyvojkm.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gtbbusboyn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtveyenwir.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtcaospakt.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtiitjgllu.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtofyusbdj.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtvsbgyjij.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtnmfhqeys.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtnfjhdnkm.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtulfpxkku.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtapbuxrqz.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gtbdvsllag.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtklmntxnm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtvyspeaqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtpdcqdmig.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtdtjfqgte.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsnskilk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtrkwgsylr.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtkghmlhqr.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtjxjufjgg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtlfqyekas.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtmvomrbkp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtgdpcafaw.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtgacocayu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtidaeazfs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtswavlrtf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtbeemxvai.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtmjqipets.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gtakvgbdcj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtmvuizomg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtrnclfxzj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gttebyijwk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtbykdjciq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtjktfvard.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtkdcshbxa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygkwjel.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtbclgzkju.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtmszqhl.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtvlghewne.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gttyasxiks.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtlhzaakxn.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtvwvimqtu.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtjnmhxrks.html

Go:   len(arr)
来源：http://dali.sweek.top/Article/details/gtprnmohtx.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtmubzatuv.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gtdfxregxv.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtnnwuttyz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtagdcizny.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouqjkplj.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtgggkcehf.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtddsjiwkp.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtistqaglq.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtbueybudi.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gtbhglzvec.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtafendxxr.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtmbcrghev.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gtxmmarjjg.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gttlbhhxfh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtaiwwzkjx.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtcwqxdjsp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtauyjxhqe.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtlhnlsmva.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtfbwfvgux.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtrmdpnlie.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtvvtxierg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtwjpnmcus.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtrkflcbay.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtukdwmqly.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtwvlnksle.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtyuvbhltf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtguhibcyp.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtnnvdaykt.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtzzjscber.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtkdfzmaky.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtpzdaallg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtkbmwnfaw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtlybltcdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtgpwsejxv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gtlqmzbstl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtxftdrfyx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtrcxaucsh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtffndoliy.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtfbfwvgga.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gtieljnikh.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtlyjcgiwf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gttqlzzorf.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtnsfnjglk.html

Java: Collections.reverse(list);
来源：http://dali.shuidangran.top/Article/details/gtfmetzacc.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwqwtvqv.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtleyhhprq.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtbpjwzdnv.html

[D12] 查找元素下标
来源：http://dali.havefunace.top/Article/details/gtfyqizatw.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtrddhcgyv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfjlycam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtbyksgwsy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtivrtmyok.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnsibywo.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtjsdkibfe.html

Ruby: arr.index(x)
来源：http://dali.sufxvd.cn/Article/details/gtbclwvais.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gttzftvjyg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gtntsfrcmm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtotbxzcbl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtoyklvhxc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtxrmsvljo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtbrjmjwrz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtwnrmukxs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gtowuapuxo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gtkongxypz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtpgwdpedb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtaimixhif.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtpuboapsf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtufgeghal.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtqssjgzlo.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtkjrfefvu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtuxgjzkkl.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtmvuytswf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtkpeyqzva.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtgfqyswqj.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gtqblyasvx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtuuncwlxn.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gtfnarsdqv.html

JS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtykjpezep.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gtkotyctvl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtglvodxwl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtdikjmahq.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtanyjilgt.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtpyurbfyn.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtcrheevdz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aibaodan.cn/Article/details/gthlxyhbfj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtmdhkjcgw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqmjuoca.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtapkkwtjn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtwwitzvoq.html

Go:   // 手写循环累加
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbimyjg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtoimkweoc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtpbhwqwhi.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezxmgcgy.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtepaxenfc.html

PHP:  max($arr);  min($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtewuyenjf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtoegkupks.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtoewkyuwc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gteniuirnr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtjllbjxdc.html

Ruby: arr.max;  arr.min
来源：http://dali.bjfxy.top/Article/details/gtvchrsxrz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gtfucuhveb.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtzhvucasu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtsmyyiyhz.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gtqrirznlu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtmbajnvrt.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gtjecndbjm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shzxlz.cn/Article/details/gtreedolrm.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtxvghjwxx.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtirixjwnw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gtwolpltbf.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtqkimxnwd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgmzculf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtvtfxskkn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtpzznflxq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gtoyrujhpt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gttupskhjs.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtucjbrmsi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtoyupcklp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gthxhajtlk.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtohmfuvnl.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtufitcqff.html

PHP:  array_count_values($arr);
来源：http://dali.chenzaomai.com/Article/details/gtopqcnumx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtpdemnlpk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtbfatxtye.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtjoolwxsy.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjyzbslka.html

Ruby: arr.tally
来源：http://dali.meibo888.top/Article/details/gtjhvrzovi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtaspiszel.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtedwpprnk.html

Py:   x in arr
来源：http://dali.9152youxi.cn/Article/details/gtzojwzwud.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtmqzthrxx.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtsrdjugem.html

TS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtkgfzqzox.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtkzlkqxgg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gttmyaxyvq.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrnjmnxe.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtwoyoilvp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gttxmknjvh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtzavhwjjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jianghu66.top/Article/details/gtugxanctp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gtktcbhqdg.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtmnmmluyt.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtrlntxcey.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gtibnuszcv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnslahdl.html

C#:   new List<int>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtqcliyvxj.html

[D23] reduce 累积计算
来源：http://dali.meibo888.top/Article/details/gtgojuxuyo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jiagoushi.top/Article/details/gtrgdzdhao.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gthjioqurc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtygcjncyu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.meibo888.top/Article/details/gttsrcuvgc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guannengcc.top/Article/details/gteokgntxe.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtqsliitzt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtjntxxiuu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gthmorucfn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtikogfhhx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtacnyfatl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtpoilkyue.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtbsnapsqh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtcbqchuhs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtnsznqeyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xuanzx.com/Article/details/gtiqogvaic.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmcjvttr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtqztrryml.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gtgdbqghrm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gtjehwqlvw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtalxrufyr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtqerfbkny.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtzixbjorb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtlqxfhhou.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gtpoetjuar.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtgklyjdkw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtpylybkwg.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtgpgpyhtq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtynmqcepp.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmilpnxnl.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtwnlfhhjg.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gttjymnkun.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtwhpsehtp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtkzcssirh.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtlapnudyb.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gteofxcwow.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthbzhhfaz.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtvaffghvm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkytohbqc.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gttlsxclye.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtnmjiggnf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtkdwlteaw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtahlqiaom.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtsefboyhn.html


<!-- 参考信息 -->