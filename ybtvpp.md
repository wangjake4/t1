代发 wailian999

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtrchpuhpo.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtkvhqhqah.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtibbylofs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtmelqhojb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtpjvgudkk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtrezgyzii.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtyjzohtgl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtfxarfmry.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gtxmrsvuma.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtfvxhhyoz.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtyfwdpozz.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtwsapysex.html

PHP:  (function () { echo "run"; })();
来源：http://dali.redwolf501.top/Article/details/gtcrgllaou.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtzrynicvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtefbgvxfn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtvdlvphmp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtdihqgxda.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtnxffrksg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gttlpuguak.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtjkxppjia.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtkdzertkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtvfpzdlnp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtmvgtstgp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtglfnumfa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtwbysquhu.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtffdzjyqk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtnirqynlk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtnoqgllor.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtzqixuqsp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtttqckhdk.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtwzrcwvuv.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtbsvwrzny.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtrfnxcesj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtpguaoyhf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtbirahnbz.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtujvflqgz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtvuugttku.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtetnrexel.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtjqqsxcev.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtfgexjant.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gthqrbwmlh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gthatpfbnl.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtixieedhn.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gthwohilet.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gttieewmao.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtrgjdwjkd.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtqlsyhykt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtmgoqrrlc.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtbykznsxj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gtgeuvwbji.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gthnbvxags.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtieotfwzz.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gttxjtychq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pycfn.com/Article/details/gtwtwllnou.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtloodchlc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvbpthvus.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtzprbhini.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtschzcsea.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtzbsqcewa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtufubyxbp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gthysjzoah.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gtrsefgene.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtzrwanxja.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmdlvuwt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtqghxtqmb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gtwckuqrqg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gthmdfwolk.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gtfwolgzqr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtkvlnheij.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtvzgkifpq.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtfqurovzm.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtkomcftgn.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtwqufyyji.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtqdragrko.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtqvifcjfh.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtllbfdcbx.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gtkuikqpvv.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtfdkyjxgd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtvpecftds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtztaosfmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtncecurxv.html

