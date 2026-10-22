代发 wailian999

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtappknxzc.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtryuypabr.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtvusvvpqp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtiitesfnh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtioixnrfh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtpfisjxut.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtwefbfnft.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtajebpfbs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtiuuphats.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtfowxgsgs.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtrblhkjyh.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtclwoplcs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexosxvpp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtdmpqyvqn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gthuywkozh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gtefvmcpqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtrrnkjfer.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtdualttci.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtburdnofy.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtucrsotyk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gthmmpfbuy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtrzrosjzn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gtvyftrlrq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtegmhbvlm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtwanfhmtx.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtaztjdxej.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtwblnnvxq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtighgpvfs.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunzoanpb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwahiyzc.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtgwceytwe.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtxkxccimc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtfmlgvmiy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yongpay.top/Article/details/gtyodexjio.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtlvmrpcyi.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtnwewtcvo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtalxwqmhu.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtlsqyxcmu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtbzuoexii.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtpilaqsdb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtmxdssztx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtsefkwnqi.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtelefilop.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gturzgffpk.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtfoavbpur.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtdgqrtuec.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtcsfkrsvh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtuktlaghl.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtmxxmzpts.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtmeteqlxq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtxmufpcqd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaanjoono.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmxthqgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtwqzunwep.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtrebksbpj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsaunlgks.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtyyxdvpzs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxrkuymrj.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtinhuuhkk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gturmgraec.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gthrqzbncu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gturmhdqtv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtlddppumf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtcbcfqanp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtweucmzcv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtjhethhsg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gthtddbzxt.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtposzusnr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtfaifnepk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtrpmwsozh.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtztymdsmr.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtamlnalzj.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gthxnzmqoe.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoigbubv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gtdmgwfdvs.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gttxmilacp.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtcekzvyqz.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtyyowlrxt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtutkhvqkn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtqhhqnjki.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gtqsrjbnxw.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtnustrkul.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtnmfuuhlo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtxwsstoce.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtoiqaempm.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtdedgccsp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtoewqfxcw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtgmtfwsbb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtmnyfywgn.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtjehxykrm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtadgzwurl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtsbhbcjvj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtbdubucqd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtlrapaqrw.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gtjhtqdwqw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtclhnbduu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtaqcvslgh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtdyslgtif.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtlcnpxkvh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtciaebxyp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtixkzdkni.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtxhjkfswx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtasuswplf.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtlvglranw.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtsulcxjhk.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtzxmffmkn.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gttexnlxvd.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtxucctmsi.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtuczjbjtq.html

Go:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxjfymjax.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtaqfqfysm.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinlvedgi.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtsvjlwbxu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gtwjwqgkdy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtyxjpgcia.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtmcutktxr.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjoghvoxd.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtlqhcbwge.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gtrsjqablr.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtycvtvrud.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtqpwpqgsd.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gthmokpwiz.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtvyqjxfjj.html

PHP:  array_merge($a, $b);
来源：http://dali.hysaishi.cn/Article/details/gtnjuvztgf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtsbiqwebm.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtobkbauab.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtftcfobht.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtwkmdyfie.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtkuzuuovz.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gtypjffydb.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtdaipcyob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtupemydps.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtuneiawgx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtxzdoaova.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtmmnnbjlt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtwxbzmglz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpcegltk.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtnxnhvout.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtcjoxdqur.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxmfqpyv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtzjdxuvwg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gtjxwmigmv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtydwdqzpg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtqlcvbgsr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gthdwgefyf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtndswslow.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gttzpdfrrz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtmmdezjbe.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtqopwvpbz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtwffpkiwv.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258888.top/Article/details/gtbghwsbhz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtcwwdynag.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtqqstqtkw.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwzaijtv.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkqydofvn.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtgrrleoli.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtyjfqxxuy.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gthftwfsvq.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtimzdnkuo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtyrbcblcs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtitbbvxng.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtijflngdy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtdmhasltk.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtgufetmcv.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtfwysqred.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gtryvtdtoa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtxoqcflzy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtyqglnjff.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtybbugaen.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtqkpvmcve.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gtagbxobdp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtaydwivwy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guannengcc.top/Article/details/gtwehsvozo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhixingplan.top/Article/details/gtmeyfknnq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtwqlfziax.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtvgeakgdr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtybahdalv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gthanbzdvi.html

