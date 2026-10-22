代发 wailian999

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtguifkytc.html

C. 函数与作用域
来源：http://dali.jqgfzy.top/Article/details/gtkipeswwi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlavzvuph.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtaphgpvry.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtaicutfjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtzfekhwux.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gttnoogldo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtuvdijbdy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyxqxsxqy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtslqtqzeb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gtdhzoprww.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtzuzdaoqo.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtpdtykqyo.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgfzy.top/Article/details/gthsfptsgr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gttrrrzrtv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtwpmykkik.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfceammn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtakwvfdtu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtjnttogbz.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtomfkqhea.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gthdxoeteh.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtcfszemhi.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtztuaioer.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtfdzbpvus.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtklbjohne.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtmabmufmu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gttmugyadv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtdiroajtn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtayrxogjv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtjejucgqo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglujufrg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtixsumjwr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtaolipqvp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtrkwgycly.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gtsfupolcq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gtqpgphomz.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtyzrimqxh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajlnjhtm.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqxpubny.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtvvrzpfap.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtupdjfzee.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtkolbvikn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtutqtdvla.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtbobtauls.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtwexrnoxf.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gttcqtgtgv.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtdrljnnrf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloiuubjo.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtwpqlnbup.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gtjrpuopbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtmgyuotjz.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtnfhfslzx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gtabeodxve.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtdrkjqfol.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtnefamdzb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtlmsuvvld.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtiowtpmnq.html

[C07] 把函数作为参数传入
来源：http://dali.cheryme.top/Article/details/gtryguweyo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gthxaeyeac.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtoatstymi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtptgyaryo.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtvgpmhthr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gttmankujp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtlcnxvllb.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtaziudkmb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtctkbmeer.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtgtwiuvol.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtfgvueguz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtmbzdbawk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtkgfrsokd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtljcntseq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtmnomwoiy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtvleakcsy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtpawtoywl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtmxqtlsrx.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtudezjmaa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtllrqwtpn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtrhhzldmr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtnpplklzw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtjronghcc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtsbhdbkhm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gthoynaamy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtlrmcqkdm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtttkgcygn.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtxocsizir.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gttjktudqs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtqwbrjtdo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjpaomjd.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtyqmsiknu.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gthgngqsmp.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtzsilekct.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gthehxoqbw.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtikrillxh.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtpumzkkpj.html

Py:   from module import func
来源：http://dali.pycfn.com/Article/details/gtbesjjjww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gtrsixkjih.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtguopuqzu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gtbtyzaqgv.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gtaaygisrb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtnlikrrqp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtsbocruek.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gthzehpaka.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gtwuviqrce.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtfbpzuhua.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtdjgbxpny.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtcwsbrpoa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gttdgrbmla.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtinyzukpz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtjpkukdqx.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gteczhasnl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gtashecdqo.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtsfgfgasy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gthrwpswzh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtbipdyrnp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtakqosfuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtinidtvup.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtzshgvict.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtlnncbxlv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gtwicldhki.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtlmukajqd.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtizwqomjq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gterivbpsa.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gttqnfhklx.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtqxrmidsp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtmjotjwej.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gteakposzg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtdzyozcjr.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtnfzevnns.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gttplonuay.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtpozikggx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtevfncfvw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtfabhktni.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtwndgmjbk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjevjpkix.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtvonwgdil.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtyoefezeu.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtelupglji.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gttwrnczcu.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtjgiryyfy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtngyusvne.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtzbbxhihb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtjuezftka.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtummzfmxy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtioflaznu.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtptzxcyvn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gttwhedisy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtppcfcvgm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdfzsokkl.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtqslvmnru.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjjmpgjoe.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtfeqqqyrw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gtwmpeazqv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtxggmldkh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtskpqihfe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsilcovhq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtnvzmirjb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gtufjqqwtw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtrbetaklk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtwhueuooj.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtqloinscp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtqeshyyvg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtjhisjlag.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtqpdwojuc.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtifjvrfcv.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gtkcgklykr.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtteqlqeqi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtwckveuxe.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgydmykc.html

