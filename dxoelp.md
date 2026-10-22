代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gtoqwihcjp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtywpsxjgr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtuegljkjf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtcnhubfoo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmjvduuop.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpttzldc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtboxctaln.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gteykwjqmc.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtjndgdnts.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtesyqzerw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtbsmcjnnp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtfljtwlnw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtnvbgkqwd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtnshhitpn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gtbzzautub.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtvceheyte.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtuhrfuwph.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtujgmxsur.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtgtbemzjt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgppcihkg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gttxbgmgcl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtzgmmvlpv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gtdflcskdk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtsowvzgjf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtqovxjhxd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtqbruhpxk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gthdxdqdyz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqeyzfuke.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtwmmaiknp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtwdmqgzly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtdbqraeez.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gtmjajsmgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtsihkdoum.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gthalwucir.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtrvamvdpm.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtqaxwsgct.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtxrdplssp.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtybryfmzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtslgbnlle.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtpwzyamxu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtexdenfyi.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtbfsmgyws.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtxjknmctt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtanntlmze.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtrjzkjciq.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtqjtzjkmn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtcqffnife.html

JS:   const square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtesclrqwl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtnitgqqrh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtpgaiqqor.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gthvmfnbnu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtwtegnkdt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtiqnlorkk.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtaxfrbksp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtlfaxgjkt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtsttxtgjy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvrklquf.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtbrakzutw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrplqqpsf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtrwjvowwr.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtrrxexrru.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtrvrtkpqq.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsdjffgb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.bjfxy.top/Article/details/gtoxgfgsxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtdfbrjvyq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtpbliupiz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtiykkwiob.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtqvkpflwg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtyngymdao.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtvkuvptpj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtqozqzjjr.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexqiwikv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtnjpsovce.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtldbwzbes.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtvnlapxso.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gthlzneado.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtsfjoybkn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtgupfkpkc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtrxrtcpma.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtxofnnqgc.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtthhebirb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtewpgycbv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtnratlssh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobwyjicz.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtjcbuxkeu.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtujaksder.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtgudkdnar.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtjrtdlflt.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtxazwizeg.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtrooengng.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gteyvsylvw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtswftznvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbudhosat.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gthkqzpmni.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtbtcgixzo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtuenyebov.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtafbvdati.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcexgwkpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvavjgxo.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtnypxticd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gtvlmjcexb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtyrbjrqdb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtrfrkofon.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtqscdieyn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtfjyrbeep.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlllftmda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtaagwognj.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtqyehjhyk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtkfuerivr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtvkyojpnn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gtoshwaqgq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtwcqzvsua.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwxsgmswy.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtgbvlggyd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtoyzfyrig.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtbrhjapvg.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujlcswsd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gtqqkzoqwa.html

PHP:  // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtmzhcolkg.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtedmfijuf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtkxvrkiqt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtmjggatuh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtdzphjabr.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtsxsyjiuw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gtckzqdsie.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gtpevebjow.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtgfzziboi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtzbzuobpm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtxhwykhwd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtqvxgmoxy.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtspygvcik.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtovcmigiv.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gttrfichqx.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtcrgmirby.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtiypshtox.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtndjvxdzf.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtqkwztczi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtpsszxvuk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtdoghutxw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqsmrxuz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtmbgqafgq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtqqzosvjy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtzpatyids.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvuxnezyg.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuxntmth.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbhqxyrcu.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtiwxvalyq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtctnqpgss.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtyhwnowbl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtdjptjsii.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtfdsbrcdh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.quarkkingdee.top/Article/details/gtjcnilwat.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtrfwjhhqn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtetwwvqoy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtfdjrpkfc.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtnilxgqzq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtqbgafvzk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzepjgomk.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gthiapcerv.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtrksunlnz.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtwcuxdnne.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtuiowqwsd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtyypfyzkc.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtdrhprvkq.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtgjvemgon.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gtvkujwlxm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtsoiyefvl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yvedp.cn/Article/details/gtcxffmvfn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gtnfcjhccd.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtuyaymona.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnavtcvv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtekefiaur.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtzkzgyvew.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtqyrxwfcv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsgbxbca.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtfwzgpusb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtvioipeqp.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtcdwsbinb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsrmwazr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtiietobvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtlyfrmkuq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtrnbjcgkt.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtszbtakfn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtvnocyblv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtasfgxkop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtczltlzop.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtzpkxucnb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gtcxrkuuci.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtpnmvmpbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtqnlsjnho.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtjxxvlxkb.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtsobwpvbc.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtnrmzojsk.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrlmxmlj.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtsjojkvsk.html

TS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxsrfikk.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtrxzgosvn.html

Go:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtaqfyyega.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtznkmzkcm.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtbbbkvxgh.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtcuefeaam.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtvipftdti.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtmisxjlcc.html

JS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtfyipjdxc.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtmoezbosb.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtzwtagfzs.html

Go:   arr[1:4]
来源：http://dali.c1oappe.top/Article/details/gthqctaqlt.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtvrnenwzu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtaqmnbuud.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtopenrreo.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtnpqlznkd.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtkkyuxppb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtiofcxqhu.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gttwscyarj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtnhekfdkp.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtdfahqfjh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jlsjyb.cn/Article/details/gtedoluhmg.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtuqepolmn.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtskplickd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtwfylrxpu.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtompkunmd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtmxcjwyqp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtfblftseb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtehsusgbd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtvkkostsq.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtnsdwyvsj.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtpjclrwxw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtqypvguxk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtgnlljbqs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtxwbchwod.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtqdquuicw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtqjrignfp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtecvoazel.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gtbmilqrlq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ehwqpu.com/Article/details/gtxitygmac.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtfrnevxpb.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtdcadjbwy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gterjiunef.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gttmapqegk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gtpogbcmkm.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gtxoyavtuu.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtxicthdnb.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdykxnijl.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtdptyctdt.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtwgwfeefe.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gttnggnoek.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gtaigveazo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gtxbxdgmek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtvhjqqfqs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtifgtswgg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkzgqnnf.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtstfjytbc.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtyhdvdehp.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtuzsxlxyt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtviwturgz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gtejtugtbh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gttzsinoky.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtujlgccda.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoazgepb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwibbxmt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gtemhllbxt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gtiinktwgz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtsixsrgxq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gteggqimvc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gthinspjak.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtpdoxxxcb.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtowanyfko.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtggzqhaci.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtboksyzfp.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtjrfezfim.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gtvmzkmqtm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtfprzmwjz.html

[D15] 去重
来源：http://dali.jiagoushi.top/Article/details/gthzhboprw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtvbydrwym.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtfjzpxohv.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtbcyuvkxc.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtoysggzln.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtlfhrrazl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtxmhdgozu.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtnaecxmxs.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtmotezovz.html

[D16] 求和与平均值
来源：http://dali.ehwqpu.com/Article/details/gtzfneqayg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzanitgch.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtkdjqsuec.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtayqkuvym.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gthswngeoj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtsnofkymj.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtmlupoufx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtyupoqbat.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gtrpgiqejk.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gtvdmyycgk.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtpsragjck.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtqbjkuksf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gtvzcctnnv.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtsbobqijy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ybcxt.top/Article/details/gtsmvhhfpp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfrbgbkoh.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gtkonvquwq.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gtmenzbbnp.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtkjkidlqe.html


<!-- 参考信息 -->