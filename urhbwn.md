代发 wailian999

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtrpmcydwt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gthqwutnws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gtokjvbsni.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtyhpsxvpx.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtzkuazgym.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtjytzregf.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtudxiqzgt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtpvnttkic.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gthfjktzjp.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtawqxvqsj.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtoexmnhzd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuetiantiany.cn/Article/details/gtoznqpxck.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtjygedsez.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtdymszugs.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gteqzbzskw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtjyrytkxo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gtmgsxoheu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtnwyffclj.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gtkmvvwgtl.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtkkgeimsg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtulzhnkkb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtthxxxddw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtmqorlmnd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtjgpshpvr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtmyxajxnk.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtbqjjtswl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtswqknuru.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtnwcmreee.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.meibo888.top/Article/details/gttoflwhak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtnigaczjl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gtidxxrlwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtlkptrzrw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfrhermxd.html

Go:   func add(a, b int) int
来源：http://dali.9152youxi.cn/Article/details/gtkdwylobk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gtlofohgym.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtcfblevid.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtjrytzkbb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gtpkfdhzno.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtacygtnah.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtdbmshlym.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtnuyiixan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtbjucavxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gttkusifns.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtivvkoghu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtsyljyqbu.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqrumpmu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtzgkchwbx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtqlnrrthp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtbwofqqao.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtkuriwjiq.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gthzmsbwsk.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtyokezlpf.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtvxvemuhl.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtbwfhymup.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtqbfsjajx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtrxhukved.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtoldzyxgw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtkjyhzyof.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtuuwytybu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtwawlcbyy.html

Go:   // 无重载：用不同函数名
来源：http://dali.ybcxt.top/Article/details/gtolzfluzt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtpuhdojcy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlvqyxdoa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfxkatry.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gttssvhqdh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcjiewayw.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtlvhhtrfi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtkgqllnqr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtkftwvtwi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gtumtmuicq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zdqjudy.top/Article/details/gtutcwexrk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtukgyebcx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtbtrevkun.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtdldptlzg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtymkcoryt.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtimgfoyfj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtxkdmjfrj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtsdnlvgnm.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtlclelhff.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtalobsikx.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gttazhrtho.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtsxpkdfqj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtggeywdmx.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtdbtsnkzs.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfifxprjm.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtinxmgvad.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaugdjvdt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gtipkiilhg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtatmlqqin.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtiwuonqps.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtwypvgwrv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gthfocinra.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtykgfznrk.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtnasnpitf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guowangkeji.top/Article/details/gtjwzclvfi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtbvurrfdy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtkmjxybpr.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtphvxrvoz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtiremtunm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gterbozjol.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtqnaowjnr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtvsxqzxho.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gttskegurk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtzsqyftoi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtoxupfrjh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtcqemoved.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ivvv.top/Article/details/gtexohuvcs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtzaexzbzm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtscskqnec.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtiykbrfjs.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtgfrmhyls.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtzhlsumfy.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzamhvilf.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtflpljvzp.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtnkdboldr.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwvlpnbs.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtcwqazsny.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtpudzedmh.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtbilrrhub.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtfyzsidgv.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtzttzitik.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtqtsalikw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtpaibtjok.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtsmllvvbg.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gthahwpbhm.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtjqobipps.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gttuzpcyne.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gtbhzgoemi.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtmitpnuhh.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gthufvhabk.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqvsgnsr.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gtvxjobaab.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhiwuduotai.top/Article/details/gtvysjqkpk.html

TS:   [...a, ...b];
来源：http://dali.yanxiufei.cn/Article/details/gtjanxjrqc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtpxwvwkex.html

Go:   append(a, b...)
来源：http://dali.cucudq.cn/Article/details/gtiqixatkk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtdmvqydrj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtpeksrxpq.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtjmapwjhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtgalcuwwb.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtuncaqupd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gttxoqupai.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtqpfacplj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtkzodglcl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtfwqzadpw.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtdvprakyk.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gtszxnlvtg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtzzbexzsf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtpbhdizcc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtaypjhwxe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtnplytefm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gteumlliwh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gtuudylakq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtgtnxeymc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtofdvtdsa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gthmempuqy.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtwrlzlxqv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.wangshuangyany.cn/Article/details/gtdwxhtbqw.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrajmqgsg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtnregdxal.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtawzoyisi.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtgpdykvjc.html

