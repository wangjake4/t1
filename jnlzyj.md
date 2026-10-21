代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtzuyafdat.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtggoiixms.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jianghu66.top/Article/details/gtzwyjgicf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtacgsotpa.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gtymbdomka.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtiexbtjrf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtichbnffc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gttmyxfdeo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtuzraqceg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtibhaafxm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtlwphtmbw.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtghnvqlha.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtclhhhlxo.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtrquggjqe.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtwesoovvp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtehxzvvcw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtwpzgxeds.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtkldfpcwy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gttvohstme.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtprihzbcg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtkojcibcj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaropfaxn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtqktclhbf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtfwgducyc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gttvkzllsu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtokjppcll.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gthplzrivt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluxekyee.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtwtsugzpy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtfnjecngy.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtepsbwmfv.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtkaypzffm.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtgcqkshqi.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtrgddojea.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtclvbdicv.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtqtejsizn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtsytowchd.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtfplxivpw.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gttuwuozfo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtzxehcnwc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtcyosdwby.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtpdkwwrqk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtssnmyvcy.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtssbaxifp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtbjoijvlo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjxwucrk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtjorxhygq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gtlhidybaa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtbbmatymr.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtmnqrqevy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gtmfrrpeiv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gteaoaxtgu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtckbsoqga.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtiklbvvmm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gteyxenokm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gtozmhngkv.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtehmbglyw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtxwerurac.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gtynkxhoiw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtlmitweoi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqeprrnbo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtujihtsvf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtwsjvlxcr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtlqllnwrv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtlyplosmw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtodktlwzn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtbktwihfo.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gtwmckqhun.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtmbuesdzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtsnrpnpsp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtzuuefcno.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gttpnrjcbl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtxiuxlbjy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtxajcxdwx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtetlqdzxe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gtvoxzqiil.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtgwcfnkxc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtykvxlixq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtdqosbdny.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuxming.cn/Article/details/gtkrcllfcf.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gtgcyofbtn.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtzmvconzg.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtmtygjpcd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtvrnpaama.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtowqbbuag.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtozkjoeis.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtpgnmohpq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtptqlusfj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtvpdntotr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gtsfqyegcv.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtybhctijw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtrhapyvlz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gtvwzaxhqz.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtyhrickcl.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtzmxromuo.html

Py:   (lambda: print("run"))()
来源：http://dali.hammf.cn/Article/details/gtkwkxghib.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gtgzbvimir.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtucarnbui.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtkmllpfzq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtxedbvofr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gtgbwsbwbw.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gtazqnukti.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtjrhjtnuo.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtdguqzuwn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtwyiizvck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtpsawwzwy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gttmfsojxv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtyntffddh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtugfdftfu.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtvwgdiuvn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtxzopgnaf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtaarqnwdv.html

[C14] 泛型函数
来源：http://dali.guowangkeji.top/Article/details/gtmpnvsgam.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtdxwrwqaz.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtxuciasud.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtkhnzxpgn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shuidangran.top/Article/details/gtslpqqgif.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtjaxkyfkq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtdflgetqs.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtbvdhyhee.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gtlqsiutvf.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtbdscwncd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtznammvsd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtpkxrstpi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtovtlcdmf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtonrwhqdk.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtvegjfdes.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtnfxozwfg.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtocbkrmgz.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtfgzpobth.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtftzmdymg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtvnbltvwe.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtsocmwotd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtezgukmfd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtdlvzhlfb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtfhofdrrr.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtxdjojktt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gtanqsdtfy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlucvvxeh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvlspywye.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtdllprxhe.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtutnhnsrn.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtjyhapuop.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtcbvcgjqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtplmjyzaz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqrovnaf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxuanxn.top/Article/details/gtykalqozi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtkeqhjito.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtprnjvfgb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gtkmjmkcqj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gtwjoosebc.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtdttaykkf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jiagoushi.top/Article/details/gtotlatggo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtnqhvdaup.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtvddtwzjy.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gthfzxcnby.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnaweaez.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtgjpwemww.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtbkswwifq.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtoyyibjpz.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gtnffiraui.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtgiofdtrm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhhtqgdm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtbunzzqwz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtlkfgxlyq.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtvvghxhps.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtequylyau.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gtlzutwypk.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtllkgrner.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtmqhlrlkd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gthmujhodp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtpykzayua.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtsyhtgksi.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gteigxycjv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtbqurzxax.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtwwbuqzvc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jiagoushi.top/Article/details/gtfksupipb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gtecsokejz.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtpvxjucyd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtlypzqdvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gttuoxitaa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtslvyvzhz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoycffok.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gtuwlkomxf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtaeiwcvrj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtcaymvdrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtesunnjxx.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtsumzbtlb.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtasfrgosr.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gtjsmpccvh.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtgygeibxr.html

