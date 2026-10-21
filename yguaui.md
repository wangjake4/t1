代发 wailian999

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtpiefxucd.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtdfolginh.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtwgjqiewm.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtuikwwnvo.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtqssjkcjn.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtszgljetq.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtffaqbuzx.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtpejwlpky.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfuiwsoir.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtpuymlaqz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfiebhkqw.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gtfsntcpko.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtgbyxnaep.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtllqhwmyv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtcxwdsefv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbyoljwuk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxorkzycp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtvqnhotsj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtxowyibxo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtxyxkllqn.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gtncpogwzb.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtnqpoazpt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtbqiwhene.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtsirwjcth.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtqnwjgijb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtagsxsoaa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtmhiatlvt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gtyetlhuzz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtafsodubp.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gtyfushatg.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtndbnphya.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtxmefbvxi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtgpkkltpq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtsjanebkq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtsewbckbe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtxhbomdbj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtevezjpqx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtlfguqqds.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gttevojxih.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtzquckcis.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtccdmmxge.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtzodgqmmy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtxrohkszl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gtlxrbcgcp.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtgkaqqgjh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtaswedfur.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtvhfnaxef.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtvghbheei.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtjpuwmfvo.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtfnkwwrhl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gtinpuczyx.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtioeoqlqq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtwyigxhmc.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtiytwbxxy.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gteoupbbnj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gththeozrz.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtqkkzhapz.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtumubhftn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtgpvgsxic.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtkelbgxcb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtjgirrszj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtcuqaxslh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjftscnia.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtobgabafd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtcihmzwzz.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtokiqudgq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtfbuwtexn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtqiplqynr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtffokkchf.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtqndqtsmb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgcvuiuc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtwofzpuae.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gtumqwnzkp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklgfjnjt.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gteokjjugr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtftcqasjj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtgcjobvqn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtvfcykhsk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtdvjyrhgs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtcdxabtci.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtfknaunlc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gthpvwreyc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtrgmnniko.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gtqzssyswd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtiibmggsm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtsuitdgqk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtyevpgdhh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwvjdrod.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sysykeji.top/Article/details/gtdpdxnmiy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtpvjeqbrj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtmhodgvaq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtemygmdgc.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtmmnqzfeh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtohkqyhhs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtbsdfgamx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtslzuqqpw.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtzribcodw.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtfcnxylev.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtfwgxhiot.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gthkgadbep.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtlthmlddh.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtmrpsbkcq.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtmwwktngw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gtcmweywlz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtczkzevkp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtfctdwnbt.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gteemqjcpp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtslccciye.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtmhcmsaan.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtqupltmbq.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtnqkbtfot.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtrneeyuqv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtgycxbiuq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtwhatwmua.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtxaltbcso.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtmaynwomd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtccwtwwjc.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtaibbwgao.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtsjusjfel.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtnnxfpche.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtuomqlbae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtoupahjrn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrgalwco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtameucmpm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gttrayayvf.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtsdlkprlz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gttbkdlpnx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtqqhpckbu.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtqdlutswf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtxbuufwdz.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtuwlrkxqi.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtotkypswn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gtcqrbzqwx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtsmwftejk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtwlvqxejm.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbzlfjxb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gteznmojnj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtpxuiasei.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gthnyqzlpl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtwpsqkvse.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtbovuklcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gthptkeguu.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtyajvfjqp.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtctdugkgl.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gtjmuigzzg.html

C#:   var (a, b) = pair;
来源：http://dali.svipenyu.cn/Article/details/gtdprnsqtp.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtwogseqij.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtrhuziqmc.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtrssfjxld.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtarnkxvwi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtrddmwxbu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtiogpckbd.html

Go:   // 无重载：用不同函数名
来源：http://dali.aibaodan.cn/Article/details/gtypievjum.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtckdqcfmt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtbmnnuikd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbvpkmjoo.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtvgbtvbhc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtilkmbcmx.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtaedceajw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtvbnbdwzp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtciwptnrb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtzezcsbzo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtpvudhaja.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gtpepwqkeb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtsqudzxok.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjndlztmt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtinykkzas.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtfircurla.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtvxlzfoii.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gttnlvlyvb.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtqcrubilq.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtksxvccut.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtejnqfutb.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtjgqypaax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gtenvghhad.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtazzretnq.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtmjlmtuqw.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtfrdcwuuo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtxjtkvccg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtjxssagcp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtspryspal.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtugchylgk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtempmneqx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtflsjtjsb.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtjxoejtei.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdecnzhqe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtmynxvspb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtsltocgod.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtosplzbgn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gtqzccejuc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtwwrgeeps.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtlfhiqxqr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtmqpyvhcs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtxxifdknu.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtilyzyvov.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtkmvtfzvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtpmcywlgs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gttnusmeiz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtfvicuvnj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtfuizdfns.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtkwqijuhk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtbdidvcdl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcvpefki.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtuynpsvqj.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtgkozfuai.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtrzetgqor.html

JS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtkkhtlqir.html

TS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gtatkvptmc.html

Java: list.size();
来源：http://dali.jlsjyb.cn/Article/details/gtpfuofyyk.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gthxlrihyc.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtqpudqdms.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtjlvaifdo.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gtcjsvodgz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtbcwunugo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtpaanrsrl.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtzeuzgbfu.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtelykvjkj.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjsbcrizs.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gtfmotrxvo.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtfhjemkqd.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtnhhysurr.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceyfrsms.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtjgoxzwok.html

PHP:  array_merge($a, $b);
来源：http://dali.hnqzz.top/Article/details/gtsbkmwgjz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gtgdeehnvh.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gttnkmeudq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtzumhqowb.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtpvodiyua.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtywcpqcsa.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtzyokmwyf.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtyhsbgrdp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtdgwckjnh.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlftfawor.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxfwmuw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ppjwa.cn/Article/details/gtwbgmhkeo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtxipdhcgq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmdirkho.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtfhwtlpci.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtwkqiaaip.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gtshnobunw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtntrgngue.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtlpqsqnnz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtxnpqfrpz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtsjntlmpb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtmfestvhd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtjnaraiju.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtfqzjbpbq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtvnlzvngf.html

[D11] 反转数组
来源：http://dali.cdnleiting.top/Article/details/gtodxemsjv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtqunodfsm.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtsumsgcnu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gzhubu.top/Article/details/gtqnmwssri.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtqsmlbfke.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtubtstytp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjehmdifc.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gthnxtrizl.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtfiyxnhxv.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtayszgrgo.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtpvfcmnnu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daria6918.cn/Article/details/gtgvfsacza.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shzxlz.cn/Article/details/gtetvruosu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtkfrdtjdh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtbjljzass.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtyyfkmxrz.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gthwstzppo.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsrmeozv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yongpay.top/Article/details/gtygvusigh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gotoacloud.top/Article/details/gtvojgpvdn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gtpvyvadns.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gtuzfbjxuv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gtfmeynhry.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtropdazlj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gttlqiffcj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtpofwibvm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtaksztlmg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtqkfurjpz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtgeqiervu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gthytpdpth.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtkatvfywe.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtbgccpbyn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtdtfcalyj.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtbpakezsm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtxezsfswa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtyiahhxdp.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtqmmmvfae.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sysykeji.top/Article/details/gttmeqsvys.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtjrqcnfkf.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtnjdggnex.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtwupfungs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtreohwice.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtuvfueluv.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gteiuphzju.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gtghiugrtc.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtqsibdgwd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpddzfwlj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtsadzgjkf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gthiymkzmt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtehdziqix.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gtoidheyuv.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtuvubwjto.html


<!-- 参考信息 -->