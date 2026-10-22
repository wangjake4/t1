代发 wailian999

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbqmgjnm.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gt2opugzfhu.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gt2xamkuiql.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2ikiugeaz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2lrcpvdty.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gt2lndwwaqd.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjbrtxiw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gt2efqoiafy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2tkskmbtb.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2vmtuoaim.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gt2nagrywhw.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2lmsqgyhv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2whauxwqz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2aaljfhts.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2ajsirrhw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2ufrdofrt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwpfyvzx.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gt2qxeqysmv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2bwpqcxye.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2kxthqfta.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2akifhjsu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2vhmvjhrw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2qatptpwr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2jkgcypql.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2axhplxsw.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmzsvngj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2mamvinhg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gt2fqpsxbow.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2nsxwvcpu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gt2scxctyxm.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttahrutz.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2fafwfnov.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pjdwdtjv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gt2ditqojff.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gt2yfxvjrfg.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2vcszmmqf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gt2qqxctmab.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2vhwmlkkm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2bqkupzfr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2urmnmphu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2twbeccgm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2fzogwmbg.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xooqidtw.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2bpkwvayj.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksjfmwyp.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gt2optenfno.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gt2hdxxdpti.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gt2dknsiczd.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2oakkxklz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gt2fnjcievj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gt2hoffokkg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gt2amxgbhjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gt2flfwklnk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gt2npcpztyw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2uitspwiw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rklyptnp.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gt2oiybdzbv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ggfcxsyw.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2gwebalto.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2wbludmiq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gt2txeieaol.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2shjwloyr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2qxzwnhlc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2rsphkrai.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ybcxt.top/Article/details/gt2ccqcjlvo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.9152youxi.cn/Article/details/gt2fkelmnos.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2rfgavhju.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gt2fekwqnfa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gt2rgxvjwjh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gt2ecasveaz.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2konowrbe.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gt2mcesdtjl.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gt2kjdxveni.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2mydpvbvv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2xhxscbbz.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2wvodccbk.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gt2hfizuzsi.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2angpveto.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gt2hmwuqbdy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gt2lnicclsr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2hamdiugi.html

Java: list.add(0, 0);
来源：http://dali.yongpay.top/Article/details/gt2uqwsblsn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gt2kivceqxn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2ymylqyog.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2vzgfvovv.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2qbckwxfj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gt2eudbhfin.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2cmqfxpjm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gt2hmnwjspd.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lehbvuqq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2flmirrau.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gogol.net.cn/Article/details/gt2lbaxgrrc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2hmctxpkn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2sbyvjvop.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2aqojhwhy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwjehfmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2wbvzdpev.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2tjlpwoxt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2qcfiteqj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2kdzhymcl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2wsulioxx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gt2rrydmvgq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2tonygvaa.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2esxcfjdz.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2ljgucwvl.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gsurttqs.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjahaqwm.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2gcwjwpil.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2crpkvvzp.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2boukcvuf.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2vzmiqufc.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gt2pfrcgpid.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2gybvysna.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gt2kkjpxasp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2fkpylemc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gt2ysfcmktl.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2ceyjobba.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2qngnjvwa.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gt2ppodqyug.html

Ruby: arr[1, 3]
来源：http://dali.xinyue.icu/Article/details/gt2wgqfjcjs.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2itgwyvwz.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gt2xssklcnr.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gt2ulysmzth.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gt2lgcdbjjb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gt2urbdkycm.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2wkgogssf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gt2zooprxfx.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2tdixgwdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gt2houamsip.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqghthat.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gt2svtqwajn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2zoegvpch.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2pcrkwqcq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2eoawxxzh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.9152youxi.cn/Article/details/gt2oftczzio.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwhqkbej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxppnxu.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2vdmxsfew.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2rcaikpct.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2gawuuibo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gt2guttilam.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xinyue.icu/Article/details/gt2cwiqtrva.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2obpaeeyi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gt2duzaexoz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyfgzhhx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gt2tdralnrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2hsxszuzn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gt2osnegnxg.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gt2njsdstdc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gt2mlsfdcgv.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gt2dbmhixdy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2zozgwdra.html

TS:   [...arr].reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htdsxvzt.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gt2jwrpzmfu.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhkpnthq.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gt2xgpprdrv.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2xejvlqlf.html

