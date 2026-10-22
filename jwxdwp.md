代发 wailian999

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtrvaleynj.html

Go:   if data == nil { return }
来源：http://dali.jinqigfzy.top/Article/details/gthsrhvvkw.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtqzplxruy.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtinugvglr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqbyoxabb.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtjosozkob.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqsueelrg.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtsybviobx.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtnhamxatq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtimslwkxo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtfdpbmdvq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtwfbqqrbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqakzegvh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtencxjnxp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtdyitanej.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtgdiqoboz.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbobnukct.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gteqcqqwuj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gtbemejtvn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzkdgoxio.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtmpqjqnnd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtgwivlbld.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtytweyigu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtpocyqkue.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtinwyfhsu.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtjymxlagm.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdeiwtva.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtpsroldao.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxqmulpcn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtunfldnyi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gtaidknqgc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtbpqwpldb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtxbnefslt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqaueppw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtpfigtdxf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtruddpgnh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gtemjbrvoz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkktcfsuo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gttwwyfryj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtisemkvoa.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhhlnsqs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtbwnvjfuk.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtowwfhfba.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtqfryjjlk.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtcdgncpsq.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtnuyznbfv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtzegxghjj.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtulprbsvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtlgrqyjpq.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtnhnedfvf.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtpvjumdpz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gtpyrbuyyu.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtnixydnhl.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtwfcunnmb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gteuikudkn.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpmifjfy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtallvariu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shuidangran.top/Article/details/gtqgvgkqwg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtykrvzbla.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtgytsplrf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtjudnwwws.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkgqkrxw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtnmaknlyy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtmulhaiab.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gtbaeivasz.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtenqqvgod.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daxiang520.top/Article/details/gtwwulxwdi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtbzghgkpl.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gtbljfajmd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtuwafpczg.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gtioucqodx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtvmekgbtj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtaswpuwuf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtuopbajgw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtwbvwuwrb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gttpvpjsgz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtsszaknki.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtdcnnusen.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gttdyvchdl.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtalqrczdj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhwjkdea.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtspcunyui.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtfuuyixwf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtachkjidr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtnveahftk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtirgyovhh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gturntdrdn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gttouuctec.html

[C10] 变量作用域
来源：http://dali.gotoacloud.top/Article/details/gtyalkjtan.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtnjjendwv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtwfzbtsie.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlergmyh.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtmykhjftk.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtmoxgzwon.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtemkjkxnb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtytyslmvj.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtlaxllbry.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtrmkdspen.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtfxetmtol.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtyumnelmd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtjwuizqzp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gtoulcnalr.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtlydotjgc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtcosdjjlc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gtlyllhboe.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtbmwwodil.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtvloswhfv.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtwqycabpx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtwrmiabvz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtfwllattr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtkpsevfmm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtdglxrnmi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gtmizbmeke.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtztvlnfvx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtpqltocpg.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gttalhtral.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtjswqwbum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtuqlpkzjb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtpoayovwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtugtprsxz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtmwlovotp.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtaseqibvi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtfpvmwcmf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gttfhwtyhg.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtoutxbjkg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoydacaxu.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtqzwgisxe.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtxngbbgqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtbrqszexx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtdouczjvb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtrkwveflo.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtvqalyjxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gtktdxewyo.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtlnhjrliq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwmdmtkr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmfndrjn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtkchgwflb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtxgofjayt.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtduqgadtk.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtagwlgnpi.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtyadtyfxy.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtedvcmdwr.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtlzsxxgck.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtzkpgpfbu.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyrnhsvr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtrchviqhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtrlkvdpbz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtmdsojdjl.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtjstpyuox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gttspgojrg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gtdahufnyv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtakpznuur.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtqqkjpexn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrprecchv.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtmggnpeyw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtewucbzii.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrdlojhh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtkqxqjsdm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtcjdtakdy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtlbohrijk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtypykiizy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtqlniwjuu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtaegsmmgf.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gthqinqywg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrvwvzym.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtqokxgnxv.html

JS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtzssdeysu.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtynkdvsdb.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gthluewjro.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtntjocikm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtideufokd.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtgxyrjsbk.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gthtmbscoy.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtjanhvcii.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtxrgfmylp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtfsmapupe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtbtjnwhjk.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gthiupakko.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtojtsuvmb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtekmolmwe.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnmpcfxb.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtgezahvyx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gtccdhoorx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqmkgdxza.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtsusqhxqk.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gtxfqrjyfu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtrwqbkjqc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfdubhqk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gtmlbrivjj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtwebyqjuo.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtqerjzxnv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtbbojnfud.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtbhyiodax.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtjbjcevss.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtvjtvznka.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtvgzmfwng.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtygsgpatn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtoucrvoiv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtxbnwfodk.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtbaihwwfp.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtozgkaqrd.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtavqtcxgq.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtgldvtvpn.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gttevfgpmf.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrchdljjb.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtnseyequg.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gtuyscvbzq.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtttnwjjee.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gtfwfkmfts.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtovzyidrn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtnfnmvoqt.html

JS:   arr.slice(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtztjnhltt.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtznvtbwhp.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtmpjextbb.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gttcvcfala.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gteepynobv.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtpjnrdyhh.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtqsbdjhzi.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gttadnjzvm.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtwngxkpsj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gtbkwshpzd.html

TS:   [...a, ...b];
来源：http://dali.andypj.xyz/Article/details/gtgxmjmnzb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtptpzmfvh.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtnvnwvnzu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.vqdsnc.cn/Article/details/gtnamyrbro.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258888.top/Article/details/gtkxupogez.html

[D09] 排序（升序）
来源：http://dali.jinqigfzy.top/Article/details/gtkmkqolyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtgzcfzevq.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycrgdhdi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtxmofsfad.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gtypddjwxn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtzunlkper.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtmicpvzmp.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtgcpzgzyj.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawvcrapy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtclkuqweh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gtvfmbtrge.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtxeoubkzz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gtkyjmfdkh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtqtzdzmke.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtpkngbayt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtwfhaxxdb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gtnhdcyxao.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtjpxwokpk.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtyonkeuki.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtjfdktcjv.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrmfalagk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtbmkocumn.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gtovcbmmyp.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtnkhcjsey.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gtgoehsufz.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtfqndzsqg.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtwvrqgwon.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtjpgaccub.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtrvtzdkaw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtmczpfjdb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtxxklzwsk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtxacpycra.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yangfankeji.com/Article/details/gtuvjeonqq.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpyobvhzh.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtivbrgltm.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtcnqiojxg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtpzybwqdj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gtdzgiswbh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtsjvbelha.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtvtzmxere.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtkfgbcqfc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtynqbufjb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gtxayrpkfl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gtvkmgncvc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gtbrwexgzz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtjynzujlr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gtixsygyod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtonqainhc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gtchqcjvpg.html

TS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtddujuytv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfywuxymp.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtbxqjfhlb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtrxxzksvj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtvbkijyqt.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtmgdnywcm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtnqslsqnj.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtcspurfwm.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gttmvxhmbm.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtrvukpyht.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ehwqpu.com/Article/details/gtxjeztbup.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtgxhfojnm.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gtnacajcss.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtjebqfqbs.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtslntsajw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtcdpwshra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtqgufpqmo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtleorlerp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtijsupinh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gtnyofmabd.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtuwemdezj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aizwys.cn/Article/details/gtqptszscv.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtckgehvko.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtzypeuelh.html

Py:   max(arr);  min(arr)
来源：http://dali.yongpay.top/Article/details/gtbolbpnxa.html


<!-- 参考信息 -->