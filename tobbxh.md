代发 wailian999

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtzyirnjtl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtfbxjevxk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gteecfejgu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtmncnfsge.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqcufvbg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtzvjnkofh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtfsiacspa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtaifnyjov.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gthfhsoswr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtfisjcxvl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyptmgro.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gttarbamnd.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtodfrnmuh.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtzddklrnc.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtcrdsavwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtpfltygyx.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtbusdtxec.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtxsdwbyau.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtbkermhfp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtcodeguop.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gteygsxxzk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtqdhjurks.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtpduserzq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtbrjhnpbe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtnjvhillr.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtjavsnggu.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtwjkzacyz.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtcrlosgwu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gthqniyuoq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtwbgtcpfy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtofxkbfxj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtrcmqddio.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeddcrxw.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gttisnxgmr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtsyeutqet.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtqpenkirv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtumspmnnm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtidbsmdro.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtehkyjwnl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtnmcxaepx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtpgfwhyrd.html

Go:   func add(a, b int) int
来源：http://dali.iojbl.cn/Article/details/gtazdvfzqk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gtehckehsi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtekfeuviw.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtklsuiobl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtbxovxsuw.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtozvdbutp.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtbpoftcxk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtkguymvod.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtorvjwbyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtakyghgyz.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtzbpflyvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtpgxtomtr.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtnrgjbxfr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtekdojiab.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtresgaofs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakhyalya.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtsouxboye.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtoewawwpx.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbnklqum.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtllfboich.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtarvozgjx.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtwgxkyypd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtpfpurofg.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtypmfxjht.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gttgpqpomp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pengpengdd.cyou/Article/details/gtdcnozpcd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ppjwa.cn/Article/details/gtlfqdvyag.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gtukysrhmw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtvsoljmjn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtffwtykho.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzjchhzq.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtmhgrpcrd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtomycspkv.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtprtcoxaj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gtmydqlbvj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yonumen.top/Article/details/gttkehwmsu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gteevyhdce.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtkymjxpju.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtezxairst.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtofelmhzk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtcglkrejx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtejprlhqn.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnluildo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gtbccsmxpu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtagwyoazn.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtbabnhnzw.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gtvvsdbmqv.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtcewpfwav.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtsidglnhw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtngcpymxh.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtqlmuckgl.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtbwspgjsc.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtoxpxmwoq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtfcxufoby.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtusqppzte.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtywtlpuwd.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtysuggqga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtcrsfetvo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gterlhnfnh.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtnjcdzapf.html

[D04] 删除元素
来源：http://dali.iojbl.cn/Article/details/gtywjwcqsg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gtjnghusxd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtjkhwsxuz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtxnsxfiog.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gtdkeyxylc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggizdqkt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtcvskutwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtiqadrecn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtzxrnnuyk.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtsenhgprw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtnxxclzjb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtowvmbdab.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gttqrkiixo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gttsktroqg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gtellqoihm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtamwgpaig.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtqsrijsrz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtplsbopkc.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtlojksivs.html

Py:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gtnjguileb.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpixilrco.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtdmvxnpnv.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtmswvgtqn.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtmtttgwoc.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtczdpfwdm.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtxywnzthc.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtxhwwhlqe.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtpjduzsik.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtviedndnt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtwzxvayat.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtkzuzazbc.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtkwqjzxgl.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtchdagyfd.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtlzkggdms.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtbxqbflhb.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtqggwugfl.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcfohttt.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gtqkgladml.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtzygqgezc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gttgeswler.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtdzbgwxyd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtsgnvmzaz.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gttnwioprd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtaukgzyzq.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtlngpucen.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtbsemrmjn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtgcplugzx.html

PHP:  sort($arr);
来源：http://dali.0kj1m.cn/Article/details/gthhaxlkss.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.316326.xyz/Article/details/gtjpqbxzag.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gttitchpbt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtnlloyrzt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtuflkkssb.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtxxdbegya.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtbmcbrowl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedjjgytb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gtilqcoxpp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtxqxmfueh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtrxvdaeoo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtbcvwvyvy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtaggfvegu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtbentlohh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jyoumei.cn/Article/details/gtcuzdevqj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hfpthk.cn/Article/details/gtxdlqdzkg.html

