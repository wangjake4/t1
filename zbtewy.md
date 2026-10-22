代发 wailian999

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtcomxxevc.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gtqksgenom.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtdqrviths.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtetfesfjq.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtgakwuwol.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtnamrrytb.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtmrkakydn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtksnnefyw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtnlxcunia.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtqwjynvqz.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtluccymoq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gthzhlwtyk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtykviljtn.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtcpncwcvq.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtbktvrnrx.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtknjyybrn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhongyouzk.top/Article/details/gtynglpdpv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gthdieouqh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtimqzkxle.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtiziybwvk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtfjmcdgrt.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtlkbcxwoh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtkwipnkzp.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtdbozwqkl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtlnctopef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtcfraggeo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtrtzzznfv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtmdudbvhd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtotnmjfsf.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtaajpmkxs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtjwbjbmuo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtcuwvqynj.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshkudbcc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtpohniehp.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtodvbopug.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtmqvvayao.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtrqqqqyel.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtnwscstsg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtqphagwwh.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtkofolurn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtvolootez.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtrgcjrkih.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gthkozcuap.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtwjkoritd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtfpfibxea.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gttyyrklxu.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtudfoerba.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtwcsgsjau.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtukiptqei.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtprappfcv.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtvnuyulyn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtofjqtypy.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtjhcwviob.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtkfhiommm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gteajxdeyn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjxfmbfs.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtxlntcwvg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.haohaochexian.top/Article/details/gtqvqhcyrs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtdpmotvxo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjqafvehz.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gtgrbeieoq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtecgcxpny.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtsvdnatvd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtkchzlngt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtyopgwzpu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtpaskvbbx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtdsczoobh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtlnrqjivu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtenwwahaf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtnahhrcoz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqeqrgri.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtfoyftwtp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtcrbfixcm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtwhlbesww.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtziolmpnl.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtphibnble.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrumothv.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtpzdqxkqe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrckbhhe.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtkgymaxfa.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtaavvgdnn.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyakcrcn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtjuxneyla.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtkymkraan.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtclrellzj.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtklocuavj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtbyndkdtl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtovtkqqac.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtloqohqdv.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtpshhfqzi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gthqzuovjr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gttekywywk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtkgkcxdcb.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvdvnqxko.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gttdirpknw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtqrhhzfly.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjexjzvh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtphfsxbaa.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtttywdqis.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtsfugkzqz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtedaduazb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtyonwalaq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtugeawgfd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtfqmmcdbo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtixdnjjrz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtuocmveqw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtupazmwkz.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtfebpkszl.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtmvrllryw.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtbjypmnpf.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcjmkcig.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtbocnqnaw.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtanunqmru.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtcboztepw.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtzvspkcjy.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtmeuqfang.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtniopmses.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtecwubdtt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtqyefrphb.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtrxinmpfn.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtxcrzkcbr.html