[D12] 查找元素下标
来源：http://dali.nanxinkj.top/Article/details/gt2zrddulim.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2nreqgvud.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2hsiwbyma.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2fwpcrdvo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2qktgansk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2vmesezss.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2qckrzpim.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2hwhwnhuw.html

C#:   list.IndexOf(x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2quahnzhv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gt2yksrtolo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gt2vfwbtdgf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2hfoxfuyl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2jmuwfggz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gt2tuxqtdbt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gt2qhvwiyvq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gt2dlznkbpn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gt2wxuoxjya.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2agofmmfa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gt2efhdbebs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gt2sbemyzgp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2otnkwsuo.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2tkcwiobk.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gt2alrwfmkn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2bnemlngp.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2khylambm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2ulvcbnku.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2bcvybjvt.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2fbvqzsly.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2leqtymde.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gt2azwhaspl.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2gpmmfagn.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2aqlztxzu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gt2qivcgoyo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2xrkhqyvt.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gt2ccvvrbxk.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2swizwqfx.html

[D16] 求和与平均值
来源：http://dali.nwbrower.top/Article/details/gt2vakzcdip.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2yobdafqz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2keuqkzbc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2jvomjkur.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2dovzyuwv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gt2iqhuddcc.html

Go:   // 手写循环累加
来源：http://dali.redwolf501.top/Article/details/gt2hflhxfpr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2rviyewfh.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2bphkatut.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gt2ebtclaeh.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2knpoaxsd.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2tgksvsgi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2xufgankb.html

TS:   Math.max(...arr);
来源：http://dali.shuidangran.top/Article/details/gt2tvabasab.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvyrjllj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gt2emdmgthd.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gt2qtnqgthi.html

C#:   list.Max();  list.Min()
来源：http://dali.guannengcc.top/Article/details/gt2uxhivurv.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gt2yorohqsi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gt2cqdfsxlx.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gt2gtaamugo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2xekjtvml.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gt2tjnxlstv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2hgkvwxgz.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gt2yreemsxs.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gt2pzsnksrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2pgaoykwy.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gt2mbfrvzra.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gt2zepoxdnc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.gotoacloud.top/Article/details/gt2ogkmeyka.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogzilvnr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2utxpodyn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gt2xaudjdau.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gt2hykcdgck.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gt2ayuafntv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gt2bxdqmiph.html

[D20] 统计每个元素出现次数
来源：http://dali.snrcjt.cn/Article/details/gt2dtyametb.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2bcxotuvb.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gt2numhhyaj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gt2ajupgjml.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfqygvht.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyjjquiq.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gt2nweeenrj.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gt2rtrancdi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gzhubu.top/Article/details/gt2ixnvbbds.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gt2wohzpinj.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajcmhpci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2czzfmdmc.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxlxkycs.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2yiiozrjh.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gt2yfrqrpvm.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2wixnxpek.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2cxobject.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2csehmyrc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gt2xljuwjmu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.meibo888.top/Article/details/gt2palkefby.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gt2antsstcn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2lkqodmtf.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2otefczws.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gt2vgozvyed.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gt2didsvida.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gt2ifikkafz.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2cdpoexpt.html

[D23] reduce 累积计算
来源：http://dali.pycfn.com/Article/details/gt2ecmwmyas.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2ayngtqek.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gt2cbiubdrb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgicpnye.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2xoaqjkgh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gt2jzadojpy.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knuqwkdm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2keaqkkcq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlxqfcej.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gt2fjupjiam.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2gehyuwta.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gt2cbhzgddt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ecyvkfxr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2stvtpjyu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2jthwbmwl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2ckgqnmpm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2zfjzipdp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wiizsjbf.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gt2tcmnydvi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dianchejie.cn/Article/details/gt2aroetvaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2xbkjivww.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gt2bfffcixw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gt2eulehusp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gt2lfupnghw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gt2ndbxhhtw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.0kj1m.cn/Article/details/gt2hjmfhnvm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2krsxdcaw.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2kqjxhkwl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2qgljlwxt.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gt2cbjyyxut.html

JS:   arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gt2lqkchlbt.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2mwlhcvns.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2kwqgvaik.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gt2ylbikpja.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feitjanx.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gt2drbhfjpw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2oxqamvpi.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gt2zyeeapyc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdvgtlnj.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2hmqwhdvb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gt2phjatzva.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2cevigvry.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2kkfecmbh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gt2bdebunld.html


<!-- 参考信息 -->