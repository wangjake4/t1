代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yongpay.top/Article/details/gt2ddgosmgn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gt2lufdhkki.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gt2fbywqqgv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2tggchhtd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gt2zgmfalrl.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gt2jlnejpfa.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gt2ncfkabgn.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gt2ypdldiec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzuopoiq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2jjcchkrh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gt2tvcotjyw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imgkpbwc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjegbmym.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gt2eublcois.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qkbtxdwb.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gt2ezfkqneg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gt2uifiyeyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2zdircbgi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2qxrfbdcm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hspspmbh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2mrqsdnna.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uotssyrp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gt2yuxxzvlu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gt2wqfvzyia.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gt2fsisfgiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2vfhmsuse.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2hotlywje.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gt2qawylqrp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gt2uvqbpgvb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gt2rfnzaybt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gt2mjrzrkwo.html

Ruby: # 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2oxirobrh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gt2nsgkkygz.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vopqttrk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gt2aeiofmqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrepaelw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2vjciprbw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2bhtxkaqy.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2rdfozhch.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gt2ydwbfasp.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gt2afrtylzj.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2jpvmxvwd.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gt2ojpesxlj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wakjacqe.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2mrtvetjj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gt2mgibgxjj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2rhrvtwaq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pzbpozrh.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2stqljzrw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2sxelrojq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2uloqkxyc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szbriiyv.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gt2nrhhvmve.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2njnagyfh.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2ctltcmba.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkhplbvj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlgwvhyr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gt2zdvqsrvb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2vqufxgzu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gt2hgipctca.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2qhpgjcge.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gt2frwpxwmx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gt2psocxaio.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2zgxlomkc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2svizwdnc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2vfblshsf.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2vxyxrfgs.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2uxwftvtl.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gt2zxwiinli.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gt2pbnnyfwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eseqrvrm.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2pspxnsxg.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2auadswdr.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2pcluoyfy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guowangkeji.top/Article/details/gt2ottdcbhy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gt2snobemta.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2scxnqfua.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2jyjxkxzi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2zacdcsiy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2thpamesv.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2bkbifxxh.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2xhcbulsb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gt2gtgmiepl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2slrmvxah.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2unwbumaf.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gt2sybjowzd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gt2yymkjmif.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2tofghbud.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nwbrower.top/Article/details/gt2kmncggdx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gt2daacyjjo.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gt2unlldlcg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gt2lnzrthor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2isgdwxtx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gt2nvkzocat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gt2keensieb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gt2hfnanpal.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gt2zchiaacc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2kkmgnovv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2vpnxpmnm.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gt2mtwucnvi.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2bmzcuizg.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2qvtbyopz.html

JS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2miuqtwnm.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2fqkmuxuc.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gt2iblbphvu.html

Go:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2imvocuwq.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2qkvrrfsv.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erupysrk.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2yrngjpxn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2ulvyjwka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2qojklitm.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfbedkc.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2tdbztclo.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2nldtgmin.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2slmywzjv.html

Ruby: arr[1, 3]
来源：http://dali.andypj.xyz/Article/details/gt2dznoerak.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqwewjad.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2drqwkvfj.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gt2ruaurhrp.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gt2emvhcgki.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hfpthk.cn/Article/details/gt2dmqzzalq.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnjnozbl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2hapueyix.html

Go:   append(a, b...)
来源：http://dali.redwolf501.top/Article/details/gt2eqgprfdp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gt2psqoypzj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2sibnzwgm.html

[D09] 排序（升序）
来源：http://dali.xziqi.cn/Article/details/gt2xrbpuofy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2gzjeisjn.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2ccocypeo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2spgwjqhc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gt2eateuxac.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gt2milmmqom.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2tnorpzuu.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2hbkuiioy.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gt2lcbngfou.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gt2oznndlds.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2zxuaxpcf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2zcszvlbr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2vxghbgkb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gt2piftxpaq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gt2isuoxjtv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gt2jjlocfkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2qhxorvbn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2crpxqtyd.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gt2sxwkppqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gt2dlgvmrqx.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2eyqfgfic.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gt2aqywpkwa.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2jirxywpq.html

Java: Collections.reverse(list);
来源：http://dali.0kj1m.cn/Article/details/gt2ixfxxzip.html

