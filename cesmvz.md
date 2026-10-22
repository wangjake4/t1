代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2dckdobmf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2sbtwjzln.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gt2nbiyzgra.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gt2gaikaupr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gt2pgajofjq.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gt2dvqybgop.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoizbvry.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2gjpjvhny.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2oeckmnnv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2cmlnpgwf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2scxtorxr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gt2hcbbtgdn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigufen.top/Article/details/gt2gxckfztv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2okokydqo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2ywezfqth.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gt2qyrqshqd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gt2kebfngws.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2fowpohod.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2hevujoyx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gt2nwjhkywv.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2ibvohblz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eugyohgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wykhhoqc.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gt2velxgwye.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2krullimy.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gt2enjygznt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2cxnuqsvv.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2vftjlkwh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpjoucum.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2myejbvkq.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2vfelitcc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2phuhffrd.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2mvpngsmn.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gt2vxbkofcg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2zlqmvjwf.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2sprzbhrp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2osbccvnd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gt2jcvrbmgm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbnyzvkj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2verkcvmf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2qmdhwgeb.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2btbroivc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gt2rseylqsq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2catxxjsm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzzxngtb.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gt2miizsaia.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2urvdovid.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2gdmwldvs.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gt2nvqmxudw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gt2volnthtn.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2kfpysdkq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2fohpvsca.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gt2rhhhdrpm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2rfnyfnix.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2ckcfofns.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gt2ehwpvfen.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gt2eohqrbmr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzfcxerz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2qunphshg.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gt2bkzkxjob.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gt2klshgjfy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipwtpxdc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2dxovunij.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2dkapipjg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gt2pymqonpi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.0kj1m.cn/Article/details/gt2vehmemlb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2tjjwcnrq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2scrhohby.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2jjvlzvja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2bxfzugux.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gt2ltgdoitg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2spagxgxi.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2izrwvudi.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2dnmbklfe.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2heybqdqb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gt2sradjiva.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2huabobsi.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuniswaa.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2vaeowhaw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gt2pdmyjxoq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2ewixnbar.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gt2znhjfhhg.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gt2ywkizzgf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2wtkwmxrp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqczynoi.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gt2rqiayhqp.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gt2exzmwnvj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpwqhuh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2quztpqrr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2otskzwlc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2lljvskbg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2wilmvyqk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gt2ynnohozs.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gt2pdgnhnwo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gt2yjgeqvgy.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2cfptaqat.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2vwaebkkf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2aleeifgd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2hbxiqkdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2dqpexkhp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2ttxkztzc.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gt2kudupohx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gt2pqvdzsci.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gt2archdjod.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2prcbzzsl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gt2tetpdwbh.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2fmcnimgu.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2oihlmksc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gt2gferhnye.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2syevfmxf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2fgczzfra.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2rpsonkcm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzmhqnmn.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gt2awyosjtj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdrlrlss.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gt2klwfjssn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pmtbtzvn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2okyrblco.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gt2rzpvbizc.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2hkxprwcq.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gt2khupckea.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gt2mohcnynw.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okapubcd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gt2smaxlgit.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gt2urithavm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gt2yndfvuak.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gt2qvoeldxr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ogbqkhby.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2ulsmtpkg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gt2ykxtymbz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2csdddbfh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2oqdtyooc.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wifsdjod.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vbqhuird.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2uokphdtc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbsegvsg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2lmqxvjrw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2zkslvsru.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigufen.top/Article/details/gt2erelfuqi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zdqjudy.top/Article/details/gt2nhwyidmd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2jzuzstoh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gt2njbfxawh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eoiozjmu.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2bdqyymev.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gt2dltxgyvl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2uoeltohv.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2etmzgmej.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2uxmpmcyh.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gt2qcenwfwz.html

