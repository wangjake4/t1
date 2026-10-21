代发 wailian999

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtycdtmbsq.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtzaerxmdz.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtojwmpovp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtmsluxiph.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtfvadauzj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtxbqhmkot.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gthtwljhsi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtowzwlunc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtaruwofrc.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gtedxtiexp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gteqghdquo.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtialbkmec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtncnipypw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtggpgjvtd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtpgjspmbx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtelpuummb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtbyutdmms.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gtlstelzsf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtnlxzjdwk.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtpcmjntlq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtjohvztyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtppmwwwod.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtzcsnvrex.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtmjikvowh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtliafasav.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtmyssalco.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtobhqinrj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtrdkmjzuo.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtpjckpvxc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtmsmlfraf.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtgtgppcga.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtunlspbib.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtvmaukqkb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtkmqsffhe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtvoymigrt.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gturoccgnd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gtvfiaudzx.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtofwvhbjd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtvtuxynlw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtnsbsoiby.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtunrzoxbm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbhwphsyh.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtlailljjm.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtwrkkstef.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gtjgdtzlyl.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtetwvzgyp.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gtxskxrltd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtpthyknaz.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtqpjtiuvm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtiaceepud.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtdgyoinie.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtxpstlgvt.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtvtlnrofm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtowqfekvx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gttxzjstkr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbnmbpyoe.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtcxgotkgz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvjbzfnik.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtoheutwsy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtggwrsmha.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtjpnjperj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtytyrrtlq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtaumdmfzj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtsdsrxmjw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gteuduyvsh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtvjngsnrg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtwaqgtprm.html

[D02] 追加元素到末尾
来源：http://dali.hnxiangtu.top/Article/details/gtkfthycsa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtsoctmhga.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtsonzzvns.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtpijwoqha.html

TS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtmbbvizxt.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtkidsksaj.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtriolkrgr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtluhsrqop.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtpiyatnez.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtltsoghea.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtlwwwzlya.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtoqzrsgqy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtgmujtqxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtuwcclfhu.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbtnxkjh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwavlrro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gttjycrqbo.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtruliqpgb.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtsgahgezg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtxhixxmbw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yongpay.top/Article/details/gtncukwrnw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgngbtmks.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtybcgkhay.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtbwyekjve.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtkpwmjwun.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gtdflazryh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtghlhvoox.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtwjtlrjbo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtcqmyoywq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gttmuttxzb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gteukvecpn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtpboyryeu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtafvoiznu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtshtgwetr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtuzxyzufp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtzwokrbqc.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwdimiwr.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelfcupap.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtstergijm.html

JS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtdphlmsqp.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtbvxffmpz.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtkaiqecxv.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtnjcuqkpp.html

Ruby: arr.length; arr.size
来源：http://dali.redwolf501.top/Article/details/gtfedvubwz.html

C#:   list.Count;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewrmzjam.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtxzlxqdtd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtdxvgjcdq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtdllhvbzs.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtctjmzpop.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtyrrekpdr.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtrplouxut.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtljkhiuzp.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gtwzeawkxf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlcxludt.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtcbnjdmrr.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtixqgpmia.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtfoaoujnq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtlmavlajs.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtgpvbtmlp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtoykiaqpk.html

Go:   append(a, b...)
来源：http://dali.pycfn.com/Article/details/gtdorsoujv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtlxhttfyi.html

C#:   a.Concat(b).ToList()
来源：http://dali.cashguo.top/Article/details/gtbazpmgzb.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtuweeaxox.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtkhlajcqv.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtdwqeeihc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtzgmijnrf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtizpjrufx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtmcuyzwmp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gthnudjgxg.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gthtbpxilm.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtzisnzlvj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtumebdfzx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtyvslmycr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtrswprlda.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtulxspyut.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtciymwylw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtqhcfaexl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtmjpyiupz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtpucsiqri.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gtjujvvggs.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtqdtkujee.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtqzlnmgwg.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtcahupdwk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtcajalpjm.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gtyyjcnxeb.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtvlaqlpkj.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gtrsktssjy.html

Ruby: arr.reverse
来源：http://dali.aibaodan.cn/Article/details/gtxrtylkek.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gtsgldvxxk.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtqtcbefzj.html

