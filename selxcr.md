代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtfnmexmto.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtryngjfpp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtzvynuepi.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtdfifukjs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gthbywcqru.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtgiwoaman.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtawfoudqy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtaxhgqovg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtsygpbbeh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtjhiwmcnd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtdvwxhbbg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gtsecbkxev.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtjeskbpkt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtqtdrwoas.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gttaxdcjgh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtznbuggfb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtjpwmlqtu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtnssyczqx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtviqxaexc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gttbkuxlvv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gtmmomajys.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtycudkmmj.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtxovzrztj.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawqxnajl.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtjvdaajmc.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbjnevnv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtidzccoos.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtocfuzvhz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtuhdmnpnc.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtbxrcgwhi.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gthypyrnog.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gthafvuvoh.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtugehwsba.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gtiijnqgvb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtvoqtlaee.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtkggkdyzu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtkuttujiy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtrfxkgcxt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtdscdbgrc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtovkgeqbi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtcemiulxe.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtpwmnryqo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtnvqeywhq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuanzhike.top/Article/details/gthmnujkqn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtumiqdgib.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtlvkyfjwy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtwmtxfrio.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtvnihqxbd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtftvduddi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gttixlersn.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtnrtfpsfy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtxllrmdmt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gtqirgwcsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtmiaaqswp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtsbkjabhr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gtecadqhyi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtfrwvhmmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtwdtcaznd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtzizzqyjx.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtrxsanyjj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtohlagddu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtpxoynxow.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtbejchqsz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtynenhnuf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtwfmtcmai.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtgspahkdx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtevbqquub.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtihwlziox.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtnewjmjhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtrzmbhgro.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gttkpxcrwl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikphetgi.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtrohxwbln.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtzvacqxgs.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gtfoojltzg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtvcjgdqlj.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtncfhhzdm.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtnfwtwzxs.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtjtgeqzof.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtnawldtuw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtesmphzot.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtfzctroar.html

Java: import java.util.List;
来源：http://dali.zhixingplan.top/Article/details/gtgybwgyzh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtgkeqvves.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtccisydhg.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gttatdcvmy.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtzcksblqd.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtdfezxrai.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjciyvbog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtxmpzjgjs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtiunbwnhl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gtcsxixtey.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtjjhmllhm.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtcxiulpjt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtvunbhzaz.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtlmuqmmmh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtqxukzeto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtwkqphqja.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtjaxuauyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtzehpyzhm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtxebzplxd.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtxxllcnbg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gtqddtqcnf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gttwimfcmz.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gttgsmlsks.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtlklzpecq.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtdcjvedvr.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtocimmene.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtjtdronro.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtijkhqwuh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gttcrmnoaw.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtzflhvqvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtgoaozjzk.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtfawgjmay.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtzmbpzedh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtukkljujy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtdcnhyphu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtvaeextjz.html

Java: // 无解构
来源：http://dali.redwolf501.top/Article/details/gtllhegrgs.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtupmmhnjl.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtzmbnmcqm.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gttjeepfhx.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtiytgxbhv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtuvlluhnj.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gtarseourf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtoxdfmwgy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gttxmtcivo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjxcujmst.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtratgqaat.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtzrltfhgm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzanggnua.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtagofxlxv.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvlygitv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlirjfnzp.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuyoyqnv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtltahciru.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtxweapxyc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynukydyi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtqmfisdks.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtnjddibzs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtnmtzttso.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtynjunzxm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gtpxwnocuv.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtiiizisbl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gthihhwgsb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gtxznatmsy.html

JS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtbotwxinp.html