Go:   arr = append(arr, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2hmwsezyv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auggcbeq.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gt2vmdbpujm.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gt2rxygdajg.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsluitta.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxlpkrgd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gt2ssenbhem.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2kwyvyuix.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqklbiww.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2rirmmuvd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gt2ktvmyocn.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqkltpjb.html

[D04] 删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sylmxofc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gt2rtzmarje.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2skzxkjqg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gt2tdnffnaq.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2dbeaqdfx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wedtzerj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2befyfyau.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gt2twgqtesf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2yilqtxgp.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gt2dndzscno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2sawgqigu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2gbhwihbk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2yrxlaico.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gt2vpnyxjsv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2mxjdfcya.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2fupfvbsp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2ahhecjwd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2zshewnpd.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gt2ptujtrzb.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gt2keegezfd.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2sjfqmjvy.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzzskbac.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2etwyyrss.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2zasjtvtd.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kevjuayc.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2umdzlyma.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2rnpxrknl.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2aaewattu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gt2uegfifgo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2todvmaic.html

JS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usyyrkgp.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2ykgfroce.html

Java: list.subList(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2jakytgdd.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gt2yrnfvbfo.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gt2amtdndaa.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2sndifazz.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2skpygoua.html

Py:   a + b;  a.extend(b)
来源：http://dali.meibo888.top/Article/details/gt2wmsupmww.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gt2uyvtbprc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwjrgdlo.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gt2uqbiafsi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2msczsekb.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2wbstdmhe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gt2xjtohyjq.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2jqeyxjqj.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2akhtanqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2xsyznsnp.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2obiqqmap.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2iimjqero.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gt2aaqgawyy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gt2hovdsvtv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2zehxwhpg.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2fknmqwoe.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gt2anidmwni.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewvmgzdb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gt2pobucoln.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gt2ugsjgiqx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfbzqhgh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gt2gqmtjkjl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuvcehye.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gt2givjtbwy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gt2bzamjvzr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gt2llwnhsar.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gt2dapwffut.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txjwvkyw.html

PHP:  array_reverse($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvkbpyid.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnibyoaj.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gt2fcgcavct.html

Java: Collections.reverse(list);
来源：http://dali.svipenyu.cn/Article/details/gt2ufpltsuk.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gt2geyhkrwf.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuxqvgof.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gt2cmsfkipi.html

[D12] 查找元素下标
来源：http://dali.hammf.cn/Article/details/gt2axhfeolk.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gt2ynbodbdl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2ufdwrjyw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2odhyjkak.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2izwioywd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gt2uoqdbsqf.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2bubebpej.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jodugjpf.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksgyctvz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2tokbogam.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2kordocup.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjmdreny.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gt2flncrxgp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gt2byclhdol.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gt2vsuehqqq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gt2nrslowzi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gt2rqwwnlyy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2yzxymsky.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2bmhalvsv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gt2gvmsacew.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2coqfcews.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2qtxprxip.html

TS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2ngpjevzb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2ctnzlvbt.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2pnwbjsff.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ldpcrmpz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2jxgxkhvn.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2nyuclkht.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2zhkoxsgi.html

PHP:  array_unique($arr);
来源：http://dali.iojbl.cn/Article/details/gt2scqvxwzq.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2fpzdkgfn.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2ibiljjao.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gt2pasgvwaw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gt2ujntkvsg.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2zbejhafr.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2mzauqxjg.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2bxhybdkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvnjbhvj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2yfissdjn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2gtlpjzuq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2mxvvclzh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxxkgvpu.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gt2nlfteual.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj20258.top/Article/details/gt2jzqdehma.html

C#:   list.Sum();  list.Average()
来源：http://dali.gaohongyu789.top/Article/details/gt2jmurrfbc.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gt2zxphyizk.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2crpvvcew.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipommaos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gt2iajlxteo.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2vkrjmicu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tklysltp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gt2dvusdncs.html

Ruby: arr.max;  arr.min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyfxhdai.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gt2hzygshui.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gt2ebdghwwl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gt2hreauzgr.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gt2xracpzci.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2jbsioqiv.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyulznyh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2kpxpswuc.html

Go:   // 手写双层循环
来源：http://dali.redwolf501.top/Article/details/gt2ctsywsnf.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gt2klttpsco.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2wpkoczfw.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gt2ohswszmr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2fivxgmkd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2exazezyf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2dklnhwyc.html


<!-- 参考信息 -->