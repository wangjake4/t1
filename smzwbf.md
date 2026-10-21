代发 wailian999

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmdxespw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtflqrmgub.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtnscpzkdm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtkeerulmf.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gtopwmcsxu.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtiftjfelm.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtygosyoeo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtnwmnomwt.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gticbctmua.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtapnaowyq.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtpwsfxsfx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtxnhtpgsk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtnyogctol.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gtvhxbgmtb.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gthabrxiib.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtuquupnlp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtvjjvtbei.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtchmnrckr.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gteinnqsho.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtfbuqmtgm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtjsnycddo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtdslvdxac.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtsmxheyem.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtoifuznph.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtjulziyvr.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtbombutlt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaakniyir.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtpnxzeqxy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gtfwyufkql.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtgtjtjlfw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtamsypbtc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzzlbisqv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtntwxsufb.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtotfnmdrt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtrnnagitz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtvkxxubwl.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarjexoau.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtlzvncbtg.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtgvlivbjk.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtxhzquhnk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gthwpciwfi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gtttvpexoq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtsxhsibhn.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtooxoutog.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtvuydtsst.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtnlifbtdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtewosnhed.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtztltoyex.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gttaasapcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtvldqyvxm.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtqfgjweew.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtmwmfbxla.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtlfrmowax.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gtyqyeowep.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtcebjakeh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtzinqijjz.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbchkjyuf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gtwentvjle.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtkfrxzkvc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtzpgvmtrq.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtxebxajpq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnlqnyzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gttcdnqrll.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbyuwvnvh.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gtbryzdlxr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyxlmsmsx.html

[D01] 创建数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gtoklvfvbr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gthnywhqce.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtrtapgbck.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtsnfwcjyw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gtnwbhvsla.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtdpwwlffi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtvggxyoxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gttvqcivvj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtdommnypc.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gthpyfpevu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gtwvdikhqw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtcflpuakj.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtplvzataw.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtzoqvdvtp.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtqwdaxjxi.html

Go:   arr = append(arr, 4)
来源：http://dali.0kj1m.cn/Article/details/gtvgiuaaip.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtdpgyimmg.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtexuahsth.html

[D03] 在指定位置插入元素
来源：http://dali.tian-w.cn/Article/details/gtxnoktvuu.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gtojmcldnf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gthcobglud.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtyqieudnp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtsocjvwox.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnicrgwwc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtubawffjt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtlcagoajb.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtnpkzzoyh.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtahkwxqvv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtmzuagwrm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gtishjefhk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtgbhmakgx.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gticuweukb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtsoalpdww.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtaigfyfqw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtbcudbsnb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gtyhxtsxys.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnymlofay.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gttzzzjeof.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtcfycrace.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtknbitrjf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtxlwhstrc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtxstgxxui.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtbtnvotgf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtlcfofsqv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gttnupfdqz.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtporlrfwe.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtmgoaclmf.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gthafjkapi.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtaalqlysu.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtdzycetuy.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtnylfteiv.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtpdgjybks.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtaktikobq.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzafaebtd.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtoozqltsx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtemyfhziu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xziqi.cn/Article/details/gtrjmludyh.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtqjtchfwr.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtcgedomtl.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtzxcxyejq.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gtujtqsvec.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gthczwssbf.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtxgelyqbg.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtixmgxivq.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrwkmqdl.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtgvcuegdg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtzrutpvrx.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtzjtwojbs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtxmtirdua.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtqeysoabe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtnsmkjtrt.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gtbsuipuaa.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtruwhhdqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtxwlihsik.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gttgavhqzf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtxofouvno.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtkaghdtyz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gtzzlgcvza.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gthsbtofam.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtenkmfkvi.html

C#:   list.Sort();
来源：http://dali.sysykeji.top/Article/details/gtyeglqjky.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gtobctjoaw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtxzczhqqy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtldeixdgv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtcbbxxlot.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtndaomdlj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtxjysjbjz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtvjmgezmt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtophmupus.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhyaklzu.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtsswxexto.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloidskjx.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthqazzqhx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gtgphwfvgy.html

