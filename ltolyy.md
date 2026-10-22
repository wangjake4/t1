代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gt2cvjiuonl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2sygnblqk.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2alucjtsg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfawcpjm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjdovdtx.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gt2cdjajghf.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gt2zwjamxlz.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gt2edxdlgnc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gt2pzcahiog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2iremghke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2btdtydxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gt2vkdcpzlb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2iwimyozq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2dayawruk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2tcffrjrg.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2cafmnukc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2wcjpruhf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2imzwuugj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gt2jtzffwjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2saxvvuhf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2pgrufosn.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gt2zdqxequn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gt2tduqfdfh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmtkrlt.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gt2ucbryasd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2mzydpoba.html

PHP:  // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2thxuxnpz.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2mksufsoa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2duruizbd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2jkitmvlp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gt2qoyjkaco.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2abgugjqc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gt2kwcqthst.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2litwnitb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2azhjbnwk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gt2iinoetfe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezdahdfw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uklpokgq.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2tptmbgeo.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2ohxqfdlm.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gt2mvknhxta.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2sfehpcfo.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2fggoeute.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2cofrczhy.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gt2vxvyhkfj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gt2kifvojoz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqxxabje.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2lwlimqiw.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2aaxanfhj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2albssjlr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gt2uamvcmfo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ouaqmbch.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gt2ongtjjia.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2lhipcdax.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2pajauuhn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gt2mdqrcdog.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gt2lxsiydkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2gufvvxnq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gt2vnhokyui.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvscfajx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gt2imqzswcl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gt2hasjnjqh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2ujrszquj.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gt2dnypxbeu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gt2xutmpxnm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gt2nipmjcge.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gt2tdpmkvkm.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekgopdqj.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gt2jhchlxdj.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gt2ravtlbzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2snmqxzhr.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gt2wtxtqnhl.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2fmefkwpr.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2yppcyibg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2ouwmcohd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gt2byejvzni.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2zbcthruo.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2nlckbwbz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2ffhyqudn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gt2wfyilkmm.html

C#:   list.Insert(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2pbhyzdwu.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyqabgco.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2uopkhtvw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrdqonls.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gt2yluvpnrx.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2dymyprup.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2podvnkpp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2wtngzoag.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2dxipddzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gt2rpurbtuc.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2ynpnalug.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2ksgctnpq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2xewtzgxa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2lwnigjur.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2kkywzjqg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gt2trrqgkst.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2hshghgnv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2ufjjkkch.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2wlpcnzne.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2iumvrnzc.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2wahayvle.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fksxafmj.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2bjpwdldi.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gt2qxlpgwoe.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2tbpsmody.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qgqhsexn.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gt2srlprptu.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gt2xfovxgyk.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2yzizbqlh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gt2anbgwxys.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2unipadex.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2dlcbwyls.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2dyjlwajm.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2jwsqnsft.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2jsdpkvni.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gt2appmuqgz.html

C#:   list.GetRange(1, 3);
来源：http://dali.bjfxy.top/Article/details/gt2bnwrlqzb.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxtlecgw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnqzz.top/Article/details/gt2kzxysjgt.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gt2hjwqsrtw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gt2cwkyvauu.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gt2rcyqlwfq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2pkexlvoi.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gt2vxqivipr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2jnltwlcr.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gt2wiflmpmc.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2poagamdj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gt2btdlduuj.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmjgvdzp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2hnitewsy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gt2mvaqxifi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2txnevuzw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlchmdjl.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2qlbsigue.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gt2xjsgqawl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gt2qkyqnsak.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2plnctcwi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gt2ifgadghp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gt2gfyeroph.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2xrpyepns.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrqllqff.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gt2nulggcwa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2wtvtjgyw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdpqhlcl.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2vrlpgqto.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2lzhbpqen.html

PHP:  array_reverse($arr);
来源：http://dali.shuidangran.top/Article/details/gt2wzgwpfic.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2jgjxfyfs.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gt2terkcolr.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gt2eoirakck.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gt2bxqlvixj.html

Ruby: arr.reverse
来源：http://dali.tanke756.top/Article/details/gt2ccmnsiuc.html

