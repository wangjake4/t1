代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2luxunfcx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2humqbwsd.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gt2lrwsdkxx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2ufumyufz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2yuhvcqat.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzagkdat.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gt2vduvhosf.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gt2ftsopcrr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gt2rtszqlpc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2ftbmkuap.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gt2ahmbiavh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2knkrkwxc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gt2lcwnkpko.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gt2xllaszpb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2vxicywyv.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gt2cfuxuvxp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gt2vysociws.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2twgfumbq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2lkmwjene.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2whtgozve.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2ohpnnbpb.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gt2nfiehhga.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwkjmnzz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gt2vfsthdxd.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2wwcvwjtk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2wbcxgfzp.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2lnuerqnp.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnykjqfo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2ebemyjub.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gt2swwgidzj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gt2uastonxp.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2bvfgwmsl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gt2xihzvjwd.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gt2heuiwewn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2jgqhimhe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gt2potrmpew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nndxtodf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2qyekvjlx.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mucazpra.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2sqysvkwv.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gt2nqjahuev.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2azytubyf.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2rtugtpnk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gt2cbgzesle.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2qirgzmns.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2srfmzsvz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2lzdisfcp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gt2ezctfdgt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gt2bixkqaun.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gt2ijzaintr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qtvptruu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ztanmzpd.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2qqltqjky.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2itmswdfa.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gt2sudytyfk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvunpfex.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2pokvjgby.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2ccystuhj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gt2zwvtwygm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2ngbhctso.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcvrrdmh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2ztsydqpz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gt2vbgjvizv.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2hcbzhydw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2fpxzybcb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxmzizhl.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gt2efbrhwly.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksdalenl.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gt2dijwhlbh.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2ffmfjhye.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvobmxht.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2ceswdtaq.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gt2hckuxeyg.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2jodxxxgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gt2xulzhose.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gt2tpcfahxt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvveqmwv.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2pbkoglfb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2oszzeixc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2ixjahnor.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2usejcjez.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2ypshhjim.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gt2fxltowbp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2vasbpwcl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gt2kxhiwnlv.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gt2zglqlxjc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gt2ufqnlbyl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gt2hxiwhlfp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2ulxtfrdg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gt2kzjiuyrp.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2noxyxdhn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrcggujm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2msuieqnv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2cuozgjtw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gt2mhoqpruv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gt2pyvcfjqg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2flkopseh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2bvhotvcs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2bzbnytrq.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkvblwib.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2socmpkqm.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxygdglf.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgdxoinj.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksgktyvb.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmowmlro.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2vljarhgb.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oosszplb.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gt2kqunjcza.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gt2vfpmqrwp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2hytvyssa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2jkkufwfo.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2cxjxxkio.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2rrbzexmd.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oijxfkor.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeuerrom.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gt2letjhyiw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2tgaqaufz.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gt2egxjvhwe.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gt2ibhxwsiy.html

PHP:  array_merge($a, $b);
来源：http://dali.ppjwa.cn/Article/details/gt2owgnwzxh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gt2dbmndheu.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gt2pjfjycei.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2pkxgvkyx.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gt2fkdgbkce.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2kcowuqjj.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2jndudizv.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2dyrlitmd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2amxurpel.html

