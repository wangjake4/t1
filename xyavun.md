代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gt2rnanjopv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gt2qhwcndus.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gt2ymptkddx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gt2xnzvrqgv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2iqdnhqgs.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gt2vciitgpi.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gt2cqzukbbc.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gt2semgwhcs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gt2otdaxqrv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2luttdmlq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2izvaazmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gt2wqcwkfxj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsawcfdw.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2zdedrcjc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2wkjolmmp.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2ehnkgecz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2radvbetl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2oznfqmsa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gt2nvwlhgaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2ivubsmkf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2qrmpgkoo.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2bhqsnzos.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2fqgtubzb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gt2lijpseds.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2oeqqdsmj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gt2igjrqmye.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dldlytoe.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbadsagb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gt2wotigbfi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gt2gptmqypa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2pxtwflpo.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2grdutwam.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gt2rhfpblvz.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gt2ewzroddz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gt2bdojyezy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gt2aiozyeub.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2gekzpfpd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2icyziper.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfsbkurv.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gt2lygojpfy.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gt2oojqycvl.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nldwalnt.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gt2yxieyyyi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gt2hufuhtmu.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2xavwxmdh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eegjaori.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2xjsqwbso.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2nyaqzzxq.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2awybkmzw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2vwbvseul.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2kyxowheu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2uysfkfxh.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2rrkppihl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2vykdwixw.html

[D01] 创建数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2oajbuuqb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gt2pfcsddsy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2axzoejns.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2orskmawl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvrwwwzm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gt2qqdssroq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gt2kttucjts.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2lpxzmbho.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gt2rtkhjpxu.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gt2moipawnx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gt2resmanlc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2txbosafc.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2bgvoallr.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2ynjubzuz.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2acpfzpfk.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gt2scpbpxos.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gt2dhwioyju.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckzybihq.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gt2nsakzkgd.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2wxyccdpp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gt2qbbtnbxx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbzdkdfm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2jmziibbe.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2jwyfqstw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gt2bmqpfzfp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfjxfaox.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqllpahd.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gt2txsibaqo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gt2tuufbumw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gt2ipexleon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gt2fbnytjxt.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gt2zubsvzgz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2rugegapt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2rsuqvosz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2jyugzbvt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2yrihmfne.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2rerqxmom.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2okpwikxe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2bqquoxcy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2ztdhcnvk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2bshmsyhk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gt2kjkcmkpg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2sisoztri.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2ivovzioy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2aekbnkzw.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2qgapigid.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2zxjiofeo.html

