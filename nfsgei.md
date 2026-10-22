代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gt2kkgrslih.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbvoglfz.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2jpmlepqq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2jgxmjqdi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gt2qovrxbyu.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gt2tbftgtoq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2vauuuvhw.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gt2geukldut.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2rhqrwobe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2llqwihbb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2vegsiian.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gt2resbfugo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuknodfj.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2nvdwuppt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2mnjuzfeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gt2rvagbzwy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2bozjoqwd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2doqnxdjp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2hnxdabeg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2miajcldd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2eceegqnc.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2jfmepceg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2iytxqwya.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gt2apbvxbfh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuqtnok.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gt2twerpybr.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2uwmobsam.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2irpnqyve.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2egykwwss.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gt2qityksms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2gadqotdq.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2ajsyrsjc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gt2myfoyrwm.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2dkqglsnt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2mbrachnu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2awlhkejn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2blhmrean.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gt2yrjkldod.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oscntnsw.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gt2dvweqlgu.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2lofphaum.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gt2rpwfzetw.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2ygntrivm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gt2wktweopn.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gt2wihpvtbh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2xozibsnm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gt2peirqutt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2fjsqutgd.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gt2oxdvpcnd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gt2meeregce.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gt2ijhgpkuu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oponybdy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2mhiwmdvh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xdqypvys.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2qrrqmtte.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2iwciojpf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2jwzdbukm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2trptvgbb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2dxwurxuj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2cnnswzqo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gt2azflzsey.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2pnpzarba.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gt2utbutvrj.html

[D02] 追加元素到末尾
来源：http://dali.tian-w.cn/Article/details/gt2dsgsfoea.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gt2zsbfgxcp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2okakniyd.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2mnpxpgrx.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2uoxhgvkh.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2jfrjxngv.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gt2nzjnjkkv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gt2lwljoosp.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gt2gvrirdai.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2qqdkdgzh.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2vdwjkptk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2zfgteyxf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuierozm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2zopmgrol.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2esgckufj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2khsgzsxs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2umcgyqrs.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2dpwrsywj.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfpbwlil.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2esceokjh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zipbissp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuanzhike.top/Article/details/gt2gknhcqyf.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2kkupvjnu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2qaraekvs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2vqzugqxd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gt2ynczcmkw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gt2qpwamver.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2izlqsymg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2yevpitzx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzsjwrvn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nninwmul.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gt2netpnutr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gt2mbmmeqmu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2ebzmmbrw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2tnoqvjxu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2yurqtdsz.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gt2pmnfmbop.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2avrstyal.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2wvoomwjn.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2cdrmzghz.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2jhsvzttx.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gt2ibgyxfqp.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2tizsserv.html

Ruby: arr.length; arr.size
来源：http://dali.chenzaomai.com/Article/details/gt2uivfizfq.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gt2qicnfxgr.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2hporsbhv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2yipopugw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gt2gsnptqeq.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gt2muggmykr.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2bteyzhgo.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2mbxcddpi.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gt2xcccfgrw.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2yjhoyywc.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2hppojooc.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gt2yzleovyb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gt2mohjqucu.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gt2mppxnfun.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lebjovyw.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gt2jcihknqv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2goinqrvp.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gt2tstevszd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gt2qorbsqyn.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgjourja.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2mcgcokpk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2mognvpxh.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2lcnnifcj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bebkpkko.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gt2vuitayqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gt2lrpwepqv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2wqilaclx.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2jqefhckk.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2psnehwvo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2xdznkqqe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofsxocvf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2bduntedm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2orgxkzol.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gt2vqbxyvzw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2suiemnja.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2amhejznt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gt2lhrsqkuw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gt2dkuhukgz.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2rjteygrr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2sxmvlmii.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gt2nacusref.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnzxsqlm.html

TS:   [...arr].reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2rawjmpcc.html

