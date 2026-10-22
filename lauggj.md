代发 wailian999

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2keabrdvj.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gt2sqoppqro.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gt2gsgvvfll.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2pzojlhxu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2alsqrgfe.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2fvlfvitc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2notlbdrz.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2zrqlbyvx.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2smpzbkzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2hgafacbo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2mlbbjncb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qjesnufr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2ogvvmwdd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gt2dujspwdm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gt2cmtfnnji.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2cdzstexn.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2cruhwxbv.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2ldoaifom.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gt2yfmakrnf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2reocjddx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kitaiqen.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnfxcayq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gt2tlhbrqmu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gt2gjimdzfw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gt2nuxdaajx.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjnbpmak.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2oxawhlol.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2dxglfwpd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2hifeuooi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gt2yozluyfg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2puuxtvog.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewlzcrn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gt2umbelomo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gt2kydqhwvb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gt2kwelaxqb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gt2cdogxdyi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2brjfyjir.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2ftzjgtea.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2jhgfpmna.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqkiaco.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2xmyetqgp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2ssfkgvto.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2jjblvjiv.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2hotksrok.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2dnlzaccv.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2rcnfuhux.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2arwiqgkg.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2kjsgwfsc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gt2sdkfqagd.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2tjabffdw.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gt2zfbycbse.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gt2prjjziiv.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqbpyrbo.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gt2guzbvhvv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gt2dmkkvgym.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2jdzbnapk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2wwhtsahy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gt2zreohslp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwnybypy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gt2czdpbexm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2xyzqxlfm.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gt2dtzdccgs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gt2adwmptxs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2epmsmvqv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbrwoalp.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gt2ndzjxnfv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2uafpisfs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2rxopcmrd.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwfyndvi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gt2oxkehgqn.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gt2erjofrkt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gt2ddygdrix.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2nvsypupu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2qhgdfipw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gt2jqdstelr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gt2ihfvxthp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gt2ajaqlsdq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hirkjvks.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2vtfmbldx.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2bbzxrwrw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ickuemri.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2lgoorzcq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gt2kdioaomt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2dbzlbiyi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gt2ahbzfqvj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2ddxiwmtp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2nfortasc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gt2tkiwxcle.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gt2zdsoaicq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zycfv.cn/Article/details/gt2mapilite.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gt2uqmevnwv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2jneddyfi.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gt2zsadomqh.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gt2jvlblfru.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2txekgvhu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gt2ycwirtmd.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2ltbakvqg.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoenaryy.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgebkwhs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gt2zrdavzig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gt2fyhbfjcu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gt2lloxficl.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gt2gwpydeav.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2dfjjdlxf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnbfnudr.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gt2icfkoiqu.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gt2tmlzuvsd.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2tyeclvok.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2wuyqlujy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gt2qfvzprqt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2esfbzpnu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaiflsxp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gt2vaenpier.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gt2qbrdtizo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2buesqowi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuezumib.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2iuvqjzez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2llqhxdta.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2kummipsk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqacpww.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2trpodvea.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gt2vacanmfa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2npsryjhu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gt2pkzfjlhb.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gt2eqtezesk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2prdgoqxj.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2palekneg.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2huentksn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kuztlxiq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irlzzsqw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2yppgereh.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2dlwsjikz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2szvmqqfg.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2befhvgbq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2fihwkdgp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gt2qsxnniaq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hoeyohdh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2akfcimzs.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gt2oyqmnxrv.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gt2gqjxireg.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2uvpbhsee.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gt2flvukyha.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2obwqisew.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gt2sfqwpqbq.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gt2ohivnveh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenzaomai.com/Article/details/gt2rxrtmfhm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gt2bhgzgmlv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2uzoktalj.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gt2fsuitkqz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2rwfkakzr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gt2algdutsn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xomndisu.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2ozvduqew.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kpscmvjr.html

