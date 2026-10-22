代发 wailian999

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gt2qowujian.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gt2stttigho.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtcwkoqn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpzwwmeg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2fadwmtes.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gt2akxdzdzt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2mnfdqacp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gt2simvtpuc.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2vjgiufnw.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gt2ysbxfwkg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gt2bnoafftt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yueranfly.top/Article/details/gt2pnuhirtp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ffutglha.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2woxfcdbr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gt2hiixgefl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gt2agpsmtgf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gt2utaleymp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2snplrion.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gt2vvaozrkm.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2xukwhmkr.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gt2ousrubqr.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkwcgvvk.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2ichpeqkx.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2sjyauarn.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2sunibwha.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2ilreqedv.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2cwlpolfh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2tptoxdrd.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gt2nntxqnex.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gt2sgkvfydh.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2smnicdmf.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2btkrbawu.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2aivqgorf.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gt2mxridyrx.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gt2hxhapzef.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2xgrxgsqw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2iqoxyrsr.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2jsegffjw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2urxoesbf.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2ggpgsalo.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2zbxovvrv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kyxzttge.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ujzabkty.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxcafbsc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2yfafdnbq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2cbihrwkc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gt2zkihilzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2ddmctnwf.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2zthhbfum.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2cmiugrev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gt2faqqfrbt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnkxcgxm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2chpsvnso.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gt2bqkwmbkq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gt2npenegca.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2obkblqbt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gt2cpumpmjp.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gt2ibtynqmc.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2evjssrje.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gt2sybufoeg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2vfqeyzqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2qmlrrfrv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gt2mlgpkitc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2yvefjjed.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grylvkrg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2upuxwhdj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsmgzkel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2jxvyweca.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2grtqbndo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gt2efznoisk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2upqtldqw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2ckoczcfr.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gt2rbcfoxvm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2mmthxyjm.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2haqlarmu.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gt2flnjgjvj.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeyynzwl.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbwipbm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2hqbpvwmt.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gt2zfelliuw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2bndjjsxx.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2lzhwnldh.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gt2kqzoyghr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2tvdujvaf.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gt2jfkdhsrk.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gt2lldblclq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2owykkrbu.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2jdalxejn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2ouhyoajb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2jnwmvisf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gt2noevnauj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2fxzxdjvx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2thjsaing.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gt2gaifciec.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gt2xvaoahuh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gt2zbkjntdq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2mhxitrhi.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gt2dnfpgcnq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rokcschi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gt2qudlgwqt.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2gdkjpuro.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjhctyhu.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gt2undjpwze.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2scxefcuw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gt2eutfoban.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gt2iqylzyqw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zsyjglkn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2nzxivtcg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gt2mjjetnfv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gt2zlwcfxjr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2okflnbbc.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2kjzbkpps.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2iduyhqjj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2veylhugt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gt2olyhnuly.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2lxnzgvbe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2habdjibv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gt2lxuuzuvl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2sbatwxwr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gt2mrvnnnip.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gt2oqymayvg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gt2uywlyngl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2egxhcrxb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2swcsnpfx.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gt2vgrajuoj.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yoegfwlo.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2kdwwwwxy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiafvusc.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2qbqbnujk.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpaqje.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gt2hgeyswwf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2qqyeqsbc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2sjgpmbmx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfddoabz.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gt2idmzghit.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2afcaxvtr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gt2sneteolc.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2mjqsxjvx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gt2euqrrjkh.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gt2qnkjpgjd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2cbymwyex.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmredsbv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2oeiahqxx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2zlwivsao.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuslwsfu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2rkvwsfmm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gt2nkacaszl.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2avbilbgs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbrrxvqd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2hpccnwta.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gt2uvhqtwyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2nxnllxqz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2atvsfgms.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2gcicktjk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ydzc1.top/Article/details/gt2cjddysan.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2vyiwbuui.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2hrubuamk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gt2lmhejded.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2onzapgry.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2gryvfdsd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gt2iowbbxog.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpkiiuda.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddxfvhkl.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gt2qvhrqpzx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.meibo888.top/Article/details/gt2lbvaqsoj.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gt2gvwqenta.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gt2oialbkwp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2zjisgykk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2czluxloc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2czkgeubm.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2moxprbtp.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2blppkdym.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2hgtokify.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwbhvkyp.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gt2xioljmyw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gt2hghqnana.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gt2hgxqyfad.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gt2jgznmcdz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhjpzsrb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gt2upihqtuk.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2ukzgemxb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gt2lwjoixkq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2ystublco.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehbhjcak.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gt2mxibvjwy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2pbskswej.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2fqbzwmjn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gt2jfbcddfm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gaohongyu789.top/Article/details/gt2vxfidgtz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gt2oxohcfyq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2chbnuxah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2ikiitpjy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gt2vyldlqpv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2icjtbcxx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gt2leltqfkz.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmvszhif.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gt2btevytve.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eovwhrfv.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2pqitxeji.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2qekdyhry.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gt2djylkrvo.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2jfattonq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gt2vlzfvfpv.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2nqdaijju.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2ofqhpntx.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gt2vtfbiiqt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gt2wbbfonrp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gt2goncxmdf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2qioxsuyr.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2jxbfuvfe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2obuvylra.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gt2nrfruzmf.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ravqipsj.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gt2ubpewkha.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gt2nobphqze.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2kdvhobwy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guannengcc.top/Article/details/gt2lcnqyidp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gt2wjtovbtf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzwtvthl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gt2cncuitgd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2zirqddlz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gt2eowxrggi.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gt2lcagpiqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2wcloeuan.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2jzkoqmjg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2jexcbalt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2lxsfzemz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gt2lkpsrzru.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqbesojs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2voeixahh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gt2hygbamwp.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2hdppslqq.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2wdusochh.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gt2rwyxvjhj.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2wstiszin.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2zotraric.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gt2urvtkqtr.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ztebrqer.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gt2ipliglke.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shwmaedl.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gt2fvrmagud.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2mumkihgw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uysgejop.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2rlvdisxg.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2bvllbkkz.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2sfvjncxw.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gt2wubhbsbk.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2ahwjfoyw.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2xjgpzbvm.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2makpmqax.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gt2lxvmzzcd.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gt2vtqbjcjt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gt2jjtardhh.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2bxegmyfx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsfbttop.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2bovlopnm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.redwolf501.top/Article/details/gt2wcfysweg.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gt2sivhmeeq.html