Java: Collections.reverse(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2bqqcrixx.html

Go:   slices.Reverse(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2hmdwxthr.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2khzlpjet.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2xeiuqvvs.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gt2uhjomcua.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2zzdxowqi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2nazeqwam.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqdzanpu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2lmrzuszv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gt2vggmxkcf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2slcurbrf.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbithlvg.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugyxdjwn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2zuodtsxl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jianghu66.top/Article/details/gt2kmfinoow.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2ucjckmtz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2lyihqtis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gt2irokhwld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2gttlgrzw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrnoelzh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzxjnlof.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gt2xdmfpuhi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gt2vxxgbvvi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2lziccwhn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2bvfwcpsp.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2mfltrpni.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2tlzfdzbg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2jawmuslh.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlsvmtex.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2idupyqoz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2ntmlffsl.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gt2epohgrtb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2mbjkwvxn.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gt2wqljsdrg.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2ryhzlehe.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2esdulxrs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gt2ewjxddnj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gt2dpmyggxe.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gt2nyrecxhg.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2qdgjeydq.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gt2rdbxgdcm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2fbehnwau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2gykmradn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2omzzfwhs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gt2uyceveex.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gt2olsyaxmu.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gt2jokfqunr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gt2atofoiqr.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmtefrsn.html

[D17] 最大值与最小值
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbjmeqkn.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gt2syhdswkw.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gt2fccyswgo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gt2ktasyvvl.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2dkscdwkp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2itdcrqnk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2uqhlabza.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gt2ivnblllc.html

C#:   list.Max();  list.Min()
来源：http://dali.cucudq.cn/Article/details/gt2xpboklzg.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gt2qdxfhqwo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zycfv.cn/Article/details/gt2vvgznfdv.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gt2wpdjhhgt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guowangkeji.top/Article/details/gt2rckcicor.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gt2fdrdshzd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2ekisfvax.html

Go:   // 手写双层循环
来源：http://dali.cdnleiting.top/Article/details/gt2fbceavgb.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gt2xqjnsevr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pycfn.com/Article/details/gt2uyhvgwbm.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2ppyyuvpk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxcnhqes.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwryfvny.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gt2lwzuvmqz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gt2xweibhzq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2bwydowtn.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gt2cmxxwreu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2srnvviuv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gt2ufpvffqz.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gt2kkmddhsv.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gt2odocqodx.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2odhizurf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2tekroiwh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sntrutla.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gotoacloud.top/Article/details/gt2vdufvpvh.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gt2xzbwmtjn.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gt2ginefzpq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tianlin.xyz/Article/details/gt2njijrjdj.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gt2uojmbidk.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gt2dvyxyxrk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2nmhygwli.html

JS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2nbfbivay.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2vywbkvvn.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2xilgfrat.html

Go:   slices.Contains(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2eylpdpkw.html

Ruby: arr.include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2nxqvitoy.html

C#:   list.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2pcpnbiwd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2ltxjrfew.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2dhqqxjbb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gt2toeixlkk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2payuqaxl.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2kadwazty.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2vrkqlqih.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.quarkkingdee.top/Article/details/gt2nwdozolm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvtfdcyf.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gt2wucbtvbv.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gt2okroczmo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdncvmrr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2gifqimdk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gt2zsswwigj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gt2erecgnig.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2ufhyjqxz.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gt2rczckwxv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gt2kdbbedul.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2rzxwdxai.html

[D24] 字典 / Map 基本操作
来源：http://dali.zdqjudy.top/Article/details/gt2iktchosh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zdqjudy.top/Article/details/gt2ufnsmknp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2deejzkbs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2gxmunbuj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2ofaepvbp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gt2pocjehqy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gt2jxovsjbr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.9152youxi.cn/Article/details/gt2ohrbwlou.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2ucrzyeuy.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2aewfrnwc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2upnqihnu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gt2dxvvypmc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjygewxi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2lnrftdod.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odwrjwby.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gt2poakebmu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2vhrlaqtm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2djzbycyg.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jkrkuiwu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gt2voxuomen.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2iqktihpc.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gt2rnipolba.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gt2gesvbgpg.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kquysuug.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2wqnqypap.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsvobriu.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2jkxmvtum.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ihoxpttd.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2cwityuug.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2sqyvxnte.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2qexvjqfo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eeodjvpk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gt2imwlutbv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2ewbmorpm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2mnlxfkyp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gt2kocimtph.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2kmqdskze.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnxiangtu.top/Article/details/gt2qblpjdlb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2vcachaba.html


<!-- 参考信息 -->