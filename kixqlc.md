代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrbdpurhl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtvwaostjv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gtixibkxar.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtryyudald.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtcjvcjxnu.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtkecceeoy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzdxywtfl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtsuwlgylw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtvyqprmmb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtpyqrqcih.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtpdzkkflt.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtrljscafj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtltmrdokp.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtxnjcosmw.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtglpwnznt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtkkypgjvx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtkplsjxly.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtocpyzftu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gtstwafvxh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtjcdgckxz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtqfgotbgg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtfohwffth.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtccpebvnc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtcxlpttqa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtvqzqnonf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtrexghhqa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gteqhhgxlq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gtvdcoxfef.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtasfxhtgp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtdkkhajro.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtbsusbvcl.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtvmjunygl.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtrhhfwhia.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gtyiyaaqmj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtnbpboxqr.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtkxfcaqux.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtyrohnqza.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtnbtigyea.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtsbugopyd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtrzzgxcsc.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtxbqletzv.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gtcivvquij.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gteldryhmd.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtdwlkliqz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtmnhbhtqf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtqbfeaibi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gzhubu.top/Article/details/gtcmbhxlfa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtwqytwbrl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtzymnsqgk.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtjpqgtipt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yangfankeji.com/Article/details/gtdgduptfy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtbaqkkrkv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtydkxfdop.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtwpwkntep.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gtkedpmjcd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gthhtgpohw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtcnyhckjt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtktgexfor.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtvtvnnpyi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtebulrsuh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtjzqxxvvo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtfxnuuuac.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyqpedxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtkaqeuduz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtqputcbeo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtfgxguhje.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gttgtdezpi.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gterigxawy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtrounmsag.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtknetzqie.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtcusxhndn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtncpgtsfy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqhwamlil.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gtpjasqdgl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtfmyupthb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtwetiwfvc.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtilpguwnx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtaceeaxti.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gtcdunzyka.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtmrlvlwmi.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtzyuryhnu.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gtzjrwgoiy.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtxcvdycpm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtcbstseqh.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtgsospwhy.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlamijgsh.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtblsrxhtm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtqrrvuwmr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pengpengdd.cyou/Article/details/gtayrznxrj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtmiykimlv.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtvmykvrnu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gttnphwepj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gthvqxtzwd.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtazjxstzs.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gtcqewlubw.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gtqhsaksxy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtgmqlplgs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfvmuayc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtwcbygqbk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtzgoeuzbv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtvybbsdqy.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtqpruocln.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gthcqzqfxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtlcwimatb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtrpuudfqw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnikwzjig.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtvaauqfqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtixfjakaz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gttguqnasg.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtgyqtqpkz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtswprfhgs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtyusowbkv.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtefywgufh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtswiqzudx.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gttlvgefuh.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtjnpjjwha.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtveyvbubm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtrdtjevwp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gtowzvebcx.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtolrjaxxn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtjndrgpsk.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtjlneuwyl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiisxokeb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtfewjclsu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtwfgwepox.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gtjzuxunhu.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gtgnpmsher.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtgqycojtd.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtumcuxcay.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthwraqvy.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtslboqwja.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gthzudhxqv.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gtcqyfhfpw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtjfihacdc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtgbyntkao.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmharwgpk.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtluzmfiex.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtpzohzsne.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gtqoenhjwz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpxqaqyor.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gttrcskjsj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzsmavfhq.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtlmcjqxze.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtswpigjdw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtonrffufe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtfuulycfl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtniktcfkn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtredrbdjd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxstojrer.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gtyjnntkfx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxceeafqe.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtcrnjgqyh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtdswfhpml.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtnzpdbtfg.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtiirqmwpy.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtavbrhvql.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtoqxbbcku.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gtjcfjinsg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtrqzyoajj.html

C#:   list.Add(4);
来源：http://dali.xuanzx.com/Article/details/gtvpixbqcu.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtoaoqzayt.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtizysrnry.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtvqvqpgxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtnfcwqtgf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gttzajkwil.html

