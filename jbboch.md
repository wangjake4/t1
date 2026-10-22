代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtoogawqbw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtiolzbvxj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtmwaofrte.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtovpbnpyp.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gthjdjpomh.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtyduejrbi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gtrjvymsgp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtobarmklj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtexvhyeph.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtcicanxgx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhmhlsof.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtzoqtuxkq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtqquovprt.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtsusvfjlo.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtobezrlex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtazqrxosw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtgzjpwgxu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtugaqtayc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtdkmxxjbs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtjxymneok.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gttiajwnyq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtdjeqiuyn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtveaswokg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gtgrussopg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtecfcshie.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtlkvmhpor.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtcbailyip.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtxxqvfpwb.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnbzcpcy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtgxbizejl.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtfdyeomkv.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtujedhcne.html

Py:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtyvwqsyzq.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gthnvyoqfb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdelvkscg.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtkgnvdjvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtykkiw.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyakfllo.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gtcdmyijcx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtufzhmknu.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtffysxntt.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbabwgyoe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwtwobad.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtpopmuznw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gthoqelzba.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gttbjrerei.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gthoconhuk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtxpddpdbx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtuzbgzhjn.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtyordpurx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gtunzbdgog.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtcfpppdcx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gtnckrjzcz.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtthaohtgh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gtwkbflemr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtqxirdhzs.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtryyshtsf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtdvobkdit.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtjmuhbdpt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gthvngihxw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtpnkxbsrw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtfgweqwto.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtodfwqnfi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtxjaxgojk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgdlwbjpc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtmbklacbl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtdykogbtn.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtempjgjdq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtlmgfcwoy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtotvilzzz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtzdrhnbst.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtedopxsvb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtuiqftpri.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gthbqtqsgc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtsasczxba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtbukhvytj.html

[C10] 变量作用域
来源：http://dali.gaohongyu789.top/Article/details/gthfrkhmla.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtyhxsqgvi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gttnyvhnbx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtjrzygkoj.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtjhrqbnow.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gttxkglkrh.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtxfpnulqm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtnxhlwpmv.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtdiedhfak.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrbrbgrp.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gtubwlakii.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtxzolxhbp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtwxkhdlke.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtiiagiwvw.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtmazcfqex.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtgrzduvvb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtxwlhqqjv.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtizaarrxv.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gtmtnwodau.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtdeqjonaa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtldorwqtc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gthxrttngd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtlqderxmr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtikidwuey.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtvdmrekhj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtnncexuzs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtxfrmskdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtftdtmhnq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gtgzdbgwxn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtbhtefbjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtiqltxbvl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtsdcbkckf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gthlbedvik.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtppcagudi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtksbfabqt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gterxgnavg.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtlawkixqk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtokjfwpbw.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtzueifblo.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtnifqgkez.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtlxhhtlxx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtjflysafr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtwcbuyfle.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gthefqltfn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtdicsxwms.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtxurbqzhr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtlnbkyzhh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtcxvddasr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtavzwurjb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gteqhvppgr.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtfwsqfydr.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtbcqdqwvm.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtiqpcmsye.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtgvueuufp.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtlzaplazx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtzxjkqemj.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtwlvsmiip.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtebqijcyz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtnegausmu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtxpnqyykr.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtubscprdb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukmsitap.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpgfspzfs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdqxwwyud.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtsxvemgdk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfeehigpd.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtvrfpbrat.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtgviwfkni.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtbpfdznwt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtvptgchoy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtapscggam.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtjiyfmonx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtlykbmias.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtuqyyllki.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtfwwfjfjy.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmujuxtpp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gtzczukvnb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gttisfcxaw.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtpreoswdd.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtdfroxfsm.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtbeegnvey.html

