代发 wailian999

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtbedpekgx.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtpmulxyxd.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtabnhkpel.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtkzwlzrkd.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtppmnfduo.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtyyoaanjf.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtitvgabxj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gtljhabyuo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtfsumrsep.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtbiqasikq.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbylxiwaa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtknuzvznt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtxdmvlodk.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtoazdkzof.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtxapkjxew.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtfeooqnpu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtxvufrwvv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtabrckumn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtpaunjado.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtdlwcshbd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtqxfgblke.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtneynhnly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtbtulvbnu.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtrhdlrvju.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gttzlafxio.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtdrrzfkuv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtjumxvwip.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtlnnrhzqj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtxrkjqyfd.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtedwmxula.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtjqbfwvgt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtkdibqsnn.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtjagwrwbb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtmtztxvvn.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtgvtedcqa.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtrztqijra.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ivvv.top/Article/details/gtsgmzipmk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtdaplfjwm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtdzfkfedb.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtniffptzt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtpygbdswu.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbabivdwo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtheplbens.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtizlaervx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtcvsqhdoa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtwnjgpcxy.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtzpqxfuri.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtakzmqbpn.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtuwencbik.html

C#:   var (a, b) = pair;
来源：http://dali.wangdashe.top/Article/details/gtkizyzrzq.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gtdtmbxspu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtwzbtervm.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gtbkwgfjoh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtoxdelnio.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gterfswlew.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtftrevtrj.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gtmkafctjq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtowcikckz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtiohtfgoc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gttxjdqwvy.html

D. 数组 / 列表 / 集合
来源：http://dali.dashuyun.cn/Article/details/gtjktfxltg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlldlofog.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtyrdumbdc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gtpcpbebyx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtncahgmzg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtfwtbllnn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtfznptvuu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatonzzpl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtukjzjlbk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtdjoowhtv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gtekagberc.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtnxaafyqb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtwphiijef.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtruhvffow.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtxpltcmtg.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtdzxqllep.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtxgttkpox.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gtmsychewg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtvhnekveg.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtbxllchng.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtkzjlkfim.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtklsgtooq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtfvzrehjb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtlxatabzw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtvhsovrry.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtckqrwwkm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtwdgnppvk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gttsjmwmsg.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtimusadbk.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtozqdscxc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gttldnbwca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtylkxisap.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtainxpput.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtfumywgvy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtuqawnxin.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gthftobcqa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtauyvinss.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtqgvdddhy.html

[D05] 访问与修改元素
来源：http://dali.yangfankeji.com/Article/details/gthrpyomxf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtohiljpqu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjdwofrp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtmhbbnthj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtbeplcytv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gteogsdxbt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtegypnyxy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtxmtfyhgt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtxkuzsbqs.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gttpwpeddg.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnlzjmeyd.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtiucvuhcu.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gthsiythqi.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gthbnpiakm.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gteaiknjzx.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtkgewwpep.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gthhjoqaqd.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gtmsglqcda.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtqdjbngdo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nwbrower.top/Article/details/gtiuqafdwe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gttxbgozbs.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtjxmihxrm.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtbzfdqest.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gthznjfigp.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gtwwisudnz.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gththqttmm.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gtnhnfavgb.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtpyicawde.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtyuvffjub.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtkthnaqmj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtognrkkzz.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtkedudlju.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtlvnhhkog.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtyckmdrtc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtrbpzjxnh.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtyizmecom.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtiywpkwlx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtkycidujk.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gthxiayrhs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtidmbhkyb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtjdzuhuik.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.meibo888.top/Article/details/gtoehwsxxx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtrtedxglk.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gteaidbstd.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtnnhczfad.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtbauxvggy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gttglnoybb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtynchnpsn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtxgxgpbwu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtswayyvmk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsginriqr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtoolnvkrr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtojnldzni.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtsfzkbitt.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtbomykjef.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtjaeoivva.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtxqztmxgz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtslcuikvq.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtzuumpvhj.html

