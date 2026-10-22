代发 wailian999

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtguazvmgy.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtdmulnkyb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthnlnkykn.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtulvbmiyn.html

Py:   def add(a, b): return a + b
来源：http://dali.cashguo.top/Article/details/gtdmqivufs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtteelqjmt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtjmsavntv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtdqgatfqa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtwhdufjzd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtsnwmtiwf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gtphlzxeic.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtxvzjobbd.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtqzzlsepv.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gtvuxkowrc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtfudhgfmv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrglretov.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtndpqnhaq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtphwzfcst.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtysnbgucd.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gtsivvmfoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtudcjkxvm.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtnybhluyt.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gtslzlxbkg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtaktdsiaa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtavjrndno.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtolppwrxp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gtqhzpsnzo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gttzebynkm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gtnrxtklbq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtwlikdrpn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gttazexbzt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gteyrhevmv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtylqwsrpe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqbenwgks.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtwqjgbihv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtsjntghkh.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtiuthkeul.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtpzfartbo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtdlmmwhkg.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtiafadhvl.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gthgkybdsu.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtmuvfskai.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtexuqqugw.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtesgrnkbu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtfyvsmqfs.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqyahpuc.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofkfxegh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtffrlcfre.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtypkaeayr.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtlhqdqrja.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtjiakdgld.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gttpmzelkg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtopcfudoq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtstaxbqkz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegysfyhc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gtshfhmgqj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtpivdgwhz.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtoodjvwun.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvrqqewg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtulmkxbpj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtbvmwtgoi.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtjktdrtui.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtrkquhdvp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtxzlxxpfb.html

Ruby: arr.map(&:upcase)
来源：http://dali.birdmap.top/Article/details/gtlxmzgopo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtfcqkghgp.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtbmgxhsxq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtpptgswdy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxrtelno.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlzopuccf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtouhrnohi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtcdfjbxtl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtembugmed.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtgvclclzh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtgeavhcyj.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtzohtxhys.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtvfodwhox.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gttrsbrlly.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdbknlwz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtboagzkiy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtthqdqlqf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtpbiuhdbi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhjzutaj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gttpsejavw.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtkzylbtlt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtueebudsc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtkhtrnpop.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtzdpvvvdu.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtdepwfeej.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxkhshtb.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtzwnsxxdi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtfqmqakte.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtsxfcrprd.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtrvizmxie.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtsnymwvtf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtfdcczsnz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtvautaksu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtwwwcxjel.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtdryjlnrc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkfmkobs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gtvhejnvjw.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gttufwiqun.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gtjowrddzr.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gtaspwxgct.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtonqugunb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtpyzmwoqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtlfjihbwj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gttmqmpiqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gtkyrkoosl.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtkoinubud.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtctzvbkru.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtrkhqojbq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtpwjuszzu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtwkbaqewx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gtsmzflfho.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtgiljpwjw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtymwwactb.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtekkxahbx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtgbobdezw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gtjscroixz.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtjtnzslyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtqnohfksq.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtclcvwvlh.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtqjaunryk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gttkcceybe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtdzyrfjtd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gthimqdbgs.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gthmmdkonr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtvxylpdgo.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtiaqpvfuc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtlrtdxvbe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtdzucdfef.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtkubrtsmm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gtzlspiwup.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gthcgpdojy.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtcsprksrf.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gtbefvqfis.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtcjvvfyhh.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtoiokacna.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtwzextvzm.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtymwvfgmi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtcuaiqyac.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gtlgymnhwt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtboycqfff.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtwickxkgv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtmwevrhdo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gtipjznvsr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdjhobmt.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtnfzyljar.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtvnxtbhvo.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtzxpvfjby.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtypyorlsh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtalixqwpn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtptgsbbem.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gticawetux.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtkqidcawf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gtjqyjpqlq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtinljjbsy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gtrgwlcrcx.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gtbkqmtsme.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtpzhokvqf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtkmlstbpb.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtuslaqqyj.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtkjzizfyd.html

Java: list.add(4);
来源：http://dali.xylfe.cn/Article/details/gtdkiudefe.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gtmrzywhol.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtkcitivlt.html

