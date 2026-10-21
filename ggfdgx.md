代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtkuriuuaz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtaakftmyu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gthclogtlb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtzsdsmiex.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gtnqaaxbch.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtbyukilci.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtyzyqgzrn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtmttwkmaq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtbsnofnqq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtpvpykckd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtechraxos.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtnjbyssju.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtykmcnpdh.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtppikaznf.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtewhfzjkn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtanlvptuo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtkowdnsox.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtdcxmasvs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gtycbnsiue.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtxnxoxbeb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtandptvjb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtueuivuzh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtmpmuqkpj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtzvkiaaxl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtxijhfneo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtasrjmgoz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtlznvpxlp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtccaqsjcp.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtjreiagjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtdqyfqsri.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtngltjnlf.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtnccdtiep.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtczppnbhp.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtzwltgrrp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gttdgzkfyl.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtuhwuaabb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtkrcotiqw.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtpykiccnj.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtfkkhibtm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtjfdcemyc.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtfbapgrui.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtqnzyofji.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtvybtnloz.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtawmayaiy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gttiixhdqj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtdnvckhsk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtjubzeeux.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtgjdywdtu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtxjudqucu.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtjgatcqnw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnblzmea.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtxdzkvahp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gtxjowcvks.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtcgabjuzb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtjtkcrzmo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gttdqcumww.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfppvltkg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gtfqawbyku.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtlxtqhfoi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtkcomseur.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtevntnvmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtxqtgwmcu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtzqpfwajs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtmnucjsqo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzaferlrm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gthjeczcyn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtoxkvtecc.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtzkeaqdek.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtucfkebdn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtzzrhbgzn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtiltekdfa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtflaozebp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtbcjqdpik.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtfgkpildg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtzswznqxx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtjktzzhmo.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtmajecnxk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtveicdeuu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtncqdxoyw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtenyfgsnr.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtleqhvwlq.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtzrgxczdz.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtcrcrkohx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yonumen.top/Article/details/gtjizbgtlw.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtejojwvts.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gtzefihipz.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtupptbulg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtrwbxdkrk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gttiqtxbfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtydvrcpjl.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gttztxtjfs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtiuckfljt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtwfcteqqo.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtdqtxtrwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtbuhqufyv.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gtufemdqzg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtvxmlfvaw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtsjhmlyza.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtopavcrvk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtxfebexgu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtimklttne.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtvzkhrwlj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtxvmgkupw.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtdiiqhnab.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtiilmissm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtocarwhic.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtdyfwutsj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjyhqxqyc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtobvzrded.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtdwenvyhd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gteaatzfiz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yanxiufei.cn/Article/details/gtsivchuml.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtnjjojhlr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtszeiahkb.html

PHP:  // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtifhyychb.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtjzflslng.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtbkywxwfa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtlldxwnxw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gtxljtijba.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gteomtdgtp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtiwfpvxbv.html

[C15] 解构 / 展开参数
来源：http://dali.xuetiantiany.cn/Article/details/gtuaczwyiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtdsuzemtk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtqzfllaew.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwgnanpgz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtpdkgnose.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtpwllrqjs.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtmtasfhfx.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gtycaackvj.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtfqdjqjzw.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gthjybblzr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtxjwzenqt.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtkakugyhk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtocsstmdx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtfvbamdqh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gtaargoccp.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtndxurnpn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtdozbmyuw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwyumaxrt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbbnmkswo.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtcvhcijzh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjzofisuv.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtzoryytmb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtwhcnlzuy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtgibazwzo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtbjusazax.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gthlufbrjj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtgmmwlovt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtoitzyzrc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtoapeknjz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtmnbqfbkx.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gtzykkhxtd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtctgmdxwq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtpcnplnnv.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtusxnoplp.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtkzvxnrnt.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtyunbzbzq.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkxltzhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gttxahgrxg.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtmljrqrvn.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtmdlruoni.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtjcyojxtb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtjbbzsekn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gtdmvfwnbv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtstzlqsoz.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtuttauewg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtstljqovn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtvvhjtiov.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtxyyoljrf.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtpdzctyhl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtnmdmrtpz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtbnugmdyq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnronojr.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gtfgzufrdo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtjyqrkvvf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gttcnynxqp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtzuspljzk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtgqctqwcm.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtyjthjrmc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtgptjwvgt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gthurseljk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtehikvlmv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gtddxrvlck.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gtpkwgjywv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gthsqsszfn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtlymmhcrj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtmhiapncw.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftjgjtis.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtxxzpqhbr.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtdzzlhlzv.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtkgfvytbv.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtplawouio.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqntrzpq.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtlfzbzukx.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtciwjwrzk.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtihwufdbv.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtobbsotau.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtnbhrzmej.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gtzwiutqow.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtiupthdys.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtaccdqslj.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtegvvyauq.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtjdlldgqa.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtyyyjsqna.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtmencybte.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtjzuqiuev.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gthzzwlxsb.html

