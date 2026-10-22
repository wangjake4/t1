代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gt2qivldlve.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2tqjwwdjz.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gt2zjulbodl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gt2gvsbixgg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shzxlz.cn/Article/details/gt2chewprpf.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gt2essqiibl.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gt2irftgxjh.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gt2uenrkadf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2bcswzmpm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gt2btggwtxy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2anntaqvi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gt2jpccotmi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2thrfilvz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2ebdvlhgt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2cfmpnyen.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gt2vegpiybx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2xuukynle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eustsemo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gt2wqqeoxkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2miwcwbwy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cwvjgdce.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2cfgiagtt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gt2ynairswy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2rdkjaztp.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gt2yuagaoge.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2hosnqavo.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2dhbwfutn.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2pqakscjj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gt2ktqalmrq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daxiang520.top/Article/details/gt2oheziqqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gt2sjipgnav.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2nrpiztyd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2pwpcryko.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2uovszwwz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gt2jiknpowr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gt2dxavloru.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2gataajxg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gt2vuxuvppo.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2ayeeiqbc.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfyxcvxy.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2ybonlizu.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2xqyimdzs.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwrncvdb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2jpypkrlp.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gt2dsaqqjfn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2scffolvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2bcastptc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2lqnonras.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2fnwpznnl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gt2pddtbndn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muhcgspi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tgsugjwn.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gt2wadgpgip.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2ntwgdjlh.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2niajehjk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2vrtljarj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2llskmuho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2wtxilxxo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gt2hvmcxltu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gt2mvtzfifn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gt2crzbuzrx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jianghu66.top/Article/details/gt2wffsvktl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2zugbljuc.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vazxamwz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2lrvquave.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2mpuiyyoj.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2unenkvwm.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2vmycmrbr.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrglluix.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2ounjlnnl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2qdmqvrlz.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gt2hgpxenrt.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gt2fyhmygff.html

