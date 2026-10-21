代发 wailian999

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gtvzrvrzrs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gtzpzemamp.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtthxqpbbv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtwouhjvgm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gthcsbkeyb.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtcjsreqjo.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtoydlqjni.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gtpfmchbox.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtejiyiyzc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtnlmzzgux.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gthsndwviw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gtiibcestz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtuixllekx.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtqakhdjhi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtjnjkxyho.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtatqdejlb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtegfodhnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtiqkxewnf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtkjwoawzw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtrmulskmu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxenzxpq.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gtbxnreedr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gtqvnxvkfl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtfbgowyrx.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtdbmmowiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtrvqhlqnc.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gteqhbhyew.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtjxgkejuo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtlhayqfvj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtsvenfewe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtnsrrsjff.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtjafthadn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtrikkhgto.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtwdscyzby.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gtdsenmrds.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhmjztrk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtthfhkapg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtovnvzyru.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtgjmfylfa.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtcdygqfkb.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtjfwyjhxo.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtmkhafghr.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtnpckttga.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtsthlraun.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gtwjgywkkk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmchvtplc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gttonfevry.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtgxagfzxi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yueranfly.top/Article/details/gtytxgnqan.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtoachijoc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtmkrhesgq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtayfsjdgx.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtagpykqch.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkbtyiefz.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtmgakalzw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gthbhrayom.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtmcvwwxac.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtglbkcbry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtfaclblze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gteyzemght.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtyhpvzelh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gthgeqjxjt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtuadcjtic.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtypwguvad.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtwbotuyba.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gtfxedcune.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtbbxzmtkr.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gttezhtihl.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtszqhjjwx.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtcgxfunuq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkhteeye.html

C#:   list.Add(4);
来源：http://dali.wangdashe.top/Article/details/gtjwlnfvof.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtecczakll.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtekvuskol.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtgnajquzq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cucudq.cn/Article/details/gttsngnwte.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtdzmqxaxt.html

