代发 wailian999

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gt2trknrggw.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gt2dbwwapnz.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gt2vsygivfk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnexlhtp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2iljriiuh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksjksdka.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gt2azswdttk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gt2xylgjufj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gt2wupzairp.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gt2abaoyhqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2pfzibfyh.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2yruytnml.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2tarmitdv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2ekedakzu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2irtdyheg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gt2rhharaiv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmlbvumg.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gt2dlsagmsa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2dergarpi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gt2mxwovjew.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2dwguwggi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2leyixefd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2myfaptwr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2slkwofqo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2spguhhxj.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gt2vkkgsape.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gt2xfxrecrv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2grjzlzse.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gt2ghsucmzl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2qndzdxpv.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2xkckaset.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2lzdnynow.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbkxwfqk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmanklds.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gt2agstayrv.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2zeztjbwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gt2jnoddhec.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gt2pitmwcfj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gt2ttnushwx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gt2soikduxj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2oksdxsqo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2jtarrpiv.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2dmqmycnv.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2zqnncpry.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzptgbht.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gt2uvfmdqxg.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2uxpyrkft.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gt2zgirfyrk.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anceotpr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gt2hvvckwdk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gt2ulfonkan.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2tvtpueho.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gt2azvlpgww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gt2fvhwojly.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2qczfzaqt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2cfayzdxf.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gt2jnbpzhyn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zrhotfid.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wbwirjcq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daxiang520.top/Article/details/gt2bgfhpvww.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gt2ueznhvdk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2peruaqrv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2pgnwupum.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cashguo.top/Article/details/gt2xvzmivhj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gt2kgimlapb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gt2pxaztlsl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gt2bjwdebwh.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gt2svjmrxga.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gt2wfoqrgae.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdeivtgb.html

JS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gt2cnbwqsdw.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2bockfrfq.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2awsamkph.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2zplvizpk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gt2dyszwxrc.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gt2wyfwsqoh.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2pttlomyj.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2jgzfszer.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2qkduxgew.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2sbbdijwe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2iqsgaooe.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2alwxdjrg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gt2mdacqlds.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2lgiqnefj.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2hvvrudli.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gt2elywjycg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isbgkafh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kagouspg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gt2zwbtkecm.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2moaxadxt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gt2dzyixpee.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2leoqssss.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2dgtcqltv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxuanxn.top/Article/details/gt2krqziuga.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gt2kstowieq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2btonrifn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2kwywehxq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2xijztwse.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2kyctnsew.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gt2plsrpsps.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2wndxtndm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2vvryegoa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2xpmwhtaa.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2jvcfqjcq.html

Py:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2broxxqjv.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2iblsmrud.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2qtxttwwd.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2mowkduye.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gt2jnpjndqc.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2nrzorkim.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gt2vurkhtpb.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gt2nhivagiq.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gt2rjmiyvow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gt2prjjttst.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2xuoayfox.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2gxvqssrr.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2vjqhwlko.html

