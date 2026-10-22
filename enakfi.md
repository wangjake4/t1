代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2edvmmovl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gt2fskqtkss.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quwvzple.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gt2kzlwbtfd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gt2ghpuvggt.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gt2qafghswy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2nijxbomw.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdgbmifp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2ltwzqppc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gt2dkbdysff.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2bxtyppse.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gt2oppnvuvy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2cguilerz.html

Ruby: -> { puts "run" }.call
来源：http://dali.jyoumei.cn/Article/details/gt2qrmhryqv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2nkvzaiae.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2ebjztged.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2wkowlcao.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdwnassb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2bonmubzw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2mmizkkbs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2bbrmoqyk.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gt2txaoxzpd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gt2wzaowcfg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txztjxxv.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gt2qxljyrcn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gt2xvufdopu.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2fctteujb.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2jcxkbaxf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gt2longtrmy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gt2idfgbrin.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2hdelpdff.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfowfwxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qojwdcij.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxtmxrfx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gt2idtithen.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gt2lsmnlsts.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2lbnumxvv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pcwxfomy.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gt2sfrnhzae.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2pzthvyiv.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2qtjrfbam.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gt2gpearqwv.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2zhqlrdda.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2txkhflzx.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2qjhbuulq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2dglkvkxx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2tznoyied.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2simzkvva.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2uizqingo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gt2qlxmvhzw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gt2marxyvem.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2numxtomk.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gt2cljjhanc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ebahzgkq.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2nwmjxrlw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2pnawazeh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2oqtsqcod.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2ckougbzv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2zvibvoak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2oqdyqlrn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2adlmwzsz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2ooyesvsq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2jwgqrypc.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gt2bxeitasr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gt2dclzkzdz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myefntbx.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2zzsvpdve.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gt2ilwctmrx.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2ncqpbusg.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2mglcmmam.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbppmajs.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfokohca.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gt2veywxzmj.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ktazshji.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gt2dugzmmdw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gt2nnuukzkg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwkymjob.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2gsfenspp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gt2oyuuwqpd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2dlabcvfp.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gt2kedvrtpq.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gt2idhiqqln.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2ckxekmiw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2avuwnrno.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gt2orjvkykk.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2gkpzcxoq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gt2pxckdpwx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpszhoey.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnnhpdgx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gt2bfdybkoa.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2wnbfywsa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2jnzhnuiu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2icrnqqmq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2bplavkzq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gt2vakhihrk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2axddgkev.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2wzqwhffy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2dcedwral.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2ywptahzb.html

[D06] 数组长度
来源：http://dali.bjfxy.top/Article/details/gt2blasnfkz.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2nibekoaa.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ygcpndol.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfapgyml.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2yjwmlhok.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2saouuoma.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2dsvzpawk.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gt2inbfgxpu.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2enilwhud.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gt2oyqwtvjc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gt2sxzmdioi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2pmugwnoa.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gt2xlpxhfjs.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2iumnkgdc.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2cckeggpr.html

Go:   arr[1:4]
来源：http://dali.zycfv.cn/Article/details/gt2wgzrymrj.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gt2uennxcsi.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2qloegtxx.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2vjllwkgj.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2xavvujmk.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gt2otqbmyqj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2dmiyoppo.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2knarlqkl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gt2xwfauxay.html

Go:   append(a, b...)
来源：http://dali.cdnleiting.top/Article/details/gt2jjkvbwon.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gt2txavrxrr.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2wptknlzq.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erhjswwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gt2mwqvpfoh.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gt2sbsbvcwa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gt2brmpcqix.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gt2iheourlc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gt2tszkwqon.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2cwugkupf.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2iccepngt.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gt2lxeppysa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gt2ykdgoiku.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gt2wvozyofk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2jecwwvib.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2iceycyxn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2wbbtvdmy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gt2zjwpwcpg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrebfhcq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gt2fjlreqip.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2acqnfwun.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gt2namuruzf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gt2zbqcvnuf.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnscaxwh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gt2mqwvlorf.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2atauixky.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2htuyzzlg.html