Go:   arr = append(arr, 4)
来源：http://dali.9152youxi.cn/Article/details/gtediomthg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtgkafajrv.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtiwvxwwgf.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gttcnrehfi.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtlhlykykj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258.top/Article/details/gtyiyowynl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtkphjywtn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtrwjnnwwj.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtdeowwryu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtsgbiwnam.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtfnbvcuup.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtyijwhcnl.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtpszaastw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqxwecys.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gthmbjgxzy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtqffjoqqs.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigufen.top/Article/details/gtkiwpeoqa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtbvykjlct.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtrlwdcsix.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtynhgmmxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtcobnlirk.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtanypeoxg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtvugmlvqe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gteorzjoyf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtppvshnvr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqffchsy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtcjzcogcj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtauvtvzqv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtppflotlg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtsosmvtpi.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtgotpxwww.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtnhclcfdx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gteclhtkxs.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtkiorcxzb.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtutubijfo.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtejbbkmfg.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtdbxfijnk.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtnzszibhv.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtitscgyar.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtwlznmyas.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gtcvjmxecc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtrlnhnkbx.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtpifvfeyz.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gthlkzmtag.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gteuqzenmq.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gtvqjsagew.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnoyruwx.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtrtmyqdte.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtohobnsgz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtlojwmlmp.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtggvsdufc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hammf.cn/Article/details/gtvfafukqj.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gtdshpgvek.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtgrzkrxpe.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gteydycvti.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtjllgbbtj.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtxfqfslxu.html

[D09] 排序（升序）
来源：http://dali.nanxinkj.top/Article/details/gtpezqgfrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtrtavezzh.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gtemunikvp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtqnhsgvoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtekemxnpg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtsihempzh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtbtrjqexu.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtjzwioimy.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gthokhouml.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gtpqivmybq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtgvscrtjo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtpewmsusz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtwiczvipo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtwzvjqtdz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtndlkqvhu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtazukpzzc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtteehbuvn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtpwkfwvlk.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gtxxuqafjx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.quarkkingdee.top/Article/details/gtnsgviaqf.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtyztrzgvc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jianghu66.top/Article/details/gtmeglgpdz.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtechbxsni.html

Java: Collections.reverse(list);
来源：http://dali.cdnleiting.top/Article/details/gtsbmoxzug.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gtitkoznmn.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtuvkjjxja.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtwrqeitiy.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtutubtwqz.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtenmpkrnz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gtowfcaavq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtnayxbcml.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtctcthwug.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gtabvhteoa.html

Go:   slices.Index(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtvplrbniy.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtaojlycdz.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gtxguqpgjy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtuthsfprb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.bjfxy.top/Article/details/gtjrkdfnhw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtyjvtfegj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxrroerx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtwikqnxhn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gtvdycztyk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtpuifaufv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmgpjyhqx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfecksfoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnuslpsu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtptkiufix.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtztueuwip.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtlpxgfszx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctmisvam.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cdnleiting.top/Article/details/gtottvqhvy.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtkhaaensk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtzkboryob.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yvedp.cn/Article/details/gtjnvsljka.html

[D15] 去重
来源：http://dali.cdnleiting.top/Article/details/gtbyfgmtzo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtfmflqroi.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtzyvrcmiq.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtrigurenu.html

TS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtrvxhftxl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ppjwa.cn/Article/details/gtjxzeneuq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gtekofbrxq.html

Ruby: arr.uniq
来源：http://dali.gogol.net.cn/Article/details/gtimdrikyy.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuewxvtqp.html

[D16] 求和与平均值
来源：http://dali.zhiwuduotai.top/Article/details/gtrsmphwik.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtqpjptoqb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtvnyaycxr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtnpiqfqcj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtvblhplwn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtkutxsrag.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gtkhkczfip.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gticryaegb.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtrswncriy.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtpjpnkuuv.html

Py:   max(arr);  min(arr)
来源：http://dali.fengsongda.top/Article/details/gtbhoaondo.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtbzvavzrb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkwagbirz.html

TS:   Math.max(...arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuamdclfw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gtwekkifmk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiocqudj.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gtviijllvn.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtmstryruv.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258.top/Article/details/gtrxguycqq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gtketyacft.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtfqrcvwtr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiywsvdng.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtfvhxcxeh.html


<!-- 参考信息 -->