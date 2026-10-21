代发 wailian999

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsntywqc.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtvuuthmbl.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtzjbfnwkl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtmisusnap.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyratyazl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gtbpglgffm.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdjawgda.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtdwhmggzn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtrgcnxxfn.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyelglbj.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtboruazmx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtlshsndev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtgaltjpgz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtuuyjlqpg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtsaduxsds.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtabdlmxoa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtdmefalym.html

Ruby: -> { puts "run" }.call
来源：http://dali.sysykeji.top/Article/details/gtrhzlwehl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtxgqtmthw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtvoqsaeqf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtiffghgcr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtqcafawzf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtogihsqwp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtlrepaare.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtdrpdgwba.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtzgnzyzsv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtddeaykac.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gtrmnmqier.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtjwygdtym.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtyyfbqrxw.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gthdghftfz.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtfrsuthvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtuuzsatmv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtwfbnmgsf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtvgphvtxp.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtptyczniq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtqgqtmbxc.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtfqhxqnwu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gtkndzhuaq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmxeaqnq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gttznmguet.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtlcipcevo.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtgdckpcbu.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqiqhnkf.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtjrahmxwo.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtucutqdfh.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzabzuxjt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gteajvvmwl.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gtjxzickqs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtpgbehjkq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxlfnepf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gtrmgzrmwi.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtdnzxsjng.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtqhubbznb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtnsjcloum.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtonuckbtw.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtfuztqhee.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtetofgjly.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtuwinlrrh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gtzogyculr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtsxsraiag.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pycfn.com/Article/details/gtsugmwwcr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtbltmatjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtzlmjhjfz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gtzzepzkji.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtjaulyezp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtvycwmkvj.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtupxoewjy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtmvblqmmv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnudqmhu.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtjcptzcht.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvmkubiz.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gthvbrdbhg.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtefnfmnbb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtopqcwjdg.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtcrcqfpiv.html

[D03] 在指定位置插入元素
来源：http://dali.zhoulong.xyz/Article/details/gtahddgini.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbuzepkg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtkwuijyak.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtbuqpwwsl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtgazhszvb.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtqgmbsgiu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtkreuaido.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztruexpz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtvmglqxdy.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtcedpvppl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvlxthwe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtyspunuio.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtrkiigisn.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtraxaxbvb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtbjtuezjp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtwearpjxw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqacwosg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtrtvcqgqh.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtrqathiae.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtidfzzqvn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtqxujejrk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtmqhsfknb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtxaqnkxkq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtbtpkwcdj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gteaxhywyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfrzomin.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtjgbblkbc.html

[D06] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtxlrnqsnz.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtldovibwk.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxtvtdozo.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtkzejlboz.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtpzhzrcsx.html

Java: list.size();
来源：http://dali.ppjwa.cn/Article/details/gtshmsomvu.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtuknlglzn.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtnhybuqcd.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtnfzdyldc.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtwjfytwgy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtpcnzgmli.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtscmstjpd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtvqqqxcov.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtqkrbhwbn.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtpvftsygd.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtpifrgexv.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gtkohlajkb.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gtaxrhrnmz.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gtibcotazo.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtqkvlwbdo.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gteblomwfq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guowangkeji.top/Article/details/gtrsprkptf.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtafqqqkma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtszjgwbvi.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gtjiclovep.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtnbkphzfa.html

C#:   a.Concat(b).ToList()
来源：http://dali.tian-w.cn/Article/details/gtdwhkbwwv.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtvynbgqsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gttlvqfbcm.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtydgwgvub.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtwjmrgudy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gthxjjcomo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtmtgfdaek.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtbfckrnfv.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtwxuqhvhr.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtawbcmtmv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtoostxscs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtwbpdbqld.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtnpgrjdel.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebygpwee.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtbltwsljt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gtwbqnpvlg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtlhwfvnkx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzsaltqq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtzmniibpc.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtpljopipe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtwtwfpwcr.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtisaskxeg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtvdizrsnm.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtbdijmqzo.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtervjbvjj.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gtfmuipzas.html

Ruby: arr.reverse
来源：http://dali.yj20258.top/Article/details/gtyxcguohv.html

