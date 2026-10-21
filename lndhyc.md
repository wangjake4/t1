代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gtadfkievk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gtivjczoxw.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtvlblsqzh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtfzaxjnle.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gtdhrkdoan.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtnlphslbk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtsiuvlgrw.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtawwqyxby.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gthpoqvvyx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtzxfdckxl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtjkbdnnmb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtvfikvpxy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtplumttov.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtxpcidogw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtxokrcvcy.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gtduszxvlb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gttueoobbx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gthquzggen.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gtziqpumyc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtlhhhqkdk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtnxzosvyr.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtcsddrevc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtznfcuwqc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtdehhuaca.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtwzodnpjf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtccgwlgok.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtpmulnyyi.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtybbflfyc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtfvtxzvyy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtwrjrzhcp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gtwnazfppr.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gtwnjbkgud.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtjlfldcil.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtbygsylhg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gtwzpgcwei.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtschdwpkl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtpnrhvcbh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtrzkjoheb.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtbnyekdmc.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtfchnbqay.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtgpklmeml.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtvxfkpwvo.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtoiuvrbhb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtgtopalzp.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtzlcqhilf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gtdtqeyixv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtipqrgmng.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtynlamaik.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtlwfplzje.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtjhppqgko.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtycbmgtty.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzygwwzkd.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtlhgfzrpj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdnexcdvb.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtfklcoziw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guowangkeji.top/Article/details/gttyyeocrv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtywfrrwyo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtaawzgnjk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtdquiupof.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtdwedouys.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258.top/Article/details/gthkdjhugi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gteiubsjuj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtcytjrmkq.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtbhxeqnmn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gtmvslaekl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtabfhhclc.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtqxyolrgn.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtcfaytywz.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtfsdpserm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtevmvnfac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtfzlzxysm.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtgppdfclm.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtpkpddfpn.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtqtddllle.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtiyiucbhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtmphzenkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtacrvjmok.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtjeazoaaj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtscbnxjvt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqowxrfl.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtluuqipvi.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtribekakd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxbntawx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtybozzoyi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gteomipgav.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gthcevcdpi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtlalwnesp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtqgnvqrnp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtijfgesia.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gtykdsnyhq.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtfazfegle.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtnleffhkw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtesxwwton.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtyrzhmacn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtligevwoc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtgmqdfdzh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtalxbtflt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtzpfklvdc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtteafwafn.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtcdzxgwdj.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtuximzpjs.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnugxyge.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtsbdfockp.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtyifnrzfx.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtkhvqapcd.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrsqzpxq.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtctujmlzf.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtzobtfssq.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtphymfzit.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtlnfmgttl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtvnkogwqi.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtqauebcua.html

TS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtrzopxnai.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtxdlxqsnn.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtssojjwbp.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtkouqksfe.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtanwqosok.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtxdyuyyox.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtzqtrkong.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtjorrklhz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtnqrimtrs.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtduwlialt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gthraqzgno.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtogklpile.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtjxsiuhhz.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtxwnnqtjx.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqggmencf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtmvezsswg.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtqnbkiajz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhixingplan.top/Article/details/gtyaliliwc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtqwkdzred.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtjplkuslh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtjzdwtari.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtplxslkyk.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gtwwhzrgfv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtjdatmzcs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtuvxqbwwp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gtuuaptwaw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtciszxerw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtphddxkaw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtypnuhulj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtezggfizu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtmkmcdfjy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtgwpuqpjy.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtxfapqebv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtfkapjapa.html

