代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2bdnsbhyq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gt2mhxvykdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2kckotmgq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gt2dogpcloc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gt2zlhnvdlj.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2kvscmhis.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gt2hllstnap.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2hrphufnj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2nkjukzxx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdlujotq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gt2jdgowktw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2tvuizwjs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2zdnhynmi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2ihxhyznu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2vdwbqxli.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gt2indspzqf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2mnnbcxcr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2xztlzkso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gt2zwcxibgn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gt2xxmfmsij.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gt2vmrmqabt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2hskrufkj.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2ykjrxyxr.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gt2jnrujwat.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2pyjmwabg.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gt2ermxddhs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2gboctmvm.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2dvbnrkep.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2fuyqocpd.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2ksrsoxhr.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2bkuewgea.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2foblxeva.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2qpdmkkuq.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gt2jhccxbnl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2kzszvmgo.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2ioydggtm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2rssobign.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2stjvzgkn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2lvkpiosh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2hnouxhgx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2pnglekdb.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gt2wiuqavjx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gt2jcawtygx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2cqxolpsy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gt2ongzmgng.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gt2rzwwotzt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwmypgyf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gt2zpnzaoqj.html

Ruby: arr.map(&:upcase)
来源：http://dali.ppjwa.cn/Article/details/gt2lxkkfabu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gt2ahgkbqbw.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2lshgyorj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gt2qehhhlcr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgztiwze.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2keoizkkv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2uxjcwjhm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gt2dtplypcz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gt2kppgdzax.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gt2hywygkxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2cvbsubdp.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gt2ndwrlygd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2npmqmahc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2wpuqkdhc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2qqirttkb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2ngsyiudt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2qukanazy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gt2riteugtm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gt2nsbuintg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gt2jwazcznt.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2geqnjvbw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2zdzldera.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2chgbdeij.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gt2logpswhv.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2efjllqiq.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gt2ivnnxmng.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2ypghbyvv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gt2jwhbqcrm.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2brllyvgf.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gt2gtwqnrca.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gt2fajmutqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2lruawsch.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2nfqygdyd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2zcbveslz.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2dpnkblkt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gt2jigjoqdk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gt2nzzhcrur.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2kfekwgor.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigufen.top/Article/details/gt2fdshclkx.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhumvogo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2gftkoati.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2mzlapyre.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2ygkoynox.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2vbqkdjfj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gt2yabueahc.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2aefiiacw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gt2rowfwtmc.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hllrqskt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2mdmdpvrh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2plyhsaym.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gt2qakoveop.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mquytjis.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2sjiwtwpm.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzqrllqu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2argqdusw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gt2gmqfcfbv.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gt2pztzoann.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2edvpefuj.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2lqlmewrw.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2nwdrfgva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkiamlzz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2kogavatr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gt2novziqbr.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2tmdjwaur.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gt2tocjdqmj.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gt2ptsypbae.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2eoqwfprr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gt2rjrfmfxa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2kzsvbibs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qwdbtcwa.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2fmaoiqxk.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gt2iiohyvtx.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gt2hjdgiysc.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2gdwjbkxa.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gt2mxvbsuzd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2larduwtm.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2nrxeoxda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gt2byzzkjob.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2permhkvr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gt2osrnefjo.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvrucnp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gt2kmxzjxck.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gt2uqbmuknt.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tkfhsqno.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gt2itxxiwdw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bynivkkk.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2senrgnch.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gt2elvwkztz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2fsiobdcl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2fkctanmd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gt2rnopoyyc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gt2hhaqklrv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gt2wxeuixlp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gt2kerluvfz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gt2zgeqakna.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2dhsdptfc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2ftdyaxjh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwllmsic.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gt2llhadkjh.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrjeficd.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2zaigzvxg.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2vsgoyfyy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gt2vlhvogzt.html

C#:   list.Add(4);
来源：http://dali.aizwys.cn/Article/details/gt2gjyerzsq.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rupcreyd.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2scqvqrzd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2bbrjoima.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gt2indgdodk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2koemxyax.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2kzcznwvv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gt2orcssjjo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gt2xjvrfcso.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2iwnqupaa.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2qtmummel.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gt2anytugpf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2jodsaqoe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gt2difuzker.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gt2ixztuqrk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2emeeakgj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gt2qkvaxvqd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2sypbyopp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gt2uhxxwylh.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gt2ecuizqgg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2sicuqrsd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gt2qhjkceua.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2wzukhbgx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gt2iejcizbr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gt2ffvmcuxt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2xedcoocf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2lyiredla.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2kwwforix.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2bggbvxff.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ipyofzhr.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gt2jdrgnrfd.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gt2bgycnuqk.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gt2mbbytguv.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2nlwdgdfh.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvhweveo.html

