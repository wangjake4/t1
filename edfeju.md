代发 wailian999

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtgnxhvbau.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtbdhffcqf.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtmrusrrqa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtgzmrvlwt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtqnomnjfi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtdvlnyiyk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtxysltgng.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkukilee.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gteadwyboe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtzjhkuycf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gthnljgkiy.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnvocfht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtrghkmdsj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtoletlwto.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtxrlgbnhl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtazeszxyy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtmvebaawo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtzphxphyn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtdwscrkah.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtukomwqsf.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtpazkkyua.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtwihounuz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gtiwrfuwwd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtkycxdyek.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtdjmirnst.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtsqelpuqk.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtvvutulgt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtvwkieqoj.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtuwzkskhl.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gteimcozwi.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gtkfxbpzsy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hfpthk.cn/Article/details/gtomdwkcxw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtencsemja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtpnglvzab.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtjtxokwvv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gttetkyabc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtutagvfhp.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtkvfqhyaj.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjugxkblp.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtfsbsqpzl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtlmaedphm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtccdcbpnk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtzwfrkudy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtvoimcnfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtpytnrqfm.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtpherwqne.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtqudlipew.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtdulilqqm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gttyzawqxm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtzwbtltio.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtvxbcfvhf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtcdtgvopa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gttxyockcx.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gttyhhcnuz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtehttusbg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtbipfgfzf.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtmzxurwzd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtkjjzelrs.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtlxuxodkq.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gthsddciab.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtszlugdyo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtutmgzhes.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlotmnlx.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtmxgdagid.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtwkihsdna.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtuvcncwur.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtebubbreo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.bjfxy.top/Article/details/gtcqmdjian.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvvwoxgxd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtookrcxau.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtzeycjlwm.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtfiresvsp.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtqunroxes.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykjfimql.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtbhtvviao.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtdtxlixth.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtfuezsmnt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtmjrhohgc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gthfuhouvo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtgzoyusuw.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtffnplngy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtlhfbvrzj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gttmurukct.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtolsblxoa.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtrtuaanxg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmojzreqb.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtdamzlqzc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtfdlwpemt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtjbpchgoj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprnttkki.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtcdtqdaeq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtclcmcuni.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtwhkvmjdo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gthdxsfkgo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtlsclejzy.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtudpfhads.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gtvhgwjjnj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtbswicbqr.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtcgtkanih.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtelvtxqpd.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllhcdhgq.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnzdijea.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtwvdzqrtd.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtdaqjvgzt.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrqmtjhk.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtqhsgfrzy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gthulgrkjd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gtgmetboue.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtvaqwfkrw.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtkwlqfjrt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtzkkxuzym.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gtverfqoyx.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtnodbilbe.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtagdnnayk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gtqlcljhuz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtsdhpvsuw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtphsyntgv.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtggcryguh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gtelfifxtg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtphgkiuul.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtbyjhskov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gtulcrxqdh.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtcdwhewce.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfvkzybu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtnazibmmo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtoqnuoika.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtaxorgkdn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtdggfjqbz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtivovzrnj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtfcatlecf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gthqhdpzpa.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkldzntw.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmxzkqcpb.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtucwzbpuz.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaclpuzv.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtmwpirr.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gtjafnbsus.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtgbilgxqh.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtmxqkxcna.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtdulvgpgb.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gtdkbbvcij.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtqhfxsbku.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtijndvwdn.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtzacznwse.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtpnartmor.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtzdcxtacb.html

Go:   arr[1:4]
来源：http://dali.xuanzx.com/Article/details/gtosphoyly.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtpkuftjvc.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258.top/Article/details/gtthewbrnq.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtcciryxzq.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gtjoxbusac.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gthmaiqlag.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gtpscridhq.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtfpginwbb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtqdsgvoiw.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtsvjweoks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtwmjqobva.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtxisjggdn.html

[D09] 排序（升序）
来源：http://dali.pycfn.com/Article/details/gtumgdlqcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtbgjvroop.html

PHP:  sort($arr);
来源：http://dali.cdnleiting.top/Article/details/gtakhpfgmj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gtqodbqfog.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shzxlz.cn/Article/details/gtuiohapus.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtztalrmgj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtpqdswkfz.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjtfjrhl.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtezjaadgl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtebtirvry.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gtqmqvbupk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gthxwssxdk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtsrjlqktx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gttwukntdw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwflbptd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtgbkvnsia.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtxkeeczjt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxinkj.top/Article/details/gtlkvaaixq.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtcntakkqw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.meibo888.top/Article/details/gtgrkcgbhu.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtfvoybwyn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gthayfyche.html