C#:   list.Add(4);
来源：http://dali.jyoumei.cn/Article/details/gtbdhuzaxv.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtygqldmcs.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtynngptdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtxapbiofd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtalcowaym.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtzjhtfhjg.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtbkkexxwn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtsrsausbe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtmoqcjlsc.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtvdzptgaf.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gticrpernz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtvuynnlrp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtrxrelgxq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuuvohxc.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtqecimfzi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtlnotxmxw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gteyongivp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guowangkeji.top/Article/details/gtenexdwjk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtplynfviv.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenyuddge.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtjyjtdwcw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gthibalhdx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtfvpkinls.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtiihmrwtr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgfzy.top/Article/details/gtylzuvnnd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtpaxctdqd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtntqvifhp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtktwozqur.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtfmqhkpor.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfsslvcuw.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtlunfiusk.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtnacvimon.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtvtpxphzl.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtacjjwvto.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtmtvpwvkj.html

Ruby: arr.length; arr.size
来源：http://dali.hywenlv.cn/Article/details/gtndkauvls.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gtsnnjwrsv.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtuojyvcjs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtledmexth.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtmfqejjgg.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtuthtcaku.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtazermwds.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtvdecwszr.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtghnqxkpk.html

Ruby: arr[1, 3]
来源：http://dali.yonumen.top/Article/details/gtazuahfew.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gtjdpduioy.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gteynsqpce.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtiotuuklz.html

PHP:  array_merge($a, $b);
来源：http://dali.cashguo.top/Article/details/gtuhqnirob.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtwtcktoom.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtlpohsscx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtlrxbyzsc.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtbleekmjt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtapnrpcul.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtqcyebxhe.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtwrrziltn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtiqvovykq.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehckwcig.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyvnxqrq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hfpthk.cn/Article/details/gtnzvfmnbe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvkiwxgn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnuerzazq.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtpldljsfj.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtzbomwwuj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtrjnwzcrk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gtxyaflnyb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtlbvrahhr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtesbiqtcm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsopxjme.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtrwljlxpg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtyjgmwndf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtbcltapsg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtamogzktt.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gtzxsqnokg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtjmihvlva.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtdxlcccmi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtwqlpwcno.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gthnzsrhwq.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtkjyptivu.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtkqrarmgl.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtbwdvhcvb.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtrfffavbr.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtvkoscsio.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnqzz.top/Article/details/gtjrswoesc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtnryryjdx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtufxeruyg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gttzhotyjp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jlsjyb.cn/Article/details/gtuaaxdoxv.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlrbifgyq.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gtmfdkqhsr.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gttdjwmlru.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtjuqkggun.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.mhx1999.top/Article/details/gtpjdsalik.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hnqzz.top/Article/details/gtzleltjkj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtzwlbfbof.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtyleenvxt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtsyhpcqlc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtmwmtenuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtiixmfrbg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tanke756.top/Article/details/gtrksvyruj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cucudq.cn/Article/details/gtlfvmrwbb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtkokxsayo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtocjmfylw.html

JS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttdpzziro.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtdyfqgyzh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtxdkltyzd.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtnhdmmnhw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxtvwkks.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtmhmlcrro.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtqkxvdtju.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtadfrpolt.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtsrmzegqt.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtvdvaibwm.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtksparoju.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guannengcc.top/Article/details/gtomhjahos.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtbzmxzwys.html

Ruby: arr.uniq
来源：http://dali.pycfn.com/Article/details/gtuxzrwisn.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtpqdzwsqr.html

[D16] 求和与平均值
来源：http://dali.aibaodan.cn/Article/details/gtiqsvdomz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ybcxt.top/Article/details/gtxruwzgyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtzirzvkxy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtyyvklbmr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtowjxnzfc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shzxlz.cn/Article/details/gtuvnxdbao.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtyqocrqsj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtwuawbbem.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtibcnrszh.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtsczhiqsq.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtahnmonqd.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtjhhvooze.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtmcauiolx.html

TS:   Math.max(...arr);
来源：http://dali.cashguo.top/Article/details/gtqzecuevg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gtbblvbkxq.html


<!-- 参考信息 -->