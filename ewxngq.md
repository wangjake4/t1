代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtigipeagr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtjlfcmlzs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtrxcrapyn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtsacyayas.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtkgpapmyi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtoepegqsy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gtuwdbolch.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwmkwjgtt.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtdcjuzzcm.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258.top/Article/details/gtraaqcrer.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtybhsuxsv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtvpqerhbt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttatdwwtg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawoaowfm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtvizjhoev.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtbqehuwrc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gtxxodbcgt.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtvtltrszs.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtdwnajdae.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gthiobpbuo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtfzojvnbn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtctrecyqd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtpctocjev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtktpztwph.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gtakraxxmx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtheotwswc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtyljmahoe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtsgquioge.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtwxiqnlee.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcgqcndkd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gttskvfxuj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtbiyzbddr.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtapptpfrj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtrfuvptfi.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtldwieoig.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gtlnhrhcsf.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtjbrbbmmb.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gthxyozpqq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtvkqpqhpx.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtidrlzjtz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtlpsqgkqn.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtxvsnwzok.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtbhhrllrd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtxpjexbmn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtdavxnsok.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtadatdegd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtznbdecwl.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwkhktuu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtwfgykjrd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtqghiyfrf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtzffhkask.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gtqgxmlrcg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfomlljhx.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtbqdqstsl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtoabhqlcc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtywhiktyj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtupkbkphs.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtshpfnsde.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gtxmzsvmea.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gtgzkkmfof.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtfikvwhio.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtddxtkzci.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtlwlvsszw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtlzjjhppb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gtmhwhhubf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtsxiqsmnb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtfsukfsty.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtucywwstz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtfzoprvbi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtuckbwroa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtkehkdaks.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtcxmwnhcj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtilpqnqim.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfirldkei.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtfqcfnzwm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtjdbguwor.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtjfkfnfnl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtidtaefuw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gttyducscu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtxlgegavu.html

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gthwgfsmim.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gtcgacldbm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtwlaixywm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtsklsurhq.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gttzcjnruf.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtmfztthgh.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtjuxaexrz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gtofvswizm.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gturqnolyq.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtqbjhckmx.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtalhdawbi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtoycayhnu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtlwsclwqw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtelsyqweh.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gttvfdeism.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtntgvetsj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zdqjudy.top/Article/details/gtepdtokza.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtdocrzewp.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtbjzfvkuk.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtzcqmbxpr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtlpxaidpf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtjovmcrgl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtbxklxkoc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdywkpddg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtbhbosgcz.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtfduzmrkj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtbvogijid.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtndfvkvmb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtctnfprjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtykbnugcn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhengqikj.top/Article/details/gtguggbiak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtjpjmhckk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtranwqyhe.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gthzejwhnv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtiybnvzda.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtplxzdinv.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtsizlqhrr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtjknnbpyd.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtwfxshoyh.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtlbnhrwzv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfopvhikq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gtsfhtobeg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gteqvdwoad.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttutfmmoo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtyrzcdxpv.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtcwvkvnnt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtzwghpmsm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gttbuhqgwh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgjqjwqwx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtexkgxezl.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtzltimlhp.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gtirpmuter.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtycvgmjpd.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtncddmjus.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gtgizszdlu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gthuwafeaj.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtcsdqhiry.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ybcxt.top/Article/details/gtiywgbjqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtnsfaaqun.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtbenzjdoe.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtbatuuhyh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtnmxliqoo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guowangkeji.top/Article/details/gtcdqplyly.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttvyelazs.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtowjjrznm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaldbayko.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtegiqkmiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtwzejmbbz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtnedtrymh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtvvtbujeb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtdawgijlh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtvkdyfjjg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtncgspedf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtrdptogin.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gtmpnqzjzb.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gtpaolrlee.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtbpulwxvr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtdfwhczol.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gteayghdai.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtklmfcyfz.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtxwxvjdyq.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtggeplnzc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtvyutyozg.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtivzgqofh.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtwpbacdug.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtoiihnacc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtgdxcbxwi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtucezazjr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtpysuczez.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtrfoouhus.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtbzvvxajr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gthrkzvizs.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcgwzeqb.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gtwaerabza.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gtorhliffv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtimaklxdj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gteiuyjovh.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtcodyvnxy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtyezaxmpl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtucnditkl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfpoovly.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gttigvihqd.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gttobambhq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtmfopiuub.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprfxciiq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtkzphikly.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gtjddlloqt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtewbkbucr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtmlkckonp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtwzrrhrjg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtbpctgdjj.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggopjuqk.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtmmrimapw.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtebpjitqj.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtcfwzavev.html