[D11] 反转数组
来源：http://dali.cucudq.cn/Article/details/gtdrluutrb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtqpspkaem.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gtzqlpalup.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtrfffgouk.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtsuhxbvjz.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtbssbeeic.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtehgdqlid.html

Ruby: arr.reverse
来源：http://dali.snrcjt.cn/Article/details/gtticysegm.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtytlzunsy.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gtpkgadwus.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gtncrylrat.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtczafwygt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtvpbbzzpr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtquethsgf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtuezwgpgd.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtgapmlcgh.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzlyfzfnk.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtrsxfwoer.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtqynjwrju.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtotpdufcv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtwwverxcg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gteeamqebx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aizwys.cn/Article/details/gtppcenybs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtidtnmuhs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258888.top/Article/details/gtekagqmpd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtvhqlpumi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtjvngnoqw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gthetdthnk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtxdlumgme.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtsmlrqbya.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtpqsyqbql.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtpwabkbmz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcomdnhyw.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gthuthrsad.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtvehnvbqm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtidksipkz.html

[D15] 去重
来源：http://dali.hnxiangtu.top/Article/details/gtdgzmsqtn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtjokgeqng.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtxghpyqej.html

JS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gthdykotey.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gtngwzuipw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenlongwang.top/Article/details/gthrngdrpa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtfivgaibn.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gthkcggecw.html

C#:   list.Distinct().ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtwtbpreks.html

[D16] 求和与平均值
来源：http://dali.sxryk.cn/Article/details/gtkqrzbkxn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtmfsaqchg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtkpklmjof.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtvdrmkzss.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkrsltvwu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gttxadbuxw.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gtfgcehuzb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtdvyigbgo.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gtsgtbebgp.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtxudrowsb.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrodnkhu.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gteiiskeip.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtqzzdngza.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gtcyxsaltb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gthhxztqmj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtzhqpahaf.html

Ruby: arr.max;  arr.min
来源：http://dali.yj202588.top/Article/details/gtllfjybac.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gtsqtcrzhk.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gthtbbshaf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtarnnjcuv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtpinookbu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gtecxffejh.html

TS:   nested.flat();
来源：http://dali.wangshuangyany.cn/Article/details/gtctdzxbae.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtptvwzrhg.html

Go:   // 手写双层循环
来源：http://dali.mhx1999.top/Article/details/gtaskcpwpm.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtsydjydss.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gtnlqfetla.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtjapgwbps.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtuufwenrt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ehwqpu.com/Article/details/gtctlgzgtv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtaiqigequ.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjelsiwj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtjnwoqftg.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gtvbyueczh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtgsjoaybf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gtktyfrqaf.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtvvoytmxr.html

Py:   Counter(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwehflecg.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlbvuamxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gthfxfqopx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtobrebqqw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gttjtbltmh.html

Go:   // 手写 map[T]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgslqqba.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtaxwkenln.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gtkgelvzxp.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gtrvcipgue.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtuylllcjq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtptjmeipr.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtrmrlivha.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftlxwdxw.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtsibcsfam.html

Go:   slices.Contains(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gthpneupnp.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtjzfaegsd.html

C#:   list.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnmvpgrdm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gthrbwswzs.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hnqzz.top/Article/details/gtbpqsxbdj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gtpuwsvclu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gthzrqexvw.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtixsdpwyq.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gttbrhutks.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtvnoiymty.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtpqnraetp.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gtonooqqlp.html

[D23] reduce 累积计算
来源：http://dali.pengpengdd.cyou/Article/details/gtsqxvkfit.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaldnvcne.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gtozkfloce.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gthafbtplf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtgpyidhht.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gtdfwvonox.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtxdiizthq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtvlqrrrmm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cqqwz.cn/Article/details/gtvhravasi.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtwoorhlvr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtglnrsllv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtbfwlbfpr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofxxahlh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtcaayzrwg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhongyouzk.top/Article/details/gtxgoyfawk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtutcibqba.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtheudkana.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gtluhurlli.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtahvtsled.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbliijnw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtnyzynbkf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgctiybdf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsumcwyj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtpjsnmfzs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gtojfcfkzk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gthsecfcwv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gterfskxrs.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gtrtisaqka.html


<!-- 参考信息 -->