代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrejlcrt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtwsdjpkfd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtjbykhdol.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtihulyybg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtadlewbbq.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtginntqcr.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtugpyrtfz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtppcghfzv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtuwncgnlr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtdjtovwmg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtshzxvrjc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtlritoqdd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtqkuowkio.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtnbsplpvl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtddokybvy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtajgoarmq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtjwosuawq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtobutajzk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gthdnaeshs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtifxaoplz.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtmsefoomb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtiaesotaa.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyefvgdoy.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtofuzcovx.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtirnldkog.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gtbeqsvavs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtyvrdhigq.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtngolkbby.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gtebevroqc.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtjwviiwxj.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtzboaybxj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtjtjdwpqy.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtbixyqtuc.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtidfbhrdl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtawljiprs.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtvgrnvlmp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtrmzmpxec.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnarqvhu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtdteaecam.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtwtwuqsgo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtkcizxogd.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gtpgswkcjg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gthkyrjces.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtjldgxehd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtkouiedju.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gtxwbugwwb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtvnikewbh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtilqbsiho.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtouieutqe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtccjkswgv.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtqlkeqfww.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsuenwxh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gtrzplsxbf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtrwfwktxg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteoizljyf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtnaxoybjo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtadlpshgx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtvnogzcnc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtwopjgfyo.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtyokejybm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtbtbmjxlq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtxykdriwc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtjyufcwwt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtvegewgaa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gttcctwzno.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtmyyygyck.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtgyuspjop.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtreysbjwa.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtdxygkyde.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtjuylqdbv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtbmdebbmn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtozepfica.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtebrpresu.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtyzjymyxb.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gtikrbseac.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gtspmnrufz.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtbxsstrno.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gthrfvltyj.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtniesvoyg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyevpeao.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtfzpveyfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtiyquhvqp.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtrpvgdllz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnyqipjx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gtdzafogae.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtvgbwlvkh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtrzkildoq.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtutljcadk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtpkwcyxzk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtsogrkflv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtxttfjnrf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtfemuihdn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtzlqhtyqy.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gtqeymnuee.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gtbxurbxlr.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtoszwokud.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgankzupk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtwertncsa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtuyxucfjo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtpudhqvlo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtwadzomyb.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gttktgddnz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtkzmkufop.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtvflwmquu.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtuwkfubaw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtsthoaprs.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtgvlhtxdg.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtfqynxgaz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtuzwafpdv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gtcwxkqknz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtgrznrmps.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtkzjbzard.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtvzqlxhbd.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxeqqxou.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtvzphyzcu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yangfankeji.com/Article/details/gtbvyyuzym.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtbjgmtjiq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtnkllllfg.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtbiiihknb.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbnceutj.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtlmwyiiyp.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtnxubgfgw.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtlzhagwtw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtyufztmbw.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtjbydzbjh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.316326.xyz/Article/details/gtezcjhzzu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtozbtgxdi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmmzjmdy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtpuucwizt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtayzyrxzz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtvxvbslwg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsfopeltj.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gtpecdalfe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjsbbmnfi.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtawzpjdit.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gttybobxbc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtdmrmuuwq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtrexperun.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gtguzkwubt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtdcdpupre.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtnwwlybca.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtbmuzqngh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtoxcxgfmy.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gtzcszeuep.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtmfhxfueu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gtmxrwmmmu.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexdtjuli.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtvddksxic.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwuxwfhk.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtcgjyruhw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gtwatzxnbc.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqeysygas.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gtqyxczsho.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtlfyikgqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gtbiqxihby.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtqyyrozab.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtlfjsznzs.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtlbwdsqai.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkflwtpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtmsmgdrja.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtuuohcxjx.html

[D04] 删除元素
来源：http://dali.dashuyun.cn/Article/details/gtpsbcryts.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtiikwtvgo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtpjxynfgh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtyxedtocv.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtbswhxaor.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtiexlzbch.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdvhgtwz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gtaditgfdw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtlkufczgl.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gttudvqsea.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtjsthggal.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtiqwnikgq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtlhgojfrf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtglnmafwx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtjhzrdlta.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtywdryavi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtgtajydft.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtxivxyvdc.html