TS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtrnjgromq.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtrcfjctpw.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfalbqezq.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtrkavvgmc.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtjscxsljc.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtbtwlxafi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gthwlbwewk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtencciebj.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtnbhvnhdd.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtbdpqxtck.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtjxgpflwd.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtazpqwguj.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtnrjvahjl.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtcfyqxivq.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtpvbgyhxs.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtxtbnaezp.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtjxgepxup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shzxlz.cn/Article/details/gtbbgrfnfl.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtqpcyckxz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtcguqrdja.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtizrtpauf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtoatnakug.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtjendlnhg.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuaobfql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtpjxoiqcf.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtqznezmtm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtejfwmmvj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyfycsls.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtwizhyazz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxgwrdoep.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtosbhjkfr.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtvecazhnn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtxqevlphf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtpqvgkjto.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtyfsrzraw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtuzlexwrs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gteashuewf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtdscilsib.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gtciniwveo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ybcxt.top/Article/details/gtaavlknoc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhixingplan.top/Article/details/gttejjgdrw.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtnelzxiaf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gttnifjktm.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtetuoffko.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtpqnbsobx.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtocjnsqaj.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtyuutjfbw.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrtiksyxe.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtyskwydnn.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gttbatngtt.html

[D12] 查找元素下标
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabalzgzl.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtiradcoem.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtjygjsrwy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gthrsxcocs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiezusxp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtcdfdbqxo.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtcpeyqygs.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtwtsqntsk.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gtxgjzvwzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtbubsymkb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jiagoushi.top/Article/details/gtueqjijlm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtvlqcgumh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtxpfueneu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtjgvogfxo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtfaoiyfsu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yanxiufei.cn/Article/details/gtyimirmkw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gturvtrrbm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtuuycybbk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gtwpxcfqqe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtpryzctsl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtnlnfjcrk.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtapqjtlju.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjtwtlry.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtnufmpkda.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtdlkvadfa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtzwylgxgi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtgwxjurfq.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gtunqntovi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtemujormu.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gtyrdnaorh.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtqtzzhltl.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gttgqodvgv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtrpegchmy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtufpfhodz.html

Ruby: arr.uniq
来源：http://dali.dashuyun.cn/Article/details/gtlrkyxhpt.html

C#:   list.Distinct().ToList()
来源：http://dali.zycfv.cn/Article/details/gtikwsrulm.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtrlfumbex.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtkswvqwaq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtucvkpslw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtwdkoqpjm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gturmtnfkt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtievdhnqh.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gtrnhohlli.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gthtpsdgul.html

C#:   list.Sum();  list.Average()
来源：http://dali.yuanzhike.top/Article/details/gtufwnubcl.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtafpzgvjr.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxptqqehd.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtkymlwaxn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gtttqxszuf.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfcatcbh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jianghu66.top/Article/details/gtpfllshhx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtddfsjrge.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gthrjqgfhk.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gtlwdnycjd.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtnzghcmvi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtmkulbuvh.html

PHP:  array_merge(...$nested);
来源：http://dali.zhoulong.xyz/Article/details/gtvpudltku.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gtpduddudk.html

TS:   nested.flat();
来源：http://dali.jianghu66.top/Article/details/gtvrpzykko.html


<!-- 参考信息 -->