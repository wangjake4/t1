代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtlgpefxzd.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtujxatuie.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtinzckqzy.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gttoiiviht.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtdfdglxou.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtuncaxizw.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gttsiejocj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtfhzqohuc.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhntxfkk.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtnqyuanoa.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtvtvcsieu.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtlaanoyqx.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtlyibjvmu.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtglcnkjed.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gtuckyyfrj.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtnxtplrzu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuozjlqvu.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gtnrecqbkl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtumgjvknz.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtzksvvhrv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtvpgrgxuw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtpjyhjipk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtxnkmeplh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtbjktrsev.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtsdwqyghb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtycoshbvc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gtxrnxxaah.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtoliayxcx.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtgrawvmjt.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtvsoqhypl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtgvsxahcq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtfknevlqz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtxvplaqsu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtetxkcmto.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtizhaimgo.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtssslihyp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtvlqvfbcs.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtvunkxbgy.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtqenlvmjo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtsaojfebq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtlnjwvpwt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtniicefze.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpjykplkp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtatfqbuxb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtfndyessi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtdojivmoe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtpnlbnsqm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtwbceleuh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gthzrdnyii.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtvpggarhd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtsqwpqvhw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gtwahcmmlf.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtxngxixfc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtyjtfxdzh.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtjckqbshn.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtuzkbbqsw.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtnramqkmu.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtnceimtok.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtcvzfrovj.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtqfgrufnv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtctzzlrvi.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gttdmgsimt.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtazaagutp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtddjzlnif.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtwnrrtxcq.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gthfakmtnq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gtrmbsyfqv.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtrtyqoann.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtwzuenoio.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gtraloklce.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtsbmvgwlk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtrqdlrilh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtnvizgybx.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtjdxwcuji.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtuvvwibgk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ydzc1.top/Article/details/gtyhgszidm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gteatqqxza.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtydwdctmo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtenufqaln.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtsmitlyyz.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gttwgsglok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtpfqujwjf.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtdwebwpqt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gtvttuylei.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtwadccfsy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklbtcnic.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtjkyvtiid.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj202588.top/Article/details/gtqsztbdjl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawimncrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gtprpnmlcx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtyssdnhyq.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gttcintmep.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtnchkbhqy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtbkgylbgf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtcsvtnohw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtltkcympd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtgcjpnxri.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtjsdnnruh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gtlhpxcarf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gttrnncmqf.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtovccejaq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gtbxjkkkxa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gthuionbza.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gtitfprsxx.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtkubwktaa.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gtqgrqssqm.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtrjzgxxvq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gttspndyle.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcpbdqmi.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtwygwhzjt.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtjeerlmck.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtjxmsogpa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtmemqhvch.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gthzyzotye.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gtnfecstmp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gthoquzltr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtsdlgemio.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtizfjzmiz.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtxaxdvgru.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtdnchqffa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtwgfrejwc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtwhsegxcy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtegoiejag.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtwlenrywz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gthqpekkzt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtkgrsekwu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtehsatwjd.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtjxltpvfq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtrftyojzf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppykgemm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtbmnaqwxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gteiuoqfkd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjaroovqo.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtzoqegkmy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtsqwpivqa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtgdminprs.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtesphhzwk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtlzqczvap.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gtibzvmkiw.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtvrlwdwou.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtrlqusvww.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtlhoeheiv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtkryaubno.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtaehyhepe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gtixzgupmz.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtfiwypnyd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtyeacjklf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtvtehlxyp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtszchlzee.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtwsdrmyhx.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtgcpodkbs.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gttcivrxkm.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gterltcmmj.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gtnvoqhsqa.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtujqvechd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtkokwanpq.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtnibwosqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtlzqpfuaq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gtssboieky.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtriyimpzu.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtrfurzhnp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtmcabkyhq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtyubqgmev.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcvtynnwm.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmediakya.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthjckwgxt.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtoqtaqtgt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtkoirseoc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtblubotfb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtjlgzxknn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gthmrygach.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtzhurmnpv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtewebsjed.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtdfvuwcyc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtvvouqmyx.html

[D02] 追加元素到末尾
来源：http://dali.chenlongwang.top/Article/details/gtkqgziinn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtdxysdggl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gttyqtzvaq.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtittgwoes.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtgjvmuznz.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gtvgdgyydk.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtdnafitvu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtjjtrbhaa.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtwaozyzyg.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtrkiuvbxy.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtgmsdsqei.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtlvhkjrnp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gthhgxartp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gthhrwnonp.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gteviqjzla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtsngyyzfv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtnwharryl.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtxdqnmwfm.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtpsiburce.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtgysppvuy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtjfpjoxdj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtyflnpyko.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtenhlgvot.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtibtnawrc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtcytoykqt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gtctfkbmwh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtadwubkpx.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gttcmbsuno.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtdeonudnb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtnudwgedj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtmjfrdajc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtlfoullro.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gtinxbwmbt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtpxjdzqtm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtpfnuxqqz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gttfktrihe.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtvschtatp.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtknvhmksd.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gthuctvgsf.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtryloxkbe.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtnjxgwfte.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtfutyxqiv.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtjmlgenqp.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gtctelqtkd.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtbjaxiplm.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtgcqxhqmp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtmrnwbjus.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gtfldxqsjx.html

JS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtjrkwfwan.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtwitwmgky.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtarvxkzoh.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtyvgzfkpe.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtdljinjat.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtaxxkfygm.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gtxnxghwau.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjddiquc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gtndgvinze.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gttwbatxwx.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtdeuvbaso.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtwvvwphve.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtaksrieuy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dianchejie.cn/Article/details/gtavpxbexg.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gthrwpmicj.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtcsypiljl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtkdzjfigw.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtkairwjlm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwddbwmct.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gteotznmag.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtulnfvgzd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtvhuascuv.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtlszbdysa.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtizavkmqx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtejbecouq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtenmngfuf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtcwdztvmq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtxhkqiqvi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtlpcfpgvs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtjmpksbvc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtsfypcevo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtllnzjbjb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtolswdyja.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtbzccksoq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtgxgykump.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtfhvsggfv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gteajfntpf.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqwlmboq.html

Java: Collections.reverse(list);
来源：http://dali.iojbl.cn/Article/details/gtfumtizol.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtvnuxnmrf.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gttwknkono.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtevbaxdal.html

[D12] 查找元素下标
来源：http://dali.cqqwz.cn/Article/details/gtapxhahjf.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gtfnmjqnqc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtraenzizz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtypxslfhw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gtqljfsfuq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtgevmhlxc.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtwblhmdjp.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gtyuholfhy.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtszduqqbb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtcedezjct.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtcmqphejj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtlcduxmoi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtntraqdsa.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtjtuwvtxd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtlxatgldt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtichuwljs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtcwfxhgel.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtiykyugtp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtpbrddisr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gtkjzmqusw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.andypj.xyz/Article/details/gthxklkzhs.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtmwxqdxil.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrqzxmjdh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtznlcgiem.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfaxiase.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtcdqxwesy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtupvfygah.html

[D15] 去重
来源：http://dali.dashuyun.cn/Article/details/gtnzzhjvxd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtltjdoyrp.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtzlgebcqj.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gtpydawycx.html

TS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfncdoxos.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sxryk.cn/Article/details/gtgoafccne.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtnycuxncu.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtjdaojbyk.html


<!-- 参考信息 -->