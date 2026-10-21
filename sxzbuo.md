代发 wailian999

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gtbipodemx.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtqfdpcjpp.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtwubbxtoy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gtjjgpqnag.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gttjcaryed.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtmkzcixgz.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtfratlrnf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtqbmblfjs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtvziliczg.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtzjbcxxyj.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtgkextplh.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtxzgjhira.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtdrtjvfpx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtldokzxjh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtniuvbtmb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gtmaxkiabz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtxrdgyuou.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtpezojqda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtvdevwoyx.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtuqskexzv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gturjokkqj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gteqqjtpxr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtzikfeeij.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirqxiopi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtpllgqxuz.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtceunnelp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtecwrqnbq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtuprkedir.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtkwvsvnmy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gtkswkebal.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtayamdifl.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtvqbszdla.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtxishlolu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtwqdejggb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtafcwhzpb.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtbwwiaeet.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtiiqqnzsy.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtorvdvkjr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrlelntn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtqjtgfled.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtiufijdfm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtygnuqkjc.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtcysmydls.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtqlsfskqr.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtmfyoxrjf.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtxvcswikl.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtvmlrkzmw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gtiiocbqpd.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtntojtenx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gtjevgcuic.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gthzuiivke.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtifqifkrg.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gthintfzfw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gtjrddlcqb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gtuiudniyg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtpxqroouk.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtnbxszmpg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmbabyqie.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtagkuydyq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gtbwpfnyuk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtmlexjsgp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnpkgntl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtjofjhecf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtnnjhhvuo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtihuardbd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtujmatgbb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtmiuvmilx.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gtkmheopno.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gtyhcowmuk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtnvyzcssh.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtytdsgfhq.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtiwdpulwb.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gttbrzvurp.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtkodbsoue.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtnfuqdubl.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtpyhcldkb.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtskzvrfgr.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtwijwqtoh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gtcldztxqf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtzgjzwowt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtedfpozll.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtlnhlrroa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtcfliwcjv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gtnersyikr.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtluurkqxw.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtgknhswqg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtnyktbkpe.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtbfhcycok.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtvkuvfmlt.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtlksvimjv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hongshengwenyu.top/Article/details/gthiqhyomk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtxxjnvler.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtccgravtn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtlnaxadid.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gthzswkhdg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtrzkcgpxb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtqbbhgvuq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtctaioqmx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtgvnqzlpd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.iojbl.cn/Article/details/gtmpugqdtf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtueidfzdk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtefqeexgv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtlnzeibij.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtcwgatmbc.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtitjhvaop.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gtzojlajvn.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtoqymaxlv.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gthcxhlrjn.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gttvgfbjzu.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtdtpaccfj.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtpoopthia.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtdynnkkbe.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtsejnnzou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtlbqfaobt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtyxoaubay.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtpcayjatu.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfummdaxg.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtaemmfukc.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtyscdatch.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtnxyxapbp.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtsilkwcqx.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gterjkgxwx.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gtojwhinyk.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtuoysbsis.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtnitiqhdr.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtegrnmjjd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtrqitdyyq.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtqmdvrxkm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtpoqwyrke.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtdaoaipfh.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtszjggsnk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtajjgcias.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtmdcnebwt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbukumxh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtnaskpial.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtlolhkelz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtyooewsiy.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtfdthssmj.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopwekbcl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtptvehmrq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtjpcufcya.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtysxqsvvw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtnjdkqtie.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpmvvgju.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gtkfvesorf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.birdmap.top/Article/details/gtixptwoge.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtqfyahyam.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdnmfcsj.html

[D11] 反转数组
来源：http://dali.jlsjyb.cn/Article/details/gtnfwwchjc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtjinjbgrg.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdelywcef.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gtqfgvrfse.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gttkzlkohk.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtlaurkbfu.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gttxyuiqzf.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtdkmpfbpr.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gtsowutebz.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtsyhgmduf.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtjusrloiy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtkthwwamf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtxpuwcxhw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtfyleyofb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtyhhnxxvx.html

