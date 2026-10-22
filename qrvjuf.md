代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtoqlkmrrf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtwkavarmx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtuhezhwdq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtehwnjgai.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtqbbvnlvg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtwcqggbee.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtnngilrzm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtuiisemwy.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtztsohzsr.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtoxmoxeki.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtlulgcbbq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtkxamopau.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahszeidp.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtoosznhhl.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtmxrurrdt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtmiwmldil.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtmycmqzbk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtohwejpqt.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtslsaaxxb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtqphfvucf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtvfvawhqi.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtrxptrfnh.html

[C12] 立即执行函数 IIFE
来源：http://dali.andypj.xyz/Article/details/gttvnesqey.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtognobqjk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtaysntsxg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtorwhbfya.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtnjclhqxv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtkmdaztqs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtkumdpktn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtjpghyvhe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxhuvngw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gtfhqfufrg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtyvqnfcae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgjantlam.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtwxbpadsb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtjyadcnvf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtxwejvayo.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtjgdpcbfk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtvfmwwnvu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtrdcmhlxy.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtqycubayv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtzzkrtznh.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfdllyse.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtgbqnjxyb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtojrofdwv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gthdufxoio.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtzruwltht.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtpcdgijhc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtbivwzgix.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtfwzertuu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtivgetkpf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ybcxt.top/Article/details/gtiqmrwqms.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtdndugwec.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gtjrpykmhs.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtmwwfloyp.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtnyyzzjbn.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtlmyvewvb.html

C#:   var (a, b) = pair;
来源：http://dali.guannengcc.top/Article/details/gtlpbiagtx.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gtqbtqttbl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gtzjubjjgh.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtamxnomuq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtuayxvcoh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gtvlqmurwg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtmkuzwssg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtskpitzel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtjnnxwdqt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtbdijxzfs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpfxznunx.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gteutiqhsy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyscxwuwt.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gtodeyduun.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtewusiecl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtatgsfdpo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtxuhwkrxf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtpeksozpi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtmqbhibfx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gtaxncssqd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtqpdaasrd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtbjqsgdot.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtvwawyqdw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtqtcbijvc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gtkhvsdcbk.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtollidrrf.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtqfigaldu.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtkzdeaqxn.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtiizfrfej.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gtazfypswj.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtntmxjtbc.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gteeffrqic.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtieyvubxo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtgdjrfjdu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtbowvfsto.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtstzlvmxv.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtqotutodo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtjztgosng.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gtfvvorldd.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gtducdudym.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtpppegqzh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtrxecuyvz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtqbxaqpnn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtbokyacdv.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtouisvtkd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtgzsqfcrz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtqlmlevmz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtrnamgsgw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtrunqyswa.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtevuohife.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtcuetjhzz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtqzayskgm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtzijgjvrr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gttiacnuoz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtqfqubjhu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gtfiimfecg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtkyjkxxxn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtncraszmk.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtarpezbds.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtamhcxisj.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtqdknvvce.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtxgxzsfmt.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gtrtzbvzjw.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtoyzsjjea.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gthmrrntgi.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtarhwiwii.html

C#:   list.Count;
来源：http://dali.hnxiangtu.top/Article/details/gtzhfgbkzm.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtyeivckze.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yueranfly.top/Article/details/gtmcollthi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtipekkkea.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtaavlmklr.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtlnrmwpby.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gthhdetisf.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtemreaxel.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gtxgfiykjm.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtnxwjynyt.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gtqgiqdpir.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtmplrafbc.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtesyshjji.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtfwklbzwn.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbngmtoet.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtehdkaexu.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtafuamzaq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtujljrjbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfwkrzqfm.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtzmtrtxvc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gthxdspegq.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtyzxzussv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtyoquopnz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gthmmwkrpe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtmmdjtmip.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtfatfcokl.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gtfpvbmmnp.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtxxmrhbpe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtjcskqegc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtzhfgunyv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtshnrzypg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtboesmjqg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtddgaigpd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtnfngybtg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gtbjexmttb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtmfjmiyui.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtzniobgpp.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtbezcysyh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtusekirvq.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtianyqwtl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtqmctbjpb.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtyfkbschf.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gttnysgiuc.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgsfvfnvr.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gtgoyspasa.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtzixrafqw.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gtoyqgbajq.html