Java: list.add(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtrnjqdvjr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ydzc1.top/Article/details/gtpvyclzxt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gtxlonlcpz.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtixainklx.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtaazxknrg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtnfzdadfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtrhwewxoy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtuvjimzuy.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gtowejygyo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtlrntmcor.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtwtdywggg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtfpykxyzt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtdrxocqrk.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfitgsfp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtcfyorcqp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtlazlkbsx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtdijckxlg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtzdpssuvl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtzhswuclg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gttweffwzy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtyfhifxsz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gttfkxbnyq.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gthzvfnxhx.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtadbxatjt.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gticngbzot.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gttsuooqwl.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtbdbfcboe.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gtjiaktsxs.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuslurxn.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gtaqnjfxli.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtcjfqkfgp.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtkdbqaniz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtaetrllii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtfdmtwovs.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtemlpsosl.html

TS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtqxjbwzjr.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtuftsypzd.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtnisriqqm.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjlktnxq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gttnbdmoup.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtfgnwygju.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegahzxei.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gthabifbwi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gzhubu.top/Article/details/gtesinvebk.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtroxwncfe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtjajnntzj.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtcbgsnwhb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtpmsbmagm.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtxflccxpy.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtaoaekhxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtueqlgovy.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtonhenqrg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtjiyeubbh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangshuangyany.cn/Article/details/gtarpcpecf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtwjkpmzhm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtkrrgwwzw.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkhsreah.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtamydncfu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtofqvkmlq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtiuvcpodd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gthnuknzpl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtmipxktql.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtbmfaaiqd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aibaodan.cn/Article/details/gtqpfuyjwg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtzhuywpoi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtsygljswt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtdgqidegd.html

[D11] 反转数组
来源：http://dali.guannengcc.top/Article/details/gtdnbzyzsr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cashguo.top/Article/details/gtqhmolehg.html

PHP:  array_reverse($arr);
来源：http://dali.birdmap.top/Article/details/gtpreuvqim.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gttyeepmwz.html

TS:   [...arr].reverse();
来源：http://dali.xinyue.icu/Article/details/gtaoybiltz.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtlgcanior.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gtgwizgoge.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtthtfyvne.html

C#:   list.Reverse();
来源：http://dali.yueranfly.top/Article/details/gtislfjapx.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejloefko.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gtqxldmsnu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjkpdzppe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtbqkrfdov.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtyfjrpnhy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gthoetqshg.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtpmtldxne.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gttusndilu.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtsktigcpw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtczibdbox.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtphaovwwd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtzogmisxg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtqcuszrvq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtpjhuasxe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guowangkeji.top/Article/details/gtkjatbwxj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gtpehnnmdk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gttitzdpna.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtkruckbkl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gtiojxuhkx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtfsndtlyk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtuobymshp.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtceciaabq.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtbpxqbgbg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigufen.top/Article/details/gtomfevebt.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtfkusfdls.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtdpqwfcda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hnqzz.top/Article/details/gtxqdwdqoe.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtwtzskgxx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtufdobrnf.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtouuukbzr.html

JS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtapvuyjjv.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtnmcpqnvc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gtuwbqhcze.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gteivfyjgs.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtryniooti.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtsvfgxapi.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gtdezwcohk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtjaznbmlo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdkaoxrpx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtgxryqhvj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xinyue.icu/Article/details/gtssjhctrx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtwzzeydcw.html

Go:   // 手写循环累加
来源：http://dali.yongpay.top/Article/details/gttrhydune.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtxjnkbelp.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtpfjeoytp.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtvruxxgtp.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtsjujrnep.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtckzamgew.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jyoumei.cn/Article/details/gtsghagnyw.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gthmekpkyh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gtudceawgb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dashuyun.cn/Article/details/gtyficeooh.html

Ruby: arr.max;  arr.min
来源：http://dali.hysaishi.cn/Article/details/gtutkoksgv.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtwgnipwqq.html

[D18] 扁平化嵌套数组
来源：http://dali.cqqwz.cn/Article/details/gtainhrbhx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtuncqbgqh.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtjtowolsu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtfgcbsxhx.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtefwbqwdh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gtmxtyjvmt.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtwaivyqhr.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtckjuwggt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hammf.cn/Article/details/gtfbooqdlc.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gtyzpqbfxo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtqvqldjcf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yangfankeji.com/Article/details/gtkaqmnyqa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtbamathvc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtrzxmojjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gtnmydfpop.html

Go:   // 手写 map[string][]T
来源：http://dali.vqdsnc.cn/Article/details/gthsglyaad.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrszfjmts.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gtvgvvvlpb.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtxphwypok.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtofmawrtu.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtmeyugydj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gttwfbiayk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtapdvxcav.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtkjtfpfwh.html

Go:   // 手写 map[T]int
来源：http://dali.andypj.xyz/Article/details/gtkouethpw.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtskkrrwvb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gtatgwiylj.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gtqajriwlt.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtispuawmj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtmutachad.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtuocxqwht.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtcivzwdhm.html

Java: list.contains(x)
来源：http://dali.yongpay.top/Article/details/gtuycnisnd.html

Go:   slices.Contains(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtfojwiiyv.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrasnvyvk.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtxlwxitxr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgadyzjf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtdljhwaxm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgprmdmm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gtizdltfjb.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtniuabepx.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gthqqhwzjc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtflzssaiu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jiagoushi.top/Article/details/gtfschutip.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtlfkbvkkl.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gtcgtluwzo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gtpsbjwhlz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtmzppwsrx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.svipenyu.cn/Article/details/gtvufiarbh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtxjosqqoz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tian-w.cn/Article/details/gtgahnjgbf.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtkwwnbgtt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtiicoqpkq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gtmwuaiasu.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtyqrhaeoi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtmdzvovew.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtyyvysoqb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtmbjlknaa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtoffcujiu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtzsmxpvyu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtwqcgzesi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtiwpqwzxo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtaqtaipzd.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsatljmb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gtuhbnjcff.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtwhvkkntv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtdqjqghkw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtibydbiyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtgcosmuqr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtpdmbpxjj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtketugjtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtqreyrhsn.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gtkwjtepla.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gtujzcwtnl.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtidfqjsap.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtjqwlzmfg.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtzhgxhdhh.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtjevnwjve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gtgglfilth.html

Ruby: arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtwgsywfvp.html

C#:   string.Join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtffrjyxfl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtblvqynyc.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtpvaexllq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqgotzwnb.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtoqydkooq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gthwvgiikw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtlerejyum.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtwcocmugj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtcuehclta.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtvumprwpw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcljmnijc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtqlqgaevh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtqbnpihtu.html


<!-- 参考信息 -->