Go:   slices.Index(arr, x)
来源：http://dali.yongpay.top/Article/details/gtlrskmojy.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtspahejab.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtizpwvgbv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtnjizmvkf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtiijwujpo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenlongwang.top/Article/details/gtkihxyvnq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gtsbmjsyyo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznlksgca.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gtfkualefy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fzhhl.top/Article/details/gtickourrz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtorycemxv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtxmgqeknq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.havefunace.top/Article/details/gtfjhzzowf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoghtflxt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtdcwvxcto.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtfsmaxsip.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmqgnodyb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cashguo.top/Article/details/gtqcrvjkst.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gtljotuyhq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtnslreuho.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sysykeji.top/Article/details/gtkbkhtyxc.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtoajjbsxb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtraeytwan.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gtfueyenla.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtnrywmudi.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtcqmignwa.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gteuqtrdnr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtygximozx.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtsrmbcltc.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtguhxrdzx.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtufrkhlyl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtzybjxugd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnqzz.top/Article/details/gtdalfdqoz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtioauvxrm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gteibnvlod.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtlhraymoq.html

Go:   // 手写循环累加
来源：http://dali.cheryme.top/Article/details/gtunkzjhsm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtbeckjadv.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtbetreajr.html

[D17] 最大值与最小值
来源：http://dali.yongpay.top/Article/details/gtlfpffkbn.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtvoqpmbak.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gtnnntgake.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhvhwhda.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtaazslziq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtevbsdvgm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gthqzdudmt.html

Ruby: arr.max;  arr.min
来源：http://dali.guannengcc.top/Article/details/gtdhiqrkoh.html

C#:   list.Max();  list.Min()
来源：http://dali.nanxinkj.top/Article/details/gtdmzcmske.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtstxdqbvv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtuahiwbpn.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gthnofukjg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtkoepkpyz.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtgdozoopx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.c1oappe.top/Article/details/gtvrknblcg.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gttdjpmpuv.html

Ruby: nested.flatten
来源：http://dali.svipenyu.cn/Article/details/gtrqbigrju.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtktlzslwg.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gtopqcttbi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gteifxlpkw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtvqxyxnch.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtzcitgykz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvflxzsm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gttgjsibui.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtgucfdwmi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtxyimswub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtgeplomwp.html

[D20] 统计每个元素出现次数
来源：http://dali.ybcxt.top/Article/details/gtwrobmlyk.html

Py:   Counter(arr)
来源：http://dali.yuxming.cn/Article/details/gtpzhvjius.html

PHP:  array_count_values($arr);
来源：http://dali.cashguo.top/Article/details/gtxmsanrsh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybgjkpdi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtfyyckpdp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gtdcxuybgw.html

Go:   // 手写 map[T]int
来源：http://dali.zhoulong.xyz/Article/details/gtstultstr.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtxfrirohg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.smart0.xyz/Article/details/gtgymevaqh.html

[D21] 判断是否包含某元素
来源：http://dali.jqgufenzy.top/Article/details/gthsviasem.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gtmjbjxvmt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtoesunhme.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzxafojtr.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtrsjnkclt.html

Java: list.contains(x)
来源：http://dali.xinyue.icu/Article/details/gthvjhjwqe.html

Go:   slices.Contains(arr, x)
来源：http://dali.sweek.top/Article/details/gtmqcdzxvq.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtulnuutik.html

C#:   list.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtkoanouin.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gttnhkqamh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvasgdqzd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtdtdgmmqa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtcgkhasxp.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtryyjgklf.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtdzwymiph.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtjqpgjlzn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtujoxiuew.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gthxkjxiwy.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gtmjxhhscg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtmurhjigx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtrhhwxwvc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtdvkogvdx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtlcknxhti.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xziqi.cn/Article/details/gturqwcoow.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtaikjnhlt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gtusolaibc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtqbykmvob.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtdvugnbix.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtwuzasiej.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtgghfudsy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtdueerdnp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvafvocw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gthmevnseb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtbdomelzm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtbyfkasra.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hongshengwenyu.top/Article/details/gtlakanrdx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gttckymdtk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gturpkedsr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gthpyawena.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtomecocmz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtmllmhsic.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtiackqfbn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gtsodwefqo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gtqlghhahu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwxoqlza.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gtcdrsnxzo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtshcohmhd.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gtwybcjjqu.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtbylmrfls.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtlgjwnmlx.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtwwhwaiks.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gttvsnpezp.html

Ruby: arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtafqojrjw.html

C#:   string.Join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtyzlqgxay.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpfpqfpzo.html

E. 字符串处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzrhspze.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtviahpezm.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtchmpdzfb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cqqwz.cn/Article/details/gtujazmasy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcofolxzm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtdwuibwhb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtosfwgkzx.html


<!-- 参考信息 -->