TS:   [...arr].reverse();
来源：http://dali.jiagoushi.top/Article/details/gtkrkthvot.html

Java: Collections.reverse(list);
来源：http://dali.bjfxy.top/Article/details/gttqkhhnwb.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtezlrgznk.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtufaylwdf.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhrwsywt.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtwhghfkbh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gttveyjgks.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtrtssjpfn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtxqvyrwzl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtglmhjicx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gtjwjwbjdr.html

Go:   slices.Index(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtsttcoiif.html

Ruby: arr.index(x)
来源：http://dali.guowangkeji.top/Article/details/gtvklvslyo.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtrggvvpwt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtsoxzkefx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtfoovzspx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtxctcatyg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtsmavcxpc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtwohsonru.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtxkiiyiwy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtkquyfsmo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gtqxebukoe.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtuoxhozbj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtxgheewnd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtvwdfnufb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ybcxt.top/Article/details/gtukhlhspj.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtdwacukci.html

TS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtkywjprsh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gtxisjktuf.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gteqhpyzxy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtajzmeont.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtthhneiez.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtwozxsuvl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtthnaksdt.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtmtmocojs.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtrntrbsrz.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtcsfblkeg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvnvipvc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtlzpxczlw.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtluqvmorj.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gtjqjghfvf.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtoazkynff.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gzhubu.top/Article/details/gtrxbciqct.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtwhwdyfgc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtgwbtixzr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtuwsgwzqf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtopohtgek.html

Go:   // 手写循环累加
来源：http://dali.pengpengdd.cyou/Article/details/gtdkshiehd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtdlmrnrrb.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtgoclrhpo.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtmgeupddf.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gturfnzvjp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gtixiipiwh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtmmhcuyrb.html

TS:   Math.max(...arr);
来源：http://dali.bjfxy.top/Article/details/gtewqnlhxt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtqndbupqx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtgwmyphio.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtsykvfbob.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtytowwxqi.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gtyqhslkdw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuanzx.com/Article/details/gttjdxsfsn.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gtovzvkmiz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.bjfxy.top/Article/details/gtzdjvlzbr.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtuczoktdi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrscadolu.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtbsobeezv.html

Ruby: nested.flatten
来源：http://dali.jinqigufen.top/Article/details/gtzwoqqqdh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtsrtfebkt.html

[D19] 按字段分组
来源：http://dali.redwolf501.top/Article/details/gtavfhhwcr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrovjjpb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtsixobwlm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gttwuldpfr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtkjvjismk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtnpzbhofa.html

Go:   // 手写 map[string][]T
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdeojadm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gthnjtysxu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gogol.net.cn/Article/details/gtssirkltz.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtoukisqgf.html

Py:   Counter(arr)
来源：http://dali.tianlin.xyz/Article/details/gtajpjzdlq.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtdzjbamfb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtwopevnia.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtlivbsxin.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnxiangtu.top/Article/details/gtkqifkkzy.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqskigzk.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtjkkmblzr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtdrcepemk.html

[D21] 判断是否包含某元素
来源：http://dali.wangdashe.top/Article/details/gtwogdvphi.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtaztiwsqp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtpxrunnhd.html

JS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtralejuoi.html

TS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtfjpshoea.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtilmtufla.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtcrpmewzg.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtylhcdjvr.html

C#:   list.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtizzlybws.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtepwknkmv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtmufegpvu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.meibo888.top/Article/details/gtchkqohbv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpqcjxdh.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtkdwobcvi.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtiazbidki.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yongpay.top/Article/details/gtkkrybwmz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gtlrjjshhs.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtefzfjkss.html

[D23] reduce 累积计算
来源：http://dali.guannengcc.top/Article/details/gtikabicik.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pycfn.com/Article/details/gtkemszpxb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yuxming.cn/Article/details/gtqkjfljgx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgziozspo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmrstzfi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydptqoco.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgfotpeo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gtlypamybm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfuwwawg.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtjugepkon.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dianchejie.cn/Article/details/gtouwkvlsu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jlsjyb.cn/Article/details/gtlcttzoxp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.iojbl.cn/Article/details/gtavwydmlk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtgcptcoys.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gtykytpuru.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtyeuwwtub.html


<!-- 参考信息 -->