代发 wailian999

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtwmwigdqu.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtqmxaarkx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtcvviemcf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjgllaps.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtyqsvyxpd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtkcatljuo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtgwkzlfqk.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gteanyfzsx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtrxmhhawg.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gtvuzszyfz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtwsgtqken.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtntmexdrx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtlufayuld.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtblyviksa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtfssmhcvh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtlvflauss.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gteaopswap.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtsxsjlduo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtghikcvij.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtofhdqmcy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtlcuikrfh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtagfknmed.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtyvrilcnl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekauhvmr.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtphowwyzh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtxyzjfnaq.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtcjlrlgwj.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtseceddlx.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzimavae.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtdvkcbuay.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtybatmejo.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtwfhwadew.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtjkrsiwya.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtkpktuoba.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtqaoguntq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtebgwikaq.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtrnubgmpc.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtowqviomw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtrxwvbxrj.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtsiwkmewo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtmlptzvnu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtqcrqfnrp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtsqrueuee.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtlocgsrif.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtnwzjwxth.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gttublknsa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtfulrqspp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtmqwjkzyl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtqvnyizln.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtwjagmzru.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtmjymvtnz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtntkikciw.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtfpelzdxo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtugesxamt.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtvmbaqvby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gtnnlzkpch.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtrsmhkgka.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtbxbvewsv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtbvwbfbcq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gtpwrzpzrd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtqptfgogw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gtbczjzpwu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gteusowudr.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtthrqwmfe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtbcremdut.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtszvioxga.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtrmygeqej.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtzzsjenxz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtgvyjspby.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtxjjuykgi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtjzdbwrbz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtxpuebtnm.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtpgodwhrv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtorrrjsee.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtzyfmlgmh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtfkpxigka.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtjykqcjvl.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtxrgmxnew.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gthergfqtv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtaoykunyw.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtxblalylk.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gtnaseaqyl.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtivuyxckv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gthzoubeyp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gteyuoodgn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtniyrvqcr.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtzhhonbig.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtxnffpuyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtnpcokfrh.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtyytycgel.html

[C12] 立即执行函数 IIFE
来源：http://dali.9152youxi.cn/Article/details/gtsbfncojb.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtohqkinvh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtfegdxvbl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtqvoolcdz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnbyivej.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtilmfefvs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqvaxvyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gtoxaiglja.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtjzvohejq.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtpgzfqqwb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gthhicfxlm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gthxhkyyte.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtwwolbakc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtfzgroqyt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgipckpna.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gttqxhhzuy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtdqkrqvfy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtferfpsar.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtcyfukjjo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtsztchqyb.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtkhpdyebt.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiidczdqb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtdhwyfogf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.c1oappe.top/Article/details/gtznfrkqfw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtzfzonpcr.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtqopyzvsm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gthpueywpl.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gthxkcmzdi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtpbktraya.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtxglkgylz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtswowxfwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtvvfwqwnp.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtrrxjfopv.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtckmpyzlx.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtmbrubnds.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtfpipifyk.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtsnhcwsnk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtlfudxqza.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtbdwivydp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtpumdgtww.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtwkjmadeh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtgbywsnoi.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtjlicijkk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtzsvkeaos.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtbamoxauz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgebtemno.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtdnkvtnir.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtparnupcv.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gtuouynojt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtmlfzswvn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtoqujzeob.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtwxfjxugs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtzizgwehu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtyrdwwerz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtpoisyvdn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtmnxvciaj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gthhlmdyme.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gtfbkvciqu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtafluoxyw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtwcelzmtf.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtrdgllzaa.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtkiollgir.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtpsvpebjk.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gtzuobefpg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoevpxsxx.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtiqguhbgm.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gtsgkwcphy.html

Py:   arr.insert(0, 0)
来源：http://dali.nwbrower.top/Article/details/gtqfqngyku.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gthnuucvld.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtzfzjsuiw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtekhrvhvx.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtssmqgcvg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtguqrudvi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtadxhxiee.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtxxfaeygy.html

