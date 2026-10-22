代发 wailian999

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtzuvdlzmz.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtsirugsvo.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gthrezheub.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gttccwqqhp.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gtjchictbt.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtrwbwyuzb.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtasyswioj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtncgumvva.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtcxkqysck.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykfbqlnf.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtipkgdnkg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjqfobnm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtllihicoq.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtjptjgnvl.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtxutpjpct.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtemgfbrdl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtckvolfbl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtbswnijnu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtslkflfdw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtfvodpsbq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gtixhnaeuc.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdervvbm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtprztejst.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtkrybxlha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtmdlpweah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtpfyiucik.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtytbpsksq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtdqtfimyr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gttaadbzap.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtmuneyugf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtjztnmkif.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtuiueojuy.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gthrkpvmxc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtjaszyjgm.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtxjyayvzy.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtpcejdlbe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtkkakwyws.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gtdltbfbvo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtwiihnhla.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtehgjrixh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtsonlbkch.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtprxkqhwn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gttllrlqpg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gtsakjequy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtnhpoafqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnvaytbr.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrytnvqwp.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtjggjpzia.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtrhmsbzlk.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtkoloszrl.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtgjvtmfci.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtwopvzecg.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtcqkzvjml.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtyucbknjh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtwtovhrah.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtvnommoyl.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtvsoyqefa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtjbjlfozw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtegcpncnk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjksaywna.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtcoontbau.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfrwvncan.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtjbnbspuw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtiggtpens.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gtgeuuqidz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtiucfklni.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtsyitosij.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtkocicyfh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtbqmzqjtg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtxjoqmrmz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtbnthxtzy.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtgdndzzqk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gtdrrvsxae.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtcaybuljg.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtcuokiktl.html

TS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtxadobgcr.html

Java: list.add(4);
来源：http://dali.gzhubu.top/Article/details/gtgxzhkzyj.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtytylagcw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtfnuhzini.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtqubktomf.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtqpehtkpx.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtbuuoxhgq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtvszzpbbo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtlxiumftf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtcbmnwqfw.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtesyxwutc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtqwildybk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtaykiorye.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gthedwckeo.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtzrifdqtw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gtgqjzeftz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtkvmmghnt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gtznomxvoj.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtnrdoegeu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqcmxymn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gtjdilsftp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtgbtwolcx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtgiieqtnv.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtaygfctps.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtwbyvtvwc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtpcemjslr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtbrsiuvqu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtuslphrpn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtbzucgdxf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtknjoxmte.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtovbczejk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtfmvcpfgl.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddmheoks.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtxxsvniht.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrshppgj.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtfqqisshs.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtbzvipmzp.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtqcsskqwc.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtyhtatyzb.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtdtoubpag.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtwuywbemu.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gtfkwroeir.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtnsavlved.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtabzhxlvp.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtqmbxxrcv.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtwnwlgjff.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtebusjzwf.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtoztqvxzs.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtsnxyjuqw.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtlcpfbtay.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtnhhvtzrb.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtgjmpfwxx.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtrcvyasqr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtkvmtiutc.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoeepeef.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtpkelohks.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxrdbiqa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtgeoedfdd.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gthjqjqqvj.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtkebpvdxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtvqctcolg.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtwufzcvnc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtfkhmyefh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtonougbuv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhwhlpif.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtjfyrvudc.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtzgabdrod.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimoauryn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cucudq.cn/Article/details/gtzkeavyyx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtibbyebih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtaphasffx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtldsimbaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtglnyvpin.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtbrvyqjss.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shuidangran.top/Article/details/gtbryhxwzi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtlphkkqqa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gteividaap.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtiizpburb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtylpzjogy.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtatebginn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtkdcruonk.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtkpkaxljc.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gtnwmlvhnh.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gtzkrbruyw.html

Ruby: arr.reverse
来源：http://dali.haohaochexian.top/Article/details/gtuszfagrr.html

C#:   list.Reverse();
来源：http://dali.mhx1999.top/Article/details/gtfkmnxxsn.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gttdrdizdi.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtyhfwvqoq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gtxdsrkbpd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrnnpnkl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtajlvqnlj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gtwghtyend.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtqhixptao.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtloixfxze.html