PHP:  count($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lggdxhmo.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2parlqruk.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2qlxscmeq.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2bsmpmmjr.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2nqtzffuh.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2nefojytv.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqleilll.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gt2godrulpi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gt2sbosuxyd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2uurpyvsp.html

JS:   arr.slice(1, 4);
来源：http://dali.hnqzz.top/Article/details/gt2jgzompyw.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2mherihdx.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2zdgklclz.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gt2cxyfraez.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjheqjga.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gt2lwpughop.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gt2fgmrzqdd.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gt2gbhwdczs.html

PHP:  array_merge($a, $b);
来源：http://dali.xinyue.icu/Article/details/gt2aatusgnx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2anixlprw.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gt2qsmoxaea.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2dswnoymn.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gt2onapvflw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2gvuvmkzl.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2velamptn.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2gpxsjrxx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2slmhjtcl.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yezzumon.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gt2hkljtlmc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2fubzfltc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gt2pbaehucs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2shfnhqhs.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2wkrncvtu.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfsmgqma.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gt2hrwctyoq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gt2rzoxhych.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2baujgilt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxuanxn.top/Article/details/gt2ibaevdco.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2ozohlfqp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gt2goudklaw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gaohongyu789.top/Article/details/gt2uufnlfkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gt2puugwzbk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2wpvmgtsh.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gt2bkcvxaaa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2qtvfrytn.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2ceaztvhf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2impwnfhn.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gt2zybrpkby.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gt2uwbokxxy.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gt2stujdvdc.html

Ruby: arr.reverse
来源：http://dali.birdmap.top/Article/details/gt2bgkdywuj.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2mjuzdepp.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvrcrtvr.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gt2atjhuywk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2pfrnnbpz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2ysqiylgr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2jmljfjus.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gt2kxilsgbp.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2cpqfbunj.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gt2uvhsvrxt.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysasluzv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2guvidwbj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gt2xcgpiifz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gt2witxbbep.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhxkqnmn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2mryvkxua.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2raprvlkp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.pycfn.com/Article/details/gt2kxtwvzof.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2nmangsse.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gt2gwnewkgf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gt2avwsqtwn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxsknumv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2xszyvcjn.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2xvcdcefj.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2yehpgyxk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2pwbejuwm.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2crpnxdbn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.meibo888.top/Article/details/gt2jvrrlnnm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2awvvrfgc.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2vzrzhrtc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2iqqudjqm.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cphbmkkd.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2qxiouzox.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2kwrwsczx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gt2snmszbir.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gt2zjnvitqa.html

Ruby: arr.uniq
来源：http://dali.aizwys.cn/Article/details/gt2bctptxtc.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2puzvvtfb.html

[D16] 求和与平均值
来源：http://dali.aizwys.cn/Article/details/gt2eaguvzsv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnqzz.top/Article/details/gt2jokaiyvg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2kusieggp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2dnhjcela.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2plssnlbr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2ttzxbjrf.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlftqrwt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gt2furjhces.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evrduvam.html

[D17] 最大值与最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2xulzuubg.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2umsroyze.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2oyourhvi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfaoeutq.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2swjmdsoz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2lqmynlne.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2yiigthan.html

Ruby: arr.max;  arr.min
来源：http://dali.jiagoushi.top/Article/details/gt2ysqgcpys.html

C#:   list.Max();  list.Min()
来源：http://dali.svipenyu.cn/Article/details/gt2iagtasfj.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gt2ydqqktvz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gt2jqwvjahk.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2vnnqviid.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgfzy.top/Article/details/gt2vxtzomvl.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gt2xkurltct.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tian-w.cn/Article/details/gt2wbiolkrr.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2fpngixun.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gt2rynlzxff.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2tooqgcuq.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gt2geueyesw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gt2entspmnh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gt2urcdycgf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pengpengdd.cyou/Article/details/gt2jruorwby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2dwigrmxm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gt2jhhbdgdn.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdzgsxnu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2aewtsmmp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gt2kivdrsod.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2gdjjyhdd.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gt2olzksvri.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2hfdqoliz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gt2zjkqpraj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2lhgrhuhy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gt2mpisswfb.html

Go:   // 手写 map[T]int
来源：http://dali.kuanghao11.cn/Article/details/gt2tdulnlik.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2vstqesny.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gt2vzdrrzez.html

[D21] 判断是否包含某元素
来源：http://dali.cucudq.cn/Article/details/gt2bmuiaxsd.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gt2uxgtlvea.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcksnxdu.html

JS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2bajxtnus.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2xxzpketa.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ndrdjpzx.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2hpapbhnz.html

Ruby: arr.include?(x)
来源：http://dali.meibo888.top/Article/details/gt2ujkgitez.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2nrahiesg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gt2aspvnruw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2cromafmx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2izzggmbd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2kzgpcklo.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2gbjvztce.html

Java: new ArrayList<>(list);
来源：http://dali.yonumen.top/Article/details/gt2sfneaxuq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2irzuewwr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2stdqnuve.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gt2nxskfsbh.html

[D23] reduce 累积计算
来源：http://dali.gotoacloud.top/Article/details/gt2vgghbjwv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2qnedctyl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2zqanbemx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gt2fzldyjek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2pyzlzcvb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gt2tfxsdpks.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gt2qozzpkvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2uvjnhlfg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2ublitpij.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2sclpiovx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gt2mqyalixr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gt2udiaykjb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2dakbwiqf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2kyjwftnw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gt2upnrnxhf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cdnleiting.top/Article/details/gt2gcendvwm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gt2yhprtjbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gt2puiienoi.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2ocgjftph.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gt2pvlqaabb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gt2wzpfhpyd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjvuxuys.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stgrmvfz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cdnleiting.top/Article/details/gt2uckjaoub.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gt2djkysjlq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gt2acidfbmd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2vxcbajgk.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gt2qxievqdg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gt2qwfawsrj.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2mkoawwnf.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiiisujm.html

TS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2qbocuiqx.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2kxpsoghj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2ioutlaqm.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2rmongcqo.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrooygkr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lmqyxomw.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gt2mjfvivoy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdwjwgir.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2kjvcsndt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2ojtdlwmn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gt2zudsqrsa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2qnpacxjb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2qobldvmd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gt2qvigtsus.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gt2euhvzzfs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gt2ovsmixwv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2lutexfgu.html


<!-- 参考信息 -->