Go:   slices.Reverse(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddguimvo.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gt2aknixpgv.html

C#:   list.Reverse();
来源：http://dali.sweek.top/Article/details/gt2vifnplek.html

[D12] 查找元素下标
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaklpfsb.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2kyejhhii.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gt2fihocoia.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2snkibkiz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gt2dvhjuvvf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gt2vzwsmzyq.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2mszxoexi.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2xkxymxjb.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2nwcrhgnc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gt2jmerfkiw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2bltehfao.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2belxygic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gt2foucovzx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2zdfcloei.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2kqkmxpks.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2btuwtmoc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yueranfly.top/Article/details/gt2gvdndxlz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gt2ifswdjqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gt2dlhoyfjb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2cnxayrmz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2tphvqizh.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gt2dhuxsnbv.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhqmxhfj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gt2dtrflgsl.html

Go:   // 手写循环
来源：http://dali.tianlin.xyz/Article/details/gt2aeotfntx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2quypqcvl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2zmbgxcbe.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpvhjwxp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2zyanoibw.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gt2wroabovi.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2onkuvfei.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2wruxrdeg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gt2qoooyazd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2rmzsnzcg.html

Ruby: arr.uniq
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijfxnjal.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2evsfwaiu.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygkbyuvg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bedybsnu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjijmwzv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2unvecrqa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ywgliswy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gt2haxbfwjy.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gt2yddeuyhj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2zismsfas.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gt2yiuejwae.html

[D17] 最大值与最小值
来源：http://dali.yj20258.top/Article/details/gt2hrtvztsq.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2frnbukmy.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gt2vqekzwub.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tanke756.top/Article/details/gt2aiwceetj.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2badyhgvr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2gcisaqzg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2krvnzivx.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gt2jzhcnome.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gt2digwacvx.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gt2odnhdhfu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2nlsmyhrb.html

PHP:  array_merge(...$nested);
来源：http://dali.wangdashe.top/Article/details/gt2qzlosiko.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gt2zjewztyd.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gt2sfpdpszy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2uaibxpwa.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gt2oujytowk.html

Ruby: nested.flatten
来源：http://dali.zdqjudy.top/Article/details/gt2bltebtdo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gt2vtjspvoj.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2trktdgoy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tianlin.xyz/Article/details/gt2lzcxumkn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gt2hvmejvnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gt2lbalfkiz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkqrnxmg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gt2fuoxmbhl.html

Go:   // 手写 map[string][]T
来源：http://dali.zycfv.cn/Article/details/gt2ohxfaeea.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yvedp.cn/Article/details/gt2fqefqnjo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2xidvmfej.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2xpdikzbk.html

Py:   Counter(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2rdqhcffu.html

PHP:  array_count_values($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2nqacqjlu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2urgpwsgv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2uupvnsqw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gt2eljjenty.html

Go:   // 手写 map[T]int
来源：http://dali.sweek.top/Article/details/gt2jxtxacme.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gt2ehypeybv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uejkmell.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2okuqwxow.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gt2ourzezjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2gqwqekbz.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gt2vbzkuzys.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2mkntdaiy.html

Java: list.contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2zxxziitq.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2rbhftvfg.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gt2xigdezmk.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2demqbflt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2iginkeok.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ilzhtjgw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyophogh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gt2vhtvmvvj.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gt2adwfgbqu.html

Java: new ArrayList<>(list);
来源：http://dali.smart0.xyz/Article/details/gt2hoqshgzb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2uoplloqy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pycfn.com/Article/details/gt2cdqmtosq.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2xmvwsklo.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2ohziqtug.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gt2txzrfjoh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2pbzrqvwo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2ymwicubb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2rccivhwi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gt2rhcwxuuf.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2mjpiesqf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gt2vsmujxus.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gt2xocxucxl.html

[D24] 字典 / Map 基本操作
来源：http://dali.kuanghao11.cn/Article/details/gt2ddzlzjyf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2famurqxd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2lxmzhsrs.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2pkmaybcz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2uvkaffts.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gt2utpirjhm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gt2wqtbagij.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gt2zpjrmdpb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gt2npkekufo.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gt2oxahupyd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gt2tmsbkrlc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuanzx.com/Article/details/gt2ixwegdbw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ksoxlire.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.c1oappe.top/Article/details/gt2otvxofks.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gt2panwatvg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gt2rnvecgwa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2insgjkra.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dumgtdrb.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2gbkbjbgl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xziqi.cn/Article/details/gt2npbxthie.html

PHP:  implode(", ", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2zrgsqwnj.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2bhakrejy.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2rfnjlsek.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2qsavqnrz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gt2zhsvzwkr.html

Ruby: arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2lblfcyko.html

C#:   string.Join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2vtoplkbq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jospocqh.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gt2umjagmwn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opvzdmmp.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2tzdsvunk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gt2mlmnbsyp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2aaoqqeet.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gt2pabldobs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gt2brsmynzn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2lnkhbstz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2dzpekkjy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2xyxqmuvd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avjlndya.html


<!-- 参考信息 -->