Go:   slices.Reverse(arr)
来源：http://dali.sxryk.cn/Article/details/gteluahoiz.html

Ruby: arr.reverse
来源：http://dali.yangfankeji.com/Article/details/gtbznjkmgk.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtyuravlgr.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtqlmribyq.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtqcvnurfp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtlplqltvy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gthttlqkpu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtzpofmnqj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yongpay.top/Article/details/gtimzswwsf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtzzgmcihu.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtpbuvmggp.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gtufdipclu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gtunsiigmn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtwjgbeqer.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtoznjgjkq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtknjeaddi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtyskfrjho.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtiqiyonfa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtlqiknjcb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gttdwsjixx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtzfvtziyr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtgkdqtean.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtouffelfu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhvtseza.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtrckclcdh.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtzbkparzw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwixpzhxu.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtwmrpjpzp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteizydizz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtmlieshog.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtcrziatgc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtvmgfrvid.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtqbleuawe.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtpoebpiqo.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtnepsencs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtnhpegvzv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckzlkgkx.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtrwjdnare.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsvsryryg.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtivgpzohs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gtytooktxv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtnuiqefjc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtaawtzloy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtrmvlpwsm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtwucsulhe.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gtqekrlbad.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtlrzdbtmp.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gtghzsncbf.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtgymrrdto.html

Py:   max(arr);  min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtdevfqxqt.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtrknuvefl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtqrenebav.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtyaueefky.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtablmkuby.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhqstbgq.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpjaszma.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gtubzkeipo.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gttxzsigjr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtekgjdtdg.html

PHP:  array_merge(...$nested);
来源：http://dali.guowangkeji.top/Article/details/gtqskmuddz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtwtlfqhmt.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtryivcjcm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtsrmypiqg.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gtjwpmoqyz.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtigptzfck.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtavvrknle.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtgsjopoyl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gtsekpbsjg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtnefoafia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yangfankeji.com/Article/details/gthezqfwrn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtvwgtaesq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gtuphanfgz.html

Go:   // 手写 map[string][]T
来源：http://dali.sweek.top/Article/details/gtttqcsaae.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhixingplan.top/Article/details/gthxnnvuij.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtkhpxsbdq.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gttzqggfzs.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtciuekzed.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtdgfrclkg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gttpxdgoci.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtwnehftij.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtuqptupzh.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gteaeoarev.html

Ruby: arr.tally
来源：http://dali.chenzaomai.com/Article/details/gtxpjvkxqs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gthkemyvcz.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gtwfgbstas.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtunkaunms.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jiagoushi.top/Article/details/gtihzgfqvt.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gtmdzcvgqz.html

TS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtgeugkadp.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gthensgahj.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtzolcfnqp.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtymvgzbeb.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxiikzrqv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtrozuqkvv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenzaomai.com/Article/details/gttwtpfkbn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gthaiptkig.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjagoddke.html

TS:   [...arr];
来源：http://dali.hnxiangtu.top/Article/details/gtqgskmwje.html

Java: new ArrayList<>(list);
来源：http://dali.quarkkingdee.top/Article/details/gthyzutlhp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daria6918.cn/Article/details/gtrupimgmq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gthtyifobf.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtgasqep.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtictlmvba.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdzelrgzd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guannengcc.top/Article/details/gtycdbxakz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtdabuoodv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pycfn.com/Article/details/gtnzoqflck.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtrsrupbji.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtlxndhctz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtuzpglemz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajfeulgj.html

[D24] 字典 / Map 基本操作
来源：http://dali.quarkkingdee.top/Article/details/gthbxpqurj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gtetrhaqhz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtudsborzw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtgndsutob.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gthncpyyix.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtowvznzgq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtzqbgapzo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtdamvinsj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sweek.top/Article/details/gtwthvikrq.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtfjvcuzva.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daxiang520.top/Article/details/gttfgimwpp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cheryme.top/Article/details/gtfdculssz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtgvjucykj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtkkxtsmxr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtvtawltzs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbljjgbll.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.iojbl.cn/Article/details/gtvqqdttdy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtjpeotvrr.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtdrcerguu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gtaxynyyrs.html

PHP:  implode(", ", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtnwbaxzub.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gthiksulqq.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtjkfnztjw.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gthbzxgudw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtvsrttcsx.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjpdkwvw.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtfrjmsvev.html


<!-- 参考信息 -->