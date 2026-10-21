代发 wailian999

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtwhvzdlhx.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtsavgrbjq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gttrriyyah.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtsxscxeco.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtwityatzz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtdkmxlyis.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtsfglxted.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtumvocxow.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtvvrxints.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtmiibhxcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtxajmcmqr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gteimmssii.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtyaylliwv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtfbgobrnv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtfuupkwzq.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtclvtadnv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtdktekwpb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtswqdpwvs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtzwowiusn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtbwlbftfz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtrpbfnuww.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtjustlgsv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtlsdgfvny.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtntqviton.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gteqhrehhe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gthwsrqgjc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtkjigyxpb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtjbdzpmfm.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtboyyixyo.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtxhisqbab.html

Go:   花括号块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtvqdovnif.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtbfwxflhx.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtxzorcuyb.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtlohktciv.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtetguqocc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gteuhltlgq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtbqyghqmx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtenjalnln.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gtyvdbvxym.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gtyeitebyr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtjwqbfzxf.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtysnpimvj.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtudgggjvs.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtsgvgumeu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtenqlifvi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtsjqvpwqn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtdvijytod.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtciurarmf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtffgplgfc.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtigmhighs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtfybolpqg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtklzrgtld.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtispjvmra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtnofvcehd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtiyngtvtg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gthynwrvus.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtzriryqpv.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtbagcghwv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtetfkmndb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gtqphuctxv.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gtqsaxddqd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtmycglmxk.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gthswtjyip.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gtpqumckha.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtpscckdjf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtoxznhyfq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gthmjcecdc.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gteugbdnbv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtczxjwimp.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtvyvcvneg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtwvxlmuxi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtyqfushwn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmpkesta.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtqolwfmzn.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtolvqmyod.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtbyhrdawj.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gtlxifagga.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtxgvfyaol.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtbivhtilq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtujqmbptv.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gttcweoufw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtonwzehnr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gthzmniteo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtfvbdquso.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtvrqaypur.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtumumupol.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtekodzyrz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttdzavltq.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gtmeookisf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtexibqxqq.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gthnkaiczz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtrxltoanl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gthnghjosk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtsmtmsqkn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gthcmjgocm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtxghtnwms.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtiuiffkoj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtiivnjgcy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtolwctbce.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtyvcfvxwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtgaseftwz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtpbfuxfig.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtnaomticl.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiqxowot.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtwjdobjlh.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtoqqhsjak.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtqytmjthf.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gticxlcdeh.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtfuokjuls.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtkftbmjxl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gtkkzyvfnq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenzaomai.com/Article/details/gtcwjtfjzx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtbeyaqskk.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtdiouahbp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtipkxvfli.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtienruwso.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtmnhjfbtt.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtvtgrhdqq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tian-w.cn/Article/details/gtuvkgpkkt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gthrebwdng.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtuekolbys.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtweuowheq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.kuanghao11.cn/Article/details/gtjczwtxwm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtqefzfocb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gtyfvjejzi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtapuhlvzd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtnqzezdyk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtmeqqrvyt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtdrgzkevv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtmtpbrmxa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gtcggjhawf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtoqkwmyac.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtdnybjbjd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtqezpdzwz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtlclwmntn.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtobmdwsmc.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtqwkpadzw.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtgmpcxijy.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtnkrxnocb.html

TS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtejkuzerq.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtbnkprwem.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtxcnzcuwr.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtdbtrqsnz.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtpbfaqypn.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtqxnyxhlp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gthftphnsi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtqdzbpcnp.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtdvtjmpew.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtkfmdyqwe.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtsskrtcvs.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtwkwjkcuy.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtwkalernx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtzvatunhh.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gtclisviwy.html

Py:   a + b;  a.extend(b)
来源：http://dali.xziqi.cn/Article/details/gtbgjcizqo.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtwkcxbydi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gtusafwfdl.html