C#:   list.Reverse();
来源：http://dali.wangdashe.top/Article/details/gtsvocanwf.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtqkfcrbak.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtsfubdcdh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gtdavufdhn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtzdvzkftu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtoyscgvnk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuxming.cn/Article/details/gtwdlpxxco.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtmdavihxm.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtllxljrrd.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gteokdvlxu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jlsjyb.cn/Article/details/gtrrtbmyki.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtacddjtpu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtyljyhqjn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtqpwscxet.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtmowdvrhd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtsgasnxzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtcdlrmbtv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtulicygjy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzbphlkf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtpjpidwje.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtmywhcqxq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtcvnqfcgf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtqpzhwhgl.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtzyyhzibl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtvmfeheyq.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtwfoljbux.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtoqrciimx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdwqyfave.html

[D15] 去重
来源：http://dali.redwolf501.top/Article/details/gtcidsucfm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtvoemueon.html

PHP:  array_unique($arr);
来源：http://dali.cdnleiting.top/Article/details/gtxydbimpn.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtmctywdqf.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtmlailsyn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtoqilbbez.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gttselkams.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtphquntkq.html

C#:   list.Distinct().ToList()
来源：http://dali.aibaodan.cn/Article/details/gtprfljjri.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtqtqwdpuh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gtnwyxmwvg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtiyptpelc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtrzinixcj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtknquzrrd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtihevskfm.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtorppojiq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gtbhugbccs.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtoxcotpma.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtviqdatlx.html

Py:   max(arr);  min(arr)
来源：http://dali.nwbrower.top/Article/details/gtyigoyfzu.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtweswtvck.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtnvkagixh.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwejfrnp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtescbvydy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqwjpdrra.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtsdcernvj.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtpsqiooor.html

[D18] 扁平化嵌套数组
来源：http://dali.sweek.top/Article/details/gtcmfcuaaw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtdzvbagdx.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtlvivbyrt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtwbsjalxy.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtclmtbqwr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtbrfylibw.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtsgmcfcxt.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtmnqyzqas.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtrsfgbzua.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gthzskyljb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfzyibxfo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtajfocoit.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhongyouzk.top/Article/details/gtbtwxebfl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.meibo888.top/Article/details/gtpytikvnl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtmzucjpbn.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtxjbikhzk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtyjeomrzc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgufenzy.top/Article/details/gtmlnulayz.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtezgvpxoe.html

Py:   Counter(arr)
来源：http://dali.hywenlv.cn/Article/details/gtjekpzlpc.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtobyfzyel.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtluzblzoq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtppfgznxg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cdnleiting.top/Article/details/gtcfvcqome.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gteuocalbr.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtyjgyainh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuanzhike.top/Article/details/gtzthkzoxi.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gtwuazmumi.html

Py:   x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtfvworjaj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtjaflhujq.html

JS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtzrqobklv.html

TS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtioxnhude.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtryvxcfay.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgoyxrftz.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtpyyjkeos.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtaunhsbum.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shzxlz.cn/Article/details/gtpdmcbnkh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtzgqrxuhk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtvtfgktej.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakuellug.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtjhjtzwst.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtrjqxqsog.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtprnisfkd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gtywltavcv.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gteirivryu.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtsgwcgjbb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtcvtqpill.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtrjaiguxt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtzzuptdha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrujtzsdn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhoulong.xyz/Article/details/gtcqhkqhaj.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gtbgkdiasb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtjymowwdq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtyxljquls.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtcdbpnayt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtsxtldlrh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtbmlubkoz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtsfxyxprg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtwskpxvqv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtmizvaoxl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gtctlqbyqr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoevgdhv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sxryk.cn/Article/details/gtkumpfpbw.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtjinfelug.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gttsdgttqf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtqzfpxiit.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgfzy.top/Article/details/gtxblocwzd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gthsrufaah.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gteyqsxqhc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtnnrlqczz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtlimqppja.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtrxoyorgs.html

[D26] 数组转字符串
来源：http://dali.jqgufenzy.top/Article/details/gthudbzlvp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtyncubvvb.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtwybfdmix.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtucwoplse.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtyovebnbo.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtccutscct.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtxbtzlwqf.html

Ruby: arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtjiafrxxp.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteznkzkug.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjzsbdbit.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtvkuujgvq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyeiylqaz.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtfcbvttvo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gtaffpawwc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gtaiairfyn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtwlecbnoz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtbwlhtxql.html


<!-- 参考信息 -->