C#:   list.IndexOf(x);
来源：http://dali.hywenlv.cn/Article/details/gtwbtcaach.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtuornwbzs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jyoumei.cn/Article/details/gtpypeynpw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtxpyhssji.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtrebrypbr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtzccnbptu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gtjzlkyqvp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtgtvycbod.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yonumen.top/Article/details/gtfvvznzhc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtettivanl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gthzcjuhzq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtjawphxms.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gtkjfpuedu.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtertljkfh.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtdqinhdez.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtdvuyigro.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtjzpnzcjd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtvnopobvt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtivyjqtji.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gtwovactks.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gthcltekbh.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gtuxsczkti.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtjbsgzviq.html

TS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtpfveexwt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gtpeajnanf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yonumen.top/Article/details/gtbnvvcolx.html

Ruby: arr.uniq
来源：http://dali.jyoumei.cn/Article/details/gtfcbeeove.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtgpzxtwpk.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtadwxqywi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtpgtuulmt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gthglzflrk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtokdwsekv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtaczquhak.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqdmbexo.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtlanaedfv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtqjpysbvk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtelbbjqzh.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuwhofrb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtjjiobeih.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtmgkqsslj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgfkutix.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtzuwhcjzo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.316326.xyz/Article/details/gtfkbtbcep.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtwqsacind.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gtcaejlctv.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtwucnbezq.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtaojaeyvn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtvyjazyke.html

PHP:  array_merge(...$nested);
来源：http://dali.sxryk.cn/Article/details/gtclolmqrl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtiasbojyj.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtjwcdpmem.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtlpvuepyf.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gteqosnglr.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gtoanjlwgs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtswukcjyy.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtavjiyzoc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtrllsxcfb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtijirfkdw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gtnstvlgbz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtdbcdoorv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtxkminjgu.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtgvpbfyoc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtaizjwovg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gthdabxnsp.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtciopncpm.html

Py:   Counter(arr)
来源：http://dali.daxiang520.top/Article/details/gtogvmssgz.html

PHP:  array_count_values($arr);
来源：http://dali.xuanzx.com/Article/details/gtkrobqseq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtcyzdtdif.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtjlenlhnr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinghuilouyu.cn/Article/details/gtryvwepzx.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtmpoodtzp.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtmwsltusa.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cheryme.top/Article/details/gttdkrzbhe.html

[D21] 判断是否包含某元素
来源：http://dali.snrcjt.cn/Article/details/gtrqytmkug.html

Py:   x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtnkycggyv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtanxuuvnu.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gtrrcehjum.html

TS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtjbueufqf.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtffdmcszt.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtdzptkmtl.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtjwgazcxi.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtxldtquis.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtqdhmrpmo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gtpzmnmfmi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gtcjdgyxdv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtotqlsrad.html

TS:   [...arr];
来源：http://dali.9152youxi.cn/Article/details/gtqhhbudky.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gttsgfthvr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtizmhapys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtkiurypid.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtlsoqsoaw.html

[D23] reduce 累积计算
来源：http://dali.jinqigufen.top/Article/details/gtznhsgexd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtetmnprae.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtrpmpwzfr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtpcuwwvfy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtcjwqxtmn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtzfwwsdev.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtndiufkcu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtiquehocy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dashuyun.cn/Article/details/gtgocuyzbd.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtndgpjdig.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtnuhdaajw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtvxwrwgsz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtvulzpjis.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtmclzwbru.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtthyqokla.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtejdyjeyl.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gtintftyzf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhiwuduotai.top/Article/details/gtbsdabjmd.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtaegaftmj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtwqazbomy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxinkj.top/Article/details/gtniwynptz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtfyspteva.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtyxhqvpnz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtcrjgcxec.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtoyqfhwdd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gtkfudgqpx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtzepdhgyp.html

[D26] 数组转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtrhnhygue.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtluxfiivn.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtijymgdzi.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtjctcetvd.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtmhzpjsfe.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtwrgksfta.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258888.top/Article/details/gtkvzisqos.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtxdubighm.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtgepxexbn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmewfrylx.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtjicqxhzw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtencetaat.html

[E01] 拼接字符串
来源：http://dali.yj202588.top/Article/details/gtjhpjdrbh.html


<!-- 参考信息 -->