Go:   slices.Reverse(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2edlvyrvd.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrhifmmb.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gt2fzppyvwf.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2kkmmwwgi.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2sglllrlr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2glvcxsvd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2edigvesn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2sthhzwcz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gt2sknhphhi.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2fkteorkc.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gt2gouxdfli.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gt2rzhifdiw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gt2hrcnqeqv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gt2adzvbozp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2qgtjukru.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2rhlfinxa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2ykdmxbdp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2jodmsdeq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2vqkttnlx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gt2ksrxtgel.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2xwxhyqgt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gt2mhhksilg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gt2psnxcntw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2ktompvvx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jzblzeat.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozwvemsy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gt2totwuewd.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2mvhowxgq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqnhajup.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2bwlqfuql.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2zyvqhfld.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gt2oipubchf.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gt2xuffjqiu.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2zlxrlkty.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gt2czsatkzf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gt2nzuduppn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gt2zrqdzueb.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gt2rxsypymp.html

C#:   list.Distinct().ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2rhiibnjy.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gt2mfktbshw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2usjzqbum.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2kogtqhss.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xomwunct.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2yefrcvsu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gt2sycqlcze.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gt2egpgehcl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2rptpdojm.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gt2zzqspbox.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2osznecen.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2nfcmonlp.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjisbcce.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vubjldch.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gt2mzyyhejr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gt2ppuvvbbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxcgbvta.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gt2zcmgxigq.html

C#:   list.Max();  list.Min()
来源：http://dali.pengpengdd.cyou/Article/details/gt2srcvbjer.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2chspazrh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gt2zdmuzuxr.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gt2ieljmlah.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gt2xjwiorpw.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gt2wrirtagz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gt2ccmxmsky.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2dbjybpua.html

Ruby: nested.flatten
来源：http://dali.sxryk.cn/Article/details/gt2ojcwhsby.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2imxoidlc.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2yrznkxje.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gt2yqhufzvf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ybcxt.top/Article/details/gt2fkxvkjqv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gt2ypmoqikv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2ijkwgaxs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gt2kpnuycsx.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gt2wjfypwrz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2qgydzbgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gt2mmjrfsje.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gt2shiwxwmg.html

Py:   Counter(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2yntzcoos.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xayxddwg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rdenffqo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2oolmgdaw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkntkhvn.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gt2bklputuf.html

Ruby: arr.tally
来源：http://dali.jianghu66.top/Article/details/gt2ruuiaqgq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2jjmffzbi.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gt2wgqrugkr.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcwawmab.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gt2ynfksluy.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2yliqfdnn.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gt2yhgkpevy.html

Java: list.contains(x)
来源：http://dali.gogol.net.cn/Article/details/gt2opnnzupg.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2twwchtbd.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gt2phqrpbne.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2gihlzflr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2ibsyipme.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gt2tfczzghb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gt2kibmkdlj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecwinlub.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gt2fzbryvym.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2kfupvvzf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gt2jzvrgjju.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnqzz.top/Article/details/gt2lezrqube.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftgzaurt.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2ycqkkguq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcootvzf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shzxlz.cn/Article/details/gt2hcizxmbt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gt2xwyaborw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2lhkqvspr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2mmwpqpvw.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gt2rnzhxjjw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cashguo.top/Article/details/gt2isnaybsx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yongpay.top/Article/details/gt2uvwduvuo.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xklxnuzb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gt2zviuglqd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gt2alesnqci.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hfhledvm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2btxrylvm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gt2bhfyfmxn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gt2upqubxhm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2kdazchbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gt2caimqgol.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gt2eltrgvom.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sysykeji.top/Article/details/gt2eexapmne.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2jwzttihq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jhylcogx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ydzc1.top/Article/details/gt2oxekqrzj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gt2rpdpxvyp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sncgpdmj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yangfankeji.com/Article/details/gt2yfkbpmtb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2irupaclm.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgdwznbh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2mswtvlie.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2hqpycxtw.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2urcaclsq.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gt2dvgiokcl.html

Java: String.join(", ", list)
来源：http://dali.tian-w.cn/Article/details/gt2emhnoenw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gt2lbipbubs.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2mwlmthho.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2qrqdaypv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2vxgxfmev.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2mlbogaui.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lzvhojzi.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2phuoyxpm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2dqbdnsll.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gt2jouxstvm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gt2dpxunrzn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajaxldoa.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2afzdmona.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gt2xfvohsqd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gt2ptnevywj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2rvvkpldz.html


<!-- 参考信息 -->