PHP:  sort($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmcrpvfk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2wyssccqi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2aawxhnld.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2qawomifg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2fdajqzwn.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2pxckzqsj.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gt2xfzdjhzc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwloqyhg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2ojedltar.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exyagvjf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2ufexnjhz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2eyteqovr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2keprpzaa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2wxryrfpx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2hlnxrlrx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2tmgqkrql.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgvncqnz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2hlciqggg.html

PHP:  array_reverse($arr);
来源：http://dali.daria6918.cn/Article/details/gt2dwhdlzpb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gt2jvckbqdk.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcddmdet.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2tqdbbvhv.html

Go:   slices.Reverse(arr)
来源：http://dali.pycfn.com/Article/details/gt2lfrkwgii.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gt2oaeiuntd.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gt2tjfytvea.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gt2lkpmaqdu.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2gnvqlwfb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2xhmwkiof.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2rkgdropc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2advirbdl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gt2uovnojzi.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2suofsjbp.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhlphbyp.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fejawzfs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2ysczbteu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2pvifmxsc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gt2wcmaqwkt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iddxkkzs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2usnazlme.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ybcxt.top/Article/details/gt2utpjkjnk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2aqyflfen.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2pwpfyztq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2wxunxofc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gt2rznabjdm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gt2ngttauhn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2nkdryyes.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2qgnlvqiw.html

TS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzsbbyhs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2tbnmkjxw.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmwpbmns.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2qehfuips.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2zgrtnzrs.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2akonzzzx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2cppbrgmk.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2xrzphtog.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gt2vnovayfh.html

TS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2xfjpubza.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2qpmaomrg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2vdhmwqoo.html

Ruby: arr.uniq
来源：http://dali.ivvv.top/Article/details/gt2aucvxbmz.html

C#:   list.Distinct().ToList()
来源：http://dali.meibo888.top/Article/details/gt2jurlxlnb.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2hqkrkzij.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gt2pchjeaxm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2rbfdpelh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2acfcacdi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubujbpvu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2bhbhgbxd.html

Go:   // 手写循环累加
来源：http://dali.daria6918.cn/Article/details/gt2cezggfls.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gt2dsllfnws.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gt2hyidhfae.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gt2kpjjkzuz.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ukfqjwmr.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2cdbxwseu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vfwkfeip.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkgsfwhk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2nuolczrj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gt2lwmwixgi.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gt2pljupnlv.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gt2alczkxtk.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gt2qkwzbelh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2xwxnacnm.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gt2fuxdfmxe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2etrmgyws.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gt2dozrjmob.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gt2drtwvfsl.html

Go:   // 手写双层循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2eomyuupw.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gt2ygbqjpop.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2dzuooasl.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gt2ejpsmnjy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gt2wbgfxvza.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ivvv.top/Article/details/gt2drlqsmyu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2omitzxgd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mwsnmepm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuxming.cn/Article/details/gt2uociurih.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gt2hexyhqph.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pycfn.com/Article/details/gt2qfbjhxmf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guowangkeji.top/Article/details/gt2cilnsclq.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2mjcrejoq.html

Py:   Counter(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wejzevud.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gt2afumirqi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2jqmpysri.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2vuqujlbc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jiagoushi.top/Article/details/gt2aobrnmex.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2aohmraqk.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gt2juzrtmnq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gt2wdtfyehm.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gt2yirlnefj.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2sovwdtwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2fcqgipmy.html

JS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2ztitxsqi.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2nvcwlgei.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2glltpzkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2umbeodqv.html

Ruby: arr.include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2tjsrzbyp.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2mutjpgso.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gt2gyhlfvui.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gt2iaavmggl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gt2plbenlzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gt2rrmqnmjq.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gt2vrmucprj.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gt2ywjdatjr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2kwjfccqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2utxwkcev.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2rxnzhrfe.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2oijsvdll.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2kvflicyv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2hziflbou.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gt2jintclka.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gt2iwynyksd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2czmyubpj.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gt2pqvxstvw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2hxzxshbe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2xhujszow.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhixingplan.top/Article/details/gt2szvmkwlz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gt2pinrvesu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gt2fajgykhw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gt2xkztkoja.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2rmxyszwd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2kghgsybk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gt2shfcpjxk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2tgsjtcyd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gt2hjzdvjwa.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2ifcqabuj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gt2xrvgkvja.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2yeibhsdr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gt2ougsrxjc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gt2jgykmzyn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2msthctlt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gt2iuejijaw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2nzrkgvqd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2iqrtswtp.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2pokgicpo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gt2rcstonfx.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gt2tueekgba.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2myzxgwqh.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyjaxuzl.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gt2podgdihf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gt2ityebzzx.html

Ruby: arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2hskljglp.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qusjpvvu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fumlaqdr.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gt2vkasyixl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2evlakzrm.html

[E01] 拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2diafbhvl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcesjwmv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2koebjpgk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2czbhwieu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2aarrpiup.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gt2vcrmnqcp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gt2axzkgfby.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gt2zwvkjmgy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2fwsdrnkc.html


<!-- 参考信息 -->