Py:   arr.index(x);  x in arr
来源：http://dali.meibo888.top/Article/details/gtonjgvgxo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtboqtwvzd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxjmhrrx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtvnfahekc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtjcorcfhp.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtjhecddhu.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gtgfqlkudj.html

C#:   list.IndexOf(x);
来源：http://dali.yongpay.top/Article/details/gtncidnrly.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhengqikj.top/Article/details/gtusilxfcm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gtxyddtkmq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtfsivtjxm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtujqhahgk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtzyiyeitx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtdfidrkhh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gthfiwzxib.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtwxnxgwzv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtypfehlha.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gttzysvbjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtnyheebcf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtyykgyedl.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtaynfuncp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtlsyjigmb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtpkmhifgx.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtvsebmors.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtbmfoudon.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtnzmlnuaz.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtsvlwqtwt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtxffwcrrw.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtoxnflrqr.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gthvoguzhb.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gtxvjjzoyn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtmmxujaxn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtxqpvxlrk.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokfnijhn.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gthobsdrws.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjooztqhd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtxolqvyrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtgfncexum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gtashswfil.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtocekflpt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gtypwbgmxk.html

Go:   // 手写循环累加
来源：http://dali.chenjidiqi.icu/Article/details/gtutfejrdo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gthinqyadw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gttgzhyqlo.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtuyabmlnv.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtiqcljkat.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gtwixkirju.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.birdmap.top/Article/details/gtusxlaijw.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtwqjpjzej.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtalwnfdhf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtmgricgql.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtpimofpqa.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtbqqbnmym.html

[D18] 扁平化嵌套数组
来源：http://dali.mhx1999.top/Article/details/gtnielqwof.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gtbfkkjqvl.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtwkoleard.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hnqzz.top/Article/details/gtyyywqkal.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtwynwurys.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhghzhvw.html

Go:   // 手写双层循环
来源：http://dali.chenzaomai.com/Article/details/gtkkplrgdg.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtgklzweke.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtyukfwzqn.html

[D19] 按字段分组
来源：http://dali.zhengqikj.top/Article/details/gtigacnbns.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtzcahmfqh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtjirzsabh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtvfldmcxa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtvwjoxckg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtnhinscwx.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gteygbgtfx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gtjwdlzrok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtuylukucw.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtmiofkphz.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtyvibkouo.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtcfufnrnb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtkxlqsxtf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtacqjwijp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtbskvoxpz.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtrlenpjsi.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfidltkj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtloqnczft.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtiyfgssru.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtghblwzvf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtcbwftjet.html

JS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtbwwnusiu.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtekwaiimp.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtzqjccsdy.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtlqklfpxr.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtvukdrldf.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtyhvwkgxt.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtuxsqjsdl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtxcmiqbbc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gttdkvqpdx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwyathcu.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtxcikghiy.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtpnvipcme.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsggmlzjs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtnmuftjcr.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gthgmpczzk.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaefnwlla.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gthlpwvmtr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtaimcfobj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtmaeacoci.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtzwuejezd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtzorjhsnl.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtctsixvmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitiirvxs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtgoqhheug.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtwavcgzms.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtgcntkfpo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtcbxgouph.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtvemqpkpy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtzbufbovp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtajfxrimd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtwroxlaqn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtucqvkezh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tanke756.top/Article/details/gtjfpeqnrp.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gttajnwkfa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcbqsldn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aibaodan.cn/Article/details/gtzguyaugo.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtalnzbyno.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtwcevuxyd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtfvrlymbi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gthoaivnww.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtsxyiqxio.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqplskarz.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnxjzrpjf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtcoyofnim.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtcpkweyvb.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtxoirxquu.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtdajwnoyx.html

Java: String.join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gtyoyglusn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpeezmee.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtyuvcjtxz.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtvtbvkhrr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gteqqddkrb.html

E. 字符串处理
来源：http://dali.hnqzz.top/Article/details/gtystjcfcn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrhkkxxrg.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtdcxcaymy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtlvrsemal.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gtegfwnsua.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gthfzcmrxu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gthdnofyoq.html


<!-- 参考信息 -->