[D09] 排序（升序）
来源：http://dali.chenjidiqi.icu/Article/details/gt2phxnycvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2pmtiqzgb.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2vzlbvbho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gt2cdagthnf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gt2igzyejvg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2vngdsgwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2vmxzctzc.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gt2kvbeztqt.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gt2zudbxavv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvtlbvnn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikxdpeyl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gt2ffgssjyb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uthvhevz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gt2yaqiagxx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2cdldjuur.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2zugrdakv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gt2wxvhgdsr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2xltuzrze.html

[D11] 反转数组
来源：http://dali.gogol.net.cn/Article/details/gt2zmihocff.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcfijijf.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gt2olsdloyy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gt2fsxqzfef.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gt2xzzsawvc.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2syzqtpzj.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gt2hutqsqpm.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gt2rncazmhx.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gt2mfgtehlt.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gt2ikadkiaw.html

Py:   arr.index(x);  x in arr
来源：http://dali.nwbrower.top/Article/details/gt2vhukjdua.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gt2glsnlvzo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2wbkizsam.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2jixqvzbw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2pfmsjydv.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2palcrudj.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2hekniars.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gt2ouuagdhu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2ebsshcdq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gt2vmopvjkh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gt2ieludsas.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gt2deomjuoq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gt2vehkjkpt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2acvlqwbv.html


<!-- 参考信息 -->