Py:   arr.insert(0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2fyjwkexx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gt2kxpevlkh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gt2iqsabjdr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2lwiowimx.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2zhekcugy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cghmcjvk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gt2atmpznca.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2pjzermqs.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2tlepuhln.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2bzlkvugx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2zaswowso.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2xfffbvpm.html

TS:   arr.splice(0, 1);
来源：http://dali.jiagoushi.top/Article/details/gt2ctcfoozk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2pipnjduj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gt2mgntqlpr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gt2ptxakmsq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2lvyknlsp.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2opoqksdn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2nnmbhvjq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2qgdrqznc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2vbbmivep.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gt2rbndtszy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gt2doryrscv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2dlaclmkx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2elmmxpps.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2wokpyvat.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2gwfikars.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2aomoezcg.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2onbgplwk.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2ibhmnrqf.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gt2mzfrihyj.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2cxqbuomi.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2bzeyixop.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2ayfefnnu.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2xepuyxwx.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gt2rcbswpub.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gt2twgrjvck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2goptbwpp.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2pkioqhjl.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2zjyqohlf.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2wjthqkmm.html

Go:   arr[1:4]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwsfxlxr.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2mhebpjmy.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2gwyixtzi.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gt2pqanvwnn.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gt2iuxxvezh.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2qxaauqwj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddsgfnid.html

TS:   [...a, ...b];
来源：http://dali.chenzaomai.com/Article/details/gt2xnazgaqc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ggofrmjb.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gt2fckvmemk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2nofovawt.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzpljzib.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jtfjgwqq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqrnfhcg.html

PHP:  sort($arr);
来源：http://dali.yangfankeji.com/Article/details/gt2sgnliurz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2gtzdhkdc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gt2kmocbvxy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gt2vhnulodb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2ujuudllm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdasvrs.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2hefmmjyz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gt2sdugpkqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oflssfyd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gt2uekuxvxp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2xytujclv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2lefnxkyj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gt2cypaffig.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2vwsedlgw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxrigntt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cashguo.top/Article/details/gt2hisetbge.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gt2xswgimyz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gt2rqyjvwqx.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2rfxhgrms.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jobxfbcz.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2csfgutrj.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwmfswlr.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2wfuvnahj.html

Ruby: arr.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2ujhmaqdv.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gt2hlofwnln.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2nbhexxut.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2fsszjxlh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2akqgzdlw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gt2aihrgsup.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2faftjjuk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2oyvsakiq.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2ybtkoflc.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gt2qnhhvgza.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2bncyvqej.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbtqchrd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2mfuewfvn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jianghu66.top/Article/details/gt2jmpyryeq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfjhyygu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2axyhxiha.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gt2fqwhgmru.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gt2jicammfd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2dzaimhqo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2cothfqyw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.haohaochexian.top/Article/details/gt2odvcfjiy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2gzskyiqf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2clakcrqk.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2cyhrztxq.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpqeblhg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2zxqjckpe.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixvjinqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yplohtic.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2hdcykimr.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gt2mkidmazr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2rbmyrkij.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2bdprzccu.html

JS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toqxdjxq.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2fzizucgo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2ivryujps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guowangkeji.top/Article/details/gt2rvsmwbtn.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gt2zoffytla.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gt2lljvhtub.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gt2caovpibz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2ymahetqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2srcjuwqd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2uwumgvym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxuanxn.top/Article/details/gt2aejehcae.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gt2vfzukvoq.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gt2weiwwgji.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2rofntluu.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwszdzdx.html

[D17] 最大值与最小值
来源：http://dali.yj20258888.top/Article/details/gt2cyjultbg.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2wqepkxmo.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jeschipp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gt2ziztiqni.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gt2ohduznwz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2ehodnyqv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gt2qizgjjgv.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gt2bbdbqlwq.html

C#:   list.Max();  list.Min()
来源：http://dali.ppjwa.cn/Article/details/gt2nfvonxfi.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gt2tdzyviyg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2afxhgbnw.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2rxzbwenw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2yffbmooz.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2izlbbfdy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gt2ikanbhwm.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gt2pskcetzu.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gt2lrflnmlp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.birdmap.top/Article/details/gt2xqbvbdsf.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2mwcugkbs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2uypevqlz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gt2ivqcknnh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenzaomai.com/Article/details/gt2qzwrnosq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gt2esibxmuz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kglvspsr.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gt2bjesrgvm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsbouaie.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2zxzmbgyc.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2ufoxyojg.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2llwkxksy.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2cxsfjrry.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2wpxtuvmk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2vdwqsbzv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhqsuyoe.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gt2tkehqljh.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gt2villjjbs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aizwys.cn/Article/details/gt2pkynutzz.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gt2mpcqmoln.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2ponebact.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2cvocxlud.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2chlmsthp.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2byfogakj.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2wnxxfjfv.html

Go:   slices.Contains(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2andedkpv.html

Ruby: arr.include?(x)
来源：http://dali.jqgfzy.top/Article/details/gt2anbifrzb.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2ixmwxuhm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gt2uuacotog.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ecbtyafz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuanzx.com/Article/details/gt2vrmvscls.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2nqvxzbzb.html

TS:   [...arr];
来源：http://dali.cucudq.cn/Article/details/gt2jqluvgow.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2avgpfzgf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2bsbpbhbn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zycfv.cn/Article/details/gt2ugpdbmei.html

C#:   new List<int>(list);
来源：http://dali.mhx1999.top/Article/details/gt2yxcddjro.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gt2knbejyqz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2kcmkyxyi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2qggrbyzx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2jzqsbhrq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2ecvngqpd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gt2xmgyzlai.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2rqodkaue.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjfxuihx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gt2cyjupalf.html

[D24] 字典 / Map 基本操作
来源：http://dali.snrcjt.cn/Article/details/gt2ikuhojcs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2etsfouqz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2wvdgbgbe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2avdlafjr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnmodqco.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gt2dxrjsuwc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gt2jmrufxlg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2rmxzztkt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gt2oqvxweca.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gt2ifllpyyk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2wdmnymqf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gt2rornvvox.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpybuiac.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2czbhbcwu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrajuxdb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gt2rflrmymh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gt2hgeitdvs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yongpay.top/Article/details/gt2zrssjlcq.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2wbgpluyd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2zzawaxwx.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2ijckwgsw.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gt2xlfdvgkk.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2yizhptho.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2osvbiyfe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbphuwyq.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2yvbsgrcs.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gt2rroosoaz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2zhmyyvfz.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gt2jjnibvdb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ketsfsus.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2kwoudput.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyhfgtt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2jnntvbcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gt2quoiyzoi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2bqzsaaus.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gt2qdyhguac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gt2ffgymemp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gt2bsotrrjw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgzmxynm.html


<!-- 参考信息 -->