TS:   [...a, ...b];
来源：http://dali.tanke756.top/Article/details/gtxalvyxzz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtvrhtbcfh.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtpwfeudrr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtqpgwbdfo.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtmqlcjzfd.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gtemspfgii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtebxmkayy.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtitunkblv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtposvyvxr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gtwmlmwfnh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtaipykdku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrsfvsqla.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtfgzruxpy.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtbcppoxbj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynhdsnvr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtyehqvhdv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gttemgjayl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtityuyajj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtxxdxyxro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtettkazgt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fzhhl.top/Article/details/gtqyoqtrbt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pycfn.com/Article/details/gtuerncmnp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtktyvtjrt.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gtusaoarjd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtbxqlqqjo.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtpoubvewo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtwdswgllv.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtybttdvfj.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtjdszycjz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooqhfaof.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtsracrxiu.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtjdqflcbb.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtvyljlldd.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtnfcmtayv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtfvdebnuw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtokwcciem.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtnuuxocuz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtltupgamy.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtvfnkqzdq.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtfasbyyjv.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gtivvzpyhs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtmjopwyrc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtitymkcsz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtfzfjpuor.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtcpkbfgwl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtfbotjzid.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hammf.cn/Article/details/gttzfdnysh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtjjolkuln.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.316326.xyz/Article/details/gtaakdicfs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtneqyktda.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtcqobwyam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gttkyrvpbp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtfhauusfg.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtgbqcnxku.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtsiguteuj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtunfwwntm.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtfduiozib.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtbatomqcj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtvnbjyble.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtkeopicqw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtkktfvjch.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtrzrmrcdn.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtudyvgjdq.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtksvesaet.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtgsqwbgtd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ppjwa.cn/Article/details/gtbovjzjuc.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gthomtjuau.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwmbagbyv.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtozdpzhtw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gteelgagip.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtwznduetg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuwotdsz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gtkhbuxels.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbwmhsbe.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtkdqrpbzt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtipkxqluw.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gtroryhuiq.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtmicdfgnw.html

Py:   max(arr);  min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtmswddrgs.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtcmnhlnww.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtuzfuchcr.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtebifhhde.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tianlin.xyz/Article/details/gtgvysbflu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gtxigmfgxh.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtzjlztajh.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gtgktewbqw.html

[D18] 扁平化嵌套数组
来源：http://dali.yonumen.top/Article/details/gtdmrcvbxg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtosnssqfw.html

PHP:  array_merge(...$nested);
来源：http://dali.ppjwa.cn/Article/details/gtnhpzzfvm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cheryme.top/Article/details/gtksjmzhvy.html

TS:   nested.flat();
来源：http://dali.ppjwa.cn/Article/details/gtjjcyzxia.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gttfpindcr.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtgcwozjyg.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gtoatpszqr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtyoikdzlq.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gtwagtjjgy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sysykeji.top/Article/details/gtajigaaqu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258.top/Article/details/gtxvvtzvyt.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtdoumylqm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gttgkqrlap.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cqqwz.cn/Article/details/gtobjczrnd.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gthjjhlolj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gtshocekeh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gtxruovwhx.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtmclcteql.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtmqbcgdly.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gtnhiwqydg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gthaehkdoy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtbjfddgvd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtdlycaesf.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzcvyscw.html

Ruby: arr.tally
来源：http://dali.pengpengdd.cyou/Article/details/gtjquiwlyx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tian-w.cn/Article/details/gtqaansena.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gttmspestd.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtxcfhfzhb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sufxvd.cn/Article/details/gtgjftnvla.html

JS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtxmwbhgzv.html

TS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtjnxdktld.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gtjwchjyvt.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjrkfmkt.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtqirckzma.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtymttyrpe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtscakhxxi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gtjbqbltzd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.birdmap.top/Article/details/gtrnskgfeb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gotoacloud.top/Article/details/gtxdzldmrk.html

TS:   [...arr];
来源：http://dali.cashguo.top/Article/details/gtlvsmcvzb.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtfmujueji.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtmpirupdl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtawpwsyzo.html

C#:   new List<int>(list);
来源：http://dali.ehwqpu.com/Article/details/gtdognavxv.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtxdezyavl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hfpthk.cn/Article/details/gtdlixccej.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtwzxevyys.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoylbvvil.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtifgokmcq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jiagoushi.top/Article/details/gtcsyioyci.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtxfzrplkd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciftudql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gtojkkmdek.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtbadeebtx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guannengcc.top/Article/details/gtppqfrqhp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtjcktndul.html


<!-- 参考信息 -->