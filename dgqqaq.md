代发 wailian999

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtrdxhyphm.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtpuxcevqb.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtsbaloagg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuxming.cn/Article/details/gthvayrtai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtsaoedyof.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtyytrnxxg.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtwgjbyslf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtfvxpoxgh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtqlwirzic.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtpyrxsukh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtyleuplgt.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtvoopnsfe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtccqiozmh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtvecdexnh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtuangxjwb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmggypqkw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtrrgqinai.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtxuujqfdg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcmesbvg.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtclscvupa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtvihmxdhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtyeoibfvp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gtdfgymczs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gthtyfhpca.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhdpwtek.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtkvbzlarh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gtwaqtfshn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gtxiitzgwf.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gthqzyzlgu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtlgdzqexr.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtnspyzdif.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtrbbvsirh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtmbxtkxlx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtjdktdonp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtiweqaqwv.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtbdtqbkbs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtshrkicqc.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtoarfqruv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtbgzfnhwz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gttbujbnbo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtujmrrsuf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtnsrvpsri.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gttczeyydm.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtlokxgqac.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtxmlmeqgk.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtcetebipw.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtgvfeqrdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtbzcndlbv.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdajywhv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtouckswdk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtuuanhaql.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtpcizzgsc.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtmshgiscl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtmnzjkash.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtnvuvcjsy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwtgtqacn.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtzwmnpjyw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjjxmryyo.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtkbnquxne.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtngqaqyzq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtemvuiwuz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gthsvnxtsl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtoftpthny.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtowqtvgrr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtjlzwnrbc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtbiugpqpz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtiuzfgxdh.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gthoqpzxwt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gttgiltvmf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gtglsokvih.html

JS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gthxpgbdbz.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gtwvcwymcr.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtmofmguuu.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtwkqmclzo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gtfscribkf.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpegdtayi.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtpyivefxw.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gtfzpjqowr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gtthqhqfrm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtouihjjhf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnlghgyw.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtcesekcgt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gttqghltwq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtltyrdkew.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtixsndyuq.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtvlqogkim.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gtydyivfxy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtfzitvbuf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtjnjkbjnt.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtkwgquawq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gtxwoatmun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtuaswwlkr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtwemluycu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtynrdoyec.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtxwgudukz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtgbusmycm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtikkctyxt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtyllyymfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtzgrwxzsp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dianchejie.cn/Article/details/gtknozitzb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtjpulniai.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtintsepbn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtszcpslce.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtgagnbwdk.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtauzuqeio.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtmpbyfnfk.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtzpraqdkt.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtfhimezmn.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gttynptcry.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtanhtrlqb.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtqsoutexp.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtxnhbjime.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtjwhqozhp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtdeshspea.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtnqtzqjwk.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtwzewboha.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtjewdrqor.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtlmllftcv.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtwhuntwcc.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfamolfp.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtrdduiffy.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gtqapefehc.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgeoxirg.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtpzyftzcs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtkclbmlci.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gttwrihenx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstnjxtxy.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtttvekecv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gtdofxxmdv.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtqefrilpx.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtqnggyyhn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtlblxfsob.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gthmjmwqmk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtnxphxsic.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtrbokgedj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gttglsmnzg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtyqlslfmx.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtbvletipq.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtgwnmnxhh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gtndgkrabg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtjpxvguye.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtiaoennyj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtnveapvrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gteukcnlvb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtzchypqei.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxuanxn.top/Article/details/gtjneekiun.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtpyhqjxxi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtcqkworqv.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gtcuzhazbs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtmrbgowce.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtnqtskpzz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfawtisgx.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtmpvlzfcm.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gthilslyhd.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtgdoltavh.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsqwukrp.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gthyopxvhw.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtkqhcwixz.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrwtqckv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtzacerkov.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtjbltcsng.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtmgthoaet.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtxuapaalm.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gthewbyvlm.html

