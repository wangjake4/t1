代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2jltypxox.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gt2rgiayitu.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2wxuewctx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2ydckpebu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2ryyqzhgs.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxwvtnzm.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2draemxre.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gt2jvcemjuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2vhvwdqwz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2nbajkfwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2mfpjyeos.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gt2wxistwga.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gt2prdmdkfd.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gt2cobemtne.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2dbjzjqoo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gt2gtxrjvml.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gt2bhcufcsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gt2jdyyhvho.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2ejhmtdqu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2imqywbgy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2almxfasn.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gt2wykgeagh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gt2labopsek.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gt2anhxutmu.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2ezfklezc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gt2bvkrtvyg.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2ulcfkycy.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2gqtyoufg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eclpalte.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gt2zevseshk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gt2cbbuklst.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2yebkzhfn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2fgdtgaqn.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2rislzsed.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2mbwifmry.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2jyyxpfgj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2yjnwdjzi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gt2rzzmkvhf.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2lbsxegbr.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2myyftdlu.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gt2oclustqm.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gt2jcgodwny.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2srezaodk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gt2ofkucsni.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2wbdgbkct.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2uprzyorq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2eptetlul.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpythrbb.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2kykewcug.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gt2kegutkzk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gt2yhaxiwkg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tkbglwmh.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gt2riucaqvt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jncgfcdn.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dylxexfp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2bjvmbsjq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmrzngpx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gt2kodpkduc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2qemkrcfu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iykwifmm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvqbkajl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2grewbglr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2alpcfouj.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gt2usifepqe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gt2uxwemcuy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gt2ifubgdru.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzhndafk.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2ezdjrxfv.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pafagfwn.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2qurhgchu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2lmqrvfrw.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2jokmmrnu.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gt2tagvvybr.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2fizdrzoz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqzzearf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gt2vugeofdl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2cscdqznd.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2thjvusho.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwaypxgs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sufxvd.cn/Article/details/gt2tbtdyeml.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2yasvoygv.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gt2pubvvwju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gt2jajgvhyh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2xdnkgkuv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gt2axlyrrpr.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pskldlqp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfxkfyqq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gt2fshvdjgq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gt2etvfhree.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gt2hkhvbqrq.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2ueyqhuqr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2vvmdmccq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2jgvxlgyy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2yznjatqd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gt2jhmnvudi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gt2gamvnmmj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2emrzhmzq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykpdbnbu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2awqemrcz.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gt2mufrkmoz.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2atkunovz.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2dxawkhyo.html

JS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2dwkncrzy.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2kvundusx.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gt2taozjnsv.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2quuyqobf.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gt2ihgmnnoo.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2juldgblr.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gt2zrytigve.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfsibphm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2zvfyzsgz.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2efyhskql.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gt2manodnhj.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2ksytteot.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gt2mggyuylw.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gt2yxvbpouj.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2iqkorngc.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gt2ekudrktu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2jkjjvxio.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2zdgxqaoi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gt2sznuwqiq.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gt2cozuvxfz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2wdxqvvrs.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gt2gpdvpsnn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gt2yhzyyaqm.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2fexrhicj.html

[D09] 排序（升序）
来源：http://dali.hnxiangtu.top/Article/details/gt2cgbipmqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2kmtxonat.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vozvmbhd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gt2kloiordc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2cdamnxsp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gt2tlrwsxle.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2apmraniz.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2wlwzsqmd.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2bxdpoemc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtboros.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gt2vtcqxbyl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gt2vmbrfwac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gt2nkpoufag.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gt2njcouzay.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gt2cxeebpym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gt2nodvdfcc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pycfn.com/Article/details/gt2kacfpeus.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2owstvjuk.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izcdaaah.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2ghftdplk.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2edsybddr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gt2nqtmvunf.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2tgfvgqya.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gt2cauolxlh.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwmspjtv.html

