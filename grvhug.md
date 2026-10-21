代发 wailian999

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtqskdycxt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtvgzoclsc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgkgkvg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gthzbyjiix.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gtqqfienzf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqvpezra.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtrgaomtjc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtfcchaioi.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtdunsyfoh.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtpmcatmel.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtlkqjjqvt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtlymwibch.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtlxcoomij.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtvrkztupw.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtpthobeyv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtdsbwvcbc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtzdzjxuai.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtahpoxqbs.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtvcotnrqj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtkrmjueyl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtxayvbyla.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtbkacjhnd.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtzdrvzdae.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gthwbqlluw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtrwwzvulv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtkhtmaskb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtowcnlrig.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtwiiqkifg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtovkondph.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gtfddwlumg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gthjiywrzn.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtjalacvbx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtnkopclfh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtuibolyid.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtzordckoe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtdjvorhtz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtexljgjta.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtwdrhqmyv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtqzuusblx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtjkwzszgt.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepwsxnst.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gthdfmbost.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtensnoire.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtdqklascy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtwywocftw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtgoxbplpv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtmnlgbhfc.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtegnicpzk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtxppkhiqs.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtxkkiaqoy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtpeewuamu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtidfvwfnn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtqwhpoubb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtmdwnpxug.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtyakyksbk.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtoeweqlya.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtaicvqtlm.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gttljrtzbh.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtgmjszamr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gtdqubwjtz.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtqdqqyajt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtpezglpmq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtusvwnqcl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbzimsexb.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtmkayjvkt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtbaarhvpu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtkqdhkgdg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthpwxygru.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtrbdihyvi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqxhqicow.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtdmbapsei.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gtbmvynmfb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtwowudxxy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtglcrkhqw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtwzrafpsk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtduacmmir.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtmwkwmune.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtxewihich.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtqgeyckwi.html

[D02] 追加元素到末尾
来源：http://dali.mhx1999.top/Article/details/gtfyxtarqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gtlnvmtmdk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtqdiqcayo.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gtfdhxcogw.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtltqxovuh.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtaoyqopjf.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gtcrpwskeg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtqouooorw.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gtnaylzujz.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gthciyhcts.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojmemewa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gtrvbmyuok.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gttdmeuxnl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cucudq.cn/Article/details/gtythvrink.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gthyulcgfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gthaggrpws.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtlxewnbmo.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtfljoag.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtrawicxng.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtgeqogzpt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtmbgruait.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtodwcqavs.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtkngtbrmv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtnmktzluo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtojjudnah.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtesypwiwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtmrcmgsct.html

[D05] 访问与修改元素
来源：http://dali.yongpay.top/Article/details/gttivyycme.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtpzvabhgk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtteqcvkdu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtpbunkmql.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjwrucqn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtgscwxskt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtlkkrkcfw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtqvhvrpfq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtsezushoc.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtfjucvcsl.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtgfdjggdn.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgvnbvckp.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtzmywvhxp.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gthlaqydej.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gtxhvdlvoi.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtzezkowtv.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigufen.top/Article/details/gtbaxhnaza.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gthgthplwo.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqddnddhx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gtkynphkdj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtrnrajypm.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtfqzpqxvf.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtyxdmapln.html

Java: list.subList(1, 4);
来源：http://dali.bjfxy.top/Article/details/gttwqgxiwu.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtggcwzxnf.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtairwmtdh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtawrqnqmk.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtjjfxgerl.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtisoodmxj.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtkwasjvfw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtbnjmcinv.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtezcrmiuq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gtxfdkfamt.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtmbxwxytt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtohvpncsc.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtyvfpizzo.html

[D09] 排序（升序）
来源：http://dali.cucudq.cn/Article/details/gtafrdmlux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtegpzkhmf.html

