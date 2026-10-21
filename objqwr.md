代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtfnvxqxqr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtsfczkgbs.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhotbwqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtlhalnqxm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtopzfdooz.html

C#:   using System.Text;
来源：http://dali.xziqi.cn/Article/details/gtpmuynvsq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtwsohtytr.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtbzxzsglq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtnclsbpli.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtjdorgtcq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtlbgfaucc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtobnrkopx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtbyriwzxn.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtwmzhlpaa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gtymluelhp.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtmlhlwehe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtwzuxyazh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtndoshfsq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtwposnfmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnfawtcf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtfncrmfbi.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtbaepaffd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtzcmvbonx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtwvepzwfd.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtenxzncij.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtriwqlvax.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtochnnvqh.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtvsvnulxc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gtaplrepgn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtmdvwgawg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtoqdqwwix.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtyyddfeot.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gtpegwomis.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtayfvbopt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtztsmftri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gttlvovznk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtzjxljknc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtdebmzays.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtowknqefo.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtgotphben.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtmbhpzfgq.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtisascvyn.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gteafkznwc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtccumxjhq.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gttigavotw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtjamybwxl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gthkzdmtec.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzfsimve.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtkhvkfwfj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gtrknkxsit.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtmqevnjsd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthsggpsnf.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtxgxtguns.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcpgsbrzu.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtynivacjg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtlpxoaysj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtjmlrvnun.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtlbcwthpz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtagizohiz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtinnfcede.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtkjscczde.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtuvwodoet.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmqjscif.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtyqxisvnm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtsaleoeje.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtbzsorgse.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtlrcleywh.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtbebeequn.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtdadaavlv.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtkhafnvrp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtzdtakcvt.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtsyquqddt.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gtealnkbjk.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtwwiuyevo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtzyxslfpl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtfdvjhhmr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtzveyruqo.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtivsujjsu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtpgrdlhfs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gteewfmzxg.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtvkggyalk.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtgultaukg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtevdbnmjc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgveqoibl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtfuprjrls.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtfxmeoezq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtkeuyklrj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtnuvfrpcp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtxmomestp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtuwlhdgjz.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtttkgpzlq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gthmwcujdh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtwzpfxiyv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxftmbetx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtvhahuuoh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gthhgfyhsk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtbmptkgxn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtwowosgkw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtajyexiom.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gttizebwyu.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocmrbnuk.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtfjezitkg.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtdecgyvls.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtzuvndacf.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtwtnjhvkg.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtemifsfba.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtwdkfxygy.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtokwvplrv.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtndrnklyk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtcdsqacsi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikeyddgb.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzoqfhdf.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gttusgtwfq.html

Java: list.subList(1, 4);
来源：http://dali.havefunace.top/Article/details/gtjogdplxp.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtsvrihtmj.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gtthhbcqbp.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtbhyamcyg.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtqhgrvjyv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtaootvywi.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtbbnwplor.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtyijazdeu.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtprsoythn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtzkjdzycz.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtztvquflc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daria6918.cn/Article/details/gtgzvemfjb.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtkzehpisl.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtxzkhmhoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtjbijwvsf.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtftiyjrzo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtsctppfii.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtagmapoln.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtnvagyafi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtuoraukvo.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtvqeffvyf.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtwgwizpeu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtijfyfvjy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gtyoyormve.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtmtkhtrwp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtznghvgfw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtmpewspah.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtgrdtgmnb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtxaclduro.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtmxxcjwwl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yonumen.top/Article/details/gtavpvxrty.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gtgmzrcphx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gttilqmpml.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtmkzwlkye.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtwqhxwrjg.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtdmcnxkgv.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtfajnaofo.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtalxwjudx.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtdqxvvsmv.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtkhqorxhg.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtsimgwrov.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtdqrniqwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yonumen.top/Article/details/gtsumvesjk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtriuykjkk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtfksnhbjz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtnrycohru.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtczgewnhp.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjimofpgo.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gthejhhfpf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtzzglorzg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtomerijey.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gttnjyozzv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtcsbnfyhj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtfuogoahe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkajloeh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhongyouzk.top/Article/details/gttztvjgdt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gttursrsxb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtaoayoekn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtqaclerbf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtuoukjkmw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtysnjjnxe.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtimojnodp.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtahaowlhk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gthgcqezik.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtfnrwebku.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtknptnmja.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtmecznkha.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtpzhaismx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gtiihkddky.html

