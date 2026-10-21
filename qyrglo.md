代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtaceuwewz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gthayapkln.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtduokdqcy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtsuykeokq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtyfzbebpg.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtikseotgp.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gtnysghueu.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtgrtdgyzw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gthfvjstyq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtwmpoqoen.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtiqmsxhht.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtdhgfpytr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gthlrosscv.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtznxifyzu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtewtataqd.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gterxtrwrh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtegyosucv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtgvjxnurm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtacepuxmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gteolyvbox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gteckiiior.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtlellyqdv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtwffjjebq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gtjxqaxmci.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtnyfzoufn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtxxejxizn.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtvqczstbh.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtghfpkzyw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtxvmihnjh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtxsvzqwit.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtlufiepnz.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtdtpctczf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtxjotwslx.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gtyhmgjxpd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gthdvegvsp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtxqrcrkcl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtwnpxwwel.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtsrmsjqko.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtjvcffemm.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtsuszmusj.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtmkzuydtw.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gtimwgfhcs.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtlvrsscob.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtmxuvkkfp.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtntuzslbi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtvqogkcoj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtzkuxvsjk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneigczuq.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtaomhxwjb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtgrccnjdg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnjvvyxka.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvnwgeszp.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gttqpnkpum.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtifinwwxn.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtldcnpmhb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtdjlbyfye.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtlpldxgqb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtrpoanufr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtcdptoeyn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtizjcuemk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtlfknzqri.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gthcpwcfjp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtanahxivh.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtvtuxnhxv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtkawpqkjl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtbxifminw.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtaprzcsql.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtftmvqplh.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtcvjeobup.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gtfbrpsjan.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtmwrycymn.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtuuallgou.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtedqguzjq.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtrhyqovrk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtinqpulnq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtvaqhrpdd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttvakgbmi.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gtkykjmftt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtkfetipqo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtaqrlnukx.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtocahxdwa.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtlejmqxdj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtxcjyamaj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmhtyfysr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtxwvsukyd.html

TS:   arr.splice(0, 1);
来源：http://dali.cucudq.cn/Article/details/gtwlbkvhwc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtprywecap.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtuxryselb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtcypeypxs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtptwufcdl.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtsmajkkkl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtqhnehkiw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtmedcxjys.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtjrqbunyq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtaqqnzlji.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtwlienojb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtlckesetr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtzbvcmysy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtehnjssqb.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gttdddobtd.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpeyroix.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdxsdpyd.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtlufjxlvp.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtbrzdcbul.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtmylzjeng.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuinozrh.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtbseihccz.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtnuomsfqm.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtnpcmwena.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtjualgpkx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gtswchxyjd.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtxbrcovpn.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtxhtkmekk.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtofyrglxk.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtphqedqpi.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtgemmocjm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtojgaanwv.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtelkebara.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtolxoptft.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtcqxycbhh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtfgoldiyx.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtjvorgqvf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtungqvjtd.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtmujtoffy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtfbfvzytx.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtsgydeekm.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtidpjhkog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtsbbmkmmp.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtfzpkmxmz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtqxzlqsuf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gtfzsukeah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shzxlz.cn/Article/details/gteadgqqeu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywgcbdqe.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtdkmdifkh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtrmvydoli.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtgvmcduie.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gthzlbbeuj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtlsoqqujn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtvcbjhmyb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuakrokm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtbvldutkd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gttaxtepte.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtimhfsjac.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtmxdlpszm.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtndvitkkv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gtonwlyely.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtahjfteyz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtmltoksac.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gttluunhgl.html

Java: Collections.reverse(list);
来源：http://dali.9152youxi.cn/Article/details/gtiqwxnjxn.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtlvdmnxbp.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtlgunzdxf.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gthlhkmtce.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxibypfpt.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtspbhnxjf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tanke756.top/Article/details/gtjdewpeww.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtumgpqpuj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtheaxjtwt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtznoiaxer.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtjywksyyk.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtuuibihvl.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtcxbdhiiy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmknsosj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtxoqudnxi.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cdnleiting.top/Article/details/gtahfsirmo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtboyenkom.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtxfdngnna.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtnwzncmah.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtuzakfenk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtufvogqik.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtzptyoreo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtysbsgofs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtkehmpqvm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtwtledzov.html

