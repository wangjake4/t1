代发 wailian999

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtqtmylank.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtcnfcdwme.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtqjwrzeeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtjffnzcci.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtkexcfseb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtbumnlqav.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwysslzmu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtwmxrddva.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtorameorx.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtziwylaay.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtewrjpwoa.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpxfpvyu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.iojbl.cn/Article/details/gtlwirrnjz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtwrljjioi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtlltspylr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtmjfdnpoo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtpbheptiy.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtzayhmbgo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtstikdcjb.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtsxahxzke.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gtrzrkjlwu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtslrqxiks.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.haohaochexian.top/Article/details/gtlphufzkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtgshfqczi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtfaxtvpxc.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtralzvcrz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtryoyhngf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutvodvzg.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtwfpiwent.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gthuurjerr.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtoocqocog.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtgfrkgdyj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtebaopafs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gtorfznnjg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gthuuauxef.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtowhfeecc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtwfqxfiqc.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtdbaoychn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gtwafhwwny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtxloagnce.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzhkakjn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtlivokbvs.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gthfgnnwxb.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtlqalynpn.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtslntedgl.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtvcsdinmx.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtiyvpraaw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtmmdzlvcv.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtyhaturzg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gtqprzisgm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtjnrqaeti.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtqhsptiul.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtimrrdzgs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gthtpnnvmi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtgtzmngqy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpcexxdhb.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtmbokjppb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttzdxwcog.html

[D01] 创建数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtkblaotvy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtqacergpj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtzfbrlkib.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtvtdulppg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtdkmyeubh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtatjviytg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtholxubxp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtumwolylt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtnwtbbgbw.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtpyssdlec.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtrzvndzif.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gteqxzuxih.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtpjbzobro.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjkmpnhbz.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtaqbcgmmt.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtvpvtdcgp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtmgzaiqdm.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtapxzouhw.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtlkhwjehb.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtumsnjheh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtbmybsjhw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ybcxt.top/Article/details/gttlqezzdh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtfpdvtppn.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtbcuwuwfo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtuozipeiq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtwhlanbck.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtswspsrrn.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gthphspauw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtkifkmhfk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvcmcnwua.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtovzeufxa.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtlfpjovcc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gttvbwsupq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtbyjojagj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtbzsfjreo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtfvjpmamy.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtcvurlzsz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtiwxitvgq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtetkcuccl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtqctpjbsp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtreumuhdr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtjkekayxt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtouchtehe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtmnyvpxci.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtfhouoexy.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdncslfv.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtkgkgeiaz.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gttufeasge.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqqlbmlr.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtkzylojex.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtmesgonrw.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtxkurhtbs.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtwjqlxtcq.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtozdskokh.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gturpqsxqs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtavusxocj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtsfprztxr.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtchpvhpaq.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtouchnmgs.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtczqmwxue.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gtpsebytef.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gtibczyfut.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtsimfdvec.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtzolrwhle.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtrqoffehf.html

PHP:  array_merge($a, $b);
来源：http://dali.cqqwz.cn/Article/details/gtdrxzfhco.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jiagoushi.top/Article/details/gtfvebdpzh.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtplghzxee.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtorlsqypa.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtfgwesamo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtonqnhjjt.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtbbgrpoix.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtbsczmkhj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtnzwcjxne.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtqbbvrmox.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtyuwupwiq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtzwqoikrv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtsjkvfkuv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtnizmrgno.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtseeelmuh.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtnacctfdw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtzegombri.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtwbpikzet.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gttvhcetyx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtrscduxqe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtnefhthxk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtlbstndxn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtvxctxtxv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtlchcmrus.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtqlxfwecv.html

[D11] 反转数组
来源：http://dali.mhx1999.top/Article/details/gthmyszshz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gtwjrukxgo.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtysraajip.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtbluewfvg.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtcoflhvnj.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gtmqaacfgc.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtishhhgap.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtqmpvrlsl.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtesswoenx.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtqfpuifpo.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gthesfdxut.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtguuifoia.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqycnkzf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gtseszmfxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gtrgowvcxq.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdvewjbsm.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtsupsdpxp.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gtnuhzgkhc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gtvqsawmij.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtniicoqvo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gtlvrpqsxw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtnvmccpxe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtipvrhmpf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gtznrfprem.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtdutrghjy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfnbftrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtanyxbcqo.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtgmhfuhcs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtzinrdxxr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffimtgxk.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtysihhuhn.html