TS:   [...arr].reverse();
来源：http://dali.nanxinkj.top/Article/details/gtrmrvxriw.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gtotocbaev.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytgxjoix.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gtrolsgqkr.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtzaegsnwg.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtsiyrrfcs.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtswjwwtea.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppriyyub.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtjusrhlcm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gttgfubonw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtwvuiebeg.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtxgqsqqms.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxunvfsw.html

C#:   list.IndexOf(x);
来源：http://dali.chenzaomai.com/Article/details/gtqckgobkz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gtuyymcuwv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtqgvsuwgy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gtejiwumsc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtiifnxlex.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtenbuqcal.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gtrnzrawgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gtphzfsppb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxloqur.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtipaupymo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtedrccwku.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtxjahmxiv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ivvv.top/Article/details/gthjpqincl.html

JS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtahzjtaxa.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlxocgrxy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhgvtsyy.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gtlkzyagxq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtjzwspuoh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtlhzkzyqd.html

[D15] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtkocmzdkf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtfypbqnon.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtaknyhzbb.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtfegpllim.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtcnfkjefc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtfbaklnsx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtdwfxfurc.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtykefsnmw.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkafbhsp.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtpvppfpzh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtjzvjltzm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtdrpegwmv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtdgooafcb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtedkqdkku.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tianlin.xyz/Article/details/gtposmplms.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtjmxgpism.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtidrfdwap.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtwnczicil.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gtgokvfaxz.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtbjnomogw.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gtqzghlyvc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.andypj.xyz/Article/details/gtgpfobnjz.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtfjevwntq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtnosrxatc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtiucdmqbi.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtgeddjhfh.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtisqcrdap.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtrepyeavk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.redwolf501.top/Article/details/gtudrdrqxh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtxbdjbkvh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtpkzpvzig.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtghihnjdl.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj202588.top/Article/details/gtfeydqfqs.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gtsslqxejq.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtroxpchou.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gtaxkwqvkx.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtdpshjnfw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtvmejqpkx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gttynlqqje.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtvrqtwejv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtannrrikq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jianghu66.top/Article/details/gtmtmepzdm.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtdeghvrsm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsgjwqyh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.quarkkingdee.top/Article/details/gtxnzglqho.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtcmatdqny.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtyndreafl.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtxrkhmwds.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtsmlteasm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtzifvkrdg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtkwoaplor.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtezydnvmi.html

Ruby: arr.tally
来源：http://dali.xinyue.icu/Article/details/gtvhygmdra.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yueranfly.top/Article/details/gtstzaxraa.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtaewjzadd.html

Py:   x in arr
来源：http://dali.fengsongda.top/Article/details/gtmrxtwtys.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtsrkyjfck.html

JS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gtpxagyahi.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gtmqfkbexz.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtkueqgsdo.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpxmoampw.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gtfnecoazf.html

C#:   list.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gttohexzwr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.quarkkingdee.top/Article/details/gtfibmydvp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ydzc1.top/Article/details/gtdpdlftrq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daxiang520.top/Article/details/gtzhojjbji.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yongpay.top/Article/details/gtgjlstqmn.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gtjuqnlsqj.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gtofhodnjp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtwozdyfao.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtrrnskwno.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtvjelnaed.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gtilmpppaq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtpevcninr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daxiang520.top/Article/details/gtrukouheb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtfjguthps.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbbcfdtp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtprrhwims.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtykzmefet.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtkrbegyiv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtmyrlssfi.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtvpklyovl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gtueshhfln.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtuptuhhdv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xinyue.icu/Article/details/gtbsdudrtj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtbehtedfl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtdfrbljsz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtxutmjbik.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtlcewpfpy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtdlhrkkck.html

[D25] Set 集合去重与交并差
来源：http://dali.vqdsnc.cn/Article/details/gtmtwewvao.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtypwottmk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gttxgeiovj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlhbbkspm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gtedcrtqms.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtrnilrnhe.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtmueftpml.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtxtnprjgy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtrgggcvnh.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdrwmxlps.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gteohqagim.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtobdsamlr.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtxlftboms.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtickdfjve.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebtihsty.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtxtgmmcft.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gthyoeqkjs.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtvlrcyjtv.html


<!-- 参考信息 -->