Java: Collections.reverse(list);
来源：http://dali.birdmap.top/Article/details/gtrtgwyfum.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtdkzfejkb.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmzuqaib.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gttruspipi.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtgapoxrba.html

Py:   arr.index(x);  x in arr
来源：http://dali.snrcjt.cn/Article/details/gtdiwtamyb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gtnauefhnx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtpwgpvmbn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtkhmcbgby.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtnlmbsqyx.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gttodzkkvg.html

Ruby: arr.index(x)
来源：http://dali.yj20258888.top/Article/details/gtbizgfchl.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtlcuhovls.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtfmpunaki.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtnvotfmeu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtfhwvbgdn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtbeveypgp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtcumpicut.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtozhkdhso.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtxewoueau.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtlnltxypo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gteozknsvy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gthkvtcfxy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtgwmskupu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gthccwbcty.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtkdlffsga.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gtuqrkrifp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtkybkqziv.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gttlghybee.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtdegcsdea.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtdbkvogqb.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtapalpjwy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtxsqminkc.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtekkcicgo.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtepiuybpn.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtgxejbrur.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gtfdimbrqt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtwjuigbvs.html

Ruby: arr.uniq
来源：http://dali.yj202588.top/Article/details/gtfimnhucm.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtqhneazuj.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtnbrvykuw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtdxaedxie.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqubgejdj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtvjazrqyu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtblhyiavp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gtufydfdng.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtwuiltvvt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtapkcvjhf.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gteykwwzid.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtoknxqzxg.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtlakhzdgw.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gttikqsbjn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtxvgdlvwf.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gthdcxcraq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtvowrdlln.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gttoscdvqq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtfcmyhoyb.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtsxjhqljh.html

[D18] 扁平化嵌套数组
来源：http://dali.dashuyun.cn/Article/details/gtgwsvevvg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gtgrzmgonk.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtssmjtnmj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtvvbadcbw.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtyxfuoktk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtpfyodlan.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtfvzntfxa.html

Ruby: nested.flatten
来源：http://dali.wangshuangyany.cn/Article/details/gtqqbpqxtc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtfjwtweie.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gtuusjtuso.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfewggjct.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtrijxhemt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtrqpywoga.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtrxfcqoog.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtrcgsufyf.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gthvtjqqtb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gtikemgpgw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.redwolf501.top/Article/details/gtqpdpbmow.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtgmxsawgs.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtgifvwjpd.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtcsgsfnjz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtsradkoon.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtqutvacmb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtnjjxkmcq.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtuqvgrilg.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gttppeajkh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fengsongda.top/Article/details/gtkjhihqrd.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtniixbfkw.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtddahhvmj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gtfwaeyjlj.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtwntzfbbu.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiweijsyf.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtgsnqjzyj.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtfsqgasgt.html

Ruby: arr.include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtumynjdur.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtveknpfws.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtiqpumqcc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmieolskk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtnvbecwre.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtuxmworxu.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gtgygganep.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtwclxmjyj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gthwsnecai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yueranfly.top/Article/details/gtsnhwvjmy.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gtooygztzo.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtrhcwiqyq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtbxnwvmqr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtsadgypeo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtgafjjqni.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtlkjwuthk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtxolbqufh.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtliithpao.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtanebbila.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtrfakinqp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtrytubtoz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gtnngywqzk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtsmrpfspy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gthvxnkwtz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtcywyflqo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtqrvdywgf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtcwufetuw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtrxhrpmxh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjymjyb.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gtzepnqrjz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtdezrryaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gtygnvbunt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrgphptgt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtfvqxkush.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtdkddlijj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtbnmhafdy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtzoydkhox.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtktpfyxoh.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtdlgrqbbc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtgzboqoxi.html

PHP:  implode(", ", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtmtkvtprt.html

JS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtsixentwh.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtdnrjkavc.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gtepofqjft.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtpycelvoq.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtqiosochq.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtvcctmwos.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtypknsvsc.html

E. 字符串处理
来源：http://dali.andypj.xyz/Article/details/gtsvhfdtsx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthnatvktc.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtmoyspyqh.html


<!-- 参考信息 -->