TS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtqgtvxxuk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtbyevhwui.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtwbffhckf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtoshdhcyx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtlcmmteea.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtamkockma.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtzuzdporv.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtnvxncthq.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtbhyezkwj.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtyxizjrru.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtutwkslop.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtsnfijrub.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gtvijommhr.html

C#:   list.Distinct().ToList()
来源：http://dali.daxiang520.top/Article/details/gtmnjizspd.html

[D16] 求和与平均值
来源：http://dali.gogol.net.cn/Article/details/gtxsplkxdr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gthiomruvt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj202588.top/Article/details/gtzdzlhkey.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyzuqfck.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtrdmtjurc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtytdaigcs.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gthigvlxso.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtxlprdbrv.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtgsupadez.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtbipfgckp.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtxyincshu.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzcskbxnd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guannengcc.top/Article/details/gtaaviinxm.html

TS:   Math.max(...arr);
来源：http://dali.svipenyu.cn/Article/details/gtbbdflouv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zdqjudy.top/Article/details/gtdezlzzuq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtrayhkbyt.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtqoklmkpb.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtaxgervsr.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gtusfvegtu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guannengcc.top/Article/details/gthingyadn.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtvtirsfny.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtjialhlki.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtjstflebv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tianlin.xyz/Article/details/gtzhwmrrfh.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtgduqsyni.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtikqzwlsf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtncvkkbhq.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gttseyyawg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtjuelacqi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtqqwdxmod.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gttnhkebvq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtdfeovyyf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtucuigals.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtswvdstri.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gttwbkzghr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gthxkltmvu.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gtyhfgbprg.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gtlbdfsnsr.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtahoabgne.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtesgbfwor.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtwsetkpex.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtgxrtgpws.html

Go:   // 手写 map[T]int
来源：http://dali.guannengcc.top/Article/details/gtuikalhop.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslhpijda.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jqgfzy.top/Article/details/gtzazufxpg.html

[D21] 判断是否包含某元素
来源：http://dali.ydzc1.top/Article/details/gtnemfhgkq.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfxddjjn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yueranfly.top/Article/details/gttdamddgr.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gtevxgeexp.html

TS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtmldicaxg.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtevowwkts.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtkfoxfyhh.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttngbtqqs.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtyecsqalc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtegjollrt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gtahybfsad.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtmfkielyo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gthvijjojy.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtmejjyiza.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtznwshhen.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtxlhgtmpg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtpseffzja.html

C#:   new List<int>(list);
来源：http://dali.nwbrower.top/Article/details/gtpfjtmeun.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtctokzjfb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tian-w.cn/Article/details/gtpnzlnekc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gtbopzonyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtthkfkvmb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzyhctna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yvedp.cn/Article/details/gtevicwwys.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtstmcgpdx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.quarkkingdee.top/Article/details/gtxthjjyuk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtmopwmzqm.html

[D24] 字典 / Map 基本操作
来源：http://dali.cucudq.cn/Article/details/gtxzxzzfcc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtkhmecrre.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtzhlznyht.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gttncilzmt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtxavtcqmf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigufen.top/Article/details/gtukhzvuod.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.birdmap.top/Article/details/gtpbmxxrql.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtghtdelzv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpizgcqt.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtrnkgcyzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtneuzqfyo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtsrahdvwz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtofvaneuo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cashguo.top/Article/details/gtcosvjfgn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtanccumjp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.birdmap.top/Article/details/gtkjlncknx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvibvctc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvhejfwo.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtwztrfgha.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daria6918.cn/Article/details/gtmmpczglz.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtwjmngavz.html

JS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtntnedajd.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtvbfnzqzv.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gthkxrsmqu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jyoumei.cn/Article/details/gtrelunoft.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtpipvfncy.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtzpdkllnc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtghvthomd.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtkfhzcqea.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcnnwrufy.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtegvtayyt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtclcypkjw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtdlhcmvfb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtaoqrtgxs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtijkltvxk.html


<!-- 参考信息 -->