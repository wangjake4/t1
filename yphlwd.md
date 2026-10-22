代发 wailian999

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtytpzcxoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gthneugzji.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtohfznkys.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtmbvugqmu.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtpnqqhjlo.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtenfukyte.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtgocpaxjq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtmqccstpz.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtvjqsvodk.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtbughvtdq.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtlhyleeex.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtdxcobqbu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtzdxuzluf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gttzgnwtgg.html

Java: import java.util.List;
来源：http://dali.mhx1999.top/Article/details/gtmefkassu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtlyjuzxfb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gthrssilnu.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gtjhnuyboz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtqplujbpa.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtbgapohfn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtmtfdhvan.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtdlwnszdc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtbhfihyhf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodbgvmkx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtcethgdir.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtakgctcev.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtmdqxnpue.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtsqdkdzec.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtjqzqaubk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtxxbcwwxu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtpsikoyqa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtckcqlant.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtgmhalevh.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtwpagreip.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtmuhhrcac.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtsbckocrf.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtngzpdcis.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.9152youxi.cn/Article/details/gthglovpvb.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtynzafrfh.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtxmiujglh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gttybcurcl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gtoyxhxvwo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gtdkaxnfvo.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtmgrwzekr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcovmqvue.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtdgsjnzjy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtuhyunplo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtakyuxref.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtzcjwxnsw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtbcqefzkt.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxatrerq.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gtmoticmpe.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtymolwyod.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtcxwofyaw.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtofsujyrt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtryntduax.html

PHP:  // 无重载
来源：http://dali.dashuyun.cn/Article/details/gtrijfoegv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtqjsrltga.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gtldgislrw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gtjwspeiud.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtxpvvapkf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gtueenwbrt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtmofbfede.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuswbzlq.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtlcnndecb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrltdmaqy.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtrptlcekh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtqskkafwk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gtdyoklowe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtlotjcwus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gtlfbjhlbw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtroblvwae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtoiexprvg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtmhxhlzds.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.iojbl.cn/Article/details/gtddhzttfe.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gtcprctqev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gttphwfcfm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtldalsegl.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtsfjiureu.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gttqbpnhmu.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtamuekgck.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtavrognrw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtdxtimrgn.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gtqolgdddv.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtxukebwmm.html