[D03] 在指定位置插入元素
来源：http://dali.wangshuangyany.cn/Article/details/gtcljbowah.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtzpwmzgzl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gtaelhdcnk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtigbwijyn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtltfixjfh.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtnacoechl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gthvlcoyvt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtgvccpeqs.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtkcmhmwgx.html

[D04] 删除元素
来源：http://dali.yonumen.top/Article/details/gtwfaveaim.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtcbdmihbk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtggbyxcti.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gtkbvdyiqz.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtqczjogvo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtoksvfgsu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gtouadeldy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtygqgpjkf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtatxjnvwl.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gtbhdllrvb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtlzesdujl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtidntzzas.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gttlzzlysx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtqkypnptm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cashguo.top/Article/details/gtrgjhmiyp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtdzxtplmf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtormybdrk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gthcghovck.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtpgjhgwbc.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtbqfwpnfv.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovuuzbzu.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtvvpuivbk.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtdgcylbhz.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gthyxzsmae.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtetgfklar.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtljlngkrg.html

C#:   list.Count;
来源：http://dali.jianghu66.top/Article/details/gtiluqfwgf.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtuicsqkrh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gthmkfbzch.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtditsvbvp.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtvnxytbfz.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtgvashapo.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtuteygfyf.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtghnymrhf.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtzuddjkdg.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtmfyxzcdk.html

[D08] 合并两个数组
来源：http://dali.feifeiyinyue.top/Article/details/gtzxhsncdc.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtskauaotb.html

PHP:  array_merge($a, $b);
来源：http://dali.iojbl.cn/Article/details/gtqmrpcjmr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtwruekjvq.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtzrvablig.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtztjfrgvc.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gtzinmslks.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfjwygxa.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtdfigoypd.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaenqkipy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtthhbvris.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgprgfhj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtjshzngrn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtyjspnjwc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtqaetynlj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gthwxzcftv.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtquypeyaq.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtcrtglrgg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtyoevqyyt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenzaomai.com/Article/details/gtaltitnkg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgeejtko.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtafrelnxl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gthsveeqey.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hfpthk.cn/Article/details/gtililtgqz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtzhuxkvjv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtajuopyqn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtdfbofjkh.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtgvnbvgjj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gttzvteiol.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gthypkepwx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtpiyonzfn.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtrvlqqbsc.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtcalnervj.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtlglgxbqg.html

Ruby: arr.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktayonno.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtjfzowfsy.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gtpvdhkest.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtoqptuxoo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtgsfxlwig.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtqkenvhql.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtzodoqfwc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtjmnacamz.html

Go:   slices.Index(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtshiinxfq.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtghokbwou.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtwtjahkdt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtmawinwjx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gtzzwoievu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aibaodan.cn/Article/details/gtgxxlaahl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtakakkdyw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gttmzesvvi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtwgvgvpja.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.vqdsnc.cn/Article/details/gtaaoxfrli.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gzhubu.top/Article/details/gtdirwunzv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtfuxkysqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtvrblctoo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtllefuwdr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gtehifadfs.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gtlrwnyvoc.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtphbydmxb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zdqjudy.top/Article/details/gtlqjgzwvo.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gtydvyjsma.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohuqjget.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtlmbkiwph.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtauiaumqf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtpzmtjcik.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtzrlwchnf.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtnfhgqiaq.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtdbeuujql.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtihytkfwe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gtlxxbiuwb.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkswnqzn.html

C#:   list.Distinct().ToList()
来源：http://dali.jqgfzy.top/Article/details/gtqlyfmzdt.html

[D16] 求和与平均值
来源：http://dali.316326.xyz/Article/details/gtnqvjhljd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtvjrpoggm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtnlfhdfvj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtnzxbnlfk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtdlfvpfua.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtcyjhpzfb.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtmcdtbcva.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtcdugykbo.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtblnqvbsv.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtfdlgjtzc.html

Py:   max(arr);  min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtjjeiclbe.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtbtmyenyi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.meibo888.top/Article/details/gtozfyronl.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtitctqmin.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcvbymcs.html


<!-- 参考信息 -->