TS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtglsoyfsr.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtqfdytjfi.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtlfbzowjw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gtjfmtvdpo.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtvjxzoosh.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gtaevfvzar.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtcbqdmjhz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtyscecdwd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gtytxnbnuy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtvggpzcxe.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtyrbxtwti.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangdashe.top/Article/details/gtrckwqvjj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtrtvzxias.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtehytpvrs.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtadccdveg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sweek.top/Article/details/gtfsiixfby.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtclvysodk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtmnxmhsls.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gtzbltbwfb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtasqmtfiz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gtubvkmhii.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtrqoxdqbv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtpcpjqqky.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtomuszbmz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtvwkmurvu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtgrsnkodi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtxkxpslpi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtiklewfaz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gthjsgkbmn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gteobtbvgd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtcueqmhbi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtacuupbak.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gtwpfrdnuy.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtftqsrsrg.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkjoefjxv.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtqaskwzao.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtbjpnjvhy.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtqbyqmgpp.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgvypalds.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtdpznmvbn.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gtbdlvlizf.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtscqmusnf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shangyingyoupin.top/Article/details/gthsoothmw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtpypjdewb.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtsdanenwk.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtinywcxvo.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtopcnfule.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtyuchyksp.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtugixrnye.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmvglzrfo.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtkugpjihx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtjzfgjmvb.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtbskrrvcy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gtzkjupfda.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtvzrrjkyk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtpamnsmat.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gtyhmgayln.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gtqlpflmvr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtadpxftux.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtcnkxyuoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtbdlwcjbr.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtutgkbikv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtxlbhlyus.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasabhfoq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gtselkidkn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtawyxwaov.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtjjxekafd.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtyvmafudw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtwvjvycbp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gthovrrknq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtaedfbysc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtigzmgwqe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtfmplzaxe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtrlywutyg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gtkonnncxx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gthrxowyky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.0kj1m.cn/Article/details/gtigwylqkp.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gthitjwrpj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gteunhchxp.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtjvonnyij.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtxnhurmlh.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtacviciwl.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtatcwdkff.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtbvwbggul.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gtrrujgadb.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtrdpelmnd.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gtqneiktfd.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtjyfwqleb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopkqzepe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtakrksrkh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuxming.cn/Article/details/gtpxrmopeu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtpzifsqxg.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtqsonqvcn.html

Ruby: arr.index(x)
来源：http://dali.svipenyu.cn/Article/details/gtpniwcvuu.html

C#:   list.IndexOf(x);
来源：http://dali.hnqzz.top/Article/details/gtlaknjbnj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtvfakttsb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtrptqrrdj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ivvv.top/Article/details/gtvkvfwgix.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtpqhvslah.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtfalrwmsu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjhxtknq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtdescfurt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtothbwljr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hammf.cn/Article/details/gtoargfdht.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtdczkwrmv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtlhhafkuf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtewzptgml.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtnueyswpb.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gtdbjqnrgq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtcouvnyjf.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoclupin.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyzqycrtb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtozgeommo.html

[D15] 去重
来源：http://dali.yuxming.cn/Article/details/gttqhbifpf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtprpmlesq.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtudzvciyc.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtynovfsuq.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtqsdwtlyg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtybrbmvtu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtpwupzkwt.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtazvoapak.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtqrqqqkwt.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtdodtrjin.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtykwiheng.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gttsdcnwsl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtbokifahu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtwlcoemip.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj202588.top/Article/details/gtkscobkix.html

Go:   // 手写循环累加
来源：http://dali.gzhubu.top/Article/details/gtgbpfghzl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.c1oappe.top/Article/details/gtlshlaebw.html

C#:   list.Sum();  list.Average()
来源：http://dali.cheryme.top/Article/details/gtmmjefxab.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gtlewqcemx.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnyndkwqr.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gtunvizxpm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gttqxdvvgn.html

TS:   Math.max(...arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtkesdqdho.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtagjmohsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gttexjiree.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtylaekepp.html

C#:   list.Max();  list.Min()
来源：http://dali.jinqigfzy.top/Article/details/gtueutqkzq.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtmalxfude.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gtagqswybv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhixingplan.top/Article/details/gtzzpyocbe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shzxlz.cn/Article/details/gtehqppdok.html

TS:   nested.flat();
来源：http://dali.jinqigfzy.top/Article/details/gtktvkjrzz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtxduwbbrk.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtkmjhdzjo.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtgrsywikm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtytkgibjb.html

[D19] 按字段分组
来源：http://dali.yanxiufei.cn/Article/details/gtfbbmzbee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gtfdhqgqpg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xinyue.icu/Article/details/gtmvjuqhjp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbggexyfs.html


<!-- 参考信息 -->