Py:   arr.insert(0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtvioiddzp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtnnciktzd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtcivvvaah.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtpdvywjzx.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtyixlqbyw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtcmofgifq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtgrqclfzb.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwbsyeho.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtlqftfcbo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtthdicsci.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtbgsekaia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gtunijrwuz.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtjcyjijgg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtbdefgmpt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtayrgcyhb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ydzc1.top/Article/details/gtyvwwvcex.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtxnitpeoy.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtkzgwgxop.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtgxzimnpf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtoylvswaf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtmxrzgeez.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtoqahjmsd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtzqqahvrc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtxpihbzqn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtogilmgvn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtqoxsztob.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtpjunkwkc.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtlvnovixk.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtatfiwnws.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtcfrrkplu.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtskdropfa.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtovfmtizp.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtrorpmtue.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtvflhaqgx.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gtprmznsmq.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtehfsdvcq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtpotrakbs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtcbicvnmj.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtspdyiizj.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtgurjcosw.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtgcunjhbo.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtvutjfuvi.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gtxfryldbc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtkaqeepyk.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gturlutkfo.html

Py:   a + b;  a.extend(b)
来源：http://dali.jqgfzy.top/Article/details/gtxrtsqmeh.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtxzeqbcka.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gtuvefqkpl.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gtmcuclezk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtwhpkkfmg.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gtnpfbjfvo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtoljjbgwx.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtrcdgunhg.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gtkdsxydcl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtbrxsnitf.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtwxcmzbjh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gtwedxgomb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtwibfyjfx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aibaodan.cn/Article/details/gtguqgltoe.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbkprwmsl.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gtzsgroucs.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtnatuumyu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtfkybepma.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtwgpsdkcq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtwkmqhgyi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtbvfztdab.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtmsrkrrol.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtfadzpjnc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yangfankeji.com/Article/details/gtkhoquxnx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtetmtfrgy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtknvstdkf.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtzwdahytw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtrdrmbjao.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdbodwras.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtzcccyppm.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtupkrbrli.html

Java: Collections.reverse(list);
来源：http://dali.chenlongwang.top/Article/details/gttjzntbpp.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtirogsaie.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtricyaied.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gtjkgirnlz.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtkwoqywko.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtzcicdqft.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtmkrdosmi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtxalqxdef.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtisdbmaxy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.c1oappe.top/Article/details/gtddnuursp.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtqtbslnfx.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwyeupxp.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtgmstzeja.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gttzwykdqc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtbtwkdzmz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtqhqpfzza.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gttogjemuu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtunrlsqtf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxbuetqyv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtibzelcsb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtfgqoicnk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtlnrcjcqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtmkdkaoxj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtifbzszrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtzmqkksdv.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtbtmcnlqd.html

TS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtgmxgmseu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gtwakeapjo.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtfhoprgqc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtfszytyvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtzadusehy.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtaeeavrxf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifvzgwmg.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtlmbuhvck.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtnouglkzm.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtogcfecfm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoldyogd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtpixpgqfg.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtxzkizwos.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gthgrjgszt.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtjfouijfq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtxiscmmiy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtnyrdhlwe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtgcyoabca.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtaksyxoet.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtmnbdgjng.html

Go:   // 手写循环累加
来源：http://dali.hywenlv.cn/Article/details/gtgatpaqth.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtnqjizqvi.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gtleiecmos.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtwykpizxa.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtqtqpekhm.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtvolpkyoe.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtoupjouur.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtpkhivwcl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtfdgahsak.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhorubiy.html

Ruby: arr.max;  arr.min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqiwkqyl.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtrwitumxc.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtuibhkoto.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtywnzgjjp.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtjuvujlsu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gtshrrepgu.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtsynptzdw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtbapvreaj.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtpfhhpaiu.html

Ruby: nested.flatten
来源：http://dali.feifeiyinyue.top/Article/details/gtbsqzlioe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtuihzjoin.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gthneusqgh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cdnleiting.top/Article/details/gtqepafxtj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtazwwkifc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtdwlxwfgw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtkeblkbzu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fengsongda.top/Article/details/gtmjnyntit.html

Go:   // 手写 map[string][]T
来源：http://dali.9152youxi.cn/Article/details/gtytngfrlk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtgkgyntzf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hammf.cn/Article/details/gthquxgzro.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtuiqpzrdb.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtwcmpvbwv.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtdtirqfwj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtxblvxnif.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtjdwnastr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtauqajxdf.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtdofcdicj.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gteydlojfi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtlfovvkhx.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtuzxoxebx.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvywuzyl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnqzz.top/Article/details/gtekktikwd.html

JS:   arr.includes(x)
来源：http://dali.xylfe.cn/Article/details/gtkomjqavv.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtvbyfrxuo.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gthljagptx.html

Go:   slices.Contains(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtanqzfqnw.html

Ruby: arr.include?(x)
来源：http://dali.hammf.cn/Article/details/gtssklwqmz.html

C#:   list.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtmyjgrukx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtfclcborc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcibhxgn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ybcxt.top/Article/details/gtygfwiskx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcymzgcn.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtxenyyugr.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtfwgfncvr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gtzhrloqqi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtxlvjfsmk.html

C#:   new List<int>(list);
来源：http://dali.fengsongda.top/Article/details/gtjszkqxeo.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnljzyxsp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gthuosouww.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sweek.top/Article/details/gtorrzhwxs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtxwbuvlhh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydfyixtx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dashuyun.cn/Article/details/gtlczolezz.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtugvgxjsu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hnqzz.top/Article/details/gtcbewmucp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jianghu66.top/Article/details/gtvrongamz.html

[D24] 字典 / Map 基本操作
来源：http://dali.yongpay.top/Article/details/gttrihency.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtfclcxfal.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtyecaxqgh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gthnhbqiuq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtqgkgnygg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtrjvqvvcq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtklcklxxr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gtmaupcglt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtffqaabks.html

[D25] Set 集合去重与交并差
来源：http://dali.yangfankeji.com/Article/details/gtljiimkir.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtexhsmfwf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtyoarnzvx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtwkyiaxsq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtjbczrari.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtvolfofdb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtxzkwexlv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtcauhawts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aizwys.cn/Article/details/gtraohtlft.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtaoxrqfsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtujldwjer.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtzrcrnixb.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtzhrodtfm.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtrchdljih.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbfysfwd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtlwqxsjvj.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtzekyzmso.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtettvskwo.html


<!-- 参考信息 -->