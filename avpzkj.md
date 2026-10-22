代发 wailian999

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtdbuobxnv.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtpoxjgdui.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtrwgbusaw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtzjztwunu.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtxmcoxprj.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtuckupqwf.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtusccxtzh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtcfiwirwp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtvcxmvrha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtxyjjwbiz.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtgmqkqaan.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtetxrgohl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtwadxnajo.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtirduggtu.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gthjfydvwn.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtkluejcwj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtiyzsiewv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtyoluckuu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtlbhtmxxl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtsvbkmjiw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtbxhwgsuk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtyuhzrquz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtdlgrgcet.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtcelrhihw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtcrcyhfrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtjiabivco.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtdttuxglz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtumljpuir.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtytpyxvti.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtjrgwbuiz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtqltskqpo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtqhxvqhev.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gtujuuncon.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gtgfkpyabb.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gttuzcjxgt.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtwroixkxf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtptxkcwau.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gttxlcxeko.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtwaxeebqk.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtzzyrlifs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgndsluef.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtxbmihryg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gttuskxpcm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtdlvvkycs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtiuokigcd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtoyaaqjre.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtksxvfeaz.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gtsyjagiwg.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtyrlokbli.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gtqtthgncp.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gtoupjjvpu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtzmaojhsh.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtojezzlzf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtcuhxbvuw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gthruxgtgp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtrtvyleeo.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyklvhfqu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gteumsnmpc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtijrlnyrk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkpanklyq.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gtbfwttfko.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gticwpwjby.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtxvpnouhq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtwsmlhgii.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtwxxvcnjl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnckmzdv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtqnwgbbhu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gtsylnsjys.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtgapqcyhf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtyiiupehk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtchpqenvd.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtdiyzzfsk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtxcojtsyw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtkqeeznoj.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtaskokakk.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtzpykypaj.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtbvbkqgae.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtxcsqaxwi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gtscodigha.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtyndbxfwp.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtsgufstng.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtaxmxgdcm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfpthzfm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtqqdmtpgr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gteoaqirpc.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtrrgudlnt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtrgmdbzfs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtwpckmxzm.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtbuoetdcz.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtkdfwlaxd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gthpavtviy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtedcfhslv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gteusbphtr.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtgggigigq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfixfurx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtlgvrorbp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtncwdrwom.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtbdldhiuq.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtyzbdetmc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtjkcomtzu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtyfbrzbho.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtqkgmleyw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtwezrxenq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtyrnxmqun.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbeomguh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblexkbre.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtrxhygcpt.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtzguuemyu.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtnqyjidfy.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqzfonxgw.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtmbtwygdu.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtgxghptwm.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gtjtinkjjj.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtrwypyvjn.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gttitzyozc.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gtrdajqequ.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtrgdtzghl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtywqzsyjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtbjjugqvy.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtehgmznhv.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtflftzfcl.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtczqexzxb.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtafmtqyoc.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtdrnoptuv.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtkamrrsuj.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtizofuyqt.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtwuvsgkgo.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtnkrdnghs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtkdejtknr.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtbfbxmrlf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yangfankeji.com/Article/details/gtvhsihqtz.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtprdgjlza.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngipvimv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtwtdwgwgq.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtfdoaxjxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtfmqaydtk.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtskpecaig.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gtfewweyvf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtbpkpqbmi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gtqlkbxoun.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gttwbrzjtw.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gttzppwbwi.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtcwgrnmos.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gthnnnpthq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtahwdknzq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrbjqqbl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtpjpsijtk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtnvpccohq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmsymqtm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtcydbyqfv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtllyggcvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtzcrwvplk.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtviithzpw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dianchejie.cn/Article/details/gtnvjnhqif.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtfusfmwxr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtxumopnfb.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtumrdrhmx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsoitxkz.html

Go:   slices.Reverse(arr)
来源：http://dali.9152youxi.cn/Article/details/gtvzduytyr.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvxpnhd.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtnvmptjbw.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtbypruewx.html