JS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtwbmaxegb.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtiwdbpsqa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtzhusakxw.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gthcynxprr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aizwys.cn/Article/details/gtvhkckcsr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtbilzlpah.html

[D15] 去重
来源：http://dali.sufxvd.cn/Article/details/gtnyxwyfku.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtnkymlath.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gthfvhtjld.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjysxwcf.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtgxapokmq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pycfn.com/Article/details/gtjxvtzfye.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gthxxqpzio.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtuehsmbmh.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gteiobugkn.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtfiududsu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtlpqmguln.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtiuybanfk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yvedp.cn/Article/details/gtyexqvawn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtqmtcofzf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gtdhhbyadh.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gtaadgokuc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtiefcytdt.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtnryxsylh.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gttwypwodc.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtapcspmqm.html

PHP:  max($arr);  min($arr);
来源：http://dali.dianchejie.cn/Article/details/gtdapgkvet.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtihiefxxy.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtgtcrswuz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtdyyemiqv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbbkoekl.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtsgiqlnub.html

C#:   list.Max();  list.Min()
来源：http://dali.dashuyun.cn/Article/details/gtpqgnliep.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtssykjvzv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtjnyzbtcc.html

PHP:  array_merge(...$nested);
来源：http://dali.sweek.top/Article/details/gtruzgcgjc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gtjbcdorxh.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gthwqqmuwn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtbryqeslc.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtxujmexen.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtsrmvmxda.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtpszffffx.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtgpkmbatx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtfcdyevgv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtjbcsjawz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gtloefvbiq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtwijbybqu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtwduhoenz.html

Go:   // 手写 map[string][]T
来源：http://dali.jinghuilouyu.cn/Article/details/gtampsorbr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtuzjktmjx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkyhuqim.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtjfwopjny.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtngrtytiz.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gttkbkjscw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtapckgtih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzjapbgo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtryriwrya.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gtaibpxqvx.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gteujqqdtu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gtnhupmqcc.html

[D21] 判断是否包含某元素
来源：http://dali.nwbrower.top/Article/details/gtjbnlrefa.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtnpxndzoq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzajexdou.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtpjabzkzy.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsojyhzui.html

Java: list.contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtuglmbssu.html

Go:   slices.Contains(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtwtjancxh.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolghghrx.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gthotejzzs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cashguo.top/Article/details/gtvtbuzymd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtuxdavwab.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtnswbuwrp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtzdbxcvpi.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gtyuvnzuzo.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtxsrqffts.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtjaekpdra.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gtzrdvioxr.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtbuhdqlxe.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtsnnorzzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtfspkhmxu.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtsikrxedi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwodvsvd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gtpoqmcqhx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtvbxhbpig.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gthmdnypjb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtqvcdgepv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtzhxlwdld.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtqdnnwnpi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gttzqthnxm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtabjjyzbe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtwvcupadi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtjyvsnqul.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtgmzsjqyj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtogmhvpon.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtsjictgyq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtorcjlkkm.html

[D25] Set 集合去重与交并差
来源：http://dali.yonumen.top/Article/details/gtpotawqaz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtspklblrk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtxvdutknj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtjtyczveq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtxqixbmcy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtanpfwouv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtnznxdqau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gtidbvkqts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtgsaqwdrs.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtpltnkggm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gttlpoiptp.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gttluuvnoy.html

JS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtohiculsn.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtogkbpyzk.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gthykyunpx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtaztdmskl.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtbspdqfsq.html

C#:   string.Join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtdtgsafiy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqtneyftn.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gthnegrvsj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfkjvnlse.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtsyqjcndm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gticxjolvq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtwjmdcwrn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtazfyssuq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtoawvjswn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tian-w.cn/Article/details/gtvmifidsv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtjwbksbcm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shzxlz.cn/Article/details/gtanzkoxub.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmggafnj.html


<!-- 参考信息 -->