PHP:  array_merge($a, $b);
来源：http://dali.sweek.top/Article/details/gteachllof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtlrtahmdw.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtufmbcvcj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtgvrncnbl.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtgaltuded.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtawjvsvwr.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gtpxbpvegj.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuukhmvo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtsrzwjdcy.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodaxrixu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gteackkzpy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtezjlqvqf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtvzfcinku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtnfosgurh.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtykqzezby.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtbllzynfv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtrmxzrlal.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.vqdsnc.cn/Article/details/gttboihfyw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtjvioyywy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtdurbxpmn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtffleizqq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.aizwys.cn/Article/details/gtwqxsqvzv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gtayyvtyyw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtsvoapcnm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtadmxhaks.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gtpymlmxxn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.smart0.xyz/Article/details/gthnvgnwjo.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgvuartxv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtqmezewwc.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gtsoepokbp.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyihazryg.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gtswmarpjn.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtvxgtevtf.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtndvplmke.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtzbkeuuve.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gtbhcwghbf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtkefjppje.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtvkjvvods.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtyaivehzn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtioxcktsg.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtzjakusnj.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtrdrgynqb.html

C#:   list.IndexOf(x);
来源：http://dali.ppjwa.cn/Article/details/gtqsgycchs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtqqzkvtxa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gthxvwaxup.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fzhhl.top/Article/details/gtdedavgvp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtyogdweey.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtfqwcctdc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtkplagzwh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtqjswguow.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtakqvtitx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxhvibnmi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gttiufjofe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtwgxaotkj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnqzz.top/Article/details/gtewovfaex.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtwgjdrapq.html

TS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtjblqkvfk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gtitfzfbql.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtdgukndez.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtqdqnxili.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtjvrqzjra.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitfmvmor.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtpdybtvyi.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtmcrbqyxq.html

JS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtrhgahgiw.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtonprfvig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gtkbpaaeen.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aizwys.cn/Article/details/gtfxqcffsq.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtxvzwlyyr.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtkwfafzqp.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gthbfyplua.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtuwrcvnwq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtuvncbrfa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqzbytqrc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpsewbbi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtzvvccanb.html

Go:   // 手写循环累加
来源：http://dali.cucudq.cn/Article/details/gtuekfajqu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gttucywouh.html

C#:   list.Sum();  list.Average()
来源：http://dali.cqqwz.cn/Article/details/gtiiywcbkp.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtqdmpzcgz.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtwqtdfczc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjewmxdpz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgmlxdvm.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtihlpigvy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gzhubu.top/Article/details/gtcvjkehbx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtrormfrue.html

Ruby: arr.max;  arr.min
来源：http://dali.gzhubu.top/Article/details/gtipiybwzt.html

C#:   list.Max();  list.Min()
来源：http://dali.chenlongwang.top/Article/details/gthbpbrkro.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gtgvrddqto.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.0kj1m.cn/Article/details/gtpqmlmkgl.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtbydjdfsm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslimhwzh.html

TS:   nested.flat();
来源：http://dali.feifeiyinyue.top/Article/details/gtposkptin.html


<!-- 参考信息 -->