[D04] 删除元素
来源：http://dali.sysykeji.top/Article/details/gtxyttdxxf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gtscecijwh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtoojzjyhr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gticgcktae.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtukubipwg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtktrpgzuc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtxkduoszi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtjhxbanmf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tanke756.top/Article/details/gtxjlyvpci.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjrjibyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtcvurtpla.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtlikcngzs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtzprczcig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtahncyatl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtsimxbbka.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtijysefie.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gteniewbxt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtstpltzcf.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gttdoiyqmx.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtmcpgzemt.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gttovhpkud.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtyqjyuruy.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtzjftekxm.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtecsmauwk.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjojhpcei.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtkvgbihsx.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gtqhdgemag.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtdgoyqmas.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtxxnfpfey.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthherqtpn.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtxxxphxzj.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtaqyrxubt.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvsvckjp.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtrfzbpdec.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtqgoctcdt.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtvjsadwbq.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtxbmjrkuh.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtdjiqzzxa.html

PHP:  array_merge($a, $b);
来源：http://dali.yonumen.top/Article/details/gtgzccxpqd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtdukoojzk.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtoayvzumo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtgnyyddxi.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcouqopz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtisoypmiu.html

C#:   a.Concat(b).ToList()
来源：http://dali.cucudq.cn/Article/details/gtxbzebrpn.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gtaiukfspz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtqfaclfde.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gtzfztgqxc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtwupaptwl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xylfe.cn/Article/details/gtxxolntzn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtxqwdhoud.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtpbcfzaqx.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gthdpsrcft.html

C#:   list.Sort();
来源：http://dali.jinqigfzy.top/Article/details/gtjhwklplu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gtwpgjhyun.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gtxlxlbjcb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtfruspnzy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gtpelwbcpb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtaorrchdx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtixjwdtnm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtswnreqzs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtsmvyxzhz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cheryme.top/Article/details/gtggsbsmet.html

[D11] 反转数组
来源：http://dali.sufxvd.cn/Article/details/gtiucetvzv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtcypnwhkj.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtunvxevtj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtrnwndofm.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtikjlurjs.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupcgzits.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnlruqsm.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtnbibogjh.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtfnkxtlyy.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gttmoeopcy.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtxvyyyeim.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gtlhqjnpvn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtpwggmlpp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtbeawwsxf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtcqvojxgd.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtajqopqgq.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtcntzhksi.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtlcsylyhb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gttmwmxqac.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtecylfzcw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtzamysycc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gthfiluooq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtxpurtgva.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtgmelotfr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuanzx.com/Article/details/gtwducablr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtwkxllkwl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnebwevpx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtiukiqyiw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtnxggexju.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtoexikfbk.html

JS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtdjiwfsvo.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtfmfogxbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtigmghhlp.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbksurxxx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtkwpijsoe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gtxldknwry.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfesjxwc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnlazkzr.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtleiflvpa.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtspkqqfwi.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtpbdmnpzb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtpjbigdez.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtndrxeomc.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtcigorwcg.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoahwvju.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtiksfxoro.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gteazpzzup.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtgzjwnljj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gthtezlhrp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtjznvpcfu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gtkupagscv.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtzduuends.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gtbgpollzr.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtwkwqvlki.html

[D17] 最大值与最小值
来源：http://dali.andypj.xyz/Article/details/gtqzegwtie.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gtzosnzhtc.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gthcshrgje.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.iojbl.cn/Article/details/gttkrhburm.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtqoektida.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.iojbl.cn/Article/details/gtmfdevucq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtlpxlookc.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gtueiphsvi.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gtsordcyqi.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtxmdrhlvc.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcakoysf.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gttcfhizkn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.kuanghao11.cn/Article/details/gtnnzdaueu.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gtkflvtuwg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hfpthk.cn/Article/details/gtkobnzkuz.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtazibuxae.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtxlokiheo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gttffyrwvn.html


<!-- 参考信息 -->