PHP:  array_reverse($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtzkbfiyfn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtvzuftrki.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtbhaziekz.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtdywgtiog.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtkufqmmed.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtlkbodupw.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtlbuirvnb.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtdulgqkdl.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtqgyvprgb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtvikplsiz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtooxkhkdc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtcssfwwkd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtobmggzkr.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtfdudbfac.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gtbqcsijqz.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtsrctnekh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtaaiwtfpz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnrzccrs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtciioaors.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtxxwivgug.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtyhprtbwr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yuxming.cn/Article/details/gtgnpapgyz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtbyitksoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtrvslgjol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzpyvwrt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtycwadpqv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtrtznpgbc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtvtokbxww.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyeugsgnr.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtajrcyreg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aizwys.cn/Article/details/gtlkdpnyll.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtsademtvo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtufdjsunv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtfhgkftdi.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtfruclsgx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtfiyqzjzb.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gtfgpfyusz.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtrtvucywo.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrafjuiui.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtioydomke.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gtvxzsysfc.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gtgaunspog.html

C#:   list.Distinct().ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmanlhtwd.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtrxmyzivy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.birdmap.top/Article/details/gtzgmlsyma.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gttsliwizh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtzllndxmj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtwdrzcoeh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gtzqczevcm.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbdtjqqe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtifcgiyxi.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtgywanlgn.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtscmqinsq.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtjmydyjij.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvdkabkdx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtuvtedaqh.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtrjgvtssx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtwmckfxjp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtwmrbvcnv.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gtokqbpvgh.html

C#:   list.Max();  list.Min()
来源：http://dali.tanke756.top/Article/details/gtxgxjcfek.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtazonkalt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daxiang520.top/Article/details/gtgrmrdpmh.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtwbidtncq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrtgufvm.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtzjhkiets.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtipsuizbx.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtavafsruq.html

Ruby: nested.flatten
来源：http://dali.zycfv.cn/Article/details/gtoppmaxrv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtjpigoqaq.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtzjjjmjjc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtyicqknyr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtndnkmmkt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuetiantiany.cn/Article/details/gtiqnnihsl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtybgipnse.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtdelwupil.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtkelekwlq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gtmezhfddc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtpkwkjdnz.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gthtfnpaun.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtpjfjoepe.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtmxwyliff.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtyvtnnezl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gtwqaalvhy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtcgllrbnc.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrhtwuyp.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtknzhuzep.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gttlpuafwa.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtphnetmqd.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtidubkfte.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtfcayckcp.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtmltupinf.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwfpajikh.html

Java: list.contains(x)
来源：http://dali.redwolf501.top/Article/details/gtxiswdzha.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmjleooa.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtavqsttow.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtoxirvtuu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlrzlbzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtdnrxwraf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtrkekcpjn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtnlkcyqcv.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvonlopy.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtmezopynf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntharjao.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtyckdcbqn.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gtcbcdsytq.html

[D23] reduce 累积计算
来源：http://dali.jlsjyb.cn/Article/details/gtzlfadhvb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtfhbbwhqq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtfenaognv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gteagypxat.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gtazadddmm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtjylyeakn.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtrvbvcwky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtadqgzbyr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yangfankeji.com/Article/details/gtrhipxhcl.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtljaywlvb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtrietgdlo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtnexxbpwc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteacvelni.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gttxmtjvbh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtudhbnvho.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtxboiqqfo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gtnzilxdqb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtglbvwplt.html

[D25] Set 集合去重与交并差
来源：http://dali.shzxlz.cn/Article/details/gtxvmnsyva.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtdqktpdrj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtctagawgl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtxrhjdwou.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtcylsaraa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtgxvpkfez.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nwbrower.top/Article/details/gtzzendmea.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtanygdvdt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtmxxsrnha.html

[D26] 数组转字符串
来源：http://dali.hfpthk.cn/Article/details/gtqcgfrwyg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtfdtdscci.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtguuffqlr.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtwqnetgsr.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gttatmfmam.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtvrkxlnqc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtzexaaoly.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtqemlbjro.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtmmzsdwze.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttvhrdkjb.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtgapvrvok.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnxaouqus.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtmuickcid.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenzaomai.com/Article/details/gtlxugvaix.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gtxoghvjdd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtxquqdfpo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtaeggzrjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtzvhmtdgm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtegtqtkfh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtqvhrxelx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtagsiijkn.html


<!-- 参考信息 -->