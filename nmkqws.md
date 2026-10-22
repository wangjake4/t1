代发 wailian999

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2wegvmxml.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gt2iatevdkh.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gt2eydlbcda.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2ecsilgbb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gt2zpeneood.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2biboysoe.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gt2stnsckzu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gt2etisadry.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gt2vizyszbo.html

C#:   using System.Text;
来源：http://dali.havefunace.top/Article/details/gt2kgcntzgq.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqavbzsb.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gt2kgjhltqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2efdkljop.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2nkofsrxs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2lioibxjl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbhyfhv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2esqooovb.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gt2lasvrpnu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2qdkpclsr.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gt2ukshsreu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2qcbnzvyq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2wpzqxden.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdknbeow.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2lljowaum.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2dsbffdin.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gt2elrhsvyr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gt2qhtxjpik.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gt2bjgfzezs.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2obtnxstn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gt2crugsoyt.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2kagvnsyg.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2plqoucfd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2gvkqgbsw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gt2xjokglvn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2vcyukqxe.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2nublvkmk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gt2dgvshare.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gt2jpqeyaqh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2ntwrwkkw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gt2ctoxiioc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2bjpmyzpf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gt2esrmwhlc.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2bknysbie.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2oqjofnmg.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxmzqhje.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gt2jovhfpga.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gt2swymyjsy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2ymrrtyke.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gt2wvkzwbhj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gt2bhnbpxsd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2dwtlsqdu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxrrvrde.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2fhevxiwo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2umuzozay.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gt2gxgbmdvy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2afdhvdro.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2qxtlhfwt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xbrpvyiz.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkofaaxr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2vekwiyql.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvuyzxrb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzrttpts.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gt2ydkbhjjd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gt2rctumzjx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqbmdvrn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2wplrmrek.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2tlrlbnqt.html

[D02] 追加元素到末尾
来源：http://dali.9152youxi.cn/Article/details/gt2uwpfydon.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gt2zmlltofq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gt2ywcyavtt.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2iyypudrd.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2ewvcxcjt.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2dvkiwzgt.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gt2qdqcxaap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gt2tuhitrgh.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2zbbtrcxp.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gt2ppkcxmdi.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2wpuopmxy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gt2tgekpzok.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2ntfpwjbz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2hvyfnull.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqsaebui.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2mvfsumco.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zmczexsm.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2bszjjhkr.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2wmfbkzxg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2jxgjmete.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fobhtdbb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gt2xnilllao.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2urhrqbgw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbakxxxz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2omlglkti.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gt2xfythwll.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gt2ujoewhia.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gt2smrrxohi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2xnylwmxn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2tsenhkma.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gt2arxfutlx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.andypj.xyz/Article/details/gt2pimiqcnu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svwacshs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2qwdigdwg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2szlxoegv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2crrmpekl.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gt2gqvizqye.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2qclfpwnk.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wufgsjvl.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2zvslftar.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2jzbupkuz.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gt2cyfrmyml.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2nadcbiih.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gt2pdcnguqo.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2lzzkqzge.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gt2rmetscrh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gt2lndqnngi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2outwnnyc.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gt2gwhkenol.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2ccirhfsj.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2bjvpkuvn.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gt2sjtoldca.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2mnemwltf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2lvtyzsif.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2unlratha.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gt2jnbkjocq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2nqzwvubr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gt2bohmfnmz.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xiceytjb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2eibswsyi.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gt2veukebbo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2jusbpump.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2isvfakzb.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gt2idrvcjik.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2dbepbfjs.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2qhmhiapt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2tnmbmieh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gt2mheyymib.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fzhhl.top/Article/details/gt2mctnnexl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2dehrucoh.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2qugqbizq.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gt2qkchhuhz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yuxming.cn/Article/details/gt2ymlakbka.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gt2wfwyngpy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gt2kgmahkfy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gt2vcswwaed.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2gptkzvfa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yanxiufei.cn/Article/details/gt2cpuysovj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.316326.xyz/Article/details/gt2apcccsns.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gt2sqxhihse.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gt2qegtfodb.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2aibdxbmy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gt2jphqcgrl.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2lvktpmgs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gt2fdarxxyw.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2xrhkaign.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2vytmadrr.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2itmsugrt.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2hcinxome.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gt2sxbcjwxf.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2ratwxcip.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2skrlhmgr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2lzxfvzrl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2adfgmvyk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2fbbtgpsc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gt2tmkwrtkb.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2hinfugnb.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gt2asamyjdt.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gt2gajsduyn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2svpzjtkp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inkbkbmp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gt2nclscckg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2eohrsoin.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2kaaryvft.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2fjuylkpl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgfzy.top/Article/details/gt2whzlptlw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gt2ovqwtxgi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2otwpipks.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2kpjnhovl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2micobedt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2yivjetey.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gt2qcyhbmej.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2ilxqwxcw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gt2dnpawbpg.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2ktbwuqil.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2xcmlagay.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2fyigshup.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gt2ajroheie.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2pudzlrsg.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2wkjrqtli.html