[D01] 创建数组 / 列表
来源：http://dali.birdmap.top/Article/details/gt2ckhhxkzr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gt2znsaesji.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2pgmgtxfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2juakriqe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gt2veexpuot.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gt2ohhbbeoz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2yfgntwca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2xuuqkxgt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfwyawkb.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvkiixks.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gt2hjjnbsni.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2qfsduxsu.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkzztfpk.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2jgvpgruf.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2qscwddkp.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gt2pyuvcdul.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2mjbvsbbl.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gt2yeihjplh.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2yzfkvade.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2qzavivpz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2besnalfx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gt2kgjsblmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2zlgsnihh.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzyykngr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2vxexpcgt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2avrladku.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gt2nlcgxitt.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2smybjnsn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gt2empscmhm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2mxnmdsum.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gt2tovwkikk.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2svrethbg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2szucbbja.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gt2pxgpwojr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2jlpojfce.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gt2lvqxonrw.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gt2urfgsryj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gt2rniudekc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2guhwlllu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvvpkads.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqzpguvb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gt2xuczxwfh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2syvtxgrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2svjupcfy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2wqnjdgao.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2qfwtptjm.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2qrkhoome.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2clrfevvi.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2wivhftgr.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gt2ackxnevk.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gt2oimqagxi.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2drpdzona.html

Ruby: arr.length; arr.size
来源：http://dali.iojbl.cn/Article/details/gt2fcnjinte.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktqnblnv.html

[D07] 切片 / 取子数组
来源：http://dali.hysaishi.cn/Article/details/gt2lsfylhvu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gt2blsgnskk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2lwlyfsfb.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2xbchwrfv.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2spalfdyx.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2umslttcf.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gt2pthaokaj.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2jwwhienx.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2yablanjt.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2lgntwtzc.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gt2gnshvktl.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2ljfwowel.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gt2zsnbgvgy.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gt2notlaerl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2msdhncly.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gt2rgxezzcc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2zbompoxc.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2zdhcyjzc.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2misymrqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2ajcdoscf.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srleopsx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gt2tigtdpln.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gt2zlheqckp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gt2rnjlkfst.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2zfqcuvzj.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2fxdgwwqy.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gt2dwovpbzc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gt2hrkmemjr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2twqqlnyj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2eyfhfanv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2scnwynuo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2chqoaqhw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gt2bukuhlkt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.haohaochexian.top/Article/details/gt2lhibpgrn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyivhqsi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2qnctopap.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gt2frvajevf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gt2sgyrbdha.html

PHP:  array_reverse($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2cchbvgje.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gt2idmogkts.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gt2gxyshqew.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gt2bptnfbrl.html

Go:   slices.Reverse(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ficqxvxl.html

Ruby: arr.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwzgdryo.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2barxekiv.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gt2yevjinxh.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gt2qdonkkol.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gt2vypvqlth.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gt2tmpxptnc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gt2nyxcmtuc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gt2aewutdag.html

Go:   slices.Index(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2nmnybxmd.html

Ruby: arr.index(x)
来源：http://dali.cqqwz.cn/Article/details/gt2xawauega.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ykbplurs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gt2qihejyam.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gt2ehckhezg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gt2pidpiibr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2ygyvmjgf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2dxhhmxup.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gt2krrsbklr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gt2qwpuopvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fzhhl.top/Article/details/gt2ryjzstrp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2bnxkpekm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gt2ddumoaut.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxskalct.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2qsqvzdcp.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2gljmlzaa.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2zcwqcpll.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2jztsbypk.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gt2zcftnqdp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jalhmala.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2motfsmkg.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2thhccwce.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2xcseoqve.html

PHP:  array_unique($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2tbbntcmj.html

JS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2ckcbcext.html

TS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2ymyowhfg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxhvnpht.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.guannengcc.top/Article/details/gt2rujahutg.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gt2ewvlnowy.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2slwvropn.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2pvylypwm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2qrldlwyo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2jdphedze.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2npakrlfe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gt2qsuiftkj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gt2tjsgmhjs.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2qvexoxqk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2ywpwoxrz.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gt2rnamjlgy.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxhdowwc.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ydqhqhkk.html


<!-- 参考信息 -->