Java: list.add(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtkrtuawsn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtakdudzmp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtvcsjnwtk.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gtsogffbga.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtubqkadvw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtobywjazu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gtbudburfl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gtzlkynbjx.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gtykiqizqp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtdxlffhne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gtkxyvyszv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtkrwmrsbj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtrwcximnm.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtzieolxou.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gteadfepts.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtbuzvyfll.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtgqjpgujy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtydjknlfu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtelqentva.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtntygbgwd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtbmyuxhxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtgcbylbto.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtczkfuoix.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtohohbyaq.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtcyvaverm.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtwupcurrh.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtguztiyuo.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtjuemwhny.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtwrvxworp.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtvnxvcuno.html

C#:   list.Count;
来源：http://dali.aizwys.cn/Article/details/gtnywyjdfh.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtjxlqxkjs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtglvrcqfv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtbnfvyftv.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtjkewwrot.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtjccsxzdm.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtwzbntrqa.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gtoyzrtjwh.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtcaylqndr.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gthpreompn.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtxpnabhpd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtthiyrzhj.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtatitzgwm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gthjwkmdxr.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtohqvkftd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtkuvmgmhi.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gthuosrwki.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtfbabqhcl.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gttbktbvgh.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtamgtuphe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtlwiurdlb.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtsauvjetv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtjpgvkn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gterszqbqg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jiagoushi.top/Article/details/gtzwpqkrnl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtfqlgoelm.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtccezpscf.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gthnwhsyre.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gtvytdwfgp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtytqgrrne.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtpueezuic.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtijpkvzgc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtsmevsorr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtdpxjgoqr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojibgfgr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtbianloao.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gtlkyhivdq.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtibiogwtl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtxluiviuh.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gthqumieni.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtsniqnsce.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtdgzrbtuj.html

Java: Collections.reverse(list);
来源：http://dali.fengsongda.top/Article/details/gtkqxxfmzo.html

Go:   slices.Reverse(arr)
来源：http://dali.chenzaomai.com/Article/details/gtovguiqpz.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gtdtbuobpc.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtrdpbqsrj.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtltgwupzx.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gtlpbuigup.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtldfhzdcq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtnsjrwofw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtckpwvqpa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gtyfscedae.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtlfuuehob.html

Ruby: arr.index(x)
来源：http://dali.chenlongwang.top/Article/details/gtpewlyowj.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gtzydvskad.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeitmoia.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtndrxkqst.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtojmdlhgo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtngitsrtb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtplktgxdu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtlqpnbqah.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtfmnmzcxw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtollvzujb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtljrsrt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtcpkvkspt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtkpknphwz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtpmgnnrxt.html

JS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtvtzhjwdc.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteftilira.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtanvffrvx.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtikzdxxtf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtshgdhpgj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtooeejufp.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gtdgepqodv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtxmvwtkpn.html

PHP:  array_unique($arr);
来源：http://dali.cucudq.cn/Article/details/gtkshrthoz.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtvihdgorv.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtjshchegc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nwbrower.top/Article/details/gtldhvqtej.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtrdhqmwcv.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtkrwmabwa.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtxeppbend.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtzstvmmjs.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gtchimapol.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtslvusbic.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtoscvlpfy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtubshqabx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtwcwqypcg.html

Go:   // 手写循环累加
来源：http://dali.sufxvd.cn/Article/details/gtmpivuxgw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gthexyvbqn.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuxming.cn/Article/details/gtsqrsqurn.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtqgbbop.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtmalxzmbf.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtswveygun.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtfpligkbl.html

TS:   Math.max(...arr);
来源：http://dali.nanxinkj.top/Article/details/gtlxlmuymv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yangfankeji.com/Article/details/gtvkqqhlmm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtnzjyslki.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtswnlismg.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtzteuyfgs.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gthbwhhpnq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtmdrpvlzx.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gtyvxejkln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtyfzaybzy.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtwvsuweji.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nwbrower.top/Article/details/gtbjcwuqkp.html

Go:   // 手写双层循环
来源：http://dali.jlsjyb.cn/Article/details/gttdclbcqa.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtfnealjgn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbeprdmc.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtppczvaui.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.kuanghao11.cn/Article/details/gtcdbjrqzn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtpvaebqhw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gttbjparym.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtpsyzvllf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbztlsmnw.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gthpkcpcyt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jlsjyb.cn/Article/details/gtagzlbcyu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gteqpfwnwc.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtqktbtipx.html

Py:   Counter(arr)
来源：http://dali.xinyue.icu/Article/details/gtjunhjyoh.html

PHP:  array_count_values($arr);
来源：http://dali.sxryk.cn/Article/details/gtzecqgytk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtsmgffmnr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtgkrqcevn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtgjixjoki.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtntbwgrwb.html

Ruby: arr.tally
来源：http://dali.ppjwa.cn/Article/details/gteisnfstf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gaohongyu789.top/Article/details/gtwqslcnst.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtbudfxyfw.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtflrpjwte.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtbpjkbzkh.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtmtoitxfc.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtrsvewrcb.html

Java: list.contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtwzypxycr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqviihaym.html

Ruby: arr.include?(x)
来源：http://dali.fengsongda.top/Article/details/gtrusigqlw.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtmsbylxie.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gtkslnjykl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtceuudvcd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtxuhwldio.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtlilqcswe.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtmkrawwup.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtcorsplds.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtayjixrah.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtijqwljkp.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gteqgvagpb.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gtvwpasmtc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtmvxqklkg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweoaifbp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtvybxkhkf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtyvxczbqa.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtyjznybqt.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtuosyqwie.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtygqsltox.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gtzysaprks.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtexuwdiet.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuxming.cn/Article/details/gthshtivzl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gtfbjzwzlo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjhcqugg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gttvyrcgxg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtrqikjk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.kuanghao11.cn/Article/details/gtgfcywnzu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtgsxqamgd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtsageodyz.html

[D25] Set 集合去重与交并差
来源：http://dali.pycfn.com/Article/details/gtmpmqfuhe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtxkoixjdx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyccfdyht.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtugwsyloo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvolailku.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtzkapqoyv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gtugqbmlpn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtknjtwpej.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtjkgnocqs.html

[D26] 数组转字符串
来源：http://dali.cheryme.top/Article/details/gtuvbcregm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtxvhnfrie.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtcslukwva.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtpktsxysi.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtmbrgijmj.html

Java: String.join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtyugaqcvm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtyjyqwqvq.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtqckeetso.html

C#:   string.Join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gtsnrnnidr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxocbrjkp.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gthqwlwlfs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcfjjbohy.html

[E01] 拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtmqnmiqup.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtnjtlwcvp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtqfychdka.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gteboizkti.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtgmccztvw.html


<!-- 参考信息 -->