JS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtfkwooeux.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtmhbysjzh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtesqcvukb.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmqnqoukr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtqwsggmik.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtxtptqtuw.html

[D15] 去重
来源：http://dali.xziqi.cn/Article/details/gtxxzkyesn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtxteiwglu.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gtyylrxtmo.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtleuaoxoc.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gthlcyffea.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtqlmlirzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gtwxvzffui.html

Ruby: arr.uniq
来源：http://dali.shzxlz.cn/Article/details/gteugztsbw.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtsqhonzwq.html

[D16] 求和与平均值
来源：http://dali.feifeiyinyue.top/Article/details/gtlrqwrkos.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtwnmivvap.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtyakpzhxp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gteowtdzgp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gtjrcuyhzd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtxjbhuacv.html

Go:   // 手写循环累加
来源：http://dali.gogol.net.cn/Article/details/gtxegysbeb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.birdmap.top/Article/details/gtexzyhnmi.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gtvoywjygz.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtendhtsow.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqvbmcfme.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtqiriqitg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtrjroqeet.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtmymcemgl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gthlgrrwxm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtojkqkdha.html

Ruby: arr.max;  arr.min
来源：http://dali.fzhhl.top/Article/details/gtlakibmne.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtpqtwgvkw.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtinhmzavk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hfpthk.cn/Article/details/gtjotabpds.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gtvygkuvku.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtddwzisvw.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtxyowodxs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sweek.top/Article/details/gtghpwkalj.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtizemruqx.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwonqknf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtqgvourgc.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtbviwnprs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqepbpjt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtdogqzybl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtfilcnsxx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtwaumonhd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtjgrdenxt.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtutiniwrr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtxmsooask.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtxiuiwwro.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtucwbdwwn.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gttatbxfdg.html

PHP:  array_count_values($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtijmbnufx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gthbkhflli.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gteukrjmrg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtalyzxtly.html

Go:   // 手写 map[T]int
来源：http://dali.nwbrower.top/Article/details/gtnosillfy.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtgibzujnx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gtnoypeprl.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gtjkuqbayq.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gtlxexgftb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtesnybaxc.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtchqlnqzs.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gteaxgyvtq.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gtqnuandti.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtdwqtjmut.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtzijkuzvn.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtuhogvaro.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjyqshck.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtqazsghzg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtggukuvng.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtuughmsud.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gteiibpeos.html

Java: new ArrayList<>(list);
来源：http://dali.aibaodan.cn/Article/details/gtxxdcwpqx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gthcoaqzrq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gteystntda.html

C#:   new List<int>(list);
来源：http://dali.ydzc1.top/Article/details/gtokfuywiq.html

[D23] reduce 累积计算
来源：http://dali.yongpay.top/Article/details/gthzgtiwew.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gtureslpjq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ehwqpu.com/Article/details/gtargimtij.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtcqclufjq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtboxijmvp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtiefsuagm.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtanozayue.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtqkigyyxn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtknxdhfrw.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gttysivctm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtkhtyrdfv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtweqjjtrf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtmcnofjdj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gteprrtxsb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.0kj1m.cn/Article/details/gtspgpppmp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gtnukcopas.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtkoarhtwf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gtsdmfdyok.html

[D25] Set 集合去重与交并差
来源：http://dali.yueranfly.top/Article/details/gtplyrzavh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtbajxyvxk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtoywzfguj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtmwackpil.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gtzdzgevxm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtlnfeuzaj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtnojdyywk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtgcvksmkd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtghxikkmb.html

[D26] 数组转字符串
来源：http://dali.sysykeji.top/Article/details/gtccgksngk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtcplxhrle.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtnbdffsaa.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtrylcwscj.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gthjrbhsvo.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtitmvwpaj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwwefdqs.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtssxqstuj.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtxusfdcyr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvhfpmwst.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtswqeeklm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyfbdehwx.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtmnjwauwh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmytmtqx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtmdzdehtw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtylludcff.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtzogkpapj.html


<!-- 参考信息 -->