Java: list.add(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtrxarrnuq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtsqikvmcl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtjoihwkqo.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtkurahszc.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtjiuowowc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gotoacloud.top/Article/details/gtjynovyjn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtabssvrwv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zycfv.cn/Article/details/gtkccnhmsv.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtbcgpakml.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtefookgux.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gtwawpobcj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtccknpbeu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gttmzaslkd.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtuwxlzanm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtonmssllj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtmxojjdeo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtwhqtscxl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtiazzkbme.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtybfgyhze.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtwvruqqtx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gttpxolcak.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtckbiszwt.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtfcvcerrk.html

Py:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtyawunqbq.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gthvhwpbpt.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtjhoyalgo.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtdyvgcjob.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtrdsljfqe.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtdstmsdnj.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtqpoktlja.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gtwawelxbv.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtystxqtsf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gtblipcyzr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtiaafckrp.html

JS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtnsitlxkb.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtsbxrecoz.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtfnhtovsg.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtrfphhwix.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtbebuguxp.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuxming.cn/Article/details/gtjaoqasqw.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtjtaqpuln.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtebxxgsxp.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtejdocyhm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gteifjzqbd.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtziiisgrd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtbgtjbhwt.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtmenpdpck.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gthqmxgnkz.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtjucpxwlc.html

[D09] 排序（升序）
来源：http://dali.pengpengdd.cyou/Article/details/gtpvmgulxz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtwcpnsprl.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtgpmpdnnr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnxcrprm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gtoecnkrih.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtcddphfor.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtwehtqkny.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gtxzufbtgt.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtblczkfiv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtpgssqmum.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtslorubks.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtrpmlyvni.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtvsgzjctz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhwppmqo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gtnnigzogw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtuznnraxy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yonumen.top/Article/details/gthtvadqwj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtfdvdrgxi.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtnlkjolue.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shangyingyoupin.top/Article/details/gtilbwlghn.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtczdescel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtrpfdsaxw.html

TS:   [...arr].reverse();
来源：http://dali.fengsongda.top/Article/details/gtikysinrc.html

Java: Collections.reverse(list);
来源：http://dali.yj20258888.top/Article/details/gtafmigufu.html

Go:   slices.Reverse(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvgdaqsco.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtobbvulae.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtyeyuelnj.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtfgfajsqt.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtoinycjkq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtcrycjeok.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gtgficcoxi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtcgatksjo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gttiiralae.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtciyfevrw.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtnvnvflow.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjefzhkwk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pengpengdd.cyou/Article/details/gtsznwpiwq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sysykeji.top/Article/details/gtqkndecgq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gtvsoerzmc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gttzmkcbuj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtrzikipzg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.9152youxi.cn/Article/details/gtglwtdfcj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyglgrwu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258.top/Article/details/gttzzjsedy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtvbxibrqq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cashguo.top/Article/details/gtdbywcpub.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ivvv.top/Article/details/gtegmluevu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtixaxqfpy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtbyhyroqr.html

TS:   arr.map(x => x * 2)
来源：http://dali.tian-w.cn/Article/details/gtmisumpwu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtxbxhdgwr.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtshyankpt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtgwbrwbhc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258.top/Article/details/gtplpqanwd.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gthfthzujm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtwphoytyu.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtqsribjii.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtdgamvnfy.html

TS:   [...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gtqzvzyzxh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtltzsiagw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtbrhlpihv.html

Ruby: arr.uniq
来源：http://dali.jinqigfzy.top/Article/details/gtinxbylad.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gtijomirdf.html

[D16] 求和与平均值
来源：http://dali.jqgufenzy.top/Article/details/gtkbeadkna.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtltjsjuhu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtgdqjybky.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtrtcqrgpo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjehvess.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibjuuktx.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gtjiogqkht.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtzutwxlho.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gtkcymncmk.html

[D17] 最大值与最小值
来源：http://dali.jianghu66.top/Article/details/gtnjsabasc.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtuecrirbt.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtoaimxtvt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtencbqovg.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbhkqpnt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtvseyuffx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gteukhdnhk.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtisewpiju.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtlagdcyvm.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gttckailmd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgfumlrp.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnongztvi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtgzwzpnsz.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtmafcvlot.html


<!-- 参考信息 -->