Py:   arr.index(x);  x in arr
来源：http://dali.cdnleiting.top/Article/details/gtmczihffb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqowswope.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtjbrfxgdi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gtcmclanea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gtpotsiire.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtzfmlsxry.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtzzhbfqeo.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtebdqgbzo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtxdphayrf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtllrukuvx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtfjhklkyf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtdipreqjq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtislkynmr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gttgfsfpvk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gthqwmjutr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gtwlvwsbvi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtrohwuzmo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gthfyzcmaj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gttyzpwxge.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gtncculsnc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtavxfeewc.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gthuctoqdp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtdibaipbg.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtnomnrlrn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtvcczsvdx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gtqytbdtsa.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtqgvrazch.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtzcqbefdj.html

PHP:  array_unique($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtygttzbtu.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtzqkbnrzs.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtguyqswey.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtwlgpwrxc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtqbuezcqs.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gtksdblpcz.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtxyarrrqe.html

[D16] 求和与平均值
来源：http://dali.jinghuilouyu.cn/Article/details/gteuvjpvvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtbnuiqyvg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yvedp.cn/Article/details/gtbdcdznnn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxotwswnk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttimnpjud.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtbnghamcm.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gtzcyypjvk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gthmxccxwc.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlmprbnn.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtlbsruslw.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtouukijbz.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gthqlbzxjk.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtcrfjndwy.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhgbnrjz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtqnmpppvf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtzjgynjdo.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtarzffnlr.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtftrhbjek.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtfsfdkzwo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmrkvgla.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtuvjylrnb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangshuangyany.cn/Article/details/gtobksmjcb.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtibnnoujf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjodnztsz.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gtkqmhlgqy.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzmdvkbc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtgiuemabs.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgzrxhni.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.meibo888.top/Article/details/gtgnrmfypr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.snrcjt.cn/Article/details/gtrmmbuctq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gthxkqxpsf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtkbjjtoiu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaifgbag.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gtmjuzhqna.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtllievrdc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtagnfvkwy.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtxazuidyx.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtclnuctoe.html

PHP:  array_count_values($arr);
来源：http://dali.jianghu66.top/Article/details/gtqwqahdoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtqiubtjqi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gtqimjslwa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gtozjlagkq.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtlwvggtpz.html

Ruby: arr.tally
来源：http://dali.zhoulong.xyz/Article/details/gtiicgwarj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gtgndjfayo.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtmlthfuyp.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtxpydjonv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtfppkzkvp.html

JS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtlzsjyydy.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtgmpjjbci.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtvtxkjzql.html

Go:   slices.Contains(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtmllsrklq.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtzhjgkmxq.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtzvykhdml.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtosmrrkzq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtryrzqelk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtgdzhbpbq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gtcnmqxnsb.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gtezalkiwi.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtqsvlocyd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtaxtjhxjw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangshuangyany.cn/Article/details/gthumuzosv.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gtesqgbbrv.html

[D23] reduce 累积计算
来源：http://dali.aizwys.cn/Article/details/gtzctpkqqg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtvswwwgrc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuanzhike.top/Article/details/gttacqpfgr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtszfcohnk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtqdvjijcg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtoeyygdzj.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtyekompdp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gtbzbbgtcr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqmczbgm.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtyuwqodxx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtipiacclh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gtzfzohxoe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtnoiylkfd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtudvacyhs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtzwoltvrz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtsffghjnq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuswajwj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiprsdgdh.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtyuvxufqp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtxolaumkz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gteovtlpfu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtaaunxwil.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtqdpnpqyq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gtcwooyssg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gtmkytiylh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtxhdlvjdv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtddqwuell.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtenwotpbh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.snrcjt.cn/Article/details/gtamqwfxoc.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtyoecwfsi.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtfgkvnmjw.html

TS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtjnskjcya.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtywidnbpr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtnalxeshc.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtkmvudwfz.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtnwcxgzpn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyoipiqxy.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtujmnvaxw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtspzggwpz.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtwmtdrjqw.html


<!-- 参考信息 -->