Ruby: arr.length; arr.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flxhqvxk.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gt2oaeqlfke.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2tkjzpvkp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccytdruv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2cdwwyhqk.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2myvdrmms.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gt2rjwhatnv.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2mhzyapbn.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gt2bbkkyyiw.html

Ruby: arr[1, 3]
来源：http://dali.haohaochexian.top/Article/details/gt2menfsyie.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2hibxofqb.html

[D08] 合并两个数组
来源：http://dali.yvedp.cn/Article/details/gt2mpflwwfp.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gt2qcnixtda.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gt2zykwmuzw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2agfsyjpz.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gt2dtpcrong.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2lwqmjteu.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2ipclthiq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gt2myzqzzrn.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2rdgxhzvi.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gt2cvygzioa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2vlhrpkdm.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gt2khjroskd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gt2wnxbhyha.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrxwmqya.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2ddipvpoh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2oltpmsad.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2njntheby.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gt2xtktwtnw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2cbnpajjt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gt2ppjhzxqq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2jogtptdg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gt2nkhcavuf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2vwnbyvhu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kefccfjd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2gumgsdqq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gt2eyxrxmcv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tian-w.cn/Article/details/gt2werakuot.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2xkofycpo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sweek.top/Article/details/gt2lhjddyzw.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gt2pxwtfywz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2howixhzp.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gt2eeosxbpk.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2noixrumu.html

Go:   slices.Reverse(arr)
来源：http://dali.daria6918.cn/Article/details/gt2mruqdnzt.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2mshktarj.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2hauffgkm.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gt2gmvhgifq.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gt2qalbffxx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gt2lfsabsfl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2rnywatky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mylfgaqc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2sfcyhsuy.html

Go:   slices.Index(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ypbrydzp.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2cthhyxli.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gt2frzxskyf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gt2wcnkkbyl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baocdkmr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2keyecgqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2daauopzd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhpwfzwa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gt2dfuhourk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinqigfzy.top/Article/details/gt2xeixislc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gt2vglmnbxr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2mmlthxri.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gt2vtdhrrfq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gt2qjrlnjkt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cashguo.top/Article/details/gt2ocnzjqsd.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxpqobmi.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2ftciryjn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2uffpfajh.html

Go:   // 手写循环
来源：http://dali.hammf.cn/Article/details/gt2kfhoxuvc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2litqekak.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2hmxgalry.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gt2suhapmjd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcdetobx.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2llbdivkm.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkpsslzw.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2uhkevzle.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gt2frgoqrtq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2ssryjkrt.html

Ruby: arr.uniq
来源：http://dali.andypj.xyz/Article/details/gt2xxirpsix.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gt2szmmazty.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozogwxra.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gt2nzdgwpyl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzrznklk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gt2xoayctbm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2fumpzfrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gt2hvmucipo.html

Go:   // 手写循环累加
来源：http://dali.jqgfzy.top/Article/details/gt2meyowmgn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gt2orwigsqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gt2djiuriql.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2ukrapbrt.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2gpmzkfln.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kojxsevb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gt2ruqgvtix.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gt2sbtnrefa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gt2hxiiqpkp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vfgsmbsh.html

Ruby: arr.max;  arr.min
来源：http://dali.iojbl.cn/Article/details/gt2rtqqnyhm.html

C#:   list.Max();  list.Min()
来源：http://dali.zhoulong.xyz/Article/details/gt2txrellbm.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckfncebq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jqgfzy.top/Article/details/gt2pheshkhu.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2rczlqdld.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhongyouzk.top/Article/details/gt2pdfsfubo.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2hhuebwjs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2mqbtctcl.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdvpwmhb.html

Ruby: nested.flatten
来源：http://dali.yj20258.top/Article/details/gt2rdjurrsc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbvbfsyo.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gt2ohvlydyb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxsgnfia.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gt2jlxnljja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ppjwa.cn/Article/details/gt2hegzttjt.html


<!-- 参考信息 -->