Ruby: arr.index(x)
来源：http://dali.yangfankeji.com/Article/details/gtbwecjyfe.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtzzaqlcnx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtumhxpzhn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtdeprjqje.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtdtgeynvv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gtlgmrlpuo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtzdeonkbo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtmezyrsqk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtffcicbcs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtcsqdixml.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtrlvuijsy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtyscxewjk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtventayld.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtsxjolhby.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtxzyacvix.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtyaviwyrv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtkflerxmp.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtvrbhkhes.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtboidixie.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtgqiiucrc.html

[D15] 去重
来源：http://dali.zhixingplan.top/Article/details/gtkricumzc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtyunraxfd.html

PHP:  array_unique($arr);
来源：http://dali.birdmap.top/Article/details/gtjeizkycw.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gttsxpadtd.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gthjmvowqu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gtliphxznl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtepnrvfhl.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtcixjgfvu.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gttndyzxkn.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjesefhq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxstzmjsu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtdnfpohlg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtjhqivadp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtkptalgph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtxhvgojof.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gttcxirpyw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtmqvreash.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmblfihge.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtieocoptq.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpnonshnu.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtedtrygtp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtrzgtmioh.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtspmottth.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtywnurvuj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tian-w.cn/Article/details/gtbuujobmt.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gtvuebmvnh.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtzezkvpmu.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtxkqpymhx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gtkbrmvkjp.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtmwaslakz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sysykeji.top/Article/details/gthlijejgy.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtuulftbou.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtwaotecpa.html

Go:   // 手写双层循环
来源：http://dali.iojbl.cn/Article/details/gthmnbwtpc.html

Ruby: nested.flatten
来源：http://dali.daxiang520.top/Article/details/gtwhyfqgfr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtlfyjbhra.html

[D19] 按字段分组
来源：http://dali.hfpthk.cn/Article/details/gttwwstznv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtiyetakvj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtvcwpywwx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtmwjzwlxs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxyeiuna.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtlfwkygyv.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjackxpof.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtptygtzfw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuetiantiany.cn/Article/details/gtpjkjcfst.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtudyhnwfv.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtuoysbpls.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkjtfcuaa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtnptqvvcv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtzgaacciy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gtovpdxtuy.html

Go:   // 手写 map[T]int
来源：http://dali.gogol.net.cn/Article/details/gtmfzkcdmy.html

Ruby: arr.tally
来源：http://dali.zhiwuduotai.top/Article/details/gtfswcnkls.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtiomuxhsy.html

[D21] 判断是否包含某元素
来源：http://dali.hfpthk.cn/Article/details/gtnsifpoon.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtrzeiduus.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtkxijtssd.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtyhtjtigx.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnakwujz.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gteudrlprv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtrjblwqqg.html

Ruby: arr.include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtfwrxvnkc.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtvhbwldhn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtbqdrarpp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqrxqnqws.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gttaoowiav.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbygsgcre.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtccgfkymw.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gtolutldjv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtgsheeizk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhoulong.xyz/Article/details/gtvgiwbyop.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtlfstciix.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtbiwcfuve.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtzhztgvmd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gticcogsct.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtpffctzls.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtfvypqlbm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtbpgvecxs.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtvrugtdjr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtskiqzdcy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gtdryojfok.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gtluwktcvq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtlnxhlsak.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtsxpljhgs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gthbbpyfzm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gthzrteqbq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmlpaxer.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaplfysel.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyzuclxc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yueranfly.top/Article/details/gtjzenrbpv.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtklnhqcrr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtlchdmpaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtcxgfwqtv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtpzmvpcdc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.svipenyu.cn/Article/details/gtcoexcvft.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgnqzoyrh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgynxewja.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtvyvdydwu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtndtityms.html

[D26] 数组转字符串
来源：http://dali.yuanzhike.top/Article/details/gthrrtilxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj202588.top/Article/details/gtqmmfevbl.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtprrjzikw.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtuzzjcchf.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtzsfunlhf.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtetnvfjkb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gttgcyamvh.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtpepjwdyp.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtzekrmdra.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqhwkugbc.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtyjdywzgs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtedlersgb.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtpkbpgtwb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtxshdesie.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtufgwmyaa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtoapiwxxi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtifvdqecq.html


<!-- 参考信息 -->