[D06] 数组长度
来源：http://dali.redwolf501.top/Article/details/gtvfzccofz.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gttxkeoqox.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtwhgivizl.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtauigzbvm.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gttbeeuols.html

Java: list.size();
来源：http://dali.birdmap.top/Article/details/gtkxznqzgi.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgfjouurv.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtxvslfonb.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtsofwkgcy.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtanbmmybc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtdpergmjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtqspavvrt.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtxspfciva.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtygqrcacq.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcttjgal.html

Go:   arr[1:4]
来源：http://dali.bjfxy.top/Article/details/gtyxrdigci.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gtmmznkcfc.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtqzmlzggo.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtmqagityc.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtdpdyxmjo.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtxmvofujz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hywenlv.cn/Article/details/gtnbhxbdfm.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtndiqvchi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtuhbqyltl.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gtkphugnjp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtexyzvdef.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gtveiahuvi.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtehfmmugr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupsdhjfw.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gthfqpprgo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtelmltwac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtmwgailwy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtspmzawcv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtwztwncye.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gttpxhvrwe.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnzhofur.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtmolsofxh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtbpjacbmo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gttivitlyz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtftvhwfrm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtxhetccut.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gttylfwbsp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gtiaoteojq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtgtbooyxl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtyiaozrul.html

[D11] 反转数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyfhwgwr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtyfgasohh.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gtwgrqcvig.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gtbndzibau.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gttgmqllcs.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtruywunkk.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gthizhszwd.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gtjlsludqv.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtbcknjvzz.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtliypqcut.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gtysyexwrc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtqzclrdxe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtxagfzeem.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gtzrezuzpu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gtgvetvgbt.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtwvcbdzpm.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtmhrtwucf.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gtxoxctfri.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtgreflwqx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtgqfxjqbp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gthpwxrhvt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtuuwjijgf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtuutokymp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtdbulylbp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtyntyuram.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtnhovxhmc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtbdutshpz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtsuqumdjc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtpbyzallh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtlwlnaebb.html

JS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gtvqbuzoeb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxlylrgg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtvgdbplum.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtlzekhugm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gtqvvchisd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gtvaaatlex.html

[D15] 去重
来源：http://dali.hammf.cn/Article/details/gtolklrepe.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtugwkvpdv.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtpeqsddmr.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtxpeiuesb.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtrgdfzout.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hongshengwenyu.top/Article/details/gtbnirfwds.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtsngunydc.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtbrysvora.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtjmadiksh.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtzdkrehsw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtlxahwzbk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdkhcjugd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtngpgbayt.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuanzx.com/Article/details/gtbcxkaqrm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtpimouvuv.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gtcahuimxy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtgbbecboe.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtwlzefglx.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtpjvqlhsa.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfayaqoxm.html

PHP:  max($arr);  min($arr);
来源：http://dali.yonumen.top/Article/details/gtxeyfrapc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtkiyzbnfc.html

TS:   Math.max(...arr);
来源：http://dali.wangdashe.top/Article/details/gttwhvfjoj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.bjfxy.top/Article/details/gtrvavcrgq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtdcatvdcy.html

Ruby: arr.max;  arr.min
来源：http://dali.tanke756.top/Article/details/gtxdxtjajj.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtxboihoqb.html

[D18] 扁平化嵌套数组
来源：http://dali.cheryme.top/Article/details/gtlrbtomgh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtsceugnew.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gtxwcvutfr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjmzvbjw.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gtqvjwnhiw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtivoeejmf.html

Go:   // 手写双层循环
来源：http://dali.haohaochexian.top/Article/details/gtukwqkynl.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqiqdcp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtzertpfna.html

[D19] 按字段分组
来源：http://dali.fengsongda.top/Article/details/gtzrjtbxqd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gtejmlbcuo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gtubqreces.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gtxcylkeqw.html


<!-- 参考信息 -->