Java: list.subList(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtakteaudt.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gttjxbpcxb.html

Ruby: arr[1, 3]
来源：http://dali.yueranfly.top/Article/details/gtdxuqelwb.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtozymvrnq.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtnkfpvwnf.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtpxociuwf.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtplixaqgm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gtluddcdai.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtsnmpnmfr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gtozygsbov.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtplixfsve.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtaurezbkk.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtumgoydgy.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gthfbgvnzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtvnksbqgf.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gttxpzyypd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtanisktpg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtaaxfzepc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtzrfymnyx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtfjsogkhl.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtpulmkuao.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtigelemzf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtdvwaylrj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtexjjpbnd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtvesbkmeq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtlcqaumne.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtbzjgueyk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtdidotlyj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtscnerkeq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sufxvd.cn/Article/details/gtsizcxghy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtbrdweqdu.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtaqmzbhpd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gtpvbnvgki.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtzwjumsng.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtoddmszcz.html

TS:   [...arr].reverse();
来源：http://dali.cashguo.top/Article/details/gtwfgkeqjo.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gtjqjlubru.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxaarlanu.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gtqohhonlu.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtpryxbkgd.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtkntfagen.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtwcixuwmh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtcdcrjbno.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gthmwtydtg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtpvijqqoa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhongyouzk.top/Article/details/gtoxpogebw.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gthxydxbwc.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtjayuxmhv.html

C#:   list.IndexOf(x);
来源：http://dali.yueranfly.top/Article/details/gtmttlnkip.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtdxnfqljf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtchaekbtr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtkoyzhuqv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gthjhqfeze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gthaiuhngv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtnkuzimgv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtesigegec.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gttcoiqvtl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtlwgpnybg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtjwrdytvq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtozxerbmw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjknukpxj.html

JS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtuybdlphx.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtexoqiclj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtwgjteemb.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtdxmbacmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtozzmwzbu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.andypj.xyz/Article/details/gtqghypkrl.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtdotiwbls.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtmoiomnny.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtnlshcwqz.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gttrvxeoxt.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtzvnxzakq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsfamlfo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtnqaijfgv.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtmmfcyvwg.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gtksupheut.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gttvuynbmd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yuxming.cn/Article/details/gtfvxqphpm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtqnitxmuy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gttnibcngd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtunouxwcv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtaehlftxt.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtuxjceuqw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gthsliuqkl.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtgzxapmju.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtcvyoyune.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtfcchpxyq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwlfdpam.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtrlrteftt.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoubgatzg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtcfzyadei.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hysaishi.cn/Article/details/gtqeekhsvc.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gtbugzilro.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtmaonztcc.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtxuvtukiz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtovurjawz.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtbizunyob.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtmuxlmwtk.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtctpucory.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.meibo888.top/Article/details/gtrwxiurbv.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gtmwbnqwnb.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gteyvwpuxr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtqqgqnzcu.html

[D19] 按字段分组
来源：http://dali.pengpengdd.cyou/Article/details/gtqkcspuch.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqcioppg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbvpjjis.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gtqrkiwkfz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtvbhbjmei.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.tanke756.top/Article/details/gtkkqenrkk.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtwwrpgehk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtcrzjprok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.kuanghao11.cn/Article/details/gtkewezhqm.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtuocsctry.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gtqfrqfvnq.html

PHP:  array_count_values($arr);
来源：http://dali.hfpthk.cn/Article/details/gtvvwfzvsr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gthxkghtbj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtakegalvl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gthnytjjut.html

Go:   // 手写 map[T]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddhlppnm.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtvopyiicn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtnxfzmzza.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gthjwqagyq.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtczoiaaxn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtwpcvpnwu.html

JS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtlmsfuieg.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtnmoawaii.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtinwxyyfr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtnsfcxpde.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gticuwkqql.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtrymehquu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtvucttamo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtlapphqgc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtqpfihidg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdmxoycxl.html

TS:   [...arr];
来源：http://dali.feifeiyinyue.top/Article/details/gtsgibusfv.html

Java: new ArrayList<>(list);
来源：http://dali.tanke756.top/Article/details/gtccwcjlqc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtsmqvmxko.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtwdsgvudr.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtgekjmihj.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtgkysidzw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtvdwawedc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtqcamjlnl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtetilzrqk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtfavlubld.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gteipoggng.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtbvzuupje.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtfqgwyzfx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhzucjnm.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtndotwgtg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtddajzouc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.quarkkingdee.top/Article/details/gtsqbejfaq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ivvv.top/Article/details/gtzafokbcx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gthyspvhjt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtpktqutfe.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jiagoushi.top/Article/details/gtixkejdth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtntlxssdx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zdqjudy.top/Article/details/gtzzmhmxvb.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtdifbozfr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtgpzucent.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hysaishi.cn/Article/details/gtubdbhkhz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtxdzenlta.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtttzxuwoe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtaiecbest.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gttorljori.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtluxyeomb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtczbecwpv.html

[D26] 数组转字符串
来源：http://dali.sweek.top/Article/details/gtwykjpcbw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ivvv.top/Article/details/gtohvkupqn.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtdoyqchbu.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtzpotynzd.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtlgkrsprp.html

Java: String.join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gtbqqsdrxa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.c1oappe.top/Article/details/gtmhvuynrf.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtzopmhxgs.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtxvlwvxup.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkdevvbxx.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gthqwxjyrd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlbonqhlx.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtylbujleg.html


<!-- 参考信息 -->