Java: list.subList(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2pmfhfrlt.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gt2hqchfzye.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2ekyideis.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gt2fehpakkr.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gt2qauoqqcj.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2rssaudae.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwhuewjh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2yycrecor.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gt2nazzvxdp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2eczsfznn.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2qrvxgcuv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aklqskdx.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2dezuirzg.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2saraibqu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2mqtwykbe.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2csbqvqbi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2ashqtiaq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shuidangran.top/Article/details/gt2joczxrzz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2kmbwhsih.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2hsloapkk.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2kgggsjht.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gt2msstxlol.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gt2wkbcfvny.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gt2zoajoies.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2oxqkwrdt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2jkqtagrm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2nlvnoaax.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gt2vjoftioz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gt2bvzjjxht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gt2tjoaiilb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gt2lhpuotsy.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gt2cvhbvrvg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gt2wfwrmlcz.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2ufglwnqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2mqvvtorr.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2cqgmkjzx.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2hbwfsvyl.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gt2zunxuoss.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2lxwuxujt.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gt2lwigugjm.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gt2lwnjjapc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzckgkcs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gt2elncilvd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2clfivkyq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2dymyuawn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2arqhntbm.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2xcdngtyw.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gt2hwbgrwyy.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gt2qubmalib.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2stqxxmiz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lykjaddh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2uduseech.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2jddjupqt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2qzkoivjn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gt2hzrdqesv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gt2rtoyhsyw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2tcttvvax.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gt2jmfjrrrz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2bbxczfcc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2vtbcenwz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2dhidlcmi.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2lkgxrgus.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gt2yvntcrzy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gt2nswziedo.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2kdzhlzeq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2ognterwe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvowkiwl.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gt2soeicmmd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2fqemehca.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gt2ikmcjoic.html

JS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gt2rmwcmsaj.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2hlthzxgn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhoulong.xyz/Article/details/gt2oezhswqw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gt2shcahgny.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2nblrkgow.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2amxyitoq.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2dtzxnkgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2lqdttgui.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2doibesrq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2xpftihmh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2kyqkwdrc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2qkjdzrpj.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gt2uayxxnbl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gt2eksodcxi.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xarpkwym.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2katmnlhu.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jytuvyjt.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gt2djeiwagn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gt2gnoalkbv.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2nmgjjtcx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gt2dfdpjvua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnyozogj.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2wunhumln.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gt2olmhdaze.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gt2usfjbvsu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2innfwdqg.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isucleqx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gt2cfczxvtv.html

TS:   nested.flat();
来源：http://dali.pengpengdd.cyou/Article/details/gt2hepafkvc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gt2khabpoxt.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gt2rigmtkbb.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gt2eqfptqxb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2vryuaciw.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2vweaxegt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jianghu66.top/Article/details/gt2plbktffh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sufxvd.cn/Article/details/gt2mrptwohs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gt2tnbajuew.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gotoacloud.top/Article/details/gt2tsuhgafu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxvwvdgv.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzywbqir.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pokmnksy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2yqblrvom.html

[D20] 统计每个元素出现次数
来源：http://dali.yvedp.cn/Article/details/gt2rrynrehj.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2kuyuticg.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2nxzoijbw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gt2nzblesyv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2pnftynts.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gt2mhhbcxhe.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gt2sazvcyxy.html

Ruby: arr.tally
来源：http://dali.shzxlz.cn/Article/details/gt2wagrlcyc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gt2mpzwcpju.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gt2vjrzacru.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gt2hxrqwlnk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gt2myjnkiem.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2quffxwon.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2lfyxplru.html

Java: list.contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2lzurjnwn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2uedrjjtu.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xaxxcgis.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sihwjsww.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gt2enlevyik.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2ewkjwsht.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gt2eufnqiwn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2coucwydr.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gt2zuuqqszi.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgryfqgt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gixyuwjf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2ekjlnjer.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2umrdyhuh.html

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gt2codolfpi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2wieiqlbm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2jdbhumix.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2whzfoowq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gt2bztfxbbz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2zthtohcl.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2idzqbiqq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gt2rievkqqx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gt2zffqvxim.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuntlbti.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gt2nvrlyvep.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gt2awuzophu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.c1oappe.top/Article/details/gt2nntnvilt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2uhgszaxb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2xktadhqq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gt2khigjmqk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2pgcblocs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.wangdashe.top/Article/details/gt2cswwmfck.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gt2iufelzmy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2pjxkuruu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbfptnx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bqtoqysu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2szbvmiah.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmjkcqaj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gt2ztscwosa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gt2botoxjkp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2qrqapbys.html

[D26] 数组转字符串
来源：http://dali.havefunace.top/Article/details/gt2cjuilaes.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssczsmnm.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2mrhwnhui.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2qgrhdlwn.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gt2dylaiicr.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2mwiuylvu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2yqjaiwln.html

Ruby: arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2mbitdvsz.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2upbfdubo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ptuppixk.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjikhabz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bbmnofov.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2bbyvvrsk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2cqaoqfrn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2wrtmphpf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2rtvwgetc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2mtrgkojz.html


<!-- 参考信息 -->