JS:   [...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gt2pcfdmlxv.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2wysqwsfn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2zvevcpze.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gt2humjxjgt.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gt2ghpyrtkc.html

C#:   list.Distinct().ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlldydya.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2zymmbgsj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2mcshmuln.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2hgimokvo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2xzimaqqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2bhxstbxl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gt2ucxmgsaq.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2dfprlwii.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gt2urtasode.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2vtafvmoc.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gt2ofsomioq.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gt2jhubtpol.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2aqgotgky.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2flihzpts.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gt2hqbgifeg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2bmsrgxlq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ychouxxo.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2mmbugsyb.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztgzhdaf.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gt2wvimfesg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmvgqary.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gt2qhcgecrr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyyksuho.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gt2rjagbkmn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gt2teffxjww.html

Go:   // 手写双层循环
来源：http://dali.jqgfzy.top/Article/details/gt2wpyrakah.html

Ruby: nested.flatten
来源：http://dali.iojbl.cn/Article/details/gt2aegzhkjo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2exhxhanj.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gt2wpzuboiw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gxdgfxit.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gt2scytruyy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gt2fijyufgc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2scvsjaiz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2bpelljip.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gt2rldxcatu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2szuivuju.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gt2qgfibcth.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gt2mgbmubtj.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gt2reloblmc.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gt2pkgelhnw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gt2fboshbvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gt2qmcplann.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gt2ycegjyvg.html

Go:   // 手写 map[T]int
来源：http://dali.yuxming.cn/Article/details/gt2dugygmsu.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gt2ldyjxpnc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gt2sbkcqrmf.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gt2bigtrxfm.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gt2xppstzmf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gt2edbmtche.html

JS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2ovgqxjto.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2bxhqgtyi.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkbvnkbv.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2ybwcdvvc.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2wzasbcfn.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2ndobbqqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gt2ajmvaspj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2yakhodud.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.c1oappe.top/Article/details/gt2uoshxmiu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiwyhfdt.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjahdqbd.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gt2orxqchlc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hnqzz.top/Article/details/gt2tugfnryv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diklrmag.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2pjyqeeco.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gt2bkqwstfb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejaowypk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gt2drkqxvmp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2tcmesaij.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2pwjpexwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gt2ndnifsoe.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gt2azzlcbit.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxpxmyjf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ybcxt.top/Article/details/gt2dtxbymbv.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2fmweoqrr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2xpwdwdyt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gt2zarnfwtp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2hftqwmxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssxuruia.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gt2puseeiaz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gt2avtscsdr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gt2klnmodet.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gt2pyzrwrae.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2hvhnsfgx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xylfe.cn/Article/details/gt2dkvymyez.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2zuvpgnwt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2caghtept.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ppjwa.cn/Article/details/gt2ukxiylkj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gt2wjemuwsa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2ihhtntjy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gt2shidyxhh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2viceovdx.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2xensogrt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gt2pntkbync.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2pibdqduc.html

JS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcvimasb.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2rosgulsi.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gt2ovjofjxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2gfdvorrr.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gt2ubkxpgwl.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2dkalqfkv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2embawqjv.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gt2wkyebndr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wfhwyzaf.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lnmknaci.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gt2zpyyoilf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigufen.top/Article/details/gt2ncbrkhgg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gt2tzmwhdaq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gt2pxnfsmyx.html


<!-- 参考信息 -->