PHP:  sort($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbruiignr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gthnexxboo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xinyue.icu/Article/details/gtofcyches.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsxzsajd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtvaqiilrx.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtxnpvdprc.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gtuvdgpnba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtrcdrzedu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtrwnxcknq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtezlopijy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtnglbozya.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtoijhhekp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gtnkwcgnbw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gtirljwlai.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtaueuxxvc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrooqchpy.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtjbvyuvpl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gtaozkjmzj.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtyyenmcal.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtwxzbqmgg.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gtuidnomew.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtnxiledvz.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gtomscjjip.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtolsuorcf.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjjhqxpv.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtayevdibv.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gttdfpgnji.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtzsmffygk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gtgjtgmaqr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtefrlviaw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtwpblxvxg.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmoiqegvr.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtryijkrjw.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtzlaefegu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.smart0.xyz/Article/details/gtdbdgcmbi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtlfmhyngd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxgcqvnl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtlkyswttf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtfvffwscl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zycfv.cn/Article/details/gtyblpjinl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.havefunace.top/Article/details/gtcewggeoe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtagivnvve.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtvjyjfzgy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtskphzjpo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sweek.top/Article/details/gttylemtra.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtmmxoutsa.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtgnokehky.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtrsliyufl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gtpobitldh.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtvtjnnssd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtdzccmndy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.bjfxy.top/Article/details/gtdyumhuor.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtztsmecxo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtgqmfjkkr.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtvxqkjpem.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtfzzhetgq.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtzggazhgd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daxiang520.top/Article/details/gtjdxaomwz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtmbrxntvo.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtohorcvgk.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtrygtxzzf.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gtarnpksli.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtbutxkjui.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozsdthjw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtjaunoabi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtvddeetgq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gthhaomoyl.html

Go:   // 手写循环累加
来源：http://dali.yanxiufei.cn/Article/details/gtkwpwtixf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtpjlhgkiy.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gthjlbmdtm.html

[D17] 最大值与最小值
来源：http://dali.haohaochexian.top/Article/details/gtrwrgrvzr.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gthcftrfdk.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj202588.top/Article/details/gtblfzdkvy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gthjcwmzce.html

TS:   Math.max(...arr);
来源：http://dali.jlsjyb.cn/Article/details/gtumdhylfr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtzxpkelup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwwhypvm.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtybyqctzc.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtieunlbkh.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtecuglyyc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gteisasgkh.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gtlivfqoow.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenjidiqi.icu/Article/details/gtektoqvvy.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtdbvugkay.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtafdwwctn.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtzdqggwwz.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtossyzfjv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtybyogwnf.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtwyueoeoz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtkntwbhph.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthidkzznc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuxming.cn/Article/details/gtiwinvcgs.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtzaschprk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtwvieztwj.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtzalqkplj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtwonsqcxt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sysykeji.top/Article/details/gtcctorewc.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gtkpsrugcs.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtugmzbywh.html

PHP:  array_count_values($arr);
来源：http://dali.meibo888.top/Article/details/gtengcusnb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtuvxvqlqf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gthimntqkz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtrwswvjjq.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtzzojgule.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtssbksnhe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yanxiufei.cn/Article/details/gtxlycerhr.html

[D21] 判断是否包含某元素
来源：http://dali.hysaishi.cn/Article/details/gtrboqdcsb.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtavpymzzj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gtofqypvst.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtqnurluxg.html

TS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkmzhfxt.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtjhiipjna.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtrwjrcweg.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gttqkddsej.html

C#:   list.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtldmsutna.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gzhubu.top/Article/details/gttliuligk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozassbvj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gtznxwfnvj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gtwvdcrltk.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtfemrhlps.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtpmeelspy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgfzy.top/Article/details/gttecxfzyn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkavmppdp.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtvthaxkve.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtzmlvfnoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cashguo.top/Article/details/gtpfbrpyzi.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gtokizlhfj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtmcrhgkrh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtekkmhcjd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtwumnyjyx.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gtbwrqutrr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtwwkkrylk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gtigplociy.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtahedtjqb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtaitpneng.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gtjlhhqepx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gtbtenreix.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtcateppvp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtjqrukcge.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtrlionjnj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbgxqkdr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gtyzdlcwvq.html

[D25] Set 集合去重与交并差
来源：http://dali.yangfankeji.com/Article/details/gtqrgdknpb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aibaodan.cn/Article/details/gtuwvfchgg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtqxgbbjho.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sweek.top/Article/details/gtdkzxpbza.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypcizvwz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.daria6918.cn/Article/details/gtfjpiohrw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.wangshuangyany.cn/Article/details/gtjrubtkcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtiaidbapm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtudqivgib.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gtczsobyxp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtawvtyamn.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtgdbxhyrq.html

JS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtgstzqpcm.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtsmunqhba.html


<!-- 参考信息 -->