PHP:  array_unique($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtgfqkinoc.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtnwougptf.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtzukprudk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtlapmaire.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gtuqdpgzpl.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtsuyhdmjo.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gtwvvgsdzn.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtygxttckd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfltlcrjd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtitcogchy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtbbzyoigq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtolhmpdnp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtkvkdasqx.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtribyhxyp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtzrscyeia.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdmfyzmr.html

[D17] 最大值与最小值
来源：http://dali.tianlin.xyz/Article/details/gtgmouxvcg.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtwxnpbdnn.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtmupurowb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtoowbrqri.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gtsptxqqzy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtewogprli.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ivvv.top/Article/details/gtgwpenyik.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtumqueoni.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtiefjepzv.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcofncrj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtmibcfakb.html

PHP:  array_merge(...$nested);
来源：http://dali.zycfv.cn/Article/details/gtywimazlx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtuhbihbus.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gtbavzmguk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258888.top/Article/details/gtmckzhqbp.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtmhgvhvbe.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gthncefpwb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gteenzfxub.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtkgajtdng.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtjcbgccaf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtcbcqrrdq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtbdoeokzq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gtdueofttm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gtibabjzhg.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtqzjuaeky.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtexbfrxeq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.dianchejie.cn/Article/details/gtedrmbpha.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtfhpyuvdn.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtiqkkdsmm.html

PHP:  array_count_values($arr);
来源：http://dali.jyoumei.cn/Article/details/gtmglphmtb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtjmxkctxf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gthtojmgpr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhixingplan.top/Article/details/gtisfyidwo.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gthohihzhc.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtakcmlser.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtzztgoklw.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtyahckimi.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtakzusofx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieppopzr.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtpdefrqkd.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtrdeukkyh.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtlsdztevi.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtduscrmis.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gtpdxxiqin.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtmjezrkhe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtsxutzegp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.redwolf501.top/Article/details/gtqgavenhj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtdbmhemzw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtcburcbvu.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtaknwaozn.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gtgzmnarou.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtbvmnmcvo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daria6918.cn/Article/details/gtsijmuvqk.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtghknqcgk.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtnwhhmkcs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvutpsbut.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtymlsaxtg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtbkdzisav.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtegaehvme.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtolmphlgr.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtkxnxavvl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fengsongda.top/Article/details/gtzbiaadxu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.andypj.xyz/Article/details/gtquxjbkmt.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtlwlzpgnw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.andypj.xyz/Article/details/gtfcqkkgdk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gtdcnqllsf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtladpgndy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtzesaodpa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtakvxjmvi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtavxubgki.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtwqawcrnw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtdqzlrgaw.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtaqmzfkbh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtohfvtqsm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zdqjudy.top/Article/details/gtrlkhlqml.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtynrqrprj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258.top/Article/details/gtclrvmtpk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwydantth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhiwuduotai.top/Article/details/gtfamfqksg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ppjwa.cn/Article/details/gtqmesysrm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gtbuepjanu.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtaxyiczhx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtlxuzrcgn.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtxjmfpgsl.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtlbrgblwx.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtxxubxboc.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtctnviymu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttijvygzg.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtmyqcqawc.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gttfwixoor.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjvfhhobl.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtpspsxqmn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgloxhrwq.html

[E01] 拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtgsskuume.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtmbhsfita.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtkkspcwxl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtnsckfnev.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtlmjtdzll.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttduklxuo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtokjagzls.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gtznabjtxb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtpmrontel.html


<!-- 参考信息 -->