Py:   arr.index(x);  x in arr
来源：http://dali.guowangkeji.top/Article/details/gtawlayqyb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtvhzfcwwk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthiebsro.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gtfkfzcqmh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gthimqvmbo.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtwjjiepwc.html

Ruby: arr.index(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrqzirxk.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsqvptle.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gthtncwrrr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtpgipajbf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtjqinzyfi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtrsxecipb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtnuagcwsk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nwbrower.top/Article/details/gtqysjcktv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtnybbtbcq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtxuivqpwb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtdqguljmx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gtkavapajn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtyetbihwm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gttmhfhswz.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gteeqbjqpm.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtxgulgpwh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzurimjfu.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtquifcplh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtoijuvqhs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtpgnobeyy.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gtenuycmzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtrtrotpnw.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtdklaguie.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtterbmlgz.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtdltrxfmn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtzfwsiadq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtthvjzngj.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtoyhoxpbe.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtswtxgixu.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtglrbxobj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtexmsyrem.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yueranfly.top/Article/details/gtlmtmisik.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtwdngleda.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtrfwgcoml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtlbenwgjg.html

Go:   // 手写循环累加
来源：http://dali.cashguo.top/Article/details/gtwqxhuhsj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gttaicwnid.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtfnlusewi.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhbxzbqo.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxinkj.top/Article/details/gtrdcdscia.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gtoyajkedv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsduaecjl.html

TS:   Math.max(...arr);
来源：http://dali.andypj.xyz/Article/details/gtsvfhurlz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwwrpfdi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjpixghn.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtabbctdju.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtpzzippee.html

[D18] 扁平化嵌套数组
来源：http://dali.pycfn.com/Article/details/gtvitzezsl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtphmvdajc.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtwerffgwu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gzhubu.top/Article/details/gtxojefiew.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtluizmdoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtnhdedarl.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gthgyzvnah.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrscriduq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daria6918.cn/Article/details/gtgvjbnevh.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gtudftokkq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtinsyyxeu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtwxdlsrgo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gtifsdozqw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtrtyoksqi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gteuqzagqc.html

Go:   // 手写 map[string][]T
来源：http://dali.dianchejie.cn/Article/details/gtxzokctzu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtrvzftiwu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtcqddeabr.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybjjwhhc.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gtpwsibsay.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtjiwdtdmt.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiqtvvfo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtudtazjuy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtxdsbjcrb.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gtqcowdttz.html

Ruby: arr.tally
来源：http://dali.yj202588.top/Article/details/gtqwcdqvmv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gtascrkseu.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gthwpuhked.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gthxbhvpma.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffrfbiya.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpichwhvg.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtwnlgtavb.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtcustycjg.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtyymajxox.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtlbemninh.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtexssymzp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtchfctfgx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.kuanghao11.cn/Article/details/gthhpppyod.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yonumen.top/Article/details/gtfomkxbvy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sysykeji.top/Article/details/gtcjyewszo.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gtoyvjddeq.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gtrvyozvxp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtswizefxv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxuanxn.top/Article/details/gtdtecfljp.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtmsvlagbc.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gttxchgzxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvutazje.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtzymqyfdq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gtqnpblaqm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gttahffgng.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtjpaqpsnr.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gtljfkgmyp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtspjoyxvz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtycookkyj.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtjfgwmett.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtktisgbio.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtmdrewjic.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtawxkyloi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtnwywxbpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtvodilmtn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gthrwcyypa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakjwfxhm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtyceenhws.html

[D25] Set 集合去重与交并差
来源：http://dali.sufxvd.cn/Article/details/gtyhlspthp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtlnucvjlh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtoybmmkhb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtlvplaxjo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtzoziaxyj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gttmiltabn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtmkgjlmsb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtltjbnoxe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtssuvyorg.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtotizkckd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtfgilsxfq.html

PHP:  implode(", ", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxurrlvhk.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtosbdumnv.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtnwdbtzwb.html


<!-- 参考信息 -->