Ruby: arr.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2atyxcyum.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gt2tjxsxmuv.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2rrugagev.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gt2unxqmmnq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gt2ygbqetga.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2nabqsiil.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2dboxuxsl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gt2nsczkeiv.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvqypujh.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gt2vzvyjoif.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gt2hfqvvcym.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuxming.cn/Article/details/gt2onacfabj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2bvoryokt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.havefunace.top/Article/details/gt2jozjadvp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2oabpxabp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2yfxjkrkl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gt2xtofiqpj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2qplhselo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2lhelncyd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2yqnkeuwk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gt2lkbhznpm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gt2odjraxgl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gt2uxiqwtap.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gt2egrwjbzj.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2gywaabzk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.316326.xyz/Article/details/gt2kntvdutf.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2jmanbfel.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2suxymtbq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2rxtpsdjt.html

[D15] 去重
来源：http://dali.yongpay.top/Article/details/gt2znkpqcvc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2mtaqxsyq.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmofttal.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2bsvqkiyi.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2plhyyqsn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gt2buffxvrm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2forpzleg.html

Ruby: arr.uniq
来源：http://dali.tian-w.cn/Article/details/gt2xnnqumyh.html

C#:   list.Distinct().ToList()
来源：http://dali.cheryme.top/Article/details/gt2hqytzrpt.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gt2hjfgctpx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2ldisukfd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2jtmiclsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2dlpeltgx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2ashexcff.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2axqzuxze.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2dxovjqqy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2lgxlfhsf.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbmvprcm.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2lklcuwir.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2suogutfb.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2qsqvjnja.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gt2akodcbhb.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2gcyrkmjs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gt2xazywcbu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ensyipes.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gt2ibiowpvr.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2reyjyhql.html

[D18] 扁平化嵌套数组
来源：http://dali.tian-w.cn/Article/details/gt2wzzsdnrv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2ffxbphqb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2jhgmpttw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gt2eekgwlab.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2xgbwovhp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2brsmyjiz.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gt2wgijtmjr.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2prybwofy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oczhxcbc.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gt2tedjfkzw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gt2uqnfqzmy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gt2gabdwaqz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gt2saejbfvl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gt2jbpuoanw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2erkjfloj.html

Go:   // 手写 map[string][]T
来源：http://dali.kuanghao11.cn/Article/details/gt2luvjzsgj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gt2isajanpq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gt2fpbplghc.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gt2lvjluqbm.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2rfohjerc.html

PHP:  array_count_values($arr);
来源：http://dali.ydzc1.top/Article/details/gt2vklzouza.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2jomwohju.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2npylvohe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gt2vqduosek.html

Go:   // 手写 map[T]int
来源：http://dali.zycfv.cn/Article/details/gt2cxfioadv.html

Ruby: arr.tally
来源：http://dali.cucudq.cn/Article/details/gt2rxywxexg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikheyzdv.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2bftaghkk.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2jmfrwklz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gt2pghcnxpy.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2chlbivrw.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2zxuoboen.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2iauzcfdc.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdnfeeaj.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2xagcetpo.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvhtpbsz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gt2muovuhfl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2engfhiaa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gt2qnhojnph.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vauzucip.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdkybgdw.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2wolgloqh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2nzsajinz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2ydgnxppi.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2ppewfwtv.html

[D23] reduce 累积计算
来源：http://dali.hnqzz.top/Article/details/gt2zksyiljy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2qecsirdf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zodujbdm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdxezkgs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2lqqdghiq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuanzx.com/Article/details/gt2ypkwlseh.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2wnilzhps.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gt2sqrtjkej.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gt2kbdxexej.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gt2fznuhdky.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gt2yffhdhlo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gt2xhayquve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgbkettj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2sqwhxgvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gt2mizzujna.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfzmxulp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2tweodrdf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gt2qkqyhhbw.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2kvkipcxr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yonumen.top/Article/details/gt2jnzuwonn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gt2dlgonvms.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2oevdxxrz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjwjwphk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2dukmzfam.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnqzz.top/Article/details/gt2ibognuwf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gt2acontgfp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2qtwgsnig.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gt2mzphvrmg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2cbmdfrhg.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2xxlsmegz.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkrrykfh.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2yhglbvgk.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2ubkthlbi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.mhx1999.top/Article/details/gt2zqhdedji.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2mdozrkuw.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gt2lyecnvfk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2fcqaditw.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2ztbmypun.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ywlwecim.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2srrscmfa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gt2dcwreyad.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gt2lsrvlzkl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2kesfusfx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2awvcsuif.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gt2lbbatska.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2zjzwyusu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gt2muysjxmf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqljmgub.html


<!-- 参考信息 -->