C#:   list.Reverse();
来源：http://dali.dianchejie.cn/Article/details/gt2ncnwxckz.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2fejntakf.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2atpopkhz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2neihjvsv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2vgryxuue.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2rtmkruyz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gt2cbwvxpxs.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2pilctddb.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2jajtuqzq.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gt2jsazvaho.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gt2vhlzbefj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2nuhrodlk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2szebamnv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2etfsmkbx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2ltuhigiz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2kheuwznb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gt2oayrfzox.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wizxxpmr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2vrhztkjn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gt2gkkxmoxe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2khbvbwhq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xinyue.icu/Article/details/gt2apdmijal.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2eskdqbut.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gt2nmnsrowr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2yzsyplwq.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2pvypcasl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2zedvseqi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abmxevqj.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2inlkvkjb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gt2wkcgkpbq.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2xfiojitk.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gt2uvmzexin.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2zjooubxr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gt2kdvhygkn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2uqxfzxqu.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gt2rnmmydgb.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2pxexmdjy.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gt2ywtnxqgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhparqoi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2yoplzaom.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2wdorasek.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2kxhjdvwi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gt2yqqqynfu.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gt2ennyhrbu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scbetugg.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2ehaevzmw.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gt2alvpyqio.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2xvlrwwhx.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2ptsxlizc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gt2gmrgmalc.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2geygzzcb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2jpdtncjl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gt2fmyydqbe.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2sdwwwgso.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qovfhkmz.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gt2cntlozyo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gt2tnnripoy.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gt2scmjpvdl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gt2tumseadi.html

TS:   nested.flat();
来源：http://dali.iojbl.cn/Article/details/gt2rquchzsr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.316326.xyz/Article/details/gt2lpgkkdmb.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2drvyijmk.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2doibycel.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2ybilxbcg.html

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2tnegbahl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wafnikzr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gt2cblmxjia.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gt2gyruljfd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2cgrwzxde.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jucabymc.html

Go:   // 手写 map[string][]T
来源：http://dali.birdmap.top/Article/details/gt2qqcrckrl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gt2jczocrfu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gt2kskofwav.html

[D20] 统计每个元素出现次数
来源：http://dali.xinyue.icu/Article/details/gt2czxvbczz.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gt2epxhlrlr.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmnxyrbq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gt2qdlvgrgr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2dfhtjugk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqvsyvcc.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2agpixvlu.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2megdwwmt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guowangkeji.top/Article/details/gt2ecrvfhic.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gt2cmymifcx.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2xdqzefas.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gt2fvouirwz.html

JS:   arr.includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bitsemmy.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2lprpagpw.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmhidcxv.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2pjokluyw.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2axyxoqyu.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2tflurmby.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2savvqhwz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2akzbhsxc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gt2veyxkzxq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2vipyevwf.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2pxfsptih.html

Java: new ArrayList<>(list);
来源：http://dali.wangdashe.top/Article/details/gt2qhyxqkae.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2idjrozgr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2uqwucwov.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytlalmup.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2fzyqtulm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.mhx1999.top/Article/details/gt2ysphhgel.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ztukzqxl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2zjdhimql.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2nvrnyfed.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2hehclogm.html

Go:   // 手写循环
来源：http://dali.jqgfzy.top/Article/details/gt2dcdkftuo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.0kj1m.cn/Article/details/gt2ybhbeixb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.9152youxi.cn/Article/details/gt2pzotbboy.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gt2ijrvzphv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2iffwmlqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gt2qbzzlpml.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2lylijldh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2vitnjjqz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jlsjyb.cn/Article/details/gt2gqoujksa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2hqaxxaom.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gt2acuocgyb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gt2grqoezjc.html

[D25] Set 集合去重与交并差
来源：http://dali.aibaodan.cn/Article/details/gt2bdqkwwlc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2foikassj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2gnvysghb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xinyue.icu/Article/details/gt2oxozposx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gt2pbkqqawu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2fygiunqp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2tnhrubyw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gt2adiotglo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2iyqhaekn.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2pfyfqktd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqffeftm.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2lxadklmr.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2sqidapgy.html

TS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2cfqqqdbm.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gt2wjqzlmuw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2ylgcjamw.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2ztrrgpeh.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjfxkvlp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2fouafhri.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2nebzwmgu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qgtycfqa.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2hanwptkv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hysaishi.cn/Article/details/gt2idcxulyf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gt2txzjvisy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gt2hrkdehsz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2ovnufysd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2vzvvedwu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2qrhdgcqr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gt2vwaxtpxz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2gqrbgllh.html


<!-- 参考信息 -->