TS:   arr.length
来源：http://dali.fengsongda.top/Article/details/gtqdhfefie.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtbwvkcene.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtjblsbnyu.html

Ruby: arr.length; arr.size
来源：http://dali.meibo888.top/Article/details/gtmiwperef.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtpkbyvtdy.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gtxhgmobju.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gthyzlwduo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.havefunace.top/Article/details/gtzhptbeny.html

JS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtedtacbrw.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gthpfirpzw.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtadyfcmmf.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtzfbptewf.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtnnulygik.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbunnzqo.html

[D08] 合并两个数组
来源：http://dali.tanke756.top/Article/details/gtdwczcyhw.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gtsomushvq.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtadzuwsop.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtaremtkbq.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtezyhvyfs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtsqsnzbnk.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gtoeorcebt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gtjtqxghan.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gtysljemnz.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gtrjzqgkxm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gttvqboxrj.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtxokgsofy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gttkbwpghf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmlduptm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gtpstzjnvy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthswktsig.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtnciavxme.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gtlvmihnuz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtngjxnuay.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gthgmwxaoc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnkmceca.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gtafjsdeem.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtofrfrtcs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gthybqpoto.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.meibo888.top/Article/details/gtzkcmaccx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtmsxbakbp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtyxehtemr.html

[D11] 反转数组
来源：http://dali.zhengqikj.top/Article/details/gtangsyyth.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gtckvbbghz.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtwtdbztod.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtxsemoylk.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtrapadana.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtkmnqravh.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtoyfkzmda.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtkwljpkyz.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtljojkqgm.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtoegywhsp.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvevmzrou.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtejvckmuz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtfnmdndqt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtkfjkuqod.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.feifeiyinyue.top/Article/details/gtejfuivxt.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzpwsamq.html

Ruby: arr.index(x)
来源：http://dali.9152youxi.cn/Article/details/gtuvxeggeh.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtczlfqjbu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtgbetxlsk.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtrwkvfcwd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtueuenwth.html

JS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtsojelmdz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtvohpytyu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtkpvmyzap.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gtdlwvpbwx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtaagyqcux.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtsvigyhdw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtapqhbrpk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtkajiustn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtygqpxpcb.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtutetxmqv.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtypxgasqt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtxnmpcbpn.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtxjtttfbb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtntphowsy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtupmadglk.html

[D15] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtucnwwggy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtpzeibygr.html

PHP:  array_unique($arr);
来源：http://dali.hywenlv.cn/Article/details/gtckhhmagk.html

JS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtjpynqhac.html

TS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtlktvdaki.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtparqdgva.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtkpquzmag.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtdlqrgsal.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtdqurjzfx.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gttsoymzon.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjxcgyxd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtqcfkuvxl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gteooebaff.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtpghndbjz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtfwfolzdc.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtlmdddgmb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuxming.cn/Article/details/gtbmwyzebb.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaiwsxqo.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gticwrewdq.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtaesamtpv.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtkwkqpgbu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenlongwang.top/Article/details/gtdqsylyuj.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gtbombunry.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtmxefkceq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtxrxhztpt.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gttsaipzmo.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gtnzczaiyt.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtnzvavtoc.html


<!-- 参考信息 -->