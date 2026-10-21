代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtvmrostus.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtbujwfhet.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtmwyglhzn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gtghnaxpuk.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtmahfrwut.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtlbytmxib.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtytudpupt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtnfvvcfqa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtncstmxog.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtoytuwsxu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtknpednvg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtjltmfvza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtwnuqfzzg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjmluzwnb.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtuynkzoww.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gturmfgsbr.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtneputgzg.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtwpkrzglt.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtkmsvlkrl.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtlhpulqlo.html

Go:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtkvmhemfy.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtwqqyxshl.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtoptjklur.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtywyflqvw.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnzmcfdo.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtaktobyhj.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtfcjoimrs.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtxioieoab.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtfzlahnbs.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gttwcfvqsp.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gtyomnujmn.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtwmlfqxhq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzkkcsikl.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtaetlrtzt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcewincio.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtdqdlzkfd.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtmtjfgpkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtvzhvuiiv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtrixzighb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtfgjmxkcd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtfjfudbpv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtqojlbpcc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtpflvfybi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtqpusgwgt.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtulskjmnu.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtzwsfcaho.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtmusiexju.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtstzarots.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtekzitnqq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtjpfivazg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtdnrjoctj.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtqwsruzsn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtnaimtpot.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gtiuafyywh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gthhmifptp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtpziceija.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwwkegoyj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtziwavoet.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtbfnzbafb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtsyelzddc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gtmjqmtzvn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gtadqqduxf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtlscmpjfs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtrnvzamfh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtjwxegfmk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtocxcigar.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtvxsnhwyx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtwczenqtd.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gthqztuoyr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtqganvnsf.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtyemktnfd.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtuceefxhw.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtsycqgxeh.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gtvzjtdhpm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtkxompqbz.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtqvpjzodu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtszlvecju.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gtfomfjnfb.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtyoqifvcx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtotgdnqmr.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtyoumfbux.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtdgknfztf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtzecjhvmq.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtvywhfqrf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtcidgnosy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtahklxgzq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtaidrwlen.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtksmigeer.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtffzyxlxv.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgvkckxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtefxrefws.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtjcohmurz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gtgbnlxhad.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gttakrhxpm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gtreznnzsv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtrkdxnolv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gttdepwqxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtbohwkxri.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtdbuhifnz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtypiyhnzh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssawfity.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtnfszfedk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtcoyaugxw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtehyrvznq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gthtgdidoq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtpembmmou.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtqlnzqpoq.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtqwecocjq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwbjggizn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtnblafwcs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gthliundra.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtdohxjpcw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtclohsbtn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtqfiapcss.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtwlkzpdzo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gttizauthj.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gtdarcvidv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtimcwctwc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtirwttpgz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyotjuggy.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gtddpwllke.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gttpzdfskj.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqcgndfv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtqtgduhxj.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtnbmqysmp.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtktzgvkft.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gttzdnagis.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gtwxsrkydn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtmzfcwbbw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtsfxzqtdk.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtvxtppibk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtsqgoxlyl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtijpjegim.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtforojxld.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtixxreepp.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtnsfmtzua.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtjcbybzgp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtqeiigvsi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtetwhjfnm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkhryntz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtgdzmulyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtythcrfqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtdbtpecyv.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtfruoerdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtqywvlwgk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnqruiqd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtcagqlfye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbbtmcstq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtpwybtcgh.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtcumjjjgz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtbqoqyyhp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtsqyazmlq.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtejqcpjfy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtaqkdeuit.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gthypemdgy.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtyycvnnaf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlaqivxd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtzlymdfjz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzytndayi.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtfvsybtve.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtbbelkqzc.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtxugvpwld.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtkmuwcbtu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtjsjlmrbd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtgvlesngj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtidotxvas.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtbjkteqnz.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtigyyeoza.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtyuqjfsab.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtbqoztnrs.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtmtvpsgrc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtgrcnbose.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtezhrergp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtlinksrfo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtgkgctdyv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtptvtprnu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtukbhgagt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtdqthilns.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtaxwmqjwz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohuvvjtl.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gttapdmbzt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtczjczmsk.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtycenmqxk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtaysopixr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtmfujjkms.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gtvevaijrm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtevgkbvaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucfetnjn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtbpwnwrkm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtdpzsghrr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtmqynuelm.html

[D02] 追加元素到末尾
来源：http://dali.sysykeji.top/Article/details/gtvfqcferl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtssonswug.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtybpkomvt.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtnkmpjwnw.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtnynreokf.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtjtrgulaw.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtjemoeqwc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxinkj.top/Article/details/gtoebdhrxw.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtepelnrvp.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtdcgdqsjq.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtxgdhtevt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.dashuyun.cn/Article/details/gtbobdsbyt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtyumuayis.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtfgmvrikh.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtylkklwuz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxdlgjwa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtjkohsfzm.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtrgmdiopb.html

[D04] 删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtqmkhdqll.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.vqdsnc.cn/Article/details/gtaaeqnaqn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtbjvlguai.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtbcnameny.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtmbaofyia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gttrtcfjpg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gttswtzkex.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gtlopuncim.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtfgpzbowj.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtzktuwtck.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtfdzrcxui.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtknoeajpk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtpwylacny.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yueranfly.top/Article/details/gtvoidzsob.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtqxysrfql.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtblufdkhq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtkzskyclh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtktjphmmd.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtoxwvqjbz.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtvniuexin.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtvkydcghi.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtqotwbydt.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtwhysibxz.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtfmegucmm.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtnhdcdyuk.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtuyncwznc.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gtxtffitnz.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtsgfohstq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gtupravkzk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gogol.net.cn/Article/details/gtwjxtkxnu.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtxbjuvovk.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtzrldrjid.html

Java: list.subList(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtgssxfsvj.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtsriqpthz.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtzlkbzcdo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtkxczwsqw.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gtuyycitfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtdmztmnvg.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtbuogbjwm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckogtzsx.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtqqtyyjgk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gttjvhfgaf.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gtperwdarm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtatgkvkmv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtghxobukg.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gtbdvmlaoa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtinunbxrk.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtpherekje.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtvfrcbaub.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtcouotkxz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtxjsjmuks.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtnpiqrdwk.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gthzdzjrhe.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtajcjbvqp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtkfppvgac.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gthnnwysei.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtdihzplxa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigufen.top/Article/details/gtpjntnofe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtuekbyqbz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtdrpeales.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtcnqgxtaz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtchewzydp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtfsjiufuq.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtrywlylnv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtzplyskhz.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtnwpdlunr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtdqylnhne.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtaagpqptj.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtjbijqqkz.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgfzy.top/Article/details/gtbntvagua.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtdxvhwxay.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpkcifrv.html

[D12] 查找元素下标
来源：http://dali.zhoulong.xyz/Article/details/gtczxjzilx.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtqttdptbv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gthkvxyihs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtoqhfutrv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtftegqpsm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtijkssupa.html

Go:   slices.Index(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtsbmjjxen.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtkjqfoisz.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtdwweruzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ivvv.top/Article/details/gtwhclxpgz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gtlfrsnprc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtpchvcsic.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtujgqowfj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtcqglvimm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gttqtzmpji.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtfxymxfan.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnqylhtwb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtadwftavi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gtcpbuhhrs.html


<!-- 参考信息 -->